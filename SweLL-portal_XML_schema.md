SweLL Portal import/export XML schema
===

This document defines the XML format of data that can be exported from, and imported into, the SweLL portal.

In essence, each Django object model is represented by an element named like the model, and the fields of the model are represented by attributes named like the fields. Fields that can have many values are instead represented as sub-elements.

Essays are different. As Django object models, they are represented in three stages: Task object, Task and TaskState. These are consolidated to one object in the XML format. Additional attributes serve to inflate it into appropriate Django models.

Any SweLL XML document has `<swell>` as its root element. The root element may contain one `<meta>` element and/or one `<essays>` element.



Steps and requirements
---
1. Check if the source(school) exist in the Portal
    - If not add the source id, name and description 
    - Check if any permission required
2. Adding task
    - Add manually(prefered)
    - Add using XML file
        - Using XML file one can add task to the portal as shown in the sample examples in the end of this page
        - In case one need to upload data for many student with same task id, then only the first XML file consist of the task information, it can be commented in the rest of the XML files or ignore when creating
        - If the task information already exist then it will raise an error message
    - Required fields
        - task id(unique, number)
        - date
        - title
3. Student Information
    - Student id is unique for each student
    - Time in sweden is given in months
    - Gender is given as m,f,o and a
    - Age is given as interval of (2,-2) in this format (2000-2004)
    - Language input
        - ISO code (swe, SWE)
        - language name (swedish)
    - Other info can be added if it is available
4. Essay and Essay data
    - Essay consist of student id, task id and grade
    - Extra is used to add more information that doesn't cover the available fields
    - Data is either of type Svala json or raw text
    
 
Root element: `<swell>`
---

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| source | Yes | A single (or a short sequence of) upper-case letters, e.g. `A` |

Metadata elements
---

These are elements that may occur inside the `<meta>` element.

### `<student>`

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| id | Yes | A number that is unique among the student records |
| birthyear_interval | | `0-1939` or one of `1940-1944`, `1945-1949`, ..., `2000-2004` |
| time_in_sweden | | number of months |
| education_elementary_outside_sweden | | number of months |
| education_elementary_in_sweden | | number of months |
| education_introduction_in_sweden | | number of months |
| education_gymnasium_outside_sweden | | number of months |
| education_gymnasium_in_sweden | | number of months |
| education_professional_outside_sweden | | number of months |
| education_professional_in_sweden | | number of months |
| education_university_outside_sweden | | number of months |
| education_university_in_sweden | | number of months |
| education_other | | text |
| language_native_education | | name of a language in Swedish, e.g. `Norska` |
| language_native_education_duration | | number of months |
| swedish_where | | text, e.g. `Har lärt mig själv` |
| swedish_where_duration | | number of months |
| metastatus | | A comma-separated subset of the values `Ofullständig`, `Eventuellt felaktig` |
| metacomment | | text |

It may contain the following elements.

#### `<gender>`

Assigns a gender to the student. Zero or more.

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| type | Yes | One of: `f` (female), `m` (male), `o` (other), `a` (abstain) |

#### `<language>`

Declares skills in a language. Zero or more.

The element text content is the name of a language in Swedish, e.g. `Norska`.

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| situation | Yes | One of `Modersmål`, `Vilket språk använder du med din familj?`, `Vilket språk använder du med vänner?`, `Vilket språk använder du på jobbet/i skolan?`, `Vilket språk skriver du bäst?`, `Vilket språk talar du bäst?` or `Övrigt` |

#### `<degree>`

An educational degree. Zero or more.

The element text content is a short description of the degree, e.g. `Kandidatexamen ekonomi`

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| type | Yes | One of: `university`, `professional` |

#### `<extra>`

This can be used to supply arbitrary information not covered by other attributes or sub-elements. Zero or more.

The element text content is an arbitrary value.

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| name | Yes | text |

### `<task>`

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| id | Yes | A number that is unique among the task records |
| task_date | | A year and week specified as `%Y-W%V`, e.g. `2019-W04` |
| course_subject | | text, e.g. `SFI D`|
| course_level | | text, e.g. `Gymnasiet årskurs 3` |
| course_books | | text, comma-separated |
| grading_scale | | One of: `CEFR`, `Godkänd/underkänd`, `SAS Grund`, `SFI`, `SVA`, `SVA 1`, `SVA 2`, `SVA 3`, `TISUS`, `Uppgiften ska ej formellt betygsättas` |
| grading_scale_comment | | text |
| task_type | | One of: `Behörighetsprov`, `Formativ skrivuppgift`, `Inplaceringsprov`, `Slutprov` |
| task_subject | | text, e.g. `Argumenterande text om arbetsmoral` |
| task_format | | `digital` or `manual` |
| task_duration | | number of minutes |
| text_types | | Comma-separated subset of the values `Argumenterande`, `Återgivande`, `Berättande`, `Beskrivande`, `Förklarande`, `Instruerande`, `Utredande` |
| task_instructions | | text |
| task_aids | | text, comma-separated |
| task_additional_material | | text |
| task_comments | | text |
| metastatus | | A comma-separated subset of the values `Ofullständig`, `Eventuellt felaktig` |
| metacomment | | text |
    
It may also contain the following elements.

#### `<extra>`

This can be used to supply arbitrary information not covered by other attributes or sub-elements. Zero or more.

The element text content is an arbitrary value.

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| name | Yes | text |

Essay element `<essay>`
---

Any number of this element may be inside the `<essays>` element.

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| student | Yes | The `id` of a student (a number) |
| task | Yes | The `id` of a task (a number) |
| grade | | Depends on the grading scale of the task; see grade table below |
| comment | | text |
| metastatus | | A comma-separated subset of the values `Ofullständig`, `Eventuellt felaktig` |
| metacomment | | text |

| Grading scale | Grades |
| --- | --- |
| CEFR | `A1`..`C2` |
| SFI | `A`..`D` |
| SAS Grund | `A`..`F` |
| SVA {,1,2,3} | `A`..`F` |
| TISUS | `IG` or `G` |
| Godkänd/Underkänd | `U` or `G` |

It may also contain the following elements.

#### `<extra>`

This can be used to supply arbitrary information not covered by other attributes or sub-elements. Zero or more.

The element text content is an arbitrary value.

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| name | Yes | text |

#### `<content>`

| Attribute | Required | Data type/constraint |
| --- | --- | --- |
| type | | `raw` (default) or `svala` |
| normalized | | `no` (default) or `yes` |
| annotated | | `no` (default) or `yes` |

If the `type` attribute is
- `svala`, the element text content is a Svala graph encoded in JSON. The Svala graph data type is documented at [swell-editor/Representation.md](https://github.com/spraakbanken/swell-editor/blob/master/Representation.md).
- `raw` or not specified, the content is plain text. It corresponds to a Svala graph where the target and source texts are identical and there are no labels.

The `normalized` and `annotated` attributes determine how this corresponds to a task in the SweLL portal:

| type | normalized | annotated | corresponding SweLL task |
| --- | --- | --- | --- |
| raw | no | no | a Normalization task |
| raw | yes | no | a Correction annotation task |
| raw | | yes | N/A |
| svala | no | no | a Normalization task |
| svala | yes | no | a Correction annotation task |
| svala | yes | yes | a finished Correction annotation task |

Example
---

```xml
<?xml version="1.0" encoding="utf-8" ?>
<swell>
  <meta>
    <student id="A1">
      <language situation="Modersmål">Norska</language>
    </student>
    <task id="AT1" grading_scale="CEFR" />
  </meta>
  <essays>
    <essay student="A1" task="AT1" grade="B2">
      <content type="svala">
        {
          "source": [
            {"id": "s0", "text": "Hello "},
            {"id": "s1", "text": "world "}
          ],
          "target": [
            {"id": "t0", "text": "Hello "},
            {"id": "t1", "text": "world "}
          ],
          "edges": {
            "e-s0-t0": {
              "id": "e-s0-t0",
              "ids": ["s0", "t0"],
              "labels": [],
              "manual": false
            },
            "e-s1-t1": {
              "id": "e-s1-t1",
              "ids": ["s1", "t1"],
              "labels": [],
              "manual": false
            }
          }
        }
      </content>
    </essay>
  </essays>
</swell>
```


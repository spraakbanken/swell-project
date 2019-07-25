# Instruktioner för SweLL-kiosken

**TODO**: Dubbelkolla att detaljerna i instruktionerna stämmer.

## Uppstart

Starta datorn och logga in med det lösenord som är förknippat med den datorn.

Om inte kioskportalen öppnas automatiskt, gå in i programmenyn och starta *SweLL kioskportal*.
Det är en genväg till sidan *http://localhost:8000/* som öppnas i webbläsaren Chromium.

## Transkribera på kioskdatorn

Skriv i programmet *Textredigerare* och spara som *(uppsats-ID).txt* (t ex *A1AT1.txt*) i katalogen */usr/local/swell/essays*.

## Överföra uppsatser från USB-minne

Anslut ett USB-minne till datorn.
Öppna minnet i utforskaren och kopiera uppsatser till */usr/local/swell/essays*.
Filnamnen måste följa mönstret *(uppsats-ID).txt* (t ex *A1AT1.txt*).

## Importera uppsatser till kioskportalen

Öppna kioskportalen och klicka på *Importera*.

Under importen görs tokenisering av texten, vilken innebär att mellanrum infogas omkring skiljetecken, och att tecknet ␤ ersätter radbrytningar.

Originalfilerna för de importerade uppsatserna flyttas till */usr/local/swell/originals*.

## Anonymiseringarbete

1. Öppna sidan *Uppgifter* i kioskportalen.
2. Klicka på *Påbörja* vid en uppgift. Uppgiften öppnas i redigeringsverktyget Svala.
3. Följ [anonymiseringsriktlinjerna](Anonymization_guidelines.md).

## Ersätta importerad uppsats

1. Öppna sidan *Uppgifter* i kioskportalen.
2. Om du har påbörjat anonymisering av uppsatsen, klicka först på *Återställ*.
3. Klicka sedan på *Ta bort*.
4. Lägg den relevanta originalfilen i */usr/local/swell/essays* (flytta tillbaka från *originals*, skriv en ny fil eller överför från USB-minne).

## Ansluta till nätverk

Kioskdatorn kan anslutas till ett nätverk. Det går inte att komma åt
andra webbplatser från kioskdatorn, men nätverket kan användas för att
exportera anonymiserade uppgifter till portalen. Anslut till nätverk
via menyn som du når längst ner till höger på skärmen.

## Stänga ner kioskdatorn

Stäng av datorn genom att välja detta alternativ från menyn som du når
längst ner till höger på skärmen.

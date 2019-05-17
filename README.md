# Metodologia de l'scraping, anàlisi per gènere i visualització dels caps de llista a les eleccions locals a Catalunya

Al mitjà digital Catalunya Plural vam publicar una anàlisi de la representació de dones i homes que encapçalen llistes electorals municipals a Catalunya on constatàvem que [només tres de cada deu caps de llista a les eleccions municipals són dones](http://catalunyaplural.cat/ca/nomes-tres-de-cada-deu-caps-de-llista-a-les-eleccions-municipals-son-dones/).

## On són les dades de les candidatures electorals?

A l'Estat espanyol, les llistes que es presenten a les eleccions encara es publiquen en llistes en format PDF (ni tant sols en taules!), un format d'allò més inaccessible per l'anàlisi de dades. 

En el cas de Catalunya, les 3658 candidatures proclamades a les 992 circumscripcions electorals es publiquen en 31 PDFs diferents, un per cada Junta Electoral de Zona. Es poden consultar al web del [Ministerio del Interior](https://eleccioneslocaleseuropeas19.es/parlamento-europeo/candidaturas-proclamadas.html#/locales/proclamadas).

## Metodologia

L'extracció de textos dels PDFs així com l'anàlisi i el creuament de dades es va fer amb R. Podeu consultar el Notebook [aquí]().

## Visualització

Per la visualització, vam crear 3 "waffle charts" amb D3.js. Els codis són els següents:

[Caps de llista als municipis catalans](https://github.com/vicoliveres/capsdellistatotal/tree/master/docs)
[Caps de llista per partit](https://github.com/vicoliveres/capsdellistapartits/tree/master/docs)
[Caps de llista per mida del municipi](https://github.com/vicoliveres/capsdellistamides/tree/master/docs)

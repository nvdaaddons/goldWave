# GoldWave (tilføjelse ikke oversat) #

* Forfattere: Joseph Lee, NVDA bidragydere.
* Download [stabil version][1]
* Download [udviklingsversion][2]
* NVDA compatibility: 2019.3 to 2021.1

Dette app-modul forbedrer adgangen til og brugen af lydredigeringsprogrammet
Goldwave. Bemærk: GoldWave-programmet har ikke en dansk sprogpakke
tilgængelig. Derfor er tilføjelsen på nuværende tidspunkt ikke oversat.

## Genveje ##

* NVDA+Shift+C: Toggles speaking of commands during audio editing.
* Ctrl+Skift+P: Annoncerer aktuelle sporposition.
* NVDA+Skift+R: Annoncerer resterende tid for det spor du er i færd med at
  redigere.
* NVDA+Ctrl+1: Annoncerer kanalen du redigere.
* NVDA+Ctrl+2: Annoncerer den fulde længde af lydfilen.
* Control+NVDA+3: announces a summary on audio selection information.
* NVDA+Ctrl+4: Annoncere det aktuelle niveau for zoom.

For yderligere oplysninger om GoldWave og tastatur kommandoer, læs
brugervejledningen til GoldWave.

Bemærk: GoldWave 6 kræver 64-bit version af Windows 7 eller nyere. For at
bruge denne tilføjelse kræves NVDA 2019.3 eller nyere.

## Version 20.06

* Løst mange problemer med kodningstil og potentielle fejl med Flake8.

## Version 20.04

* Tilføjet inputhjælpsmeddelelser til kommandoen til resterende tid (NVDA
  +Shift+R).
* Kommandoen til at at aktivere og deaktivere udtale af meddelelser, når
  kommandoer udføres (NVDA+Shift+C) vises nu under kategorien "GoldWave" i
  NVDA's dialogboks med inputbevægelser.

## Version 20.01

* Kræver NVDA 2019.3 eller nyere.

## Version 19.09

* Windows 7 SP1, GoldWave 6.x og NVDA 2019.1 eller nyere er påkrævet.
* Tilføjet hjælpemeddelelse til lydvindue (tilgængelig, hvis tilføjelsen
  Brugsassistent til kontroller er installeret).

## Version 18.12

* NVDA vil ikke længere gør ingenting eller afspill fejletoner, når du
  udfører visse GoldWave-kommandoer med kommando-meddelelse slået til (dette
  kan medføre underlig adfærd i nogle tilfælde).
* Interne ændringer for at bedre kunne understøtte fremtidige versioner af
  NVDA.

## Version 18.07

* Løst et problem, hvor ledende nul ikke ville blive vist, når man forsøgte
  at opnå resterende tid for et spor.

## Version 17.05

* Tilføjet mulighed for at give fejlfindingsoplysninger, når NVDA kører med
  logføring aktiveret (NVDA 2017.1 eller senere).
* Opdaterede oversættelser.

## Version 16.12

* Versionsordning er nu year.month i stedet for major.minor.

## Ændringer i 4.0

* Depotet til tilføjelsen er flyttet til GitHub (nu placeret på
  https://github.com/josephsl/goldwave).
* Ydelsesforbedringer, når du slår op information som kanalnavn og anden
  statusinformation.

## Ændringer i 3.0

* Added a command to announce remaining time for the current track
  (NVDA+Shift+R).
* Små forbedringer når NVDA annoncerer statusoplysninger såsom
  kanaloplysninger.

## Ændringer i 2.0

* Understøttelse for GoldWave 6, herunder 64-bit version af GoldWave (se
  bemærkning ovenfor).
* Hjælp til tilføjelsen kan nu tilgås ved hjælp fra dialogen "Styring af
  tilføjelsesprogrammer" (NVDA 2014.3 og nyere).
* NVDA annoncerer nu den valgte kanal, hvis du trykker på
  kanalvalgskommandoer som Ctrl+Skift+L for den venstre kanal.
* Forskellige problemer med numeriske redigere felter som censor felt og
  time selector i mix dialog er blevet rettet, herunder valg af tekst,
  opdatering værdier, osv.
* Indstilling til annoncering af kommandoer vil blive husket, når der
  skiftes til andre programmer.

## Ændringer i 1.2

* Rettede et problem, hvor NVDA havde svært ved at annoncere nogle
  editfelter.
* Nye og opdaterede oversættelser.
* Bemærk venligst at på grund af de seneste ændringer i NVDA, vil kommandoer
  til valg af lyd og statuskommandoer ikke nødvendigvis fungerer korrekt på
  nogle systemer.

## Ændringer i 1.1

* Understøtter meddelelser på punkt, når informationer annonceres.
* Opsummeringer af den markerede del af lydfilen vil nu blive præsenteret i
  andre sprog udover engelsk.
* Flere kommandomeddelelser tilføjet, herunder bevægelser af
  startmarkeringer samt beskæring og sletning.
* Rettede et problem i flere redigeringsfelter, såsom forskellige
  effect-dialoger hvor intet eller forkert feltnavn blev annonceret.
* Nye og opdaterede oversættelser.

## Ændringer i 1.0

* Første version.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=gwv

[2]: https://addons.nvda-project.org/files/get.php?file=gwv-dev

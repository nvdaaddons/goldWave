# Goldwave #

* Autori: Joseph Lee, NVDA saradnici.
* Preuzmi[stabilnu verziju][1]
* Preuzmi[razvojnu verziju][2]
* NVDA compatibility: 2019.1 to 2019.2

This app module enhances access and usage of GoldWave audio editor.

## Prečice ##

* NvDA+šift+C: uključuje i isključuje izgovor komandi u toku uređivanja
  zvuka.
* Kontrol+Šift+P: Izgovara trenutnu poziciju zapisa.
* NVDA+Šift+R: Izgovara preostalo vreme za zapis koji se trenutno uređuje.
* Kontrol+NVDA+1: Izgovara kanal koji uređujete.
* Kontrol+NVDA+2: Izgovara ukupno trajanje zapisa koji se uređuje.
* Kontrol+NVDA+3: Izgovara kratak pregled informacija o izboru.
* Kontrol+NVDA+4: Izgovara nivo zumiranja.

For more information about GoldWave and keyboard commands, refer to GoldWave
Manual.

Note: GoldWave 6 requires 64-bit version of Windows 7 or later. To use this
add-on, NVDA 2019.1 or later is required.

## Version 19.11

* Windows 7 SP1, GoldWave 6.x, and NVDA 2019.1 or later is required.
* Added help message for sound window (accessible if Control Usage Assistant
  add-on is installed).

## Version 18.12

* NVDA will no longer appear to do nothing or play error tones when
  performing certain GoldWave commands with command announcement set to off
  (this may result in odd behaviors in some cases).
* Internal changes to support future NVDA releases.

## Version 18.07

* Fixed an issue where leading zeroes would not be displayed when trying to
  obtain remaining time for a trakc.

## Version 17.05

* Added ability to provide debug information when NVDA is running with debug
  logging enabled (NVDA 2017.1 or later).
* Updated translations.

## Verzija 16.12

* Imena verzija su sada u formatu godina.mesec umesto veći.manji broj

## Promene u 4.0

* Dodatke dodatka su premeštene na Github(sada se nalaze na lokaciji
  https://github.com/josephsl/goldwave).
* Poboljšanja u brzini kada se zahtevaju informacije kao što su trenutni
  kanal ili druge statusne informacije

## Promene u 3.0

* Dodata komanda za izgovor preostalog vremena zapisa(NvDA+Šift+R).
* Manja poboljšanja u izgovoru statusnih informacija kao što su ime kanala

## Promene u 2.0

* Podrška za GoldWave 6, uključujući 64-bitnu verziju programa
  GoldWave(pogledajte napomenu iznad).
* Možete pristupiti pomoći za dodatak iz upravljača dodataka(NVDA 2014.3 i
  noviji).
* NVDA sada izgovara odabran kanal ako koristite komande za izbor kanala kao
  što su Kontrol+Šift+L za levi kanal.
* Razni problemi sa numeričkim poljima za vreme kao što su izbor i
  ažuriranje su popravljeni
* Podešavanje za izgovor komandi će se pamtiti kada pređete na neki drugi
  program

## Promene u 1.2

* Popravljen problem gde je NVDA imao poteškoće u izgovoru određenih polja
  za unos teksta
* Novi i ažurirani prevodi
* Molimo imajte na umu da zbog skorijih promena programa NVDA, komande za
  izbor možda neće uvek ispravno raditi

## Promene u 1.1

* Podrška za prikazivanje poruka na brajevom redu
* Kratak opis izbora zvuka se prikazuje na jezicima koji nisu Engleski
* Više izgovora za komande je dodato uključujući brisanje i isecanje zvuka
* Popravljen problem u brojčanim poljima za vrednost efekta gde se ili ništa
  nije izgovaralo ili je to bila pogrešna vrednost
* Novi i ažurirani prevodi

## Promene u 1.0

* Prva verzija

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=gwv

[2]: https://addons.nvda-project.org/files/get.php?file=gwv-dev

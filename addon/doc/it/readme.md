# Goldwave #

* Autori: Joseph Lee, vari collaboratori di NVDA.
* Scarica la [versione stabile][1]
* Scarica la [versione in sviluppo][2]
* NVDA compatibility: 2019.1 to 2019.2

This app module enhances access and usage of GoldWave audio editor.

## Comandi rapidi: ##

* NVDA+Shift+C: Attiva o disattiva la lettura dei comandi quando si lavora
  con l'audio.
* Control+Shift+P: legge la posizione attuale nella traccia. 
* NVDA+Shift+R: legge il tempo restante nella traccia che si sta
  modificando.
* Control+NVDA+1: legge il canale che si sta modificando.
* Control+NVDA+2: legge il tempo totale della traccia audio.
* Control+NvDA+3: legge alcune informazioni sull'audio  selezionato.
* Control+NVDA+4: legge il livello zoom.

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

* Aggiunta la possibilità di fornire informazioni di debug quando NVDA è in
  esecuzione con la registrazione di debug abilitato (NVDA 2017.1 o versione
  successiva). 
* Traduzioni aggiornate. 

## Version 16.12

* Version scheme is now year.month instead of major.minor.

## Changes for 4.0

* Add-on repository has moved to GitHub (now located at
  https://github.com/josephsl/goldwave).
* Miglioramenti delle prestazioni per la ricerca di informazioni come il
  nome del canale e altre situazioni. 

## Changes for 3.0

* Aggiunto un comando per annunciare il tempo residuo del brano corrente
  (NvDA+Shift+R). 
* Lievi miglioramenti, lettura di informazioni sullo  stato come ad esempio
  informazioni sul canale. 

## Changes for 2.0

* Supporto per GoldWave 6, tra cui la versione a 64 bit di GoldWave (vedi la
  nota precedente). 
* La guida di aiuto si può ora aprire dalla finestra  Gestore Componenti
  Aggiuntivi (NVDA 2014.3 e superiori).
* NVDA ora legge il canale selezionato premendo il comando per il canale
  selezionato, come ad esempio ctrl+Maiusc+L per il canale sinistro. 
* Various issues with numeric edit fields such as censor field and time
  selector in mix dialog has been fixed, including selecting text, updating
  values and so on.
* Command announcement setting will be remembered when switching to other
  programs.

## Changes for 1.2

* Fixed an issue where NVDA had difficulty announcing some edit fields.
* New and updated translations.
* Please note that due to recent changes in NVDA, audio selection and other
  status commands may not work as expected in some systems.

## Changes for 1.1

* Support for message announcements in braille.
* Audio selection summary is presented in languages other than English.
* More command announcements added including cue position movement and
  delete/trim operations.
* Fixed an issue in numeric edit fields such as various effects dialogs
  where nothing or wrong field name was announced.
* New and updated translations.

## Changes for 1.0

* Initial version.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=gwv

[2]: https://addons.nvda-project.org/files/get.php?file=gwv-dev

# GoldWave #

* Készítők: Joseph Lee, NVDA közreműködők
* [Stabil verzió][1]
* [Fejlesztői verzió][2]
* NVDA compatibility: 2019.3 to 2021.1

This app module enhances access and usage of GoldWave audio editor.

## Gyorsbillentyűk ##

* NVDA+Shift+C: Toggles speaking of commands during audio editing.
* Control+Shift+P: Az aktuális sávpozíció bemondása.
* NVDA+Shift+R: Bemondja a szerkesztés alatt lévő sávból hátra lévő időt.
* Control+NVDA+1: A szerkesztés alatt álló csatorna bemondása.
* Control+NVDA+2: A hangfájl teljes hosszának bemondása.
* Control+NVDA+3: announces a summary on audio selection information.
* Control+NVDA+4: A nagyítási szint bemondása.

For more information about GoldWave and keyboard commands, refer to GoldWave
Manual.

Note: GoldWave 6 requires 64-bit version of Windows 7 or later. To use this
add-on, NVDA 2019.3 or later is required.

## Version 20.06

* Resolved many coding style issues and potential bugs with Flake8.

## Version 20.04

* Added input help messages for remainig time command (NVDA+Shift+R).
* Toggle command announcement command (NVDA+Shift+C) will now show up under
  "GoldWave" category in NVDA's input gestures dialog.

## Version 20.01

* Requires NVDA 2019.3 or later.

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

## Version 16.12

* Version scheme is now year.month instead of major.minor.

## A 4.0 verzió változásai

* A bővítmény tárolóját áthelyezték a GitHubra (jelenleg a
  https://github.com/josephsl/goldwave webhelyen található).
* Performance improvements when looking up information such as channel name
  and other status information.

## A 3.0 verzió változásai

* Added a command to announce remaining time for the current track
  (NVDA+Shift+R).
* Kissebb javítások történtek az állapot információk bemondásában, úgy mint
  csatorna információk.

## A 2.0 verzió változásai

* A GoldWave 6 támogatása, beleértve a 64-bites változatot is. (Lásd a fenti
  megjegyzést!).).
* A kiegészítő súgója már elérhető az NVDA Bővítménykezelő
  párbeszédpanelén. NVDA 2014.3 és újabb verziói esetén.
* Az NVDA már bejelenti a kiválasztott csatornát csatornák kijelölésére
  szolgáló parancsok használatakor (Control+Shift+L a bal oldali csatorna
  kijelöléséhez).
* Különböző számokkal dolgozó szerkesztőmezőkkel (szűrőmező, vagy
  időválasztó a mix párbeszédpanelen) kapcsolatos hiba javítva, beleértve
  szöveg kijelölése, érték módosítása, stb.
* A parancsok bejelentésére vonatkozó beállítás más programokra váltás
  esetén is megmarad.

## Az 1.2 verzió változásai

* Kijavításra került az a hiba, mely néhány szerkesztő mező bemondásakor
  lépett fel.
* Új, és frissített fordítások.
* Kérjük, vegye figyelembe, hogy a legújabb NVDA változások miatt, az audio
  kijelölés és egyéb státusz billentyűparancsok nem minden rendszeren
  működnek megfelelően.

## Az 1.1 verzió változásai

* Támogatott az üzenetek Braille megjelenítése
* A kijelölt hang tulajdonságai már nem csak angol nyelven elérhetők.
* Több parancs bemondása hozzáadva, köztük a hellyelző mozgása, törlés/trim
  műveletek.
* Hibajavítás a numerikus szerkesztőmezőkben, olykor hibás mező megnevezés
  került bemondásra.
* Új, és frissített fordítások.

## Az 1.0 verzió változásai

* Kezdeti verzió.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=gwv

[2]: https://addons.nvda-project.org/files/get.php?file=gwv-dev

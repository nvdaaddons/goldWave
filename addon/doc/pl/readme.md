# GoldWave #

* Autorzy: Joseph Lee, współpracownicy NVDA.
* Pobierz [wersja stabilna][1]
* Pobierz [wersja rozwojowa][2]
* NVDA compatibility: 2019.3 to 2021.1

Ten dodatek zwiększa dostępność i użyteczność edytora audio Goldwave.

## Skróty ##

* NVDA+Shift+C: przełącza wypowiadanie komend podczas edycji audio.
* Control+Shift+P: odczytuje aktualną pozycję ścieżki.
* NVDA+Shift+R: Oznajmia pozostały czas dla aktualnie edytowanego utworu.
* Control+NVDA+1: wypowiada aktualnie edytowany kanał.
* Control+NVDA+2: wypowiada całkowitą długość pliku dźwiękowego.
* Control+NVDA+3: Wymawia podsumowanie informacji o zaznaczonym fragmencie
  dźwięku.
* Control+NVDA+4: wypowiada aktualny poziom powiększenia.

Więcej informacji o Goldwave i jego klawiszach skrótów, znajduje się w
podręczniku Goldwave.

Uwaga: GoldWave 6 wymaga 64-bitowej wersji Windows 7 lub nowszej. Aby używać
tego dodatku, potrzebna jest wersja NVDA 2019.3 lub nowsza.

## Wersja 20.06

* Naprawiono mnóstwo błędów w kodzie oraz potencjalne błędy związane z
  Flake8.

## Wersja 20.04

* Dodany komunikat pomocy klawiatury dla polecenia (NVDA+Shift+R).
* Polecenie służące do włączania oraz wyłączania wymowy zdarzeń naciśniętych
  poleceń  (NVDA+Shift+C) od teraz będzie się pojawiało w
  kategorii"GoldWave" w dialogu Zdarzeń wejścia NVDA.

## Wersja 20.01

* Wymaga wersji NVDA 2019.3 lub nowszej.

## Wersja 19.11

* Windows 7 SP1, GoldWave 6.x, i NVDA 2019.1 i nowsze są wymagane.
* Dodano wiadomość kontekstową doa okna dźwięku (dostępne jeśli dodatek
  Control usage assistant jest zainstalowany).

## wersja 18.12

* NVDA już nie będzie odtwarzała dźwięk tonu lub robiła nic gdy niektóre
  polecenia goldwawe są wypełniane z wyłączonym wymawianiem poleceń (może to
  w niektórych sytuacjach dźiwnie działać).
* Zmiany wewnętrzne dla wsparcia nowych wersji NVDA.

## Wersja 18.07

* Naprawiony błąd w którym wiodące zera nie były wyświetlane gdy próbowało
  się dostarczyć pozostały czas dla utworu aktualnego.

## Wersja 17.05

* Dodano możliwość dostarczania informacji o debugowaniu po uruchomieniu
  NVDA w trybie debugowania (NVDA w wersji 2017.1 lub nowszej).
* Aktualizacja tłumaczeń

## Wersja 16.12

* Schemat wersjonowania został zmieniony i teraz brzmi on rok.miesiąc
  zamiast duży.mniejszy.

## Zmiany dla wersji 4.0

* Repozytorium tego dodatku zostało przeniesione na Github (teraz znajdujący
  się pod adresem https://github.com/josephsl/goldwave).
* Ulepszona wydajność przy pobieraniu informacji takich jak nazwa kanału i
  inne informacje statusu.

## Zmiany dla wersji 3.0

* Dodano komendę do ogłaszania aktualnego czasu aktualnego
  utworu(NVDA+Shift+R).
* Trochę większe ulepszenia czytania informacji stanu takich jak informacji
  o kanale.

## Zmiany dla wersji 2.0

* Wsparcie dla GoldWave 6, włącznie z 64-bitową wersją GoldWave (zobacz
  powyższą uwagę).
* Pomoc dodatku dostępna w managerze dodatków (NVDA 2014.3 i nowsze).
* NVDA oznajmia wybrany kanał po wciśnięciu polecenia zmiany zaznaczonego
  kanału np. Control+Shift+L dla zaznaczenia lewego kanału.
* Rozwiązano różne problemy z edycją pól numerycznych, np. pole cenzora i
  wybór czasu w oknie miksowania, w tym zaznaczanie tekstu, aktualizowanie
  wartości itd.
* Przełącznik oznajmiania komend jest zapamiętywany po przejściu do innych
  programów.

## Zmiany dla wersji 1.2

* Poprawiono problem dotyczący odczytywania przez NVDA niektórych pól
  edycji.
* Nowe i zaktualizowane tłumaczenia.
* Proszę zwrócić uwagę, że w związku z ostatnimi zmianami w NVDA,
  zaznaczanie audio i inne polecenia statusu mogą nie działać na niektórych
  systemach zgodnie z oczekiwaniami.

## Zmiany dla wersji 1.1

* Obsługa powiadomień w brajlu.
* Podsumowanie zaznaczenia audio jest prezentowane w językach innych niż
  angielski.
* Dodane oznajmianie większej liczby komend, uwzględniające takie polecenia
  jak przemieszczenia wskaźników, operacje usuwania i przycinania.
* Poprawiono problem w polach edycji liczb, np. w różnych okienkach efektów,
  gdzie oznajmiana była nieprawidłowa nazwa, albo brak nazwy kontrolki.
* Nowe i zaktualizowane tłumaczenia.

## Zmiany dla wersji 1.0

* Początkowa wersja.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=gwv

[2]: https://addons.nvda-project.org/files/get.php?file=gwv-dev

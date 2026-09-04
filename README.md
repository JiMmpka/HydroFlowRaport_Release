# HydroFlow Raport

Publiczne repozytorium dystrybucyjne dodatku HydroFlow Raport dla Microsoft Excel.
Służy do udostępniania instrukcji użytkownika i jednego aktualnego wydania dodatku XLAM.
Kod źródłowy oraz historia rozwoju nie są publikowane w tym repozytorium.

Dodatek jest przygotowany do automatycznego rozpoznawania obsługiwanych formatów
źródłowych. Aktualna wersja obsługuje pliki zgodne ze standardem CPK; użytkownik
nie wybiera profilu raportowania.

## Pobieranie

Najnowsza wersja będzie dostępna na stronie:

https://github.com/JiMmpka/HydroFlowRaport_Release/releases/latest

Bezpośredni link do dodatku:

https://github.com/JiMmpka/HydroFlowRaport_Release/releases/download/Release/HydroFlowRaport.xlam

## Instalacja

1. Pobierz `HydroFlowRaport.xlam` z sekcji Assets najnowszego wydania.
2. Przed uruchomieniem sprawdź podpis cyfrowy pliku, gdy podpisywanie zostanie wdrożone.
3. W Excelu otwórz `Plik > Opcje > Dodatki`.
4. W polu `Zarządzaj` wybierz `Dodatki programu Excel` i kliknij `Przejdź`.
5. Wskaż pobrany plik XLAM i włącz dodatek.

## Integralność pliku

W sekcji Assets publikowany jest również `manifest.json` zawierający numer wersji
i SHA-256 aktualnego pliku XLAM. Hash pozwala wykryć uszkodzony albo niezgodny
plik, ale nie zastępuje podpisu cyfrowego wydawcy.

## Zgłaszanie problemów

Nie publikuj w zgłoszeniach skoroszytów, danych projektowych, logów ani innych
informacji poufnych.

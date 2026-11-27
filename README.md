# Dokumentacja projektu – What If Calculator

## 1. Dokumentacja użytkownika

### 1.1. Opis aplikacji
What If Calculator to interaktywna aplikacja internetowa umożliwiająca analizowanie hipotetycznych scenariuszy i sprawdzanie, jak zmiana wybranych parametrów wpływa na końcowy rezultat. Aplikacja pozwala użytkownikowi wprowadzać własne dane, modyfikować wartości i obserwować różnice pomiędzy scenariuszem początkowym a alternatywnym.

### 1.2. Cel aplikacji
Celem aplikacji jest ułatwienie podejmowania decyzji poprzez symulowanie różnych sytuacji. Użytkownik może sprawdzić, co wydarzyłoby się po zmianie określonych czynników, bez konieczności wykonywania rzeczywistych działań.

### 1.3. Wymagania
Do korzystania z aplikacji potrzebne są:
- komputer, laptop, tablet lub telefon,
- dostęp do przeglądarki internetowej,
- dostęp do internetu w przypadku korzystania z wersji online.

### 1.4. Instrukcja obsługi

1. Otwórz aplikację What If Calculator w przeglądarce internetowej.
2. Przejdź do głównego ekranu aplikacji.
3. Wybierz kategorię lub scenariusz, który chcesz analizować.
4. Wprowadź wartości początkowe.
5. Zmień wybrane parametry, aby stworzyć alternatywny scenariusz.
6. Kliknij przycisk obliczania lub symulacji.
7. Odczytaj wyniki wyświetlone przez aplikację.
8. Porównaj scenariusz początkowy z nowym wariantem.
9. W razie potrzeby zmień dane i wykonaj kolejne obliczenie.

### 1.5. Funkcje aplikacji
- wprowadzanie własnych danych,
- zmiana parametrów scenariusza,
- wykonywanie obliczeń,
- porównywanie różnych wariantów,
- prezentowanie wyników,
- możliwość ponownego wykonania symulacji,
- intuicyjny interfejs użytkownika.

### 1.6. Obsługa błędów
W przypadku wprowadzenia nieprawidłowych danych aplikacja powinna poinformować użytkownika o błędzie. Należy sprawdzić, czy pola wymagające wartości liczbowych zawierają prawidłowe dane oraz czy wszystkie wymagane informacje zostały uzupełnione.

---

# 2. Dokumentacja techniczna

## 2.1. Opis techniczny projektu
What If Calculator jest aplikacją internetową zaprojektowaną do przeprowadzania symulacji hipotetycznych scenariuszy. Projekt został wykonany z wykorzystaniem technologii webowych i może być uruchamiany w przeglądarce internetowej.

## 2.2. Wykorzystane technologie

**HTML5** – odpowiada za strukturę aplikacji, rozmieszczenie elementów, formularzy, przycisków oraz sekcji wynikowych.

**CSS3** – odpowiada za wygląd aplikacji, kolory, układ strony, typografię, animacje oraz dostosowanie interfejsu do różnych rozmiarów ekranów.

**JavaScript** – odpowiada za logikę działania aplikacji, obsługę formularzy, pobieranie wprowadzonych danych, wykonywanie obliczeń oraz aktualizowanie wyników na stronie.

**Visual Studio Code** – środowisko programistyczne wykorzystane do tworzenia i edycji kodu źródłowego.

## 2.3. Architektura aplikacji
Aplikacja składa się z trzech głównych warstw:

1. **Warstwa prezentacji** – interfejs użytkownika, formularze, przyciski i wyniki.
2. **Warstwa logiki** – obsługa danych wejściowych, walidacja oraz wykonywanie obliczeń.
3. **Warstwa wyników** – prezentowanie obliczonych wartości i porównywanie scenariuszy.

## 2.4. Struktura plików projektu

Przykładowa struktura projektu:

- `index.html` – główny plik aplikacji i struktura strony.
- `style.css` – arkusz stylów odpowiadający za wygląd interfejsu.
- `script.js` – logika aplikacji, funkcje obliczeniowe i obsługa zdarzeń.
- `assets/` – folder przeznaczony na dodatkowe grafiki, ikony i inne zasoby.

## 2.5. Zasada działania
Po uruchomieniu aplikacji użytkownik wprowadza dane dotyczące wybranego scenariusza. JavaScript pobiera wartości z formularzy, sprawdza ich poprawność, a następnie wykonuje odpowiednie działania matematyczne lub logiczne.

Wyniki są przekazywane do interfejsu i wyświetlane użytkownikowi. W przypadku zmiany danych możliwe jest ponowne przeprowadzenie symulacji.

Schemat działania:

**Dane wejściowe → Walidacja → Obliczenia → Analiza wyników → Wyświetlenie rezultatu**

## 2.6. Walidacja danych
Aplikacja powinna kontrolować poprawność danych wprowadzanych przez użytkownika. Walidacja obejmuje:
- sprawdzanie wymaganych pól,
- kontrolę poprawności wartości liczbowych,
- wykrywanie pustych pól,
- ograniczanie nieprawidłowych wartości,
- informowanie użytkownika o błędach.

## 2.7. Bezpieczeństwo
Aplikacja nie powinna wykonywać niebezpiecznych operacji na danych użytkownika. Dane wprowadzane do formularzy powinny być odpowiednio sprawdzane. Projekt nie wymaga podawania danych osobowych ani logowania użytkownika, jeśli nie zostały dodane takie funkcje.

## 2.8. Uruchomienie aplikacji
Aby uruchomić projekt lokalnie:

1. Otworzyć folder projektu w Visual Studio Code.
2. Sprawdzić, czy wszystkie pliki projektu znajdują się w odpowiednich folderach.
3. Otworzyć plik `index.html` w przeglądarce albo uruchomić projekt za pomocą rozszerzenia Live Server.
4. Sprawdzić działanie interfejsu i funkcji obliczeniowych.
5. Wprowadzić przykładowe dane i przetestować działanie kalkulatora.

## 2.9. Testowanie
Testowanie aplikacji obejmuje:
- sprawdzenie poprawności działania przycisków,
- testowanie formularzy,
- sprawdzanie poprawności wykonywanych obliczeń,
- testowanie nieprawidłowych danych,
- sprawdzenie wyglądu na różnych rozdzielczościach,
- sprawdzenie działania aplikacji w różnych przeglądarkach.

## 2.10. Możliwości rozwoju
Projekt może zostać rozbudowany o:
- zapisywanie historii symulacji,
- dodawanie nowych kategorii scenariuszy,
- wykresy prezentujące zmiany,
- możliwość eksportowania wyników,
- zapis danych w bazie danych,
- system kont użytkowników,
- wersję mobilną,
- bardziej zaawansowane modele obliczeniowe.

## 2.11. Podsumowanie
What If Calculator jest aplikacją umożliwiającą analizowanie alternatywnych scenariuszy za pomocą wprowadzania danych i wykonywania symulacji. Projekt wykorzystuje technologie HTML, CSS i JavaScript, dzięki czemu jest prosty w uruchomieniu, rozwijaniu i dalszej rozbudowie. Aplikacja może znaleźć zastosowanie w edukacji, analizie danych oraz podejmowaniu decyzji.

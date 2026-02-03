# Plan Testów – ElderMT2

## 1. Wstęp
Celem niniejszego planu testów jest wykonanie testów eksploracyjnych witryny internetowej serwisu ElderMT2 w celu wykrycia błędów funkcjonalnych, logicznych oraz bezpieczeństwa wpływających na doświadczenie użytkownika i integralność danych.

## 2. Zakres testów
Zakres testów obejmuje:
* Testy eksploracyjne podstawowych funkcjonalności (rejestracja, logowanie).
* Weryfikację poprawności walidacji formularzy (pola E-mail, PIN, Hasło).
* Sprawdzenie działania nawigacji i spójności interfejsu użytkownika.
* Analizę błędów po stronie klienta za pomocą narzędzi deweloperskich.

Zakres nie obejmuje:
* Testów wydajnościowych.
* Testów automatycznych.
* Testów kompatybilności z urządzeniami mobilnymi.

## 3. Kryteria wejścia
* Aplikacja ElderMT2 dostępna w wersji produkcyjnej/testowej.
* Skonfigurowane środowisko testowe i dostęp do narzędzia Jira.

## 4. Kryteria wyjścia
* Wykonanie zaplanowanych sesji testów eksploracyjnych.
* Zidentyfikowanie, opisanie i zaraportowanie wykrytych defektów w systemie Jira.

## 5. Środowisko testowe
* **System operacyjny:** Windows 11
* **Przeglądarka:** Opera GX
* **Urządzenie:** PC

## 6. Kategorie testów
* Błąd krytyczny (np. Security/Information Disclosure).
* Błąd funkcjonalny.
* Błąd UI/UX.
* Błąd techniczny (Konsola JS).

## 7. Narzędzia
* **Jira** – raportowanie i zarządzanie defektami.
* **Chrome/Opera DevTools** – analiza błędów technicznych i sieciowych.
* **ShareX / Przeglądarka** – tworzenie dokumentacji wizualnej.

## 8. Harmonogram testów
| Etap | Czas trwania | Status |
|---|---|---|
| Testy eksploracyjne | 2h | Zrealizowane |
| Zgłoszenie defektów | 1h | Zrealizowane |

**Autor:** Kamil Szyszkowski  
**Data:** Luty 2026

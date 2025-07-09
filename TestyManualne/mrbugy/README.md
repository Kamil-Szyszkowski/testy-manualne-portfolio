
# Testowanie Aplikacji "MrBuggy"

Ten projekt dokumentuje proces testowania aplikacji desktopowej MrBuggy7 w celu identyfikacji defektów bezpieczeństwa, funkcjonalnych oraz w walidacji formularzy.

---

### Narzędzia i podejście testowe

W ramach tego projektu korzystałem z następujących narzędzi i metodyk:

* **Jira:** Do śledzenia, kategoryzowania i dokumentowania wszystkich znalezionych defektów.
* **GitHub:** Jako centralne repozytorium dla całej dokumentacji testowej i do kontroli wersji.
* **ShareX / Narzędzie Wycinanie:** Do tworzenia precyzyjnych zrzutów ekranu i nagrań wideo dokumentujących błędy.
* **Testy Eksploracyjne:** Jako główna technika testowania, pozwalająca na swobodne odkrywanie aplikacji i znajdowanie nieoczywistych błędów.
* **Analiza Funkcjonalna:** Do zrozumienia, jak aplikacja powinna działać i weryfikacji jej zgodności z oczekiwaniami.

---

### Dokumentacja Projektu

* **Zobacz szczegółowy Plan Testów:** [Plan-Testow-MrBuggy.md](./Plan-Testow-MrBuggy.md)

---

## Zaraportowane Błędy (Wybrane Przykłady)

Poniżej znajdują się screenshoty wybranych defektów, które zostały zaraportowane w systemie Jira. Zostały one wybrane, aby zademonstrować różnorodność znalezionych problemów.

### 1. Błąd Krytyczny (Bezpieczeństwo): Możliwość otwarcia dowolnej strony internetowej w aplikacji

**Opis błędu:** Ten defekt o wysokim priorytecie pozwala użytkownikowi na otwarcie dowolnej witryny internetowej (np. Google) w tle aplikacji za pomocą skrótów klawiszowych `CTRL+O` lub `CTRL+L`. Jest to luka w bezpieczeństwie, ponieważ program powinien blokować takie działania.

![Zgłoszenie błędu krytycznego - otwieranie stron](./bug-reports/bug-security-ctrl-o.png)

### 2. Błąd Funkcjonalny: Wyszukiwarka nie odświeża wyników po wyczyszczeniu

**Opis błędu:** To zgłoszenie o średnim priorytecie opisuje sytuację, w której wyszukiwarka w zakładce "Providers" nie odświeża listy wyników po usunięciu frazy za pomocą ikonki "x". Użytkownik musi ręcznie odświeżyć widok, co psuje doświadczenie i jest nielogiczne.

![Zgłoszenie błędu wyszukiwarki](./bug-reports/bug-search-clear.png)

### 3. Błąd Walidacji Formularza: Brak komunikatu walidacyjnego

**Opis błędu:** Ten błąd o niskim priorytecie pokazuje brak komunikatu walidacyjnego ("This field is required.") dla pola "Confirm password" podczas tworzenia nowego administratora. Mimo że inne pola mają walidację, to jedno zostało pominięte, co wprowadza niespójność.

![Zgłoszenie błędu walidacji formularza](./bug-reports/bug-validation-password.png)

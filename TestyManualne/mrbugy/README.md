
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

* **Zobacz szczegółowy Plan Testów:** [Plan-Testow-MrBuggy.md](https://github.com/Kamil-Szyszkowski/testy-manualne-portfolio/blob/main/TestyManualne/mrbugy/Plan-Testów.md)

---

## Zaraportowane Błędy (Wybrane Przykłady)

Poniżej znajdują się screenshoty wybranych defektów, które zostały zaraportowane w systemie Jira. Zostały one wybrane, aby zademonstrować różnorodność znalezionych problemów.

### 1. Błąd Krytyczny (Bezpieczeństwo): Możliwość otwarcia dowolnej strony internetowej w aplikacji

**Opis błędu:** Ten defekt o wysokim priorytecie pozwala użytkownikowi na otwarcie dowolnej witryny internetowej (np. Google) w tle aplikacji za pomocą skrótów klawiszowych `CTRL+O` lub `CTRL+L`. Jest to luka w bezpieczeństwie, ponieważ program powinien blokować takie działania.

![bugy1](https://github.com/user-attachments/assets/624a1830-931f-4aec-9ebd-3cecb768e36b)


### 2. Błąd Funkcjonalny: Wyszukiwarka nie odświeża wyników po wyczyszczeniu

**Opis błędu:** To zgłoszenie o średnim priorytecie opisuje sytuację, w której wyszukiwarka w zakładce "Providers" nie odświeża listy wyników po usunięciu frazy za pomocą ikonki "x". Użytkownik musi ręcznie odświeżyć widok, co psuje doświadczenie i jest nielogiczne.

![bugy2](https://github.com/user-attachments/assets/dd0608eb-0dcf-4d81-8a02-d8dd4cf5cf1f)


### 3. Błąd Walidacji Formularza: Brak komunikatu walidacyjnego

**Opis błędu:** Ten błąd o niskim priorytecie pokazuje brak komunikatu walidacyjnego ("This field is required.") dla pola "Confirm password" podczas tworzenia nowego administratora. Mimo że inne pola mają walidację, to jedno zostało pominięte, co wprowadza niespójność.

![Zgłoszenie błędu walidacji formularza](./bug-reports/bug-validation-password.png)

---

## Plany Rozwoju

W przyszłości planuję rozbudować to portfolio o:
* Testy automatyczne (Cypress)
* Testy API (Postman)
* Testy SQL (analiza danych)

Dziękuję za odwiedziny! Wszelkie uwagi mile widziane.

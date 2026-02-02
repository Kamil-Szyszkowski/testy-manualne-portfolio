# Plan Testów – Serwis dachluxaugustow.pl

W ramach tego projektu przygotowałem plan testów dla rzeczywistej strony usługowej **Dach-Lux**. Skupiłem się na weryfikacji ścieżek krytycznych, które mają bezpośredni wpływ na kontakt klienta z firmą.

**Podejście:** Testy manualne funkcjonalne, analiza UX/UI.  
**Narzędzia:** Git, GitHub, Opera, iPhone 16 Pro.  

---

## 📌 1. Cel i zakres testów
Celem jest wykrycie błędów blokujących komunikację oraz weryfikacja poprawności nawigacji w serwisie.

**Zakres obejmuje:**
* **Sekcja Kontakt:** Testowanie odnośników e-mail oraz tel.
* **Nawigacja:** Testowanie przycisków w sekcji Galeria oraz linków do Social Media.
* **Warstwa Wizualna:** Weryfikacja czytelności treści w sekcji "O nas".

---

## 🛠 2. Środowisko testowe
* **Desktop:** Windows 11 Pro, Przeglądarka Opera.
* **Mobile:** iPhone 16 Pro.

---

## 📝 3. Scenariusze Testowe (Zestawienie)

| ID | Tytuł Testu | Opis | Rezultat |
| :--- | :--- | :--- | :--- |
| **ST-01** | Weryfikacja linku e-mail | Kliknięcie w adres e-mail w zakładce Kontakt. | ❌ **FAIL** (404) |
| **ST-02** | Weryfikacja linku tel | Kliknięcie w numer telefonu w zakładce Kontakt. | ❌ **FAIL** (404) |
| **ST-03** | Test przycisku Aktualności | Kliknięcie w odnośnik "Aktualności" w Galerii. | ❌ **FAIL** (monica.im) |
| **ST-04** | Test linków Social Media | Sprawdzenie ikon Facebooka w treści i stopce. | ❌ **FAIL** (Błędny cel) |
| **ST-05** | Test czytelności (UX) | Weryfikacja sekcji „Dlaczego warto wybrać naszą firmę?”. | ❌ **FAIL** (Słaba czytelność) |

---

## 🏁 4. Kryteria zakończenia
Testy uznaje się za zakończone, gdy wszystkie błędy zostaną udokumentowane za pomocą zrzutów ekranu i opisane w raporcie końcowym (README.md).

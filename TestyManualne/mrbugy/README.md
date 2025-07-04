
## 📌 Przykładowe zgłoszenia błędów

### 🔴 Błąd 1 – Brak walidacji pola "Confirm password"

- **Priorytet**: Niski  
- **Opis**: Podczas dodawania nowego administratora brak komunikatu walidacyjnego przy pustym polu "Confirm password".  
- **Kroki do reprodukcji**:
  1. Zaloguj się jako administrator
  2. Przejdź do zakładki “Users”
  3. Kliknij “New Admin”
  4. Zostaw wszystkie pola puste i kliknij “Save”
- **Rzeczywisty rezultat**: Brakuje komunikatu walidacyjnego dla pola "Confirm password"  
- **Oczekiwany rezultat**: Powinien pojawić się komunikat „This field is required.”  
- **Dowód (film)**: [Zobacz nagranie](https://drive.google.com/file/d/1gD-ZyHXWGRpnlZB1e_9Xz0DpbcmzYyuo/view?usp=sharing)

---

### 🟠 Błąd 2 – Wyszukiwarka ignoruje wielkość liter

- **Priorytet**: Średni  
- **Opis**: Wyszukiwarka w zakładce „Providers” nie rozróżnia wielkich i małych liter.  
- **Kroki do reprodukcji**:
  1. Stwórz dwóch Providerów: „TEST” i „test”
  2. Wyszukaj frazę „test”
- **Rzeczywisty rezultat**: Oba wyniki są traktowane jako różne – brak walidacji  
- **Oczekiwany rezultat**: System powinien wykrywać duplikaty niezależnie od wielkości liter  
- **Dowód (film)**: [Zobacz nagranie](https://drive.google.com/file/d/1srdinhVljyG4Uj0F-2fn9C1N5X_JcHI5/view?usp=sharing)

---

## 🧾 Opis projektu

Dokument przygotowany w formacie przypominającym zgłoszenia do systemu JIRA, zawiera dokładne opisy defektów wraz z:
- Tytułem błędu
- Priorytetem
- Kroki do reprodukcji
- Rzeczywistym i oczekiwanym rezultatem
- Środowiskiem testowym
- Załącznikami (screeny, filmy – linki do Google Drive)

---

## 🧪 Zakres testów
- Walidacja pól formularzy
- Responsywność elementów interfejsu
- Obsługa klawiatury i skrótów
- Wyszukiwarka, filtrowanie, lista wyników
- Obsługa znaków specjalnych i polskich

---

## 🖥️ Środowisko testowe
- System operacyjny: Windows 11
- Przeglądarka: Opera (wersja aktualna)
- Aplikacja: MrBuggy7 (wersja testowa)

---


---

## 📍 Status projektu
Projekt demonstracyjny – część portfolio testera manualnego.  
Zadanie zrealizowane samodzielnie w ramach ćwiczeń testerskich.

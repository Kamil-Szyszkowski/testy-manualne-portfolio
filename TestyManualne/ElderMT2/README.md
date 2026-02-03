# Projekt: Testy eksploracyjne serwisu ElderMT2

## 🎯 Cel projektu
Przeprowadzenie testów manualnych witryny gry ElderMT2 ze szczególnym uwzględnieniem modułów rejestracji, logowania oraz nawigacji.

## 🛠️ Narzędzia i Środowisko
- **System raportowania:** Jira (Tablica Kanban)
- **Diagnostyka:** Chrome DevTools (Konsola)
- **Środowisko:** Windows 11, Opera GX

## 📸 Dowody Pracy: Zgłoszenia Błędów w Jirze

### 1. Tablica Kanban Projektu
Poniżej znajduje się widok tablicy z aktualnym statusem wszystkich zgłoszonych defektów.
<img width="943" height="699" alt="q" src="https://github.com/user-attachments/assets/3f881d31-a58d-4216-b65d-6ecb2403bbe1" />


---

### 2. [Security] Wyciek danych (User Enumeration) - KAN-7
**Problem:** Formularz rejestracji informuje w czasie rzeczywistym, czy podany adres e-mail jest już zarejestrowany w systemie, co umożliwia weryfikację bazy użytkowników.
<img width="788" height="686" alt="image" src="https://github.com/user-attachments/assets/755b5943-788f-41f1-9542-2e920eb5efbb" />


---

### 3. [Technical] Błąd składni JS w konsoli - KAN-5
**Problem:** Podczas ładowania strony w konsoli deweloperskiej pojawia się błąd składniowy `Uncaught SyntaxError: Unexpected token 'export'`.
<img width="1054" height="717" alt="image" src="https://github.com/user-attachments/assets/c3c552d6-4ae7-45b3-ba57-87abb8aec6b6" />


---

### 4. [UI/UX] Błędna walidacja pola PIN - KAN-6
**Problem:** Pole PIN świeci na zielono (sugerując poprawność), mimo wpisania błędnych danych podczas logowania.
<img width="795" height="692" alt="image" src="https://github.com/user-attachments/assets/6c4e6c8c-46d8-4475-9f2f-7a255da8421d" />


---

### 5. [UX] Brak nawigacji wstecznej - KAN-4
**Problem:** Brak możliwości powrotu do poprzedniej strony przyciskiem "wstecz" z poziomu panelu logowania i odzyskiwania danych.
<img width="783" height="665" alt="image" src="https://github.com/user-attachments/assets/a2f79bfb-7f5a-4b0d-9ea1-838258583499" />

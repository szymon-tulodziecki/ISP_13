## Projekt Laboratoryjny – GitHub Pages

**Opis projektu**  
To prosta strona internetowa służąca jako wizytówka projektu laboratoryjnego. Strona główna zawiera odnośniki do kluczowych podstron laboratorium nr 12, w tym do głównej strony projektu oraz podstron użytkownika. Projekt jest przeznaczony do publikacji przez GitHub Pages.

---

**Struktura projektu**

- `index.html` – Strona główna projektu.
- `styles.css` – Plik ze stylami dla strony głównej.
- `lab_12/` – Katalog z plikami laboratorium nr 12:
  - `index.html` – Główna strona laboratorium.
  - `user.html` – Podstrona użytkownika.
  - Dodatkowe podkatalogi z plikami JS, CSS, obrazami i pluginami.

---

**Jak uruchomić projekt lokalnie**

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/szymon-tulodziecki/ISP_13.git
   cd ISP_13
   ```
2. Otwórz plik `index.html` w przeglądarce.

---

**Publikacja na GitHub Pages**

1. W repozytorium na GitHub przejdź do ustawień (Settings).
2. W sekcji "Pages" wybierz gałąź (np. `main` lub `gh-pages`) oraz katalog źródłowy (np. `/root`).
3. Po chwili strona będzie dostępna pod adresem [`https://szymon-tulodziecki.github.io/ISP_13/`](https://szymon-tulodziecki.github.io/ISP_13/).

---

**Nawigacja**

- [Strona główna laboratorium](lab_12/index.html)
- [Podstrona użytkownika](lab_12/user.html)

---

**Autor**  
Szymon Tułodziecki

---

**Licencja**  
Projekt udostępniany na licencji MIT.

---

Jeśli chcesz rozbudować projekt, możesz dodać kolejne podstrony, własne style lub skrypty JS.  
Wszelkie uwagi i propozycje zmian są mile widziane w Issues lub Pull Requestach.
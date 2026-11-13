# Simple Webpage

A clean and modern HTML/CSS webpage with a responsive design.

## Features

- Responsive navigation header
- Three main sections (Home, About, Contact)
- Fixed footer
- Modern styling with hover effects
- Clean typography and layout

## Files

- `index.html` - Main HTML structure
- `styles.css` - Stylesheet with all the styling

## How to Use

1. Open `index.html` in your web browser
2. Navigate between sections using the header links

## Technologies

- HTML5
- CSS3

---
# Secțiune Galerie Foto (HTML5 & CSS Grid)

O componentă web modernă și responsive pentru afișarea unei galerii foto, construită folosind **HTML5 semantic** și **CSS Grid**.

## Structura Proiectului

Proiectul este organizat în două fișiere principale:

* `index.html` – Conține structura HTML a paginii, inclusiv secțiunea `#galerie` integrată în elementul `<main>`.
* `style.css` – Conține regulile de stilizare, layout-ul de tip grid și regulile responsive (media queries).

## Funcționalități Cheie

* **Layout pe 3 coloane:** Utilizează `display: grid` și `grid-template-columns: repeat(3, 1fr)` pentru a alinia imaginile uniform pe ecranele desktop și tabletă.
* **Spațiere consistentă:** Aplică `gap: 1rem` între elementele grilei pentru un aspect aerisit.
* **Design Responsive:** Include un breakpoint la `600px` (`@media (max-width: 599px)`) care transformă automat grila într-o singură coloană pe dispozitivele mobile.
* **Stilizare Imagini:** Imaginile au colțuri rotunjite (`border-radius: 8px`) și folosesc `object-fit: cover` pentru a preveni deformarea.

## Instalare și Utilizare

1. **Descarcă fișierele** `index.html` și `style.css` în același folder.
2. **Asigură-te că fișierul CSS este conectat** în secțiunea `<head>` a fișierului `index.html`:
   ```html
   <link rel="stylesheet" href="style.css">
   ```
3. **Personalizează imaginile:** Înlocuiește link-urile placeholder (`https://placehold.co`) din `index.html` cu căile către imaginile tale locale și actualizează atributele `alt`.
4. **Deschide `index.html`** în orice browser web modern pentru a vizualiza rezultatul.

## Personalizare Rapidă

* **Modificarea numărului de coloane:** Ajustează valoarea `3` din `grid-template-columns: repeat(3, 1fr);` în `style.css`.
* **Schimbarea spațiului dintre imagini:** Modifică valoarea proprietății `gap` (ex: `gap: 1.5rem;`).
* **Ajustarea punctului de rupere (mobile):** Schimbă valoarea `599px` din regula `@media` în funcție de nevoile proiectului tău.

© 2025 My Simple Webpage

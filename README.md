# 📚 BookWorm

---

## 📖 Opis projekta

**BookWorm** je aplikacija za iskanje, odkrivanje in upravljanje knjig.  
Uporabnikom omogoča brskanje po knjigah, filtriranje glede na različne kriterije (žanr, avtor) ter dodajanje knjig v lastno knjižnico.

Uporabnik lahko knjige v svoji knjižnici označi kot:
- želim prebrati
- trenutno berem
- prebrano

> Navdih: aplikacija *Goodreads*

---

## 🛠️ Uporabljene tehnologije

- **Programski jeziki:** C#, javascript, html, css
- **Ogrodje:** ASPNET, Vue, Bootstrap
- **Gradnja:** npm, vite, docker
- **Podatkovna baza:** PostgreSQL, 
- **Razvojno okolje:** VS Code, VS Community, pgAdmin 4 
- **Različice kode:** GitHub  
- **Oblačna platforma:** Azure  
- **Orkestracija:** Kubernetes  

---

## 🧩 Arhitektura mikrostoritev

Projekt temelji na **mikrostoritveni arhitekturi**, sestavljeni iz naslednjih storitev:

### 👤 User Service
- Prijava in registracija uporabnika
- JWT tokens
- Avtentikacija in avtorizacija

### 📚 Book Service
- Pridobivanje seznama knjig
- Brskanje in iskanje po knjigah
- Filtriranje (žanr, avtor)
- Dodajanje in odstranjevanje knjig (samo za admina)

### 🗂️ Library Service
- Uporabnikova osebna knjižnica
- Dodajanje in odstranjevanje knjig
- Označevanje statusa knjige (prebrano, berem, želim prebrati)
---

## ✅ Primeri uporabe

- Uporabnik se prijavi v aplikacijo
- Brska po seznamu knjig
- Filtrira knjige po:
  - žanru
  - avtorju
- Doda knjige v svojo knjižnico
- Označi knjige glede na bralni status
---

## 🚀 Nadaljnji razvoj

- Ocene in komentarji knjig
- Priporočilni algoritem
- Povezava z zunanjimi API-ji (npr. Google Books)
---

Slika arhitekture priložena.

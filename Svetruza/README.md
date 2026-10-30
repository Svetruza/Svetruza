# Svet Ruža — sajt

Satenske ruže · ručni rad · Beograd · dostava širom Srbije
Instagram: [@_svet_ruza_](https://instagram.com/_svet_ruza_) · +381 65 5266 134

## Fajlovi (svi su u jednom nivou, bez foldera)
| Fajl | Čemu služi |
|---|---|
| `index.html` | ceo sajt; sve fotografije su ugrađene u njega |
| `favicon.png` | ikonica u pregledaču |
| `apple-touch-icon.png`, `icon-512.png` | ikonica kad se sajt doda na početni ekran telefona |
| `site.webmanifest` | podešavanja za „Dodaj na početni ekran“ |
| `share.jpg` | slika koja se pojavi kad se link pošalje na Viber, WhatsApp ili Facebook |
| `404.html` | vraća posetioca na početnu ako otvori pogrešnu adresu |
| `robots.txt` | dozvoljava Google-u da pronađe sajt |
| `.nojekyll` | da GitHub Pages prikaže sajt bez obrade |

Sajt radi i ako se uploaduje samo `index.html`. Ostali fajlovi su dodatak.

## Postavljanje na GitHub Pages
1. Na github.com napravi novi repozitorijum, npr. `svet-ruza`, i postavi ga kao **Public**.
2. Klikni **Add file → Upload files**, pa **choose your files** i označi SVE fajlove iz ovog foldera.
   Na Mac-u pritisni Cmd + Shift + . u prozoru za izbor da vidiš i skriveni `.nojekyll`. Ako ga ne vidiš, nije problem.
3. Klikni **Commit changes**.
4. **Settings → Pages**: pod „Branch“ izaberi `main` i `/ (root)`, pa **Save**.
5. Posle 1–2 minuta sajt je na: `https://TVOJE-KORISNICKO-IME.github.io/svet-ruza/`

Ako posle izmene vidiš staru verziju, otvori sajt u privatnom prozoru ili sačekaj par minuta.

## Posle objave
U `index.html` nađi `content="share.jpg"` i upiši punu adresu, npr.
`content="https://TVOJE-KORISNICKO-IME.github.io/svet-ruza/share.jpg"`, da bi se slika videla kad se link deli.

## Izmene
- Cene: u `index.html` traži `var QTYS` (ruže) i `var EXTRAS` (dodaci).
- Telefon: traži `381655266134`.
- Za nove slike u galeriji najlakše je da ih pošalješ Claude-u da napravi novi `index.html`.

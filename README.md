# MYOFFICESHOP

Landing page pentru consumabile de birou, cu trafic direcționat spre listările eMAG.

Site static, un singur fișier `index.html` (CSS și JS inline, fără build step, fără dependențe — doar fontul Archivo încărcat de la Google Fonts).

## Publicare (GitHub Pages)

1. **Settings → Pages**
2. **Source**: `Deploy from a branch`
3. **Branch**: `main` / `(root)`
4. Salvează. Site-ul va fi disponibil la `https://myofficeshop.github.io/MYOFFICESHOP/`

## De făcut înainte de lansare

Datele din obiectul `CONFIG` (la finalul `index.html`) sunt parțial placeholder și trebuie verificate/completate:

- `priceBox`, `priceReam`, `pricePalletBox` — prețurile reale
- `products[]` — doar primul produs are URL real către eMAG
- Numele de brand, emailul de contact și afirmațiile din FAQ despre livrare

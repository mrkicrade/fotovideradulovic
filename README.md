# Studio Momenat — fotografski sajt

Statički sajt (jedna stranica) spreman za hostovanje na GitHub Pages.

## Sadržaj
- `index.html` — sajt
- `support.js`, `image-slot.js` — potrebne skripte (moraju ostati pored index.html)
- `min-*.jpg` — sve fotografije

## Postavljanje na GitHub Pages
1. Napravi novi repozitorijum na GitHub-u.
2. Ubaci SVE fajlove iz ovog foldera u koren repozitorijuma (ne u podfolder).
3. U repozitorijumu: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, izaberi granu `main` i folder `/ (root)`, pa **Save**.
4. Za par minuta sajt je dostupan na `https://<korisnicko-ime>.github.io/<repo>/` — taj link šalješ klijentu.

## Napomene
- Svi fajlovi moraju biti zajedno u istom folderu — putanje su relativne.
- Kontakt podaci (telefon, email, Instagram, Facebook) su placeholderi — zameni ih pravim u `index.html`.
- Kontakt forma je vizuelna; za primanje poruka poveži servis (Formspree/Web3Forms).

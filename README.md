# Website - Benjamin Dums

Persönliche Unternehmens-Website (One-Pager + Impressum/Datenschutz). Statisches HTML/CSS ohne Build-Schritt, ohne JavaScript, ohne externe Abhängigkeiten (Systemschriften, keine Cookies, kein Tracking).

**Inhalte sind abgeleitet, nicht führend:** Die Texte werden im career-Repo gepflegt (`/workspaces/work/career/60-website/content.md` sowie `impressum.md`, `datenschutz.md`) und von dort hierher übernommen. Änderungen an Texten zuerst dort. Betrieb (Domain, Hosting, Impressumsdaten) ist im Firmen-Repo dokumentiert (`company-knowlage`).

## Struktur

- `index.html` - One-Pager: Hero, Leistungen, Referenzen, Über mich, Kontakt
- `impressum.html`, `datenschutz.html` - Pflichtseiten (noindex)
- `style.css` - gesamtes Styling
- `assets/portrait.jpg` - Webfassung des Profilfotos (Quelle: `career/70-linkedin/assets/profile-photo.jpg`)

## Lokal ansehen

```sh
python3 -m http.server 8000
# http://localhost:8000
```

## Offene Punkte

- Domain registrieren und als Custom Domain in GitHub Pages hinterlegen (siehe career/60-website/README.md, Firmen-Repo).
- Screenshots/Bilder für die Referenzkarten ergänzen (aktuell reine Textkarten).
- LinkedIn-URL prüfen (angenommen: linkedin.com/in/benjamin-dums).
- Favicon und Open-Graph-Bild ergänzen.

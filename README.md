# Proxeratech – Firemní Web

Tento repozitář obsahuje zdrojový kód prezentačního webu Proxeratech.

Web je statický (HTML, CSS, obrázky) a nevyžaduje žádný backend ani build proces. Lze jej nasadit na GitHub Pages, Netlify, Vercel nebo libovolný běžný hosting.

## Struktura projektu

```
.
├── index.html           # Hlavní stránka
├── assets/
│   ├── css/             # Stylování webu
│   └── images/          # Logo a grafika
└── .github/workflows/   # CI a automatické nasazení
```

## Úprava obsahu

1. Texty upravíš přímo v `index.html`
2. Barvy a styly najdeš v `assets/css/style.css`
3. Obrázky se nachází v `assets/images/`

Pro náhled stačí dvojklik na `index.html`.

## Nasazení na GitHub Pages

1. Ujisti se, že jsi pushnul na větev `main`:
   ```bash
   git push -u origin main
   ```

2. V GitHubu otevři:
   **Settings → Pages → Build and deployment → Source → GitHub Actions**

3. Po pushi se automaticky vytvoří veřejná adresa:
   https://mojeproxeratech.github.io/mojeproxeratech/

## Licencování
Vlastní interní firemní kód. Nepoužívat bez povolení.

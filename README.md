# Portfolio QA — One-page (HTML)

Ce dépôt contient un portfolio **one-page** (un seul fichier HTML) optimisé pour :
- SEO (meta, Open Graph, JSON-LD)
- Responsive (mobile / tablette / desktop)
- Performance (pas de framework lourd)

## Fichiers
- `index.html` : page principale (tout-en-un : HTML + CSS + JS)
- `robots.txt` : directives crawl
- `sitemap.xml` : sitemap (à personnaliser avec ton URL)
- `404.html` : page 404 simple (utile pour GitHub Pages)

## Personnalisation rapide
Dans `index.html`, remplace les placeholders suivants :
- `[Ton prénom et nom]`
- `[INSÈRE TON URL ICI]` (URL canonique + Open Graph)
- `[INSÈRE TON URL LINKEDIN ICI]`
- `[INSÈRE TON EMAIL ICI]`
- `[INSÈRE TA PHRASE D’ACCROCHE ICI]`
- `[INSÈRE TA DESCRIPTION ICI : ...]`
- `[INSÈRE CE QUE TU APPRENDS/FAIS EN CE MOMENT : ...]`
- `[INSÈRE TON CAS D’ÉTUDE / PROJET QA DE FORMATION ICI]`
- `[INSÈRE TON LIEN REPO ICI - optionnel]`
- `[INSÈRE TA DISPONIBILITÉ ICI]`
- (optionnel) `og:image` et `twitter:image`

## Publication (exemple GitHub Pages)
1. Pousse ce repo sur GitHub.
2. Dans GitHub : Settings -> Pages
3. Source : `Deploy from a branch`
4. Branch : `main` / folder : `/root`

Ton site sera accessible via une URL du type :
`https://<ton-user>.github.io/<nom-du-repo>/`

## Notes
- Le formulaire de contact utilise `mailto:` (sans backend). C’est volontaire pour rester 100% statique.
- Si tu veux un envoi réel, il faudra ajouter un backend ou un service (Formspree, Netlify Forms, etc.).

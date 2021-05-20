# Trame du jour

## Retour sur les bases du HTML

## Les balises

Ressource : https://developer.mozilla.org/fr/docs/Web/HTML/Element

- insensibles à la casse
- 2 types de balises
  - classiques
  - auto fermantes
- comportement des balises
  - block
  - inline
- attributs des balises
  - ex : name, class, id, width, style...

## Nommage des balises

- ID : élément unique
- Classes : éléments multiples

## Le nesting

- les balises peuvent contenir d'autres balises
- on parle alors de parent et enfant(s)

## Les balises spécifiques

- `<meta>` : `<head>`
- `<title>` : `<head>`
- `<style>` : `<head>`
- `<link>` : `<head>` pour les feuilles de style
- `<script>` : `<head>` ou avant la fermeture de la balise `<body>`

## Bonnes pratiques

- externaliser les fichiers CSS et JS
  - permet d'avoir un code plus clean et maintenable
- créer une structure de projet claire

  - html
    - dossier css
      - fichiers css
    - dossier js
      - fichiers js
    - dossier assets
      - dossier images
        - fichiers images
      - dossier sons
        - fichiers sons

- positionnement des balises
  - `<link>` : toujours dans le `<head>`
  - `<script>` : privilégier un positionnement dans le `<head>` avec un attribut `defer` ou juste avant la fermeture du `<body>`

Ressources :

https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works

https://developer.mozilla.org/en-US/docs/Web/Performance/Critical_rendering_path

https://web.dev/defer-non-critical-css/

https://blog.logrocket.com/improve-site-performance-inlining-css/

## Quelques balises

- Headings : `<h1> ... <h6>`, hiérarchie
- Links `<a>`
- select
- datalist
- form
- fieldset
- input
- ul / ol

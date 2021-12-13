# Exercices HTML / CSS

Voici une liste d'exercices vous permettant
de pratiquer HTML et CSS.

Afin de réaliser ces exercices vous pouvez
vous aider de l'éditeur VSCode.

**Attention !** Essayer de respécter
**l'indentation** dans votre code afin de
conserver un jolie code lisible.

Vous pouvez aussi facilement générer une
structure HTML sur vscode en tapant
"html" puis en séléctionnant `html:5` depuis
la liste déroulante.

N'hésitez pas non plus à utiliser le
copier / coller ! Vous pouvez copier
en séléctionant une partie de texte puis
en appuyant sur la combinaison de touche
`Control + C`. Vous pouvez ensuite coller
en utilisant la combinaison de touche
`Control - V`

## Partie 1 - Les bases

### Exercice 1 - Créer une page d'accueil

1. Ouvrez un dossier vide avec VSCode (Fichier > Ouvrir le dossier, puis séléctioner ou créé un dossier complémtement video)
2. Avec l'éditeur VSCode créer un fichier html :
   `accueil.html`
3. Créer la structure du document HTML (le doctype,
   la balise html et la balise head et body)
4. Vous pouvez utiliser votre navigateur afin
   d'afficher votre page HTML
5. Personaliser la balise `<title>` avec le titre
   suivant : "Mon site - Accueil"
6. Créer dans la balise `body` un titre en utilisant
   la balise `h1` avec le contenu suivant : "Bienvenue sur mon site"
7. Ajouter à la suite du h1 la balise `p` avec le
   contenu suivant :

   ```
   Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus qui praesentium voluptatem voluptatum porro molestias

   quae pariatur labore consectetur laborum
   modi possimus, non dicta.
   Alias consequatur animi modi incidunt explicabo?
   ```

8. Ajouter à la suite de cette balise `p` une balise
   `h3` avec le contenu : "Menu"
9. Ajouter à la suite de la balise `h3` la balise
   `ul` qui contient 3 balises `li` avec le contenu
   suivant :

   - Accueil
   - Présentation

### Exercice 2 - Creer la page de présentation

1. Toujours avec VSCode créer un fichier `presentation.html`.
2. Ouvrez le fichier `presentation.html` et créé
   la structure HTML avec le `title` suivant :
   "Mon Site - Présentation"
3. Ajouter dans la balise `body` une balise `h1`
   avec le contenue suivant : "Présentation de mon activité"
4. A la suite de cette balise `h1` ajouter une balise
   `p` avec le texte suivant :

   ```
   Lorem ipsum dolor sit amet consectetur
   adipisicing elit. Accusamus qui
   praesentium voluptatem voluptatum
   porro molestias
   ```

5. Toujours avec VSCode créer un répertoire
   `images`
6. Télécharger l'[image suivante](https://www.vacancesweb.be/resources/cms/chan_copy1.jpg) et
   enregistré (ou déplacé) la dans le répertoire
   "images" créé précédement. Vous pouvez renomer
   cette image en "paysage.jpg"
7. Dans la page html "presentation.html" ajouter une
   balise `p` contenant une balise `img` affichant
   l'image téléchargé précédement. Voici un éxample dont vous pouvez vous inspirer afin d'afficher l'image :
   ```html
   <p>
     <img src="lien/vers/image.format" alt="text alternatif" />
   </p>
   ```

### Exercice 3 - Lier les pages entre elles

1. Dans la page `accueil.html`, à l'intérieur
   de la balise `ul` puis à l'intérieur de
   la balise `li` contenant "Présentation";
   créer une balise `a` contenant le texte
   "Présentation" et pointant vers la page
   "presentation.html". Voici un exemple
   d'utilisation de cette balise `a` :

```html
<ul>
  <li>
    <a href="lien/vers/page.html"> Présentation </a>
  </li>
</ul>
```

2. Faire la mème chose dans la page `presentation.html`
3. Ajouter de la même manière un lien vers la page
   `accueil.html`

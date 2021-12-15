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

## Partie 2 - Le CSS

### Exercice 1 - Créer la page d'accueil d'un restaurant

1. Créer, dans un répertoire vide, le fichier html "accueil.html".
2. Générer dans ce fichier un document html (le doctype, html, head et body)
3. Changer la balise title du head par "Mon Restaurant - Accueil"
4. Créer dans ce même répertoire une feuille de style "style.css"
5. Ajouter cette feuille de style à la page HTML en utilisant
   la balise `link` (ex: `<link rel="stylesheet" href="chemin/vers/style.css">`)
6. Placer à l'intérieur de la balise body le HTML suivant :

```html
<header>
  <h1>Mon Restaurant</h1>
  <nav>
    <ul>
      <li><a href="#presentation">Présentation</a></li>
      <li><a href="#menu">Menu</a></li>
      <li><a href="#map">Ou sommes-nous</a></li>
      <li><a href="#contact">Nous contacter</a></li>
    </ul>
  </nav>
</header>

<article>
  <h1>Bienvenue dans mon restaurant</h1>
  <p>
    <img
      src="https://www.toulouscope.fr/wp-content/uploads/2016/05/10871-11038014-975117875865100-6996763706854362029-n.jpg"
      alt="Mon restaurant"
    />
  </p>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>
</article>

<article id="presentation">
  <h2>Présentation</h2>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>
</article>

<article id="menu">
  <h2>Menu</h2>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>

  <h3>Les entrées</h3>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>

  <h3>Les plats</h3>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>

  <h3>Les Desserts</h3>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>
</article>

<article id="map">
  <h2>Ou sommes nous ?</h2>
  <iframe
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4085.832251505685!2d1.4315433276057394!3d43.6040494123757!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12aebb67cc269537%3A0x87156dceb798679e!2sRestaurant%20Michel%20Sarran!5e0!3m2!1sen!2sfr!4v1639481852864!5m2!1sen!2sfr"
    width="600"
    height="450"
    style="border:0;"
    allowfullscreen=""
    loading="lazy"
  ></iframe>
</article>

<article id="contact">
  <h2>Nous contacter</h2>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis eum,
    consectetur totam accusamus quisquam laboriosam cupiditate commodi qui harum
    delectus ullam sunt blanditiis ea quia ipsam libero! Laboriosam, nisi eius!
  </p>

  <h3>Adresse</h3>
  <p>21 Bd Armand Duportal, 31000 Toulouse</p>

  <h3>Téléphone</h3>
  <p>05 51 12 32 32</p>

  <h3>Nous envoyer un message</h3>
  <form>
    <div>
      <label for="username">Votre nom et prénom :</label>
      <input type="text" id="username" />
    </div>
    <div>
      <label for="email">Vore email :</label>
      <input type="text" id="username" />
    </div>
    <div>
      <label for="contenue">Votre message :</label>
      <textarea id="contenue"></textarea>
    </div>
    <div>
      <button>Envoyer le message</button>
    </div>
  </form>
</article>

<footer>
  <p>Mon Restaurant - 21 Bd Armand Duportal, 31000 Toulouse - 05 51 12 32 32</p>
</footer>
```

### Exercice 2 - Centrer les titre

Gràce à la régle CSS `text-align` center les titres
h1 et h2

### Exercice 3 - Titre principal

1. Gràce à la régle `font-family`, changer la police
   d'écriture de `h1` en `"Arial Rounded MT"` ou `"Times New Roman"`
2. Gràce à la régle `font-size` changer la taille de
   la police par `34px`

### Exercice 4 - Centrer avec une classe

1. Dans la première balise article ajouter la class
   css : `centrer`
2. Dans la feuille de style ajouter la class `.centrer`
   avec la régle css: `text-align: center`

### Exercice 5 - Le footer

1. Ajouter à la balise footer la class "centrer"
2. Gràce à la régle `font-style` mettre le text
   du footer en italic !

### Exercice 6 - Le menu

1. Grace au propriétés css `font-weight`,
   `text-decoration` et `color` mettre chaque
   lien du menu en non souligné, gras et de couleur
   grise

### Exercice 7 - Couleurs

1. Gràce à la régle css `background-color` et `color`,
   changer la couleur de fond de toute la page
   en `#FCFAEE` et la couleur du texte en `#0B2027`
2. Toujours avec les mémes régles css, changer la couleur
   des liens du menu en `#49798C`
3. Changer la couleur de fond du header et du footer en
   `#0B2027` et la couleur du texte du header en `#FCFAEE`
4. Changer la couleur de fond du l'article avec l'id
   menu en `#40798C`
5. Changer la couleur de fond de l'article avec l'id
   map en `#70A9A1`

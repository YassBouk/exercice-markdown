Le markdown, c'est quoi ?
=========================

Le markdown, c'est un language qui permet d'utiliser certaines fonctionnalitées du language *HTML* de façon raccourcie


# **le markdown sur un site.**

Pour que les visiteurs puisse écrire en Markdown sur un site il existe des implémentations de Markdows dans plusieurs langues.

un liste des implémentations est disponible sur [wikipedia](https://en.wikipedia.org/wiki/List_of_Markdown_implementations)

toutes les bibliotheques ont le même rôle, elles traduises du texte Markdown en HTML.

![Titre](https://user.oc-static.com/files/420001_421000/420264.png)

Si vous voulez utiliser Markdown pour vos forums par exemple, les choses devraient se passer dans cet ordre :

   1. Le visiteur écrit un texte en Markdown lorsqu'il rédige un message sur vos forums ;

   2. Vous stockez ce texte tel quel en Markdown dans votre base de données ;

   3. Lorsqu'un autre visiteur veut lire le message du membre, vous récupérez le texte en Markdown et vous le faites traduire en    HTML par une bibliothèque Markdown.
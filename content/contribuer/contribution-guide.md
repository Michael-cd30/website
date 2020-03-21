---
Title: Guide de contribution à Geotribu
Category: contribution
Date: 2020-03-20 10:20
Tags: guide
---

# Guide de contribution

## Créer une revue de presse

Créer un fichier dans `content\rdp` en respectant le nommage suivant : `rdp_AAAA-MM-JJ.md`. Exemple : `rdp_2020-03-27.md` pour la revue de presse du 20 mars 2020.

## Modifier une revue de presse

### Texte

Coucher sa prose en markdown en s'appuyant sur :

- [voir un spécimen de ce qu'il est possible d'obtenir](https://squidfunk.github.io/mkdocs-material/specimen/)
- [utiliser des blocs stylés](https://squidfunk.github.io/mkdocs-material/extensions/admonition/)
- [insérer du code](https://squidfunk.github.io/mkdocs-material/extensions/codehilite/)

### Ajouter une image

Dans la mesure du possible, les images doivent être récupérées depuis les autres sites / hébergées en externe :

```markdown
![Texte de remplacement](https://www.site-externe.com/medias/adresse_de_l_image.png "Titre/légende de mon image")
```

Si ça n'est vraiment pas possible :

1. Déposer l'image dans le sous-dossier adéquat sous `content/assets/images/`
2. La référencer dans un article suivant cette syntaxe :

<!-- Hyperlinks reference -->
[Git]: https://git-scm.com/download/win
[GitHub Desktop]: https://desktop.github.com/
[GitHub]: https://help.github.com/en/github/writing-on-github
[markdown]: https://fr.wikipedia.org/wiki/Markdown
[Python]: http://help.geotribu.com/development-guidelines/languages/python/
[StackEdit]: https://stackedit.io/
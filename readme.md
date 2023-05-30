# Second exo

Faire un site avec un tableau et un formulaire.

# Correction

Tout est bon pour moi. Les quelques points qui peuvent être améliorés sont :

- D'utiliser des classes et des identifiants pour appliquer des styles CSS ou pour cibler des éléments spécifiques à l'aide de JavaScript.
- D'ajouter un attribut id unique à chaque élément `<input>` et `<textarea>`, ce qui faciliterait leur ciblage à l'aide de JavaScript ou de CSS.
- (optionel et vu que je ne te l'ai pas dit tu ne pouvais pas savoir) : Il manque l'attribut required sur les champs du formulaire, ce qui permettrait de s'assurer que les utilisateurs saisissent toutes les informations nécessaires avant de soumettre le formulaire.

Pour le css je n'ai rien a redire, c'est très bien.
Pour le button, si tu veux le rendre "plus beau" la petite astuce est de rajouter les règles suivantes :

```css
button {
  border: none; // enlève la bordure de base
  background: none; // enlève le fond de base mais tu as mis un fond vert donc tu peux ignorer cette règle
  cursor: pointer; // change le curseur de la souris quand on passe dessus
  border-radius: 5px; // arrondi les coins
}
```

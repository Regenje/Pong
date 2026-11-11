# Pong Néon

Un Pong arcade dans le navigateur, joueur contre ordinateur, avec des bonus, des obstacles et des smashs.
Un seul fichier HTML, aucune dépendance.

**Jouer :** https://regenje.github.io/Pong/

## Commandes
- **Z/W et S**, **↑ / ↓**, ou la souris / le doigt : bouger la raquette
- **F** (ou Maj, ou le bouton SMASH sur mobile) : déclencher le smash quand la jauge est pleine
- **Espace** / **Échap** : pause · **R** : recommencer · **M** : couper le son

## Bonus
Les bonus vont au dernier joueur qui a touché la balle. La balle prend la couleur de son propriétaire.

| | Effet |
|---|---|
| ×3 | Multiball : la balle se divise en 3 |
| XL | Ta raquette grandit pendant 10 s |
| XS | La raquette adverse rétrécit pendant 10 s |
| 🔥 | Balle de feu : beaucoup plus rapide, traverse et casse les obstacles |
| ⏳ | Ralenti pour tout le monde pendant 5 s |
| 🛡 | Bouclier : un mur derrière toi qui sauve un point |

## Mécaniques
- **Angle selon l'impact** : au centre de la raquette la balle part tout droit, sur les bords elle part en diagonale.
- **Effet (spin)** : si tu bouges ta raquette au moment du contact, la balle courbe sa trajectoire.
- **Obstacles** : trois blocs mobiles au centre, qui se cassent après quelques coups et réapparaissent.
- **Jauge de smash** : chaque renvoi la remplit. Une fois pleine, arme le smash : le coup suivant part très vite.

## Réglages
Difficulté (facile → expert), points pour gagner, vitesse de balle, et activation/désactivation des bonus, obstacles, spin, smash, son et secousses. Les réglages sont mémorisés dans le navigateur.

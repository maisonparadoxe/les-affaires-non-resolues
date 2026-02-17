# Les Affaires Non Résolues

Un jeu de logique et de déduction jouable directement dans le navigateur, en un seul fichier HTML.  
Développé par **Maison Paradoxe**.

---

## Jouer

Ouvrez `index.html` dans un navigateur — aucune dépendance, aucun serveur requis.

Ou jouez en ligne via GitHub Pages :  
`https://maisonparadoxe.github.io/les-affaires-non-resolues/`

---

## Règles

Un meurtre a été commis. Trois catégories d'éléments sont en jeu :
- **Suspects** — qui a commis le crime ?
- **Armes** — quel objet a été utilisé ?
- **Lieux** — où le crime a-t-il eu lieu ?

### La grille de déduction
La grille croise chaque entité avec les autres. Pour chaque case :
- **1 clic** → `◆` (confirmé)
- **2 clics** → `✕` (exclu)
- **3 clics** → effacé

Quand vous confirmez une case, le jeu exclut automatiquement les autres possibilités sur la même ligne/colonne.

### Les indices
Chaque affaire fournit des indices logiques dans l'onglet **Indices**. Cliquez sur un indice pour le marquer comme utilisé.

### L'accusation
Une fois certain de votre déduction, rendez-vous dans l'onglet **Accusation**. Vous n'avez **qu'une seule chance** — une mauvaise accusation met fin à l'enquête.

### Le temps
Un minuteur décompte. Si le temps s'écoule, l'affaire reste non résolue.

---

## Affaires disponibles

| Affaire | Niveau | Suspects | Armes | Lieux | Temps |
|---|---|---|---|---|---|
| Le Dîner de Gala | Novice | 3 | 3 | 3 | 10 min |
| La Nuit du Vernissage | Inspecteur | 4 | 4 | 4 | 15 min |
| Le Congrès des Ombres | Détective | 5 | 5 | 5 | 20 min |
| Le Bal des Masques | Dossier d'Exception | 6 | 6 | 6 | 30 min |

### Dossier d'Exception — Le Bal des Masques
Le quatrième cas est verrouillé. Il se débloque automatiquement une fois que les trois premières affaires ont été ouvertes (victoire ou défaite). La progression est sauvegardée entre les sessions.

## Maison Paradoxe

*Maison d'expériences narratives interactives.*  
Nous concevons des enquêtes, des mystères et des récits à résoudre.

&copy; 2026 Maison Paradoxe

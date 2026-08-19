# L'Établi

**Reprendre la main.**

Des outils libres qui éclairent la part navigable d'une démarche et accompagnent jusqu'au seuil du professionnel — sans péage, sans captation de données.

L'Établi est un établi partagé : une collection d'outils qui reprennent, une à une, les démarches qu'on paie trop cher pour ne pas les faire soi-même. Chaque outil éclaire la **part navigable** d'une démarche, accompagne jusqu'au **seuil** du professionnel vraiment nécessaire — et s'arrête là.

Ce n'est ni une plateforme, ni une entreprise de désintermédiation. Pas de commission, pas de compte, pas de données captées : les outils tournent dans le navigateur de la personne.

→ Lire le [**Manifeste**](MANIFESTE.md).

---

## Les trois critères

Un sujet a sa place ici seulement si les trois conditions sont réunies :

1. **Une voie publique existe** — la démarche est faisable seul, légalement, par des moyens gratuits ou accessibles.
2. **Un péage l'obscurcit** — un intermédiaire se rémunère sur l'accès au chemin, pas sur un savoir irremplaçable.
3. **La démarche est stable** — les règles ne changent pas tous les six mois, sinon un outil figé périme et devient un piège.

---

## Les outils

| Outil | État | Ce dont il libère |
|-------|------|-------------------|
| **Vendre sans agence** | 🟢 En ligne | La vente d'un logement, de l'annonce au notaire, sans commission. |
| **Assurance emprunteur** | 🔨 En chantier | Changer l'assurance de son prêt (loi Lemoine). |
| **Après un décès** | 🔨 En chantier | L'administratif d'un deuil, sans opacité sur les devis. |
| **Comprendre sa parcelle** | 🔨 En chantier | Cadastre, PLU, servitudes à partir des données publiques. |
| **Louer sans agence** | 🔨 En chantier | Bail, état des lieux, récupération d'une caution abusive. |
| **Résilier & récupérer** | 🔨 En chantier | Annulations, contestations, lettres de réclamation. |

L'outil « Vendre sans agence » vit actuellement dans son propre dépôt (`vendez`). L'objectif est de faire de L'Établi la page qui les fédère.

---

## Structure du dépôt

```
letabli/
├── index.html        → la page d'accueil (le contenant)
├── MANIFESTE.md      → le texte fondateur
├── README.md         → ce fichier
├── LICENSE           → AGPL-3.0 (le code)
├── tribunes/         → les textes / prises de position (à venir)
└── outils/           → les outils intégrés (au fur et à mesure)
```

Chaque outil reste une brique autonome (HTML statique, sans dépendance serveur), branchée sous la même page d'accueil.

---

## Licences

- **Textes** (manifeste, tribunes) : [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — réutilisables, à condition de citer la source.
- **Code des outils** : [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html) — copyleft réseau : quiconque réutilise ce code, même en le proposant seulement en ligne, doit publier ses sources sous la même licence. Nul ne pourra reprendre L'Établi pour en faire un péage fermé.

---

## Parenté

L'Établi partage l'esprit d'[IA'm](https://iam-inside.eu) — l'honnêteté, le fait-main, l'humain qui reste maître de ses choix — mais reste une maison séparée : dépôt, identité et gouvernance propres.

---

## Contact

L'atelier de Joseph — l.etabli.de.joseph@gmail.com

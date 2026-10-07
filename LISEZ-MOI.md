# Dactylo AZERTY — site statique

Deux fichiers, aucune dépendance, aucun serveur applicatif, aucun appel réseau.

```
index.html     l'application entière (HTML + CSS + JS)
favicon.svg    icône d'onglet
```

## Mise en ligne

**Partage réseau / lecteur commun** — copier le dossier, puis ouvrir `index.html`.
Fonctionne aussi en double-clic depuis un poste local.

**Serveur web interne (IIS, Apache, nginx)** — déposer le contenu du dossier dans la
racine d'un site ou d'un sous-dossier. Rien à configurer côté serveur.

**Hébergement statique (GitHub Pages, Netlify, Cloudflare Pages)** — glisser le
dossier, l'URL est immédiatement utilisable.

## Utilisation

- **Leçons** (21) : de la rangée de repos aux majuscules, chiffres, ponctuation et accents
  circonflexes (touche morte `^`). Les touches où tu te trompes reviennent plus souvent.
- **Vitesse** : tests de 30 s à 5 min, en mots ou en phrases ; record mémorisé.
- **Jeu** : pluie de mots, pause automatique quand on quitte l'onglet.
- **Progression** : courbe, carte du clavier (erreurs ou lenteur par touche), historique,
  export / import en JSON.

Raccourcis : `Entrée` pour continuer, `Échap` pour recommencer, `←` `→` pour changer de leçon
avant de commencer. Le chrono démarre à la première touche, et une inactivité de plus de
2,5 s n'est pas comptée dans les mots/min.

## Enregistrement de la progression

Les leçons validées, les statistiques par touche et l'historique sont stockés dans le
`localStorage` du navigateur. Conséquences :

- la progression est liée au poste **et** au navigateur, elle ne suit pas l'utilisateur ;
- vider les données de navigation efface la progression ;
- en ouverture directe par `file://`, certains navigateurs restreignent le stockage.
  Passer par un vrai serveur (même en local) lève cette limite.
- pour changer de poste ou de navigateur : onglet Progression → *Exporter*, puis *Importer*
  sur l'autre poste.

## Pré-requis

Un clavier physique AZERTY. Navigateur récent (Chrome, Edge, Firefox).
La page s'adapte aux petits écrans, mais l'exercice n'a pas de sens sans clavier réel.

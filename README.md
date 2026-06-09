# Le Slip Magreben

> Lingerie fusion magrébine — projet **parodique** du slip français, imaginé entre amis pour le plaisir et le second degré.

Une fausse marque de sous-vêtements « éco-responsables » qui mêle le confort du slip français aux motifs magrébins (zellige, broderies berbères, indigo touareg…). Le tout est une **fiction humoristique** : aucune boutique réelle, aucun produit à vendre, juste une page vitrine soignée pour faire sourire.

## Aperçu

Le site est une **landing page autonome** ([index.html](index.html)) — un seul fichier HTML/CSS/JS, sans build ni dépendance. Il contient :

- une bannière (hero) et une navigation ancrée ;
- une boutique de 8 modèles fictifs avec visuels et prix ;
- des sections packs, histoire de la marque, inspiration, guide des tailles, avis et abonnement ;
- des données structurées [Schema.org](https://schema.org/) (`Organization`, `Product`) et des balises SEO/Open Graph.

### La collection (fictive)

| Modèle | Inspiration | Prix |
|---|---|---|
| Zellige Edge | Motifs zellige indigo | 32 € |
| Berbère Whisper | Symboles amazighs brodés | 35 € |
| Safran Silk | Soie teintée au safran | 42 € |
| Indigo Nomade | Dégradé indigo touareg | 38 € |
| Atlas Dusk | Aurores sur l'Atlas | 29 € |
| Médina Blanc | Dentelle arabesques | 32 € |
| Henna Night | Rouge henné, broderies or | 45 € |
| Desert Dawn | Sable et ocre amazigh | 29 € |

## Lancer en local

Aucune installation requise. Ouvrez simplement [index.html](index.html) dans un navigateur, ou servez le dossier :

```sh
python3 -m http.server 8000
# puis ouvrez http://localhost:8000
```

## Structure

```
.
├── index.html   # la page complète (HTML + CSS + JS inline)
├── img/         # visuels des modèles (.png)
├── LICENSE      # MIT
└── README.md
```

## Avertissement

Projet humoristique et volontairement décalé, réalisé entre amis. Contenu à prendre avec légèreté : il ne s'agit ni d'une vraie marque, ni d'un vrai commerce.

## Licence

[MIT](LICENSE) © 2026 Jean-David Halimi

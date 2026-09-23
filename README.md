# Observatoire de l'IA dans les entreprises d'Occitanie

Combien d'entreprises d'Occitanie recrutent réellement autour de l'intelligence
artificielle ? Ce dépôt publie les chiffres, en CSV, relevé après relevé.

**Relevé du 23 septembre 2026** : 32 864 offres lues, sur les offres
publiées du 1er septembre 2026 au 23 septembre 2026.

Sous licence **CC BY 4.0**. Réutilisable librement, y compris commercialement, en
créditant la source.

## Les données

| Fichier | Question à laquelle il répond |
|---|---|
| `departements.csv` | Où recrute-t-on en Occitanie ? |
| `secteurs.csv` | Quels secteurs recrutent le plus ? |
| `contrats.csv` | Quels types de contrat propose-t-on ? |
| `tailles.csv` | Qui recrute, les petites ou les grandes entreprises ? |
| `metiers.csv` | Quels métiers recrutent le plus ? |
| `communes.csv` | Quelles villes concentrent les offres ? |
| `outils.csv` | Quels outils d'IA sont nommés dans les offres ? |

Encodage UTF-8, séparateur point-virgule, première ligne d'en-têtes.

`metadonnees.json` porte la période, les sources et la méthode du relevé.

## Le dénominateur, et pourquoi il compte

68 373 entreprises actives de plus de 5 salariés en Occitanie
composent la population de référence.

Un chiffre d'offres d'emploi sans son dénominateur ne veut rien dire. C'est la
raison d'être de cet observatoire : rapporter ce qui est annoncé à ce qui existe.
Les chiffres qui en sortent sont souvent plus bas que le discours ambiant, et
c'est précisément ce qu'ils servent à mesurer.

## Sources

- **Offres d'emploi** : France Travail, API Offres d'emploi v2. <https://francetravail.io/produits-partages/catalogue/offres-emploi>
- **Population d'entreprises** : API Recherche d'entreprises (annuaire-entreprises.data.gouv.fr), relevé du 14 septembre 2026

Traitement Oriq. Les offres elles-mêmes ne sont pas republiées : ce dépôt ne
contient que des agrégats.

## Comment citer

Ce dépôt porte un [`CITATION.cff`](CITATION.cff) au format standard.

> Observatoire de l'IA dans les entreprises d'Occitanie, Oriq, releve du 23 septembre 2026, https://oriq.fr/observatoire/

## Méthode et limites

La méthode complète est publiée : <https://oriq.fr/observatoire/methodologie.html>

Une limite est assumée et vaut d'être lue avant toute reprise : une offre qui ne
nomme pas l'IA n'est pas comptée, et une entreprise qui utilise l'IA sans
recruter ne l'est pas non plus. Cet observatoire mesure ce qui est **annoncé
dans les offres d'emploi**, pas l'usage réel de l'IA en entreprise.

## Rythme

Le relevé est périodique. Chaque mise à jour de ce dépôt correspond à un relevé
daté, et remplace le précédent. L'historique des versions est dans les releases.

---

Publié par [Oriq](https://oriq.fr/), Toulouse.

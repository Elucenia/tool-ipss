<!-- ELUCENIA technical documentation · ipss · fr · no clinical/professional/rights approval -->

# IPSS (score international des symptômes prostatiques)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/ipss)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Vidange incomplète : sensation de ne pas vider complètement la vessie

`esvaz`

- `0` — Jamais
- `1` — Moins de 1 fois sur 5
- `2` — Moins de la moitié des fois
- `3` — Environ la moitié des fois
- `4` — Plus de la moitié des fois
- `5` — Presque toujours

### Fréquence : besoin d’uriner à nouveau moins de 2 heures après

`freq`

- `0` — Jamais
- `1` — Moins de 1 fois sur 5
- `2` — Moins de la moitié des fois
- `3` — Environ la moitié des fois
- `4` — Plus de la moitié des fois
- `5` — Presque toujours

### Intermittence : le jet urinaire s’arrête et reprend plusieurs fois

`inter`

- `0` — Jamais
- `1` — Moins de 1 fois sur 5
- `2` — Moins de la moitié des fois
- `3` — Environ la moitié des fois
- `4` — Plus de la moitié des fois
- `5` — Presque toujours

### Urgence : difficulté à retenir l’urine

`urg`

- `0` — Jamais
- `1` — Moins de 1 fois sur 5
- `2` — Moins de la moitié des fois
- `3` — Environ la moitié des fois
- `4` — Plus de la moitié des fois
- `5` — Presque toujours

### Jet urinaire faible

`jato`

- `0` — Jamais
- `1` — Moins de 1 fois sur 5
- `2` — Moins de la moitié des fois
- `3` — Environ la moitié des fois
- `4` — Plus de la moitié des fois
- `5` — Presque toujours

### Effort : besoin de pousser pour commencer à uriner

`esforco`

- `0` — Jamais
- `1` — Moins de 1 fois sur 5
- `2` — Moins de la moitié des fois
- `3` — Environ la moitié des fois
- `4` — Plus de la moitié des fois
- `5` — Presque toujours

### Nycturie : nombre de levers nocturnes pour uriner

`noct`

- `0` — Aucune
- `1` — 1 fois
- `2` — 2 fois
- `3` — 3 fois
- `4` — 4 fois
- `5` — 5 fois ou plus

## Édition de la méthode

AUASI/Barry 1992, IPSS 7 items 0–5, total 0–35 ; qualité de vie, 8e item séparé

## Formule documentée

Sept questions sur le dernier mois, chacune de 0 à 5 points. Total 0 à 35.

La 8e question (qualité de vie, de 0 "enchanté" à 6 "très malheureux") est enregistrée à part et n’entre pas dans la somme.

## Limites et population

L’IPSS/AUA quantifie les symptômes urinaires et leur évolution, mais le total n’établit pas que leur cause soit une hyperplasie bénigne de la prostate. La validation originale concernait des personnes atteintes d’HBP et des témoins. La formulation, la fenêtre temporelle, la qualité de vie et les limites de la version linguistique doivent être conservées et vérifiées séparément.

## Références

- [Barry MJ et al. The American Urological Association symptom index for benign prostatic hyperplasia. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)36966-5)

- [Lerner LB et al. Management of lower urinary tract symptoms attributed to benign prostatic hyperplasia: AUA guideline part I, initial work-up and medical management. J Urol, 2021.](https://doi.org/10.1097/JU.0000000000002183)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

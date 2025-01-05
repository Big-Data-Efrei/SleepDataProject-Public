# Projet d'Analyse de Données de Santé et de Bien-Être

## Introduction

Dans un monde où les rythmes de la vie moderne influencent directement la santé et le bien-être des individus, l'étude des interactions entre le sommeil, l'activité physique, l'occupation, le stress et d'autres facteurs liés au mode de vie est essentielle. Ce projet a pour but d'explorer un ensemble de données combinant des informations démographiques, de santé et de sommeil afin de mieux comprendre ces relations et de suggérer des moyens d'améliorer le bien-être général.

## Contexte du Projet

Le sommeil joue un rôle crucial dans la santé physique et mentale. Cependant, il n'agit pas seul : des facteurs tels que l'activité physique, l'activité professionnelle, les niveaux de stress et les caractéristiques démographiques (âge, sexe) interagissent pour influencer la qualité et la durée du sommeil. En analysant ces données, nous espérons pouvoir répondre à des questions clés, telles que :

- Comment les groupes démographiques se reposent-ils ?
- L'activité physique influence-t-elle la qualité du sommeil ?
- Le niveau de stress affecte-t-il directement la durée ou la qualité du sommeil ?
- Existe-t-il un lien entre la profession exercée et le niveau de stress, et par extension, la qualité du sommeil ?

## Analyses et Visualisations

1. **Visualisation de la Durée Moyenne de Sommeil par Person_ID**

**Objectif** : Montre la durée moyenne de sommeil par individu, ce qui permet d'identifier les variations de sommeil parmi les différentes personnes.

**Analyse des Résultats** :

- **Variabilité du Sommeil** : La visualisation montre une variabilité significative de la durée de sommeil parmi les individus. Certains peuvent dormir plus de 8 heures en moyenne, tandis que d'autres dorment moins de 6 heures.

- **Identification des Cas Particuliers** : Les individus avec des durées de sommeil extrêmes peuvent être identifiés facilement, permettant de repérer ceux qui pourraient avoir des troubles de sommeil ou des habitudes non optimales.

- **Potentiel d'Intervention** : Ces informations peuvent être utilisées pour fournir des recommandations personnalisées pour améliorer les habitudes de sommeil.

![Durée Moyenne de Sommeil par Groupe de Person_ID](https://github.com/Big-Data-Efrei/SleepDataProject-Public/assets/chart_1.png)

---

2. **Visualisation du Niveau de Stress par Person_ID**

**Objectif** : Présente le niveau moyen de stress par individu, permettant ainsi de détecter ceux qui éprouvent des niveaux de stress plus élevés que la moyenne.

**Analyse des Résultats** :

- **Écart de Stress** : Le niveau de stress varie considérablement entre les individus, certains ayant des niveaux de stress nettement plus élevés que d'autres.

- **Groupes à Risque** : Les individus présentant des niveaux de stress chroniquement élevés peuvent être identifiés comme des groupes à risque nécessitant une attention particulière.

- **Interventions Ciblées** : Ces informations peuvent aider à cibler les interventions de gestion du stress pour les individus les plus stressés.

![Niveau de Stress par Groupe de Person_ID](https://github.com/Big-Data-Efrei/SleepDataProject-Public/assets/chart_2.png)

---

3. **Tendance de la Durée de Sommeil par Âge**

**Objectif** : Met en lumière les tendances de la durée de sommeil en fonction de l'âge, en identifiant les âges où la durée de sommeil est maximale ou minimale.

**Analyse des Résultats** :

- **Variabilité par Âge** : La durée de sommeil varie de manière significative en fonction de l'âge.

- **Valeurs Maximale et Minimale** : Les points critiques où la durée de sommeil est la plus basse (**5.80 heures**) et la plus haute (**8.42 heures**) sont identifiés.

- **Tendances Générales** : La ligne bleue du graphique montre une fluctuation de la durée de sommeil, influencée par des facteurs tels que les cycles biologiques et les obligations professionnelles.

![Tendance de la Durée de Sommeil par Âge](https://github.com/Big-Data-Efrei/SleepDataProject-Public/assets/chart_3.png)

---

4. **Visualisation du Niveau d'Activité Physique par Person_ID**

**Objectif** : Illustre le niveau moyen d'activité physique par groupe de Person_ID, avec des couleurs et des catégories pour différents niveaux d'activité, aidant à comprendre les habitudes d'exercice des individus.

**Analyse des Résultats** :

- **Distribution des Niveaux d'Activité** : Les niveaux d'activité physique sont catégorisés en groupes, permettant une identification facile des groupes d'individus ayant des habitudes d'exercice similaires.

- **Focus sur l'Intervention** : Les groupes avec des niveaux d'activité physique faibles peuvent être ciblés pour des interventions visant à augmenter leur activité physique.

![Niveau d'Activité Physique par Groupe de Person_ID](https://github.com/Big-Data-Efrei/SleepDataProject-Public/assets/chart_4.png)

---

5. **Segmentation par Genre et Occupation**

**Objectif** : Étudier les différences dans la durée de sommeil selon le genre et l'occupation.

**Analyse des Résultats** :

- **Répartition par Genre** : Le graphique montre la distribution des différentes occupations par genre, permettant de voir comment les durées de sommeil varient en fonction du genre et de l'occupation.

- **Occupations** : Les différentes occupations représentées incluent Accountant, Doctor, Engineer, Lawyer, Manager, Nurse, Sales Representative, Salesperson, Scientist, Software Engineer, et Teacher. Chaque segment de la barre est coloré pour représenter une occupation différente.

- **Différences selon le Genre** : Cette analyse aide à identifier les différences dans la durée de sommeil entre hommes et femmes pour chaque occupation.

-**Impact de l'Occupation sur le Sommeil** : Les professions telles que Manager ou Lawyer, associées à des niveaux de stress plus élevés, peuvent montrer des durées de sommeil réduites.

![Durée Moyenne de Sommeil par Genre et Occupation](https://github.com/Big-Data-Efrei/SleepDataProject-Public/assets/chart_5.png)

---
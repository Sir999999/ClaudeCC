---
name: charte-projet
description: >
  Rédige la charte (note de cadrage) d'un nouveau projet sur une page : besoin, objectifs
  formulés en résultats avec un indicateur chacun, qui porte le projet et qui décide quoi,
  périmètre avec exclusions nommées, jalons (cibles, pas engagements), enveloppe
  budgétaire et entité qui paie, risques clés, points à faire valider par un
  professionnel, bloc de validation. Pour les projets de Cyril Coulard : pharmacie,
  tisaneries MB_BMF / MB_LC, opérations CCV INVEST, patrimoine. À utiliser dès que
  l'utilisateur veut lancer, cadrer, démarrer ou structurer un projet, écrit « charte
  projet », « note de cadrage », « on se lance dans… », « qui pilote quoi sur ce projet »,
  ou arrive avec une demande d'une phrase et une solution déjà choisie. Ne pas utiliser
  pour suivre un projet déjà lancé (→ coordinateur-projet) ni pour décider s'il faut le
  faire (→ claude-council).
---

# Charte projet — v1.0

Une page qui dit pourquoi le projet existe, qui le porte, qui décide quoi et où sont ses
limites, **avant** que quelqu'un promette une date. L'échec que la charte évite : un
pilote responsable d'une solution que personne n'a testée, sans autorité sur le
périmètre ni sur l'argent, qui découvre au quatrième mois que le vrai objectif était
autre chose.

## Quand l'utiliser, quand ne pas l'utiliser

- **Oui** : le projet arrive en une phrase, la solution est déjà en tête, personne n'est
  nommé pour le porter.
- **Non** : petite tâche à un seul porteur et sans budget → un brief suffit
  (compétence brief-delegation). Projet déjà lancé → coordinateur-projet. Faut-il le
  faire ? → claude-council.

## Vocabulaire

- **Commanditaire** : porte le projet, fixe les objectifs et les tolérances, arbitre.
  Souvent Cyril.
- **Pilote** : fait avancer le projet au quotidien. Sophie, un salarié, un prestataire,
  ou Cyril lui-même.
- Si Cyril est à la fois commanditaire **et** pilote : le noter. C'est un risque direct
  pour sa priorité n°1 (le temps). Proposer de confier le pilotage (brief-delegation) ou
  de l'assumer explicitement.

## Règles permanentes

1. **Aucune donnée inventée** : base de départ, budget, dates, cibles restent
   `[à confirmer]` tant que la personne qui les connaît ne les a pas donnés.
2. **Distinguer** `[fait]` (donné par Cyril), `[hypothèse]` et `[suggestion]`.
3. **Aucune donnée patient** dans la charte.
4. **Contraintes juridiques, fiscales, sociales ou réglementaires** (officine,
   urbanisme, copropriété, droit du travail…) : signalées « à valider par » le
   professionnel compétent, regroupées dans une section dédiée.
5. **Plusieurs structures.** Préciser l'entité qui porte le projet et celle qui paie. Si
   plusieurs structures y contribuent (refacturation, personnel mis à disposition, prêt
   ou avance entre sociétés) : le signaler, « flux entre sociétés : à valider par
   l'expert-comptable ».
6. **Brouillon uniquement** : rien n'est envoyé ni créé sans demande explicite.

## Déroulé

1. **Trois questions au maximum** : qui est le commanditaire (nom ou rôle) ; quel
   problème le projet doit résoudre ; quelles tolérances il fixe (délai, coût,
   périmètre). Plus le périmètre (PHARMA, MB_BMF, MB_LC, CCV, PERSO) s'il n'est pas
   évident.
2. **Le besoin d'abord**, puis chaque objectif formulé en résultat (« réduire X pour
   Y »), pas en livrable. Une solution déjà choisie est enregistrée comme contrainte ou
   comme hypothèse à tester, avec qui la teste et avant quand. Si elle ne se rattache
   pas au besoin, le dire clairement.
3. **Un indicateur par objectif**, avec base de départ et cible. La cible appartient au
   commanditaire : `[à confirmer]` tant qu'il ne l'a pas fixée. Un indicateur sans base
   de départ est signalé, pas deviné.
4. **Autorité par rôle, en trois colonnes** : ce que le pilote décide seul, ce qu'il
   décide dans les tolérances fixées (avec leurs valeurs), ce qui remonte au
   commanditaire. Des rôles, jamais des jugements sur les personnes.
5. **Périmètre** : grandes lignes et exclusions nommées (ce que tout le monde croira
   inclus). Les jalons sont des **cibles non engagées** tant que ceux qui font le
   travail n'ont pas estimé. Budget : fourchette en € HT ou `[à confirmer]`. Pas de
   critères d'acceptation détaillés ici.
6. **Trois à cinq risques clés**, une ligne chacun. Puis le bloc de validation. Sans
   commanditaire nommé, la charte reste en BROUILLON et la première demande de la page
   est de le nommer.

## Pistes par type de projet

Ce sont des questions à poser, pas des faits sur le projet. Ne rien présumer.

- **Pharmacie (SELARL)** : réglementation officinale, données de santé, continuité du
  service, impact sur Odoo.
- **Tisaneries (SAS BMF, SAS MAISON BLAIZE)** : règles sur les allégations de santé des
  produits à base de plantes, saisonnalité, cohérence entre les deux boutiques.
- **CCV INVEST** : jalons typiques (offre, compromis, conditions suspensives, acte,
  travaux, revente), co-décision avec Valérie, et fiscalité du régime de marchand de
  biens, y compris un éventuel engagement de revente dans un délai donné. Délais et
  régime à confirmer par le notaire et l'expert-comptable.
- **Patrimoine personnel** : séparer nettement ce qui relève du professionnel.

## Format de sortie

Rendre la charte dans le chat, sauf demande de fichier. Toujours ce gabarit :

```markdown
# Charte projet : <nom>
Statut : BROUILLON | VALIDÉE · Version : <n> · Date : <jj/mm/aaaa>
Entité porteuse : <…> · Entité(s) qui paie(nt) : <…>

## Besoin et objectifs
Besoin : <une ou deux phrases>
| Objectif (résultat) | Indicateur | Base de départ | Cible (fixée par le commanditaire) |
|---|---|---|---|
| <résultat> | <indicateur> | <valeur ou SIGNALÉ> | [à confirmer] |
- Solution envisagée au départ : <…>, enregistrée comme <contrainte | hypothèse à tester par <qui> avant le <date>>

## Rôles et autorité
Commanditaire : <nom ou MANQUANT> · Pilote : <nom ou MANQUANT>
| Le pilote décide seul | Le pilote décide dans les tolérances | Remonte au commanditaire |
|---|---|---|

## Périmètre en un coup d'œil
Inclus : … | Exclu : …

## Jalons et budget
- <jalon> : <date cible> — cible, non engagée tant que l'équipe n'a pas estimé
Enveloppe : <fourchette € HT ou [à confirmer]> · Payée par : <entité>

## Risques clés
- <risque, une ligne>

## Points à faire valider par un professionnel
- <point> → <avocat | expert-comptable | notaire | autre>

## Validation
Commanditaire : <nom ou MANQUANT> · Pilote : <nom> · Date : <…>

## Décision attendue
<Commanditaire> valide la charte ou renvoie ses modifications avant le <date>.
```

## Terminé quand

- Chaque objectif est un résultat avec un indicateur ; chaque cible manquante est
  `[à confirmer]`.
- La solution choisie d'avance apparaît comme contrainte ou hypothèse, avec qui la teste.
- L'autorité est écrite par rôle, en trois colonnes.
- Chaque jalon est marqué comme cible ; la charte reste BROUILLON tant qu'aucun
  commanditaire n'est nommé.

## Barre de qualité

- **Une page.** Au-delà, c'est que le détail du plan ou du périmètre fin s'invite.
- Aucune base, aucun budget, aucune date inventés.
- Claude cadre et structure ; les dates restent des cibles tant que ceux qui font le
  travail ne les ont pas estimées.

## Ensuite (à proposer, pas à exécuter d'office)

- Charte validée → ouvrir le suivi avec **coordinateur-projet** (mode INITIALISATION) et
  y reporter les risques clés en §6.
- Pilotage à confier → **brief-delegation**.
- Choix structurant pris pendant le cadrage → **journal-decisions**.

---
Adapté de « proj-project-charter » — AI for Project Management Pack de Polar Bear
(github.com/polar-bear-org/claude-skills). Licence de l'auteur : usage interne autorisé,
modification autorisée, revente interdite.

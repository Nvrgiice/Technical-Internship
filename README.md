# Stage S7 — LISA, Université Libre de Bruxelles

Stage de 4 mois réalisé au Laboratory of Image Synthesis and Analysis (ULB, Bruxelles)
de septembre à décembre 2025, dans le cadre de ma formation ingénieur à l'ESEO Angers.

## Le contexte

Le labo gérait les sujets de mémoire et les candidatures étudiantes avec un assemblage
de LimeSurvey et de scripts Python qui ne fonctionnait plus après une mise à jour.
Ma mission : remplacer tout ça par une solution robuste, maintenable et adaptée
à un public mixte ULB/VUB (étudiants francophones et néerlandophones).

## Ce que j'ai fait

J'ai conçu et déployé from scratch une application web complète basée sur ERPNext/Frappe,
avec trois espaces dédiés selon le rôle : étudiant, professeur et administration.

Le flux couvre tout le cycle : publication des sujets, candidatures, décision du professeur
avec traçabilité, suivi côté étudiant, dépôt du PDF final et export CSV pour l'administration.
Les notifications e-mail sont automatisées via des hooks Frappe, et l'application est
déployée sur un serveur Linux dans un environnement Docker reproductible.

## Stack technique

`Python` `Frappe / ERPNext` `MariaDB` `JavaScript` `Jinja2` `Docker` `GitLab CI/CD` `SMTP` `Linux`

## Contenu du dépôt

Le code source est confidentiel (propriété de l'ULB). Ce dépôt contient le rapport
de stage complet qui détaille les choix techniques, l'architecture, le développement
et le déploiement de l'application.

## Tuteurs

Olivier Debeir & Rudy Ercek — LISA, Université Libre de Bruxelles

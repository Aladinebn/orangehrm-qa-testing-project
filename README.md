## 📌 Contexte
Ce projet est un projet personnel de test logiciel réalisé après l’obtention de la certification ISQB.
Il a pour objectif de mettre en pratique les concepts fondamentaux du test logiciel à travers un cas concret : l’application web OrangeHRM Demo.

## 🎯 Objectifs
- Appliquer une méthodologie de test fonctionnel manuel
- Concevoir des cas de test à partir de User Stories et critères d’acceptation
- Exécuter les tests et analyser les résultats
- Identifier, documenter et prioriser des anomalies
- Produire un reporting de test clair et structuré

## Périmètre de test
### Inclus
- Authentification utilisateur (Login)
- Déconnexion utilisateur (Logout)

### Hors périmètre
- Gestion des employés
- Gestion des utilisateurs système
- Fonctionnalités avancées de sécurité
- Tests de performance et d’automatisation

## Types de tests réalisés
- Tests fonctionnels manuels
- Tests basés sur les exigences (requirements-based testing)
- Vérifications de base liées à la sécurité (authentification / session)

## Outils et supports
- Cas de test : Excel
- Bug reporting : Excel (format proche des outils type Squash TM / Jira)
- Reporting : Test Summary Report
- Navigateur : Chrome
- OS : Windows

## Résumé d’exécution
- Nombre total de cas de test : 17
- Cas de test exécutés : 17
- PASS : 16
- FAIL : 1
- Bugs identifiés : 1 (sévérité critique liée à la sécurité après logout)

## Anomalies notables
Un bug critique a été identifié concernant l’accès aux pages sécurisées via le bouton "Retour" du navigateur après déconnexion.
Ce comportement peut être lié aux limitations de la version de démonstration, mais représente un risque de sécurité en contexte réel.

## Livrables
- Cas de test Login & Logout
- Rapport de bugs
- Test Summary Report
- User Stories et critères d’acceptation

## Conclusion
Ce projet m’a permis de consolider mes compétences en test logiciel manuel, en appliquant une démarche complète :
analyse des exigences → conception des tests → exécution → bug reporting → reporting final.

Il constitue une base solide pour évoluer vers des projets de test plus complexes et, à terme, vers l’automatisation des tests.

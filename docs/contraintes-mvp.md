# 🚧 Contraintes du MVP — XARAÑ

## Périmètre du MVP

### Inclus (IN)
- Catalogue de 3 à 5 modules courts (marketing digital + bureautique)
- Assistant IA vocal bilingue wolof / français, en pédagogie « indices d'abord »
- Affichage systématique de la transcription avant envoi
- Exercices pratiques + une mini-évaluation par module
- Suivi de progression simple
- Authentification basique + interface mobile-first

### Exclu (OUT — versions futures)
- Mode hors-ligne complet
- Paiement intégré / abonnement Premium
- Modules de code avancés
- Communauté et messagerie entre apprenants
- Attestations vérifiables / certification officielle
- Tableau de bord coach avancé

## Contraintes

| Type | Contrainte | Impact / arbitrage |
| --- | --- | --- |
| Technique | Compréhension vocale wolof imparfaite | Toujours afficher la transcription + reformulation en français clair |
| Technique | Données mobiles limitées des apprenants | Leçons légères, audio compressé, pas de vidéo lourde au MVP |
| Temps | Sprint court (quelques semaines) | Limiter à 3–5 modules et 1 domaine principal |
| Budget | Coût des appels au modèle IA | Minimiser les données envoyées, mode dégradé non génératif prévu |
| Équipe | Petite équipe étudiante | Prioriser le no-code (Lovable) + Dify pour les agents |
| Données | Confidentialité des apprenants | Collecte minimale, séparation données / couche IA |

## Risque principal du MVP
La **qualité de la compréhension vocale en wolof / français** : si elle est insuffisante, toute la proposition de valeur s'effondre. C'est l'hypothèse n°1 à valider (voir `hypotheses-validation.md`).

---

GET409 — Swiss UMEF University — Campus de Dakar — Juin 2026

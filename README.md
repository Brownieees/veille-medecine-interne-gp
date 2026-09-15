# Veille Médecine Interne

Veille bibliographique hebdomadaire automatisée, destinée à un médecin interniste français.

Chaque semaine, ce dépôt produit une synthèse des publications récentes en médecine interne (essais cliniques, revues, recommandations), avec une section dédiée à la médecine générale et à la pharmacovigilance (ANSM) présentée en complément, pour la culture générale.

## Contenu

- **`reports/`** — archive de tous les rapports hebdomadaires, un fichier par édition, nommé `AAAA-MM-JJ.md` (date de publication).
- **`site/index.html`** — page web présentant la dernière édition du rapport, mise à jour à chaque exécution.
- **`SITE_URL.txt`** — contient l'URL de la page publiée (dernière édition en ligne).
- **`PROTOCOL.md`** — protocole exact suivi pour la recherche, la vérification des sources et la rédaction de chaque rapport.

## Fonctionnement

Une tâche planifiée exécute la veille chaque semaine : recherche PubMed sur les grandes revues de médecine interne, recherche web sur les sites institutionnels français (HAS, ANSM, SNFMI), rédaction du rapport, archivage dans `reports/`, mise à jour et publication de `site/index.html`, puis envoi d'une notification par e-mail.

La dernière édition est toujours consultable en ligne à l'adresse indiquée dans `SITE_URL.txt`.

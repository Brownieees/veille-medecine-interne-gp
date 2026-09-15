# Protocole de veille bibliographique

## Périmètre de recherche

### Recherche PubMed (prioritaire)

Recherche PubMed, avec une priorité donnée aux revues suivantes :

- New England Journal of Medicine (NEJM)
- The Lancet
- JAMA
- JAMA Internal Medicine
- BMJ
- Annals of Internal Medicine
- European Journal of Internal Medicine
- Mayo Clinic Proceedings

### Recherche web (institutionnel français)

Recherche web ciblée sur les sites suivants, en utilisant la recherche web puis en récupérant et lisant le contenu réel des pages (jamais seulement les extraits de résultats de recherche) :

- has-sante.fr (Haute Autorité de Santé — recommandations)
- ansm.sante.fr (Agence nationale de sécurité du médicament — pharmacovigilance, alertes, retraits)
- snfmi.org (Société Nationale Française de Médecine Interne)

## Règles de rigueur

- Ne jamais inventer un résultat, une étude, un chiffre ou une recommandation.
- Chaque affirmation du rapport doit être traçable à une source réelle et vérifiée : lien PMID/DOI pour un article PubMed, ou URL fonctionnelle pour une page web.
- Si une catégorie n'a rien de solide à rapporter sur la période couverte, le dire explicitement plutôt que de remplir avec du contenu marginal ou hors sujet. La qualité prime sur la quantité.
- La période de recherche couvre la date du dernier rapport archivé (moins 2 à 3 jours de marge, pour couvrir les délais d'indexation), jusqu'à la date du jour. En l'absence de rapport antérieur, la période couvre les 14 derniers jours.

## Structure de chaque rapport

Chaque rapport (`reports/AAAA-MM-JJ.md`) suit exactement cet ordre de sections :

1. **À ne pas manquer** — la sélection la plus importante de la semaine, tous domaines confondus.
2. **Médecine interne** — section prioritaire, la plus développée : essais cliniques, revues, articles marquants issus des revues listées ci-dessus.
3. **Recommandations HAS** — nouvelles recommandations ou mises à jour publiées par la Haute Autorité de Santé.
4. **Médecine générale & Pharmacovigilance/ANSM** — traitement bref, en fin de rapport, pour la culture générale : alertes de pharmacovigilance, retraits de lots, actualités ANSM, et actualités de médecine générale pertinentes.
5. **Notes méthodologiques** — période couverte, sources consultées, limites de la recherche de la semaine.

## Publication

À chaque exécution, `site/index.html` est mis à jour avec le contenu du dernier rapport et republié à la même URL (voir `SITE_URL.txt`), en conservant le même système de design.

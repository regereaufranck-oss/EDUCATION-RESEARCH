# Catalogue documentaire — registre des contenus

**Rôle :** point d'entrée central pour retrouver les documents **effectivement présents** dans EDUCATION-RESEARCH. L'[architecture](architecture.md) définit où ranger ; ce catalogue recense ce qui existe. Les fiches restent dans leur dossier canonique, **sans copie** ici.

**Dernière réconciliation manuelle :** 2026-10-08. Ce fichier est un index maintenu lors des changements ; il ne se synchronise pas automatiquement avec GitHub.

## Documents de recherche présents

| Identifiant | Document | Nature | État |
|---|---|---|---|
| RR-001-BIB | [Bibliographie RR-001](../recherches/RR-001/BIBLIOGRAPHIE.md) | Références et limites | NEEDS_REVISION |
| RR-001-CAND | [Sept fiches candidates RR-001](../recherches/RR-001/FICHES-CANDIDATES.md) | Archive de capitalisation, non canonique | NEEDS_REVISION |

Les identifiants **NUM-01 à NUM-06** et **PED-01** sont actuellement des sections du document RR-001-CAND, **pas sept fichiers indépendants**. Aucune fiche canonique validée n'est enregistrée dans ce catalogue.

## Entrées par famille

- [CONNAISSANCES](../CONNAISSANCES/README.md) — fiches canoniques : aucune validée recensée.
- [PEDAGOGIE](../PEDAGOGIE/README.md) — approches, médiation, stratégies, remédiations : aucune validée recensée.
- [EVALUATIONS](../EVALUATIONS/README.md) — méthodes et outils : aucune fiche validée recensée.
- [SOURCES](../SOURCES/README.md) — notices canoniques de sources : aucune recensée ; bibliographie provisoire dans RR-001.
- [RESSOURCES](../RESSOURCES/README.md) — notices d'outils et supports : aucune recensée.
- [SYNTHESES](../SYNTHESES/README.md) — aucune synthèse canonique recensée.
- [NAVIGATION](../NAVIGATION/README.md) — index thématiques et multi-entrées.

## Documents de gouvernance documentaire

- [Architecture](architecture.md)
- [Modèle de fiche](modele-fiche.md)
- [Relations](relations.md)
- [Statuts et révisions](statuts-et-revisions.md)
- [Preuves et sources](preuves-et-sources.md)
- [Publication et confidentialité](publication.md)

## Contrat de mise à jour à chaque ajout ou modification

1. **Rechercher l'existant** par identifiant, titre, synonymes et domaine ; choisir CREATE, ENRICH, REFINE, CORRECT, CHALLENGE, LINK ou NO_CHANGE.
2. **Placer ou modifier un seul fichier canonique** dans la famille compétente ; conserver son identifiant stable. Les archives de recherche restent distinctes.
3. **Mettre à jour ce catalogue dans la même opération de publication** : identifiant, titre, lien relatif, type, domaine, niveaux, état documentaire, date de contrôle et source de provenance si applicable.
4. **Actualiser les index concernés** dans NAVIGATION et les liens de relations ; vérifier les chemins relatifs.
5. **Contrôler** absence de doublon, source, statut de preuve, confidentialité, droits et liens cassés. Noter tout échec de mise à jour : ne pas annoncer une indexation complète si elle a échoué.
6. **Respecter l'autorisation explicite d'écriture GitHub** : ce contrat s'applique lorsqu'une publication est demandée ou autorisée, et n'accorde aucune permission permanente de commit.

## Entrée type (pour une future fiche)

`ID | titre | lien canonique | type | domaine | niveau | maturité documentaire | date de vérification | source/étude | relations`

Les champs inconnus restent `UNKNOWN`. L'index peut être scindé par famille lorsqu'il grandira, tout en gardant ici les pointeurs vers les index détaillés.

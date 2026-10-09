# École thématique #2 — Métabolomique & Santé Humaine

**RFMF × SFBC · 5–9 octobre 2026 · Centre CNRS Paul-Langevin, Aussois**

Ce dépôt centralise le matériel pédagogique de l'école : présentations,
tutoriels, scripts et jeux de données des ateliers.

🌐 Site de l'école : <https://2-et-rfmf-2026.sciencesconf.org>

---

## À propos

L'école parcourt les étapes d'une étude de métabolomique appliquée à la santé
humaine, du design expérimental et de la collecte d'échantillons jusqu'à
l'analyse et l'intégration des données.

**Objectifs pédagogiques**

- Choisir les matrices, la préparation d'échantillons et les stratégies
  analytiques adaptées à la clinique.
- Mettre en place une assurance qualité compatible avec des études
  longitudinales et multicentriques.
- Renforcer l'annotation par MS et RMN, les réseaux moléculaires et le contexte
  biologique.
- Intégrer des données multiomiques / multiblocs et explorer l'apport des grands
  modèles de langage.
- Structurer les données selon les principes FAIR, ontologies et vocabulaires
  contrôlés.

---

## Organisation du dépôt

```
.
├── J1_lundi_metabolomique-clinique/
├── J2_mardi_methodologie-qualite/
├── J3_mercredi_annotation/
│   ├── MS/
│   │   ├── 20261007_mzmine/
│   │   └── 2026-10-07_DavidTouboul_MetGem/
│   └── RMN/
├── J4_jeudi_donnees-IA/
│   └── 2026-10-07_FlorenceMehl_Multiblock/
├── J5_vendredi_contextualisation/
├── LICENSE.md
└── README.md
```

---

## Programme et matériel

### Jour 1 · Lundi 05/10 — Introduction à la métabolomique clinique

| Horaire | Session | Intervenant·e | Matériel |
| --- | --- | --- | --- |
| 17:00 | Mot d'ouverture | A. Le Gouellec | [Slides d'accueil (PPTX)](J1_lundi_metabolomique-clinique/2026-10-06_LeGouellec_Slide_Accueil_Ecole_thematique_Aussois.pptx) |
| 17:15 | La métabolomique clinique à l'hôpital : point de vue d'un biologiste médical | G. Grzych | *à venir* |
| 18:00 | La métabolomique clinique : point de vue de l'industrie | A. Limonciel | [Présentation (PDF)](J1_lundi_metabolomique-clinique/2026-10-06_AliceLimonciel_Clinical_metabolomics_Industry_point_of_view.pdf) |
| 18:45 | Construire un projet de recherche clinique : réglementation et gestion des données | P. Audouin | [Présentation (PDF)](J1_lundi_metabolomique-clinique/2026-10-06_PierreAudouin_reglementaire.pdf) |

### Jour 2 · Mardi 06/10 — Défis méthodologiques et assurance qualité

| Horaire | Session | Intervenant·e | Matériel |
| --- | --- | --- | --- |
| 08:30 | Échantillons cliniques et couverture du métabolome : choix et compromis | J. Bertrand-Michel | [Présentation (PDF)](J2_mardi_methodologie-qualite/2026-10-06_JustineBertrand-Michel.pdf) |
| 09:15 | La RMN a-t-elle encore une place en métabolomique clinique ? | P. de Tullio | [Présentation (PDF)](J3_mercredi_annotation/RMN/20261007_PascaldeTullio_introRMN.pdf) |
| 10:15 | De la préparation des échantillons à la confiance clinique : qualité et harmonisation | V. González-Ruiz | [Présentation (PDF)](J2_mardi_methodologie-qualite/2026-10-06_VGR_qualite_harmonisation.pdf) |
| 11:15 | Table ronde : études multicentriques | J.-C. Martin (mod.), J. Bertrand-Michel, R. Thuillier, A. Limonciel | [Présentation (PPTX)](J2_mardi_methodologie-qualite/2026-10-06_jcmartin_metaboring.pptx) |
| 14:00 | Présentations flash des participant·es | Tous | — |
| 17:15 | Études longitudinales et stabilité des échantillons | E. Salanon | [Présentation (PDF)](J2_mardi_methodologie-qualite/2026-10-06_ElfriedSalanon_Etudes_longitudinales_stabilite.pdf) |

### Jour 3 · Mercredi 07/10 — Annotation et réseaux moléculaires (sessions parallèles)

**Session MS**

| Horaire | Session | Intervenant·e | Matériel |
| --- | --- | --- | --- |
| 09:15 | MZmine : cours théorique | A. Rutz | [Cours (PDF)](J3_mercredi_annotation/MS/20261007_mzmine/20261007_aussois-mzmine-theorie.pdf) |
| 10:45 | MZmine : atelier pratique | A. Rutz | [Atelier (PDF)](J3_mercredi_annotation/MS/20261007_mzmine/20261007_aussois-mzmine-pratique.pdf) |
| 13:30 | MetGem : réseaux moléculaires et propagation de l'annotation | D. Touboul | *[Cours (PDF)](J3_mercredi_annotation/MS/2026-10-07_DavidTouboul_MetGem/cours_MetGem_2026.pdf)* |
| 15:15 | MetGem : atelier pratique | D. Touboul | [Dossier de l'atelier](J3_mercredi_annotation/MS/2026-10-07_DavidTouboul_MetGem/) — données : [MSV000080502_MetGem.mgf](J3_mercredi_annotation/MS/2026-10-07_DavidTouboul_MetGem/MSV000080502_MetGem.mgf), [MSV000080502_MetGem_quant.csv](J3_mercredi_annotation/MS/2026-10-07_DavidTouboul_MetGem/MSV000080502_MetGem_quant.csv), [PHENOLICSDB.mgf](J3_mercredi_annotation/MS/2026-10-07_DavidTouboul_MetGem/PHENOLICSDB.mgf) |
| 16:30 | Annotation : importance du contexte | A. Rutz | [Présentation (PDF)](J3_mercredi_annotation/MS/20261007_aussois-annotations-contextualisation.pdf) |

**Session RMN**

| Horaire | Session | Intervenant·e | Matériel |
| --- | --- | --- | --- |
| 09:15 | Bonnes pratiques d'échantillonnage et de préparation des échantillons | G. Bertho | [Présentation (PDF)](J3_mercredi_annotation/RMN/2026-10-07_GildasBertho.pdf) |
| 10:45 | Traitement des données RMN : des spectres aux métabolites | C. Goossens | [Présentation (PDF)](J3_mercredi_annotation/RMN/2026-10-07_CorentineGoossens_NMRprocessing.pdf) |
| 13:30 | RMN bidimensionnelle en métabolomique clinique | M. Letertre & P. de Tullio | [Présentation (PDF)](J4_jeudi_donnees-IA/2026-10-08_MarineLetertre_Two-dimensional_NMR_in_clinical.pdf) |
| 15:15 | Quantification par RMN en métabolomique clinique | C. Goossens & G. Bertho | [Présentation (PDF)](J3_mercredi_annotation/RMN/2026-10-07_GildasBertho_CorentineGoossens.pdf) |
| 16:30 | RMN et MS : approches complémentaires en multiomique | M. Letertre | [Présentation (PDF)](J3_mercredi_annotation/RMN/2026-10-07_MarineLetertre_NMRandMS.pdf) |

**Session commune**

| Horaire | Session | Intervenant·e | Matériel |
| --- | --- | --- | --- |
| 17:15 | Étude de cas en métabolomique et santé humaine | F. Fauvelle | [Présentation (PDF)](J3_mercredi_annotation/2026-10-07_FlorenceFauvelle_CaseStudy.pdf) |

### Jour 4 · Jeudi 08/10 — Exploration des données, analyses multivariées et IA

| Horaire | Session | Intervenant·e | Matériel |
| --- | --- | --- | --- |
| 09:00 | Découverte à partir des dépôts de données : PAN-REPO, MASST, MicrobeMASST | V. Charron-Lamoureux | [Présentation (PDF)](J4_jeudi_donnees-IA/Aussois_talk_final_Vincent_discovery.pdf) |
| 11:15 | Intégration de données multiomiques / multiblocs : atelier pratique | F. Mehl | Voir [matériel multiblocs](#matériel-de-latelier-multiblocs) ci-dessous |
| 14:00 | Intégration multiomique / multiblocs : suite | F. Mehl | Voir [matériel multiblocs](#matériel-de-latelier-multiblocs) ci-dessous |
| 15:30 | Atelier LLM : grands modèles de langage en métabolomique | Animé par R. Thuillier | *[Comptes rendus de l'atelier](J4_jeudi_donnees-IA/Atelier_LLM/)* |

#### Matériel de l'atelier multiblocs

Dossier : [`J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/`](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/)

| Type | Fichier |
| --- | --- |
| Cours | [ET02_RFMF_2026_cours_FM.pdf](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/ET02_RFMF_2026_cours_FM.pdf) |
| Consignes des TP | [Practicals.pdf](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/Practicals.pdf) |
| Liens utiles | [Liens_utiles.pdf](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/Liens_utiles.pdf) |
| Installation des packages R | [packages_installation.R](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/packages_installation.R) |
| TP non supervisé | [unsupervised_multiblock_analyses.Rmd](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/unsupervised_multiblock_analyses.Rmd) — correction : [Rmd](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/unsupervised_multiblock_analyses_correction.Rmd) · [HTML](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/unsupervised_multiblock_analyses_correction.html) |
| TP supervisé | [supervised_multiblock_analyses.Rmd](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/supervised_multiblock_analyses.Rmd) — correction : [Rmd](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/supervised_multiblock_analyses_correction.Rmd) · [HTML](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/supervised_multiblock_analyses_correction.html) |

### Jour 5 · Vendredi 09/10 — Contextualisation

| Horaire | Session | Intervenant·e | Matériel |
| --- | --- | --- | --- |
| 09:00 | Contextualisation biologique des données analytiques | J.-C. Martin | *[Présentation (PDF)](J5_vendredi_contextualisation/2026-10-09_JCMartin_contextualisation.pdf)* |
| 10:30 | Ontologies et vocabulaire contrôlé pour des données FAIR et adaptées à l'IA | M. Weber | [Présentation (PDF)](J5_vendredi_contextualisation/2026-10-08_MagalieWeber_FAIR_ontologies.pdf) |
| 11:45 | Bilan de la semaine | A. Le Gouellec | — |

---

## Logiciels pour les ateliers

- **MZmine** — <https://mzmine.github.io/> (vérifier la version demandée dans
  les consignes de l'intervenant)
- **MetGem** — <https://metgem.github.io/>
- **R / RStudio** pour l'atelier multiblocs — packages à installer avec
  [packages_installation.R](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock/packages_installation.R)

---

## Licence et réutilisation

Le dépôt est placé sous licence [Creative Commons Attribution 4.0
International](LICENSE.md), sauf mention contraire. Les supports restent la
propriété de leurs auteur·es : merci de les citer en cas de réutilisation.

---

## Organisation

**Portage scientifique** : [RFMF](https://www.rfmf.fr/) — Réseau Francophone
de Métabolomique et Fluxomique · [SFBC](https://www.sfbc-asso.fr/) — Société
Française de Biologie Clinique

**Soutien** : CNRS

**Coordination scientifique** : Audrey Le Gouellec

**Comité d'organisation** : Audrey Le Gouellec, Justine Bertrand-Michel, Pascal
de Tullio, Gildas Bertho, Jeremy Monteiro, Raphaël Thuillier, Marie Lenski,
Jean-Charles Martin, Ghina Hajjar, Delphine Debayle, Sophie Ayciriex, Florence
Mehl

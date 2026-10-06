# École thématique #2 --- Métabolomique & Santé Humaine

**RFMF × SFBC · 5--9 octobre 2026 · Centre CNRS Paul-Langevin, Aussois**

Ce dépôt centralise le matériel pédagogique de l'école : présentations,
tutorials, scripts et jeux de données des ateliers.

🌐 Site de l'école : <https://2-et-rfmf-2026.sciencesconf.org>

--------------------------------------------------------------------------------

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

--------------------------------------------------------------------------------

## Organisation du dépôt

```
.
├── J1_lundi_metabolomique-clinique/
├── J2_mardi_methodologie-qualite/
├── J3_mercredi_annotation/
│   ├── MS/
│   └── RMN/
├── J4_jeudi_donnees-IA/
├── J5_vendredi_FAIR-ontologies/
└── README.md
```

Chaque session a son sous-dossier (`AAAA-MM-JJ_NomIntervenant_titre-court/`)
contenant les supports (PDF) et, pour les ateliers, un `README.md` avec les
instructions, les scripts et les liens vers les données.

--------------------------------------------------------------------------------

## Programme et matériel

### Jour 1 · Lundi 05/10 --- Introduction à la métabolomique clinique

  | Horaire | Session                                                                              | Intervenant·e  | Matériel  |
  | ---     | ---                                                                                  | ---            | ---       |
  | 17:00   | Mot d'ouverture                                                                      | A. Le Gouellec | —         |
  | 17:15   | La métabolomique clinique à l'hôpital : point de vue d'un biologiste médical         | G. Grzych      | *à venir* |
  | 18:00   | La métabolomique clinique : point de vue de l'industrie                              | A. Limonciel   | *à venir* |
  | 18:45   | Construire un projet de recherche clinique : réglementation et gestion des données   | P. Audoin      | *à venir* |

### Jour 2 · Mardi 06/10 --- Défis méthodologiques et assurance qualité

  | Horaire | Session                                                                               | Intervenant·e                                                       | Matériel  |
  | ---     | ---                                                                                   | ---                                                                 | ---       |
  | 08:30   | Échantillons cliniques et couverture du métabolome : choix et compromis               | J. Bertrand-Michel                                                  | *[2026-10-06_JustineBertrand-Michel](J2_mardi_methodologie-qualite/2026-10-06_JustineBertrand-Michel.pdf)* |
  | 09:15   | La RMN a-t-elle encore une place en métabolomique clinique ?                          | P. de Tullio                                                        | *à venir* |
  | 10:15   | De la préparation des échantillons à la confiance clinique : qualité et harmonisation | V. González-Ruiz                                                    | *à venir* |
  | 11:15   | Table ronde : études multicentriques                                                  | J.-C. Martin (mod.), J. Bertrand-Michel, R. Thuillier, A. Limonciel | —         |
  | 14:00   | Présentations flash des participant·es                                                | Tous                                                                | —         |
  | 17:15   | Études longitudinales et stabilité des échantillons                                   | E. Salanon                                                          | *à venir* |

### Jour 3 · Mercredi 07/10 --- Annotation et réseaux moléculaires (sessions parallèles)

**Session MS**

  | Horaire | Session                                                       | Intervenant·e | Matériel  |
  | ---     | ---                                                           | ---           | ---       |
  | 09:15   | MZmine : cours théorique                                      | A. Rutz       | *à venir* |
  | 10:45   | MZmine : atelier pratique                                     | A. Rutz       | *à venir* |
  | 13:30   | MetGem : réseaux moléculaires et propagation de l'annotation  | D. Touboul    | *à venir* |
  | 15:15   | MetGem : atelier pratique                                     | D. Touboul    | *[2026-10-07_DavidTouboul_MetGem](J3_mercredi_annotation/MS/2026-10-07_DavidTouboul_MetGem)* |
  | 16:30   | Annotation : importance du contexte                           | A. Rutz       | *à venir* |

**Session RMN**

  | Horaire | Session                                                                | Intervenant·e              | Matériel  |
  | ---     | ---                                                                    | ---                        | ---       |
  | 09:15   | Bonnes pratiques d'échantillonnage et de préparation des échantillons  | G. Bertho                  | *à venir* |
  | 10:45   | Traitement des données RMN : des spectres aux métabolites              | C. Goossens                | *à venir* |
  | 13:30   | RMN bidimensionnelle en métabolomique clinique                         | M. Letertre & P. de Tullio | *à venir* |
  | 15:15   | Quantification par RMN en métabolomique clinique                       | C. Goossens & G. Bertho    | *à venir* |
  | 16:30   | RMN et MS : approches complémentaires en multiomique                   | M. Letertre                | *à venir* |

**Session commune**

  | Horaire | Session                                        | Intervenant·e | Matériel  |
  | ---     | ---                                            | ---           | ---       |
  | 17:15   | Étude de cas en métabolomique et santé humaine | F. Fauvelle   | *à venir* |

### Jour 4 · Jeudi 08/10 --- Exploration des données, analyses multivariées et IA

  | Horaire | Session                                                                    | Intervenant·e          | Matériel  |
  | ---     | ---                                                                        | ---                    | ---       |
  | 09:00   | Découverte à partir des dépôts de données : PAN-REPO, MASST, MicrobeMASST  | V. Charron-Lamoureux   | *à venir* |
  | 11:15   | Intégration de données multiomiques / multiblocs : atelier pratique        | F. Mehl                | *[2026-10-07_FlorenceMehl_Multiblock](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock)* |
  | 14:00   | Intégration multiomique / multiblocs : suite                               | F. Mehl                | *[2026-10-07_FlorenceMehl_Multiblock](J4_jeudi_donnees-IA/2026-10-07_FlorenceMehl_Multiblock)* |
  | 15:30   | Atelier LLM : grands modèles de langage en métabolomique                   | Animé par R. Thuillier | *à venir* |

### Jour 5 · Vendredi 09/10 --- Ontologies et données FAIR

  | Horaire | Session                                                                     | Intervenant·e  | Matériel  |
  | ---     | ---                                                                         | ---            | ---       |
  | 09:00   | Contextualisation biologique des données analytiques                        | J.-C. Martin   | *à venir* |
  | 10:30   | Ontologies et vocabulaire contrôlé pour des données FAIR et adaptées à l'IA | M. Weber       | *à venir* |
  | 11:45   | Bilan de la semaine                                                         | A. Le Gouellec | —         |

--------------------------------------------------------------------------------

## Logiciels pour les ateliers

À installer **avant** l'école :

- **MZmine** --- <https://mzmine.github.io/> (vérifier la version demandée dans
  les consignes de l'intervenant)
- **MetGem** --- <https://metgem.github.io/>

Les jeux de données des ateliers sont distribués via RENATER FileSender (lien
transmis par e-mail aux participant·es).

--------------------------------------------------------------------------------

## Pour les intervenant·es : déposer votre matériel

1. Placez vos fichiers dans le dossier du jour correspondant (PDF de préférence
   pour les présentations).
2. Pour un atelier, ajoutez un `README.md` décrivant les prérequis, les étapes
   et l'origine des données.
3. Remplacez *à venir* dans le tableau ci-dessus par le lien vers votre dossier
   ou fichier.
4. Évitez les fichiers volumineux (> 50 Mo) : préférez un lien vers Zenodo ou un
   autre dépôt.

Vous pouvez aussi envoyer vos fichiers au comité d'organisation, qui les
ajoutera pour vous.

--------------------------------------------------------------------------------

## Licence et réutilisation

Sauf mention contraire, les supports restent la propriété de leurs auteur·es.
Merci de les citer en cas de réutilisation et de vérifier la licence indiquée
dans chaque dossier.

--------------------------------------------------------------------------------

## Organisation

**Portage scientifique** : [RFMF](https://www.rfmf.fr/) --- Réseau Francophone
de Métabolomique et Fluxomique · [SFBC](https://www.sfbc-asso.fr/) --- Société
Française de Biologie Clinique

**Soutien** : CNRS · [CAES du CNRS --- Centre
Paul-Langevin](https://www.caes.cnrs.fr/sejours/centre-paul-langevin-3-2/)

**Coordination scientifique** : Audrey Le Gouellec

**Comité d'organisation** : Audrey Le Gouellec, Justine Bertrand-Michel, Pascal
de Tullio, Gildas Bertho, Jeremy Monteiro, Raphaël Thuillier, Marie Lenski,
Jean-Charles Martin, Ghina Hajjar, Delphine Debayle, Sophie Ayciriex, Florence
Mehl

# Widget treegrid_widget

**Nom :** treegrid_widget.xhtml

**Bean(s) associé(s) :** TreegridActionsBean

**Rôle :** Affiche un composant de type treegrid

Ce widget peut être associé aux champs :
* vrp:components (vReceipe)
* tout autre champ de schéma dont la structure est strictement identique à vrp:components

## Propriétés possibles dans Studio :

| Nom                               | Valeur par défaut | Description                                                                                                           |
| --------------------------------- | ----------------- | --------------------------------------------------------------------------------------------------------------------- |
| **phaseVocabulary**               | `PhaseVoc`        |                                                                                                                       |
| **tagVoc**                        | `vReceipeTagVoc`  | Indique le vocabulaire à utiliser pour la colonne Tag.                                                                |
| **geographicalOrigVocabulary**    | `GeoVoc`          | Vocabulaire des origines géograhiques                                                                                 |
| **subGeographicalOrigVocabulary** | `SubGeoVoc`       | Sous-vocabulaire des origines géograhiques                                                                            |
| **varietyOrigVocabulary**         | `RMOrigin`        | Vocabulaire des origines variétales                                                                                   |
| **subVarietyOrigVocabulary**      | `RMSubOrigin`     | Sous-vocabulaire des origines variétales                                                                              |
| **etiquetVoc**                    | `EtiquetVoc`      | Vocabulaire d’étiquetage                                                                                              |
| **paramVoc**                      | `paramVoc`        | Vocabulaire des paramètres de pourcentage                                                                             |
| **unitVoc**                       | `unit`            | Vocabulaire des unités                                                                                                |
| **unite**                         | `g`               | Unité par défaut                                                                                                      |
| **enableSaveAndStay**             | `false`           | Active la possiblité d’enregistrer son travail dans le treegrid par la touche `<F8>` sans cliquer sur `<enregistrer>` |
| **costPattern**                   | `0.####`          | Pattern d’affichage des coût/montants                                                                                 |
| **pricePattern**                  | `0.00##`          | Pattern d’affichage des prix                                                                                          |
| **quantityPattern**               | `0.###`           | Pattern d’affichage des quantités                                                                                     |
| **coeffPattern**                  | `0.00`            | Pattern d’affichage des coefficients                                                                                  |
| **percentagePattern**             | `0.##\\%`         | Pattern d’affichage des pourcentages                                                                                  |
| **canEditLeafYield**              | `false`           | Autoriser la saisie des rendements sur les lignes "non phases" = "feuilles"                                           |
| **showTag**                       | `false`           | Si true, la colonne Tag s’affichera.                                                                                  |
| **showGeographicalOrig**          | `true`            | Affichage de la colonne "Origine géo"                                                                                 |
| **showVarietyOrig**               | `true`            | Affichage de la colonne "Origine variétale"                                                                           |
| **showPhase**                     | `true`            | Affichage de la colonne "Phase"                                                                                       |
| **showEtiquetage**                | `true`            | Affichage de la colonne "Etiquetage"                                                                                  |
| **showParametragePourcentage**    | `true`            | Affichage de la colonne "Parametrage pourcentage"                                                                     |
| **showUnite**                     | `true`            | Affichage de la colonne "Unite"                                                                                       |
| **showCoutParPhase**              | `true`            | Affichage de la colonne "Coût par phase"                                                                              |
| **showCoutParPhaseParKg**         | `true`            | Affichage de la colonne "Coût par phase par kg"                                                                       |
| **showCoutRecette**               | `true`            | Affichage de la colonne "Coût recette"                                                                                |
| **showCoutRecetteParKg**          | `true`            | Affichage de la colonne "Coût recette par kg"                                                                         |
| **showPrixKgImpConvertie**        | `true`            | Affichage de la colonne "PrixKgImpConvertie"                                                                          |
| **showPrixKgForce**               | `true`            | Affichage de la colonne "PrixKgForce"                                                                                 |
| **showQuantite**                  | `true`            | Affichage de la colonne "Quantite"                                                                                    |
| **showQuantiteConvertie**         | `true`            | Affichage de la colonne "Quantite convertie"                                                                          |
| **showQuantitePF**                | `true`            | Affichage de la colonne "Quantite PF"                                                                                 |
| **showQuantitePFSimulation**      | `true`            | Affichage de la colonne "Quantité souhaitée"                                                                          |
| **showQuantitePFSimulee**         | `true`            | Affichage de la colonne "Quantité calculée"                                                                           |
| **showPoidsBrutPhase**            | `true`            | Affichage de la colonne "Poids brut phase"                                                                            |
| **showPoidsBrutPF**               | `true`            | Affichage de la colonne "Poids brut PF"                                                                               |
| **showQuantiteMiseEnOeuvre**      | `true`            | Affichage de la colonne "Quantité MEO"                                                                                |
| **showQuantiteMiseEnOeuvrePhase** | `true`            | Affichage de la colonne "Quantité MEO par phase"                                                                      |
| **showPPhase**                    | `true`            | Affichage de la colonne "% Phase"                                                                                     |
| **showPTotal**                    | `true`            | Affichage de la colonne "% Total"                                                                                     |
| **showPPerteMP**                  | `true`            | Affichage de la colonne "% Perte MP"                                                                                  |
| **showPRdtPhase**                 | `true`            | Affichage de la colonne "% Rdt phase"                                                                                 |
| **showPFreinte**                  | `true`            | Affichage de la colonne "% Freinte"                                                                                   |
| **showYieldFactor**               | `false`           | Affichage de la colonne "Coefficient"                                                                                 |
| **showReference**                 | `false`           | Affichage de la colonne "Référence"                                                                                   |
| **showPBaker**                    | `false`           | Affichage de la colonne "% / référence"                                                                               |
| **showPPhasePdsBrut**             | `true`            | Affichage de la colonne "% Phase pds brut"                                                                            |
| **showPTotalPdsBrut**             | `true`            | Affichage de la colonne "% Total pds brut"                                                                            |
| **showPQuantiteMiseEnOeuvre**     | `true`            | Affichage de la colonne "% Quantité MEO"                                                                              |
| **showPCoutParPhase**             | `true`            | Affichage de la colonne "% Coût par phase"                                                                            |
| **showPCoutRecette**              | `true`            | Affichage de la colonne "% Coût recette"                                                                              |
| **showCadence**                   | `true`            | Affichage de la colonne "Cadence"                                                                                     |
| **showHeures**                    | `true`            | Affichage de la colonne "Heures"                                                                                      |
| **showDeclareOriginIngredient**   | `true`            | Affichage de la colonne "Déclarer origine"                                                                            |
| **showDeclareAllergens**          | `true`            | Affichage de la colonne "déclarer allergènes"                                                                         |
| **showFctTechno**                 | `true`            | Affichage de la colonne "Fonction technologique"                                                                      |
| **showRegroupement**              | `true`            | Affichage de la colonne "Regroupement"                                                                                |
| **showEquivalentA**               | `true`            | Affichage de la colonne "Équivalent à"                                                                                |
| **showSplitable**                 | `true`            | Affichage de la colonne "Éclatable"                                                                                   |
| **showCommentaire**               | `true`            | Affichage de la colonne "Commentaire"                                                                                 |
| **layoutFile**                    | `baseURL.concat(`<br>`treegridActionsBean.`<br>`generateTreegridLayout(`<br>`field_0, widget.mode`<br>`))` | Fichier définissant le layout du treegrid. Actuellement, on lui renvoie le fichier Def.xml                                                                                                                                 |


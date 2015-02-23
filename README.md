# Widget plim_unit_widget.xhtml

**Nom :** plim_unit_widget.xhtml

**Bean(s) associé(s) :** UnitVocAvtionsBean.java → "unitVocActions"

**Rôle :** Widget de sélection d’une unité

**Utilisation :** Sélection d’une unité dans un layout


## Propriétés possibles dans Studio :

| Nom              | Valeur par défaut | Description                                                                                                                                                  |
| ---------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **unitFamily**   |                   | La ou les famille(s) de l’unité à afficher dans le widget (ex : "weight" ou "length", etc.).<br>Si plusieurs familles, les séparer par une virgule (ex : "weight,length").<br>Si non renseignée, le widget permet de sélectionner toutes les unités quel que soit leur famille.<br><br>Liste des familles existantes :<br><ul><li>others</li><li>energy</li><li>length</li><li>piece</li><li>weight</li><li>surface</li><li>proportion</li><li>temperature</li><li>time</li><li>volume</li><li>microbiology</li><li>physicochemical</li><li>density</li></ul>     |
| **unitFamilies** |                   | *idem unitFamily*                                                                                                                                            |
| **units**        |                   | La ou les unité(s) à afficher dans le widget (ex : "cm" ou "g", etc.).<br>Si plusieurs unités, les séparer par une virgule (ex : "g,cm,kg").<br>Les unités renseignées doivent appartenir à une des familles renseignées dans “unitFamilies”.<br>Si non renseignée, le widget permet de sélectionner toutes les unités quel que soit leur famille.               |
| **required**     | `false`           | true si l'unité est requise                                                                                                                                  |

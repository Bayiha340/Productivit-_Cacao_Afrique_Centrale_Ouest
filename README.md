📊 Analyse de la productivité du cacao en Afrique subsaharienne
🌍 Contexte

Ce projet analyse la productivité du cacao en Afrique subsaharienne à travers trois pays majeurs : Cameroun, Côte d’Ivoire et Ghana. Les données proviennent de FAOSTAT et couvrent la période 2012-2022 (10 ans).
L’objectif est de comparer la productivité du cacao et de fournir des recommandations utiles aux décideurs pour renforcer la durabilité de la filière.

🎯 Objectif

Évaluer la production, le rendement et la superficie cultivée du cacao.

Identifier les forces et fragilités liées à la qualité des données.

Produire des recommandations stratégiques pour les décideurs africains.

⚠️ Limites

L’étude se concentre uniquement sur les données FAOSTAT, sans croisement avec d’autres bases. Cela implique un niveau d’incertitude qui a été évalué par des tests de sensibilité univariés.

🛠️ Méthodologie

Base de données : 99 observations et 15 variables initiales. Après nettoyage, 7 variables principales ont été retenues : Zone, Élément, Produit, Année, Unité, Description du symbole, Note.

Outils mobilisés :

MySQL → restructuration des données (segmentation des indicateurs et modélisation logique).

Python → analyses exploratoires, pondération et tests de sensibilité.

Analyse des données :

Pondération selon l’origine des données (officielles, estimées, imputées, internationales).

Réalisation de tests de sensibilité univariés pour évaluer la robustesse des résultats.

📈 Résultats clés

Production : la Côte d’Ivoire reste leader incontesté, suivie du Ghana et du Cameroun. Les résultats sont robustes, même en cas de forte incertitude.

Superficie récoltée : hiérarchie stable (Côte d’Ivoire > Ghana > Cameroun), mais forte incertitude sur la précision des chiffres.

Rendement : résultats fragiles et sensibles aux hypothèses. La hiérarchie entre pays n’est pas stable, les intervalles se chevauchant.

🌱 Recommandations

Renforcer les systèmes statistiques nationaux pour améliorer la fiabilité des données.

Réorienter la filière vers une intensification durable (agroforesterie) afin de réduire la pression foncière.

Intégrer systématiquement la pondération des données dans les comparaisons régionales pour mieux gérer l’incertitude.

📚 Références

Fountain, A. C., & Hütz-Adams, F. (2022). Cocoa Barometer 2022. VOICE Network. lien

ICCO (2023). Quarterly Bulletin of Cocoa Statistics & Monthly Cocoa Market Reports. lien

Briggs, A. H., Sculpher, M., & Buxton, M. J. (1994). Uncertainty in the economic evaluation of health care technologies: the role of sensitivity analysis. Health Policy and Planning, 9(4), 385–394.

# Optimisation de la gestion des données avec Python

En tant que data analyst freelance chez une marchand de vin très prestigieux, ma mission était d'optimiser la gestion des données avec Python. 
Pour gérer ses ressources and sa clientèle, mon client utilise un ERP qui n'est absolument pas relié à son site de vente en ligne. Les outils en 
place sont vraiment artisanaux 
et dans ces conditions, la gestion des stocks est vraiment complexe et sa visibilité en termes d’analyse des ventes sur le Net est vraiment 
réduite, car très peu de personnes ont accès au back-office. En attendant une solution plus centralisée, un rapprochement entre les 2 bases, 
même manuel, pourrait être très utile.

Ma mission était axée sur trois points:

Premièrement, j’avais besoin de rapprocher deux exports : un export de l’ERP contenant les références produit, leur prix de vente et leur état 
de stock, et un export d’une table de l’outil de CMS contenant les informations des produits commercialisés en ligne (nom, description, nombre 
de ventes...). L’export issu de la boutique en ligne contenait le nombre de ventes pour chaque produit depuis sa mise en ligne, il ne me permettais pas d’analyser l'évolution des ventes dans le temps.

En plus de ces 2 exports, j'ai pu me bénéficier d'un tableau Excel qui m'a permet d’établir le lien entre la référence du produit dans l’ERP (product_id) et la référence du même produit dans la base de la boutique en ligne (SKU). 

Deuxièmement, une fois le rapprochement effectué, j'ai analisé le chiffre d’affaires par produit, ainsi que le total du chiffre d’affaires réalisé en ligne.

Troisièmement et pour finir, j'ai dû vérifier s’il n’y avait pas eu des erreurs de saisie dans certains prix des produits. L'objectif ici c'était d'analiser des variables afin de détecter d’éventuelles valeurs aberrantes, de les lister et d’en faire une représentation graphique pour plus de lisibilité.

Mes résultats ont été présenté lors de la prochaine réunion de COPIL.

Ce projet a été proposé par ENSAE - Paris / OpenClassRooms dans le cadre de la formation Data Analysis

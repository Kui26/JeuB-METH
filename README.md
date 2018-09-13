# (B) Le pouvoir d’achat des ouvriers anglais du 16ème au 19ème siècle

William Playfair était un des pionniers de la présentation graphique des données. Il est notamment considéré comme l’inventeur de l’histogramme. Un de ses graphes célèbres, tiré de son livre ”A Letter on Our Agricultural Distresses, Their Causes and Remedies”, montre l’évolution du prix du blé et du salaire moyen entre 1565 et 1821. Playfair n’a pas publié les données numériques brutes qu’il a utilisées, car à son époque la réplicabilité n’était pas encore considérée comme essentielle. Des valeurs obtenues par numérisation du graphe sont aujourd’hui téléchargeables, la version en format CSV étant la plus pratique (https://raw.githubusercontent.com/vincentarelbundock/Rdatasets/master/csv/HistData/Wheat.csv).

Quelques remarques pour la compréhension des données:

   * Jusqu’en 1971, la livre sterling était divisée en 20 shillings, et un shilling en 12 pences.
   * Le prix du blé est donné en shillings pour un quart de boisseau de blé. Un quart de boisseau équivaut 15 livres britanniques ou 6,8 kg.
   * Les salaires sont donnés en shillings par semaine.
   
## Les missions

  1. Votre première tâche est de reproduire le graphe de Playfair à partir des données numériques. Représentez, comme Playfair, le prix du blé par des barres et les salaires par une surface bleue délimitée par une courbe rouge. Superposez les deux de la même façon dans un seul graphique. Le style de votre graphique pourra rester différent par rapport à l’original, mais l’impression globale devrait être la même.
  2. Par la suite, améliorez la présentation des ces données. Pour commencer, Playfair a combiné les deux quantités dans un même graphique en simplifiant les unités “shillings par quart de boisseau de blé” et “shillings par semaine” à un simple “shillings”, ce qui aujourd’hui n’est plus admissible. Utilisez deux ordonnées différentes, une à gauche et une à droite, et indiquez les unités correctes. À cette occasion, n’hésitez pas à proposer d’autres représentations que des barres et des surface/courbes pour les deux jeux de données si ceci vous paraît judicieux.
  3. L’objectif de Playfair était de montrer que le pouvoir d’achat des ouvriers avait augmenté au cours du temps. Essayez de mieux faire ressortir cette information. Pour cela, faites une représentation graphique du pouvoir d’achat au cours du temps, définie comme la quantité de blé qu’un ouvrier peut acheter avec son salaire hebdomadaire. Dans un autre graphique, montrez les deux quantités (prix du blé, salaire) sur deux axes différents, sans l’axe du temps. Trouvez une autre façon d’indiquer la progression du temps dans ce graphique. Quelle représentation des données vous paraît la plus claire ? N’hésitez pas à en proposer d’autres.

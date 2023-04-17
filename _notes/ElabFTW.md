---
title: 
subtitle:
author: Damien Belvèze
date: 26-11-2021
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: []
tags: [données_recherche]
---

[eLabFTW](https://datacc.elab.one/login.php)

objectif des cahiers numériques et en l'occurrence d'ElabFTW : 

-   Fournit une sauvegarde numérique.
-   Centralise les données, même s’il ne s’agit pas d’un espace de stockage ou d’archivage de ces dernières.
-   Permet de compiler les données (export en différents formats).
-   Est accessible à distance de façon sécurisée et participe ainsi à améliorer le suivi des manips et des projets ainsi que l’encadrement des équipes.
-   Facilite le travail collaboratif grâce au partage d’expériences, de modèles d’expériences et d’une base de données commune à l’équipe.
-   Intègre un moteur de recherche
-   Assure la traçabilité des expériences par l’authentification de chaque utilisateur et la datation des expériences à l’aide d’un horodatage certifié.



logiciel de [[cahiers numériques]] adapté à la chimie de synthèse, produit par un chercheur de l'institut Curie.
critères pour le choix d'une solution : 

le pour des petites institutions qui n'ont pas la masse critique pour négocier

autre solution libre (plus axé chimie, elab est plus générique) : [chemotion](https://pubchem.ncbi.nlm.nih.gov/source/1195)

# ElabFTW

page expérience : liste des expériences avec les noms des administrateurs de l'expérience.


éditeur de l'expérience
statut de l'expérience (à venir, en cours, terminée)
eLabView est un outil générique pas d'application métier.

[intallation d'ElabFTW à l'Université de Lorraine](https://factuel.univ-lorraine.fr/node/23166) 

Possibilité de lier des objets de la [[base de données]]. 
Dans la base de données, on peut créer une grande quantité de type d'objets
possibilité de joindre un fichier (image, graphique : spectre, jeu de données déjà traité)

- édition du code ([[R (logiciel)]])
- dupliquer 
- export PDF
- export en format zip de l'expérience
- partager des liens vers une vue
- horodatage de l'expérience : cela permet de clarifier les contributions de chaque auteur en cas de litige
- certifier avec la [[blockchain]]

pas de synchro avec [[R (logiciel)]], copier/coller le texte de R dans elabFTW
coloration syntaxique de R disponible dans la solution

La création de templates oblige les jeunes chercheurs à ne pas oublier de noter des aspects importants de l'expérience.
Ce qui prend du temps c'est de créer les premiers templates, après on peut les dupliquer facilement.

Q: Peut-on connecter ces [[cahiers numériques]] avec le [[Plan de gestion des données|Plan de gestion de données]] ? 
R: Cela n'est pas encore possible, mais on peut formaliser les choses dans le logiciel de telle sorte que leur export soit réutilisable directement ou le plus simplement possible dans le PGD
On ne peut pas importer dans cette solution le spectre (format pas disponible), passer le spectre en PNG. 



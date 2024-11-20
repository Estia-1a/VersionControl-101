---
title: "Web development Project"
---

# Project

## Context

### Rules :

- Team of 3/4
- The Guide can have several pages but should have one index file that serves at the entry point.
  https://estia-1a.github.io/VersionControl-101/evaluation.html#project-evaluation-criteria

## Pedagogical Objectives

- Learn by doing : Explore concepts and tools provided to you and try to use them in this project.
- Team based Project : Create and manage a small project as a team, use tools provided by github to help you.
- Learn about advanced concepts in git and github that help you manage your project.

## Subject

Create the website following the instructions on the [Developpement Web course](https://ingenieurs.estia.fr/course/view.php?id=762).

> Vous êtes ingénieur consultant dans la société internationale « Shinra ». Votre responsable vous confie, à vous et votre équipe, une mission pour un appel d’offre chez un client qui souhaite développer ses services dans plusieurs domaines. Pour cela, vous allez, en équipe, devoir proposer une version minimale d’un site web lié au secteur d’activité que vous avez choisi (entertainment, voyage, grande distribution, solidarité, ou culture). Si ces versions minimales sont satisfaisantes, alors votre société remportera l’appel d’offre, et votre équipe recevra une prime.
>
> Le client vous fournit les maquettes5 qu’il vous faut implémenter en HTML5 et CSS3. Le cahier des charges stipule clairement que la recette doit comprendre des sites web réactifs (responsive design) puisque le client testera les sites sur ordinateur mais aussi sur smartphone. De plus, toutes les pages HTML ainsi que les feuilles de style CSS doivent être valides6 selon le World Wide Web Consortium (W3C). Chaque site web devra comporter au minimum 2 pages pour avoir un aperçu de ce que vous proposez : une page d’accueil, et une page en rapport avec le panier et/ou sa validation. Pour le moment, vous êtes libre du contenu (e.g., offres et produits sur le site) et pouvez simplement simuler ce que le panier comportera. Enfin, pour faciliter la validation finale, votre proposition de site web devra être déployée via FTP sur un serveur distant afin d’être accessible en ligne via http://devweb.estia.fr/web1a/<equipe>/project. Répondre au cahier des charges et aux demandes du client est une condition nécessaire pour remporter le contrat (i.e., ne pas avoir F). Votre responsable vous informe qu’il a des attentes particulières en plus pour mettre toutes les chances de votre côté :
>
> - Tous les liens que vous mettez sur votre site doivent être fonctionnels. Les liens qui mèneraient à des pages web ou bien des éléments non inclus dans cette version minimale du > site doivent aller vers une page temporaire (avec HTML et CSS valides) indiquant « en cours de construction ».
> - De plus, votre responsable vous fait confiance pour que les pages web soient esthétiques avec un style professionnel.
> - Enfin, il faut que votre site web respecte les critères d’accessibilité selon les standards « Techniques and Failures for Web Content Accessibility Guidelines 2.0 » (WCAG 2.0)7 .
> - Votre responsable vous donne l’autorisation d’utiliser des librairies particulières. Le service informatique de votre entreprise vous fait part des habitudes de programmation > existantes en ce qui concerne les pages web, et qu’il faut respecter lors du déploiement du site :
> - Le code HTML doit exploiter une feuille de style séparée, et ne contenir directement aucune directive de style.
> - Votre site devrait considérer des valeurs d’éco-conception, et notamment « écoconception web : les 115 bonnes pratiques », en suivant les recommandations officielles listées sur GitHub https://github.com/cnumr/best-practices. Pour chaque recommandation suivie, le service informatique vous invite à compléter le fichier greenit.html (cf. Moodle) et le mettre à la racine de votre répertoire <equipe_name>/. Vous pouvez appliquer du style à ce fichier, mais en aucun cas modifier la structure de la table (id « main_table »), à part pour ajouter des lignes bien entendu

## Advice for this assignment

### Example of a Planning

This is a group project:

- You should have group activity, to manage your team, share your work, learn from the other...
- You should have individual activity: work on the html, css, the images... commit your work, pull the modifications from the other and push yours to github.
- Github has a lot of tools to help you manage your project, discover them quickly to use them in your project.

Here is an example of a planning you could follow during the first 4h of this project. Feel free to modify to better suit your needs.

| Time  | Activity                                                                                                                           |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------- |
| 5min  | Group Activity : Create team <br> Individual Activity : Follow the link on moodle to register your account on classroom.github.com |
| 15min | Group Activity : Organize your team                                                                                                |
| 15min | Individual Activity : Prepare your environment (VScode)                                                                            |
| 15min | Group Activity : Organize your team: Divide the work among the team members                                                        |
| 60min | Individual Activity : Work on your assigned page/style                                                                             |
| 15min | Group Activity : Push and Pull the modification, merge them                                                                        |
| 15min | Group Activity : Organize your team: Divide the remaining work among the team members, select a new strategy                       |
| 60min | Individual Activity : Work on your assigned page/style                                                                             |
| 15min | Group Activity : Push and Pull the modification, merge them                                                                        |
| 30min | Group Activity : Final Debriefing                                                                                                  |

### How to Start

1. Follow the link on moodle to create your team (find your name in the pdf file, create a new team or join an existing team)
2. All the group members clone the repository created for your team.
   ![](/ressources/clone_img.png)
3. One member of the group
   1. change the title of the website,
   2. save the index.html
   3. stage index.html
   4. commit ("feat: add the name of our site")
   5. push the commit to github.
4. All the other group members pull the modified HTML and check that the title has been changed.
5. All group members work on their assigned tasks: don't forget to commit regularly !
6. When a group member is satisfied with the work done and want to share with the other ones, they push their changes. During this step, you may have to manage conflicts. Check difference (diff) with master and merge. Check your course or call the teacher if there are any problems.

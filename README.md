# Rendu de <LOICOHT Alix>

Une capture par étape, dans l'ordre. Terminal entier non rogné, invite visible.
Afficher l'historique en graphe quand c'est pertinent.

## Niveau 1

J'ai rien à ajouter sur cette partie, les screens parle d'eux meme

1. Configuration Git
![image 1](./img/1.png)
![image 2](./img/2.png)

2. Branche de travail
![image 3](./img/3.png)

3. Historique des commits
![image 4](./img/4.png)
![image 5](./img/5.png)

4. Pull Request
![image 6](./img/6.png)

5. Revue croisée
![image 7](./img/7.png)

## Niveau 2

6. Secret retiré du suivi

Galere galere: j'ai commencer par revert mais ca na rien avoir mdr

![image 8](./img/8.png)

J'ai ensuite rebase -i sur le premier commit depuis main. Ce qui ma permis d'enlever les commit "oops"

![image 8](./img/9.png)

J'ai eu une galere avec la branche que j'ai créé mais j'ai reussi finalement a les enlever (j'ai rebase comme la branche principal)

![image 8](./img/10.png)

Et j'ai mis dans le gitignore "*.env" qui fait plaisir (comme ca il revient pas, au cas ou)

![image 8](./img/11.png)

7. Conflit résolu (marqueurs avant, graphe après)

J'ai créé un conflit simple sur index.html (j'ai changer la meme ligne sur main et ma branch)

![image 8](./img/12.png)

Il va falloir me croire mais en gros j'ai bien reussi à merge, j'ai fait le merge grace à visual code et ai donc resolue le conflit

![image 8](./img/13.png)

8. Revert du bandeau promo

Regarde pas les commit avant :p regarde juste le revert qui a bien fonctionner :o

![image 8](./img/14.png)

9. Issue fermée par une Pull Request

J'ai créé une "issue #5" puis j'ai fait une pr et je l'ai resolue:

![image 8](./img/15.png)
![image 8](./img/16.png)

10. Protection de main et CI au vert

La derniere modif est obligatoire si tu veux testé si les modif de la branch fonctionne (vu que je suis admin)

![image 8](./img/17.png)
![image 8](./img/18.png)


## Cible mobile

11. Commit distant récupéré et conflit résolu
![image 8](./img/19.png)
![image 8](./img/20.png)

Et j'ai bien merge du coup

12. Bonus

J'ai rajouter quelques features au site: rien de fou mais ca reste une feature

![image 8](./img/21.png)
![image 8](./img/22.png)

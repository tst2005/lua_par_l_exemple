# Faire un site sur le langage Lua en français

Perso je me vois bien faire un tuto comme avec [golang](https://gobyexample.com/) à savoir par l'exemple plutôt que de faire de long discourts

[Site](http://fengari.io/) pour tester lua sans installation
[Version plus complète de ArRay_](https://github.com/BetaRays/tutoriel-lua/)

Liste à faire:

1. [Hello World](hello_world.md)
2. [Les commentaires](commentaires.md)
3. [Les valeurs](valeurs.md)
4. [Les variables](variables.md)
5. [Les boucles](boucles.md)
6. [If/Else](conditions.md)
7. [Break](break.md)
7. [Les tables](tables.md)
8. [Les fonctions](fonctions.md)
9. [Portée des variables](portee_variables.md)
10. [Fonction à nombre d'arguments variables](variadic.md)
10. [Les imports](imports.md)
10. [Créer ses propres librairies](creer_lib.md)
10. [La récursivité](recursivite.md)
11. [Lire et écrire un fichier](lecture_ecriture.md)
11. [Les coroutines](coroutines.md)
12. Awesome Lua
13. Remerciements

Les choses à rajouter dans la liste
* Expliquer ce que c'est que nil
* Parler de select (function a(...) for i=1,select('#',...) do print(i,select(i,...)) end end a('c','est','cool'))

exemple: [22:20:21] <nheir> select est une fonction qui prend un premier argument correspondant à l'action que tu veux faire et d'autres arguments ensuite, si le premier est '#', select renvoie le nombre d'arguments qui suit
[22:21:00] <nheir> si c'est un nombre, il renvoie les arguments à partir de l'argument en position ce nombre
[22:21:34] <ChipsterOne> ok
[22:22:03] <nheir> !lua select('#', 4,8,9,1,5,9,7)
[22:22:04] <arch_ange> > 7
[22:22:09] <nheir> !lua select('4', 4,8,9,1,5,9,7)
[22:22:10] <arch_ange> > 1 5 9 7
[22:22:22] <nheir> !lua select('3', 4,8,9,1,5,9,7)

* Récupérer les arguments de la ligne de commandes
* les closures
* sandbox (avec do … end)
* les variables magiques
* pack/unpack (voir ici: https://github.com/BetaRays/tutoriel-lua/blob/master/030-Les_variables.md#les-fonctions-variadiques)
* rajouter sort aux tables (http://wxlua.free.fr/Tutoriel_Lua/Tuto/Tables/tables9.php)
* Les regex
* Les fonctions à nombre de variables indéterminées
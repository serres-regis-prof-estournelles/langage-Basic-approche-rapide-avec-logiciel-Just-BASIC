## Un jeu de logique classique en BASIC pour TO7/MO5 (milieu des années 80).

Ce dépôt présente plusieurs incarnations d'un jeu de logique classique : trouver une combinaison secrète de 4 chiffres. 
#
Il met particulièrement en lumière son implémentation originelle en **BASIC** pour les ordinateurs 8-bits **Thomson TO7 et MO5**, témoignage d'une époque où la programmation commençait au collège ou dans sa chambre.

#
Lien du téléchargement : **https://justbasic.com/** ou exécuter le fichier **jb20setup.exe**.
#
Au cœur de ce projet se trouve `cadenas.bas`. Ce n'est pas seulement un programme, c'est une **capsule temporelle**.
#
*   **Origine** : J'ai conçu ce programme en 1985-1986 pour les ordinateurs **Thomson TO7 et MO5** très utilisés en France à cette époque. L'interface visuelle, ce n'était pas le top.
#
*   **Langage** : Écrit en **BASIC**, le langage interprété fourni d'office avec ces machines, souvent appris à partir de magazines et par quelques profs de maths au collège ou au lycée... Pas d'Internet, d'IA. On trouvait une idée et on programmait.
#
*   **Contexte** : À une époque où exécuter un programme était sauvegardé précieusement sur une **cassette audio**. Pour ouvrir un fichier (LOAD) et l'enregistrer, ça prenait parfois plusieurs minutes.
#
❌ Pas de souris à l'époque mais un crayon optique... 
#
❌ Le CTRL + V n'existait pas. 
#
❌ S'il y avait 100 fois PRINT dans un programme, il fallait saisir 100 fois PRINT...
# 
❌ Quand on avait un message du type "SYNTAX ERROR IN 100", on pouvait y passer des heures. Il y avait une erreur à la ligne 100. C'était à toi de la trouver et de la corriger sans aide extérieure.
#
✅ Ce code, avec ses numéros de ligne, ses instructions `GOTO` et `GOSUB`, et ses `PRINT` en majuscules, est l'**ancêtre** des versions modernes en **C++** et **Python**. 
#
## 🎮 Qu'est-ce que le Jeu du Cadenas ?

1️⃣ C'est un jeu de **déduction logique** solo contre l'ordinateur.
#
2️⃣ L'ordinateur génère aléatoirement une **combinaison secrète** de 4 chiffres (de 0 à 9), tous différents.
#
3️⃣ Le joueur a 10 tentatives pour la deviner.
#
4️⃣ À chaque proposition, l'ordinateur donne un feedback :
#
► Nombre de **chiffres bien placés** : Chiffre(s) correct(s) et à la bonne position (**sans indiquer lesquels**, c'est toute la difficulté du jeu). 
#
► Nombre de **chiffres mal placés** : Chiffre(s) correc(s) mais à la mauvaise position (**sans indiquer lesquels**).
#   
► But du jeu : déduire le **code secret** et gagner la partie en moins de **10 essais**.
#
## Le geek des années 80, c'est la 2CV : quand ton jeu plante, tu utilises le manuel, tu regardes sous le capot (le code), et avec un peu d'huile de coude (et un GOTO bien placé), ça redémarre. Ce n'est pas rapide, ça vibre, mais tu comprends comment ça marche 😀.
## Le geek d'aujourd'hui, c'est la Tesla : quand ça plante, tu fais une mise à jour OTA en espérant que le bug soit fixé. C'est rapide, c'est fluide, mais si l'écran tactile meurt, tu ne sais même pas où est le capot 😀.
#
👤 Auteur : SERRES Régis - Enseignant - Lycée Estournelles de Constant, La Flèche (72) GitHub : @serres-regis-prof-estournelles

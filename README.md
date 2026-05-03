Un commercial doit visiter 6 villes.
Il veut faire le moins de kilomètres possible.
Dans quel ordre partir ?

Ce problème s'appelle le Voyageur de Commerce. 🗺️
Il est étudié depuis les années 1930.
Toujours pas résolu parfaitement.

J'ai codé une simulation en EduCode avec Paris, Lyon, Marseille, Bordeaux, Nantes et Lille.

Ma stratégie : l'algorithme glouton.
A chaque étape, aller vers la ville la plus proche non encore visitée.

Paris -> Lille (225 km)
Lille -> ... -> retour Paris

C'est intuitif. C'est rapide.
Mais ce n'est pas toujours optimal.

Parce qu'un choix localement bon peut être globalement mauvais.
En choisissant la ville la plus proche à chaque pas, on peut se retrouver à faire un immense détour à la fin.

J'ai comparé 4 circuits différents sur les mêmes villes.
Résultat : plusieurs centaines de km d'écart entre le meilleur et le pire.
Meme point de départ. Même arrivée. Juste un ordre différent.

Et pour 20 villes ?
60 000 milliards de circuits à comparer.
Même les ordinateurs les plus puissants ne peuvent pas tout tester.

C'est ça qui est fascinant avec le TSP :
- Le problème est simple à comprendre.
- La solution parfaite reste hors de portée.

<img width="1908" height="882" alt="screenshot" src="https://github.com/user-attachments/assets/55396131-a6da-4593-8791-b46ae2efca06" />

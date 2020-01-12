les autheur du projet : 
bendellah boubeker 	G1
mokrani mehdi   	G1
Ghazali hichem 		G6


RESUME:
Analyse lexical:
On a placer le texte dans une variable global que l'on divise et pui la mettre dans un tableau  qui  compare chaque case du tableau grace a la fonction nbredeclone(int i,String A[]) 
si le resultat est juste on affiche sur jfieldtexte le resultat soit (identificateur , mot reservé ,etc ..) si l'inverse on affiche "erreur syntaxique".

Analyse syntaxique:
Dans ce cas on utilise la variable globale precedent et ont la separe pour mettre chaque  ligne dans une case du tableau ,en utilisant la fonction AnalyseSyntexique(String ligne) qui separe les ligne 
en mot et les compare avec la premier case du tableau et si il la trouve il apelle une autre fonction qui commence par le mot utilisé qui ensuite lit la ligne et la compare  avec les mot du tableau en boucle .
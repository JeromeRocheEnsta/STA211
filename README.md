# STA211

** Overview: **
Les méthodes de capture-marquage-recapture sont des méthodes astucieuses d'échantillonage non destructif pour évaluer le nombre (inconnu) d'individu dans une population. Dans le omaine de la gestion de l'halieutique elles consistent à effectuer un certains nmbre de pêches successives, avec remise, à l'aide d'un dispotif possèdant une efficacité $\pi$. Cette efficacité est a probabilité de pêcher un poisson. 

** What is in this work ?: **
Dans ce projet, on s'intéresse au cas de deux pêches succéssives (avec marquage et remise) effectuées pour estimer le nombre de poisson N (inconnu) dans un lac. On appelle respectivement $C_1$ et $C_2$ le nombre de poisson pêchés et marqués à la pêche numéro 1 et numéro 2. On note $C_{20}$ le nombre de poisson non marqués pêchés à la secone capture et $C_{21}$ le nombre poisson marqués capturés à la seconde pêche. Ainsi $C_2 = C_{20} + C_{21}$.

On se place dans le cas où les données de l'expérience sont: $C_1 = 125$; $C_{20} = 134$ et C_{21} = 21$.
On considère le modèle probabiiste $\cal{M}$ suivant:
$$
C_1 ~ B(N, \pi)\\
C_{20} ~ B(N-C_1, \pi) \\
C_{21} ~ B(C_1, \pi)
$$

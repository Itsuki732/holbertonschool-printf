# Printf

## Description
Parcourt une chaîne de format spécifié et affiche un caractère à la fois, ainsi quand le % est rencontré, il regarde un spécificateur de conversion qui définit le format d'affichage de l'argument suivant.

## Prérequis
Compilateur C (gcc)
Connaissance de base en langage C

## Installation

git clone https://github.com/Itsuki732/holbertonschool-printf.git

cd holbertonschool-printf

Compilation du projet : gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c

## Utilisation

#include "main.h"

int main(void)

{
_printf("Hello %s ! Je suis %s et développeur depuis %i ans.\n", "astrophysicien", 35);
return 0;
}

## Fonctionnalités

%c : 1 seul caractère
%s : chaîne de caractères
%% : affiche un pourcentage
%d, %i : entier

## Contribution

Forker un dépôt/copier pour modifier sans casser l'original
Créer une branche
Faire un commit et push

## Licence

## Contact

Maxime

<img width="1360" height="1080" alt="Image" src="https://github.com/user-attachments/assets/e518d19a-552e-4d86-a7d0-93df4401b37a" />
# test-1
shell00
changer les date sur un document
https://pubs.opengroup.org/onlinepubs/009695399/utilities/touch.html


shell01
exo1

#!/bin/bash
id -Gn $FT_USER | tr ' ' ','


id = identifiant 
$ = sert a mettre une variable sur un nom
tr = sert a montrer une version modifier (sans changer la version)

#! = sert a executé un script
/bin/bash sert a lancer en format bash


exo2

#!/bin/bash
find . -type files -name "*.shss" 


sed = sert a modifier l'affichage de l'emplacement d'un document

exo3

#!/bin/bash

find . \( -type f -o -type d \)


-o = c'est ou 
\( ... \) => permet de cree une condition sorte de si


exo4 

ip link | grep ether | awk '{print $2}'


awk => traite les donné ligne par ligne
a revoir


exo5 
juste cree un ficher avec echo

echo 42 > "etc"


Exo6

ls -l | awk "NR % 2 == 1"

awk = ligne par ligne

NR = nombre 

% 2 = fais une division par deux ou le debut d'un prompt

$ = debut de promte et aussi symbole de variable

== = test une égalité


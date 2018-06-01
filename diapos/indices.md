# Les indices

1. [Calcul d'un indice](#/7/1)
2. [Passage de l'indice à l'évolution](#/7/3)
3. [Les propriétés de l'indice](#/7/4)  
4. [Passage de deux indices à l'évolution](#/7/5)
5. [Liens utiles](#/7/7)

----

## Calcul d'un indice  

Soit Vt la valeur de la variable à la date t et Vt0 la valeur de la variable à la date t0, l'indice à la date t en base 100 à la date t0 se calcule selon la formule suivante :  
  > I(t1/t0) = 100 \* Vt/Vt0  

----

## Calcul d'un indice

Il y a toujours une date de référence lorsqu'on parle d'un indice. La date de référence ou date de base (il s'agira souvent d'une année) est t0.
L'indice à la date t0 vaut toujours 100.
Un indice n'a pas d'unité et est toujours positif.  
Un indice inférieur strictement à 100 équivaut à un taux d'évolution négatif, et un indice strictement supérieur à 100 équivaut à un taux d'évolution positif.  

----

## Passage de l'indice à l'évolution  


> taux_variation entre t1 et t0 = I(t1/t0) - 100  
> Multiplicateur = I(t1/t0)/100

----

## Les propriétés de l'indice  

Principe de circularité :
> I(t2/t1) = 100 \* I(t2/t0) / I(t1/t0)  

Cas particulier, la réversibilité :  
> I(t0/t1) = 100 \* I(t0/t0)/I(t1/t0) = 10 000 / I(t1/t0)  

Les indices permettent des réévaluations de variables selon la formule :
> Vn = Va \* In / Ia  

----

## Passage de deux indices à l'évolution

> Multiplicateur = I(t2/t0) / I(t1/t0)  
> taux_variation entre t1 et t0 = 100 * ((I(t2/t0) / I(t1/t0)) - 1)

En appliquant le principe de circularité de l'indice, on obtient :

> Multiplicateur = I(t2/t1) / 100
> taux_variation entre t1 et t0 = 100 * ((I(t2/t1)/100) - 1)

----

## Liens utiles  

Ces différents indices sont disponibles sur [www.insee.fr](https://www.insee.fr).  
Par exemple,
- [pour l’indice des prix à la consommation](https://www.insee.fr/fr/information/3128533?qserie=indice+des+prix+%C3%A0+la+consommation)
- [pour l’indice de référence des loyers](https://www.insee.fr/fr/information/3128533?qserie=indice+de+r%C3%A9f%C3%A9rence+de+loyers)

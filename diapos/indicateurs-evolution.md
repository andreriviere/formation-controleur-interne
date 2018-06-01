# Les indicateurs d'évolution

1. [La variation absolue ou écart](#/6/1)
2. [La variation relative (taux d'évolution)](#/6/2)
3. [Le multiplicateur](#/6/4)
4. [Quel indicateur faut-il utiliser ?](#/6/5)

----

## La variation absolue ou écart

** Définition : **
> Soit Vabs la variation absolue, Va la valeur d'arrivée et Vd la valeur de départ, alors on a :  
> - Vabs = Va - Vd

La variation absolue s'exprime dans la même unité que la grandeur.
La variation absolue traduit moins bien l'importance de l'évolution que la *[variation relative.](#/6/2)*  

----

## La variation relative (taux d'évolution)  

** Définition : **
> Soit Vrel la variation relative, alors on a :  
> - Vrel = (Va - Vd) / Vd = Va / Vd - 1  
> - Vrel = Vabs / Vd  

La variation relative est un nombre sans unité, qui multipliée par cent peut s'exprimer en pourcentage. C'est le *taux d'évolution* ou *taux de variation*.  

> - Taux_evolution = Vrel * 100.  

----

## La variation relative (taux d'évolution)

<p id="piege"> ATTENTION PIEGE</p>
<div id="souspiege"><p>Il ne faut pas confondre un ralentissement et une baisse.</p>

<p>Si un taux de variation passe de 20% à 15%, il s'agit d'un ralentissement car le taux de variation, bien que plus faible, reste positif et donc la variable continue d'augmenter, plus faiblement qu'auparavant.</p>

<p>Si un taux de variation est de -3%, il s'agit alors en effet d'une baisse car le taux est négatif, ce qui implique une diminution de la valeur de la variable étudiée.</p></div>

----

## Le multiplicateur  

** Définition : **  
> Multiplicateur = Va / Vd  
> => Va = Multiplicateur \* Vd  
> Or Va = (1 + Vrel) \* Vd  
> => Multiplicateur = 1 + Vrel  

[Exemple à compléter](files/exemple-a-completer.ods)  

----

## Quel indicateur faut-il utiliser ?  
- Pour calculer une évolution, utiliser le [taux de variation](#/6/2). S'il est supérieur ou égal à 100%, le [multiplicateur](#/6/3) sera plus parlant.  
- Pour obtenir la valeur d'arrivée à partir de la valeur de départ et de l'évolution :  
    - Va = Vd + (taux_variation/100\*Vd) = Vd \* (1 + taux_variation/100)  
- Inversement, pour obtenir la valeur de départ à partir de la valeur d'arrivée et de l'évolution :  
    - Vd = Va / (1 + taux_variation/100)  
- La variation en points se calcule par différence entre deux pourcentages.  
- Le calcul des évolutions successives se fait par le produit des multiplicateurs auquel on retire 1.  

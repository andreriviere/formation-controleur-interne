# Rappels mathématiques  

1. [Les puissances](#/10/1)
2. [Les moyennes](#/10/4)
3. [Les équations](#/10/12)
4. [La concentration](#/10/15)
5. [La régression](#/10/17)

----

## Les puissances

La puissance d'un nombre est le résultat de la multiplication répétée de ce nombre avec lui-même.  

<img src="img/puissances.jpg" alt="Puissances">

----

## Les puissances

### Codage des puissances

<img src="img/codagepuissance.png" alt="Codage des puissances">

----

## Les puissances

### Opérations algébriques sur les puissances

Pour les multiplications et les divisions de puissances, on sait que pour tous nombres a et b et pour tous entiers naturels m et n non nuls :  

- a^m*a^n=a^(m+n)  
- a^m/a^n=a^(m-n) si a!=0.  
- (a*b)^n=a^n * b^n  
- (a^m)^n=a^(m * n)  
- (a/b)^n=a^n/b^n si b!=0.  

Ces formules sont encore valables si m ou n sont des entiers strictement négatifs, à condition que a et b soient non nuls.  
- a^n*a^(-n)=a^(n+(-n))=a(n-n)=a^0=1  

----

## Les moyennes

### Moyenne arithmétique

La *moyenne arithmétique* est la moyenne "ordinaire", ie la somme des valeurs numériques (de la liste) divisée par le *nombre* de ces valeurs numériques.  

<img src="img/moyennearithmetique.jpg" alt="Moyenne arithmétique">  

----

## Les moyennes

### Moyenne arithmétique pondérée

Etant donné un ensemble de données : X = {x1, x2, ..., xn}, ainsi que les poids correspondants : W = {w1, w2, ... , wn}  

<img src="img/moyennearithmetiqueponderee.jpg" alt="Moyenne arithmétique pondérée">  

----

## Les moyennes

### Moyenne géométrique

<img src="img/moyennegeometrique.jpg" alt="Moyenne géométrique">  

----

## Les moyennes

### Moyenne géométrique pondérée

Etant donné un ensemble de données : X = {x1, x2, ..., xn}, ainsi que les poids correspondants : W = {w1, w2, ... , wn}, la moyenne géométrique pondérée est calculée comme étant :  

<img src="img/moyennegeometriqueponderee.jpg" alt="Moyenne géométrique pondérée">  

----

## Les moyennes

### Moyenne harmonique

La moyenne harmonique est définie de la manière suivante :  

<img src="img/moyenneharmonique.jpg" alt="Moyenne harmonique">  

----

## Les moyennes

### Moyenne harmonique pondérée

Etant donné un ensemble de données : X = {x1, x2, ..., xn}, ainsi que les poids correspondants : W = {w1, w2, ... , wn}, la moyenne harmonique pondérée est calculée comme étant :  

<img src="img/moyenneharmoniqueponderee.jpg" alt="Moyenne harmonique pondérée">  

----

## Les moyennes

### Taux de variation annuel moyen

[Présentation](files/présentation_tcam.odt)  

Le taux de croissance annuel moyen, exprimé en pourcentage, sur périodes (années, mois, semaines, etc.) est donné par la formule :  

<img src="img/tcam.jpg" alt="taux de variation annuel moyen">  

----

## Les moyennes

[Exercice](files/exercice_tcam.odt)

----

## Les équations

### Equations simples

Une équation est une question, une égalité entre deux quantités algébriques. Cette égalité contient des inconnues. Résoudre l’équation, c’est trouver les valeurs des inconnues qui rendent vraie l’égalité.  
En voici des exemples :
    • 3 x + 5 = 14, on cherche x  

Si 3x+5 = 14
alors 3x = 9
soit x = 3

----

## Les équations

### Equation d'une droite dans un plan

En géométrie affine, une équation de droite, au sens large, permet de décrire l’ensemble des points appartenant à cette droite.  

Une droite dans un plan affine de dimension 2 est déterminée par une équation cartésienne ; une droite dans un espace affine de dimension 3, est déterminée par un système de deux équations cartésiennes définissant deux plans sécants dont la droite est l'intersection.  
Dans le plan, l'ensemble des points M (x, y) formant D peut se représenter par une équation de la forme : a x + b y + c = 0 où a, b et c sont des constantes telles que (a, b) ≠ (0, 0).
Dans ce cas, D = { (x, y) ∈ R2   |   a x + b y + c = 0 }.  

----

## Les équations

### Notions de fonctions

En mathématique, l’application qui transforme un nombre est appelé une fonction.  

Ainsi, la chaîne ci-dessus est une fonction. On la note : f : x → 3x + 15  
x est le nombre de départ, on l’appelle l’antécédent.  
3x + 15 est le nombre d’arrivée.  
On le note f(x) = 3x + 15 et on l’appelle l’image de x.  

----

## Concentration

### La médiane

[La médiane](#9/6)  

----

## Concentration

### L'écart interquartile

L’écart interquartile est la différence entre le troisième et le premier quartile.  
L’écart interquartile correspond donc à l'étendue de la série statistique après élimination de 25 % des valeurs les plus faibles et de 25 % des valeurs les plus fortes. Cette mesure est plus robuste que l’étendue, qui est sensible aux valeurs extrêmes.  

<img src="img/ecartinterquartile.jpg" alt="Ecart interquartile">  

----

## Concentration

### Les déciles

[Les quantiles](#9/6)  

Si on ordonne une distribution de salaires, de revenus, de chiffre d’affaires, les déciles sont les valeurs qui partagent cette distribution en dix parties égales.
Ainsi, pour une distribution de salaires :
    • le premier décile (noté généralement D1) est le salaire au-dessous duquel se situent 10 % des salaires ;
    • le neuvième décile (noté généralement D9) est le salaire au-dessous duquel se situent 90 % des salaires.
Le premier décile est, de manière équivalente, le salaire au-dessus duquel se situent 90 % des salaires ; le neuvième décile est le salaire au-dessus duquel se situent 10 % des salaires.  

----

## Concentration

### Les quartiles

[Les quantiles](#9/6)  

Si on ordonne une distribution de salaires, de revenus, de chiffre d’affaires, les quartiles sont les valeurs qui partagent cette distribution en quatre parties égales.
Ainsi, pour une distribution de salaires :
    • le premier quartile (noté généralement Q1) est le salaire au-dessous duquel se situent 25 % des salaires ;
    • le deuxième quartile est le salaire au-dessous duquel se situent 50 % des salaires ; c’est la médiane ;
    • le troisième quartile (noté généralement Q3) est le salaire au-dessous duquel se situent 75 % des salaires.
Le premier quartile est, de manière équivalente, le salaire au-dessus duquel se situent 75 % des salaires ; le deuxième quartile est le salaire au-dessus duquel se situent 50 % des salaires, et le troisième quartile le salaire au-dessus duquel se situent 25 % des salaires.

----

## Concentration

### L'écart-type

L’écart-type sert à mesurer la dispersion, ou l’étalement, d’un ensemble de valeurs autour de leur moyenne. Plus l’écart-type est faible, plus la population est homogène.

<img src="img/ecarttype.jpg" alt="Ecart type">

----

## Concentration

### La variance

**La variance est le carré de l’écart-type.**  

----

## Concentration

### La covariance

[Définition et exemple](files/covariance.odt)  

----

## Concentration

### La covariance

Le coefficient de variation (CV) est le rapport de l’écart-type à la moyenne.  
Plus la valeur du coefficient de variation est élevée, plus la dispersion autour de la moyenne est grande. Il est généralement exprimé en pourcentage. Sans unité, il permet la comparaison de distributions de valeurs dont les échelles de mesure ne sont pas comparables.  

----

## Concentration

### Indice de Gini

indice mesurant le degré d’inégalité d’une distribution pour une population donnée. Il varie entre 0 et 1, la valeur 0 correspondant à l’égalité parfaite (tout le monde a le même niveau de vie), la valeur 1 à l’inégalité extrême (une personne a tout le revenu et les autres n’ont rien).  

<img src="img/indicegini.jpg" alt="Indice Gini">

----

## Régression

[Cours](files/courscomplet.odt)

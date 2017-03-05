
<br>
<br>
<br>











# Why is $1 - \frac{1}{1 - \frac{1}{1 - ...}}$ not real?

*****************************

So we all know that the continued fraction containing all 1 s...

$$x = 1 + \frac{1}{1 + \frac{1}{1 + ...}}$$

yields the golden ratio $x =\phi$, which can easily be proven by rewriting it as $x = 1 + 1/x$, ...












<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<br>
<br>
<br>









# Why are these numbers unequal?

*****************************

The following code is obviously wrong. What's the problem?


```
i <- 0.1
i <- i + 0.05
i
## [1] 0.15
if(i==0.15) cat("i equals 0.15") else cat("i does not equal 0.15")
## i does not equal 0.15
```













<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>









## Options d'affichage


Code source et sortie

```r
  2+3
```

```
## [1] 5
```



--------------------


Code source

```r
  2+3
```

--------------------

Sortie

```
## [1] 5
```











<br>
<br>
<br>
<br>
<br>
<br>








## Analyse de l'objet R `cars` 

En premier lieu, un aperçu graphique de la distance en fonction de la vitesse :

```
plot(cars)
```

![](C:\Users\Laurent\Documents\GitHub\OTC\images\img_car_plot.jpeg)















<br>
<br>
<br>
<br>
<br>




# Première solution




<br>
<br>
<br>
<br>







En simulant encore une fois 10 000 mains aléatoirement, tout en forçant le premier joueur à posséder deux valets au départ, on obtient les résultats suivants pour chaque joueur :

```
##    Nombre.de.gains Prob.de.victoire
## J1            4830            0.483
## J2            1723            0.172
## J3            1697            0.170
## J4            1750            0.175
```
Tout comme au premier numéro, nous avons distribué ici les égalités également entre les joueurs impliqués dans chaque égalité. Toutefois, il peut être intéressant de se












<br>
<br>
<br>
<br>









# Deuxième solution

Voici le tableau des résultats :

Table: Tableau 2 : Gains et probs ...

      Nombre.de.gains   Prob.de.victoire
---  ----------------  -----------------
J1               4830              0.483
J2               1723              0.172
J3               1697              0.170
J4               1750              0.175

On constate que ...

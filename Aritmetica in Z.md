#Aritmetica in $\mathbb{Z}$

Consideriamo ( $\mathbb{Z}$ ,$+$, $\bullet$ ) anello unitario

$a$ / $b$ ( $a$ divide $b$ ) $\iff$ $\exists$ $c$ $\in$ $\mathbb{Z}$ : $b$ = $a$ $\bullet$ $c$

####Divisori banali

$\forall$ $a$ $\in$ $\mathbb{Z}$ :

$a,-a$ / $a$ : $a$ = $a$ $\bullet$ 1 = $(-a)$ $\bullet$ $(-1)$

1,-1 / $a$

I divisori banali di $a$ sono $\{ 1, -1 , a, -a\}$

I divisori banali sono sempre inclusi nell'insieme dei divisori

$Div$ $banali$ $(a)$ $\subseteq$ $Div$  $(a)$ = { $b$ $\in$ $\mathbb{Z}$ | $b$ / $a$ } $\not$= $\varnothing$

Div (7) = $\{ 1, -1, 7, -7 \}$

Div (6) = $\{ 1, -1, 6, -6, 2, -2, 3, -3 \}$

Div (0) = { $b$ $\in$ $\mathbb{Z}$ | $b$ / 0 } = $\mathbb{Z}$ questo perchè :

$\exists$ $c$ $\in$ $\mathbb{Z}$ : 0= $b$ $\bullet$ $c$ = $b$ $\bullet$ 0

$\forall$ $b$ $\in$ $\mathbb{Z}$ $b$ $\bullet$ 0 = 0 $\implies$ b $\in$ Div(0)

Div (1) = $\{1,-1\}$ $\subset$ Div ($a$) $\forall$ $a$ $\in$ $\mathbb{Z}$

Div ($a$) = Div ($-a$) $\forall$ $a$ $\in$ $\mathbb{Z}$

##Numeri primi

$p$ $\in$ $\mathbb{Z}$ si dirà primo $\forall$ $a,b$ $\in$ $\mathbb{Z}$ $\iff$ 
$\forall$ $a,b$ $\in$ $\mathbb{Z}$ 

1. $p$ $\not$= 1,-1 ossia $p$ non è invertibile
2. $\forall$ $a,b$ $\in$ $\mathbb{Z}$ $p$ / $a$ $\bullet$ $b$ $\implies$ $p$ / $a$ $\lor$ $p$ / $b$


Div ($p$) = $\{1,-1,p,-p\}$

####Osservazione

Suppongo che $a$ $\in$ Div ($p$), questo comporta che $a$ si può scrivere come 

$a$ / $p$ : $p$ = $a$ $\bullet$ $c$ con $c$ $\in$ $\mathbb{Z}$

$p$ / $a$ $\bullet$ $c$ $\implies$ $p$ / $a$ oppur $p$ / $c$

Questo implica che

i) se $p$ / $a$ $\implies$ $\exists$ $d: a = p$ $\bullet$ $ d$
ii) se $p$ / $c$ $\implies$ $\exists$ $f$ : $c = p$ $\bullet$ $f$

i) $p$ = $a$ $\bullet$ $c$ = $p$ $\bullet$ $d$ $\bullet$ $c$ $\implies$ $dc$ = 1 $\implies$ $d$ = $c$ = 1, -1

*Un po di background quando io scrivo p = a $\bullet$ c la variabile a corrisponde da ipotesi a p $\bullet$ d. Quindi tolgo p da entrambe le parti ed ecco che rimango solo con cd che fa 1 *

ii) si dimostra in modo equivalente.

##Combinazioni lineari

Siano $a,b,c$ $\in$ $\mathbb{Z}$ . Se $a$ / $b$ e $a$ / $c$ allora $\forall$ $h,k$ $\in$ $\mathbb{Z}$ $\implies$

$a$ / ( $b$ $\bullet$ $h$ + $c$ $\bullet$ $k$ ) ovvero se a divide una coppia di valori dividerà anche le loro combinazioni lineari

$a$ / $b$ $\rightarrow$ $b$ = $b_{1}$ $\bullet$ $a$

$a$ / $c$ $\rightarrow$ $c$ = $c_{1}$ $\bullet$ $a$

($b$ $\bullet$ $h$ + $c$ $\bullet$ $k$ ) = $b_{1}$$a$$h$ + $c_{1}$$a$$k$

Metto in evidenza $a$ $\rightarrow$ $a$($b_{1}$$h$ + $c_{1}$$k$) ho dimostrato quindi che se $a$ / $b,c$ divide anche qualsiasi combinazione lineare di $b,c$


##Teorema sulla divisione Euclidea

Siano $m$ , $n$ $\in$ $\mathbb{Z}$  e $m$ $\not$= 0.

Allora $\exists$! ($q,r$) $\in$ $\mathbb{Z}$ x $\mathbb{N}$ :

$n$ = $m$ $\bullet$ $q$ + $r$ con 0 $\le$ $r$ < |$m$|

$q$ = quoziente
$r$ = resto

**Dimostrazione:** 

Si utilizza il principio d'induzione nella II forma

Si inizia dimostrando l'esistenza della coppia ($q,r$)

$P_{0}$ base d'induzione

Se $n=0$ $\rightarrow$ $q=r=0$

0 = $m$ $\bullet$ 0 + 0

Si supponga quindi che $n$ $\geq$ 0 e $m>0$

$Pn$ : $\forall$ $n$ e $m$ $\not$= 0 $\exists$ $q,r$ : $n=$ $m$ $\bullet$ $q$ + $r$ con 0 $\le$ $r$ < $|m|$

$P_{L}$ (passo d'induzione) 0 $\le$ $l$ < $n$ sia vera

**Osserviamo che se $m$ > $n$** 

$n$ = $m$ $\bullet$ 0 + $n$ con 0 $\le$ $n=r$ < $m$

$q$ = 0
$r$ = $n$

**Sia $n$ $\geq$ $m$** 

0 $\le$ $l$ = $n-m$ < $n$

$P_{l}$ è vera 

$l$ = $m$ $\bullet$ $q_{1}$ + $r_{1}$ 0$\le$ $r_{1}$ < $m$

0 $\le$ $r_{1}$ > $m$

$n=m$ $\bullet$ $q_{1}$ + $m$ + $r_{1}$ = $m$($q_{1}$ + 1) + $r_{1}$

$q$ = $q_{1}$ + 1 

$r$ = $r_{1}$

**Osserviamo ora se $m$ < 0 la proposizione $Pn$ è vera per ($-m$) > 0**

$n$ = ($-m$) $\bullet$ $q_{1}$ + $r_{1}$ con 0 $\le$ $r-{1}$ < $(-m) = |m|$

$n$ si puo scrivere però anche come:

$n$ = $m$ $\bullet$ ($-q_{1}$) + $r$


$q$ = $-q_{1}$
$r_{1}$ = $r$


####ESEMPIOOOOOOO

13 lo voglio dividere per (-5) divido prima 13 per 5 quindi:

13=5 $\bullet$ 2 + 3

si può scrivere anche come : (-5) $\bullet$ (-2) + 3

$q$ = $-q_{1}$ = -2

----


**Caso n<0**

Se $n$ < 0 

$-n$ > 0 

$P_{-n}$ sarà vera : $(-n) = m$ $\bullet$ $q_{1}$ + $r_{1}$ con 0 $\le$ $r_{1}$ < $|m|$

i) $r_{1}$ = 0

$n$ = $-m$ $\bullet$ $q_{1}$ = $m$($-q_{1}$) 

$q$ = $-q_{1}$

$r$ = $r_{1}$ = 0

ii) $r_{1}$ > 0

$n$ = -($mq_{1}+r_{1}$) = $m$($-q_{1}$ - $r_{1}$ ma il resto non può essere negativo quindi aggiungo e sottraggo la stessa quantità $|m|$

$n$ = -($mq_{1}+r_{1}$) = $m$($-q_{1}$) - $r_{1}$ +$|m|-|m|$


$m$ - $q_{1}$ - |$m$| + ( $|m|$ - $r_{1}$) metti in evidenza $m$

$m$($q_{1}$ +- 1) + ($|m|$ - $r_{1}$)

$q$ = $q_{1}$ +- 1
$r$ = $|m|$ - $r_{1}$



####ESEMPIOOOOOOOOOOOOOOOOOOOOO


Voglio dividere -13 per 5.

-13 non lo so dividere ma so dividere 13 che è uguale a :

$13 = 5$ $\bullet$ $2 + 3$

$-13 = 5$ $\bullet$ $(-2) -3 +5 -5 =$

$5 (-2-1) + (5-3) = -15 +2 = -13$

$q$ = -3
$r$ = 2


####TUTTA STA ROBA E' PER DIMOSTRARE L'ESISTENZA DELLA COPPIA MO DOBBIAMO VERIFICARE L'UNICITA'

$n$ = $m$ $\bullet$ $q_{1}$ + $r_{1}$ = $m$ $\bullet$ $q_{2}$ + $r_{2}$

0 $\le$ $r_{1}$,$r_{2}$ < $|m|$

Consideriamo che $r_{2}$ $\geq$ $r_{1}$

$m$ $\bullet$ $q_{1}$ - $m$ $\bullet$ $q_{2}$ = $r_{2}$ - $r{1}$ quindi questa quantità sia $\geq$ 0

metto in evidenza $m$

$m$($q_{1}$, $q_{2}$) = $m$ $\bullet$ $q_{1}$ - $m$ $\bullet$ $q_{2}$ = $r_{2}$ - $r_{1}$ $\geq$ 0

con $r_{2}$ - $r_{1}$ < $m$

$implies$ $r_{2}$ - $r_{1}$ è un multiplo non negativo di $m$ e $r_{2}$ - $r_{1}$ < $|m|$ $\implies$ $r_{2}$ - $r_{1}$ = 0 $\implies$ $r_{2}$ = $r_{1}$ 

$m$($q_{1}$ - $q_{2}$) = 0

$m$ $\not$= 0 $\implies$ $q_{1}$ - $q_{2}$) = 0 $\implies$ $q_{1}$ = $q_{2}$


####TEOREMA DIMOSTRATO


##M.C.D tra due numeri

Siano $a,b$ $\in$ $\mathbb{Z}$ 

$d$ è M.C.D ($a,b$) $\iff$ 

1. $d$ / $a$ e $d$ / $b$
2. se $c$ / $a$ e $c$ / $b$ allora $c$ / $d$


**Esempio**

M.C.D ($12,40$) 

Div comuni di 12 e 40 = $\{1,-1,2,-2,4,-4\}$ 

Div 12 = $\{1,-1,2,-2,3,-3-4,-4,6,-6,12,-12\}$
div 40 = $\{1,-1,2,-2,4,-4,5,-5,8,-8,10,-10,20,-20,40,-40\}$

L'intersezione mi da i divisori comuni : $\{1,-1,2,-2,4,-4\}$

Div comuni di 21 e 18

Div 21 = $\{1,-1,3,-3,7,-7,21,-21\}  $

Div 18 = $\{1,-1,2,-2,3,-3,6,-6,9,-9,18,-18\}$

Div comuni sono : $\{1,-1,3,-3\}$


M.C.D (21,18) = {3,-3}



####Considerazioni

-Se $p$ è primo

div ($p$) = $\{1,-1,p,-p\}$

M.C.D ( $a,p$ ) i divisori comuni saranno solo o {$-1,1$} o { $p, -p$}


-Se $a$ / $b$ 

$b$ = $a$ $\bullet$ $c$

I div ($a$) $\subseteq$ div ($b$)

Quindi quando vado a fare l'intersezione per i divisori comuni saranno i div ($a$) e quindi l' M.C.D = {$a,-a$}
Esempio: M.C.D (8,24) = {8,-8}

-Se M.C.D ( 0, $b$) = b

-Se considero p e q primi con $p$ $\not$= $q$ l'M.C.D = 1

-Se $a,b$ $\in$ $\mathbb{Z}$ $a$ e $b$ sono coprimi se il M.C.D è uguale a 1

##Teorema di Bezout







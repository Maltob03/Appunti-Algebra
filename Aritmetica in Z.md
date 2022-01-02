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

**Osservazioni**

Siano : $a,b$ $\in$ $\mathbb{Z}$ 

Possiamo scrivere il M.C.D di una coppia come:

$d$ ( $a,b$ ) oppure $a = a_{1} \bullet d$ , $b = b_{1} \bullet d$

E' possibile dimostrare che l'M.C.D tra ( $a_{1}$ , $b_{1}$ ) = 1 ovvero ( $a_{1}$ , $b_{1}$ ) coprimi

Se $c$ / $a_{1}$ e $c$ / $b_{1}$ $\implies$ $c$ / $a$ $\bullet$ b = $a_{1}$ $\bullet$ $d$, $b_{1}$ $\bullet$ $d$

Se $c$ $\not$= 1 , -1 $cd$ / $a$ , $cd$ $b$

$cd$ / $d$

$d$ = $h$ $\bullet$ $cd$ e $hc$ = 1

Se $c$ = +-1 $\implies$ ( $a_{1}$ , $b_{1}$ ) = 1 


##Teorema di Bezout

Siano $a,b$ $\in$ $\mathbb{Z}$ Allora $\exists$ $h,k$ $\in$ $\mathbb{Z}$ : $d$ = $a$ $\bullet$ $h$ + $b$ $\bullet$ $k$ sia M.C.D ($a,b$)

Algoritmo delle divisioni successive

1 caso.
$a=b=0$
$d=0$

2 caso.
$a$ $\not$= 0 e $b=0$
$d=0$

$a$ / $b$ $\rightarrow$ 0 = $a$ $\bullet$ 0

$d$ = $a$ = $a$ $\bullet$ + 0 $\bullet$ $k$

$a$ = $d$

M.C.D ( $a,0$ )

3 caso.

$a$ $\not$= 0 , $b$ $\not$= 0

$\exists$! $q_{1}$ , $r_{1}$ : $a$ = $b$ $\bullet$ $q_{1}$ + $r_{1}$ con 0 $\le$ $r_{1}$ < $|b|$

i) $r_{1}$ = 0 : $a$ = $b$ $\bullet$ $q_{1}$ $\implies$ $b$ / $a$ $\implies$ $b$ è M.C.D di ( $a,b$ ) e tale M.C.D si potrà scrivere come $b$ = $a$ $\bullet$ $0$ + $b$ $\bullet$ $1$ 

ii) $r_{1}$ $\not$= 0 : $b$ = $r_{1}$ $\bullet$ $q_{2}$ + $r_{2}$ con 0 $\le$ $r_{2}$ < $r_{1}$

se $r_{2}$ = 0 $\implies$ $r_{1}$ / $b$ $\implies$ $r_{1}$ / $a,b$ 

$r_{1}$ = $a$ - $b$ $\bullet$ $q_{1}$ OK

se $r_{2}$ $\not$= 0 allora $r_{1}$ = $r_{2}$ $\bullet$ $q_{3}$ + $r_{3}$ con 0 $\le$ $r_{3}$ < $r_{2}$

$r_{2}$ = $b$ - $r_{1}$ $\bullet$ $q_{2}$

se $r_{3}$ = 0 $implies$ $r_{2}$ / $r_{1}$ $implies$ $r_{2}$ / $b$ $\implies$ $r_{2}$ / $q$ $implies$ $r_{2}$ / $a$ , $r_{2}$ / $b$ $\implies$ $r_{2}$ è M.C.D di ( $a,b$ )


**Proposizione** 

Sia $d$ M.C.D ( $a,b$ ) , $d$ $\not$= 0 

Allora $m$ = $\frac{a \bullet b}{d}$ $m$ è m.c.m

$a$ $\not$= 0

Dimostrazione:

$a$ = $d$ $\bullet$ $a_{1}$

$b$ = $d$ $\bullet$ $b_{1}$

( $a_{1} , b_{1}$ )


$m$ = $\frac{a \bullet b}{d}$ = $\frac{ a_{1} \bullet d \bullet b_{1} \bullet d}{d}$ = $a_{1} \bullet b_{1} \bullet d$

i) $m$ = $ a_{1} \bullet b_{1} \bullet d = a_{1} \bullet b$ $\implies$ m è multiplo di $b$ ($b / m$)
$m$ = $ b_{1} \bullet a_{1} \bullet d = b_{1} \bullet a$ $\implies$ $m$ è multiplo di $a$ ( $a / m$)

ii) sia $l=h\bullet a=k\bullet b$

$l = h \bullet a = h \bullet a_{1} \bullet d = k \bullet b_{1} \bullet d$

$h \bullet a_{1} = k \bullet b_{1} \implies b_{1} /$ $h \bullet a_{1}$ e $( b_{1} , a_{1} ) = 1 $ $\implies$ $b_{1}$ / $h$ = $h$ = $h_{1}$ $\bullet$ $b_{1}$

$l$ = $h$ $\bullet$ $a$ = $h_{1}$ $\bullet$ $b_{1}$$a_{1}$$d$ = $h_{1}$ $\bullet$ $m$


####Applicazione Teorema Bezout

$a=27$ 

$b=33$

27 = 33 $\bullet$ 0 +27

$q_{1}$ = 0 e $r_{1}$ = 27

27 = 27 - 33 $\bullet$ 0

$r_{1}$ $\not$= 0 quindi:

33 = 27 $\bullet$ 1 + 6

$q_{2}$ = 1 e $r_{2}$ = 6

6 = 33 - 27 $\bullet$ 1

27 = 6 $\bullet$ 4 +3

$q_{3}$ = 4 e $r_{3}$ = 3

3 = 27 - 6 $\bullet$ 4

6 = 3 $\bullet$ 2 + 0

$q_{4}$ = 2 e $r_{4}$  = 0

$r_{4}$ = 0 ci fermiamo!!!


3 = 27 - 6 $\bullet$ 4 = 27 -4 $\bullet$ ( 33 - 27 ) = 27 - 4 $\bullet$ 33 + 4 $\bullet$ 27 = 5 $\bullet$ 27 - 4 $\bullet$ 33

$h$ = 5 e $k$ = - 4


##Teorema fondamentale dell'aritmetica

Sia $n$ $\in$ $\mathbb{Z}$ \ { 0,1,-1 }

Allora $n$ o è primo o è prodotto di primi e tale decomposizione è unica a meno dell'ordine dei fattori della positività o negatività.

$n$ = $p_{1}$...$p_{t}$ = $q_{1}$...$q_{r}$

con $p_{i}$ e $q_{j}$ primi

Allora:

1. $t=r$ ovvero il numero dei numeri primi che compaiono è lo stesso. E 

$\forall$ $i$ = 1...$t$ $\exists$ $j$ : $p_{1}$ = +- $q_{j}$

**Cioè:**

12 = 2 $\bullet$ 2 $\bullet$ 3 =  -2 $\bullet$ -2 $\bullet$ 3 = 2 $\bullet$ 2 $\bullet$ 2

Come detto su al netto dell'ordine e del segno non cambia la decomposizione. 12 si può scomporre solo in 3 numeri primi i quali saranno necessariamente 2 e 3.



####Dimostrazione del Teorema

Partiamo col dimostrare l'esistenza di tale decomposizione:

Se dimostro vero $\forall$ $n$ > 1 $\implies$ vero $\forall$ $n$ $\forall$ $n$ $\in$ $\mathbb{Z}$ \ { 0, 1 ,-1 } 

$n>1$ $\implies$ $\exists$ $p_{1}$ ... $p_{t}$ primi tali che:

$n = p_{1} \bullet p_{2}...p_{t}$
$-n = -p_{1} \bullet p_{2}...p_{t}$

Quindi se lo dimostro positivo va bene anche per il segno negativo.


Supponiamo $n>1$ per utilizzare il principio d'induzione, ci serve che sia indiciata in $n$.


$P_{n}$ : Sia $n>1$ $n$ = $p_{1}$ ... $p_{t}$ $p_{i}$ primi

$P_{2}$ 2=2 (2 è primo) base d'induzione vera.

$\forall$ $m$ : 2 $\le$ m < n $P_{m}$ sia vera $\implies$ $P_{n}$ vera (passo d'induzione)

$n>2$ :

1. $\not$$\exists$ divisori propri di $n$ quindi i div ($n$) sono quelli banali, quindi $n$ è primo.
L'esistenza è dimostrata.

2. $\exists$ divisori propri di $n$. Quindi 
$n$= $a$ $\bullet$ $b$ con $1 < a,b < n$

$P_{a}$ è vera $: a = p_{1} ... p_{r}$  $con$ $p_{i}$ $primi$

$P_{b}$ è vera $: a = q_{1} ... q_{s}$ $con$ $q_{j}$ $ primi $

Allora $n$ = $a$ $\bullet$ $b$ = ( $p_{1} ... p_{j}$) $\bullet$ ( $q_{1} ... q_{s}$ )

**Esempio:**
60 = 4 $\bullet$ 15 = ( 2 $\bullet$ 2) $\bullet$ ( 3 $\bullet$ 5 )

$a$ = 2 $\bullet$ 2
$b$ = 3 $\bullet$ 5

**Rimane da dimostrare l'unicità**

Sia $n$ = $p_{1}$ ... $p_{t}$ = $q_{1}$ ... $q_{r}$ con $p_{i}$,$q_{j}$ primi

$p_{1}$ / $q_{1}$...$q_{r}$ 

*Background : $p_{1}$ divide $n$ e $n$ è uguale al prodotto $q_{1}$... $q_{r}$ *

Essendo $p_{i}$ numero primo $p_{1}$ / $q_{j}$ ma anche $q_{j}$ è primo quindi $p_{1}$ = +- $q_{j}$


$p_{1}$ = $q_{1}$ 

$p_{1}$($p_{2}$...$p_{t}$) = $q_{1}$($q_{2}$...$q_{r}$)

Semplifica $p_{1}$ e $q_{1}$ e trovi: 

$p_{2}$...$p_{t}$ = $q_{1}$...$p_{a}$

$t=s$ $\forall$ $i$ $\exists$ $j$ : $p_{i}$ = +-$q_{j}$


##Elementi associati

In $\mathbb{Z}$ $a,b$ $\in$ $\mathbb{Z}$ 

$ a \sim b $ ( $a$ associato $b$ ) $\iff$ $a$ = $\pm$b = 1 $\bullet$ $b$ o -1 $\bullet$ $b$


Un altra definzione equivalente è :

$a$ $\sim$ $b$ $\iff$ $\exists$ $u$ inv : a = $u$ $\bullet$ $b$

I div banali ($a$) sono gli elementi invertibili (1,-1) in $\mathbb{Z}$ e gli elementi associati : $a$ e $-a$.

##Teorema di Euclide

Sia $P$ insieme dei numeri primi:

$P$ è infinito 

**Dimostriamo per assurdo**

Per assurdo $P$ finito ovvero:

$P$ = { $p_{}, p_{2}, p_{r}$}

$n$ = $p_{1} \bullet p_{2} \bullet p_{r}$ + 1

Per il teorema fondamentale dell'aritmetica $n$ o è primo o e prodotto di numeri primi  

$\exists$ $p_{i}$ $\in$ $P$ : 

$p_{i}$ / $n$ : $n$ = $h$ $\bullet$ $p_{i}$ = $h$ $\bullet$ $p_{1}$


$h$ $\bullet$ $p_{1}$ = $p_{1}$ $\bullet$ $p_{2}$ ... $p_{r}$ +1 $\rightarrow$ 1 = $h$ $\bullet$ $p_{1}$ + $p_{1}$ $\bullet$ $p_{2}$ ... $p_{r}$ = $p_{1}$($h+p_{2}...p_{r}$) $\implies$ $p_{1}$ / 1 MA i div (1) = {1,-1} ASSURDO


*Allo qua stanno un po di passaggi mentali perchè se lo leggi cosi non si capisce**

Parliamo dell'ultima catena di uguaglianze ( la conclusione della dimostrazione)

h $\bullet$ $p_{1}$ è un modo per scrivere n come prodotto di numeri primi sfruttando il TFDA.
Immagina che la prima uguaglianza sia h $\bullet$ $p_{1}$ = $n$ è la stessa cosa.

Ora dalla definizione di n muovi n a destra dell'uguale e 1 a sinistra. Ora n riportalo come lo abbiamo scritto prima come $h$ $\bullet$ $p_{1}$ e per il resto rimane uguale. Metti in evidenza $p_{1}$ e ti trovi che $p_{1}$ / 1 , un assurdo!!!!!

###Corollario

Sia $n$ $\in$ $\mathbb{Z}$ \ { 0, 1 ,-1}

Allora $n$ = $p_{1}^{\alpha_{1}}$ $\bullet$ $p_{2}^{\alpha_{2}}$ ... $p_{}^{\alpha_{t}}$ 

con $p_{1}...p_{t}$ primi distinti e $\alpha_{i}$ $\geq$ 1 

n = $p_{1}...p_{t}$ = $p_{1}^{\alpha_{1}}$ ... $p_{}^{\alpha_{t}}$

Vale a dire: 

60 = 2 $\bullet$ 2 $\bullet$ 3 $\bullet$ 5 = $2^{2}$ $\bullet$ 5

e quindi $d$ è M.C.D ( $a,b$ ) $\iff$ $d$ è il prodotto di tutti i numeri primi presenti nella decomposizione sia di $a$ che di $b$ ciascuno preso con il minimo esponente.

Supponiamo che :

$a$ = $p_{1}^{\alpha_{1}}$ $\bullet$ $p_{2}^{\alpha_{2}}$ ... $p_{}^{\alpha_{t}}$ 

$b$ = $q_{1}^{\beta_{1}}$ $\bullet$ $q_{2}^{\beta_{2}}$ ... $q_{}^{\beta_{t}}$ 

$d$ = è il prodotto di tutti i fattori primi presenti nella decomposizione di a e nella decomposizione di b 

$d$ = $l_{1}^{\gamma_{1}}...l_{j}^{\gamma_{j}} $ e $\gamma$ = il grado minimo di $\alpha_{i}$ e $\beta_{i}$

$d$ / $a$, $d$ / $b$

se $c$ / $a$ e $c$ / $b$ allora gli unici divisori di $c$ saranno gli $l_{h}$ $\implies$ $c$ / $d$

$m(m.c.m) = a_{1} \bullet b_{1} \bullet d$


##Funzione di Eulero

La funzione di Eulero o indicatore di Gauss-Eulero corrisponde alla seguente funzione.

$f$ : $n \in \mathbb{N}$ \ ${0,1}$ $\rightarrow$ $f(n)$ numero dei numeri primi minori di $n$ e primi con $n$

Esempio:

$f(2)$ = 1
$f(3)$ = 2

In generale se p è primo $f(p)$ = $p-1$

$f(m)$ = | $U(\mathbb{Z}_{m})$ |

ovvero l'ordine degli elementi invertibili di $\mathbb{Z}_{m}$

$f(p \bullet q)$ = $f(p) \bullet f(q)$ = $(p-1) \bullet (q-1)$
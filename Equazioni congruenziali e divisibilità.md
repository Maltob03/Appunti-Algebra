

##Equazioni congruenziali

####Equazioni in $\mathbb{Z}$


In $\mathbb{Z}$ è possibile determinare diversi tipi di equazioni che possono essere risolte o meno.

Esempi:

$2x=-10$ la soluzione è $x=-5$

$2x=11$ l'equazione non ha soluzione quindi $\not\exists$ .

Nel secondo caso non si ha soluzione perchè in $\mathbb{Z}$ 2 non è un elmento invertibile.Fossimo stati in $\mathbb{Q}$ l'equazione avrebbe avuto una soluzione.

####Equazioni congruenziali

Un equazione congruenziale è un equazione del tipo:

$ax \equiv b $ $(mod$ $m)$

$\bar{a} \bullet x \equiv \bar{b}$ in $\mathbb{Z}_{m}$


Trovare una soluzione per questo tipo di equazioni vale a dire determinare un c : $a \bullet c \equiv b$ $mod m$ , in $\mathbb{Z}_{m}$ $\bar{a} \bullet \bar{c} = \bar{b}$ 

Se $c$ è soluzione $\implies$ $c+m \bullet h$ è soluzione in quanto:

$ a \bullet c \equiv b$ si puo scrivere come:

$ a \bullet c - b = m \bullet k$

$ a \bullet ( c + mh) -b $ = $ (a \bullet c - b) + amh = mk + amh = m ( k + ah ) $

e quindi anche $ a \bullet ( c + mh) \equiv b$ $mod$ $m$


In $\mathbb{Z}_{m}$ si può provare lo stesso molto facilmente in quanto se $\bar{c}$ è soluzione allora:

{ $ \bar{c} + m \bullet h $ | $ h $$\in$ $\mathbb{Z}$ }


Con queste basi procediamo con i primi esempi di equazioni congruenziali

1) $6x \equiv 4$ $mod$ $10$ $\rightarrow \bar{6} \bullet x = \bar{4} $ in $\mathbb{Z}_{10}$
2) $6x \equiv 3$ $mod$ $10$ $\rightarrow \bar{6} \bullet x = \bar{3} $ in $\mathbb{Z}_{10}$
3) $7x \equiv 3$ $mod$ $10$ $\rightarrow \bar{7} \bullet x = \bar{3} $ in $\mathbb{Z}_{10}$


1) $ \bar{6} \bullet \bar {4} = 4 $ $\rightarrow$ $ 6 \bullet 4 \equiv 4$ $mod$ $10$ 

e quindi { $4 + h \bullet 10 | h \in \mathbb{Z}$}

**MA** non solo: infatti anche 

$ \bar{6} \bullet \bar{9} = \bar{4}$

e quindi $ 6 \bullet 9 \equiv 4$ $mod$ $10$

{ $9 + h \bullet 10 | h \in \mathbb{Z}$}

2) $\not\exists x$

3) $\exists !$ soluzione $\rightarrow$ $ 7 \bullet 9 \equiv 3$


###Teorema

Sia $ ax \equiv b $ $mod$ $m$ un equazione congruenziale. Tale equazione ammette soluzione $\iff$ 

$d(a,m)$ , $d / b$ ed inoltre il numero delle soluzioni a due a due incongrue modulo m è esattamente $d$ (classi distinte).

**Dimostrazione**

( * ) $ ax \equiv b $ $mod$ $m$ $\rightarrow$ $d=(a,m)$

Considerazioni

$a= a_{1} \bullet d$
$m= m_{1} \bullet d$
$b= b_{1} \bullet d$

Svolgimento

$a_{1} \bullet dx \equiv b_{1} \bullet d$ ($mod$ $m$) 

**RICORDA**

$ a \bullet c \equiv b$ si puo scrivere come:

$ a \bullet c - b = m \bullet k$

**QUINDI**

$d(a_{1}x - b_{1})$ $\equiv$ $dm_{1} \bullet h$

semplifico le d e trovo:

$a_{1}x -b_{1}$ = $m_{1} \bullet h$

( ** ) $a_{1}X \equiv b_{1}$ $mod$ $m_{1}$ con ( $a_{1}, m_{1}$ ) = 1

1 lo possiamo esprimere combinazione lineare del prodotto tra $a_{1} , m_{1}$ e quindi

1 = $h \bullet a_{1} + k \bullet m_{1}$ per il teorema di Bezout

$b_{1} = b_{1} \bullet 1 = b_{i} \bullet ( h \bullet a_{1} + k \bullet m_{1}) = hb_{1} \bullet a_{1} + kb_{1} \bullet m_{1}$

E quindi trovo che:

$a_{1} \bullet ( h \bullet b_{1}) \equiv b_{1} $ $mod$ $m_{1}$

( *** ) $a_{1}x \equiv 1$ $mod$ $m_{1}$

Se $c_{1}$ è soluzione di ( ** ) ovvero:

$a_{1} \bullet c_{1} \equiv b_{1}$ $mod$ $m_{1}$

Quindi:

$a_{1} \bullet c_{1} - b_{1} = l \bullet m_{1}$

Moltiplichiamo tutto per $d$ e otteniamo

$ ( a_{1} \bullet d ) \bullet c_{1} - (b_{1} \bullet d ) = ldm_{1}$

Considero ora $c_{2} = c_{1} + m_{1}$
e $c_{3} = c_{1} + 2m_{1}$ fino ad arrivare a 

$cd = c_{1} + (d-1)m$

L'insieme delle soluzioni distinte sarà dato da :

- $c_{1}$
- $c_{1}+m_{1}$
- $c_{1}+2m_{1}$
- ...
- $c_{1}+(d-1)m_{1}$



####Riprendiamo l'esempio di prima


1) $6x \equiv 4$ $mod$ $10$ $\rightarrow \bar{6} \bullet x = \bar{4} $ in $\mathbb{Z}_{10}$

Avevamo visto che la prima soluzione era 4.

$m è 10$

$m_{1}$ = $\frac{10}{2}$ = $5$

quindi le soluzioni sono $\bar{4} $ e $\bar{4+5}=\bar{9}$


####Completiamo la dimostrazione.

Rimane da dimostrare che se $ax \equiv b$ $mod$ $m$ ammette soluzioni allora $d=(a,m)$ / $b$

Sia $c$ una soluzione allora vuol dire che :

$a \bullet c \equiv b$ $mod$ $m$

$a \bullet c -b$ = $h \bullet m$

$a \bullet c - h \bullet m = b$

Se $d / (a,m) $ $\implies$ $d / l \bullet a + s \bullet m $ $ \forall s,l \in \mathbb{Z} \implies d/a \bullet c - h \bullet m = b$ 


###Risolviamo equazioni congruenziali

1) $12576 x \equiv 23 $ $mod$ 104 

Ragioniamo abbiamo detto che un equazione congruenziale se e solo se il M.C.D divide $b$

*In questo caso abbiamo che il M.C.D fra 12576 e 104 qualsiasi sia sarà maggiore di 1 e sicuramente pari. Un numero pari non può dividere un numero dispari quindi quest'equazione non ammette soluzione.*

$d$ = 2 $\bullet$ $k$ e non divide 23 (dispari)

2) $105x \equiv 75$ $mod$ $115$

M.C.D ( 105, 115 ) = 5

$105 =  3 \bullet 5 \bullet 7 $
$75 =  3 \bullet 5^{2}$
$115 =  3 \bullet 23$ 

Per costruirmi l'equazione 2-star divido tutto per 5

( ** ) $21 \bullet x \equiv 15$ $mod$ $23$

Ora poichè 21 e 23 sono primi tra loro passo all'equazione 3-star in modo da avere le soluzioni per ogni combinazione lineare.

( *** ) $21x \equiv 1$ $mod$ $23$

$23 = 21 \bullet 1 + 2$

$2 = 23 - 21 \bullet 1$

$21 = 2 \bullet 10 + 1$

$1 = 21 - 2 \bullet 10$

Quindi:

$1 = 21 - 2 \bullet 10 $ = $21 - 10 \bullet 2$ = $21 - 10 \bullet ( 23 - 21 )$ = $ -10 \bullet 23 + 11 \bullet 21$ 

La soluzione di 3-star è il coefficiente per il quale è moltiplicato 21 quindi 11.

Per avere la soluzione di 2-star devo moltiplicare $c_{1}$ per $b_{1}$ ovvero :

$11 \bullet 15 = 165$

$165$ si puo ridurre modulo 23 e quindi risulta essere uguale a :

$165 = 23 \bullet 7 +4$

quindi da 165 passo a 4

$4$ quindi risulta essere una soluzione 

Le altre soluzioni saranno : 
 $4$
 $4 + 23$
 $4+2 \bullet 23$
 $4+3 \bullet 23$
 $4+4 \bullet 23$
 

##Criteri di divisibilità

Consideriamo $ a \in \mathbb{Z}$

$m$ / $a$ $\iff [a]_{m} = [0]_{m}$

####Divisibilità in generale

$a$ si puo scrivere tramite scrittura polinomiale

Supponiamo che $a$ sia uguale a:

$a = 10122 = 2 \bullet 10^{0} + 2 \bullet 10^{1} + 1 \bullet 10^{2} + 0 \bullet 10^{3} + 1 \bullet 10^{4}$

##Divisibilità

###Divisibilità per 2 e per 5

$ [0]_{2} = [a]_{2} $?

$ [a]_{2} = [c_{0}] + [c \bullet 10] + ... + [c_{t} \bullet 10^{t} ] = [c_{0}]$

Il perchè rimanga solamente la classe $[c_{0}]$ è semplice: 10 in $\mathbb{Z}_{2}$ è uguale a 0 quindi rimane solo l'ultima cifra da analizzare. Se pari l'ultima cifra il numero è divisibile per due mentre se dispari non è divisibilie per 2.

Lo stesso discorso può essere affrontato per 5 in quanto anche in $\mathbb{Z}_{5}$ 10 è uguale a 0 e rimane solo l'ultima cifra da analizzare. Se uguale a 0 o 5 allora il numero è divisibile per 5

Quindi con $n \geq 1$ $[10]^{n}_{2} = [{0}]_{2}$ e $[10]^{n}_{5} = [{0}]_{5}$

###Divisibilità per 4 e per 25

Il discorso è molto simile. Supponiamo di avere $m = 4 o 25$ 

$[0]_{m} =  [c_{0}] + [c_{1} \bullet 10] + [c_{2} \bullet 10] + ... + [c_{t} \bullet 10^{t} ] = [c_{0}]$

Da $10^{2}$ tutte le classi vanno a 0 quando $m=2,25$ quindi si considerano solo le prime due cifre.

Quindi con $n \geq 2$ $[10]^{n}_{4} = [{0}]_{4}$ e $[10]^{n}_{25} = [{0}]_{25}$

###Divisibilità per 3 per 9

Un numero è divisibile per 3 o per 9 quando la somma delle cifre è divisibile per 3 o per 9.

$ [ 10 ]_{3} = [1]$ ho che $\forall$$n$ $[10]^{n}_{3}$ = $[1]$

Quindi:

$[c_{t}...c_{0}] = [c_{t} \bullet 10^{t}]_{3} + [c_{t-1} \bullet 10^{t-1}]_{3} ...+... [c_{0}]_{3} $ = $ [c_{t}] \bullet [10]^{t}_{3} + [c_{t-1]}] \bullet [10]^{t-1}_{3} + ... + [c_{1}] \bullet [10]_{3} + [c_{0}]_{3} = $$ [c_{t}]_{3}] + [c_{t-1}]_{3}] + ... + [c_{1}] + [c_{0}]_{3}$ = 

$[c_{t} + c_{t-1} + ... + c_{1} + c_{0}]$ = $[0]_{3}$

Stesso discorso base 9



###Divisibilità per 11


$[10]_{11} = [-1]_{11}$

$[10]^{2}_{11} = [-1]^{2}_{11} = [1]_{11}$

$[10]^{2n}_{11} = [1]_{11}$

$[10]^{2n+1}_{11} = [-1]^{2}_{11}$

$n = c_{t} \bullet c_{t-1} ... \bullet c_{1} \bullet c_{0} =$ $[0]_{11} = [n]_{11} = [c_{0}] - [c_{1}] + [c_{2}] ... (-1)^{t} \bullet [c_{t}] = [0]$


Con i criteri di divisibilità posso avere subito il resto:

rest ( 74642 , 3 ) = 2
rest ( 74642 , 9 ) = 5

IN questo caso la somma delle cifre viene 23 e quindi 2+3=5. Dividendo per 3 il resto è 2, dividendo per 9 il resto è 4

rest ( 74642, 11) = 4

Sfrutto criterio divisione per 11 ed il resto è 7
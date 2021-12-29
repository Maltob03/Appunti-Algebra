#Operazioni e strutture algebriche #2




<br>

##Multipli di un insieme

Consideriamo l'anello ( $\mathbb{Z}$, $+$ , $\bullet$ }

$n$$\mathbb{Z}$ = { $n$ $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ }

Che corrisponde all'insieme degli $n$ $\bullet$ $h$ al variare di $h$ in $\mathbb{Z}$ ovvero tutti i multipli di $n$

Esempi:

0$\mathbb{Z}$ = { 0 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ }

1$\mathbb{Z}$ = { 1 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } = $\mathbb{Z}$

2$\mathbb{Z}$ = { 2 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } = numeri pari

3$\mathbb{Z}$ = { 3 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } multipli di 3 in $\mathbb{Z}$ 

6$\mathbb{Z}$ = { 6 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } 6$\mathbb{Z}$ = 2$\mathbb{Z}$ $\bigcap$ 3$\mathbb{Z}$

$m/n$ $\iff$ $n$$\mathbb{Z}$ $\subseteq$ $m$$\mathbb{Z}$

Osservazioni:

1. $\forall$ $n$$\mathbb{Z}$ = $(-n)$$\mathbb{Z}$ coincidono.
2. $n$$\mathbb{Z}$ è stabile sia per l'operazione ($+$) sia ($*$)


Dimostrazione prima osservazione:

$n$$\mathbb{Z}$ = { $n$ $\bullet$ $h$ $\in$ $\mathbb{Z}$ } = { ($-n$) $\bullet$ ($-h$) = $n$ $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ = ($-n$)$\mathbb{Z}$ }

Dimostrazione seconda osservazione:

Suppongo di avere $l,m$ $\in$ $\mathbb{Z}$ con
$l$ = $n$ $\bullet$ $h$
$m$ = $n$ $\bullet$ $k$

$l+m$ = $n$ $\bullet$ $h$ + $n$ $\bullet$ $k$ = $n$ $\bullet$ ( $h+k$ ) $\in$ $n$$\mathbb{Z}$

$l$ $\bullet$ $m$ = $n$ $\bullet$ $h$ $\bullet$ $n$ $\bullet$ $k$ = $n$ $\bullet$ ( $h$ $\bullet$ $k$ $\bullet$ $n$ ) $\in$ $n$$\mathbb{Z}$

---


Si può dimostrare che $X$ $\subseteq$ $\mathbb{Z}$ è stabile rispetto alle due operazioni $\implies$ $\exists$$n$ : $x$ = $n$$\mathbb{Z}$

Dimostrazione:

i) $x$ = {0} e ( $x$ , $+$ ) è gruppo $\implies$ $x=0$$\mathbb{Z}$ 

ii) $x$ $\not$= 0 $m$ $\in$ $X$ $m$ $\not$= 0 $\implies$ $-m$ $\in$ $X$ , $m+(-m)$ = 0 $\in$ $X$


Definiamo $X^{+}$ = { $l$ $\in$ $X$ | $l>0$ }

$x$ $\not$= {0} 

$m$ $\in$ $X$ $\rightarrow$ $-m$ $\in$ $X$

n = minimo di $X^{+}$

$n$$\mathbb{Z}$ = $x$

sappiamo che (n+n+n+...+n) h volte è stabile $\in$ $X$ e anche il suo opposto -(n+n+n+...+n) è stabile


$m$ $\in$ $X^{+}$ 

$m$ = $n$ $\bullet$ $q$ + $r$ con 0$\leq$$r$$<$$n$

$r$ = $m$ - $n$ $\bullet$ $q$ opp $r$ = 0

e quindi $m$ = $n$ $\bullet$ $q$

con m $\in$ $n$$\mathbb{Z}$ 

$n$$\mathbb{Z}$ = $X$


##Sottogruppo

Una parte $H$ inclusa in $S$ con ( $S$ , $+$ ) è un sottogruppo $\iff$

( $H$ , $+$ ) è stabile
( $H$ , $+$ ) è un gruppo

$H$ $\subseteq$ $\mathbb{Z}$ $\iff$ $H$ = $n$$\mathbb{Z}$ ( $n$ $\in$ $\mathbb{N}$ )

##Parte stabile

$x$ $\subseteq$ $S$ con ( $S$ , $*$ )

$L(X)$ = $<X>$ = parte stabile generata da $x$.

$x$ è parte stabile $\iff$ $ x= <x> $

Esempi di parte stabile genertata:

( $\mathbb{Z}$, $\bullet$ ) < {$-1$} > = {-1, 1}

( $\mathbb{Z}$ , $+$ ) < {$-1$} > = { $-h$ | $h$ $\in$ $\mathbb{N^{*}}$}


( $\mathbb{Z}$, $+$ ) < {$2$} > = 2$\mathbb{N^{*}}$ = { 2 $\bullet$ $h$ | h $\in$ $\mathbb{N^{*}}$}

( $\mathbb{Z}$ , $+$ ) < {$2$} > = { $2^{n}$ | $n$ $\in$ $\mathbb{N^{*}}$}


##Congruenza

Consideriamo un generico ( $S$ , $*$ ) con $R$ relazione di equivalenza in $S$

$R$ è una congruenza $\iff$

$\forall$ $a,b,c,d$ $\in$ $S$ :

$aRc$ e $bRd$ $\implies$ ( $a$$*$$b$ ) $R$ ( $c$$*$$d$ )

$R$ deve essere compatibile con l'operazione $*$

Definiamo l'insieme quoziente $S_{R}$ = { $[a]_{R}$ | $a$ $\in$ $S$ }

$[a]_{R}$ = $[c]_{R}$ $\iff$ $aRc$

Se $aRc$ ovvero ( $[a]_{R}$ = $[c]_{R}$) e $bRd$ ovvero ($[b]_{R}$ = $[d]_{R}$) $\implies$ ($a*b$)$R$($c*d$) $\implies$ $[a*b]_{R}$ = $[c*d]_{R}$

Si può quindi definire un operazione nella struttura insieme quoziente:

$*$ : ( $[a]_{R}$,$[b]_{R}$ ) $\in$ $S_{R}$ x $S_{R}$ $\rightarrow$ $[a]_{R}$ * $[b]_{R}$ = $[a*b]_{R}$ $\in$ $S_{R}$


Facciamo un esempio in $\mathbb{Z}$ $aRb$ $\iff$ $|a| = |b|$

$[a]$ = { $a, -a$ }
$\mathbb{Z}_{R}$ = { $[a]_{R}$ | $a$ $\in$ $\mathbb{Z}$}

( $\mathbb{Z}$ , $\bullet$ ) $R$ è compatibile perchè se suppongo che :

$aRc$ ( $|a| = |c|$) e $bRd$ ( $|b| = |d|$) allora

$| a$ $\bullet$ $b |$ = $|a|$ $\bullet$ $|b|$ = $|c|$ $\bullet$ $|d|$ = $| c$ $\bullet$ $d |$

Se considero l'operazione :

$\bullet$ : ( $[a]_{R}$,$[b]_{R}$ ) $\rightarrow$ $[a $$\bullet$$b]_{R}$

Esempio pratico:

$\bullet$ : ( $[2]_{R}$,$[-5]_{R}$ ) $\rightarrow$ $[2 $$\bullet$$-5]_{R}$ = $-10$

$\bullet$ : ( $[2]_{R}$,$[5]_{R}$ ) $\rightarrow$ $[2 $$\bullet$$5]_{R}$ = $10$

Il risultato delle due operazioni rappresenta la stessa classe quindi equivalente quindi compatibile con la moltiplicazione.

**NON E' COMPATIBILE CON L'ADDIZIONE**

$[-3] = [2] + [-5]$ $\not$= $[2] + [5] = [7]$ 


##Congruenze modulo m in $\mathbb{Z}$

Nell'anello ( $\mathbb{Z}$ , $+$ , $\bullet$ ) sono definite le congruenze modulo $m$ : $m$ $\in$ $\mathbb{Z}$

$m$$\mathbb{Z}$ = { $m$ $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } = { ($-m$) $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } = ($-m$)$\mathbb{Z}$

($m$$\mathbb{Z}$ , $+$ ) **gruppo abeliano**
($m$$\mathbb{Z}$ , $\bullet$ ) **stabile**

$a$ ($m$$\mathbb{Z}$) $b$ oppure ( a $\equiv_{m}$ $b$ , oppure $a$ $\equiv$ $b$ ($mod$ $m$) $\iff$

$\exists$ $h$ $\in$ $\mathbb{Z}$ : $a-b$ = $m$$\bullet$ $h$ $\iff$ $a-b$ $\in$ $m$$\mathbb{Z}$

Se $m$ = 0  $a$ $\equiv_{0}$ $b$ $\iff$ $a-b$ = 0 $\bullet$ $h$ = 0 $\iff$ $a=b$ 

0$\mathbb{Z}$= $id_{Z}$

Se $m$ = 1 $a$ $\equiv$ $b$ $\iff$ $a-b$ = 1 $\bullet$ $h$

1$\mathbb{Z}$ = $tot$ $\mathbb{Z}$


####Proposizione : $m$$\mathbb{Z}$ è una relazione di equivalenza ed è compatibile con le operazioni $+$ , $\bullet$.

**Per vedere che la relazione $m$$\mathbb{Z}$ sia di equivalenza dobbiamo verificare che :**

1. **Riflessiva** :  $\forall$ $n$ $\in$ $\mathbb{Z}$ 

$n$ ($m$$\mathbb{Z}$) $n$  $\iff$ $n-n$ = $0$ = $m$ $\bullet$ $0$

2. **Simmetrica** : $\forall$ $x,y$ $\in$ $\mathbb{Z}$ se $x$ ($m$$\mathbb{Z}$) y $\iff$ $x-y =$ $m$ $\bullet$ $h$ $\implies$ $y-x = -(x-y) = $ - ($m$ $\bullet$ $h$ ) = $m$ $\bullet$ ($-h$) $\implies$ $y$ ($m$$\mathbb{Z}$)$x$

3. **Transitiva** : $\forall$ $x,y,z$ $\in$ $\mathbb{Z}$

Consideriamo $x$($m$$\mathbb{Z}$)$y$ e $y$($m$$\mathbb{Z}$)$z$

Quindi: $x$ - $y$ = $m$ $\bullet$ $h$ 
Quindi: $y$ - $z$ = $m$ $\bullet$ $k$

Sommiamo membro a membro e otteniamo;

($x-y$) + ($y-z$) = $m$ $\bullet$ ($h+k$)

= a $x-z$ = $m$ $h$ $\bullet$ $k$ $\implies$ $x$($m$$\mathbb{Z}$)$z$

---
($m$$\mathbb{Z}$) **è una congruenza** $(+)$ , ( $\bullet$ ) 

Operazione ($+$)

$a$ ($m$$\mathbb{Z}$) $c$
$b$ ($m$$\mathbb{Z}$) $d$

$a-c$ = $m$ $\bullet$ $h$
$b-d$ = $m$ $\bullet$ $k$

Sommo membro a membro

($a+b$) - ($c+d$) = $m$ $\bullet$ ($h+k$)

($a+b$) ($m$$\mathbb{Z}$) ($c+d$)

---
Operazione ( $\bullet$ ) 
 
 
$a$ ($m$$\mathbb{Z}$) $c$
$b$ ($m$$\mathbb{Z}$) $d$

$a$ = $c$ + $m$ $\bullet$ $h$
$b$ = $d$ + $m$ $\bullet$ $k$

Stavolta moltiplico membro a membro e ottengo:

$a$ $\bullet$ $b$ = ( $c$ + $mh$ ) ( $d$ + $mk$ ) = $cd$ + $m$( $ck$ + $hd$ + $mhk$ ) = $ab$ - $cd$ = $m$($l$) dove $l$ è la quantità tra parentesi nella precedente equivalenza

Quindi $ab$ ($m$$\mathbb{Z}$) $cd$ 

---

$m$$\mathbb{Z}$ Risulta essere una congruenza in $\mathbb{Z}$



###Teorema

$\forall$ $a,b$ $\in$ $\mathbb{Z}$ e $b$ $\not$= 0 $\exists$! ($q,r$):

$a=$ $b$ $\bullet$ $q$ + $r$ con 0$\le$$r$<$|b|$

$r$ = $rest(a,b)$

**Proposizione Sia $m$ > 0**

$a$ $\equiv$ $b$ $(mod$ $m)$ $\iff$ $rest(a,m)$ = $rest(b,m)$

$\leftarrow$

$rest(a,m)$ = $rest(b,m)$ = $r$

$a$ = $m$ $\bullet$ $q_{1}$ +$r$
$a$ = $m$ $\bullet$ $q_{2}$ +$r$

sottraggo membro a membro e ottengo:

$a-b$ = $m$($q_{1}$ - $q_{2}$) $\rightarrow$ $a$$\equiv_{m}$$b$

$\rightarrow$

$a$$\equiv_{m}$$b$ $\implies$ $rest(a,m)$ = $rest(b,m)$

$a$ = $m$ $\bullet$ $q_{1}$ +$r_{1}$
$a$ = $m$ $\bullet$ $q_{2}$ +$r_{2}$

0$\le$$r_{1}$<$|m|$
0$\le$$r_{2}$<$|m|$

Poniamo per ipotesi che $r_{1}$ > $r_{2}$

Sottraendo membro a membro otteniamo:

$a-b$ = $m$($q_{1}$ - $q_{2}$) + ( $r_{1}$ - $r_{2}$ )

sappiamo che $a-b$ essendo una congruenza è uguale a $m$ $\bullet$ $h$

quindi otteniamo

$m$ $\bullet$ $h$ = $a-b$ = $m$($q_{1}$ - $q_{2}$) + ( $r_{1}$ - $r_{2}$ )

Ora sappiamo per ipotesi che la quantità $r_{1}$ - $r_{2}$ sia maggiore o uguale a 0 e strettamente minore di $m$.

$r_{1}$ - $r_{2}$ è un multiplo di $m$. Per rispettare le condizioni elencate prima ($\le$0 e >$m$) $r_{1}$ - $r_{2}$ deve per forza essere = 0 e quindi :

$r_{1}$ = $r_{2}$


####Caratterizzazione

Se m>0

Possiamo definire un operazione $*$

($*$) $a$ $\equiv$ $b$ $\iff$ $rest(a,m)$ = $rest(b,m)$

$a$ $\in$ $\mathbb{Z}$

**$m=0$** 

$\rightarrow$ $[a]_{0}$ = {a} 

$\mathbb{Z}_{0Z}$ = { {$a$} | $a$ $\in$ $\mathbb{Z}$ }

**$m=1$** 

$\rightarrow$ $[a]_{1}$ = $\mathbb{Z}$  

$\mathbb{Z}_{1Z}$ =  {$\mathbb{Z}$ }

**$m>1$** 

$[a]_{m}$ = { $b$ | $a-b$ = $m$ $\bullet$ $h$ con $h$ $\in$ $\mathbb{Z}$ } = 

$[rest(a,m)]$ = { $a+m$ $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ }

$a$ $\equiv$ $rest(a,m)$ 

$aRb$ $\iff$ $[a]_{R}$ = $[b]_{R}$


####Facciamo un esempio pratico:

m=2 e 5 $\in$ $\mathbb{Z}$

$[5]_{2}$ = { 5 + 2 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } = $[1]_{2}$ = [$rest(5,2)=1$] = { 1+2 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } e corrisponde alla classe dispari.


$[16]_{2}$ = { 16 + 2 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } = $[0]_{2}$ = [$rest(16,2)=0$] = { 2 $\bullet$ $h$ | $h$ $\in$ $\mathbb{Z}$ } e corrisponde alla classe dei numeri pari


$\mathbb{Z}_{2}$ = $\mathbb{Z}_{2Z}$ = { $[0]$ , $[1] $ }

----

**Proposizione** 

$\forall$ m $\geq$ 1 l'ordine di $\mathbb{Z}_{m}$ = $m$
quindi |$\mathbb{Z}_{m}$| = $m$ e $\mathbb{Z}_{m}$ è rappresentato da :

$\mathbb{Z}_{m}$ = { $[0]_{m}$ , $[1]_{m}$ , ... , $[m-1]_{m}$ } ovvero tutti i possibili resti.

**Dimostrazione:**

Sappiamo che $\forall$ $a$ $\in$ $\mathbb{Z}$

$[a]_{m}$ = $[rest(a,m)]_{m}$ $\in$ { $[0]_{m}$ , ... , $[m-1]_{m}$ } quindi

$\mathbb{Z}_{m}$ = { $[0]_{m}$ , $[1]_{m}$ , ... , $[m-1]_{m}$

devo verificare che tale insieme ha ordine $m$ , ossia che se prendo 0 $\le$ $i,j$ $\le$ $m-1$ e $i$ $\not$= $j$ $\implies$ $[i]_{m}$ $\not$= $[j]_{m}$

Supponiamo $i$ $\geq$ $j$

0$\le$ $i-j$ $<$$m$ se $i$ $\equiv$ $j$ ($mod$ $m$) $\implies$ $i-j$ multiplo di $m$ $\implies$ $i-j=0$ $\implies$ $i=j$

####Esercizio di esempio

$\mathbb{Z}_{7}$ = { $[0]_{7}$ , $[1]_{7}$ , $[2]_{7}$ , $[3]_{7}$ , $[4]_{7}$ , $[5]_{7}$ , $[6]_{7}$ }

$[-17]_{7}$ a quale classe corrisponde ???

-17 = 7 $\bullet$ (-3) + 4

quindi corrisponde alla classe $[4]_{7}$



##L'anello dell'insieme resto

**Proposizione:** ( $\mathbb{Z}_{m}$ , $+$ , $\bullet$ ) è un anello commutativo unitario.

**Dimostrazione:** 

( $\mathbb{Z}_{m}$ , $+$ ) gruppo abeliano: 

$\forall$ $[a]_{m}$,$[b]_{m}$,$[c]_{m}$

*Associatività*

$[a]_{m}$ + ( $[b]_{m}$ + $[c]_{m}$ ) = $[a]_{m}$ + $[b+c]_{m}$ = $[a + (b+c)]_{m}$ = $[(a+b)+ c]_{m}$ = $[a+b]_{m}$ + $[c]_{m}$ = ( $[a]_{m}$ + $[b]_{m}$ ) + $[c]_{m}$

*Commutatività nello stesso modo*

*Elemento neutro*

la classe $[0]_{m}$ è elmento neutro in quanto:

$[a]_{m}$ + $[0]_{m}$ = $[a+0]_{m}$ = $[a]_{m}$

$[0]_{m}$ ci sono tutti i multipli di m 

**Proprietà**

$-[a]_{m}$  = $[-a]_{m}$ = $[0]_{m}$ + $[-a]_{m}$ = $[m]_{m}$ + $[-a]_{m}$ = $[m-a]_{m}$

Questo che significa:

se prendiamo $[-17]_{7}$ = $[7-17]_{7}$ = $[10]_{7}$ = $[7-10]_{7}$ = $[-3]_{7}$ = $[7-3]_{7}$ = $[4]_{7}$

##Omomorfismi e isomorfismi

Consideriamo due strutture ( $S$ , $*$ ) e ( $T$ , $\circ$ )

l'applicazione $f$ : $S$ $\rightarrow$ $T$ $\iff$ $\forall$ $a,b$ $\in$ $S$ 

$f(a*b)$ = $f(a)$ $\circ$ $f(b)$

Se $f$ è omomorfismo inettivo si dice MONOMORFISMO
Se $f$ è omomorfismo suriettivo si dice EPIMORFISMO
Se $f$ è omomorfismo biettivo si dice ISOMORFISMO

Esempio:

Considera : ( $\mathbb{Z}$ , $+$ ) e ( $\mathbb{Q}$ , $\bullet$ ) e verifica se la seguente applicazione è un omomorfismo e di che tipo.

$f$ : $a$ $\in$ $\mathbb{Z}$ $\rightarrow$ $2^{a}$ $\in$ $\mathbb{Q}$


Quindi devo verificare che :

$f(a+b)$ = $f(a)$ $\bullet$ $f(b)$

$2^{a+b}$ = $2^{a}$ $\bullet$ $2^{b}$ = $2^{a+b}$

omomorfismo (monomorfismo)

Se consideriamo ( $\mathbb{Z}$ , $+$ ) e ( $\mathbb{Q}$ , $+$ )

$f(a+b)$ = $f(a)$ $+$ $f(b)$

$2$^{$a$ $\bullet$ $b$} $\not$=  $2^{a+b}$

**Niente isomorfismo**


##Divisori dello Zero

In un anello ( $A$ , $+$ , $*$) un elemento $a$ $\in$ $A$, con $a$ $\not$= 0 si dice divisore dello 0 se esiste un $b$ $\in$ $A$, $b$ $\not$= 0 tale che sia $a$ $\bullet$ $b$ = 0, oppure $b$ $\bullet$ $a$ = 0

In ( $\mathbb{Z}_{6}$ , $+$ , $\bullet$ ) $[2]$ e $[3]$ sono divisori dello zero. Questo tipo di anello non è stato ancora affrontato vedremo poi nel dettaglio.

( $\mathbb{Z}$ , $+$ , $\bullet$ )
( $\mathbb{Q}$ , $+$ , $\bullet$ )
( $\mathbb{Z}_{5}$ , $+$ , $\bullet$ )

Sono privi di divisori dello zero.

Se un elemento è divisore dello zero non può essere invertibile

Per essere elemento invertibile deve dare resto 1 ad esempio

$\mathbb{Z}_10$ = $\{ 0,1,2,3,4,5,6,7,8,9\}$

$U$($\mathbb{Z}_{10}$) = $\{ 1 , 3 , 7 , 9\}$

Div dello zero = $\{ 2, 5, 4, 6 , 8 \}$


####Teorema 

Sia a $\in$ $\mathbb{Z}_{m}^{*}$ = $\mathbb{Z}_{m}$ \ {0}

i) a è divisore dello 0 $\iff$ M.C.D ($ a , m$) $\not$= 1

ii) a è invertibile $\iff$ M.C.D ($ a, m$) = 1


##Dominio d'integrità

Un domminio d'integrità è un anello commutativo privo di divisori dello zero. Più precisamente un anello ( $A$ , $+$ , $\bullet$ ) è un dominio d'integrità $\iff$

$\forall$ $a,b$ $\in$ $A$ 

$a$ $\bullet$ $b$ = $b$ $\bullet$ $a$
$a$ $\bullet$ $b$ = 0 $\implies$ $a=0$ $\lor$ $b=0$

Esempio di dominio d'integrità sono:

( $\mathbb{Z}$ , $+$ , $\bullet$ )

( $\mathbb{Z}_{5}$ , $+$ , $\bullet$ ) o tutti gli $\mathbb{Z}_{m}$ con $m$ numero primo


##Elementi nilpotenti

Elementi nilpotenti in un anello unitario:

$a$ $\in$ $A$ nilpotente se $\exists$ $n$ > 0 :

$a^{n}$ = 0

Esempio:

$[4]_{8}$ 

$[4]_{8}^{2}$ = 0  

$[4]_{8}^{3}$ = 0

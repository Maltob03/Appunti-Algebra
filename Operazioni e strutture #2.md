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


##Conguenza

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


##Dominio d'integrità

Un domminio d'integrità è un anello commutativo privo di divisori dello zero. Più precisamente un anello ( $A$ , $+$ , $\bullet$ ) è un dominio d'integrità $\iff$

$\forall$ $a,b$ $\in$ $A$ 

$a$ $\bullet$ $b$ = $b$ $\bullet$ $a$
$a$ $\bullet$ $b$ = 0 $\implies$ $a=0$ $\lor$ $b=0$

Esempio di dominio d'integrità sono:

( $\mathbb{Z}$ , $+$ , $\bullet$ )

( $\mathbb{Z}_{5}$ , $+$ , $\bullet$ ) o tutti gli $\mathbb{Z}_{m}$ con $m$ numero primo

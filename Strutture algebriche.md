#Operazioni e strutture algebriche

Dati un insieme $S$ = 0 ed un operazione binaria interna $\perp$ tale che:

($S$, $\perp$)


($S$, $\perp$) si dice **$semigruppo$** $\iff$ $\perp$ gode della proprietà associativa

$\\forall$ $a,b,c$ $\in$ $S$ :

$a$ $\perp$ ( $b$ $\perp$ $c$) = ( $a$ $\perp$  $b$ ) $\perp$ $c$ = $a$ $\perp$  $b$ $\perp$ $c$


Esempi di **semigruppi** sono:

( $\mathbb{N}$ , + ) e ( $\mathbb{N}$ , $\bullet$ ) 
( $\mathbb{Z}$ , + ) e ( $\mathbb{Z}$ , $\bullet$ ) 
( $\mathbb{K}$ , + ) e ( $\mathbb{K}$ , $\bullet$ ) 


( $\mathbb{Z}$ , - )  non è un semigruppo perchè 5-(3-2) $\not$ = (5-3)-2

( $\mathbb{K}$ , - )  non è un semigruppo


L'operazione divisione non gode della proprietà associativa, quindi non risulta essere un semigruppo


L'operazione di composizione gode della proprietà associativa, quindi ($S^{S}$, $\circ$) è un semigruppo.

Rispetto a $P(s)$ le operazioni di $\bigcup$, $\bigcap$, e $\Delta$ godono della proprietà associativa quindi sono semigruppo.

$P(s)$ rispetto alla operazione complemento non gode della proprietà associativa quindi non è un semigruppo.


###Semigruppi commutativi

Se oltre a essere semigruppi (e quindi godere della proprietà associativa) godono della proprietà commutativa questi si dicono semigruppi commutativi.

Esempi di semigruppi commutativi sono:

$\forall$ $a,b,c$ $\in$ $S$ : $a$ $\perp$ $b$ = $b$ $\perp$ $a$

( $\mathbb{N}$ , + ) e ( $\mathbb{N}$ , $\bullet$ ) 
( $\mathbb{Z}$ , + ) e ( $\mathbb{Z}$ , $\bullet$ ) 
( $\mathbb{K}$ , + ) e ( $\mathbb{K}$ , $\bullet$ ) 

Esempio di semigruppo non commutativo : ($S^{S}$, $\circ$)



##Elemento neutro

Dato un semigruppo:

($S$, $\perp$) 

L'elemento neutro rispetto all'operazione $\perp$ è definito $\iff$

$\forall$ $a$ $\in$ $S$ 

$a$ $\perp$ $u$ = $u$ $\perp$ $a$ = $a$

Esempi di elementi neutri

per ($S$ , + ) $u$ = 0
per ($S$ , $\bullet$ ) $u$ = 1

In $R^{2}$ gli elementi neutri per addizione e moltiplicazione sono rispettivamente (0,0) e (1,1).

L'elemento neutro per il semigruppo ($S^{S}$, $\circ$) corrisponde all' $id_{s}$.

Per quanto riguarda $P(s)$:

($P(s)$, $\bigcap$ ) : $A$ $\bigcap$ $S$ = $A$ = $S$ $\bigcap$ $A$. 

Quindi $u$ = $S$

($P(s)$, $\bigcup$ ) : $A$ $\bigcup$ $\varnothing$ = $A$ = $\varnothing$ $\bigcup$ $A$.

Quindi $u$ = $\varnothing$


($P(s)$, $\Delta$ ) : $A$ $\Delta$ $\varnothing$ = $A$ = $S$ $\Delta$ $\varnothing$.


**Quando un semigruppo possiede elemento neutro questo si dice Monoide**


##Monoide

($S$, $\perp$) è MONOIDE $\iff$

 1. ($S$, $\perp$) è un semigruppo
 2. $\exists$ elemento neutro.


##Elemento neutro

$u_{S}$ è elemento neutro $\iff$ $\forall$ $a$ $\in$ $S$ $a$$*$$u_{s}$=$u_{s}$ $*$ $a$ = $a$

$u_{S}$ è elemento neutro a destra $\iff$ $\forall$ $a$ $\in$ $S$ $a$ $*$ $u_{s}$ = $a$

$u_{S}$ è elemento neutro a sinistra $\iff$ $\forall$ $a$ $\in$ $S$ $u_{s}$ $*$ $a$ = $a$

$u_{s}$ è elemento neutro $\iff$ $u_{s}$ è elemento neutro a destra e sinistra.

**L'elemento neutro se esiste è unico**

Se si trovano piu di due elmenti neutri a destra e a sinistra non esiste elemento neutro


##Elemento simmetrizzabile

$a$ $\in$ $S$ si dice simmetrizzabile $\iff$ $a'$ $\in$ $S$ | 
$a$ $*$ $a'$ = $a'$ $*$ $a$ = $u_{s}$

Esempi di elementi simmetrizzabili:

Per ($K$, +) $a'$ = $-a$

Per ($K$, $\bullet$) $a'$ = $\frac{1}{a}$ = $a^{-1}$

Per ($S^{S}$, $\circ$) $(f)'$ = $f^{-1}$


Come per l'elemento nuetro $a$ $\in$ $S$ è simmetrizzabile a destra e a sinistra $\iff$ $\exists$ $a'$ $\in$ $S$ : $a$ $*$ $a'$ = $u_{s}$ $a'$ $*$ $a$ = $u_{s}$

$a$ è simmetrizzabile $\iff$ é simmetrizzabile a destra e a sinistra. In tal caso il simmetrico è unico.


Esempio di elemento simmetrizzabile.

($S$ , $*$) monoide.

L'insieme degli elementi simmetrizzabili:

$U_{s}(S)$ = { a $\in$ $S$ | a è simmetrizzabile }

a,b $\in$ $U_{s}(S)$

$a'$ è il simmetrico di a
$b'$ è il simmetrico di b

($a*b$) = ( $b'*a'$ )

($a*b$) = ( $b'*a'$ ) = a $*$ ($b$ $*$ $b'$) $*$ $a'$ = $a$ $*$ $u_{s}$ $*$  $a'$ = $a$ $*$ $a'$ = $u_{s}$ quindi  
$b'*a'$ è il simmetrico.

*I passaggi vanno un po spiegati:*

($b$ $*$ $b'$) corrisponde a $u_{s}$ ecco spiegato il primo passaggio.

Nel secondo passaggio $a$ $*$ $u_{s}$ corrisponde ad $a$ da qui $a$ $*$ $a'$ = $u_{s}$

$b'$ $*$ $a'$ $*$ $a$ $*$ $b$ = $u_{s}$


##Gruppi

( $S$ , $\perp$) è un **gruppo** $\iff$ 

1. ( $S$ , $\perp$ ) è un monoide
2. Tutti gli elementi di S sono simmetrizzabili $\rightarrow$ $U_{G}$ = $G$

##Gruppi Abeliani

( $S$ , $\perp$ ) è un gruppo abeliano $\iff$ 
1. ( $S$ , $\perp$ ) è un gruppo
2. ( $\perp$ ) gode della proprietà commutativa.


##Anelli

Fino ad ora abbiamo visto tutte strutture dove era definita una singola operazione. In un anello sono definite due operazioni binarie interne.

( $A$ , $*$ , $\perp$ ) è un esempio di anello.

Si definisce anello $\iff$ 

1. ( $A$ , $*$ ) gruppo abeliano
2. ( $A$ , $\perp$ ) semigruppo
3. $\forall$ $a,b,c$ $\in$ $A$

**L'anello deve godere della proprietà distributiva di $\perp$ rispetto a $*$**

i) $a$ $\perp$ ( $b$ $*$ $c$ ) = $a$ $\perp$ $b$ $*$ $a$ $\perp$ $c$

ii) ( $b$ $*$ $c$ ) $\perp$ $a$ = $b$ $\perp$ $a$ $*$ $c$ $\perp$ $a$



Se $\perp$ è commutativa si dice **Anello Commutativo**

Se ( $A$ , $\perp$ ) è monoide si dice **Anello Unitario**


Esempi di anelli unitari sono:

( $\mathbb{Z}$ . +, $\bullet$ ) Anello commutativo unitario
( $\mathbb{K}$ . +, $\bullet$ )


Esempio di verifica di un anello:

---

Verificare che ( $P(s)$ , $\Delta$ , $\bigcap$ ) Anello commutativo unitario


Primo passo verificare quindi che ( $P(s)$ , $\bigcap$ ) sia monoide.

1. Deve godere della proprietà associativa.
2. Deve avere elemento neutro


Verifica del primo punto:

$\forall$ $A, B, C$ $\in$ $P(s)$ :

 $A$ $\bigcap$ ( $B$ $\bigcap$ $C$) = ( $A$ $\bigcap$ $B$ ) $\bigcap$ $C$
 
Verifica del secondo punto:
 
 In $P(s)$ con l'operazione $\bigcap$ sappiamo che l'elemento neutro è $S$ in quanto :
 
 ($P(s)$, $\bigcap$ ) : $A$ $\bigcap$ $S$ = $A$ = $S$ $\bigcap$ $A$. 
 
 Quindi l'elemenento neutro è $S$
 

Secondo passo verificare che ( $P(s)$ , $\Delta$ ) gruppo abeliano :

   Verifica primo punto verifichiamo che abbia tutti gli elementi simmetrizzabili:

Considerando che $A$ $\Delta$ $A$ = $\varnothing$ quindi $A'$ = $A$, di conseguenza tutti gli elementi sono simmetrizzabili.

   Verifica secondo punto gode della proprietà commutativa.
   
  $A$ $\Delta$ $B$ = $B$ $\Delta$ $A$
  
  $A$ $\Delta$ $B$ = ( $A$ $\setminus$ $B$ ) $\bigcup$ ( $B$ $\setminus$ $A$ ) = ( $A$ $\bigcup$ $B$ ) $\setminus$ ( $A$ $\bigcap$ $B$ ) 
  
  Lo stesso è per  $B$ $\Delta$ $A$ quindi l'operazione gode della proprietà commutativa.
  
  
  
  Ora so che ( $P(s)$ , $\Delta$ ) gruppo abeliano
  So che ( $P(s)$ , $\bigcap$ ) semigruppo.
  
  
  Rimane da verificare la terza condizione per essere un anello ovvero :
  
  $A$ $\bigcap$ ( $B$ $\Delta$ $C$ ) = ( $A$ $\bigcap$ ) $\Delta$ ( $B$ $\bigcap$ $C$ )
  
  Si puo scrivere come : $A$ $\bigcap$ ( ( $B$ $\setminus$ $C$) $\bigcup$ ( $S$ $\setminus$ $B$ ) ) =
  
 ( $A$ $\bigcap$ (  $B$ $\setminus$ $C$) ) $\bigcup$ ( $A$ $\bigcap$ (  $C$ $\setminus$ $B$) )
 
 
 Essendo distributiva a destra lo sarà anche a sinistra per la proprietà commutativa. Ne risulta che è un anello commutativo unitario.
 
 
##Corpo 

Si definisce corpo $\iff$ 

1. ( $A$ , $+$ , $\bullet$ ) anello unitario
2. ( $A^{*}$ , $\bullet$ ) gruppo (dove $A^{*}$ = $A$ $\setminus$ {$0$} )


##Campo

Si definisce campo $\iff$ 

( $A$ , $+$ , $\bullet$ ) corpo
( $\bullet$ ) è commutativa


Esempi di campo sono :

( $\mathbb{K}$ , $+$, $\bullet$ ) 

( $\mathbb{Z}$ , $+$, $\bullet$ ) **Non è un campo**
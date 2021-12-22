#Teoria degli Insiemi

Quando voglio considerare più oggetti come un unico oggetto uso gli insiemi.
Esempi di insiemi sono: $\mathbb{N}$ , $\mathbb{Z}$ , $\mathbb{Q}$ , $\mathbb{R}$

####Un po' di simboli:

$x$ $\in$ $A$  per indicare che x è un elemento che "appartiene" all'insieme $A$.
$A$ $\subseteq$ $B$ per indicare che $A$ è "incluso" nell'insieme $B$, ovvero che ogni elemento di $A$ è anche elemento di $B$.


$A$ $\subseteq$ $B$ $\iff$ ($x$ $\in$ $A$) $\land$ ($x$ $\in$ $B$)

$A$ $=$ $B$ $\iff$ $A$$\subseteq$$B$ $\land$ $B$$\subseteq$$B$

##Definizione di un insieme

$S= \{x | Ps\}$ ovvero l'insieme S formato dagli $x$$\in$S, ovvero gli x tali che la proprietà $Ps$.


$S = \{a,b,c,$$\varnothing$\}


dove $\varnothing$ è il **vuoto** che è sempre incluso ma **non** è detto che appartiene.

---

Consideriamo due insiemi  $P1$ e $P2$ 

$P1$ insieme delle lettere che compongono le parole baco
$P2$ insieme delle lettere che compongono le parole bocca

Gli insiemi $P1$ $\iff$ $P2$ 

###I diagrammi di Euler-Venn

I diagrammi di Euler-Venn sono un potente mezzo grafico grazie al quale è immediato stabilire la relazione tra due o più insiemi

![MacDown Screenshot](https://www.youmath.it/images/stories/Insiemi/Inclusione-di-un-insieme-nel-diagramma-di-Eulero-Venn.png )

**In questo esempio possiamo vedere come $A$$\subseteq$$B$$\subseteq$$C$**



##Iniseme delle parti

$P(s)$ è l'insieme delle parti di S ovvero:

$P(s)$ = \{ $x$ | $x$ $\subseteq$ $S$ \} 

$\forall$ S 
 .1 $P(s)$ $\not$= $\varnothing$ $\implies$ $\varnothing$ $\in$ $P(s)$ e $\varnothing$ $\subseteq$ $P(s)$
 .2 $S$$\in$$P(s)$ ma non è detto che sia incluso ($\subseteq$)
 .3 $P(s)$ singleton $\iff$ $S=$$\varnothing$
 
 
 Se il numero di elemnti dell'insieme S è uguale a n $|S|=n$ il numero di elementi dell'insieme $P(s)$ sarà $2^n$
 
 Esempio:
 
 $S =\{a,b,c\}$
 $|S|=3$
 $|Ps)|=2^3=8$
 $P(s) =\{S, $$\varnothing$, {a}, {b} ,{c} , {a,b} , {a,c}, {b,c}\}
 
 
 **Nell'insieme $P(s)$ il $\varnothing$ appartiene sempre ed è sempre incluso**



##Insieme singleton

Un singleton è un insieme composto da un singolo elemento.Per esempio :

{$\varnothing$} si dice singleton del vuoto ed è un insieme che è composto solamente dal vuoto
{$a$} si dice singleton di a ed è un insieme che contiene solamente l'elemento a.


<br>


##Appartenenza e inclusione 

Consideriamo l'insieme $S = \{a,b,${c}$\}$

a $\in$ S **V**
a $\subseteq$ S **F**
b $\in$ S **V**
b $\subseteq$ S **F**
{a} $\in$ S  **F**
{a} $\subseteq$ S  **V**
{b} $\in$ S   **F**
{b} $\subseteq$ S    **V**
{c} $\in$ S   **V**
{c} $\subseteq$ S   **F**

--


#Operazioni tra insiemi

####Unione

$A$ $\bigcup$ B = \{ x | x$$\in$A $\land$ x$\in$B \} oppure $ ${$ $ $x |$ $Ps$ $\lor$ $Pt$ }

<img src="https://sawakinome.com/img/images/difference-between-union-and-intersection.png" alt="drawing" width="200"/>

####Intersezione

$A$ $\bigcap$  B = \{ x | x$$\in$A $\lor$ x$\in$B \} oppure $ ${$ $ $x |$ $Ps$ $\land$ $Pt$ }

<img src="https://sawakinome.com/img/images/difference-between-union-and-intersection_2.png" alt="drawing" width="200"/>


Se A $\bigcap$ B = $\varnothing$ allora i due insiemi sono **disgiunti** 

####Complemento

$A$ $\setminus$ $B = \{ x | x$$\in$A $\land$ x$\not$$\in$B \}

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Gli_Insiemi_XII.jpg" alt="drawing" width="200"/>


####Differenza simmetrica

$A$ $\Delta$ $B$ =  ($A$ $\bigcup$ $B$) $\setminus$ ($A$ $\bigcap$ $B$) $=$ (A $\setminus$ B) $\bigcup$ (B $\setminus$ A)

<img src="https://www.youmath.it/images/stories/Insiemi/differenza-simmetrica.png" alt="drawing" width="200"/>



###Riassunto

<img src="https://www.ideegreen.it/wp-content/uploads/2018/02/diagramma-di-venn-esempi-2.jpg" alt="drawing" width="400"/>

<br>

##Alcune proprietà dell'inclusione

####Doppia implicazione

($S=T$) $\iff$ ($Ps$ $\iff$ $Pt$) $\iff$ ($Ps$ $\iff$ $Pt$) $\land$ ($Pt$ $\iff$ $Ps$) $\iff$ (S $\subseteq$ T) $\land$ (T $\subseteq$ S)

####Transitività 

($S$$\subseteq$$T$) $\land$ ($T$$\subseteq$$V$) $\implies$ ($S$$\subseteq$$V$)

<br><br>


##Proprietà dell'unione e dell'intersezione

###Proprietà associativa:


$A$ $\bigcup$ ($B$ $\bigcup$ $C$) $\iff$ ($A$ $\bigcup$ $B$) $\bigcup$ $C$

$A$ $\bigcap$ ($B$ $\bigcap$ $C$) $\iff$ ($A$ $\bigcap$ $B$) $\bigcap$ $C$

###Proprietà commutativa

$A$ $\bigcup$ $B$ $\iff$ $B$ $\bigcup$ $A$

$A$ $\bigcap$ $B$ $\iff$ $B$ $\bigcap$ $A$

###Idempotenza

$A $$\bigcup$ A =$ A $$\bigcap$$ A$ = $A$

###Distributività dell'unione rispetto l'intersezione e viceversa

$A$ $\bigcap$ ($B$ $\bigcup$ $C$) $\iff$ ($A$ $\bigcap$ $B$) $\bigcup$ ($A$ $\bigcap$ $C$)

$A$ $\bigcup$ ($B$ $\bigcap$ $C$) $\iff$ ($A$ $\bigcup$ $B$) $\bigcap$ ($A$ $\bigcup$ $C$)

<br><br>


##Proprietà dell'operatore complemento

###Per l'operatore complemento non valogno proprietà commutativa e associativa

####Esempio:

Consideriamo gli insiemi S , T e V dove 

$S = \{a,b,c,d\}$

$T = \{a,e,i,o,u\}$

$T = \{a,e,d\}$


($S$ $\setminus$ $T$) $\setminus$ $V$  $=$ {$b,c,d$} $\setminus$ V = {$b,c$}
 
$S$ $\setminus$ ($T$ $\setminus$ $V$)  $=$ $S$ $\setminus$ {$b,c,d$}  = {$b,c,d$}

**Ecco come la proprietà dimostrativa non vale**


$S$ $\setminus$ $T$ $\not$ =  $T$ $\setminus$ $S$

**La proprietà commutativa non vale**



###Distributività (De Morgan rispetto agli insiemi)

$S$ $\setminus$ ($T$ $\bigcap$ $V$) = ($S$ $\setminus$ $T$) $\bigcup$ ($S$ $\setminus$ $V$)
$S$ $\setminus$ ($T$ $\bigcup$ $V$) = ($S$ $\setminus$ $T$) $\bigcap$ ($S$ $\setminus$ $V$)

<br> <br>

##Proprietà dell'operatore differenza simmetrica

####Distributività dell'intersezione rispetto la differenza simmetrica

$A$ $\bigcap$ ($B$ $\Delta$ $C$) = ($A$ $\bigcap$ $B$) $\Delta$ ($A$ $\bigcap$ $C$)

####Non vale la distributività dell'unione rispetto la differenza simmetrica

###Idempotenza

$A$ $\bigcap$ $A$ $=$ $A$ $\bigcup$ $A$ $=$ $A$

$A$ $\Delta$ $A$ = ($A$ $\setminus$ $A$) $\bigcup$ ($A$ $\setminus$ $A$) = $\varnothing$

$A$ $\Delta$ $\varnothing$ = $A$
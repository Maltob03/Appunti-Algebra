#Corrispondenze, relazioni, applicazioni

<br>


##Proprietà delle relazioni binarie

Definiamo quindi 5 proprietà delle relazioni binarie:

1. Proprietà riflessiva $\iff$ $\forall$ $x$ $\in$ $S$ $xRx$
2. Proprietà antiriflessiva $\iff$ $x$ $\in$ $S$ $x$$\not$$R$$x$
3. Proprietà simmetrica $\iff$ $\forall$ $x,y$ $\in$ $S$ se $xRy$ $\implies$ $yRx$
4. Proprietà antisimmetrica $\iff$ $\forall$ $x,y$ $\in$ $S$ se $(xRy)$ $\land$ $(yRx)$ $\implies$ $x=y$
5. Proprietà transitiva $\iff$ $\forall$ $x,y,z$ $\in$ $S$ se $xRy$ e $yRz$ $\implies$ $xRz$


---


Definiremo $R$ **relazione di equialenza** $\iff$ $R$ è :

1. **Riflessiva**
2. **Simmetrica**
3. **Transitiva**

Definiremo $R$ **relazione d'ordine** $\iff$ $R$ è :

1. **Antiriflessiva**
2. **Asimmetrica**

Definiremo $R$ **relazione d'ordine stretto** $\iff$ $R$ è :

1. **Antiriflessiva**
2. **Asimmetrica**
3. **Transitiva**

Esempi di relazione d'ordine sono: 
($\mathbb{Z}$, $\subseteq$) $a$ $\subseteq$ $b$ 
($P(s)$, $\subseteq$) $A$ $\subseteq$ $B$

Esempi di relazione d'ordine stretto sono:
($\mathbb{Z}$ , $\subset$) dove $a$ $\subset$ $b$
($P(s)$, $\subset$) dove $A$ $\subset$ $B$

--



####Verifchiamo quindi questa relazione d'ordine di quali proprietà gode

La relazione $R= (SxS, G)$ di $f$ in $S$ corrisponde all'applicazione identità:

$id_{s}$ = $(SxS, G)$ = $diagS$ = {$(x,x) : x$ $\in$ $S$ }

Consideriamo ora un esempio:

$S= \{a,b,c\}$
e grafico
$G= \{(a,b),(a,c),(a,a),(b,a)\}$

Quindi per il grafico delle corrispondenze :

$aRb$, $bRa$, $aRc$, $aRa$


**Proprietà riflessiva**: $xRx$ : Questa relazione **non** gode della proprietà riflessiva in quanto è pur vero che $aRa$
 **MA** $b$$\not$ R $b$ e $c$$\not$ R $c$
 
 
**Proprietà Antiriflessiva**: $x$$\not$R$x$ : Questa relazione non gode della proprietà antiriflessiva in quanto è pur vero che $b$$\not$ R $b$ e $c$$\not$ R $c$
**MA** $aRa$

**Prorpietà simmetrica**: $\forall$ $x,y$ $\in$ $S$ se $xRy$ $\implies$ $yRx$ : Questa relazione non gode della proprietà simmetrica in quanto manca la coppia $(c,a)$

**Proprietà antisimmetrica** : $\iff$ $\forall$ $x,y$ $\in$ $S$ se $(xRy)$ $\land$ $(yRx)$ $\implies$ $x=y$ : Questa relazione non gode della proprietà asimmetrica in quanto è vero che $(aRb)$ e $(bRa)$ **MA** $a$ e $b$ sono due elementi distiniti.

**Proprietà transitiva** : $\iff$ $\forall$ $x,y,z$ $\in$ $S$ se $xRy$ e $yRz$ $\implies$ $xRz$ : Questa relazione non gode della proprietà transitiva perchè : è vero che $(bRa)$ e $(aRb)$ **MA** ($b$$\not$R$b$) **oppure** $(bRa)$ e $(aRc)$ **MA** ($b$$\not$R$c$) 

--

####Consideriamo un nuovo grafico $G_{2}$ = {$a,a$}
-La relazione con questo grafico non è riflessiva perchè deve valere $\forall$ $x$ $\in$ $S$

-Non è antiriflessiva in quanto c'è la coppia $(a,a)$

-E' simmetrica in quanto non riesco a trovare un altra coppia che possa giustificare il fatto di non essere asimmetrica

-E' asimmetrica per lo stesso motivo non posso negarlo

-E' transitiva perchè non ci sono altri elementi quindi non posso negare la transitività

##Relazione di equivalenza

Ricordiamo che $R$ è una relazione di equivalenza $\iff$ $R$ gode delle seguenti proprietà: **riflessiva, simmetrica transitiva**

Consideriamo un generico insieme $S$ e una relazione $R$ $\rightarrow$ ($S,R)$

$\forall$ $a$ si dice classe di $a$ modulo $R$ $\in$ $S$ $[a]_{R}$ = { $x$ $\in$ $S$ : $aRx$ }

####1. $\forall$ a $\in$ S $[a]_R$ è sempre diverso dal $\varnothing$
$[a]_R$ $\not$ = $\varnothing$ : $\forall$ $a$ $\in$ $S$ $a$ $\in$ $[a]_{R}$

####2. $\forall$ $a,b,$ $\in$ $S$ $aRb$ $\iff$ $[a]_{R}$ = $[b]_{R}$

Dimostrazione secondo punto:

----
E' sufficiente far vedere che $[a]_{R}$ $\subseteq$ $[b]_{R}$ poichè da $aRb$ segue $bRa$ (*proprietà riflessiva essendo relazione di equivalenza*) $\rightarrow$ $[b]_{R}$ $\subseteq$ $[a]_{R}$

Partiamo con la prima implicazione $\implies$ :

considero un generico $x$ $\in$ $[a]_{R}$, questo implica che $xRa$.

Per la proprietà transitiva $xRa$ $\land$ $aRb$ $\implies$ $xRb$

Se $x$ $\in$ $[b]_{R}$ allora $[a]_{R}$ $\subseteq$ $[b]_{R}$

Concludiamo quindi con la seconda implicazione $\Leftarrow$ :

Se $a$ $\in$ $[a]_{R}$ = $[b]_{R}$ allora $\implies$ $aRb$

$\spadesuit$

---

<br>

####3. $\forall$ $a,b$ $\in$ $S$ $[a]_{R}$ $\bigcap$ $[b]_{R}$ $\not$= $\varnothing$ $\implies$ $[a]_{R}$ = $[b]_{R}$

Dimostrazione terzo punto:

---

Sia $c$ $\in$ $[a]_{R}$ $\bigcap$ $[b]_{R}$ $\not$= $\varnothing$

$cRa$ $\implies$ $aRc$ (*proprietà riflessiva*)
$cRb$

*N.B essendo che c appartiene a quelle due classi intersecate, c è in relazione con a e con b da definizione, ecco perchè posso scrivere le due righe sopra*

Concludiamo dicendo che se $aRc$ $\land$ $cRb$ $\implies$ $aRb$ $\implies$ $[a]_{R}$ = $[b]_{R}$

$\spadesuit$

**3'** 
$[a]_{R}$ $\bigcap$ $[b]_{R}$ = $\varnothing$ $\implies$ $[a]_{R}$ $\not$= $[b]_{R}$


---

####4. S = $\bigcup$ $[a]_{R}$

$\forall$ $a$ $\in$ $S$ $a$ $\in$ $[a]_{R}$ $\subseteq$ $\bigcup$ $[b]_{R}$

S = $\bigcup$ $[a]_{R}$

**Sto punto non è proprio chiarissimo** invece si



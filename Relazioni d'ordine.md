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


Definiremo $R$ **relazione di equivalenza** $\iff$ $R$ è :

1. **Riflessiva**
2. **Simmetrica**
3. **Transitiva**

Definiremo $R$ **relazione d'ordine** $\iff$ $R$ è :

1. **Riflessiva**
2. **Aimmetrica**
3. **Transitiva**

Definiremo $R$ **relazione d'ordine stretto** $\iff$ $R$ è :

1. **Antiriflessiva**
2. **Transitiva**

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

In altre parole, $[a]_R$ è il sottoinsieme di A formato da tutti gli elementi che sono equivalenti ad a. In particolare, dire che $x$ $\in$ $[a]_{R}$, o che x appartiene alla classe di equivalenza di $a$, significa dire che $x$ è equivalente ad $a$.

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

**Sto punto non è proprio chiarissimo**


<br>


##Insieme quoziente e partizione

Gli elementi dell’insieme quoziente $S_{R}$ sono le classi di equivalenza degli elementi di S. Quindi una classe di equivalenza $[a]_R$ pu`o essere vista o come un sottoinsieme di S, o come un elemento dell’insieme quoziente $S/_{R}$.

$S_{/R}$ = { $[a]_{R}$ : $a$ $\in$ $S$ }

$S$ insieme $\not$= $\varnothing$  

L'insieme $F$ $\subseteq$ $P(s)$ è una partizione di $S$ $\iff$ :

1. $\forall$ $A$ $\in$ $F$ $A$ $\not$= $\varnothing$
2. $\forall$ $a,B$ $\in$ $F$ se $A$ $\not$= $B$ $\implies$ $A$ $\land$ $B$ = $\varnothing$
3. $\bigcup$ $A$ = $S$

$S_{/R}$ è una partizione di $S$.



####Teorema 

Se $R$ è una relazione di equivalenza in $S$ allora : $S_{R}$ è una partizione di $S$.

Se $F$ è una partizione di $S$ posto $xR_{F}y$ $\iff$ $\in$ $A$ $\in$ $F$ : $x,y$ $\in$ $A$

Allora $R_{F}$ è una relazione di equivalenza e l'insieme quoziente coincide con la partizione di $S$.

---

Dimostrazione punto 1:

$S_{R}$ = {$[a]_{R}$ : a $\in$ $S$}

i) $\forall$ a $\in$ $S$ $a$ $\in$ $[a]_{R}$ $\not$= $\varnothing$ e $\bigcup$ $[a]_{R}$ = $S$

ii) $\forall$ $a,b$ $\in$ $S$ se $[a]_{R}$ $\not$= $[b]_{R}$ $\implies$ $[a]_{R}$ $\bigcap$ $[b]_{R}$ = $\varnothing$ 

$S_{R}$

---

Dimostrazione punto 2:

Sia $F$ una partizione di S

$xR_{F}y$ $\iff$ $\exists$ $A$ $\in$ $F$ : $x,y$ $\in$ $A$

$xR_{F}y$ Riflessiva quindi 

$\forall$ $x,y$ $\in$ $S$ se $xR_{F}y$ $\implies$  $\exists$ $A$ : $x,y$ $\in$ $A$ , ma anche $y,x$ $\in$ $A$ 

$yR_{F}x$ è simmetrica

Infine è anche transitiva quindi:

$\forall$ $x,y,z$ $\in$ $S$ se $xR_{f}y$ e $yR_{f}z$

x,y $\in$ $A$ , $y,z$ $\in$ $B$ $\implies$ $A$ $\bigcap$ $B$ $\not$= $\varnothing$ $\implies$ $A=B$ $\implies$ $x,z$ $\in$ $A$

---

###Teorema fondamentale delle relazioni di equivalenza 

Sia $S$ $\not$= $\varnothing$ allora :

Se $R$ è una relazione di equivalenza allora $S_{R}$ determina una partizione di $S$

Se $F$ è una partizione di $S$ allora la relazione $xR_{F}y$ $\iff$ $\exists$ $A$ $\in$ $F$ : $x,y$ $\in$ $A$ determina una relazione di equivalenza in $S$ e $S_{RF}$ = $F$

Dimostrazione punto 1:

Se $R$ è una relazione di equivalenza

$S_{/R}$ = { $[a]_{R}$ : $a$ $\in$ $S$ }

allora:

1. $\forall$ $a$ $\in$ $S$ $[a]_{R}$ $\not$= $\varnothing$
2. $\bigcup$  $[a]_{R}$ $\not$= $\varnothing$
3. $[a]_{R}$ $\bigcap$ $[b]_{R}$ $\not$= $\varnothing$ $\iff$ $aRb$ $\iff$ $[a]_{R}$ = $[b]_{R}$


---

Dimostrazione punto 2:

$F$ una partizione $xR_{F}y$ $\exists$ $A$ $\in$ $F$ : $x,y$ $\in$ $A$

1. $\forall$ $a$ $\in$ $S$ $\exists$ $A$ $\in$ $F$ : $a$ $\in$ $A$ ( $\bigcup$$A$ = $S$)

$a,a$ $\in$ $A$ $a$$R_{F}$$a$ riflessiva

2. $\forall$ $a,b$ $\in$ $S$ se $a$$R_{F}$$b$ $\iff$ $\exists$ $A$ $\in$ $F$ : $a,b$ $\in$ $A$ $(b,a $ $\in$ $A$ )$ $
Quindi $bR_{f}a$ simmetrica

3. $\forall$ $a,b,c$ $\in$ $S$ se $a$$R_{F}$$b$ $\iff$ $\exists$$ A$$\in$ $F$ : $a,b$ $\in$ $A$
$b$$R_{F}$$c$ $\iff$ $\exists$ $B$$\in$ $F$ : $b,c$ $\in$ $B$

Se $A$ $\bigcap$ $B$ $\not$= $\varnothing$ $\implies$ $A=B$ quindi $a,b,c$ $\in$ $A=B$ $\implies$ $aR_{f}c$

---

Teorema di caratterizzazione della relazione di equivalenza

Siano due insiemi $S,T$ $\not$= $\varnothing$ e $f$: $S$ $\rightarrow$$T$ un' applicazione.
Allora $\forall$ $x,y$ $\in$ $S$ $xR_{f}y$ $\implies$ $f(x)=f(y)$ 

$R_{f}$ è una relazione di equivalenza (nucleo di equivalenza) e 

$f^{*}$ : $S_{/RF}$ $\rightarrow$ $T$ 
$[x]_{Rf}$ $\rightarrow$ $f^{*}$ ( $[x]_{Rf}$) = $f(x)$ 
è un applicazione ineittiva

Dimostrazione 

---

$f$: $S$ $\rightarrow$ $T$ 

$xR_{f}y$ $\iff$ $f(x)$ = $f(y)$

1. Riflessiva : $\forall$ $x$ $\in$ $S$ $f(x)=f(x)$, $xR_{f}x$
2. Simmetrica : $\forall$ $x,y$ $\in$ $S$ se $f(x)=f(y)$ allora $f(y)=f(x)$ quindi $xR_{f}y$ $\implies$ $yR_{f}x$
3. Transitiva : $\forall$ $x,y,z$ $\in$ $S$ se $f(x)=f(y)$ $\land$ $f(y)=f(z)$ $\implies$ $f(x)=f(z)$ 

$xR_{f}y$ $\land$ $yR_{f}z$ $\implies$ $xR_{f}z$

$[x]_{Rf}$ = {$y$ $\in$ $S$ : $f(x)=f(y)$} = $f^{-1}x$

L'applicazione $f^{*}$ : $[x]_{Rf}$ $\in$ $S_{/Rf}$ $\rightarrow$ $f^{*}([x]_{Rf})$ = $f(x)$

$f(x)$ = $f^{*}([x]_{Rf})$ = $f^{*}([y]_{Rf})$ = $f(y)$ $\iff$ $xR_{f}y$ $\iff$ $[x]_{Rf}$ = $[y]_{Rf}$


####Osservazione

La relazione $R_{f}$ = $id_{s}$ $\iff$ 

$\forall$ $a$ $\in$ $S$ $[a]_{Rf}$ = {$a$} $\iff$ [$f(x)$ = $f(a)$ $\iff$ $x=a$] $\iff$ $f$ sia iniettiva

**Esempio:**

$f$: $x$ $\in$ $\mathbb{Z}$ $\implies$  $5x+1$ $\in$ $\mathbb{Z}$

$R_{f}$ = $id_{Z}$ 
$[25] = {25}$

$g:$ $x$ $\in$ $\mathbb{Z}$ $\implies$ $5x^2+1$ $\in$ $\mathbb{Z}$
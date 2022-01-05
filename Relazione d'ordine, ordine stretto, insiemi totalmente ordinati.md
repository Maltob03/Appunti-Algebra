#Relazioni d'ordine

Considero un insieme $L \not= \varnothing$ e una relazione:

($L , R$) è relazione d'ordine $\iff$

1. **Proprietà Riflessiva:** $\forall x \in L$ $xRx$
2. **Proprietò Assimetrica:** $\forall x,y \in L $ allora ($xRy$) $\land$ ($yRx$) $\implies$ $x=y$
3. **Proprietà Transitiva:** $\forall x,y,z \in L$ allora $(xRy) \land (yRz)$ $\implies$ $xRz$


($L , R^{*}$) è relazione d'ordine stretto $\iff$

1. **Proprietà Antiriflessiva** $\forall x \in L$ $x  \not R x$
2. **Proprietà Transitiva:**


Il legame fra la relazione d'ordine e la relazione d'ordine stretto è la seguente ( a destre ordine , a sinistra ordine stretto)

$G = G^{*} \bigcup $ $DiagL$ $\iff$ $G^{*} = G$ \ $Diag L$

####Passaggio da ordine a ordine stretto e vicecersa


Suppongo che $G$ relazione d'ordine in $L$

$R$ = $(L,G)$

$R^{*} = ( L,G^{*}$ = $G$ \ $Diag L$ )

$R$ è riflessiva $\implies$ $DiagL$ $\subseteq$ $G$

$R^{*}$ = ($L, G^{*}$)

1. $R^{*}$ è antiriflessiva in quanto $\forall x \in L$ $x \not R x$ avendo tolto tutti gli elementi della diagonale
2. $R^{*}$ è transitiva perchè $R$ lo era

Quindi ho definito una relazione d'ordine stretto.



$R^{*}$ Relazione d'ordine stretto.

$G^{*}$ $\bigcup$ $DiagL$ = $G$ 

$R=(L,G)$

1. E' riflessiva perchè contiente la diagonale
2. E' asimmetrica perchè $(xRy) \land (yRx) \implies x=y$
3. E' transitiva perchè $R^{*}$ lo era

###Esempi di relazione d'ordine usuale

( $\mathbb{Z} \le$ ) : $ a \le b \iff b-a \in \mathbb{N}$ 

$\mathbb{N}^{*}$ = $\mathbb{N}$ / {0}

$ a < b \iff b-a \in \mathbb{N}^{*}$ 


( $\mathbb{N}$ , / ) : $a/b \iff \exists c \in \mathbb{N} : b = a \bullet c$

$a$ / $a$ perchè $a = 1 \bullet a$ quindi riflessiva

$a$ / $b$ e $b$ / $a$ $\implies$ $a=b$

Nota bene che in $\mathbb{Z}$ non è possibile in quanto ad esempio 3 , -3 sono si divisibili tra loro ma diversi.


Infine $a$ / $b$ e $b$ / $c$ $\implies$ $a$ / $c$

$b$ = $a \bullet h$ e $c= b\bullet k$

$c = b \bullet c = a \bullet h \bullet k$ quindi $a$ / $c$


($P(s), \subseteq $) è una relazione d'ordine

($L$ , $R$ ) è ima relazione d'ordine totale $\iff$ $\forall x,y \in L$ 
$xRy$ oppure $yRx$ ovvero tutti gli elementi di $L$ sono confrontabili.

($\mathbb{Z}$ , $\le$ ) è totalmente ordinato.

($\mathbb{N}$ , $\le$ ) è totalmente ordinato.

($\mathbb{Q}$ , $\le$ ) è totalmente ordinato.

Infatti vanno confrontate prima le parti intere, se diverse si confrontano se uguali si confronta la mantissa.

($\mathbb{R}$ , $\le$ ) è totalmente ordinato.

($\mathbb{C}$ , $\le$ ) non è possibile definire una relazione d'ordine totale, ma è possibile definire una relazione d'ordine.



$\mathbb{C}$ = { $a +ib$ | $a,b \in \mathbb{R} , i^{2} = -1 $}

$e = a +ib$
$f = c +id$ 

$e$ $\le$ $f$ $\iff$ $\{ 1. e=f$  $2. a^{2}+b^{2}=c^{2}+d^{2}$

$\le$ è riflessiva

$\le$ è asimmetrica perchè:

$e \le f$ e $f \le e$

$a^{2} + b^{2} < c^{2} + d^{2} < $a^{2} + b^{2}

$\implies$ $e=f$

$\le$ è transitiva




MA ($\mathbb{Z}$ , / ) NON è totalmente ordinato.

poichè 2 non divide 3 e 3 non divide 2, quindi non sono confrontabili tra di loro.

Altro esempio di insieme non totalmente ordinato:

( $P(s) , \subseteq$) in quanto {1} $\not\subseteq$ {2}



##Elemento coprente

($L , \le$) $a$ copre $b$ $\iff$ $b \le a e \not \exists c : b < c < a$

Ad esempio in $S^{S}$ = {$  id_{S}, \tau, cost_{1}, cost_{2}$}

$cost_{1}$ $R$ $id_{s}$ $R$ $cost_{2}$

l'applicazione costante 1 è coperta dall'identità di S perchè in mezzo non c'è niente.


##Diagramma di Hasse

Quando ho un insieme ordinato posso disegnare il diagramma di Hasse, mettendo verso il basso gli elementi piu piccoli.


Quando ho una relazione d'ordine totale il diagramma di Hasse è una retta

##Minimo e Massimo

In un insieme $S$ dove è definita una relazione d'ordine $R$:

($S,R$) con $a \in S$ 

$a$ è il minimo di $S$ $\iff$ $a \le b$ $\forall b \in S$

$a$ è il massimo di $S$ $\iff$ $a \geq b$ $\forall b \in S$

Il minimo (massimo) se esiste è unico

$a_{1}, a_{2} = minS$ $a_{1} \le a_{2}, a_{2} \le a_{1} \implies a_{1}=a_{2}$


##Massimale e minimale

$a \in S$ è minimale in $S$ $\iff$ $\not \exists b \in S$ : $ b < a$
oppure $\forall b \in S, b \le a \implies b=a$

$a \in S$ è massimale in $S$ $\iff$ $\not \exists b \in S$:
$ b > a$
oppure $\forall b \in S, b \geq a \implies b=a$


$a$ minimo $\implies$ $a$ minimale

MA NON IL VICEVERSA

####Lista di esempi di minimi e massimi

($\mathbb{N}, \le $) min $\mathbb{N}$ = 0, $\not \exists$  $max$

($\mathbb{Z}, \le $) min $\mathbb{N}$ = $\not \exists$ $min$, $\not \exists$  $max$

($\mathbb{N}, \le $) max $\mathbb{N}$ = 0, min $\mathbb{N}$ = 1

($P(s) \subseteq$) max $P(S)$ = $S$ , min $P(s)$ = $\varnothing$


##Minoranti e Maggioranti

Dato ($L , \le$) insieme ordinato ed un suo sottoinsieme $X$ :

$\varnothing$ $\not$=  $\subseteq$ $L$

minoranti di X = {$a \in L $ | $ a \le x \forall x \in X$}

maggioranti di X = {$a \in L$ | $a \geq x, \forall x \in X$}

In ($\mathbb{N}, /$)

$\forall a,b \in \mathbb{N}$

minoranti {a,b} = divisori comuni di a e b.

inf{a,b} = max divisori comuni = M.C.D

maggioranti {a,b} = multipli comuni di a,b

sup = min multipli comuni = m.c.m

##Divisori primi

($\mathbb{N}, R$)

$\pi(a)$ = {divisori primi di $A$}

$\pi(0)$ = $P$

$\pi(1)$ = $\varnothing$

$\pi(2)$ = {2}

$\pi(4)$ = {2}

$aRb$ $\iff$ 1.$a=b$ oppure 2.$\pi(a) \subset \pi(b)$



Riflessiva per 1.

Asimmetrica $aRb$ e $bRa$ e P.A $a \not= b$

$\implies$ $\pi(a) \subset \pi(b) \land \pi(b) \subset pi(a)$ $\implies$ $\pi(a) \subset \pi(a) \implies$ ASSURDO $\implies$ $a=b$

Transitiva 

$aRb$ (1. $a=b$ oppure 2. $\pi(a) \subset \pi(b)$)

$bRc$ (1. $b=c$ oppure 2. $\pi(b) \subset \pi(c)$)

Verifichiamo le condizioni:

1 $\land$ 3 : $a=b$ $\land$ $b=c$ $\implies$ $a=c$ quindi $aRc$

1 $\land$ 4 : $a=b$($\pi(a)=\pi(b)$) $\land$ $\pi(b)$ $\subset$ $\pi(c)$ $\implies$ $\pi(a) \subset \pi(c) \implies aRc$

2 $\land$ 3 : $\pi(a) \subset pi(b) \land b=c (\pi(b) = \pi(c))$

$\pi(a) \subset \pi(b) = \pi(c) \implies aRc$

2 $\land$ 4 $\pi(a) \subset \pi(b) \land \pi(b) \subset pi(c) \implies \pi(a) \subset \pi(c) \implies aRc$

Usiamo questa relazione per la seguente applicazine:

$f : a \in \mathbb{N} \rightarrow \pi(a) \in P(P)$

$f$ è iniettiva? NO perchè:

$\pi(2) = $ {2} $ = \pi(4)$ ma 2 $\not=$ 4

$f$ è suriettiva? NO perchè:

immaginiamo l'insieme $A = \{p_{1},...,p_{n}\}$

quindi ad esempio $\{2,5,7,11,17,43\}$

un elemento $a \in A$ = $2 \bullet 5 \bullet 7 \bullet 11 \bullet 17 \bullet 43$

quindi gli elementi $a \in A$ = $\{p_{1} \bullet p_{2} \bullet ... \bullet p_{n}\}$ 

Non è suriettiva in quanto non esiste un elemento $a$ tale che l'insieme $P$ meno qualsiasi singleton faccia un numero appartenente all'insieme delle parti di P

$\not$ $\exists$ $a$ | $P$ \ {2} = $\pi(a)$

($\mathbb{N} , R$)

$\pi(1)= \varnothing$

1 = min $\mathbb{N}$
0 = max $\mathbb{N}$

minimali sono { $p^{n}$ | $n \in \mathbb{N}^{*}, p \in P$ }

perchè $\pi(2)$ = 2 MA $\pi(4)=${2} 

$\pi(2^{n})$ = {2}

##Definizione di sup e inf

($S$ , $\le$ ) $L \subseteq S$

$inf$ $L$ = max {minoranti di L} se $\exists$
$sup$ $L$ = min (maggioranti di L} se $\exists$.


##Compatibilità relazione d'ordine

Suppongo di avere :

($S , \le$_{1}) e ($T , \le_{2}$)

$f: S \rightarrow T$

$f$ è compatibile con $\le$ $\iff$ $\forall x,y \in S$ 

$x \le_{1} y$ $\implies$ $f(x) \le_{2} f(y)$

####Esempio

($N, /$) e ($N, R$) dove $aRb$ $\iff$ { 1. $a=b$ oppure 2. $\pi(a) \subset \pi(b)$


$f = id_{N} : a \in N \rightarrow a \in N$

$a$ / $b$ $\rightarrow \pi(a) \subset \pi(b)$

2 / 4 e $f(2)=2$ e $f(4)=4$

MA 2 $\not$R 4

Quindi non determina un applicazione


Se pensiamo alla stessa applicazione ma nel codominio consideriamo $N$ con la relazione d'ordine usuale ($\le$)


$a$ / $b$ $\implies$ $a \le b$ c'è compatibilità.



##Ordinamento duale

Consideriamo $S$ con la relazione d'ordine usuale.

($S$ , $\le$) ordinamento duale $\le^{*}$

$a \le^{*} b \iff b \le a$

Questo determina una relazione d'ordine.

##Matrici


$M_{2,2}(R)$=$\begin{pmatrix} a_{11} & a_{12}\\ a_{21} & a_{22} \end{pmatrix}$ | $a_{i,j} \in R$

Nelle matrici possiamo definire delle operazioni come somma o prodotto.

( $M_{2,2}(R), + , \bullet$)


$\begin{pmatrix} a_{11} & a_{12}\\ a_{21} & a_{22} \end{pmatrix}$ + $\begin{pmatrix} b_{11} & b_{12}\\ b_{21} & b_{22} \end{pmatrix}$ = 

$\begin{pmatrix} a_{11}+b_{11} & a_{12}+b_{12}\\ a_{21}+b_{21} & a_{22}+b_{22} \end{pmatrix}$



( $M_{2,2}(R), +$) Gruppo abeliano:

1. Vale la proprietà associativa
2. Esiste elemento neutro matrice nulla
3. Ogni elemento ha opposto ed è $-M$
4. Vale la proprietà commutatuva

E dunque ( $M_{2,2}(R), +$) gruppo abeliano.

Prodotto riga per colonna

$\begin{pmatrix} a_{11} & a_{12}\\ a_{21} & a_{22} \end{pmatrix}$ $\bullet$ $\begin{pmatrix} b_{11} & b_{12}\\ b_{21} & b_{22} \end{pmatrix}$ = $\begin{pmatrix} c_{11} & c_{12}\\ c_{21} & c_{22} \end{pmatrix}$

dove:

$c_{11} = a_{11} \bullet b_{11} + a_{12} \bullet b_{21}$

$c_{12} = a_{11} \bullet b_{12} + a_{12} \bullet b_{22}$

$c_{11} = a_{21} \bullet b_{11} + a_{22} \bullet b_{21}$

$c_{11} = a_{21} \bullet b_{12} + a_{22} \bullet b_{22}$


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

$e$ $\le$ $f$ $\iff$ ${ 1. e=f$  $2. a^{2}+b^{2}=c^{2}+d^{2}$

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


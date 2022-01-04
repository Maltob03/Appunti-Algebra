#Sottoanelli, elementi irriducibili e reticoli

Dato un insieme $S$ ed un operazione $\perp$

($S , \perp$) 

$\varnothing \not= X \subseteq S$

$X$ è parte stabile $\iff$ $\forall a,b \in X$ $a \perp b \in X$

$x \subseteq S$ $S$ è semigruppo se $X$ è stabile

$X$ stabile $\not\implies$ ($x,\perp$) monoide e può succedere che ( $x,\perp$ ) sia monoide con elemento neutro diverso.

####Esempio

($\mathbb{Z}x\mathbb{Z}, \bullet$)

($a_{1} \bullet a_{2}$) $\bullet$ ($b_{1} \bullet b_{2}$) = ($a_{1} \bullet b_{1}$ , $a_{2} \bullet b_{2}$)


($\mathbb{Z}x\mathbb{Z}, \bullet$) monoide commutativo.

U elemento neutro = (1,1)

Definisco la parte X:

$X = \{(a,0) | a \in \mathbb{Z}\}$

 Verifico che X è parte stabile: 
 
 $\forall (a,0), (b,0) \in X $
 
 $(a,0)$ $\bullet$ $(b,0)$ = ( $a \bullet b$, 0)
 
 ($X$ , $\bullet$ ) semigruppo commutativo
 
 ( 1, 1 ) $\not\in X$
 
 ( 1, 0 ) $\in$ $X$ elemento neutro in $X$ 
 
 
 Monoide ma ha elemento neutro
 
 
##Sottoanello

($A$ , $+$ , $\bullet$ ) anello

$H$ $\subseteq$ $A$ $H$ $\not=$ $\varnothing$ 

$H$ è sottoanello $\iff$

1. ($H$, +) , ($H,\bullet$) stabile
2. ($H , + , \bullet$) è anello


$H$ è ideale di $A$ $\iff$

1. ($H , + $) è stabile
2. ($H, +$)è un gruppo abeliano
3. $\forall a \in A$ e $\forall h \in H, a \bullet h, h \bullet a \in H$

Verifichiamo che

$\forall m$ se considero gli $m\mathbb{Z} = \{ m \bullet h | h \in \mathbb{Z}\}$

Gli ideali non sono unici.

3 $\mathbb{Z}$ = 3 $\bullet$ $h$ | $h \in \mathbb{Z}$ 


Verifichiamo ($m\mathbb{Z}, +$) gruppo

0 $\in$ $m\mathbb{Z}$

$m \bullet h, m \bullet k \in m\mathbb{Z} \implies (m \bullet h) + ( m \bullet k) \in m\mathbb{Z}$

Questo risulta essere un gruppo abeliano

$\forall a \in \mathbb{Z}$

$\ a \bullet (mh) \in m\mathbb{Z}$

$m\mathbb{Z} ideale di \mathbb{Z} $

--

($(M_{2,2}(R),+, \bullet$) anello unitario non commutativo

($S$ , $\perp$ ) associativa $\forall$ $X \subseteq S$ $X$ è stabile , ($X,+$) è associativa

($S$ , $\perp$) commutativa $\forall$ $X \subseteq S$ $X$ è stabile , ($X,+$) è commutativa.


$(M_{2,2}(R)$ chiamiamo una parte $L_{1}$ data da tutte le matrici

 $\begin{pmatrix} a & 0\\ 0 &b \end{pmatrix}$ 
 
 tali che $a,b \in R$


$\begin{pmatrix} a & 0\\ 0 &b \end{pmatrix}$ $\bullet$ $\begin{pmatrix} c & 0\\ 0 &d \end{pmatrix}$ =

$\begin{pmatrix} a \bullet c & 0\\ 0 &b \bullet d \end{pmatrix}$

($L_{1}, \bullet$) è stabile, possiede elemento neutro, quindi è un monoide commutativo.


$(L_{1}, +, \bullet)$ anello commutativo unitario.

($L_{1}, \bullet)$ monoide commutativo
($L_{1}, + )$ gruppo abeliano

$\begin{pmatrix} a & 0\\ 0 &b \end{pmatrix}$ + $\begin{pmatrix} c & 0\\ 0 &d \end{pmatrix}$ =

$\begin{pmatrix} a +c & 0\\ 0 &b + d \end{pmatrix}$

ha elemento neutro e ha opposto. Quindi è un anello commutativo unitario, pertanto $L_{1}$ è un sottoanello commutativo unitario di $M_{2,2}$$R$ che è anello unitario non commutativo.




Diciamolo male ma lo ricordiamo una proprietà viene ereditata dalla sottostruttura quindi scendono ma non salgono. Infatti una struttura non eredita da una sottostruttura.



####Altro esempio

($M_{2,2}(R)$ , + , $\bullet$) 

$L_{2}$ = $\begin{pmatrix} a & -a\\ b & c \end{pmatrix}$ 

con $a,b,c \in R$

1. ($L_{2}, + $) sottogruppo
2. ($L_{2}. \bullet$) non è stabile

Quindi che sia staible rispetto ad un operazione non significa che sia stabile rispetto ad un altra.

##Elementi irriducibili

In un anello unitario ($A$ , + , $\bullet$)

$a \in A$ \ $\{0\}$ a è irriducibile $\iff$ 

$a$ $\in$ $div(a)$ = { $c$ $\in$ $A$ |$ \exists b \in A : a = b \bullet c$ } = elementi invertibili di $a,c\bullet a$ | $c \in U(A) $} = divisori banali

$U(A)$ = elementi invertibili di a 

$\forall c \in U(A)$ e $\forall a \in A$ $c$ / $a$ : $a = c \bullet $( $c^{-1} \bullet$ $a$ }

Concretamente sarebbe il perchè i divisori banali sono 1,-1 e $a,-a$

Ad esempio in $\mathbb{Z}$ gli elementi invertibili sono 1,-1 e quindi i divisori banali sono 1,-1 e $a,-a$


Considerati due elemnti $a,b$ $\in$ $A$ a associato b ($a \sim b$) $\iff$

$\exists c \in U(A) : a = b \bullet c$

$\sim$ : è una relazione di equivalenza:

1. Riflessiva: $\forall a \in A$ $a=1 \bullet a, aRa$
2. Simmetrica: $\forall a,b \in A$ se $a \sim b$
 $\exists c \in U(A) : a=b \bullet c$
 
 $a \bullet c^{-1} = b \bullet c \bullet c^{-1} = b$ quindi $b \sim a$
 
3. Transitiva : $\forall a,b,c \in A$ $a \sim b$ e $b \sim c$ allora:

$\exists d_{1},d_{2} \in U(A) : a=b\bullet d_{1}$ e $b=c \bullet d_{2}$
quindi $a \sim c$

####Esempio Pratico

In $\mathbb{Z}_{7}$ gli elementi invertibili $U(\mathbb{Z}_{7})$ = ?

e considero $[2]_{\sim}$

$2 \sim a \iff \exists b \in \mathbb{Z}_{7} : 2 = a \bullet b$

1 è associato, 2 è associato, essendo l'elemento invertibile come elementi associati trovo esattamente $\mathbb{Z}_{7}$

**Altro esempio**

In $\mathbb{Z}_{8}$ 

Gli elementi invertibili sono $U(\mathbb{Z}_{8})$ = { 1 , 3 , 5, 7 }

div banali di 4 sono = { 1, 3 ,5 ,7, 4}

$4 = 1 \bullet 4$

$4 = 3 \bullet ( 3 \bullet 4)$

$5 = 5 \bullet ( 5 \bullet 4)$

$4 = 7 \bullet ( 7 \bullet 4)$


##Definizione di reticolo

Un insieme ordinato ($L , \le$) si dice reticolo $\iff$ $\forall a,b \in L$ $\exists$ $l'inf\{a,b\}$ e il $sup\{a,b\}$

L'$inf\{a,b\}$ viene indicato con $a \land b$

L'$sup\{a,b\}$ viene indicato con $a \lor b$

**MI RACCOMANDO E' PER a,b NON PER L**


Se ($L, \le$) totalmente ordinato $\implies$ $L$ reticolo.

$\forall a,b \in L a \le b$ oppure $b \le a$ quindi:

$ \exists min \{a,b\} = a = inf \{a,b\}$
$ \exists max \{a,b\} = b = sup \{a,b\}$

**Non necessariamente se è un reticolo è totalmente ordinato**

($P(S) , \subseteq$) 

$\{A,B\}$

minoranti $\{A,b\}$ = $\{X \in P(S) | X \subseteq A, X \subseteq B \}$ = { $X \in P(S) | x \subseteq A \bigcap B\}$

$\exists$ inf $\{a,b\}$ = $A \bigcap B$

$\exists$ sup $\{a,b\}$ = $A \bigcup B$


##Monoidi fattoriali

Un monoide commutativo 

($S$,$\bullet$) è fattoriale $\iff$ 

$\forall a \in S$ \ {0} e $a$ non invertibile

$a$ è prodotto di elementi irriducibili e tale decomposizione è unica a meno dell'ordine dei fattori e di elementi associati.

($\mathbb{Z}$ , $\bullet$)

$U(Z)$={1,-1}

$\mathbb{Z}$ \ {0,1,-1}

$\forall a \in \mathbb{Z}$ \ {0,1,-1}

$a$ è primo o è prodotto di numeri primi e tale decomposizione è unica a meno dell'ordine dei fattori e del segno.

Per queste osservazioni ($\mathbb{Z}$, $\bullet$) è un monoide fattoriale come conseguenza del teorema fondamentale dell'aritmetica.


**Esempio di elemento irriducibile che non coincide come elemento primo.**

$M = \{1, 2 \bullet h | h \in \mathbb{N}^{*}\}$

quindi tutti i numeri pari e 1.

Il numero 6 $\in$ $\mathbb{N}$

$6 / 6 \bullet 6 = 36$
6 / 36 = 2 $\bullet$ 18

MA 6 $\not$ \ 2 E 6 $\not$ \ 18 in $M$

div 6 = {1,6} 6 è irriducibile ma non è primo.


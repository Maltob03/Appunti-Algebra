#Anello dei polinomi

($A$, +, $\bullet$) anello commitativo unitario

$A$ = $\mathbb{Z}$, $\mathbb{Q}$, $\mathbb{R}$, $\mathbb{C}$, $\mathbb{Z}_{m}$

$A_{[x]}$ = $\{f(x) = a_{0} + a_{1}x + a_{2}x^{2}+...+a_{n}x^{n}$}


($A_{[x]}, +) 

$\ f(x) = a_{0} + a_{1}x + a_{2}x^{2}+...+a_{n}x^{n}$

$\ g(x) = a_{0} + a_{1}x + a_{2}x^{2}+...+a_{n}x^{n}$

La somma di questi due polinomi è:

($a_{0}+b_{0}) + (a_{1}+b_{1})x +...+(a_{n}+b_{n})x^{n}$

**Esempio**

Ho polinomi $f(x), g(x) \in \mathbb{Z}_{[x]}$

$f(x)= 3 + 5x^{2} - 7x^{4}$
$g(x)= -1 + x + 4x^{3}$

$f(x)+g(x)= -2 + x +5^{2}+4x^{3}-7x^{4}$

---


($A_{[x]}, +$) è un gruppo abeliano.

L'elemento neutro sarà il polinomio nullo.

l'inverso di un polinomio sarà ad esempio $-f(x)$


associatività e commutatività derivano dalle proprietà delle operazioni definite in $A$


($A_{[x]}, \bullet ) monoide commutativo.

Se 

$f(x)$ = $a_{0} + a_{1}x + a_{2}x^{2}+...+a_{n}x^{n}$

$\ g(x) = a_{0} + a_{1}x + a_{2}x^{2}+...+a_{n}x^{n}$

il prodotto sarà definito come:

$f(x) \bullet g(x)$ = 


$c_{0} + c_{1}x +...+c_{n+m}x^{n+m}$

$ci$ = $\sum a_{h} \bullet b_{k}$
con $h+k=i$

**Esempio**

$f(x) = 3 + x - 2x^{2}$
$g(x) = 1 + 7x -x^{3}$

$f(x) \bullet g(x) = 3 + 22x + 5x^{2} - 17x^{3} -x^{4} +2x^{5}$


($A_{[x]}, \bullet$)

ha come elemento neutro :

$a_{0}=1 e a_{n}=1$

risulta essere un monoide commutativo unitario.

Vale la distributività, è solamente lungo da scrivere ma è distributivo.


($A_{[x]}, +, \bullet) anello commutativo unitario.

##Grado di un polinomio non nullo

Se il polinomio è diverso dal polinomio nullo (ovvero con tutti i coefficienti uguali a 0) ha un grado. Il grado di un polinomio viene indicato come $\delta(f)$=$gr(f)$=max{n|a_{n$\not$=0}$


##Monomio

Si definisce monomio un polinomio tale che a_{n} sia uguale a 0 tale che per un valore.

Esempio di monomio :

$7x, 7x^{5}$ sono monomi

Ogni polinomio si può vedere come somma di monomi.

Si definisce polinomio costante ogni polinomio che abbia $\delta f()=0$,$f=0$

Se considero l'applicazione $i$

$i: a \in A \rightarrow a \in A_{[x]}$

determina un monomordismo in quanto inettiva e compoatibile con le operazioni di somma e prodotto.

$A$ = $i(a) \le A[x]$

**Esempio:**

Se prendo come $A =  \mathbb{Z}_{6}$ e ho l'anello di polinomio:

($\mathbb{Z}_{6}[x], + , \bullet$)

questo anello di polinomi ha divisori in quanto se normalmente in $\mathbb{Z}_{6}$ il divisore dello 0 è 3 in questo polinomio il monomio costante 3 è divisore dello zero.

####Teorema di addizione dei gradi
####Proposizione : 

Sia ($A$, + , $\bullet$ ) anello commutativo unitario, dominio d'integrità.

Se $f,g \in A_{[x]}$\ {0} e $\delta(f)=n,\delta(g)=m \rightarrow \delta(f \bullet g) = n+m$

In particolare se ($A,+,\bullet$) dominio d'integrità allora anche ($A_{[x]},+,\bullet$) è dominio d'integrità


Dimostrazione:

$\delta(f)=n$ quindi $f=a_{0} + a_{1}x + a_{n}x^{n}$

$\delta(g)=m$ quindi $f=b_{0} + b_{1}x + b_{m}x^{m}$

$f \bullet g = c_{0} + c_{1}x + ... + c_{n+m}x^{n+m}$

$c_{n+m}= \sum ah \bullet bk = a_{m} \bullet b_{m} \not= 0$

$\delta(f \bullet g)=n+m$

$f(x) \not = 0$
$\delta(f)=n$
parametro direttore di f il coefficiente di $a_{n}


Sia ($A,+,\bullet$) dominio d'integrità, $\delta(f)=n,\delta(g)=m \rightarrow \delta(f \bullet g)= n + m $ e il parametro direttore di $f \bullet g$ = $a_{n} \bullet b_{m}$

**Esempio**

In $\mathbb{Z}_{4}[x]$ 

$(\bar{2} + \bar{2}x) \bullet (\bar{2}+\bar{2x})= (\bar{2}+\bar{2x})^{2}=\not \bar{4} + \not \bar{8x} + \not \bar 4x^{2}$ quindi alla fine è = $\bar{0}$

Se $A{[x]}$ dominio d'integrità

$f(x) \bullet f(x)^{-1}=1$

$\delta(f) + \delta(f^{-1})$=$\delta(f(x) \bullet f^{-1}(x)) = \delta(1)=0$

Quindi per forza di cose $\delta(f)=\delta(f^{-1})=0$

**Esempio**

$\mathbb{Z}_{4}[x]$

$\delta(\bar{1}+\bar{2x})=1$

$(\bar{1}+\bar{2x}) \bullet (\bar{1}+\bar{2x})$ = $\bar{4x^{2}}$ + $\bar{4x}$ + $\bar{1}$ = $\bar{1}$

quindi $(\bar{1}+\bar{2x})$ è invertibile e il suo inverso è proprio $(\bar{1}+\bar{2x})^{-1}$ ma anche $(\bar{1}+\bar{2x^{n}})^{-1}$

E se mentre in $U(\mathbb{Z}_{4}$ gli elementi invertibili sono 1,3 in $U(\mathbb{Z}_{4[x]}$ sono infiniti


##Anello ordinato

Sia ($A,+,\bullet$) anello commutativo unitario.

Supponiamo che in $A$ sia definita una relazione d'ordine : ($A,\le$)

$\le$ è compatibile con $+,\bullet$ $\iff$

1. $\forall a,b,c \in A$ se $a \le b \implies a+c \le b+c$
2. $\forall a,b,c \in A$ se $a \le b$ e $c>0$ $\implies a \bullet c \le b \bullet c$
se $c < 0 \implies a \bullet c \geq b \bullet c$


Esempi di anelli ordinati sono

($\mathbb{Z},+,\bullet$) con $\le$

($\mathbb{Q},+,\bullet$) con $\le$

($\mathbb{R},+,\bullet$) con $\le$


##Polinomi monici

$f(x) = a_{0}+ a_{1}x+...+a_{n}x^{n}$

parametro direttore di f è $a_{n} : a_{n} \not= 0$ e $a_{m}=0 \forall m > n$

$f(x)$ MONICO $\iff$ parametro direttore = 1

Due polinomi si dicono assiocati se esiste un polinomio tale che $f(x)=h(x) \bullet g(x)$

$f(x) \sim g(x) \iff \exists h(x) \in U(A_{[x]}) | f(x) = h(x) \bullet g(x)$

Se $A$ dominio d'integrità

$U(A_{[x]})=U(A)$ (vale il teorema di addizione dei gradi)

non è piu vero se $A$ non è dominio d'integrità

Se $A$ è dominio d'integrità e $f \sim g$ (sono polinomi associati) $\implies$ $\delta(f)=\delta(g)

infatti:

$f \sim g \iff \exists h(x) \in U(A_{[x]})= U(A)$ visto che $A$ è dominio d'integrità

$\implies \delta h(0)$

$f=h \bullet g \implies \delta(f) = \delta(h \bullet g) = \delta(h) + \delta(g) = \delta (g)$

Se $A$ è un campo ad ogni polinomio non nullo è associato un unico polinomio monico.

$f(x) = a_{0} + a_{1}x +...+ a_{n}x^{n}$

$\exists a^{-1}_{n}$

$a^{-1}_{n} \bullet f(x) = a^{-1}_{n} \bullet a_{0} + a^{-1}n \bullet a_{1}x +...+ a_{n}^{-1} \bullet a_{n}x^{n}$ è monico di grado $n$


$f \sim g$ se sono entrambi monici coincidono.

Infatti se $f(x) = a_{0} + a_{1}x +...+ a_{n}x^{n}$ e $g(x) = b_{0} + b_{1}x +...+ b_{n}x^{n}$

e $f = h \bullet g \implies h=1$ e $f=g$


I divisori banali di $f$ sono sempre gli elementi invertibili di $A_{[x]}$ e gli elementi associati


$f(X) \in A_{[x]}$

$f(x)$ è irriducibile $\iff$ 

1. $f(x)$ non è invertibile
2. Gli unici divisori di $f$ sono quelli banali

$x^{2}+1 \in R_{[x]}$ è irriducibile in questo insieme

$x^{2}+1 \in \mathbb{Z}_{2[x]}$ 

Questo polinomio si può ridurre come $(x+1)(x+1)=(x+1)^{2}=(x^{2}+2x+1)$  *nota bene so tutte classi*

$f(x)$ è irriducibile $\iff$ 

1. $f(x)$ non è invertibile
2. Gli unici divisori di $f$ sono quelli banali

equivale a richiedere $\iff$

1. $f$ non è invertibile
2. Se $f=g \bullet h \implies f \sim g$ e $h$ $inv$ oppure $f \sim h$ e $g$ è $inv$


$f(x) \in A_{[x]}$

posso considerare l'applicazione polinomiale:

$\bar{f}: a \in A \rightarrow \bar{f(a)} = a_{0} + a_{1}a + a_{2}a^{2}+...+a_{n}a^{n}$

Ad esempio

$f(x) = 3 + 5x^{2}-7x^{3} \in Q_{[x]}$

$\bar{f(1)} = 3+5-7=1$

$\bar{f( \frac{1}{2})} = 3 + \frac{5}{4}-\frac{7}{8} = \frac{24+10-7}{8}=\frac{27}{8}$




##Radici di un polinomio

$f$ ammette $c$ come radice (zero) $\iff$ $\bar{f(c)}=0$

##Teorema

Siano $f,g \in A_{[x]}$ e $g \not= 0$

Supposto che il parametro direttore di $g$ sia invertibile allora $\exists! (q,r) : f(x)=g(x) \bullet q(x) +r(x)$

con $r(x)=0$ oppure $gr(r)<gr(g)$

**Dimostrazione:**

$f(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+....a_{1}x + a_{0}$
$g(x)=b_{n}x^{n}+b_{n-1}x^{n-1}+....b_{1}x + b_{0}$

1. $f(x) = 0$ allora $q=r=0$ e $0=g \bullet 0 + 0$
2. $f(x) \not= 0$ e $gr(f)<gr(g)$ allora $q=0$ e $r=f$ quindi $f=0 \bullet g + f$ quindi $r=f$ e $gr(f)<gr(g)$
3. $gr(f)\geq gr(g)$ 

Uso il principio d'induzione (II forma):

$Pn :$ Sia $gr(f)=n \implies \exists q,r : f=g \bullet q + r$

Base $P_{0}$ : Sia $gr(f)=0 \implies \exists q,r$ $f=g \bullet q + r$ e $r=0$ oppure $gr(r)<gr(g)$

$gr(f)=0 \geq gr(g)=0$

$f=a_{0}$ e $g=b_{0}$ parametro direttore di $g$ quindi $\exists$ $b_{0}^-1$

e di conseguenza $f=a_{0}=b_{0} \bullet a_{0} + 0$


QUINDI BASE D'INDUZIONE VERIFICATA

Supponiamo ora vera 

$P_{l} \forall 0 \le l \le gr(f)=n$ deve seguire Pn vera

$f(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+....a_{1}x + a_{0}$
$g(x)=b_{n}x^{n}+b_{n-1}x^{n-1}+....b_{1}x + b_{0}$

$\exists bm^{-1}

moltiplico il polinomio g per 

$h(x) = g \bullet (a_{n}b_{m}^{-1}x^{n-m})= a_{n}x^{n}+b_{m-1} \bullet (a_{n}b^{m-1})x^{n-m-1}+...$

$\bar{f(x)}=f(x)-h(x)=f(x)-g(x) \bullet a_{n}b^{-1}_{m}x^{n-m}$

$gr(\bar f) < gr(f)$

$P_{\bar{n}}$ è vera

$\bar{f} = g \bullet \bar{q} + \bar{r}$ con $r=0$ oppure $gr(\bar{r})< gr (g)$

$f = g \bullet a_{n} \bullet b^{-1}_{m}x^{n-m}+gq+r$

metto g in evidenza quindi:

$g(anb^{-1}_{m}x^{n-m}+q)+r

Teorema dimostrato (per l'esistenza)

Unicità:

$f = g \bullet q_{1} + r_{1}= g \bullet q_{2}+r_{2}$

$r_{1}=0$ $r_{2}=0$



$gr(r_{1}) \le gr(g)$ oppure $gr(r_{2}) \le gr(g)$

posso supporre che

$gr(r_{1}) \le gr(r_{2})$ quindi



$g(q_{q}-q_{2}) = gq_{1}-gq_{2}=r_{2}-r_{1}$

$gr(g(q_{1}-q_{2}))=g(r_{2}-r_{1})<gr(g)$

$\implies r_{2}-r_{1}=0 \implies$ $r_{1}= r_{2}$

$g(q_{1}-q_{2})=0 \implies q_{1}=q_{2}$






####Let's divide some polyname (credo si scriva così sto impazzendo)
$f-g \bullet a_{m} \bullet b^{-1}_{m}x^{m-n}$=$f(x)= 5x^{6}+7x^{4}-x^{3}+3x^{2}+1$

$g(x)= 2x^{3}-x+3$

Entrambi i polinomi appartengono a $\mathbb{Q}$ se ero in $\mathbb{Z}$ non avrei potuto dividere, perchè  il parametro direttore di $g$ è 2 che in Z non è invertibile.


Praiticamente qua devi fa la divisione dei polinomi e alle 22:00 non ne ho voglia. Falla domani


----









Dato l'anello di polinomio ($A_{[x]},+,\bullet$)

Se $A$ è campo $f(x)$ irriducibile se {1. $f(x)$ non invertibile o 2. $f=g \bullet h \implies f \sim g$ e $h$ $inv$}

Se $A$ è campo $\iff$ { 1. $f(x)$ non è invertibile, 2.$f(x)$ non si puo esprimere come il prodotto di due polinomi aventi entrambi grado<grado di f }


Se $A$ non è campo questo non è piu vero

$2x + 4$ $\in \mathbb{Z}_{[x]}$

Infatti si scrive come $2 \bullet (x+2)$ dove ne 2 ne $(x+2)$ sono invertibili ne associati.

In $Q_{[x]} questi fattori sono banali , 2 è invertibile.

Conseguenza:

Se $A$ è campo i polinomi di primo grado sono sempre irriducibili

Se ho un polinomio di $\delta(f)=1$

$f=g \bullet h$ avrò $\delta(f)=\delta(g)+\delta(h)$

Perchè la somma deve essere 1 allora $f \sim g$ e dunque $f$ irriducibile.

Esempi:

$f(x)=-x +3 $ questo è riducibile perchè se voglio scriverlo come $-x+3=h \bullet g$

E poi il parametro direttore di $f$ deve essere = al parametro direttore di $g$ $\implies$ $h=h_{0}$ e $g=b_{0}+b_{1}x$

Quindi $h_{0} \bullet b_{1} = -1$ 

quindi $h_{0}=+-1 e$ quindi $f \sim g$

Altro esempio:

$k(x)=6x-3=3(2x-1$

3 non è invertibile quindi divisore proprio
3 è associato a $k(x)$ No perchè grado di k=1 e grado di 3=0

2x-1 non è invertibile perchè il grado è uguale a 1
2x-1 non è associato

3 e (2x-1) sono divisori propri di k(x) in $\mathbb{Z}_{[x]}$

in $\mathbb{Q}_{[x]}$ sono divisori banali.

##Divisibilità tra polinomi

($A_{[x]},+,\bullet)$

Considerati due polimomi $f(x),g(x)$

$g(x)$ \ f(x)$ \iff \exists h(x): f(x) = g(x) \bullet h(x)$ ovvero che rest ($f(x),g(x))=0

##M.C.D tra polinomi

$d(x)$ è M.C.D di ($f(x),g(x)$) $\iff$ 

1.$ d(x) / f(x) , d(x) / g(x)$

2.$\forall h(x) / f(x)$ e $h(x) / fg(x)$ $\implies$ $h(x) / d(x)$

$[d(x)]_{\sim}$ = $\{c \bullet d(x) | c \in A^{*}\}$

Il M.C.D in $A[x]$ è quello monico

$[d(x)]_{\sim}$

$d(x)= d_{0}+d_[1]x+...+d_{l}x^{l}$

$\exists d_{l}^{-1}$

$d_{l}^{-1} \bullet d(x)$ è monico ed è associato a $d(x)$

Per garantire l'esistenza di questo M.C.D si sfrutta il teorema di Bezout.

##Teorema di Bezout per i polinomi

$(A_{[x]},+,\bullet$)

Sia $(A_{[x]},+,\bullet$) campo

$\forall f(x),g(x) \in A_{[x]}$

$\exists d(x) M.C.D (f(x),g(x)) ed \exists (u(x),v(x)):$

$d(x) = u(x) \bullet f(x) + v(x) \bullet g(x)

Dimostrazione

$f(x)=g(x) \bullet q_{1}(x) + r_{1}(x)$ con $r_{1}=0$ oppure $\delta(r_{1}<\delta(g))$

$g(x)=r_{1} \bullet q_{2} + r_{2}$ con $r_{2 = 0}$ oppure $\delta(r_{2}) < \delta(r_{1})$

l'ultimo resto non nullo è M.C.D ($f(x),g(x))$ e lo si può scrivere come combinazione lineare

####Vari esempi di calcolo di M.C.D


##Teorema di fattorizzazione

Sia ($A_{[x]},+,\bullet$) un campo allora

$\forall f(x) \in A_{[x]}$ \ $A$

$f(x)$ o è irriducibile o è prodotto di polinomi irriducibili e tale decomposizione è unica al meno dell'ordine dei fattori e di elementi associati.

##Esistenza m.c.m

m.c.m ($f,g$) = m(x) = $\frac{f \bullet g}{d}$

confronto tra due applicazioni

In $\mathbb{Z}_{3[x]}$ $f=x^{3}+1$ e $g=x+1$

$f \not= g$ ($\delta(f) \not= \delta(g)$)

Valutiamo le funzioni calcolate negli elementi di $\mathbb{Z}_{m}$

$f : 0 \rightarrow 0^{3}+1=1$

$f : 1 \rightarrow 1^{3}+1=2$

$f : 0 \rightarrow 2^{3}+1=9=0$

$f : 0 \rightarrow 0+1=1$

$f : 0 \rightarrow 1+1=1$

$f : 0 \rightarrow 2+1=0$

$f \not = g$ MA $\bar{f} \equiv \bar{g}$

**Lemma**

Sia $f(x) \in A_{[x]}$ e $c \in A$. Allora rest($f(x),(x-c)$)=$f(c)$

Esempio

Se voglio calcolare il resto($x^{4}-x^{3}+2x-5),(x-2)$)

$f(2)=16-8+4-5=7$

In quale $\mathbb{Z}_{m}$ ($x-2$) / ($x^{4}-x^{3}+2x-5)$

in $\mathbb{Z}_{7[x]}$ perchè il resto deve essere 0.

Dimostrazione del lemma:

$f(x)$ e ($x-c$)$

($x-c$) ha parametro direttore 1 ed è invertibile.

$f(x)=q(x) \bullet (x-c) + r(x)$ con $r(x)=0$ opp. $\delta(r) < \delta(x-c)=1$

$r=r_{0}$ polinomio costante.

$f(c)=q(c) \bullet (c-c) +r(c) = 0 + r_{0}=r$

$r=f(c)$


##Teorema di ruffini

Sia $f(x) \in A_{[x]}$ $c$ è radice di $f(x)$ $\iff$ $(x-c) divide f(x)$ cioè il resto $(f(x),(x-c)=0)$

dim:

supponiamo che c sia radice di $f(x)$ $\implies$ 

$f(x)=(x-c) \bullet q(x) + f(c) = (x-c) \bullet q(x)$

l'uguaglianza è data dal lemma sopra scritto, mentre $f(c)=0$ perchè è radice. 

$(x-c) / f(x)$

$f(x) = (x-c) \bullet q(x)$
$f(c) = (c-c) \bullet q(c)=0$

Teorema di Ruffini dimostrato.

In generale dal fatto che $(x-c) / (f(x)$) non segue che il prodotto dei polinomi ottenuti considerate le radici di $f$ divida il prodotto. Esempio

**Esempio**

Consideriamo il polinomio $f=x^{2}-5x= x^{2}+x \in \mathbb{Z}_{6[x]}$

$f(0)=0$
$f(1)=1+1 = 2$
$f(2)=4+2=0$
$f(3)=9+3=0$
$f(4)=16+4=2$
$f(5)=25+5=0$

$X_{f}=\{0,2,3,5\}$

per il teorema di Ruffini

$(x-0)$ \ $f(x) = x(x+1)$
$(x-2)$ \ $f(x) = (x-2)(x-3)$
$(x-3)$ \ $f(x) = (x+2)(x-3)$
$(x-5)$ \ $f(x) = x(x-5)$

MA Il prodotto tra:

$x(x-2)(x-3)(x-5)$ non divide $x^{2}+x$

In quanto da un lato grado 4 dall'altro grado 2

##Teorema di Ruffini generalizzato.

Sia ($A,+,\bullet$) un dominio d'integrità e $f(x) \in A_{[x]}$ e $X_{f}=\{c_{1},c_{2},...c_{t}\}$ radici distinte di $f$

Allora $(x-c_{1})(x-c_{2})...(x-c_{t})$ / $f(x)$

Dimostrazione:

Induzione su $t$ (numero di radici distinte)

t=1 è il teorema di ruffini 

t>1 il risultato vero $\forall h(x)$ avente $t-1$ radici distinte. 

$f(x)=(x-c_{1}) \bullet q(x)$ per il teorema di ruffini.

$\forall i \not= 1$ 

0=$f(c_{i}) = (c_{i}-c_{1}) \bullet q(c_{i})$ uno dei due fattori deve essere uguale a 0 $\implies$ $q(c_{i})=0 \forall i \not= 1$

$q(x)$ ammette $t-1$ radici distinte $\{c_{2},...,c_{t}\}$

applicando l'ipotesi d'induzione

$q(x)=(x-c_{2})(x-c_{3})...(x-c_{t})\bullet h(x)$

$f(x) = (x-c_{1}) \bullet q(x)= (x-c_{1})(x-c{2})...(x-c_{t}) \bullet h(t)$


Teorema dimostrato.


**Corollario**

Sia ($A,+,\bullet$) dominio d'integrità allora $f(x) \in A_{[x]}$ e $\delta(f)=n \implies f(x)$ possiede al piu n rardici distinte

Dimostrazione

$\delta(f)=n$ e $c_{1},...,c_{t}$  sono radici distinte per il teorema di ruffini generalizzato

$f(x)=(x-c_{1})(x-c_{2})...(x-c_{t}) \bullet h(x)$

$\delta(f)=1+1+1+...+1 + \delta(h)= t + \delta(h) \implies t \le \delta(h)$

##Principio d'identità dei polinomi

Sia ($A,+,\bullet$) un campo e $f(x),g(x) \in A_{[x]}$

Allora

$f \equiv g \iff $ :

1. se $A$ è infinito $f=g$
2. se $|A| = n (f-g)=h(x)(x^{m}-x)$

il polinomio $x^{m}-x \in A_{[x]}$ con $|A| = m$ è detto polinomio fondamentale

Prima considerazioni sul polinomio fondamentale

$|A|$ = $m$

$|A^{*}|$ = $m-1$

($A^{*}, \bullet$)

$\forall c \in A^{*}$ se considero il sottogruppo <c> generato da c e dato dalle potenze di c quindi:

$\{c^{h} | h \in Z\}$ $\implies$ $c^{m-1}=1$ $\implies$ \forall C \in A^{*}$

$h(x) = x^{m-1}-1$
$h(c) = c^{m-1}-1=0$

Il polinomio $x^{m}-x=(x^{m-1}-x)$ è tale che 

0 ed è una sua radice per questa decomposizione ($x$)

$(x^{m-1}-1) \forall c \in A^{*}$ c è racice

$x^{m}-x$ ammette come radici tutti gli elementi di A

$A=\{0,a_{1},...,a_{m-1}\}$

$x^{m}-x = x (x-a_{1})(x-a_{2})...(x-a_{m}) \bullet k(x)$

I parametri direttori sono tutti 1 quindi k(x) deve essere per forza 1.

E il polinomio fondamentale non è altro che il prodotto di tutti i polinomi che ottengo al variare dei coefficienti presenti in A

Esempio:

$x^{7}-x$ = $x(x-1)(x-2)(x-3)(x-4)(x-5)(x-6)$

Questo è

$x^{5}-x$ = $x(x-1)(x-2)(x-3)(x-4)$


Il polinomio 

$x^{3}+1$ e $x+1$ in $\mathbb{Z}_{2[x]}$

$(x^{3}+1)-(x+1)=x^{3}-x$ questo è il polinomio fondamentale del suo insieme

Altro esempio:

In $\mathbb{Z}_{5[x]}$ il polinomio:

$x^{5}+2x^{3}-x^{2}+3$ e
$2x^{3}-x^{2}+x+2$

Per vedere se i due polinomi sono uguali facciamo la differenza e troviamo:

$x^{5}-x$ e quindi posso asserire che i due polinomi sono uguali, nel loro insieme.

##Molteplicità di una radice

Considerato un polinomio $f(x) \in A_{[x]}$ e $c$ radice di $f$, la molteplicità di c come radice di f è k $\iff$

1. $(x-c)^{k}$ divide $/ f$
2. $(x-c)^{k+1}$ non divide $\not/$ $f$

c è una radice semplice $\iff$ la molteplicità di $c = 1$

Esempio:

Sto considerando il polinomio: $x^{2}-5x+6 \in Q[x]$

$(x-2)(x-3)$ quindi sia 2 che 3 sono radici semplici


Se invece considero il polinomio $(x-2)^{2}(x-3)$ due ha molteplicità 2 mentre 3 è radice semplice

###Teorema fonamentale dell'algebra

Sia $f(x) \in C_{[x]}$ e il $\delta(f)=n$

se $c_{1}...c_{t}$ sono le sue radici

se ($\alpha_{1},..,\alpha_{t})$ le sue molteplicità

allora il polinomio $f(x)=k(x-c_{1})^{\alpha_{1}} (x-c_{2})^{\alpha_{2}}...(x-c_{t})^{\alpha_{t}}$

Se non siamo in $C_{[x]}$ tutto questo non è vero.

In $R{{x}}$ $x^{2}+1$ non ammette radici, neanche in $Q$ e in $Z$ , però in $\mathbb{Z}_{2}$ ammette radici, in $\mathbb{Z}_{5}$ ammette due radici semplici.

##Relazione tra essere irriducibile e possedere radici

Consideriamo ($A,+,\bullet$) con $A$ campo

1. Se $f(x)$ : $\delta(f)=1 \implies f$ irriducibile e $f(x)$ possiede una sola radice


$\delta(f)=1$ $f=g \bullet h \implies 1 = \delta(f)=\delta(g)$

Se $\delta(g)=0$ $g$ è una costante nulla $\implies$ g è invertibile e $h \sim f$ sono i divisori banali

$(2x + 2) \in Q_{[x]}$ è irriducibile

$(2x +2) \in Z_{[x]}$ si può scrivere come $2(x+1)$ entrambi non sono invertibili, sono divisori propri quindi riducibile. QUesto ha senso solo perchè A è campo


Se $\delta(f)=1$ allora $f$ possiede una radice.

$f(x)=a_{0}+a_{1}x$ con $a_{1} \not= 0$

$c = -a_{0} \bullet a_{1}^-1$

$a_{0}+a_{1}(a_{0} \bullet a_{1}^{-1})=a_{0}-a_{0}=0

**Proposizione**

Sia ($A,+,\bullet) campo e $f(x) \in A_{[x]}$ e $\delta(f)=2,3$

$f$ è irriducibile $\iff$ $f$ è privo di radici

Dimostrazione:

la prima implicazione è una conseguenza del lemma sotto

la seconda implicazione va dimostrata:

Supponiamo $f(x)$ riducibile quindi puo essere espresso come 

$f(x)=g(x) \bullet h(x)$ e $\delta(f)=\delta(g)+\delta(h)$

La somma dei gradi g e h deve essere la somma di due interi e deve essere = a 2 o a 3 e $\delta(g)$ e $\delta(h) \geq 1$

Se la somma è 2  $\delta(g)=\delta(h)$
Se la somma è 3  $\delta(g)=2$ $\delta(h)=1$

In ogni caso uno dei due fattori deve essere di grado 1

Ma se h ha grado 1 h è radice

$h=b_{0}+b_{1}x \implies c=-b_{0} \bullet b_{1}^{-1}$

$f(c)= g(c) \bullet h(c)=0$
$c$ è radice di f (contro questo supposto)

$\delta(f)=2,3$

$f$ privo di radici $\implies$ f irriducibile

$f$ riducibile $\implies$ $f$ possiede radici


**Lemma**

Sia ($A,+,\bullet$) dominio d'integrità.

Se $\delta(f) > 1$ e $f$ irriducibile $\implies$ $f$ privo di radici

$\delta(f) >1

Per assurdo c è radice $\implies$ $f=(x-c)\bullet q(x)$

1 < n = $\delta(f) = \delta(x-c) + \delta(q)=1+\delta(q)=n>1$

$\delta(q) \geq 1 \implies f$ avendo fattori di grado 1,$n-1$ è riducibile, contro l'ipotesi.

In generale $f$ privo di radici non implica $f$ irriducibile.

Infatti se considero:

$x^{4}+2x^{2}+1 \in R_{[x]}$

si pup esprimere come $(x^{2}+1)(x^{2}+1)$

Privo di radici ma riducibile.



####Riassunto di tutto cio in tre righe

Ipotesi A campo

1. $\delta(f) = 1 \implies f$ irriducibile e possiede una radice
2. $\delta(f) > 1 \implies f$ irriducibile $\implies$ $f$ privo di radici
3. $\delta(f)$ = 2,3 $\implies$ $f$ irriducibile $\iff$ $f$ è privo di radici


###Teorema fondamentale dell'algebra nella seconda forma

Sia $f(x) \in \mathbb{C}_{[x]}$

1. $\delta(f) \geq 1$ allora $f$ si esprime nel prodotto di polinomi di primo grado, ovvero tutti e soli i polinomi irriducibili sono quelli di grado 1.

2. In $R_{[x]}$ tutti e soli i polinomi irriducibili sono di primo grado e di secondo grado con il delta < 0.
   Ovviamente il delta si calcola con la formula risaputa e le radici altrettanto.

---

####Teorema

Sia $f(x) \in \mathbb{Z}_{[x]}$ se 

$f(x)$ irriducibile in $\mathbb{Z}_{[x]}$ sono irriducibili in $Q_{[x]}$

Non vale il viceversa


####Teorema di Eisenstein:

Sia $f(x)=a_{0}+a_{1}x+...+a_{n}x^{n} \in \mathbb{Z}_{[x]}$

$\exists p$ primo : 

1. p / $a_{0},a_{1},a_{n-1}$
2. p non divide $a_{n}$
3. $p^{2}$ non divide $a_{0}$

Allora $f(x)$ è irriducibile in $\mathbb{Z}_{[x]}$ e dunque in $Q_{[x]}$

Quindi un polinomio di qualsiasi grado in Q è irriducibile, per il criterio di Eisenstein.

Se abbiamo un polinomio di grado 127 in $R{[x]}$ sappiamo che i fattori irriducibili sono quelli di grado 1 o 2. Essendo 127 un numero dispari lo si puo scomporre in piu polinomi dove almeno un fattore deve essere necesssariamene essere dispari quindi necessariamente di grado 1 quindi esiste almeno un fattore riducibile Formalizziamo

###Teorema

Sia $f(x) \in R{[x]}$. Se $\delta(f)$ è dispari $\implies $ $f(x)$ possiede almeno una radice

$f=f_{1}...f_{t}$ con $f_{i}$ polinomi irriducibili

$\delta(f)=\delta(f_{i})+\delta(f_{2})+...+\delta(f_{t})$

poichè il grado di $f$ è dispari almeno un fattore ha grado 1 quindi f possiede una radice.


---

###Teorema

Sia $f(x) \in \mathbb{Z}_{[x]}$ e $\delta(f) \geq 1$

Se $\exists$ p primo : $(f(x))_{p}$ \in $\mathbb{Z}_{p}[x]$ ha grado $n=\delta(f)$ e $(f(x))_{p}$ è irriducibile in 

$\mathbb{Z}_{p}[x]$ $\implies$ f(x) è irriducibile in $\mathbb{Z}[x]$ e dunque in $Q[x]$

Vediamo come usare il teorema

$x^{3}+x+2$ $\in$ $Z[x]$

in $C[x]$ ha tre radici
in $R[x]$ possiede almeno una radice (grado dispari)

In questi due casi è riducibile.

$x^{3}+x+2$ $\in$ $Z_{5}[x]$

verifichiamo se ci sono radici sostituendo con i valori di $Z_{5}[x]$. Sarà irriducibile se privo di radici
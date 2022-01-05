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
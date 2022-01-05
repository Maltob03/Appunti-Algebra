#Reticoli

##Definizione di reticolo

Un insieme ordinato ($L , \le$) si dice reticolo $\iff$ $\forall a,b \in L$ $\exists$ $l'inf\{a,b\}$ e il $sup\{a,b\}$

L'$inf\{a,b\}$ viene indicato con $a \land b$

L'$sup\{a,b\}$ viene indicato con $a \lor b$

**MI RACCOMANDO E' PER a,b NON PER L**


Se ($L, \le$) totalmente ordinato $\implies$ $L$ reticolo.
Non vale il viceversa.

$\forall a,b \in L a \le b$ oppure $b \le a$ quindi:

$ \exists min \{a,b\} = a = inf \{a,b\}$
$ \exists max \{a,b\} = b = sup \{a,b\}$

**Non necessariamente se è un reticolo è totalmente ordinato**

($P(S) , \subseteq$) 

$\{A,B\}$

minoranti $\{A,B\}$ = $\{X \in P(S) | X \subseteq A, X \subseteq B \}$ = { $X \in P(S) | x \subseteq A \bigcap B\}$

$\exists$ inf $\{a,b\}$ = $A \bigcap B$

in quanto l'insieme dei minoranti è dato da tutti gli $x \subseteq A \land x \subseteq B$

$\exists$ sup $\{a,b\}$ = $A \bigcup B$

in quanto l'insieme dei minoranti degli insiemi $A,B$ è dato dagli $y$ tali che $A \subseteq y \land B \subseteq y$


Un reticolo può essere rappresentato anche come il seguente anello:

($L,\land,\lor$)

####Alcune prorpietà

1. Proprietà iterativa
$a \land a = inf \{a,a\} = a = sup \{a,a\} = a \lor a$

2. Proprietà commutativa

$\forall a,b \in L :$

$a\land b = inf \{a,b\} = inf \{b,a\} = b \land a$

$a\lor b = sup \{a,b\} = sup \{b,a\} = b \lor a$

3. Proprietà associativa

$\forall a,b,c \in L :$

$a \land (b \land c) = inf\{a,inf \{b,c\}\} = inf \{a,b,c\} = a \land b \land c = (a \land b) \land c$

Analogamente:

$a \lor (b \lor c) = (a \lor b) \lor c = a \lor b \lor c$

4. Legge di assorbimento

$\forall a,b \in L :$

$ a \land (b \lor a) = a \lor (b \land a) = a$

La relazione d'ordine $\le$ in un reticolo è la seguente:

$a \le b \iff$:

$a \land a = a$
$b \lor b = b$

Questo ci serve per passare da una struttura algebrica del tipo ($L,\land,\lor$) ad un insieme con la relazione d'ordine del tipo ($L, \le$)


**Verifica della relazione d'ordine**

$(L,\land,\lor)$

1. Riflessiva per la prorpietà iterativa

2. Asimmetrica $a \le b$ e $b \le a$ $\implies a=b$

$a=(a \land b)$
$b=(a \land b)$

$a = a \lor (a \land b) = a \lor b$

In questo caso sto applicando la legge di assorbimento. Molto più semplicemente essendo $a \le b \land b \le a \implies a=b$

3. Transitivà 

$a \le b$
$b \le c$

$a=(b \land a)$
$b=(b \land c)$

$a=(b \land a)$
$b=(b \land c)$

$a=a \land b = a \land (b \land c) = (a \land b) \land c = a \land c$

$\implies$

$a \le c$ 
$a = a \land c$

Abbiamo sfruttato la commutatività

##Omomorfismo di strutture algebriche

Abbiamo visto la compatibilità di una funzione con una relazione d'ordine.

Se consideriamo di nuovo

($S , \le_{1}$) e ($T , \le_{2}$)

ma li consideriamo come reticoli

$f: S \rightarrow T$

è necessariamente un omomorfismo di strutture algebriche ? NO

Consideriamo :

$f: n \in N \rightarrow 2^{n} \in N$

e consiedero come dominio ($N , \le$) e come codominio ($N$,/ ) entrambi reticoli.


$a,b \in (N,\le)$ allora $a \le b (b \le a)$

**Dominio**
$a \land b = a$
$a \lor b = b$

Se condisero $(N, /)$
**Codominio**
$a \land b = M.C.D$
$a \lor b = m.c.m$


Se considero due elementi $2,3 \in N$
**Dominio**
$2 \lor 3 = 3$
$2 \land 3 = 2$

Se condiero invece:
**Codomminio**
$f(2 \lor 3) = f(3)=2^{3} = m.c.m (2^{2},2^{3})$
$f(2 \land 3) = f(2)=2^{4} = (2^{2}, 2^{3})$

Ora però l'm.c.m tra 2 e 3 è 6 e il M.C.D tra 2 e 3 è 1, quindi:

$f(2 \lor 3) = f(6) = 2^{6} \not= f(2) \lor f(3) = 2^{3}$

Non risulta un omomorfismo.


##Sottoreticolo

Dato un reticolo ($L, \le$) con $H \le L$

$H$ è sottoreticolo $\iff$ $\forall a,b \in H$

$a \land b, a \lor b \in H$

Facciamo un osservazione.

Prendiamo un gruppo $G = \{1,x\}$ con l'operazione ($G,\bullet$) dove la condizione è che $x^{2}=1$  è un gruppo abeliano poichè l'elemento neutro è 1 e gli elementi inveritbili sono 1 e se moltiplico x per sè stesso ho l'opposto che è uguale a 1

Considero ora: 
$H=\{x\}$ 
Questo è stabile ? NO perchè $x \bullet x$ = 1 che $\not \in H$

$\forall x \in L$ però il $\{x\}$ è un sottoreticolo perchè:

$x \lor x = x = sup {x}$
$x \land x = x = inf {x}$

In un reticolo se considero un singleton del reticolo questo si dice sottoreticolo.

**Altro grosso esempio (che secondo me è anche piu chiaro)**

Consideriamo ($N , /$) e delle parti che dobbiamo definire stabili:

$H_{1} = \{2^{n} | n \in N\}$ stabile

$H_{2} = \{3^{n} | n \in N\}$ stabile

$H_{3} = \{2^{n}, 3^{n} | n \in N\}$ per lo stesso di $H_{6}$ motivo non stabile

$H_{4} =\{2,4\}$ è stabile perchè ($2 \land 4 = 2$ e $2 \lor 4=4$)

$H_{5} =\{3,9\}$ per lo stesso motivo di $H_{4}$ è stabile

$H_{6} =\{2,3\}$ non è stabile perchè ($2 \land 3 = 1$ e $2 \lor 3 = 6$) per essere stabile $H_{6} = \{1,2,3,6\}$


Se era invece ($N,\le$) tutti gli $H$ sarebbero stati stabili perchè tutti gli elementi sarebbero stati confrontabili.


##Reticoli trirettangoli e pentagonali

![reticoli](http://www.andreaminini.org/data/andreamininiorg/reticoli-non-distributivi.gif)

In un reticolo trirettangolo o pentagonale non valgono le proprietà distributive.



##Reticolo distributivo

In un reticolo $L$, dirò che $L$ è un reticolo distributivo $\iff$ $\forall a,b,c \in L$ 

1. $a \lor (b \land c) = (a \lor b) \land (a \lor c)$
2. $a \land (b \lor c) = (a \land b \lor (a \land c)$

Si puo dimostrare che se vale il punto 1. allora vale il punto 2.

##L'ESEMPIO DI RETICOLO DISTRIBUTIVO


($P(S), \bigcap, \bigcup$)

Infatti $\forall A,B,C \in P(S)$ 

i)$ A \bigcup (B \bigcap C) = (A \bigcup B) \bigcap (A \bigcup C)$ 

ii)$ A \bigcap (B \bigcup C) = (A \bigcap B) \bigcup (A \bigcap C)$ 

####Teorema

Un reticolo ($L,\land,\lor$) è un reticolo distributivo $\iff$ $L$ privo di sottoreticoli trirettangoli o pentagonali.

##Reticolo limitato

Un reticolo ($L,\land,\lor$) si dice limitato $\iff$

$\exists max L = 1_{L}$
$\exists min L = 0_{L}$

Se il reticolo è limitato $1_{L}$ è elemento neutro rispetto all'operazione $\land$, $0_{L}$ è elemento neutro rispetto all'operazione $\lor$

Infatti:

$\forall a \in L$ $a \land 1_{L} = inf \{a,1_{L}\}= a$
$\forall a \in L$ $a \lor 0_{L}= sup \{a,0_{L}\}= a$

($L,\land,\lor$) è limitato $\iff$ 

$\exists 1_{L}$ elemento neutro rispetto a $\land$
$\exists 0_{L}$ elemento neutro rispetto a $\lor$

Equivale a richiedere che $a \land 1_{L}= a \iff a \le 1_{L} \implies 1_{L}=maxL$ 

$a \lor 0_{L}= a \iff 0_{L} \le a \implies 0_{L}=maxL$

##Reticolo complementato


Sia ($L,\land,\lor$) è complementato $\iff$ 

1. $L$ è limitato$
2. $\forall$ a $\in$ L $\exists$ $a'$ $complemento$

$\exists a' \in L : a \land a' = 0_{L}$
$\exists a' \in L : a \lor a' = 1_{L}$

Un esempio di reticolo complementato è ($P(S), \bigcap, \bigcup$)

$P(S)$ è limitato da $S$ e $\varnothing$ 

e il complemento di $P(S)$ è $S$ \ $A$, 

 $\forall A \in P(S)$


##Reticolo booleano

Un reticolo ($L,\land,\lor)$ è booleano $\iff$

1. $(L,\land,\lor)$ è distributivo
2. $(L,\land,\lor)$ è complementato

#L'esempio di reticolo booleano è ($P(S),\bigcup,\bigcap$)

####Teorema

Sia ($L,\land,\lor$) un reticolo booleano allora il complemento di ogni elemento esiste ed è unico.


**Dimostrazione**

Supponiamo di avere $a \in L$

$a'$ e $a''$ siano suoi complementi

$a \land a' = a \land a'' = 0_{L}$
$a \lor a' O a \lor a'' = 1_{L}$

$a'=a' \land 1_{L} = a' \land (a \lor a'') = (a' \land a ) \lor (a' \land a'') = 0_{L} \lor (a' \land a'') = a' \land a'' \implies a' \le a''$.Ripetendo lo stesso discorso invertendo gli $a'$ e $a''$ trovo che $a'' \le a'$ quindi $a' = a''$

####Nota bene

Per essere $L$ un reticolo booleano l'ordine di $L$, ovvero $|L|$ deve essere una potenza di 2, questo poichè ogni reticolo booleano è un sottoreticolo di $P(S)$ che ha ordine $2^{n}$

Dato il reticolo (T,$\le$) = $\{1,2,3,4\}$

E' limitato, possiede un max e un min
E' distributivo non avendo sottostrutte interne.

MA non è complementato.

$\not \exist a \in T : a \land 2 = 1$ o a $\lor 2 = 4$


###Teorema di Stone

($L,\land,\lor$) è booleano $\iff$ 

$\exists x : L$ sia isomorfo a ($P(x),\bigcup,\bigcap$)

In particolare se L è finito $\implies$ $|L|$ = $2^{|x|}$

La condizione enunciata prima è necessaria ma non sufficiente in quanto il reticolo deve essere anche complementato


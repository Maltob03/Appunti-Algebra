#Grafi


##Grafi non orientati

Supponiamo di avere un insieme $V \not= \varnothing$ e un insieme $L$ $\subseteq P(V)$ e $\forall l \in L |l| = 2$

Facciamo un esempio

$V = \{a,b,c,d\}$

$L = \{\{a,c\},\{a,d\}\}$

Considero la Relazione $R$ definita in $V$ che ammette come grafico $G$ esattamente $L$

$G = \{x,y | x,y \in l$ e $ l \in L\}$


$R$ antiriflessiva: $\forall x \in V$ $x$$\not R x$
$R$ simmetrica: $\forall x,y \in l , y,x \in l$

$l$ saranno i lati del grafo mentre gli elementi di $V$ sono detti vertici del grafo

Un vertice che non appartiene a nessun lato è detto **isolato**.

Due vertici si dicono **adiacenti** $\iff$ $\exists l \in L : l=\{a,b\}$ quindi se appartengono allo stesso lato.

Due lati si dicono incidenti $\iff$ l'intersezione tra $l_{1},l_{2}$ è $\not= \varnothing$

Il grado di un vertice $d(v)$ è il numero dei lati a cui appartiene.

###Lemma

Sia V un grafo finito (l'ordine di V è finito) allora |L|= $\frac{1}{2}\sum d(v)$

Ogni grafo finito ammette un numero pari di vertici dispari.

Se $|V|$=n < $\infty$ e V è regolare di grado d

$\sum d(v)$ = $\frac{1}{2} n \bullet d = |L|$


$\exists$ un cammino da $v_{0}$ a $v_{t}$ $\iff$ 

$\exists \{l_{1},l_{2},...,l_{t}\}$: $l_{i}$ = $\{v_{i-1},v_{i}\}$

$l_{1}=v_{0},v_{1}$

$l_{t}={v_{t-1},v_{t}}$

Se $\exists$ un cammino non vuoto tra $v_{0}$ e $v_{0}$ parlo di circuito (sarebbe una struttura chiusa dove puoi arrivare di nuovo nel punto di partenza in piu versi).

Dati due grafi $V_{1}$ e $V_{2}$ esiste un isomorfismo di grafi $\iff$

$\exists f: V_{1} \rightarrow V_{2} biettiva :$

$\forall l \in L_{1} f(l) \in L_{2}$

osservazione se ho un isomorfismo $d(v)= d(f(v))$



$G(V,L)$ è connesso $\iff$ $\forall$ $j,w$ $\in V \exists$ un cammino da $v$ a $w$ 

{$l_{1},...,l_{n}$} e $l_{i}=\{z_{i-1},z_{i}\}$

con $z_{0}=v$ e $z_{n}=w$


componente connessa $\iff$ è sottografo connesso massimale

##Cammino Euleriano

Cammino euleriano (circuito euleriano) $\iff$

$L=\{l_{1},...,l_{n}\}$

##Teorema di Eulero

Sia $G$ un multigrafo finito e privo di vertici isolati. Allora $G$ ha un circuito Euleriano $\iff$ è connesso e tutti i suoi vertici sono pari.

Un circuito si dice Hamiltoniano se si passa per ogni vertice una sola volta

##Albero grafo

Si dice albero un grafo privo di circuiti e connesso

é una foresta le sue componenti connesse sono alberi

##Teoremi

Sia $G$ un grafo, sono equivalenti:

1. $G$ è un albero
2. $\forall v,w \in V \exists! $ cammino da v a W
3. $G$ è connesso e $\forall$ $l \in L$ e $L'=L$\ $\{l\}$
4. $G$ è privo di circuiti e $\forall$ v,w non adiacenti

$L'' = L \bigcup \{v,w\}$
$G''= (v,L'')$

##Teorema

Sia $G$ un grafo finito e |V|=n

Sono equivalenti:

1. $G$ è un albero
2. $G$ è privo di circuiti |L| = n-1
3. $G$ è connesso e |L| = n-1
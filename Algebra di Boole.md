
#Algebra di boole

In un insieme $A$ non vuoto si può considerare una struttura con una serie di operazioni del tipo:

($A,\perp_{1},\perp_{2},...,\perp_{t}$)

Algebra di Boole : una struttura del tipo:

($A , \land, \lor, '$)

$\land , \lor$ due operazioni binarie

$ ' : a \in A \rightarrow a' \in A$

1) $\forall a,b \in A a \lor b = b \lor a, a \land b = b \land a$
2) vale la proprietà associativa $\land,\lor$A
3) $\forall a,b \in A a \land (a \lor b)= a \lor (a \land b)=a$ legge di assorobimento
4) $\forall a \in a a \land a = a \lor a = a$
5) $\forall a,b,c \in A :$
i)$ a \land (b \lor c) = (a \land a ) \lor (a \land c)$
ii)$a \lor (b \land c)) = (a \lor b) \land (a \lor c)$

6) $\exists 0_{A}, 1_{A} : \forall a \in A a\lor 0_{A} = a \land 1_{A} = a$
7) $\forall a \in A a \land a' = 0_{A} e a \lor a' = 1_{A}$

Quando valgono tutte queste condizioni dirò che ho un algebra di boole

Un esempio di algebra booleana sarà dato da:

($P(S), \bigcap, \bigcup,$ \ )

Teorema di Stone può essere enunciato per le algebre di boole


($A , \land, \lor, '$) sia un algebra di boole allora:

$\exists  X : A$ sia isomorfa ad una sottoalgebra di ($P(X), \bigcap,\bigcup$,\ ) e se $A$ è finita allora isomorfa ($P(X)$)

Poi ripete i 7 punti applicati a P(S) ma non servono

##Anello Booleano 

Consideriamo un anello:

($P(S), \Delta, \bigcap$)

($P(S), \Delta$) gruppo abeliano, elemento neutro = $\varnothing$ e l'opposto $-A=A$

($P(S), \bigcap$) monoide, con elmento neutro $S$, vale la proprietà distributiva dell'intersezione rispetto alla differenza simmetrica.

$2 \bullet S = S \Delta S = S$ \ $S$ $\bigcup$ $S$ \ $S$ = $\varnothing$ = 0

La caratteristica è 2

$\forall A \in (P(S))$

$A^{2} = A \bigcap A = A$

$\forall A \in P(S)$ $A$ è idempotente

Un generico anello ($A,+,\bullet$) unitario

e suppongo valga la seguente proprietà

$\forall a \in A$  $a^{2}=a$

$ab = (ab^{2}) \bullet a \bullet b$

MA $ab = a^{2}b^{2}= a \bullet b \bullet b$

Altra osservazione $(a+b)^{2} = a^{2} + ab +b \bullet a + b^{2} = a + ab + ba +b$

$ab=-ba$ = $ba$

Anello è commutativo, ogni elemento coincide con il suo opposto

1_{A} = - 1_{A}

$2 \bullet 1_{A} = 1_{A} + 1_{A} = 0_{A}

caratteristica 2

($A,+,\bullet$) anello booleano $\iff$ anello unitario e $\forall a \in A a^{2} = a$

###($P(S), \Delta, \bigcap$) è l'esempio di anello booleano.

##Confronto tra reticolo boolean, algebra booleana e anello booleano.


Reticolo booleano ($L,\land,\lor$) 

Algebra booleana($L,\land,\lor$,')

Anello booleano ($A,+,\bullet$)

Se ho un reticolo booleano ($L,\land,\lor$) $\rightarrow$ $a \bullet b= a \land b$
$a+b= (a \land b') \lor (a' \land b)$

Se ho un anello booleano definisco la relazione d'ordine come :

$a \le b \iff a \bullet b = a$

Posso cosi passare tra le tre strutture



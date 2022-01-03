#Gruppi di permutazione


##Ripasso dell'insieme $S^{S}$

$S$ $\not$= $\varnothing$

$s^{S}$ = { $f$ $|$ $f:S \rightarrow S $}

Abbiamo visto poi il monoide non commutativo:

( $S^{S} , \circ $ )

$ g \circ f : x \in S \rightarrow g(f(x)) \in S$

L'elemento neutro corrisponde all' $id_{S}$ infatti:

$ id_{S} \circ f = f \circ id_{S} = f $ 

$\forall f \in S^{S}$

Se l'ordine di $S = n$ l'ordine di $S^{S}$ = $n^{n}$


Gli elementi invertibili di $S^{S}$ 

$ U(S^{S})$ = { $f$ $|$ $ \exists  f' : f \circ f' = f' \circ f = id_{S}$ } = { $ f \in S^{S} $ $|$ $f$ è biettiva } = $B(S)$

$|B(S)|$ = $n!$

Se $S$ è un insieme finito di ordine $n$ 

$|S|$ = $n$ $\iff \exists$ $h$ biettiva con $h:${$1,2,...,n$} $\rightarrow$ $S$

$S$ = $\{x_{1},x_{2},...,x_{n}\}$ = {$1,2,...,n$}



Indicheremo con $S_{n}$ = { $f$ $|$ $f \in B(S)$ }

####Esempio:

1) Primo caso:

$S = \{1\}$

Il numero di applicazioni biettive di $f$ in sè stesso è 1, che corrisponde all'$id_{s}$

$S_{1} = \{id_{s}\}$

$id_{s} : 1 \rightarrow 1$

2) Secondo caso:

$s = \{1,2\}$

Le applicazioni biettive sono l'$id_{s}$ e l'$inv_{s}$

$id_{s}$ :

$ 1 \rightarrow 1$
$ 2 \rightarrow 2$

E' possibile scrivere questo tipo di applicazione in una specie di forma contratta ovvero:

$\begin{pmatrix} 1 & 2\\ 1 & 2 \end{pmatrix}$ 


$inv$ :

$ 1 \rightarrow 2$
$ 2 \rightarrow 1$

$\begin{pmatrix} 1 & 2\\ 2 & 1 \end{pmatrix}$

Quindi $S_{2}$ sarà uguale a:

$S_{2} = \{ id_{s} , \begin{pmatrix} 1 & 2\\ 2 & 1 \end{pmatrix} \}$

3) Terzo caso:

$S = \{1,2,3\}$

Numero di applicazioni biettive $3!$ = $6$

$\begin{pmatrix} 1 & 2 & 3\\ 1 & 2 & 3 \end{pmatrix}$ = $id_{S}$

$\begin{pmatrix} 1 & 2 & 3\\ 2 & 3 & 1 \end{pmatrix}$ = $f_{2}$

$\begin{pmatrix} 1 & 2 & 3\\ 3 & 1 & 2 \end{pmatrix}$ = $f_{3}$

$\begin{pmatrix} 1 & 2 & 3\\ 1 & 3 & 2 \end{pmatrix}$ = $f_{4}$

$\begin{pmatrix} 1 & 2 & 3\\ 3 & 2 & 1 \end{pmatrix}$ = $f_{5}$

$\begin{pmatrix} 1 & 2 & 3\\ 2 & 1 & 3 \end{pmatrix}$ = $f_{6}$


$S_{3} = \{ id_{s}, f_{1}, f_{2}, f_{3}, f_{4}, f_{5}, f_{6}\}$


####Elementi invertibili di $S_{3}$

Essendo ($S_{3}$, $\circ$) gruppo oltre ad avere elemento neutro = $id_{S}$ deve avere tutti gli elementi invertibili. Verifichiamo:


$( 1 2 3 )^{-1} = (1 3 2)$ infatti :

$(123)(132) = id_{S}$

Ma non abbiamo finito in quanto non essendo commutativa dobbiamo verificare anche che:

$(132)(123) = id_{S}$

Altri esempi sono:

$(1 2 )^{-1} = (12)$
$(1 3 )^{-1} = (13)$
$(2 3 )^{-1} = (23)$


##Permutazioni

Se ho una qualsiasi permutazione $\sigma \in S_{n}$

$\sigma$ si può esprimere come il prodotto di cicli disgiunti.

Due permutazioni $\sigma$ e $\tau$ $\in$ $S_{n}$

$X(\sigma) = { i | \sigma(i) \not= i }$


$\sigma$ e $\tau$ sono disgiunti $\iff$ $X(\sigma$ $\bigcap$ $X(\tau)$

e la decomposizione è unica a meno d'ordine dei fattori

####Esempio:

$S_{7}$


$\begin{pmatrix} 1 & 2 & 3 & 4 & 5 & 6 & 7 \\ 2 & 5 & 1 & 3 & 7 & 6 & 4 \end{pmatrix}$

$X(\sigma) = \{1,2,3,4,5,6,7\}$ =

( 1 2 5 7 4 3)

<br>

$\begin{pmatrix} 1 & 2 & 3 & 4 & 5 & 6 & 7 \\ 7 & 4 & 3 & 2 & 6 & 5 & 1 \end{pmatrix}$

$X(\tau) = \{1,2,3,4,5,6,7\}$ = 

(1 7) (2 4) (5 6)

Una trasposizione è un ciclo di lunghezza 2

####Teorema

$\forall n \geq 1 $ $S_{n}$ si puo generare tramite le sue trasposizioni.

$T = \{ \tau \in S_{n}$ | $ \tau = ( i j) }

$<T> = $$S_{n}$


###Ritorniamo a $S_{3}$

$S_{3} = \{ id_{S}, (123), (132) , (12), (13), (23)\}$

$S_{3}$ ammette sottogruppi, ad esempio:

$A_{3}$ { $id_{S}, (123), (132)$ }

Da definizione di sottogruppo:

$G$ tale che $H \subseteq G$ $H$ è sottogruppo $\iff$ 

$H$ è stabile ( e questo sottogruppo $A_{3}$ è stabile)
($H$ , $\bullet$ ) gruppo.


##Trasposizioni pari e dispari

$\sigma$ è una trasposizione pari $\iff$ $\sigma$ si esprime come prodotto di un numero pari di trasposizioni.

$\sigma$ è una trasposizione dispari $\iff$ $\sigma$ si esprime come prodotto di un numero dispari di trasposizioni.

Una trasposizione è sempre dispari

Un ciclo di lunghezza 3 ( i j k) = (i j) (i k) pari.

Piu in generale un ciclo di lunghezza k si puo esprimere come il prodotto di $k-1$ trasposizioni.Pertanto se k è pari il ciclo è dispari mentre se k è dispari il ciclo è pari
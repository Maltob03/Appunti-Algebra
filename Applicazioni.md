#Corrispondenza, relazioni, applicazioni


<br>


##Applicazioni



###$f$ è un applicazione o funzione $\iff$ $\forall$ $x$ $\in$ $S$ $\exists$$! $$y$ $\in$ $T$: $x$ $f$ $y$ $con$ $(x,y)$ $\in$ $G$

###Dove S è il dominio e T è il codominio

###$\varphi$ = ($SxT, G$) 


###Immagine di x tramite $f$

###$x$$f$$y$ = $f(x)$ = $y$ 

$f$ $S$ $\implies$ $T$ $oppure$ $x$ $\implies$ $f(x)=y$

<br>


##Negazione della definizione di applicazione


###$\exists$ $x$ $\in$ $S$ : ($\not$$\exists$$ $$y$ $\in$ $T$:$(x,y)$ $\in$ $G$) $\lor$ ($\exists$ $y1,y2:(x,y1),(x,y2)$ $\in$ $G$ $con$ $ y1$ $\not$ = $y2$

<br><br>

##Esempi di applicazioni

$S$ = $\mathbb{N}$

$T$ = $\mathbb{Z}$

$G1$ = { $(x,y) $ $\in$ $ $$\mathbb{N}$x$\mathbb{Z}$ $ |$ $ x=y+1$ } 

$G2$ = { $(x,y) $ $\in$ $ $$\mathbb{N}$x$\mathbb{Z}$ $ |$ $ y=x+1$ } 


**Entrambe determinano un' applicazione**


$G3$ = { $(x,y) $ $\in$ $ $$\mathbb{Z}$x$\mathbb{N}$ $ |$ $ y=x+1$ } 

**Questa non determina un'applicazione in quanto se considero la x come -5 ricavandomi la y avrò come risultato -4 che non appartiene all'insieme N.**



##Esempi di applicazioni notevoli

####Applicazione somma

$S$ = $\mathbb{N}$x$\mathbb{N}$

$T$ = $\mathbb{N}$


$G1$ = {$(x,y)$ $\in$ $SxT : x1+x2=y$}

*Dove nella prima variabile x vi sono le coppie $x1,x2$ appartenenti a S, mentre nella variabile y gli elementi appartenenti a T*

Ovviamente questo tipo di applicazione non è **iniettiva** [^1]


Nello stesso modo considerando S = $\mathbb{Z}$X$\mathbb{Z}$ si definisce l'applicazione differenza

<br>

[^1]: Definiremo una funzione **iniettiva** quando ad un elemento del dominio è associato un unico elemento del codominio.


##Definizione di funzione iniettiva e suriettiva


###Definzione funzione iniettiva:

Una funzione si dice **iniettiva** se e solo se ad uno specifico elemento del dominio è associato uno specifico elemento del codominio

$\forall$ $x1,x2 $$\in$ $S $$\implies$ $f(x1)=f(x2) $$\implies$ $x1=x2$

Un esempio di funzione (o applicazione) iniettiva è la somma che abbiamo visto prima in quanto:

$2+2=4=3+1$
**MA** $2+2 $ $\not$$= 3+1 $

--

###Definizione di funzione suriettiva:

Una funzione si dice suriettiva se per ogni elemento del codominio esiste un elemento del codominio tale che $f(x)=y$

$\forall$ $x$ $\in$ $S $ $\exists$ $y$ $\in$ $T$ $|$ $f(x)=y$



###Caratterizazioni
Se $f(x)$ è iniettiva l'antimmagine (ovvero la funzione inversa) o è un singleton o è il $\varnothing$ [^2]

Se $f(x)$ è suriettiva l'antimmagine (ovvero la funzione inversa) associa necessariamente un elemento del dominio.

<br>


[^2]: Si dimostra per assurdo e si verificano le due implicazioni. Dimostrazione da integrare in un formulario

##Riassunto con definizioni e caratterizzazioni, definizione di biettività

**Definzione applicazione iniettiva:**  
$\forall$ $x1,x2 $$\in$ $S $$\implies$ $f(x1)=f(x2) $$\implies$ $x1=x2$

$\forall$ $x1$$\not$ = $x2 $$\in$ $S $$\implies$ $f(x1)$$\not$ = $f(x2)$    
**Caratterizzazione applicazione iniettiva:**

$\not$$\exists$ $x1$ $\not$= $x2$ :  $f(x1)$=$f(x2)$
  
$\forall$ $y$$\in$ $T$ $f^{-1}$({$y$}) o è $\varnothing$ o un singleton {x}

**Definzione applicazione suriettiva:**

$\forall$ $y$ $\in$ $T$ $\exists$ $x$ $\in$ $S$ : $f(x)=y$  

**Caratterizzazione applicazione suriettiva:**

$\forall$ $y$ $\in$ $T $ $f^{-1}$({$y$}) $\not$= $\varnothing$

**Definizione funzione biettiva**

$f(x)$ si dice biettiva se solo se $f$ è iniettiva e suriettiva.

Definizione : $\forall$ $y$ $\in$ $T$ $\exists$! $x$$\in$$S$ : $f(x)=y$
 
**Caratterizzazione funzione biettiva**  

$\forall$ $y$ $\in$ $T $ $f^{-1}$({$y$}) = {$x$}



##Inisieme finito.

Si dice S iniseme finito $\iff$ 

1. S = $\varnothing$
2. $\exists$ $f$: $S$ $\rightarrow$ {$1,2,...,n$} **biettiva** tale che $|S|$ = n ovvero l'ordine di $S$ = n

Se due insiemi S e T hanno stesso ordine si dicono equipotenti.

$|S|$ = $|T|$ **equipotenti** allora $\rightarrow$

1. $f$: $S$ $\rightarrow$ $T$ è iniettiva $\implies$ è biettiva
2. $f$: $S$ $\rightarrow$ $T$ è suriettiva $\implies$ è biettiva [^3]

[^3]: Dimostazione n.3 del formulario che ancora deve esistere

<br>


##Applicazione composta

Consideriamo due generiche applicazioni $f$ e $g$ :

$f$: $S$ $\rightarrow$ $T$ e $g$: $T$ $\rightarrow$ $V$

$f$$\circ$$g$ = $g$$\circ$$f$ : $S$$\rightarrow$$V$

L'applicazione composta è una applicazione dove il codominio della funzione $f$ sarà il dominio della funzione $g$.

Esempio di applicazione composta:

$f$: $x$ $\in$ $\mathbb{Z}$ $\rightarrow$ $3x+1$ $\in$ $\mathbb{Z}$

$g$: $x$ $\in$ $\mathbb{Z}$ $\rightarrow$ $|y|$ $\in$ $\mathbb{N}$

$g$$\circ$$f$ : $\mathbb{Z}$ $\rightarrow$ $\mathbb{N}$ 

$x$ $\rightarrow$ $g(f(x))$ = $g(3x+1)$ = $|3x+1|$


##Applicazione identità e costante

###Applicazione identità
L'applicazione identità è un applicazione definita da $S$$\rightarrow$$S$. Questa funzione associa ad un elemento $x$ $x$ stesso. Viene detta anche diagonale di S ed è un applicazione biettiva. 

###Applicazione costante

L'applicazione $f$ definita da $S$ $\rightarrow$ $T$ che ad ogni elemento x $\in$ $S$ associa lo stesso elemento $y$ $\in$ $T$ tale che: 

$f(x)$ = $y$ $\forall$ $x$ $\in$ $S$

##Restrizione del Dominio

Consideriamo un'applicazione 

$f$: $S$ $\rightarrow$ $T$ con $f=(SxT,G)$

$G$ = {$(x,f(x) : x $$\in$ $S$}

E'possibile restringere il dominio ponendo

$A$ $\subseteq$ $S$

Determinando quindi un nuovo grafico

$Ga$ = {$(x,f(x) : x $$\in$ $A$}

**Esempio di restrizione del dominio**

$f$ $x$ $\in$ $\mathbb{Z}$ $\rightarrow$ $|x|$ $\in$ $\mathbb{N}$

$G$ = {$(x,|x|) : x$ $\in$ $\mathbb{Z}$}

Considero quindi la restrizione $f_{A}$

$f$ $x$ $\in$ $\mathbb{N}$ $\rightarrow$ $|x|$ $\in$ $\mathbb{N}$

In entrambi i casi l'applicazione risulta essere **suriettiva**.

Nel primo caso però l'applicazione **non** è iniettiva in quanto $-4=4=4$ **MA** $-4$ $\not$= $4$

Nel secondo caso l'applicazione risulta essere iniettiva in quanto corrisponde ad un applicazione identità che va da N in N. L'applicazione quindi risulta essere biettiva.


Elenco alcune caratterizzazioni:

*( $f'$ è una funzione con dominio ristretto)*

$f$ iniettiva $\implies$ $f'$ iniettiva
$f$ non iniettiva $\not$$\implies$ $f'$ non iniettiva
$f$ suriettiva $\not$$\implies$ $f'$ suriettiva
$f$ non suriettiva $\implies$ $f'$ non suriettiva.


##Applicazione inversa

Se $f$ è **biettiva** $f^{-1}$ : $y$  $\in$ $T$ $\implies$ $x$ $\in$ $S$ dove x è l'unico elemento in $S$ tale che $f(x)=y$


Esempio

$f$ : $x$ $\in$ $\mathbb{Q}$ $\rightarrow$ $3x+1$ $\in$ $\mathbb{Q}$

**E' iniettiva ?** 

3x<sub>1</sub> +1 = 3x<sub>2</sub> +1 quindi x<sub>1</sub>=x<sub>2</sub>

Quindi **iniettiva**

**E' suriettiva ?** SI

Mi ricavo quindi la x sapendo che $y$ = $3x+1$ $\rightarrow$ $x$ = $\frac{y-1}{3}$

$f^{-1}$($\frac{y-1}{3}$) = $3$$\times$$($$\frac{y-1}{3}$$)+1$= $y$

###Condizioni di invertibilità

$f$ è inveribile $\iff$ $\exists$ $f^{-1}$  : $T$ $\rightarrow$ $S$ : $f$$\circ$$f^{-1}$ = $id_{T}$

$f$ è inveribile $\iff$ $f$ è biettiva $f^{-1}$$\circ$$f$ = $id_{S}$
<h1>Logica #0</h1>

-

 Quando è possibile attribuire un valore di verità ad una proposizione si tratta di una <mark>formula chiusa.</mark>
 
 **Esempio:** "il Vesuvio è alto almeno 1500m"
 
 A questa proposizione è possibile assegnare un valore di verità, si tratta quindi di una formula chiusa.
 
 **Un esempio di formula non chiusa è:** "x>3" in quanto x è una variabile non definita che non ci permette di assegnare un valore di verità a tale proposizione.Con l'ausilio dei così detti **quantificatori** è possibile assegnare un valore di verità a tale proposizione.  
Questi sono:
 
 **$\forall$** che si legge "per ogni"  
 **$\exists$** che si legge "esiste". 
 
 Tramite l'uso dei quantificatori universali è possibile assegnare un valore di verità alla proposizione **"x>3"**
 
 Vi sono poi delle eccezioni dove si definiscono formule chiuse proposizioni con variabili non definite, ad esempio:  
 x=x oppure x$\not=$x
 
##Connettivi

Per formulare proposizioni più complesse si usano i connettivi ("unari o binari"). Ogni connettivo ha una sua tavola di verità


###Negazione

    P     |$\neg$$P$|     
:--------:|:-------:|
    V     |   F     |
    F     |   V     |
    
 P: "Vado a Barcellona"  
 $\neg$$P$: "**Non** vado a Barcellona.  
 
 
###Connettivi binari: Congiunzione e Disgiunzione inclusiva

P $\land$ Q P **and** Q Congiunzione.  
P $\lor$ Q P **or** Q Disgiunzione inclusiva. 

###Tavole di Verità

    P     |     Q    |P $\land$ Q| P $\lor$ Q |
:--------:|:--------:|:---------:| :---------:|
    V     |    V     |  V        |      V     |
    V     |    F     |  F        |      V     |
    F     |    V     |  F        |      V     |
    F     |    F     |  V        |      F     |
    
  
  
###Connettivo dell'equivalenza

P $\iff$ Q ha valore di **vero** quando le due proposizioni hanno lo stesso valore di verità

    P     |    Q    |   P$\iff$ Q|     
:--------:|:-------:|:----------:|
    V     |   V     |		V		|
    V     |   F     |		F		|
    F     |   V     |		F		|
    F     |   F     |		V		|
    
 
 
###Connettivo dell'implicazione

P$\implies$ Q si legge P **"implica"** Q. Ricorda da un'ipotesi falsa il valore dell'implicazione è sempre vero

    P     |    Q    |   P$\implies$ Q|     
:--------:|:-------:|:----------:|
    V     |   V     |		V		|
    V     |   F     |		F		|
    F     |   V     |		V		|
    F     |   F     |		V		|
    
    
  <br><br>
    
##Tautologie e contraddizioni


###$\Phi$ ha sempre valore di vero si dice "Tautologia".
###$\neg$$\Phi$ ha sempre valore di falso si dice "Contraddizione"


###Tavola di verità
    P     |     Q    |P $\implies$ Q| Q $\implies$ P| $\neg$P $\implies$ $\neg$Q | $\neg$Q $\implies$ $\neg$P |
:--------:|:--------:|:---------:| :---------:      |  :---------:   | :-------------:|
    V     |    V     | <span style="color:blue">V</span>         |<span style="color:red">V</span>|<span style="color:red">V</span>|<span style="color:blue">V</span>
    V     |    F     |  <span style="color:blue">F</span>        |<span style="color:red">V</span>|<span style="color:red">V</span>|<span style="color:blue">F</span>
    F     |    V     |  <span style="color:blue">V</span>        |<span style="color:red">F</span>|<span style="color:red">F</span>|<span style="color:blue">V</span>
    F     |    F     |  <span style="color:blue">V</span>        |<span style="color:red">V</span>|<span style="color:red">V</span>|<span style="color:blue">V</span>
  
  
  
  
###P$\implies$Q   e   $\neg$Q $\implies$$\neg$P sono tautologie
###Q$\implies$P e  $\neg$P$\implies$$\neg$Q sono tautologie

<br><br>

##Proprietà 


###Idempotenza

**P$\land$Q$\implies$P**
**P$\lor$Q$\implies$P**

###Commutatività

**(P$\land$Q)$\iff$(Q$\land$P)**
**(P$\lor$Q)$\iff$(Q$\lor$P)**
**(P$\iff$Q)$\iff$(Q$\iff$P)**



###Distributività

**P$\land$(Q$\land$R)$\iff$(P$\land$Q)$\lor$(P$\land$R)**
**P$\land$(Q$\land$R)$\iff$(P$\land$Q)$\lor$(P$\land$R)**
**P$\implies$(Q$\lor$R)$\iff$(P$\implies$Q)$\lor$(P$\implies$R)**
**P$\implies$(Q$\land$R)$\iff$(P$\implies$Q)$\land$(P$\implies$R)**


###Transitività

**(P$\implies$Q)$\land$(Q$\implies$R)$\implies$(P$\implies$R)**


<br>


##Leggi di De Morgan



    P     |     Q    |P $\lor$ Q   | P $\land$ Q | $\neg$P $\land$ $\neg$Q     |     $\neg$P $\lor$ $\neg$Q  | $\neg$(P$\land$Q)               | $\neg$(P$\lor$Q)|
:--------:|:--------:|:---------:       | :---------:     |  :---------:                   | :-------------:                 |                       :--------:|         :-------:|
    V     |    V     |          V       |     V           |<span style="color:red">F</span>|<span style="color:blue">F</span>|<span style="color:blue">F</span>|<span style="color:red">F</span>
    V     |    F     |          V       |     F           |<span style="color:red">F</span>|<span style="color:blue">V</span>|<span style="color:blue">V</span>|<span style="color:red">F</span>
    F     |    V     |          V       |     F           |<span style="color:red">F</span>|<span style="color:blue">V</span>|<span style="color:blue">V</span>|<span style="color:red">F</span>
    F     |    F     |          F       |     F           |<span style="color:red">V</span>|<span style="color:blue">V</span>|<span style="color:blue">V</span>|<span style="color:red">V</span>


###$\neg$P$\land$$\neg$Q $\iff$ $\neg$(P$\lor$Q) è una tautologia
###$\neg$P$\lor$$\neg$Q $\iff$ $\neg$(P$\land$Q) è una tautologia

<br>

##Altri connettivi

**XOR** $\oplus$ (Non è questo il simbolo ma va beh) corrisponde alla congiunzione latina out out

###Tavola di verità

    P     |    Q    |   P$\oplus$Q|     
:--------:|:-------:|:----------:|
    V     |   V     |		F		|
    V     |   F     |		V		|
    F     |   V     |		V		|
    F     |   F     |		F		|
    
    
    
    
###NOT AND  E   NOT OR
Non sono altro che la negazione dell'and e dell'or e le tavole di verità corrispondono con le relazioni di De Morgan



###Alcune proprietà di questi connettivi:

P$\oplus$(Q$\oplus$R)$\iff$(P$\oplus$Q)$\oplus$R **Proprietà associativa**
P$\oplus$Q $\iff$ Q$\oplus$P **Proprietà commutativa**
($\neg$P$\iff$$\neg$Q)$\iff$(P$\oplus$Q) **E' una tautologia**

<br><br>

##Quantificatori

**$\exists$** $\implies$ **"Esiste"**
**$\exists$!** $\implies$ **"Esiste ed è unico"**
**$\forall$** $\implies$ **"Per ogni"**

###Negazione dei quantificatori

$\forall$x($\varphi$) $\implies$ $\neg$($\forall$x($\varphi$)) $\iff$ $\exists$x($\neg$$\varphi$)
$\exists$x($\varphi$) $\implies$ $\neg$($\exists$x($\varphi$)) $\iff$ $\forall$x($\neg$$\varphi$)

**La negazione di $\exists$! è non esiste o esistono almeno due x($\varphi$)**

Def. $\exists$! :   
$\exists$! x($\varphi$)) $\iff$ ($\exists$x($\varphi$)) $\land$ ($\varphi$(y) $\iff$ x=y))

Negazione:

$\neg$($\exists$! x($\varphi$)) $\implies$ ($\forall$x($\neg$$\varphi$)) $\lor$ ($\exists$ x$\not$=y , $f(x)$$\not$=$f(y)$)
<br><br>


##$\varphi$ dipendente da x e y

Data una qualsiasi forma $\varphi$ si possono combinare più quantificatori per formulare proposizioni complesse a cui è possibile assegnare un valore di verità.

<H4>$\exists$x ($\forall$y ($\varphi$))</h4> è una proposizione a cui possiamo assegnare un valore di vero o falso. Questa nello specifico ha un valore di **falso** in quanto non potendo fissare la y ad un valore fisso è impossibile determinare un valore di x che vada bene per ogni y tale che valga la forma $\varphi$. E' possibile dimostrare che questa proposizione sia falsa valutandola per assurdo, ovvero negandola.


####$\forall$x ($\exists$y ($\neg$$\varphi$)).

Prendiamo come esempio di $\varphi$= $x<y+3$

se pongo $y$ = $x-3$ ottengo $x<(x-3)+3$ ovvero:

 $x<x$ 
 
 **UN ASSURDO!!!**
 
 Quindi la proposizione principale ha valore di falso.
   
   <br>
   
**Vediamo un altro esempio:** 
####$\forall$x ($\exists$y ($\varphi$))
Anche per questa proposizione è possibile determinare un valore di verità.Considerando sempre la stessaforma $\varphi$=$x<y+3$ posso fissare un valore di $y$ tale che valga $\forall$x. Ad esempio fissando $y=x$ ottengo che:

$x<x+3$ e questo è sempre vero $\forall$x quindi la proposizione risulta essere **vera**
 
                                                      


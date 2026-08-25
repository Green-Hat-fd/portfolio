<link href="./other/styles.css" rel="stylesheet">

<right-text><a href="./">[ English versione here ]</a></right-text>

<br>


# Chi sono
Ciao, sono Francesco, un programmatore junior che sta cercando un lavoro nell'industria dei (video)giochi.

Ho studiato Game Development & Game design alla Nautilus Academy, mentre ora sto lavorando a _[Going to Sleep](#going-to-sleep)_, un giochetto basato sul contare le pecore prima di addormentarsi. [[Altro&hellip;]](./ita_about "Vai alla pagina &quot;Chi sono&quot; &rarr;")


Il mio CV: [[qui]](./assets/pdf/francesco_degno_cv_ita_s.pdf "Clicca per scaricare il mio CV") – <i style="color: DeepSkyBlue">(versione intera alla fine)</i>


### &ensp; Conoscenze di programmazione

| Livello        | Lingue | Game Engine   |
|----------------|--------|---------------|
| `Intermedio`   | C#     | Unity         |
| `Principiante` | C++    | Unreal Engine |

<br>


# Progetti

### &emsp; Yamigatari:FOR3ST

<div style="display: flex; justify-content: flex-start; align-items: center; width: 100vw;">
    <iframe width="500" height="300" src="https://www.youtube.com/embed/gNR3R6dprqY" title="YAMIGATARI: FOR3ST — Official Trailer (2D Psychological Horror Game)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"  allowfullscreen style="margin: 0.5em;"></iframe>
    <iframe src="https://store.steampowered.com/widget/4025010/" title="The official Steam page of YAMIGATARI: FOR3ST" frameborder="0" width="646" height="190" style="scale: 1;"></iframe>
    <!-- OG video: width="914" height="533" / OG Steam: width="646" height="190" -->
</div>


| Ruolo                 |
|-----------------------|
| Traduttore principale |

`(Descrizione di Steam)` _Yamigatari:FOR3ST_ è un gioco horror psicologico in 2D che racconta la raggelante storia di una giovane ragazza intrappolata in un incubo dal quale non riesce a scappare. Quello che è iniziato come un tranquillo ritiro nella natura si è subito trasformato in una disperata battaglia per la sopravvivenza quando Nora scopre che un'entità la sta perseguitando tra gli alberi. 

**Nota:** Il direttore ha chiesto (nel suo server Discord) se ci fossero persone disposte a tradurre il gioco in altre lingue, e io mi sono offerto di aiutare a tradurlo in italiano.

* * *

### &emsp; Fight 4 Life

<img alt="F4L screenshot" src="./assets/images/screenshots/F4L-screen.jpg" width="47.5%">
<img alt="F4L carousel (GIF)" src="./assets/images/screenshots/F4L-carousel.gif" width="47.5%">

| Ruoli                    |
|--------------------------|
| Programmatore principale |
| Game Designer            |

_Fight 4 Life_ è un gioco survival indie in 2D dove la temperatura del sole è oltre le stelle e 4 personaggi si trovano intrappolati dentro una stazione della metro, mentre provano a trovare riparo dal calore. Il compito del giocatore è quello di tenerli in vita, dividere le risorse, esplorare nottetempo l'esterno di una stazione e lottare qualora fosse necessario.

Ciò che iniziò come un piccolo gioco scritto in `C` per la console dei comandi, iniziò come un idea che poi si è trasformata in questo piccolo gioco/progetto extra fatta con un'amica mia!

**_Sfide_**

- _Fight 4 Life_ è un gioco fatto in 3 mesi, con un'amica (io mi sono occupato del codice, lei dell'aspetto visivo, e entrambi abbiamo gestito il game design & bilanciamento)
    - abbiamo provato a gestire il tempo completando il Game Design Document per la fine delle prime 2 settimane, finendo le meccaniche (e asset) più importanti per la metà del 2° mese, aggiungendole e rifinendole per la fine del 3° mese
- Il gioco presenta il "Minig-aim", un minigioco con una barra a scorrimento, dove bisogna fermare la barra più al centro possibile, ma il movimento e la velocità della barra stessa dipende da quale arma hai trovato
    - All'inizio, sembrava molto divertente ma mancavano ricompense, dunque abbiamo deciso di ricompensare il giocatore dando più risorse al quanto più la barra è vicina al centro

<!--**_Feature_**

- Un minigame con una barra a scorrimento &ndash; il Mira-game
    - Usato nelle lotte per difenderti contro i brutti ceffi
    - Ogni arma determina lo stile di movimento della barra
- In ogni stazione si trovano diversi tipi di risorse
- Musica dinamica
    - Cambia se c'è un personaggio in esplorazione o no
    - Diventa più intensa nelle lotte
- 2 lingue (italiano & inglese)
- 2 finali-->

* * *

### &emsp; Spaceships' Threat

<img alt="ST screenshot" src="./assets/images/screenshots/ST-screen.JPG" width="47.5%">
<img alt="ST carousel (GIF)" src="./assets/images/screenshots/ST-carousel.gif" width="47.5%">

| Ruoli                    |
|--------------------------|
| Programmatore principale |
| Game Designer            |
| Artista principale       |

_Spaceships' Threat_ è un piccolo gioco arcade in 3D che si basa su azioni rapide e sulla rigiocabilità. Ti trovi nei panni del cattivo, il quale vuole conquistare l'universo a tutti i costi, distruggendo tutte le astronavi dei "buoni", raccogliere i loro Rottami e usarli per migliorare la sua astronave per poter conquistare sempre di più!

**Challenge(s)_**

- _Spaceships' Threat_ ha un semplice ma intricato sistema di salvataggio, il quale salva parti importanti (come la valuta corrente, miglioramenti sbloccati e impostazioni presenti in quel momento) partendo inizialmente da variabili tenute in uno Scriptable Object (e dunque accessibile e editabile da qualsiasi parte del gioco), per poi scriverle tutte in un file nel pc
    - (Devo dire che sono molto fiero di come ho fatto questo sistema di salvataggio)
- Un aspetto importante di questo gioco è la _rigiocabilità_: per ottenere questo aspetto, ho reso i Rottami (la valuta del gioco) in modo "persistente", ovvero che vengono aggiunti a quelli guadagnati prima ad ogni Game Over
    - Aggiungendo anche i Miglioramenti (Power-up), l'aspetto di rigiocabilità è aumentato - avendo anche preso ispirazione da alcuni giochi arcade + dei factory game usciti di recente (che ti fanno migliorare col tempo mentre ti fanno guadagnare più valuta di gioco)

<!--**_Feature_**

- Un sistema di salvataggio realizzato da sé (in cui salva la quantità di valuta e le opzioni presenti in quel momento)
- Miglioramenti (Power-up) che vengono applicati all'astronave
- Rigiocabilità: sconfiggi "i buoni" per guadagnare più Rottami (la valuta) e potenzia la tua astronave per poterli sconfiggere meglio-->

* * *

### &emsp; Going to Sleep

<!-- ~~![G2S screenshot](Images here)~~ -->

Un piccolo gioco in sviluppo che si basa sull'atto di contare le pecore prima di addormentarsi, ispirato dall'atto del contare le pecore e dalla sua rappresentazione nei cartoni animati.

**_Sfide_**

- Un minigame con una barra scorrevole curva con una piccola pecora, la quale aiuterà il personaggio principale ad addormentarsi
    - (lo stesso concept di quello trovato in _[Fight 4 Life](#fight-4-life)_)


## Lavoro in accademia

&emsp; &emsp; <sup>(Tutto protetto da Nautilus Academy Copyright)</sup>

### &ensp; _Quiet puzzles_

<!-- FIXME: QP screen -->
~~![QP screenshot](Images here)~~
<!--  <img alt="GlS screenshot" src="./assets/images/screenshots/GlS-screen.jpg" width="47.5%">  -->
<!--  <img alt="GlS concept art" src="./assets/images/screenshots/GlS-concept-art.jpg" width="40%">  -->

<!--<sup>(Left: game screenshot; Right: concept art of the game)</sup>-->


| Ruoli              |
|--------------------|
| Programmatore      |
| Game Designer      |
| Artista principale |

_Quiet Puzzles_ è la demo di un gioco puzzle-platformer in 3D in prima persona che utilizza 3 abilità principali. Vengono sbloccate per tutta la demo e il giocatore deve utilizzarle in un paio di puzzle.

&ensp; &ensp; (Questo gioco è stato realizzato con l'aiuto di altre persone quando studiavo all'accademia)

**_Sfide_**

- 3 diversi tipi di abilità (la "Mano", la "Pistola d'Acqua" e la "Bomba")
    - Una ruota per le abilità su cui lavorato e sviluppato, nel quale le abilità ruotano, usando la rotellina del mouse per ciclare tra di esse

### &ensp; _Walking the planks_

<!-- FIXME: WtP screen -->
~~![WtP screenshot](Images here)~~
<!--  <img alt="GlS screenshot" src="./assets/images/screenshots/GlS-screen.jpg" width="47.5%">  -->
<!--  <img alt="GlS concept art" src="./assets/images/screenshots/GlS-concept-art.jpg" width="40%">  -->

<!--<sup>(Left: game screenshot; Right: concept art of the game)</sup>-->


| Ruoli              |
|--------------------|
| Programmatore      |
| Game Designer      |
| Artista principale |

_Walking the planks_ è la demo di un gioco platformer in 3D in prima persona con il tema dei pirati dove il personaggio principale deve attraversare diverse trappole e ostacoli. Con ciò, il giocatore deve utilizzare la sua pistola a pietra focaia per i puzzle e l'intero gioco.

&ensp; &ensp; (Questo gioco è stato realizzato con l'aiuto di altre persone quando studiavo all'accademia)

**_Sfide_**

- Una pistola sempre carica che può distruggere i bersagli e attivare alcuni interruttori
- Una botte ("botte ruzzolante") ispirata dai cartoni animati su cui il giocatore può salirci e rolotata 
    - Quando ci si sale, il giocatore deve muoversi all'indietro per poter far rotolare la botte in avanti, e viceversa (seguendo come la fisica)
    > (Creato usando il Prodotto Vettoriale tra la direzione di dove il giocatore sta guardando e la direzione "davanti" ("forward") del barile – limitando il movimento del giocatore per potersi muovere solo di lato, non avanti o indietro, quando si trova sopra il barile)
- Due diversi tipi di pulsanti: uno a interruttore (che rimane nell'ultima posizione in cui viene attivato) e uno a pressione (il quale deve rimanere premuto per rimanere attivo)
    - Entrambi sono basati sulla fisica (quindi o il giocatore o gli oggetti, come delle scatole, possono interagirvi)
- Una meccanica basata sul Rum che mostra delle piattaforme nascoste per un certo periodo di tempo quando bevuto

### &ensp; _GlyphSeeker_

<img alt="GlS screenshot" src="./assets/images/screenshots/GlS-screen.jpg" width="47.5%">
<img alt="GlS concept art" src="./assets/images/screenshots/GlS-concept-art.jpg" width="40%">

<sup>(Sinistra: screenshot del gioco; Destra: concept art del gioco)</sup>

| Ruoli         |
|---------------|
| Programmatore |
| Game Designer |

_GlyphSeeker_ è un gioco in 3D in prima persona dove il personaggio principale ha 4 tipi diversi di rune, ognuna con la sua abilità di tiro (in particolare: _Elettrica_, _Esplosiva_, _Scudo_ e _Smaterializzatore_). Lei dovrà usare le suddette rune per risolvere puzzle e farsi strada tra tutti i nemici che incontrerà.

&ensp; &ensp; (Questo gioco è stato realizzato con altre persone quando studiavo all'accademia)

**_Sfide_**

- 4 tipi diversi di abilità di tiro (le rune)
    - Io ho lavorato principalmente sulla runa blu, lo Scudo, e mi sono offerto nel lavorare anche su quella viola, lo Smaterializzatore
- Un sistema di salvataggio complesso (è realizzato da sé, con crittografia inclusa), ma non implementato dato il poco tempo a disposizione
    - Il codice lo si può trovare [[qui]](https://github.com/NautilusAcademy/GlyphSeeker/blob/Salvataggio_e_Opzioni/Proj_GlyphSeeker/Assets/Script/-Saves%20%2B%20Options/SaveManager.cs)

* * *

### &ensp; _Altri piccoli progetti in cui ho lavorato_

- _Global Game Jam 2026_
    - Ruolo/i: programmatore, game designer
    - [[Link al gioco]](https://globalgamejam.org/games/2026/identity-seeker-9 "Identity-Seeker")
- _Global Game Jam 2024_
    - Ruolo/i: programmatore
    - [[Link al gioco]](https://globalgamejam.org/games/2024/clowning-around-9 "Clowning Around")
- _Global Game Jam 2023_
    - Ruolo/i: programmatore principale, game designer
    - [[Link al gioco]](https://v3.globalgamejam.org/2023/games/lost-seed-4 "The Lost Seed")

<br>


### Contatti

> E-mail: [franc.degno@gmail.com](mailto:franc.degno@gmail.com "Clicca per mandarmi un'email!")

> [[ Curriculum / CV ]](./assets/pdf/francesco_degno_cv_ita.pdf "Clicca per scaricare il mio Curriculum (CV)") <i style="color: DeepSkyBlue">(intero)</i>

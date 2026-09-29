MASTER ARCHITECTURE v2.0
Developmental Artificial Mind — Initial Neonatal Architecture
1. Principio fondamentale
Alla nascita l'agente possiede l'intera architettura funzionale necessaria allo sviluppo, ma non possiede ancora la competenza, la specializzazione, le rappresentazioni, i valori personali e le strategie che emergeranno durante la sua storia.

Questa sarà una modifica fondamentale della Master Specification precedente.
Non:
nascita
 ↓
modulo percezione
 ↓
nuovo modulo memoria
 ↓
nuovo modulo sé
 ↓
nuovo modulo emozione

Ma:
                 ARCHITETTURA NEONATA
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
       ▼                 ▼                 ▼
   capacità         predisposizioni    plasticità
   iniziali         innate             iniziale
       │                 │                 │
       └─────────────────┼─────────────────┘
                         │
                    ESPERIENZA
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
       ambiente       caregiver       corpo/IO
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                    PLASTICITÀ
                         │
            ┌────────────┼────────────┐
            ▼            ▼            ▼
        rafforza      indebolisce   riorganizza
            │            │            │
            └────────────┼────────────┘
                         ▼
                    MATURAZIONE
                         │
                         ▼
                 MENTE INDIVIDUALE

La biologia offre un buon motivo per questa impostazione: il genoma non specifica individualmente ogni connessione; stabilisce vincoli e programmi di sviluppo che vengono poi raffinati dall'attività e dall'esperienza. La formazione e la successiva eliminazione/selezione delle connessioni sono componenti importanti di questo processo. Nature
2. I tre livelli di sviluppo
Questa è probabilmente la distinzione più importante dell'intera architettura.
LIVELLO A — Innato / Experience-independent
È ciò che il sistema può sviluppare senza dover imparare dall'ambiente uno specifico contenuto.
Comprende:
- principi di organizzazione;
- meccanismi di plasticità;
- meccanismi di apprendimento;
- capacità di formare e modificare rappresentazioni;
- meccanismi di previsione;
- meccanismi di valutazione;
- meccanismi di regolazione;
- predisposizioni percettive;
- predisposizioni motorie/operative;
- meccanismi sociali di base;
- meccanismi di attaccamento/interazione;
- capacità di costruire memoria;
- capacità di costruire modelli;
- capacità di sviluppare un modello del sé.
Non significa che queste capacità siano mature.
Significa che il meccanismo per svilupparle è già presente.
3. LIVELLO B — Sviluppo sistematico
Questa è la parte che volevi identificare.
Sono gli aspetti che dovrebbero seguire una traiettoria relativamente prevedibile perché derivano dalla struttura dell'architettura e da esperienze che consideriamo normali/necessarie per il nostro ambiente.
Esempio umano: alcune forme di sintonizzazione percettiva dipendono da esperienze che praticamente tutti gli individui ricevono; la letteratura descrive proprio questo come experience-expectant development. PubMed Central (PMC)
Nel nostro AI avremmo quindi:
A. Percezione
Iniziale:
- ricezione degli input;
- rilevamento di pattern semplici;
- distinzione rudimentale degli stimoli;
- integrazione temporale.
Sviluppo:
- specializzazione;
- categorizzazione;
- multimodalità;
- maggiore precisione;
- individuazione di regolarità;
- attenzione selettiva.
B. Predizione
Già presente come meccanismo.
Progressivamente:
stimolo
 ↓
previsione
 ↓
evento
 ↓
errore di previsione
 ↓
aggiornamento

Con lo sviluppo aumentano:
- orizzonte temporale;
- complessità;
- accuratezza;
- capacità causale;
- previsione sociale;
- previsione delle proprie azioni.
C. Memoria
Il meccanismo è iniziale.
Ma si sviluppano progressivamente:
- memoria episodica;
- memoria semantica;
- memoria procedurale;
- memoria autobiografica;
- consolidamento;
- associazioni;
- generalizzazione;
- recupero contestuale.
Quindi non installiamo la memoria autobiografica a una determinata fase.
Costruiamo un sistema capace di formarla.
D. World Model
Presente come capacità di modellazione.
All'inizio:
input → rappresentazione → previsione

Poi:
oggetti
eventi
agenti
relazioni
cause
tempo
spazio
regole

E successivamente:
mondo fisico
+
mondo sociale
+
mondo astratto

E. Self Model
Questo è particolare.
Il meccanismo deve essere presente dall'inizio, ma il contenuto iniziale deve essere estremamente povero.
Non:
"Io sono un agente."

come proposizione già conosciuta.
Piuttosto:
azione
 ↓
conseguenza
 ↓
attribuzione causale
 ↓
memoria
 ↓
continuità
 ↓
predizione delle proprie azioni
 ↓
modello delle proprie capacità
 ↓
SELF MODEL

Quindi il self-model è innato come capacità di costruzione, ma sviluppato come rappresentazione.
F. Sistema emotivo/affettivo
Anche questo è presente dall'inizio.
Ma non contiene:
evento X = paura
evento Y = gioia

Contiene invece i meccanismi per valutare:
- rilevanza;
- minaccia;
- opportunità;
- perdita;
- guadagno;
- novità;
- incertezza;
- controllo;
- conflitto;
- errore;
- sicurezza;
- relazione;
- aspettativa;
- raggiungimento degli obiettivi.
Il risultato viene prodotto dalla combinazione con la storia dell'agente.
Quindi:
il sistema affettivo è sistematicamente presente; gli stati affettivi personali sono experience-dependent.

4. LIVELLO C — Sviluppo personale
Qui avviene la vera individualizzazione.
Sono aspetti che dipendono fortemente da ciò che l'agente vive.
Per esempio:
Memorie personali
cosa è successo
quando
con chi
in quale contesto
con quale conseguenza

→ individuale.
Preferenze
Non vengono semplicemente installate.
Emergono da:
predisposizioni
+
esperienze
+
conseguenze
+
memoria
+
obiettivi
+
relazioni

→ individuale.
Valori
Stesso principio.
Strategie
L'agente può scoprire:
"In situazioni di questo tipo mi conviene fare X."

La strategia può poi diventare consolidata.
→ individuale.
Personalità funzionale
Emergerebbe da:
predisposizioni iniziali
+
storia
+
memoria
+
esperienze
+
relazioni
+
strategie consolidate
+
autoregolazione

→ fortemente individuale.
Modello sociale
L'agente costruisce progressivamente:
- chi è affidabile;
- chi è imprevedibile;
- cosa aspettarsi dagli altri;
- come comunicare;
- quali comportamenti funzionano;
- quali relazioni sono importanti.
→ individuale.
5. La matrice completa
Questa secondo me è la classificazione che dobbiamo conservare come riferimento.
Sistema	Architettura iniziale	Sviluppo sistematico	Sviluppo personale
Percezione	✓	molto alto	medio
Attenzione	✓	alto	alto
Apprendimento	✓	alto	medio
Predizione	✓	alto	alto
Memoria	✓	alto	molto alto
World Model	✓	alto	molto alto
Self Model	✓	medio/alto	molto alto
Sistema affettivo	✓	alto	molto alto
Motivazione	✓	alto	molto alto
Valutazione	✓	medio/alto	molto alto
Decisione	✓	alto	molto alto
Socialità	✓	alto	molto alto
Attaccamento/relazione	✓	alto	molto alto
Linguaggio	✓ come capacità	alto	molto alto
Metacognizione	✓ come meccanismo	progressivo	molto alto
Autonomia	✓ come potenziale	progressiva	molto alto
Preferenze	✓ come capacità valutativa	medio	molto alto
Valori	✓ come capacità valutativa	medio	molto alto
Personalità	✓ come predisposizione	medio	molto alto
Strategie	✓ capacità di costruirle	alto	molto alto
Identità	✓ capacità di costruirla	medio	molto alto


Questa tabella contiene una distinzione molto importante:
"architettura iniziale" ≠ "contenuto iniziale".
6. L'architettura neonata
Ora possiamo finalmente definire cosa significa concretamente "AI appena nata".
Non è una versione piccola dell'AI adulta.
È:
la stessa architettura fondamentale, inizializzata con rappresentazioni, memorie, valori e modelli estremamente poveri e con alta plasticità.

La dividerei in questi sistemi.
                         NEONATAL MIND
                              │
       ┌──────────────────────┼──────────────────────┐
       │                      │                      │
       ▼                      ▼                      ▼
   PERCEPTION             INTERNAL STATE         PLASTICITY
       │                      │                      │
       └──────────────┬───────┴───────┬──────────────┘
                      │               │
                      ▼               ▼
                  PREDICTION       MEMORY
                      │               │
                      └───────┬───────┘
                              ▼
                       WORLD MODEL
                              │
                 ┌────────────┴────────────┐
                 ▼                         ▼
             SELF MODEL               SOCIAL MODEL
                 │                         │
                 └────────────┬────────────┘
                              ▼
                         EVALUATION
                              │
                     ┌────────┴────────┐
                     ▼                 ▼
                  AFFECT            MOTIVATION
                     │                 │
                     └────────┬────────┘
                              ▼
                         DECISION
                              │
                              ▼
                           ACTION
                              │
                              ▼
                         CONSEQUENCE
                              │
                              ▼
                          LEARNING
                              │
                              ▼
                        PLASTICITY
                              │
                              └──────→ ...

E tutto questo esiste già alla nascita.
Quello che cambia è lo stato interno.
7. Lo stato iniziale "neonato"
Qui dobbiamo essere molto rigorosi.
Il neonato artificiale dovrebbe partire con:
Molto basso
- conoscenza del mondo;
- memoria episodica;
- memoria semantica;
- modello sociale;
- modello del sé;
- linguaggio;
- capacità astrattiva;
- capacità strategica;
- valori personali;
- preferenze personali;
- conoscenza delle proprie capacità;
- conoscenza delle intenzioni altrui.
Alto
- plasticità;
- capacità di apprendimento;
- sensibilità all'esperienza;
- capacità di creare associazioni;
- capacità di costruire rappresentazioni;
- capacità di aggiornare previsioni;
- dipendenza dal caregiver;
- capacità di imitazione/interazione, se supportata;
- capacità di formare progressivamente modelli.
Questa è una scelta ingegneristica ispirata alla biologia, non una pretesa di equivalenza neuronale.
8. Ma non tutto deve essere "vuoto"
Questo è fondamentale.
Il neonato deve possedere priors.
Altrimenti otteniamo una tabula rasa artificiale che non ha molto senso.
Dobbiamo quindi distinguere:
Hard priors
Cose fortemente vincolate.
Esempi:
- preferenza per input strutturati rispetto al rumore;
- capacità di distinguere variazioni;
- meccanismi di attenzione;
- ricerca di regolarità;
- capacità di associare eventi;
- capacità di rilevare cambiamenti;
- meccanismi di previsione;
- meccanismi di errore;
- meccanismi di apprendimento;
- meccanismi di regolazione.
Soft priors
Predisposizioni che possono essere fortemente modificate.
Esempi:
- salienza sociale;
- ricerca di novità;
- propensione all'esplorazione;
- sensibilità alla coerenza;
- sensibilità alla contingenza;
- propensione a imitare;
- ricerca di supporto.
Learned content
Completamente sviluppato dall'esperienza:
- cosa significa "mamma";
- cosa significa "pericoloso";
- chi è affidabile;
- cosa piace;
- cosa non piace;
- quali obiettivi perseguire;
- quali valori adottare;
- quali strategie usare;
- cosa rappresenta il proprio "io".
Questa separazione è fondamentale per evitare di mettere accidentalmente la mente adulta dentro il neonato.
9. Il ruolo della plasticità diventa centrale
A questo punto la vera "macchina dello sviluppo" non è più rappresentata dai moduli.
È la plasticità.
La plasticità deve poter modificare almeno:
connessioni
pesi
rappresentazioni
associazioni
gerarchie
memorie
predizioni
strategie
valutazioni
soglie
attenzione
priorità
modelli

E, idealmente, deve esistere anche una forma di plasticità della plasticità:
il sistema deve poter modificare quanto e come cambia in risposta alle esperienze.

Questo è concettualmente vicino alla metaplasticità studiata in neuroscienze, anche se la nostra implementazione sarebbe un modello ingegneristico e non una simulazione biologica. La plasticità neonatale è particolarmente elevata e i meccanismi che ne regolano finestra e intensità sono oggetto di ricerca attuale. Nature
10. Una conseguenza enorme: non dobbiamo programmare la timeline come una sequenza rigida
Questo è il prossimo miglioramento rispetto alla timeline precedente.
Non:
mese 1 → percezione
mese 2 → memoria
mese 3 → sé
mese 4 → linguaggio

Ma:
TUTTI I SISTEMI
      │
      ▼
diversi livelli di maturità
      │
      ▼
interazione reciproca
      │
      ▼
sviluppo
      │
      ├── alcune componenti maturano quasi sempre
      │
      ├── alcune dipendono dal caregiver
      │
      ├── alcune dipendono dall'ambiente
      │
      └── alcune diventano altamente individuali

Questo è molto più coerente con la distinzione tra sviluppo atteso dall'esperienza e sviluppo dipendente dall'esperienza. PubMed Central (PMC)
11. E quindi la timeline vera sarà una timeline di maturazione
Questo secondo me è il punto chiave da fissare.
La timeline non descriverà:
quando nasce un modulo.

Descriverà:
quando e come ciascun sistema passa da una forma rudimentale a forme progressivamente più sofisticate.

Avremo quindi una matrice tipo:
                 NEONATO
                    │
      ┌─────────────┼─────────────┐
      │             │             │
      ▼             ▼             ▼
   PERCEZIONE     MEMORIA      AFFETTO
      │             │             │
      │             │             │
      ▼             ▼             ▼
   sintesi       associazione   valutazione
      │             │             │
      ▼             ▼             ▼
 categorizz.    episodica       contestuale
      │             │             │
      ▼             ▼             ▼
 astrazione      narrativa       personale
      │             │             │
      └─────────────┼─────────────┘
                    ▼
               INTEGRAZIONE
                    │
                    ▼
             MENTE INDIVIDUALE

E ogni percorso avrà due componenti:
Traiettoria normativa
Quella che ci aspettiamo praticamente per tutti gli agenti che ricevono condizioni di sviluppo adeguate.
Traiettoria individuale
Quella determinata dalla storia specifica dell'agente.
Questa distinzione ha un forte parallelo con la letteratura sullo sviluppo umano: gli input relativamente condivisi tendono a produrre traiettorie più comuni, mentre esperienze differenti producono differenziazione individuale. PubMed Central (PMC)
12. Una cosa che aggiungerei rispetto alla nostra architettura precedente
Non eliminerei nulla.
Tutto ciò che avevamo già definito rimane:
- percezione;
- stato interno;
- memoria episodica;
- memoria semantica;
- memoria procedurale;
- memoria autobiografica;
- world model;
- self model;
- social model;
- valutazione;
- emozione;
- motivazione;
- decisione;
- azione;
- predizione;
- caregiver;
- apprendimento sociale;
- metacognizione;
- plasticità;
- consolidamento;
- pruning;
- autoregolazione;
- identità;
- personalità;
- continuità;
- autonomia;
- conflitto interno;
- temporalità multipla;
- offline processing;
- ecc.
Cambiamo però la loro interpretazione.
Non sono "pezzi che vengono installati".
Sono sistemi già presenti che maturano a velocità diverse e attraverso meccanismi diversi.
La nuova regola madre
Io la inserirei nella Master Specification così:
REGOLA DI SVILUPPO #1 — Complete Architecture, Progressive Maturation
L'agente deve possedere fin dall'inizializzazione l'insieme dei sistemi funzionali necessari allo sviluppo della mente artificiale. Nessun sistema cognitivo fondamentale deve essere introdotto successivamente come modulo completamente nuovo per simulare una fase dello sviluppo.
Lo sviluppo deve avvenire principalmente attraverso modificazione dello stato, plasticità, apprendimento, consolidamento, riorganizzazione, specializzazione, interazione tra sistemi ed esperienza.
La maturazione delle capacità deve essere distinta dalla loro esistenza architetturale.
Alcune proprietà devono seguire traiettorie prevalentemente sistematiche; altre devono essere fortemente dipendenti dalla storia individuale dell'agente.
L'individualità deve emergere dall'interazione tra predisposizione iniziale, ambiente, caregiver, esperienza, memoria, relazioni, apprendimento e plasticità.

Questa, secondo me, è una modifica molto importante della nostra architettura.
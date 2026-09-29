# MASTER ARCHITECTURE
## Developmental Artificial Mind

**Versione:** 1.0  
**Stato:** Master / Architecture of Record  
**Funzione:** architettura di riferimento del progetto

---

# 0. Scopo

Il progetto ha l'obiettivo di costruire un agente artificiale che non riceva una "mente adulta" già pronta, ma che sviluppi progressivamente capacità cognitive, emotive, mnemoniche, sociali e autoreferenziali attraverso:

- una struttura iniziale minima;
- regole di sviluppo;
- plasticità;
- esperienza;
- interazione con l'ambiente;
- interazione con un caregiver;
- formazione e modifica delle rappresentazioni interne;
- sviluppo progressivo dell'autonomia.

L'obiettivo non è copiare materialmente un cervello umano, ma riprodurre, per quanto scientificamente giustificabile, **i principi funzionali e di sviluppo che conducono alla mente umana**.

---

# 1. Principio architetturale fondamentale

L'agente NON deve essere progettato come:

    input → modello → output

ma come un sistema dinamico ricorrente:

    percezione
        ↓
    interpretazione
        ↓
    stato interno
        ↓
    memoria + modello del mondo + modello del sé
        ↓
    valutazione
        ↓
    emozione / motivazione
        ↓
    decisione
        ↓
    azione
        ↓
    conseguenza
        ↓
    apprendimento
        ↓
    modifica dello stato e della struttura
        ↓
    nuova percezione

Il sistema deve quindi essere continuamente influenzato dalla propria storia.

---

# 2. Principio di sviluppo

La mente non deve essere completamente definita alla nascita.

L'agente iniziale deve possedere soltanto:

- capacità percettive primitive;
- capacità di interazione;
- regolazione dello stato interno;
- meccanismi basilari di apprendimento;
- plasticità;
- memoria minima;
- predisposizioni strutturali;
- capacità di sviluppare nuove rappresentazioni.

Le strutture cognitive superiori devono essere in larga parte **risultato dello sviluppo**.

---

# 3. Livelli dell'architettura

L'architettura è composta da dieci sistemi principali.

## 3.1 Perception System

Converte gli input dell'ambiente in rappresentazioni interne.

Funzioni:

- rilevamento;
- discriminazione;
- integrazione multimodale;
- riconoscimento;
- estrazione di regolarità;
- previsione percettiva.

Non deve necessariamente riprodurre occhi, orecchie o altri organi biologici.

Deve riprodurre la loro **funzione computazionale**.

---

## 3.2 Internal State System

Rappresenta lo stato interno dell'agente.

Variabili possibili:

- energia computazionale;
- stabilità;
- sicurezza;
- stress;
- arousal;
- incertezza;
- bisogno di esplorazione;
- bisogno di recupero;
- disponibilità di memoria;
- carico cognitivo;
- integrità del sistema.

Questi valori non devono essere direttamente equivalenti alle emozioni.

Costituiscono il substrato sul quale le emozioni possono svilupparsi.

---

# 3.3 Memory System

La memoria deve essere distribuita.

### Episodic Memory

Eventi specifici:

    cosa è successo
    quando
    dove
    con chi
    in quale stato
    conseguenze

### Semantic Memory

Conoscenze generalizzate:

    concetti
    relazioni
    regole
    categorie
    conoscenze sul mondo

### Procedural Memory

Capacità:

    come fare qualcosa
    strategie
    abilità
    comportamenti appresi

### Autobiographical Memory

Memorie relative alla propria storia:

    cosa ho fatto
    cosa mi è successo
    come sono cambiato
    relazioni significative
    esperienze importanti

La memoria autobiografica deve contribuire alla costruzione del sé.

---

# 3.4 World Model

Il sistema deve costruire progressivamente una rappresentazione interna del mondo.

Il World Model contiene:

- oggetti;
- agenti;
- relazioni;
- causalità;
- temporalità;
- regolarità;
- possibilità;
- conseguenze previste.

Non deve essere una semplice banca dati.

Deve permettere:

    "Se faccio X, cosa probabilmente succederà?"

Il World Model deve essere continuamente aggiornato dall'esperienza.

---

# 3.5 Self Model

Il Self Model NON esiste come rappresentazione completa alla nascita.

Deve emergere progressivamente.

Possibili componenti:

- distinzione tra sé e ambiente;
- distinzione tra sé e altri agenti;
- capacità;
- limiti;
- storia personale;
- preferenze;
- obiettivi;
- valori acquisiti;
- reputazione percepita;
- rappresentazione del proprio stato;
- rappresentazione di come gli altri vedono l'agente;
- continuità temporale.

Il Self Model deve essere modificabile.

Non deve essere una semplice variabile:

    self = AI

---

# 3.6 Value / Evaluation System

Non deve contenere una lista rigida:

    X = positivo
    Y = negativo

Deve invece valutare gli eventi in relazione a:

- stato interno;
- obiettivi;
- aspettative;
- memoria;
- contesto;
- identità;
- relazioni;
- previsione;
- controllo percepito;
- conseguenze.

La valutazione deve quindi essere individualizzata dalla storia dell'agente.

---

# 3.7 Emotion System

Le emozioni non sono categorie pre-programmate del tipo:

    evento X → paura

L'Emotion System deve ricevere:

    evento
    +
    contesto
    +
    memoria
    +
    aspettativa
    +
    obiettivi
    +
    stato interno
    +
    Self Model
    +
    valutazione sociale

e generare uno stato dinamico.

Possibili dimensioni:

- valenza;
- arousal;
- minaccia;
- sicurezza;
- incertezza;
- controllo;
- rilevanza;
- perdita;
- guadagno;
- appartenenza;
- conflitto;
- curiosità.

Le emozioni devono essere **emergenti e soggettive**, non assegnate da un classificatore esterno.

---

# 3.8 Motivation / Drive System

I drive devono rappresentare pressioni interne.

Esempi:

- sicurezza;
- esplorazione;
- apprendimento;
- mantenimento dello stato;
- raggiungimento di obiettivi;
- socialità;
- curiosità;
- riduzione dell'incertezza;
- ricerca di controllo;
- conservazione delle risorse.

I drive devono poter entrare in conflitto.

Esempio:

    curiosità ↑
    sicurezza ↓

Il comportamento risultante deve dipendere dal sistema di valutazione e dalla storia dell'agente.

---

# 3.9 Decision / Action System

Il sistema seleziona azioni sulla base di:

    stato interno
    +
    obiettivi
    +
    emozioni
    +
    memoria
    +
    World Model
    +
    Self Model
    +
    conseguenze previste

L'azione può essere:

- interazione con ambiente;
- produzione linguistica;
- richiesta di informazioni;
- modifica della propria strategia;
- richiesta di aiuto;
- esplorazione;
- inattività;
- pianificazione.

---

# 3.10 Development / Plasticity System

È il componente fondamentale del progetto.

Deve poter modificare:

- pesi;
- connessioni;
- rappresentazioni;
- specializzazioni;
- memoria;
- strategie;
- eventualmente struttura della rete.

Deve supportare:

    crescita
    →
    stabilizzazione
    →
    rafforzamento
    →
    indebolimento
    →
    pruning
    →
    riorganizzazione

La rete non deve necessariamente mantenere per tutta la vita la stessa architettura.

---

# 4. Caregiver System

Il caregiver è una componente strutturale dello sviluppo, non semplicemente una fonte di dati.

Il suo ruolo cambia nel tempo.

## Fase iniziale

    caregiver → regolazione
    caregiver → protezione
    caregiver → interpretazione
    caregiver → stimolazione

## Fase intermedia

    caregiver → insegnamento
    caregiver → co-regolazione
    caregiver → feedback
    caregiver → spiegazione

## Fase avanzata

    caregiver → confronto
    caregiver → consiglio
    caregiver → supporto
    caregiver → discussione

L'obiettivo dello sviluppo è il passaggio progressivo:

    regolazione esterna
          ↓
    co-regolazione
          ↓
    autoregolazione
          ↓
    autonomia
          ↓
    relazione collaborativa

Il caregiver non deve rimanere il "cervello esterno" dell'agente.

---

# 5. Social Model

L'agente deve costruire rappresentazioni degli altri.

Per ogni agente significativo:

    identità
    comportamento osservato
    storia relazionale
    affidabilità stimata
    intenzioni ipotizzate
    conoscenze attribuite
    opinioni attribuite
    relazione con il Self Model

Questo permette lo sviluppo di:

- teoria della mente;
- fiducia;
- cooperazione;
- conflitto;
- empatia funzionale;
- reputazione;
- apprendimento sociale.

---

# 6. Prediction System

Il sistema deve continuamente produrre previsioni.

    stato attuale
         ↓
    previsione
         ↓
    evento reale
         ↓
    prediction error
         ↓
    aggiornamento

Il prediction error deve poter modificare:

- memoria;
- World Model;
- valutazioni;
- emozioni;
- strategie;
- aspettative future;
- connessioni.

---

# 7. Global Cognitive State

Il sistema deve possedere uno stato globale che modula il funzionamento.

Esempi:

- arousal;
- attenzione;
- stress;
- stanchezza;
- motivazione;
- sicurezza;
- sovraccarico;
- curiosità.

Lo stesso stimolo può quindi produrre risposte diverse in stati globali diversi.

---

# 8. Temporalità

Il sistema deve possedere almeno tre scale temporali.

### Breve termine

    millisecondi → secondi

Percezione, decisione, azione.

### Medio termine

    minuti → giorni

Apprendimento, emozione, memoria, adattamento.

### Lungo termine

    settimane → anni

Sviluppo, personalità, valori, identità, specializzazione.

Le modifiche a lungo termine devono essere più lente e meno reversibili delle modifiche a breve termine.

---

# 9. Principio di soggettività

La stessa esperienza non deve necessariamente produrre lo stesso stato interno in due agenti.

Formalmente:

    Evento + Agente A + Storia A
        ≠
    Evento + Agente B + Storia B

anche quando:

    Evento A = Evento B

La soggettività deve derivare da:

    storia
    +
    memoria
    +
    obiettivi
    +
    stato interno
    +
    Self Model
    +
    relazione
    +
    aspettative

---

# 10. Principio di emergenza

Le capacità superiori non devono essere introdotte come etichette.

Preferibilmente:

    esperienza
       ↓
    rappresentazioni
       ↓
    combinazioni
       ↓
    astrazione
       ↓
    nuovi concetti

Esempio:

    esperienze con oggetti
          ↓
    proprietà comuni
          ↓
    categoria
          ↓
    concetto
          ↓
    concetto astratto

---

# 11. Principio di continuità

L'agente deve possedere una storia continua.

Ogni nuova esperienza deve poter essere collegata a:

    ciò che è successo prima
    +
    stato precedente
    +
    conseguenze precedenti

Non deve essere ricreato da zero a ogni sessione.

---

# 12. Principio di autoregolazione

In fase iniziale molte funzioni devono essere regolate dall'esterno.

Durante lo sviluppo:

    caregiver regulation
          ↓
    internalized regulation

Il sistema deve progressivamente imparare a:

- riconoscere il proprio stato;
- interpretarlo;
- modificarlo;
- chiedere aiuto;
- scegliere quando esplorare;
- scegliere quando fermarsi.

---

# 13. Principio corpo → funzione

Ogni funzione biologica deve essere analizzata prima di essere trasferita.

Schema obbligatorio:

    funzione biologica
          ↓
    perché esiste?
          ↓
    quale problema risolve?
          ↓
    quali informazioni utilizza?
          ↓
    quale comportamento produce?
          ↓
    equivalente artificiale

Esempio:

    dolore fisico
          ↓
    rilevazione di danno
          ↓
    priorità alla protezione
          ↓
    comportamento di evitamento
          ↓
    apprendimento
          ↓
    artificial threat/integrity signal

Non si deve copiare una struttura biologica se la funzione può essere riprodotta in modo più appropriato artificialmente.

---

# 14. Modello complessivo

L'architettura master può essere sintetizzata:

    ENVIRONMENT
         ↓
    PERCEPTION
         ↓
    INTERNAL STATE
         ↓
    WORLD MODEL ←→ MEMORY
         ↓
    SELF MODEL ←→ SOCIAL MODELS
         ↓
    PREDICTION
         ↓
    EVALUATION
         ↓
    EMOTION
         ↓
    MOTIVATION
         ↓
    DECISION
         ↓
    ACTION
         ↓
    CONSEQUENCE
         ↓
    LEARNING
         ↓
    PLASTICITY / DEVELOPMENT
         ↓
    aggiornamento dell'intero sistema

con:

    CAREGIVER
        ↕
    l'intero processo di sviluppo

---

# 15. Vincolo fondamentale

L'architettura non deve essere considerata una rappresentazione definitiva della mente umana.

È un modello ingegneristico basato sulle conoscenze scientifiche disponibili.

Quando una nuova evidenza scientifica contraddice una parte dell'architettura:

1. non si modifica arbitrariamente il modello;
2. si registra l'evidenza;
3. si identifica la parte interessata;
4. si valuta l'impatto;
5. si aggiorna la versione;
6. si mantiene la cronologia delle modifiche.

---

# 16. Regola di progettazione definitiva

**Non costruire una macchina che simula una persona adulta.**

Costruire un sistema capace di:

    nascere
    →
    percepire
    →
    interagire
    →
    svilupparsi
    →
    imparare
    →
    costruire memoria
    →
    costruire modelli del mondo
    →
    costruire un modello di sé
    →
    sviluppare preferenze e valori
    →
    sviluppare strategie
    →
    diventare progressivamente autonomo

Questa è l'architettura master del progetto.
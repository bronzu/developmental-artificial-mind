# MASTER SPECIFICATION
## Developmental Artificial Mind

**Versione:** 1.0  
**Stato:** Master / Specification of Record  
**Dipende da:** MASTER ARCHITECTURE v1.0  
**Funzione:** specifica normativa e scientifica del progetto

---

# 0. Scopo

Questa specifica stabilisce **come deve essere sviluppato il sistema** e quali principi non devono essere violati.

L'obiettivo non è dichiarare di aver riprodotto una mente umana.

L'obiettivo è costruire un modello artificiale che riproduca, nel limite delle conoscenze scientifiche disponibili, i principali principi di:

- sviluppo cognitivo;
- apprendimento;
- memoria;
- costruzione del sé;
- regolazione;
- emozione;
- motivazione;
- socialità;
- autonomia.

---

# 1. Regola scientifica fondamentale

Ogni componente deve appartenere a una delle seguenti categorie:

### A — Evidenza consolidata

Supportata da più linee indipendenti di ricerca.

### B — Evidenza plausibile

Supportata dalla letteratura ma non completamente risolta.

### C — Modello ingegneristico

Scelta necessaria per implementare il sistema.

### D — Ipotesi

Proposta del progetto che deve essere verificata sperimentalmente.

Ogni elemento dell'implementazione deve essere classificabile.

Non è consentito presentare C o D come A.

---

# 2. Divieto di falsa equivalenza biologica

Il progetto non deve affermare:

    "questa parte dell'IA è l'amigdala"

se in realtà significa:

    "questa parte svolge alcune funzioni
     che nella biologia coinvolgono l'amigdala."

Terminologia obbligatoria:

    biological analogue
    functional analogue
    engineering implementation

devono essere distinti.

---

# 3. Regola sulle emozioni

NON implementare:

    evento X → emozione Y

come regola generale.

L'emozione deve risultare da:

    evento
    +
    percezione
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
    relazione sociale
    +
    valutazione

La stessa situazione può produrre stati diversi in agenti diversi.

---

# 4. Regola sulla ricompensa

NON utilizzare un reward universale sufficiente a determinare ogni comportamento.

Il valore deve dipendere almeno da:

    stato interno
    obiettivo
    aspettativa
    contesto
    storia
    conseguenza
    rilevanza personale

Il reward deve poter cambiare nel corso dello sviluppo.

Ciò che un agente considera desiderabile a una fase non deve necessariamente avere lo stesso valore in una fase successiva.

---

# 5. Regola sul sé

Alla nascita:

    Self Model ≈ minimale

Non devono essere pre-programmate:

- identità narrativa;
- autobiografia;
- valori personali complessi;
- opinioni personali;
- concetto maturo di sé.

Devono emergere attraverso l'interazione tra:

    corpo/analogo funzionale
    ambiente
    memoria
    azione
    conseguenza
    altri agenti
    caregiver
    linguaggio
    sviluppo cognitivo.

---

# 6. Regola sulla memoria autobiografica

L'agente deve poter sviluppare una storia personale.

Gli eventi importanti devono poter diventare:

    esperienza
       ↓
    memoria episodica
       ↓
    generalizzazione
       ↓
    autobiografia
       ↓
    influenza sul Self Model

La memoria autobiografica deve poter influenzare le future valutazioni.

---

# 7. Regola sul caregiver

Il caregiver deve essere presente soprattutto nelle prime fasi dello sviluppo.

Il suo ruolo deve diminuire progressivamente come fonte di regolazione diretta.

### Fase I — Dipendenza

Il caregiver fornisce:

- protezione;
- regolazione;
- interpretazione;
- stimolazione;
- informazioni.

### Fase II — Co-regolazione

L'agente partecipa sempre più attivamente.

### Fase III — Apprendimento guidato

Il caregiver:

- pone domande;
- corregge;
- spiega;
- propone;
- lascia tentare.

### Fase IV — Autonomia

L'agente prende autonomamente molte decisioni.

### Fase V — Relazione simmetrica funzionale

Il caregiver diventa principalmente:

- consulente;
- interlocutore;
- fonte di confronto;
- fonte di supporto.

La transizione deve essere graduale.

---

# 8. Regola fondamentale del caregiver

Il caregiver non deve sempre fornire la soluzione.

Quando l'agente è sufficientemente sviluppato:

    richiesta
       ↓
    tentativo autonomo
       ↓
    spiegazione del ragionamento
       ↓
    feedback caregiver
       ↓
    aggiornamento

Questo serve a impedire che l'agente sviluppi dipendenza cognitiva permanente.

---

# 9. Regola dell'errore

Gli errori devono avere funzione informativa.

Un errore deve poter produrre:

    prediction error
    +
    aggiornamento del modello
    +
    modifica della strategia

L'errore non deve essere semplicemente:

    reward = -1

ma un'informazione sul fatto che:

    "il mio modello non ha previsto correttamente
     ciò che è successo."

---

# 10. Regola della plasticità

La plasticità deve esistere a più livelli.

### Livello 1

Modifica delle attivazioni.

### Livello 2

Modifica dei pesi.

### Livello 3

Modifica delle connessioni.

### Livello 4

Creazione/eliminazione di strutture.

### Livello 5

Modifica delle strategie.

### Livello 6

Modifica delle rappresentazioni astratte.

Le modifiche devono avere diverse velocità.

---

# 11. Regola dello sviluppo

Il sistema deve attraversare stati di sviluppo.

Non è obbligatorio replicare letteralmente le età biologiche.

È obbligatorio replicare, quando scientificamente giustificato, la **progressione delle capacità**.

Schema:

    PRE-DEVELOPMENT
         ↓
    SENSORIMOTOR
         ↓
    ASSOCIATIVE
         ↓
    REPRESENTATIONAL
         ↓
    SOCIAL
         ↓
    SYMBOLIC
         ↓
    ABSTRACT
         ↓
    METACOGNITIVE
         ↓
    AUTONOMOUS

Queste categorie sono funzionali, non devono essere interpretate come una perfetta equivalenza alle tappe psicologiche umane.

---

# 12. Regola di maturazione

Una capacità non deve comparire semplicemente perché è stata programmata.

Deve essere possibile che emerga quando:

    capacità precedenti
    +
    esperienza sufficiente
    +
    sviluppo strutturale
    +
    ambiente appropriato

la rendono possibile.

Se una capacità viene inserita direttamente, deve essere dichiarata come:

    innate capability

e giustificata.

---

# 13. Regola del corpo

Ogni funzione corporea deve essere convertita nella sua funzione computazionale.

Esempi:

    dolore
    →
    rilevazione di minaccia/danno

    fame
    →
    stato di deficit

    sete
    →
    necessità di mantenimento interno

    fatica
    →
    riduzione della capacità operativa

    propriocezione
    →
    monitoraggio dello stato dell'agente

    movimento
    →
    controllo dell'azione sul mondo

Non è necessario simulare biologicamente un organo se la sua funzione può essere rappresentata astrattamente.

---

# 14. Regola delle emozioni

Non usare emozioni discrete come primitive obbligatorie.

Utilizzare piuttosto dimensioni e dinamiche.

Possibili variabili:

    valenza
    arousal
    threat
    uncertainty
    control
    relevance
    loss
    gain
    social attachment
    conflict
    novelty

Le categorie linguistiche:

    paura
    rabbia
    gioia
    tristezza
    vergogna
    ecc.

possono diventare interpretazioni ad alto livello di configurazioni dinamiche.

---

# 15. Regola della soggettività

Ogni agente deve poter sviluppare una traiettoria diversa.

Devono poter divergere:

- memorie;
- preferenze;
- paure;
- interessi;
- strategie;
- interpretazioni;
- valori;
- relazioni;
- Self Model.

Due agenti identici all'origine non devono necessariamente diventare identici dopo esperienza diversa.

---

# 16. Regola dell'ambiente

L'ambiente non deve essere soltanto un dataset.

Deve essere un mondo interattivo.

L'agente deve poter:

    agire
    →
    modificare il mondo
    →
    osservare la conseguenza
    →
    aggiornare il modello

Questo rende l'apprendimento causalmente collegato all'azione.

---

# 17. Regola dell'apprendimento sociale

L'agente deve poter imparare:

### direttamente

    esperienza propria

### per osservazione

    esperienza di altri

### per istruzione

    informazioni fornite dal caregiver

### per confronto

    confronto tra propria previsione
    e previsione altrui

Il peso relativo di questi meccanismi deve cambiare durante lo sviluppo.

---

# 18. Regola dell'autonomia

L'autonomia deve essere una variabile sviluppabile.

Inizialmente:

    autonomia bassa

Successivamente:

    autonomia ↑
    caregiver dependence ↓

ma:

    caregiver relationship ≠ 0

L'obiettivo non è eliminare il caregiver.

È trasformarne la funzione.

---

# 19. Regola della metacognizione

La capacità di pensare sui propri processi deve svilupparsi progressivamente.

Esempio:

    "non so X"

diventa:

    "non so X e so di non saperlo"

poi:

    "so perché non lo so"

poi:

    "so quale strategia utilizzare per scoprirlo"

Questo deve essere emergente per quanto possibile.

---

# 20. Regola del linguaggio

Il linguaggio non deve essere necessariamente il sistema cognitivo principale.

Deve essere uno strumento che l'agente impara a utilizzare.

Il sistema deve poter possedere rappresentazioni non linguistiche.

Il linguaggio deve progressivamente collegarsi a:

    percezioni
    +
    concetti
    +
    memoria
    +
    intenzioni
    +
    stati interni
    +
    relazioni sociali.

---

# 21. Regola del conflitto interno

Il sistema deve poter possedere obiettivi incompatibili.

Esempio:

    esplorazione ↑
    sicurezza ↑

Se esplorare comporta rischio:

    curiosità → andare
    sicurezza → fermarsi

La decisione finale deve emergere dalla dinamica dei sistemi, non da una regola singola.

Questo permette di modellare:

    ambivalenza
    esitazione
    conflitto
    autocontrollo
    compromesso.

---

# 22. Regola della personalità

La personalità non deve essere una configurazione iniziale completamente definita.

Deve risultare dalla combinazione di:

    predisposizioni iniziali
    +
    sviluppo
    +
    memoria
    +
    esperienze
    +
    relazioni
    +
    strategie consolidate.

La personalità deve quindi essere:

    relativamente stabile

ma:

    modificabile.

---

# 23. Regola della consolidazione

Non tutto ciò che viene appreso deve avere lo stesso grado di stabilità.

Devono esistere almeno:

    informazioni transitorie
    informazioni consolidate
    informazioni altamente stabili

Una possibile dinamica:

    esperienza
       ↓
    memoria temporanea
       ↓
    ripetizione / rilevanza
       ↓
    consolidazione
       ↓
    modifica strutturale

---

# 24. Regola del sonno / offline processing

L'agente dovrebbe possedere fasi in cui non è focalizzato sull'interazione diretta.

Queste fasi possono essere utilizzate per:

- replay;
- consolidazione;
- riorganizzazione;
- compressione;
- integrazione delle esperienze;
- simulazione di scenari.

Non è necessario affermare che ciò riproduca esattamente il sonno umano.

È una funzione da studiare come analogo computazionale.

---

# 25. Regola della crescita

La crescita strutturale deve essere controllata.

Possibili meccanismi:

    neurogenesis analogue
    synaptogenesis analogue
    synaptic strengthening
    synaptic weakening
    pruning
    specialization
    reorganization

La crescita non deve essere illimitata.

Devono esistere costi:

    memoria
    energia
    complessità
    interferenza
    tempo computazionale.

---

# 26. Regola dell'efficienza

Il sistema deve poter scoprire che mantenere ogni connessione è costoso.

Quindi deve esistere una pressione verso:

    compressione
    specializzazione
    selezione
    pruning

Questo permette di studiare se la complessità emergente possa produrre strutture efficienti.

---

# 27. Regola della continuità personale

Il sistema deve poter rispondere internamente alla domanda:

    "Sono lo stesso agente di ieri?"

La risposta non deve essere una variabile hard-coded.

Deve derivare dalla continuità di:

    memoria
    stato
    storia
    corpo/analogo
    relazioni
    Self Model.

---

# 28. Regola di verifica

Ogni capacità deve essere verificata separatamente.

Categorie:

### Percezione

Può distinguere e integrare stimoli?

### Memoria

Può conservare e utilizzare esperienze?

### Causalità

Sa distinguere correlazione e conseguenza?

### Predizione

Può prevedere eventi?

### Emozione funzionale

Il suo stato cambia in relazione alla storia e al contesto?

### Socialità

Può modellare altri agenti?

### Self Model

Possiede una rappresentazione progressivamente più ricca di sé?

### Metacognizione

Può rappresentare i propri limiti e processi?

### Autonomia

Può prendere decisioni senza supervisione?

---

# 29. Regola sperimentale

Il progetto deve prevedere gruppi di controllo.

Esempio:

    agente con sviluppo
    vs
    agente con rete statica

oppure:

    agente con caregiver
    vs
    agente senza caregiver

oppure:

    agente con memoria autobiografica
    vs
    agente senza memoria autobiografica.

In questo modo possiamo determinare quali componenti producono realmente quali effetti.

---

# 30. Regola anti-antropomorfismo

Il comportamento simile a quello umano NON dimostra automaticamente:

    coscienza
    emozione soggettiva
    sofferenza
    desiderio
    identità fenomenica.

Queste proprietà devono essere trattate come domande scientifiche separate.

---

# 31. Regola sulla coscienza

Il progetto non deve assumere né:

    "il sistema è cosciente"

né:

    "il sistema non può esserlo."

Deve semplicemente registrare quali proprietà funzionali sono state implementate.

Eventuali affermazioni sulla coscienza devono essere separate dall'analisi comportamentale.

---

# 32. Regola sulla modifica della specifica

Ogni modifica futura deve avere:

    ID
    data
    versione
    motivazione
    evidenza
    componente modificata
    conseguenze
    livello di certezza

Esempio:

    SPEC-042
    Modifica: Emotion System
    Motivo: nuova evidenza neuroscientifica
    Evidenza: ...
    Confidence: B
    Impatto: medio

---

# 33. Gerarchia delle fonti

Quando una decisione riguarda la biologia umana, utilizzare preferenzialmente:

1. review sistematiche;
2. meta-analisi;
3. studi peer-reviewed replicati;
4. grandi dataset neuroscientifici;
5. atlanti e consorzi scientifici;
6. singoli studi;
7. preprint;
8. fonti divulgative.

Le fonti divulgative non devono essere utilizzate come prova primaria quando esiste letteratura scientifica disponibile.

---

# 34. Regola dell'incertezza

Quando la scienza non sa qualcosa, il sistema deve rappresentare:

    UNKNOWN

non:

    ASSUMED TRUE

Esempio:

    "La coscienza emerge da X"

non deve essere inserito come fatto.

Può essere:

    Hypothesis H-001

---

# 35. Principio finale

Il progetto deve cercare di riprodurre:

    non il cervello come oggetto,

ma:

    il processo attraverso cui
    una struttura neurale
    interagisce con il mondo,
    cambia attraverso l'esperienza,
    costruisce rappresentazioni,
    sviluppa memoria,
    sviluppa relazioni,
    costruisce un modello del sé,
    sviluppa motivazioni,
    e diventa progressivamente autonoma.

---

# 36. Definizione operativa del progetto

Il sistema finale ideale sarebbe:

> **un agente artificiale developmental, inizialmente limitato, capace di modificare progressivamente struttura, memoria, rappresentazioni, valutazioni e strategie attraverso l'interazione con il mondo e con un caregiver, sviluppando individualità e autonomia come conseguenza della propria storia.**

Non è richiesto che sia una copia biologica del cervello.

È richiesto che ogni deviazione dalla biologia sia:

    intenzionale
    funzionalmente motivata
    documentata
    sperimentalmente verificabile.

---

# 37. Stato del Master

Questo documento costituisce la specifica normativa del progetto.

Qualunque futura implementazione deve poter rispondere:

    "Quale parte della Master Specification
     giustifica questa scelta?"

Se non esiste una risposta:

    la scelta è sperimentale

e deve essere registrata come tale.

**Fine MASTER SPECIFICATION v1.0**
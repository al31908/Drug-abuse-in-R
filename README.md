# Drug-abuse-in-R

# Analisi del National Survey on Drug Use and Health (NSDUH) 2019
Questo progetto utilizza il dataset del National Survey on Drug Use and Health (NSDUH) del 2019 ("https://www.datafiles.samhsa.gov/dataset/national-survey-drug-use-and-health-2019-nsduh-2019-ds0001"), che fornisce dati dettagliati sull'uso di sostanze stupefacenti e non, nella popolazione degli Stati Uniti. Lo scopo dell'analisi è esplorare le relazioni tra vari fattori demografici e comportamentali e l'uso di droghe, visualizzando le distribuzioni e creando 
modelli per comprendere meglio le dinamiche alla base di questi comportamenti.

# Struttura del Progetto

# Dataset Utilizzato
Il dataset contiene informazioni su un ampio campione di individui negli Stati Uniti, includendo variabili come:

Sesso

Razza

Età

Condizione lavorativa

Uso di sostanze stupefacenti (es. alcol, marijuana, cocaina, eroina, ecc.)

Situazione familiare (presenza dei genitori)

# Librerie Utilizzate
Le principali librerie utilizzate nel progetto sono:

**ggplot2**: per la creazione di grafici e visualizzazioni


**dplyr**: per la manipolazione e il filtraggio dei dati

**tidyr** e **magrittr**: per la trasformazione dei dati

**lme4**, **glmmTMB** e **lmerTest**: per la modellazione statistica (modelli misti)

**FactoMineR** e **factoextra**: per l'analisi esplorativa dei dati

**sjPlot**: per la creazione di tabelle descrittive

**haven**: per importare i dati da formati specifici (SAS, SPSS, Stata)

# Obiettivi dell'Analisi
L'analisi si concentra sui seguenti punti chiave:

**Distribuzione delle variabili demografiche**: Analisi delle distribuzioni di sesso, razza, età e condizione lavorativa per comprendere le caratteristiche della popolazione.

**Conteggio delle sostanze stupefacenti**: Creazione di una variabile aggregata che misura il numero di droghe consumate da ogni individuo.

**Analisi sui non consumatori**: Identificazione e analisi delle persone che non hanno mai consumato alcuna sostanza.

**Confronto tra consumatori e non consumatori**: Esplorazione delle differenze tra i gruppi di consumatori e non consumatori in relazione all'età, la situazione familiare e la 
condizione lavorativa.

**Relazione tra condizione lavorativa e uso di droghe**: Analisi specifica del comportamento di consumo di droghe per i giovani con condizione lavorativa "99" (partecipanti sotto i 14 
anni).

**Visualizzazione delle combinazioni di consumo**: Visualizzazioni delle combinazioni di sostanze più comuni (es. alcool e marijuana) in base a diversi fattori (età, condizione 
lavorativa).

# Modellazione Statistica
È stata utilizzata la regressione a effetti misti (GLMM) per analizzare l'associazione tra l'uso di sostanze e fattori demografici, con particolare attenzione all'età e alla situazione 
familiare

L'analisi ha permesso di esplorare le variabili che influenzano significativamente il numero di droghe consumate da ogni individuo, tenendo conto della variabilità tra i gruppi.



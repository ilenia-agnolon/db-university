# 🎓 db-university

## Descrizione

Progetto di modellazione di un database relazionale per rappresentare la struttura e i dati di una **università**.  
Il database gestisce dipartimenti, corsi di laurea, insegnamenti, studenti, docenti e appelli d’esame.

---

## 📋 Consegna

Modellizzare la struttura di un database per memorizzare tutti i dati riguardanti una università:

- sono presenti diversi **Dipartimenti** (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
- ogni **Dipartimento** offre più **Corsi di Laurea** (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc.);
- ogni **Corso di Laurea** prevede diversi **Corsi** (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
- ogni **Corso** può essere tenuto da diversi **Insegnanti**;
- ogni **Corso** prevede più **Appelli d’Esame**;
- ogni **Studente** è iscritto ad un solo **Corso di Laurea**;
- ogni **Studente** può iscriversi a più **Appelli d’Esame**;
- per ogni appello d’esame a cui lo studente ha partecipato, è necessario memorizzare il **voto ottenuto**, anche se non sufficiente.

Pensiamo a quali **entità (tabelle)** creare per il nostro database e cerchiamo poi di stabilirne le **relazioni**.  
Infine, definiamo le **colonne** e i **tipi di dato** di ogni tabella.

---

## 🧩 Schema E-R

Diagramma realizzato con lucidchart(https://www.lucidchart.com/)

![ER Diagram](./schema%20ER/db-university-schema.jpeg)

---

## 🗂 Struttura del progetto

- **DB/**

  - `db_university.sql` → Script SQL completo (creazione e dati)

- **EX\_-_Query/**

  - `EX_-_Query_con_SELECT.txt` → Esercizi con SELECT
  - `EX_-_Query_con_GROUP_BY.txt` → Esercizi con GROUP BY
  - `EX_-_Query_con_JOIN.txt` → Esercizi con JOIN tra tabelle

- **schema ER/**

  - `db-university-schema.jpeg` → Diagramma E-R

- `README.md` → Documentazione del progetto

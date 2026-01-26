<!-- @format -->

# EXOMARE - EXploring Old French through MAnuscript REadings

**EXOMARE** è un progetto di edizione digitale e analisi linguistica dedicato alla seconda prosificazione del _Roman de Troie en prose_ (nota come **Prose 2**).

Il progetto ha ricevuto finanziamenti dal programma di ricerca e innovazione Horizon 2020 dell'Unione Europea nell'ambito dell'accordo di sovvenzione Marie Skłodowska-Curie n. 886478.

## Obiettivi del Progetto

Il progetto si concentra su un anello poco studiato della tradizione troiana medievale: la **Prose 2**, redatta in Italia in lingua francese prima del 1298, e il suo successivo volgarizzamento in fiorentino ad opera di Binduccio dello Scelto (1322).

L'obiettivo è duplice:

1.  **Filologico**: Offrire un'edizione digitale (diplomatica e interpretativa) di testi finora in parte inediti.
2.  **Informatico/Linguistico**: Applicare filtri di analisi linguistica avanzata (lemmatizzazione, POS tagging e MSD) utilizzando standard internazionali come **TEI** (Text Encoding Initiative).

## Il Corpus

Il corpus analizzato comprende quattro testimoni principali:

- **Grenoble** (Manoscritto di Prose 2)
- **Paris** (Manoscritto di Prose 2)
- **Oxford** (Manoscritto di Prose 2)
- **Volgarizzamento di Binduccio dello Scelto**

## Caratteristiche del Sito

Il sito offre diverse modalità di consultazione:

- **Visione Sinottica**: Confronto parallelo dei diversi testimoni manoscritti.
- **Edizioni Diplomatiche e Interpretative**: Visualizzazione dei testi secondo criteri filologici rigorosi.
- **Testi Lemmatizzati**: Consultazione dei testi con annotazioni linguistiche realizzate tramite l'interfaccia **ULA** (_Universal Language Annotation_).
- **Risorse Tecniche**: Manuale di codifica, principi editoriali e bibliografia di riferimento.

## Partner e Istituzioni

Il progetto è il risultato della collaborazione tra diverse istituzioni accademiche:

- **Università della Tuscia**
- **Università degli Studi di Padova**
- **Université Grenoble Alpes (UGA)**
- **Laboratorio ProDigi**

## Struttura del Repository

- `index.html`: Punto di ingresso (reindirizza alla home del progetto).
- `static/`: Contiene il core dell'applicazione.
  - `exomare.html`: Pagina principale del framework.
  - `css/`: Fogli di stile LESS e risorse grafiche (loghi istituzionali).
  - `javascript/`: Logica applicativa e librerie (jQuery, LESS, motori di rendering TEI).
  - `pag/`: Contenuti statici e pagine descrittive del progetto.
  - `html/`: Trascrizioni dei singoli testimoni suddivise per sede (gre, oxf, par).

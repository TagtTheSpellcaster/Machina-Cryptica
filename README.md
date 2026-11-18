# MACHINA CRYPTICA

**Officina degli Enigmi · Machina N° 004**

![Version](https://img.shields.io/badge/version-1.12.2-B8864B?style=flat-square)
![License](https://img.shields.io/badge/license-AGPL--3.0-526B55?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E76F32?style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-6B8799?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F0C674?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-none-526B55?style=flat-square)

**BREVETTO MECCANICO 1.12.2 – 1894**

MACHINA CRYPTICA è un gioco numerico ispirato ai Cryptex meccanici, reinterpretato in chiave steampunk.

Il giocatore deve allineare i tamburi numerici per individuare una combinazione segreta. Ogni tentativo restituisce indizi sulla correttezza delle cifre e sulla loro posizione.

L'interfaccia riproduce l'estetica di uno strumento meccanico ottocentesco, con componenti grafici illustrati, effetti sonori e musica d'atmosfera.

[Puoi giocarci qui](https://tagtthespellcaster.github.io/Machina-Cryptica/)

## Caratteristiche

- Cryptex configurabile con 4, 5 o 6 anelli.
- Dieci cifre disponibili per ciascun anello.
- Combinazioni generate casualmente.
- Possibilità di ripetere le cifre.
- Rotazione degli anelli tramite mouse e trascinamento.
- Supporto ai dispositivi touch.
- Controllo della combinazione e restituzione degli indizi.
- Schermata iniziale con comando di avvio.
- Messaggi casuali di vittoria visualizzati su un cartiglio illustrato.
- Effetti sonori meccanici e musica di sottofondo.
- Interruttori indipendenti per musica ed effetti sonori.
- Interfaccia adattiva alle dimensioni della finestra.

## Come si gioca

1. Avvia la macchina tramite il pulsante **AVVIA LA MACCHINA**.
2. Seleziona il numero di anelli desiderato.
3. Ruota ciascun tamburo fino a impostare la cifra scelta.
4. Premi **TENTA APERTURA** per verificare la combinazione.
5. Leggi gli indizi restituiti dal meccanismo.
6. Continua fino a individuare la sequenza corretta.

Il gioco restituisce due informazioni:

- Cifre corrette nella posizione corretta.
- Cifre presenti nella combinazione ma collocate in una posizione diversa.

Le cifre possono essere ripetute.

## Comandi

| Comando | Funzione |
|---|---|
| Rotellina del mouse | Ruota il tamburo |
| Trascinamento | Ruota il tamburo |
| Touch | Ruota il tamburo |
| Azzera anelli | Riporta tutti gli anelli a zero |
| Tenta apertura | Verifica la combinazione |
| Nuovo codice | Genera una nuova combinazione |

## La vittoria

Quando la combinazione è corretta:

1. Il meccanismo viene sbloccato.
2. I tamburi mostrano la sequenza vincente.
3. Compare il messaggio di apertura.
4. Dopo 2,5 secondi viene visualizzato un cartiglio con un messaggio misterioso scelto casualmente.

Il cartiglio può essere chiuso con:
- Un clic del mouse.
- Il tasto ESC.
- La barra spaziatrice.

Sono disponibili 24 messaggi differenti.

## Asset esterni

Il gioco utilizza immagini e file audio esterni. Tutti gli asset devono trovarsi nella stessa directory di `index.html`.

| File | Descrizione |
|---|---|
| `index.html` | Applicazione principale |
| `left.png` | Estremità sinistra del tamburo |
| `right.png` | Estremità destra del tamburo |
| `00.png` – `09.png` | Grafica delle dieci cifre |
| `cartiglio.png` | Pergamena utilizzata per i messaggi di vittoria |
| `mistery.mp3` | Musica di sottofondo |

Le immagini dei tamburi vengono affiancate direttamente, senza spazi intermedi.

**Importante:** non rinominare gli asset e non spostarli in sottocartelle, a meno di aggiornare i relativi percorsi nel codice.

## Audio e tipografia

La musica di sottofondo è riprodotta in loop. Gli effetti sonori dei tamburi e dei pulsanti sono generati tramite Web Audio API.

L'utente può attivare o disattivare indipendentemente:
- Musica.
- Effetti sonori.

La riproduzione musicale inizia dopo l'interazione esplicita dell'utente, nel rispetto delle restrizioni dei browser sull'autoplay.

Il cartiglio utilizza il carattere **Rye**, caricato da Google Fonts.

## Installazione

Non è richiesta alcuna installazione di dipendenze o compilazione.

1. Scarica il repository.
2. Estrai tutti i file mantenendo la struttura prevista.
3. Apri `index.html` con un browser moderno.

È possibile pubblicare il gioco anche tramite GitHub Pages.

Per utilizzare correttamente la musica e le risorse grafiche, tutti gli asset devono essere presenti nella directory del progetto.

È necessaria una connessione Internet per caricare il carattere Rye da Google Fonts.

## Tecnologie

- HTML5
- CSS3
- JavaScript
- Web Audio API
- Google Fonts

Nessun framework JavaScript e nessuna dipendenza esterna lato applicazione.

## Crediti musicali

Musica di sottofondo:

**Music by [Johan Benitez](https://pixabay.com/users/johan_benitez99co-47699230/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=279249) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=279249).**

## Licenza

MACHINA CRYPTICA è distribuito sotto licenza **GNU Affero General Public License v3.0 (AGPL-3.0)**.

È possibile utilizzare, studiare, modificare e ridistribuire il software nel rispetto delle condizioni previste dalla licenza.

Il testo completo della licenza è disponibile su:

https://www.gnu.org/licenses/agpl-3.0.html

---

**OFFICINA DEGLI ENIGMI**

*MACHINA CRYPTICA · Machina N° 004*

**BREVETTO MECCANICO 1.12.2 – 1894**

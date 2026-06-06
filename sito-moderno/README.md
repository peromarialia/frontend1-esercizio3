# Avengers-Wiki-20260606

## Dettagli Progetto

*   **Nome:** Avengers-Wiki-20260606
*   **Data:** 06/06/2026
*   **Autore:** Marialia Pero
*   **Versione:** v3.0.0

---

## Tecnologie Usate

*   FIGMA
*   HTML5
*   TAILWIND CSS
*   JAVASCRIPT

---

## Analisi Critica

### layout e Gerarchia Visiva
*   **Problema:** Nelle prime versioni, il layout del sito risultava eccessivamente vincolato a una larghezza massima fissa (max-width limitata). Questo creava un effetto di "vuoto" e di eccessiva staticità sugli schermi desktop di grandi dimensioni, compromettendo la fluidità dell'esperienza utente.
*   **Soluzione:** È stato rimosso il blocco rigido della larghezza rendendo la struttura completamente "screen adaptive". Ora gli elementi, i poster dei film e le griglie delle Fasi si espandono e respirano sfruttando l'intera ampiezza orizzontale su qualsiasi display.

### Cambio totale di Palette (Viola Chiaro)
*   **Problema:** La palette iniziale utilizzava una combinazione di toni azzurri generici. Inoltre, il passaggio del mouse sopra i riquadri delle Fasi provocava uno schiarimento dello sfondo che risultava visivamente troppo carico e poco elegante.
*   **Soluzione:** È stata impostata una nuova palette basata sul viola chiaro per tutte le transizioni dinamiche dei bordi e delle ombreggiature dei poster. È stato rimosso lo schiarimento dello sfondo sui box delle Fasi, mantenendo il loro colore scuro originale per alleggerire l'affaticamento della vista.

### Elementi di Navigazione (Header e Barra di Ricerca)
*   **Problema:** La barra di ricerca originale occupava una porzione di spazio troppo invasiva all'interno dell'header, compromettendo la pulizia visiva dell'intestazione e creando problemi di disallineamento sui dispositivi mobili.
*   **Soluzione:** La barra è stata riprogettata per presentarsi come un piccolo bottone circolare, con l'icona della lente perfettamente centrata al millimetro. Solo in fase di focus (quando viene cliccata) si espande fluidamente in larghezza per permettere l'inserimento del testo, integrandosi elegantemente con il menu sottostante.

### Integrazione a Tema (Spider-Man)
*   **Problema:** Il banner inferiore dedicato a Spider-Man presentava una scritta piatta e priva di un carattere visivo che richiamasse l'atmosfera dei film o dei fumetti.
*   **Soluzione:** È stato adottato il font "Bangers" (stile fumettistico classico), applicando un'inclinazione di pochi gradi alla scritta e un'ombra nera profonda tridimensionale (drop-shadow). Al passaggio del mouse, il testo si ingrandisce ed espande le lettere in larghezza per un impatto altamente cinematografico.

---

## Dettagli Tecnici con Tailwind

*   Utilizzo di griglie responsive flessibili per l'adattamento delle Fasi cinematografiche.
*   Uso combinato di Flexbox per ottenere la centratura geometrica assoluta della lente d'ingrandimento all'interno del bottone di ricerca chiuso.
*   Utilizzo della proprietà `overflow-hidden` accoppiata ad `aspect-[2/3]` per mantenere le proporzioni e i tagli dei poster sempre identici e ordinati.
*   Gestione delle animazioni dinamiche tramite le classi `transition-all duration-500` e `ease-in-out` applicate alla barra di ricerca e ai poster dei film.

---

## Report Lavoro

*   **06/06/2026 ore 15:00** = Analisi del layout originale ed eliminazione degli hover di schiarimento dello sfondo dai box delle Fasi.
*   **06/06/2026 ore 15:45** = Configurazione della nuova palette cromatica basata sul viola chiaro per i bordi e gli hover dei poster.
*   **06/06/2026 ore 16:30** = Riprogettazione strutturale della barra di ricerca, convertita in un compatto bottone circolare salvaspazio.
*   **06/06/2026 ore 17:15** = Risoluzione del disallineamento dell'icona all'interno della barra tramite l'uso di Flexbox per una centratura millimetrica.
*   **06/06/2026 ore 18:00** = Importazione del font "Bangers" e personalizzazione grafica tridimensionale del testo nel banner di Spider-Man.
*   **06/06/2026 ore 18:45** = Ottimizzazione "screen adaptive" dell'intero contenitore principale per la corretta visualizzazione sui monitor desktop più grandi.
*   **06/06/2026 ore 19:30** = Rimozione degli effetti hover di schiarimento sui singoli titoli dei film, pulizia del codice e test finale di responsive.


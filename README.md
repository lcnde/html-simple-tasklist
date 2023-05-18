# Readme
This task list was made as an exercise for a developer working at the company. This repository contains my solution to the exercise.

# Media queries
Le media query non sono mobile first. Esempio di query mobile first:
```html
<div class="hi">hi</div>
```
```css
.hi {
  color: green;
}
@media only screen and (min-width: 1200px) {
  /* Styles applied when the width exceeds 600px */
  .hi {
    color: red;
  }
}
```

In sostanza mobile first significa disporre gli elementi e il loro stile prima per mobile, poi aggiungere le alterazioni con le media query che apportano modifiche per desktop (quindi senza media queries il design sarebbe esclusivamente per mobile). 

Mobile-first e' importante da imparare siccome e' la stessa convenzione adottata da TailwindCSS che usiamo sul sito.

# CSS
* Alcune classi come `.name-inputs`, `.description-input` non puntano a niente.
* Era preferibile non usare Bootstrap. L'obiettivo dell'esercizio era anche capire il livello di conoscenza delle tecnologie HTML CSS e Javascript. 

# Altre note
* Per il codice di YouTestPlus e' necessario utilizzare l'indetazione di 2 spazi siccome tutta la codebase utilizza quella. L'indentazione di 4 spazi non ha niente di male siccome e' questione di preferenza, ma per mantenerla costante su Youtest va utilizzata a 2 spazi.
* Non ci sono commenti del codice. E' molto importante commentare il codice e occasionalmente scrivere documentazione per le parti piu' complicate. I commenti sono utili non solo alle altre persone che lavorano al progetto, ma anche a chi ha scritto il codice quando lo revisiona a distanza di tempo.

# Note positive
* Il codice di javascript e' molto pulito e chiaro. Le variabili hanno nomi descrittivi e si capisce la loro funzione.

# Consigli
* Per scrivere CSS e' piu' comodo utilizzare SCSS, per via del nesting che e' possibile fare. In questo modo diminuisce il rischio di assegnare stili alla classe sbagliata.
* Quando si segue un design bisogna fare molta attenzione ai dettagli. 


Lo stile che ho seguito per risolvere l'esercizio non e' identico al design dato, ho cambiato i bordi degli input field, era una scelta di design migliore usare bordi solidi al posto di usare bordi sfumati. Il pulsante Aggiungi ha un padding verticale maggiore, sempre per questione di design.
# Midnight Rush – verifica web

## Come aprire la pagina
Estrai tutti i file nella stessa cartella (`verifica-web`), aprila in VS Code e apri `index.html` nel browser. Non serve JavaScript.

## Tre modifiche effettuate
1. **HTML:** nuovo titolo "Midnight Rush" (scheda del browser, `<h1>` e footer), nuovo slogan e quarta voce nell'elenco ("Sfide a tempo ogni settimana"). Il link "Scopri la gara" porta ancora alla sezione `#dettagli`.
2. **CSS base:** sfondo scuro, colori presi dagli SVG (ciano, viola, giallo), schede con bordo e angoli arrotondati, etichetta a pillola, "Demo gratuita" evidenziata, immagini con `max-width: 100%` e `height: auto`.
3. **Bonus CSS:**
   - *Cura grafica:* ombre leggere su schede, copertina e pulsante; bagliore sul titolo. Il testo chiaro su fondo scuro mantiene un buon contrasto.
   - *Interazione:* il pulsante cambia colore e si alza in `:hover`; con la tastiera (Tab) mostra un contorno giallo con `:focus-visible`.
   - *Schermi piccoli:* `@media (max-width: 600px)` riduce titolo, margini e dimensione dell'auto. Rispettata anche `prefers-reduced-motion`.

## Prova eseguita
**Da completare dopo la tua prova nel browser.** Controlli da fare: pagina a zoom 100%, finestra ridotta fino a circa 360 px (testo leggibile, immagini proporzionate, nessuno scorrimento orizzontale), tasto Tab sul pulsante e click che porta alla prima scheda. Scrivi qui cosa hai visto.

## Problema rimasto
Non avevo l'immagine del modello da confrontare: colori, caratteri e spaziature sono scelti a occhio e vanno ritoccati confrontandoli con il modello della consegna.

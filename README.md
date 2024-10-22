Boolando
===
## Esercizio
Ci ispiriamo al sito di Zalando per riprodurre il layout nello screenshot.
Per ogni prodotto sono fornite 2 immagini: la prima sarà visualizzata all’apertura della pagina, la seconda sarà visualizzata al posto della prima, quando il cursore del mouse va in hover sulla card.
Sono presenti anche un header in posizione fixed e un footer.
## Mio approccio
Per cominciare l'header della pagina sembra piuttosto semplice, avrò un container flex che mi permetterà di gestire facilmente la posizione del menù a sinistra, del logo al centro e le icone a destra.

Mi concentrerò prima però sul corpo della pagina, tutte le card le inserirò in un unico contenitore centrato, una volta aggiustate le dimensioni di ciascuna card mi occuperò di metterle nell'ordine più corretto aiutandomi con un altro container flex. Ogni card avrà due immagini, di cui una nascosta che appare all'hover, tramite l'uso di position per sovrapporle e la proprietà z-index per scegliere quale appare, a quel punto all'hover del mouse penso di cambiare il valore della proprietà z-index in modo che appaia la seconda immagine.
Position tornerà poi utile per posizionare le due etichette e il riquadro del cuore.
infine ciascuna card avrà un altro riquadro con la descrizione e il prezzo.

Infine ci sarà un footer con a sinistra un div che conterrà del testo e a destra un menù con i link ai social.

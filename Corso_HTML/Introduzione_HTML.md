# Hyper text markup language

[Sito ufficiale HTML](https://html.spec.whatwg.org/ "Sito Ufficiale")

### Breve storia di HTML
La sua storia inizia negli anni ‘80, quando il fisico inglese Tim Berners-Lee, presso il CERN (Organizzazione Europea per la Ricerca Nucleare), sviluppò un sistema di gestione delle informazioni basato su ipertesti e collegamenti. Nel 1991, venne pubblicata la prima versione dell’HTML con un set limitato di elementi e attributi.

Nel corso degli anni ‘90, l’HTML ha subito diverse revisioni e aggiornamenti, portando alla popolarità della versione HTML 4.01. Successivamente, nel 2014, è stata rilasciata l’ultima versione ufficiale, l’HTML5, che ha introdotto nuovi elementi, attributi e funzionalità per supportare lo sviluppo web moderno, compresi elementi per video, audio, grafica vettoriale e interazioni avanzate.

HTML ha svolto un ruolo cruciale nella crescita e nell’evoluzione del World Wide Web, rendendo possibile la creazione di pagine web interattive e accessibili a milioni di persone in tutto il mondo.

### Introduzione
HTML è il linguaggio di markup standard che descrive la struttura di una pagina web. Consiste in una serie di elementi che indicano al browser come visualizzare il loro contenuto grazie ad etichette che dicono al browser:
* questo è un titolo 
* questo è un paragrafo 
* questo è un collegamento

Lo scopo di un browser web (Chrome, Edge, Firefox, Safari) è quello di leggere i documenti HTML e visualizzarli correttamente.

##### Esempio di HTML
```
<!DOCTYPE html>
<html>
  <head>
    <title>Titolo della Pagina</title>
  </head>
  <body>
    <h1>Il mio primo titolo</h1>
    <p>Il mio primo paragrafo.</p>
  </body>
</html>
```

* La dichiarazione \<!DOCTYPE html> definisce che questo documento è un documento HTML
* L’elemento \<html></html> è l’elemento radice di una pagina HTML, tutto quello che è racchiuso al suo interno è HTML.
* L’elemento \<head> contiene informazioni meta sulla pagina HTML
* L’elemento \<title> specifica un titolo per la pagina HTML (che viene mostrato nella barra del titolo del browser o nella scheda della pagina)
* L’elemento \<body> definisce il corpo del documento ed è un contenitore per tutto il contenuto visibile, come titoli, paragrafi, immagini, collegamenti ipertestuali, tabelle, elenchi, ecc.
* L’elemento \<h1> definisce un titolo grande
* L’elemento \<p> definisce un paragrafo

### Elemento HTML
E' definito da un tag di apertura, del contenuto e un tag di chiusura e comprende tutto quello che è all'interno dei tag.

`<nomeTag>Il contenuto va qui...</nomeTag>`

L'elemento è annidato quando contiene più tag al suo interno.

L'elemento è vuoto se non ha un tag di chiusura. Questo perchè l'elemento non è in funzione al suo contenuto. Può essere un immagine, un link.....

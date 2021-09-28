---
title: "Dettagli C++ Day 2016"
layout: splash
permalink: /cppday16-talks
---

### C++17 per tutti i giorni

Relatore: **Marco Arena**

Siamo arrivati quasi al completamento del prossimo standard, nominato C++17. Ad ogni meeting del comitato, l’ecosistema si spacca a metà: chi gioisce perché la sua feature preferita è stata approvata e chi invece si lamenta perché i concepts sono stati rimandati ancora! Il dibattito è costantemente acceso e si sentono spesso opinioni polemiche del tipo “il C++17 è uno standard che fa contenti solo i library developers”, oppure “sono state approvate features di cosmetica e poco più” . Insomma, siamo lontani dal percepire quell’entusiasmo che nel 2011 ha fatto avvicinare tantissimi sviluppatori al nostro linguaggio preferito.  
Io invece non riesco a lamentarmi e penso che proprio come il C++11 rivoluzionò le basi del linguaggio, il C++17 ci propone nuovi margini di miglioramento e semplificazione nascosti in dettagli apparentemente cosmetici. Vi presenterò la mia personalissima selezione di features C++17 per il lavoro di tutti i giorni. Che siate novizi o esperti programmatori C++, vi accorgerete che il nuovo standard non è altro che un insieme di scelte pragmatiche finalizzate a semplificare e rendere sempre più produttivo il nostro C++ quotidiano.

Materiale:

- [Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2016/10/C17-per-tutti-i-giorni.pdf)
- [Video](https://www.youtube.com/watch?v=sRdAvQkFjXY)


### C++ e Kafka: streaming ad alte prestazioni

Relatore: **Gian Lorenzo Meocci**

Nel mondo dei BigData si stanno imponendo in questi ultimi anni due potenti framework per l’analisi dei dati: [Impala](https://github.com/cloudera/Impala) (scritto in C++ e utilizzato come engine SQL) e [Spark](https://spark.apache.org/) (scritto in Scala e utilizzato come aggregation layer). Quello che tuttavia non risulta sempre chiaro è come far fluire i dati dal nostro sistema ad una soluzione BigData.  
Questo talk vuole presentare [Kafka](https://kafka.apache.org/), un potente tool di streaming, e la sua interazione con il C++ cercando di dimostrare con esempi concreti come sia possibile “trasportare” i nostri dati in modo efficiente e veloce verso piattaforme avanzate di BigData.

Materiale:

- [Slides](http://www.meocci.it/C++Day16_Streaming.pdf)
- [Video](https://www.youtube.com/watch?v=4S94Nap9K_M)


### Lo stack grafico di Qt  

Relatore: **Luca Ottaviano**

Vi siete mai chiesti come fa un framework grafico a disegnare su schermo? Avete mai pensato a cosa succede quando fate una stampa? In questo talk presenterò come è organizzato lo stack grafico di Qt.  
Partirò dalla base, ossia di come si richiede una finestra al sistema operativo, poi saliremo di livello e vedremo la differenza tra il rendering di Qt Quick e il rendering dei widgets, infine vedremo come lo stesso stack può essere usato in altri modi, come ad esempio per fare screenshot o stampare.

Materiale:

- [Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2016/11/Lo-stack-grafico-di-Qt-Luca-Ottaviano.pdf)
- [Video](https://www.youtube.com/watch?v=UWBwO_-afBY)

### Data Oriented Design: alte performance in C++  

Relatore: **Daniele Maccioni**

Nei computer moderni l’accesso alla RAM e’ diventato uno dei colli di bottiglia del sistema. L’approccio “data oriented” si propone di scrivere codice di alta qualita’ e al tempo stesso alte performance, utilizzando al meglio l’uso della cache del processore. Proviamo insieme a dare uno sguardo alla filosofia “data oriented” e ai suoi possibili vantaggi in termini di performance.

Materiale:

- [Video](https://www.youtube.com/watch?v=SwUF1UaWbYs)


### Introduzione a Modern C++

Relatore: **Raffaele Rialdi**

Il progetto Modern C++ è nato dall’idea di Kenny Kerr con lo scopo di usare la sintassi standard di C++ per sviluppare applicazioni e componenti del Windows Runtime.

Inizialmente Microsoft creò C++/CX, un dialetto analogo a C++/CLI usato per l’interoperabilità .NET, credendo di non riuscire a nascondere la complessità dell’infrastruttura in una semplice libreria.

Modern C++ controverte questo pensiero e dimostra che è possibile usare lo standard C++; conseguentemente Microsoft assume Kenny che evolve il progetto all’interno della divisione Windows.

Durante la sessione vedremo come funziona Windows Runtime, guarderemo rapidamente la libreria di più basso livello WRL confrontandola con C++/CX e con Modern C++.

I punti salienti della sessione saranno la vitale questione del contratto binario, i meccanismi dietro al Windows Runtime e la preziosa Developer eXperience che ogni autore di libreria dovrebbe sempre avere a cuore.

Materiale:

- [Slides](http://www.slideshare.net/RaffaeleRialdi/project-modern-c-ita)
- [Video](https://www.youtube.com/watch?v=rTJUPsYuj1M)

### Le API e il miele. Come disegnare una libreria senza rimanere invischiati

Relatore: **Marco Foco**

Scrivere librerie è semplice, basta raccogliere una manciata di funzionalità ed esporle. Scrivere delle API che funzionino in quante più situazioni, che non creino problemi agli utenti, e che possano interagire con diversi linguaggi è molto più complicato. In questo intervento verranno proposte alcune soluzioni e spunti di riflessione a riguardo.

Materiale:

- [Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2016/12/Marco-Foco-Le-API-e-il-miele.pdf)
- [Video](https://www.youtube.com/watch?v=Gne_cQf4TBU)

### C++ Unconference  

Durante il corso dell’evento sarà possibile proporre degli argomenti da discutere tutti insieme al termine della giornata.

Come funziona:

- durante il corso dell’evento sarà disponibile una lavagna con dei post-it dove chiunque potrà appuntare l’argomento di cui vorrebbe parlare per circa 10/15′;
- in qualsiasi momento chiunque potrà andare alla lavagna e votare gli argomenti proposti;
- i 3/4 argomenti più votati saranno selezionati per essere discussi dal partecipante che li ha proposti;
- la discussione può chiaramente essere totalmente interattiva, tra chi propone l’argomento e il resto del pubblico.


### Ask Us Everything  

*Tutti gli speakers*

Questo slot finale è dedicato all’interazione aperta tra speakers e platea nel nostro classico formato “Fateci tutte le domande che volete”!


### C++ Coding Dojo  

Moderatori: **Marco Arena** e **Stefano Saraulli**

Un Coding Dojo **completamente interattivo**, dedicato alla risoluzione di programming puzzles con algoritmi e containers C++. Sotto la moderazione di Marco e Stefano, i partecipanti cercano le soluzioni ai problemi proposti, mentre un volontario scrive il codice e ogni 15′ si cambia con un altro.

L’obiettivo della sessione è quello di arrivare a scrivere soluzioni compatte ed eleganti che utilizzino in modo efficace algoritmi e containers offerti dallo standard. Se non siete mai andati oltre l’uso di std::accumulate e siete curiosi, questa è la sessione che fa per voi!

Materiale:

- [Esercizi](https://github.com/italiancpp/cppday16/)


### Introduzione al C++ Template Metaprogramming

*Workshop*

Relatore: **Eugenio Bargiacchi**

Se siete sempre stati spaventati dai templates, e non vi siete mai spinti più in là che nell’uso di std::vector, questo workshop potrebbe fare al caso vostro. Mostreremo le basi del funzionamento del template metaprogramming, che differenze ci sono tra codice “normale” e codice “meta”, e alcuni possibili utilizzi di queste tecniche per produrre flussi logici che dipendono da determinate proprietà di tipi, piuttosto che di valori.


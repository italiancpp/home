---
title: "Dettagli Meetup Pordenone 2015"
layout: splash
---

### Keynote: Perché nel 2015 parliamo ancora di C++?

Relatore: **Marco Arena**

Numerosi sistemi che utilizziamo ogni giorno sono scritti completamente o parzialmente in C++. Per esempio, se stai leggendo queste righe con Chrome o Mozilla forse saprai già che questi lo sono. Nonostante la diffusione di tanti eccellenti linguaggi, perché il C++ è ancora così utilizzato? Cosa offre in più o in meno rispetto ad altre tecnologie? Vi presenterò la mia visione, composta da alcuni “segreti” che rendono il C++ speciale ed evoluto.

[Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2015/02/Perch%C3%A9-nel-2015-parliamo-ancora-di-Cpp.pdf)

### C++11 & C++14 Overview

Relatore: **Gian Lorenzo Meocci**

Dal 1998 fino al tardo 2011 il C++ è rimasto sostanzialmente invariato. In questo talk rivredremo assieme le innumerevoli “aggiunte” apportate al linguaggio cercando di capirne gli effeti sullo stile di programmazione quotidiano. Type Inference, Lambdas, Thread, STL e tutte le altre features rendono il C++ un linguaggio rinnovato e questo ci offre la possibilità di affrontare con strumenti nuovi e con occhi nuovi le sfide di tutti i giorni. Sta al singolo programmatore cercare di abbandonare le vecchie abitudini e con questo talk partiremo da qui.

[Slides](http://www.meocci.it/meetup/2015/pordenone/C++_11_14_Overview.pdf)



### C++ from ’90 to ’14

Relatore: **Gianluca Padovani & Marco Foco**

In questa sessione vogliamo raccontare le potenzialità del nuovo C++, mostrando esempi tratti da una code base pubblica. Il talk è ispirato all’omonimo workshop – ben più lungo – (facilitato per la prima volta all’AgileDay 2014) che stiamo sviluppando da alcuni mesi. Gli argomenti presentati andranno dal miglioramento della produttività, alla gestione delle risorse, affrontando poi le lambdas e la loro interazione con la libreria standard. Argomenti fondamentali del C++ di nuova generazione.

[Slides](https://docs.google.com/presentation/d/1hoevSYgpyFXg2ZO-HksPC3ZheZBfQlctYjMEP30yRkE/edit?usp=sharing)


### Introduzione al framework Qt

Relatore: **Luca Ottaviano**

Qt è un vasto framework per lo sviluppo di applicazioni cross-platform in C++. I concetti chiave che Qt aggiunge al C++ standard sin dalla sua prima versione sono l’introspezione a runtime, grazie al Meta object compiler, il meccanismo di signal/slot per implementare il pattern observer nascondendo il boilerplate associato, un meccanismo semplificato per la gestione della memoria dinamica, basato su relazioni padre/figlio, e una vasta libreria di widget per la creazione di interfacce grafiche. In questo intervento vedremo in dettaglio queste caratteristiche e faremo una veloce panoramica su tutte le altre funzionalità offerte dal framework.

[Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org//wp-content/uploads/2015/02/Luca-Ottaviano-Intro-Qt.pdf)

### L’accesso ai dati nell’epoca moderna. Sql++11 e ODB

Relatore: **Nicola Gigante**

Sia il C++ che SQL sono dei linguaggi fortemente tipati, eppure le classiche interfacce tra i due perdono qualsiasi tipo di type-safety fornendo una API basata su stringhe. Ciò comporta problemi di sicurezza (es. SQL injection) e di manutenibilità (eventuali errori vengono alla luce solo a runtime, durante il debug o peggio, in produzione). Grazie al typesystem molto espressivo disponibile in C++, e alle nuove caratteristiche del C++ moderno, è possibile fare molto meglio. Nel mio intervento introdurrò due librerie per l’accesso a database relazionali che sfruttanoquesti concetti. La prima, SQL++11, è una API per l’accesso a database SQL che fornisce una API completamente controllata a compile-time, e rappresenta il bleeding-edge di quello che si può ottenere in C++11. La seconda, ODB, è una soluzione di ORM type-safe matura e rodata, che offre un’assoluta semplicità di utilizzo.

[Slides](http://cpp.ud.it/data/2015-02-07/sqlpp11_odb.pdf) 

### L’Unreal Engine 4

Relatore: **Matteo Bertello**

In questo talk presenterò brevemente l’Unreal Engine 4 come tool e la storia che lo accompagna. Poi passerò a presentare alcune delle features più importanti che ci hanno convinto a fare il passaggio da tool offline più noti come Cinema4D e 3DS Max, a una soluzione real time. Tra queste la più interessante è sicuramente il sistema di scripting visuale Blueprint, e la sua dualità con il C++. In particolare come riesce a mantenere le performance e le caratteristiche di una applicazione C++ (es. type safety) fornendo caratteristiche tipiche dei linguaggi dinamici (es. ricompilazione dinamica del codice) utili alla prototipazione rapida e al debugging.


### **Chromium as a Framework**

Relatore: **Raffaele Intorcia & Tiziano Cappellari**

Chromium è un browser opensource da cui è creato il browser Chrome. E’ un browser multipiattaforma, sviluppato per sistemi Linux, OS X, Windows e Android. Chromium però può essere utilizzato anche come framework per lo sviluppo della propria applicazione Desktop. In questo talk approfondiremo questo aspetto, così da unire i vantaggi delle applicazioni Web, ai vantaggi derivanti dalle applicazione Desktop. Analizzeremo nel dettaglio le ripercussioni di questo approccio. Faremo inoltre una panoramica del progetto Chromium e andremo a scoprire come iniziare ad utilizzarlo per i propri scopi.

[Slides](https://italiancpp.github.io/wp-statico/www.italiancpp.org/wp-content/uploads/2015/02/Intorcia-Cappellari-Chromium-as-a-framework.pptx)

### C++ in Windows Phone Apps

Relatore: **Mirco Vanini**

In questa sessione vedremo una panoramica degli strumenti messi a disposizione per lo sviluppo nativo su Windows Phone 8. Verrà posta particolare attenzione al suo utilizzo per lo sviluppo di applicazioni ibride (C#/C++) che hanno la necessità di riutilizzare algoritmi sviluppati su piattaforme desktop.

[Slides](https://mircovanini.blogspot.it/2015/02/pordenone-italianc-meetup-slide-demo.html)


### C++ nello sviluppo iOS/Android

Relatore: **Giuseppe Merlino & Lucio Cosmo**

Nello sviluppo di applicazioni mobile complesse, l’utilizzo di librerie condivise in C++ può esser una scelta importante per  agevolare il porting delle applicazioni tra le diverse piattaforme. Creare le proprie librerie in C++ permette una notevole condivisione di codice ed una diminuzione dei tempi di debug. Da questo approccio, ad esempio,  traggono particolare beneficio le applicazione che necessitano di complicate elaborazioni real time o che implementano sistemi di comunicazione client server particolarmente delicati. Nel corso dell’intervento vedremo quali siano i casi migliori per utilizzare questo approccio e come utilizzare codice C++ in iOS ed  Android.

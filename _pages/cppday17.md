---
title: "Dettagli C++ Day 2017"
layout: splash
permalink: /cppday17-talks
---

[Slides repository](https://github.com/italiancpp/cppday17)

#### Immediate Mode Graphical User Interfaces in C++

Speaker: **Stefano Cristiano**

Most graphical user interface paradigms are based on the retained mode pattern.  
This means building an object graph describing the user interface, listening to events in callbacks and modifying the object graph.  
Very often a lot of code and conversion between basic types like strings and vectors are needed to keep the GUI in sync with application data model.  
The browser Document Object Model (DOM) is one of the most developed forms of retained mode system.  
In recent years a new paradigm commonly referred as “immediate mode” changes perspective on how to create a graphical user interface.  
It’s not entirely new, as it has been used in the field of game programming since long time, but only in the last years it has been re-discovered and formally defined as an alternative to retained mode systems.  
The key elements of Immediate Mode Graphical User Interfaces (IMGUI) are:

1) Minimise or remove model state typically cached in retained mode gui controls (stateless controls)  
2) Define the user interface by calling functions that generates graphics and modifies model data in place (functional style, creating ui by coding)  
3) Redraw the entire user interface at every frame or in general when there are user inputs or model data changes

This approach considerably lowers application complexity but is not without caveats.  
We will explore the concepts of retained and immediate mode gui, with advantages and disadvantages of each approach.  
We will then describe a very popular open source implementation called “dear imgui”, providing code examples in C++.  
Finally we will show real world use case of imgui in industrial robotic vision field.

Material:

- [Slides](https://github.com/italiancpp/cppday17/blob/master/Immediate%20Mode%20User%20Interface%20in%20C%2B%2B%20-%20Stefano%20Cristiano.pdf)
- [Video](https://youtu.be/Sx7vPcUVQX4)

#### Intelligenza Artificiale oggi

Speaker: **Sebastiano Galazzo**

Sessione prettamente teorica, avrà lo scopo di approfondire cosa è realmente, ma soprattutto cosa non è, l’intelligenza artificiale ad oggi.  
Verrà esploso in dettaglio lo stato dell’arte ad oggi su questo tema per passare ad approfondimenti teorici dettagliati sui principali algoritmi di machine learning in uso come regressione logistica e reti neurali, quindi un approfondimento di implementazioni da zero di una rete neurale in C++.

Material:

- [Slides](https://github.com/italiancpp/cppday17/blob/master/Intelligenza%20Artificiale%20Oggi%20-%20Sebastiano%20Galazzo.pptx)
- [Video](https://youtu.be/I7KtY4lACLQ)

 
#### (Slightly) Smarter smart pointers  

Speaker: **Carlo Pescio**

L’uso degli smart pointers rende la scrittura del codice C++ più rapida e sicura, e più in generale permette una progettazione robusta delle politiche di ownership ed una rappresentazione esplicita di tali politiche nel nostro codice.  
Tuttavia gli smart pointers a cui siamo abituati (mi riferisco in particolare ai puntatori con reference count, pensati per risorse condivise) hanno un overhead non trascurabile, sia in termini di spazio che di tempo. D’altra parte, dopo tutti questi anni sembra improbabile migliorare in modo significativo le performance degli shared pointers.  
Per chi non vuole arrendersi, una buona notizia arriva da una serie di esperimenti, che di fatto forniscono una specie di meccanica statistica dei reference count nei programmi object oriented, da cui possiamo trarre ispirazione per creare uno smart pointer piuttosto interessante, che in media occupa meno spazio ed ha prestazioni migliori (ad es., in un benchmark misto con uso di algoritmi e contenitori STL, risulta oltre 2 volte piu’ veloce rispetto a std::shared\_ptr).  
Il talk riprende le più comuni implementazioni di shared pointers, inclusa ovviamente quella standard, le confronta con alcuni semplici benchmark, spiega le basi statistiche e mostra le parti più rilevanti dell’implementazione dello shared pointer alternativo, ma anche il processo “creativo” che ha portato, in realtà con un percorso piuttosto lungo, a concepire questa nuova implementazione.

Material:

- [Slides](https://github.com/italiancpp/cppday17/blob/master/(Slightly)%20Smarter%20Smart%20Pointers%20-%20Carlo%20Pescio.pdf)
- [Video](https://youtu.be/Ywehms9PtVY)


#### C/C++ interoperability with other languages  

Speaker: **Alberto Bignotti**

La comunità C/C++ è molto vasta e lo standard corrente (C++ 17) è il risultato di anni di miglioramenti. Inoltre, gli strumenti di sviluppo integrati vengono costantemente arricchiti e quindi esistono librerie per affrontare qualsiasi problema informatico. Tuttavia esistono linguaggi alternativi e complementari che possono offrire caratteristiche interessanti (come semplicità d’uso e scalabilità) e vantano comunità significative.

L’obbiettivo è quello di studiare con esempi pratici un prodotto che offra una base C++ e possa essere esteso usando i linguaggi di programmazione più diffusi (ad esempio Java, JavaScript, C# ecc…). Nel corso della sessione, vedremo come implementare un server C/C++ che espone un set di servizi GIS, una App Web based (pure HTML/JavaScript) che li richiama e mostra i risultati su una mappa geografica.

Material:

- [Slides](https://github.com/italiancpp/cppday17/blob/master/C%2B%2B%20interoperability%20with%20other%20languages%20-%20Alberto%20Bignotti.pdf)
- [Video](youtu.be/_wSs8J4ZBrU)

#### C++ e UI: un approccio alternativo

Speaker: **Daniele Pallastrelli**

Nel mio intervento propongo una soluzione alternativa all’annoso problema delle UI per applicazioni desktop, che ultimamente ho adottato con successo in diversi progetti reali.  
Mostrerò come declinarla nel caso di applicazioni C++ e descriverò com’è possibile organizzare questo tipo di software.

Material:

- [Slides](https://github.com/italiancpp/cppday17/blob/master/C%2B%2B%20and%20UI%20un%20approccio%20alternativo%20-%20Daniele%20Pallastrelli.pdf)
- [Video](https://youtu.be/9buNhizFmzc)

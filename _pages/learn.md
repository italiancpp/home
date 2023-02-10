---
title: "Studiare il C++"
date: 2015-10-12T23:14:24+02:00
author: marco
layout: splash
permalink: /learn
guid: http://www.italiancpp.org/?page_id=5285
evolve_sidebar_position:
  - default
evolve_full_width:
  - 'no'
evolve_page_title:
  - 'yes'
evolve_page_breadcrumb:
  - 'yes'
evolve_widget_page:
  - 'no'
evolve_slider_position:
  - default
evolve_slider_type:
  - 'no'
---
_Scusate, ma... questa pagina è un po' vecchia. Stiamo aggiornando le risorse consigliate._

<h5 style="text-align: justify;">
  Se sei un principiante e vuoi pubblicare le tue domande: entra nel <a href="https://www.reddit.com/r/cppit/" target="_blank">nostro subreddit in Italiano dedicato al C++</a>, scrivi un messaggio di testo e taggalo con flair <strong>&#8220;principanti&#8221;:</strong>
</h5>

<img src="/assets/images/flair_principianti_reddit.png">

> Ricordati che un bravo Neofita non pubblica post del tipo &#8220;mi risolvete l&#8217;esercizio?&#8221;, ma piuttosto pone domande dettagliate su quello che non ha capito 🙂

<p>Ci trovi anche su <strong>Discord</strong>.</p>

<p style="text-align: justify;">
  <span style="color: #ffffff;"> </span>
</p>

<p style="text-align: justify;">
  Una domanda ricorrente è <strong>&#8220;da dove iniziare per imparare a programmare in C++?&#8221;</strong>. Esistono tante scuole di pensiero e risposte possibili, anche noi di <span style="color: #0000ff;">++it</span> desideriamo dare la nostra interpretazione.
</p>

<p style="text-align: justify;">
  Molto dipende dal livello di programmazione e dalle conoscenze di chi pone la domanda, se già si conoscono altri linguaggi, se si desidera approfondire argomenti avanzati, ecc. La pagina è quindi divisa in diverse sezioni che aiutano ad orientarsi in base ad esigenze e argomenti differenti.
</p>

Tre raccomandazioni importanti:

  * Dove possibile, tendi sempre a utilizzare risorse moderne (>= C++11)
  * Non spaventarti se la maggior parte delle risorse sono in Inglese (ma ti indicheremo quelle in italiano)
  * Imparare a programmare in C++ ≠ Imparare a programmare in C

##### <span style="color: #2945a4;">Per programmare in C++ non serve conoscere il C<br /> <span style="color: #ffffff;"> </span></span>

<p style="text-align: justify;">
  Ebbene sì, sfatiamo un mito! Il C è <em>quasi</em> un subset del C++ ma in realtà è un linguaggio molto più scarno, privo di moltissimi costrutti e meccanismi supportati dal C++. Il C è un linguaggio adatto a fare <a href="https://en.wikipedia.org/wiki/System_programming" target="_blank">Systems Programming</a>, il C++ è un linguaggio di più alto livello ma adatto a fare sia Systems Programming che Application Programming. Programmare in C++ con uno stile C-like è come comprare una PS4 e usarla solo per giocare con dei titoli della PS3!
</p>

<p style="text-align: justify;">
  Qualche esempio concreto? Si vedono spesso in giro stringhe fatte come char*, quando invece potrebbe andar benissimo una std::string. Oppure array dinamici gestiti manualmente con T*, quando un std::vector&lt;T&gt; è quasi sempre una scelta appropriata.
</p>

<p style="text-align: justify;">
  Se non ti abbiamo ancora convinto leggi <a href="https://isocpp.org/blog/2014/12/myths-1" target="_blank">questo breve articolo</a> di Bjarne Stroustrup! Oppure dai un&#8217;occhiata a <a href="https://github.com/CppCon/CppCon2015/tree/master/Presentations/Stop%20Teaching%20C" target="_blank">questa presentazione</a> di Kate Gregory!
</p>

##### <span style="color: #2945a4;">Una raccomandazione sul materiale pre-C++11</span>  
<span style="color: #2945a4;"> </span>

<p style="text-align: justify;">
  Come forse saprai il C++ si è trasformato con l&#8217;introduzione del <strong>C++11</strong>, mutando molti idiomi e semplificandosi tantissimo. Per questa ragione molti libri &#8220;classici&#8221; del passato (pre-C++11) ora mancano delle &#8220;ultime novità&#8221;. Tuttavia, alcuni sono ancora dei validissimi strumenti (li indicheremo con la dicitura &#8220;<strong>old but gold</strong>&#8220;).
</p>

<p style="text-align: justify;">
  La nostra raccomandazione è di <strong>imparare partendo dal nuovo standard</strong> e solo in seguito &#8211; eventualmente &#8211; spingersi su materiale &#8220;più datato&#8221;. In questo modo si avranno più strumenti per adattare il vecchio al nuovo. Esistono delle eccezioni ovviamente, ma in questa fase transitoria occorre un po&#8217; di pazienza! Quindi in caso di dubbi valgono le raccomandazioni di sempre: cercare su Internet, postare una domanda sul forum, ecc.
</p>

##### <span style="color: #2945a4;">Catalizzatori di risorse/news<br /> <span style="color: #ffffff;">  </span></span>

<p style="text-align: justify;">
  Il bravo C++-ista è sempre interessato all&#8217;evoluzione del linguaggio e delle tecnologie ad esso correlate! Oltre a seguire <a href="http://twitter.com/italiancpp" target="_blank">italiancpp</a>, segue i siti internazionali più importanti (si raccomanda di seguirli anche su <strong>twitter</strong>):
</p>

  * <a href="http://isocpp.org" target="_blank">isocpp.org</a>
  * <a href="http://meetingcpp.com" target="_blank">meetingcpp.com</a>

##### <span style="color: #2945a4;">Reference ufficiali<br /> <span style="color: #ffffff;"> </span></span>

  * <a href="http://en.cppreference.com/w/" target="_blank">C++ Reference</a>
  * <a href="http://eel.is/c++draft/" target="_blank">Draft Interattivo dello standard ISO</a>

&nbsp;

#### <span style="color: #2945a4;">Da dove iniziare?</span>

<p style="text-align: justify;">
  Segue il <strong>set minimo di risorse consigliate per iniziare. </strong>Abbiamo classificato alcune richieste comuni in cui il lettore potrà identificarsi. Col tempo e grazie anche al feedback degli utenti ne inseriremo delle altre. Le sezioni successive aiuteranno ad &#8220;andare oltre&#8221;.
</p>

##### Vorrei un&#8217;introduzione di alto livello sul linguaggio e sulla sua evoluzione  
<span style="color: #ffffff;"> </span>

  * **Libro gratuito**: &#8220;<a href="https://www.jetbrains.com/cpp-today-oreilly/books/Cplusplus_Today.pdf" target="_blank">C++ Today</a>&#8221; di Jon Kalb & Gašper Ažman


##### Desidero imparare a programmare e ho scelto il C++ come linguaggio  
<span style="color: #ffffff;"> </span>

  * **Libro**: <a href="http://www.stroustrup.com/Programming/" target="_blank">&#8220;Programming &#8211; Principles and Practice Using C++ (Second Edition)&#8221;</a> di Bjarne Stroustrup (il creatore del C++)


##### Sono un programmatore, vorrei imparare il C++  
<span style="color: #ffffff;"> </span>

  * **Libro**: <a href="http://www.informit.com/store/c-plus-plus-primer-9780321714114" target="_blank">&#8220;C++ Primer (5th Edition)&#8221;</a> di Lippman, Lajoie, Moo
  * **Libro** (alternativa con taglio più universitario): <a href="http://www.amazon.com/Programmers-Edition-Deitel-Developer-Series/dp/0133439852" target="_blank">&#8220;C++11 for Programmers&#8221;</a> dei fratelli Deitel
  * **Libro**: <a href="http://shop.oreilly.com/product/0636920033707.do" target="_blank">&#8220;Effective Modern C++&#8221;</a> di Scott Meyers (<a href="http://www.hoepli.it/libro/programmazione-c-moderna/9788820367039.html" target="_blank">Esiste la versione italiana</a>)


##### Sono un programmatore C++ &#8220;old-school&#8221; (pre-C++11), vorrei modernizzarmi  
<span style="color: #ffffff;"> </span>

  * **Libro**: <a href="http://www.stroustrup.com/Tour.html" target="_blank">&#8220;A tour of C++&#8221;</a> di Bjarne Stroustrup
  * **Libro**: <a href="http://shop.oreilly.com/product/0636920033707.do" target="_blank">&#8220;Effective Modern C++&#8221;</a> di Scott Meyers (<a href="http://www.hoepli.it/libro/programmazione-c-moderna/9788820367039.html" target="_blank">Esiste la versione Italiana</a>)


##### Sono un programmatore C#, vorrei imparare il C++  
<span style="color: #ffffff;"> </span>

  * **Libro grautito**: <a href="http://geekswithblogs.net/mikebmcl/archive/2012/09/07/c-succinctly-now-available.aspx" target="_blank">&#8220;C++ Succinctly&#8221;</a> di Michael McLaughlin


##### Sto imparando il C++11/C++14/C++1z, cosa non devo perdermi?  
<span style="color: #ffffff;"> </span>

  * **Libro**: <a href="http://shop.oreilly.com/product/0636920033707.do" target="_blank">&#8220;Effective Modern C++&#8221;</a> di Scott Meyers (<a href="http://www.hoepli.it/libro/programmazione-c-moderna/9788820367039.html" target="_blank">Esiste la versione italiana</a>)

&nbsp;

#### <span style="color: #2945a4;">Beyond the basics</span>

Se sei arrivato/a qui hai comunque letto <a href="http://shop.oreilly.com/product/0636920033707.do" target="_blank">&#8220;Effective Modern C++&#8221;</a> di Scott Meyers (<a href="http://www.hoepli.it/libro/programmazione-c-moderna/9788820367039.html" target="_blank">Esiste la versione italiana</a>).

##### Perfezionare la conoscenza del linguaggio  
<span style="color: #ffffff;"> </span>

  * **Libro**: <a href="http://www.stroustrup.com/4th.html" target="_blank">&#8220;The C++ Programming Language (4th Edition)&#8221;</a> di Bjarne Stroustrup (<a href="http://www.hoepli.it/libro/c-linguaggio-libreria-standard-principi-di-programmazione/9788865184486.html" target="_blank">Esiste la versione italiana</a>)



##### Best Practices & Idiomi  
<span style="color: #ffffff;"> </span>

  * **Documento a contributo aperto mantenuto dallo standard**: <a href="https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md" target="_blank">C++ Core Guidelines</a>
  * **Libri** (old but gold): <a href="http://www.gotw.ca/publications/" target="_blank">pubblicazioni di Herb Sutter</a>



##### Approfondire lo studio della STL  
<span style="color: #ffffff;"> </span>

  * **Serie di Video**: <a href="https://channel9.msdn.com/Series/C9-Lectures-Stephan-T-Lavavej-Standard-Template-Library-STL-" target="_blank">&#8220;Standard Template Library&#8221;</a> di Stephen T. Lavavej
  * **Serie di Video**: <a href="https://channel9.msdn.com/Series/C9-Lectures-Stephan-T-Lavavej-Advanced-STL" target="_blank">&#8220;Advanced STL&#8221;</a> di Stephen T. Lavavej
  * **Libro**: <a href="http://www.cppstdlib.com/" target="_blank">&#8220;The C++ Standard Library (2nd Edition)&#8221;</a> di Nicolai M. Josuttis
  * **Libro** (old but gold): <a href="http://www.amazon.it/Effective-Stl-Specific-Standard-Template/dp/0201749629" target="_blank">&#8220;Effective STL&#8221;</a> di Scott Meyers

&nbsp;

#### <span style="color: #2945a4;">Argomenti avanzati</span>

##### Programmazione multi-thread & multi-core  
<span style="color: #ffffff;"> </span>

  * **Libro**: <a href="https://www.manning.com/books/c-plus-plus-concurrency-in-action" target="_blank">&#8220;C++ Concurrency in Action&#8221;</a> di Anthony Williams (sconto _Mannings_: **cplusromeug**)
  * **Libro gratuito**: <a href="https://msdn.microsoft.com/en-us/library/gg675934.aspx" target="_blank">&#8220;Parallel Programming with Microsoft Visual C++&#8221;</a> di Colin Campbell & Ade Miller
  * **Libro**: <a href="http://www.gregcons.com/cppamp/" target="_blank">&#8220;C++ AMP: Accelerated Massive Parallelism with Microsoft Visual C++&#8221;</a> di Kate Gregory & Ade Miller
 

##### Template Metaprogramming  
<span style="color: #ffffff;"> </span>

  * **Libro** (old but gold): <a href="http://www.josuttis.com/tmplbook/" target="_blank">&#8220;C++ Templates &#8211; The Complete Guide&#8221;</a> di Nicolai Josuttis & David Vandevoorde
  * **Libro**: <a href="http://www.amazon.com/Advanced-Metaprogramming-Classic-Davide-Gennaro/dp/1484210115" target="_blank">&#8220;Advanced Metaprogramming in Classic C++&#8221;</a> di Davide Di Gennaro
  * **Libro** (old but gold): <a href="http://www.amazon.com/Template-Metaprogramming-Concepts-Techniques-Beyond/dp/0321227255" target="_blank">&#8220;C++ Template Metaprogramming&#8221;</a> di David Abrahams

&nbsp;

#### <span style="color: #2945a4;">Altre risorse online</span>

  * <a href="https://isocpp.org/wiki/faq/" target="_blank">C++, C++11, C++14 FAQs</a>
  * <a href="http://www.cppsamples.com/" target="_blank">C++ Samples</a>: un repository open con idiomi e pattern tipici

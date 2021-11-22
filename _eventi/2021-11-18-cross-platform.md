---
title: "Windows, macOS and the Web: Lessons from cross-platform development"
excerpt: "Meetup...in presenza!"
read_time: false
related: false
show_date: true
toc: true
share: true
comments: false
author_profile: false
tags:
  - community
  - meetup
  - cross-platform
---

Tornano i meetup C++ **in presenza** realizzati dall'Italian C++ Community e ospitati da ConoscereLinux!

Ogni incontro prevede la condivisione di un argomento, spazio per le domande e poi una pizza tutti insieme.
Il formato della presentazione può variare ed è deciso dal relatore ospite della serata: talk frontale, workshop, live coding, ecc.

Gli incontri, **come avveniva prima dell'emergenza sanitaria**, saranno trasmessi **anche** in diretta streaming. Per interagire con il resto della community, richiedi (se non ce l'hai già) l'accesso al nostro [team slack](https://italiancpp.org/join) ed entra sul canale *#meetup-modena*.

### La sessione

For twelve years, think-cell had been a Windows-only software company and their codebase of approximately 700k lines of code had accumulated many unintentional platform dependencies. Six years ago, the company decided to port their application to the Mac. This change has affected every part of the development process: the project organization, build system, and the way they program in C++ today. The commonly used cross-platform libraries such as Qt and boost were good tools to build on, but by themselves were not enough. For many concepts, such as mutexes, semaphores, or shared memory, they only offer a common interface to platform-specific objects with very different semantics and lifetimes. The team wanted light-weight, platform-independent C++ abstractions with identical semantics for rendering, internationalization, file I/O, mouse event handling, RPC calls, and error reporting. Developing these was challenging, firstly, because they had to define which semantics application needed and, secondly, the team had to implement them on each platform. This was not an easy process but Sebastian would argue it has improved the quality of code very much. By now, think-cell has moved on to the next challenge and has started to move some functionality to web applications. They wanted to reuse the existing code-base of course, and that meant writing web applications in expressive, type-safe C++. Definitely an advantage in the book! They have built web applications using emscripten, but thanks to a student intern, they generate type-safe C++ bindings, beyond those provided by emscripten, from any TypeScript interface definition. In this talk, Sebastian will give you an overview of the C++ abstractions think-cell have implemented, focusing on the cross-platform problem areas where common semantics were hard to define due to limitations of either one of the operating systems, and of course, Sebastian will show you tools that let the company write a web application in C++.

### Il relatore

**Sebastian Theophil** studied Computer Science in Berlin and Toulouse and holds a Ph.D. in Computer Science from the Humboldt University of Berlin. He has been working at think-cell Software since its founding in 2002 and has recently been working on porting think-cell to the Mac.

### Video dell'evento

Se desideri seguire la diretta YouTube e partecipare da remoto:

{% include video id="ssb4Uhs1y1w" provider="youtube" %}

- [Slides](https://www.think-cell.com/en/career/talks/cross-platform/)

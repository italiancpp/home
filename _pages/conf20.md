---
title: "Dettagli Italian C++ Conference 2020"
layout: splash
permalink: /conf20-talks
---

[Slides repository](https://github.com/italiancpp/itcppcon20)

#### Let’s Move – The Hidden Features and Traps of C++ Move Semantics

Speaker: **Nicolai Josuttis**

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/LetsMove%20-%20Nicolai%20Josuttis.pdf)
- [Video](https://youtu.be/OOLR96-GjsI?t=1692)   

#### Lightning Strikes!

Speaker: **Walter E. Brown**

In an homage to a memorable multi-topic Fortran talk from circa 50 years ago, this session will consist of several mini-presentations (“Lightning Talks”) delivering C++ nuggets.

We will explore:

*   how C++ Lambdas came to be thusly named,
*   how form follows use in C++ declaration syntax,
*   classifications within the universe of C++ types, and
*   the influence on C++20 of an early 20th-century mathematician.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/Lightning%20Strikes%20-%20Walter%20Brown.pdf)
- [Video](https://www.youtube.com/watch?v=4yl8gwRS7eQ)  


#### My Least Favorite Anti-Pattern  

Speaker: **Conor Hoekstra**

There is one anti-pattern that is pervasive – it shows up everywhere all the time: the ITM anti-pattern. This is my least favorite anti-pattern and avoiding it can lead to more readable, understandable and beautiful code. ITM stands for “Initialize Then Modify”. When Sean Parent says “no raw loops” – that is an application of avoiding ITM. When Ben Deane says “avoid the initialization declaration split” – that is an application of avoiding ITM. And when Jason Turner walks you through different code smells to avoid – a lot of them are examples of ITM. This talk will introduce the ITM anti-pattern, walk you through the story of my discovery of it and highlight / demonstrate how to avoid it.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/MyLeastFavoriteAntiPattern-Conor%20Hoekstra.pdf)
- [Video](https://www.youtube.com/watch?v=CjHgL5EQdcY)    

#### A Practical Approach to Error Handling  

Speaker: **Arno Schödl**

Every program may encounter errors, some originating from internal bugs in the program, others coming from the environment the program is operating in. Ignoring all errors will make the program utterly unreliable, while treating every conceivable one introduces lots of extra complexity with little benefit. At think-cell, we have been using and refining our own principled approach to error handling, which we have not seen elsewhere. This lecture teaches our method, so that you in your next project, too, can write more reliable software with less effort.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/A%20Practical%20Approach%20to%20Error%20Handling%20-%20Arno%20Sch%C3%B6dl.pdf)
- [Video](https://www.youtube.com/watch?v=E_B8IKJV4ew)   

#### C++ – Macchina a Stati Finiti con il Functor Pattern

Speaker: **Franco Diaspro**

There are many strategies for implementing a state machine in programming languages. I have to study the Functor Pattern for an architecture developed by my customer, then I had the intuition that this pattern is suitable  for this activity. With this aim and to give a service to both, those who use the functions and those who develop finite state machines, I began to develop this project.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/State%20machine%20by%20the%20functor%20pattern%20(C%2B%2B%20Italian%20Conference).pdf)
- [Video](https://www.youtube.com/watch?v=2Ed_kfsTfXI)   


#### The C++20 firehose talk

Speaker: **Fabio Fracassi**

C++20 is feature complete, and nearly ready for ratification.

You might already have heard about the big 4 features Modules, Concepts, Coroutines and Ranges. But what about everything else? The small helpers that make your daily coding more productive, the improvements that make the language easier and more fun?

This talk will be fast-paced. Blink and you might have missed a feature. Let yourself be soaked with information, and gain a good overview of the features that C++20 will have in store for you.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/The%20C%2B%2B20%20Firehose%20talk%20-%20Fabio%20Fracassi.pdf)
- [Video](https://www.youtube.com/watch?v=Be47dtmj8EE) 

#### C++20 Text Formatting  

Speaker: **Alberto Barbati**

Let’s face it, as soon as your program needs to present data to a human user, you will need to some kind of text formatting. Either you write your own library or you are stuck with old C printf or the “modern” iostreams, both of which have limitations and weaknesses. The C++20 library introduces new facilities addressing those limitations and much more. Will they replace the old one? Only future will tell, but it’s a good time to learn about them!

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/C%2B%2B20%20Text%20Formatting%20-%20Alberto%20Barbati.pdf)
- [Video](https://www.youtube.com/watch?v=NVl8BLi3oXI)  

#### Writing performant C++  

Speaker: **Laurence Bank**

A little knowledge goes a long way in writing efficient C++ code. In 30 minutes, I’ll walk you through the areas that have the greatest impact on your code’s speed. I’m an advocate of writing your own SIMD code, but instead of overloading you with SIMD coding knowledge, I’ll show you how to help the compiler create better output of plain old C++ instead.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/Writing%20Performant%20C%2B%2B%20Code%20-%20Larry%20Bank.pdf)
- [Video](https://www.youtube.com/watch?v=DY2M7RBhGng&t=5s) 


#### C++ Development with Visual Studio Code  

Speaker: **Julia Reid**

If you’re looking for a fast and lightweight open-source code editor, Visual Studio Code has you covered. Come for a deep dive into the features of Visual Studio Code, which provide a rich, productive environment for C++ development. This session will cover the C++ extension, CMake Tools extension, and Remote Development extensions for VS Code. Features will be presented live so you can see how they can aid your day-to-day editing, building and debugging. We will also discuss how you can contribute to the core editor and extensions.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/C%2B%2B%20Development%20with%20Visual%20Studio%20Code%20-%20Julia%20Reid.pdf
- [Video](https://www.youtube.com/watch?v=j4nF0NrfdiE&t=1292s)

#### The Silicon Valley coding interview

Speaker: **Nicolò Valigi**

Max Howell, author of the brew package manager for MacOS, famously failed his job interview at Google because he didn’t know the algorithm to invert a binary tree. What is it about coding interviews at major tech companies in Silicon Valley (Apple, Google, Facebook, and friends) that makes even accomplished programmers stumble? This talk will offer a whirlwind tour of the major families of programming puzzles used in technical interviews: dynamic programming, graphs, trees, and recursion. We’ll see how they can be solved with just a few lines of code and the right intuition, and will give references for further study.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/The%20Silicon%20Valley%20coding%20interview%20-%20Nicol%C3%B2%20Valigi.pdf)
- [Video](https://www.youtube.com/watch?v=vKfXw5VdbB8)   

#### Current trends in the C++ Community

Speaker: **Jens Weller**

Presenting on some of the current results from the Meeting C++ Community Survey.  
I will talk a little about what the survey is and then move on to the current results and interesting graphs.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/Current%20trends%20in%20the%20C%2B%2B%20Community%20-%20Jens%20Weller.pdf)
- [Video](https://www.youtube.com/watch?v=ZckduPcuvDs)   


#### Move-only types can save the API

Speaker: **Ivan Čukić**

C++ is a language celebrated for its abstraction mechanisms that do not incur performance penalties at runtime. It is often used in many mission critical systems, games, and everywhere else where speed and safety are paramount.

That does not mean all C++ programs are fast by default. One of the most time costly mistakes we can make in C++ is creating unnecessary copies. C++11 move semantics made a move into the right direction. The move semantics allow us to give away data that we no longer want to use to somebody else without the penalty of creating the copy and without the risk of data races due to data being shared between multiple entities.

But, while generally cheaper than copying, moving is still not a free operation. For this reason, many people diss on the FP-style APIs as inefficient and create impure stateful APIs instead.

We are going to cover “linear types” – an idea from Phil Wadler that was meant to simplify and optimize pure GC-based languages such as Haskell. We’re going to show how the same concept that allows pure functional programming languages to efficiently “change the world” can improve software written in a traditionally imperative impure language such as C++. We will show that with linear types, the FP-style APIs do not need to be inherently slower than their impure imperative counterparts.

Material:

- [Slides](https://github.com/italiancpp/itcppcon20/blob/master/Move-only%20types%20can%20save%20the%20API%20-%20Ivan%20Cukic.pdf)
- [Video](https://www.youtube.com/watch?v=l0ienjOkK-4)
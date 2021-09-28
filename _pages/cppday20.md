---
title: "Dettagli C++ Day 2020"
layout: splash
permalink: /cppday20-talks
---

[Slides repository](https://github.com/italiancpp/cppday20)

#### Let’s make a telegram bot with C++

Speaker: **Alberto Bignotti**

During the evolution of a software I had the need to send notification messages to users and receive messages from the user to the app. I studied telegram, created a Bot and implemented a C ++ library that communicates with users. Some peculiarities:

Local user handshake to the app, telegram user  
– Send notifications from the app to the user  
– Receive commands from the user  
– Implementation of the Bot in polling mode  
– Implementation of the Bot in WebHook mode  
– Some particularities (position of the user, images …)

The object of the session is not how to use my library, but to give ideas so that everyone can create their own.

Material:

- [Slides](https://dev.bigno.it/cpp/tgmAPI-en.pdf)
- [Video](https://www.youtube.com/watch?v=s2XiEXDU-wc)
   
#### WebAssembly: an overview

Speaker: **Lorenzo Veneri**

An introduction and overview about the WebAssembly technology.

Material:

- [Slides](https://github.com/italiancpp/cppday20/blob/main/WebAssembly%20-%20Lorenzo%20Veneri.pdf)
- [Video](https://www.youtube.com/watch?v=5M6kVq-p7l0)

#### Understanding value categories in C++  

##### [Kris van Rens](https://web.archive.org/web/20210128052837/http://italiancpp.org/speakers/#kris)

In C++ today, do you know what an xvalue is? Or a prvalue? Why would you want to know? Because it matters! In C++, each expression is characterized by a value category. These value categories are used to describe parts of the C++ standard, and are often used in books and articles. You might have heard of terms like ‘lvalue’ or ‘rvalue’, which are the most commonly known ones. Over the years, changes to the C++ language changed the meaning of value categories. This means a lot of information about value categories is outdated or just plain wrong. In this talk, I will explain what expression value categories are in today’s C++ standard. It turns out that knowledge about value categories can really be beneficial. Not only will it enrich your understanding of C++ in general, it will deepen your understanding of mechanisms like move semantics. Also, it can help you to make better choices about code. These choices can then leverage language rules to enable compilers to generate efficient code without redundant copies. Other, related topics that will be covered: copy elision, return value optimization, temporary materialization.

Material:

- [Slides](https://krisvanrens.github.io/slides/value-categories-talk-cpp-it/talk.html#/title-slide)
- [Video](https://www.youtube.com/watch?v=km3Urog_wzk)


#### Comunicazione real-time con WebRTC in C++  

##### [Yuri Valentini](https://web.archive.org/web/20210128052837/http://italiancpp.org/speakers/#yvalentini)

WebRTC è una libreria di Google, scritta in C++, per la comunicazione audio/video/dati in tempo reale via internet.  
Rappresenta lo standard di fatto in quanto è integrata all’interno dei maggiori web browser e utilizzata da tantissime applicazioni javascript per audio/video chat.  
Illustreremo i concetti relativi alla comunicazione audio/video in tempo reale, analizzeremo le caratteristiche della base di codice e vedremo come utilizzare la libreria all’interno di programmi C++.

Material:

- [Slides](https://github.com/italiancpp/cppday20/blob/main/webrtc-cppday2020.pdf)
- [Video](https://www.youtube.com/watch?v=4NX9NgzaYAE)

#### Our first game using UE4 and C++

##### [Michele Mischitelli](https://web.archive.org/web/20210128052837/http://italiancpp.org/speakers/#mmischitelli)

During this brief session I will try to show you how to create some key aspects of a simple vertical scrolling shooter game.  
The player’s pawn, projectiles, enemies and special effects.  
Some knowledge of UE4 is required to fully understand what’s going on, but in the mean time you can head over my previous talks where I explain the basics.  
I will also make the full source code available for everyone to download and play with it.

Material:

- [Slides](https://github.com/italiancpp/cppday20/blob/main/Our%20first%20game%20using%20UE4%20and%20Cpp%20-%20Michele%20Mischitelli.pdf)
- [Video](https://www.youtube.com/watch?v=ap6TJtFNJbM)

#### TDD is not about testing (C++ version)  

##### [Gianluca Padovani](https://web.archive.org/web/20210128052837/http://italiancpp.org/speakers/#gpad)

TDD is now mainstream but a lot people don’t know or don’t remember what is its purpose. TDD is about software design not testing or catching bug. TDD helps developers to shape and create software with “good” design, what is a “good” design is something that we will discuss in the topic.

Material:

- [Slides](https://www2.slideshare.net/gpadovani/tdd-is-not-about-testing-c-version)
- [Video](https://www.youtube.com/watch?v=WrPkCXHHUBw)

#### Interoperable AI: ONNX e ONNXRuntime in C++  

##### [Marco Arena](https://web.archive.org/web/20210128052837/https://www.italiancpp.org/speakers/#marco-arena) & Mattia Verasani

ONNX is an open source format built to represent machine learning and deep learning models. The project enables AI developers to use models with a variety of frameworks, tools, runtimes, and compilers. The development of ONNX is driven by a community of partners including Microsoft, Facebook, NVIDIA and Mathworks.

ONNXRuntime is an open source project driven by Microsoft which provides an optimized implementation of all the standard ONNX operators for the CPU. It supports a plenty of acceleration targets like cuDNN by NVIDIA and MKL-DNNL by Intel, and it exposes the right abstraction and runtime support for custom accelerators and runtimes.

In this session you’ll learn about ONNX and ONNXRuntime, and see some practical examples of accelerating ONNX models in C++ with ONNXRuntime.
Material:

- [Slides](https://github.com/italiancpp/cppday20/blob/main/Interoperable%20AI%20-%20Marco%20Arena%2C%20Mattia%20Verasani.pdf)
- [Video](https://www.youtube.com/watch?v=exsgNLf-MyY)
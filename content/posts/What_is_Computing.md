---
title: What exactly are computers?
date: "2021-10-19T21:46:37.121Z"
template: "post"
draft: false
slug: ""
category: "Basics"
tags:
  - "Basics"
  - "Logic"
  - "History"
description: "There is nothing in the world at a macroscopic level that has been co-ordinated with such finesse, on such a grand scale as the billions of transistors moving in sync inside a modern CPU chip, and to work with it correctly you need to understand that how all it really comes down to, is controlled chaos."
socialImage: "/media/comp.jpeg"
---



- [Tools, Machines and Computers](#tools-,-machines-and-computers)
- [So what exactly is a computer?](#what-exactly-is-a-computer-?)
- [Computers as Universal Turing Machines](#computers-as-universal-turing-machines)
- [Computing and Computers](#computing-and-computers)
- [Computing as a history of building Abstractions](#computing-as-a-history-of-building-abstractions)
- [Computers are like bicycle to the Mind](#computers-are-bicycles-to-the-mind)
- [Sources](#sources)


## Tools, Machines and Computers
Right from time immemorial if there is one thing that stands true today as ever, it is this - Humans are driven by needs and desires. Technology has always been a result of these primal factors - right from early man who discovered the wheel and fire to present day scientists working on virtual reality. Every paradigm of change we observe, from the Agricultural Age to Industrial, Computational and Information Age of today can be understood as reinforcements in the social and technological advancements of those periods. If the Industrial Age sparred in unprecented technology improvements like steam engines, weapons and automobiles, the larger wisdom it gave to humankind was that we can *build machines that can do things for us*. 

In the course of the mid 20th century, we realized through a series of challenges and solutions that machines not only can *do* things for us but also *think* for us, *compute* for us to make our cognitive loads smaller. The need for performing computations is an ancient one, right when early man figured that the world around him was far easy to understand using numbers. Advancements in mathematics lead them to understand through the Agricultural age that quantifying things and phenomena offered *leverage* and *convenience*. Using these numbers to get different tasks like accountancy, engineering and business done was the story of the past few centuries.

Till about the time of 1970s, computers could have very well even meant human computers who sat down in research laboratories looking up multiplication, division and trigonomteric tables to compute advanced scientific computations. The film *Hidden Figures* is a wonderful depiction of the same. So how did this definition of "computers" change from humans to present day **Internet of Things**?

## So what exactly is a computer?
>Computers are powerful, flexible machines that perform calculations by processing information through an input and returning output.

Computers are syntactic machines, which means that they manipulate information without properly understanding the meaning of it. What you are looking at right now is a surface of colored pixels, which to a computer means a grid of light intensities arranged in lines. That you see words in those lines means you are semantic, you interpret shapes as having meaning, and you respond to the shapes with more meaning, actions upon those pixels using a cursor or touchscreen.

At it's core it is just a device with processor and memory - the rest of the details about design (mechanical, electrical, optical or quantum) are optional. As long as the phenomenon of storage(either as a combinaiton of specific phycial properties of materials and electrons, or complex probabilistic quantum theories) and processing (basic operations like retrieval, loading onto storage and arithmetic operations) are met enabling us to perform other complex tasks through above operations, it can be deemed to be a computer. Notice that the above definition could include a human, smart watch or a digital calculator as well.

So does that also make a digital watch a computer? Yes and No. The important point to note here is that the digital watch is not entirely **programmable** ie. it is not a machine that allows us to perform more than one kind of computation by itself. Contrast this with the run of the mill personal desktops that can open excels sheets, play music, edit photos, browse the internet etc. Some of the latest smart watches however might offer you this feature of rewiring in which case it would qualify to our model of a computer.  A much better explanation on this front awaits in the next section on UTM.

## Computers as Universal Turing Machines

**The Universal Turing Machine** is a machine that can simulate any other machine described using symbols. Turing wanted to show that, in principle, such a "computer" can exist. He devised amchine that could read symbols off an extremely long tape and modify these symbols based on what it reads. Once the computation is complete, it should also be able to halt. So at any time, the state of the UTM should depend only on two pieces of information: (1) the symbol currently being read, and (2) the machine's current "internal configuration" or "state." Based on its internal state and the symbol currently being read, the machine should (1) write a new symbol in the current square, (2) move backwards or forwards one square, and (3) switch to a new state or halt. Finally, since we want this machine to be physically realizable, the number of possible internal states should be finite. These are the only requirements.

The above design of a machine that can perform the above functions is treated as a "computer" even to this day. Specifically, the electronic device in which you are reading this now is the Von Neumann implementation of the above design scheme itself. A Turing machine defines (as far as we know) what physically-achievable computers are *able to do*. That is, as far as we know, any computer we build (whether using classical physics, quantum mechanics, or something else), can at most solve exactly the problems a Turing machine can and no others.

![utm.jpg](/media/utm.jpg)

## Computers and Computer Science

>Computer Science is to computers what geometry is to surveying instruments.

Computer Science is actually not science in the truest sense of the word. It might be engineering or it might be art. It has a lot in common with magic. But it is not also really about computers. It is not about computers in the same sense that physics is not really about particle accelerators and biology is not really about microscopes. Consider the word "geometry". It means to "measure Earth" or surveying. The name stuck because the Egyptian priesthood developed some of the rudiments of geometry so as to restore the fields after the annual flooding of the Nile.The reason why we think computer science is about computers is the same reason why ancient Egyptians thought geometry was the use of surveying instruments. In a field that is just getting started it is easy to confuse the essence of what you are doing, with the tools that you use. We look back at the ancient Egyptian surveyors and say, gee what they were really doing is formalizing notions about space and time, to start talking about mathematical truths formally. This led to modern mathematics, which is a way to talk precisely about declarative knowledge:  i.e. what is true. Similarly people of the future will look back at us and say, yes those primitives in the 20th century were fiddling around with these gadgets called computers, but really what they were doing is starting to formalize intuitions about process, how to do things, starting to develop a way to talk precisely about how-to knowledge as opposed knowledge which talks about what is true. This is what computer science is about.

Computer Science is probably more closer to the phenomenon of mathematical logic and computational processes as opposed to electronics and the whole paradgim of "computers as machines". Later developments in algorithms and programming languages veered in the "machine" direction a little more, but it's a long time before many of the readers of Turing's work on computability would see themselves as mainly continuing the progress of early 19th century electrical engineers who built the first computers.

## Computers as a history of building Abstractions

>The history of computing is a history of building abstracitons

As and when the 

## Computers are like bicycle to the Mind

>If it can be imagined it can be built


<iframe width="560" height="315" src="https://www.youtube.com/embed/L40B08nWoMk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Sources
🎥 [Crash Course Computer Science](https://youtu.be/tpIctyqH29Q)<br>
🎥 [Code.org : How computers work](https://youtu.be/OAx_6-wdslM?)<br>
🎥 [Richard Feynman Computer Heuristics](https://youtu.be/EKWGGDXe5MA)<br>
📰 [Scott Aaronson - Turing and Godel](https://www.scottaaronson.com/democritus/lec3.html)<br>
📖 [Computer Organization Design](http://www.amazon.com/Computer-Organization-Design-Third-Edition/dp/1558606041/ref=cm_lmf_tit_7) <br>
📖 [CODE : The Hidden Language of Computer Hardware and Software](https://www.amazon.in/Code-Language-Computer-Developer-Practices-ebook/dp/B00JDMPOK2)<br>
📖 [Structured Computer Organization](https://www.amazon.in/Structured-Computer-Organization-6-Tanenbaum/dp/9332571244/ref=sr_1_1?crid=1MDZGR85RX9G3&dchild=1&keywords=structured+computer+organization&qid=1635070731&sprefix=structured+comp%2Cdigital-text%2C283&sr=8-1)<br>
📖 [D is for Digital](https://www.amazon.in/Digital-Well-Informed-Person-Computers-Communications/dp/1463733895/ref=sr_1_1?crid=1HK2XVJZ3YGOP&dchild=1&keywords=d+is+for+digital&qid=1635070786&sprefix=d+is+for+%2Caps%2C293&sr=8-1)<br>
📚 [XORPD](https://www.xorpd.net/)<br>
📚 [MIT Computation Structures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/)<br>
📚 [NAND to TETRIS](https://www.nand2tetris.org/)

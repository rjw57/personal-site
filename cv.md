---
layout: page
title: Curriculum Vitæ
permalink: /cv/index.html
---

# Employment

## University of Cambridge, Department of Engineering

### Senior Research Associate, The Centre for Sustainable Road Freight Sep. 2013–present

Developing computer vision and data analysis algorithms for recognising and
tracking cars from a traffic camera feed between sites. Developing Dual-Tree
Complex Wavelet Transform based algorithms to perform real-time analysis of
video.

### Research Associate, BBSRC (LoLa grant) Oct. 2009–Sep 2013

Part of the Data Analysis for the LoLa single-molecule imaging team. Developed
a custom suite of data analysis and visualisation tools for biological imaging
and tracking. Created novel image and signal processing algorithms for dealing
with noisy and ambiguous input. Co-ordinated geographically disparate team and
lead efforts to improve code quality with automated build testing tools, test
suites and coding standards.

## Pneumacare Ltd

### Consultant Software Engineer Oct. 2008–Oct. 2009

Based at the University of Cambridge. Technology lead and inventor of the
Pneumascan passive lung function monitor system. Rôle required investigation
and development of computer vision algorithms for real-time high-frequency 3D
data capture. Implemented a prototype capture and analysis system including GPU
accelerated processing via CUDA. Created product mock up and marketing renders
using the Blender rendering suite.

## Geomerics Ltd

### Consultant Research Associate Oct. 2007–Oct. 2008

Researched new algorithms for rigging and skinning 3D character models
resulting in the publication of a fully-automated system called Bone Glow

### Senior Software Engineer Jun. 2006–Jul. 2007

Real-time graphics research including full physical global illumination
calculations performed via GPU and CPU co-operation. Developed a practical,
real-world system for lighting now in use in well known game titles such as
Battlefield 3 and Need for Speed: The Run.

# Experience

I have a great deal of experience in various programming languages including C,
C++, JavaScript and Python and have a passion for writing good, clean and
well-tested code. In addition, I have an Academic background in Machine
Learning, Computer Vision and Artificial Intelligence.  I've contributed to a
number of Open Source projects to greater or lesser degrees and my GitHub
account https://github.com/rjw57 has a large number of repositories which give
an overview of my areas of knowledge.

## Popular Open Source Projects

Open Source projects which I created and which are sufficiently
widely used to be packaged in the popular Debian distribution of Linux.

### libdvdnav

This is written
in C and was a project I started to provide support for DVD navigation in Open
Source projects. At the time, I was a committer to the xine media player project
and the library was created as a re-usable off-shoot from the DVD playback
functionality I was adding. The library forms the core of the vast majority of
Open Source DVD playback programs. In addition to parsing the somewhat baroque
binary data structures used by the DVD Video format it also contains an
implementation of the DVD Virtual Machine used to execute navigation programs.
The library is now maintained by the mplayer project.

### dtcwt

The ``dtcwt`` module for Python which is hosted at
https://github.com/rjw57/dtcwt. It implements a particular technique in signal
processing known as the *Dual-Tree Complex Wavelet Transform* (DT-CWT). This
is used in computer vision, image processing and financial time series analysis.
The library has multiple performant implementations of the numerically intensive
DT-CWT algorithm for both CPU and GPU via OpenCL. I am mentoring a PhD student
who is providing a further implementation using Tensorflow, a framework which is
popular in the Machine Learning and Artificial Intelligence field.

Each pull request for the dtcwt library is tested via a Continuous Integration
system which ensures correct functionality via a test suite and code coverage
check. Documentation is automatically built and is available on the web. The
library is structured so that it may be installed automatically using the
standard Python ``pip`` tool. I passionately believe that software must be
packaged, documented and tested well in order to be useful and I use the dtcwt
module as an example to my students on how much quality assurance infrastructure
is available in the cloud.

## Invited talks

I am a confident public speaker and was invited to give the keynote talk at
last year's *Diamond Developer Day*. The event was a conference of all of the
research software engineers for the UK's largest particle accelerator. I gave a
talk on software quality engineering in an Academic environment which was very
well received.

## Other experience

I am passionate about the history of computing and the history of programming
languages in particular. In order to learn more about compilers, I wrote a toy
compiler for the B programming language which was the direct predecessor of
the well-known C language. The compiler is available at
https://github.com/rjw57/rbc and uses the powerful LLVM compiler
infrastructure. It was intended as a teaching aid for compiler implementation
and formed the core of a talk I gave last year at the Cambridge Python Users
Group.

In order to learn electronics and to practice low-level and embedded
programming, I decided to create my own computer from scratch. The result is the
Búri microcomputer system (https://github.com/rjw57/buri) which is a 6502-based
computer system with an Operating System written in 6502 assembler. The latest
version of the hardware uses a 65816 CPU with 512K of memory and has an
in-development video card.

As a more modern example, I co-designed and programmed an embedded inertial
measurement unit as part of Cambridge University Spaceflight. This credit-card
sized module integrated an STM32 microcontroller with various inertial, GPS and
magnetic sensors to provide a real time estimate of spacecraft attitude and
position. In essence it was a modern-day Apollo guidance computer.

I've tried to keep myself abreast of modern web development and am reasonably
fluent in JavaScript. I have personal relationships with some people who work
for the Portable Antiquities Scheme (PAS) and have created a couple of web apps
related to their work which may be found at
http://rjw57.github.io/findmyflo/ and http://rjw57.github.io/pas-measure/.
I've contributed to the Open Source PAS database project. I've experience with
React, WebPack and AngularJS all of which I've used for various internal work
projects and some personal web app projects.

# Education

## University of Cambridge

### Doctor of Philosophy, Signal Processing Oct. 2002–Oct. 2006

Researched applications of advanced mathematical geometry techniques for
real-world use. Gained experience in geometric interpretation of signal
processing techniques, knowledge of accelerated graphics APIs and developed new
research in the fields of computational geometry, non-Euclidean problem solving
and fractals. Thesis title: Computer Graphics using Conformal Geometric
Algebra.

### Master of Engineering, Distinction Oct. 1998–Oct. 2002

Received a distinction (class I equivalent) in Information Engineering. Course
scope included signal processing techniques, computer graphics, artificial
intelligence and software engineering.

# Work Interests

## Computing & Software

I try to keep a broad range of technical skills up to date because, frankly, I
like to play with technology and writing software. In general I am quick to
'deep-dive' into a new field and find it easy to pick up new programming
languages and software-related skills. I find systems design extremely
satisfying and am never happier than when all of the metaphorical plates are
kept spinning by a robot which I have designed. I am particularly enthused by
what has come to be called agile development.

## Academic

I am a signal processor by trade which means that I am particularly interested
in the inferences one may draw from data that one can observe. To this end I
make heavy use of Bayesian methods such as Monte Carlo sampling in order to
find maximally likely a posteriori estimates of the true state of a system from
noisy observations of its output. My research interests are therefore
wide-ranging and have wide applicability. My recent interests have been in
fields as diverse as computer vision and analysis and inference of the dynamics
of receptors on cell membranes. A list of my publications may be found on the
University of Cambridge's Department of Engineering website.

# Technical Skills

## Languages and Libraries

Extensive experience with C, C++, Python and various Unix glue languages such
as sed, awk, perl and ed. Experience in writing for the Gtk+ and Qt GUI
toolkits. I have written at least one non-trivial program in order to learn
languages including Scheme, Smalltalk, Ruby, Java and C#. I class myself as a
competent multi-paradigm programmer who is capable of picking up any sane house
language or coding style with some rapidity.

## Web Technologies

Experience with HTML/CSS/JavaScript (including the latest HTML5 standards) over
a wide variety of personal projects including, but not limited to, this CV, an
interactive Anglo-Saxon dictionary, an Old English speech synthesiser, a
client-side Google+ syndication system and webmaster for my group's website.
Developed a public-facing in-house course management system for the Department
of Engineering which is used to manage third and fourth year module choices.
Experience with server-side programming languages such as Python (WSGI), PHP,
Perl (Mason) and Java servlets.

## Computer Graphics

Enthusiastic student of realistic rendering techniques. Wrote an accelerated
(via SSE) path-tracing renderer for Minecraft maps. Can program using both the
OpenGL 2/3 and DirectX 9/10 APIs. Real-world experience of writing computer
graphics software and GPU acceleration.

## High-performance Computing

Member of the Many Core Computing Group in the University of Cambridge with a
research interest in GPU acceleration of scientific computing. As part of the
LoLa project, I have ported many of our compute-intensive algorithms to a
multi-Tesla architecture and developed a computing engine allowing single
source-code compilation with CUDA and OpenMP accelerated backends. Developed a
novel multi-threaded Metropolis Hastings and Gibbs sampling algorithm to be
published in a forthcoming paper.

## System Administration

I've been de facto system administrator in many places of work and although I
would class myself as a knowledgeable amateur in this field I haven't as yet
lost anyone's data despite many hardware failures over the years. I have
created company-critical backup and restore systems along with designing a
company source control and quality engineering work flow.

# Other Skills

## Languages

I enjoy languages and can speak French to a conversational level. I am
currently studying Arabic, Anglo-Saxon and Welsh.

## Driving

I have a full, clean UK driving license and have held it for more than ten years.

## Design & Theatre

I enjoy typographic design work and have designed many posters for theatre
groups in and around Cambridge. In addition, I have performed with many theatre
groups and have taken several improvised comedy and comic theatre shows to the
Edinburgh Fringe festival. I have long ago lost any fear of public speaking.


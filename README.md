<h1 align="center">My Online Path to a Full Online Computer Science Degree</h1>



# Contents

- [Overview](#overview)
- [Curriculum](#curriculum)
  - [Prerequisites](#prerequisites)
  - [Introduction to Computer Science](#introduction-to-computer-science)
  - [Core CS](#core-cs)
  - [Advanced CS](#advanced-cs)
  - [Final project](#final-project)
  - [Pro CS](#pro-cs)
- [References](#references)

# Overview

The OSSU curriculum is a **complete education in computer science** using online materials.
It's not merely for career training or professional development.
It's for those who want a proper, *well-rounded* grounding in concepts fundamental to all computing disciplines,
and for those who have the discipline, will, and (most importantly!) good habits to obtain this education largely on their own,
but with support from a worldwide community of fellow learners.


# Curriculum

**Curriculum version**: `8.0.0` (see [CHANGELOG](CHANGELOG.md))

- [Prerequisites](#prerequisites)
- [Introduction to Computer Science](#introduction-to-computer-science)
- [Core CS](#core-cs)
  - [Core programming](#core-programming)
  - [Core math](#core-math)
  - [Core systems](#core-systems)
  - [Core theory](#core-theory)
  - [Core applications](#core-applications)


## Introduction to Computer Science

**CS50**, like a lot of other people, changed my life and made me love computer science. David J. Malan introduces Computer Science
to begginers in an amazing and challenging way. Taking this course if you have never writen a line of code before can be
tough, really tough, completing each week's assignment can feel really rewarding. 
The content of the course itself is really complete: from how to use a basic command-line interface to how to implement a complexe stock related
website through explaining how simple algorithms work, CS50 is a incredible class to give you a taste of what Computer Science is.

Courses | Duration | Effort
:-- | :--: | :--: 
[CS50's : Introduction to computer Science](https://www.edx.org/course/cs50s-introduction-to-computer-science)| 11 weeks |

<details>
<summary>Hoverview of what I learnt</summary
><br>


 
</details>

## Core CS

All coursework under Core CS is **required**, unless otherwise indicated.

### Core programming
**Topics covered**:
`functional programming`
`design for testing`
`program requirements`
`common design patterns`
`unit testing`
`object-oriented design`
`Java`
`static typing`
`dynamic typing`
`ML-family languages (via Standard ML)`
`Lisp-family languages (via Racket)`
`Ruby`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[How to Code - Simple Data](https://www.edx.org/course/how-code-simple-data-ubcx-htc1x) | 7 weeks | 8-10 hours/week | none
[How to Code - Complex Data](https://www.edx.org/course/how-code-complex-data-ubcx-htc2x) | 6 weeks | 8-10 hours/week | How to Code: Simple Data
[Software Construction - Data Abstraction](https://www.edx.org/course/software-construction-data-abstraction-ubcx-softconst1x) | 6 weeks | 8-10 hours/week | How to Code - Complex Data
[Software Construction - Object-Oriented Design](https://www.edx.org/course/software-construction-object-oriented-ubcx-softconst2x) | 6 weeks | 8-10 hours/week | Software Construction - Data Abstraction
[Programming Languages, Part A](https://www.coursera.org/learn/programming-languages) | 4 weeks | 8-16 hours/week | recommended: Java, C
[Programming Languages, Part B](https://www.coursera.org/learn/programming-languages-part-b) | 3 weeks | 8-16 hours/week | Programming Languages, Part A
[Programming Languages, Part C](https://www.coursera.org/learn/programming-languages-part-c) | 3 weeks | 8-16 hours/week | Programming Languages, Part B

#### Readings
- **Required** to learn about monads, laziness, purity: [Learn You a Haskell for a Great Good!](http://learnyouahaskell.com/)
  - **Note**: probably the best resource to learn Haskell: [Haskell Programming from First Principles](http://haskellbook.com/) `paid`
- **Required**, to learn about logic programming, backtracking, unification: [Learn Prolog Now!](http://lpn.swi-prolog.org/lpnpage.php?pageid=top)

### Core math

**Topics covered**:
`linear transformations`
`matrices`
`vectors`
`mathematical proofs`
`number theory`
`differential calculus`
`integral calculus`
`sequences and series`
`discrete mathematics`
`basic statistics`
`O-notation`
`graph theory`
`vector calculus`
`discrete probability`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | pre-calculus
[Linear Algebra - Foundations to Frontiers](https://www.edx.org/course/linear-algebra-foundations-to-frontiers-0) ([alt](http://ulaff.net/)) | 15 weeks | 8 hours/week | Essence of Linear Algebra
[Calculus 1A: Differentiation](https://www.edx.org/course/calculus-1a-differentiation) | 13 weeks | 6-10 hours/week | pre-calculus
[Calculus 1B: Integration](https://www.edx.org/course/calculus-1b-integration) | 13 weeks | 5-10 hours/week | Calculus 1A
[Calculus 1C: Coordinate Systems & Infinite Series](https://www.edx.org/course/calculus-1c-coordinate-systems-infinite-series) | 13 weeks | 5-10 hours/week | Calculus 1B
[Mathematics for Computer Science](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/index.htm)<sup>**1**</sup> | 13 weeks | 5 hours/week | Calculus 1C

<sup>**1**</sup>: Students struggling with MIT Math for CS can consider taking the [Discrete Mathematics Specialization](https://www.coursera.org/specializations/discrete-mathematics) first.
It is more interactive but less comprehensive, and it costs money to unlock full interactivity.

### Core systems

Skip to the second course (Nand2Tetris) when the first course (CS50) moves away from C.
([Why?](FAQ.md#why-do-you-recommend-skipping-the-second-half-of-cs50))

**Topics covered**:
`procedural programming`
`manual memory management`
`boolean algebra`
`gate logic`
`memory`
`computer architecture`
`assembly`
`machine language`
`virtual machines`
`high-level languages`
`compilers`
`operating systems`
`network protocols`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Introduction to Computer Science - CS50](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x#!) ([alt](https://cs50.harvard.edu/)) | 12 weeks | 10-20 hours/week | introductory programming
[Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alt](http://www.nand2tetris.org/)) | 6 weeks | 7-13 hours/week | C-like programming language
[Build a Modern Computer from First Principles: Nand to Tetris Part II ](https://www.coursera.org/learn/nand2tetris2) | 6 weeks | 12-18 hours/week | one of [these programming languages](https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png), From Nand to Tetris Part I
[Introduction to Computer Networking](https://lagunita.stanford.edu/courses/Engineering/Networking-SP/SelfPaced/about)| 8 weeks | 4–12 hours/week | algebra, probability, basic CS
[ops-class.org - Hack the Kernel](https://www.ops-class.org/) | 15 weeks | 6 hours/week | algorithms

#### Readings
- **Recommended**: While Hack the Kernel recommends Modern Operating Systems as a textbook, we suggest using [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/).

### Core theory

**Topics covered**:
`divide and conquer`
`sorting and searching`
`randomized algorithms`
`graph search`
`shortest paths`
`data structures`
`greedy algorithms`
`minimum spanning trees`
`dynamic programming`
`NP-completeness`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Algorithms: Design and Analysis, Part I](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms1+SelfPaced/about) | 8 weeks | 4-8 hours/week | any programming language, Mathematics for Computer Science
[Algorithms: Design and Analysis, Part II](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms2+SelfPaced/about) | 8 weeks | 4-8 hours/week | Part I


### Core applications

**Topics covered**:
`Agile methodology`
`REST`
`software specifications`
`refactoring`
`relational databases`
`transaction processing`
`data modeling`
`neural networks`
`supervised learning`
`unsupervised learning`
`OpenGL`
`raytracing`
`block ciphers`
`authentication`
`public key encryption`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Databases](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about)| 12 weeks | 8-12 hours/week | some programming, basic CS
[Machine Learning](https://www.coursera.org/learn/machine-learning)| 11 weeks | 4-6 hours/week | linear algebra
[Computer Graphics](https://www.edx.org/course/computer-graphics-uc-san-diegox-cse167x)| 6 weeks | 12 hours/week | C++ or Java, linear algebra
[Cryptography I](https://www.coursera.org/course/crypto)| 6 weeks | 5-7 hours/week | linear algebra, probability
[Software Engineering: Introduction](https://www.edx.org/course/software-engineering-introduction-ubcx-softeng1x) | 6 weeks | 8-10 hours/week | Software Construction - Object-Oriented Design
[Software Development Capstone Project](https://www.edx.org/course/software-development-capstone-project-ubcx-softengprjx) | 6-7 weeks | 8-10 hours/week | Software Engineering: Introduction


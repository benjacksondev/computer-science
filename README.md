![Open Source Society University (OSSU)](https://i.imgur.com/kYYCXtC.png)

<h3 align="center">Open Source Society University</h3>
<p align="center">
  Path to a free self-taught education in Computer Science!
</p>
<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
  </a>
  <a href="https://github.com/ossu/computer-science">
	<img alt="Open Source Society University - Computer Science" src="https://img.shields.io/badge/OSSU-computer--science-blue.svg">
  </a>
</p>

# Contents

- [Curriculum](#curriculum)
- [Code of conduct](#code-of-conduct)
- [Team](#team)

# Curriculum

**Curriculum version**: `8.0.0` (see [CHANGELOG](CHANGELOG.md))

- [Prerequisites](#prerequisites)
- [Core CS](#core-cs)
  - [Core math](#core-math)
  - [Core systems](#core-systems)
  - [Core applications](#core-applications)
- [Advanced CS](#advanced-cs)
  - [Advanced theory](#advanced-theory)
  - [Advanced theory](#advanced-theory)
  - [Advanced Math](#advanced-math)

---

## Prerequisites

- [Core CS](#core-cs) assumes the student has already taken [high school math](https://github.com/ossu/computer-science/blob/master/FAQ.md#how-can-i-review-the-math-prerequisites), including algebra, geometry, and pre-calculus.
- [Advanced CS](#advanced-cs) assumes the student has already taken the entirety of Core CS
and is knowledgeable enough now to decide which electives to take.

## Core CS

### Core math
Discrete math (Math for CS) is a prerequisite and closely related to the study of algorithms and data structures. Calculus both prepares students for discrete math and helps students develop mathematical maturity.

**Topics covered**:
`discrete mathematics`
`mathematical proofs`
`basic statistics`
`O-notation`
`discrete probability`
`and more`

Courses | Duration | Effort | Notes | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--: | :--:
[Calculus 1A: Differentiation](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.1x+2T2019/about) ([alt](https://ocw.mit.edu/courses/mathematics/18-01sc-single-variable-calculus-fall-2010/index.htm)) | 13 weeks | 6-10 hours/week | The alternate covers this and the following 2 courses | [high school math](FAQ.md#how-can-i-review-the-math-prerequisites) | [chat](https://discord.gg/mPCt45F)
[Calculus 1B: Integration](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.2x+3T2019/about) | 13 weeks | 5-10 hours/week | - | Calculus 1A | [chat](https://discord.gg/sddAsZg)
[Calculus 1C: Coordinate Systems & Infinite Series](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.3x+1T2020/about) | 6 weeks | 5-10 hours/week | - | Calculus 1B | [chat](https://discord.gg/FNEcNNq)
[Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about) ([alt](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/)) | 13 weeks | 5 hours/week | [2015/2019 solutions](https://github.com/spamegg1/Math-for-CS-solutions) [2010 solutions](https://github.com/frevib/mit-cs-math-6042-fall-2010-problems) [2005 solutions](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2005/assignments/). | Calculus 1C | [chat](https://discord.gg/EuTzNbF)

### Core systems

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

[Operating Systems: Three Easy Pieces](coursepages/ostep/README.md) | 10-12 weeks | 6-10 hours/week |

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

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Divide and Conquer, Sorting and Searching, and Randomized Algorithms](https://www.coursera.org/learn/algorithms-divide-conquer) | 4 weeks | 4-8 hours/week | any programming language, Mathematics for Computer Science | [chat](https://discord.gg/mKRS7tY)
[Graph Search, Shortest Paths, and Data Structures](https://www.coursera.org/learn/algorithms-graphs-data-structures) | 4 weeks | 4-8 hours/week | Divide and Conquer, Sorting and Searching, and Randomized Algorithms | [chat](https://discord.gg/Qstqe4t)
[Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming](https://www.coursera.org/learn/algorithms-greedy) | 4 weeks | 4-8 hours/week | Graph Search, Shortest Paths, and Data Structures | [chat](https://discord.gg/dWVvjuz)
[Shortest Paths Revisited, NP-Complete Problems and What To Do About Them](https://www.coursera.org/learn/algorithms-npcomplete) | 4 weeks | 4-8 hours/week | Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming | [chat](https://discord.gg/dYuY78u)

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
`ray tracing`
`and more`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Computer Graphics](https://www.edx.org/course/computer-graphics-2)| 6 weeks | 12 hours/week | C++ or Java, linear algebra | [chat](https://discord.gg/68WqMNV)

## Advanced CS

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest.
Not every course from a subcategory needs to be taken.
But students should take *every* course that is relevant to the field they intend to go into.

### Advanced programming

**Topics covered**:
`debugging theory and practice`
`goal-oriented programming`
`parallel computing`
`object-oriented analysis and design`
`UML`
`large-scale software architecture and design`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Parallel Programming](https://www.coursera.org/learn/scala-parallel-programming)| 4 weeks | 6-8 hours/week | Scala programming
[Compilers](https://www.edx.org/course/compilers) | 9 weeks | 6-8 hours/week | none
[Introduction to Haskell](https://www.seas.upenn.edu/~cis194/fall16/)| 14 weeks | - | -

### Advanced theory

**Topics covered**:
`formal languages`
`Turing machines`
`computability`
`event-driven concurrency`
`automata`
`distributed shared memory`
`consensus algorithms`
`state machine replication`
`computational geometry theory`
`propositional logic`
`relational logic`
`Herbrand logic`
`game trees`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Theory of Computation](https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/) ([alt](http://aduni.org/courses/theory/index.php?view=cw)) | 13 weeks | 10 hours/week | [Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about), logic, algorithms
[Computational Geometry](https://www.edx.org/course/computational-geometry) | 16 weeks | 8 hours/week | algorithms, C++
[Game Theory](https://www.coursera.org/learn/game-theory-1) | 8 weeks | 3 hours/week | mathematical thinking, probability, calculus

### Advanced math
Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | [high school math](FAQ.md#how-can-i-review-the-math-prerequisites) | [chat](https://discord.gg/m6wHbP6)
[Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) | 14 weeks | 12 hours/week | corequisite: Essence of Linear Algebra | [chat](https://discord.gg/k7nSWJH)
[Introduction to Numerical Methods](https://ocw.mit.edu/courses/mathematics/18-335j-introduction-to-numerical-methods-spring-2019/index.htm)| 14 weeks | 12 hours/week | [Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) | [chat](https://discord.gg/FNEcNNq)
[Introduction to Formal Logic](https://forallx.openlogicproject.org/) | 10 weeks | 4-8 hours/week | [Set Theory](https://www.youtube.com/playlist?list=PL5KkMZvBpo5AH_5GpxMiryJT6Dkj32H6N) | [chat](https://discord.gg/MbM2Gg5)
[Probability](https://projects.iq.harvard.edu/stat110/home) | 15 weeks | 5-10 hours/week | [Differentiation and Integration](https://www.edx.org/course/calculus-1b-integration) | [chat](https://discord.gg/UVjs9BU)

![keep learning](https://i.imgur.com/REQK0VU.jpg)

# Code of conduct
[OSSU's code of conduct](https://github.com/ossu/code-of-conduct).

# Team

* **[Eric Douglas](https://github.com/ericdouglas)**: founder of OSSU
* **[Josh Hanson](https://github.com/joshmhanson)**: lead technical maintainer
* **[Waciuma Wanjohi](https://github.com/waciumawanjohi)**: lead academic maintainer
* **[Contributors](https://github.com/ossu/computer-science/graphs/contributors)**

# B.tech wala

## What is it?

![Coding at the whiteboard - from HBO's Silicon Valley](https://d3j2pkmjtin6ou.cloudfront.net/coding-at-the-whiteboard-silicon-valley.png)

This is a 4 week study plan for having an excelance in C,C++ and DSA 

**Required:** 
* Patience
* Time

Note this is a study plan for **software engineering**, not frontend engineering or fullstack development. There are really 
super roadmaps and coursework for those career paths elsewhere (see https://roadmap.sh/ for more info).

There is a lot to learn in a university Computer Science program, but only knowing about 75% is good enough for an interview, so that's what I cover here. 
For a complete CS self-taught program, the resources for my study plan have been included in Kamran Ahmed's Computer Science Roadmap: https://roadmap.sh/computer-science

---

## Table of Contents

### The Study Plan

- [What is it?](#what-is-it)
- [Why use it?](#why-use-it)
- [How to use it](#how-to-use-it)
- [Don't feel you aren't smart enough](#dont-feel-you-arent-smart-enough)
- [A Note About Video Resources](#a-note-about-video-resources)
- [Choose a Programming Language](#choose-a-programming-language)
- [Books for Data Structures and Algorithms](#books-for-data-structures-and-algorithms)
- [Interview Prep Books](#interview-prep-books)
- [Don't Make My Mistakes](#dont-make-my-mistakes)
- [What you Won't See Covered](#what-you-wont-see-covered)
- [The Daily Plan](#the-daily-plan)
- [Coding Question Practice](#coding-question-practice)
- [Coding Problems](#coding-problems)

### Topics of Study

- [Algorithmic complexity / Big-O / Asymptotic analysis](#algorithmic-complexity--big-o--asymptotic-analysis)
- [Data Structures](#data-structures)
    - [Arrays](#arrays)
    - [Linked Lists](#linked-lists)
    - [Stack](#stack)
    - [Queue](#queue)
    - [Hash table](#hash-table)
- [More Knowledge](#more-knowledge)
    - [Binary search](#binary-search)
    - [Bitwise operations](#bitwise-operations)
- [Trees](#trees)
    - [Trees - Intro](#trees---intro)
    - [Binary search trees: BSTs](#binary-search-trees-bsts)
    - [Heap / Priority Queue / Binary Heap](#heap--priority-queue--binary-heap)
    - balanced search trees (general concept, not details)
    - traversals: preorder, inorder, postorder, BFS, DFS
- [Sorting](#sorting)
    - selection
    - insertion
    - heapsort
    - quicksort
    - merge sort
- [Graphs](#graphs)
    - directed
    - undirected
    - adjacency matrix
    - adjacency list
    - traversals: BFS, DFS
- [Even More Knowledge](#even-more-knowledge)
    - [Recursion](#recursion)
    - [Dynamic Programming](#dynamic-programming)
    - [Design Patterns](#design-patterns)
    - [Combinatorics (n choose k) & Probability](#combinatorics-n-choose-k--probability)
    - [NP, NP-Complete and Approximation Algorithms](#np-np-complete-and-approximation-algorithms)
    - [How computers process a program](#how-computers-process-a-program)
    - [Caches](#caches)
    - [Processes and Threads](#processes-and-threads)
    - [Testing](#testing)
    - [String searching & manipulations](#string-searching--manipulations)
    - [Tries](#tries)
    - [Floating Point Numbers](#floating-point-numbers)
    - [Unicode](#unicode)
    - [Endianness](#endianness)
    - [Networking](#networking)
- [Final Review](#final-review)

### Getting the Job

- [Update Your Resume](#update-your-resume)
- [Find a Job](#find-a-job)
- [Interview Process & General Interview Prep](#interview-process--general-interview-prep)
- [Be thinking of for when the interview comes](#be-thinking-of-for-when-the-interview-comes)
- [Have questions for the interviewer](#have-questions-for-the-interviewer)
- [Once You've Got The Job](#once-youve-got-the-job)

**---------------- Everything below this point is optional ----------------**

### Optional Extra Topics & Resources

- [Additional Books](#additional-books)
- [System Design, Scalability, Data Handling](#system-design-scalability-data-handling) (if you have 4+ years experience)
- [Additional Learning](#additional-learning)
    - [Compilers](#compilers)
    - [Emacs and vi(m)](#emacs-and-vim)
    - [Unix command line tools](#unix-command-line-tools)
    - [Information theory](#information-theory-videos)
    - [Parity & Hamming Code](#parity--hamming-code-videos)
    - [Entropy](#entropy)
    - [Cryptography](#cryptography)
    - [Compression](#compression)
    - [Computer Security](#computer-security)
    - [Garbage collection](#garbage-collection)
    - [Parallel Programming](#parallel-programming)
    - [Messaging, Serialization, and Queueing Systems](#messaging-serialization-and-queueing-systems)
    - [A*](#a)
    - [Fast Fourier Transform](#fast-fourier-transform)
    - [Bloom Filter](#bloom-filter)
    - [HyperLogLog](#hyperloglog)
    - [Locality-Sensitive Hashing](#locality-sensitive-hashing)
    - [van Emde Boas Trees](#van-emde-boas-trees)
    - [Augmented Data Structures](#augmented-data-structures)
    - [Balanced search trees](#balanced-search-trees)
        - AVL trees
        - Splay trees
        - Red/black trees
        - 2-3 search trees
        - 2-3-4 Trees (aka 2-4 trees)
        - N-ary (K-ary, M-ary) trees
        - B-Trees
    - [k-D Trees](#k-d-trees)
    - [Skip lists](#skip-lists)
    - [Network Flows](#network-flows)
    - [Disjoint Sets & Union Find](#disjoint-sets--union-find)
    - [Math for Fast Processing](#math-for-fast-processing)
    - [Treap](#treap)
    - [Linear Programming](#linear-programming-videos)
    - [Geometry, Convex hull](#geometry-convex-hull-videos)
    - [Discrete math](#discrete-math)
- [Additional Detail on Some Subjects](#additional-detail-on-some-subjects)
- [Video Series](#video-series)
- [Computer Science Courses](#computer-science-courses)
- [Papers](#papers)

---

## Why use it?

If you want to work as a software engineer for a large company, these are the things you have to know.

If you missed out on getting a degree in computer science, like I did, this will catch you up and save four years of your life.

When I started this project, I didn't know a stack from a heap, didn't know Big-O anything, or anything about trees, or how to
traverse a graph. If I had to code a sorting algorithm, I can tell ya it would have been terrible.
Every data structure I had ever used was built into the language, and I didn't know how they worked
under the hood at all. I never had to manage memory unless a process I was running would give an "out of
memory" error, and then I'd have to find a workaround. I used a few multidimensional arrays in my life and
thousands of associative arrays, but I never created data structures from scratch.

It's a long plan. It may take you months. If you are familiar with a lot of this already it will take you a lot less time.

## How to use it

Everything below is an outline, and you should tackle the items in order from top to bottom.

I'm using GitHub's special markdown flavor, including tasks lists to track progress.
  - [More about GitHub-flavored markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

### If you don't want to use git

On this page, click the Code button near the top, then click "Download ZIP". Unzip the file and you can work with the text files.

If you're open in a code editor that understands markdown, you'll see everything formatted nicely.

![How to download the repo as a zip file](https://d3j2pkmjtin6ou.cloudfront.net/how-to-download-as-zip.png)

### If you're comfortable with git

Create a new branch so you can check items like this, just put an x in the brackets: [x]

1. ***Fork the GitHub repo:*** `https://github.com/jwasham/coding-interview-university` by clicking on the Fork button.

    ![Fork the GitHub repo](https://d3j2pkmjtin6ou.cloudfront.net/fork-button.png)

1. Clone to your local repo:

    ```
    git clone git@github.com:<your_github_username>/coding-interview-university.git
    cd coding-interview-university
    git checkout -b progress
    git remote add jwasham https://github.com/jwasham/coding-interview-university
    git fetch --all
    ```

1. Mark all boxes with X after you completed your changes:

    ```
    git add .
    git commit -m "Marked x"
    git rebase jwasham/main
    git push --set-upstream origin progress
    git push --force
    ```

## Don't feel you aren't smart enough

- Successful software engineers are smart, but many have an insecurity that they aren't smart enough.
- Following videos may help you overcome this insecurity:
    - [The myth of the Genius Programmer](https://www.youtube.com/watch?v=0SARbwvhupQ)
    - [It's Dangerous to Go Alone: Battling the Invisible Monsters in Tech](https://www.youtube.com/watch?v=1i8ylq4j_EY)

## A Note About Video Resources

Some videos are available only by enrolling in a Coursera or EdX class. These are called MOOCs.
Sometimes the classes are not in session so you have to wait a couple of months, so you have no access.

It would be great to replace the online course resources with free and always-available public sources, 
such as YouTube videos (preferably university lectures), so that you people can study these anytime, 
not just when a specific online course is in session.

## Choose a Programming Language

You'll need to choose a programming language for the coding interviews you do, 
but you'll also need to find a language that you can use to study computer science concepts.

Preferably the language would be the same, so that you only need to be proficient in one.

### For this Study Plan

When I did the study plan, I used 2 languages for most of it: C and Python

* C: Very low level. Allows you to deal with pointers and memory allocation/deallocation, so you feel the data structures 
    and algorithms in your bones. In higher level languages like Python or Java, these are hidden from you. In day to day work, that's terrific,
    but when you're learning how these low-level data structures are built, it's great to feel close to the metal.
    - C is everywhere. You'll see examples in books, lectures, videos, *everywhere* while you're studying.
    - [The C Programming Language, 2nd Edition](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628)
        - This is a short book, but it will give you a great handle on the C language and if you practice it a little
            you'll quickly get proficient. Understanding C helps you understand how programs and memory work.
        - You don't need to go super deep in the book (or even finish it). Just get to where you're comfortable reading and writing in C.
        - [Answers to questions in the book](https://github.com/lekkas/c-algorithms)
* Python: Modern and very expressive, I learned it because it's just super useful and also allows me to write less code in an interview.

This is my preference. You do what you like, of course.

You may not need it, but here are some sites for learning a new language:
- [Exercism](https://exercism.org/tracks)
- [Codewars](http://www.codewars.com)
- [HackerEarth](https://www.hackerearth.com/for-developers/)
- [Scaler Topics (Java, C++)](https://www.scaler.com/topics/)

### For your Coding Interview

You can use a language you are comfortable in to do the coding part of the interview, but for large companies, these are solid choices:

- C++
- Java
- Python

[CC-BY-SA-4.0](./LICENSE.txt)

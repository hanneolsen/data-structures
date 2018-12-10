# Data Structures in Javascript
[![Build Status](https://travis-ci.org/slugbyte/data-structures.svg?branch=master)](https://travis-ci.org/slugbyte/data-structures)

![abstract data structure drawing](https://github.com/slugbyte/data-structures/raw/master/assets/data-structures-header.png)

## Goals
* The implamentations will be test driven
* Each implamentaion will use closures to maintain state (not classes or constructurs)
* Each data structure will have docs to describe their use cases, link resources, and list exercises 

## What are "abstract data types"?
Often when the words "data type" are used together they are often refering to a model of some "type" of information. The phrase "data type" may remind you of _primitive data types_ in programming languages like floating point numbers, integers, booleans, and characters, or perhaps it reminds you of more complex data types such as JPEG image files, and WAV audio files. If you are familiar with Object Oriented Programing (OOP) you should be used to the idea of modeling all kinds of information in to classes which could be though of as "types", for example you may have at some point modeled user data, website content, or video game state. A data type is just a model. 

Where ever there is data in software there is usually actions that can be preformed on that data. These actions are typicaly functions desgined to limit the ways in which the data can be mutated (modified). One of OOP's main goals was to couple data types with the their actions (class methods). Data types are often coupled with actions.
 
Over time many software design patterns have emmerged as programmers have realized certian data types, data actions, and software architecutes have repeatedly solved specific common problems. One category of design patterns that has emmerged is called Abstract Data Types (ADTs). ADTs are models for data types that are defined by their behavior instead of there inforamtion. At first this can seem a bit confusing, but Its only giving a name to a thing that programmers do naturally ie. coupling actions with data. Often this coupling is thought of in reverse, like-data is thought to have a type and actions can belong to that type. However ADTs define common behaviors or actions as a type and are agnostic to the kind of information stored. ADTs are data types that model behavior. 

Abstract data types are amazing tools that solve many common programming problems. Learing to implament them can greatly inhance your understanding of solutions to common software design problems. 

## General Abstrat Data Structures
* ✗ Linked List
* ✗ Doubly Linked List
* ✗ Array
* ✗ Enumeratin
* ✔︎ [Stack](src/stack)
* ✗ Queue
* ✗ Set
* ✗ Tuple 
* ✗ Container 
* ✗ Tree
* ✗ Binary Tree
* ✗ Binary Search Tree
* ✗ Binary Heap
* ✗ Graph 
* ✗ Trie 
* ✗ Hash Table

### Bonus  
* Binary Math Functions
* Observable
* Circular Buffer
* Dynamic Array
* AA Tree
* AVL Tree
* Binary Search Tree
* Cartesian Tree
* Red-Black Tree
* Rope
* B-Tree
* Heap
* Binomial Heap
* Ternary Tree
* K-Ary Tree
* Double Hashed Hash Table
* Directed Graph 

## References
* [https://en.wikipedia.org/wiki/Abstract_data_type](https://en.wikipedia.org/wiki/Double_hashing)

# Quantum computing for beginners

In this guide you will get a quick introduction to quantum computing. It is intended for people who barely know anything about the field but want to know more about this exciting new technology. We will answer five questions:

+ **What is quantum computing?**
In this section we will explain the core concepts of quantum computing and what makes it different from classical computing.
+ **Why do we need quantum computing?**
Here we will see how some problems that are impossible to solve realistically by classical computers can be solved efficiently by quantum computers.
+ **Why should you learn quantum computing?**
Not sure if learning quantum computing is worth your while? Here we'll give you several reasons why it's a good idea to learn quantum computing.
+ **What is Q#?**
Here we will outline the main features of Q#, the new programming language that Microsoft is developing. We will see what is different from other quantum computing frameworks and other programming languages.
+ **How can you learn quantum computing?**
In this last question we will present a short guide with all the learning resources that you need to start writing your first quantum programs.

## 1- What is quantum computing?

Ok, let's be honest, quantum computing is a daunting term. However, it's not that hard if you look at it from the right perspective! So let's start by the basics!

The term quantum computing is a combination of two fields that have revolutionized technology and the human society during the last century: *quantum physics* and *computing*. So to understand what is new in quantum computing first let's make sure that we understand how a classical computer works. Then we will see how quantum physics completely changes the game.

### Brief introduction to classical computing
A computer is a device that takes some input information (e.g two numbers *a* and *b*) and manipulates it through some automated process to give another information as an output (eg. the sum *a* + *b*).
![alt text][logo]

[logo]: \computer_diagram.png
The input and the output can be expressed in different forms. For example, a question and its answer:
 + **Input:** Is the number *a* prime?
 + **Output:** Yes/No

The process in which the information is transformed from the input to the output is called the *computation* and it follows a well defined set of operations defined by a program or algorithm. This computation takes some time that depends on the physical realization of the computer and on the algorithm. In general we want it to be as short as possible, nobody likes to wait for the result.

#### The bit

Information may be represented by *symbols* of an *alphabet*. For example, this text is written in English, which has an alphabet composed of 26 letters and some punctuation marks. We want computers to solve a great variety of problems. Then it makes sense to build them to process the information in its simplest representation. This will help us to generalize the computation process to any triple of input, algorithm, and output.

The simplest alphabet possible is the binary alphabet, composed only by two symbols: **0** and **1**. Each instance of information represented by a symbol of the binary alphabet represents a basic unit of information, which is called *bit*. Any piece of information can be represented by a string of concatenated bits. Then, roughly speaking, a computer is just a physical device that transforms a set of input bits into another set of output bits.

#### Logical gates and circuits

If bits are the basic units of information, logic gates are just the most basic processes of computation. The good thing is that any complex computation can be decomposed as a concatenation of different logic gates (furthermore, we only need one type of gate to make any computation). Let's take a look at some of the simplest gates.

+ **Identity gate:** is the simplest gate possible. Takes one bit as the input and outputs one bit with the same value.
![Altt](./Identity_gate.svg)

+ **NOT gate:** it takes one bit as the input and outputs one bit with the opposite value. 
![Altt](./NOT_gate.svg)
+ **AND gate:** it takes two bits as the input and outputs a bit with value 1 if both input bits are 1 and outputs 0 otherwise. ![Altt](./AND_gate.svg)
+ **OR gate:** it takes two bits as the input and outputs a bit with value 1 if at least one of the input bits are 1 and outputs 0 otherwise.
![Altt](./OR_gate.svg)
+ **XOR gate:** it takes two bit as the input and outputs a bit with value 1 if one and only one of the input bits are 1 and zero otherwise.
![Altt](./XOR_gate.svg)
+ **NAND gate:** the NAND gate can be thought as a concatenation of one AND gate followed by a not gate. It takes two bit as the input and outputs a bit with value 0 if both input bits are 1 and outputs 1 otherwise.
![Altt](./NAND_gate.svg)

These gates can be used to construct more complex computations. For example, we can use one XOR gate and one AND gate to create a computation that adds two bits:

![Altt](./half_adder.svg)

The scheme above is called **circuit** and it is one of the possible ways to represent the algorithm that rule the computations. The circuit is read from left to right. Each wire carries one bit that can be either **1** or **0**. The variables (A and B) at the left of each wire represent the input bits and the variables at the right end of each wire represent the output bits. It is easy to check that $C_1C_0$ represents the binary addition of A and B.

Here we won't dive more into the theory of classical computing, but it is worth to note that these gates constitute a framework to express a very general set of computations. To see why note that if we can add numbers, we can multiply them by summing several times. If we can multiply and sum numbers then we can also combine these operations to execute more complex operations and so on.

A very useful mathematical fact is that the NAND gate is a *universal gate*: this means that any of the other gates can be implemented using only NAND gates. This allow us to express any circuit only in terms of one type of gate. If we associate an execution time to the NAND gate (the time that takes the NAND gate to transform the input bits into the output bit) we can estimate the required time for the computation by counting the number of sequential NAND gates and multiplying it by the execution time. Later on, this concept of counting the number of gates needed to execute an algorithm will be important to see why quantum computers are faster than classical ones for certain types of computations.

### Physical realization of computers

### What's new in quantum computing?

Ok, now that we understand more or less how a classical computer let's start with the quantum!

#### Quantum superposition


+ From the bit to the qubit
+ Entanglement
+ Quantum gates and quantum circuits

## 2- Why do we need quantum computing?

### Non tractable classical problems

Here we can explain how some problems are impossible to handle with realistic classical resources

+ Molecular dynamics simulation
+ Factorization (?)

### quantum boost examples

+ Search algorithm
+ Solving linear systems of equations

## 3- Why should you learn quantum computing?

### New way of thinking about computing

### quantum inspired algorithms

### Preparing for the future

### quantum computing is fun

## 4- What is Q#?

### Circuit model vs programming language

### Short description of basic Q# features

## 5- How can you learn quantum computing?

### Essential mathematical tools 
Here we can link to the documents the intern is preparing.
### Learning resources
+ Katas
+ Samples
+ Brilliant course
+ Other resources
### Useful references
+ Books
+ quantum blogs
+ Other resources



 


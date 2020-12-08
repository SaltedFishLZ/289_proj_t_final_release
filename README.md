# [Week 5] Different Types of Activation Units
CS289A(20F) Project T Final by Team Placeholder

## Learning Objectives

* The role activation units paly in neural networks [Linyuan Gong, Wayne Tung-Wei Lin]
  - Why activations are essential in neural networks. What happens when activation units are absent.
  - With activation units, we can approximate any function in theory.

* Introduction to common activation units [Wayne Tung-Wei Lin, Sheng-Jung Yu]
  - Know different activation units and their advantages/disadvantages
  - Apply them in practice

* Gradient vanishing/exploding caused by activation units [Zheng Liang, Linyuan Gong]
  - What is the problem
  - Why it happens
  - How to solve/mitigate it

## Teaching Methods

* The role activation units paly in neural networks
  * For this part, we will first introduce some basic concepts and conclusions in lecture slides.
  * To give students a deeper understanding, we will provide rigorous mathematical proof in notes and ask students to prove some basic conclusions in assignments.

* Introduction to common activation units
  - Visualize different activation functions and let the student hand-derive derivatives of common activation units.
  - Explain how gradient vanishing happens and how to avoid such a problem.
  - Compare performances of different activation units with a toy example of MNIST dataset.


* Gradient vanishing/exploding caused by activation units
  * We will briefly introduce this problem as well as some solutions in lecture slides.
  * To give students a deeper understanding, we will provide a detailed analysis in the notes and ask students to think about the roots of this issue given our analysis. Once students know the roots, they should think further about how to eliminate/mitigate/suppress this problem by attacking the root causes. Then we will talk about some concrete solutions like weight initialization in notes.
  * For one specific solution, weight initialization, We will ask students finish a homework problem step by step to derive the famous Xavier initialization for tanh and Kaiming initialization for ReLU in theory and also implement these techniques in the coding part.

    After finishing the homework problem:
    + Students should know the basic principle for weight initialization and can derive their own initialization methods for different activation functions. This skill is very useful in engineering practice as well as researches.
    + Xavier and Kaiming initializationn are both famous and recent papers. Conquering weight initialization and discover the main points of 2 papers by themselves, students will be encouraged and have more confidence on research.
    + Students may also develop their interest in some advanced topics like random matrices.
 

## File Structure
<pre>
project
│   <b>Note.pdf</b>: main lecture content  
│   <b>Slides.pdf</b>: brief summary of the Note.pdf.     
│   <b>Quiz.pdf</b>   
└───<b>assignments</b>: folder containing problem descriptions and corresponding jupyter notebook for each problem   
│   │   <b>Assignment.pdf</b>: problem descriptions   
│   └───<b>prob2</b>: folder containing the problem and the solution for problem 2    
│   │   │   <b>prob2.ipynb</b>   
│   │   └─  <b>prob2_sol.ipynb</b>       
│   └───<b>prob3</b>: folder containing the problem and the solution for problem 3     
│   │   │   <b>prob3.ipynb</b>      
│   │   └─  <b>prob3_sol.ipynb</b>      
│   └───<b>prob4</b>: folder containing the problem and the solution for problem 4     
│       │   <b>prob4.ipynb</b>     
└─      └─  <b>prob4_sol.ipynb</b>   
</pre>

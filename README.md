# BSU Grad Twine Story

## Introduction
This is an interactive choose your own adventure style narrative using the **Twine** framework. 
It explores the concepts of searching for a job after graduating with a Computer Science degree, presented in a humorous and silly lens.
Through player-made choices and some random chance, the player may find themselves in situations they may or may not have prepared for.
Will you find your dream job, be trapped working a dead-end job, or find yourself working in a different field than expected?

## Technical Framework
This project was used with [Twine 2.10](https://twinery.org/) using the built-in **Harlowe** story format language.

## How to run
#### Option 1
1. Use the GitHub Pages build [https://alexsmurray.github.io/CS439_FiniteStateLab/](https://alexsmurray.github.io/CS439_FiniteStateLab/)
2. Play!
   
#### Option 2
1. Download or clone this repository.
2. Open the file `index.html` in a browser like Chrome, Firefox, or Edge.
3. Play!
   
## Nodes
**Twine** uses **passages** to indicate nodes. These **passages** are then stored in something called a **story library**, which is stored in the browser's storage. More on this can be found [here](https://twinery.org/reference/en/getting-started/basic-concepts.html)  
Swapping between nodes in **Twine's Harlowe language** is done by creating a **link** and pointing to the next **passage** you want to go to through the use of a **macro**.  
Macro example: [[Go to next node ->next]]  
"Go to next node" is the **link** that will display as a clickable link. It will then go to a **passage** named "next"

## Reflection
Through this project, I have learned how to efficiently use more features of **Twine** to create an interactive story.
Things I learned the hard way include, setting variables inside of links, removing whitespace caused by macros, and logic needed to manage states between nodes.
The viewport given by **Twine** is a great tool to see how different elements interact with one another. 
In terms of game design, this also allows for a better understanding of state management between game objects. 


### What I am proud of
I am proud of the silly story, turning work into combat, finding a way to change variables when selecting a link, and getting rid of that annoying whitespace caused by macros.

### Things I would have liked to do that I did not
Mainly, I would have liked to add more polishing to the story; things like more text style or maybe even images and sounds. 
I also thought about adding a random chance that the player accidentally causes the company to go bankrupt or get liquidated.
Or just more risk for getting the dream job.

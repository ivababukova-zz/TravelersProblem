## The Traveller's Problem

This repository contains a formal description of the Traveller's Problem (TP). Traveller's Problem is a computational task whose extensions and variations are often encountered by travellers around the world.

The task is concerned with creating a valid travel schedule, using airplanes as a means of transportation and in accordance with certain constraints specified by the traveller. TP is NP-hard, a fact we prove by reduction from the Travelling Salesman Problem (TSP) to TP.

This work is done as part of my MSci degree at the [University of Glasgow](http://www.gla.ac.uk/). This project is supervised by [David Manlove](http://www.dcs.gla.ac.uk/~davidm/).

Informal description of TP can be found in `problem.pdf`. More formal definitioncan be found in `problem2.pdf`. The `mprop/` folder contains the project proposal files: planned approach to model and solve the problem and review of existing work.

#### Compling the text
This work is done using latex. If you want to compile a given `.tex` file, do the following:

##### To generate problem.pdf:
`pdflatex problem`
`bibtex problem`
`pdflatex problem`

Similarly for problem2.pdf, and for the files in `mprop/`.

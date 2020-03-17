# Regenerating Neural Network
[Growing Neural Cellular Automata](https://distill.pub/2020/growing-ca/)
* Dr. Károly Zsolnai-Fehér - cellular automatons
* Automata are similar to games with a bunch of cells and simple rules 
	* Simple rules determine when cell should be full and when should be empty 
	* Best Example: John Horton Conway’s Game of Life 
		* Each cell represents little life form 
* Too many neighbours will lead to overpopulation deaths, and too few leads to underpopulation deaths the right amount will thrive and reproduce 
* Why is it interesting?
	* Shows that small set of simple rules can give rise to remarkably complex life forms including: 
		* Gliders
		* Spaceships 
		* John Von Neumann’s universal conductor 
* Cellular Automaton programmed to evolve single cell to grow into prescribed kind of life form 
	* Two key differences from most works 
		* Cell state is different 
		* Mathematical formulation is similar to deep neural network
* Exception but why?
	* Gives rise to useful feature - teach it to grow prescribed organisms 
	* Over time sometimes will decay and can’t continue growing - but paper describes how to recover from undesirable states - which might mean that it can regenerate when damaged 
* Amazing considering it wasn’t even trained for it 
	* Main objective of paper was to grow and maintain shape (regeneration is a subset of this)

#### Possible Applications?
* Possibly for jpeg manipulation as a filtering option - self regulating compression 

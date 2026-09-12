# Neuraltex
I'm taking a class on neural networks and had a fun idea, I recalled that LaTeX was supposedly turing complete, so why not see if we can run a neural network as a LaTeX document.

The `neural.tex` document creates an AND gate truth table, by compiling it with `pdflatex` it will output a poorly formatted document that displays the truth table, the neural networks finalized weights and biases, and the neural networks computed output truth table.

The main issue I ran into is the fact that loops cannot be nested in any way in LaTeX, at least in the naive methods I tried, so I had to hand unroll them.

This is fine given I only have two neurons, but if we want more complexity, a solution to this needs to be found.


Heres an image of what the output looks like, you can see that the ground truth table T column matches the output column.

<img width="548" height="375" alt="image" src="https://github.com/user-attachments/assets/30036470-990f-49ab-9ee8-50173cbcd879" />


Real TeX wizards will probably flinch at seeing my code, I flinched seeing it too. 

I will probably mess around with TeX more and see if there are any more stupid-fun programs that can be written.

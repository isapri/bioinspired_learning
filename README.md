# Bioinspired Learning
Bio-inspired algorithms application por MUTSC/BINL practical project.

In this project we developed a modification for 'Reversing the game of life using genetic algorithms' [[1]](#1) original implementation. We introduced a regularization term in the fitness function in order to select better initial boards of Conway's game of life based on the concept of 'Garden of Eden'. 
Our modification allows us to obtain less noisy initial boards that will improve the metrics of the comparision between the 'ground truth' initial board and the predicted board based on the genetic algorith. 

We wrote a small paper that can be found [An experiment on reversing Game Of Life using Genetic Algorithms](src/BINL_GA_paper.pdf)

# Contact 
For further contact you can reach us via e-mail: 

Isabel Prieto Payo: isabel.prieto.payo@alumnos.upm.es
Víctor Gutiérrez García: v.ggarcia@alumnos.upm.es

# Setup
Go to your project parent directory and create and activate your virtual environment.
```bash
python3 -m venv env
source env/bin/activate
```

Once activated, downoload all the required packages.
```bash
pip install -r requirements.txt
```
Now, you will be able to install packages and run Python within the environment without interfering with packages installed globally.

Once you are finished, exit the virtual environment.
```bash
deactivate
```

# Developer
You may need to update the requirements file with new needed packages.
```bash
pip freeze > requirements.txt
```
## References
<a id="1">[1]</a> 
Pavel Tyshevskyi. 
Reversing the game of life using genetic algorithms. 
https://medium.com/@ptyshevs/rgol-ga-1cafc67db6c7   
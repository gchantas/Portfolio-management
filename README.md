# Portfolio-management
Software demonstrating core idea of Chapter 25-Statistical Consequences of Fat-tails, N.N. Taleb. 
Particularly, the differences are shown between the distribution of gain/loss when allocating budget on a certain portfolio. 
Two models are compared: multivariate Gaussian vs. multivariate Students-t.

Chaing the seed changes the experimental results. For fixed seed, the results are always the same (reproducibiility!).
N is the dimensions of the random variables X.
S,S2 are the number of samples of the Gaussian/Student's-t.
$Nu$ is the parameter controlling the degree of the fat tails: the smaller its value the fatter the tails. It must be always positive and for <2 the variance becomes undefined.
The weights w are chosen randomly in the current edition. User can adapt them.

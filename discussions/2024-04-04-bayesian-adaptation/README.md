# April 4

## Phylogenetics Models Continued

## Bayesian Methods, Gene Trees, and Molecular Adaptation  

Bayesian approaches are related to Maximum Likelihood in the sense that the (potentially) same models of evolution are used, but included in the assessment of the best fitting tree is the use of "priors" on many of the parameters, which represents the investigatorʻs "belief" or knowledge of the system. After observing the data, the likelihood is calculated and multiplied with the prior (updated) to give us the "posterior", which represents an update of our beliefs after conducting the study. The use of priors is the most controversial part of Bayesian approaches.   

Practically speaking, Bayesian approaches are used to create much more nuanced models to fit onto the data. More recently they have been used to model demographic parameters along phylogenies such as population size, timing of splits, accounting for heterogeneity of rates, etc. One of the first uses of Bayesian approaches was to study the phylodynamics of virus evolution.

### 52. [Felsenstein, J. 2004. Chapter 18](../54.Felsenstein2004Ch18_BayesianMethods.pdf). Bayesian inference of phylogenies. Pp. 288-306 in Inferring Phylogenies. Sinauer Assoc., Sunderland.    **todos:person1, person2**      

To Dos:  
Bayes Theorem - person 1  
Bayesian methods for phylogenies, MCMC, Metropolis - person 2  
Bayesian MCMC for phylogenies, Proposal distributions - person 1  
Computing likelihod, summarizing the posterior, priors on trees - person 2
Controversies - All  

### Great [Intro to Coalescent Theory](http://www.sfu.ca/biology/courses/bisc869/869_lectures/MHP_Coalescent.pdf) lecture by Mick Elliot and Arne Moers

### 42. [Maddison, W. P. 1997](https://drive.google.com/drive/u/0/folders/1ocqMPD5gX9xi4VQy_5OtU5wSyg-X8ftM) Gene trees in species trees. Systematic Biology 46(3):523-536  

#### Concept Map by Allison Fisher   

<img width="700" src="Maddison1997_conceptmap_af.jpg" >

#### Questions

1. Can we know the “true” species tree without using gene trees?

2. Is it inhibiting to try to consider all of the possible gene histories and discordance processes in constructing a phylogeny? If so, how many do you think would be sufficient to construct a functional phylogeny?

3. How can we apply Bayesian theory to gene trees in species trees? What would be considered the data?

### 43. [Drummond, A. J., Nicholls, G. K., Rodrigo, A. G., and Solomon, W. 2002](https://drive.google.com/drive/u/0/folders/1ocqMPD5gX9xi4VQy_5OtU5wSyg-X8ftM) Estimating Mutation parameters, population history and geneaology simultaneously from temporally spaced sequence data. Genetics 161:1307-1320.   

One of the first papers to use phylogenetics to infer demographic parameters. This was accomplished using a Bayesian approach which in general allows the specification of more parameter rich models. These are also the developers of the BEAST phylogenetic software package. In this paper they inferred population size, timing of evolutionary dynamics, and rapid viral evolution.


### 44. [Yang, Z., Nielsen, R. 2002](https://drive.google.com/drive/u/0/folders/1ocqMPD5gX9xi4VQy_5OtU5wSyg-X8ftM) Substitution models for detecting molecular adaptation at individual sites along specific lineages. Mol. Biol. Evol. 19(6):908-917.   **map:Dani**  

With mathematically explicit models of sequence evolution, it became possible to test many hypotheses beyond the topology and branch lengths of an evolutionary process. In particular, it was now possible to test for selection at particular sites and thus testing for molecular adaptation.

#### Concept Map by Dani Bartz   

<img width="700" src="Yang2002_conceptmap_db.png" >

#### Questions 

1. What are some of the parameters or qualities of branch-site Model B that makes it fit the data better than the other models? Which dataset did it fit the best?

2. The authors stated that the branch-site models from this paper could identify positively selected sites when they exist using Bayes prediction, but then later mentioned that typical data sets may not contain enough information for Bayes prediction to be reliable and that it wouldn't offer much advantage over simple ancestral sequence reconstruction. Do you think that Bayes prediction plays a necessary role here, or is it not necessary?


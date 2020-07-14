## Welcome to My Page

# **About Me**

![](https://raw.githubusercontent.com/SourangshuGhosh/SourangshuGhosh.github.io/master/Pictures/me%20(1).jpg)

I am a fourth year undergraduate student of the department of civil engineering enrolled in its Dual Degree Program in **Indian institute of Technology Kharagpur, West Bengal, India** mostly knows to all as IIT KGP. I am also doing my minors in Mathematics and Computing in its Master of Science program. Apart from these I have been working under various professors of my university in various research projects. I have been mostly collaborating in my research works with Dr. Baidurya Bhattacharya, Professor, Department of Civil Engineering, IIT KGP.

## **Contact Details**

Personal Email ID: [sourangshug123@gmail.com](mailto:sourangshug123@gmail.com) Institute Email ID: [sourangshu@iitkgp.ac.in](mailto:sourangshu@iitkgp.ac.in)

Phone Number: 7063068190

## **My Research Works and Interests**

All of my works are basically scientific computing projects. I mostly interested in application of various Stochastic and Probabilistic Methods/Models in Real Life Problems. Apart from that I have also good knowledge in the field of Evolutionary Algorithms and its recent incorporation in Various Machine Learning Algorithms. I mostly do my coding works in Fortran, C/C++/MATLAB and Python. All of my codes are uploaded as Github Repositories. My Github Profile can be seen by clicking here [https://github.com/SourangshuGhosh](https://github.com/SourangshuGhosh) . This website contains all the links to the various repositories/topics and explains how it works and what they are meant for

1. **Stochastic Reactive Brownian Dynamics**

![](https://raw.githubusercontent.com/SourangshuGhosh/SourangshuGhosh.github.io/master/Pictures/SRBD.jpg)
<br />We develop a Split Reactive Brownian Dynamics (SRBD) algorithm for particle simulations of reaction-diffusion systems based on the Doi or volume reactivity model, in which pairs of particles react with a specified Poisson rate if they are closer than a chosen reactive distance. In our Doi model, we ensure that the microscopic reaction rules for various association and dissociation reactions are consistent with detailed balance (time reversibility) at thermodynamic equilibrium. The SRBD algorithm uses Strang splitting in time to separate reaction and diffusion, and solves both the diffusion-only and reaction-only subproblems exactly, even at high packing densities. To efficiently process reactions without uncontrolled approximations, SRBD employs an event-driven algorithm that processes reactions in a time-ordered sequence over the duration of the time step. A grid of cells with size larger than all of the reactive distances is used to schedule and process the reactions, but unlike traditional grid-based methods such as Reaction-Diffusion Master Equation (RDME) algorithms, the results of SRBD are statistically independent of the size of the grid used to accelerate the processing of reactions. We use the SRBD algorithm to compute the effective macroscopic reaction rate for both reaction- and diffusion-limited irreversible association in three dimensions, and compare to existing theoretical predictions at low and moderate densities. We also study long-time tails in the time correlation functions for reversible association at thermodynamic equilibrium, and compare to recent theoretical predictions. Finally, we compare different particle and continuum methods on a model exhibiting a Turing-like instability and pattern formation. Our studies reinforce the common finding that microscopic mechanisms and correlations matter for diffusion-limited systems, making continuum and even mesoscopic modeling of such systems difficult or impossible. We also find that for models in which particles diffuse off lattice, such as the Doi model, reactions lead to a spurious enhancement of the effective diffusion coefficients.

The links to the Github Repository is [https://github.com/SourangshuGhosh/Stochastic\_Reactive\_Brownian\_Dynamics](https://github.com/SourangshuGhosh/Stochastic_Reactive_Brownian_Dynamics)

2. **FORM( First Order Reliability Methods)**

![](https://raw.githubusercontent.com/SourangshuGhosh/SourangshuGhosh.github.io/master/Pictures/FORM.jpg)
<br />The first-order reliability method (FORM) has been widely used in structural reliability estimation applications. The method involves Taylor expansion of the failure function, i.e. the linearization of the limit state equation, not performed around the mean value of the function, but at a point that is called the &#39;most probable failure point&#39;. The selection of an appropriate linearization point is an important consideration (Ang and Tang, 1984), and actually leads to an iterative solving procedure.

Based on the underlying theory and adopting the method proposed by Hasofer and Lind, the following is a summary of the selection procedure. The process starts with the transformation of the non-normal variables to standard normal variables with zero mean and unit variance (Madsen _et al.,_ 1986), using the Rosenblatt transformation (see also Ang and Tang, 1984). The target is to find the most probable failure point, i.e. the point on the failure locus that defines the minimum distance of the limit state surface from the origin in the space of the reduced variables (Shinozuka, 1983). The shortest distance between the failure surface and the origin in the space of the reduced variables is called the reliability index _β_.

The point on the failure surface that has the minimum distance from the origin can be found by using, for example, the method of Lagrange multipliers (Ang and Tang, 1984), following an iterative procedure. Given that _β_ is now available, the failure probability of the system can be approximated by:

Pf=Φ−β

where Φ(–_β_) is the cumulative distribution of the standard normal variate (Madsen _et al.,_1986).

For linear failure functions this solution is exact. For non-linear failure functions, as in the case of the failure function of a composite material layer, the exact calculation of the failure probability or the reliability generally involves mathematical and computational difficulties. Following the reviews by, for example, Eamon _et al._ (2005) and Schueller _et al._ (2004), of various structural reliability methods and their accuracy and effectiveness in solving problems based on the number of random variables and the linearity (or not) of the failure function, FORM can be seen to have limitations for non-linear failure functions having a large number of random variables.

Several algorithms have been proposed for the approximation of the most probable failure point and the _β_ index (see e.g. Ang and Tang, 1984; Madsen _et al.,_ 1986). In a comparison between five algorithms that can be used for the approximation of the most probable failure point (Liu and Der Kiureghian, 1991), the general conclusion is that the decision as to which is the most effective algorithm depends on the failure function of interest. Similarly, in Wang and Grandhi (1994) a new search algorithm is proposed for the estimation of the _β_ index, and its application is compared with other widely used algorithms. An iterative algorithm already applied for composite laminates is described in Madsen _et al._ (1986). However, when a limit state function is not unimodal, that is, if there is more than one local minimum, it is not certain that the global minimum will be obtained. In fact the failure function as described in the previous section is multi-modal (Miki _et al.,_ 1990), and therefore the search algorithm might need modifications. Still, there is no guarantee that the algorithm will converge in all cases, and it is likely that when it is being applied it will produce, for the basic variables, values that are outside of their natural limits (Madsen _et al.,_ 1986).

The links to the Github Repository is[https://github.com/SourangshuGhosh/FORM](https://github.com/SourangshuGhosh/FORM)

3. **Solution of Three Dimensional Isotropic/Anisotropic Seismic Wave Equation**

One of the most popular methods to simulate numerically the seismic wave propagation in an elastic medium is the finite difference method. In the context of numerically modelling in unbounded medium, the wave needs to be absorbed at the artificial boundaries of the computational domain and therefore it is necessary to define non-reflecting conditions at these boundaries to mimic an unbounded medium.

The Perfectly Matched Layer(PML) has the remarkable property of having a zero reflection coefficient for all angles of incidence and all frequencies before discretezition and has become widely used( eg Collino and Tsogka 2001). However the reflection coefficient is not zero anymore after the discretezition and becomes even very large at grazing incidence. Therefore an improved version of the PML condition has been developed: the convolution perfectly matched layer condition(CPML) (e.g. Komatitisch and martin 2007). The repository developed is a similar implementation of this in Fortran.

The links to the Github Repository is[https://github.com/SourangshuGhosh/SeismicAnalyzer](https://github.com/SourangshuGhosh/SeismicAnalyzer)

4. **Steel Section Properties**
5. **COVID-19 Model by SIR method**
6. **Stein Variational Gradient Descent(SVGD)**

![](https://raw.githubusercontent.com/SourangshuGhosh/SourangshuGhosh.github.io/master/Pictures/SVGD.png)
<br />We propose a general purpose variational inference algorithm that forms a natural counterpart of gradient descent for optimization. Our method iteratively transports a set of particles to match the target distribution, by applying a form of functional gradient descent that minimizes the KL divergence. Empirical studies are performed on various real world models and datasets, on which our method is competitive with existing state-of-the-art methods. The derivation of our method is based on a new theoretical result that connects the derivative of KL divergence under smooth transforms with Stein&#39;s identity and a recently proposed kernelized Stein discrepancy, which is of independent interest. The repository was build based upon the paper &quot;Stein Variational Gradient Descent: A General Purpose Bayesian Inference Algorithm&quot; by [Qiang Liu](https://arxiv.org/search/stat?searchtype=author&amp;query=Liu%2C+Q), [Dilin Wang](https://arxiv.org/search/stat?searchtype=author&amp;query=Wang%2C+D)

7. **N-gram Model**

![](https://raw.githubusercontent.com/SourangshuGhosh/SourangshuGhosh.github.io/master/Pictures/NGRAM.png)
<br />Given a sequence of N-1 words, an N-gram model predicts the most probable word that might follow this sequence. It&#39;s a probabilistic model that&#39;s trained on a corpus of text. Such a model is useful in many NLP applications including speech recognition, machine translation and predictive text input.An N-gram model is built by counting how often word sequences occur in corpus text and then estimating the probabilities. Since a simple N-gram model has limitations, improvements are often made via smoothing, interpolation and backoff.

An N-gram model is one type of a **Language Model (LM)**, which is about finding the probability distribution over word sequences.

The links to the Github Repository is[https://github.com/SourangshuGhosh/N-gram](https://github.com/SourangshuGhosh/N-gram)

8. **Bag of Words Model**

![](https://raw.githubusercontent.com/SourangshuGhosh/SourangshuGhosh.github.io/master/Pictures/BAGWORDS.png)
<br />The  **bag-of-words model**  is a simplifying representation used in natural language processing an information retreival (IR). In this model, a text (such as a sentence or a document) is represented as the  bag(multiset) of its words, disregarding grammar and even word order but keeping multiplicity. The bag-of-words model has also been used for computer vision. The bag-of-words model is commonly used in methods of document classification where the (frequency of) occurrence of each word is used as a feature for training a classifier. In practice, the Bag-of-words model is mainly used as a tool of feature generation. After transforming the text into a &quot;bag of words&quot;, we can calculate various measures to characterize the text. The most common type of characteristics, or features calculated from the Bag-of-words model is term frequency, namely, the number of times a term appears in the text. For the example above, we can construct the following two lists to record the term frequencies of all the distinct words (BoW1 and BoW2 ordered as in BoW3):

(1) [1, 2, 1, 1, 2, 1, 1, 0, 0, 0]

(2) [0, 1, 1, 1, 0, 1, 0, 1, 1, 1]

Each entry of the lists refers to the count of the corresponding entry in the list (this is also the histogram representation). For example, in the first list (which represents document 1), the first two entries are &quot;1,2&quot;:

- The first entry corresponds to the word &quot;John&quot; which is the first word in the list, and its value is &quot;1&quot; because &quot;John&quot; appears in the first document once.
- The second entry corresponds to the word &quot;likes&quot;, which is the second word in the list, and its value is &quot;2&quot; because &quot;likes&quot; appears in the first document twice.

This list (or vector) representation does not preserve the order of the words in the original sentences. This is just the main feature of the Bag-of-words model.

Some more repositories developed by me are

1. **Genetic Programming for development of CNN Architecture**
2. **A Model For Topological Defects in Superfluids**
3. **Evolutionary Deep Neural Networks**
4. **Structural Reliability**
5. **Stochastic Seismic Generator**
6. **Cartesian Genetic Programming**

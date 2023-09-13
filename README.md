
# Stability Function

[zoom link]([https://us02web.zoom.us/j/88521701658]())

---

![firstpage](image/README/firstpage.png)

### Document about the Hackathon:

***Introductory file :**

  **Cyril Morcrette, Martin Best, Helena Reid, Joana Rodrigues, Theo XirouchakiHelena Reid, Joana Rodrigues, Theo Xirouchaki.*

* Evaluation of Surface Layer Stability Functions and Their Extension to First Order Turbulent Closures for Weakly and Strongly Stratified Stable Boundary Laye

  **Andrey V. Debolskiy · Evgeny V. Mortikov · Andrey V. Glazunov  · Christof Lüpkes*

  **Location**: `"docs/"`

### Examples available

Machine Learning for Improving Surface-Layer-Flux Estimates: `https://link.springer.com/article/10.1007/s10546-022-00727-4`

*[Tyler McCandless](https://link.springer.com/article/10.1007/s10546-022-00727-4#auth-Tyler-McCandless-Aff1), [David John Gagne](https://link.springer.com/article/10.1007/s10546-022-00727-4#auth-David_John-Gagne-Aff2), [Branko Kosović](https://link.springer.com/article/10.1007/s10546-022-00727-4#auth-Branko-Kosovi_-Aff2), [Sue Ellen Haupt](https://link.springer.com/article/10.1007/s10546-022-00727-4#auth-Sue_Ellen-Haupt-Aff2), [Bai Yang](https://link.springer.com/article/10.1007/s10546-022-00727-4#auth-Bai-Yang-Aff3-Aff4), [Charlie Becker](https://link.springer.com/article/10.1007/s10546-022-00727-4#auth-Charlie-Becker-Aff2) & [John Schreck](https://link.springer.com/article/10.1007/s10546-022-00727-4#auth-John-Schreck-Aff2)*

### Data source

1.`https://fluxnet.org/data/`

**PLEASE DO NOT PUBLISH ANYTHING USING THIS DATA WITHOUT REFERRING TO THEIR DATA POLICY**

### Tasks

1. Powerpoint:

   1.*Powerpointslides to explain the science behind what we are doing. Why it matters? What if affects? What does stable/unstable mean?slides to explain the science behind what we are doing. Why it matters? What if affects? What does stable/unstable mean?*

   2.*Slide explaining the input features: what are LWdownLWdown, , PrecipPrecip, , PsurfPsurf, , QairQair, , SWdownSWdown, , TairTair, , UstarUstar, Wind, Z0, how are these measured?, Wind, Z0, how are these measured?*
2. Data exploration:

   1. Produce histogram of each input and output variables
   2. Produce scatter plots of correlations between variables.
   3. Find max, min of all variables.
   4. Should some variables be looked at in terms of logs?
   5. Produce code to generate a normalised/standardised/rescaled data set.
3. Visualization:

   1. produce maps of total amount of data from each site.
   2. Maps of mean values of parameters at each site
4. Writing paper:

   1. Start drafting a paper using Overleaf Latex. Think about literature review and sections and O(5) key figures
5. Balancing

   1. Assess how balanced the data is
   2. Develop a code to balance it
6. Training

   1. Train a random forest to predict stability function. Optimise hyper--parameters.parameters
   2. Train a MLP to predict the stability function. Optimise hyper--parameters.parameters.

![in_out](image/README/input_output.png"input and output")

![tasks](image/README/tasks.png)

### Message from Helena,

* In order to optimise your participation in this hackathon, it is advised that:
* you have eduroam set up on your laptop
* you check are able to run python when away from your home institute
* you have some file space available
* you setup an environment with your favourite/most used python libraries, numpy, matplotlib and either keras/tensorflow and/or pytorch

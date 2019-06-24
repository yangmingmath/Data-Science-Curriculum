# Ming Yang's Data Science Curriculum


Table of Contents
=================

* [**Math**](#Math)
  * [**Calculus**](#Calculus)
  * [**Linear Algebra**](#Linear-Algebra)
* [**Statistics/Probability Theory**](#Statistics-Probability-Theory)
  * [**General**](#General-Statistics)
  * [**Bayesian**](#Bayesian)
  * [**Advanced**](#Advanced-Statistics)
    * [**Statistical Learning Theory**](#Statistical-Learning-Theory)
    * [**Theory of Probability**](#Theory-of-Probability)
* [**Algorithms**](#Algorithms)
* [**Machine Learning/Artificial Intelligence**](#Machine-Learning-Artificial-Intelligence)
  * [**General**](#General-Machine-Learning)
  * [**Advanced**](#Advanced-Machine-Learning)
    * [**Deep Learning**](#Deep-Learning)
* [**Other Topics**](#Other-Topics)
  * [**Big Data**](#Big-Data)
  * [**Advanced**](#Advanced-Other-Topics)
    * [**Optimization**](#Optimization)
    * [**Digital Signal Processing**](#Digital-Signal-Processing)

Curriculum
==========
  * <a name="Calculus"></a>**Calculus**
      * Textbooks
          * [Calculus, Vol. 1: One-Variable Calculus, with an Introduction to Linear Algebra](http://www.wiley.com/WileyCDA/WileyTitle/productCd-EHEP001951.html) (Apostol) - Apostol's textbooks are classics for a reason. They are a great introduction to calculus and do an excellent job of developing intuition for limits, derivatives, and integrals.
          * [Calculus, Vol. 2: Multi-Variable Calculus and Linear Algebra with Applications to Differential Equations and Probability](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0471000078.html) (Apostol)
  * <a name="Linear-Algebra"></a>**Linear Algebra**
      * Textbooks
          * [Linear Algebra and Its Applications](http://www.cengage.com/search/productOverview.do?N=16+4294922413+4294952008) (Strang) - linear algebra is probably my favorite math course. There is a lot of geometric intuition that is really satisfying, and the fact that linear algebra has tons of applications today doesn't hurt. Strang is a great teacher and writer, and his texts are classics for a reason.
          * [Linear Algebra Done Right](http://linear.axler.net/) (Axler)
  * <a name="Advanced-Math"></a>**Advanced**
      * These subjects are only necessary for those who want to achieve a deeper understanding of the math behind machine learning/probability.
      * <a name="Analysis"></a>**Analysis**
        * Textbooks
            * [Principles of Mathematical Analysis](http://www.mheducation.com/highered/product/principles-mathematical-analysis-rudin/007054235X.html) (Rudin) - analysis delves into the "why" of math and does so by deriving the existence of various mathematical concepts (e.g., the real and complex numbers, differentiation) from very simple initial building blocks (i.e., sets, addition, multiplication, and limits). Like abstract algebra, it is an interesting subject, but it's probably only practically relevant to individuals pursuing math-y subjects at higher levels. Subjects that use some analysis for derivations/proofs will generally provide the necessary background.

* <a name="Statistics-Probability-Theory"></a>**Statistics/Probability Theory**
  * <a name="General-Statistics"></a>**General**
      * Textbooks
          * [All of Statistics: A Concise Course in Statistical Inference](http://www.stat.cmu.edu/~larry/all-of-statistics/) (Wasserman)
          * [OpenIntro Statistics](https://www.openintro.org/stat/index.php) (free!)
          * [Causal Inference](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/) (HernÃ¡n and Robins) (draft: free!)
          * [Forecasting: Principles and Practice](https://otexts.org/fpp2/) (Hyndman and Athanasopoulos) (free!)
          * [Probability Theory: The Logic of Science](http://www.cambridge.org/gh/academic/subjects/physics/theoretical-physics-and-mathematical-physics/probability-theory-logic-science?format=HB&isbn=9780521592710) (Jaynes) (draft: free!)
      * Courses
          * [18.440: Probability and Random Variables](https://ocw.mit.edu/courses/mathematics/18-440-probability-and-random-variables-spring-2014/index.htm) (MIT)
  * <a name="Bayesian"></a>**Bayesian**
      * Textbooks
          * [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/) (Gelman et al.)
          * [Doing Bayesian Data Analysis: A Tutorial with R, JAGS, and Stan](https://sites.google.com/site/doingbayesiandataanalysis/) (Kruschke)
          * [Think Bayes](http://www.greenteapress.com/thinkbayes/) (Downey) (free!)
          * [Probabilistic Programming & Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) (Davidson-Pilon) (free!)
          * [Data Analysis Using Regression and Multilevel-Hierarchical Models](http://www.stat.columbia.edu/~gelman/arm/) (Gelman and Hill)
  * <a name="Advanced-Statistics"></a>**Advanced**
    * <a name="Statistical-Learning-Theory"></a>**Statistical Learning Theory**
      * Textbooks
          * [Statistical Learning Theory](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0471030031.html) (Vapnik)
    * <a name="Theory-of-Probability"></a>**Theory of Probability**
      * Courses
        * [18.175: Theory of Probability](http://math.mit.edu/~sheffield/fall2016math175.html) (MIT)
* <a name="Econometrics"></a>**Econometrics**
    * I used to have the "Econometrics" section below the "Other" section, but I decided to move it here because I've come to the conclusion that thinking like an economist is one of the most valuable skills a data scientist can have. Economists, like data scientists, often work with [observational data](https://en.wikipedia.org/wiki/Observational_study), which can make estimating the causal effect of any particular [intervention](https://plato.stanford.edu/entries/causation-mani/#Inte) rather challenging. As a result, economists tend to be *very* careful when using models to investigate causalityâ€”a skill that is sometimes [underrated by those in the data science community](https://www.linkedin.com/pulse/linear-models-actually-easily-interpretable-michael-a-alcorn).
    * Textbooks
        * [Mostly Harmless Econometrics: An Empiricist's Companion](http://www.mostlyharmlesseconometrics.com/) (Angrist and Pischke)
        * [Introductory Econometrics: A Modern Approach](https://www.cengage.com/c/introductory-econometrics-a-modern-approach-6e-wooldridge/9781305270107) (Wooldridge)
        * [Econonmetric Analayis of Cross Section and Panel Data](https://mitpress.mit.edu/books/econometric-analysis-cross-section-and-panel-data-second-edition) (Wooldridge)
        * [Econometric Analysis](http://pages.stern.nyu.edu/~wgreene/Text/econometricanalysis.htm) (Greene)
        * [Econometrics](http://press.princeton.edu/titles/6946.html) (Hayashi)
        * [Fundamental Mathematics of Mathematical Economics](http://www.amazon.com/Fundamental-Methods-Mathematical-Economics-Wainwright/dp/0070109109) (Wainwright and Chang)
    * Courses
        * [Applied Econometrics](http://people.stern.nyu.edu/wgreene/Econometrics/Econometrics.htm) (New York University)
        * [Econometric Analysis of Panel Data](http://people.stern.nyu.edu/wgreene/Econometrics/PanelDataEconometrics.htm) (New York University)
        * [Undergraduate Course](https://www.youtube.com/watch?v=M_5SLG7sUa0&list=PLwJRxp3blEvZyQBTTOMFRP_TDaSdly3gU)
        * [Graduate Course](https://www.youtube.com/watch?v=GMVh02WGhoc&list=PLwJRxp3blEvaxmHgI2iOzNP6KGLSyd4dz)
        * [Mathematical Methods for Economic Theory](http://mjo.osborne.economics.utoronto.ca/index.php/tutorial/index/1/int/i) (University of Toronto)
* <a name="Algorithms"></a>**Algorithms**
  * Textbooks
      * [Introduction to Algorithms](https://mitpress.mit.edu/books/introduction-algorithms) (Cormen et al.)
  * Courses
      * [Algorithms Specialization](https://www.coursera.org/browse/computer-science/algorithms) (Coursera)
      * [Bioinformatics Specialization](https://www.coursera.org/specializations/bioinformatics) (Coursera) - while the subject matter might not be relevant to everyone, I think most computer scientists would benefit from taking this course as it really gets you thinking about efficient algorithms in a real world context.
* <a name="Machine-Learning-Artificial-Intelligence"></a>**Machine Learning/Artificial Intelligence**
  * <a name="General-Machine-Learning"></a>**General**
      * Textbooks
          * [Pattern Recognition and Machine Learning](http://research.microsoft.com/en-us/um/people/cmbishop/prml/) (Bishop)
          * [Machine Learning: A Probabilistic Perspective](http://www.cs.ubc.ca/~murphyk/MLbook/) (Murphy)
          * [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (James et al.)
          * [Machine Learning](http://www.cs.cmu.edu/~tom/mlbook.html) (Mitchell)
          * [Advanced Data Analysis from an Elementary Point of View](http://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/) (Shalizi) (draft: free!)
          * [The Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/) (Hastie, Tibshirani, and Friedman) (free!)
          * [Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/) (Russell and Norvig)
      * Courses
          * [Machine Learning](https://www.udacity.com/course/machine-learning--ud262) (Udacity)
          * [Machine Learning](https://www.coursera.org/learn/machine-learning) (Coursera)
          * [Learning From Data](https://www.edx.org/course/learning-data-introductory-machine-caltechx-cs1156x-0) (edX) - warning: this one is more on the theoretical side.
          * [Artificial Intelligence for Robotics](https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373) (Udacity)
          * [Artificial Intelligence](https://www.edx.org/course/artificial-intelligence-uc-berkeleyx-cs188-1x) (edX)
  * <a name="Natural-Language-Processing"></a>**Natural Language Processing**
      * Textbooks
          * [Foundations of Statistical Natural Language Processing](http://nlp.stanford.edu/fsnlp/) (Manning and SchÃ¼tze)
          * [Speech and Language Processing](http://www.cs.colorado.edu/~martin/slp.html) (Jurafsky and Martin)
      * Courses
          * [Natural Language Processing](https://www.coursera.org/course/nlangp) (Coursera) - no longer offered. Course notes available [here](http://www.cs.columbia.edu/~mcollins/notes-spring2013.html).
          * [Natural Language Processing](https://www.coursera.org/course/nlp) (Coursera) (different one) - no longer offered on Coursera, but can be found on [the professor's website](https://web.stanford.edu/~jurafsky/NLPCourseraSlides.html).
          * [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/) (Stanford)
  * <a name="Advanced-Machine-Learning"></a>**Advanced**
    * <a name="Deep-Learning"></a>**Deep Learning**
        * Textbooks
            * [Deep Learning](http://www.deeplearningbook.org) (Goodfellow, Bengio, and Courville) (draft: free!)
            * [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) (Nielsen) (free!)
  
* <a name="Other-Topics"></a>**Other Topics**
  * <a name="Big-Data"></a>**Big Data**
      * Textbooks
          * [Mining of Massive Datasets](http://www.mmds.org/) (Leskovec et al.) (free!)
  * <a name="Advanced-Other-Topics"></a>**Advanced**
    * <a name="Optimization"></a>**Optimization**
        * Textbooks
          * [An Introduction to Numerical Analysis](http://www.cambridge.org/gh/academic/subjects/mathematics/numerical-analysis/introduction-numerical-analysis-1?format=PB) (SÃ¼li and Mayers) - my first [applied math](https://en.wikipedia.org/wiki/Applied_mathematics) subject, it felt like a continuation of linear algebra (in fact, there was a fair amount of overlap). Probably not necessary unless you see yourself implementing numerical solvers in the future.
          * [Convex Optimization](http://web.stanford.edu/~boyd/cvxbook/) (Boyd and Vandenberghe) (free!)
        * Courses
          * [Convex Optimization](https://lagunita.stanford.edu/courses/Engineering/CVX101/Winter2014/about) (Stanford Online)
          * [Machine Learning 10-725: Convex Optimization](http://www.stat.cmu.edu/~ryantibs/convexopt/) (Carnegie Mellon University)
    * <a name="Digital-Signal-Processing"></a>**Digital Signal Processing**
        * Textbooks
          * [Discrete-Time Signal Processing](https://www.pearsonhighered.com/program/Oppenheim-Discrete-Time-Signal-Processing-3rd-Edition/PGM212808.html) (Oppenheim and Schafer)
          * [Foundations of Signal Processing](http://www.fourierandwavelets.org/) (Vetterli, KovaÄeviÄ‡, and Goyal) (draft: free!)
        * Courses
          * [Digital Signal Processing](https://www.coursera.org/learn/dsp) (Coursera)


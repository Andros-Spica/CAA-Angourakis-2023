# Simulation in the age of machine learning
Presentation for CAA 2023 Annual Meeting in Amsterdam (3-6 April 2023).

CAA Annual Meeting 2023 page: https://2023.caaconference.org/

Prepared with reveal.js (see https://revealjs.com/)

Slides: https://andros-spica.github.io/CAA-Angourakis-2023/

**_Author_**

Andreas Angourakis

**_Abstract_**

*Context*

Simulation is a methodological approach that aims to improve our knowledge about real-world phenomena through experimentation on mathematical models as similes. In contrast to other mathematical models, such as those used in statistics, simulation models are designed to reproduce patterns and trends in empirical data not directly but as outcomes of postulated mechanisms under controlled conditions. While other mathematical models may involve explanations, the conjecture of causality remain outside the model formulation and will be used solely to justify or interpret their formal design. Simulation models, on the other hand, are themselves formal definitions of causal relationships, sitting in-between datasets and theory. In this sense, the many varieties of simulation are often referred to as process-based or explanatory modelling, in contrast to approaches that are data-based or descriptive, among which machine learning (ML) is currently the most promising. In terms of practice, simulation modellers take on different tasks than those of data scientists, as the workflow of the former require a model to be defined with precision, and then exploring a wide range of inputs and outputs, whereas the latter demand that the input and output is given to define a model.  

*Main argument*

The digitalisation of statistics and the increasing computational complexity in data science has pushed simulation modelling to become a rather separate and somewhat niche community of practice. In some circles and disciplines, simulation is even regarded as a lesser and weaker methodology, given its relatively freedom towards empirical data (Winsberg 2010). However, once the differences between simulation and statistical inference are well understood, together with their strengths and limits, we can go beyond the misperception of a methodological opposition.

Regarding ML, there are many opportunities for exchange and combination that hold the potential for revolutionising our approach to scientific problems (von Rueden et al. 2020). The aim of this paper is to raise awareness of the possibilities explored or still to explore, organising them according to their role in both simulation and ML workflows, and showcasing a selection of examples of applications in archaeology and beyond:

- Simulation for ML:
  - Simulation for the creation of training datasets 
  - Simulation models as ML hypothesis set
  - Simulation models as learning algorithms
  - Simulation for validation of final ML hypothesis
- ML for simulation:
  - ML for model generation
  - ML for model selection (e.g., Carrignon, Brughmans, and Romanowska 2020)
  - ML for surrogate model generation
  - ML for preprocessing or selecting input data
  - ML for pattern detection in simulation output
  - ML for parameter calibration and optimisation
  - ML as simulation model component

*Implications*

These and other areas of applications are not only promising for simulation and ML studies separately but carry the possibility of inaugurating a new scientific methodology, able to treat complex problems that otherwise would have been avoided as intractable or even unsolvable. As the simulation of social and socio-ecological processes are applied to archaeology and history, such a revolution could in fact make of this approach, if not a time machine, something perhaps better: a what-if machine, informed by both consolidated human knowledge and the data of numerous generations of humans in the past.
The benefits of artificial intelligence to the achievement of the UN Global Goals remain to this day mainly instrumental, as an approach that generally makes certain analytical processes more effective and faster. That is because of the characteristic semantic void behind the mathematical formulation of ML so far. However, the further combination with simulation may be able to fill this gap in the near future, helping the more consciously exploration of the solution space lying beyond the immediate imagination of current societies.

*References*

> Carrignon, Simon, Tom Brughmans, and Iza Romanowska. 2020. ‘Tableware Trade in the Roman East: Exploring Cultural and Economic Transmission with Agent-Based Modelling and Approximate Bayesian Computation’. Edited by Sergi Lozano. PLOS ONE 15 (11): e0240414. https://doi.org/10.1371/journal.pone.0240414.

> Rueden, Laura von, Sebastian Mayer, Rafet Sifa, Christian Bauckhage, and Jochen Garcke. 2020. ‘Combining Machine Learning and Simulation to a Hybrid Modelling Approach: Current and Future Directions’. In Advances in Intelligent Data Analysis XVIII, edited by Michael R. Berthold, Ad Feelders, and Georg Krempl, 12080:548–60. Lecture Notes in Computer Science. Cham: Springer International Publishing. https://doi.org/10.1007/978-3-030-44584-3_43.

> Winsberg, Eric. 2010. Science in the Age of Computer Simulation. University of Chicago Press. https://doi.org/10.7208/chicago/9780226902050.001.0001.


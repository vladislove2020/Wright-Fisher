# Wright-Fisher
This Google Colab provides a python code for Wright-Fisher modelling of genetic drift

Genetic drift is an effect of fast elimination or fixation of some genetic polymorphism, either adaptive or slight inadaptive, due to small population size and stochastic nature of reproduction

This code provides an illustration of this effect.
You can change some parameters: 
- selectivity coefficient s range (s_min, s_max, step)
- population size (N)
- number of replicas per every s value (num_iterations_per_s)

As a result, you can visualize how does the probability of a single once happened mutation to be fixed in a population of provided size change depending on its selectivity coefficient

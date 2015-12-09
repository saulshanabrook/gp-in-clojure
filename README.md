# gp-in-clojure

Search in Clojure...

## Problem Goals

Should support:

* Push
* [evolutionary algorithms](https://en.wikipedia.org/wiki/Evolutionary_algorithm)
* hill climbing
* random chance
* [differential evolution](https://en.wikipedia.org/wiki/Differential_evolution)
* [cuckoo search](https://en.wikipedia.org/wiki/Cuckoo_search)

Maybe a generalized library for
[metaheuristic optimization](http://www.scholarpedia.org/article/Metaheuristic_Optimization)?


### Why should we have one library for all of these?

It would allow us to easily compare different methods on
the same input problem to understand their strengths 
and weaknesses easily.

Since we are using Push, it makes the most sense to design
around strategies we can use Push with.

However, over generalization can be risky because it can 
get more confusing.

### What libraries are similar?

* [inspyred](https://pythonhosted.org/inspyred/overview.html) 
* [cilib](https://github.com/cirg-up/cilib)
* [PradisEO](http://paradiseo.gforge.inria.fr/index.php) ([docs](http://paradiseo.gforge.inria.fr/addon/eo/doc/index.html))
* [tensorflow](https://www.tensorflow.org/) seems interesting because it is proven. It runs production ML at Google and 
  also seems to be well documented. Interop w/ clojure might be possible, by going going from c++ -> java -> clojure, but that would probably be more trouble than its worth.


## Implementation Goals

Should have:

* customizable output/logs so you can save results easily
* correct style
* idiomatic code
* complete test suite
* feature parity with Clojush
* Easy to mix/match different strategies/problems

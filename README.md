# gp-in-clojure

Search in Clojure...

## Goals

Should support:

* Push
* [evolutionary algorithms](https://en.wikipedia.org/wiki/Evolutionary_algorithm)
* hill climbing
* random chance
* [differential evolution](https://en.wikipedia.org/wiki/Differential_evolution)
* [cuckoo search](https://en.wikipedia.org/wiki/Cuckoo_search)

Basically a generalized library for
[metaheuristic optimization](http://www.scholarpedia.org/article/Metaheuristic_Optimization)
in Clojure.


### Why should we have one library for all of these?

It would allow us to easily compare different methods on
the same input problem to understand their strengths 
and weaknesses easily.


Since we are using Push, it makes the most sense to design
around strategies we can use Push with.



### Meta

Should have:

* customizable output/logs so you can save results easily
* correct style
* idiomatic code
* complete test suite
* feature parity with Clojush

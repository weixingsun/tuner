# A Bayes Optimization Tool

The purpose of developing this tool is provide a method to tune various workloads by using Gaussian Process & Bayesian Optimization


Python version [HyperOpt](https://github.com/hyperopt/hyperopt) is ready, 
C++ version still developing [Limbo](https://github.com/resibots/limbo) / [bayesopt](https://github.com/rmcantin/bayesopt) version.


One scenario to standalone app:
1. monitor memory bandwidth: change the bios [options](https://github.com/weixingsun/tuner/blob/master/cfg/bios.json) (over rebooting)
2. monitor benchmark score:  change the java [options](https://github.com/weixingsun/tuner/blob/master/cfg/java.json) (re-launching)
3. monitor training duration: change the DL [hyperparameters](https://github.com/weixingsun/tuner/blob/master/cfg/deep_learning.json) (re-launching)
4. monitor LLC miss rate.  search space: the nested-loop order, array size,,,


Another scenario is integrate with [jbprof](https://github.com/weixingsun/jbprof) to mornitor the latency / counter of a java function:
1. change thread number
2. change java.static_variable
3. execute java.method
...

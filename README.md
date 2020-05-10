# A Bayes Optimization Tool

The purpose of developing this tool is provide a method to tune various workloads by using Gaussian Process & Bayesian Optimization


[HyperOpt](https://github.com/hyperopt/hyperopt) version is ready, and still developing [Limbo](https://github.com/resibots/limbo) version.

One scenario is integrate with [jbprof](https://github.com/weixingsun/jbprof) to mornitor the latency / counter of a java function:
1. change thread number
2. change java.static_variable
3. change nested-loop order
4. execute java.method

# GeneralizedDispersionProblem
Max-Min Dispersion with Capacity and Cost for a Practical Location Problem
Diversity and dispersion problems deal with selecting a subset of elements from a given set in such a way that their diversity is maximized. This study considers a practical location problem recently proposed in the context of max-min dispersion models. It is called the generalized dispersion problem, and it models realistic applications by introducing capacity and cost constraints. We propose two effective linear formulations for this problem, and develop a hybrid metaheuristic algorithm based on the variable neighborhood search methodology, to solve real instances. Extensive numerical computational experiments are performed to compare our hybrid metaheuristic with the state-of-art heuristic, and with integer linear programming formulations (ILP). Results on public benchmark instances show the superiority of our proposal with respect to the previous algorithms. Our extensive experimentation reveals that ILP models are able to optimally solve medium-size instances with the Gurobi optimizer, although metaheuristics outperform ILP both in running time and quality in large-size instances.

Paper link: https://www.sciencedirect.com/science/article/pii/S0957417421001445

Datasets
GDP Instances
USCAP real instance
All txt format instances can be found in instances folder.

Executable
You can just run the GDP.jar as follows.
<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
java -jar GDP.jar "FOLDER_WITH_INSTANCES"

java -jar GDP.jar instances/USCAP
    </div>
  </foreignObject>
</svg>

If you want new instances just replace folder instances.

Solutions
Solution folder contains an excel with the results and a folder with each solution per instance.




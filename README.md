CAIM with Frequency Analisys
=====

A modification of Python implementation of *Class-attribute interdependence maximization* algorithm<sup>1</sup> provided by https://github.com/airysen (https://github.com/airysen/caimcaim). This implementation was made for cluster description with *CAIBAL - Cluster-Attribute Interdependency Based Automatic Labeler* <sup>2</sup> and implements:
   - low frequency verification criteria for candidate cut points <sup>3</sup>;
   - changes the condition to accept a cut point for discretization intervals (CAIM > GlobalCAIM **and** K<S);
   - correct show cut points intervals values.

Reference
----------
[1] *"L. A. Kurgan and K. J. Cios (2004), CAIM discretization algorithm, in IEEE Transactions on Knowledge and Data Engineering, vol. 16, no. 2, pp. 145-153, Feb. 2004. doi: 10.1109/TKDE.2004.1269594"*
[http://ieeexplore.ieee.org/document/1269594](http://ieeexplore.ieee.org/document/1269594)

[2] *"Marcel Moura, Rodrigo Veras, and Vinicius Machado. 2022. CAIBAL: cluster-attribute interdependency based automatic labeler. In Proceedings of the 37th ACM/SIGAPP Symposium on Applied Computing (SAC '22). Association for Computing Machinery, New York, NY, USA, 1109–1116. https://doi.org/10.1145/3477314.3507140"*
[https://dl.acm.org/doi/abs/10.1145/3477314.3507140](https://dl.acm.org/doi/abs/10.1145/3477314.3507140)

[3] *"Rahman, Md Geaur & Islam, Md. (2015). Discretization of continuous attributes through low frequency numerical values and attribute interdependency. Expert Systems with Applications. 45. 10.1016/j.eswa.2015.10.005"*
[https://www.researchgate.net/publication/284014628_Discretization_of_continuous_attributes_through_low_frequency_numerical_values_and_attribute_interdependency](https://www.researchgate.net/publication/284014628_Discretization_of_continuous_attributes_through_low_frequency_numerical_values_and_attribute_interdependency)

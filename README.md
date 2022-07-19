# Dutch Energy System Dynamics Models

This repository contains sketches for a high-level energy system design for the Netherlands. It contains a currated dataset for the most important parameters of the system. The system itself is build using [AlgebraicJulia](https://github.com/AlgebraicJuliai) and [Vensim](https://vensim.com), a category theoretic library for  scientific computing.

The following exemplary policy interventions are included:
- `stockFlow_e_sector_policy1.vpmx`: Reduce investment in non-renewable sources after `n` months in a incremental or abrupt fashion.
- `stockFlow_e_sector_policy2.vpmx`: Increase construction delay of non-renewable sources due to, e.g., increased societal opposition.
- `stockFlow_e_sector_policy3.vpmx`: Increase motivation to invest into renewable sources by lowering the minimum expected return.



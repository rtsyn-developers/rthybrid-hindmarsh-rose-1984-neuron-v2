# RTHybrid Hindmarsh-Rose 1984 Neuron v2

Hindmarsh-Rose 1984 neuron model integrated with RK4.

This is a C RTSyn module ported from the older RTHybrid RTSyn plugin tree. Load the module by selecting this
repository's `xmake.lua`; the RTSyn module loader will build the shared library and load the descriptor.

## Build

```sh
xmake f -c -y
xmake
```

## Please, if you use RTHybrid or RTHybrid modules for RTXI, cite the following papers:

Amaducci, R., Reyes-Sanchez, M., Elices, I., Rodriguez, F.B., & Varona, P. (2019). RTHybrid: a standardized and open-source real-time software model library for experimental neuroscience. Frontiers in Neuroinformatics, 13, 11. https://doi.org/10.3389/fninf.2019.00011

Reyes-Sanchez, M., Amaducci, R., Elices, I., Rodriguez, F. B., & Varona, P. (2020). Automatic adaptation of model neurons and connections to build hybrid circuits with living networks. Neuroinformatics 18: 377–393. https://doi.org/10.1007/s12021-019-09440-z

## Links

[Grupo de Neurocomputación Biológica (GNB)](http://arantxa.ii.uam.es/~gnb/)

[Escuela Politécnica Superior (EPS)](http://www.uam.es/ss/Satellite/EscuelaPolitecnica/es/home.htm)

[Universidad Autónoma de Madrid (UAM)](http://www.uam.es)

# Synergistic-reinforcement-learning-by-cooperation-of-the-cerebellum-and-basal-ganglia
Tatsumi Yoshida, Hikaru Sugino, Hinako Yamamoto, Sho Tanno, Mikihide Tamura, Jun Igarashi,  Yoshikazu Isomura,  Riichiro Hira
doi: https://doi.org/10.1101/2024.07.12.603330

# Dependencies

The code depends on the neuron simulator Brian2.  
Installation instructions for Window OS is available in the official documentation:

https://brian2.readthedocs.io/en/stable/introduction/install.html#

Brian2 has the following minimal requirements:

Python >=3.7

Brian2 can then be installed with:

```
conda install -c conda-forge brian2
```

# Simulations
The code in the folder ```code/``` contains the neural network model of basal ganglia, cerebellum and thalamus.

Charactersitics of the input can be changed at the beginning of ```spiking_neural_network_model.py.```

We commented out the lines to record parameters at the end of this code so that this code does not record any parameters by default.  
Please remove comment out from any parameter you want to monitor

The code has been tested on Windows 11 Pro, using python 3.9 and 3.8 and Brain2 version 2.7.1. We cannot assure that it will work on other versions.

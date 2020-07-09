# Abstract
A greenhouse is build based on calculations regarding the thermal processes. A configuration tool is used to define the dimensions. Temperature and irradiance data measured over a period of three weeks is compared to the calculated values. The resulting plots of measured vs. calculated temperatures show similar behaviour, but deviations in the greenhouse temperature peaks, e.g. due to constructive differences and simplified thermal processes. The interactive configurator is published as an open source tool and the greenhouse is built with sustainable components.


![](graphics/SolarThermalColdframe_header.png)  

Fig. 1: Greenhouse

# Motivation & Goals

* Extended growing period for vegetable plants in Germany
* Low budget components
* Low impact materials
* Solar energy driven
* Configurator tool for easy reconstruction based on a thermal model

# Thermal Model

![](graphics/HeatTransferMechanisms.png) 
Fig.2: Heat transfer mechanisms:
<span style="color:darkblue">convection</span>,
<span style="color:darkred">conduction</span> and
<span style="color:orange">radiation</span>.
![](graphics/ThermalNetwork.png) 
Fig.3: Thermal Network

# Interactive Jupyter Notebook

![](graphics/FlowChart.png) 
Fig.4: Flow Chart

![](graphics/UserInterfaceNotebook.png) 
Fig.5: User Interface of the configurator

You can try it online:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Taubenstrohhalm/SolarThermalColdframe/master)
# Evaluation & Conclusion
![](graphics/temp_gh_v2.png)
![](graphics/temp_storage_v2.png) 
Fig.6: Measured data vs. calculated values

Deviations between model and measurement due to
* Constructive differences (e.g. geometry, material parameters)
* Neglected / uncertain thermal processes (e.g. thermal mass of construction material, ventilation number)
* Approximated irradiance measurement  

Achievement 
* Solar greenhouse with sustainable component acquisition
* Interactive configurator tool (Jupyter notebook) available on:
     https://github.com/Taubenstrohhalm/SolarThermalColdframe





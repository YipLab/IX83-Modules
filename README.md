# IX83-Modules

Modules enable different microscopy techniques to be applied on the same optical system. Modules are inserted into designated modular spaces the IX83 system. Detailed description of the modules can be found in their respective folders.


![System Schematic](https://github.com/YipLab/IX83-Modules/blob/master/images/schematic.png)


The system has 4 free spaced lasers that are aligned using a laser combiner. The beam profile can be manipulated in to modular exciation areas(Mod_Ex). The beam is then expanded and focused to the back focal plane of the objective.

There are two modular emission areas(Mod_Em), this permits image manipulation before it is acquired by the camera. Mod_Em1 is the second deck in a dual deck IX83 microscope body. The second is space between the microscope body and the camera.

## Components

### Lasers
405 Laser | Coherent Cube 405 nm 25 mW  
488 Laser | Coherent Sapphire 488 nm 200 mW  
561 Laser | Laser Quantum GEM 561 nm 200 mW  
647 Laser | Laser Glow 647 nm 200 mW  

### Optics
L1 | Achromatic Doublet f = 30 mm ([AC254-030-A-ML](https://www.thorlabs.com/thorproduct.cfm?partnumber=AC254-030-A-ML))    
L2 | Achromatic Doublet f = 250 mm ([AC254-250-A-ML](https://www.thorlabs.com/thorproduct.cfm?partnumber=AC254-250-A-ML))  
L3 | Achromatic Doublet f = 300 mm ([AC254-300-A-ML](https://www.thorlabs.com/thorproduct.cfm?partnumber=AC254-300-A-ML))  
IX83 | Olympus IX83 Dual Deck

### Objectives
5x | LMPlanFLN 5x/0.13  
10x | UPlanFl 10x/0.30  
20x | LCPlanFl 20x/0.40  
40x | LCPlanFl 40x/0.60  
60x | PlanApo 60x/1.4 Oil  
100x | UApoN 100x/1.49 Oil  

### Camera
CAM | Photometrics Prime BSI sCMOS

### Software
Micromanager 1.4

## TODO:
* filter cube  
* software requirements
	*make folder
	*shutter code, laser control code, micromanager config
* license


# Energy-Harvesting-Backpack
An Efficient Design of an Energy Harvesting Backpack for Remote Applications

This repository contains the CAD model of a designed backpack as described in the paper (https://doi.org/10.1016/j.seta.2022.102173). The design was optimized using a genetic algorithm. In addition, a dynamic model of the backpack was created using the Simscape library in Simulink. To validate the Simscape model, the differential equations were derived, solved using MATLAB's ODE45 solver, and the results showed that the backpack performed at the state of the art level. A prototype of the optimized model was also manufactured for further testing and verification. The experimental results using manufactured backback were found to be in close agreement with the simulated results, demonstrating the accuracy of the model. 

Here is the picture of the backpack model

![Assem1 - Copy](https://user-images.githubusercontent.com/57262710/218341992-2602a50f-2bec-40ed-b079-639e4606b49a.JPG)
![figures](https://user-images.githubusercontent.com/57262710/218342868-dd039a72-9554-4732-b0f6-f9a7e781225e.png)

And this is the simulated dynamic model in Simulink using the powerful simscape library. This includes the mechanical section consisting of springs, rack and pinions and backpack load mass, and electrical parts such as generator and resistors.

![image](https://user-images.githubusercontent.com/57262710/218342362-1be1c8a5-ab66-49a1-9881-f95a3259303e.png)

Furthemore, pictures below show the prototype of the backpack

![image](https://user-images.githubusercontent.com/57262710/218343249-64d6b628-19b4-42a3-a791-7464cc32917c.png)
![image](https://user-images.githubusercontent.com/57262710/218343257-ba1db95e-1ade-4b17-8daa-c9056ac7bd28.png)





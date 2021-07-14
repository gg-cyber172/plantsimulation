# plantsimulation
Created with [@Nevan Oman Crowe]( https://github.com/Branchman577 ) for our Third Year project.  
The concept of this project was to simulate how plants grow, compete and reproduce over limited resources and space. Along with this we created a UI that shows you a timelapse of what happened.  
  
At the start of the simulation the user can decide how big the board/living space will be and how many plants start off on it. Each board starts off with resources scattered around it randomly, with the initial plant seedlings being planted in the top 2 layers.  
Each resource is finite and can be drained dry by the plants. The only way the resources can be replenished is when a plant dies it has a chance of turning into a new resource deposit.  
  
Each plant also has "genes" that determined the characteristics of each plant. Their genes determine how much of each resources it needs per it's size, how fast it can grow to reach new resources, how long till it reaches maturity, and finally how aggressively it passes on it's genes. When a plant reproduces it first finds a mate, when it finds one depending on it's aggressiveness level it passes a certain portion of its characteristics to it's children.  
  
The project was made in Java and JavaScript. It used the library DESMOJ for the simulation and 3.js for the UI. 

# Maze Solver
Exploring MDP solving algorithms with mazes!

****

## Introduction:
We generate random maze and sovle using two basic algorithms for solving MDPs are value iteration
and policy iteration.
## Methods:
  **1. Value Iteration**
  
   The value iteration approach finds the optimal policy π* by calculating the optimal value
   function, V*. Starting with V(s) = 0 for all states s, the values of each state are iteratively
   updated to get the next value function V, which converges towards V*.
      
   <p align="center"><img src="visuals/viequation.png?raw=true" width="350" height="50"></p>
      
  **2. Policy Iteration**
  
   Starting with a random policy π<sub>0</sub> , this approach consists of two steps:
      
   I. Calculate the utilities of a non-optimal policy π<sub>i</sub>
            
   <p align="center"><img src="visuals/piequation1.png?raw=true" width="350" height="50"></p>
            
   II. Update the policy using the resulting converged utilities from the previous step to obtain π<sub>i+1</sub>.
            
   <p align="center"><img src="visuals/piequation2.png?raw=true" width="350" height="50"></p>
        
   These steps are repeated until π converges to π<sup>*</sup>
## Sample Run
Policy Iteration           |  Value Iteration          |  Scale
:-------------------------:|:-------------------------:|:-------------------------:
![Policy Iteration](visuals/pi_iterations_new.gif) |  ![Value Iteration](visuals/vi_iterations_new.gif) | ![scale](visuals/Scale.png)

## Authors

* **Mohamed Bakr** [MohamedBakrAli](https://github.com/MohamedBakrAli)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

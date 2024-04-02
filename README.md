**Motivation behind the project:**

Selecting the most influential variables is a fundamental challenge in developing accurate and 
interpretable predictive models. While penalized regression techniques like Lasso and Ridge 
regression have been widely used, they suffer from drawbacks including bias introduced by the 
penalty parameter. Meanwhile, optimization methods for direct variable selection have been long 
dismissed as computationally intractable. However, recent advances in mixed integer quadratic 
programming (MIQP) have made direct variable selection viable. This project marks an important 
milestone in realizing the full potential of optimization for predictive analytics.


By leveraging MIQP to encode variable selection decisions as binary variables, we can now 
optimize and directly identify the variables with maximum predictive power. The merits of this 
approach are multifold. First, it avoids biases and distortions created by penalty methods. Second, 
it provides inherent interpretability by extracting the optimal variable subset. Third, it allows 
incorporating predictive performance objectives directly into the optimization model. A key focus 
of this project is posing the variable selection problem for regression as an MIQP and solving it 
using Gurobi. This allows us to directly find the optimal subset of variables to include in the 
regression model.

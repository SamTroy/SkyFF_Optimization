# SkyFF_Optimization
A tool to help make decisions for Sky Fantasy Football

## Setting up
- Install python
- Add CBC to environment path (e.g. https://www.youtube.com/watch?v=DFXCXoR6Dvw&t=1642s)
- Install all packages in the Imports section of the notebook

## Running the solver
- Download FPL Review projections, and save the file in data folder as fplreview.csv (alternatively, produce your own set of expected minutes)
- Run import and function definition cells
- Generate model output using generate_model_output function
- Generate optimal solution using solve_sky_mp function

### Future plans
- Add a more context to the noise function
- Add a function to run the solver with multiple possible fixture permutations
- Perform experiments to get a better idea of what parameters and settings are best for the solver
- Refine player and team model
- Maintain player and team model, and refresh their data with each new set of matches
- Add a user interface to the solver to streamline the process

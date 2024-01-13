# SkyFF_Optimization
A tool to help make decisions for Sky Fantasy Football

Generates player expected points and transfer plan

Modifying player EV and xMins or using other sources to reflect your own judgment is encouraged

## Setting up
- Install python
- Add CBC to environment path
- Clone this repository to your machine
- Install all packages in the Imports section of the notebook

## Running the solver
- Download FPL Review projections, and save the file in data folder as fplreview.csv (alternatively produce your own set of expected minutes, or omit this step to use defaults)
- Run import and function definition cells
- Generate model output using generate_model_output function
- Generate optimal solution using solve_sky_mp function

### Acknowledgements and sources
- Team strength data (projected goals for and against) from Elevenify: https://elevenify.substack.com/
- All other team data and all player data derived from publicly available Opta stats
- Inspiration and guidance for the solver from Sertalp: https://github.com/sertalpbilal/FPL-Optimization-Tools
- Continuous feedback and collaboration with members of the fantasy football analytics community

### Future plans
- Periodically update player and team prior data
- Add a function to run the solver with multiple possible fixture permutations
- Perform experiments to get a better idea of what parameters and settings are best for the solver
- Add a user interface to the solver to streamline the process

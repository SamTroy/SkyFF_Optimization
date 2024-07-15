NOTE: With Sky Fantasy Football discontinued for the 24/25 season, development on this tool will cease and I will begin work for other fantasy games for the upcoming season

# SkyFF_Optimization
A tool to help make decisions for Sky Fantasy Football

Generates player expected points and transfer plan

Modifying player expected values and minutes (EV and xMins) or using other sources to reflect your own judgment is encouraged

## Setting up
- Install python
- Add CBC to environment path
- Clone this repository to your machine
- Install all packages in the Imports section of the notebook

## Running the solver
- For xMins purposes it is recommended to download FPL Review projections and save the file in data folder as "fplreview.csv". Alternatively, omit this step to use defaults or produce your own set of xMins
- Open the notebook and run import and function definition cells
- Generate model output using generate_model_output function
- Generate optimal solution using solve_sky_mp function

### Acknowledgements and sources
- Team strength data (projected goals for and against) used with permission from Elevenify: https://elevenify.substack.com/
- Other team and player data derived from publicly available statistics (primarily Opta) and market odds
- Inspiration and guidance for the solver framework from Sertalp: https://github.com/sertalpbilal/FPL-Optimization-Tools
- Continuous feedback and collaboration with members of the fantasy football analytics community

### Future plans
- Add a function to run sensitivity analysis with coherent noise and weighted fixture permutations
- Perform experiments to better inform what parameters and settings are best for the solver
- Add a user interface to the solver to streamline the process

# Stochastic Wheatfield Harvest Yield Simulation

## Project Description
This project is a stochastic simulation built in MATLAB that models the harvest yield of a wheat field over a 10-month growing season. The model incorporates real-world variables, including user-defined growth rates and random weather conditions, to predict the final harvest yield and provide a statistical report of the outcomes.

## Business Question
How does the chance of sunny weather impact the total harvest yield of a wheat field, and what is the expected variability in the final harvest?

## Methodology
The simulation uses a **stochastic modeling approach** to simulate a series of independent experiments. The program's core logic is as follows:
- **User Input:** The model requires a user to define the number of experiments, the monthly chance of sun, and the growth rates for both sunny and cloudy conditions.
- **Inner Loop:** For each experiment, the program simulates 10 months. In each monthly step, a random number generator determines if the weather is sunny or cloudy, which in turn influences the wheat population's growth rate.
- **Population Dynamics:** The wheat population is modeled based on a simple growth equation, with a fixed amount lost each month to a hypothetical pest, *Puccinia*.
- **Outer Loop:** The entire simulation is run multiple times (defined by the user) to generate a distribution of possible outcomes.

## Key Findings 

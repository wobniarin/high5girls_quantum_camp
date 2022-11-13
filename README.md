# high5girls_quantum_camp
Examples of code to be shown during the High5Girls camp hosted at DTU on the 18th and 19th of November, 2022. 

## Getting started 
### Part 1: Planning a meal 
Things to remember: 
1. Clone the repository 
2. Install requirements.txt 
3. Create an account at D-WAVE so that we get an API token to run the code. 
4. Run the following code on the terminal inside your virtual environment to create a configuration file: 
   1. `dwave  config create`
   2. This code will create a configuration file so that we can access the d-wave quantum computer. Remember to include the token from the website when creating this profile. 
   3. We can test that everything is set up correctly by running already prepared quantum code connected to D-Wave servers: 
      1. `dwave ping --client qpu`
      2. `dwave sample --random-problem`
   4. Useful link: https://docs.ocean.dwavesys.com/en/stable/overview/sapi.html#sapi-access
   5. Useful link 2: https://docs.ocean.dwavesys.com/en/stable/examples/hybrid_cqm_diet.html
### Part 2: Planning our hiking trip 
1. Useful links: https://github.com/dwave-examples/tour-planning    



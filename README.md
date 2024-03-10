> **Note**  
> This is a demo. Formal version will be released in the future

KMC simulations for the Pt catalyst under CO gas conditions.

There is a demo that can be executed in linux environment.

ini.xyz is a customizable input structure file, where initial structure can be a nanoparticles with any sizes and shapes.

The temperature and CO pressure can be defined in the file of input.

During simulaiton, the following files will be generated:

- last_one.xyz: Structure file of the final structure. The last column records the state of the site, where 0 means an empty surface site, 1 means a CO-occupied surface site, 5 means a buld site.
- atom_str_00.xyz: Structural evolution during the simulation, with a recording inteval of 50,000 steps.
- step_rec_00.dat: Time and event statistics during the simulation, with a recording inteval of 1000 steps. Each data column represents: time (s), Steps, number of atomic jumping events, number of CO adsorption events, number of CO desorption events, and number of CO diffusion events.
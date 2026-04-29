# middle_mile_fuel_distribution
This repository contains the files needed to simulate disruption scenarios in Southern California’s middle-mile fuel distribution network.

# Folder "Capacities":
This folder stores the capacity input files for refineries, ports, and terminals.

# Folder Inputs_and_model:
This folder stores the input files for the three tested scenarios, plus one additional scenario used as the baseline. To test a specific scenario, open the simulation.ipynb file and update the file path to point to the corresponding scenario spreadsheet.
All parameter changes are made directly in the spreadsheets, while the code only contains the simulation logic. This makes the model easily replicable for other networks by modifying the Excel input files, as long as the same input structure is maintained.
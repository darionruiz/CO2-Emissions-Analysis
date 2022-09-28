# CO2-Emissions-Analysis

***If you would just like to see the Q&As and the overall recommendations, it will be on the [Analysis Page](https://github.com/darionruiz/CO2-Emissions-Analysis/blob/personal_projects/Analysis.md).***

In this project, I go over 7 years worth of car and CO2 emissiond ata from the canada government website. The way it's outlined is I set the background, describe the data, then do my analysis followed by each question. At the end of the notebook, I have a review of the questions and recommendations the task of:

**What are some recommendations for guidelines on CO2 emissions rules?**

## Background
You volunteer for a public policy advocacy organization in Canada, and your colleague asked you to help her draft recommendations for guidelines on CO2 emissions rules. 

After researching emissions data for a wide range of Canadian vehicles, she would like you to investigate which vehicles produce lower emissions.

## The Data

### You have access to seven years of CO2 emissions data for Canadian vehicles ([source](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6)):

- ***Make*** - The company that manufactures the vehicle.
- ***Model*** - The vehicle's model.
- ***Vehicle Class*** - Vehicle class by utility, capacity, and weight.
- ***Engine Size(L)*** - The engine's displacement in liters.
- ***Cylinders*** - The number of cylinders.
- ***Transmission*** - The transmission type: A = Automatic, AM = Automatic Manual, AS = Automatic with select shift, AV = Continuously variable, M = Manual, 3 - 10 = the number of gears.
- ***Fuel Type*** - The fuel type: X = Regular gasoline, Z = Premium gasoline, D = Diesel, E = Ethanol (E85), N = natural gas.
- ***Fuel Consumption Comb (L/100 km)*** - Combined city/highway (55%/45%) fuel consumption in liters per 100 km (L/100 km).
- ***CO2 Emissions(g/km)*** - The tailpipe carbon dioxide emissions in grams per kilometer for combined city and highway driving. 

The data comes from the Government of Canada's open data [website](https://open.canada.ca/en).

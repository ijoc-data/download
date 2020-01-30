The repository contains the research data for monotone classification problems involving preference-ordered criteria (input variables) and classes (output variables). Each .csv file provides the notation, performances of alternatives on multiple criteria, and their assignments to the respective classes. All criteria are of gain type (greater values are more preferred) with performances normalized in the [0,1] interval. Greater class index indicates more preferred class (e.g., Cl2 is preferred to Cl1).

A brief description of the data sets is as follows:

Breast Cancer (BCC)  
Source: the UCI repository (https://archive.ics.uci.edu/ml/index.php) (originally from the University Medical Center, Institute of Oncology, Ljubljana, Yugoslavia (Slovenia))  
Number of alternatives: 278 (patients)  
Number of criteria: 7 (menopause gain, tumor size, inv-nodes, node-caps, deg-malig, breast cost, irradiat gain)  
Number of classes: 2 (output is a binary variable, namely no-recurrence-events and recurrence-events)

Car Evaluation (CEV)
Source: the UCI repository (https://archive.ics.uci.edu/ml/index.php) Number of alternatives: 1728 (cars)
Number of criteria: 6 (buying price, price of maintenance, number of doors, capacity in terms of persons to carry, the size of the luggage boot (g5), estimated safety of the car)
Number of classes: 3 (overall evaluation of the car: unacceptable, acceptable, or good)

CPU
Source: the UCI repository (https://archive.ics.uci.edu/ml/index.php)
Number of alternatives: 209 (CPUs)
Number of criteria: 6 (machine cycle time, minimum main memory, maximum main memory, cache memory, minimum channels, maximum channels)
Number of classes: 4 (the (estimated) relative performance of a CPU)

DenBosch (DBS)
Source: Daniels H, Kamp B (1999), Applications of MLP networks to bond rating and house pricing. Neural Computing & Applications 8(3):226–234.
Number of alternatives: 120 (houses in the city of Den Bosch)
Number of criteria: 8 (area, number of bedrooms, type of house, volume, storeys, type of garden, garage, price)
Number of classes: 2 (the output is a binary variable indicating whether the price of the house is low or high)

Employee Rejection/Acceptance (ERA)
Source: WEKA (https://www.cs.waikato.ac.nz/ml/weka/) (originally from an academic decision-making experiment)
Number of alternatives: 1000 (candidates for a certain type of job)
Number of criteria: 4 (features of a candidate such as past experience, verbal skills, etc.)
Number of classes: 3 (subjective judgment; degree to which applicant for the job would be accepted) 

Employee Selection (ESL)
Source: WEKA (https://www.cs.waikato.ac.nz/ml/weka/)
Number of alternatives: 488 (applicants for certain industrial jobs)
Number of criteria: 4 (scores based upon psychometric test results and interviews with the candidates)
Number of classes: 5 (degree of suitability of each candidate to this type of job)

Lecturers Evaluation (LEV)
Source: WEKA (https://www.cs.waikato.ac.nz/ml/weka/) 
Number of alternatives: 1000 (lecturer evaluations taken at the end of MBA courses)
Number of criteria: 4 (oral skills and contributions to their professional/general knowledge)
Number of classes: 4 (comprehensive evaluation of each lecturer’s performance)

Mammographic (MMG)
Source: the UCI repository (https://archive.ics.uci.edu/ml/index.php) 
Number of alternatives: 830 (patients evaluated in terms of breast cancer screening by mammography)
Number of criteria: 5 (BI-RADS assessment, age, mass shape, mass margin, density)
Number of classes: 2 (severity (benign or malignant))

Auto MPG (MPG)
Source: the UCI repository (https://archive.ics.uci.edu/ml/index.php) (originally from the 1983 American Statistical Association Exposition)
Number of alternatives: 392 (cars)
Number of criteria: 7 (mpg, cylinders, displacement, horsepower, weight, acceleration, model year)
Number of classes: 3 (city–cycle fuel consumption)

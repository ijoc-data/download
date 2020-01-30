This repository contains the research data for each monotone classification problem. Each .csv file provides the notation, the performance on multiple criteria, and the assignment for each alternative.

A brief description of the data sets is as follows:

DenBosch (DBS): This data set contains eight criteria describing houses in the city of Den Bosch: district, area, number of bedrooms, type of house, volume, storeys, type of garden, garage, and price. The output is a binary variable indicating whether the price of the house is low or high (depending on whether it exceeds a threshold).

CPU: This is a standard benchmark data set from the UCI repository. It contains eight input criteria, two of which were removed because they are obviously of no predictive value (vendor name, model name). The problem is to predict the (estimated) relative performance of a CPU (binarized by thresholding at the median) based on its machine cycle time in nanoseconds, minimum main memory in kilobytes, maximum main memory in kilobytes, cache memory in kilobytes, minimum channels in units, and maximum channels in units.

Breast Cancer (BCC): This data set was obtained from the University Medical Center, Institute of Oncology in Ljubljana, Yugoslavia. There are seven criteria, namely menopause gain, tumor size, inv-nodes, node-caps, deg-malig, breast cost and irradiat gain. The output is a binary variable, namely no recurrence events and recurrence events.

Auto MPG (MPG): This data set was used in the 1983 American Statistical Association Exposition. The criteria are mpg, cylinders, displacement, horsepower, weight, acceleration, model year, and origin. The data concerns city–cycle fuel consumption in miles per gallon to be predicted in terms of three multivalued discrete and five continuous criteria.

Employee Selection (ESL): This data set contains profiles of applicants for certain industrial jobs. The values of the four input criteria were determined by expert psychologists based upon psychometric test results and interviews with the candidates. The output is an overall score on an ordinal scale between one and five, corresponding to the degree of suitability of each candidate to this type of job.

Mammography (MMG): This data set is taken from breast cancer screening by mammography. The goal is to predict the severity (benign or malignant) of a mammographic mass lesion from BI-RADS criteria (mass shape, mass margin, density) and the patient’s age.

Employee Rejection/Acceptance (ERA): This data set originates from an academic decision-making experiment. The input criteria are features of a candidate, such as past experience, verbal skills, etc., and the output is the subjective judgement of a decision maker, measured on an ordinal scale from one to three, to which degree the decision maker tends to accept the applicant for the job.

Lecturers Evaluation (LEV): This data set contains examples of anonymous lecturer evaluations, taken at the end of MBA courses. Students were asked to score their lecturers according to four criteria, such as oral skills and contribution to their professional/general knowledge. The output was a total evaluation of each lecturer’s performance measured on an ordinal scale from zero to four.

Car Evaluation (CEV): This data set contains six criteria describing a car, namely buying price, price of maintenance, number of doors, capacity in terms of persons to carry, the size of the luggage boot, and estimated safety of the car. The output is the overall evaluation of the car: unacceptable, acceptable, or good.

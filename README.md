# 590PR Final_Project

# Title: 
Monte Carlo Simulation of Air Ticket Overselling

## Team Member(s):
Cong Xiang, Chin-Han Lin, Xuefeng Qin

# Monte Carlo Simulation Scenario & Purpose:
Airline Companies usually oversell tickets to maximize the profits of each scheduled flight because there is a probability that some passangers who booked ticktes will not take on the plane, overselling can raise the seat utiliaztion. However the exact number of overselling tickets is uncertain, which is very significant to be kept in a reasonable range. If overbooking numbers are not well controlled, it will lead to finance compensation and customer loss due to the absence of seats for excess passengers, or profit loss due to low seat utilization.

So in this model. we will simulate the real-world airline booking scenario based on Monte Carlo simulation principle to find out the best overbooking number range and purse the maximum profits for an airline company.

## Simulation's variables of uncertainty
We will take all the following variable into condiseration, which are related to the profits of a single airline flight.
#### The demand of a scheduled flight
#### The number of final show-up passengers 
#### The distribution of no-show passengers on different flight class (including business and economy)
#### The different finance compensation to excess passengers who do not have a seat 
#### The probability of no-show passengers who canceled the tickets before departure

tips:List and describe your simulation's variables of uncertainty (where you're using pseudo-random number generation). For each such variable, how did you decide the range and probability distribution to use?  Do you think it's a good representation of reality?

## Hypothesis or hypotheses before running the simulation:
We assume a certain airline(United Airlines) and a certain air route(Chicago to NewYork), so the types of airplanes and the cost of each seat can be confirmed. 
The hypothesis is that within a certain range, the profits will grow following the overbooking numbers' increasement. Then there is a peak to achieve the maximum profits, however the profits will begin to drop after the peak as the overselling keep increaing due to the compensation for the excess passengers.

## Analytical Summary of your findings: (e.g. Did you adjust the scenario based on previous simulation outcomes?  What are the management decisions one could make from your simulation's output, etc.)
The output of this program include a plot, a table and the optimizing result, which can show users how many tickets they should overbook to maximize the profit based on the certain flight type.

## Instructions on how to use the program:
The user will need to input the type of flight and other variables according to the reminder. And the program can figure out how many tickets the airline should overbook to maximize the profit.

## All Sources Used:
Oberstone, J. L. (2010). Spreadsheet Simulation of Airline Reservation Policy Using Multimedia Software. International Journal of Advanced Corporate Learning (iJAC), 3(1). doi:10.3991/ijac.v3i1.1169

Basa, G., & Kedir, A. (2017). Modeling and optimization of the single-leg multi-fare class overbooking problem. Momona Ethiopian Journal of Science, 9(2), 200. doi:10.4314/mejs.v9i2.5

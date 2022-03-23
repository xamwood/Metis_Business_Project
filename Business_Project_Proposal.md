# Business Project Proposal:

### Changing the New York EV Rebate Program 

#### Abstract

Herein I propose modeling sales of electric vehicles in New York to see what effect the New York electric vehicle rebate had. I am primarily concerned with seeing what impact the rebate had on sales of more efficient vehicles as the public benefits corporation providing the rebate’s stated goal is one of energy efficiency, but the rebate targeted increasing vehicle range. I collect data for New York's electric vehicle sales and preliminarily find the rebate is correlated with vehicle range, but not with vehicle efficiency.

#### Design

NYSERDA is a New York state public benefit corporation with the stated goals of helping New Yorkers increase energy efficiency, save money, use renewable energy, and reduce their reliance on fossil fuels. In 2017 NYSERDA started a point-of-sale rebate program for plug-in hybrid and fully electric vehicles that offered up to $2000 off of leasing or buying a new electric vehicle. The rebates given were based on the amount of distance a car could travel based on a single battery charge as well as the MSRP of the vehicle:

●   Greater than 200 miles: $2,000 off

●   40 to 199 miles: $1,000 off

●   Less than 40 miles: $500 off

●   Electric cars with MSRP >$42,000: $500 off

Since its introduction Electric Vehicle Sales in New York State have seen a steep increase in sales.

##### Question/Need:

Does New York's EV rebate eoncourage the sale of more efficient vehicles? Part of NYSERDA's stated mission is to 

##### Impact Hypothesis:

Knowing how the rebate is impacting sales will quantify the cost and benefit of the rebate and provide insight into how resutructuring the rebate could impact the sales of more efficient electric vehicles. 

##### Solutions Path:

I propose we create a simple linear regression to look at the effects the rebate has on number of sales of a particular vehicle model.

Target: Vehicle Sales Features of Interest: Rebate amount, Vehicle Range, Vehicle Efficiency

In addition to these features of interest we can look at other vehicle features such as size, cost, power, ect. to see how the features of interest compare. Furthermore, we can look at electric vehicle sales in other states without rebates, such as Illinois, to have a control for what vehicle sales might have been without the rebate in place. 

Once we have a good handle on the impact the rebate has had we might want to redesign it in such a way that it maximizes sales of more efficient electric vehicles. 

##### Risks and Assumptions

While part of NYSERDA's Mission is to increase energy efficiency it also aims to reduce NY's reliance on fossil fuels. Altering the rebate to focus on efficiency rather than range may negatively impact overall sales of electric vehicles, which would be counter to this goal. 

#### Data

Data on New York's electric vehicle sales:

https://www.nyserda.ny.gov/All-Programs/Drive-Clean-Rebate/How-it-Works/Eligible-Models

https://www.nyserda.ny.gov/All-Programs/ChargeNY/Support-Electric/Map-of-EV-Registrations

https://data.ny.gov/Energy-Environment/NYSERDA-Electric-Vehicle-Drive-Clean-Rebate-Data-B/thd2-fu8y

Data on New York's Grid Energy:

https://www.epa.gov/egrid/power-profiler#/

Data on electric vehilce sales in other states:

https://afdc.energy.gov/data/10962

Data on car features:

https://www.kaggle.com/code/goyalshalini93/car-price-prediction-linear-regression-rfe

#### Algorithms & Models

Eventually I would like to run a linear regression with the targets and features given above. For this project I've stayed to only using Microsoft Excel and its single variable regression. Analyzed data in excel can be found here: https://github.com/xamwood/Metis_Business_Project

#### Tools

* Microsoft Excel
* Tableau

#### Comunication

In addition to the slides and visuals presented I've created this interactive tableau dashboard that can compare electric vehicle locations to what percentage of fossil fuels are being used for the grid energy. 

https://public.tableau.com/views/NewYorkEnergySources/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link




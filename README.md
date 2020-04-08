# Post-secondary-application-and-tuition-fee

Under the market mechanism, it is obvious that price and quantity depend on each other. First, I am trying to find whether it is also true in the education market where the application number seems has no influence on university tuition, especially for top universities. In this project, the outcome being a statistical confirmation that suggests a 1% increase in application number would unjustifiably result in a 0.28% increase in tuition fees.

The final project report is named "Does The Number of College Applications Affect U.S Tuition?"

# Methodology

Similar to the demand and supply mechanism, I applied simultaneous equations to solve endogeneity. In the education market, the number of applications is quantity, and tuition is price. Applicants demand a college education, and colleges set the price (tuition fee). Hence, the demand side focuses on the number of applications, where the supply side is based on the tuition fee. The number of application and tuition fee are jointly determined, where they are in no way exogenous to each other. Therefore, we instinctively apply Simultaneous Equations Model (SEM).

Equation(1):

log(Tuition3)=\alpha


# Data Source:

1. The equiality of opportunity: http://www.equality-of-opportunity.org/data/index.html#college 

This website includes cross-sectional statistics of average graduates income from every university, which is an important instrumental variable. Also, it includes several university characteristics: graduation rate, enrollment, rejection rate etc..

2. IPEDS: https://data-planet.libguides.com/education 

This website provides statistics on the number of applications received, number of staff (faculty and administrative) and also tuition fee. The public dataset is from IPEDS(The Integrated Postsecondary Education Data System). Delta.public is a handy IPEDS dataset firstly analyzed by DELTA COST PROJECT. The data is not first handed, but it is well formatted.

# Empirical Results:

According to the SEM results, the number of applications received, a factor that does not contribute directly to education quality, does positively impact tuition cost. With the parameter of 0.28, roughly a 3.5% increase in application numbers will result in a 1% increase in tuition on average. Another notable finding is that prestigiousness (ranking), graduates future income, and location only affect tuition costs positively through the application quantity channel, in an indirect way. In other words, schools may not set tuition fees based on these factors, yet applicants really take them into consideration.

|               | Equation1     | Equation 2|
| ------------- |:-------------:| -----:    |
| log(Tuition3) |               | -6.932*** |
| log(Applcn)   | 0.281***      |           |
| log(Stufacr)  | -0.4769***    |  1.00***  |
| public | -0.678***||
| k_mean ||2.040***|
| Locale |0.00248|-0.0179***|
| tier   |-0.011|-0.222***|

# Reference:
1. Archibald R., F. D. (2016). Why does college cost so much? In E. M. Airoldi, D. Blei, E. Erosheva, and S. E. Fienberg (Eds.), Why Does College Cost So Much? Oxford University Press.
2. Davidson, A. (2019). Is college tuition really too high? - the new york times. The New York Times.
3. Schools, B. V. (2018). Understanding the rising costs of higher education. Best Value Schools .
4. System, T. S. (2019). The real reasons why college tuition is so high and what you can do about it. The Scholarship System.

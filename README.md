# Website-Change-Effect-

import pandas as pd
import numpy as np
import random
import matplotlib.pyplot as plt
%matplotlib inline
random.seed(42)

# Gathering the data 

Like always, see that once all the files are imported correctly and run smoothly. Use the basic commands as usual like .info, .describe, etc. 

**This project unlike others is more volatile and has a more unique data in it**

Therefore, we check the shapes and how each variable like : landing page, old page, control and treatment are dependant of each other. 

Since we are running for a statistical approach **it is important that I have checked that the data is not missing any values and can be properly interpreted between each other**


# Hypothesis 

This part takes a look at the hypothesis of what 'version' would be better for the webiste page. 

I look into the 'convertion' rates of the employees, where towards the end I generate a massive simulations that show me the possibilities and probabilities of possible outcomes. 

# Regression 

The goal is to use statsmodels to fit the regression model I specified in part before to **to see if there is a significant difference in conversion based on which page a customer receives** 

# Conclusion 

From the results, none of the variables have high p-value and therefore supporting the fact that countries and new page guarantee a more significant impact on the converstion rate. Moving to the new page should not be a priority, however, with more testing and possibly additional variables the results may come in differently. We accept the Null Hypothesis

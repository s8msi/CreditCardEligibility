# CreditCardEligibility
In this project, we use the dataset of a list of customers in a bank. The dataset contains a few demographic features of the customers that help us the determine if it is profitable to provide a credit card to the particular customer.
--------
To begin with, a description of the dataset has been given in detail in the beginning of the Jupyter Notebook. The dataset is a collection of demographic, socio-economic & transactional variables to help us determine if it is profitable to provide a credit card to a particular customer.

Let's begin our EDA on the data!

As with all types of data, firstly, we upload them and look to clean up the data. So, we identify the outliers by plotting them on a BoxPlot and remove those particular entries as that data could interfere with our analysis.

Then we move on to deal with the missing values in the data. Since there are three columns with missing values in this dataset, we take three different approaches to treat the missing values: We fill the missing values with the most common value, value right beneath the missing value & the mean of the column.

Then, to find correlation between the variables in the dataset, I use Correlation Matrix and Chi-Square Test. While my variant of Correlation Matrix didn't yield an insight, the Chi-Square Test proved to provide correlation between a few variables.

Finally, I use a few models to find out the precision of the dataset. I use Decision Tree Model, Random Forest Model & Ordinally Encoded. The result was that the Ordinally Encoded Model had the least Mean Absolute Error. So, we go ahead with that.

Thank you!

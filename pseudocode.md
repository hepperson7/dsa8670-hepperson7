## Step 1: Load the dataset  
Use an appropriate command to load the dataset into the code. 
For example, in R this looks like:
    read.csv("excel_file.csv")

---

## Step 2: Clean the data

Replace or remove null / missing values, depending on the situation.
Ensure each record matches its column's datatype. For example, a numeric column should not have any records with text.
Consider normalizing numeric data, if appropriate (K-means clustering, etc)
Normalize categorical data into standard categories. For example "Doctor" vs. "doctor" vs. "Dr." should all be combined into "Doctor".
Convert binary data to factors, if needed. 

---

## Step 3: Calculate summary statistics  

Calculate mean, standard deviation, IQR, max, and min for numeric columns.
For categorical or binary data, calculate frequency / relative frequency.
Calculate correlation to see if relationships exist between variables.

---

## Step 4: Create a visualization  

For numeric data, create a histogram or barchart. 
For categorical data, create boxplots.

Consider creating charts that compare two or more variables:
To compare two numeric variables, create a scatterplot.
To compare a numeric and a categorical variable, create a bar chart or a box plot.
To compare two categorical variables, create a frequency table or a stacked barchart.


---

## Step 5: Interpret results

Determine if there are any outliers in the data. 
Use initial exploratory summary statistics to inform what analysis to do on the data, such as regression. 
Consider sample size and if the sample was representative of the population.
Check any assumptions you may have made about the data, such as normality. 

---  
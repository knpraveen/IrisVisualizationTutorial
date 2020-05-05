# IRIS | Data Visualization
This folder has IRIS data set, where we run data visualization using Python

The Iris dataset was used in **R.A. Fisher's classic 1936 paper**, _The Use of Multiple Measurements in Taxonomic Problems_, and can also be found on the **UCI Machine Learning Repository**.

It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.

## Information on IRIS Dataset

### The columns in this dataset are:

Id

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Species

### Number of values for each species

| Iris-Versicolor        | Iris-Virginica     | Iris-Setosa  |
| ------------- |:-------------:| -----:|
| 50      | 50 | 50 |
| ![GitHub Logo](/3.jpg)      | ![GitHub Logo](/2.jpg) | ![GitHub Logo](/1.jpg) |


## The code explanation with results

##### 1. To code the data visualization first we need to import important library like Panda, Seaborn and Matplotlib

##### 2. We then import the Iris.csv data into python

##### 3. We now run the scatter plot to check how the data is scattered

![GitHub Logo](/4.JPG) 

##### 4. We explore line graph to see if it shows any meaningful relation if these data points

![GitHub Logo](/5.JPG) 

##### 5. We are not able to differenciate the different species with above two graph so we use Facet Grid. This graph shows the species in different colors.

**facet_grid** forms a matrix of panels defined by row and column facetting variables. It is most useful when you have two discrete variables, and all combinations of the variables exist in the data.

![GitHub Logo](/6.JPG) 

##### 6. We now run jointplot using seanborn library to see the relationship using Regression, Dernel Density Estimate and Hexbin plot
Joint plot draws a plot of two variables with bivariate and univariate graphs.

![GitHub Logo](/7.JPG) 

![GitHub Logo](/8.JPG) 

![GitHub Logo](/9.JPG) 

##### 7. We use boxplot to plot the summary like minimum, first quartile, median, third quartile and maximum

![GitHub Logo](/10.JPG) 

![GitHub Logo](/11.JPG) 

##### 8. We explore swarm plot an violin plot

Swarm plot draws a categorical scatterplot with non-overlapping points.

![GitHub Logo](/12.JPG) 

Violin plots are similar to box plots, except that they also show the kernel probability density of the data at different values. Typically, violin plots will include a marker for the median of the data and a box indicating the interquartile range, as in standard box plots.

![GitHub Logo](/13.JPG) 

##### 9. We see that only swarmplot and violinplot is not able to get enough information in last two plot. So we use violet plot, The violin plot is similar to box plots, except that they also show the probability density of the data at different values

![GitHub Logo](/14.JPG) 

##### 10. Seaborn plot is useful for looking at univariate relations is the kdeplot, which creates and visualizes a kernel density estimate of the underlying feature

kdeplot : Fit and plot a univariate or bivariate kernel density estimate.

![GitHub Logo](/15.JPG) 

##### 11. We will use pairplot which shows relation between each pair. We observe how the species Iris Setosa, which is blue is separated from others. We see that Petal length and petal width are correlated.

Plot pairwise relationships in a dataset. By default, this function will create a grid of Axes such that each variable in data will by shared in the y-axis across a single row and in the x-axis across a single column. The diagonal Axes are treated differently, drawing a plot to show the univariate distribution of the data for the variable in that column.

It is also possible to show a subset of variables or plot different variables on the rows and columns.

![GitHub Logo](/16.JPG) 

##### 12. We will use pairplot which shows relation between each pair and also kernel density estimate

![GitHub Logo](/17.JPG) 

##### 13. we plot We plot boxplot using panda

![GitHub Logo](/18.JPG) 

##### 14. We use Andrew curves using panda for the three species. Andrews Curves involve using attributes of samples as coefficients for Fourier series and then plotting these

![GitHub Logo](/19.JPG) 

##### 15. We use Parallel coordinates using panda for the three species. Parallel coordinates plot each feature on a separate column & then draws lines connecting the features for each data sample

![GitHub Logo](/20.JPG) 

##### 16. we use multivariate visualization technique pandas has is radviz. It enables the visualization of multidimensional data while maintaining the relation to the original dimensions.

![GitHub Logo](/21.JPG) 

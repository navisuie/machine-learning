# machine-learning
Iris Data Predictions

Navpreet Singh

An Iris gets its name from the Greek goddess of the rainbow, Iris. The Iris flower data set was
made by British biologist Ronald Fisher, while the data was collected Edgar Anderson. The goal of the
project was to see if any discernible variable helped predict what species of the flower we are looking at.
These flowers can be found everywhere when it comes to culture. An Iris is the birth flower for February,
can also be found in Christianity, Vincent van Gogh was also intrigued by the flowers as they appeared in
some of his works. The point of the project is to be better able to discern the differences between the
species in help to, one sees how many more of one species can grow or simple predicting when it comes
to new habitat discoveries.
The data was found on “https://www.kaggle.com/arshid/iris-flower-dataset”, however it may also
be downloaded straight through sklearn in the form of an import. More precisely “from sklearn.datasets
import load_iris” The data set is comprised of 50 samples of each of the three species, Iris Setosa, Iris
virginica, and Iris versicolor, each flower was categorized into 4 variables, the length and width of the
sepals which is the green leaf like structure found underneath the petals. And, the length and the width of
the petal, which is also called the corolla and is the fun colorful part of the flower. Comparing the
variables and training the algorithm to predict what species the flower may be is what I did.
  Figure 1 shows the relationship of the four variables, sepal length and width also petal length and
width. The figure takes the first entry in the data and plots all its attributes, continuing all the way to the
end of the data. Plotting all the entries. For example, the first entry has a sepal length of 5.1 then going to
the graph and looking at the red line labeled “sepal_length” you can see the first dot plotted is just past 5
on the y axis labeled “Values specific to each iris.” Figure 1 gives us a base understanding of how the
data compares each variable to another data point in the data frame. One thing we can for sure see is that
while one lines trend changes the other lines follow. At about count number 50, we see all the lines jump
in an increase to the next data point at count number 49 the sepal length is 5.0 and at count 50 the sepal
length is 7.0, but the best discovery is that the reason for the shift could be because at count 49 the species
is Iris-setosa but at count 50 the species is Iris versicolor.
  Figure 2 is the K-means clustering of the data set. There are 3 clusters in the figure one cluster
per species. The clustering is done to show some relationship between the species and if we can pick out a
way to better predict what species the flower could be. In the clustering it is very apparent that from just
looking at the data you could predict an Iris Versicolor, for example if the sepal length is between 4.5 cm
and 5.5 cm and the sepal width is between 3.0 cm and 4.0 cm you could use this clustering to make a very
educated guess that the flower would be an Iris Versicolor. However, to predict between a setosa and a
virginica can be much harder. I believe any incorrect answers the predicting method makes must mostly
come from this problem. You can still make a very good guess but looking at the point whose coordinates
are ~ sepal length of 6.2 and sepal width of 2.6 according to the data you would guess this point to be a
setosa, but this is an outlier, and the point can be identified as a virginica
  Figure 3 is showing the coefficients of logistic regression. Unlike the name Logistic regression is
not a regression but rather a classification. A classification is used to predict categories that do not have a
value associated with them but rather a label in this case predicting what species the flower is. In figure 3
I mapped the logistic coefficients, which describe the size and direction between the predictor and
variable. We see that for petal width the weight of the coefficient is ~ -1.0. This means that the predictor
is least likely to use this when predicting but more likely to use sepal width as it has a coefficient of ~ 0.3.
In conclusion after looking at the distinct differences in the figures we can use the 4 given
variables of the flowers to make a better prediction for which flower is what species we have learned that
it is easiest to classify a versicolor more than another of the 2 species and using the combination of
clustering and classification we can make a good guess onto whether the species is setosa or virginica.

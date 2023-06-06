# Knn
> It finds the distance from new point(input features) to the nearby points.

> Nearby points can be of different classification based on dataset.

> It classifies based on majority of the neighbor points classification.(For example : Classes are a,b,c. If the new point has nearby 3 points classified as a,a,b. It takes majority which is "a" and new point is classified as "a").

> We can manually set the number of nearby neighbor points to be considered by using n_neighbors parameter in this algorithm. 

> Better to use neighbor value = Number of Classifications do the target feature has. So that, accuracy will be more.. (For example : Classes are a,b,c. Take n_neighbors as 3 because target featured classes are 3 in number).

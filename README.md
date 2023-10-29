# NASA Nearest Earth Objects Classification

**About the Dataset:**

In the vast expanse of outer space, an endless multitude of celestial objects orbits around us. Contrary to our intuition, a distance of 70,000 kilometers may seem insignificant, but within the cosmic scale, it holds the potential to disrupt numerous natural phenomena. Some of these objects, specifically asteroids, have the capacity to pose a threat to our planet. Gain insight into our celestial surroundings, particularly those objects that could potentially harm Earth with this meticulously assembled dataset. It features a comprehensive list of NASA-certified asteroids, specifically categorized as the nearest Earth objects.

**Dataset Source:**
[Download Dataset](https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects)

**Machine Learning Code:**

The code associated with this repository takes the raw dataset through a series of essential transformations. It addresses missing values using three distinct methods: median, mean, and iterative imputation. Following imputation, all three datasets are normalized using the MinMaxScaler method. The analysis employs three robust machine learning models: logistic regression, random forest classification, and support vector machine. Notably, before fitting the latter two models, random forest classification and support vector machine, GridSearchCV is utilized to determine the optimal hyperparameters for each, enhancing the model's performance.

The code leverages the power of scikit-learn libraries to execute these tasks efficiently.

**Key Findings:**

The results from this analysis demonstrate that the random forest model consistently outperforms the other models. It remains the top-performing model across all three datasets, imputed using different methods (mean, median, and iterative).

These results strongly suggest that the fitting process is highly effective, as indicated by the high and identical accuracy scores of the training and testing sets, both reaching an impressive 88%. This consistency implies a robust model capable of making accurate predictions, which is crucial when dealing with potential asteroid threats. Explore this repository to gain insights into our celestial surroundings and enhance our understanding of potentially hazardous objects in our cosmic neighborhood.

# **PCA and t-SNE Project: Auto MPG**


-----------------------------
## **Context**
-----------------------------

The automobile industry is undergoing rapid transformation driven by global market shifts, rising cost pressures, increased competition, and unpredictable economic conditions. These factors are reshaping how companies operate and strategize. Amidst this evolving landscape, data-driven decision-making—empowered by advancements in machine learning—is becoming a crucial tool for gaining competitive advantage. Automobile companies are now turning to data and AI to optimize operations, personalize customer experiences, and make more informed business decisions.

The auto market itself is highly diverse, featuring a wide range of vehicle types with different configurations and specifications such as engine displacement, horsepower, acceleration, and fuel efficiency. Identifying meaningful patterns and clusters within this data can reveal distinct segments of vehicles that appeal to different customer preferences or use cases. This segmentation is particularly useful for tailoring marketing strategies, pricing models, and inventory decisions.

As a Data Scientist at SecondLife, a prominent used car dealership with a growing interest in vintage automobiles, your role is to leverage historical sales data to uncover insights about the vintage car market. The company has been systematically collecting detailed data on vintage cars sold across its many U.S. outlets. Now, the Director of Operations wants to use this data to identify natural groupings of vintage vehicles—clusters that share similar characteristics. By doing so, SecondLife aims to better understand its inventory, tailor its offerings, and target distinct customer groups more effectively. This strategic use of machine learning for clustering and segmentation will not only enhance marketing efficiency but also improve customer satisfaction and business outcomes.

-----------------------------
## **Objective**
-----------------------------
The objective of this problem is to thoroughly analyze a high-dimensional dataset with the goal of simplifying it while preserving its most important information. When a dataset contains a large number of features (or variables), it can become difficult to visualize, interpret, or use effectively in modeling. This is where dimensionality reduction techniques come into play.
In this project, we aim to use methods such as Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE) to reduce the number of dimensions (features) in the dataset. These techniques help us transform the original high-dimensional data into a lower-dimensional representation that still retains the core structure and patterns present in the original data.
    PCA is a linear method that transforms the data into a new coordinate system where the greatest variance lies along the first principal components. It helps simplify the dataset while maintaining the majority of its variability.
    t-SNE is a non-linear technique that is particularly effective for visualizing high-dimensional data in two or three dimensions, often revealing clusters and groupings that might not be obvious from the raw data.
By applying these dimensionality reduction techniques, we aim to:
    Identify patterns or clusters in the data
    Reveal relationships between different observations
    Highlight important features or feature combinations
    Provide visualizations that make complex data easier to understand
    Extract insights that could inform decision-making or further analysis
Ultimately, this process allows us to better understand the structure and characteristics of the dataset, and prepares the data for use in downstream tasks such as clustering or classification.

-----------------------------
## **Dataset** 
-----------------------------
There are 8 variables in the data: 

- mpg: miles per gallon
- cyl: number of cylinders
- disp: engine displacement (cu. inches) or engine size
- hp: horsepower
- wt: vehicle weight (lbs.)
- acc: time taken to accelerate from 0 to 60 mph (sec.)
- yr: model year
- car name: car model name
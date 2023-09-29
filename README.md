# Star-Type-Classification
Astronomical institutions or sky survey projects all around the world get enormous volumes of astronomical data every day as astronomical observation techniques continue to advance. By categorizing and analyzing the data, astronomers can discover new celestial objects and learn new things. The most well-known astronomical object is a star, which also serves as the primary  component of galaxies. A galaxy's history, dynamics, and evolution can be traced by the age, distribution, and composition of its stars. Additionally, stars produce and distribute heavy elements like carbon, nitrogen, and oxygen, and their features are closely related to those of any planetary systems that may form around them. As a result, the core of astronomy is the study of the creation, evolution, and demise of stars. 

Stars in the universe can be classified into several groups . The groups which have been used here are: Brown Dwarf, Red Dwarf, White Dwarf, Main Sequence, Supergiant and Hypergiant. These groups are classified based on several characteristics of stars such as : Luminosity(L/L0), Radius (R/R0), Surface Temperature(T/T0), Absolute Magnitude(Mv) and Spectral Class (O, B,A,F,G,K,M). The Luminosity , Radius and Surface Temperatures are taken with respect to that of the Sun's . Subscript 0 denotes these values of the Sun. L0 = 3.828 x 1026   Watts, R0 = 6.9551 x 108 m and T0 = 5778 K. The objective is to classify the stars with Luminosity(L/L0), Radius (R/R0), Surface Temperature(T/T0), Absolute Magnitude(Mv) and Spectral Class (O, B,A,F,G,K,M) into their respective type using machine learning classification algorithm i.e. Logistic Regression and K Nearest Neighbor and deep neural network.

## Algorithms
1. Logistic Regression - One of the most often used Machine Learning algorithms, within the category of Supervised Learning, is logistic regression. Using a predetermined set of independent factors, it is used to predict the categorical dependent variable. Despite its name, logistic regression is more of a classification model than a regression model. For situations involving binary and linear classification, logistic regression is a straightforward and more effective approach. It's a classification model that's incredibly simple to implement and performs admirably with linearly separable classes. It is a widely used categorization method in business. 
2. K-Nearest Neighbors (KNN) - The K-NN algorithm makes the assumption that the new case and the existing cases are comparable, and it places the new instance in the category that is most like the existing categories. A new data point is classified using the K-NN algorithm based on similarity after all the existing data has been stored. This means that utilizing the K-NN method, fresh data can be quickly and accurately sorted into a suitable category. Although the K-NN approach is most frequently employed for classification problems, it can also be utilized for regression. Since K-NN is a non-parametric technique, it makes no assumptions about the underlying data. It is also known as a lazy learner algorithm since it saves the training dataset rather than learning from it immediately. 
3. Deep Neural Network (DNN) - DNNs can easily incorporate query features and item features (due to the flexibility of the input layer of the network), which can help capture the specific interests of a user and improve the relevance of recommendations. The main purpose of a neural network is to receive a set of inputs, perform progressively complex calculations on them, and give output to solve real world problems like classification. We restrict ourselves to feed forward neural networks. We have an input, an output, and a flow of sequential data in a deep network.

## Analysis
The Hertzsprung-Russell diagram (HR diagram) is one of the most important tools in the study of stellar evolution. Developed independently in the early 1900s by Ejnar Hertzsprung and Henry Norris Russell, it plots the temperature of stars against their luminosity (the theoretical HR diagram), or the color of stars (or spectral type) against their absolute magnitude (the observational HR diagram, also known as a color-magnitude diagram). Depending on its initial mass, every star goes through specific evolutionary stages dictated by its internal structure and how it produces energy. Each of these stages corresponds to a change in the temperature and luminosity of the star, which can be seen to move to different regions on the HR diagram as it evolves. This reveals the true power of the HR diagram – astronomers can know a star’s internal structure and evolutionary stage simply by determining its position in the diagram.The classification of stars is done using a H-R Diagram as shown below: 

![H-R Diagram (1)](https://github.com/engineer-sonali/Star-Type-Classification/assets/71033672/0f31c911-d60f-4b2a-bc65-ffc33ba10e46)

![Scatter plot](https://github.com/engineer-sonali/Star-Type-Classification/assets/71033672/d38cc9c5-8a1b-41e1-8ca1-50996549663b)

![Scatter plot1](https://github.com/engineer-sonali/Star-Type-Classification/assets/71033672/11c751f2-5726-409d-a9ac-d3f13e97797b)

## Result
The dataset is trained using Logistic Regression, KNN and Deep Neural Network algorithms and the accuracy is obtained. Among all Logistic Regression gives the highest accuracy.

![result](https://github.com/engineer-sonali/Star-Type-Classification/assets/71033672/321b4b50-53cf-48f7-9d91-1a1f0b95a1fa)

The main goal was to understand the working of Logistic Regression , KNN and Deep Neural Network for classification problems of star type dataset. As shown in the result, we are convinced that Logistic Regression based classification gives better accuracy as compared to Deep Neural Network and KNN. 

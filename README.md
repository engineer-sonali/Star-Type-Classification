# Star-Type-Classification
Astronomical institutions or sky survey projects all around the world get enormous volumes of astronomical data every day as astronomical observation techniques continue to advance. By categorizing and analyzing the data, astronomers can discover new celestial objects and learn new things. The most well-known astronomical object is a star, which also serves as the primary  component of galaxies. A galaxy's history, dynamics, and evolution can be traced by the age, distribution, and composition of its stars. Additionally, stars produce and distribute heavy elements like carbon, nitrogen, and oxygen, and their features are closely related to those of any planetary systems that may form around them. As a result, the core of astronomy is the study of the creation, evolution, and demise of stars. 

Stars in the universe can be classified into several groups . The groups we have used here are: Brown Dwarf, Red Dwarf, White Dwarf, Main Sequence, Supergiant and Hypergiant. These groups are classified based on several characteristics of stars such as : Luminosity(L/L0), Radius (R/R0), Surface Temperature(T/T0), Absolute Magnitude(Mv) and Spectral Class (O, B,A,F,G,K,M). The Luminosity , Radius and Surface Temperatures are taken with respect to that of the Sun's . Subscript 0 denotes these values of the Sun. L0 = 3.828 x 1026   Watts, R0 = 6.9551 x 108 m and T0 = 5778 K. Our objective is to classify the stars with Luminosity(L/L0), Radius (R/R0), Surface Temperature(T/T0), Absolute Magnitude(Mv) and Spectral Class (O, B,A,F,G,K,M) into their respective type using machine learning classification algorithm i.e. Logistic Regression and K Nearest Neighbor and deep neural network.

## Algorithms
1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Deep Neural Network (DNN)

## Analysis
The Hertzsprung-Russell diagram (HR diagram) is one of the most important tools in the study of stellar evolution. Developed independently in the early 1900s by Ejnar Hertzsprung and Henry Norris Russell, it plots the temperature of stars against their luminosity (the theoretical HR diagram), or the color of stars (or spectral type) against their absolute magnitude (the observational HR diagram, also known as a color-magnitude diagram). Depending on its initial mass, every star goes through specific evolutionary stages dictated by its internal structure and how it produces energy. Each of these stages corresponds to a change in the temperature and luminosity of the star, which can be seen to move to different regions on the HR diagram as it evolves. This reveals the true power of the HR diagram – astronomers can know a star’s internal structure and evolutionary stage simply by determining its position in the diagram.The classification of stars is done using a H-R Diagram as shown below: 

![H-R Diagram (1)](https://github.com/engineer-sonali/Star-Type-Classification/assets/71033672/721cfee5-6cbf-493d-9789-15c036c75fbd)

![Scatter plot](https://github.com/engineer-sonali/Star-Type-Classification/assets/71033672/a550f674-53e8-4d06-bfc5-6150d0a2513a)

## Result
The dataset is trained using Logistic Regression, KNN and Deep Neural Network algorithms and the accuracy is obtained. Among all Logistic Regression gives the highest accuracy.

![result](https://github.com/engineer-sonali/Star-Type-Classification/assets/71033672/56e5a07e-d0c6-41c5-800c-6329e97525dc)

The main goal was to understand the working of Logistic Regression , KNN and Deep Neural Network for classification problems of star type dataset. As shown in the result, we are convinced that Logistic Regression based classification gives better accuracy as compared to Deep Neural Network and KNN. 








# ANN-based-Machine-Learning-Model-for-Optimizing-the-Haber-Bosch-Process-Using-COMSOL
Inverse Modeling of the Haber-Bosch Process for Yield Optimization
This project uses an Artificial Neural Network (ANN) built with TensorFlow and Keras to optimize the Haber-Bosch process. Instead of a traditional "forward" model that predicts ammonia yield from given process conditions, this project implements an inverse model. You provide a desired ammonia yield, and the model predicts the optimal operational conditions (Temperature, Pressure, and H₂ Fraction) required to achieve it.
This approach is powerful for industrial and chemical engineering applications where the goal is to determine the inputs needed to hit a specific target output.
Project Overview
The Haber-Bosch process, represented by the equation N2+3H2 ⇌ 2NH3, is a cornerstone of modern chemical manufacturing, primarily for producing ammonia used in fertilizers. The yield, of this process is highly dependent on operational parameters like temperature and pressure.
This project tackles the optimization challenge by:
- Normalizing a simulated dataset of Haber-Bosch process data.
- Training a sequential neural network to learn the relationship between the ammonia yield and the conditions that produce it.
- Using the trained model to predict the necessary Temperature, Pressure, and H₂ Fraction for any given target yield.

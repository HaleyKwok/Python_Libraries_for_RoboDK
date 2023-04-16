# Python_Libraries_for_RoboDK


## 📍 Mission
Our mission is to gain understanding of RoboDK robot parameters patterns. This repo provides insights on Collaborative and Industrial Robotics listed in RoboDK. 

- Improve robot control: This can help improve the accuracy and efficiency of simulations, ultimately leading to better results.
- Training deep learning models: The data collected from RoboDK simulations can be used to train deep learning models that can be used for tasks such as object detection, pose estimation, and motion planning.
- Develop new models: Data collected from RoboDK simulations can be used to develop new deep learning models that can be used for tasks such as robot grasping, collision avoidance, and visual navigation.
- Validate models: To use simulation data to compare the performance of different models and determine which model provides the best results.
- Use Flask, Postman and Python (pickle package) to pass elements generated from the model and publish them on a web page.

--- 

## 🔆 Introduction

The list provided [RoboDK.xlsx](https://github.com/HaleyKwok/Python_Libraries_for_RoboDK/blob/main/RoboDK.xlsx) contains several industrial robotic arms from various manufacturers, along with some basic technical specifications for each. Some of the manufacturers included in the list are Omron, Nachi, Niryo, Panasonic, Precise, PUMA, QJAR, Rainbow Robotics, Reis, RoboDK, Robostar, Rokae, Siasun, and Staubli.

These are specifications for various industrial robots, including the model name, number of axes, reach (in mm), payload capacity (in kg), weight (in kg), and repeatability (in mm), which can be used to determine which robot model is best suited for a particular task based on the payload, reach, and other requirements.

---

## 📝 Brief Introduction to Robotics Company

AUBO - A Chinese manufacturer of collaborative robots (cobots) that are designed to work alongside humans.
Automata - A UK-based company that produces a low-cost collaborative robot called Eva, which is designed to be user-friendly and easy to set up.
BORUNTE - A Chinese company that produces a range of industrial robots, including welding robots, palletizing robots, and robots for handling heavy loads.
CLOOS - A German manufacturer of welding robots and welding equipment.
Comau - An Italian company that produces a wide range of industrial robots, including cobots, SCARA robots, and six-axis robots for a variety of applications.
CPR - A Canadian manufacturer of small, lightweight collaborative robots.
CRS - A Taiwanese company that produces a range of industrial robots, including SCARA robots, six-axis robots, and linear robots.
Denso - A Japanese manufacturer of industrial robots that specializes in small, high-precision robots for assembly, inspection, and other applications.
Each of these brands has its own strengths and areas of expertise, and the robots they produce vary in terms of size, payload capacity, precision, and other factors.

---
## 📋 Example: Using the RoboDK dataset to do the clustering

[Clustering](https://github.com/HaleyKwok/Python_Libraries_for_RoboDK/blob/main/Clustering.ipynb)

> This code performs k-means clustering on a dataset X with two features, where n_clusters = 3 is the number of clusters to be formed. The init parameter is set to 'k-means++', which means the initial cluster centers will be selected in a smart way to speed up convergence. The random_state parameter is set to 50 to ensure reproducibility of the results. The fit_predict method is called on the KMeans object kmeans to perform clustering on the dataset and obtain the cluster assignments for each data point in X. The resulting cluster assignments are stored in the y_predict variable. The code then visualizes the clusters by plotting the data points of each cluster in a scatter plot. The data points belonging to each cluster are color-coded differently. The centroids of the clusters are also plotted as yellow circles with a larger size. The resulting plot is titled "Clusters of RoboDK" and the x and y axis labels indicate the features "Reach (mm)" and "Repeatability (mm)" respectively. Finally, the legend is shown to indicate the meaning of different colors in the plot.

---

## 📖 Acknowledgements
Collection of RoboDK is an open source project, contributed by our team. We thank all contributors who implemented their methods or added new features, as well as users who provided valuable feedback. We hope for further implementation and improvement of these systems.

Permission is hereby granted, free of charge, to any person obtaining a copy of this Repository and associated documentation files, to deal in the Repository without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Repository is furnished to do so.

The authors or copyright holders are not be liable for any claim, damages or other liabillty, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the Repository or the use or other dealings in the Repository.


## 📢 Disclaimer
We develop this repository for Assignment purposes, so it can only be used for personal/research/non-commercial purposes.


## 📭 Contact
If your have any comments or questions, feel free to contact kwokhinchi@gmail.com 





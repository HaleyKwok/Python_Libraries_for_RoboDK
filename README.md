# Python Libraries for RoboDK


## 📍 Mission
Our mission is to gain understanding of RoboDK robot parameters patterns. This repo provides collected dataset of 5 DOF/6 DOF/7 DOF Collaborative and Industrial Robotics listed in the [RoboDK Libraries](https://robodk.com/library). 

Dataset can provide insights to:
- Improve robot control: This can help improve the accuracy and efficiency of simulations, ultimately leading to better results.
- Training deep learning models: The data collected from RoboDK simulations can be used to train deep learning models that can be used for tasks such as object detection, pose estimation, and motion planning.
- Develop new models: Data collected from RoboDK simulations can be used to develop new deep learning models that can be used for tasks such as robot grasping, collision avoidance, and visual navigation.
- Validate models: To use simulation data to compare the performance of different models and determine which model provides the best results.
- Use Flask, Postman and Python (pickle package) to pass elements generated from the model and publish them on a web page.


<div align="center"><img src="https://github.com/HaleyKwok/Python_Libraries_for_RoboDK/blob/main/RoboDK.png" align="center" />
</div> 
<br>

--- 

## 🔆 Introduction

The list [RoboDK.xlsx](https://github.com/HaleyKwok/Python_Libraries_for_RoboDK/blob/main/RoboDK.xlsx) and [RoboDK.csv](https://github.com/HaleyKwok/Python_Libraries_for_RoboDK/blob/main/RoboDK.csv) provided contains several industrial robotic arms from various manufacturers, along with some basic technical specifications for each. Some of the manufacturers included in the list are Omron, Nachi, Niryo, Panasonic, Precise, PUMA, QJAR, Rainbow Robotics, Reis, RoboDK, Robostar, Rokae, Siasun, and Staubli.

These are specifications for various industrial robots, including the model name, number of axes, reach (in mm), payload capacity (in kg), weight (in kg), and repeatability (in mm), which can be used to determine which robot model is best suited for a particular task based on the payload, reach, and other requirements.


<div align="center"><img src="https://github.com/HaleyKwok/Python_Libraries_for_RoboDK/blob/main/RoboDKdataset.png" align="center" />
</div> 
<br>


---

## 📝 Background information on industrial robotics companies

Each of these brands has its own strengths and areas of expertise, and the robots they produce vary in terms of size, payload capacity, precision, and other factors.

<details>
  <summary>Industrial Robotics Companies</summary>
  
- Fanuc: A Japanese robotics company that specializes in producing industrial robots, CNC systems, and factory automation systems.
- Kawasaki: A Japanese multinational corporation that produces a wide range of products, including industrial robots, motorcycles, and aerospace equipment.
- KUKA: A German manufacturer of industrial robots and automation systems.
- Mitsubishi: A Japanese multinational conglomerate that produces a wide range of products, including industrial robots, heavy electrical equipment, and automotive components.
- Yaskawa Motoman: A subsidiary of the Japanese corporation Yaskawa Electric Corporation, which produces industrial robots, servo motors, and machine controllers.
- Nachi: A Japanese manufacturer of industrial robots, machine tools, and bearings.
- Staubli: A Swiss manufacturer of industrial robots and automation solutions for a wide range of industries.
- OTC Daihen: A Japanese manufacturer of welding robots and automation systems.
- Franka Emika: A German robotics company that produces lightweight collaborative robots.
- Kinova: A Canadian company that produces lightweight robotic arms for applications in healthcare, research, and education.
- Siasun: A Chinese manufacturer of industrial robots and automation equipment.
- ABB: A Swiss-Swedish multinational corporation that produces a wide range of products, including industrial robots, power grids, and electrification products.

</details>

---
## 📋 Machine Learning with RoboDK dataset

Clustering Example: [Clustering](https://github.com/HaleyKwok/Python_Libraries_for_RoboDK/blob/main/Clustering.ipynb)

<div align="center"><img src="https://github.com/HaleyKwok/Python_Libraries_for_RoboDK/blob/main/Clustering.png" align="center" />
</div> 
<br>


> This code performs k-means clustering on a dataset `X` with two features, where `n_clusters = 3` is the number of clusters to be formed. The `init` parameter is set to `k-means++`, which means the initial cluster centers will be selected in a smart way to speed up convergence. The `random_state` parameter is set to `50` to ensure reproducibility of the results. The `fit_predict` method is called on the KMeans object kmeans to perform clustering on the dataset and obtain the cluster assignments for each data point in `X`. The resulting cluster assignments are stored in the `y_predict` variable. The code then visualizes the clusters by plotting the data points of each cluster in a scatter plot. The data points belonging to each cluster are color-coded differently. The centroids of the clusters are also plotted as yellow circles with a larger size. The resulting plot is titled `"Clusters of RoboDK"` and the `x` and `y` axis labels indicate the features "Reach (mm)" and "Repeatability (mm)" respectively. Finally, the legend is shown to indicate the meaning of different colors in the plot.

---

## 📖 Acknowledgements
Collection of 5 DOF/6 DOF/7 DOF Collaborative and Industrial Robotics from the [RoboDK Libraries](https://robodk.com/library) is an open source project, contributed by our team. We thank all contributors who implemented their methods or added new features, as well as users who provided valuable feedback. We hope for further implementation and improvement of these systems.

Permission is hereby granted, free of charge, to any person obtaining a copy of this Repository and associated documentation files, to deal in the Repository without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Repository is furnished to do so.

The authors or copyright holders are not be liable for any claim, damages or other liabillty, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the Repository or the use or other dealings in the Repository.


## 📢 Disclaimer
This repository is for personal/research/non-commercial use only.


## 📭 Contact
If your have any comments or questions, feel free to contact kwokhinchi@gmail.com 

---

Copyright © [Haley Kwok](https://github.com/HaleyKwok). All rights reserved.



# Spark_Streaming

This project aims to perform stream processing from an IoT device using Apache Spark’s Structured Streaming API

The project consists of Heterogeneity Human Activity Recognition (HHAR) dataset from Smartphones
and Smartwatches. 

This is a dataset devised to benchmark human activity recognition algorithms
(classification, automatic data segmentation, sensor fusion, feature extraction, etc.) in real-world
contexts; specifically, the dataset is gathered with a variety of different device models and use-
scenarios, in order to reflect sensing heterogeneities to be expected in real deployments.

Take a look here to know more about the data we will use:
https://archive.ics.uci.edu/ml/datasets/Heterogeneity+Activity+Recognition#

This data measures the orientation of a sensor along x,y,z dimensions as 9 subjects perform
various activities (gt). The device and model are recorded, as well as various timestamps and an
index.

The file consists of the following columns:
• 'Arrival_Time' - The time the measurement arrived to the sensing application
• 'Creation_Time' - The timestamp the OS attaches to the sample
• 'Device' - The specific device this sample is from. prefixed with the model name and then
the number, e.g., nexus4_1 or nexus4_2 (8 available)
• 'Index' - observation id/ row number
• 'Model' - smartphone/watch model (4 available)
• 'User' - user id
• 'gt' – activities carried out by participant (ground truth): bike sit, stand, walk, stairsup,
stairsdown and null'x' - sensor orientation along dimension x
• 'y' - sensor orientation along dimension y
• 'z' - sensor orientation along dimension z

Mainly our data contains only one Model: LG’s nexus4 and two devices: nexus4_1 and


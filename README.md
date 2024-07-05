# Spatio-Temporal-Autoencoder-based-Video-Anomaly-Detection
This project involves a multi-step process: first, videos are converted into frames using FFmpeg, and then each frame is further converted into cuboids, which are organized into separate folders. Subsequently, a spatio-temporal autoencoder is trained for each cuboid folder individually.

# ABSTRACT
The widespread adoption of video surveillance systems across diverse sectors has
generated vast amounts of video data, necessitating effective analysis methods for
enhanced safety and efficiency. Anomaly detection in videos is pivotal for identifying
threats, accidents, or equipment malfunctions, yet traditional techniques relying on
handcrafted features face limitations in capturing intricate spatial-temporal patterns and
scalability to large datasets. In response, deep learning-based approaches, particularly
spatio-temporal autoencoders, have emerged as promising solutions for unsupervised
learning of complex features directly from video data.
In this project, the efficacy of spatio-temporal autoencoders for video anomaly
detection, focusing on the decomposition and analysis of video cuboids to capture both
spatial and temporal characteristics. By harnessing the feature learning capabilities of
deep learning and the granularity offered by cuboid-based representations, the proposed
method aims to achieve more accurate, and computationally efficient anomaly
detection. The report delves into the underlying principles and techniques of spatiotemporal autoencoders, detailing their application in decomposing video sequences and
extracting meaningful features. Evaluation of the method's performance is conducted
across various real-world video datasets, providing insights into its effectiveness and
potential applications. Additionally, the report discusses challenges and outlines future
directions for advancing video anomaly detection using spatio-temporal autoencoders.

# PROBLEM STATEMENT
The increasing adoption of video surveillance systems across various sectors,
including public safety, traffic management, and industrial production, has led to an
exponential growth in video data. Effective analysis of this data can yield valuable
insights, leading to improved safety and efficiency in these domains. Anomaly
detection is a critical aspect of video analysis that has attracted considerable attention
among researchers and practitioners. Identifying anomalous events in videos is
essential for recognizing potential threats, accidents, or malfunctioning equipment.
However, the complex nature of video data, which encompasses spatial and temporal
dimensions, makes this task challenging. Recently, deep learning-based methods [1-
8] have demonstrated promising results in video anomaly detection.
In this report, an innovative method for detecting video anomalies using
spatiotemporal autoencoders [1-2]. the proposed method involves converting the video
into frames using FFmpeg, a widely used multimedia framework. These frames are
then transformed into cuboids [11], which are three-dimensional pixel blocks. Each
cuboid is saved in its own folder for subsequent processing. A spatio-temporal
autoencoder is then trained on each folder of cuboids, learning the spatiotemporal
features of the cuboids.
Traditional video anomaly detection methods rely on handcrafted features like
optical flow or Histogram of Oriented Gradients (HOG). Although these approaches
have shown some success, they may not fully capture the intricate spatial and temporal
patterns present in the data. Additionally, extracting handcrafted features is often
computationally expensive, limiting the scalability of these methods for large-scale
video datasets.


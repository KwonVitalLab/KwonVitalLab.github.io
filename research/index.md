---
title: Research
nav:
  order: 2
  tooltip: Research Projects
---

# Research Projects
{:.center}

{%
  include button.html
  type="link"
  icon=""
  text="Human Activity Recognition"
  link="research/#machine-learning-for-human-activity-recognition"
%}

{%
  include button.html
  type="link"
  icon=""
  text="Machine Learning with Edge and Cloud Computing"
  link="research/#edge-computing-and-machine-learning-framework-using-multi-modal-ambient-mobile-and-wearable-sensors"
%}

{%
  include button.html
  type="link"
  icon=""
  text="Health Analytics"
  link="research/#behavior-analytics-for-health-assessments"
%}

<!-- [Machine Learning for Human Activity Recognition](#machine-learning-for-human-activity-recognition) 

[Edge Computing and Machine Learning Framework Using Multi-modal Ambient, Mobile, and Wearable Sensors](#edge-computing-and-machine-learning-framework-using-multi-modal-ambient-mobile-and-wearable-sensors)

[Behavior Analytics for Health Assessments](#behavior-analytics-for-health-assessments)
-->



{% include section.html %}

## Machine Learning for Human Activity Recognition

### Opportunistic Use of Video Data for Wearable-based Human Activity Recognition

{% include figure.html image="images/research/IMUTube Diagrams.jpg" width="50%" %}

Building human activity recognition model involves training a machine learning model to classify the given sensor signal input for target activities. The performance of the supervised learning approach largely depends on the scale of the training dataset that covers diverse activity patterns in the wild. However, collecting wearable sensor data from users is expensive, and annotation is time-consuming. Thereby, wearable datasets are typically limited in scale. To overcome the challenges in collecting wearable datasets, We proposed a method that uses a virtually unlimited amount of video data in online repositories to generate a training sensor dataset. The proposed technique uses state-of-the-art computer vision algorithms to track full human motions from human activity video and extract virtual inertial measurement signals from the on-body locations. The collection of virtual sensors from target activity videos is used to train the human activity recognition model, which is deployed in the real world. The proposed technique opens up the opportunity to apply complex analysis models for human activity recognition with the availability of large-scale training data

- Kwon, H., Tong, C., Haresamudram, H., Gao, Y., Abowd, G. D., Lane, N. D., & Ploetz, T. (2020). IMUTube: Automatic extraction of virtual on-body accelerometry from video for human activity recognition. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 4(3), 1-29.
- Kwon, H., Wang, B., Abowd, G. D., & Plötz, T. (2021). Approaching the Real-World: Supporting Activity Recognition Training with Virtual IMU Data. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 5(3), 1-32.
- Kwon, H., Abowd, G. D., & Plötz, T. (2021). Complex Deep Neural Networks from Large Scale Virtual IMU Data for Effective Human Activity Recognition Using Wearables. Sensors, 21(24), 8337.

### Large Language Model and Generative Motion Model for Wearable-based Human Activity Recognition

{% include figure.html image="images/research/gpt-iswc.png" width="50%" %}

The development of robust, generalized models in human activity recognition (HAR) has been hindered by the scarcity of large-scale, labeled data sets. Recent work has shown that virtual IMU data extracted from videos using computer vision techniques can lead to substantial performance improvements when training HAR models combined with small portions of real IMU data. Inspired by recent advances in motion synthesis from textual descriptions and connecting Large Language Models (LLMs) to various AI models, we introduce an automated pipeline that first uses ChatGPT to generate diverse textual descriptions of activities. These textual descriptions are then used to generate 3D human motion sequences via a motion synthesis model, T2M-GPT, and later converted to streams of virtual IMU data. We benchmarked our approach on three HAR datasets (RealWorld, PAMAP2, and USC-HAD) and demonstrate that the use of virtual IMU training data generated using our new approach leads to significantly improved HAR model performance compared to only using real IMU data. Our approach contributes to the growing field of cross-modality transfer methods and illustrate how HAR models can be improved through the generation of virtual training data that do not require any manual effort.

- Zikang Leng, Hyeokhyen Kwon, and Thomas Ploetz. 2023. Generating Virtual On-body Accelerometer Data from Virtual Textual Descriptions for Human Activity Recognition. In Proceedings of the 2023 International Symposium on Wearable Computers (ISWC '23). Association for Computing Machinery, New York, NY, USA, 39–43. https://doi.org/10.1145/3594738.3611361

### Robust Human Activity Recognition Model with Uncertainty Modeling

{% include figure.html image="images/research/label jitter.png" width="80%" %}

Building human activity recognition model involves training a machine learning model to classify the given sensor signal feature for target activities. For the conventional supervised learning approach, discriminative sensor feature representation and accurate activity annotations are necessary to learn the robust human activity recognition model. However, acquiring accurate activity annotation is intractable due to the continuous nature of human activities. Thereby, the activity annotations have uncertainty regarding the correct temporal alignment of activity boundaries and the correctness of the actual label. We explore novel machine learning techniques to handle such uncertainties. 

- Kwon, H., Abowd, G. D., & Plötz, T. (2018, October). Adding structural characteristics to distribution-based accelerometer representations for activity recognition using wearables. In Proceedings of the 2018 ACM international symposium on wearable computers (pp. 72-75).
- Kwon, H., Abowd, G. D., & Plötz, T. (2019, September). Handling annotation uncertainty in human activity recognition. In Proceedings of the 23rd International Symposium on Wearable Computers (pp. 109-117).

{% include section.html %}

## Edge Computing and Machine Learning Framework Using Multi-modal Ambient, Mobile, and Wearable Sensors

### Distributed Multi-view Camera System for Behavior Recognition Using Edge, Fog, and Cloud Computing System.

{% include figure.html image="images/research/cep_ep6_camera_mot.png" width="60%" %}

Localization of individuals in a built environment is a growing research topic. Estimating the positions, face orientation (or gaze direction) and trajectories of people through space has many uses, such as in crowd management, security, and healthcare. In this work, we present an open-source, low-cost, scalable and privacy-preserving edge computing framework for multi-person localization, i.e. estimating the positions, orientations, and trajectories of multiple people in an indoor space. Our computing framework consists of 38 Tensor Processing Unit (TPU)-enabled edge computing camera systems placed in the ceiling of the indoor therapeutic space. The edge compute systems are connected to an on-premise fog server through a secure and private network. A multi-person detection algorithm and a pose estimation model run on the edge TPU in real-time to collect features which are used, instead of raw images, for downstream computations. This ensures the privacy of individuals in the space, reduces data transmission/storage and improves scalability. We implemented a Kalman filter-based multi-person tracking method and a state-of-the-art body orientation estimation method to determine the positions and facing orientations of multiple people simultaneously in the indoor space. For our study site with size of 18,000 square feet, our system demonstrated an average localization error of 1.41 meters, a multiple-object tracking accuracy score of 62%, and a mean absolute body orientation error of 29°, which is sufficient for understanding group activity behaviors in indoor environments. Additionally, our study provides practical guidance for deploying the proposed system by analyzing various elements of the camera installation with respect to tracking accuracy.

- Kwon et al. (2023). Indoor Localization and Multi-person Tracking Using Privacy Preserving Distributed Camera Network with Edge Computing. 	arXiv:2305.05062 

### Wearable-based Behavior Recognition Using Edge, Fog, and Cloud Computing System

{% include figure.html image="images/research/cep_ep6_ble_imu_mot.png" width="40%" %}

Spatial navigation of indoor space usage patterns reveals important cues about the cognitive health of individuals. In this work, we present a low-cost, scalable, open-source edge computing system using Bluetooth Low Energy (BLE) and Inertial Measurement Unit sensors (IMU) for tracking indoor movements for a large indoor facility (over 1600 $m^2$) that was designed to facilitate therapeutic activities for individuals with Mild Cognitive Impairment. The facility is instrumented with 39 edge computing systems with an on-premise fog server, and subjects carry BLE beacon and IMU sensors on-body. We proposed an adaptive trilateration approach that considers the temporal density of hits from the BLE beacon to surrounding edge devices to handle inconsistent coverage of edge devices in large spaces with varying signal strength that leads to intermittent detection of beacons. The proposed BLE-based localization is further enhanced by fusing with an IMU-based tracking method using a dead-reckoning technique. Our experiment results, achieved in a real clinical environment, suggest that an ordinary medical facility can be transformed into a smart space that enables automatic assessment of the individual patients' movements.

- Kiarash et al. (2023). Indoor Localization using Bluetooth and Inertial Motion Sensors in Distributed Edge and Cloud Computing Environment. arXiv:2305.19342 

{% include section.html %}

## Behavior Analytics for Health Assessments

### Movement Disorder Assessment with Kinematics Dataset

{% include figure.html image="images/research/xai4fog.png" width="60%" %}

Freezing of gait (FOG) is a poorly understood heterogeneous gait disorder seen in patients with parkinsonism which contributes to significant morbidity and social isolation. FOG is currently measured with scales that are typically performed by movement disorders specialists (i.e., MDS-UPDRS), or through patient-completed questionnaires (N-FOG-Q), both of which are inadequate in addressing the heterogeneous nature of the disorder and are unsuitable for use in clinical trials. Moreover, prior studies that investigated machine-learning-based techniques to objectively phenotype FOG primarily used spectral analyses of kinematic data from few on-body locations during gait assessments, which lack details to capture complex whole-body movements. To overcome those limitations, we devise a method using explainable artificial intelligence models that can measure FOG objectively and accurately, hence improving our ability to identify it and accurately evaluate new therapies. The proposed model was able to explain how kinematic movements are associated with each FOG severity level that were highly consistent with the features, in which movement disorders specialists are trained to identify as characteristics of freezing. Overall, the proposed technique demonstrates that deep learning models’ capability to capture complex movement patterns in kinematic data can automatically and objectively score FOG with high accuracy. These models have the potential to discover novel kinematic biomarkers for FOG that can be used for hypothesis generation and potentially as clinical trial outcome measures.

- Kwon, H., Clifford, G. D., Genias, I., Bernhard, D., Esper, C. D., Factor, S. A., & McKay, J. L. (2023). An explainable spatial-temporal graphical convolutional network to score freezing of gait in parkinsonian patients. Sensors, 23(4), 1766.

### Mental Health Assessment with Remote Interviews

{% include figure.html image="images/research/multi-modal-MH.png" width="60%" %}

The current clinical practice of psychiatric evaluation suffers from subjectivity and bias, and requires highly skilled professionals that are often unavailable or unaffordable. Objective digital biomarkers have shown the potential to address these issues. In this work, we investigated whether behavioral and physiological signals, extracted from remote interviews, provided complimentary information for assessing psychiatric disorders. Time series of multimodal features were derived from four conceptual modes: facial expression, vocal expression, linguistic expression, and cardiovascular modulation. The features were extracted from simultaneously recorded audio and video of remote interviews using task-specific and foundation models. Averages, standard deviations, and hidden Markov model-derived statistics of these features were computed from 73 subjects. Four binary classification tasks were defined: detecting 1) any clinically-diagnosed psychiatric disorder, 2) major depressive disorder, 3) self-rated depression, and 4) self-rated anxiety. Each modality was evaluated individually and in combination. Multimodal features extracted from remote interviews revealed informative characteristics of clinically diagnosed and self-rated mental health status. The proposed multimodal approach has the potential to facilitate objective, remote, and low-cost assessment for low-burden automated mental health services.

- Jiang, Zifan, Salman Seyedi, Emily Lynn Griner, Ahmed Abbasi, Ali Bahrami Rad, Hyeokhyen Kwon, Robert O. Cotes, and Gari D. Clifford. "Multimodal mental health assessment with remote interviews using facial, vocal, linguistic, and cardiovascular patterns." medRxiv (2023): 2023-09.

### Cognitive Impairment

Soon to come. _Stay tuned_

### Autism Spectrum Disorder

Soon to come. _Stay tuned_
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
  link="research/#generative-ai-and-cross-modality-techniques-for-human-activity-recognition"
%}

{%
  include button.html
  type="link"
  icon=""
  text="Smart Hospital with Ubiquitous AI"
  link="research/#smart-hospital-using-edge-computing-and-machine-learning-framework-with-multi-modal-ambient-mobile-and-wearable-sensors"
%}

{%
  include button.html
  type="link"
  icon=""
  text="Telehealth with Fair AI"
  link="research/#intelligent-telehealth-platforms-with-fair-artificial-intelligence-and-cloud-computing"
%}


{%
  include button.html
  type="link"
  icon=""
  text="Health Analytics with XAI"
  link="research/#behavior-analytics-for-health-assessments"
%}

<!-- [Machine Learning for Human Activity Recognition](#machine-learning-for-human-activity-recognition) 

[Edge Computing and Machine Learning Framework Using Multi-modal Ambient, Mobile, and Wearable Sensors](#edge-computing-and-machine-learning-framework-using-multi-modal-ambient-mobile-and-wearable-sensors)

[Behavior Analytics for Health Assessments](#behavior-analytics-for-health-assessments)
-->



{% include section.html %}

## Generative AI and Cross-modality Techniques for Human Activity Recognition

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

## Smart Hospital using Edge Computing and Machine Learning Framework with Multi-modal Ambient, Mobile, and Wearable Sensors


### Low-cost, Passive, and Continuous Patient Monitoring System Using Artificial Intelligence, Distributed Multi-view Camera System, and Wearables.

{% include figure.html image="images/research/cep_ep6_cam_wear.png" width="90%" %}

Neurological disorders can influence an individual's mobility and social interactions, offering insights into disease progression. Yet, accurately measuring intricate movements and social interactions in real-world settings is challenging, making clinicians rely on retrospective surveys. Addressing this challenge, I've introduced a cost-effective, passive, continuous patient-monitoring system capable of quantifying patients' social behaviors and movements within therapeutic facilities spanning 18,000 sqft. This system integrates multiple edge computing devices, combined with AI, cameras, and wearable sensors, to localize, track, and identify group activities. Specifically, it's applied to quantify Mild Cognitive Impairment (MCI). With minimal modification to the existing infrastructure, this system can transform standard therapeutic areas into smart environments that can evaluate conditions linked to neurological disorders at a low cost.

- H. Kwon et al., "A Feasibility Study on Indoor Localization and Multi-person Tracking Using Sparsely Distributed Camera Network with Edge Computing," in IEEE Journal of Indoor and Seamless Positioning and Navigation, doi: 10.1109/JISPIN.2023.3337189.
- C. Hegde et al., "Indoor Group Identification and Localization Using Privacy-Preserving Edge Computing Distributed Camera Network," in IEEE Journal of Indoor and Seamless Positioning and Navigation, doi: 10.1109/JISPIN.2024.3354248.
- Kiarashi et al., "Graph Trilateration for Indoor Localization in Sparsely Distributed Edge Computing Devices in Complex Environments Using Bluetooth Technology," Sensors 2023, 23, 9517.


{% include section.html %}

## Intelligent Telehealth Platforms with Fair Artificial Intelligence and Cloud Computing

### Multi-modal Machine Learning System for Assessing Remote Interviews

{% include figure.html image="images/research/multi-modal-MH.png" width="60%" %}

This research addresses the challenges in current psychiatric evaluations, which often suffer from subjectivity, bias, and the need for highly skilled professionals. The study explores the use of objective digital biomarkers, derived from behavioral and physiological signals in remote interviews, for psychiatric disorder assessment. These signals include facial and vocal expressions, linguistic content, and cardiovascular modulation. The study used a multimodal approach, evaluating each modality individually and in combination, to assess mental health status. This approach aims to make mental health assessments more objective, remote, and cost-effective. The research also critically examines the fairness of these automated mental health assessment tools across different demographics (race, gender, education level, and age). Despite their growing importance, especially in telehealth, these tools can carry biases that may lead to unfair treatment of certain groups. The study systematically evaluated and discussed the need for reporting and mitigating these biases to build trust and ensure appropriate application in clinical settings. Using a developed multimodal mental health assessment system, the study analyzed how various features (facial expressions, voice acoustics, linguistic expressions, and cardiovascular patterns) affected fairness across demographics. The findings indicated that no single modality was consistently fair for all groups. Although methods to mitigate unfairness improved fairness levels, they also highlighted a trade-off between performance and fairness. This calls for a broader moral discussion and further investigation into the ethics and application of automated mental health assessment tools.

- Jiang, Z., Seyedi, S., Griner, E., Abbasi, A., Rad, A.B., Kwon, H., Cotes, R.O. and Clifford, G.D., 2024. Multimodal Mental Health Digital Biomarker Analysis from Remote Interviews using Facial, Vocal, Linguistic, and Cardiovascular Patterns. IEEE Journal of Biomedical and Health Informatics.
- Jiang, Zifan, Salman Seyedi, Emily Griner, Ahmed Abbasi, Ali Bahrami Rad, Hyeokhyen Kwon, Robert O. Cotes, and Gari D. Clifford. "Evaluating and mitigating unfairness in multimodal remote mental health assessments." medRxiv (2023): 2023-11.

{% include section.html %}

## Behavior Analytics for Health Assessments

### Explainable Artificial Intelligence for Movement Disorder Assessment with Kinematics Dataset

{% include figure.html image="images/research/xai4fog.png" width="60%" %}

Traditional methods for diagnosing and assessing Parkinson’s disease (PD) often involve thorough physical examinations by specialists in movement disorders. These methods, including the use of scales like MDS-UPDRS or patient questionnaires (N-FOG-Q), can be subjective and vary between different raters. Particularly challenging is assessing Freezing of Gait (FOG), a complex aspect of parkinsonism that significantly affects quality of life. PD is also known to manifest in different motor subtypes, mainly tremor dominant (TD) and postural instability/gait difficulty (PIGD), each presenting unique challenges in balance and gait. Previous studies have employed machine learning to analyze kinematic data from body movements during gait assessments, but these often lacked the detail necessary to fully capture the complexity of whole-body movements in PD. To address this, a new method using explainable artificial intelligence models has been developed. These models can objectively and accurately measure PD, mirroring the assessment capabilities of human specialists. They show promise in accurately identifying FOG severity levels and PD subtypes, thereby aiding in the early identification of motor subtypes and predicting disease progression. Moreover, these models can potentially discover new kinematic biomarkers for PD, offering valuable insights for clinical trials and hypothesis generation.

- Kwon, H., Clifford, G. D., Genias, I., Bernhard, D., Esper, C. D., Factor, S. A., & McKay, J. L. (2023). An explainable spatial-temporal graphical convolutional network to score freezing of gait in parkinsonian patients. Sensors, 23(4), 1766.
- Gong, N. J., Clifford, G. D., Esper, C. D., Factor, S. A., McKay, J. L., & Kwon, H. (2023). Classifying Tremor Dominant and Postural Instability and Gait Difficulty Subtypes of Parkinson’s Disease from Full-Body Kinematics. Sensors, 23(19), 8330.

### Mental Health Assessment with Remote Interviews

Refer ["Multi-modal AI System"](/research/#multi-modal-machine-learning-system-for-assessing-remote-interviews)

### Cognitive Impairment

Soon to come. _Stay tuned_

### Autism Spectrum Disorder

Soon to come. _Stay tuned_
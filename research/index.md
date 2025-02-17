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
- Zikang Leng, Amitrajit Bhattacharjee, Hrudhai Rajasekhar, Lizhe Zhang, Elizabeth Bruda, Hyeokhyen Kwon, and Thomas Plötz. 2024. IMUGPT 2.0: Language-Based Cross Modality Transfer for Sensor-Based Human Activity Recognition. Proc. ACM Interact. Mob. Wearable Ubiquitous Technol. 8, 3, Article 112 (August 2024), 32 pages. https://doi.org/10.1145/3678545

### Robust Human Activity Recognition Model with Uncertainty Modeling

{% include figure.html image="images/research/label jitter.png" width="80%" %}

Building human activity recognition model involves training a machine learning model to classify the given sensor signal feature for target activities. For the conventional supervised learning approach, discriminative sensor feature representation and accurate activity annotations are necessary to learn the robust human activity recognition model. However, acquiring accurate activity annotation is intractable due to the continuous nature of human activities. Thereby, the activity annotations have uncertainty regarding the correct temporal alignment of activity boundaries and the correctness of the actual label. We explore novel machine learning techniques to handle such uncertainties. 

- Kwon, H., Abowd, G. D., & Plötz, T. (2018, October). Adding structural characteristics to distribution-based accelerometer representations for activity recognition using wearables. In Proceedings of the 2018 ACM international symposium on wearable computers (pp. 72-75).
- Kwon, H., Abowd, G. D., & Plötz, T. (2019, September). Handling annotation uncertainty in human activity recognition. In Proceedings of the 23rd International Symposium on Wearable Computers (pp. 109-117).

{% include section.html %}

## Smart Hospital using Edge Computing and Machine Learning Framework with Multi-modal Ambient, Mobile, and Wearable Sensors

### Low-cost, Passive, and Continuous Patient Monitoring System Using Artificial Intelligence, Distributed Multi-view Camera System, and Wearables

{% include figure.html image="images/research/cep_ep6_cam_wear.png" width="90%" %}

Neurological disorders, like Alzhemer's Disease or related dementia (ADRD), can influence an individual's mobility and social interactions, offering insights into disease progression. Yet, accurately measuring intricate movements and social interactions in real-world settings is challenging, making clinicians rely on retrospective surveys. Addressing this challenge, I've introduced a cost-effective, passive, continuous patient-monitoring system capable of quantifying patients' social behaviors and movements within therapeutic facilities spanning 18,000 sqft. This system integrates multiple edge computing devices, combined with AI, cameras, and wearable sensors, to localize, track, and identify group activities. Specifically, it's applied to quantify Mild Cognitive Impairment (MCI), a preceding condition of ADRD. With minimal modification to the existing infrastructure, this system can transform standard therapeutic areas into smart environments that can evaluate conditions linked to neurological disorders at a low cost.

- H. Kwon et al., "A Feasibility Study on Indoor Localization and Multi-person Tracking Using Sparsely Distributed Camera Network with Edge Computing," in IEEE Journal of Indoor and Seamless Positioning and Navigation, doi: 10.1109/JISPIN.2023.3337189.
- C. Hegde et al., "Indoor Group Identification and Localization Using Privacy-Preserving Edge Computing Distributed Camera Network," in IEEE Journal of Indoor and Seamless Positioning and Navigation, doi: 10.1109/JISPIN.2024.3354248.
- Kiarashi et al., "Graph Trilateration for Indoor Localization in Sparsely Distributed Edge Computing Devices in Complex Environments Using Bluetooth Technology," Sensors 2023, 23, 9517.

### Transforming Education Space Using Multimodal Artificial Intelligence using Camera, Audio, and Wearables

{% include figure.html image="images/research/tcfd-vision-group-binary.png" width="60%" %}

Rapid identification and accurate documentation of interfering and high-risk behaviors in ASD, such as aggression, self-injury, disruption, and restricted repetitive behaviors, are important in daily classroom environments for tracking intervention effectiveness and allocating appropriate resources to manage care needs. However, having a staff dedicated solely to observing is costly and uncommon in most educational settings. Recently, multiple research studies have explored developing automated, continuous, and objective tools using machine learning models to quantify behaviors in ASD. However, the majority of the work was conducted under a controlled environment and has not been validated for real-world conditions. In this work, we demonstrate that the latest advances in video-based group activity recognition techniques can quantify behaviors in ASD in real-world activities in classroom environments while preserving privacy. Our explainable model could detect the episode of problem behaviors with a 77% F1-score and capture distinctive behavior features in different types of behaviors in ASD. To the best of our knowledge, this is the first work that shows the promise of objectively quantifying behaviors in ASD in a real-world environment, which is an important step toward the development of a practical tool that can ease the burden of data collection for classroom staff.

- Barun Das, Conor Anderson, Tania Villavicencio, Johanna Lantz, Jenny Foster, Theresa Hamlin, Ali Bahrami Rad, Gari D. Clifford, Hyeokhyen Kwon (2024). Explainable Artificial Intelligence for Quantifying Interfering and High-Risk Behaviors in Autism Spectrum Disorder in a Real-World Classroom Environment Using Privacy-Preserving Video Analysis. arXiv:2407.21691

### Transforming Movement Disorder Clinics Using Explainable Artificial Intelligence for Motion Capture

{% include figure.html image="images/research/xai4fog.png" width="60%" %}

Traditional methods for diagnosing and assessing Parkinson’s disease (PD) often involve thorough physical examinations by specialists in movement disorders. These methods, including the use of scales like MDS-UPDRS or patient questionnaires (N-FOG-Q), can be subjective and vary between different raters. Particularly challenging is assessing Freezing of Gait (FOG), a complex aspect of parkinsonism that significantly affects quality of life. PD is also known to manifest in different motor subtypes, mainly tremor dominant (TD) and postural instability/gait difficulty (PIGD), each presenting unique challenges in balance and gait. Previous studies have employed machine learning to analyze kinematic data from body movements during gait assessments, but these often lacked the detail necessary to fully capture the complexity of whole-body movements in PD. To address this, a new method using explainable artificial intelligence models has been developed. These models can objectively and accurately measure PD, mirroring the assessment capabilities of human specialists. They show promise in accurately identifying FOG severity levels and PD subtypes, thereby aiding in the early identification of motor subtypes and predicting disease progression. Moreover, these models can potentially discover new kinematic biomarkers for PD, offering valuable insights for clinical trials and hypothesis generation.

- Kwon, H., Clifford, G. D., Genias, I., Bernhard, D., Esper, C. D., Factor, S. A., & McKay, J. L. (2023). An explainable spatial-temporal graphical convolutional network to score freezing of gait in parkinsonian patients. Sensors, 23(4), 1766.
- Gong, N. J., Clifford, G. D., Esper, C. D., Factor, S. A., McKay, J. L., & Kwon, H. (2023). Classifying Tremor Dominant and Postural Instability and Gait Difficulty Subtypes of Parkinson’s Disease from Full-Body Kinematics. Sensors, 23(19), 8330.
- Saad, M., Hefner, S., Donovan, S., Bernhard, D., Tripathi, R., Factor, S.A., Powell, J.M., Kwon, H., Sameni, R., Esper, C.D. and McKay, J.L., 2024. Development of a Tremor Detection Algorithm for Use in an Academic Movement Disorders Center. Sensors, 24(15), p.4960.


{% include section.html %}

## Intelligent Telehealth Platforms with Fair Artificial Intelligence and Cloud Computing

### Multi-modal and Fair Machine Learning System for Assessing Remote Interviews for Underserved Populations

{% include figure.html image="images/research/multi-modal-MH.png" width="60%" %}

This research addresses the challenges in current psychiatric evaluations, which often suffer from subjectivity, bias, and the need for highly skilled professionals. The study explores the use of objective digital biomarkers, derived from behavioral and physiological signals in remote interviews, for psychiatric disorder assessment. These signals include facial and vocal expressions, linguistic content, and cardiovascular modulation. The study used a multimodal approach, evaluating each modality individually and in combination, to assess mental health status. This approach aims to make mental health assessments more objective, remote, and cost-effective. The research also critically examines the fairness of these automated mental health assessment tools across different demographics (race, gender, education level, and age). Despite their growing importance, especially in telehealth, these tools can carry biases that may lead to unfair treatment of certain groups. The study systematically evaluated and discussed the need for reporting and mitigating these biases to build trust and ensure appropriate application in clinical settings. Using a developed multimodal mental health assessment system, the study analyzed how various features (facial expressions, voice acoustics, linguistic expressions, and cardiovascular patterns) affected fairness across demographics. The findings indicated that no single modality was consistently fair for all groups. Although methods to mitigate unfairness improved fairness levels, they also highlighted a trade-off between performance and fairness. This calls for a broader moral discussion and further investigation into the ethics and application of automated mental health assessment tools.

- Jiang, Z., Seyedi, S., Griner, E., Abbasi, A., Rad, A.B., Kwon, H., Cotes, R.O. and Clifford, G.D., 2024. Multimodal Mental Health Digital Biomarker Analysis from Remote Interviews using Facial, Vocal, Linguistic, and Cardiovascular Patterns. IEEE Journal of Biomedical and Health Informatics.
- Jiang, Z., Seyedi, S., Griner, E., Abbasi, A., Rad, A.B., Kwon, H., Cotes, R.O. and Clifford, G.D. (2024) Evaluating and mitigating unfairness in multimodal remote mental health assessments. PLOS Digital Health 3(7): e0000413. https://doi.org/10.1371/journal.pdig.0000413

### Debiasing Artificial Intelligen for Monitoring Parkinson's Disease with Wearables in Underserved Populations

{% include figure.html image="images/publications/arxiv-2502.09626.png" width="60%" %}

Freezing of gait (FOG) is a debilitating feature of Parkinson's disease (PD), which is a cause of injurious falls among PD patients. Recent advances in wearable-based human activity recognition (HAR) technology have enabled the detection of FOG subtypes across benchmark datasets. Since FOG manifestation is heterogeneous, developing models that quantify FOG consistently across patients with varying demographics, FOG types, and PD conditions is important. Bias and fairness in FOG models remain understudied in HAR, with research focused mainly on FOG detection using single benchmark datasets. We evaluated the bias and fairness of HAR models for wearable-based FOG detection across demographics and PD conditions using multiple datasets and the effectiveness of transfer learning as a potential bias mitigation approach. Our evaluation using demographic parity ratio (DPR) and equalized odds ratio (EOR) showed model bias (DPR & EOR < 0.8) for all stratified demographic variables, including age, sex, and disease duration. Our experiments demonstrated that transfer learning from multi-site datasets and generic human activity representations significantly improved fairness (average change in DPR +0.027, +0.039, respectively) and performance (average change in F1-score +0.026, +0.018, respectively) across attributes, supporting the hypothesis that generic human activity representations learn fairer representations applicable to health analytics.

- Timothy Odonga, Christine D. Esper, Stewart A. Factor, J. Lucas McKay, Hyeokhyen Kwon. "On the Bias, Fairness, and Bias Mitigation for a Wearable-based Freezing of Gait Detection in Parkinson's Disease." arXiv preprint arXiv:2502.09626 (2025).

### Mobile Artificial Intelligence Systems for Assessing Gait Impairment

{% include figure.html image="images/research/mobile_phone_gait.png" width="80%" %}

Accurate diagnosis of gait impairments is often hindered by subjective or costly
assessment methods, with current solutions requiring either expensive multi-camera
equipment or relying on subjective clinical observation. There is a critical need for
accessible, objective tools that can aid in gait assessment while preserving patient
privacy. In this work, we present a mobile phone-based, privacy-preserving artificial
intelligence (AI) system for classifying gait impairments and introduce a novel dataset
of 743 videos capturing seven distinct gait patterns. The dataset consists of frontal and
sagittal views of trained subjects simulating normal gait and six types of pathological
gait (circumduction, Trendelenburg, antalgic, crouch, Parkinsonian, and vaulting),
recorded using standard mobile phone cameras. Our system achieved 86.5% accuracy
using combined frontal and sagittal views, with sagittal views generally outperforming
frontal views except for specific gait patterns like Circumduction. Model feature
importance analysis revealed that frequency-domain features and entropy measures were
critical for classifcation performance, specifically lower limb keypoints proved most
important for classification, aligning with clinical understanding of gait assessment.
These findings demonstrate that mobile phone-based systems can effectively classify
diverse gait patterns while preserving privacy through on-device processing. The high
accuracy achieved using simulated gait data suggests their potential for rapid
prototyping of gait analysis systems, though clinical validation with patient data
remains necessary. This work represents a significant step toward accessible, objective
gait assessment tools for clinical, community, and tele-rehabilitation settings.

- Reddy, Lauhitya, Ketan Anand, Shoibolina Kaushik, Corey Rodrigo, J. Lucas McKay, Trisha M. Kesar, and Hyeokhyen Kwon. "Classifying Simulated Gait Impairments using Privacy-preserving Explainable Artificial Intelligence and Mobile Phone Videos." arXiv preprint arXiv:2412.01056 (2024).

{% include section.html %}

## Behavior Analytics for Health Assessments

### Parkinson's Disease

- [Movement clinic with AI](/research/#transforming-movement-disorder-clinics-using-explainable-artificial-intelligence-for-motion-capture)
- [Wearables for Parkinson's Disease](/research/#debiasing-artificial-intelligen-for-monitoring-parkinsons-disease-with-wearables-in-underserved-populations)

### Stroke survivors

- [Mobile AI for Stroke](/research/#mobile-artificial-intelligence-systems-for-assessing-gait-impairment)

### Mental Health and Depression

- ["Multi-modal AI System"](/research/#multi-modal-machine-learning-system-for-assessing-remote-interviews)

### Autism Spectrum Disorder

- ["Classroom with AI"](/research/#transforming-education-space-using-multimodal-artificial-intelligence-using-camera-audio-and-wearables)

### Cognitive Impairment, Alzheimer's Disease, and Dementia

{% include figure.html image="images/publications/cep_ep6_vision_only_moca.png" width="50%" %}

Mild cognitive impairment (MCI) is characterized by a decline in cognitive functions beyond typical age and education-related expectations. Since, MCI has been linked to reduced social interactions and increased aimless movements, we aimed to automate the capture of these behaviors to enhance longitudinal monitoring.
Using a privacy-preserving distributed camera network, we collected movement and social interaction data from groups of individuals with MCI undergoing therapy within a 1700$m^2$ space. 
We developed movement and social interaction features, which were then used to train a series of machine learning algorithms to distinguish between higher and lower cognitive functioning MCI groups.
A Wilcoxon rank-sum test revealed statistically significant differences between high and low-functioning cohorts in features such as linear path length, walking speed, change in direction while walking, entropy of velocity and direction change, and number of group formations in the indoor space.
Despite lacking individual identifiers to associate with specific levels of MCI, a machine learning approach using the most significant features provided a 71\% accuracy.  
We provide evidence to show that a privacy-preserving low-cost camera network using edge computing framework has the potential to distinguish between different levels of cognitive impairment from the movements and social interactions captured during group activities.

- Hegde, Chaitra, Yashar Kiarashi, Allan I. Levey, Amy D. Rodriguez, Hyeokhyen Kwon, and Gari D. Clifford. "Feasibility of assessing cognitive impairment via distributed camera network and privacy-preserving edge computing." arXiv preprint arXiv:2408.10442 (2024).
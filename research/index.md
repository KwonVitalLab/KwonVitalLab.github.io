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
  text="Clinics with Multimodal AI"
  link="research/#behavior-sensing-in-clinics-using-edge-and-cloud-ai-with-video-audio-and-wearable-sensors"
%}

{%
  include button.html
  type="link"
  icon=""
  text="Telehealth with Ethical AI"
  link="research/#ethical-artificial-intelligence-for-remote-interviews-or-wearables"
%}


{%
  include button.html
  type="link"
  icon=""
  text="Mobile Computer Vision"
  link="research/#mobile-computer-vision-and-closed-loop-intervention-systems-for-motion-assessments-and-rehabilitation"
%}

<!-- [Machine Learning for Human Activity Recognition](#machine-learning-for-human-activity-recognition) 

[Edge Computing and Machine Learning Framework Using Multi-modal Ambient, Mobile, and Wearable Sensors](#edge-computing-and-machine-learning-framework-using-multi-modal-ambient-mobile-and-wearable-sensors)

[Behavior Analytics for Health Assessments](#behavior-analytics-for-health-assessments)
-->



{% include section.html %}

## Generative AI and Cross-modality Techniques for Human Activity Recognition

{% include figure.html image="images/research/crossmodalHAR.png" width="80%" %}

In addressing the challenges of building a human activity recognition model with limited wearable sensor data, we proposed a novel method utilizing vast video and textual data resources to generate a comprehensive training dataset. This cross-modality transfer learning technique harnesses state-of-the-art computer vision algorithms to interpret human motions from videos or Large Language Models to create text descriptions of human activities, eventually generating virtual inertial measurement signals for model training. The resulting model, trained on this rich dataset, can tackle real-world applications. Additionally, we introduced an innovative training scheme to account for the inherent uncertainties in activity annotations. This is complemented by a novel sensor feature representation that effectively captures the structural and distributional nuances of sensor signals, capturing human activity, enhancing the model's robustness.

- Kwon, H., Tong, C., Haresamudram, H., Gao, Y., Abowd, G. D., Lane, N. D., & Ploetz, T. (2020). IMUTube: Automatic extraction of virtual on-body accelerometry from video for human activity recognition. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 4(3), 1-29.
- Zikang Leng, Amitrajit Bhattacharjee, Hrudhai Rajasekhar, Lizhe Zhang, Elizabeth Bruda, Hyeokhyen Kwon, and Thomas Plötz. 2024. IMUGPT 2.0: Language-Based Cross Modality Transfer for Sensor-Based Human Activity Recognition. Proc. ACM Interact. Mob. Wearable Ubiquitous Technol. 8, 3, Article 112 (August 2024), 32 pages. https://doi.org/10.1145/3678545
- Kwon, H., Abowd, G. D., & Plötz, T. (2018, October). Adding structural characteristics to distribution-based accelerometer representations for activity recognition using wearables. In Proceedings of the 2018 ACM international symposium on wearable computers (pp. 72-75).
- Kwon, H., Abowd, G. D., & Plötz, T. (2019, September). Handling annotation uncertainty in human activity recognition. In Proceedings of the 23rd International Symposium on Wearable Computers (pp. 109-117).

{% include section.html %}

## Behavior Sensing in Clinics using Edge and Cloud AI with Video, Audio, and Wearable Sensors

{% include figure.html image="images/research/cep_ep6_cam_wear.png" width="80%" %}

Neurological disorders impact mobility and social interaction, yet continuous and passive monitoring and assessment remain difficult, often relying on clinicians’ observations. To address this, a cost-effective multimodal monitoring system was developed using edge computing, AI, cameras, microphones and wearables to track movement and social behavior in therapeutic spaces, particularly for Mild Cognitive Impairment (MCI). Similarly, in autism spectrum disorder (ASD), video and wearable-based systems have shown promise in detecting challenging behaviors like aggression in classrooms, while preserving privacy. For Parkinson’s disease (PD), explainable AI models now offer objective assessments of motor subtypes, tremors, and Freezing of Gait (FOG), surpassing traditional subjective methods and potentially uncovering new biomarkers for early diagnosis and clinical research.

- Hegde, C., Kiarashi, Y., Levey, A. I., Rodriguez, A. D., Kwon, H., & Clifford, G. D. (2025). Feasibility of assessing cognitive impairment via distributed camera network and privacy‐preserving edge computing. Alzheimer's & Dementia: Diagnosis, Assessment & Disease Monitoring, 17(1), e70085.
- Barun Das, Conor Anderson, Tania Villavicencio, Johanna Lantz, Jenny Foster, Theresa Hamlin, Ali Bahrami Rad, Gari D. Clifford, Hyeokhyen Kwon (2024). Explainable Artificial Intelligence for Quantifying Interfering and High-Risk Behaviors in Autism Spectrum Disorder in a Real-World Classroom Environment Using Privacy-Preserving Video Analysis. arXiv:2407.21691
- Rad, A. B., Villavicencio, T., Kiarashi, Y., Anderson, C., Foster, J., Kwon, H., ... & Clifford, G. D. (2025). From motion to emotion: exploring challenging behaviors in autism spectrum disorder through analysis of wearable physiology and movement. Physiological Measurement, 13(1), 015004.
- Kwon, H., Clifford, G. D., Genias, I., Bernhard, D., Esper, C. D., Factor, S. A., & McKay, J. L. (2023). An explainable spatial-temporal graphical convolutional network to score freezing of gait in parkinsonian patients. Sensors, 23(4), 1766.

{% include section.html %}

## Ethical Artificial Intelligence for Remote Interviews or Wearables

{% include figure.html image="images/research/ethical_ai.png" width="80%" %}

We developed multimodal machine learning systems that analyze facial, vocal, linguistic, and cardiovascular signals from remote interviews to enhance psychiatric evaluations through objective digital biomarkers. While addressing demographic bias, the system effectively detects conditions like depression, cognitive impairment, social isolation, and psychological well-being. We also developed wearable-based models for monitoring gaits in Parkinson’s disease with transfer learning from diverse datasets, improving generalizability for varying demographics and disease conditions.

- Jiang, Z., Seyedi, S., Griner, E., Abbasi, A., Rad, A.B., Kwon, H., Cotes, R.O. and Clifford, G.D., 2024. Multimodal Mental Health Digital Biomarker Analysis from Remote Interviews using Facial, Vocal, Linguistic, and Cardiovascular Patterns. IEEE Journal of Biomedical and Health Informatics.
- Jiang, Z., Seyedi, S., Griner, E., Abbasi, A., Rad, A.B., Kwon, H., Cotes, R.O. and Clifford, G.D. (2024) Evaluating and mitigating unfairness in multimodal remote mental health assessments. PLOS Digital Health 3(7): e0000413. https://doi.org/10.1371/journal.pdig.0000413
- Mu, X., Seyedi, S., Zheng, I., Jiang, Z., Chen, L., Omofojoye, B., ... & Kwon, H. (2024). Detecting Cognitive Impairment and Psychological Well-being among Older Adults Using Facial, Acoustic, Linguistic, and Cardiovascular Patterns Derived from Remote Conversations. arXiv preprint arXiv:2412.14194.
- Timothy Odonga, Christine D. Esper, Stewart A. Factor, J. Lucas McKay, Hyeokhyen Kwon. "On the Bias, Fairness, and Bias Mitigation for a Wearable-based Freezing of Gait Detection in Parkinson's Disease." arXiv preprint arXiv:2502.09626 (2025).

## Mobile Computer Vision and Closed-loop Intervention Systems for Motion Assessments and Rehabilitation

{% include figure.html image="images/research/mobileComputerVision.png" width="60%" %}

We developed mobile AI systems to improve motor assessment and rehabilitation. A mobile phone-based, privacy-preserving system classifies various gait impairment patterns, demonstrating the potential for accessible gait analysis in clinical and tele-rehabilitation settings. We also developed a closed-loop neurostimulation system that integrates real-time video-based movement classification on webcam with wireless transcutaneous vagus nerve stimulation (tVNS), automatically triggering stimulation during rehabilitation exercises, showcasing a promising step toward patient-driven, home-based motor rehabilitation.

- Reddy, Lauhitya, Ketan Anand, Shoibolina Kaushik, Corey Rodrigo, J. Lucas McKay, Trisha M. Kesar, and Hyeokhyen Kwon. "Classifying Simulated Gait Impairments using Privacy-preserving Explainable Artificial Intelligence and Mobile Phone Videos." arXiv preprint arXiv:2412.01056 (2024).
- Minoru Shinohara, Arya Mohan, Nathaniel Green, Joshua N. Posen, Milka Trajkova, Woon-Hong Yeo, Hyeokhyen Kwon, "Closed-loop Neuromotor Training System Pairing Transcutaneous Vagus Nerve Stimulation with Video-based Real-time Movement Classification", medRxiv 2025.05.23.25327218; doi: https://doi.org/10.1101/2025.05.23.25327218

{% include section.html %}



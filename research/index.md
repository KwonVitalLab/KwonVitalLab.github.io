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
  text="Ambient AI in Clinic"
  link="research/#behavior-sensing-in-clinics-using-ambient-ai-with-video-and-wearable-sensors"
%}

{%
  include button.html
  type="link"
  icon=""
  text="Wearable AI at Home"
  link="research/#behavior-sensing-with-wearables-at-home"
%}

{%
  include button.html
  type="link"
  icon=""
  text="Mobile Computer Vision"
  link="research/#mobile-computer-vision-and-closed-loop-intervention-systems-for-motion-assessments-and-rehabilitation"
%}

{%
  include button.html
  type="link"
  icon=""
  text="Multimodal AI for Mental Health Interview"
  link="research/#faical-expression-speech-language-cardiovascular-signal-analysis-in-remote-mental-health-interviews"
%}




<!-- [Machine Learning for Human Activity Recognition](#machine-learning-for-human-activity-recognition) 

[Edge Computing and Machine Learning Framework Using Multi-modal Ambient, Mobile, and Wearable Sensors](#edge-computing-and-machine-learning-framework-using-multi-modal-ambient-mobile-and-wearable-sensors)

[Behavior Analytics for Health Assessments](#behavior-analytics-for-health-assessments)
-->



{% include section.html %}

## Generative AI and Cross-modality Techniques for Human Activity Recognition

{% include figure.html image="images/research/har.png" width="70%" %}

In addressing the challenges of building a human activity recognition model with limited wearable sensor data, we proposed a novel method utilizing vast video and textual data resources to generate a large-scale training dataset. This cross-modality transfer learning technique harnesses state-of-the-art computer vision algorithms to interpret human motions from videos or Large Language Models to create text descriptions of human activities, eventually generating virtual inertial measurement signals that can be used for model training. The resulting model, trained on this rich dataset, can tackle real-world applications. Additionally, we introduced an innovative training scheme to account for the inherent uncertainties in activity annotations. This is complemented by a novel sensor feature representation that effectively captures the structural and distributional nuances of sensor signals, capturing human activity, enhancing the model's robustness.

- Kwon, H., Tong, C., Haresamudram, H., Gao, Y., Abowd, G. D., Lane, N. D., & Ploetz, T. (2020). IMUTube: Automatic extraction of virtual on-body accelerometry from video for human activity recognition. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 4(3), 1-29.
- Zikang Leng, Amitrajit Bhattacharjee, Hrudhai Rajasekhar, Lizhe Zhang, Elizabeth Bruda, Hyeokhyen Kwon, and Thomas Plötz. 2024. IMUGPT 2.0: Language-Based Cross Modality Transfer for Sensor-Based Human Activity Recognition. Proc. ACM Interact. Mob. Wearable Ubiquitous Technol. 8, 3, Article 112 (August 2024), 32 pages. https://doi.org/10.1145/3678545
- Kwon, H., Abowd, G. D., & Plötz, T. (2018, October). Adding structural characteristics to distribution-based accelerometer representations for activity recognition using wearables. In Proceedings of the 2018 ACM international symposium on wearable computers (pp. 72-75).
- Kwon, H., Abowd, G. D., & Plötz, T. (2019, September). Handling annotation uncertainty in human activity recognition. In Proceedings of the 23rd International Symposium on Wearable Computers (pp. 109-117).

{% include section.html %}

## Behavior Sensing in Clinics using Ambient AI with Video and Wearable Sensors

{% include figure.html image="images/research/ambient.png" width="70%" %}

Our work explores how smart, privacy-preserving camera and sensor systems can monitor cognitive and social behaviors in real-world clinical settings. Focusing on mild cognitive impairment (MCI), we used edge-computing camera networks and Bluetooth beacons in a large therapeutic facility to detect differences in movement and social interactions between high- and low-functioning individuals. A novel method was also developed to identify when and where group activities occur in indoor spaces using lightweight pose detection, with high accuracy. The system was scalable, low-cost, and effective in localizing and tracking people while preserving privacy. Further, the 3D kinematics motion analysis technologies were adapted to objectively measure freezing of gait in Parkinson’s patients using explainable deep learning in a motion analysis laboratory in academic clinics. A video-based group activity analysis system could identify problematic behaviors in students with autism in real-world special education classroom. Together, these studies demonstrate the promise of edge AI systems for passive, real-time monitoring of cognitive and behavioral health across diverse populations and environments.

- Hegde, C., Kiarashi, Y., Levey, A. I., Rodriguez, A. D., Kwon, H., & Clifford, G. D. (2025). Feasibility of assessing cognitive impairment via distributed camera network and privacy‐preserving edge computing. Alzheimer's & Dementia: Diagnosis, Assessment & Disease Monitoring, 17(1), e70085.
- Hegde, C., Kiarashi, Y., Rodriguez, A. D., Levey, A. I., Doiron, M., Kwon, H., & Clifford, G. D. (2024). Indoor Group Identification and Localization Using Privacy-Preserving Edge Computing Distributed Camera Network. IEEE journal of indoor and seamless positioning and navigation, 2, 51-60.
- Kwon, H., Hegde, C., Kiarashi, Y., Madala, V. S. K., Singh, R., Nakum, A., ... & Clifford, G. D. (2023). A feasibility study on indoor localization and multiperson tracking using sparsely distributed camera network with edge computing. IEEE Journal of Indoor and Seamless Positioning and Navigation, 1, 187-198.
- Barun Das, Conor Anderson, Tania Villavicencio, Johanna Lantz, Jenny Foster, Theresa Hamlin, Ali Bahrami Rad, Gari D. Clifford, Hyeokhyen Kwon (2024). Explainable Artificial Intelligence for Quantifying Interfering and High-Risk Behaviors in Autism Spectrum Disorder in a Real-World Classroom Environment Using Privacy-Preserving Video Analysis. arXiv:2407.21691
- Kwon, H., Clifford, G. D., Genias, I., Bernhard, D., Esper, C. D., Factor, S. A., & McKay, J. L. (2023). An explainable spatial-temporal graphical convolutional network to score freezing of gait in parkinsonian patients. Sensors, 23(4), 1766.

{% include section.html %}

## Behavior Sensing with Wearables at Home

{% include figure.html image="images/research/wearables.png" width="60%" %}

We are exploring how wearable sensors and thoughtful home design can help detect and support cognitive and behavioral challenges in people with conditions like Parkinson’s disease (PD), autism spectrum disorder (ASD), and mild cognitive impairment (MCI). In Parkinson’s, they found that existing activity recognition models used to detect "freezing of gait" (FOG) can be biased by age, sex, and disease stage, but fairness and accuracy improved using transfer learning from diverse datasets. In children with ASD, wearable devices tracking movement and physiological signals like skin temperature were able to detect behaviors like self-injury in everyday settings, offering a real-world way to support care. For older adults with MCI, wearables helped identify functional differences in kitchen tasks—like weaker upper body movements and delayed eye movements—highlighting how behavior reflects cognitive decline. They also found that open kitchen shelving slightly improved motivation and task efficiency, though personal aesthetic preferences still mattered. Overall, these studies show how wearable technology and personalized environments can offer practical, real-world support for people facing cognitive and behavioral health challenges.

- Odonga, T., Esper, C. D., Factor, S. A., McKay, J. L., & Kwon, H. (2025). On the Bias, Fairness, and Bias Mitigation for a Wearable-based Freezing of Gait Detection in Parkinson's Disease. arXiv preprint arXiv:2502.09626.
- Rad, A. B., Villavicencio, T., Kiarashi, Y., Anderson, C., Foster, J., Kwon, H., ... & Clifford, G. D. (2025). From motion to emotion: exploring challenging behaviors in autism spectrum disorder through analysis of wearable physiology and movement. Physiological Measurement, 13(1), 015004.
- Ibrahim Bilau, Bonwoo Koo, Esther Fu, Wendy Chau, Hyeokhyen Kwon, Eunhwa Yang, Visual Accessibility through Open Shelving: Impacts on Cognitive Load, Motivation, Physical Activity, and User Perception in Older Adults with Mild Cognitive Impairment, medRxiv 2025.05.21.25328033; doi: https://doi.org/10.1101/2025.05.21.25328033
- Bonwoo Koo, Ibrahim Bilau, Amy D. Rodriguez, Eunhwa Yang, Hyeokhyen Kwon, Quantifying Mild Cognitive Impairments in Older Adults Using Multi-modal Wearable Sensor Data in a Kitchen Environment, medRxiv 2025.05.24.25328107; doi: https://doi.org/10.1101/2025.05.24.25328107

{% include section.html %}


## Mobile Computer Vision and Closed-loop Intervention Systems for Motion Assessments and Rehabilitation

{% include figure.html image="images/research/mobileComputerVision.png" width="60%" %}

We developed mobile AI systems to improve motor assessment and rehabilitation. A mobile phone-based, privacy-preserving system classifies various gait impairment patterns, demonstrating the potential for accessible gait analysis in clinical and tele-rehabilitation settings. We also developed a closed-loop neurostimulation system that integrates real-time video-based movement classification on webcam with wireless transcutaneous vagus nerve stimulation (tVNS), automatically triggering stimulation during rehabilitation exercises, showcasing a promising step toward patient-driven, home-based motor rehabilitation.

- Reddy, Lauhitya, Ketan Anand, Shoibolina Kaushik, Corey Rodrigo, J. Lucas McKay, Trisha M. Kesar, and Hyeokhyen Kwon. "Classifying Simulated Gait Impairments using Privacy-preserving Explainable Artificial Intelligence and Mobile Phone Videos." arXiv preprint arXiv:2412.01056 (2024).
- Minoru Shinohara, Arya Mohan, Nathaniel Green, Joshua N. Posen, Milka Trajkova, Woon-Hong Yeo, Hyeokhyen Kwon, "Closed-loop Neuromotor Training System Pairing Transcutaneous Vagus Nerve Stimulation with Video-based Real-time Movement Classification", medRxiv 2025.05.23.25327218; doi: https://doi.org/10.1101/2025.05.23.25327218

{% include section.html %}


## Faical Expression, Speech, Language, cardiovascular signal Analysis in Remote Mental Health Interviews

{% include figure.html image="images/research/remote_interview.png" width="80%" %}

We are developing novel machine learning tools that use audio, video, language, and heart rate data from remote interviews to help detect mental health conditions and cognitive decline in older adults. These tools can assess risks like dementia, depression, anxiety, social isolation, and personality traits like neuroticism, using features like facial expressions, speech patterns, and cardiovascular signals. Studies also showed that different data types—like speech for cognitive issues and heart rate for mental health—play unique roles. However, fairness remains a concern, as detection accuracy can vary across demographic groups like race, age, and education. While methods like post-training calibration can reduce these biases, they come with the cost of reduced performance. Overall, these tools show promise for affordable, remote mental health and cognitive screening, but continued attention to fairness and clinical integration is critical.

- Jiang, Z., Seyedi, S., Griner, E., Abbasi, A., Rad, A.B., Kwon, H., Cotes, R.O. and Clifford, G.D., 2024. Multimodal Mental Health Digital Biomarker Analysis from Remote Interviews using Facial, Vocal, Linguistic, and Cardiovascular Patterns. IEEE Journal of Biomedical and Health Informatics.
- Jiang, Z., Seyedi, S., Griner, E., Abbasi, A., Rad, A.B., Kwon, H., Cotes, R.O. and Clifford, G.D. (2024) Evaluating and mitigating unfairness in multimodal remote mental health assessments. PLOS Digital Health 3(7): e0000413. https://doi.org/10.1371/journal.pdig.0000413
- Mu, X., Seyedi, S., Zheng, I., Jiang, Z., Chen, L., Omofojoye, B., ... & Kwon, H. (2024). Detecting Cognitive Impairment and Psychological Well-being among Older Adults Using Facial, Acoustic, Linguistic, and Cardiovascular Patterns Derived from Remote Conversations. arXiv preprint arXiv:2412.14194.
- Qin, R., Yang, K., Abbasi, A., Dobolyi, D., Seyedi, S., Griner, E., Kwon, H., Cotes, R., Jiang, Z., Clifford, G. and Cook, R.A., 2025. Language models for online depression detection: A review and benchmark analysis on remote interviews. ACM Transactions on Management Information Systems, 16(2), pp.1-35.
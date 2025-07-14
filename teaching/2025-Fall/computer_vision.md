---
title: Computer Vision
description: Long version
---

# BMI/CS XXX - Computer Vision

{:.center}
**The course is cross-listed in both BMIXXX and CSXXX, so please register for the one with available seats.**

### Instructor:

Hyeokhyen Kwon, Ph.D. \
Assistant Professor \
Department of Biomedical Informatics \
Office: Rm 4105, 4th Floor, Emory Woodruff Memorial Research Building (101 Woodruff Cir, Atlanta, GA 30322)

Teaching Assistant: TBD ([mail](mailto:XXX@emory.edu))

## Course Overview

Computer vision is integral to many aspects of modern society, including autonomous vehicles, YouTube content analysis, mobile phone filters, and robotics. In this course, students will learn the basics of image formation, camera imaging geometry, feature detection and matching, stereo vision, motion estimation, convolutional networks, image classification, segmentation, object detection, 3D computer vision, transformers, generative computer vision, and applications in ubiquitous computing and healthcare.
The course also covers multi-view geometry and both classical and advanced machine learning techniques for various computer vision applications. The primary focus is to develop students' engineering and mathematical intuition through lectures and project assignments, equipping them with fundamental skills in computer vision.

### Learning Objectives

Upon completion of this course, students should be able to:
- Identify and explain both the theoretical and practical elements of image computing, linking challenges in Computer Vision to those in Human Vision.
- Outline the principles of image formation and analysis, and grasp the fundamentals of 2D and 3D Computer Vision.
- Gain knowledge of the key technical methods in computer vision, detailing various techniques for image registration, alignment, and matching.
- Explore advanced topics such as object categorization and image segmentation.
- Develop applications using computer vision techniques.


### Prerequisites:

No prior experience with computer vision is required, though familiarity with visual computing or signal processing is beneficial. The following skills are essential for this course:

- **Data Structures**: You'll need to write code that creates representations of images, features, and geometric constructs.
- **Programming**: Projects will be done and assessed in Python and PyTorch. All starter code will be provided in Python. TAs will assist with Python-related queries. If you're new to Python, that's fine as long as you have programming experience, but you may need to catch up compared to other students.
- **Math**: Knowledge of linear algebra, vector calculus, and probability is necessary. Linear algebra is particularly crucial, and students without a background in it have struggled previously. For a refresher on linear algebra, refer to Prof. [Gilbert Strang's lectures](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/video_galleries/video-lectures/).

- (Optional) Permission by the instructor (Send an email to the [instructor](mailto:hyeokhyen.kwon@emory.edu))

### Compute Requirements

Emory University has set [minimum computing requirements](https://ats.emory.edu/sdl/student-resources/student_technology_recommendations.html) for all students, which you must meet. However, the projects are quite compute-intensive, so having a faster machine will allow you to iterate more quickly. Unfortunately, the institute's requirements do not mention GPUs. While deep learning projects can benefit from a local GPU, it is not mandatory. Since we cannot assume all students have access to GPUs, projects will utilize cloud services like Google Colab.

## Course Logistics

### Communication & Course Materials:

- **Canvas:** \
The class syllabus, schedule, lecture slides, homework handouts/files, discussion, and grades are posted on this platform. 
Please ask all questions under the discussions section of Canvas. You are encouraged to answer other students’ questions when you know the answer. Do not ask or answer questions that are exactly homework questions.


- **Email:** \
If there are private matters specific to you (e.g., special accommodations, requesting alternative arrangements, etc.) or confidential matters you want to report, please email with the subject heading starting with “[CSXXX] or [BMIXXX]”. I probably will not respond immediately but will try to respond within 24 hours(during specific busy periods I may need 48 hours). It is best to avoid last-minute questions that require immediate attention (e.g., before a deadline!). Plan accordingly.

- **Office Hours:**
  - Instructor (Hyeokhyen Kwon): XXX. X - X pm @ Instuctor's office / [Zoom](https://zoom.us/j/2097437412?pwd=NXVuYkwwQlVIUlhEM2Z3dGkwT1I0dz09)
  - TA (TBD): Thursdays (3-5 pm) @ BMI classroom / [Zoom](XXX)

- **Remote Attendance:** \
  - You can attend remotely only if necessary. This has to be communicated with the instructor and TA at least a week before. 
  - [Zoom](XXX)

### Textbook(s):

- "Computer Vision: Algorithms and Applications, 2nd ed.", by Richard Szeliski, 2022, The University of Washington (The book is available for purchase, but is also free to download from this [link](https://szeliski.org/Book/))

### Acknowledgements

- The class materials heavily utilize slides created by other instructors, notably Derek Hoiem, James Hays, Svetlana Lazebnik, and Meera Hahn. Each slide set and assignment includes proper acknowledgements

## Expectations & Grading:

The final grade will be determined by a weighted average of all the graded items. 

Component   | Weight |
--------- | ------ |
Participation  |  10% |
Homeworks   | 40%  |
Midterm   | 20%    |
Project | 30% |

Final grades may be curved up so that the class mean falls at least in a B range. The class median, mean, and standard deviation will be announced for each assignment and exam so that you have an idea of where you stand.


- **Class participation, punctuality, and attendance (10%):** 

  This is not based on attendance, even if you show up for all classes you can still get a 0. The goal is to encourage class participation and active dialogue. 
  This can be achieved in several different fashions:
  - Asking questions in class, during office hours (TAs or instructor), or on Canvas discussion
  - Answering my questions in class
  - Participating in-class exercises and projects.
  - Reviewing the lecture slides and corresponding readings/references after each class
  - Attend office hours and contribute to the discussion, i.e. asking and answering other students’ questions


- **Homework (40%):** 
  
  - One assignment will be assigned for every topic to check if you keep up with the materials.
  - Discussions are allowed; however, your work must be original.
  - Late submissions: You will lose 10% each day for late projects. 
  - You will receive zero credit for more than one week delays.
  - Additional extensions on homework will be granted with appropriate documentation.
  <!-- Solutions for written homework will be reviewed in class after all students submit homework, including late submissions. -->


- **Midterm (15%):** 

  The midterm must be taken at the required time. Rescheduling the midterm is only permitted in emergencies. There will be no final exam so you can focus on the final project

- **Project (40%)** \
  This is a critical part of the course.
  The semester-long team project is designed to provide you with practical experience in data handling, implementation, designing validation experiments, and teamwork and
  The goal of the project is to apply computer vision techniques to real-world tasks or to prepare you for computer vision-related research and project management.


  *Topic*: \
  The project topic is open-ended, but needs to be within the scope of the computer vision techniques or their applications. \
  It can be an application project or an algorithmic project (developing a new learning algorithm or a novel variant of an existing state-of-the-art). \
  Each team can select any problem and dataset, provided that the problem and tasks haven't been solved in the latest papers for the dataset.
  This means that for your proposed topic, you will need to study state-of-the-art papers and provide a justification for why it is interesting. \
  There is a strong preference for using a publicly available dataset. If you intend to collect the needed data yourself, keep in mind this is only one part of the expected project work and can often take considerable time. \
  Also, the topic can be related to your research interest, but *DO NOT* select graduate research mentored by your advisor as your topic.

  *Team size*: \
  You will work in groups of 2-3 for the final project.

  *Evaluation*: \
  Each team has four deliverables:
    - Proposal (15%)
    - Spotlight: a short “madness” presentation (10%)
    - Final presentation (25%)
    - Final report. (50%)


  The team size will also be taken under consideration when evaluating the scope of the project in breadth and depth, meaning that a 3-person team is expected to accomplish more than a 2-person team. \
  Teammates will score each other's contributions, and each student's final project grade will be weighted using this feedback.
  A fair distribution of work is achieved when each team member has an equal amount of work.

  *Project Proposal*: \
  For the proposal, your group will pick a topic and receive feedback from the instructor. Your proposal should be a type-set PDF document that contains approximately 1-2 pages worth of material. 
  You can also copy and use this [overleaf template](https://www.overleaf.com/read/ktprdzqxsndf#7dcf5f) for Project Proposal.
  
  It should have the following parts:
  - Format & Contents
    - Title of the project.
    - Full names of all team members
    - Description of the problem and the data. \
      Explain the aim of your project. What will be the criteria for the success of your project?
      For example, it can be achieving a certain level of performance metric (accuracy, f1 score, roc curve) for your problem.
      If you are using an existing benchmark dataset (e.g., Kaggle competition), it is not sufficient to provide just the link.
      To ensure that the proposal is self-complete, it's important to provide a summary of the dataset description that is easily understandable by others. 
    - Description of what you plan to do and how your work is different than existing other work on this dataset/domain. \
      - what are the computer vision methods you plan to apply or improve on?
      - What are the experiments you plan to run and how do you plan to evaluate the algorithms?

      You are not obligated to stick to what you propose, but this is to ensure you've done the appropriate literature search and have an initial plan of attack.


    - Potential Pitfalls and Mitigation Strategies. \
      What are the potential challenges you foresee in your projects to achieve your aims?
      Provide a short list of the challenges and mitigation plans to overcome the challenge.
      This is to help you think through the backup plans.

    - Timeline
      - Weekly plans of your research.
      - Specify who will do what in each timeline.
      - Do not forget to include times for writing the research paper and preparing for the final presentation


    - Short list of references. \
      The relevant articles need to be cited in the main text accordingly.


  - Grading \
    The project proposal is mainly intended to make sure you decide on a project topic, think about the initial steps to take, and get feedback early. As long as your proposal follows the instructions above and the project seems reasonably well-thought-out, you should do well on the proposal.


  *Spotlight*: \
  For the spotlight, each team will give a 1 to 2-slide, 90-second talk to convey an overview of their project. This gives each team a chance to experience talking to a large audience and get some presentation feedback while also getting an idea of what all the other teams are working on.


  - Format \
    1 Powerpoint presentation slide (PPT) that will auto-advance to the next slide.


  - Grading \
    Each team will be scored by the other teams and the instructor based on clarity, problem motivation, quality of the content, and overall presentation quality. The scoring rubric where the full score is 10 will be based on the following:


    - Overview + motivation (3):
      - Is the problem well described and motivated?
      - Is the problem novel and challenging?


    - Methodology (5):
      - Is the approach well described and justified?
      - What do the dataset/features look like?
      - What are the preprocessing, models, metrics, and evaluation methodology?
      - How does it compare to existing work?
      - Is the potential pitfall and mitigation strategy justified?

    - Presentation/slide quality and clarity (2):
      - Is the presentation clear, coherent, and compelling?


  *Presentation*: \
  For the presentation, each team will give a ~10-15 minute talk (depending on the number of groups and group size).


  - Format \
    Slides with content that motivate the problem, the approach, and the experimental results. A PDF version of the slides will be submitted to Canvas.


  - Grading \
    Each team will be scored by the other teams and the instructor based on clarity, problem motivation, quality of the content, and overall presentation quality. The scoring rubric will be based on the following:


    - Problem overview and motivation (20%):
      - Is the problem well described and motivated?
      - Is the problem novel and challenging?

    - Methodology (40%):
      - Is the approach well described and justified?
      - What do the dataset/features look like?
      - What are the preprocessing, models, metrics, and evaluation methodology?
      - How does it compare to existing work?


    - Preliminary results (20%):
      - Are there any preliminary results or findings for preprocessing and the selected models?
      - How does the result compare to existing work (if any)?
      - Is the project on track to deliver?
      - Is the future work clear and justified?


    - Presentation/slide quality and clarity (20%):
      - Is the presentation clear, coherent, and compelling?


  *Report* \
  Each team will submit a final project report. If you did this work in collaboration with someone else, or if someone else (such as another professor) had advised you on this work, your write-up must fully acknowledge their contributions.
  You can also copy and use this [overleaf template](https://www.overleaf.com/read/vcfkhrmcjdvp#738148) for Project Report.


  - Format \
    A typeset PDF document that is between 6-12 pages (single columns and no smaller than 11-point font) with unlimited pages for references. Suggested length (not required): 6-8 pages for 2-person teams, 10-12 pages for 3-person teams. The typical (but not always obligatory) ingredients of a project report are:


    - Abstract:
      - 1 paragraph
    - Introduction:
      - What is the problem being addressed?
      - Why is it important?
      - Overview and high-level rationale of your approach.
      - Highlight the novelty, key contributions, or significance of your project.
    - Background:
      - Past related work on the problem done by others.
    - Methods:
      - Describe your learning algorithms or proposed algorithm(s).
      - Introduce any relevant mathematical notation if needed.
      - For each algorithm, give a short description of how it works.
      - For algorithms covered in class, this can be 1-3 sentences to convey why it might be useful for this problem.
      - If you are using a niche or cutting-edge algorithm, you may want to explain your algorithm in 1-2 paragraphs
    - Experiments:
      - Data description
      - Plan for Exploratory data analysis, preprocessing, feature extraction, and feature selection:
        - Enough to ensure your experiments can be replicated by others
      - Modeling choices:
        - What models did you select? Why?
        - How were parameters determined?
        - Other design choices such as subsampling, oversampling, etc.
      - Evaluation plan:
        - What is the cross-validation approach and metric you used to evaluate the model? Why?
        - If any, what is your baseline method to compare with the proposed method?
    - Result:
      - Empirical results and comparisons (figures and tables)
    - Discussion:
      - What are the key findings and lessons learned from the experiment?
      - What are the limitations of this work?
      - What are the future work or applications for this work based on the findings?
    - Conclusion:
      - Summary of motivation, contribution, experiment result, findings, and future work
      - 1 paragraph
    - Team contributions
      - What did each team member work on for the project?
      - What are the percentages (%) of the contributions of each team member?
    - Code/Dataset:
      - Include the link to a Github repository, Google Drive folder, or Dropbox folder with the code and dataset
      - The code should be executable standalone with the provided dataset. So, provide an execution script and description for the instructor and TA to run the code and check results efficiently.
      - Include the comments on the code for the instructor and TA to understand the process of the code.
      - The result in the report should be replicable. This means that, if you are using any random function in your model or experiment, the final version should fix the random seed for the replication.
  - Grading \
    The final report will be judged based on the clarity of the report, the novelty of the problem, the technical quality, the analysis, and the significance of the work. The major components include a clear motivation and description of the project goals, the chosen methodologies (preprocessing and computer vision techniques), the presentation and evaluation of the results, replicability of the results (is the description such that someone well-versed in computer vision could obtain similar results on the same dataset), insights from the project and analysis of the results, appropriate/relevant reference list, and the quality of the writing (grammar and style).


## University Policies and Academic Integrity

Any suspected violations of course rules or the Emory's Honor Codes will be referred to the honor council for a hearing. \
This includes but is not limited to consulting electronic or printed materials during Quizzes and plagiarism on homework or class projects.\
It is your responsibility to understand the [Laney Graduate School Honor Code](https://www.gs.emory.edu/_includes/documents/lgs-2022_2023-handbook-updated-december-13.pdf), the [Emory College Honor Code](http://catalog.college.emory.edu/policies/honor-code.html), and the [Department Statement of Policy on Computer Assignments](https://cs.emory.edu/undergraduate/general-information/spca/).   

You are excepted to uphold and cooperate in maintaining academic integrity as a member of the Laney Graduate School. By taking this course, you affirm your commitment to the Laney Graduate School Honor Code, which you can find in the Laney Graduate School Handbook. You should ensure that you are familiar with the rights and responsibilities of members of our academic community and with policies that apply to students as members of our academic community. Any individual, when they suspect that an offense of academic misconduct has occurred, shall report this suspected breach to the appropriate Director of Graduate Studies, Program Director, or Dean of the Laney Graduate School. If an allegation is reported to a Director of Graduate Studies or a Program Director, they are in turn required to report the allegation to the Dean of Laney Graduate School.


### ChatGPT (or Any other Large Language Model and Internet Resourses):

  The Internet and ChatGPT can also be useful resources for learning.

  DISCLAIMER: You are responsible for discerning whether the resource is reliable and correct (i.e., caveat emptor). While it is okay to look at resources for the broad topic (e.g., how decision trees work), it is not okay to look for solutions to a specific homework problem (e.g., how to implement a decision tree in Python). Please ask if you are unsure whether something is allowed. You must cite all online sources used while working on homework and projects. It is always your responsibility to learn if a source is allowed.

  Apparent copies from any source, including your colleagues and internet sites, will be referred to the appropriate honor council. Every homework submission must have a README file with the following comments:

  /* THIS CODE IS MY OWN WORK, IT WAS WRITTEN WITHOUT CONSULTING CODE WRITTEN BY OTHER STUDENTS OR LARGE LANGUAGE MODELS LIKE CHATGPT. Your_Name_Here */


### Homework: 

  assignments should be completed independently.
  All submissions must contain only your original work and reflect your understanding of the assignment.
  A signed honor **pledge** be submitted with each homework assignment. Assignments will not be accepted without a pledge.
  Discussing homework assignments is not expressly forbidden. Code should not be   communicated under any circumstances. Sharing and receiving codes related to homework   assignments will be considered a violation of the honor code.


### Accommodations: 

  As the instructor of this course, I endeavor to provide an inclusive learning environment. I want every student to succeed. The Department of Accessibility Services (DAS) works with students who have disabilities to provide reasonable accommodations. It is your responsibility to request accommodations. In order to receive consideration for reasonable accommodations, you must register with the [DAS](https://accessibility.emory.edu/students/). Accommodations cannot be retroactively applied so you need to contact DAS as early as possible and contact us as early as possible in the semester to discuss the plan for implementation of your accommodations. For additional information about accessibility and accommodations, please contact the DAS at (404) 727-9877 or accessibility@emory.edu.

### Stress Management and Mental Health

  As a student, you may find that personal and academic stressors in your life, including those related to illness, economic instability, and/or racial injustice, are creating barriers to learning this semester. Many students face personal and environmental challenges that can interfere with their academic success and overall wellbeing. If you are struggling with this class, please visit me during office hours or contact me via email at name@emory.edu. If you are feeling overwhelmed and think you might benefit from additional support, please know that there are people who care and offices to support you at Emory. These services – including confidential resources – are provided by staff who are respectful of students’ diverse backgrounds. For an extensive list of well-being resources on campus, please go to: [http://campuslife.emory.edu/support/index.html](http://campuslife.emory.edu/support/index.html). And keep in mind that Emory offers free, 24/7 emotional, mental health, and medical support resources via [TimelyCare](https://timelycare.com/emory).
  
  Other Emory resources include:
  
  - [Counseling & Psychological Services](https://counseling.emory.edu/)
  - [Office of Spiritual & Religious Life](https://religiouslife.emory.edu/)
  - [Student Case Management and Interventions Services](https://success.emory.edu/)
  - [Student Health Services Psychiatry](https://studenthealth.emory.edu/services/psychiatry.html)
  - [Support During A Crisis: A Guide for Faculty & Staff](https://campuslife.emory.edu/support/the-blue-folder/index.html)
  - [Emory Anytime Student Health Services](https://campuslife.emory.edu/anytimehealth.html)

### Getting Help

The problem sets in this course can be challenging, and you may need clarifications or guidance. Some explanations will come from lecture materials and project handouts. If you're stuck, you can seek help from other students (within the guidelines), ask questions on Canvas (without posting code publicly), or attend TA office hours. Don't wait until the last few days of a project to seek help, as TAs may be overwhelmed.
TAs are not responsible for debugging your code. Avoid posting entire source code files on Canvas or asking TAs to fix your code directly. Their main goal is to ensure you understand the computer vision concepts needed to complete the projects. While some code-level discussions may be necessary, TAs will try to minimize these. Be prepared to show the debugging steps you've already taken, such as visualizing the output for specific inputs.

## (Tentative) Course Schedule


Topics, homework, midterm, and project schedule can be changed.
I suggest reading material listed below before the lecture to facilitate your understanding for the lecture materials.

|\# | **Date** | **Topic** | **Reference** | **Assignment** |
|:- |:---- |:---------------------------------- |:------ |:------ |
| 1 | X/X | Intro + Course Logistics (Review syllabus, Overview of course topics) | Szeliski 1 | HW1 OUT |
|   |  | **Image Formation and Filtering** (*Szeliski chapters 2 and 3*) |  |
| 2 | X/X | Camera Projection and Image Filtering | Szeliski 2.1, especially 2.1.4 | |
| 3 | X/X | Thinking in Frequency | Szeliski 3.2 and 3.4 | |
| 4 | X/X | Light, Cameras, Eyes, and Color | Szeliski 2.2 and 2.3 | |
|  ^^ |  | **Feature Detection and Matching** (*Szeliski chapters 7 and 8*) |  |
| 5 | X/X | Interest point intro | Szeliski 7.1.1 and 7.1.2 | |
| 6 | X/X | Local image features, SIFT | Szeliski 7.1.3 | |
| 7 | X/X | Model fitting, Hough Transform | Szeliski 7.4.2 and 2.1 | |
| 8 | X/X | RANSAC, ICP, and geometric transformations | Szeliski 8.1 and 2.1 | |
|   |  | **Multiple Views and Motion** (*Szeliski chapters 11 and 12*) |  |
| 9 | X/X | Camera Calibration, Stereo intro | Szeliski 12 and 11.2.1 | |
| 10 | X/X | Epipolar Geometry | Szeliski 11.3 | |
| 11 | X/X | Dense Stereo Correspondence | Szeliski 12 | |
|    |  | **Recognition** (*Szeliski chapters 5 and 6*) |  |
| 12 | X/X  | Machine learning crash course | Szeliski 5.1, 5.2, 5.3 | |
| 13 | X/X  | Neural Networks and Convolutional Networks | Szeliski 5.3 and 5.4 | |
| 14 | X/X  | Network Visualization | | |
| 15 | X/X  | Recognition techniques, old and new | Szeliski 6.2.1 | |
| 16 | X/X  | Big Data and Geolocalization | Szeliski 6.3 | |
| 17 | X/X  | Crowdsourcing and ResNet | | |
| 18 | X/X  | Semantic Segmentation | Szeliski 5.5 | |
| 19 | X/X  | Self-Supervised Learning and Colorization | | |
| 20 | X/X  | Deep Object Detection and Structured Output from Deep Networks | Szeliski 5.4.7 | |
| 21 | X/X  | 3D Point Processing | | |
| 22 | X/X  | Transformer architectures | | |
| 23 | X/X  | Generative Models - GANs and Diffusion | | |
| 24 | X/X  | NeRF and Gaussian Splatting | | |
|    | | **Other Applications of Computer Vision** | | 
| 25 | X/X | Cross-modality Human Activity Recognition | |
| 26 | X/X | Multimodal Artificial Intelligence in Health | |
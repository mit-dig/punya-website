---
layout: default
title: End-user Development of Mobile AI-based Clinical Apps
---

# Punya 2022: End-user Development of Mobile AI-based Clinical Apps using Punya

Half-day tutorial at the [20th International Conference on Artificial Intelligence in Medicine (AIME 2022)](https://aime22.aimedicine.info/).

- [Material](#material)
- [Motivation](#motivation)
- [Audience](#audience)
- [Description](#description)
- [Schedule](#schedule)
- [Materials](#materials)
- [Organizers](#organizers)

### Material

See the [Google Document](https://docs.google.com/document/d/13RKJF8Vjtq2Djcr9Tu1oZllJ-S_xwNQn6MJ48TW3KYk/edit?usp=sharing) for the tutorial material.

### Motivation

Long-term chronic patients are increasingly being encouraged to self-manage their illness in a home setting, to improve quality of life and reduce avoidable healthcare costs [^who]. To that end, smartphone apps, known as mobile patient diaries, can help with daily vital and symptom recording, medication adherence, and positive health behavior change. Chronic illnesses have wildly varying requirements for self-care, ranging from the careful management of glucose levels, over avoiding acute exacerbations or flare-ups, to effecting health behavior change by applying psychological theories (e.g., Cognitive Behavioral Therapy - CBT). Hence, different illnesses will require bespoke solutions for self-management, tailored to the reporting and follow-up needs of the illness; but also latest insights from design and behavioral science, psychology, and evidence from the particular medical domain (e.g., endocrinology, cardiology). 

This paints a picture of exploratory app development, where evolving and new insights will require the prototyping and evaluation of new or updated apps. This can be problematic in an academic setting: mobile app development requires specialized skills and thus tends to incur high development costs, whereas researchers often rely on one-shot grant funding. 

The Punya platform, a fork of [MIT App Inventor](https://appinventor.mit.edu/), aims to empower people with a non-IT background to develop their own mobile apps, ranging from pothole reporting to aiding with disaster relief [^shih]. The platform provides an intuitive, visual environment outfitted with drag-and-drop features and a puzzle-piece metaphor, all within a user-friendly Web tool. With the click of a button, a user can build a mobile app that implements a custom user-interface and application logic. 

We aim to demonstrate how healthcare and medical informatics researchers can use Punya for the rapid prototyping of mobile healthcare apps, without requiring specialized development experience. In support of this, Punya provides Artificial Intelligence (AI) features that include (a) Semantic Web technologies, which allow apps to query online data sources and reason over health data to provide smart health recommendations; (b) embedding of machine learning models to drive application features, such as image classification and training patient-specific models. Punya also facilitates the integration of health peripheral devices using IoT technologies. The platform enables participatory design and prototyping workflows, where clinicians, patients and IT specialists work together to create mobile health apps with direct input from all stakeholders.


## Audience

People with an interest in mobile health apps, e.g., for self-management of chronic illness, or delivery of psychological interventions. No previous experience with mobile app development is required, nor with Semantic Web, rule engines, or machine learning. Experience with these technologies may be helpful, but the materials will be presented at a high level.

## Description

This tutorial provides a gentle introduction for non-technical attendees to develop AI-enabled mobile apps using an intuitive and visual Web platform. 

This will be a hands-on tutorial. Participants will be provided with a skeleton Punya app and fill in 3 important components: (1) machine learning, using the Personal Image Classifier [^tang] for training models (transfer learning) to recognize certain foods and deploying the model in Punya; (2) IoT devices, such as smart (food) scales or wearable fitness trackers, integrating their physical measurements in a Punya app; and (3) knowledge representation and reasoning: using the recognized foods, the FoodKG knowledge graph [^foodkg] with knowledge on food nutrients, and a set of knowledge-based rules, the Punya app will issue smart health recommendations on whether the food should be consumed or not.

## Schedule

The workshop will take place from 9h30 until 12h00 (Atlantic Daylight Time, ADT) on Tuesday, June 14th, 2022. 

## Materials

We expect participants will bring their own laptop with Google Chrome, Mozilla Firefox, or Apple Safari preinstalled for developing apps with the Punya Web platform. 

To run the apps, we will provide a limited number of Android devices - participants will be encouraged to bring their own Android devices. Alternatively, people can easily setup an Android emulator to run Punya mobile apps on their laptops; please follow [these instructions](https://docs.google.com/document/d/1wN5QUk9gVnnmSj6d7lkUeWoMeaMwruUdZD4DXv0rM8c/edit?usp=sharing) to get a development and emulation environment setup on your laptop.

<!--- The instructions for the tutorial are available as a [Google Doc](https://docs.google.com/document/d/1CJ-uecwaE5kGDX6QFHuZCIwyVlcWJCQ4Xd6iwEfwxZs/edit?usp=sharing). --->
  
  
  
## Organizers

### Evan Patton

<img src="https://appinventor.mit.edu/explore/sites/explore.appinventor.mit.edu/files/people/PATTON.jpg" style="float: left; width: 175px; margin-right: 15px;">

[ewpatton@mit.edu](mailto:ewpatton@mit.edu)

**Affiliation:** MIT App Inventor

Evan Patton did his Ph.D. work at Rensselaer Polytechnic Institute, where he studied applications of Linked Data and Semantic Web in the context of mobile devices. Now, as the lead developer of MIT App Inventor, of which the Punya platform is a fork, Evan has organized and proctored workshops for people interested in app development of all ages from middle school to working adults, often working with 30 or more participants. He is also a regular contributor to App Inventor communities providing insights on complex app building issues. He has presented at venues around the world including conferences in Hong Kong and at the International Committee of the Red Cross in Geneva, Switzerland. Additional organizational experiences include the annual App Inventor Summit as well as MoDeST, a workshop at ISWC 2015.
<div style="clear: both"></div>

### Floriano Scioscia

<img src="https://sisinflab.poliba.it/wp-content/uploads/2020/07/scioscia-679471825.jpg" style="float: left; width: 175px; margin-right: 15px;">

[floriano.scioscia@poliba.it](mailto:floriano.scioscia@poliba.it)

**Affiliation:** Information Systems Laboratory, Polytechnic University of Bari, Italy

<!-- ![Floriano Scioscia image](https://sisinflab.poliba.it/wp-content/uploads/2020/07/scioscia-679471825.jpg) -->
Floriano Scioscia received his Ph.D. in 2010 at the Polytechnic University of Bari (Italy), where he has been an Associate Professor since 2021. His research interests include knowledge representation and reasoning for mobile and pervasive computing, service discovery in ubiquitous wireless networks, semantic-enhanced cyber-physical systems and blockchain frameworks. He has co-authored over 20 articles in international peer-reviewed journals and over 60 papers in international conferences and workshops.
<div style="clear: both"></div>

### William Van Woensel

<img src="https://niche.cs.dal.ca/wp-content/uploads/2022/05/PXL_20210502_200043903-3.jpg" style="float: left; width: 175px; margin-right: 15px;">

[william.van.woensel@gmail.com](mailto:william.van.woensel@gmail.com)

**Affiliation:** Telfer School, University of Ottawa, Canada

William Van Woensel received his Ph. D. of Computer Science in 2013 at the Vrije Universiteit Brussel (Belgium). He is an Assistant Professor at the Telfer School, University of Ottawa (Canada). His research interests lie at the crossroads of Knowledge Representation and Reasoning (KRR), Machine Learning and Mobile Computing applied to Health Informatics. 
William has served in the organizing committees of the International Conference on Artificial Intelligence in Medicine, International Joint Conference on Rules and Reasoning, the International Workshop on Representing and Reasoning with Imperfect knowledge, and the Mobile Deployment for Semantic Technologies (MoDeST) workshop. He has many years of experience in teaching a range of graduate-level CS courses, including graduate courses for a Health Informatics program. He has co-authored over 50 articles in international journals and conferences.
<div style="clear: both"></div>

### Giuseppe Loseto

<img src="https://sisinflab.poliba.it/wp-content/uploads/2020/07/giuseppe_loseto-217611717.jpg" style="float: left; width: 175px; margin-right: 15px;">

[loseto@lum.it](mailto:loseto@lum.it)

**Affiliation:** Department of Management, Finance and Technology - LUM University "Giuseppe Degennaro", Italy

Giuseppe Loseto received his Ph.D. in 2013 at the Polytechnic University of Bari (Italy) and he has been an Assistant Professor at the LUM University "Giuseppe Degennaro" (Italy) since 2021. His research interests include pervasive computing and the Internet of Things, knowledge representation systems and applications for ubiquitous smart environments and semantic-enhanced cyber-physical systems. On these topics, he has co-authored over 50 papers in international journals and conferences.
<div style="clear: both"></div>

### Oshani Seneviratne

<img src="https://idea.rpi.edu/sites/default/files/person-images/oshani_0.png" style="float: left; width: 175px; margin-right: 15px;">

[senevo@rpi.edu](mailto:senevo@rpi.edu)

**Affiliation:** Rensselaer Polytechnic Institute, USA

Oshani Seneviratne is the Director of Health Data Research at the Institute for Data Exploration and Application at Rensselaer Polytechnic Institute. Oshani's research interests span decentralized systems that include web and blockchain technologies, data integration, knowledge graphs, artificial intelligence, and health systems. Oshani has co-founded and co-organized the AIChain workshop series co-located with the IEEE Blockchain conference, the Personal Health Knowledge Graph workshop series at the Knowledge Graph Conference, and the AAAI Symposium on AI for Social Good. Oshani has served in organizing committees of the International Semantic Web Conference, Web Science Conference, and IEEE Blockchain Conference


### References

[^who]: World Health Organization: Innovative Care for Chronic Conditions. Tech. rep. (2002), https://www.who.int/chp/knowledge/publications/icccglobalreport.pdf 
[^shih]: Fuming Shih, Oshani Seneviratne, Ilaria Liccardi, Evan Patton, Patrick Meier, and Carlos Castillo. 2013. Democratizing mobile app development for disaster management. In Joint Proceedings of the Workshop on AI Problems and Approaches for Intelligent Environments and Workshop on Semantic Cities (AIIP '13). Association for Computing Machinery, New York, NY, USA, 39–42. https://doi.org/10.1145/2516911.2516915
[^tang]: Tang, D. 2019. Empowering novices to understand and use machine learning with personalized image classification models, intuitive analysis tools, and MIT App Inventor. Master’s thesis, Massachusetts Institute of Technology.
[^foodkg]: FoodKG: Semantics-Driven Knowledge Graph for Food Recommendation. Steven Haussmann, Oshani Seneviratne, Yu Chen, Yarden Ne'Eman, James Codella, Ching-Hua Chen, Deborah L. McGuinness, Mohammed J. Zaki. ISWC 2019.

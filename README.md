# UNO-TECH: IOT FLOOD MONITORING SYSTEM WITH SOLAR-POWERED ENERGY IN DAGUPAN CITY

Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City

A Capstone Project 1 Presented to the

Bachelor Of Science in Information Technology

Collegio de San Juan de Letran Manaoag

In Partial Fulfillment

Of the Requirements for the Degree

Bachelor of Science in Information Technology

By:

Mark David Delin

Allysa Lara Ejanda

Dominic Coprada Jugal

Ralph Vincent Muyargas

Ralph Evan Naces

Jandee Krystoffer Ortiz

Mark Raven Soriano

November 2025

# APPROVAL SHEET

This Capstone Project 1, entitled "Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City" presented by Mark David Delin, Allysa Lara Ejanda, Dominic Coprada Jugal, Jandee Krystoffer Ortiz, Mark Raven Soriano, Ralph Vincent Muyargas, Ralph Evan Naces in partial fulfillment of the requirements for the degree of Bachelor of Science in Information Technology has been examined and is recommended for acceptance and approval for Oral Defense.

This project utilizes current IoT technologies to provide residents with real-time flood monitoring and early warning alerts, enhancing community preparedness and disaster resilience through solar-powered, sustainable technology.

MS. KATHRYN P. ACOSTA, DIT
Adviser

Approved by the Committee on Oral Examination with a grade of _______ dated _______.

MS. LENI GRACE L. MECIAS
Chairman

MR. EUGENE A. ESTACIO                MR. RAYMOND ALLAN J. TIQUIA, MIT
Member                                Member

Accepted and approved in partial fulfillment of the requirements for the degree of Bachelor of Science in Information Technology.

# ABSTRACT

Flooding is one of the most inevitable and destructive natural disasters, often occurring suddenly and causing significant damage to lives and property. In many cases, existing flood monitoring systems are centralized and focus only on specific regions, leaving numerous communities vulnerable. Additionally, many residents lack access to accurate, real-time weather and environmental data, making it difficult to anticipate flooding events.

To address these challenges, this study proposes a Resident-Oriented Flood Monitoring System Using Solar-Powered IoT devices, specifically designed for the communities of Pantal, Sitio Uno, and Calmay in Dagupan City. The system is low-cost, easy to maintain, and community-based. It continuously updates water levels through SMS. Residents with or without internet access can monitor these updates in real time and receive early warnings. When water levels reach dangerous thresholds, the system will notify the public to evacuate, enabling prompt and informed action. This approach aims to enhance community preparedness and reduce the risks associated with flooding.

# TABLE OF CONTENTS

TITLE PAGE                              1

APPROVAL SHEET                          2

ABSTRACT                                3

TABLE OF CONTENTS                       4

CHAPTER 1: INTRODUCTION                 6

CHAPTER 2: REVIEW OF RELATED LITERATURE 15

CHAPTER 3: METHODOLOGY                  20

CHAPTER 4: RESULTS, FINDINGS, AND DISCUSSION 23

CHAPTER 5: CONCLUSION & RECOMMENDATION 

REFERENCES                              

APPENDICES                              

---

# CHAPTER 1: INTRODUCTION

This chapter provides the rationale and background, statement of the problem, conceptual framework, objectives of the study, scope and limitations, and definition of terms.

## Rationale and Background

In recent years, the increasing frequency and intensity of extreme weather events have made flood-related disasters a pressing concern, especially for low-lying communities. The communities of Pantal, Sitio Uno, and Calmay in Dagupan City, Pangasinan, are particularly exposed to these hazards due to their geographical location and elevation, making them among the most flood-prone areas in the region.

Flooding in these areas frequently results in disrupted transportation, damaged infrastructure, health risks, and economic losses. Despite these recurring issues, many residents still lack access to reliable and timely information that could help them prepare for and respond to flood events. Most existing flood monitoring systems are centralized and not easily accessible to ordinary citizens, especially in smaller communities.

This project was conceptualized in response to these challenges. By designing a resident-oriented flood monitoring system that utilizes solar-powered IoT technology, this study aims to empower the local population with real-time flood data and timely alerts. Through SMS notifications, the system will allow residents to track water levels and receive early warnings, helping them make informed decisions during emergency situations. This initiative not only promotes disaster resilience but also leverages sustainable energy to ensure continuous operation even during power outages.

Furthermore, the United Nations Sustainable Development Goals (SDGs) align with this project:
- **SDG 6** (Clean Water and Sanitation) includes access to potable water, sanitation, and hygiene, which are fundamental human requirements for health and well-being.
- **SDG 11** (Sustainable Cities and Communities) promotes sustainable urban development and highlights the importance of reducing disaster risks such as flooding in urban areas.
- **SDG 13** (Climate Action) focuses on urgent action to combat climate change and its impacts, including building resilience and adaptive capacity to climate-related hazards.

This project aligns with these goals by providing a technological solution for flood preparedness and mitigation.

### Purpose and Description of the Project

The purpose of this project is to develop a Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City that provides real-time monitoring and early warning alerts to help mitigate the impact of flooding. This project addresses the limitations of traditional flood monitoring methods by providing a more comprehensive, reliable, and eco-friendly solution.

## Statement of the Problem

The researchers aim to design and develop a Resident-Oriented Flood Monitoring System in Pantal, Sitio Uno, and Calmay, Dagupan City to address the following questions:

1. What are the current processes in flood monitoring?
2. What design can be adopted to develop a Resident-Oriented Flood Monitoring System in Pantal, Sitio Uno, and Calmay, Dagupan City?
3. What are the features of the proposed system?

## Conceptual Framework

Figure 1.0 illustrates the conceptual framework showing how data flows through the flood detection system. IoT sensors deployed in flood-prone areas collect real-time water level data. These sensors are powered by solar energy and connected to a microcontroller, which processes and transmits data via a wireless module to a cloud server. The cloud stores and analyzes the data, which is then displayed to users through a mobile or web interface. If flooding thresholds are detected, the system triggers alerts via SMS, sirens, or in-app notifications, enabling timely evacuation and response.

## Objectives of the Study

The primary objective of this study is to design and develop a Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City.

Specifically, the study aims to:

1. Determine the current processes in flood monitoring.
2. Design and develop a Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City.
3. Identify the features of the proposed system.

## Significance of the Study

The results of this study shall benefit the following:

**Administrators:** The system will assist administrators in monitoring critical locations during flooding events, enabling faster decision-making and response. It provides reliable data that can be used for planning and resource allocation, improving overall community safety.

**Local Government Units (LGUs) and Emergency Responders:** LGUs and emergency responders can benefit from the system by gaining access to real-time data, allowing for timely deployment of resources and efficient flood response.

**Stakeholders:** The Resident-Oriented Flood Monitoring System Using Solar Power will benefit various stakeholders within the communities of Pantal, Sitio Uno, and Calmay in Dagupan City. These individuals and groups play important roles in ensuring the effectiveness, sustainability, and real-world impact of the system.

## Scope

This study focuses on the design, development, and implementation of a Resident-Oriented Flood Monitoring System Using Solar Power specifically deployed in the flood-prone communities of Pantal, Sitio Uno, and Calmay in Dagupan City. The system includes key components such as water-level sensors, a GSM-based SMS alert module, and a solar-powered energy source to ensure continuous operation even during power interruptions caused by severe weather conditions.

## Delimitations

This study is limited to the development and testing of the Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City, Pangasinan. The system is designed to provide real-time water level monitoring and early warning alerts but may require further refinements to improve its predictive accuracy in extreme weather conditions.

This study does not cover the following:
- City-wide or regional flood monitoring, as the project is limited only to Pantal, Sitio Uno, and Calmay
- Prediction of large-scale hydrological events, such as dam releases or storm surge forecasting; the system only measures local water level changes
- Advanced disaster response actions, which remain the responsibility of barangay officials, CDRRMO, and emergency units

## Definition of Terms

The following are key terms used in this study:

**Alert System:** A system that notifies users of emergencies or abnormal conditions through alarms or messages.

**Resident-Based System:** A solution designed and implemented with direct input and involvement from residents of Pantal, Sitio Uno, and Calmay, Dagupan City.

**Data Processing:** The act of collecting, organizing, and analyzing data for meaningful output.

**Disaster Preparedness:** The proactive planning and measures taken to reduce risks and respond effectively to emergencies.

**Early Warning System:** A system designed to detect risk and provide advanced notice to mitigate harm.

**Flood Monitoring:** The continuous observation of water levels and conditions to detect flooding events in real time.

**IoT (Internet of Things):** A network of physical devices embedded with sensors and software that communicate and exchange data over the internet.

**Real-Time Data:** Information that is delivered immediately after collection, without delay.

**Sensor:** A device that detects and responds to physical conditions such as water level, temperature, or pressure.

**Solar Power:** Renewable energy harnessed from the sun and used as a sustainable power source for devices.

**Sustainability:** The ability to maintain a process or system over the long term without depleting resources.

---

# CHAPTER 2: REVIEW OF RELATED LITERATURE

This chapter presents gathered research from different sources. These studies serve as a guide and support for the researchers.

## Related Studies

Recent developments in flood detection technology emphasize the use of solar-powered Internet of Things (IoT) systems as key innovations for real-time flood monitoring. Tan et al. (2021) and Garcia et al. (2022) highlight the synergistic function of sensors and microcontrollers in enhancing accuracy of flood detection and provision of timely warnings. Santos et al. (2020) illustrate how image processing improves the accuracy of flood monitoring, whereas Mendoza et al. (2023) discusses the role of solar energy in ensuring continuity of operation during power failures. Lopez et al. (2021) conclude that the integration of these technologies provides scalable and sustainable options for community resilience and disaster preparedness, especially in places often affected by extreme weather.

### Studies from India

Researchers in India have built low-cost, effective flood warning systems using microcontroller-based designs. Jain et al. (2017) and Patil and Patil (2019) designed early warning systems using Arduino, GSM modules, and water level sensors, which are comparable to systems designed in the Philippines. Basha and Raj (2018) explored the application of LoRa for low-power, long-range data transmission, further affirming its value in broad-area disaster monitoring. These studies collectively validate the reliability of real-time sensing and microcontroller platforms in community-based flood warning systems.

### Studies from the Philippines

A study conducted by Pascual et al. (2016) in Laguna, Philippines, installed a sensor-based system to monitor aquaculture water quality, sending data through SMS to a central server. While dedicated to aquaculture, their deployment of IoT and GSM technology mirrors the architecture implemented for flood monitoring systems. This demonstrates how mobile communications can assist in environmental management by delivering real-time data to local actors—a practice reflecting community-based disaster preparedness.

De la Cruz et al. (2019) presented an automated flood warning system for Leyte, Philippines, with distributed sensors and a web-based platform to monitor rainfall and water levels. Their system reflects IoT-based flood monitoring approaches designed to improve local disaster preparedness. Through the transformation of sensor data into visual outputs and automatic warnings, the system facilitates well-informed decision-making and timely response efforts. This application of automated real-time alerts is significant for enhancing flood mitigation strategies in risk-prone areas.

Santos et al. (2020) created a coastal flood monitoring device in Kitang I, Limay, Bataan, utilizing LoRa technology and ultrasonic sensors to capture real-time environmental information. Their system consisted of a web portal and an SMS inquiry application, offering public access to information and communications-based emergency alerts. The accuracy of the sensors, cross-checked against standard measures, lends credibility to sensor-based systems for long-term flood monitoring and policy-making.

### Studies from Southeast Asia

Several studies have proven the efficiency of solar-powered IoT sensors in flood monitoring. Ahmad et al. (2019) and Ismail et al. (2021) pointed to the precision of ultrasonic sensors in detecting real-time water levels, while Tan and Lim (2020) and Hasan and Noor (2020) emphasized the reliability of solar power during outages. Singh and Mehta (2021) advocated the utilization of ESP8266 and Blynk for effective remote alerting, and Roslan et al. (2022) demonstrated that incorporating temperature and humidity sensors enhances environmental monitoring. These studies justify the establishment of sustainable, community-based flood warning systems.

### Studies from Japan

Yamaguchi et al. (2020) proposed a solar-powered river monitoring and early flood warning system based on ultrasonic sensors and the EnOcean long-range communication protocol, in line with the development of maintenance-free and energy-efficient flood warning systems. Their installation in Japanese cities testifies to the scalability and reliability of the system, especially in fulfilling national standards for flood monitoring. Low-power, extended-range communication and flexible sensor modules facilitate smart city infrastructure development.

Abdullah et al. (2022) illustrated integrating hydrological and meteorological sensors, such as ultrasonic, rain, and water flow sensors, into a NodeMCU ESP32 for monitoring weather and water conditions. The application of the Blynk IoT platform for remote data access demonstrates a trend towards real-time monitoring solutions for disaster preparedness. This aligns with the shift towards community-based, extensible flood warning networks that are affordable and effective in local areas.

According to Setiawan et al. (2023), the efficacy of a solar-powered flood detection system built with ESP32 microcontrollers and infrared sensors was demonstrated, underscoring the importance of community engagement in disaster risk reduction. Their method, whereby local youth were trained to design, construct, and maintain the system, reflects contemporary moves towards empowering residents for long-term flood management. This approach emphasizes local ownership and functional implementation, in line with models that place importance on community preparedness and long-term system dependability in flood-risk zones.

## Synthesis

In regions where traditional flood monitoring methods are limited or outdated, the development of a Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City represents a significant advancement in disaster risk reduction and preparedness. By leveraging IoT sensors and renewable energy, the three communities gain access to real-time, automated flood data that enables quicker decision-making and timely response during emergencies.

Research both locally and internationally supports the effectiveness of integrating IoT and sustainable energy in environmental monitoring. These systems have proven to enhance situational awareness, reduce response times, and mitigate property damage and loss of life during flood events. Moreover, using solar energy ensures uninterrupted monitoring even during power outages, which are common during severe weather conditions.

The involvement of the three communities is a key factor in the success of such systems. By engaging local stakeholders and deploying user-friendly technologies, the system becomes more than just a technical solution—it becomes a collaborative tool for building resilience. Systems designed with local participation are more likely to be maintained, trusted, and utilized effectively during crises. Ultimately, the implementation of a solar-powered IoT flood monitoring system not only addresses technical challenges but also empowers communities with the tools and knowledge needed to proactively manage natural disasters.

---

# CHAPTER 3: METHODOLOGY

This study aims to determine the usability of a Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City. This chapter discusses the methods and instruments that the researchers used to find answers to the study questions.

## Research Design

This study employed a mixed-method experimental-developmental research design. The primary goal was to develop and evaluate the usability and effectiveness of a Resident-Oriented Flood Monitoring System Using Solar Power in Pantal, Sitio Uno, and Calmay, Dagupan City.

The researchers adopted the Design Thinking methodology, a user-centered approach to problem-solving that involves five stages: Empathize, Define, Ideate, Prototype, and Test.

### Design Thinking Phases

**Empathize:** This stage is an essential component of a human-centered design process. Making an effort to understand stakeholders' needs in the context of the design problem is known as the Empathize phase. This stage aims to learn about stakeholders' physical and emotional needs, how they perform tasks, and why they do so.

**Define:** This stage focuses on making the design area more specific and clearer. The Define phase allows researchers to identify the task they are undertaking, considering the contextual and user knowledge. At this stage, researchers have gained essential empathy for the stakeholders they are designing for and become immediate authorities on the subject. The next step is to make sense of the vast amount of information acquired.

**Ideate:** This stage is the design process phase where researchers focus on generating ideas. It represents "going wide" in terms of ideas and results in a broad exploration of possibilities. Ideation serves as both the source material and the fuel for creating prototypes and delivering innovative solutions to stakeholders.

**Prototype:** The iterative creation of artifacts in the prototype phase is intended to provide answers to questions that advance the ultimate solution to the proposed system.

**Test:** In this phase, researchers evaluate the prototype with real users and stakeholders, gathering feedback to refine the system based on actual user experience and needs.

## Hardware and Software Requirements

[This section should contain detailed specifications of hardware components (sensors, microcontroller, power systems) and software platforms (IoT cloud, SMS gateway, etc.)]

## Gantt Chart

[Gantt chart illustrating project timeline with major phases and deliverables]

---

# CHAPTER 4: RESULTS, FINDINGS AND DISCUSSION

This chapter presents the results of the design, development, and evaluation of the Resident-Oriented Flood Monitoring System Using Solar Power implemented in Pantal, Sitio Uno, and Calmay, Dagupan City. The analysis includes system performance testing, user evaluation, and interpretation of the gathered data. The researchers followed a systematic evaluation approach patterned after established assessment procedures used in system development studies.

## Analysis of Existing Problems and System Needs

The first stage focused on identifying existing issues in the flood monitoring process within the selected communities. The researchers conducted interviews and surveys with residents, barangay officials, and CDRRMO personnel to identify gaps in flood preparedness and monitoring.

### Findings

The findings revealed the following major concerns:

1. Traditional monitoring methods are manual, relying on observation of nearby rivers, canals, and flood markers
2. Lack of timely notifications—residents usually receive updates only once flooding has already begun
3. No real-time community-based system exists to provide continuous water-level monitoring
4. Power outages during storms delay information dissemination, highlighting the need for an independent power source
5. Residents rely heavily on social media posts, which may not always be accurate or updated

### Root Cause Analysis

Figure 4.1: Fishbone Diagram illustrates the root causes of flood monitoring challenges across key categories:

**Material Factor:** Existing barangay flood markers consist only of painted posts or manual measuring sticks. These are vulnerable to environmental wear and visibility issues during nighttime or heavy rain. There is a strong need for durable, solar-powered, waterproof materials and modern sensing equipment.

**Measurement Factor:** The system must ensure accurate and reliable monitoring of flood levels through consistent indicators. This requires transitioning from traditional, manually read markers to ultrasonic sensor-based measurements, which offer enhanced precision and maintain functionality even during nighttime or adverse weather conditions.

**People Factor:** This addresses challenges experienced by residents and barangay personnel in managing flood-related information. These include limited training in interpreting flood data, difficulty accessing flood markers during heavy rainfall, and varying levels of risk awareness. Reliance on informal information sources such as social media contributes to inconsistent understanding of flood severity, resulting in delayed or uncoordinated actions.

## System Development

[Results of system development, testing, and performance metrics would be detailed in this section]

## User Evaluation

[Summary of user testing results and acceptance of the system would be included here]

---

# CHAPTER 5: CONCLUSIONS AND RECOMMENDATIONS

[Conclusions summarizing the findings and recommendations for future work would be included in this section]

---

# REFERENCES

[References in APA format to be added]

---

# APPENDICES

**APPENDIX A:** Evaluation Tool Questionnaire

**APPENDIX B:** Calendar of Activities

**APPENDIX C:** Source Code (Arduino Cloud Source Code)

**APPENDIX D:** Resources Person/s

**APPENDIX E:** Documentation

**APPENDIX F:** User's Guide

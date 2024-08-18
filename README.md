# OpenCTI Threat Intelligence Platform Walkthrough

## Project Overview

This project is a detailed walkthrough of the OpenCTI platform, conducted on TryHackMe. OpenCTI is an open-source threat intelligence platform that facilitates the management, storage, analysis, and visualization of cyber threat data. The walkthrough explores how to use the platform to analyze threats like APT37 and CaddyWiper malware.

## Objective

The main objective of this project is to develop practical skills in navigating and utilizing OpenCTI for threat intelligence analysis. The walkthrough focuses on using OpenCTI to investigate real-world cyber threats, understand threat actor behaviors, and assess attack techniques.

## Skills Learned

- **Threat Analysis:** How to investigate and analyze malware and APT groups using OpenCTI.
- **Platform Navigation:** Navigating through the OpenCTI dashboard and utilizing different tabs to extract relevant threat intelligence.
- **Understanding Attack Techniques:** Identifying and associating attack techniques and tools used by threat actors.
- **Threat Actor Profiling:** Profiling threat actors like APT37, including their techniques and tools.

## Tools Used

- **OpenCTI:** The primary tool used for threat intelligence analysis and investigation.
- **MITRE ATT&CK Framework:** Used to map and understand attack techniques and threat actor tactics.

## Walkthrough Steps

### 1. Room Overview
- **Objective:** Understand the purpose of OpenCTI and its application in threat intelligence.
- **Key Points:** 
  - Overview of OpenCTI functionalities and navigation.
  - Understanding the prerequisites for using OpenCTI effectively.

### 2. Introduction to OpenCTI
- **Objective:** Explore the core functionalities of OpenCTI.
- **Key Points:** 
  - OpenCTI's integration with the MITRE ATT&CK Framework.
  - The platform's role in managing CTI, including storage and visualization of threat data.

### 3. OpenCTI Data Model
- **Objective:** Understand the data model used in OpenCTI.
- **Key Points:** 
  - Explanation of the OpenCTI architecture, including `API`, `front-end`, `connectors`, and `storage`.
  - Usage of `STIX2` standards for structuring threat data.
- **Reference:** OpenCTI Data Model screenshot.
![https://tryhackme.com/r/room/opencti](https://github.com/user-attachments/assets/0e96b5fa-a553-4220-9c2f-379b68e5a455 "https://tryhackme.com/r/room/opencti")

### 4. Investigative Scenario
- **Objective:** Apply knowledge in a real-world SOC scenario.
- **Key Points:** 
  - Investigate the CaddyWiper malware and its association with the APT37 group.
  - Analyze attack techniques like **Native API** used by CaddyWiper.
  - Identify tools and techniques used by APT37 for initial access.
- **Details:**
  - **Earliest date recorded for CaddyWiper:** `2022/03/15`
  - **Attack Technique used by CaddyWiper for execution:** `Native API`
  - **APT37 associated country:** `North Korea`
  - **Tools used by APT37 in 2016:** `BloodHound`, `Empire`, `ShimRatReporter`
- **Reference:** Investigative scenario on TryHackMe.

### 5. Activities & Knowledge Management
- **Objective:** Learn to manage and categorize threat data.
- **Key Points:** 
  - Using the `Activities` tab to track incidents.
  - Observing threat actor behaviors and their related indicators in the `Knowledge` tab.
- **Reference:** Screenshots of the Activities and Knowledge tabs in OpenCTI.

### 6. General Tabs Navigation
- **Objective:** Efficiently navigate through different OpenCTI tabs.
- **Key Points:** 
  - `Overview Tab`: Provides general information about the selected entity.
  - `Knowledge Tab`: Displays linked information like reports, indicators, and relations.
  - `Analysis Tab`: Shows reports where the identified entry has been seen.
  - `Indicators Tab`: Provides information on IOCs identified for all the threats and entities.
  - `History Tab`: Tracks changes made to the element, attributes, and relations.
- **Reference:** Navigation through the Cobalt Strike entity in OpenCTI.

## Conclusion

This project provided hands-on experience with OpenCTI, emphasizing its role in modern cybersecurity. The walkthrough enabled a deep dive into the functionalities of OpenCTI, reinforcing the ability to analyze and manage threat intelligence effectively.

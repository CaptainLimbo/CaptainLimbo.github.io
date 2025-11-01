---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I'm a PhD student in Computer Science at Duke University, in the Intelligent Interactive Internet of Things (I^3T) Lab under the supervision of [Prof. Maria Gorlatova](https://maria.gorlatova.com/). We as a lab work boardly in edge computing, IoT, and especially in augmented reality (AR)/virtual reality (VR).

# Research Interest
AI-assisted safe Augmented Reality (AR) systems, using eye tracking and machine learning for user context sensing, particularly sensing human attention. My research is oriented around building effective deep learning models with eye tracking data to detect suboptimal user attention patterns in AR and to integrate such models into AR systems to provide real-time feedback to users and mitigate potential safety risks by adaptively adjusting AR content. I'm also broadly interested in other aspects of safe AR systems, including but not limited to semantic sensing of the physical environment, securing AR-based human-robot collaboration and edge-assisted AR applications. 

[My CV (v. 2025.10)](../files/cv.pdf)
[My Resume (v. 2025.10)](../files/resume.pdf)

<span class='anchor' id='news'></span>

# 🔥 News
- *2025.09*: &nbsp;🎉🎉  My (second-author) paper AR-TMT: Investigating the Role of Distraction Type and Attention Control in AR Visual Search* has been accepted to ACM VRST 2025!
- *2025.08*: &nbsp;🎉🎉  My paper *Will You Be Aware? Eye Tracking–Based Modeling of Situational Awareness in Augmented Reality.* has been accepted to IEEE ISMAR 2025!
- *2025.08*: &nbsp;🎉🎉  My (second-author) paper *Spatial Sensing Evaluation for Multiple XR Devices* has been accepted to IEEE ISMAR 2025!

<span class='anchor' id='publications'></span>

# 📝 Publications 
## Conference Proceedings
- **VRST25** S. Baek, **Z. Qu**, and M. Gorlatova, AR-TMT: Investigating the Role of Distraction Type and Attention Control in AR Visual Search. To be presented at ACM VRST, Nov. 2025. [Code Repo](https://github.com/Duke-I3T-Lab/AR-TMT); [Video Demo](https://www.youtube.com/watch?v=-CHhz_t5S40)

- **ISMAR25a** **Z. Qu**,  T. Hu, C. Fronk, and M. Gorlatova, Will You Be Aware? Eye Tracking–Based Modeling of Situational Awareness in Augmented Reality. To be presented at IEEE ISMAR, Oct. 2025. [Code Repo](https://github.com/Duke-I3T-Lab/AR_CPR_SA); [Video Demo](https://www.youtube.com/watch?v=wGF_hvBP-hg)

- **ISMAR25b** T. Hu, **Z. Qu**, and M. Gorlatova, Spatial Sensing Evaluation for Multiple XR Devices. To be presented at IEEE ISMAR, Oct. 2025. [Code Repo](https://github.com/Duke-I3T-Lab/XR_Tracking_Evaluation)

- **ISMAR24** **Z. Qu**, R. Byrne, and M. Gorlatova, "Looking" into Attention Patterns in Extended Reality: An Eye Tracking–Based Study. In Proc. IEEE ISMAR, Oct. 2024. [Code Repo](https://github.com/Duke-I3T-Lab/XR_Attention_Sudoku); [Video Demo](https://www.youtube.com/watch?v=KJo9mlpy4hQ)

- **IPSN24** L. Duan, Y. Chen, **Z. Qu**, M. McGrath, E. Ehmke, M. Gorlatova, BiGuide: A Bi-Level Data Acquisition Guidance for Object Detection on Mobile Devices. In Proc. ACM/IEEE IPSN, May 2024. **(21.5% acceptance rate)** **IEEE/ACM IPSN Best Research Artifact Runner-up Award**. [Code Repo](https://github.com/BiGuideCollection/BiGuide)

## Workshop Proceedings
- **IEEEVRW24** S. Eom, T. Ma, N. Vutakuri, A. Du, **Z. Qu**, J. Jackson, M. Gorlatova, Did You Do Well? Real-Time Personalized Feedback on Catheter Placement in Augmented Reality-Assisted Neurosurgical Training. In Proc. IEEE VR Abstracts and Workshops, Mar. 2024.
- **ISMARDC24** **Z. Qu**, Doctoral Consortium: Attention-Safe Augmented Reality System with Edge Computing. In Proc. IEEE ISMAR-Adjunct, Oct. 2024. **Best Doctoral Consortium Presentation Honorable Mention**.

## Conference Demonstrations and Poster Presentations
- **XRSecurity25** **Z. Qu**, T. Hu, M. Gorlatova, Demo: More Than Just Compressions: Attentional Tunneling in Augmented Reality--Guided Cardiopulmonary Resuscitation. To be presented at the First Workshop on Enhancing Security, Privacy, and Trust in Extended Reality (XR) Systems, Oct. 2025. [Video Demo](https://www.youtube.com/watch?v=2MfYJF6sW8A)
- **IEEEVRW24** R. Byrne, **Z. Qu**, C. Fronk, S. Eom, T. Scargill, M. Gorlatova, AR Simulations in VR: The Case for Environmental Awareness. In Proc. IEEE VR Abstracts and Workshops, Mar. 2024.

<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards
- *2024.10* **Best Doctoral Consortium Presentation Honorable Mention** at ISMAR 24 Doctoral Consortium, Greater Seattle Area, USA. 
- *2024.03* **Best Applied AI Poster Award** at NSF AI Spring School, San Antonio, TX, USA.

<span class='anchor' id='service-teaching-mentorship'></span>

# Service, Teaching and Mentorship
## Reviewer
- ACM VRST 2025
- ACM UbiComp/ISWC 2025
- ACM Transactions on Sensor Networks 2024

## Teaching Assistant
- **COMPSCI 371**: Elements of Machine Learning, Fall 2023
- **COMPSCI 370D**: Intro to AI, Spring 2023

## Research Supervision
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Position</th>
      <th>Duration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ahmad Choudhary</td>
      <td>Undergrad</td>
      <td>Jan. 2025 - present</td>
    </tr>
    <tr>
      <td>Fareeda Akewusola</td>
      <td>Undergrad</td>
      <td>May 2024 - July 2024</td>
    </tr>
    <tr>
      <td>Ryleigh Byrne</td>
      <td>Research Associate</td>
      <td>Oct. 2023 - April 2024</td>
    </tr>
  </tbody>
</table>


<!-- # 📖 Educations
- *2022.08 - present*, Ph.D. in Computer Science, Duke University
- *2018.09 - 2022.06*, Bachelor, Computer Science (IEEE Honor Class), Shanghai Jiao Tong University -->

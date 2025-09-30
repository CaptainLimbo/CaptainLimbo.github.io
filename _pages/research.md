---
permalink: /research/
title: "Research Projects"
layout: default
author_profile: true
---

<!-- Add spacing between project sections -->
<style>
  .project-block h1,
  .project-block h2 {
    margin-top: 2.5rem;
  }
  .project-block h1:first-of-type {
    margin-top: 0; /* keep top tight */
  }
</style>

Here are selected research projects. For publications, see the Publications section.

<div class="project-block">

# Modeling Situational Awareness in AR-Guided CPR


<div style="text-align:center; margin: 0.5rem 0 1.25rem 0;">
	<img src="{{ '/images/cpr/teaser.png' | relative_url }}" alt="AR-Guided CPR situational awareness study teaser" style="max-width: 900px; width: 100%; height: auto;">
</div>

- In this work, we aim to model situational awareness though eye tracking data captured on a Magic Leap 2 device, in an AR app designed for cardiopulmonary resuscitation (CPR) guidance. To evaluate situational awareness, we designed two realistic, unexpected incidents, i.e. the patient bleeding or vomiting during the CPR procedure, to observe the participants' response. Based on their responses we label them with good or poor SA labels (with 24 out of 60 cases labeled "poor") and trained a graph neural network that predicts such label at 83% accuracy.

- Paper accepted to IEEE ISMAR 2025, a leading conference in the field of augmented and virtual reality.

##### Links to related resources:
- Video Demo: [YouTube Link](https://www.youtube.com/watch?v=wGF_hvBP-hg)
- Paper Preprint: [arXiv Link](https://arxiv.org/abs/2508.05025)
- Code Repo: [GitHub Link](https://github.com/Duke-I3T-Lab/AR_CPR_SA)


# Analyzing and Predicting the Distraction Potential of Augmented Reality

## Sudoku Attention Study in AR and VR
<div style="text-align:center; margin: 0.5rem 0 1.25rem 0;">
	<img src="{{ '/images/sudoku/teaser.png' | relative_url }}" alt="AR/VR Sudoku attention study teaser" style="max-width: 900px; width: 100%; height: auto;">
</div>
- In this work we developed two Sudoku Helper apps in AR and VR that assist the user to solve a Sudoku puzzle by overlaying hints on top of it. Additionally, we added a distractor in the form of a dancing Duke Blue Devil to investigate how the users' gaze behavior corresponds to (1) the modality, i.e. whether it is AR or VR and (2) the presence of distraction. Through a user study with 38 users in total, we identified that VR induced higher perceptual load and decreased user focus, while cognitive load increased in AR. With the data collected we also trained ML models to predict the existence of distractors and user attention control ability, showing performance drops when transferring between AR and VR, validating the gap between the two.

- Paper was accepted to IEEE ISMAR 2024.

##### Links to related resources:
- Video Demo: [YouTube Link](https://www.youtube.com/watch?v=GmX4YkK8b2I)
- Paper: [IEEE Link](https://ieeexplore.ieee.org/abstract/document/10765374)
- Code Repo: [GitHub Link](https://github.com/Duke-I3T-Lab/XR_Attention_Sudoku)



## AR Trail Making Test (AR-TMT) Study
<div style="text-align:center; margin: 0.5rem 0 1.25rem 0;">
	<img src="{{ '/images/ar-tmt/teaser.png' | relative_url }}" alt="AR Trail Making Test study teaser" style="max-width: 900px; width: 100%; height: auto;">
</div>
- In this work we developed an AR Trail Making Test (AR-TMT), an AR adaptation of the Trail Making Test that spatially renders targets for sequential selection on the Magic Leap 2. We implemented distractions in three categories: top-down, bottom-up, and spatial distraction based on Wolfe's Guided Search model, and captured performance, gaze, motor behavior, and subjective load measures to analyze attention and behavior. We found that top-down distraction degraded performance through semantic interference, while bottom-up distraction disrupted initial attentional engagement.

- Paper (led by my colleague Sihun Baek) was accepted to ACM VRST 2025.

##### Links to related resources:
- Video Demo: [YouTube Link](https://www.youtube.com/watch?v=-CHhz_t5S40)
- Paper: [arXiv Link](https://arxiv.org/pdf/2509.13468)
- Code Repo: [GitHub Link](https://github.com/Duke-I3T-Lab/AR-TMT)

</div>

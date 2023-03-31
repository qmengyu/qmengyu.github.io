---
permalink: /
title: "Personal Homepage of Qmengyu"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## 研究生工作：

### **Visual Scanpath Transformer              ICCV在投**

Human visual system (HVS) can respond to complex visual environments in real-time. Scanpath prediction is a task that simulates HVS to predict the eye movement trajectory and fixations when freely viewing visual scenes. Existing methods often ignore some of the historical trajectory information or compress them into a hidden unit. We propose a new method to simulate visual working memory to retain all historical trajectory information and learn how them affect the current saccade decision. Our approach, named Visual ScanPath Transformer (VST), treats scanpath prediction as a continuous fixation sequence generation problem. We build a fixation query with the position of the previous fixation, which accesses scene information from the global visual representation and incorporates the dependency relationship among the historical fixations. VST is a heuristic-rule-free visual scanpath predictor, it eliminates the dependency on visual rules such as the inhibition of return (IOR) mechanism that are widely referenced in other model designs, which greatly simplifies the workflow of scanpath prediction and the overall model architecture. Relevant experiments demonstrate that the VST could self-learn these popular visual rules. We evaluated VST on four widely used eye-tracking benchmark datasets, and conducted qualitative and quantitative experiments, which demonstrated that it outperforms the state-of-the-art scanpath prediction methods.

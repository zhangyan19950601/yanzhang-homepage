---
permalink: /
title: "Yan Zhang's Homepage"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* 1. 全局样式：基础规整+移动端适配 */
body {
  line-height: 1.7;
  margin: 0 auto;
  max-width: 1200px;
  padding: 20px;
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #333;
}

/* 2. 模块标题：强化识别度+统一间距 */
h2 {
  color: #2c3e50;
  border-bottom: 2px solid #3498db;
  padding-bottom: 10px;
  margin: 50px 0 25px;
  font-size: 1.4rem;
}

/* 3. 个人信息模块：突出关键成就 */
.profile-intro {
  margin-bottom: 30px;
  opacity: 0;
  animation: fadeInUp 0.8s ease forwards;
  animation-delay: 0.2s;
}
.profile-intro strong {
  color: #2980b9;
}

/* 4. 论文卡片：优化图片排版+响应式适配+动画 */
.paper-box {
  display: flex;
  gap: 30px;
  padding: 25px;
  margin: 0 auto 35px;
  max-width: 1100px;
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.06);
  align-items: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  opacity: 0;
  animation: fadeInUp 0.8s ease forwards;
  animation-delay: 0.4s;
}
.paper-box:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
}

/* 移动端：卡片垂直布局，无多余留白 */
@media (max-width: 768px) {
  .paper-box {
    flex-direction: column;
    padding: 20px;
    gap: 20px;
  }
  .paper-box-image {
    flex: none !important;
    width: 100% !important;
    max-width: 420px !important;
    margin: 0 auto !important;
    padding: 0 !important;
  }
  .paper-box-image img {
    height: auto !important;
    width: 100% !important;
  }
}

/* 图片容器：无额外留白，尺寸放大，和文字比例协调 */
.paper-box-image {
  flex: 0 0 350px;
  padding: 0;
  margin: 0;
  overflow: hidden;
  border-radius: 8px;
}
.paper-box-image img {
  border-radius: 8px;
  object-fit: cover;
  width: 100%;
  height: 240px;
  /* 取消图片四周多余留白 */
  border: none;
  transition: transform 0.5s ease;
}
.paper-box-image img:hover {
  transform: scale(1.03);
}
.paper-box-text {
  flex: 1;
  font-size: 15px;
  color: #34495e;
  line-height: 1.8;
  padding: 0;
}

/* 5. 成果列表：优化间距+层级+动画 */
#Achievements {
  padding-left: 20px;
  opacity: 0;
  animation: fadeInUp 0.8s ease forwards;
  animation-delay: 0.6s;
}
#Achievements li {
  margin-bottom: 30px;
  padding-left: 12px;
  border-left: 3px solid #3498db;
  transition: border-color 0.3s ease, background-color 0.3s ease;
}
#Achievements li:hover {
  border-left-color: #2980b9;
  background-color: rgba(52, 152, 219, 0.03);
}
#Achievements li strong {
  color: #2980b9;
  font-size: 16px;
}

/* 6. 发表论文：规整格式+高亮期刊+动画 */
.articles-list {
  padding-left: 20px;
  list-style-type: decimal;
  opacity: 0;
  animation: fadeInUp 0.8s ease forwards;
  animation-delay: 0.8s;
}
.articles-list li {
  margin-bottom: 20px;
  padding-right: 10px;
  font-size: 15px;
}
.articles-list li em {
  color: #e74c3c;
  font-style: normal;
  font-weight: bold;
}
.articles-list li a {
  color: #3498db;
  text-decoration: none;
  position: relative;
  transition: color 0.3s ease;
}
.articles-list li a::after {
  content: "";
  position: absolute;
  bottom: -2px;
  left: 0;
  width: 0;
  height: 2px;
  background-color: #2980b9;
  transition: width 0.3s ease;
}
.articles-list li a:hover {
  color: #2980b9;
}
.articles-list li a:hover::after {
  width: 100%;
}

/* 7. 标签样式：优化视觉 */
.badge {
  display: inline-block;
  padding: 4px 10px;
  margin-bottom: 10px;
  background: #3498db;
  color: #fff;
  font-size: 13px;
  border-radius: 6px;
  font-weight: bold;
}

/* 8. 谷歌学术统计：居中显示+间距 */
.gs-stats {
  text-align: center;
  margin: 40px 0;
}
.gs-stats img {
  margin: 0 15px;
  vertical-align: middle;
}

/* 9. 动画关键帧定义 */
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>

<span class='anchor' id='about-me'></span>

## About Me

<div class="profile-intro">
I am a "Distinguished Hundred Talents" postdoctoral fellow at Beihang University. My research focuses on key issues in respiratory exoskeleton robots, including bionic mechanisms, variable-stiffness and variable-configuration design, and human-in-the-loop control.
I have published 6 SCI papers as the first author or corresponding author, including high-level papers in IEEE Transactions on Biomedical Engineering (IEEE TBME, a Q1 journal in the biomedical engineering field) and IEEE Transactions on Neural Systems and Rehabilitation Engineering (2) (IEEE TNSRE, a Q1 journal in the rehabilitation field). My doctoral dissertation was awarded the 2025 Doctoral Dissertation Incentive Program by the Technical Committee on Intelligent Robots of the China Computer Federation. Relevant achievements were invited for a presentation at the Youth Forum of the 2025 China Haptic Technology and Application Conference(ranked <strong>3rd out of 80 participants</strong>).
</div>

## Doctoral Supervisor: Dangxiao Wang

<div class="profile-intro">
Professor Wang Dangxiao is a doctoral supervisor at Beihang University and Deputy Director of the State Key Laboratory of Virtual Reality Technology and Systems. He is also the Chief Scientist of a National Key Research and Development Program project.
He has previously served as Chair of the IEEE Technical Committee on Haptics, Chair of AsiaHaptics 2022, and Associate Editor of IEEE Transactions on Haptics (IEEE TOH). His research areas include medical rehabilitation robots, haptic human-computer interaction, and brain-computer interface technology.
Professor Wang has published more than 50 papers in IEEE Transactions journals as the first or corresponding author, including 25 papers in IEEE Transactions on Haptics (a top journal in the haptics field) as the first/corresponding author (ranked <strong>5th globally</strong> in terms of author order in the Web of Science database).
</div>


## Achievements

<div class='paper-box'>

<div class='paper-box-image'>
    <div>
      <div class="badge">Prototype</div>
      <img src='images/robot.png' alt="Respiratory exoskeleton prototypes">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
<br><br>
Three types of respiratory assist robotic devices were developed, and their efficacy was validated in five categories of patients with typical respiratory disorders (motor neuron injury, chronic obstructive pulmonary disease, cervical spinal cord injury, stroke, and traumatic respiratory failure). This research provides a hardware foundation and clinical experience for personalized optimization strategies involving human-in-the-loop for patients with various respiratory diseases. <br>
<strong>Professor Roche Ellen from the Department of Mechanical Engineering and Medical Engineering at MIT commented that the cardiopulmonary function assistive technology based on soft robots is promising to overcome the limitations of traditional ventilators.</strong>
  </div>
<span style="font-size: 18px; color: #2980b9; font-weight: bold;">Development of respiratory exoskeleton prototypes</span><br>
<span style="font-size: 16px; color: #34495e; font-weight: bold;">To address the issue that clinical positive pressure ventilators do not fully align with physiological breathing mechanisms and are prone to causing lung injuries and alveolar collapse, we proposed a soft wearable robotic device that simulates human physiological breathing.</span>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Bionic Design</div>
      <img src='images/muss-2.png' alt="Bionic muscle-driven variable-stiffness design">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
<br><br>
We achieved a breakthrough in fiber-reinforced double-layer casting technology and developed a high-output-force, high-folding-ratio soft actuator based on the Yoshimura tubular origami structure of Broussonetia papyrifera for expiratory assistance. The designed personalized portable exoskeleton system can effectively provide respiratory assistance to wearers in daily life scenarios and support the exploration of exoskeleton-assisted strategies during routine movements.
  </div>
<span style="font-size: 18px; color: #2980b9; font-weight: bold;">Bionic muscle-driven variable-stiffness design</span><br>
<span style="font-size: 16px; color: #34495e; font-weight: bold;">The research team conducted preliminary studies on key technologies of respiratory assist devices, designing a variable-stiffness negative-pressure shell based on the layer-blocking variable-stiffness actuation principle, which can switch between rigid and soft states.</span>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Control Strategy</div>
      <img src='images/loop.png' alt="Human-in-the-loop control strategies">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
<br><br>
By integrating a dual-chamber respiratory mechanics model with backstepping control, a biphasic control strategy for respiratory assist devices was proposed, enabling precise regulation of lung volume. Through flexible force tactile sensors and human-device interactive force compliance control, patient-ventilator asynchrony was effectively reduced. The previously developed exoskeleton testing platform allows rapid configuration of assistive modes and has high-precision control performance, providing technical support for real-time performance optimization and assistive mode efficacy evaluation of closed-loop exoskeleton systems.
  </div>
<span style="font-size: 18px; color: #2980b9; font-weight: bold;">Research on human-in-the-loop control strategies</span><br>
<span style="font-size: 16px; color: #34495e; font-weight: bold;">A closed-loop control system for respiratory assist devices was established, and a model-based proportional controller was designed to achieve personalized parameter adjustment and closed-loop tracking of complex breathing signals.</span>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Intention Perception</div>
      <img src='images/muti.png' alt="Multimodal respiratory intention perception">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
<br><br>
An IMU-based motion artifact removal method and a dynamic respiratory feature recognition algorithm were developed, achieving millisecond-level respiratory status monitoring and patient-ventilator synchrony triggering. Using diaphragm ultrasound for noninvasive monitoring of deep respiratory muscles, results showed that machine-assisted intervention significantly improved diaphragm mobility.These findings provide a solid foundation for personalized respiratory profiling, respiratory status assessment, and real-time clinical efficacy evaluation across diverse diseases and individuals.
  </div>
<span style="font-size: 18px; color: #2980b9; font-weight: bold;">Multimodal respiratory intention perception</span><br>
<span style="font-size: 16px; color: #34495e; font-weight: bold;">A multimodal intention decoding framework was proposed based on the respiratory nerve-muscle-skeleton-airflow conduction mechanism.</span>
</div>

## Principal Investigator

<div class="profile-intro">

I have presided over and participated in a number of national, provincial and horizontal research projects, mainly focusing on wearable respiratory assistive robots, bionic soft exoskeletons and human-in-the-loop control technology. Relevant project information is listed as follows:

<ul style="padding-left: 20px; margin-top: 15px;">

<li><strong>Human-Machine Integrated Cardiopulmonary Assistive Wearable Robot</strong><br>

<em>Source:</em> National Key R&D Program of China, Key Project on "Intelligent Robotics"<br>

<em>Duration:</em> Jan 2025 – Dec 2027<br>

<em>Role:</em> Key Participant

</li>

<li><strong>Bio-Inspired Cough Mechanism-Based Assistive Expectorating Soft Exoskeleton Robot</strong><br>

<em>Source:</em> General Program of the National Natural Science Foundation of China (NSFC)<br>

<em>Duration:</em> Jan 2022 – Dec 2025<br>

<em>Role:</em> Key Participant

</li>

<li><strong>Research on Respiratory Enhancement Training Technology Based on Thoraco-Abdominal Pressure-Assisted Regulation</strong><br>

<em>Source:</em> [Blinded] Project<br>

<em>Duration:</em> Jun 2023 – Jun 2025<br>

<em>Role:</em> Key Participant

</li>

<li><strong>Neural Decoding and Adaptive Control Mechanism of Voluntary Respiratory Engagement in VR Environments</strong><br>

<em>Source:</em> Independent Project of the State Key Laboratory of Virtual Reality Technology and Systems<br>

<em>Duration:</em> Jan 2022 – Dec 2023<br>

<em>Role:</em> Key Participant

</li>

<li><strong>Tactile Feedback Glove</strong><br>

<em>Source:</em> Huawei Collaborative Project<br>

<em>Duration:</em> Jan 2021 – Dec 2021<br>

<em>Role:</em> Participant

</li>

</ul>

</div>

## Published Essays

<!-- 优化：改为有序列表，高亮SCI/Q1，规整作者与期刊格式 -->

<ol class="articles-list">
 <li><strong>Yan Zhang</strong>, Xue Dinghao, Zhang B, Shi Mai, Nan Xiaolu, Zhang Yuru, Ge Qinggang, Zhang Zongyu, Wang Yuxing, Feng Yanggang and Wang Dangxiao. A systematic review of soft respiratory exoskeletons: assistance mechanisms, system architectures, and key technologies in <em>IEEE Transactions on Neural Systems and Rehabilitation Engineering</em>, 2026, 34:1869-1884.</li>
<li><strong>Yan Zhang</strong>, Qinggang Ge, Zongyu Wang, Yuxing Qin, Yixing Wu, Mingjing Wang, Mai Shi, Lei Xue, Weidong Guo, Yuru Zhang, Guangyu Wang, and Dangxiao Wang. Extracorporeal closed-loop respiratory regulation for patients with respiratory difficulty using a soft bionic robot in <em>IEEE Transactions on Biomedical Engineering</em>, 2024. (SCI, Q1, IF: 4.6)</li>
<li><strong>Yan Zhang</strong>, Danye Li, Fengyao Zhang, Zongyu Wang, Lei Xue, Xiaolu Nan, Nianming Li, Xilai Tan, Weidong Guo, Yuru Zhang, Hongmei Zhao, Qinggang Ge, Dangxiao Wang. Evaluation and modeling of diaphragm displacement using ultrasound imaging for wearable respiratory assistive robot in <em>Frontiers in Bioengineering and Biotechnology</em>. (SCI, Q1, IF: 4.3)</li>
<li><strong>Yan Zhang</strong>, Ziqi Wang, Qinggang Ge, Zongyu Wang, Xiangjie Zhou, Shaohang Han, Yuru Zhang, Dangxiao Wang. Soft exoskeleton mimics human cough for assisting the expectoration capability of SCI patients in <em>IEEE Transactions on Neural Systems and Rehabilitation Engineering</em>, 2022. (SCI, Q1, IF: 4.9, Co-first Author)</li>
<li>Wenzhuo Zhi, Wei Zhao, <strong>Yan Zhang</strong>, Enming Shi, Yangfan Zhou, Bi Zhang. Thoraco-abdominal biomechanical model and dual-layer control method for soft robotic system with application to respiratory assistance in <em>Frontiers in Bioengineering and Biotechnology</em>. (Corresponding Author, SCI, Q1, IF: 4.3)</li>
<li>Yue Wang, <strong>Yan Zhang</strong>, Qinggang Ge, Yaoxi Zhang, Zongyu Wang, Weidong Guo, Yuru Zhang, Yuhui Wang, and Dangxiao Wang. Voluntary respiration control: signature analysis by EEG in <em>IEEE Transactions on Neural Systems and Rehabilitation Engineering</em>, 2023. (SCI, Q1, IF: 4.9)</li>
<li>Zemin Wang, <strong>Yan Zhang</strong>, Dongjie Zhao, Ruibo He, Yuru Zhang, and Dangxiao Wang. Perceptually inspired C0-continuity haptic shape display with trichamber soft actuators in <em>Soft Robotics</em>, 2023. (SCI, Q1, IF: 6.4)</li>
<li>Xilai Tan, <strong>Yan Zhang</strong>, Bin Zhao, Xiaolu Nan, Yuru Zhang, and Dangxiao Wang. A vibrotactile belt for interpersonal synchronization of breath in <em>6th International Conference AsiaHaptics 2024</em>, 2024. (Conference Paper)</li>
<li>Ziqi Wang, Xiangjie Zhou, Zejian Zhou, <strong>Yan Zhang</strong>, Yuru Zhang, and Dangxiao Wang. MateJam: Multi-material teeth-clutching layer jamming actuation for soft haptic glove in <em>IEEE Transactions on Haptics</em>, 2023. (SCI, Q2, IF: 2.4)</li>
<li><strong>Yan Zhang</strong>, Li H, Qin X, et al. Analysis of vibration response and machining quality of hybrid robot based UD-CFRP trimming in <em>Proceedings of the Institution of Mechanical Engineers, Part B: Journal of Engineering Manufacture</em>, 2021, 235(6-7): 974-986. (First Author)</li>
  </ol>

## Collaborators

<div class="profile-intro">
Below are the core students and faculty collaborators from our team. You are welcome to reach out to them for potential collaborations. Interns are not listed here—however, we warmly welcome motivated individuals to join us!
</div>

## Faculty

<div class="profile-intro">
<li>
Bi Zhang, Shenyang Institute of Automation — Rehabilitation Exoskeleton Robot
</li>
<li>
Xiao Zhang, Tianjin University — Origami Engineering
</li>
<li>
Yanggang Feng, Beihang University — Wearable Robot
</li>
<li>
Guotao Li, Institute of Automation, Chinese Academy of Sciences (CAS) — Exoskeleton Robot
</li>
</div>

## Doctor

<div class="profile-intro">
<li>Qinggang Ge, Zongyu Wang, Mai Shi, Lei Xue, Peking University Third Hospital — Respiratory and Critical Care Medicine</li>
<li>Shu Li, Peking University People’s Hospital — Respiratory Function in Trauma Patients</li>
<li>Dan Huang, Xiaotangshan Hospital — Hypoxic Respiration</li>
<li>Xiaoxuan Liu, Peking University Third Hospital — ALS</li>
</div>


## News

## 2026-05-26

<div class="profile-intro">
Our wearable variable-stiffness textile with three-dimensional bistable structures for bionic respiratory sensing won the <strong>Second Prize</strong> in the Beihang University Fengru Cup Competition. Congratulations to Zhao Yingheng and the team.
</div>

## 2022

<div class="profile-intro">
Our respiratory assistive robot technology was featured in the <strong>China Rehabilitation Medicine Report 2022</strong> as the only selected technology in the respiratory assistive robot category.
</div>

---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-section {
  margin-bottom: 2.2em;
}
.cv-section h2 {
  font-size: 1.1em;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  color: #494e52;
  border-bottom: 2px solid #52adc8;
  padding-bottom: 0.3em;
  margin-bottom: 1em;
}
.cv-entry {
  margin-bottom: 1.4em;
}
.cv-entry-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 0.3em;
}
.cv-entry-title {
  font-weight: 700;
  font-size: 0.95em;
  color: #2c3e50;
}
.cv-entry-date {
  font-size: 0.82em;
  color: #7a8288;
  white-space: nowrap;
}
.cv-entry-sub {
  font-size: 0.88em;
  color: #52adc8;
  margin: 0.1em 0 0.4em;
  font-style: italic;
}
.cv-entry ul {
  margin: 0.3em 0 0 1.2em;
  padding: 0;
}
.cv-entry ul li {
  font-size: 0.88em;
  margin-bottom: 0.3em;
  line-height: 1.55;
  color: #3d4144;
}
.skill-group {
  display: flex;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 0.4em;
  margin-bottom: 0.7em;
}
.skill-label {
  font-size: 0.78em;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: #7a8288;
  min-width: 110px;
}
.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.35em;
}
.skill-tag {
  background: #f0f6f9;
  border: 1px solid #c8dce6;
  color: #2c3e50;
  font-size: 0.8em;
  padding: 0.15em 0.6em;
  border-radius: 3px;
}
</style>

<div class="cv-section">
<h2>Education</h2>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">University of Michigan, Ann Arbor</span>
  <span class="cv-entry-date">Aug. 2024 – May 2026</span>
</div>
<div class="cv-entry-sub">M.S. in Electrical and Computer Engineering &nbsp;|&nbsp; GPA: 3.9 / 4.0</div>
<ul>
  <li>Coursework: Communication Networks (A), Probability and Random Processes (A), Linear Systems Theory (A)</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">The Chinese University of Hong Kong, Shenzhen</span>
  <span class="cv-entry-date">Sep. 2020 – Jul. 2024</span>
</div>
<div class="cv-entry-sub">B.E. in Electronic Information Engineering &nbsp;|&nbsp; GPA: 3.6 / 4.0 &nbsp;|&nbsp; First Class Honor, Full Scholarship, Dean's List</div>
<ul>
  <li>Coursework: Computer and Network Security (A), Data Structures (A), Digital Signal Processing (A), Computer Architecture (A−), Operating Systems (A−), Machine Intelligence and Applications (A−)</li>
</ul>
</div>
</div>

<div class="cv-section">
<h2>Work Experience</h2>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">University of Michigan — Graduate Research Assistant</span>
  <span class="cv-entry-date">Apr. 2025 – Apr. 2026</span>
</div>
<div class="cv-entry-sub">Battery Control Group &nbsp;|&nbsp; Ann Arbor, MI</div>
<ul>
  <li>Designed a high-precision battery expansion diagnostic system utilizing a PCap04 capacitance-to-digital converter and RP2040 microcontroller, achieving capacitance measurements with an error margin under 0.5%.</li>
  <li>Developed firmware via Arduino to establish reliable multi-protocol sensor communication (CAN, I2C, ADC) at 1 Hz, and built a Python-based DAQ system for real-time logging and analysis.</li>
  <li>Engineered a custom PCB using EAGLE to integrate 4 gas sensors for in-motion dynamic testing; implemented a robust power management architecture coordinating diverse operating voltages across the board.</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">Pingyang Institute of Intelligent Manufacturing — R&amp;D Engineer Intern</span>
  <span class="cv-entry-date">Dec. 2022 – Feb. 2023</span>
</div>
<div class="cv-entry-sub">Wenzhou, China</div>
<ul>
  <li>Designed three elastic mechanics spatial models in ADINA with 3-/4-/6-node &amp; polyhedral elements, achieving &lt;2% error margin through iterative triangular mesh optimization around circular holes.</li>
  <li>Built PLC control systems with servo motor coordination and PC-PLC communication protocols, reducing manual intervention by 30% in production line testing scenarios.</li>
  <li>Applied HIKVision Master modules for defect detection (98.7% accuracy) and QR code recognition (1300+/min throughput), integrated equipment data via Python scripts with 500 ms latency.</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">Pingyang Wasu Broadcasting Network — Technical Operations Intern</span>
  <span class="cv-entry-date">Mar. 2022 – Dec. 2022</span>
</div>
<div class="cv-entry-sub">Wenzhou, China</div>
<ul>
  <li>Configured virtualization on a Linux host using VirtualBox, allocating 4 independent VM nodes to construct a simulated multi-node network for set-top box (STB) multimedia signal distribution.</li>
  <li>Executed system-level performance testing for STB screen-casting; quantified video frame rates and end-to-end network latency to evaluate throughput and streaming stability.</li>
  <li>Contributed to a Smart Healthcare IoT door system by analyzing interaction logic across CV-based fall detection, Alibaba Cloud storage, and admin/client UIs; authored comprehensive technical documentation.</li>
</ul>
</div>
</div>

<div class="cv-section">
<h2>Research</h2>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">The Chinese University of Hong Kong, Shenzhen</span>
  <span class="cv-entry-date">Aug. 2023 – Apr. 2024</span>
</div>
<div class="cv-entry-sub">Rate Adaptation with Long Short-Term Memory &nbsp;|&nbsp; Shenzhen, China</div>
<ul>
  <li>Proposed LSTM-based rate adaptation algorithm for 802.11 systems, implementing real-time channel estimation through PyTorch-trained models, achieving over 90% MCS prediction accuracy across 8 transmission rates.</li>
  <li>Developed NS-3 simulation framework with dynamic environment modeling, improving throughput by 15% in static scenarios and reducing convergence time by 30% in non-stationary conditions.</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">Shenzhen Institute of AI and Robotics for Society</span>
  <span class="cv-entry-date">Oct. 2022 – Feb. 2023</span>
</div>
<div class="cv-entry-sub">Digital Twin of Unmanned Aerial Vehicles &nbsp;|&nbsp; Shenzhen, China</div>
<ul>
  <li>Implemented an ESP32-based digital twin of the UAV framework in Unity, enabling real-time 3D model synchronization via asynchronous Bluetooth communication.</li>
  <li>Developed sensor fusion algorithm combining accelerometer/gyroscope data from MPU6050, implementing complementary filtering on ESP32 to reduce motion tracking latency from 1.5 s to 0.5 s.</li>
</ul>
</div>
</div>

<div class="cv-section">
<h2>Projects</h2>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">UMich Business+Tech &amp; Deloitte Datathon</span>
  <span class="cv-entry-date">Feb. 2025</span>
</div>
<div class="cv-entry-sub">Employment Based Immigration Analysis: LinkedIn Product Strategy &amp; Revenue Prediction</div>
<ul>
  <li>Engineered data processing pipelines using Python (Pandas) to aggregate and clean 1M+ historical records (2015–2024) from H-1B/PERM visa datasets and LinkedIn financial reports.</li>
  <li>Built a predictive model to forecast Premium subscription growth; designed interactive Power BI dashboards to visualize talent-policy dynamics.</li>
  <li>Secured 4th place out of 50+ teams; strategic insight validated by LinkedIn's subsequent official feature rollout.</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">Penetration Testing Lab: TCP Session Hijacking &amp; Adaptive Firewall</span>
  <span class="cv-entry-date">Mar. 2024 – Apr. 2024</span>
</div>
<ul>
  <li>Built virtual cyber range with KVM virtualization, automating VLAN configuration via Python-Fabric.</li>
  <li>Developed time-driven TCP RST injection tool with Scapy, achieving 91.4% success rate by dynamic SEQ/ACK prediction.</li>
  <li>Designed stateful firewall rules with GeoIP filtering and connection tracking, reducing attack surface by 78%.</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">Microprocessor-Based Bouncing Ball Game (STM32)</span>
  <span class="cv-entry-date">Sep. 2023 – Dec. 2023</span>
</div>
<ul>
  <li>Designed real-time physics engine on STM32F4 MCU using FSM architecture with mode selection and sub-pixel collision detection (±1px accuracy).</li>
  <li>Built Python GUI with PyQt5 for dynamic baud rate computation; validated UART timing via oscilloscope-based protocol reverse engineering, achieving 99.2% packet integrity.</li>
  <li>Architected ISR-driven synchronization with NVIC priority config, achieving 10 ms input-response latency via DMA-accelerated framebuffer (100 Hz refresh).</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">Student Information Registration System</span>
  <span class="cv-entry-date">Oct. 2023 – Dec. 2023</span>
</div>
<ul>
  <li>Designed relational database architecture normalized to 3NF with core entity models (students, courses, users).</li>
  <li>Implemented JWT-based authentication with multi-role (student/admin) access control and responsive frontend.</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">Operating System Core Modules Simulation in C</span>
  <span class="cv-entry-date">Sep. 2022 – Dec. 2022</span>
</div>
<ul>
  <li>Built process scheduler with MLFQ algorithm, reducing turnaround time by 35% through dynamic priority adjustment.</li>
  <li>Designed virtual memory manager with page table/TLB, achieving 89% hit rate using second-chance LRU.</li>
  <li>Implemented FAT32-like file system supporting COW and fsck tools, fragmentation rate &lt;8%.</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">5-Stage Pipelined MIPS CPU with Hazard Handling</span>
  <span class="cv-entry-date">Jan. 2022 – Apr. 2022</span>
</div>
<ul>
  <li>Implemented 32-bit MIPS CPU supporting 18 core instructions (R/I/J-type) with full 5-stage pipeline.</li>
  <li>Designed forwarding unit to resolve structural, data and control hazards by 99%+ and branch prediction reducing stalls by 67%.</li>
</ul>
</div>
</div>

<div class="cv-section">
<h2>Skills</h2>

<div class="skill-group">
  <span class="skill-label">Languages</span>
  <div class="skill-tags">
    <span class="skill-tag">Python</span><span class="skill-tag">C/C++</span><span class="skill-tag">Java</span><span class="skill-tag">Go</span><span class="skill-tag">C#</span><span class="skill-tag">JavaScript</span><span class="skill-tag">SQL</span><span class="skill-tag">Scala</span><span class="skill-tag">Bash</span>
  </div>
</div>
<div class="skill-group">
  <span class="skill-label">ML / AI</span>
  <div class="skill-tags">
    <span class="skill-tag">PyTorch</span><span class="skill-tag">OpenCV</span><span class="skill-tag">CUDA</span><span class="skill-tag">HuggingFace</span><span class="skill-tag">Pandas</span><span class="skill-tag">Matplotlib</span>
  </div>
</div>
<div class="skill-group">
  <span class="skill-label">Embedded</span>
  <div class="skill-tags">
    <span class="skill-tag">C/C++</span><span class="skill-tag">RTOS</span><span class="skill-tag">Verilog</span><span class="skill-tag">VHDL</span><span class="skill-tag">LabVIEW</span><span class="skill-tag">Virtuoso</span>
  </div>
</div>
<div class="skill-group">
  <span class="skill-label">Web & Backend</span>
  <div class="skill-tags">
    <span class="skill-tag">Node.js</span><span class="skill-tag">React</span><span class="skill-tag">.NET</span><span class="skill-tag">REST API</span><span class="skill-tag">MongoDB</span><span class="skill-tag">MySQL</span><span class="skill-tag">Redis</span>
  </div>
</div>
<div class="skill-group">
  <span class="skill-label">Cloud & DevOps</span>
  <div class="skill-tags">
    <span class="skill-tag">AWS</span><span class="skill-tag">Docker</span><span class="skill-tag">Kubernetes</span><span class="skill-tag">Linux</span><span class="skill-tag">Git</span>
  </div>
</div>
</div>

<div class="cv-section">
<h2>Certification &amp; Leadership</h2>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">JLPT N1</span>
  <span class="cv-entry-date">Dec. 2025</span>
</div>
<div class="cv-entry-sub">Score: 151/180 &nbsp;|&nbsp; CEFR Level: C1</div>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">CUHKSZ IEEE Student Branch — Founder &amp; Vice Chair</span>
  <span class="cv-entry-date">Jul. 2022 – Jun. 2024</span>
</div>
<ul>
  <li>Founded the branch as core team leader; drove recruitment campaigns to attract 500+ members in the first academic year.</li>
  <li>Hosted tech symposia for 400+ members and organized 10+ academic interviews and career-development lectures.</li>
  <li>Launched a centralized online platform for IEEE academic resources, improving collaboration across 300+ active users.</li>
</ul>
</div>

<div class="cv-entry">
<div class="cv-entry-header">
  <span class="cv-entry-title">CUHKSZ ChemA Community — Founder &amp; Academic Department</span>
  <span class="cv-entry-date">Jul. 2022 – Jun. 2023</span>
</div>
<ul>
  <li>Established the first student-led chemistry hub at CUHKSZ; published two articles reaching 300+ readers.</li>
  <li>Led lab immersion tours attracting 100% more freshman applicants compared to previous years.</li>
</ul>
</div>
</div>

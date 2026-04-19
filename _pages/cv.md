---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<br>

Education
======
**University of Michigan** | Aug. 2024 - May 2026 <br>
Master of Science in Electrical and Computer Engineering (Network, Communication and Information System Track)
  * GPA: 3.9 / 4.0
  * Relevant Coursework: Communication Networks (A), Probability and Random Processes (A), Linear Systems Theory (A)

**The Chinese University of Hong Kong, Shenzhen** | Sept. 2020 - Jul. 2024 <br>
Master of Engineering in Electronic and Information Engineering (Computer Engineering Track)
  * MGPA: 3.7 / 4.0, CGPA: 3.6 / 4.0
  * First Class Honor Graduate, Full Scholarship, Dean's List
  * Relevant Coursework: Computer and Network Security (A), Data Structures (A), Digital Signal Processing (A), Computer Architecture (A-), Operating Systems (A-), Machine Intelligence and Applications (A-), Microprocessor System Design (A-), 

Work Experience
======
**University of Michigan, Ann Arbor** | Apr. 2025 - Apr. 2026 <br>
Graduate Research Assistant | Battery Control Group | Ann Arbor, MI
  * Designed a high-precision battery expansion diagnostic system utilizing a PCap04 capacitance-to-digital converter and RP2040 microcontroller, achieving highly accurate capacitance measurements with an error margin of under 0.5%.
  * Developed firmware via Arduino to establish reliable multi-protocol sensor communication (CAN, I2C, ADC) at a 1Hz sampling rate, and built a Python-based data acquisition (DAQ) system for real-time logging and analysis.
  * Engineered a custom printed circuit board (PCB) using EAGLE to integrate 4 distinct gas sensors for in-motion dynamic testing; implemented a robust power management architecture to coordinate diverse operating voltages across the board.

**Pingyang Institute of Intelligent Manufacturing** | Dec. 2022 - Feb. 2023 <br>
Research and Development Engineer Intern | Wenzhou, China
  * Designed three elastic mechanics spatial models in ADINA with 3-/4-/6-node & polyhedral elements, achieving < 2%
error margin through iterative triangular mesh optimization around circular holes.
  * Built PLC control systems with servo motor coordination and PC-PLC communication protocols, reducing manual
intervention by 30% in production line testing scenarios.
  * Applied HIKVision Master modules for defect detection (98.7% accuracy) and QR code recognition (1300+/min through-
put), integrated equipment data via Python scripts with 500 ms latency.

**Pingyang Wasu Broadcasting Network Company** | Mar. 2022 - Dec. 2022 <br>
Technical Operations Engineer Intern | Wenzhou, China
  * Configured virtualization on a Linux host using VirtualBox, allocating 4 independent virtual machine nodes to construct a simulated multi-node network for set-top box (STB) multimedia signal distribution.
  * Executed system-level performance testing for STB screen-casting capabilities; quantified and analyzed key metrics including video frame rates and end-to-end network latency to evaluate system throughput and streaming stability.
  * Contributed to a Smart Healthcare IoT door system by analyzing interaction logic across computer vision-based fall detection, Alibaba Cloud storage, and admin/client UIs; authored comprehensive technical and user documentation.

Academic Research
======
**The Chinese University of Hong Kong, Shenzhen** | Aug. 2023 - Apr. 2024 <br>
Rate Adaption with Long Short Term Memory | Shenzhen, China
  * Proposed LSTM-based rate adaptation algorithm for 802.11 systems, implementing real-time channel estimation through PyTorch-trained models, achieving over 90% MCS prediction accuracy across 8 transmission rates.     
  * Developed NS-3 simulation framework with dynamic environment modeling, improving throughput by 15% in static scenarios and reducing convergence time by 30% in non-stationary conditions.

**Shenzhen Institute of Artificial Intelligence and Robotics for Society** | Oct. 2022 - Feb. 2023 <br>
Digital Twin of Unmanned Aerial Vehicles | Shenzhen, China
  * Implemented an ESP32-based digital twin of the Unmanned Aerial Vehicle framework in Unity, enabling real-time 3D model synchronization via asynchronous Bluetooth communication.
  * Developed sensor fusion algorithm combining accelerometer/gyroscope data from MPU6050, implementing complementary filtering on ESP32 to reduce motion tracking latency from 1.5 to 0.5 s. 

Other Projects
======
**University of Michigan Business+Tech & Deloitte Datathon** | Feb. 2025 <br>
Employment Based Immigration Analysis: LinkedIn Product Strategy and Revenue Prediction | Ann Arbor, MI
  * Engineered data processing pipelines using Python (Pandas) to aggregate and clean over 1 million historical records (2015–2024) from H-1B/PERM visa datasets and LinkedIn financial reports, analyzing talent mobility and market demands.
  * Uncovered key insights on AI talent retention by engineering features like PERM certification rates and expiration rates; built a predictive model to forecast Premium subscription growth driven by proposed product features.
  * Designed interactive Power BI dashboards to visualize talent-policy dynamics; presented data-driven product recommendations to Deloitte judges, securing 4th place out of 50+ competing teams (strategic insight highly validated by LinkedIn’s subsequent official feature rollout).

**The Chinese University of Hong Kong, Shenzhen** | Mar. 2024 - Apr. 2024 <br>
Penetration Testing Lab: TCP Session Hijacking & Adaptive Firewall | Shenzhen, China
  * Built virtual cyber range with KVM virtualization (N=hash(StudentID)%3+2), automating VLAN configuration via Python-Fabric.
  * Developed time-driven TCP RST injection tool with Scapy, achieving 91.4% success rate by dynamic SEQ/ACK prediction.
  * Designed stateful firewall rules with GeoIP filtering and connection tracking, reducing attack surface by 78%.

**The Chinese University of Hong Kong, Shenzhen** | Sept. 2023 - Dec. 2023 <br>
Microprocessor Based Bouncing Ball Game | Shenzhen, China
  * Designed real-time physics engine on STM32F4 MCU using finite-state machine architecture, implementing mode selection (easy/hard difficulty, pause) and sub-pixel level collision detection (±1px accuracy).
  * Built Python GUI with PyQt5 to compute dynamic baud rate (SHA-1 hashed student ID → 9600–115200 bps) and validated UART timing via oscilloscope-based protocol reverse engineering, achieving 99.2% packet integrity.
  * Architected ISR-driven synchronization with NVIC priority configuration, achieving 10ms input-response latency by DMA-accelerated framebuffer transfers (100Hz refresh rate, tested via logic analyzer).

**The Chinese University of Hong Kong, Shenzhen** | Oct. 2023 - Dec. 2023 <br>
Student Information Registration System | Shenzhen, China
  * Lead the design of relational database architecture, normalize table structure (3NF), and establish core entity relationship models such as students, courses, and users
  * Implement a Token-based JWT authentication system, support multi-role (student/administrator) authority separation, and ensure data security.
  * Design responsive front-end interface, output database design documents (ER diagram/SQL script), and promote team collaboration efficiency.

**The Chinese University of Hong Kong, Shenzhen** | Mar. 2023 - May 2023 <br>
Image Compression & Restoration System | Shenzhen, China
  * Designed DCT-based block compression with adaptive quantization matrix, achieving 34.9dB PSNR at 5:1 ratio
  * Built hybrid filter combining median and adaptive mean filters, improving MSE by 77.8% on Gaussian+missing-pixel noise.

**The Chinese University of Hong Kong, Shenzhen** | Feb. 2023 - May 2023 <br>
Zhihu Hot List Prediction Model Development & Data Analysis | Shenzhen, China
  * Designed Python-based web crawlers to automate collection of Zhihu hot list attributes (views, answers, comments, etc.) from the API, applied a regularization function to adjust visit count weights enhancing feature relevance.
  * Identified limitations of linear models (R² < 0.5) through exploratory data analysis (EDA) and proposed a 3-layer neural network (ReLU activation, dropout layers) for regression.
  * Optimized model performance using MAE/MSE dual-loss functions, achieving a 36% improvement over baseline linear models (test MSE: 0.0079).

**The Chinese University of Hong Kong, Shenzhen** | Sept. 2022 - Dec. 2022 <br>
Operating System Core Modules Simulation in C | Shenzhen, China
  * Built process scheduler with MLFQ algorithm, reducing turnaround time by 35% through dynamic priority adjustment.
  * Designed virtual memory manager with page table/TLB, achieving 89% hit rate using second-chance LRU.
  * Implemented FAT32-like file system supporting COW and fsck tools, fragmentation rate < 8%.

**The Chinese University of Hong Kong, Shenzhen** | Jan. 2022 - Apr. 2022 <br>
5-Stage Pipelined MIPS CPU with Hazard Handling | Shenzhen, China 
  * Implemented 32-bit MIPS CPU supporting 18 core instructions (R/I/J-type) with 5-stage pipeline.
  * Proposed a static branch priority strategy, insert a bubble (Stall) in the ID stage and refresh the IF stage instructions, and control the risk delay cycle from 3 to 1.
  * Designed forwarding unit to resolve structural, data and control hazards by over 99% and branch prediction logic reducing stalls by 67%.
  


Skills
======
* **Languages** <br>
  Python · C/C++ · Java · Go · C# · JavaScript · SQL · Scala · Bash
* **ML / AI** <br>
  PyTorch · OpenCV · CUDA · HuggingFace · Pandas · Matplotlib
* **Embedded** <br>
  C/C++ · RTOS · Verilog · VHDL · LabVIEW · Virtuoso
* **Web & Backend** <br>
  Node.js · React · .NET · REST API · MongoDB · MySQL · Redis
* **Cloud & DevOps** <br>
  AWS · Docker · Kubernetes · Linux · Git

Service and leadership
======
**CUHKSZ IEEE Student Branch** | Jul. 2022 - Jun. 2024 <br>
Founder and Vice Chair
  * Founded CUHKSZ IEEE Student Branch as a core team leader, driving recruitment campaigns to attract 500+ members within the first academic year.
  * Organized career-development lectures and hosted 1:1 interviews with IEEE fellows , enhancing members’ technical communication and professional networking skills.
  * Launched a centralized online platform for IEEE-related academic resources (e.g., research papers, project templates), improving collaboration efficiency and engagement across 300+ active users.

**CUHKSZ ChemA Community** | Jul. 2022 - Jun. 2023 <br>
  Founder and Academic Department
  * Drafted the association charter and recruitment strategy, established the first student-led chemistry hub at CUHKSZ.
  * Published two general explanatory articles through the official association channels, which brought more than 300 readers.
  * Led lab immersion tours directly engaging undecided majors and attracted 100% more freshman applicants compared to previous years.

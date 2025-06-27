---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can also download my Resume/CV by clicking [this link](/files/Resume/MichaelTung_Resume_2025_06_26.pdf).

Education
======
* Ph.D in Electrical and Computer Engineering, Purdue University, 2029 (expected)
<!--* M.S. in Jekyll, GitHub University, 2014 -->
* B.S. in Electrical Engineering with Summa Cum Laude, University of Florida, 2025


# Research Interest
To pursue a PhD in Electrical Engineering exploring information theory and its intersection in communication systems and machine learning, with an additional focus on stochastic processes, control systems, and optimization. <br>

My research will bridge theoretical foundations with practical implementations through digital design and embedded systems, addressing challenges in scalable and secure real-time technologies.


Research experience
======
* June 2025 - Present: Graduate Research Fellow <br>
  _Purdue University, West Lafayette, Indiana_
	* Conduct research on communication systems, dection and estimation theory.
  
* May 2024 – Present: Undergraduate Research Assistant <br>
  _Wireless Information Networking Group (WING), University of Florida, Gainesville, FL_
  * Developing a real-time RF spectrum monitoring application using RFSoC and SDR, specifically designed for the detection and identification of unauthorized drone activities.
  * Collected and analyzed RF data across various scenarios, developing a mathematical model and simulation code to better understand and explain real-world behaviors.
  * Engaged actively in weekly lab meetings with Dr. John Shea, Dr. Tan Wong, and PhD. Students contribute insights, receive feedback, and foster project advancements.
  * Supervisor: [Dr. John Shea](https://www.ece.ufl.edu/people/faculty/john-m-shea/) and [Dr. Tan Wong](https://www.ece.ufl.edu/people/faculty/tan-wong/)

* May 2023 – Sep 2024: REU Fellowship (Paid research assistant) <br>
  _Smart Systems Lab (SSL), University of Florida, Gainesville, FL_ 
  * Developed and implemented a 3D object tracking camera system using Python and OpenCV within the lab's testing space.
  * Enhanced FFmpeg-based video streaming performance by 30% through CUDA hardware acceleration.
  * Tested FPGA and microprocessor integration on drones for improved system control and data processing.
  * Supervisor: [Dr. Christophe Bobda](https://www.ece.ufl.edu/people/faculty/christophe-bobda/)

  
Work & Project Experience
======
* **Capstone/Co-op Project Member IPPD**, _Aug 2024 – May 2025_ <br>
  **Northrop Grumman**, Melbourne, FL
	* Recognized as "Best Team" among all senior design projects in IPPD
	* Developed an automatic asset management system using RFID, microcontrollers, sensors, and data management frameworks for a designated lab space within the Northrop Grumman facilities.
	* [My team's blog](https://www.ippd.ufl.edu/blogs/ay2425team09/).

* **1-D Time Domain Convolution on FPGA**, _Nov 2024 - Dec 2024_ <br>
	* Designed and implemented a high-performance 1-D convolution circuit on the Zedboard FPGA, leveraging parallelism to achieve ~15x speed-up compared to an ARM at 667MHz.
	* Optimized throughput with pipelined and unrolled convolution loops and dual-clock DRAM DMA interface with FIFO and handshake for reliable data transfer and mitigate metastability.
	* Implemented smart buffer (sliding window) design for efficient data reuse, reducing memory bandwidth requirements.
	* [Report](/posts/2024/12/Reconfig-final-project/)

* **Pong Game on FPGA**, _Apr 2024 – May 2024_ <br>
	* Developed a Pong game using VHDL with custom logic for game mechanics and VGA output.
	* Implemented FSM for game state control and optimized real-time performance.

* **Circuit Analysis Tool**, _Apr 2023 – May 2023_ <br>
	* Developed a C++ tool to calculate currents, voltages, and drops from netlist data.
	* Improved efficiency by 20% with dynamic programming for complex circuits.

Honors & Awards
======
* **Ross Fellowship**, **_Purdue University_**, 2025
	* A competitive, fully funded award for the recruitment of outstanding PhD candidates.

* **Electric E Award**, **_University of Florida_**, 2025
	* The ECE department's most prestigious award.
	
* **Ralph Sias Scholarship**, **_University of Florida_**, 2024
	* A merit-based scholarship awarded for outstanding academic achievement in ECE.

* **James E. Dykes Scholarship**, **_University of Florida_**, 2023
	* A merit-based scholarship awarded for outstanding academic achievement in ECE.

* **Honor Roll and Dean's List**, **_University of Florida_**, 2023 – 2025
  
Skills
======
## Programming Languages
* **Systems Programming:** C/C++, Assembly
* **Software Development:** Java, Python
* **Machine Learning:** PyTorch, TensorFlow
* **Technical Computing:** MATLAB
* **Version Control:** Git

## Digital Design & Hardware
* **HDL Languages:** VHDL, SystemVerilog
* **Verification:** UVM (Universal Verification Methodology)
* **High-Level Synthesis:** Vitis HLS
* **Circuit Design:** LTspice, Altium Designer

## Professional & Technical Skills
* **Certifications:** NVIDIA Fundamentals of Deep Learning, Lean Six Sigma White Belt
* **Documentation:** Technical Writing, Microsoft Office Suite
* **Communication:** Professional Presentation, Cross-functional Collaboration

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
<!--  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
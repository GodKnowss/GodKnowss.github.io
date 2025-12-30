---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- You can also download my Resume/CV by clicking [this link](/files/Resume/MichaelTung_Resume_2025_10_19.pdf). --> <!--* everytime change, also change the config cv too -->

Education
======
* Ph.D in Electrical and Computer Engineering, Purdue University, 2030 (expected)
<!--* M.S. in Jekyll, GitHub University, 2014 -->
* B.S. in Electrical Engineering with Summa Cum Laude, University of Florida, 2025 (GPA: 4.00/4.00)


# Research Interest
**Key Areas**: Communication Systems | Information Theory | Machine Learning | Stochastic Processes | Control Theory | Optimization | Digital Design <br>


Research Experience
======
* June 2025 - Present: **Graduate Research Fellow** <br>
  _TSAC Laboratory, Purdue University, West Lafayette, Indiana_
	* Wireless communication systems and Information Theory
  
* May 2024 – Present: **Undergraduate Research Assistant** <br>
  _Wireless Information Networking Group (WING), University of Florida, Gainesville, FL_
  * Research using RFSoC and FPGA for wireless communication systems and spectrum sensing in drone applications

* May 2023 – Sep 2024: **REU Fellowship (Paid research assistant)** <br>
  _Smart Systems Lab (SSL), University of Florida, Gainesville, FL_ 
  * Research experience with FPGA, OpenCV, and embedded systems development

  
Work & Project Experience
======
* **Capstone Design Project Engineer, Northrop Grumman Sponsored**, _Aug 2024 – May 2025_ <br>
  **Northrop Grumman**, Melbourne, FL
	* Awarded **"Best Team"** in the University's **IPPD** program, placing first among all teams for overall project excellence, execution, and presentation.
	* Engineered an end-to-end automated asset tracking system for a secure Northrop Grumman lab space, integrating RFID, microcontrollers, and a custom data management framework.
	* [My team's blog](https://www.ippd.ufl.edu/blogs/ay2425team09/).

* **1-D Time Domain Convolution on FPGA**, _Nov 2024 - Dec 2024_ <br>
	* Achieved a **~15x performance speed-up** for 1-D convolution compared to a 667MHz ARM processor by designing a highly parallelized circuit on a Zedboard FPGA.
	* Maximized throughput with pipelined and unrolled convolution loops and dual-clock DRAM DMA interface with FIFO and handshake for reliable data transfer and to mitigate **metastability**.
	* Optimized memory bandwidth by implementing a smart buffer (sliding window) for efficient data reuse.
	* [Report](/posts/2024/12/Reconfig-final-project/)

* **Pong Game on FPGA**, _Apr 2024 – May 2024_ <br>
	* Developed a Pong game using VHDL with custom logic for game mechanics and VGA output.
	* Implemented FSM for game state control and optimized real-time performance.

* **Circuit Analysis Tool**, _Apr 2023 – May 2023_ <br>
	* Developed a C++ tool to calculate currents, voltages, and drops from netlist data.
	* Improved efficiency by **20%** with **dynamic programming** for complex circuits.


Honors & Awards
======
* **Ross Fellowship**, **_Purdue University_**, 2025
	* A competitive, fully funded award for the recruitment of outstanding PhD candidates.

* **Presidential Doctoral Excellence Awards**, **_Purdue University_**, 2025
	* A multi-year, university-wide fellowship awarded to a select cohort of top incoming PhD candidates based on academic merit and research potential.

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
* **Machine Learning:** TensorFlow, Scikit-learn
* **Technical Computing:** MATLAB
* **Version Control:** Git

## Digital Design & Hardware
* **HDL Languages:** VHDL, SystemVerilog
* **Verification:** UVM (Universal Verification Methodology)
* **High-Level Synthesis:** Vitis HLS
* **Software Defined Radio:** GNU Radio
* **Circuit Design:** LTspice, Altium Designer

## Professional & Technical Skills
* **Certifications:** Lean Six Sigma White Belt, NVIDIA Fundamentals of Deep Learning, Building Transformer-Based Natural Language Processing Applications
* **Documentation:** Technical Writing, Microsoft Office
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
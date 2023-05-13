---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Comunication Engineering, China University of Petroleum, 2020

Project experience
======
* Fall 2020: Microcontroller Development
  * Platform: Arduino UNO
  * Technology:C,3D Printing
  * Tasks:Start by easy project,such as RFID card swipe system, 
    traffic light, temperature and humidity display.
    Finally I finished making the tractor car.        
* Summer 2021: Website Design
  * Platform: IDEA,Tomact,Postman
  * Technology:HTML, CSS, js,machine learning,database
  * Tasks:Design of a high school volunteer application platform
  * Functions:Major inquiry, college inquiry, intelligent volunteer application,
   college entrance examination information browsing, etc.
* Fall 2021: Adjustable duty cycle square wave sawtooth wave generator
  * Platform: Multisim
  * Technology:Analog Electronics and Circuit board soldering
  * Functions:Dual-supply self-excited oscillation to generate ±5V sine wave;
  Designing signal conversion circuits to complete the conversion of sine wave signals 
  to square waves and square wave signals to sawtooth waves;Adjustable frequency and 
  duty cycle for both square and sawtooth waveforms.
 * Fall 2021: DTMF dial tone signal generation and detection
   * Platform: Matalb
   * Technology:Singal and System Analysis
   * Tasks:By designing a digital oscillator, the corresponding DTMF signal is generated 
   for the playback of dial tone. The DTMF signal amplitude and frequency map of 
   the corresponding four-digit number is given and decoded to the corresponding 
   four-digit number based on the analysis of the Fourier transform.
 * Summer 2022: Intelligent Attendance System
    * Platform: Pycharm
    * Technology: Python,OpenCV,Pytorch,Alexnet
    * Functions: Face entry, Face capture, Information matching, Attendance information 
      uploading to the cloud, Website management of attendance information.
 * Summer 2022:2FSK modulation circuit design and soldering
    * Platform: Mlitisum,AD18
    * Technology: Communication principles, Circuit fundamentals
    * Functions: Voltage regulator circuit, Pseudo-random sequence generation circuit, 
      Local oscillation generation circuit, Frequency divider circuit, Circuit for 2fsk modulation.
 * Fall 2022:Asynchronous FIFO design and implementation
    * Platform: Quartus Prime
    * Technology: Verilog
    * Task: Write full but not overflowing, read empty but not over read
    * Functions: Dual-port RAM for data storage,Full judgment and data writing controller
      Empty judgment and data reading controller,Empty and full judgment,Read or Write Synchronizer
 * Fall 2022:Digital transmission system for analog signals
    * Platform: Simulink 
    * Technology: Communication principles
    * Functions: The analog signal is transmitted after sampling, PCM coding,
      BPSK modulation and then restored at the receiver.
 <ul>{% for post in site.courses %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  


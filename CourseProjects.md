<span style="color:Blue;">Course Projects</span>
=========

<!--ts-->
   * [Computer Science Projects](#computer-science-projects)
     * [Interactive C Shell](#interactive-c-shell)
     * [File Sharing Protocol between client and server](#file-sharing-protocol-between-client-and-server)
     * [Style Transfer for Headshot Portraits](#style-transfer-for-headshot-portraits)
     * [Face classification](#face-classification)
     * [Multi Dimensional Divide and Conquer](#multi-dimensional-divide-and-conquer)
   * [Core ECE Projects](#core-ece-projects)
      * [ALU Design using Full Swing GDI technique](#alu-design-using-full-swing-gdi-technique)
      * [OFDM and OFDMA](#ofdm-and-ofdma)
      * [Adaptive Modulation Applications](#adaptive-modulation-applications)
      * [Wavelet based denoising of ECG Signal](#wavelet-based-denoising-of-ecg-signal)
      * [6T-SRAM Memory Array](#6t-sram-memory-array)
      * [Insertion Sort on FPGA](#insertion-sort-on-fpga)
      * [Square Wave Generator](#square-wave-generator)
      * [Class-D Power Amplifier](#class-d-power-amplifier)
      
<!--te-->


___

<span style="color:grey;">Computer Science Projects</span>
===========

Interactive C Shell
-----
- <span style="color:green;">Course: - </span> *Operating Systems*
* Developed a user-interactive shell in C, implementing the major features of GNU/Linux shell like piping, redirecting, handling background and foreground processes
  - [Link to project details](https://github.com/saikrishnacharan/Interactive-Shell)

File Sharing Protocol between client and server
-----
- <span style="color:green;">Course: -</span> *Communication Networks*
* File sharing protocol is created between client and server using socket programming which had functionalities like Indexed searching, File Hashing (using MD5 checksum), File transfer (UDP and TCP) and caching.
  - [Link to project details](https://github.com/saikrishnacharan/File-Transfer-Protocal-between-client-and-server)

Style Transfer for Headshot Portraits
-----
- <span style="color:green;">Course: - </span>*Digital Image Processing*
* Headshot portraits are a popular subject in photography but to achieve a compelling visual style requires advanced skills that a casual photographer will not have. 
* Presented a technique to transfer the style of an example head-shot photo onto a new one. This can allow one to easily reproduce the look of renowned artists. At the core of our approach is a new multiscale technique to robustly transfer the local statistics of an example portrait onto a new one. This technique matches properties such as the local contrast and the overall lighting direction while being tolerant to the unavoidable differences between the faces of two different people. 
  - [Link to project details](https://github.com/saikrishnacharan/Style-Transfer-for-Headshot-Potrait)
* Our proposed method output looks like:- 

  <img src="images/Headshot.png?raw=true"/>
  
  
Face Classification 
-----
- <span style="color:green;">Course: -</span>  *Statistical Methods in AI*
* Performed data reduction techniques like K-PCA, LDA and build classifers using Multi Layer Perceptron(MLP) and Support Vector Machines(SVM) on popular datasets for distinguishing image classes.
  - [Link to project details](https://github.com/saikrishnacharan/Image-Classification)

Multi Dimensional Divide and Conquer
-----
- <span style="color:green;">Course: -</span>  *Operating Systems*
* Used this paradigm to solve domination and closest point problems in k-dimensional space and performed complexity analysis.
* Algorithms analyzed are All-points ECDF problem, ECDF Searching Problem, Maxima Finding, Maxima Searching, Range Searching, Fixed-Radius Near Neighbors, Nearest Neighbours.
  - [Link to project details](https://github.com/saikrishnacharan/Multi-Dimensional-Divide-and-Conquer)

<span style="color:grey;">Core ECE Projects</span>
===========

ALU-Design-using-Full-Swing-GDI-technique
-----
- <span style="color:green;">Course: -</span>  *Digital VLSI Design*
* Desinged a 4-bit Arithmetic Logical Unit in LTSpice using Full Swing GDI technique with optimized Area, Speed and Transistor count.
* Also talked about various logic design techniques and we justify why GDI (Gate Diffusion Input) technique is the best compared to others. 
  - [Link to project details](https://github.com/saikrishnacharan/ALU-Design-using-Full-Swing-GDI-technique)

OFDM and OFDMA
-----
- <span style="color:green;">Course: -</span>  *Communication Networks*
* End to end modelling of OFDM and OFDMA is studied and compared with other existed multiplexing and multiple access schemes
  - [Report](/pdf/Communication_Networks_Project1_OFDM_OFDMA.pdf)  |  [Slides](/pdf/CN_Slides_OFDM.pdf)
  
Adaptive Modulation Applications
-----
- <span style="color:green;">Course: -</span>  *Wireless Communications*
* Studied different adaptive modulation techniques for various scenarios and analyzed how BER and average spectral efficiency improve with adaption.
* Also analyzed Varialbe Rate - Variable Power MQAM, Adaptive techniques in Fast and Slow Fading, Use of Adaptive techniques for Coding Issues and Capacity and discussed present case scenario and technology (5G) where adaptive technquies are used.
* Various simulations are done using MATLAB. 
  - [Link to project details](https://github.com/saikrishnacharan/Adaptive-Modulation)
 
Wavelet based denoising of ECG Signal
-----
 - <span style="color:green;">Course: -</span>  *Digital Signal Processing*
 * Detrended and then denoised the ECG signal using wavelet denoising technique making QRS complex more distinct and identified peaks and valleys of denoised ECG signal.
 * Our main aim of project is to remove those noises and detect QRS complex of ECG signal.
 * This project is a modified version of Pan-Tompkins algorithm which detects QRS complexes in ECG signals.
   - [Link to project details](https://github.com/saikrishnacharan/Wavlet-based-denoising-of-ECG-signal)

 * Our proposed method output looks like:-
 
    <img src="images/DSP_Wavlet_based_denoising.png?raw=true"/>
    
6T-SRAM Memory Array
-----
  - <span style="color:green;">Course: -</span>  *Digital VLSI Design*
  * Modelled Parasitic capacitances and analysis of Noise Margin, Power, Delay, Rise Time and Fall Time is done. 
  * Analysis is done using Cadence-Virtuoso
  * Design Details (Links of pdfs)
    - [Decoder Design](/pdf/20171140_Decoder.pdf)
    - [Single SRAM Design](/pdf/20171140_SRAM.pdf)
    - [Array SRAM Design](/pdf/20171140_Array_SRAM.pdf)

Insertion Sort on FPGA
------
- <span style="color:green;">Course: -</span>  *Embedded Hardware Design*
* Implemented accelerated Insertion sort on FPGA (Zedboard Zync-7000).
* Included Parallelism and blocks like BRAM , FIFO. Xilinx-Vivado is the software used.
* Also analyzed power consumption and complexity of algorithm compared to normal processor.
  - [Link to project details](/pdf/EHD_project.pdf)

Square Wave Generator
-----
- <span style="color:green;">Course: -</span>  *Linear Electronic Circuits*
* Implemented Transistor level Design of Square wave generator on Cadence with minimum power consumption and MOSFET’s being in subthreshold region of operation.
* Building blocks of design are Current Source, 2-Stage Amplifier (acts as comparator), D-FlipFlop and Buffer.
* Above blocks are designed using Cadence-Virtuoso in Transistor level.
  - [Link to project details](/pdf/LEC_Project.pdf)

Class-D Power Amplifier
-----
- <span style="color:green;">Course: -</span>  *Electronic Workshop*
* Implemented Class D power amplifier with efficiency around 80-90% on breadboard.


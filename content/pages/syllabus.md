---
content_type: page
description: The syllabus section provides the course overview and information on
  prerequisites, lecture topics, laboratory projects, bibliography, grading, and recommended
  citation.
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: 56042719-319d-3af6-691e-a312c80b0d80
---

Course Meeting Times
--------------------

Lectures: 2 sessions / week, 1.5 hours / session

Labs: 1 session / week, 4 hours / session

Overview
--------

This course presents the fundamentals of digital signal processing with particular emphasis on problems in biomedical research and clinical medicine. It covers principles and algorithms for processing both deterministic and random signals. Topics include data acquisition, imaging, filtering, coding, feature extraction, and modeling. The focus of the course is a series of labs that provide practical experience in processing physiological data, with examples from cardiology, speech processing, and medical imaging. The labs are done on the MIT Server in MATLAB® during weekly lab sessions that take place in an electronic classroom. Lectures cover signal processing topics relevant to the lab exercises, as well as background on the biological signals processed in the labs.

Prerequisites
-------------

6.003 Signals and Systems, 2.004 Dynamics and Control II, 16.004 Unified Engineering IV, or 18.085 Computational Science and Engineering I.

Lecture Topics
--------------

1.  Biomedical Signals and Images
    *   ECG: Cardiac electrophysiology, relation of electrocardiogram (ECG) components to cardiac events, clinical applications. Guest lecture.
    *   Speech Signals: The source-filter model of speech production, spectrographic analysis of speech.
    *   Speech Coding: Analysis-synthesis systems, channel vocoders, linear prediction of speech, linear prediction vocoders.
    *   Imaging Modalities: Survey of major modalities for medical imaging: ultrasound, X-ray, CT, MRI, PET, and SPECT.
    *   MRI: Physics and signal processing for magnetic resonance imaging. Guest lecture.
    *   Surgical Applications: A survey of surgical applications of medical image processing. Guest lecture.
2.  Fundamentals of Deterministic Signal and Image Processing
    *   Data Acquisition: Sampling in time, aliasing, interpolation, and quantization.
    *   Digital Filtering: Difference equations, FIR and IIR filters, basic properties of discrete-time systems, convolution.
    *   DTFT: The discrete-time Fourier transform and its properties. FIR filter design using windows.
    *   DFT: The discrete Fourier transform and its properties, the fast Fourier transform (FFT), the overlap-save algorithm, digital filtering of continuous-time signals.
    *   Sampling Revisited: Sampling and aliasing in time and frequency, spectral analysis.
    *   Image processing I: Extension of filtering and Fourier methods to 2-D signals and systems.
    *   Image processing II: Interpolation, noise reduction methods, edge detection, homomorphic filtering.
3.  Probability and Random Signals
    *   PDFs: Introduction to random variables and probability density functions (PDFs).
    *   Classification: Bayes' rule, detection, statistical classification.
    *   Estimating PDFs: Practical techniques for estimating PDFs from real data.
    *   Random signals I: Time averages, ensemble averages, autocorrelation functions, crosscorrelation functions.
    *   Random signals II: Random signals and linear systems, power spectra, cross spectra, Wiener filters.
    *   Blind source separation: Use of principal component analysis (PCA) and independent component analysis (ICA) for filtering.
4.  Image Segmentation and Registration
    *   Image Segmentation: statistical classification, morphological operators, connected components.
    *   Image Registration I: Rigid and non-rigid transformations, objective functions.
    *   Image Registration II: Joint entropy, optimization methods.

Laboratory Projects
-------------------

### Optional: Fundamentals of MATLAB®

Optional introduction/review of software package used throughout the semester. (1 week - Siracusa)

1.  ECG Filtering and Frequency Analysis of the Electrogram Design filters to remove noise from electrocardiogram (ECG) signals and then design a system to detect life-threatening ventricular arrhythmias. The detector is tested on normal and abnormal ECG signals. (3 weeks - Greenberg)
2.  Speech Coding Implement, test, and compare two speech analysis-synthesis systems. These systems utilize a pitch detector and a speech synthesizer based on the source-filter model of speech production. (3 weeks - Greenberg)
3.  Image Segmentation Process clinical MRI scans of the human brain to reduce noise, label tissue types, extract brain contours, and visualize 3-D anatomical structures. (2 weeks - Fisher)
4.  Image Registration Explore the co-registration of medical images, focusing on 2-D to 2-D (slice to slice) registration and using non-linear optimization methods to maximize various measures of image alignment. (2 weeks - Fisher)
5.  ECG: Blind Source Separation Separate fetal and maternal ECG signals using techniques based on second- and higher-order statistical methods. Techniques include Wiener filtering, principal component analysis, and independent component analysis. (2 weeks - Clifford/Greenberg)

Bibliography
------------

### General

Oppenheim, A. V., and R. W. Schafer, with J. R. Buck. _Discrete-Time Signal Processing_. 2nd ed. Upper Saddle River, NJ: Prentice-Hall, 1999. ISBN: 9780137549207.

Papoulis, A., and S. U. Pillai. _Probability, Random Variables, and Stochastic Processes_. New York, NY: McGraw Hill, 2001. ISBN: 9780072817256.

### Basics

{{% resource_link "6f3e6438-2de4-478c-a9fa-9bd899319653" "![Buy at MIT Press](/images/mp_logo.gif)" %}} Siebert, W. M. {{% resource_link "6f3e6438-2de4-478c-a9fa-9bd899319653" "_Circuits, Signals and Systems_" %}}. Cambridge, MA: MIT Press, 1985. ISBN: 9780262192293.

Oppenheim, A. V., and A. S. Willsky, with H. Nawab. _Signals and Systems_. 2nd ed. Upper Saddle River: Prentice-Hall, 1996. ISBN: 9780138147570.

Karu, Z. Z. _Signals and Systems Made Ridiculously Simple_. Huntsville, AL: ZiZi Press, 1995. ISBN: 9780964375215.

### Probability and Classification

Duda, R., and P. Hart. _Pattern Classification and Scene Analysis_. New York, NY: John Wiley & Sons, 1973. ISBN: 9780471223610.

Duda, R., P. Hart, and D. Stork. _Pattern Classification_. 2nd ed. New York, NY: John Wiley & Sons, 2000. ISBN: 9780471056690.

Bishop, C. _Neural Networks for Pattern Recognition_. New York, NY: Oxford University Press, 1996. ISBN: 9780198538646.

Nabney, I. {{% resource_link "359649d3-4dcc-42e2-b350-df8ef2412232" "_Netlab: Algorithms for Pattern Recognition_" %}}. 3rd ed. New York, NY: Springer, 2004. ISBN: 9781852334406.

### ECG Analysis

Clifford, G., F. Azuajae, and P. McSharry. {{% resource_link "39687ecb-27f8-4020-8025-2b2cab1ac9ff" "_Advanced Methods and Tools for ECG Data Analysis_" %}}. Norwood, MA: Artech House, 2006. ISBN: 9871580539661.

### Speech Analysis

Rabiner, L. R., and R. W. Schafer. _Digital Processing of Speech Signals_. Upper Saddle River, NJ: Prentice-Hall, 1978. ISBN: 9780132136037.

Quatieri, T. F. _Discrete-Time Speech Signal Processing: Principles and Practice_. Upper Saddle River, NJ: Prentice-Hall, 2001. ISBN: 9780132429429.

### Image Processing and Medical Imaging

Lim, J. S. _Two-Dimensional Signal and Image Processing_. Upper Saddle River, NJ: Prentice Hall, 1989. ISBN: 9780139353222.

Gonzalez, R., and R. E. Woods. _Digital Image Processing_. 2nd ed. Upper Saddle River, NJ: Prentice-Hall, 2002. ISBN: 9780201180756.

Epstein, C. L. _Mathematics of Medical Imaging_. Upper Saddle River, NJ: Prentice Hall, 2003. ISBN: 9780130675484.

Webb, S. _The Physics of Medical Imaging_. New York, NY: Taylor & Francis, 1988. ISBN: 9780852743492.

Westbrook, C., C. Kaut Roth, and T. Talbot. _MRI in Practice_. 3rd ed. Malden, MA: Blackwell Science, Inc., 2005. ISBN: 9781405127875.

Macovski, A. _Medical Imaging Systems_. Upper Saddle River, NJ: Prentice Hall, 1983. ISBN: 9780135726853.

Grading
-------

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
ACTIVITIES
{{< thclose >}}
{{< thopen >}}
PERCENTAGES
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
Lab reports (5 total)
{{< tdclose >}}
{{< tdopen >}}
60%
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Quizzes (2 total)
{{< tdclose >}}
{{< tdopen >}}
25%
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Problem sets (5 total)
{{< tdclose >}}
{{< tdopen >}}
10%
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Class participation
{{< tdclose >}}
{{< tdopen >}}
5%
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Problem sets are graded on a 0-4 scale, as follows:

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
GRADING POINTS
{{< thclose >}}
{{< thopen >}}
CRITERIA
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
Problem set contains few to no errors, indicating a thorough understanding of the material
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
Problem set contains some errors, indicating a less-than-thorough understanding of the material
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
Problem set is complete, but numerous errors indicate a lack of understanding of the material
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
Problem set is incomplete
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
0
{{< tdclose >}}
{{< tdopen >}}
Problem set not handed in, or is handed in late without prior arrangement
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}
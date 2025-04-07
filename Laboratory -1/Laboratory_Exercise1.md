DSP - Laboratory Exercise 1

Group Members:
Neil Robert Lagsub 
Domingo Third Villanueva


I. OBJECTIVES:
In this laboratory exercise, the students are expected to:
  *  Find Discrete Fourier Transform and Inverse Discrete Fourier Transform of given digital signal..

II. MATERIALS:
  * Software: MATLAB
    
III. PROCEDURE:
THEORY:
Basic equation to find the DFT of a sequence is given below. 

![image](https://github.com/user-attachments/assets/71ddba97-8029-4ae9-8b19-96351462c1e6)

Basic equation to find the IDFT of a sequence is given below. 

![image](https://github.com/user-attachments/assets/9e6baa19-6d00-42cb-9473-8d41bd0007d4)

Algorithm:
Step I: Get the input sequence.
Step II: Find the DFT of the input sequence using direct equation of DFT.
Step III: Find the IDFT using the direct equation.
Step IV: Plot DFT and IDFT of the given sequence using matlab command stem.
Step V: Display the above outputs.

Flow chart:

![image](https://github.com/user-attachments/assets/9ecef2a4-8f77-4232-b538-629d1c764567)

Output Waveforms:

![image](https://github.com/user-attachments/assets/c441d9bb-e48a-4400-9c4e-9729b385c3f2)

RESULT:

VIVA QUESTIONS:
1. Define signal, Give Examples for 1-D, 2-D, 3-D signals.
* Signal: A signal is a function that conveys information about the behavior or attributes of some phenomenon.

* 1-D signal: Depends on one variable (e.g., audio signal as a function of time).

* 2-D signal: Depends on two variables (e.g., image as a function of x and y coordinates).

* 3-D signal: Depends on three variables (e.g., video or 3D medical scans over space and time).

2. Define transform. What is the need for transform?
* Transform: A mathematical technique that converts a signal from one domain to another (e.g., time to frequency).
  
3. Differentiate Fourier transform and discrete Fourier transform.
* The Fourier Transform analyzes continuous signals and gives a continuous frequency spectrum. The Discrete Fourier Transform (DFT) works on sampled (discrete) signals and provides a finite set of frequency components, making it suitable for digital systems.

4. Differentiate DFT and DTFT
* The DTFT applies to infinite-length sequences and gives a continuous spectrum. The DFT is used for finite-length sequences and gives a discrete spectrum—ideal for computation and real-world digital signal processing.

5. Explain mathematical formula for calculation of DFT.

![image](https://github.com/user-attachments/assets/e77ad5b3-92ed-4382-a80c-e2e8b2fb9fe2)
* It transforms a time-domain signal x(n)x(n) into its frequency-domain form X(k)X(k), using complex exponentials as basis functions.   

6. Explain mathematical formula for calculation of IDFT.

![image](https://github.com/user-attachments/assets/fdfab41f-ac6a-461c-9b39-6576ee0d6d2a)

* It reconstructs the original signal from its frequency components by reversing the DFT process.
7. How to calculate FT for 1-D signal?

  ![image](https://github.com/user-attachments/assets/7f50930c-fc1e-418d-bb19-0d0d88189426)

* This expresses the signal in terms of its frequency content.

8. What is meant by magnitude plot, phase plot, power spectrum?
* Magnitude plot: Shows frequency strength.

* Phase plot: Shows the phase shift of each frequency.

* Power spectrum: Shows energy at each frequency, calculated as ![image](https://github.com/user-attachments/assets/874359b9-ee75-44fa-a3f1-8a27da0347d7)

9. Explain the applications of DFT.
* DFT is used in audio and image processing, communication systems (like 4G/5G), biomedical signal analysis, and spectrum analysis, helping extract frequency information and enable compression/filtering.
      
10. What are separable transforms?
*Separable transforms allow multi-dimensional processing by applying 1D transforms separately on rows and columns. They're widely used in image and video processing (e.g., 2D DFT, DCT).

Exercise:
1. Find 8-point DFT of the sequence x (n) = [1 2 3 4 4 3 2 1] 




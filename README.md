# Fast-Fourier-Transform-in-C
This repository contains the C code for ARM Implementation of FFT on Zynq-7000 APSoC from Xilinx.

Abstract:
Nowadays, the development of the Fast Fourier Transform (FFT) remains of a great importance due to its substantial role in the field of signal processing. 
In this project, a radix-2 algorithm of the FFT, 8 point is proposed and its software implementation on the Zynq 7000 all programmable SoC is discussed. Complete project is carried out in the Xilinx SDK and the code is cross-compiled on the ARM cortex A9 processor present in the Zynq SoC. The Xilinx Software Development Kit (SDK)
is an Integrated Development Environment (IDE) for development of embedded software applications targeted towards Xilinx embedded processors. The SDK provides
feature-rich C/C++ code editor and compilation environment which is exactly needed in this case since the algorithm is brought to life in the form of C code. The SDK
also provides for System level performance analysis which is also depicted in this project for the FFT algorithm. Zynq 7000 all programmable soc is chosen for the 
project since it comes with both the processing system and programmable logic. Hence it is crucial to compare the performance of PS only with that of PL in the picture since the integration of PL with PS on Zynq 7000 gives rise to higher bandwidth. Hence, this project also analyses the performance of the ARM (PS) implementation of FFT algorithm on the Zynq 7000 All Programmable SoC.

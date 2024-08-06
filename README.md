# Improved Quantum Rebound Attacks on Double Block Hashing with Round-Reduced AES-256 and ARIA-256

## Overview

This repository contains codes for the paper titled **''Improved Quantum Rebound Attacks on Double Block Hashing with Round-Reduced AES-256 and ARIA-256.''**

## Contents

### Q_State_Preparation.ipynb
This script includes quantum state preparation using single-qubit rotation gates presented in Appendix A. This notebook is designed to run on Google Colab, ensuring compatibility across different operating systems and software versions. The notebook includes cells for installing the necessary Qiskit libraries.

The only parameters you need to modify are n and S in the first cell. Currently, the code is set with:

n = 8 

S = [1,5,25,97,77,88,33,27,19,240,255,59,30] 

The program ultimately generates the quantum state

![image](https://github.com/user-attachments/assets/81a6c050-993b-493f-b498-c672c2beb7c1)

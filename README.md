#  Audio Watermarking Project

## Overview
This watermark project implements a **robust and imperceptible audio watermarking system** using **FFT-domain embedding** and **optimization techniques**.  
The watermark is embedded in perceptually significant frequency components and detected using a correlation-based approach, ensuring resilience against common signal processing attacks.

---

## Team Members

| Name | Roll Number |
|------|-------------|
| Ishwarya | CB.SC.U4AIE24220 |
| Himavarshini | CB.SC.U4AIE24228 |
| Meghana K | CB.SC.U4AIE24232 |
| Ranjith | CB.SC.U4AIE24250 |

---

## References

1. I. J. Cox, J. Kilian, F. T. Leighton, T. Shamoon,  
   **Secure Spread Spectrum Watermarking for Multimedia**, IEEE Transactions on Image Processing  
   https://ieeexplore.ieee.org/document/597272

2. Pranab Kumar Dhar, Jong-Myon Kim,  
   **Digital Watermarking Scheme Based on Fast Fourier Transformation for Audio Copyright Protection**,  
   International Journal of Security and Its Applications, Vol. 5, No. 2, April 2011  
   https://www.earticle.net/Article/A171143

3. Stephen Boyd et al.,  
   **Distributed Optimization and Statistical Learning via ADMM**  
   https://web.stanford.edu/~boyd/papers/pdf/admm_distr_stats.pdf

##  Project Outline

### Problem
Digital audio content is easily copied and redistributed without ownership verification.

### Objective
- Embed an imperceptible watermark into audio signals  
- Ensure reliable detection after common signal processing attacks

### Methodology
1. Audio input acquisition  
2. FFT transformation  
3. Frequency bin selection  
4. Watermark embedding  
5. ADMM-based optimization  
6. Inverse FFT reconstruction  
7. Correlation-based detection  
8. Performance evaluation

### Tools & Technologies
- MATLAB / Python  
- FFT / IFFT  
- ADMM Optimization  
- Evaluation: SNR, Correlation, BER

---

##  Current Updates

- Literature review completed  
- FFT-based embedding implemented  
- Watermark detection module ready  
- Optimization integrated  
- Initial robustness testing completed

---

##  Challenges

- Selecting optimal frequency bins  
- Maintaining imperceptibility  
- Parameter tuning for optimization  
- Robust detection under attacks

---

##  Future Plans

- Adaptive watermark embedding  
- Improved robustness against compression and time scaling  
- AI-assisted watermark optimization  
- Real-time implementation  
- Publication-ready evaluation

---

##  Repository Structure



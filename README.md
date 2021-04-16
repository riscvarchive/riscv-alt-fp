# RISC-V Alternate FP Format

## About
This repository is used to develop standardisation proposals for RISC-V Alternate Floating-Point Formats.

## Motivation

Low-bit-width quantization has been proposed in order to compress the neural network without hurting performance. 
Neural networks are far more sensitive to the size of the exponent than that of the mantissa, so some alternate FP formats 
hold the potential to improve performance over IEEE-FP in some specific fields. 
Brain floating-point format (bfloat16/BF16) ,as a non-IEEE floating point format, is designed
to be used in hardware accelerating machine learning algorithms, many AI frameworks and AI libraries both 
support BF16 data by default. 

## Short-term Actions
- Get lightweight BF16 standards process approved.
- Provide a framework for BF16 formats encodings.
- Consider defining RISC-V instructions for BF16 formats.

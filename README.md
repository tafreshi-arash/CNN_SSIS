# CNN_SSIS
This project contains the Google Colab files for the CNN_SSIS project

__ File Description __

1. Universal_Classification_Resnet18_4class:
This file fine-tunes a CNN based on ResNet-18 using the COCO database. Eight datasets, including clean and "dirty" data with various distortions—asynchronization (shift attack), rotation, blurring, contrast change, brightness change, additive random noise, and additive Gaussian noise—are utilized for fine-tuning. The final result of this code is a Universal CNN model that is robust against all mentioned attacks.

2. Universal_Robustness_Evaluation_With_Attacks:
This file evaluates the robustness of proposed watermarking method against various attacks.
   
3. General_Transparency_Evaluation:
This file evaluates the transparency of the watermarked image both in an ideal mode (without any attacks) and under attacks.
   
4. Effect_of_Mask_Ratio_on_Transparency_Robustness:
This file analyzes the effect of the mask ratio on transparency and Robustness (BER).

5. PRNG_vs_WavePettern:
This file analyzes other Pseudo-Random Number Generation (PRNG) methods and examines the advantage of using a sinusoidal wave pattern over other PRNG methods.

6. Correlation_Detector_vs_CNN:
This file analyzes the advantage of using a CNN detector compared to a Correlation detector.

7. Watermarking_Classes: Containing classes and functions
   
8. MyWatermarkinClasses: Containing classes and functions

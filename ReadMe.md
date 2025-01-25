

# Limitations of Gradient Shaping as a defense against Data Poisoning

This is the official implementation of the project - Limitations of Gradient Shaping Against Data Poisoning.



# Features
- Clean label backdoor attack
- Blend Patch-based backdoor attack
- DP-SGD implementation and extension to models with batch-norm
- Physical world attack
- Work with the case that models are trained from scratch

# Requirements
+ Python >= 3.6
+ PyTorch >= 1.10.1
+ TorchVisison >= 0.11.2
+ OpenCV >= 4.5.3
+ Opacus >= 1.2

# Usage & HOW-TO
Use the 'DP-SGD Narcissus CIFAR.ipynb' notebook for implementing the NARCISSUS backdoor attack with DP-SGD and 'DP-SGD Blend CIFAR.ipynb' to implement Blend attack with DP-SGD. The default attack and defense state both use Resnet-18 as the model, with SmallCNN as an alternative. CIFAR-10 is the target dataset, and the default attack poisoning rate is 1%. 

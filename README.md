# ntab-fmri-reconstruction
fMRI Image Reconstruction, Neurotech@Berkeley

Fully self-contained multi-phase image generation:
https://colab.research.google.com/drive/12W2U426YXYYagJ_mpuKH0SZWUtvUUC5w?usp=sharing

Original paper: https://www.nature.com/articles/s41598-023-42891-8
Improvements:
* RAM-safety, massive memory and speedup optimizations to enable accessible Colab computing
* Swapped first phase model with fully-connected MLP regression network that maps fMRI vectors to latent diffusion vectors
* Swapped second phase model with LCM-LoRA latent diffusion prompt-based image generator

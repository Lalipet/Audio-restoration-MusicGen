# Audio-restoration-MusicGen
A pipeline to enhance MusicGen audio quality through preprocessing, denoising and neural bandwidth extension

## Project Overview  
This project proposes a **post-processing restoration pipeline** that operates on generated audio without modifying the generative model itself.

The pipeline includes:
1. Audio generation using MusicGen:
Select random prompts form a list with 5 prompts per genre
2. Peak normalization and high-pass filtering:
- Denoising  
- Neural bandwidth extension using a HiFi-GAN–based model  

---
## References
- https://github.com/facebookresearch/audiocraft
- https://github.com/timsainb/noisereduce
- https://github.com/brentspell/hifi-gan-bwe
 

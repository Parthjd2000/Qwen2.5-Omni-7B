# Qwen2.5-Omni-7B – Speech-to-Speech Notebook

This repository contains a Jupyter notebook for running **Qwen2.5-Omni-7B** as a **speech-to-speech (S2S)** model on GPU. It was created as part of a graduate research project comparing different S2S systems (Moshi, NeMo, Qwen2.5-Omni) on latency and naturalness.

The notebook demonstrates:

- Loading **Qwen2.5-Omni-7B** with the correct Transformers branch  
- Running **text** and **audio (speech)** prompts  
- Generating **spoken replies**  
- Measuring **end-to-end latency** for S2S turns  
- Saving generated audio for MOS / naturalness evaluation  

# Drawing-from-Diffusion
Database of generated images for Thesis Studio GenAI 2024-2025


--------------------
Appendix: AI-Based Video Generation

Recent advancements in artificial intelligence have significantly enhanced video generation capabilities, 
primarily through the use of diffusion models. These models synthesize video content by iteratively denoising random input, 
progressively forming coherent sequences of video frames based on natural language prompts. 
The integration of large language models and neural networks enables both semantic alignment and temporal consistency across frames.

A range of tools and frameworks are now available, varying in complexity and intended use. 
These include user-friendly interfaces for rapid prototyping as well as advanced systems offering detailed narrative control. 
These tools demonstrate the growing accessibility and creative potential of AI video generation, 
with ongoing research continuously improving quality, control, and application scope. 


Key developments in this field include:

Imagen Video (Google Research): A multi-stage diffusion model enabling high-resolution, text-to-video generation. (https://imagen.research.google/video/)
For additional technical detail, see the Imagen Video publication on arXiv. (https://arxiv.org/abs/2210.02303)

Stable Video Diffusion (Stability AI): An open-source framework supporting detailed animation and scene coherence. (https://stable-diffusion-art.com/stable-video-diffusion-img2vid/)

W.A.L.T.: A transformer-based approach designed for efficient and photorealistic video synthesis. (https://walt-video-diffusion.github.io/assets/W.A.L.T.pdf)

LTX Studio: A platform offering granular control over narrative structure and character behavior, oriented toward storytelling applications. (https://ltx.studio)

Sora (OpenAI): A high-performance model focused on producing professional-grade video content. (https://openai.com/sora/)

--------------------




--------------------
Appendix: Low-Rank Adaptation (LoRA) for Model Fine-Tuning

Low-Rank Adaptation (LoRA) is a parameter-efficient fine-tuning technique that enables the customization of large generative models, 
such as those used for image and video synthesis, without requiring full retraining. 
By introducing a small number of additional trainable parameters into the model architecture, 
LoRA allows for targeted adaptation to specific styles, subjects, or tasks using relatively limited computational resources.

The typical LoRA training process involves curating a relevant dataset, 
selecting appropriate training parameters such as learning rate and number of epochs, 
and employing specialized tools to generate a LoRA file. This file can be merged with a base model to guide generation according to the desired output characteristics.
These resources collectively form a solid foundation for applying LoRA in various creative and research contexts, 
offering accessible and effective pathways for model customization.


Several guides and tutorials provide practical support for both beginners and advanced users:

Kohya tutorials offer detailed, step-by-step instructions for training LoRA models locally. (https://www.youtube.com/watch?v=sQpP8bHjHRo - https://vancurious.ca/generative-AI-Kohya - https://www.mimicpc.com/ja/learn/kohya-ss-lora-training-guide)

This Colab-based training guide outlines a cloud-based workflow for users without access to a local GPU. (https://www.reddit.com/r/StableDiffusion/comments/110up3f/i_made_a_lora_training_guide_its_a_colab_version/)

This Stable Diffusion Art guide presents a written overview of dataset preparation and parameter tuning. (https://stable-diffusion-art.com/train-lora/)

This RunPod Blog explains video-specific LoRA training, including infrastructure setup and hyperparameter selection. (https://blog.runpod.io/complete-guide-to-training-video-loras/)

This SeaArt guide explores advanced techniques such as mixed precision and optimization of training cycles. (https://docs.seaart.ai/guide-1/3-advanced-guide/3-2-lora-training-advance)

--------------------

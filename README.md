# Knee Osteoarthritis Image Generation with Diffusion Models

A personal project exploring the application of diffusion models for generating synthetic medical images, specifically focusing on knee X-rays from the Knee Osteoarthritis Dataset.

## Project Overview
I developed an end-to-end pipeline for training a diffusion model to generate realistic knee X-ray images. This project allowed me to gain hands-on experience with:

- **State-of-the-art generative modeling:** Implemented a diffusion model from scratch using PyTorch, learning the intricacies of the denoising process and loss functions
- **Deep learning infrastructure:** Set up efficient training loops with proper logging, checkpointing, and evaluation metrics

## Technical Implementation
The project consists of several key components:
- Custom dataset class for handling medical imaging data
- U-Net architecture modified for the diffusion process
- Training pipeline with noise scheduling and denoising
- Evaluation framework using FID and SSIM metrics

## Results and Insights
Through this project, I successfully:
- Generated synthetic knee X-rays that preserve anatomical structures
- Implemented conditional generation based on osteoarthritis severity
- Achieved an FID score of 85.41 and IS of 1.03 compared to real images

The most challenging aspects were handling the medical data peculiarities and tuning the diffusion parameters for stable training. This project significantly deepened my understanding of both generative AI and medical image processing.

### Future Improvements
- Experiment with more advanced architectures like ADM
- Incorporate additional medical metadata for better controlled generation
- Explore applications in data augmentation for medical AI training

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

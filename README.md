### Denoising Diffusion Probabilistic Model Implementation on Kaggle Flowers
A hands-on, reproducible PyTorch implementation showcasing Denoising Diffusion Probabilistic Models (DDPMs) trained on the Kaggle Flowers dataset. This project demonstrates the entire pipeline—from dataset preparation, training, checkpointing, and logging, to visualizing sampling of synthetic images and generating videos—using best practices and modular code structure.

### Key Features
- Full DDPM Pipeline: Includes forward diffusion, reverse/sampling algorithms, visualization, and logging.

- PyTorch-based Modular Code: Utilizes classes for configuration, data loading, diffusion process, and training for extensibility and clarity.

- Kaggle Integration: Seamlessly downloads and uses the Flowers Recognition dataset using kagglehub.

- Configurable Training: Easy adjustment of timesteps, epochs, model architecture, batch sizes, and device selection.

- Mixed-Precision Training: Optionally leverages PyTorch’s AMP for faster training (configurable).

- Checkpointing & Logging: Automated directory structure for logs/results and checkpoints.

- Sampling Visualization: Generate grid images and videos to inspect model performance.

- Clear Separation of Concerns: Data, models, configs, training, sampling, and result saving handled independently.



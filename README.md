# Knee OsteoArthritis Image Generation Challenge

For this task, we invite you to develop a working pipeline for image generation using a 2D medical imaging dataset. You may use the Knee Osteoarthritis Dataset on Kaggle or any other similar 2D medical imaging dataset of your choice.

## Task Description
You will need to submit your code (either Python scripts or a tidy Jupyter Notebook) for training an image generation model. For this task:
- **Preferred approach:** We encourage the use of Diffusion models, as they represent the state-of-the-art in generative modeling.
- **Alternative approach:** If you are more familiar with GANs, you may choose this approach instead.

We recognize that the time constraints make this task extremely challenging if you are not already familiar with these types of models. If you believe this is the case, we strongly encourage you to consider the Image Segmentation task instead.
Regardless of the model you choose, your submission should demonstrate the following:
- **Dataset handling:** Loading and pre-processing the dataset appropriately for your model.
- **Model training:** Implementing the training pipeline and ensuring the model trains properly.
- **Visual output evaluation:** Producing generated images that demonstrate the model is learning effectively. High-quality outputs are not required; we are looking for generations where the overall shapes and structures make sense.
Flexibility with Datasets

If you find accessing or preparing the suggested dataset is taking too much of your allotted time, you may switch to any 2D medical imaging dataset of your choice to simplify the process.

### Optional Extensions
- Add controllable generation (e.g., osteoarthritis severity)
- Add quantitative evaluation using FID and SSIM
- Writing a technical report describing your methods and results in the format of a conference paper

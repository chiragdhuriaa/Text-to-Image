# Text-to-Image

![output](https://github.com/user-attachments/assets/cc7315dd-d102-4a86-a687-10c778c18d8d)


Overview

This project leverages the power of machine learning and artificial intelligence to generate stunning images from textual descriptions. Using the Stable Diffusion model, a cutting-edge AI model for image generation, users can input a text prompt, and the system will create a high-quality image that matches the description. The model is optimized for fast performance and uses FP16 precision to enhance processing speed and efficiency.
Features

    1. Text-to-Image Generation: Input any text prompt, and the model will generate a corresponding image. For example, describing "a cat on Mars" can result in a creative image of a cat on the Martian surface.
    2. NSFW Filter: The system includes a built-in mechanism to detect and block explicit content by filtering out unsafe keywords.
    3. Customizable Parameters: Users can adjust the guidance scale to control the creativity and fidelity of the generated images.
    4. Save and Display: Once an image is generated, it is displayed within the application and saved to a local file for further use.

Technology Stack

    1. PyTorch: The AI model is built using PyTorch, a popular deep learning library, for efficient model loading and inference.
    2. Diffusers: The image generation pipeline is powered by the diffusers library, which includes pre-trained models like Stable Diffusion.
    3. CUDA Support: For faster processing, the model utilizes GPU acceleration through CUDA, falling back to CPU if no GPU is available.

How It Works

    1. Input: The user provides a text prompt describing the desired image.
    2. Processing: The prompt is passed to the Stable Diffusion model, which uses deep learning to generate a high-quality image that corresponds to the description.
    3. Safety Check: The system automatically filters for potentially harmful or explicit content, ensuring a safe experience.
    4. Output: A generated image is displayed on the screen and saved to disk as a .jpg file.

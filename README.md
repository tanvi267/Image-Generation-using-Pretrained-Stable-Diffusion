# Image-Generation-using-Pretrained-Stable-Diffusion
Implemented a pretrained Stable Diffusion model using the Hugging Face Diffusers library to generate images from text prompts.

## 📌 Aim

To implement a pretrained Stable Diffusion model using the Hugging Face Diffusers library to generate images from text prompts and analyze the impact of inference steps, guidance scale, and different sampling methods on the quality of generated images.

## 🛠️ Technologies Used

* Python
* Google Colab
* Hugging Face Diffusers
* PyTorch
* Transformers
* Accelerate
* Stable Diffusion v1.5
* Matplotlib
* PIL (Python Imaging Library)

## 🧠 About Stable Diffusion

Stable Diffusion is a text-to-image generative AI model that creates images based on natural language descriptions (prompts). It uses a latent diffusion process to gradually remove noise and generate high-quality images.

## ⚙️ Implementation Steps

1. Install the required Python libraries.
2. Import the necessary modules.
3. Load the pretrained Stable Diffusion v1.5 model.
4. Provide a text prompt and generate an image.
5. Analyze the effect of different inference steps.
6. Compare different guidance scale values.
7. Experiment with different sampling methods.
8. Display and save the generated images.

## 🔬 Experiments Performed

### 1. Effect of Inference Steps

Tested different inference steps:

* 10 steps
* 20 steps
* 30 steps
* 50 steps

**Observation:** Increasing inference steps can improve image refinement but also increases generation time.

### 2. Effect of Guidance Scale

Tested different guidance scale values:

* 3.0
* 5.0
* 7.5
* 10.0
* 12.0

**Observation:** A lower guidance scale allows more creative freedom, whereas a higher value makes the generated image follow the text prompt more closely. Very high values may introduce visual artifacts.

### 3. Comparison of Sampling Methods

The following schedulers were compared:

* DDIM Scheduler
* Euler Scheduler
* DPM-Solver Scheduler

**Observation:** Different schedulers use different denoising strategies and can affect image quality, visual appearance, and generation speed.

## 📊 Results

* Successfully loaded a pretrained Stable Diffusion model.
* Generated images using text prompts.
* Compared image generation with different inference steps.
* Analyzed the impact of guidance scale.
* Compared three different sampling methods.
* Saved generated images for further analysis.

## 🎯 Conclusion

In this practical, a pretrained Stable Diffusion model was successfully implemented using the Hugging Face Diffusers library. The experiments demonstrated how inference steps, guidance scale, and sampling methods influence image generation quality and speed. Different parameter settings produce different results, and selecting suitable parameters helps achieve better image generation.

## ▶️ How to Run

1. Download the `.ipynb` notebook.
2. Open Google Colab.
3. Upload the notebook.
4. Select GPU runtime (T4 GPU recommended).
5. Execute all cells sequentially.
6. View and download the generated images.

## 📁 Project Structure

```text
Practical-05-Stable-Diffusion/
│
├── Practical_05_Stable_Diffusion_Image_Generation.ipynb
├── README.md
└── stable_diffusion_outputs/
    ├── first_generated_image.png
    ├── steps_10.png
    ├── steps_20.png
    ├── steps_30.png
    ├── steps_50.png
    └── scheduler_outputs/
```

## 👩‍💻 Author

**Tanvi**
B.Tech – Computer Science and Engineering (AI & ML)

---

**Practical No.:** 05
**Subject:** Generative AI / Image Generation

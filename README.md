# 🖼️ Text-to-Image Generation with Stable Diffusion XL

This project demonstrates **text-to-image generation** using **Stable Diffusion XL (SDXL)** with an interactive **Gradio GUI**.
Users can enter a **prompt** (things to generate) and an optional **negative prompt** (things to avoid), and the model will generate a high-quality image.

---

## 🚀 Features

* **Stable Diffusion XL** pre-trained model (`stabilityai/stable-diffusion-xl-base-1.0`)
* **Gradio interface** for user-friendly input/output
* **Prompt + Negative Prompt** support
* Runs on **Google Colab GPU** (or locally with CUDA)
* Generates realistic, high-quality images from text

---

## 🛠️ Tech Stack

* **Python 3**
* **[Hugging Face Diffusers](https://huggingface.co/docs/diffusers/index)**
* **Transformers**
* **Gradio**
* **PyTorch**
* **Matplotlib** (optional visualization)

---

## 📂 Project Structure

```
├── text_to_image_generation.py    # Main code with pipeline + Gradio GUI
├── README.md                      # Project documentation
```

---

## ⚙️ Installation & Setup

Clone this repository:

```bash
git clone https://github.com/your-username/text-to-image-generation.git
cd text-to-image-generation
```

Install dependencies:

```bash
pip install diffusers transformers accelerate safetensors gradio torch matplotlib invisible_watermark
```

---

## ▶️ Usage

Run the script:

```bash
python text_to_image_generation.py
```

This will launch a **Gradio app** with a web interface.

1. Enter a **Prompt** (e.g., `"A vibrant sunset over the city skyline with silhouetted buildings"`)
2. (Optional) Enter a **Negative Prompt** (e.g., `"blurry, text, watermarks"`)
3. Click **Submit** and view the generated image.

---

## 💻 Example

**Prompt:**

```
A vibrant sunset over the city skyline with silhouetted buildings
```

**Negative Prompt:**

```
Avoid including any water elements in the scene
```

**Output:**
An AI-generated image matching the description 🎨

---

## 📌 Future Improvements

* Add support for **multiple images per prompt**
* Allow users to adjust **inference steps** and **guidance scale** from the GUI
* Option to **download generated images** directly from the interface

---

## 🙌 Acknowledgements

* [Stable Diffusion XL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
* [Hugging Face Diffusers](https://huggingface.co/docs/diffusers/index)
* [Gradio](https://www.gradio.app/)

---



# 🌟 Harnessing Foundational Models for Enhanced Image Creation and Search Using Amazon Bedrock 🌟

## 📖 Introduction
Welcome to the [Amazon Bedrock Image Generator](https://docs.aws.amazon.com/bedrock/latest/userguide/titan-image-models.html) getting started tutorial with Python! 🐍 This repository contains a Python Jupyter notebook 📓 designed to showcase and facilitate the use of the Amazon Bedrock Large Language Model (LLM) for advanced image generation tasks, including text-to-image generation, inpainting, and outpainting.

![](/img/img5.png)

## 🚀 Getting Started

### Prerequisites
Before you can run the Jupyter notebook in this repository, ensure you have the following prerequisites installed:
- Python 3.8 or higher 🐍
- Jupyter notebook or JupyterLab 📓
- Necessary Python libraries as specified in `requirements.txt` 📄

### Installation
1. Clone this repository to your local machine using `git clone` 🖥️.
2. Navigate to the cloned directory 📂.
3. Install the required Python libraries using `pip install -r requirements.txt` 🛠️.

### Running the Notebook
To start using the notebook:
1. Launch JupyterLab or Jupyter notebook by running `jupyter lab` or `jupyter notebook` in your terminal. Alternatively, you can use Amazon SageMaker Studio or Amazon SaheMaker Notebook 🚀.
2. Open the `ImageGenerationBedrock.ipynb` notebook 📖.
3. Follow the instructions within the notebook to perform text-to-image generation, inpainting, and outpainting 🖌️.

## 🛠️ Usage
The notebook is divided into sections, each demonstrating a different capability of the Amazon Bedrock Image Generator LLM:

- **Text-to-Image Generation**: Learn how to create images from textual descriptions ✏️🖼️. Here the model accepts a text prompt as input and generates a new image as output. The generated image captures the concepts described by the text prompt.
- **Inpainting**: Discover how to edit images by filling in missing parts with contextually appropriate content 🧩. You can modify an image by changing the inside of a mask to match the surrounding background.
- **Outpainting**: Extend the borders of an image and have the LLM predict and generate the extended areas 🌌. It uses an image and a segmentation mask as input (from either the user or estimated by the model) and generates new pixels that seamlessly extend the region.

Each section contains code cells that you can run to execute the image generation tasks. You can also modify the text prompts and parameters to experiment with different outputs 🔀.

## 🤝 Support and Contributions
For support, please open an issue in this repository, and we will address it as soon as possible 🆘.

If you would like to contribute to this project, please fork the repository and submit a pull request with your proposed changes 🤲.

## 📜 License
This project is licensed under the MIT License - see the `LICENSE` file for details 📄.

# ArchiVision-AI

## Project Overview

ArchiVision-AI is an advanced AI-powered platform that reimagines architectural and interior design workflows. It integrates deep learning, computer vision, and generative models to assist designers, architects, and investors in planning, visualizing, and evaluating real estate and interior projects.

The project covers full-cycle automation: from collecting contextual location data to generating customized 3D interiors with budget-aware recommendations and future-ready design tools, including VR/AR and AI-based assistants.

## Key Features

- Automated Location Data Collection  
  Integration with OpenStreetMap and Google Maps to fetch geospatial, environmental, and zoning data for accurate site analysis.

- Image Classification for Interior Design  
  Custom datasets of interior styles and room types used to train models for design classification and moodboard generation.

- Generative AI for Visual Concepts  
  Use of Stable Diffusion (or similar) for generating tailored interior renders based on client preferences, prompts, and constraints.

- AI Cost Estimation & Budget Flexibility  
  Dynamic AI modules that estimate renovation or construction costs based on region, style, and size — adaptable to different budget levels.

- VR/AR Walkthroughs  
  Exportable scenes and models for immersive virtual experiences to evaluate spatial arrangements and materials.

- AI Design Assistant  
  An interactive AI chatbot that assists with style decisions, prompt generation, spatial tips, and code-based automation of design tasks.

- Investment-Focused Module  
  Suitable for pitching projects to investors by generating visual, financial, and spatial documentation with minimal input.

## Installation
# 1. Clone the repository
git clone https://github.com/VladislavaFr/archivision-ai.git
cd archivision-ai

# 2. Create and activate a virtual environment
python -m venv venv
# On Unix/macOS:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

## Usage

- Data Collection  
  Run src/data_collector.py to automatically collect and structure spatial and contextual data.

- Dataset Preparation  
  Use folder structure data/{style}/{room_type} to store images. Parser available for automated collection.

- Model Training  
  Train classifiers or generative models using prepared datasets. Launch training from src/train.py.

- Prompt Engineering Tools  
  Access Jupyter notebooks in notebooks/ to test prompt generation for generative models.

- Visualization & Export  
  Generated interiors are stored in output/ and can be converted into VR-ready formats.

## Project Structure
archivision-ai/
├── data/                # Image datasets (excluded from repo)
│   ├── contemporary/
│   ├── wabi-sabi/
│   └── etc.
├── src/                 # Python source code
│   ├── data_collector.py
│   ├── train.py
│   ├── generator.py
│   └── prompts.py
├── notebooks/           # Jupyter notebooks
├── tests/               # Unit and integration tests
├── output/              # Generated images and models
├── .gitignore
├── README.md
├── requirements.txt
└── LICENSE

## Collaboration

This project is developed by Vladislava Fridmann in collaboration with OpenAI tools and models. It’s an open research and development initiative focused on real-world architecture and AI integration.

We welcome contributions in data science, architecture, generative AI, or UI/UX development.

## Future Development

- Expand API support for location analytics (e.g., zoning, terrain).
- Integration with 3D modeling tools (Blender, Unreal Engine).
- Cloud deployment of the AI assistant for real-time consulting.
- GAN-based upscaling and material prediction.
- Style transfer between real and generated interiors.

## Legal & Licensing

All code in this repository is published under the MIT License. Image datasets used for training are collected for educational and research purposes and are not distributed with the repository.
If you use your own datasets, ensure compliance with data rights and licensing.

## Contact

If you have questions, ideas, or want to collaborate — feel free to [open an issue](https://github.com/VladislavaFr/archivision-ai/issues) or submit a pull request.

---

Developed by Vladislava Fridmann using OpenAI technologies

# ArchiVision.AI: AI-Powered Interior Design & Architecture Analysis

ArchiVision.AI is a cutting-edge Python project that combines architecture, interior design, deep learning, and prompt engineering. Designed in collaboration with AI Open, this project aims to revolutionize how we approach residential and investment-based design, especially for budget-conscious users.

##  Overview

This project uses real-time AI techniques to:
- Analyze architectural plans and optimize interior layouts
- Generate photorealistic interior visualizations using AI
- Match designs to user budgets, needs, and regional styles
- Predict material costs and renovation expenses
- Suggest design decisions based on natural light analysis, cultural aesthetics, and user preferences
- Create presentation-ready investment concepts

## Features

-  Deep Learning: Predicts layout efficiency, lighting performance, and renovation costs.
-  Interior AI Visuals: Generate stunning photorealistic renderings using prompt-engineered AI models.
-  Data-Driven Budgets: Calculates real-world renovation costs and visualizes allocation by room/zone.
-  Cultural Adaptation: Supports user input for religion, region, or specific investor taste (e.g., Arabic motifs, Eastern European minimalism, etc.)
-  Investment Scenarios: Automatically assembles a PDF or pitch deck for investors based on selected variables.

## Technologies

- Python 3.11+
- Pandas, NumPy
- Scikit-learn, TensorFlow (or PyTorch)
- Matplotlib, Seaborn, Plotly
- OpenAI API / Midjourney / Stable Diffusion (via integration)
- Custom prompt-engineering framework
- Streamlit / Gradio (for UI prototype)

## Installation

1. Clone the repo:
git clone https://github.com/yourusername/archivision-ai.git
cd archivision-ai

2. Install dependencies with Poetry:
poetry install
poetry run python src/main.py

## Usage

- Use CLI or Streamlit UI to input:
  - Layout plan
  - Desired style keywords
  - Region & religion
  - Budget
- Let the AI generate:
  - Layout optimization
  - Moodboards and rendered rooms
  - Budget estimates by room
  - Investor-ready visuals and reports

## Project Structure
archivision-ai/

 src/
    data.py          # Data loading & preprocessing
    model.py         # Deep learning model
    visualizer.py    # Budget and layout visuals
    prompts.py       # Prompt generator for AI renderings
    main.py          # Project entry point

 assets/              # Rendered images and visualizations
 reports/             # Investor decks, PDFs
 data/                # Input sample datasets
 README.md
 pyproject.toml

## License

This project is licensed under the MIT License. You're free to use and adapt it.

## Disclaimer

This project was created as a collaboration with AI Open and represents a fusion of architectural expertise and artificial intelligence. It is intended for research, design experimentation, and future-forward investor planning. All AI-generated visuals are for concept purposes only.

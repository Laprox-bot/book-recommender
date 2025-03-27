# Book Recommender

This project is a book recommendation application based on sentiment analysis and vector search. It uses **Gradio** as the interface and requires access to external APIs.

##  Project Structure
- `gradio-dashboard.py`: Main interface to launch the project.
- `sentiment-analysis.ipynb`: Sentiment analysis on book descriptions.
- `text-classification.ipynb`: Classification of books into categories.
- `vector-search.ipynb`: Vector search for recommendations.

## Installation & Usage

1. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
2. **Create a `.env` file** with the following variables:
   ```
   HUGGINGFACE_API_TOKEN=your_huggingface_token
   GOOGLE_API_KEY=your_google_api_key
   ```
3. **Run the Gradio application**:
   ```sh
   python gradio-dashboard.py
   ```

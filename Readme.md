## Next Word Prediction Using LSTM
    
    This project is a Deep Learning application that predicts the next word in a sequence using a Long Short-Term Memory (LSTM) network trained on Shakespeare's Hamlet.

🚀 Features
    Model: LSTM (Long Short-Term Memory) / GRU.

    Dataset: NLTK Gutenberg Corpus (Hamlet).

    Deployment: Interactive web interface built with Streamlit.

    Text Preprocessing: Tokenization, Padding, and N-gram sequence generation.

🛠️ Tech Stack
    Language: Python

    Libraries: TensorFlow/Keras, NumPy, Pandas, Scikit-learn, Streamlit.

    Environment: VS Code / Jupyter Notebook.

📂 Project Structure
    experiemnts.ipynb: Data cleaning and model training.

    app.py: Streamlit application script.

    next_word_lstm.h5: Trained model file.

    tokenizer.pickle: Saved tokenizer for text processing.

🏃 How to Run
    Install dependencies:
        pip install -r requirements.txt
    
    Run the Streamlit app:
        streamlit run app.py

📊 Results
    The model was trained for 50 epochs and achieved an accuracy of approximately 43%, effectively capturing the semantic style of Shakespearean English.
# Next Word Prediction App

A simple Streamlit app that uses an LSTM model to predict the next word for a typed sentence.

## What is included

- `app.py` for the Streamlit interface and prediction flow
- `lstm_model (1).h5` for the trained model
- `tokenizer.pkl` for text tokenization
- `max_len.pkl` for the input sequence length

## Run locally

```bash
python -m venv .venv
.venv\Scripts\activate
pip install streamlit tensorflow numpy
streamlit run app.py
```

## Notes

- The app expects all model files to stay in the project root.
- Use `streamlit run app.py` instead of `python app.py`.
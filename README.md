# LSTM_WordPredictor
LSTM-WordPredictor is a deep learning model for next-word prediction using Long Short-Term Memory (LSTM) networks. Trained on text sequences, this NLP model learns to predict the most probable next word given an input phrase

---

##  Features  
✅ **LSTM-based neural network** for sequence modeling  
✅ **Text tokenization & embedding** for language processing  
✅ **N-gram sequence generation** for contextual predictions  
✅ **Dropout & EarlyStopping** to prevent overfitting  
✅ **GRU variant** for performance comparison  

---

##  Technologies Used  
- **Python**  
- **TensorFlow/Keras** for deep learning  
- **Natural Language Processing (NLP)**  
- **Scikit-learn** for dataset handling  
- **NumPy & Pandas** for data processing  

---

##  Installation & Setup  

```sh
git clone https://github.com/SanjanaDuraiswamy/LSTM-WordPredictor.git
cd LSTM-WordPredictor

Create a virtual environment and activate it:

```sh
python -m venv env
# For Windows
env\Scripts\activate
# For Mac/Linux
source env/bin/activate
```

Install the required dependencies:

```sh
pip install -r requirements.txt
```
## Training the Model

Run the Jupyter Notebook:

```sh
jupyter notebook
```

Open `hyperparametertuningann.ipynb` to train and tune the LSTM & GRU model.

## Running the Streamlit App

After training, you can test the model using Streamlit:

```sh
streamlit run app.py
```

This will launch an interactive web UI where you can input the sequence of words and predict the next word

## Model Deployment

The model can be deployed using:

- **Streamlit Cloud**
- **Heroku / AWS / GCP (Future Scope)**

## Usage

- Modify `app.py` to enhance UI/UX.
- Update `requirements.txt` if adding new libraries.
- Train with different architectures for better accuracy.

## Contributing

Feel free to fork the repo and submit PRs for improvements!

## License

This project is licensed under the MIT License.

---

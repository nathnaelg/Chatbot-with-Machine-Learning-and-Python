# 🤖 Chatbot with Machine Learning and Python

A simple AI chatbot built using Python, Natural Language Processing (NLP), and Machine Learning techniques. This project demonstrates how to train a basic intent-based chatbot using a custom dataset.

---

## 🧠 Features

- Trainable on custom intents (using `intents.json`)
- Tokenization and label encoding using Keras and sklearn
- Saves model and tokenizer artifacts for reuse
- Interactive Jupyter Notebook for experimentation
- Easily extendable with more intents and responses

---

## 🗂️ Project Structure
```

├── chat\_model/               # Trained model files
├── Chat-Bot.ipynb            # Main notebook to train and test chatbot
├── intents.json              # Dataset of intents and responses
├── label\_encoder.pickle      # Serialized label encoder
├── tokenizer.pickle          # Serialized tokenizer
├── README.md                 # Project documentation
├── LICENSE                   # License file
└── .gitignore                # Files to ignore in git


## 🛠️ Setup and Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Chatbot-with-Machine-Learning-and-Python.git
   cd Chatbot-with-Machine-Learning-and-Python
````

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebook**
   Open `Chat-Bot.ipynb` in Jupyter Notebook or Jupyter Lab and run all cells to train the model and interact with the chatbot.

---

## 🧾 Dataset (intents.json)

The `intents.json` file contains a list of intents with associated patterns (user inputs) and responses. You can add new intents or modify existing ones to customize your chatbot.

Example:

```json
{
  "intents": [
    {
      "tag": "greeting",
      "patterns": ["Hi", "Hello", "Is anyone there?", "Good day"],
      "responses": ["Hello!", "Hi there!", "Greetings!"]
    }
  ]
}
```

---

## 🧪 Model Artifacts

* `label_encoder.pickle`: Encodes text labels into numeric classes.
* `tokenizer.pickle`: Converts words into token IDs.
* `chat_model/`: Contains the trained Keras model for inference.

---

## 🧰 Technologies Used

* Python
* TensorFlow / Keras
* scikit-learn
* NumPy
* NLTK / re (text preprocessing)
* Jupyter Notebook

---

## 🚀 Future Improvements

* Add a GUI interface using Tkinter or Streamlit
* Use a Transformer-based model for more natural conversations
* Add context-awareness and memory to handle conversations
* Deploy via Flask or FastAPI

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🙋‍♂️ Author

Developed by [@nathnaelg](https://github.com/nathnaelg)

---

## 🌟 Star This Repo

If you found this project helpful, please consider starring ⭐ the repository to show your support!


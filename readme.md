# 🤖 AI Chatbot Using Machine Learning

This is a simple AI-powered chatbot built using Python, TensorFlow, and NLTK. It uses a neural network to classify user inputs based on intents and respond appropriately.

---

## 📁 Project Structure

```pgsql
chatbot-ml/
│
├── intents.json           ✅ Intent dataset
├── train_chatbot.py       ✅ Training script
├── chatbot.py             ✅ Chat interface
├── words.pkl              ⬅️ Will be created after training
├── classes.pkl            ⬅️ Will be created after training
├── chatbot_model.h5       ⬅️ Will be created after training

```


# Install required libraries:
```bash
pip install tensorflow nltk numpy
```

## Optional: Clean Environment Setup with venv
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install tensorflow nltk numpy
```

# Download necessary NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```
#  Train the Model

Create a Python script train_chatbot.py and paste the training code from train_chatbot.py provided earlier.

Then run:

```bash
python train_chatbot.py
```

This will:
- Process your data
- Train a neural network
- Save the model as chatbot_model.h5
- Save the vocabulary and classes as words.pkl and classes.pkl

# Chat with the Bot
Create a new script chatbot.py and paste the chatbot interface code.
Then run:
```bash
python chatbot.py
```
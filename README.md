

1. **Model and Tokenizer Initialization:**
   - Necessary libraries are imported, including Torch and Transformers.
   - A pre-trained GPT-2 model along with its associated tokenizer is initialized.

2. **Data Preparation:**
   - A dataset of jokes is loaded from a CSV file, utilizing a custom dataset class.
   - The data is preprocessed to prepare it for model training.

3. **Model Training:**
   - The GPT-2 model is trained on the jokes data, with jokes fed into the model in batches.
   - Loss is calculated at each iteration to adjust the model weights.

4. **Generation of New Jokes:**
   - Once the model is trained, it is utilized to generate new jokes.
   - The generation process iteratively selects the next tokens to complete a joke until a termination condition is met.

5. **Model and Results Saving:**
   - The trained model is saved after each epoch.
   - The generated jokes are saved in an output file.

In summary, the code implements a complete process, from data preparation to training a GPT-2 model on a set of jokes, followed by the generation of new jokes using the trained model.



## 1. RNN Model:

### Functionality:

- Scrapes text data from Arabic websites.
- Preprocesses the text data by tokenization and removing stopwords.
- Converts text data into numerical representation.
- Defines an RNN model class using PyTorch.
- Defines a custom dataset class for Arabic text data.
- Trains the RNN model on the Arabic text data.
- Evaluates the trained model.

### Key Components:

- **RNNModel:** Defines a simple RNN model with one hidden layer.
- **ArabicTextDataset:** Custom dataset class to load Arabic text data.
- **Model Training Loop:** Iterates over the training data, computes loss, and updates model parameters.

### Evaluation:

- The RNN model is trained and evaluated on Arabic text data for a regression task.

## 2. Bidirectional GRU Model:

### Functionality:

- Similar to the RNN model, but it uses bidirectional GRU layers instead.
- Scrapes, preprocesses, and prepares Arabic text data.
- Defines a Bidirectional GRU model class.
- Trains and evaluates the model on the Arabic text data.

### Key Components:

- **BiGRUModel:** Defines a Bidirectional GRU model using PyTorch.

### Evaluation:

- The Bidirectional GRU model is trained and evaluated on Arabic text data for regression.

## 3. Bidirectional LSTM Model:

### Functionality:

- Similar to the previous models, but it uses bidirectional LSTM layers instead.
- Scrapes, preprocesses, and prepares Arabic text data.
- Defines a Bidirectional LSTM model class.
- Trains and evaluates the model on the Arabic text data.

### Key Components:

- **BiLSTMModel:** Defines a Bidirectional LSTM model using PyTorch.

### Evaluation:

- The Bidirectional LSTM model is trained and evaluated on Arabic text data for regression.

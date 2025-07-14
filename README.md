# Spam-Classification-Deep-Learning
- **Objective:** Developed a spam classification model using deep learning techniques on a dataset of 1500 messages labeled as "spam" or "ham".
- **Preprocessing:**
    - Used NLTK for:
        - Removing stopwords.
        - Tokenizing text.
        - Lemmatizing words using WordNet.
    - Applied TF-IDF vectorization to convert text into feature vectors.
- **Model Architecture:**
    - Built a Sequential Neural Network using TensorFlow & Keras.
    - Architecture included:
        - 2 hidden layers (32 neurons each, ReLU activation).
        - 1 output layer (2 neurons, Softmax activation).
    - Used categorical crossentropy as the loss function.
- **Training & Evaluation:**
    - Trained with:
        - Batch size: 256
        - Epochs: 10
        - Validation split: 20%
    - Achieved consistent improvement in accuracy across epochs.
    - Final test accuracy reached 94.31%, indicating strong model performance.
- **Visualization:** Accuracy plotted across epochs to observe training progress.
- **Outcome:** Demonstrated a robust, well-generalized spam classifier and reinforced key deep learning and NLP principles in practice.


Please read the blog for a detailed explanation: https://www.notion.so/Deep-Learning-Project-Spam-Classification-21e997fee92d80fdb02bddb569697083

# 🚀 Project Title: Fine-tuning BERT on Amazon Reviews Classification 📚

## 🌟 Overview
This project is on a mission to fine-tune a BERT (Bidirectional Encoder Representations from Transformers) model using a dataset of Amazon reviews 📝. Our quest? To predict the sentiment of reviews with a five-class classification approach! 🌈

## 📊 Dataset
The dataset is our treasure trove, containing a 'Text' column and a magical one-hot encoded sentiment column called 'One'! 🧙‍♂️ The sentiment column flaunts five classes, elegantly represented as binary vectors. 🎩✨

## ⚙️ Configuration
### 🔑 Key Variables
- **MAX_LEN:** Maximum length of the input text.
- **TRAIN_BATCH_SIZE:** Batch size for training.
- **VALID_BATCH_SIZE:** Batch size for validation.
- **EPOCHS:** Number of training epochs.
- **LEARNING_RATE:** Learning rate for the optimizer.

## ✨ Text Preprocessing
The journey begins with enchanting text preprocessing, a magical ritual that involves lowercase conversion, handling contractions, removing special characters, isolating punctuations, removing stop words, and more! 🧹🔮

## 📚 Custom Dataset
Behold the creation of the mighty `CustomDataset` class! 🦸‍♂️ This hero processes the data and crafts PyTorch datasets, ready to embark on epic adventures. ⚔️

## 🏰 Model Architecture
The BERT model undergoes customization, featuring a brave dropout layer and a wise dense layer, all in pursuit of the final output! 🏹🛡️

## 🚂 Training
Join us on the training expedition! The Adam optimizer steers us through epochs, forging a path to greatness. 🚀

## 🌟 Validation
After the battles of training, it's time to validate and assess our model's prowess on the test dataset! 🎉

## 📈 Model Evaluation
Behold the metrics! Accuracy, F1 score (micro and macro) stand as the pillars of evaluation, showcasing our model's strength. 📊🌐

## 🧙‍♀️ Inference
Witness the magic as we perform inference on a sample text, showcasing the power of the trained model! ✨🔍

## 🏆 Model Saving
Our hero, the trained model, is saved in two forms - the complete model and the model's state dictionary. For posterity and future endeavors! 🗝️💾

Now embark on this magical journey, and may the emojis guide you! 🌟✨

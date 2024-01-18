# Project Title: Fine-tuning BERT on Amazon Reviews Classification 🌟

## Overview 🚀
Welcome to our project where we're diving into the fascinating world of sentiment analysis using BERT! 📚 Our goal? To fine-tune this powerful model on a collection of Amazon reviews, predicting sentiments across five classes. Let's embark on this exciting journey together! 🌈

## Dataset 📊
Our dataset is a treasure trove of text ('Text') and sentiments ('One') cleverly encoded in binary vectors. It's like a secret language only our model can decipher! 🧑‍💻💬

## Configuration ⚙️
Let's talk settings! Here are the key variables that steer our ship:
- **MAX_LEN:** How long is too long? Maximum length of the input text.
- **TRAIN_BATCH_SIZE:** Our crew size during training.
- **VALID_BATCH_SIZE:** The team for validation.
- **EPOCHS:** The number of training epochs - our journey's chapters.
- **LEARNING_RATE:** The pace at which our model learns - our project's heartbeat.

## Text Preprocessing ✨
Before the magic happens, we prepare the text – making it lowercase, handling contractions, and sprinkling some charm to remove unnecessary elements. Just like preparing a potion! 🧙‍♂️✨

## Custom Dataset 📚
Meet our hero, the `CustomDataset` class! Crafted to process data and create PyTorch datasets, it's the backbone of our adventure. 🦸‍♂️⚔️

## Model Architecture 🏰
Our BERT model is no ordinary knight. It's customized with a touch of flair – a dropout layer and a dense layer – gearing up for the final showdown! 🛡️🤺

## Training 🚂
Join us on the training expedition! With the trusty Adam optimizer, we navigate through epochs, shaping our model into greatness. 🚀

## Validation 🌟
After the battles of training, it's time to validate! We assess our model's prowess on the test dataset – a moment of truth! 🎉

## Model Evaluation 📈
Behold the metrics! Accuracy, F1 scores (micro and macro) – our compass in this vast sea of data. 🗺️

## Inference 🧙‍♀️
The magic unfolds as we perform inference on a sample text, showcasing the power our model wields! ✨🔮

## Model Saving 🏆
Our hero, the trained model, is saved in two forms – the complete model and the model's state dictionary. Ready to be called upon for future quests! 🗝️💾

Embark on this magical journey with us, where the code comes alive! 🌟✨


# sms_spam_detector
Module 21 Challenge

Summary

This project creates a simple SMS spam detector using machine learning. We used a Support Vector Classification (SVC) model to classify text messages as either "spam" or "ham" (not spam). After training the model, we built a user-friendly Gradio interface where users can input a text message and instantly find out if it’s spam.

Key Steps

Model Training: Trained the model using a dataset of SMS messages, converting the text into numerical data with TF-IDF vectorization.
Model Testing: Tested the model to ensure accuracy and reliability in identifying spam.
Gradio Interface: Created an easy-to-use Gradio app where users can type in a message and see the classification result.

How to Use
Clone the Repository: Download the project files to your computer.
Install Dependencies: Use pip to install the required Python packages.

Run the Notebooks:
 - Open sms_text_classification_solution.ipynb and run the cells to train the spam detection model.
 - Open gradio_sms_text_classification.ipynb and run the cells to launch the Gradio interface.

Conclusion
This project provides a quick and easy way to identify spam messages using machine learning, with an interface that anyone can use.

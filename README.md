# Text-Generation

This web application is designed to accept the beginning of a text as input and predict its continuation based on the user-specified number of words to forecast next.

It utilizes a customized LSTM (Long Short-Term Memory) model, which has achieved a ROUGE score of 0.86 and a test accuracy of 90%.

# Features

Input text: Users can enter the beginning of a text in the provided input field.

Word prediction: The application will generate a forecast of the next set of words based on the input.

Customized LSTM model: The model used in this application has been tailored to provide accurate and meaningful predictions.

ROUGE score: The model's performance is evaluated using the ROUGE (Recall-Oriented Understudy for Gisting Evaluation) score, which measures the quality of the generated text in comparison to a reference text.

Test accuracy: The model's accuracy has been assessed using a test dataset, resulting in a score of 90%.

# Getting Started
To run the application locally, follow these steps:

Clone the repository: git clone https://github.com/your-username/repo-name.git

Install the required dependencies: pip install -r requirements.txt

Launch the application: python app.py

Access the application in your web browser at http://localhost:5000

# Usage
Step 1: Enter the beginning of a text in the provided input field.

Step 2: Specify the number of words you want to predict for the continuation.

Step 3: Click the "Forecast" button.

Step 4: The application will display the predicted text based on your input.

Step 5: Model Training

If you are interested in training the LSTM model yourself or improving its performance, you can follow these steps:

1) Prepare your dataset: Collect a suitable dataset for training, ensuring it is formatted properly for the task.
 
2) Customize the LSTM model: Adjust the model architecture, hyperparameters, and training process as needed for your specific use case.
 
3) Train the model: Use the prepared dataset to train the LSTM model. Monitor the performance metrics such as ROUGE score and test accuracy to assess its quality.
 
4) Save the trained model: Once the model has been trained to your satisfaction, save it for later use in the web application.

5) Integrate the model with the web application: Replace the existing model in the application with your customized LSTM model and update any necessary code changes.

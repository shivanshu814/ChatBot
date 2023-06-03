# Flask Chatbot

A simple Flask Chatbot application that utilizes a trained model for natural language processing.

## Features

- Chatbot Interface: Users can interact with the chatbot through a web-based chat interface.
- Natural Language Processing: The chatbot uses a trained model to understand and respond to user input.
- Training Script: The application provides a script (`training.py`) to train the chatbot model using a given dataset.
- Customization: The trained model and data files can be easily updated or replaced to customize the chatbot's behavior.

## Installation

1. Clone the repository: https://github.com/shivanshu814/ChatBot
2. Navigate to the project directory: cd ChatBot 
3. Run: python app.py
4. Install the dependencies: pip freeze > requirements.txt


## Training the Model

1. Ensure you have the necessary data file (`data.json`) and trained model file (`model.h5`) in the project directory.
2. Run the training script (`training.py`) to train the chatbot model:
3. The script will create the necessary training data and train the chatbot model using the data file.
4. The trained model (`model.h5`) and associated data files (`texts.pkl` and `labels.pkl`) will be generated.

## Usage

1. Run the application:
2. Access the chatbot in your browser at `http://localhost:5000`.
3. Interact with the chatbot by entering messages in the chat interface.

## Configuration
The application requires a trained model (`model.h5`), data files (`texts.pkl` and `labels.pkl`), and a data file for intents (`data.json`) for natural language processing. Make sure to place these files in the appropriate location or update the file paths in the code.

## Contributing
Contributions are welcome! If you find any issues or have suggestions, please open an issue or create a pull request.


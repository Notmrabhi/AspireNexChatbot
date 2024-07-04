# AspirenexChatbot Task - 1 Domain AI

## Tech Stack
Tech Stack Used
1. Python: Programming language used for developing the chatbot.
2. PyTorch: Framework for building and training the neural network.
3. Flask: Micro web framework used for deploying the chatbot as a web application.
4. NLTK (Natural Language Toolkit): Library for natural language processing, used for tokenization and preprocessing text data.
5. HTML, CSS and JS - Used for creating the frontend of the web application, providing a user-friendly interface for interacting with the chatbot.

## Technique Used - Pattern matching technique

## Initial Setup for Chatbot Deployment

1. **Clone the Repository and Create a Virtual Environment**
   - Clone the repository and navigate into the project directory.
   - Create and activate a virtual environment.
   
   ```bash
   $ git clone https://github.com/Notmrabhi/AspireNexChatbot.git
   $ python -m venv venv
   $ . venv/bin/activate
   ```

2. **Install Dependencies**
   - Install the necessary dependencies within the virtual environment.
   
   ```bash
   $ (venv) pip install Flask torch torchvision nltk
   ```

3. **Install NLTK Package**
   - Open a Python shell within the virtual environment and download the required NLTK package.
   
   ```bash
   $ (venv) python
   >>> import nltk
   >>> nltk.download('punkt')
   >>> exit()
   ```

4. **Train the Model**
   - Run the training script to generate the `data.pth` file.
   
   ```bash
   $ (venv) python train.py
   ```

5. **Test the Chatbot**
   - Run the following command to test the chatbot in the console.
   
   ```bash
   $ (venv) python chat.py
   ```

6. **Run the Flask Application**
   - To run the Flask web application, execute the following command.
   
   ```bash
   $ (venv) python app.py
   ```

7. **For the Demo of the project, watch the video tutorial linked below:**

# Chat with any LLM

## Introduction
This notebook provides a simplified interface to interactively chat with any Language Model (LLM) available on Hugging Face's Chatbot Arena Leaderboard. By leveraging the Hugging Face API and Gradio, users can easily converse with state-of-the-art models without diving deep into the underlying complexities.

## Requirements
To successfully run and interact with the models using this notebook, ensure the following:

1. **Python Environment:** A Python 3.x environment is recommended.
2. **Python Libraries:** Ensure you have the following libraries installed:
   - `os`
   - `io`
   - `dotenv`
   - `requests`
   - `json`
   - `transformers`
   - `gradio`
You can install them locally:
`pip install os io dotenv requests json transformers gradio`
Or putting them as a requirements.txt in the HugginFace interface.

3. **Hugging Face API Key:** You need a Hugging Face API key to interact with the models. This can be obtained by signing up on the Hugging Face website. Store your API key in an environment variable or a .env file.
4. **Internet Connection:** Ensure a stable internet connection for seamless interaction with the Hugging Face API.

## How to Use
1. **Environment Setup:** After installing the necessary libraries and setting up your Hugging Face API key, you can run the notebook.
2. **Interacting with the Model:** With the Gradio interface launched, you can:
   - Choose the desired LLM from the dropdown list.
   - Enter your message or query in the provided text box.
   - Click "Submit" or the equivalent action button to send the message to the LLM.
   - View the model's response in the output area.

## Contributing
Contributions to improve the notebook or expand its capabilities are always welcome. Whether it's improving the user interface, adding new features, or enhancing the overall user experience, your efforts are appreciated. Please refer to the "Contributing" section in the main repository documentation for guidelines on how to contribute.

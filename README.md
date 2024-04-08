
# Streamlit GPT-3.5 Chatbot 

This is a chatbot app built using Streamlit and OpenAI API. The app allows users to interact with a chatbot powered by OpenAI's language model


## Deployment

This app has been deployed on Streamlit IO cloud. You can access the live version [here](https://chatgpt-app-zr6undfgp9sbwdjjqz3etg.streamlit.app/)


##  Usage
To run the app locally, follow these steps:

* Clone the repository
* Install the neccessary libraries using
```bash
  pip install -r requirements.txt
```
* Create .streamlit directory
* In the .streamlit directory create a secrets.toml file

* Add your api token in the secrets.toml file
 ```bash
OPENAI_API_KEY = "xxx"
```
* Run the app using
```bash
  streamlit run main.py
```
* Access the app in your browser at  
```bash
  localhost:8501
```
##Acknowledgements
I would like to acknowledge Chanin Nantasenamat from dataprofessor, majority of the code in this project is adapted from his GitHub repository  [link](https://github.com/dataprofessor/openai-chatbot.git)

# End-to-end-Medical-Chatbot-using-Llama2

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mchatbot python=3.8 -y
```

```bash
conda activate mchatbot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


### Download the quantize model from the link provided in model folder & keep the model in the model directory:

```ini
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```

```bash
# run the following command
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- Meta Llama2
- Pinecone
  
###  Frontend
![Screenshot (1621)](https://github.com/ApurvBhusari/End_to_End_Medical_chatbot_generative_ai/assets/80256026/9296ecf2-d232-48af-906e-5a9f26296ae4)

###  VS Code
![Screenshot (1622)](https://github.com/ApurvBhusari/End_to_End_Medical_chatbot_generative_ai/assets/80256026/4dffba05-fbf0-4e3c-a665-36bc91e93791)

### Response
![Screenshot (1623)](https://github.com/ApurvBhusari/End_to_End_Medical_chatbot_generative_ai/assets/80256026/8bdef5ff-07a8-4f63-ae79-ac3c9c7c284e)




# Llama2-on-CPU-Machine
Steps 1:
clone the repository

```bash
git clone https://github.com/
```
Steps 2:
Create Virtual Environment
```bash
Create a virtual environment
```

conda create -n cpullama python=3.8 -y
conda activate cpullama
pip install -r requirements.txt
python app.py

Step 3:
Download the quantize model from the link provided in model folder & keep the model in the model directory:
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
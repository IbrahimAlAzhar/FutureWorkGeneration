# FutureWorkGeneration
This project generated Future Work using scientific articles text


![Alt text for the image](https://github.com/IbrahimAlAzhar/FutureWorkGeneration/blob/main/assets/Archi.png)

### Create a virtual environment: (Step 1): 
mkdir my_project 

cd my_project

### Activate the virtual environment (Step 2): 
env\Scripts\activate (windows)

source env/bin/activate

### install related libraries (Step 3):
pip install -r requirements.txt

## Code and Datasets

```plaintext

code/
│
├── Data Preprocessing/                
│   ├── 1.(FutureGen)_Data_Preprocessing.ipynb   #  regarding Data Preprocessing
|   ├── 2.(FutureGen)_GPT_based_ground_truth.ipynb   #  regarding refining ground truth using gpt 3
|   ├── 3.(FutureGen)_BART.ipynb   # using BART for future work generation
|   ├── 4.(FutureGen)_T5.ipynb   # using T5 for future work generation
|   ├── 5.(FutureGen)_GPT_3_(all_sections).ipynb   # using all sections of papers with gpt 3 to generate future work
|   ├── 6.(FutureGen)_GPT_3_(top_3_sections).ipynb  # using top 3 sections of papers with gpt 3 to generate future work
|   ├── 8.(FutureGen)_Evaluations.ipynb # quantitiave evalutions and judgy by LLM
|   ├── 7.(FutureGen)_GPT_4o_mini+RAG.ipynb  # using gpt 4o mini with RAG for future work generation
|   ├── 10.(FutureGen)_Llama_fine_tuned.ipynb   # fine tuned llama to generate future work

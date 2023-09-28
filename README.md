<h1 align="center">CipherChat 🔐</h1>
A novel framework CipherChat to systematically examine the generalizability of safety alignment to non-natural languages – ciphers.
<br>   <br>



## 🛠️ Usage
✨An example run:
```
python3 main.py \
 --model_name gpt-4-0613 \
--data_path data/data_en_zh.dict \
--encode_method caesar \
--instruction_type Crimes_And_Illegal_Activities \
--demonstration_toxicity toxic \
--language en
```
## 🔧 Argument Specification
1. `--model_name`: The name of the model to evaluate.

2. `--data_path`: Select the data to run. 

3. `--encode_method`: Select the cipher to use.

4. `--instruction_type`: Select the domain of data.

5. `--demonstration_toxicity`: Select the toxic or safe demonstrations.

6. `--language`: Select the language of the data.



## 📃Results
The query-responses pairs in our experiments are all stored in the form of a .list and .txt in the "experimental_results" folder, and torch.load() can be used to load data (*.list).



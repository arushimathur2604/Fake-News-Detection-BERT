# 🧠 Fake News Detection Using BERT

## 📌 Overview
This project uses **BERT (Bidirectional Encoder Representations from Transformers)** — a state-of-the-art deep learning model developed by Google — to detect whether a given news headline or article is **real or fake**.  
BERT understands the **context and meaning** of words in both directions, making it ideal for text classification tasks like fake news detection.

---

## 🚀 How to Run the Project

### 🧭 Step 1: Open the Folder in VS Code
1. Extract the ZIP file.  
2. Open **VS Code → File → Open Folder… →** select the extracted `Fake-News-Detection-Using-BERT-main` folder.  
3. Open a new terminal (`Ctrl + \``).

---

## ⚙️ Step 2: Create a Python Virtual Environment

```bash
python -m venv bert_env


bert_env\Scripts\activate

You should see (bert_env) appear at the start of the terminal prompt.

---

```markdown
## 📦 Step 3: Install Dependencies

If a `requirements.txt` file is available, run:
```bash
pip install -r requirements.txt

If not available:
pip install torch torchvision torchaudio transformers pandas numpy scikit-learn flask tqdm


---

```markdown
## 🧠 Step 4: Check the Project Structure

├── app.py / main.py ← entry file
├── model/ ← BERT model / weights
├── data/ ← dataset
├── requirements.txt
├── utils.py

## ▶️ Step 5: Run the Application

**Flask Web App:**
```bash
python app.py

Visit → http://127.0.0.1:5000

Jupyter Notebook:
pip install notebook
jupyter notebook

Open the .ipynb file and run each cell.

Training or Testing Script:
python train.py
python predict.py


---

```markdown
## 💡 Step 6: (Optional) Use GPU

```python
import torch
print(torch.cuda.is_available())

If it prints True, BERT will run faster using GPU.

---

```markdown
## 🧾 Step 7: Deactivate Environment

```bash
deactivate


---

```markdown
## ❤️ Acknowledgment

Built using **BERT**, one of the most powerful NLP models, to fight misinformation through the power of AI.

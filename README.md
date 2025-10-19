# Trained model

Model size exceeds GitHub limit.  
This is its access link on Google Drive:  
[🔗 Google Drive Folder](https://drive.google.com/drive/folders/1eMeHFjh-5YGrf3VU2rG6nJS4vwuhlEkY?usp=sharing)

---

## 🧠 How to Load the Model

```python
from transformers import AutoTokenizer, AutoModelForSeq2SeqLM

# Load your fine-tuned model from a local folder after downloading
model = AutoModelForSeq2SeqLM.from_pretrained("./nllb_translation_model")
tokenizer = AutoTokenizer.from_pretrained("./nllb_translation_model")

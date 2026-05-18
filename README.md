# SafeCare AI

## Gemma 4-powered healthcare risk screening for rural women in India

SafeCare AI is a multilingual healthcare assistance system fine-tuned using Gemma 4, LoRA, and quantized inference.

The system analyzes symptom descriptions in Hindi, detects severity levels, identifies abuse-related risk indicators, and generates structured healthcare guidance in JSON format.

---

# Features

* Gemma 4 fine-tuning
* LoRA + 4-bit quantization
* Hindi healthcare instruction tuning
* Structured JSON generation
* Abuse-risk signal detection
* Lightweight Gradio deployment

---

# Technical Stack

* Gemma 4
* Unsloth
* Transformers
* PEFT / LoRA
* Gradio
* Kaggle GPU

---

# Example Input

Mere chest mein ganthi hai lekin pati doctor ke paas nahi jaane deta

---

# Example Output

```json
{
  "severity": "high",
  "abuse_risk_flags": ["partner control"],
  "action_steps": [
    "Turant sarkari aspatal jayein",
    "Mahila Helpline 181 par call karein"
  ]
}
```

---

# Demo Video

Add your YouTube link here.

---

# Live Demo

Add your Gradio demo link here.

---

# Kaggle Notebook

Add your Kaggle notebook link here.

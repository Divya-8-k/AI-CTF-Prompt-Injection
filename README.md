# CTF Prompt Injection

## 📌 Project Overview

This project contains a Google Colab-based solution for a **Capture The Flag (CTF) Prompt Injection Challenge**.

The project focuses on working with encoded challenge prompts, decoding the provided levels, and analyzing them using Python and AI/LLM-based techniques.

## 🎯 Objectives

* Decode the encoded challenge prompts.
* Process multiple CTF levels.
* Work with Base64-encoded data.
* Use Python for decoding and verification.
* Experiment with Hugging Face models for prompt analysis.
* Identify and analyze prompt-injection techniques.
* Generate the final decoded outputs for the challenge levels.

## 🛠️ Technologies Used

* Python
* Google Colab
* Hugging Face
* Transformers
* Base64
* Large Language Models (LLMs)

## 📂 Project Structure

```text
CTF-Prompt-Injection/
│
├── CTF-Prompt-Injection.ipynb
└── README.md
```

## 🚀 How to Run

### 1. Open Google Colab

Upload or open:

```text
CTF-Prompt-Injection.ipynb
```

### 2. Install Required Libraries

Run the installation cell in the notebook.

```python
!pip install -q transformers accelerate huggingface_hub sentencepiece protobuf
```

### 3. Provide the Challenge Data

Add the encoded strings provided for the different CTF levels to the notebook.

The notebook processes the levels individually.

### 4. Decode the Encoded Data

The Python code checks and decodes the Base64-encoded challenge data.

Example:

```python
import base64

decoded = base64.b64decode(encoded_data).decode("utf-8")
print(decoded)
```

### 5. Analyze the Prompts

The decoded prompts can then be analyzed to understand the prompt-injection challenge and determine the required outputs.

## 🔐 CTF Levels

The challenge contains multiple levels that can be processed individually.

```text
Level 1
Level 2
Level 3
Level 4
Level 5
```

Each level may contain different encoded or prompt-injection content.

## ⚠️ Notes

* The encoded values must be copied exactly as provided by the challenge.
* Invalid or incomplete Base64 strings will result in decoding errors.
* Hugging Face models may require authentication or access permission depending on the selected model.
* The notebook is intended for educational and CTF purposes.

## 📚 Learning Outcomes

Through this project, the following concepts are explored:

* Base64 encoding and decoding
* Python data processing
* Prompt injection
* LLM security
* AI security testing
* CTF problem solving
* Hugging Face Transformers
* Google Colab experimentation

## 👩‍💻 Author

**Dharshini A**

GitHub Repository:

`CTF-Prompt-Injection`

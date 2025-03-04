# **Part-of-Speech (POS) Tagging using NLTK**

## **Overview**
This project demonstrates **Part-of-Speech (POS) tagging** using the **Natural Language Toolkit (NLTK)** in Python. POS tagging is a fundamental step in Natural Language Processing (NLP), where each word in a sentence is labeled with its grammatical category, such as **noun (NN), verb (VB), adjective (JJ), adverb (RB), etc.**  

---

## **Features**
- ✅ Tokenizes sentences into words.  
- ✅ Uses **NLTK’s POS tagging** to label words.  
- ✅ Supports English language POS tagging.  
- ✅ Displays POS-tagged words in a structured format.  

---

## **Installation**
To use this project, you need to install **NLTK**, which is a Python library for NLP.  

### **Step 1: Install NLTK**
```bash
pip install nltk
Step 2: Download Required NLTK Data
After installing NLTK, download the POS tagger dataset using the following command:

python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
Usage
Import the required libraries
Tokenize a sentence into words
Apply POS tagging using NLTK
View the tagged output
Example Output
bash
Copy
Edit
Sentence: "The quick brown fox jumps over the lazy dog."
POS Tags: [('The', 'DT'), ('quick', 'JJ'), ('brown', 'JJ'), ('fox', 'NN'), ('jumps', 'VBZ'), ('over', 'IN'), ('the', 'DT'), ('lazy', 'JJ'), ('dog', 'NN')]
POS Tags Explanation
POS Tag	Description	Example
NN	Noun	Dog, Car, Tree
VB	Verb	Run, Jump, Write
JJ	Adjective	Quick, Happy, Bright
RB	Adverb	Quickly, Slowly, Happily
DT	Determiner	The, A, An
IN	Preposition	In, On, Over
For a full list of POS tags, refer to the NLTK POS Tag Documentation.

Applications of POS Tagging
✅ Chatbots & Virtual Assistants – Understanding user input.
✅ Text Analytics & Sentiment Analysis – Extracting key insights.
✅ Machine Translation – Improving language translation accuracy.
✅ Speech Recognition – Enhancing spoken language processing.

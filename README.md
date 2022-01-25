# NLP Seminar - Final Project
This repository contains the following:
- A list of stop words in Hebrew in multiple morphological forms
- A python code that parses the MILA corpus

A download link for the parsed corpus:
[MILA adapted corpus and resources](https://technionmail-my.sharepoint.com/:u:/g/personal/ariel_kr_campus_technion_ac_il/EeDu_IrymyRHikVhciVqjJYBSRGn5_yQB2jzNVgjD9BCCA?e=saw9V5)


### How to load the data
Use the following python snippet to load the data files:

```python
  import json
  
  with open("MILA_corpus.json", "r", encoding='utf-8') as file:
    corpus = json.load(file)
  
  with open("MILA_resources.json", "r", encoding='utf-8') as file:
    resources = json.load(file)
```

### Resources
Alon Itai and Shuly Wintner. "Language Resources for Hebrew." Language Resources and Evaluation 42(1):75-98, March 2008.

ALL RIGHTS RESERVED TO MILA - KNOWLEDGE CENTER FOR PROCESSING HEBREW  

# German Prompt Engineering

This is a repository including examples on how to create german prompt datasets using the [BigScience PromptSource library](https://github.com/bigscience-workshop/promptsource).

## Getting started

1. Installing required packages and `promptsource` 

```bash
git clone https://github.com/philschmid/promptsource
pip install -r promptsource/requirements.txt
pip install -e promptsource/
```

2. Run PromptSource UI

```bash
streamlit run promptsource/promptsource/app.py
```

3. Check out jupyter notebook on how to create new prompted datasets and push them to the hub.

[jupyter notebook](data_engineering.ipynb)


### New Added datasets 

The new added german dataset templates are currently only available in my fork. I play to upstream as soon as possible. 
Fork: https://github.com/philschmid/promptsource 

* [germanquad](https://huggingface.co/datasets/deepset/germanquad): I copied the `squad` template and translated it to german. [TEMPLATE](https://github.com/philschmid/promptsource/blob/main/promptsource/templates/germanquad/templates.yaml)


### Todos

~* [ ] [germanner](https://huggingface.co/datasets/germaner)~
* [ ] [xsum - german part](https://huggingface.co/datasets/xsum)
* [ ] [xquad - german part](https://huggingface.co/datasets/xquad)
* [ ] [xquad_r - german part](https://huggingface.co/datasets/xquad_r)
* [ ] [germandpr](https://huggingface.co/datasets/deepset/germandpr)
* [ ] [amazon_reviews_multi](https://huggingface.co/datasets/amazon_reviews_multi)
~* [ ] [germeval_14](https://huggingface.co/datasets/germeval_14)~
* [ ] [germeval_18](https://huggingface.co/datasets/germeval_14)
~* [ ] [german_legal_entity_recognition](https://huggingface.co/datasets/german_legal_entity_recognition)~
* [ ] [gnad10 - German news article](https://huggingface.co/datasets/gnad10)

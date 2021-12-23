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

* [germanquad](https://huggingface.co/datasets/deepset/germanquad): I copied the `squad` template and translated it to german.

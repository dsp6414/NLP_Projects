<div style="text-align: center">

<h1>Machine Translation</h1>

<h2>
    Summary of Repository
</h2>

This repository houses Machine Translation models fine-tuned using checkpoints from HuggingFace. More information about each model can be found in their respective subdirectory.

<br />

<h2>
    Model Checkpoint
</h2>

<a href="https://huggingface.co/facebook/mbart-large-50">
    <em>facebook/mbart-large-50</em>
</a>

<br />

<h2>
    Dataset Source:
</h2>

<a href="https://www.kaggle.com/datasets/hgultekin/paralel-translation-corpus-in-22-languages">
    Parallel Translation Corpus in 24 languages! (~5M)
</a>

<br />

<h2>
    Results Comparison
</h2>
</div>


| Project Name | Loss | Bleu | Rouge1 | Rouge2 | RougeL | RougeLsum | Meteor |
| ----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| NLP Translation Project-EN to FR | 0.3902 | 35.1914 | 0.6420 | 0.4573 | 0.6070 | 0.6069 | 0.5917 |
| NLP Translation Project-EN_DE | 1.2342 | 35.5931 | 0.5803 | 0.3939 | 0.5439 | 0.5442 | 0.5501 |
| NLP Translation Project-EN_ES | 1.0290 | 41.4437 | 0.6751 | 0.4977 | 0.6372 | 0.6376 | 0.6479 |

<caption>
    *All Metrics are the Evaluation version of the metrics.
</caption>

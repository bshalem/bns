# What is BNS?
BNS is a dataset of long-form biographical narratives for evaluating multi-stage text summarization.

The data is formatted as a collection of four json line files. Each json object is defined as follows:
```json
{
    "volume": [3],
    "chapter": ["11"],
    "text": ["source text"],
    "esummary": ["extractive summary"],
    "asummary": ["abstractive summary"],
    "id": ["101"],
  },
```
# Download BNS
The dataset comprises four biographical narratives formatted as jsonl files: [douglass.jsonl](douglass.jsonl), [grant.jsonl](grant.jsonl),[marktwain.jsonl](marktwain.jsonl), [napoleon.jsonl](napoleon.jsonl).

# Paper
More details on the collecting of the data is available in our companion paper:

Avi Bleiweiss. *Two-step Text Summarization for Long-form Biographical Narrative Genre*. In CODI, 2023.

### Citation
If you use the BNS dataset as part of your work, please cite:

    @inproceedings{,
        author = {Bleiweiss, Avi},
        title = {Two-step Text Summarization for Long-form Biographical Narrative Genre},
        booktitle = {4th workshop on Computational Approaches to Discourse - ({CODI})},
        month = {july},
        year = {2023},
        publisher = {Association for Computational Linguistics},
        address = {Toronto, Canada},
        pages = {1},
    }
    

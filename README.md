# CPDE: Artificial Intelligence in Qualitative Analaysis

Slide deck and supplemental materials for the talk "Artificial Intelligence in Qualitative Analysis" given at the Center for Program Design & Evaluation's Lunch & Learn Session, March 10, 2025, Dartmouth College.


## Contents
This repository contains the following materials:

```
cpde-talk
├── .env-sample                         # See "Running the code example" below
├── README.md                           # This README
├── demo
│   ├── 01-semantic_embeddings.ipynb    # A demonstration of semantic embeddings for topic analysis
│   ├── 02-llm_assisted_coding.md       # A walkthrough of an example of AI-assisted qualitative coding
│   └── data                            # Materials used in the examples
├── doc                                 # PDF and HTML versions of the demos
├── ppt                                 # The slide deck
└── requirements.txt                    # Requirements for the demos
```

## Running the code example
To run the code example, you need to install the requirements:

```
pip install -r requirements.txt
```

Then rename the file `.env-sample` to `.env` and fill in the value for `DARTMOUTH_CHAT_API_KEY` (see the [instructions here](https://rcweb.dartmouth.edu/~d20964h/2024-12-11-dartmouth-chat-api/api_key/) on how to obtain a key).

Then run the Jupyter Notebook `demo/01-semantic_embeddings.ipynb`.


## Synthetic responses

The dataset of synthetic survey responses and the synthetic reflection essay was created using Claude 3.7 Sonnet. All prompts and responses can be found in `demo/data/prompt/`.

## Licensing

<table>
<tbody>
  <tr>
    <td style="padding:0px;border-width:0px;vertical-align:center">
    Instructional materials created by Simon Stone for Dartmouth College under <a href="https://creativecommons.org/licenses/by/4.0/">Creative Commons CC BY-NC 4.0 License</a>.
    </td>
    <td style="padding:0 0 0 1em;border-width:0px;vertical-align:center"><img alt="Creative Commons License" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></td>
  </tr>
</tbody>

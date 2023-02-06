# MCTest-Augmented
A new version of the MCTest dataset for machine based reading comprehension. Prompts are presented with syntactic complexity scores used for standardized human-machine evaluation. We use use the [Stanza](https://github.com/stanfordnlp/stanza) parser to generate CoNLL-U universal dependency representations of prompts and score those prompts accoring to various measures of syntactic complexity The goal is to create a standardized benchmark for humans and machines on NLU tasks. The MCTest dataset contains hundreds of of passages of natural lanaguge text and associated multiple choice questions. We are in the process of reformatting these data for ease of use with evaluating both humans and language models comparatively.

We have just started building the dataset and it will be undergoing a process of iterative development and design for the next few weeks. Check back in soon!

# Usage
TBD

# To-Do
+ Add metric for recursive complexity derived from constituency parse
+ Modify notebooks for out of the box functionality
+ Filter dataset for prompts that are too long
+ Add `tsv` files for prompt questions and scores
+ Combine questions and contexts to create complete prompts and scores

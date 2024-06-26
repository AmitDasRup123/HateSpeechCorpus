# HateSpeechCorpus

## Overview
The HateSpeechCorpus is a dataset collected from Twitter, consisting of 3003 tweets. It has been meticulously annotated by three speech-language pathology graduate students, ensuring high-quality labeling of hate speech. This dataset is invaluable for researchers and practitioners working on hate speech detection and natural language processing.

**Source:** Twitter  
**Length:** 3003 tweets  
**Annotators:** Three speech-language pathology graduate students  

## Paper
For a detailed investigation of annotator bias in LLMs for hate speech detection, refer to the associated paper: [Investigating Annotator Bias in Large Language Models for Hate Speech Detection](https://arxiv.org/abs/2406.11109).

## Citation
If you use this dataset in your research, please cite the following paper:

@misc{das2024investigating,
title={Investigating Annotator Bias in Large Language Models for Hate Speech Detection},
author={Amit Das and Zheng Zhang and Fatemeh Jamshidi and Vinija Jain and Aman Chadha and Nilanjana Raychawdhary and Mary Sandage and Lauramarie Pope and Gerry Dozier and Cheryl Seals},
year={2024},
eprint={2406.11109},
archivePrefix={arXiv},
primaryClass={cs.CL}
}

# Load the dataset
df = pd.read_csv('HateSpeechCorpus.csv')

# Display the first few rows
print(df.head())

## License: CC BY

Contact Information: azd0123@auburn.edu
---

This README provides an overview of the HateSpeechCorpus, including its source, length, annotators, keywords used for generation, and citation details. The dataset is a valuable resource for advancing the field of hate speech detection.


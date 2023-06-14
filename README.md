# CAOD: Chinese Agitative Opinion Dataset

CAOD is a ten-thousands scale Chinese agitative opinion dataset based on WeChat public account.

## Agitative Opinions

we categorize agitative opinions into nine types which are **inflammatory, fearmongering, group opposition, unrealistic, offensive, pornographic, mammonish, immoral and extreme** opinions. If a sentence contains any type of opinions above, we regard it as a sentence containing agitative opinions.

## Construction

CAOD is constructed from articles with negative sentiment on WeChat public account. First, the sentences containing agitative opinions are annotated manually in articles. Then the sentences containing agitative opinions are extracted to form the positive samples with the rest negative ones. The following figure displays this process.

![process](fig/process.svg)

## Content

In `Chinese_agitative_opinion_dataset.xlsx` is CAOD. There are totally 26,592 samples in CAOD, with 2,198 positive samples and 24,394 negative samples. 

Label `1` represents the sentence containing agitative opinions;

Label `0` represents the sentence not containing agitative opinions.

Part of the dataset is shown here:

![label1](fig/label1.png)

![label0](fig/label0.png)



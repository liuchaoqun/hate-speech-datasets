# hate-speech-datasets
This repository consist dataset mentioned in some papers. 
## [Contextualizing Hate Speech Classifiers with Post-hoc Explanation](https://arxiv.org/abs/2005.02439) ([source code](https://github.com/BrendanKennedy/contextualizing-hate-speech-models-with-explanations))
* dataset
  - GabHateCorpus
  - [Stormfront corpus](https://github.com/aitor-garcia-p/hate-speech-dataset)
* problem
  - models tend to have biases over group identifiers but unable to learn from context, which leads to false positives.
* methodology
  - propose a novel regularization technique (Regularizing SOC explanations of group identifiers) based on these explanations that encourages models to learn from the context of group identifiers in addition to the identifiers themselves.
* performance
  - ![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/contextualizing.png?raw=true)

## [Latent Hatred: A Benchmark for Understanding Implicit Hate Speech](https://arxiv.org/abs/2109.05322)
* dataset
  - implicit-hate-corpus
* problem
  - most work has focused on explicit or overt hate speech, failing to ad- dress a more pervasive form based on coded or indirect language.
* methodology
  - introduce a theoretical taxonomy of implicit hate speech 
  - Provide a dataset for implicit hate speech.
  - Provide several state of the art baselines for detecting and explaining implicit hate speech.
* performance
![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/implicit1.png?raw=true)
![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/implicit2.png?raw=true)

## [Hate Speech Detection Based on Sentiment Knowledge Sharing](https://aclanthology.org/2021.acl-long.556/) ([source code](https://github.com/1783696285/SKS))
  - Twitter SA
  - DV
  - SE2019-task-5 ([source from CodaLab](https://competitions.codalab.org/competitions/19935#learn_the_details))

## [Targets and Aspects in Social Media Hate Speech](https://aclanthology.org/2021.woah-1.19.pdf) ([source code](https://github.com/TalnUPF/HateSpeechTargetsAspects))

## [Lone Pine at SemEval-2021 Task 5: Fine-Grained Detection of Hate Speech Using BERToxic](https://arxiv.org/abs/2104.03506) ([source code](https://github.com/Yakoob-Khan/Toxic-Spans-Detection))
  - Task: [Toxic Spans Detection (SemEval 2021 Task 5)](https://github.com/ipavlopoulos/toxic_spans)


# Some other hate speech datasets: 
* [Hate speech identification](https://github.com/t-davidson/hate-speech-and-offensive-language): Contributors viewed short text and identified if it a) contained hate speech, b) was offensive but without hate speech, or c) was not offensive at all. Contains nearly 15K rows with three contributor judgments per text string. (3 MB)

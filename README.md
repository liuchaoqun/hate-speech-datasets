# hate-speech-datasets
This repository consist dataset mentioned in some papers. 
  * [HateXplain: A Benchmark Dataset for Explainable Hate Speech Detection](https://arxiv.org/abs/2012.10289) ([source code](https://github.com/hate-alert/HateXplain))
  * [Automated Hate Speech Detection and the Problem of Offensive Language](https://github.com/t-davidson/hate-speech-and-offensive-language)
    - Task: Contributors viewed short text and identified if it a) contained hate speech, b) was offensive but without hate speech, or c) was not offensive at all. Contains nearly 15K rows with three contributor judgments per text string. (3 MB)
   * [TweetEval benchmark (Findings of EMNLP 2020)](https://github.com/cardiffnlp/tweeteval)
# Papers
## [The Gab Hate Corpus: A collection of 27k posts annotated for hate speech](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/GabHateCorpus/Documentation/2020_The%20Gab%20Hate%20Corpus-%20A%20collection%20of%2027k%20posts%20annotated%20for%20hate%20speech.pdf)
* dataset
  - [GabHateCorpus](https://github.com/liuchaoqun/hate-speech-datasets/tree/main/GabHateCorpus)
* problem
  -  provide a large-scale hate speech dataset
* performance (baseline)
  - <img src="https://github.com/liuchaoqun/hate-speech-datasets/blob/main/GabHateCorpus/GHC_baseline.png?raw=true" width="600">

## [Contextualizing Hate Speech Classifiers with Post-hoc Explanation](https://arxiv.org/abs/2005.02439) ([source code](https://github.com/BrendanKennedy/contextualizing-hate-speech-models-with-explanations))
* dataset
  - [GabHateCorpus](https://github.com/liuchaoqun/hate-speech-datasets/tree/main/GabHateCorpus)
  - [Stormfront corpus](https://github.com/aitor-garcia-p/hate-speech-dataset)([paper](https://arxiv.org/pdf/1809.04444.pdf))
* problem
  - models tend to have biases over group identifiers but unable to learn from context, which leads to false positives.
* methodology
  - propose a novel regularization technique (Regularizing SOC explanations of group identifiers) based on these explanations that encourages models to learn from the context of group identifiers in addition to the identifiers themselves.
* performance
  - ![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/contextualizing.png?raw=true)

## [Latent Hatred: A Benchmark for Understanding Implicit Hate Speech](https://arxiv.org/abs/2109.05322)([source code](https://github.com/GT-SALT/implicit-hate))
* dataset
  - [implicit-hate-corpus](https://github.com/liuchaoqun/hate-speech-datasets/tree/main/implicit-hate-corpus)
* problem
  - most work has focused on explicit or overt hate speech, failing to ad- dress a more pervasive form based on coded or indirect language.
* methodology
  - introduce a theoretical taxonomy of implicit hate speech 
  - Provide a dataset for implicit hate speech.
  - Provide several state of the art baselines for detecting and explaining implicit hate speech.
* performance
  - ![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/implicit1.png?raw=true)
  
  - ![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/implicit2.png?raw=true)

## [Hate Speech Detection Based on Sentiment Knowledge Sharing](https://aclanthology.org/2021.acl-long.556/) ([source code](https://github.com/1783696285/SKS))
* dataset 
  - [Twitter SA](https://github.com/liuchaoqun/hate-speech-datasets/tree/main/Twitter-SA)
  - [DV](https://github.com/liuchaoqun/hate-speech-datasets/tree/main/DV)
  - [SE2019-task-5](https://github.com/liuchaoqun/hate-speech-datasets/tree/main/SE2019-task-5) ([source from CodaLab](https://competitions.codalab.org/competitions/19935#learn_the_details))
* problem
  - The deep learning methods of predecessors often only used pre-trained models or deeper networks to obtain semantic features, ignoring the sentiment features of the target sentences and external sentiment resources, which also makes the performance of neural networks unsatisfactory in hate speech detection.
* methodology
  - propose a hate speech detection framework based on sentiment knowledge sharing
  - ![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/SKS_arch.png?raw=true)
* performance
  - ![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/SKS.png?raw=true)

## [Targets and Aspects in Social Media Hate Speech](https://aclanthology.org/2021.woah-1.19.pdf) ([source code](https://github.com/TalnUPF/HateSpeechTargetsAspects))
* dataset
  - [data](https://github.com/TalnUPF/HateSpeechTargetsAspects/tree/main/data)
* problem
  -	Identify who is the target in a given hate speech post.
  -	Identify what aspects (or characteristics) of the target are attributed to the target in the post.
* methodology
  - ![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/targets_arch.png?raw=true)

## [Lone Pine at SemEval-2021 Task 5: Fine-Grained Detection of Hate Speech Using BERToxic](https://arxiv.org/abs/2104.03506) ([source code](https://github.com/Yakoob-Khan/Toxic-Spans-Detection))
* problem: 
  - Task: [Toxic Spans Detection (SemEval 2021 Task 5)](https://github.com/ipavlopoulos/toxic_spans)
  - extract the list of toxic spans that attribute to a text???s toxicity 
* Methodology: BERT + post-processing
  - ![](https://github.com/liuchaoqun/hate-speech-datasets/blob/main/figs/bertoxic.png?raw=true)
* Performance: ???	Our system significantly outperformed the pro- vided baseline and achieved an F1-score of 0.683, placing Lone Pine in the 17th place out of 91 teams in the competition.



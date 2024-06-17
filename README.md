<div align='center'>

English | [简体中文](README_zh.md)

# LLM4TS: Large Language Models for Time Series

</div>

This project collects the papers and codes of Large Language Models (LLMs) and Foundation Models (FMs) for Time Series (TS). Hope this project can help you to understand the LLMs and FMs for TS.

## 🦙 LLMs for Time Series

*After the success of BERT, GPT, and other LLMs in NLP, some researchers have proposed to apply LLMs to Time Series (TS) tasks. They fintune the LLMs on TS datasets and achieve state-of-the-art results.*

* PromptCast: A New Prompt-based Learning Paradigm for Time Series Forecasting Hao, in *arXiv* 2022. [PaperPaper](https://arxiv.org/abs/2210.08964)[GitHubGitHub](https://)
* One Fits All: Power General Time Series Analysis by Pretrained LM, in *arXiv* 2023. [PaperPaper](https://arxiv.org/abs/2302.11939)[GitHubGitHub](https://)
* Temporal Data Meets LLM -- Explainable Financial Time Series Forecasting, in *arXiv* 2023. [PaperPaper](https://arxiv.org/abs/2306.11025)[GitHubGitHub](https://)
* TEST: Text Prototype Aligned Embedding to Activate LLM's Ability for Time Series. [PaperPaper](https://arxiv.org/abs/2308.08241)[GitHubGitHub](https://)
* LLM4TS: Two-Stage Fine-Tuning for Time-Series Forecasting with Pre-Trained LLMs. [PaperPaper](https://arxiv.org/abs/2308.08469)[GitHubGitHub](https://)

* The first step is the hardest: Pitfalls of Representing and Tokenizing Temporal Data for Large Language Models. [PaperPaper](https://arxiv.org/abs/2309.06236)[GitHubGitHub](https://)

* Large Language Models Are Zero-Shot Time Series Forecasters. [PaperPaper](https://arxiv.org/abs/2310.07820)[GitHubGitHub](https://)

* TEMPO: Prompt-based Generative Pre-trained Transformer for Time Series Forecasting. [PaperPaper](https://arxiv.org/abs/2310.04948)[GitHubGitHub](https://)

* Time-LLM: Time Series Forecasting by Reprogramming Large Language Models. [PaperPaper](https://arxiv.org/abs/2310.01728)[GitHubGitHub](https://)

* S2IP-LLM: Semantic Space Informed Prompt Learning with LLM for Time Series Forecasting. [PaperPaper](https://arxiv.org/pdf/2403.05798.pdf)[GitHubGitHub](https://)

### 📍 Survey

* Large Models for Time Series and Spatio-Temporal Data: A Survey and Outlook. [SurveySurvey](https://arxiv.org/abs/2310.10196)[GitHubGitHub](https://)

* Position Paper: What Can Large Language Models Tell Us about Time Series Analysis. [SurveySurvey](https://arxiv.org/abs/2402.02713)[GitHubGitHub](https://)

* Foundation Models for Time Series Analysis: A Tutorial and Survey [SurveySurvey](https://arxiv.org/abs/2403.14735)[GitHubGitHub](https://)

### 📍 Similar Things
* Large Language Models are Few-Shot Health Learners, in *arXiv* 2023. [PaperPaper](https://arxiv.org/abs/2305.15525)[GitHubGitHub](https://)

* Frozen Language Model Helps ECG Zero-Shot Learning, in *arXiv* 2023.[PaperPaper](https://arxiv.org/abs/2303.12311)[GitHubGitHub](https://)

## 🧱 Foundation Models for Time Series

*Recently, some kinds of Foundation Models (FMs) for Time Series (TS) have been proposed. These FMs aims to learn the representation of Time Series from large datasets and then transfer the representation to downstream tasks. Compared with TS-LLMs, these methods do not depend on the pretrained LLMs.*

* Tiny Time Mixers (TTMs): Fast Pretrained Models for Enhanced Zero/Few-Shot Forecasting of Multivariate Time Series. [PaperPaper](https://arxiv.org/abs/2401.03955)[GitHubGitHub](https://)

* A decoder-only foundation model for time-series forecasting. [PaperPaper](https://arxiv.org/abs/2310.10688)[GitHubGitHub](https://)

* TimeGPT-1. [PaperPaper](https://arxiv.org/abs/2310.03589?ref=emergentmind)[GitHubGitHub](https://)

* Lag-Llama: Towards Foundation Models for Time Series Forecasting. [PaperPaper](https://arxiv.org/abs/2310.08278)[GitHubGitHub](https://)

* Unified Training of Universal Time Series Forecasting Transformers. [PaperPaper](https://arxiv.org/abs/2402.02592)[GitHubGitHub](https://)

* MOMENT: A Family of Open Time-series Foundation Models. [PaperPaper](https://arxiv.org/abs/2402.03885)[GitHubGitHub](https://)

* Chronos: Learning the Language of Time Series [PaperPaper](https://arxiv.org/abs/2403.07815) [GitHubGitHub](https://github.com/amazon-science/chronos-forecasting)

## 🔗 Related Fields
*Here, some related fields are listed. These fields are not the main focus of this project, but they are also important for understanding how LLMs are applied to other fields rather than NLP and FMs in specific fields are developed.*

### 📍 PreTrained Time Series
* A Survey on Time-Series Pre-Trained Models, in *arXiv* 2023. [PaperPaper](https://arxiv.org/abs/2305.10716)
* Transfer learning for Time Series Forecasting. [GitHubGitHub](https://github.com/Nixtla/transfer-learning-time-series)
* TST: A transformer-based framework for multi- variate time series representation learning. [PaperPaper](https://arxiv.org/abs/2010.02803)
* Ti-mae: Self-supervised masked time series autoencoders. [PaperPaper](https://arxiv.org/abs/2301.08871)
* SimMTM: A Simple Pre-Training Framework for Masked Time-Series Modeling. [PaperPaper](https://arxiv.org/pdf/2302.00861.pdf)

* Cost: Contrastive learning of disentangled seasonal-trend rep- resentations for time series forecasting.[PaperPaper](https://arxiv.org/abs/2202.01575)

* TS2Vec: Towards Universal Representation of Time Series. [PaperPaper](https://arxiv.org/abs/2106.10466)

### 📍 LLM for Recommendation Systems
* Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5), in *arXiv* 2022. [PaperPaper](https://arxiv.org/abs/2203.13366)
* LLM4Rec. [GitHubGitHub](https://github.com/WLiK/LLM4Rec)


### 📍 LLM/FM for Tabular Data
* AnyPredict: Foundation Model for Tabular Prediction, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2305.12081)
* XTab: Cross-table Pretraining for Tabular Transformers, in *ICML* 2023. [\[Paper\]](https://arxiv.org/abs/2305.06090)

### 📍 LLM in Production (LLMOps)
* Awesome-LLMOps. [\[GitHub\]](https://github.com/tensorchord/Awesome-LLMOps)

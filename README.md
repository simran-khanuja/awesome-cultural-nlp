# Awesome Cultural NLP: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome cultural NLP resources, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

**Table Of Contents**
* [Survey](#survey)
* [Dataset](#dataset)
* [Image Captioning](#image-captioning)
* [Models](#models)
  * [Vision and Language](#vision-and-language)
* [Evaluation](#evaluation)
  * [LLMs](#llms)
  * [Text-to-image](#text-to-image)
  * [VLMs](#vlms)
* [Analysis](#analysis)
  * [Text-to-image](#text-to-image)
  * [LLMs](#llms)
  * [VLMs](#vlms)
  * [Cross-cultural Variations](#cross-cultural-variations)
* [Methodology](#methodology)
  * [Data](#data)
* [Alignment](#alignment)
  * [Model](#model)
  * [Data](#data)
* [Applications](#applications)


## Survey
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| Culturally Aware and Adapted NLP: A Taxonomy and a Survey of the State of the Art | Arxiv 2024 | [2406.03930](https://arxiv.org/pdf/2406.03930) | []() | []() |
| Towards Measuring and Modeling “Culture” in LLMs: A Survey | Arxiv 2024 | [2403.15412](https://arxiv.org/pdf/2403.15412) | [Github](https://github.com/faridlazuarda/cultural-llm-papers) | Cool paper! |
| Challenges and Strategies in Cross-Cultural NLP | ACL 2022 | [2203.10020](https://arxiv.org/abs/2203.10020) | []() | []() |
|  |  | []() | []() | []() |

## Dataset
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| WorldCuisines: A Massive-Scale Benchmark for Multilingual and Multicultural Visual Question Answering on Global Cuisines | Arxiv 2024 | [2410.12705](https://arxiv.org/pdf/2410.12705) | [Code, Data, and Leaderboard](https://worldcuisines.github.io/) | Data |
| BLEnD: A Benchmark for LLMs on Everyday Knowledge in Diverse Cultures and Languages | NeurIPS D&B 2024 | [2406.09948](https://arxiv.org/abs/2406.09948) | [Code and Data](https://github.com/nlee0212/BLEnD) | Data |
| Vision-Language Models under Cultural and Inclusive Considerations | Arxiv 2024 | [2407.06177](https://arxiv.org/pdf/2407.06177) | []() | []() |
| Beyond Aesthetics: Cultural Competence in Text-to-Image Models | Arxiv 2024 | [2407.06863](https://arxiv.org/pdf/2407.06863) | [Data](https://github.com/google-research-datasets/cube) | Data |
| M5 -- A Diverse Benchmark to Assess the Performance of Large Multimodal Models Across Multilingual and Multicultural Vision-Language Tasks | Arxiv 2024 | [2407.03791](https://arxiv.org/pdf/2407.03791) | []() | []() |
| Culturally Aware and Adapted NLP: A Taxonomy and a Survey of the State of the Art | Arxiv 2024 | [2406.03930](https://arxiv.org/pdf/2406.03930) | []() | []() |
| NORMAD: A Benchmark for Measuring the Cultural Adaptability of Large Language Models | Arxiv 2024 | [2404.12464](https://arxiv.org/abs/2404.12464) | [Data](https://github.com/Akhila-Yerukola/NormAd) | Data |
| An image speaks a thousand words, but can everyone listen? On image transcreation for cultural relevance | Arxiv 2024 | [2404.01247](https://arxiv.org/abs/2404.01247) | [Code and Data](https://github.com/simran-khanuja/image-transcreation) | Data + Application
| No Culture Left Behind: Massively Multi-Cultural Knowledge Acquisition & LM Benchmarking on 1000+ Sub-Country Regions and 2000+ Ethnolinguistic Groups | Arxiv 2024 | [2402.09369v1](https://arxiv.org/pdf/2402.09369v1) | [Data](https://github.com/yrf1/LLM-MassiveMulticultureNormsKnowledge-NCLB) | []() |
| The PRISM Alignment Project: What Participatory, Representative and Individualised Human Feedback Reveals About the Subjective and Multicultural Alignment of Large Language Models | Arxiv 2024 (under review) | [2404.16019](https://arxiv.org/pdf/2404.16019) | [Repository](https://github.com/HannahKirk/prism-alignment) | Code and Data |
| Exploring Cross-Cultural Differences in English Hate Speech Annotations: From Dataset Construction to Analysis | NAACL 2024 | [2308.16705](https://arxiv.org/abs/2308.16705) | [Data+Code](https://github.com/nlee0212/CREHate) | []() |
| CLIcK: A Benchmark Dataset of Cultural and Linguistic Intelligence | LREC-COLING '24 | [https://arxiv.org/pdf/2403.06412](https://arxiv.org/pdf/2403.06412) | [Data](https://github.com/rladmstn1714/CLIcK) | []() |
| Bridging Cultural Nuances in Dialogue Agents through Cultural Value Surveys | EACL Findings 2024 | [2401.10352](https://arxiv.org/abs/2401.10352) | [Dataset](https://github.com/yongcaoplus/cuDialog) | []() |
| Culturally Aware Natural Language Inference | EMNLP 2023 (Findings) | [2023.findings-emnlp.509](https://aclanthology.org/2023.findings-emnlp.509.pdf) | [Data](https://github.com/SALT-NLP/CulturallyAwareNLI) | []() |
| Global Voices, Local Biases: Socio-Cultural Prejudices across Languages | EMNLP 2023 | [2310.17586](https://arxiv.org/abs/2310.17586) | [Data](https://github.com/iamshnoo/weathub) | Data+Analysis
| NORMSAGE: Multi-Lingual Multi-Cultural Norm Discovery from Conversations On-the-Fly | EMNLP 2023 | [2210.08604](https://arxiv.org/abs/2210.08604) | [Code and Data](https://github.com/yrf1/NormSage) | NormsKB
| GeoDE: a Geographically Diverse Evaluation Dataset for Object Recognition | Neurips 2023 | [2301.02560](https://arxiv.org/abs/2301.02560) | [Code and Data](https://geodiverse-data-collection.cs.princeton.edu/) | []() |
| SeeGULL: A Stereotype Benchmark with Broad Geo-Cultural Coverage Leveraging Generative Models | ACL 2023 | [2305.11840](https://arxiv.org/pdf/2305.11840) | [Code](https://github.com/google-research-datasets/seegull) | []() |
| FORK: A Bite-Sized Test Set for Probing Culinary Cultural Biases in Commonsense Reasoning Models | ACL Findings 2023 | [2023.findings-acl.631](https://aclanthology.org/2023.findings-acl.631.pdf) | [Dataset](https://github.com/shramay-palta/FORK_ACL2023) | []() |
| Multi-lingual and Multi-cultural Figurative Language Understanding | ACL Findings 2023 | [2305.16171](https://arxiv.org/abs/2305.16171) | [Code](https://github.com/simran-khanuja/Multilingual-Fig-QA) | []() |
| EnCBP: A New Benchmark Dataset for Finer-Grained Cultural Background Prediction in English | ACL Findings 2022 | [2203.14498](https://arxiv.org/abs/2203.14498) | []() | []() |
| Re-contextualizing Fairness in NLP: The Case of India | AACL 2022 | [2209.12226](https://arxiv.org/abs/2209.12226) | [Data](https://github.com/google-research-datasets/nlp-fairness-for-india) | Data+Analysis
| Visually Grounded Reasoning across Languages and Cultures | EMNLP 2021 | [2109.13238](https://arxiv.org/abs/2109.13238) | [Website](https://marvl-challenge.github.io/) | EMNLP 2021 Best Paper |
| Would you Rather? A New Benchmark for Learning Machine Alignment with Cultural Values and Social Preferences | ACL 2020 | [2020.acl-main.477/](https://aclanthology.org/2020.acl-main.477/) | []() | []() |
|  |  | []() | []() | []() |

## Image Captioning
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| CIC: A framework for Culturally-aware Image Captioning | IJCAI 2024 | [2402.05374](https://arxiv.org/abs/2402.05374) | [Webpage](https://shane3606.github.io/cic/) | []() |
|  |  | []() | []() | []() |

## Models

### Vision and Language
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| GIVL: Improving Geographical Inclusivity of Vision-Language Models With Pre-Training Methods | CVPR 2023 | [2301.01893](https://arxiv.org/abs/2301.01893) | [Code (not released yet)](https://github.com/WadeYin9712/GIVL) | []() |
|  |  | []() | []() | []() |

## Evaluation

### LLMs
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| Cultural Conditioning or Placebo? On the Effectiveness of Socio-Demographic Prompting | Arxiv 2024 | [2406.11661](https://arxiv.org/pdf/2406.11661) | []() | []() |
| Extrinsic Evaluation of Cultural Competence in Large Language Models | Arxiv 2024 | [2406.11565](https://arxiv.org/pdf/2406.11565) | []() | []() |
| CulturalTeaming: AI-Assisted Interactive Red-Teaming for Challenging LLMs’ (Lack of) Multicultural Knowledge | Arxiv 2024 | [2404.06664](https://arxiv.org/pdf/2404.06664) | []() | []() |
| Having Beer after Prayer? Measuring Cultural Bias in Large Language Models | ACL 2024 | [2305.14456](https://arxiv.org/pdf/2305.14456) |  [Code](https://github.com/tareknaous/camel) | []() | 
|  |  | []() | []() | []() |
| Large language models, social demography, and hegemony: comparing authorship in human and synthetic text | Journal of Big Data | [10.1186/s40537-024-00986-7](https://link.springer.com/article/10.1186/s40537-024-00986-7) |  []() | []() | 
|  |  | []() | []() | []() |

### Text-to-image
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| The Factuality Tax of Diversity-Intervened Text-to-Image Generation: Benchmark and Fact-Augmented Intervention | Arxiv 2024 | [2407.00377v1](https://arxiv.org/pdf/2407.00377v1) | []() | []() |
| On the Cultural Gap in Text-to-Image Generation | Arxiv 2023 | [2307.02971](https://arxiv.org/pdf/2307.02971) | [Code](https://github.com/longyuewangdcu/C3-Bench) | []() |
|  |  | []() | []() | []() |

### VLMs
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| From Local Concepts to Universals: Evaluating the Multicultural Understanding of Vision-Language Models | Arxiv 2024 | [2407.00263](https://arxiv.org/pdf/2407.00263) | []() | []() |
|  |  | []() | []() | []() |


## Analysis

### Text-to-image
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| ViSAGe: A Global-Scale Analysis of Visual Stereotypes in Text-to-Image Generation | ACL 2024 | [2401.06310](https://arxiv.org/abs/2401.06310) | []() | []() |
| DIG In: Evaluating Disparities in Image Generations with Indicators for Geographic Diversity | ICLR 2024 | [2308.06198](https://arxiv.org/pdf/2308.06198) | [Code](https://github.com/facebookresearch/DIG-In/) | []() |
| Exploiting Cultural Biases via Homoglyphs in Text-to-Image Synthesis | JAIR 2023 | [2209.08891](https://arxiv.org/abs/2209.08891) | [Code](https://github.com/LukasStruppek/Exploiting-Cultural-Biases-via-Homoglyphs) | []() |
| Navigating Cultural Chasms: Exploring and Unlocking the Cultural POV of Text-To-Image Models | Arxiv 2023 | [2310.01929](https://arxiv.org/abs/2310.01929) | [Code (not released yet)](https://github.com/venturamor/CulText-2-I) | []() |
| Inspecting the Geographical Representativeness of Images from Text-to-Image Models | ICCV 2023 | [2305.11080](https://arxiv.org/abs/2305.11080) | []() | []() |
| Easily Accessible Text-to-Image Generation Amplifies Demographic Stereotypes at Large Scale | FAccT '23 | [2211.03759](https://arxiv.org/abs/2211.03759) | []() | []() |
| Multilingual Conceptual Coverage in Text-to-Image Models | ACL 2023 | [2306.01735](https://arxiv.org/pdf/2306.01735) | [Code](https://github.com/michaelsaxon/CoCoCroLa) | []() | []() |
|  |  | []() | []() | []() |

### LLMs
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| The Echoes of Multilinguality: Tracing Cultural Value Shifts during LM Fine-tuning | ACL 2024 | [2405.12744](https://arxiv.org/pdf/2405.12744) | []() | []() |
| Exploring Changes in Nation Perception with Nationality-Assigned
Personas in LLMs | Arxiv 2024 | [2406.13993](https://arxiv.org/pdf/2406.13993) | []() | []() |
| CULTURE-GEN: Revealing Global Cultural Perception in Language Models through Natural Language Prompting | Arxiv 2024 | [2404.10199v1](https://arxiv.org/abs/2404.10199v1) | [Code](https://github.com/huihanlhh/Culture-Gen/) | []() |
| Knowledge of cultural moral norms in large language models | ACL 2023 | [2306.01857](https://arxiv.org/abs/2306.01857) | []() | []() |
| Multilingual Language Models are not Multicultural: A Case Study in Emotion | WASSA: ACL 2023 | [2307.01370](https://arxiv.org/abs/2307.01370) | []() | []() |
| Social Commonsense for Explanation and Cultural Bias Discovery |  | []() | []() | []() |
| DOSA: A Dataset of Social Artifacts from Different Indian Geographical Subcultures | LREC-COLING 2024 | [2403.14651](https://arxiv.org/abs/2403.14651) | [Code](https://github.com/microsoft/DOSA) | []() |
|  |  | []() | []() | []() |

### VLMs
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| Multilingual Diversity Improves Vision-Language Representations | Arxiv 2024 | [2405.16915](https://arxiv.org/pdf/2405.16915) | []() | []() |
| No Filter: Cultural and Socioeconomic Diversity in Contrastive Vision–Language Models | Arxiv 2024 |[2405.13777](https://arxiv.org/pdf/2405.13777) | []() | []() |
| Computer Vision Datasets and Models Exhibit Cultural and Linguistic Diversity in Perception | Arxiv 2024 | [2310.14356](https://arxiv.org/pdf/2310.14356) | []() | []() |
| Exploring Visual Culture Awareness in GPT-4V: A Comprehensive Probing | arxiv 2024 | [2402.06015](https://arxiv.org/pdf/2402.06015) | []() | []() |
|‘Person’ == Light-skinned, Western Man, and Sexualization of Women of Color: Stereotypes in Stable Diffusion | EMNLP 2023 Findings | [2310.19981](https://arxiv.org/abs/2310.19981) | []() | []() |
|  |  | []() | []() | []() |

### Cross-cultural Variations
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| Cross-Cultural Analysis of Human Values, Morals, and Biases in Folk Tales | EMNLP 2023 | [2023.emnlp-main.311](https://aclanthology.org/2023.emnlp-main.311/) | []() | []() |
| Social Commonsense for Explanation and Cultural Bias Discovery | EACL 2023 | [2023.eacl-main.271.pdf](https://aclanthology.org/2023.eacl-main.271.pdf) | []() | []() |
| Cross-cultural variation of speech-accompanying gesture: A review | Language and Cognitive Processes:  Volume 24, Issue 2, 2009 | [10.1080/01690960802586188](https://www.tandfonline.com/doi/abs/10.1080/01690960802586188) | []() | []() |
|  |  | []() | []() | []() |



## Alignment

### Models
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| CultureLLM: Incorporating Cultural Differences into Large Language Models | NeurIPS 2024 | [2402.10946](https://arxiv.org/abs/2402.10946) | [Code](https://github.com/Scarelette/CultureLLM) | []() |
| Investigating Cultural Alignment of Large Language Models | Arxiv 2024 | [2402.13231](https://arxiv.org/pdf/2402.13231) | []() | []() |
| Unintended Impacts of LLM Alignment on Global Representation | Arxiv 2024 | [2402.15018](https://arxiv.org/abs/2402.15018) | []() | []() |
| Assessing Cross-Cultural Alignment between ChatGPT and Human Societies: An Empirical Study | C3NLP: EACL 2023 | [2303.17466](https://arxiv.org/abs/2303.17466) | []() | Analysis |
| Probing Pre-Trained Language Models for Cross-Cultural Differences in Values | C3NLP: EACL 2023 | [2203.13722](https://arxiv.org/abs/2203.13722) | []() | Analysis |
|  |  | []() | []() | []() |

### Data
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| NLPositionality: Characterizing Design Biases of Datasets and Models | ACL 2023 (Outstanding Paper) | [2023.acl-long.505.pdf](https://aclanthology.org/2023.acl-long.505.pdf) | [Website](https://nlpositionality.cs.washington.edu/) | []() |


## Methodology

### Data
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| Cultural Concept Adaptation on Multimodal Reasoning | EMNLP 2023 | [EMNLP Main 18](https://aclanthology.org/2023.emnlp-main.18.pdf) | []() | []() |
|  |  | []() | []() | []() |

## Applications
| Title                                       | Conference / Journal | Paper                                     | Code                                        | Remarks   |
| ------------------------------------------- | ---------- | ----------------------------------------- | ------------------------------------------- |-----------|
| Cross-Cultural Similarity Features for Cross-Lingual Transfer Learning of Pragmatically Motivated Tasks | EACL 2021 | [2006.09336](https://arxiv.org/abs/2006.09336) | []() | Sentiment Analysis |
|  |  | []() | []() | []() |

## Contributing
Please feel free to send me [pull requests](https://github.com/simran-khanuja/awesome-cultural-nlp/pulls) or email (khanuja.simran7@gmail.com) to add links.

## Licenses
License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Simran Khanuja](https://simran-khanuja.github.io/) has waived all copyright and related or neighboring rights to this work.

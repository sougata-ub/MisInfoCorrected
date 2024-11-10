# Integrating Argumentation and Hate-Speech-based Techniques for Countering Misinformation
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository shares the annotated **MisinfoCorrected** dataset with the hate speech-based counter-response strategies from the paper:

## [**Integrating Argumentation and Hate-Speech-based Techniques for Countering Misinformation**](https://aclanthology.org/2024.emnlp-main.622.pdf). 
[**Sougata Saha**](https://sougata-ub.github.io), [**Rohini Srihari**](https://www.acsu.buffalo.edu/~rohini/) 

Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing, pages 11109–11124. November 12-16, 2024

## Abstract
The proliferation of online misinformation presents a significant challenge, requiring scalable strategies for effective mitigation. While detection methods exist, current reactive approaches, like content flagging and banning, are short-term and insufficient. Additionally, advancements like large language models (LLMs) exacerbate the issue by enabling large-scale creation and dissemination of misinformation. Thus, sustainable, scalable solutions that encourage behavior change and broaden perspectives by persuading misinformants against their viewpoints or broadening their perspectives are needed. To this end, we propose persuasive LLM-based dialogue systems to tackle misinformation. However, challenges arise due to the lack of suitable datasets and formal frameworks for generating persuasive responses. Inspired by existing methods for countering online hate speech, we explore adapting counter-hate response strategies for misinformation. Since misinformation and hate speech often coexist despite differing intentions, we develop classifiers to identify and annotate response strategies from hate-speech counter-responses for use in misinformation scenarios. Human evaluations show a 91% agreement on the applicability of these strategies to misinformation. Next, as a scalable counter-misinformation solution, we create an LLM-based argument graph framework that generates persuasive responses, using the strategies as control codes to adjust the style and content. Human evaluations and case studies demonstrate that our framework generates expert-like responses and is 14% more engaging, 21% more natural, and 18% more factual than the best available alternatives.

### MisInfoCorrected Dataset
1. This repository shares the annotated **MisinfoCorrected** dataset with the hate speech-based counter-response strategies.
2. The dataset contains tweet IDs. You can get the corresponding tweet text for the IDs from the **MisinfoCorrect** repository: https://github.com/claws-lab/MisinfoCorrect

## Citation
If you are using this dataset then do cite: 
```bibtex
@inproceedings{saha-srihari-2024-integrating,
    title = "Integrating Argumentation and Hate-Speech-based Techniques for Countering Misinformation",
    author = "Saha, Sougata  and
      Srihari, Rohini",
    editor = "Al-Onaizan, Yaser  and
      Bansal, Mohit  and
      Chen, Yun-Nung",
    booktitle = "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.emnlp-main.622",
    pages = "11109--11124"}
```

# Integrating Argumentation and Hate-Speech-based Techniques for Countering Misinformation
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository shares the annotated **MisinfoCorrected** dataset with the hate speech-based counter response strategies from the paper:

## [**Integrating Argumentation and Hate-Speech-based Techniques for Countering Misinformation**](https://aclanthology.org/2023.acl-long.466.pdf). 
[**Sougata Saha**](https://sougata-ub.github.io), [**Rohini Srihari**](https://www.acsu.buffalo.edu/~rohini/) 

Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics. Volume 1: Long Papers, pages 8373–8388. July 9-14, 2023 (ACL 2023)

## Abstract
The proliferation of online misinformation presents a significant challenge, requiring scal- able strategies for effective mitigation. While detection methods exist, current reactive ap- proaches, like content flagging and banning, are short-term and insufficient. Additionally, ad- vancements like large language models (LLMs) exacerbate the issue by enabling large-scale creation and dissemination of misinformation. Thus, sustainable, scalable solutions that en- courage behavior change and broaden perspec- tives by persuading misinformants against their viewpoints or broadening their perspectives are needed. To this end, we propose persuasive LLM-based dialogue systems to tackle misin- formation. However, challenges arise due to the lack of suitable datasets and formal frameworks for generating persuasive responses. Inspired by existing methods for countering online hate speech, we explore adapting counter-hate re- sponse strategies for misinformation. Since misinformation and hate speech often coexist despite differing intentions, we develop classi- fiers to identify and annotate response strategies from hate-speech counter-responses for use in misinformation scenarios. Human evaluations show a 91% agreement on the applicability of these strategies to misinformation. Next, as a scalable counter-misinformation solution, we create an LLM-based argument graph frame- work that generates persuasive responses, using the strategies as control codes to adjust the style and content. Human evaluations and case stud- ies demonstrate that our framework generates expert-like responses and is 14% more engag- ing, 21% more natural, and 18% more factual than the best available alternatives.

### MisInfoCorrected Dataset
1. This repository shares the annotated **MisinfoCorrected** dataset with the hate speech-based counter response strategies.
2. The dataset contains tweet ids. You can get the corresponding tweet text for the ids from the **MisinfoCorrect** repository: https://github.com/claws-lab/MisinfoCorrect

## Citation
If you are using this dataset then do cite: 
```bibtex
@inproceedings{saha-srihari-2023-argu,
    title = "{A}rg{U}: A Controllable Factual Argument Generator",
    author = "Saha, Sougata  and
      Srihari, Rohini",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.466",
    pages = "8373--8388"
}
```

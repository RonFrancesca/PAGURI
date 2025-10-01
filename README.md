<div align="center">

# PAGURI: a user experience study of creative interaction with text-to-music models

<!-- <img width="700px" src="docs/new-generic-style-transfer-headline.svg"> -->
 
[Francesca Ronchini](https://www.linkedin.com/in/francesca-ronchini/), [Luca Comanducci](https://www.linkedin.com/in/lucacomanducci/), Gabriele Perego, [Fabio Antonacci](https://scholar.google.com/citations?user=9e2rt3gAAAAJ&hl=en&oi=ao)

<sup>1</sup> Dipartimento di Elettronica, Informazione e Bioingegneria - Politecnico di Milano<br>
    
[![MDPI Eletroncis](https://img.shields.io/badge/Eletronics-20799292-blue.svg)](https://www.mdpi.com/2079-9292/14/17/3379)

</div>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Abstract](#abstract)
- [Code](#code)
- [Acknowledge](#acknowledge)
- [Additional information](#additional-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Abstract
In recent years, text-to-music models have been the biggest breakthrough in automatic music generation. While they are unquestionably a showcase of technological progress, it is not clear yet how they can be realistically integrated into the artistic practice of musicians and music practitioners. This paper aims to address this question via Prompt Audio Generation User Research Investigation (PAGURI), a user experience study where we leverage recent text-to-music developments to study how musicians and practitioners interact with these systems, evaluating their satisfaction levels. We developed an online tool through which users can generate music samples and/or apply recently proposed personalization techniques, based on fine-tuning, to allow the text-to-music model to generate sounds closer to their needs and preferences. Using questionnaires, we analyzed how participants interacted with the proposed tool, to understand the effectiveness of text-to-music models in enhancing users' creativity. Results show that even if the audio samples generated and their quality may not always meet user expectations, the majority of the participants would incorporate the tool in their creative process. Furthermore, they provided insights into potential enhancements for the system and its integration into their music practice. 

![image](docs/figures/PAGURI_Logo.png)

## Code

The jupyter notebook **PAGURI_interface.ipynb** contains all the necessary code needed to run the PAGURI interface. Before running PAGURI, it is necessary to clone the current repo and install the requirements contained in requirements.txt

## Supplementary Material

Code and supplementary material containing the answers to all questions, feedback, and further details are available on the [accompanying website](https://ronfrancesca.github.io/PAGURI/). 

## Acknowledge
This code is heavely based on the following references : 

[Investigating Personalization Methods in Text to Music Generation Generation](https://arxiv.org/abs/2309.11140)

[DreamSound](https://zelaki.github.io/)

[AudioLDM](https://github.com/haoheliu/AudioLDM)

[Diffusers](https://github.com/huggingface/diffusers) 


## Additional information

For more details:
"[PAGURI: A User Experience Study of Creative Interaction with Text-to-Music Models](https://www.mdpi.com/2079-9292/14/17/3379)" - Electronics 2025, 14, 3379. https://doi.org/10.3390/electronics14173379

If you use code or comments from this work, please cite our paper:

```BibTex
@article{ronchini2024paguri,
    AUTHOR = {Ronchini, Francesca and Comanducci, Luca and Perego, Gabriele and Antonacci, Fabio},
    TITLE = {PAGURI: A User Experience Study of Creative Interaction with Text-to-Music Models},
    JOURNAL = {Electronics},
    VOLUME = {14},
    YEAR = {2025},
    NUMBER = {17},
    ARTICLE-NUMBER = {3379},
    ISSN = {2079-9292},
}
```


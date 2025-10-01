<div align="center">

# PAGURI: a user experience study of creative interaction with text-to-music models

<!-- <img width="700px" src="docs/new-generic-style-transfer-headline.svg"> -->
 
[Francesca Ronchini](https://www.linkedin.com/in/francesca-ronchini/)<sup>1</sup>, [Luca Comanducci](https://www.linkedin.com/in/lucacomanducci/), Gabriele Perego, [Fabio Antonacci](https://scholar.google.com/citations?user=9e2rt3gAAAAJ&hl=en&oi=ao)<sup>2</sup>

<sup>1</sup> Dipartimento di Elettronica, Informazione e Bioingegneria - Politecnico di Milano<br>
<sup>2</sup> Université de Lorraine, CNRS, Inria, Loria <br>
    
[![IEEEXplore](https://img.shields.io/badge/IEEEXplore-10445834-blue.svg)](https://ieeexplore.ieee.org/abstract/document/10445834)

</div>


[![MDPI - Eletronics](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://www.mdpi.com/2079-9292/14/17/3379) *Francesca Ronchini, Luca Comanducci, Gabriele Perego, Fabio Antonacci*

This repository contains the implementation of the paper **_PAGURI: a user experience study of creative interaction with text-to-music models_**, Electronics 2025, 14, 3379.

</div>


### Abstract
In recent years, text-to-music models have been the biggest breakthrough in automatic music generation. While they are unquestionably a showcase of technological progress, it is not clear yet how they can be realistically integrated into the artistic practice of musicians and music practitioners. This paper aims to address this question via Prompt Audio Generation User Research Investigation (PAGURI), a user experience study where we leverage recent text-to-music developments to study how musicians and practitioners interact with these systems, evaluating their satisfaction levels. We developed an online tool through which users can generate music samples and/or apply recently proposed personalization techniques, based on fine-tuning, to allow the text-to-music model to generate sounds closer to their needs and preferences. Using questionnaires, we analyzed how participants interacted with the proposed tool, to understand the effectiveness of text-to-music models in enhancing users' creativity. Results show that even if the audio samples generated and their quality may not always meet user expectations, the majority of the participants would incorporate the tool in their creative process. Furthermore, they provided insights into potential enhancements for the system and its integration into their music practice. 

![image](docs/figures/PAGURI_Logo.png)


### Code

The jupyter notebook **PAGURI_interface.ipynb** contains all the necessary code needed to run the PAGURI interface. Before running PAGURI, it is necessary to clone the current repo and install the requirements contained in requirements.txt

## ACKNOWLEDGMENTS
This code is heavely based on the following references : 

[Investigating Personalization Methods in Text to Music Generation Generation](https://arxiv.org/abs/2309.11140)

[DreamSound](https://zelaki.github.io/)

[AudioLDM](https://github.com/haoheliu/AudioLDM)

[Diffusers](https://github.com/huggingface/diffusers) 

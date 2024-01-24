Title: a foundation model for science publishing
Subtitle: the implications for scientific publishers? November 17
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/a-foundation-model-for-science-publishing
---
I’ve got three draft newsletters on the boil: 

**One** reporting on the success of the Deviant Art artists’ rebellion against the website’s plan to work with Stability, and what it might say about the future of the copyright uncertainty

 **Two,** reporting on the recent Asian Pacific Copyright Association meeting in Singapore, and some straws in the wind for copyright developments, and 

**Three,** a less newsy post on the practice of “model patching”, how corporate model providers use various processes to filter the output of their foundation models to be Safe For Work, less biased, or to block copyright violations that the models produce pre-filtering.

Subscribe if you want those when I get to them.

Subscribe

But I think this latest development trumps these, given its potential impact on STM publishers. 

### Meta has just open-sourced [Galactica](https://galactica.org/), a large language model trained on scientific papers & data

 **The good news** here is that the creators of the model have been very careful about their data, and validated the idea that high quality text and content will lead to better performing models. They also _seem at first sight_ to have been careful about about using material that they have permission to access and mine, under various open science licenses.

They have spent energy combining text articles and scientific databases. They have used tags within papers to identify citations, DNA sequences, math equations and so on. They even have tokens to highlight step-by-step reasoning, as the LLMs need help with this sort of thing. They seem to have used citation counts and impact factors in helping to filter and weight the text inputs, though it is not clear to me how that works.

 **The bad news (for publishers)** is that the model is getting good at things that publishers traditionally do, at least in works which synthesize and report on research, as opposed to publishing. Here is the front page of the model, advertising its capabilities:

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F6dfdaf0f-2051-4601-a63e-2f9a5db0a74d_2762x1086.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F6dfdaf0f-2051-4601-a63e-2f9a5db0a74d_2762x1086.png)

The starting point of open science was to allow harvesting of data from papers, and the creation of databases that gathered genomic information, protein information, etc and allowed these to be co-related. But now, with the language capabilities of the LLMs, this process is supercharged to include summarization, question-answering, etc. 

Here’s a good Twitter thread that sets out some of the reasons this LLM is a bit different:

[![Twitter avatar for @DrJimFan](https://substackcdn.com/image/twitter_name/w_96/DrJimFan.jpg)Jim (Linxi) Fan @DrJimFanToday a 120B model called “Galactica” is open-sourced by @paperswithcode. It’s capable of writing math notations, citations, code, chemical formula, DNA, etc. Here’s why I think Galactica is a huge milestone in open foundation models, scientific automation, and responsible AI: 🧵 ![Image](https://substackcdn.com/image/fetch/w_600,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fpbs.substack.com%2Fmedia%2FFhpY_jHVsAAlMXP.jpg)](https://twitter.com/DrJimFan/status/1592683269866549249)[12:57 AM ∙ Nov 16, 2022

* * *

1,671Likes338Retweets](https://twitter.com/DrJimFan/status/1592683269866549249)

The backlash has been pretty instant, but so far more from AI ethics people than data scientists that I can see. The critics jump on the well-known capabilities of LLMs to hallucinate (yes, that is the technical term), and prompt Galactica to generate lots of amusing nonsense, which it seems to do pretty easily. They then use this to cast doubt on the capabilities of LLMs to actually capture knowledge. 

But I’m not so sure how strong that line is in the medium or longer term, though I think it is important to register for wider understanding the nature of LLM training (LLMs copy expression, not facts and ideas). The data scientists are fully aware of this issue, and deal with it in the paper as follows:

>  **Language Models as Knowledge Bases** Storing information in weights is more unreliable in the sense models may blend information together, **hallucination** , but it is more "pliable" in the sense it can associate information through the representation space, **association**. Despite hallucination risks, there is evidence large language models can act as implicit knowledge bases with sufficient capacity (Petroni et al., 2019). They perform well on knowledge-intensive tasks such as general knowledge (TriviaQA) and specialist knowledge (MMLU) without an external retrieval mechanism (Brown et al., 2020; Hendrycks et al., 2020). 
> 
> The question of how to update network knowledge remains an active research question (Scialom et al., 2022; Mitchell et al., 2022). Likewise, the question of how to improve the reliability of generation is an active question (Gao et al., 2022). Despite these limitations, today’s large models will become cheaper with experience (Hirschmann, 1964), and so a growing proportion of scientific knowledge will enter weight memory as training and re-training costs fall. In this work we perform probes to investigate Galactica’s depth of knowledge, and show that the ability to absorb scientific knowledge improves smoothly with scale.[1](https://aicopyright.substack.com/p/a-foundation-model-for-science-publishing#footnote-1-85036282)

The model is open sourced. **STM Publishers had better be all over this.** This initial release may be a long way off being a useful system, but I’m not sure we can safely bet that such models won’t eventually be able to handle “scientific knowledge”, whether from within the language model, or by combining and blending language models with more traditional knowledge management and expert system techniques. At the very least, this release shows the potential of that approach.

 _And it was brought to you by Facebook!_

Subscribe

[1](https://aicopyright.substack.com/p/a-foundation-model-for-science-publishing#footnote-anchor-1-85036282)

Taylor, Ross, Marcin Kardas, and Guillem Cucurull. “Galactica: A Large Language Model for Science.” Papers with Code, November 15, 2022. https://galactica.org/static/paper.pdf.

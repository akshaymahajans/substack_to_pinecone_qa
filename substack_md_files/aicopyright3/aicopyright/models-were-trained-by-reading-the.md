Title: “Models were trained by reading the internet"
Subtitle: Not “reading”, and not really “the internet” - models were trained by copying publisher content - where did Google get 4m books to train Chinchilla?
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/models-were-trained-by-reading-the
---
The cliché that Large Language Models were trained by “reading the internet” is firmly established, and highly problematic. Here are three problems:

 **First, there’s the easy acceptance of the metaphor that machines “read”.** This is one link in the chain of anthropomorphic metaphor, that has LLMs “reading”, then “learning” and “knowing” and being, well, intelligent. Of course this is a useful shorthand if you are engaged in training Large Language Models, and want to talk to your colleagues about how their performance has increased against certain benchmarks. But if you are making policy or copyright law judgements based on this metaphor, that’s another thing entirely. 

And while I’ll grant that there is some sort of generalization going on in the large language models, this metaphor obscures more than reveals. Among the problems here is the unseemly rush to assume that performance on benchmarks (like theory of mind tests, or arithmetic) is based on actual capacities, and not leakage from the training data. On one point everyone talking about LLMs agrees — we need more research to understand what exactly is going on inside them, so as to learn in what ways they generalize and in what ways they are just statistical predictions.

![](https://substackcdn.com/image/fetch/w_720,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F6b3ff302-97d3-41b1-abad-920e99e6019e_1179x2556.png)![](https://substackcdn.com/image/fetch/w_720,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F5a5e3d76-348e-4285-8558-750f1aeeccda_1179x2556.png)

Discussing this very point with the Brazilian Books Chamber, subtitled in Portuguese

 **Secondly, the “LLMs read the internet” makes people think of LLM-training materials as being nasty user-generated content in forums like Reddit.** Many commentators (not the researchers) blame the tendency for the models to hallucinate and say harmful things on the fact that they have read lots of low-quality internet content. In fact from even before transformers, NLP neural net researchers have been very keen to get as high-quality text as they possibly can, and they have worked very hard to avoid low quality content. Why? Because low-quality content means worse-performing models. Also, to remind you, even models trained on high quality content get lots of hallucinations if they are not RLHF-ed and fine-tuned to within an inch of their life. That’s just how the models work. Hallucinations are good outcomes for models trained only to be plausible. And remember [the infamous Galactica](https://aicopyright.substack.com/p/a-foundation-model-for-science-publishing), trained by Facebook _only_ on high quality scientific papers? It was withdrawn after only a few days because it said lots of nasty stuff, when prompted by the troublemaking public.

 **Thirdly, and connected to the second point, this tired “reading the internet” metaphor obscures the fact that content from publishers has been essential to the training of the existing models.** The “content from publishers” I mean includes caches of pirated ebooks, as well as datasets like all of Google Books which are not available to anyone just “reading the internet”. When the good folks at Eleuther.AI released The Pile dataset (later used by Facebook, Microsoft and nVidia to train models), they justified including Shawn Pressler’s scrape of the Bibliotik cache of 196,640 pirated ebooks by saying “We included Bibliotik because books are invaluable for long-range context modeling research and coherent storytelling.”

In fact it is probably more accurate to say “Large Language Models were trained on books, journal articles and news articles, that is to say, publisher content.”

Subscribe

### Filtering the internet to get the good stuff

[Different analyses of the CommonCrawl webscrape datasets](https://www.washingtonpost.com/technology/interactive/2023/ai-chatbot-learning/) show that the top domains are dominated by publishers, including news organizations. Preprint servers and services like the PhilPaper archive of philosophy papers have been important sources. Many of these websites in fact do not allow copying of material for AI training. Only Public Library of Science is completely open to all forms of text and data-mining.

When people talk about models being trained by reading Reddit, they are mangling info on the way Reddit was _actually_ used by OpenAI in its GPT training. Back in 2018-9 OpenAI researchers knew[1](https://aicopyright.substack.com/p/models-were-trained-by-reading-the#footnote-1-135855913) that webscrapes included much content that was “mostly unintelligible”. For GPT-2, researchers filtered their webscrape training data by using Reddit popularity as a kind of quality test. According to [James Vincent](https://www.theverge.com/2019/2/14/18224704/ai-machine-learning-language-models-read-write-openai-gpt2) “They collected the most upvoted links from the site (some 8 million in the end) and then scraped their text.” The filtered dataset was called WebText.

When the time came round to train GPT-3, OpenAI was able to build on this work, to handle the challenge of creating a quality filter for the one trillion tokens now in the CommonCrawl dataset. In fact they trained an entirely different classification model just to recognize high quality data in the soup of low quality text that comes from “ ~~reading~~ scraping the internet”. What were the examples of high quality data used to train the model? From the GPT-3 paper:

 _“For the positive examples, we used **a collection of curated datasets such as WebText, Wikiedia [sic], and** **our web books corpus** as the positive examples, and for the negative examples, we used unfiltered Common Crawl.”_[2](https://aicopyright.substack.com/p/models-were-trained-by-reading-the#footnote-2-135855913)

 **So they used books to create filters of the internet to get more book-like content. They used this filter to go from 1000b CommonCrawl tokens down to the 180b they actually used in training GPT-3.**

And then, as even that wasn’t likely to be good enough, they added to the training set “ _our_ web books corpus” as well as the previously filtered WebText and Wikipedia to get to 300b tokens.

### Massive increases in amounts of data used to train models - but the amount of publisher data used keeps pace! 

The race to scale zoomed past GPT-3 pretty quickly, but only in terms of increasing the number of parameters of the model. The massive PaLM model, from Google Research, announced on April 4, 2022, set a record with 540b parameters. But just a few days earlier, March 29th, the _other_ Google team, over at Deep Mind in London, published a paper claiming that additional resources for training models should be spent on increasing the amount of text used to train the models. Chinchilla was trained on some 1.4 trillion tokens of data, but using only 70b parameters, so less costly to train, and also cheaper to fine tune and actually run. _(I wonder how those two papers coming out so close together played out internally…)_

Of those 1.4 trillion tokens used in training Chinchilla, 420b are from a dataset Google calls “Books”. They even tell us that the total Books dataset has 4m works in it.[3](https://aicopyright.substack.com/p/models-were-trained-by-reading-the#footnote-3-135855913) For comparison, the British Library holds 14 million books (by law they get free copies of every book published in the UK, and they’ve been around for awhile!) So what could possibly be the source of four million works copied by Google to train their models? 

_**It can only be Google Books.** _

I’ve created an interactive graphic to track the growth of the amounts of text used to train LLMs, from the 10b tokens that trained BERT (Wikipedia and 11,000 Smashwords novels) to the 1.4 trillion tokens used to train Chinchilla. It doesn’t play well with Substack, so I’ll have to ask you to [have a look on Flourish here:](https://public.flourish.studio/story/1997906/)

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F62f72a9d-37bf-4a2d-9362-4f337ae62cbd_1656x1488.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F62f72a9d-37bf-4a2d-9362-4f337ae62cbd_1656x1488.png)

But here’s the TL;DR. Forty percent of the data used to train Chinchilla does not come from internet sources, but from publisher sources, including those not freely available to anyone surfing the internet. And as we’ve seen above, even the data that is really “scraped from the web” overwhelmingly comes from publisher sources… and the AI companies have spent a lot of time and energy to filter those webscrapes to get the good publisher content.

The latest LLM release that I’m tracking, as of this writing, is the open-sourced Llama 2 from Meta, which is only 70b parameters large but is trained on 2b tokens. By mid-2023 however, with copyright holders now citing specific datasets in their lawsuites against AI companies, no one dares to share any detail on their datasets. Where did Meta get 2b tokens of text? _“A new mix of publicly available online data”._ OK… that’s sounding pretty disingenuous by now…

So next time someone says “Chat-GPT was trained by reading the internet”, remind them that it is better described as having been trained on books and high quality publisher content.

[Share](https://aicopyright.substack.com/p/models-were-trained-by-reading-the?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/models-were-trained-by-reading-the#footnote-anchor-1-135855913)

Radford et al, “Language Models are Unsupervised Multitask Learners” **** https://paperswithcode.com/paper/language-models-are-unsupervised-multitask

[2](https://aicopyright.substack.com/p/models-were-trained-by-reading-the#footnote-anchor-2-135855913)

Brown, et al, “Language Models are Few-Shot Learners”, https://arxiv.org/abs/2005.14165

[3](https://aicopyright.substack.com/p/models-were-trained-by-reading-the#footnote-anchor-3-135855913)

Hoffman, et al, “Training Compute-Optimal Large Language Models”, https://arxiv.org/abs/2203.15556  


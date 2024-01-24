Title: Whether you're an undergraduate doing research, or a fan of the Nick Stone novels, or indeed a hungry AI...
Subtitle: Pirates rush in where publishers weren't asked to tread! a special report November 29
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing
---
_There is a serious lack of clarity in the AI literature about the text corpora used to train the large language models. Why is that? Does it have something to do with the fact that key models rely not only on open access content, and material freely available but scraped in violation of license conditions, but also book content that is clearly from pirated sources? I mean, it’s at least a_ little _embarrassing, no?_

This special midweek update comes courtesy of my very late discovery of the[ lesswrong.com ](https://www.lesswrong.com)website, one of the haunts of the effective altruists and source of some extremely good writing on AI subjects. Over the last two months I’ve been trying to gather information on the text corpora used to train the biggest models, with some difficulty. On lesswrong.com I meet [nostalgebraist,](https://www.lesswrong.com/users/nostalgebraist) in search of the same information. Except they are looking for that information in order to answer the question of whether there is enough good text material _**in the world**_ to train AI language models to their fullest potential. Much of this comes from their somewhat technical but very clear lesswrong article [chinchilla's wild implications](https://www.lesswrong.com/posts/6Fpvch8RR29qLEWNH/chinchilla-s-wild-implications). 

But first, a short excursion into AI scaling laws. (You can skip this section if you prefer.) For a much more complete and very clear explanation of this subject, see — also from lesswrong — [New Scaling Laws for Large Language Models](https://www.lesswrong.com/posts/midXmMb2Xg37F2Kgn/new-scaling-laws-for-large-language-models), by 1a3orn.[1](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-1-87330111)

### How to best grow your AI model?

Growth in the size of the latest AI models is driving AI’s incredible development, particularly the foundation models. There are three variables involved here: the amount of computer processing you have access to, the size of the model (number of parameters), and the amount of data (number of tokens)[2](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-2-87330111) you feed it.

In practice, most people start with a fixed amount of computing time budgeted to train and build a model. In the industry they call this the “compute”. 

The more computing resources you devote to the size and sensitivity of the model, the less data you can ingest. The more data you ingest, the fewer parameters you can set, the smaller the model. Clearly it is important to understand which trade-off between these two variables will give you the best result. (Of course it’s also interesting to know how much better your results will be by adding “compute”, by increasing the size of the pie, but let’s leave that aside for a minute). 

A recent paper — [the Chinchilla paper](https://doi.org/10.48550/arXiv.2203.15556) — has upended the previous understanding of the optimal relationship of model size and data size. Whereas the 2020 rules of scale strongly emphasised size of model (number of parameters), the new understanding shows more benefit to adding data. (See Hoffmann, Jordan, et al. _Training Compute-Optimal Large Language Models_. arXiv, 29 Mar. 2022).

### Just add data

In his [“chinchilla’s wild implications”](https://www.lesswrong.com/posts/6Fpvch8RR29qLEWNH/chinchilla-s-wild-implications) posting nostalgebraist sets it out: 

> _Data, not size, is the currently active constraint on language modeling performance. Current returns to additional data are immense, and current returns to additional model size are miniscule; indeed, most recent landmark models are wastefully big._
> 
>  _If we can leverage enough data, there is no reason to train ~500B param models, much less 1T or larger models._
> 
>  _If we have to train models at these large sizes, it will mean we have encountered a barrier to exploitation of data scaling, which would be a great loss relative to what would otherwise be possible._

So if data is really where we have the most leverage, asks nostalgebraist, why don’t AI researchers tell us more about the data they use? 

> _The data collection sections of LM papers tend to be vague and slapdash, often failing to answer basic questions like "where did you scrape these webpages from?" or "how many more could you scrape, if you wanted to?"_

 _ **I have a theory about that…**_

### So what do we know about the corpora used to train LLMs?

I’m still looking for the best way to compile what we know of the datasets used to train LLMs. But here are some of the leading sources:

  *  **Wikipedia** \- its open access license would seem to allow crawling for training data. Wikipedia is also very useful for its knowledge graph, the sum of the “see also’s” that represent relationships of different ideas and things. There are about **3b tokens** in English wikipedia.

  *  **web crawls** \- these include much copyrighted information, and may or may not include restrictions in their licenses or user agreements. One key subset of the always updated Common Crawl data [(also mentioned in the October 8th newsletter) ](https://aicopyright.substack.com/p/how-big-tech-is-exploiting-existing)is CC-News, which contains something like 63 million English news articles crawled between September 2016 and February 2019. Most of the crawled datasets yield around **100-500b tokens.**

  *  **open access preprint and abstract servers -** The recently released Galactica was trained mostly on these, as well as databases of scientific information.[3](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-3-87330111) The preprints and abstracts add up to around **88b of 106b total tokens.**

  * **computer code repositories** \- Github is the big fish here. I quote nostalgebraist: “We've more-or-less exhausted Github. It's been scraped a few times with different kinds of filtering, which yielded broadly similar data sizes”, that is around **3-500 billion tokens.**




Which leads us to books, more than 50% of the composition of the corpora used to train the biggest models. Here are some of the key datasets:

  *  **BooksCorpus** \- one of the key early datasets used since 2016, created by scraping and copying some 11,000 novels found on the Smashwords website

  *  **Books1 -** used by OpenAI, including BooksCorpus, and other unnamed sources

  *  **Books2** \- used by OpenAI to train GPT-3. OpenAI has never revealed the source of this dataset, despite facing the persistent rumour that it is an upload of notorious pirate site SciHub. Around **50b tokens.**

  *  **Books3** – (part of a broader collection called The Pile), which is “[all of Bibliotik](https://twitter.com/theshawwn/status/1320282149329784833?lang=en).” It contains 196,640 full-text books, amounting to **27B tokens**. What is Bibliotik? A notorious pirated collection. According to one torrent guide, “Whether you're an undergraduate doing research or just looking for an obscure franchise like the Nick Stone series, **Bibliotik** is bound to have what you need.”[4](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-4-87330111) We know that ISBNs are part of the dataset.

  *  **MassiveText: books –** a dataset used by Google to train its Gopher models, Says nostalgebraist, **** “…a mysterious subset called "books" has **560B tokens**. That's a lot more than the Pile has! Are these all the books? In . . . the world? In . . . Google books? Who even knows?”

  *  **PaLM: books** \- another Google dataset, or another version of the same dataset, at around **390b tokens,** used to train its biggest model, not publicly accessible. Says nostalgebraist, “Why is the GLaM/PaLM number so much smaller than the MassiveText number? Is it a tokenization thing? Both of these datasets were made by Google, so it's not like the Gopher authors have special access to some secret trove of forbidden books (I assume??).”




Nostalgebraist is concerned to understand how much more text is available to train LLMs. He reckons we would be getting much better results if we could train models on 9 trillion tokens, not the paltry 1 trillion we seem to be getting close to being able to cobble together from webscrapes, books and other corpora. 

I hope nostalgebraist will allow me to focus more on the copyright status of these corpora. 

Already in 2016 questions were being asked about the ethics and legality of using BooksCorpus.[5](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-5-87330111) A 2021 audit of this dataset concluded __ “we found that many books contained copyright claims that, based on a plain language interpretation, should have prevented their distribution in the form of a free machine learning dataset.”[6](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-6-87330111)

As far as I know, no one has raised an alarm bell about the use of Bibliotik to train LLMs. _**RING RING RING.**_ Also I hadn’t yet seen as clear a suggestion that the Google Books corpus is being used to train at least Google’s models.

Some concluding questions:

  * How would the use of flagrantly infringing content to train text models affect the fair use argument regarding training data? 

  * The “chinchilla finding” (from Google) seems to suggest that much more text is required to progress LLMs further. But the Galactica team (from Facebook) claims even better results from a much smaller but higher quality dataset, and some tweaks to the software architecture. Which approach will prove most effective? 

  * If Google or Meta were to approach publishers, or their collective management organisations, with a licensing proposition, how many more higher quality tokens could be added to these piles of training data, enriched with good metadata? 




_**The fact that the LLMs are trained on copyright content, including content copied from flagrant violators and pirates, has not attracted as much attention as the use without permission of copyrighted images to train image generators.**_ _**“In the style of…” seems to work as well in LLM prompts as in image prompts, but the results are a little less obvious. Still, considering that GPT-3 can be so easily used “behind the scenes” for so many use cases, it is arguably going to be much more disruptive. Or even harmful?**_

Subscribe

[1](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-anchor-1-87330111)

“The name was randomly chosen. Specifically, I randomly generated ten 5-character alphanumeric strings and chose the one I liked the most.” From 1a3orn.com. I don’t have an explanation for nostalgebraist’s pen name.

[2](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-anchor-2-87330111)

Language models don’t know what “words” are, they are trained on tokens, which are bits of text, so words or parts of words but might also include white spaces and punctuation. Open AI says the ratio of tokens to words in the data they used to train GPT-3 is around 0.75 to 1, but different systems of tokenization of a text are one part of the art and science of model training.

[3](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-anchor-3-87330111)

https://galactica.org/static/paper.pdf

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F0572abd7-f1aa-4fc4-8651-623742b6926a_952x628.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F0572abd7-f1aa-4fc4-8651-623742b6926a_952x628.png)

[4](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-anchor-4-87330111)

https://vpnoverview.com/privacy/downloading/best-torrent-sites/

[5](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-anchor-5-87330111)

Richard Lea, “Google swallows 11,000 novels to improve AI's conversation”, _The Guardian,_ https://perma.cc/LG94-ZXZA

[6](https://aicopyright.substack.com/p/whether-youre-an-undergraduate-doing#footnote-anchor-6-87330111)

Bandy, Jack, and Nicholas Vincent. “Addressing ‘Documentation Debt’ in Machine Learning: A Retrospective Datasheet for BookCorpus,” November 11, 2021. <https://openreview.net/forum?id=Qd_eU1wvJeu>, p. 9

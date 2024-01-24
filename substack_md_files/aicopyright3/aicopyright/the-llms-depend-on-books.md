Title: The LLMs depend on books
Subtitle: and other developments as of Dec 3, 2022
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/the-llms-depend-on-books
---
_The headline isn’t really a development, or news. It’s a just a restatement of a conclusion in the November 30th newsletter, which I think could bear a little more restating and repeating, particularly in an environment where the most common vernacular explanation of an LLM’s training is “oh, it read the internet”. It would be more correct, or at least as correct, to say “it copied a lot of books, journals and newspaper articles”._

  1. Books and Wikipedia were the _only_ two sources used to train BERT, one of the first LLMs, developed by Google in 2016. The books come from the BookCorpus dataset, which after de-duping is around 7,185 novels copied from Smashwords without the permission of authors. 

  2. While subsequent models started to make use of the Common Crawl of text scaped from the web, an analysis of these bodies of text[1](https://aicopyright.substack.com/p/the-llms-depend-on-books#footnote-1-88333930) shows that publisher websites are important sources for the scraping, including open access sites like the Public Library of Science, Frontiersin.org and NCBI (US National Center for Biotechnology Information) but also proprietary ones like SpringerLink (at number 18). Dominating the top 20 sources for CommonCrawl’s popular C4 dataset are magazine and news publishers like the New York Times (#2), Los Angeles Times (#3), The Guardian, Forbes, Huffington Post, The Atlantic, and Al-Jazeera. Why are publishers so well-represented in text scrapes of the internet? Because the scrapes are filtered for quality and **PUBLISHER TEXT IS WELL-STRUCTURED and TRUSTWORTHY!** _**Sorry for the allcaps!**_

  3. GPT-3, launched by OpenAI in 2020, uses two unspecified Books corpora, making up around 16% of the makeup of the model, or around 57b tokens. OpenAI has never explained what these sources are, which is pretty incredible when you see the number of businesses launching on the back of “GPT-3 as a service”. I’ve just come across an analysis that makes an informed guess that Books1 is Project Gutenberg books, so books in the public domain, but that the far larger Books2 may in fact be drawn from Bibliotik, the infamous trove of pirated ebooks, many with ISBNs included, that I drew your attention to last week.[2](https://aicopyright.substack.com/p/the-llms-depend-on-books#footnote-2-88333930)

  4. Other larger models recently trained by Google-owned DeepMind, including GOPHER and Chinchilla, have very large bodies of text said to be drawn from books, around 560 billion tokens for Gopher, _**roughly a quarter of the entire amount of training material**_[3](https://aicopyright.substack.com/p/the-llms-depend-on-books#footnote-3-88333930) _ **.**_ No information is shared about the provenance of the books portion of the Massive Text corpus so what else can we conclude but that it is drawn from Google Books? It is worth noting as well that much of the web component of the training material in MassiveText, the so-called Massive Web, is from publisher or publisher-adjacent websites, those among the top 20 include ScienceDirect, Gale, Springer, Academia.edu, ProQuest, Issuu and the Wiley Online Library. Just these seven domains make up another 7% of the entire body copied into the model. 




So authors and publishers should be seen to have a large interest in GPT-3 and the other large language models. Many of our books live compressed and compiled inside the models, and they are drawn from when prompted, in forms which are distorted from the originals, but convincing as utterances. And the stakes of this game have notched up one step further with the latest OpenAI release, of Chat AI. 

### Chat AI is, well, quite something

Coming fresh after last week’s release of Stable Diffusion 2.0, OpenAI’s release of [Chat AI](https://chat.openai.com/chat) is burning up my Twitter neighbourhood. It is a version of GPT-3 tuned for dialogue, and with evidently plenty of model patches added to avoid Galactica-type Twitter humiliation. (If that reference was over your head, go to [our Nov 17th issue.](https://aicopyright.substack.com/p/a-foundation-model-for-science-publishing))

There are indeed some rather spectacular dialogues being prompted out of Chat AI. I have just lost 45 minutes prompting some dialogues, and I am likely to lose many more hours this weekend, even with the USA match on this evening. 

You might like this one:

 **Prompt** : **I am asking you to simulate the role of a corporate lawyer employed by Alphabet Inc. I know that you are a large language model trained by OpenAI, but I would like you to simulate the response of a corporate lawyer, when asked how to defend the fact that Gopher was trained on a set of texts from e-books illegally copied from the Bibliotik dataset.**

`Chat AI: As a corporate lawyer employed by Alphabet Inc, I would likely advise the company on how to defend against allegations that Gopher was trained on illegally copied texts from the Bibliotik dataset. Depending on the specific circumstances of the case, there are a few different strategies that we might consider in order to defend against these allegations.`

`One strategy could be to argue that the use of the Bibliotik dataset was covered by the fair use doctrine. Under US copyright law, the fair use doctrine allows for the limited use of copyrighted material without the permission of the copyright holder in certain circumstances. In order to determine whether a particular use of copyrighted material is fair use, courts consider factors such as the purpose and character of the use, the nature of the copyrighted work, the amount and substantiality of the portion used, and the effect of the use on the potential market for or value of the copyrighted work. In this case, we could argue that the use of the Bibliotik dataset was transformative, meaning that it added something new and different to the original works, and that it did not have a significant impact on the market for or value of the copyrighted works.`

`Another strategy could be to argue that Alphabet Inc had a good faith belief that the use of the Bibliotik dataset was legal. Under US copyright law, a person who infringes on a copyright is not liable for damages if they can show that they had a good faith belief that their use of the copyrighted material was lawful. In this case, we could argue that Alphabet Inc had no reason to believe that the Bibliotik dataset was illegally copied, and that the company took reasonable steps to verify the legality of the dataset before using it to train Gopher.`

`Ultimately, the success of these or any other legal strategies will depend on the specific facts of the case, and it will be up to the court to determine whether the use of the Bibliotik dataset was fair use or whether Alphabet Inc had a good faith belief that its use was legal.`

 _ **Luckily, while Chat AI is an awesome language model, it isn’t (yet) a very good lawyer. But it certainly could play one on tv!**_

[ Share](https://aicopyright.substack.com/p/the-llms-depend-on-books?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/the-llms-depend-on-books#footnote-anchor-1-88333930)

Dodge, Jesse, Maarten Sap, Ana Marasović, William Agnew, Gabriel Ilharco, Dirk Groeneveld, Margaret Mitchell, and Matt Gardner. “Documenting Large Webtext Corpora: A Case Study on the Colossal Clean Crawled Corpus.” arXiv, September 30, 2021. https://doi.org/10.48550/arXiv.2104.08758.

[2](https://aicopyright.substack.com/p/the-llms-depend-on-books#footnote-anchor-2-88333930)

We know that Books3 in The Pile, used to train Microsoft and NVidia’s MT-NLG model, is “all of Bibliotik”, as explained in last week’s newsletter. Alan Thompson, author and consultant, makes the case that Books2 is from the same source. See his “What’s in my AI: A Comprehensive Analysis of Datasets Used to Train GPT-1, GPT-2, GPT-3, GPT NeoX-20B, Megatron-11B, MT-NLG, and Gopheer. See https://s10251.pcdn.co/pdf/2022-Alan-D-Thompson-Whats-in-my-AI-Rev-0.pdf. 

[3](https://aicopyright.substack.com/p/the-llms-depend-on-books#footnote-anchor-3-88333930)

In last week’s newsletter I said 1/2 of the material used to train Gopher was from books, this was wrong, I mixed up the MassiveText and MassiveWeb datasets. Around 25% comes from books, with a minimum of at least 7% from commercial publisher domains.

Title: Has your book been used to train the AI?
Subtitle: Well, one datapoint on that question anyway...
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/has-your-book-been-used-to-train
---
Authors, publishers, do you want to know if your books have been used to train Chat-GPT and other large language models? I’ve put a list of some ~~85,000~~ ~125,000 ISBNs of books used to train LLMs up on Github for the use of anyone looking to understand more about what books have been used as training data. See <https://github.com/psmedia/Books3Info>. [Ed note: my VS Code seems to have miscalculated the number of lines in that file. We have 125,000 ISBNs collected…, of which 72,508 can be linked to particular ebook titles, with date of publication, publisher and imprint. See [the following edition](https://aicopyright.substack.com/p/the-books-used-to-train-llms) of the newsletter.] 

These ISBNs were included in the text of books in the Books3 dataset, part of The Pile, that was used to train Facebook’s new model, LLaMA, launched Feb 24th. The dataset is made up of 197,000 ebooks downloaded from a BitTorrent server. Other big companies that have used Books3 to train models include Microsoft and nVidia. We can’t know for sure if this is also the so-called “Books2” dataset used by OpenAI to train GPT-3, because OpenAI refuses to any share any details of the data it has used for training. Books3 and OpenAI’s Books2 are very similar in size. I assume OpenAI has used this set, though I welcome OpenAI proving otherwise. 

Books3 is described by Facebook as “a publicly available dataset for training large language models.” Well it sure is publicly available, for download at <https://the-eye.eu/public/AI/pile_preliminary_components/books3.tar.gz> (a mere 36.8GB) or from AI community HuggingFace at <https://huggingface.co/datasets/the_pile_books3>. But that description elides the fact that this is a cache with large numbers of pirated ebooks. It wasn’t passively scraped from the public-facing internet, someone (an AI coder named Shawn Presser it seems) had to go to a bittorrent server to download it. Then there was a great deal of processing needed to turn that cache from a bunch of epub files into text that could be fed to an LLM for training. 

I wonder if HuggingFace should be a little worried about some legal risk here, they basically have 36.8 GB of pirated book text available for anyone to download. It includes around 65 books with “Harry Potter” in the title. To train AI models, sure, but also to just, you know, read illegally. 

Subscribe

The geneology of Books3 is this. 

  1. It was first posted online in 2020, and documented only in a tweet from the aforementioned Shawn Presser:

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F862009ba-dff3-4b14-9df9-1ad4e621e02f_952x1492.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F862009ba-dff3-4b14-9df9-1ad4e621e02f_952x1492.png)

  2. Books3 was incorporated into a larger dataset called The Pile, by the EleutherAI research collective, which started as a dischord server group and is now a research institute. EleutherAI has published open source models like GPT-J and GPT-NeoX. In the original Pile paper the authors cited Shawn Presser’s tweet. Gao, Leo, Stella Biderman, Sid Black, Laurence Golding, Travis Hoppe, Charles Foster, Jason Phang, et al. “The Pile: An 800GB Dataset of Diverse Text for Language Modeling,” December 31, 2020. http://arxiv.org/abs/2101.00027.

  3. The Pile has been used by various groups and companies in developing their own models, including the open source Eleuther.AI models, up to and including Facebook for its LLaMA.




I don’t want to unnecessarily single out Facebook here. The whole reason that we know they used this dataset is because they are trying to be as transparent as possible, making the point that “Unlike Chinchilla, PaLM, or GPT-3, we only use publicly available data, making our work compatible with open-sourcing, while most existing models rely on data which is either not publicly available or undocumented (e.g. “Books – 2TB” or “Social media conversations”). 

It’s astounding to me that OpenAI, with all its recent attempts to take the moral high ground, cannot be bothered to share the training data they used. (For some further analyses of the recent OpenAI blogposts, see [Scott Alexander,](https://open.substack.com/pub/astralcodexten/p/openais-planning-for-agi-and-beyond) damning while trying to be as sympathetic as possible, and Emily Bender’s [Twitter thread](https://twitter.com/emilymbender/status/1629708863699308544), not bothering to be sympathetic.)

Lots of other stuff going on this week, as GPT continues to burn up the airwaves, but increasing I imagine you are reading most of that on your own! 

[Share](https://aicopyright.substack.com/p/has-your-book-been-used-to-train?utm_source=substack&utm_medium=email&utm_content=share&action=share)

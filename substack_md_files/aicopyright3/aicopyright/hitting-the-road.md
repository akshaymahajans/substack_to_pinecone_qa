Title: hitting the road
Subtitle: looking forward to seeing many of you in Reykjavik or Frankfurt
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/hitting-the-road
---
I’ve been very quiet on Substack lately but that’s because there’s been such a rich discussion going on through other channels, including with many of the subscribers to the newsletter. Let’s keep that going. But here’s a quick stocktake. 

_My messaging over the last several months hasn’t changed much:_

1\. **Publishers and authors have a big stake in generative AI since the models rely on our content.** In important ways, our content is _in_ the models (though how _exactly_ is a complicated question).

2\. **The cliche is “the models read the internet” but it would be more appropriate to say the models were trained by copying books, journal articles and news articles.** And here I’ve highlighted the role of Books3, Books2 and most recently the enormous Books dataset (of 4 million works) used by Google to train its Chinchilla model. Even the “internet” bits, the webscrapes, are filtered in ways that prefer publisher content over user-generated material.

And in the last few presentations, though it’s been a theme in the Substack for longer, that 

3\. **There are important differences between phase one of deep learning, circa 2017,** with supervised learning over large but carefully groomed datasets for classification models **and phase two ,** coming into prominence from 2020 onwards, self-supervised learning on enormous datasets harvested from torrent sites and other sources or scraped from the internet, **to train large language models and generative tools.**

The rules and copyright exceptions around text and data mining (as well as many of the protocols around ethics) were developed from 2016 or so, based on “old AI” use cases and outputs. I’ve argued that large language models aren’t looking for facts when they build their statistical models of language use. What they are mining is expression, quite different than the facts that TDM is usually meant to yield. Facts aren’t protected by copyright. But expression is. What does that mean for thinking about how we govern LLMs now?

Subscribe

## How is this all playing out? 

The training of AIs on pirated books (the Books3 dataset) is now a mainstream topic, after Gizmodo [broke the story](https://gizmodo.com/anti-piracy-group-takes-ai-training-dataset-books3-off-1850743763) on the Danish Rights Alliance’s takedown of Books3. Since then we have the excellent Atlantic story by Alex Reisner - [“Revealed- The Authors Whose Pirated Books Are Powering Generative AI”](https://www.theatlantic.com/technology/archive/2023/08/books3-ai-meta-llama-pirated-books/675063), which kindly name-checked me, and included a tool for searching author names in the dataset, now hosted by Authors Guild. _[on Monday afternoon the 2nd Oct (GMT) Damon Beres of_ The Atlantic _reached out to me to say that the Author’s Guild is linking directly to the app created by_ The Atlantic _(and_ _bypassing the story), not co-hosting… apologies for not checking more closely.]_ And with that, the story really is everywhere, see [this Guardian article](https://www.theguardian.com/australia-news/2023/sep/28/australian-books-training-ai-books3-stolen-pirated) about the Australian case, quoting Richard Flanagan. 

Singapore’s Anglophone literary set discovered the Authors’ Guild tool on Thursday last week, and it became a thing for our writers are check and see if they are included in the training set (some seeming more worried about being left out!). 

The idea that the TDM exception in the EU Digital Single Market rule might not apply to LLM training (or should not be applied) is getting some traction, though so far European publishers have been cautious about making that claim. The recent fiery statement by the European Writers Council — [“The success of Generative AI in the book sector is based on theft”](https://europeanwriterscouncil.eu/gai-is-based-on-theft/)—takes the view that it is “highly doubtful” that the DSM Clause 4 applies to machine learning, as opposed to more traditional text and data mining. 

[![gray building](https://images.unsplash.com/photo-1565520599628-f1cff16e1c9e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzMDAzMzh8MHwxfHNlYXJjaHwxNHx8cmV5a2phdmlrfGVufDB8fHx8MTY5NjA5MzU2MXww&ixlib=rb-4.0.3&q=80&w=1080)](https://images.unsplash.com/photo-1565520599628-f1cff16e1c9e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzMDAzMzh8MHwxfHNlYXJjaHwxNHx8cmV5a2phdmlrfGVufDB8fHx8MTY5NjA5MzU2MXww&ixlib=rb-4.0.3&q=80&w=1080)The Reykjavik Opera House; I’ve got tickets to hear the Iceland Symphony Orchestra play some Anna Þorvaldsdóttir… Photo by [Michael Held](https://unsplash.com/@michaelheld) on [Unsplash](https://unsplash.com)

I’m looking forward to discussing all this in October, including in some exciting in person sessions: I’ll be giving a keynote presentation to the Reykjavik annual meeting of IFFRO, hosting a panel discussion later that day with a stellar group, and then a couple of weeks later in Frankfurt will be joining the Federation of European Publishers’ (FEP) long-established Rendez Vous event . 

All Frankfurt Book Fair professional visitors are welcome to the Rendez Vous session, and that’s on Thursday from 12 noon (refreshments will be served). It will start with a presentation on cultural policies in Europe from the Director at DG Culture (European Commission), Georg Häusler, followed by a panel on artificial intelligence with me, Thomas Heldrup, the Head of Content Protection & Enforcement at Danish Rights Alliance, he of the Books3 takedowns, and a publisher to be named later. FEP Legal Advisor Quentin Deschandelliers will brief participants on the state of play of the EU AI Act. I’m very much looking forward to this and to meeting some of you there I hope! 

## From RAG to riches?

Meanwhile I’m starting to think more about another theme, the modular nature of the models, especially as the big companies rolled out a variety of out new products this September. Most new applications use an architecture that involve lots of “retrieval augmented generation”, in addition to fine tuning the LLM through reinforcement learning with human feedback. RAG is an architecture which links LLMs to more restricted databases of text, and so attempts to control the hallucination problem. 

The LMM uses its training to turn a question or query into a vector representation — then searches for similar texts in a database of texts that have also been described with vectors. The big news here is that vector similarity (which can be calculated in many different ways) looks like it could be a better way to search than relying on single search terms. You are not just matching words, you are comparing the similarity of texts along those thousands of dimensions that LLMs use in their statistical models. _There may be spurious correlations between texts as well as deep and fascinating ones that weren’t obvious from keyword matching. Time will tell!_

Once you’ve identified that some material from your own cache of text is similar to your query, and therefore might be helpful in answering the question, one version of RAG pulls out the retrieved text, and sends it (with the query) back to the LLM. Given this retrieved material in the prompt, the model will mostly likely (remember, the models are probabilistic) give you an answer which is more closely tied to the information in your database, less likely to be a hallucination.

McKinsey built such a system to help its consultants, drawing on its huge (and very well-managed and carefully “sanitized”) cache of “knowledge documents”. [Lilli](https://www.mckinsey.com/about-us/new-at-mckinsey-blog/meet-lilli-our-generative-ai-tool) is said to be a much more effective way of exploring and synthesizing McKinsey knowledge. Google is proposing that you index your Gmail, and it will perform this sort of RAG on the data represented in your correspondence. _The dream of the personal digital assistant…_

Craig Smith [hosted Dimitry Shapiro, Founder of Youai.ai,](https://www.eye-on.ai/podcast-archive) on his Eye on AI podcast . Shapiro wants to augment this sort of system with what he’s calling a Mind Index, a personal profiling dataset based on 1000s of questions and fun quizzes posed to users, which amounts to a profile of their interests, preferences and knowledge levels, etc. If you combine some measure of who you are (the Mind Index) with some pool of text that you know or should know, or should consult, then you just may get something even more useful, argues Shapiro.

And of direct relevance to my academic publishing colleagues, there’s a great deal of activity here in discovery and research tools across research publishing. I’m trying out Elicit, an excellent tool that uses these techniques across a wide pool of open access journal material. You can also upload your own cache of pdfs (however you got them) and query that material. There are many contenders out there right now.

These sorts of augmentation strategies should lead to more real licensing opportunities, different ways to plug in LLMs to vetted text, the knowledge graph etc. But it may also tempt AI companies to try to push the “original sin” of training LLMs without permission further and further into the background. We’re starting to see that strategy from the companies already, with OpenAI and Google both talking up their technical measures to opt-out of _new_ webscraping to support their models, while being silent on the old training. Is this new webscraping to create datastores for RAG? or for fresh rounds of LLM training?

There’s could be a good side to this as well . One recent paper[1](https://aicopyright.substack.com/p/hitting-the-road#footnote-1-137483325) is arguing for an architecture that trains the LLM only on public domain data, and then does RAG on a huge scale, across large databases of content. So the “juice” of recognizing patterns in text is built on public domain data, but the question answering, the advice, the “in the style of” questions can be linked through the retreival process to specific texts that have been pulled in from these vector databases. That would allow licensing, opt-out, accountability, withdrawal of material from the database, all the norms that authors and publishers are calling for. Watch this space.

[Share](https://aicopyright.substack.com/p/hitting-the-road?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/hitting-the-road#footnote-anchor-1-137483325)

Sewon Min, Suchin Gururangan, Eric Wallace, Hannaneh Hajishirzi, Noah A. Smith, Luke Zettlemoyer, SILO Language Modes: Isolating legal risk in a nonparametric datastore arXiv:2308.04430v1 8 Aug 2023

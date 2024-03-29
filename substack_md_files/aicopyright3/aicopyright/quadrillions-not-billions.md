Title: Quadrillions not billions
Subtitle: The heat generated by the uncertainty around AI and copyright is increasing. Not sure we are getting a corresponding increase in light…
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/quadrillions-not-billions
---
Some five months [after I highlighted the role of pirated books](https://aicopyright.substack.com/p/has-your-book-been-used-to-train) in AI training materials — the Books3 dataset in The Pile — the txt file cache is down from its home at The-Eye.EU. I had thought initially this was based on the dataset being mentioned in the Kadrey et al v Meta lawsuit, but in fact it was because of the action taken by [Rights Alliance](https://rettighedsalliancen.com/), a non-profit organisation representing the creative industries in Denmark. They identified 150 pirated books published by their members in Books3. Despite their defiant DMCA takedown video statement, The Eye recognized the simple justice of the takedown request, and acted accordingly.

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F34374912-a0bc-45e4-9ca7-f437a8e5f0a3_256x256.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F34374912-a0bc-45e4-9ca7-f437a8e5f0a3_256x256.png)The-Eye.EU logo from their website

The story of the takedown is covered well in Gizmodo [here](https://gizmodo.com/anti-piracy-group-takes-ai-training-dataset-books3-off-1850743763). A thoughtful story very much worth reading…

The engineer who originally processed Bibliotik into Books3, [Shawn Presser](https://twitter.com/theshawwn), has attempted to keep access to the dataset alive, and is feeling a bit of a martyr, running a poll on Twitter/X on whether he will go to jail for creating “a research dataset”. 

And I couldn’t help but smile at the person who found their way to Presser’s Twitter/X thread on the matter and replied wanting to know if they could download a subset of of Books3 “that excludes, say, books written by straight white cis men?”, so as to avoid racism…. _Nice that you’re looking for a technological fix for racism, but meanwhile how about having a care for the interests of the creators (of all sorts) whose works were copied against their interests._

But Presser is also making a very useful point, as he put it in his interview with Gizmodo:

>  _“The only way to replicate models like ChatGPT is to create datasets like Books3,” Presser said. **“And every for-profit company does this secretly, without releasing the datasets to the public...** without Books3, we live in a world where nobody except OpenAI and other billion-dollar companies have access to those books—meaning you can’t make your own ChatGPT. No one can. Only billion-dollar companies would have the resources to do that.”_

Subscribe

Books3 is the target for the takedown because Presser was transparent about what went into it. For a long time now Google, OpenAI, Microsoft and Meta are making use of similarly infringing content, but without sharing information on their datasources. (Comparing machine learning output with ML training data is really an important part of the process of understanding model performance, so this is not just bad for copyright holders trying to understand if their works have been used without permission, it’s bad for data scientists trying to evaluate models on many many dimensions.)

Unless they are required by law to share copyright status of their training data, as the draft EU AI Act proposes, to tackle Google and OpenAI you have to catch them. Even before you can argue that copying to train LLMs is not fair use, you have to find ways of proving that your works have been copied. The approach of Silverman et al v OpenAI is to show that Chat-GPT can deliver reasonably accurate summaries of their books.

“On information and belief, the reason ChatGPT can accurately summarize a certain copyrighted book is because that book was copied by OpenAI and ingested by the underlying OpenAI Language Model (either GPT-3.5 or GPT-4) as part of its training data.“

This seems like proof to me, but then I’m no lawyer, and I’m deep in how books have been used to train the models. Will a judge agree? 

### Model Patching

Another story out this weeks points to an observation made by researchers that “speculate that ChatGPT developers have implemented a mechanism to detect if the prompts aim to extract copyright content or check the similarity between the generated outputs and copyright-protected contents.”[1](https://aicopyright.substack.com/p/quadrillions-not-billions#footnote-1-136242012)

Actually this variety of model patching was sketched out already by the Stanford Foundation Models paper of July 2022. Then there’s the Henderson et al paper (with Mark Lemley as one of the co-authors) that assumes that copying training data is an inbuilt characteristic of LLMs, and proposes a variety of expensive computational mitigation strategies to try and avoid this in future.[2](https://aicopyright.substack.com/p/quadrillions-not-billions#footnote-2-136242012) _And why isn’t licensing even contemplated, I have to ask again…_

So the big companies don’t tell us what material was copied, and then try to patch over the output when their sources start to show. 

### Wipe ChatGPT and start over

So as the tension increases, we have headlines like this one: “Potential NYT lawsuit could force OpenAI to wipe ChatGPT and start over”. 

This was an excitable _Gizmodo_ headline on a report sourced to _NPR_ , which is [the one you want to read](https://www.npr.org/2023/08/16/1194202562/new-york-times-considers-legal-action-against-openai-as-copyright-tensions-swirl). The _New York Times_ is evidently seriously considering a lawsuit against OpenAI. While there had been talks about a licensing deal, evidently, recently these talks had “turned contentious”. 

The _NPR_ story does cover the possibility of starting over, of algorithmic disgorgement. It also raises the possibility of penalties of up to US$ 150,000 for each infringement conducted willfully, under American precedent. So let’s see, if Google was to be sued for the 1.1b copyrighted articles it included in the “News” dataset used to train Chinchilla, that’s, well, I think, north of a quadrillion dollars… 

The NPR story also recognizes the way that LLM copying is different from Google Books copying: 

> “…[a 2015 federal appeals court ruling](https://fairuse.stanford.edu/case/authors-guild-v-google-inc/) that found that Google's digitally scanning of millions of books for its Google Books library was a legally permissible use of ‘fair use,’ and not copyright infringement. The court found that Google’s digital library of books did not create ‘a significant market substitute’ for the books, meaning it did not compete with the original works. **Legal experts say proving that in the AI cases will be a major hurdle to overcome for OpenAI.**

And the NPR story concludes:

> “If you're copying millions of works, you can see how that becomes a number that becomes potentially fatal for a company,” said Daniel Gervais, the co-director of the intellectual property program at Vanderbilt University who studies generative AI. “Copyright law is a sword that's going to hang over the heads of AI companies for several years unless they figure out how to negotiate a solution.”

And that realization is why I started this newsletter! Because I really do think it’s important that we figure this out… 

[Share](https://aicopyright.substack.com/p/quadrillions-not-billions?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/quadrillions-not-billions#footnote-anchor-1-136242012)

Liu and Yao et al, “Trustworthy LLMs: a Survey and Guideline for Evaluating Large Language Models’ Alignment”, arXiv:2308.05374v1 [cs.AI] 10 Aug 2023

[2](https://aicopyright.substack.com/p/quadrillions-not-billions#footnote-anchor-2-136242012)

The paper is Henderson, Peter, Xuechen Li, Dan Jurafsky, Tatsunori Hashimoto, Mark A. Lemley, and Percy Liang. ‘Foundation Models and Fair Use’. arXiv, 27 March 2023. [http://arxiv.org/abs/2303.15715](http://arxiv.org/abs/2303.15715).

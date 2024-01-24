Title: “I will get an order out when I get an order out.”
Subtitle: tentatives, difficulties, and who's a threat to whom?
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/i-will-get-an-order-out-when-i-get
---
### Motions 

The hearing of the motions to dismiss the Anderson et al v Stable Diffusion et al case was July 19th. We don’t have a written order from the judge, but we do have [reporting](https://www.linkedin.com/feed/update/urn:li:activity:7087578153614807040/) on the judge’s verbal tentative ruling, by Aaron Moss of Copyrightlately.com, a partner at Greenberg Glusker in Los Angeles. 

Moss reckons that most claims will be dismissed, but with leave to amend.

Among the key points reported: “The judge seemed skeptical of plaintiffs’ claim that the Stable Diffusion model incorporates copies of plaintiffs’ works given how small the model is vs. the five billion images it was trained on, and wants these claims pled with more specificity to determine whether they're plausible.”

As covered in [the newsletter of January 16,](https://aicopyright.substack.com/p/battle-of-the-metaphors) Stability CEO Emad Mostaque has long been using this point to defend Stable Diffusion against copyright infringement claims. And the incredible compression involved in the model’s architecture indeed makes it hard to imagine that five billion images can be “hiding” inside a model that I can run on my iPhone. Many [(including me) ](https://aicopyright.substack.com/p/understanding-understanding)warned that the plaintiffs’ comparatively unsophisticated language in characterizing the nature of the models (calling Stable Diffusion a 21st century collage machine) was going to make this case challenging to argue. 

I don’t doubt that the legal team has been working hard on this exact point, but will this amount to the rabbit out of the hat that Moss believes they will need? They will try to find ways to counter this conceptual difficulty with the fact that diffusion models do or at any rate _can_ reproduce the images they were trained on, sometimes at a pixel-perfect level.[1](https://aicopyright.substack.com/p/i-will-get-an-order-out-when-i-get#footnote-1-135308545) So how to explain what’s going on in a way that works in a courtroom, and allows Judge Orrick to make a call here? 

We shall see. But as for the judgements on motions to dismiss, we await Judge Orrick’s written orders, which, as per Moss’ reporting, the judge will get out when gets out. No rushing the American legal system. 

[![clear glass ball on brown dried leaves](https://images.unsplash.com/photo-1590012705866-810e697c20c8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzMDAzMzh8MHwxfHNlYXJjaHw1fHxjcnlzdGFsJTIwYmFsbHxlbnwwfHx8fDE2ODk5MDA2MjV8MA&ixlib=rb-4.0.3&q=80&w=1080)](https://images.unsplash.com/photo-1590012705866-810e697c20c8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wzMDAzMzh8MHwxfHNlYXJjaHw1fHxjcnlzdGFsJTIwYmFsbHxlbnwwfHx8fDE2ODk5MDA2MjV8MA&ixlib=rb-4.0.3&q=80&w=1080)Photo by [Brad West](https://unsplash.com/@mintchap) on [Unsplash](https://unsplash.com)

### a tale of two cases

Plenty of room for speculation and crystal-ball gazing. Most legal commentators see the Getty v Stable Diffusion case is much stronger than Anderson, given that Getty 1) apparently did license images to OpenAI to train DallE-2, so has a more obvious economic claim, ie that Stability could have licensed their images but chose not to. They also 2) have a much larger file of images produced from the models that have Getty watermarks or otherwise closely resemble Getty images.

In an interview with Lawfare, Berkeley law Professor Pam Samuelson says Stability should settle with Getty. She [wrote a recent piece](https://www.science.org/doi/10.1126/science.adi0656) on Generative AI and copyright for _Science_ , which seems pretty weighted towards warning us all of the downsides if court decisions go against big tech (or they don’t settle their way out of cases that could set a bad precedent for them). It’s a good article to read if you want to understand the tech company approach to the legal argument. If you prefer the podcast version you can listen to her on Lawfare, [“Pam Samuelson on Copyright's Threat to Generative AI”](https://shows.acast.com/lawfare/episodes/pam-samuelson-on-copyrights-threat-to-generative-ai). 

_(As an aside, I really don’t quite understand why Lawfare seems to give more space to the_ “copyright a threat to AI” _side of things rather than the_ “generative AI a threat to copyright” _side which looks a little more likely to me! But perhaps we need to stop seeing the threats only and start with the opportunities already.)_

But, anyway, here is Samuelson on the threats:

> “If the plaintiffs prevail, the only generative AI systems that may be lawful in the United States would be those trained on public domain works or under licenses, which will affect everyone who deploys generative AI, integrates it into their products, and uses it for scientific research. 

_Why does she assume that training models on data under license will be so bad? Good data, legal certainty, a reason to invest in improving and developing data, etc._

A bit later…

> “Rulings in favor of plaintiffs might trigger “innovation arbitrage,” causing developers of generative AI systems to move their bases of operation to countries that regard the ingestion of copyrighted works as training data as fair use, like Israel’s Ministry of Justice did in early 2023.” 

_Or Singapore!_

Not a legal argument. There are some legal arguments in there of course.

Regular readers will know [what I make](https://aicopyright.substack.com/p/the-rockstars-gambit) of that Israeli ruling, from the Ministry of Justice to give legal cover to its Ministry of Defence to train an Israeli national LLM in Hebrew and local dialects of Arabic. Hmmm…

Samuelson at least has the good sense not to raise the bogeyman of China, making the claim that some do that we _must_ allow training of copyrighted material otherwise we lose the AI war with China. 

Subscribe

### New cases

Meanwhile, after the Samuelson article came out, [two more cases hit the wire,](https://www.theverge.com/2023/7/9/23788741/sarah-silverman-openai-meta-chatgpt-llama-copyright-infringement-chatbots-artificial-intelligence-ai) both from prominent writers and both focusing on copyright issues in large language models. In the case of _Kadrey et al v Meta_ the plaintiffs have firm evidence of copying of illegally accessed works, as books by the plaintiffs are found in the by-now infamous Books3 database that Meta/Facebook used. See the complaint [here](https://llmlitigation.com/pdf/03417/kadrey-meta-complaint.pdf).

Perhaps it was a coincidence but around the same time as the filing, industry website HuggingFace finally stopped hosting the Books3 dataset (though it is still available elsewhere). 

Just a couple of days ago Meta released an open source version of its large language model, Llama-2, and already people are figuring out how to run it on their laptops, etc. More to come on this, and the technical paper makes a good read. But Facebook is not being as transparent about the training data as they were on the first version of Llama —and you have read the reason why two paragraphs ago. Models are trained on copyrighted content, some of it pirated. Be transparent about it, and be sued. 

But on the other hand, how can any sort of governance, or any real scientific evaluation of the models take place if there is no transparency? Progress in this technology relies on assessing performance against training data! This a technology that has been commercialised too early. 

(In [his recent interview with Ezra Klein,](https://share.snipd.com/snip/9ae1f612-8859-4f02-b76f-414463c8e3f9) Demis Hassabis of Google Deep Mind laments that we’ve moved from the scientific stage of development of AI to the engineering/business side so quickly…and why has it done so? Perhaps this _Fortune_ headline holds a clue: “[Microsoft’s stock has risen almost 1,000% since Satya Nadella became CEO in 2014, netting him a reported $1 billion in compensation](https://fortune.com/2023/07/20/microsoft-stock-1000-percent-ceo-satya-nadella-1-billion-compensation/?utm_source=flipboard&utm_content=user%2Ffortune) **”** )

Here’s what Meta says about the training data for Llama-2. It is: 

> a new mix of data from publicly available sources, which does not include data from Meta’s products or services. We made an effort to remove data from certain sites known to contain a high volume of personal information about private individuals.

### still, I’m optimistic

Meanwhile, one continent and an ocean away in Europe, the trilogue on the AI Act commences. I really enjoyed Craig Smith’s _[Eye-on-AI](https://share.snipd.com/snip/1bac4d33-0249-4bd3-8ad0-8ef2f1de73ee)_[ interview](https://share.snipd.com/snip/1bac4d33-0249-4bd3-8ad0-8ef2f1de73ee) with EU Parliamentarian Alexandra Geese of Germany’s Green Party. [Craig Smith’s podcast](https://www.eye-on.ai/about) is generally invaluable for understanding the industry. Chapeau to Smith for attempting to reach across the divide separating Silicon Valley from Brussels. 

Perhaps he just had a bit of a cold, but I had to chuckle at the tentative slight tremble in his voice as he asked Geese whether the European position was that the existing models were illegal and would have to be tossed out: “does that mean that people providing foundational models will have to train from scratch, start over, and if they want to operate in Europe, provided that the act passes in its current form?”

Geese doesn’t commit, “that’s a question that’s very hard to answer” but she recognizes that the copyright discussion is core here.

Later there’s a classic misunderstanding. Geese says she’s optimistic about the foundation models. Smith asks if she means she’s optimistic that 

> “there won't be major changes required on behalf of the providers of these models. I mean that the existing models won’t be banned based on the inability to identify copyrighted materials in their training data, for example, and that the companies providing those models [won’t] have to start from scratch. You're optimistic in that way or you're optimistic that those restrictions will will be waived for the current generation and it'll be applied going forward”

Sorry Craig, neither one… 

> “I’m optimistic that the obligations to test and analyze, identify reasonably foreseeable risks and risk mitigation measures will stay in [the AI Act] and the obligations for data governance. That that’s what I’m optimistic about. What exactly that means for copyright, I can’t say at the moment,”

We’ll know when we know. In her interview with Smith, Geese muses that it would be nice to have “a glass sphere”. I agree! 

_**Corrections: July 21 - apologies to Alexandra Geese for getting her name wrong in the initial version of this. Also Aaron Moss’ law firm which is Greenberg Glusker!**_ _**Seems like the Books3 dataset is also still available on HuggingFace… as only some versions have been taken down.**_

[ Share](https://aicopyright.substack.com/p/i-will-get-an-order-out-when-i-get?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/i-will-get-an-order-out-when-i-get#footnote-anchor-1-135308545)

See Nicholas Carlini et al, Extracting Training Data from Diffusion Models, https://doi.org/10.48550/arXiv.2301.13188

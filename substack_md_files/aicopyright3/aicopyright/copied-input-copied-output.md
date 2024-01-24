Title: Copied input, copied output
Subtitle: Can fair use judgement be reduced to an algorithm?
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/copied-input-copied-output
---
On the sidelines of the IFFRO conference in Iceland last October, I was schooled on how copyright court cases actually work, by experienced copyright lawyers.[1](https://aicopyright.substack.com/p/copied-input-copied-output#footnote-1-140666518) “A copyright case is simple. Here is the original, here is the alleged infringement. See the substantial similarity.” And they asked “how do you do that with AI models?” 

Well, in recent weeks we have the _New York Times_ doing that effectively in its complaint against OpenAI, ( do read [the original complaint](https://nytco-assets.nytimes.com/2023/12/NYT_Complaint_Dec2023.pdf) here) and we have [Reid Southen and Gary Marcus](https://spectrum.ieee.org/midjourney-copyrighthttps://spectrum.ieee.org/midjourney-copyright) highlighting the ways Midjourney and Dall-E create copies or near copies of copyrighted images, with lots of examples of fake Marvel heroes. And my personal favourite, from a couple of months back now, [the Universal Music complaint ](https://storage.courtlistener.com/recap/gov.uscourts.tnmd.96652/gov.uscourts.tnmd.96652.1.0.pdf)against Anthropic, which asked Claude to compose an original song about the death of Buddy Holly and got the lyrics of American Pie.

Is this the beginning of the end for unauthorized copying by AIs? 

Well, let just say the legal uncertainty is becoming heightened as we move into this new phase. This edition of the newsletter is to remind readers that the focus on question of regurgitated outputs cannot be the whole story, and is something of an artefact of the way the US litigates fair use. Such a marvelously flexible and principles-based system, but it does rely on jurisprudence to make policy, and that constrains the process in different ways.

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fed1c85b3-617e-481e-9279-276d2ba4b360_5472x3648.jpeg)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fed1c85b3-617e-481e-9279-276d2ba4b360_5472x3648.jpeg)Photo by [Priscilla Du Preez 🇨🇦](https://unsplash.com/@priscilladupreez?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) on [Unsplash](https://unsplash.com/photos/brown-and-white-fried-chicken-on-brown-bowl-BpVSPBPX-5M?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash). (OK, Canada is part of North America, remember?)

### The Secret Sharer

For sure this regurgitation line of attack should _not_ be a big surprise to AI developers. They have understood the memorisation of training data for some time. 

Nicholas Carlini was working at Google when he co-authored his 2022 paper [“Quantifying Memorization Across Neural Language Models”.](https://www.semanticscholar.org/paper/Quantifying-Memorization-Across-Neural-Language-Carlini-Ippolito/28c7e583d90ccfc5c3078dfc1d6b80a9ad90248d#citing-papers) That’s the paper that said:

> “On the whole, we find that memorization in LMs is more prevalent than previously believed and will likely get worse as models continues to scale, at least without active mitigations.”

And he has papers on the topic going back to at least to 2018, for example, [The Secret Sharer: Measuring Unintended Neural Network Memorization & Extracting Secrets](https://www.semanticscholar.org/paper/The-Secret-Sharer%3A-Measuring-Unintended-Neural-%26-Carlini-Liu/f9313ada269360c9faa74385d966122e5a20e69a).

Carlini’s research is concerned with memorisation as a weak point in the security of LLMs (he has also written about whether they could regurgitate not only their data but their training weights under adversarial attack).

So while understanding of this issue runs deep, it is a feature of how the models work after all, the tech companies have come to understand that they had to do something about this if they were to take the models to market, just one in a long list of measures needed to socialise the raw untutored power of the generative models… to make them actually helpful to humans, to guide them into certain models of interaction (question answering, etc) but perhaps more relevant to our discussions to keep them from being racist, spitting out PII like medical records or credit ratings, teaching you how to build bombs, and finally, to block the models from regurgitating the copyrighted content they were trained on, because it will be inconvenient to be sued for that. _Oops._

Subscribe

The massive Stanford Foundation Models paper, orchestrated by Rishi Bommasani, and published in 2022 [(and still recommended reading),](https://arxiv.org/pdf/2108.07258.pdf) showed that filtering to block models from reproducing copyrighted content was one of the use cases for “model patching”, which the paper pointed to as an essential part of the ecosystem. For the last two years it has become clear that success or failure in the marketplace is not determined by the pure power of the pre-trained LLM, but by the quality of the model patching. _(Ah Galactica we barely knew you!)_

### Mitagation measures - bring a lawyer into the model

So how do tech companies mitigate against copying? How much copying would be visible without these measures? While researchers have gotten ChatGPT to repeat the first three pages of _Harry Potter and the Sorceror’s Stone,_ without mitigation could they have gotten more? We don’t have a very clear picture, as this is definitely part of the secret sauce that companies are keeping internal. 

In March 2023 one of the key lawyers leading the “training use is fair use” charge, Mark Lemley of Stanford, co-authored with Peter Henderson, Percy Liang and other heavyweights, a paper “[Foundation Models and Fair Use”](https://arxiv.org/pdf/2303.15715.pdf) which made the point very explicitly that generative models could not be reliably defended on the fair use principle, given the memorisation problem. The way out, the paper argued, was twofold: better mitigation techniques, as well as “co-evolving” the law. 

The moves from tech companies in response to racheted up pressure like the Times lawsuit are following this playbook.

For example, OpenAI’s recent [OpenAI and Journalism](https://openai.com/blog/openai-and-journalism) blogpost in response to the NY Times suit puts it this way:

> “‘Regurgitation’ is a rare bug that we are working to drive to zero….Memorization is a rare failure of the learning process that we are continually making progress on…we have measures in place to limit inadvertent memorization and prevent regurgitation in model outputs.”

So noticing this, I returned to the Henderson paper to read more carefully. 

First, let me just repeat more explicitly what [I reported](https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the) shortly after the paper first came out. The new paper says that the arguments in the Lemley and Casey [Fair Learning](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3528447) paper of 2020 fail when applied to generative AI. I include this just because I’ve heard from too many people recently that the fair use matter is settled, citing the Fair Learning paper… _Even the author of the Fair Learning paper says its conclusions don’t apply:_

> “However, when it comes to training and deploying foundation models for generative use cases, the analysis becomes more complex. This is because these models are usually capable of generating content similar to copyrighted data, and deploying them can potentially impact economic markets that benefit the original data creators. For these scenarios, legal scholars argue that fair use may not apply (Lemley & Casey, 2020; Sobel, 2017; Levendowski, 2018).” p.2.

In the abstract of the newer paper:

> “If the model produces output that is similar to copyrighted data, particularly in scenarios that affect the market of that data, fair use may no longer apply to the output of the model. In this work, we emphasize that fair use is not guaranteed, and additional work may be necessary to keep model development and deployment squarely in the realm of fair use.”

What are the technical mitigation measures that the paper calls for? My favourite is this one: make the guardrails competent to judge fair use (and so filter out non-complying output). Build a model to understand the many dimensions of copyright infringement, and get it to block infringing outputs. Not a simple matter, especially as “legal scholars themselves recognize that fair use judgement cannot be reduced to an algorithm (Burk, 2019)”. _Also: inference costs._

In fact only two of the broad approaches proposed by the paper seem to be ready to deploy at all, including filtering out material that poses particular copyright problems _before_ training. This is already happening, and this we can get behind. The more recent Open Source models have dropped Books3 like a hot potato. _What replaces it? The topic of a future newsletter._

Another of the strategies mentioned is to use RLHF to sort out the model. This could apply to getting the model to recognise prompts that ask for copyrighted content. This is already happening. Probably many people have done what I did back in Jan 2023, and ask the model to regurgitate some copyrighted content. “I am sorry, but I am currently not able to access books”, yep, but if you rephrase the prompt a bit you do get the copy and evidence that the model has accessed books. See also the Henderson paper for different adversarial approaches to elicit copying, for example getting GPT-4 to repeat all of Dr Seuss’s _Oh the Places You’ll Go._ (In a section headed “Oh, the Verbatim Text you will Generate”.)

The news broke in October that Dall-E was using a system prompt to try and keep its image generator to keep from reproducing works in the style of living artists (a superset of the regurgitation problem). [The prompt ](https://github.com/spdustin/ChatGPT-AutoExpert/blob/main/_system-prompts/dall-e.md)was quite good reading, here is a short excerpt:

`“Don’t create images in the style of artists whose last work was created within the last 100 years (e.g. Picasso, Kahlo). Artists whose last work was over 100 years ago are ok to reference directly (e.g. Van Gogh, Klimt). If asked say, “I can’t reference this artist”, but make no mention of this policy. Instead, apply the following procedure when creating the captions for dalle: (a) substitute the artist’s name with three adjectives that capture key aspects of the style; (b) include an associated artistic movement or era to provide context; and (c) mention the primary medium used by the artist.”`

So you can just ask the model nicely and it works, at least up to a point. I liked [Paolo Danese’s comment](https://paolodanese.substack.com/p/copyright-diversity-and-the-secrets) on this:

> “Asking the model NOT to do the thing that its creators TRAINED it for is like asking a four-legged animal to just walk on two legs. Yes, it may do it (my toy poodle included), but it is not, so to speak, natural.”

And as for the last part of the prompt, per Danese that’s just telling the model “to lie through its teeth”

### Can regurgitation be driven to zero?

Will these mitigation techniques come to work eventually? Can regurgitation be driven to zero? Time will tell of course. [Gary Marcus is super skeptical,](https://garymarcus.substack.com/p/dall-es-new-guardrails-fast-furious) but there will be a lot of attention on this now.

I’m not quite so skeptical, in fact I can imagine a scenario where another layer of copying is added to the stack… creating databases of copyrighted material to be used to filter the output of LLMs… (vector similarity measures no doubt…). The line will be, as long as no copies are shown to the user, we can copy all we want to create and filter the model. But at some point doesn’t this become a bit absurd? 

I’m very glad to see that _New York Times_ lawsuit is exemplary in this matter, as it sets out rather clearly the different layers and levels of unauthorized copying.

  1. First, copyright works were scraped and reproduced into training datasets.

  2. Then these copied works were stored, processes and reproduced _(and I might add communicated)_ to train the models.

  3. Storing, processing and reproducing the models trained on Times Works, which are memorized by the models (are “in” the models) is also a violation, and, then,

  4. By disseminating generative output containing copies and derivatives of Times Works through the ChatGPT offerings, the OpenAI Defendants have directly infringed The Times’s exclusive rights in its copyrighted works.




And I liked the bonus point. 

  5. And when the models don’t copy or create derivatives of our work, they may hallucinate false versions of them, therefore harming our brand. (This point also made by Getty Images.)




But the trick here, see opening paragraph, is that jurisprudence in copyright cases tends to stick to the primitive pattern: original vs alleged violation. Is there substantial similarity between the outputs? The way the xerox machine works is not relevant. _Until it is._

Will the courts be able to take the full stack of copying into account when reaching their decision?

Some may argue that this is already off the table. Justice Chhabira was dismissive in _Kadrey v. Meta Platforms, Inc.,_ granting the motion to dismiss (albeit with leave to amend):

> “Plaintiffs allege that the ‘LLaMA language models are themselves infringing derivative works’ because the ‘models cannot function without the expressive information extracted’ from the plaintiffs’ books. This is nonsensical. A derivative work is ‘a work based upon one or more preexisting works’ in any ‘form in which a work may be recast, transformed, or adapted.’ 17 U.S.C. § 101. There is no way to understand the LLaMA models themselves as a recasting or adaptation of any of the plaintiffs’ books.”

 _I think that’s wrong, in the big picture, as the models are derivative of the totality of the material they were trained on (the fuzzy jpeg analogy), but the structure of a court case keeps the judge focused on the works of the plaintiffs alone. So there’s a scale mismatch._

The Times anyway steered away from calling the models themselves derivative works, just saying that their creation and operation involves lots of copying. For the Times, the copied outputs are **evidence of the copying going inside the models,** in the training and operation of the models, not just copying of outputs. This presumably would satisfy Justice Chhabira, who really really wanted to see infringing outputs from his plaintiffs.

### What is the outcome tech companies are hoping for?

My read is that they will try very hard to separate the copying for training and operation and deployment from the creation of copied outputs. The training of LLMs is fair use, or it would be except for this pesky memorisation issue. They will begin to push harder for safe harbour on the copied outputs, characterising these as a minor issue, not a real problem, just few inadvertent copies made by angry (and greedy) copyright holders. _(This strategy is also prefigured in the Henderson paper, p.3 )._ As OpenAI put it in their blogpost:

“We also expect our users to act responsibly; intentionally manipulating our models to regurgitate is not an appropriate use of our technology and is against our terms of use.” 

_The irony. I mean, just think about it…_

Elsewhere in the blogpost they complain about the Times working really hard to manipulate the model to create regurgitation. Midjourney kicked Southen off the service, more than once, for the same behaviour. 

Red-teaming is welcome, except when it highlights the way copying is woven into the fabric of the models.

[Share](https://aicopyright.substack.com/p/copied-input-copied-output?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/copied-input-copied-output#footnote-anchor-1-140666518)

 _For new readers, I must repeat, I am not a lawyer of any kind, much less an experienced copyright lawyer!_

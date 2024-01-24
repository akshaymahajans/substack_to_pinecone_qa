Title: From Goethe to Mickey Mouse, in the major world-changing machine
Subtitle: Bring me some sweet water from the well
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the
---
[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fed8d206f-297e-46fa-94d3-5eff936ecf22_2186x1440.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fed8d206f-297e-46fa-94d3-5eff936ecf22_2186x1440.png)Neither a McKinsey consultant nor a Stanford Law prof. A still from the all-AI-generated anti-Biden attack ad recently commissioned by Republican operatives, see below. 

Thanks for reading AI and Copyright! Subscribe for free to receive new posts and support my work.

Subscribe

## Legal News 

We have a new case: German photographer Robert Kneschke has sued LAION, the non-profit research collective that scraped the internet to provide some of they key datasets behind the Stable Diffusion model (and others). You would think a non-profit research collective would be protected by Article 3 of the Digital Single Market Directive, the European TDM exception for non-profits. However, as discussed in these pages before, the computing power used by LAION in collecting its word-image pairs data set was funded by a commercial entity, namely Stable Diffusion. Knesche has apparently argued along these lines in his public statements.

This is maybe the reason that Christopher Schuhmann, LAION founder recently disavowed responsibility for whatever use Stability AI was making of LAION data, trying (belatedly it feels like) to put some light between LAION and the company, in a must-read story from [Sifted](https://sifted.eu/articles/stability-getty-lawsuit) :

> “(The dataset) can be used by companies at their own risk and responsibility. We write everywhere on our papers, blog posts and dataset distributions that you should clean them and make sure to use them responsibly, so I cannot speak for Stability AI,” he tells Sifted. “I think if you train an AI model on some data you should make some decisions about what to include in the training data and what not to include. You have to take the responsibility.”

A sentiment which was the theme of [the last newsletter](https://aicopyright.substack.com/p/for-those-with-promises-to-keep). But I’m not sure how much light there is. The links between Emad Mostaque, StabilityAI and LAION run pretty deep. Richard Vencu, according to his LinkedIn profile head of ML Ops at Stability, is still listed as Engineering Lead and Founder of LAION on the LAION website. A tangled web. Much back-propagation. 

Most of the coverage of the lawsuit is in German media, and Kneschke’s [blog](https://www.alltageinesfotoproduzenten.de/2023/02/20/laion-verein-droht-urhebern-die-ihre-daten-aus-ki-trainingssatz-nehmen-wollen-mit-schadensersatzanspruechen/) , but be sure to read legal scholar Andres Guadamuz’ [blogpost](https://www.technollama.co.uk/photographer-sues-laion-for-copyright-infringement). It tells an interesting story of how the lawsuit came to be, and sets out the legal position very clearly. Says Guadamuz, “the more I have looked into it, the more I think that this could go all the way…” 

It’s going to be complex. Although news stories can’t go into this depth, it’s worth remembering that the image generation models are themselves made up of _at least_ three different foundation models stitched together (one to “learn” how to turn noise to images, one parallel model that trains on word-image pairs, creating common encodings for both different modalities and one frozen language model that encodes your prompt for inference, comparing that to the paired modalities and then nudging the diffuser to create the image you want).

## Legal News Two

Across the world in California, and not exactly news, but a fascinating new paper just made available in preprint form: “Fair Use and Foundation Models”. This is important because one of the authors is Stanford Law prof and attorney acting for StabilityAI, Mark Lemley, who had been one of the legal experts most often cited for his view that copying to train foundation models is likely to be fair use[1](https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the#footnote-1-120095927). In a Twitter exchange (from November ‘22) with Neil Turkewitz (and me): “That’s where we disagree. I think using inputs to train an AI to generate some thing that is not infringing is no different than reading a bunch of books before becoming an author.”

The paper is Henderson, Peter, Xuechen Li, Dan Jurafsky, Tatsunori Hashimoto, Mark A. Lemley, and Percy Liang. ‘Foundation Models and Fair Use’. arXiv, 27 March 2023. <http://arxiv.org/abs/2303.15715>.

I’m not _sure_ Lemley has changed his mind on the Twitter opinion above, but at least he (and his co-authors) acknowledge that the situation with generative models is much more complex than tech companies are wont to admit.

In my (very very far from law professor level) [October 2022 paper](https://psmedia.asia/good-ais-copy/) on the “input problem” I argued that one reason that training models might not be fair use was that they were known to copy their training data. (This copying is not the _only_ problem I see with the fair use defense.) The Henderson, Lemley _et al_ paper acknowledges this unfortunate tendency of the models, and agrees, seeing this as a major barrier to the fair use defense. This is how the abstract starts off:

> “In the United States and several other countries, copyrighted content may be used to build foundation models without incurring liability due to the fair use doctrine. However, there is a caveat: If the model produces output that is similar to copyrighted data, particularly in scenarios that affect the market of that data, fair use may no longer apply to the output of the model.” (Henderson _et al_., 2023, p. 1)

I’m still reading the paper. But having shown the copying problem, the solution the authors identify is to find technical means to ensure that models do not create infringing outputs. More better model-patching. To understand the roots of the copying problem, they run more serious and systematic versions of my attempts to get Chat-GPT to recite passages from Harry Potter.

Subscribe

> “it is the job of machine learning researchers and practitioners, working together with legal practitioners, to ensure that foundation models create transformative content which would pass muster under the same fair use analysis as provided to a human. To get there, new strategies and techniques will need to be developed, taking steps to ensure that foundation models behave in more transformative and novel ways. We call for more research to align technical mitigation strategies with fair use, including better output filtering mechanisms relying on higher-level semantics and new innovation in training-time techniques like extraction-preventative learning from human feedback.” (Henderson _et al._ , 2023, p. 2)”

 **I’m still of the view that the unauthorized copying at the training stage poisons the well.** Henderson, Lemley _et al_ want to create a better water filter so we can draw from the well. _I’m not sure I could ignore the bitter taste of that water, even if it were legally pure! How sweet would be the water from a well of properly compensated works, reproduced with the permission of their creators…_

Still, the authors are working hard to grapple with the broader issues. And they recognize that even if technical mitigation strategies work so well as to allow the fair use defense to prevail in court at every turn, that’s not the end of the story. 

> “But we emphasize that even if fair use is met to the fullest, the impacts to some data creators will be large. We suggest that further work is needed to identify policies that can effectively manage and mitigate these impacts, where the technical mitigation strategies we propose here will fundamentally fall short….We emphasize, again, that even if foundation models are covered by fair use the impacts on labor might be considerable…” (Henderson _et al._ , 2023, p. 28)

I’ll keep reading the paper, and am sure will have more to share on it soon. 

But given the new EU rule on transparency of copyrighted data, the Kneschke challenge to AI training under the EU TDM exception, and now with a key paper from a high profile Stanford team that sets out significant doubts that AI training is excused by American fair use, it seems we are moving closer to some convergence on acknowledging that we need to find a solution together.

Sounds good, right? Maybe, or maybe things are just moving too fast for even the good folks in Palo Alto and Brussels.

## Out of the box… and into the beefy laptop

I hope you saw the news about the [Google “We have no moats” Paper](https://www.semianalysis.com/p/google-we-have-no-moat-and-neither?r=gtkc) which sets out how far LLMs arenow out of the box of Big Tech and into the wilds of open source. The timeline of developments just in the past month is shocking, and the capabilities of models that can run on “a beefy laptop” are approaching some of Big Tech’s models. More to the point, the open ecosystem is fostering a huge wave of innovation in software and “open” datasets that is outstripping anything that can be done in big, bureaucratic companies. 

Readers of this newsletter might get an ironic smile (or grimace) out of this one point from the memo, among many, about why Google needs to wake up and take a whole different approach:

>  _ **Individuals are not constrained by licenses to the same degree as corporations**_ The legal cover afforded by “personal use” and the impracticality of prosecuting individuals means that individuals are getting access to these technologies while they are hot.

Pretty funny because from my perspective the corporations haven’t been greatly constrained, at least when it comes to the licenses in the content they’ve trained the AIs on. But if Big Tech is worried about all those unconstrained individuals out there with their beefy laptops, gee… 

From our perspective, one issue here is that the “open datasets” that are fueling this innovation are built on our old favourites The Pile and Books3. While Henderson, Lemley _et al_ acknowledge that these datasets are seriously problematic[2](https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the#footnote-2-120095927), the open source community is still of the view that these are somehow licensed or legitimate because, well, they are used by everyone else. We need to close this gap. (Hint to publishers: have you sent your takedown notices to HuggingFace for hosting Books3?)

### Some more news on harms:

[“AI is already writing books, websites and online recipes”](https://www.washingtonpost.com/technology/2023/05/05/ai-spam-websites-books-chatgpt) \- _The Washington Post_

Very depressing reading, that includes the sale of GPT-authored knockoffs on Amazon. “From product reviews to recipes to blog posts and press releases, human authorship of online material is on track to become the exception rather than the norm.” 

Also

“[Rise of the Newsbots: AI-Generated News Websites Proliferating Online](https://www.newsguardtech.com/special-reports/newsbots-ai-generated-news-websites-proliferating)”

“In April 2023, NewsGuard identified 49 websites spanning seven languages — Chinese, Czech, English, French, Portuguese, Tagalog, and Thai — that appear to be entirely or mostly generated by artificial intelligence language models designed to mimic human communication — here in the form of what appear to be typical news websites.”

NewsGuard is a service run by savvy newsmen Stephen Brill and Gordon Crovitz which licenses things like “top 40 false narratives on the internet” to BigTech companies to help them model-patch to minimize the harm from LLMs. _What’s remarkable is that they used really simple and literal searches to identify AI-written content, and still turned up so many sites._

And then there’s the first American political attack ad created fully by AI, hallucinating all the disastrous things that will happen if Joe Biden gets re-elected. Not a game-changer in and of itself, but a milestone nonetheless. 

Ted Chiang has another fresh and insightful take, again with accountability and responsibility a key theme: “[Will A.I. Become the New McKinsey?”](https://www.newyorker.com/science/annals-of-artificial-intelligence/will-ai-become-the-new-mckinsey)[3](https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the#footnote-3-120095927) Here he refers to the well-known use of consultants to carry out unpopular job cuts on behalf of a management that can pretend innocence: “that escape from accountability is one of the most valuable services that management consultancies provide...”

It’s a wicked piece, pointed. It’s one of the many recent pieces that picks up on the Sorcerer’s Apprentice as the the most suitable archetype to think about AI. _(Goethe by way of Mickey Mouse if you didn’t remember)._ If you are too busy to read Chiang’s piece, here is the payoff sentence:

“ **Capitalism** is the machine that will do whatever it takes to prevent us from turning it off…”

 _You could argue that our world is already well on its way to being turned to paperclips…_

### It’s all just…weird!

And lastly, a new metaphor to help with the metaphors. 

We’re familiar now with being stuck between the two views that “the LLMs are statistical models, 21st century collage machines, etc” and “they learn, they have knowledge of the world (even if it is only via language)”. The April 22 _Economist_ cover story handles in the same way I did in my IPA webinar. ( I read it after- _lah,_ but I’m pretty sure we’re drawing on the same sources…)

But Ezra Klein’s [recent interview with Erik Davis](https://www.nytimes.com/2023/05/02/opinion/ezra-klein-podcast-erik-davis.html), scholar of the weird and California culture (both) throws up another way of looking at things. Listen to the interview, it’s a lot of fun, but here’s Davis from the transcript:

“And you can intellectually lay that back on and go, OK, this is just a machine. It’s just operating. It’s read the whole internet _(and pirated books Erik)._ It’s just making a really good guess. It just has that feel. And you’re like, OK, but that’s not at all what’s happening emotionally or even spiritually in that response.…. if you’re trying to deconstruct it and at the same time recognizing its interactive dimension, well, then we’re in this animist space where I’m not so sure if that doll in the corner is actually animated or not. And that’s a very classic site of the uncanny. So suddenly there’s an uncanniness in the midst of this highly commoditized, major, major world-changing machine. That is — well, that’s pretty weird.”

fine words on which to conclude… 

[Share](https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the#footnote-anchor-1-120095927)

Lemley, Mark A., and Bryan Casey. ‘Fair Learning’. _SSRN Electronic Journal_ , 2020. <https://doi.org/10.2139/ssrn.3528447>.

[2](https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the#footnote-anchor-2-120095927)

“The Pile (Gao _et al._ , 2020) contains Books3, a dataset of copyrighted and commercially sold books downloaded from Bibliotik, a torrent tracker for books and learning materials (Presser, 2020; Biderman _et al._ , 2022)…”

[3](https://aicopyright.substack.com/p/from-goethe-to-mickey-mouse-in-the#footnote-anchor-3-120095927)

I worked (very happily) for McKinsey for six years, from 2005 to 2011 or so. When I left I was leading the Firm’s reputation management for Asia… We can talk offline about all that!

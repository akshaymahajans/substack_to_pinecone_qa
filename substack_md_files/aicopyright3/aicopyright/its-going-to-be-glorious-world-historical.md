Title: It's going to be glorious, world-historical!
Subtitle: and some thoughts from actual lawyers
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/its-going-to-be-glorious-world-historical
---
This newsletter was started to cover the considerable uncertainty about the legal status of the foundation models. While there is uncertainty around AI output or authorship (can AI-generated content be copyrighted?), I am more focused on the input problem — can the unauthorized copying of works to train AIs be justified, under fair use (US) or different exceptions? For a quick summary of my views to date, see [the PSMedia.Asia blogpost](https://psmedia.asia/good-ais-copy/).

Today’s topic: How much is that uncertainty holding back corporate deployment of AI technology? The answer: some but not that much, even if the legal risk is far from trivial. 

Following is a kind of quick scorecard based on what I’ve seen. Note there are plenty of smart applications of AI that don’t use the foundation models, see for example Disney’s digital aging system and Apple’s audiobooks, below.

Will try to keep updating this scorecard as more products are rolled-out… please let me know what I’m missing. Lots of this comes from _[The Verge’s](https://www.theverge.com/authors/james-vincent)_[ James Vincent](https://www.theverge.com/authors/james-vincent) who is tracking this space.

Subscribe

### Company: position on generative AI

  * MICROSOFT **:** **All In,** with a US$ 10b investment in OpenAI, and many products on the way

  * GOOGLE: Spending tens of billions in AI research, but has been cautious and slow to launch products externally. Now is said to be moving into a “code red” phase of enhanced deployment, with Sergei and Page back in the Googleplex to help; but the [smart money is that they stay cautious](https://www.platformer.news/p/the-consumer-ai-era-has-begun)

  * META: Spending as aggressively as Google on research, releasing much open source, but mostly deploys internally

  * ADOBE: Has launched a stock imagery product based on Stable Diffusion, with [a policy](https://helpx.adobe.com/stock/contributor/help/generative-ai-content.html) which “prohibits submissions based on third-party content — including text prompts referring to people, places, property, or an artist’s style”; also has had to deny that data from users of its products is used for training

  * GETTY IMAGES: Opposed, is suing Stable Diffusion

  * SHUTTERSTOCK: Has launched a product based on OpenAI’s DALL-E 2 selling output but with a (not very well documented) fund to compensate creators on the sale of images and on the licensing of their work by Shutterstock to model developers. Not sure if this is applying retroactively to [OpenAI’s reported licensing of Shutterstock images](https://www.theverge.com/2022/10/25/23422359/shutterstock-ai-generated-art-openai-dall-e-partnership-contributors-fund-reimbursement).

  * DEVIANTART: Has launch a product based on Stable Diffusion, defendant in the class action, see below

  * DISNEY: Cautious. Has deployed image tool to produce digital effects of aging of actors, but using synthetic training data

  * ANDREESSEN HOROWITZ VC: “We are just entering [an AI-powered golden age](https://twitter.com/pmarca/status/1610829608626327554) of writing, art, music, software, and science. It’s going to be glorious. World historical.”

  * APPLE: A bit cautious but did tweak the Apple operating system to allow better operation of Stable Diffusion on Apple-made chips, and launched [an audio books creation service](https://authors.apple.com/support/4519-digital-narration-audiobooks) for independent authors, partnering with Ingram Coresource, using AI-generated voices (presumably licensed?) 

  * CNET (a digital publisher - many years ago I co-founded a company which was the JV partner of CNET for Asia): used AI to generate some 77 articles without telling anyone, has had to deal with the backlash when it had to admit that [41 of them needed to be revised](https://www.engadget.com/cnet-corrected-41-of-its-77-ai-written-articles-201519489.html). _I think they’ve done us a service is highlighting the flood of AI-generated clickbait to come…_

  * BUZZFEED (a digital publisher): [Has announced](https://www.theverge.com/2023/1/26/23572834/buzzfeed-using-ai-tools-personalize-generate-content-openai) it will used GPT-3 tools to enhance and personalize its content




### A bit more on DeviantArt in the class action

DeviantArt is a named defendant in the class action, and their story is not inspirational, but worth recounting. They were an artist’s community site, founded in 2000, with tools for highlighting and presenting new work by professional and aspiring digital artists. The site hosts millions of digital images. The company was sold for US$ 37m in 2017 to Wix, a NASDAQ-listed website building software as a service company with a current market cap around $5.5b.

DeviantArt was an important source of images used to train Stable Diffusion at its launch, with an something like a million images being scraped. 

DeviantArt cut a deal with StabilityAI to develop a DeviantArt-branded web-based tool built on Stable Diffusion, and available to paying members for extra fees. This tool would be further fine-tuned and trained on art in the DeviantArt website. When the tool was first announced, there was already unhappiness among digital artists about their work being used to train generative models, and the subsequent use of their names in prompts to evoke their styles. So DeviantArt announced that members could opt out of their images being used in this further fine-tuning, claiming that this measure “lets you create AI art knowing that creators and their work are treated fairly”.

This enraged some of the members, who were unhappy about the _initial_ training of the model on their works, and thought it was more appropriate that DeviantArt _protest_ the copying of their works for that initial creation of Stable Diffusion. Especially as DeviantArt’s terms of service had several clauses prohibiting use of content on the site “for commercial purposes”, including making derivative works. 

To make matters worse, shortly after ending a webinar to discuss the new service with members, DeviantArt changed its terms of service to allow “Data Scraping and Machine Learning Activities” under certain circumstances, and further, devolving the responsibility for enforcing that policy to individual members.

This narrative is drawn from the class action complaint, but it seems completely in line with the story as I saw it playing out on Twitter in November 2022. Yucks! The class action points out that DeviantArt is now competing with—and displacing the market for—digital illustrators whose works were copied without permission.

### A lawyer’s reading of the StableDiffusion lawsuit

And speaking of the Stable Diffusion lawsuit, here’s the [first comprehensive commentary](https://katedowninglaw.com/2023/01/26/an-ip-attorneys-reading-of-the-stable-diffusion-class-action-lawsuit/) I’ve seen from an actual copyright lawyer. Kate Downing raises two issues with the suit, first, the definition of the class, and secondly, the characterization of the operation of the model. I’ll leave consideration of the class to those who understand such things, but let’s look at the characterization of the operation of the model, which I am sure will be key. 

She says “the claim that the output is nothing more than the input is deeply specious.” I am not sure that _is_ the claim actually, it’s a little more sophisticated, but like I said [a couple of weeks ago,](https://aicopyright.substack.com/p/battle-of-the-metaphors) this is the caricature of the model that drives Stable Diffusionists nuts. 

Downing goes on to say 

> “[the] question of how much of the output should be credited to the training data versus to the model’s processing of the training data should be at the heart of the debate over whether Stable Diffusion’s use of the various images as training data is truly transformative and thus eligible for copyright’s fair use defense (or perhaps even to the question of whether the output is eligible for copyright protection at all).”

 _(As you know, I think there are other reasons the fair use case is not so strong… though I guess we will soon know more about the US Supreme Court’s definition of transformative use!)_

To me this key paragraph reads a bit like a hold-over from our old metaphors of software, that the software designer has created more or less from scratch a set of processing routines that adds value and creativity to the inputs, at least when used by a skilled user. These generative models are a bit different; they create a system for interpolating from all the images in the dataset, but there is no principle of image creation behind that, just better and better statistical association of visual features with words. (There _is_ the ability to mobilize — _“understand”_ — features.) And I don’t think we can dismiss the “corner cases” of models copying their input so easily as Downing does, even if they are all filtered out in deployment. Among other things, it is these edge and corner cases that tell us something important about how the models work.

It will be a war of the metaphors. I share Downing’s view that “it’s going to be easy for the defense to present alternative analogies and narratives to those presented by the plaintiffs here.” I’m not sure that these alternative analogies will be any better at capturing what exactly is going on with the models but the battle of the metaphors will certainly present a headache to anyone trying to adjudicate this!

[Share](https://aicopyright.substack.com/p/its-going-to-be-glorious-world-historical?utm_source=substack&utm_medium=email&utm_content=share&action=share)

Finally, I’m not sure if you can bear to watch Jason’s hugely self-conscious presentation of his thoughts, but this is a pretty clever example of the hype around AI-generated content. It’s going to be glorious, world-historical!

[![Twitter avatar for @JasonSilva](https://substackcdn.com/image/twitter_name/w_96/JasonSilva.jpg)Jason Silva @JasonSilvaMy thoughts on AI GENERATED ART ](https://twitter.com/JasonSilva/status/1607928319957422081)

[2:35 AM ∙ Dec 28, 2022

* * *

3,326Likes320Retweets](https://twitter.com/JasonSilva/status/1607928319957422081)

Much better watching is this video summary of the AI copyright problem, from SolarSands, on Youtube.

Title: Algorithmic disgorgement, ISIS executions...
Subtitle: And other developments of the week ended 1 October
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/algorithmic-disgorgement-isis-executions
---
_A weekly email update on developments in the world of large language models (LLMs) and image synthesizers, with a specific focus on the question of how the legal uncertainty around these models will be sorted. For more background, please read[here.](https://aicopyright.substack.com/about)_

* * *

#### The horrible stuff being used to train the latest image generation models…

Vice Media’s [Chloe Xiang](https://www.vice.com/en/contributor/chloe-xiang) has been doing strong reporting on the image datasets behind some of the new image synthesizer models, her latest an article entitled [AI Is Probably Using Your Images and It's Not Easy to Opt Out](https://www.vice.com/en_asia/article/3ad58k/ai-is-probably-using-your-images-and-its-not-easy-to-opt-out) a follow up from a Sept 21 piece, [ISIS Executions and Non-Consensual Porn Are Powering AI Art](https://www.vice.com/en_asia/article/93ad75/isis-executions-and-non-consensual-porn-are-powering-ai-art).

She engaged with LAION, the team behind the dataset used to train the Stable Diffusion model, and Google’s forthcoming ImaGen model. (DALL-E and Midjourney have not revealed on what data they have trained their models). LAION describes itself as “a non-profit organization with members from all over the world, aiming to make large-scale machine learning models, datasets and related code available to the general public.”

Here is Xiang on the datasets:

>  _“They are, by design, scraping images that they do not own, may not be classified correctly, and that copyright holders and subjects may or may not have given their permission to be used to train AI tools. Motherboard previously reported that the LAION-5B dataset, which has more than 5 billion images, includes photoshopped celebrity porn, hacked and stolen nonconsensual porn, and graphic images of ISIS beheadings. More mundanely, they include living artists' artwork, photographers’ photos, medical imagery, and photos of people who presumably did not believe that their images would suddenly end up as the basis to be trained by an AI. There is currently not a good way to opt out of being included in these datasets, and in the cases of tools like DALL-E and Midjourney, there is no way to know what images have been used to train the tools because they are not open-source.”_

It looks like LAION claims legal legitimacy from the fact that their datasets are links only… If you want to use their data to train a model they only send you links, model buildings have to do the copying of the images from across the internet themselves. However they also admit that they did copy the photos in order to calculate “similarity scores” between the images and text used to describe them. I’m still digging into the ways that the image generators are built, so I’ll try for an update on all this in the next couple of weeks.

Reporter Xiang is as or more concerned about issue of bias, privacy violation and the abusive potential of the images used to train these models as the copyright implications and their impact on creators. But she does see the lack of accountability on all aspects of this data as linked. At the end of her story she cites [a paper](https://yjolt.org/sites/default/files/23_yale_j.l._tech._special_issue_1.pdf) from US Federal Trade Commissioner Rebecca Kelly Slaughter, who is directly concerned with the harms that come from AI, and who has a refreshingly clear approach to illegitimate data:

>  _“The premise is simple: when companies collect data illegally, they should  
>  not be able to profit from either the data or any algorithm developed using it.”_

The FTC has already enforced “logarithmic disgorgement”, ie the destruction of software and data, in the case of a company that violated its promises to users on the collection of facial recognition data. 

Also retrieved from Xiang’s article, the URL of a service which allows you to check and see if your own image (or your author’s) has been used in LAION training data. 

https://haveibeentrained.com

#### In the style of…

One of the recommendations for creating good prompts for image generators like DALL-E2, Midjourney and Stable Diffusion is that you should brief the generator on the style you would like to achieve. And it’s no surprise that many users of these tools will ask for works in the style of well-known named artists. With a bit of luck and practice, the results are clearly recognizable as being in a particular artist’s style. The _Forbes_ article by Rob Salkowitz cited [in last week’s newsletter](https://aicopyright.substack.com/p/this-requires-a-legislative-solution) quotes commercial artist Greg Rutkowski, whose name shows up in hundreds of thousands of prompts captured by prompt search engine [libraire.ai](https://libraire.ai/).

>  _“As a digital artist, or any artist, in this era, we’re focused on being recognized on the internet. Right now, when you type in my name, you see more work from the AI than work that I have done myself, which is terrifying for me. How long till the AI floods my results and is indistinguishable from my works?”_

If you want to lose several hours, try using libraire.ai or a similar service at [lexica.art](https://lexica.art/), which search prompts and images created with Stable Diffusion. If you are representing a well-known image creator, maybe you need to. Libraire turned up 52,482 results for the search “Studio Ghibli”.

Furthermore, there is [now a marketplace](https://promptbase.com/) for prompts, where particularly good ones can be sold. Here is the story as reported by [Verge](https://www.theverge.com/2022/9/2/23326868/dalle-midjourney-ai-promptbase-prompt-market-sales-artist-interview), with an interview with a prompt writer who has, this should be no surprise, also launched [a GPT-3 based tool](https://typestitch.com) to help you generate prompts… 

One proposal floating around on the Discords (the chat sites popular with AI users) — pay a royalty to artists whose names are used in prompts. Not a bad suggestion, but it doesn’t solve the question of the rights in the images and texts used to create the tool in the first place.

Here’s just one example of an artist-based prompt and the resulting image.

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F723bcd0c-8543-4124-b1c3-04a39675d77d_1280x704.webp)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F723bcd0c-8543-4124-b1c3-04a39675d77d_1280x704.webp)

###### Prompt: “Single flooded simple wooden arch! tower, very coherent and colorful high contrast!! masterpiece by rene magritte simon stalenhag carl spitzweg syd mead norman rockwell edward hopper james gilleard, minimalist, dark shadows, sunny day, hard lighting”

#### And in a follow up to the Getty Images announcement, what does competitor Shutterstock do? 

Nothing, or at least, not much. CEO Paul Hennessy releases an [anodyne statement](https://www.shutterstock.com/blog/ai-generated-media-with-shutterstock) that says remarkably little: “we’re taking steps to look at the impact AI-generated art has on our consumers and contributors.”

#### James Earl Jones as Darth Vader will live on forever

Over the weekend, Disney announced that they were hiring Ukrainian startup [Respeecher](https://www.respeecher.com/) to create an AI-generated version of James Earl Jones’ voice, under license, as the character Darth Vader. This sort of speech synthesis technology has been around for some time now, but the licensing of this iconic voice for this iconic character does mark a milestone. Jones is 91, and was thinking of maybe winding down his voice work for Disney. According to the story, the AI-version hearkens more to his original voice work of 45 years ago than to his recent work.

#### More from the quality papers on the development of image synthesizers

 _[Washington Post:](https://www.washingtonpost.com/technology/interactive/2022/artificial-intelligence-images-dall-e/)_[ “AI can now create any image in seconds, bringing wonder and danger”](https://www.washingtonpost.com/technology/interactive/2022/artificial-intelligence-images-dall-e/)

#### The latest thing AI models can generate: 3d models

C[hipmaker nVidia has announced](https://www.awn.com/news/nvidia-get3d-ai-model-populate-virtual-worlds-revealed) a new model that uses 2D images to generate 3D digital models. However it was trained on “synthetic data”, 2D renders of 3D models, ie apparently without recourse to image databases scraped from the internet. (nVidia also recently announced a new LLM with an innovative training module.)

Then Google announced something similar!

[![Twitter avatar for @poolio](https://substackcdn.com/image/twitter_name/w_96/poolio.jpg)Ben Poole @poolio](https://t.co/4xI2VHcoQW">https://t.co/4xI2VHcoQW</a><br><br>We optimize a NeRF from scratch using a pretrained text-to-image diffusion model. No 3D data needed!<br><br>Joint work w/ the incredible team of <a href="https://twitter.com/BenMildenhall?ref_src=twsrc%5Etfw">@BenMildenhall</a> <a href="https://twitter.com/ajayj_?ref_src=twsrc%5Etfw">@ajayj_</a> <a href="https://twitter.com/jon_barron?ref_src=twsrc%5Etfw">@jon_barron</a><a href="https://twitter.com/hashtag/dreamfusion?src=hash&amp;ref_src=twsrc%5Etfw">#dreamfusion</a> <a href="https://t.co/YeG0zaFxuu">pic.twitter.com/YeG0zaFxuu</a></p>&mdash; Ben Poole \(@poolio\) <a href="https://twitter.com/poolio/status/1575576632068214785?ref_src=twsrc%5Etfw">September)

[Happy to announce DreamFusion, our new method for Text-to-3D! ](https://t.co/4xI2VHcoQW">https://t.co/4xI2VHcoQW</a><br><br>We optimize a NeRF from scratch using a pretrained text-to-image diffusion model. No 3D data needed!<br><br>Joint work w/ the incredible team of <a href="https://twitter.com/BenMildenhall?ref_src=twsrc%5Etfw">@BenMildenhall</a> <a href="https://twitter.com/ajayj_?ref_src=twsrc%5Etfw">@ajayj_</a> <a href="https://twitter.com/jon_barron?ref_src=twsrc%5Etfw">@jon_barron</a><a href="https://twitter.com/hashtag/dreamfusion?src=hash&amp;ref_src=twsrc%5Etfw">#dreamfusion</a> <a href="https://t.co/YeG0zaFxuu">pic.twitter.com/YeG0zaFxuu</a></p>&mdash; Ben Poole \(@poolio\) <a href="https://twitter.com/poolio/status/1575576632068214785?ref_src=twsrc%5Etfw">September)[dreamfusion3d.github.io](http://dreamfusion3d.github.io) We optimize a NeRF from scratch using a pretrained text-to-image diffusion model. No 3D data needed! Joint work w/ the incredible team of @BenMildenhall @ajayj_ @jon_barron #dreamfusion

[8:01 PM ∙ Sep 29, 2022

* * *

3,228Likes867Retweets](https://t.co/4xI2VHcoQW">https://t.co/4xI2VHcoQW</a><br><br>We optimize a NeRF from scratch using a pretrained text-to-image diffusion model. No 3D data needed!<br><br>Joint work w/ the incredible team of <a href="https://twitter.com/BenMildenhall?ref_src=twsrc%5Etfw">@BenMildenhall</a> <a href="https://twitter.com/ajayj_?ref_src=twsrc%5Etfw">@ajayj_</a> <a href="https://twitter.com/jon_barron?ref_src=twsrc%5Etfw">@jon_barron</a><a href="https://twitter.com/hashtag/dreamfusion?src=hash&amp;ref_src=twsrc%5Etfw">#dreamfusion</a> <a href="https://t.co/YeG0zaFxuu">pic.twitter.com/YeG0zaFxuu</a></p>&mdash; Ben Poole \(@poolio\) <a href="https://twitter.com/poolio/status/1575576632068214785?ref_src=twsrc%5Etfw">September)

#### The latest thing AI models can generate: short videos

Meta has shared some early results from a new model that can generate short videos from text prompts. 

[![Twitter avatar for @AntoineBordes](https://substackcdn.com/image/twitter_name/w_96/AntoineBordes.jpg)Antoine Bordes @AntoineBordesToday we release Make-A-Video, a single system that lets you generate high-quality videos from text prompts like "a knight riding in the countryside"! @MetaAI is building the future of creative content! ![Twitter avatar for @MetaAI](https://substackcdn.com/image/twitter_name/w_40/MetaAI.jpg)Meta AI @MetaAIWe’re pleased to introduce Make-A-Video, our latest in #GenerativeAI research! With just a few words, this state-of-the-art AI system generates high-quality videos from text prompts. Have an idea you want to see? Reply w/ your prompt using #MetaAI and we’ll share more results. https://t.co/q8zjiwLBjb](https://twitter.com/MetaAI?ref_src=twsrc%5Etfw">@MetaAI</a> is building the future of creative content! <a href="https://t.co/m0h8jbckKo">https://t.co/m0h8jbckKo</a> <a href="https://t.co/OlOfO84b4A">pic.twitter.com/OlOfO84b4A</a></p>&mdash; Antoine Bordes \(@AntoineBordes\) <a href="https://twitter.com/AntoineBordes/status/1575547951706910720?ref_src=twsrc%5Etfw">September)

[6:07 PM ∙ Sep 29, 2022

* * *

141Likes15Retweets](https://twitter.com/MetaAI?ref_src=twsrc%5Etfw">@MetaAI</a> is building the future of creative content! <a href="https://t.co/m0h8jbckKo">https://t.co/m0h8jbckKo</a> <a href="https://t.co/OlOfO84b4A">pic.twitter.com/OlOfO84b4A</a></p>&mdash; Antoine Bordes \(@AntoineBordes\) <a href="https://twitter.com/AntoineBordes/status/1575547951706910720?ref_src=twsrc%5Etfw">September)

And all of this just last week…

### New Products or Services built on LLMs and other models

 _Just a few of the products launched or updated on[ProductHunt](https://www.producthunt.com) in the last week_

#### AI Grammar Checker - Grammica

##### Check your writing errors with grammica - https://grammica.com

‘Rewording your article to get unique and plagiarism free content.’

 _More like a rewriter — hadn’t thought about this risk before: the models can plagiarize without plagiarizing_

#### Peregrine

##### Expressive Generative Text-to-Speech Model by Play.ht - https://play.ht/ultra-realistic-voices/

Use cases: videos, audiobooks, e-learning, IVR systems

#### Text to Image Editor

##### 'Photoshop' using only text - https://imgeditor.zmo.ai/

“No photoshop skills needed anymore, transfer any image to what you want simply using text, with zero learning barrier. Just focus on your imagination, AI will do all the rest” 

_The tech commentators are starting to talk about the new AI tools disaggregating conception from substantiation (or should that be instantiation). The creative act is to come up with the idea, the AI does the rest. At the very least this way of thinking should push out the distracting discussion of whether a synthesized image can be copyrighted. Clearly the writer of the prompts should be able to claim copyright, if the terms of use of the software allow…(a big if, and there’s a whole ‘nother question for a future newsletter…)_

#### Quazel

##### Get conversational language practice by talking to an AI - https://talk.quazel.com

“In unscripted and dynamic conversations, learners can respond with whatever comes to mind just like you would in real-life conversations.”

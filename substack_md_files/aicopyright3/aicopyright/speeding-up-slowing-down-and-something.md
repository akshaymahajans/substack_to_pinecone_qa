Title: Speeding up, slowing down, and something in the fridge for you...
Subtitle: Plus more evidence that models copy
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/speeding-up-slowing-down-and-something
---
### Speeding up

Well Chat-GPT has well and truly made a breakthrough, up to 100 million users in a matter of two months, according to recent reports. 

And here’s a tweet that captures some of the news from just January, a few of these stories (only a few!) mentioned here:

Thanks for reading AI and Copyright! Subscribe for free to receive new posts and support my work.

Subscribe

[![Twitter avatar for @AlphaSignalAI](https://substackcdn.com/image/twitter_name/w_96/AlphaSignalAI.jpg)Lior⚡ @AlphaSignalAIEverything that happened in AI this January. Ready for February? ![Image](https://substackcdn.com/image/fetch/w_600,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fpbs.substack.com%2Fmedia%2FFn_FFgZWIAAPFq-.png)](https://twitter.com/AlphaSignalAI/status/1621232101646295041)[7:40 PM ∙ Feb 2, 2023

* * *

1,463Likes451Retweets](https://twitter.com/AlphaSignalAI/status/1621232101646295041)

My intray is flooded with invites to seminars and webinars on generative AI, and there are more and more “my experience with Chat-GPT” stories in media every day. And the range of new generative AI products being developed is, well, astounding, to pick just two:

##### Empathy

Bereavement assistance platform Empathy has introduced [an AI tool](https://u5080173.ct.sendgrid.net/ss/c/0dORZiTaa00yDlF_VpPyVV0ri9mrtbMb8IfBejUbHpxrl_v2u29l_pRmucr_ubfd6qsKy_FIrC5RjeMKXsL2pKn7UQLTX2OcZ-l7yoiUQ5Y9DryBoyW670HYuSpE4WW-kWKdS8bYCP4TcuBwLzCRtw/3td/4gmvKzmGSoi69ud4_EJeyg/h138/iuVjFbxb0lrr2WBmVGFOAyIk3A6cwCoOIg9NTUP6WWg) that automatically generates obituary drafts based on information provided by family.

##### Lunchbox

And a company called Lunchbox has launched an AI food photography generator, a service targeted at restaurants. 

> “What our operators are saying is, ‘wait, if I had something in the fridge, I can now promote it very quickly,’ the Lunchbox CEO says. ‘I don’t have to go ahead and wait for a photographer to turn things around. I can test something out very live, very quickly.’”

The journalist from photographer’s site [PetaPixel](https://petapixel.com/2023/01/30/lunchbox-replaces-photographers-as-the-first-ai-image-generator-for-food/) did muse that “this may cause potential problems if the food in the images is nothing like the actual dishes served up in the restaurants, _let alone real.”_ He helpfully[ mentions a case](https://petapixel.com/2022/05/20/mcdonalds-and-wendys-sued-for-misleading-ad-photos-of-burgers/) where McDonald’s was sued for making its burgers in its marketing pix appear bigger than they were in life…

Subscribe

### And slowing down (despite the fast food)

So as the story speeds up, I’m going to try and slow down, and take some time to think about how best to spend the energy I’m now putting into the newsletter. This may mean a slowdown in output.

My hope is to move from a one-way newsletter to more time in conversations, particularly to help copyright holders and creators figure out the best way to approach these changes. Please reach out if you have ideas about the best way to do that. The readership of the newsletter is small but mighty, with readers in senior roles in publishing, the law, the arts, etc, as well as younger creators with an interest.

### Meanwhile, from the generate-and-filter pipeline, some copying and interpolation

Meanwhile, [a new preprint](https://doi.org/10.48550/arXiv.2301.13188) on Arxiv, with authors from industry (Google, OpenAI, etc)[1](https://aicopyright.substack.com/p/speeding-up-slowing-down-and-something#footnote-1-100653334), takes a fresh look at whether diffusion models reproduce their training data. Moreover they present this as key to the question of whether the models create novel images or just interpolate their training data, ie battle of the metaphors baseline version. The verdict: “With a generate-and-filter pipeline, we extract over a thousand training examples from state-of-the-art models, ranging from photographs of individual people to trademarked company logos.” 

The authors are sensitive to copyright and privacy questions throughout, and acknowledge that their paper “raises questions on how diffusion models work and how they should be responsibly deployed.” 

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff047b6d0-5214-43f3-adc8-5519cb296609_1636x412.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff047b6d0-5214-43f3-adc8-5519cb296609_1636x412.png)

Some perspective: using Stable Diffusion for example, they found 109 duplicated images out of 175m images generated from 350,000 text prompts. A lot less (four orders of magnitude less!) than the 2% in the 2022 Somepalli paper, but then Carlini et al are counting only “images that are reproduced with near pixel-perfect accuracy”. 

Now as discussed in previous newsletters, this may be “just” “overfitting”, too much training on insufficiently general data, but I’m less and less patient with that as an excuse for the generative models, as 1) the world is not a very general thing, there will always be lots of one-offs and category breakers, images “out of distribution ”, no matter how much model-patching you do or data you add[2](https://aicopyright.substack.com/p/speeding-up-slowing-down-and-something#footnote-2-100653334), and 2) the edge and corner are where we _see_ the models operating. Yes, they can create things we haven’t seen before, but hey, it’s still the (latent encodings/compressions of the) training images that are being used in the process, as we can tell in the cases where the model can’t find enough other images to bring to the mix.

The authors put it this way:

> “Do large-scale models work by generating novel output, or do they just copy and interpolate between individual training examples? If our extraction attacks had failed, it may have refuted the hypothesis that models copy and interpolate training data; but because our attacks succeed, this question remains open.”
> 
> Carlini, Hayes, Milad, et al (Jan 30, 2023)

### And good news out the UK

Got a welcome email from the Publishers Association in UK just now that the UK IP Office’s proposal for a broad blanket exception for copying for Text and Data Mining has been withdrawn. This was announced in the House of Lords [debate](https://hansard.parliament.uk//commons/2023-02-01/debates/7CD1D4F9-7805-4CF0-9698-E28ECEFB7177/ArtificialIntelligenceIntellectualPropertyRights#contribution-D574C991-51DD-41C7-9936-64BB36FCD47D) on the communications and digital committee report.

> “When I returned to office, the Minister of State, Department for Digital, Culture, Media and Sport, my hon. Friend the Member for Hornchurch and Upminster (Julia Lopez), and I met promptly to look at the issue. We have written around to make it clear to other Ministers that the proposals were not correct, that we have met with a huge response, which should have been picked up in the pre-consultation before the proposals were announced, and that we are looking to stop them.
> 
> “We will have a rather deeper conversation with the all-party group, whom I met yesterday, and with experts in both Houses and in the industry—creators, platforms, publishers, broadcasters and digital intermediaries—to ensure that we do not rush precipitately into a knee-jerk move that is wrong. We must try to anticipate the challenges that are coming and to get a regulatory framework in the UK that can keep pace with the pace of the technology and the issues it raises.” 
> 
>   * George Freeman, UK’s Minister for Science, Research and Innovation
> 
> 


Exceptions are just a very blunt tool when things are changing quickly… glad to see that the UK government recognizes this.

[Share AI and Copyright](https://aicopyright.substack.com/?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/speeding-up-slowing-down-and-something#footnote-anchor-1-100653334)

Nicholas Carlini, Jamie Hayes, Milad Nasr, Matthew Jagielski, Vikash Sehwag, Florian Tramèr, Borja Balle, Daphne Ippolito, Eric Wallace, Extracting Training Data from Diffusion Models, arXiv:2301.13188 [cs.CR]

[2](https://aicopyright.substack.com/p/speeding-up-slowing-down-and-something#footnote-anchor-2-100653334)

See Gary Marcus’ latest critiques of the neural net approach, [here ](https://substack.com/inbox/post/100472453)and [here](https://garymarcus.substack.com/p/gaslighting-and-reality-in-ai). All very well presented but as we hear more we realize this is a feud with roots going back 30 years…

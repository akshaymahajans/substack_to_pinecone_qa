Title: We’re all going to poop rainbows!
Subtitle: A (more or less) weekly email update on developments in the world of Foundation Models, with a specific focus on the question of how their legal uncertainty will be sorted
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/were-all-going-to-poop-rainbows
---
### **Shutterstock announces a payment path for artists whose works have been used to train AIs...**

The first news we have that some copyrighted material was indeed licensed in order to train one of the big Foundation Models (in this case DALL-E) comes from the press release announcing the new Shutterstock-DALL-E partnership, which includes a path to paying artists whose work was used to train DALL-E. 

From the press release [here](https://www.shutterstock.com/press/20435):

>  _“The data we licensed from Shutterstock was critical to the training of DALL-E,” said Sam Altman, OpenAI’s CEO. “We’re excited for Shutterstock to offer DALL-E images to its customers as one of the first deployments through our API, and we look forward to future collaborations as artificial intelligence becomes an integral part of artists’ creative workflows.”_

and

>  _Shutterstock believes that AI-generated content is the cumulative effort of its contributing artists. In an effort to create a new industry standard and unlock new revenue streams for the Company’s artist community, Shutterstock has also created the framework to provide additional compensation for artists whose works have contributed to develop the AI models. The Company also aims to compensate its contributors in the form of royalties when their intellectual property is used._

Not sure the legal copyright position implied in “AI-generated content is the cumulative effort of its contributing artists”, exactly, but the point is one many artists agree with. 

#### Questions: 

  * Remind me to check the licensing terms for selling images on Shutterstock. Will Shutterstock artists be given an opt-out for future model training?

  * Is this a bid to reduce the legal uncertainty around the troublesome “fair use” claim around training data? Or a bid to recruit artists? Or both? 

  * So how exactly did OpenAI train DALL-E2? What other datasets were used, and can we expect more such deals in future? Were Shutterstock images licensed to create the model? Or to tune it? 

  * If Shutterstock images were licensed, couldn’t other datasets to build (or tune, or refine) other models have been licensed? _(See next point on Stability’s business model)_

  * What does this mean for model-builders who used huge amounts of copyrighted text to train their models without a license?




This steals the thunder a bit from Emad Mostaque’s almost announcement that Stability.ai saw the artists’ claim on training data to be legitimate. See next section. 

### Stability AI comes out in Style

The Stability coming out party at the Exploratorium in San Francisco, after the announcement of their Series A funding round of US$ 101m seems to have been quite the event. I haven’t yet watched the video (available [here](https://youtu.be/1Uy_8YPWrXo)), but one quote from Stability founder Emad Mostaque awas captured by the _[New York Times](https://www.nytimes.com/2022/10/21/technology/generative-ai.html)_[ report](https://www.nytimes.com/2022/10/21/technology/generative-ai.html):

“So much of the world is creatively constipated, and we’re going to make it so that they can poop rainbows,” 

Er, OK! Let’s not put that in a image generation prompt thank you very much. 

In addition to the NYT story is [an interview that Mostaque recorded with Kevin Roose and Casey Newton](https://www.nytimes.com/2022/10/21/podcasts/generative-ai-is-here-who-should-control-it.html). The interview is well-worth a listen for many reasons (what’s _your_ generative-content strategy?), but let’s start with the legal uncertainty question that is this newsletter’s focus. Mostaque did not address that directly, but did seem to acknowledge an obligation to the creators whose works had trained the model. He was asked a question about the concerns raised by artist Greg Rutkowski (covered [in this newsletter](https://aicopyright.substack.com/p/algorithmic-disgorgement-isis-executions) on October 1st).

>  _So I think this is a very valid thing, I mean the fears and concerns around that. So like I said, it was trained on 2 billion images. It was a snapshot of Google Images, basically. So anything you could find through there, you can find through here._
> 
>  _And then it learns from the relationship between words and images. That’s why you need a huge frickin’ supercomputer to kind of do that. So it learns principles. You can’t recreate any image from the data set, but it understands what a cup is or what Greg is and other things._
> 
>  _In fact, the interesting thing is our data set didn’t actually have very many pictures of Greg Rutkowski. Instead it was another model that was released by OpenAI, which had much more of his. We don’t know because we don’t know what the data set is that was part of this that introduced the concept of Greg into this model._

But at this point in the interview (around 41:33 into the podcast), Roose interjects with an annoying (to me) fit of techbro giggling that allows Mostaque to escape without having to say what he means in more detail.

Newton attempts to get back on track, but his follow up question is too general, and this allows Mostaque to pivot to a broader point about “new artistic tools don’t mean the end of art, photography didn’t kill painting…” which is all well and good but avoids the copyright / moral right issue that Mostaque was addressing moments before. See [the transcript here](https://www.nytimes.com/2022/10/21/podcasts/generative-ai-is-here-who-should-control-it.html?showTranscript=1).

Evidently Mostaque made further comments on the possibility of compensating artists in a “fireside chat” with Elad Gill, but I haven’t been able to track that down. In any case I would not be surprised to see Stability make a statement in this area soon.

The Mostaque interview is well worth a listen/read, and I’ll be covering different aspects of it in future notes. He lays out more of the Stability business strategy, which includes customized versions of the Stable Diffusion model, fine-tuned on specific branded content, under license, as per this tweet (as proof-of-concept, not sure @Nitrosocke licensed her training data):

[![Twitter avatar for @_akhaliq](https://substackcdn.com/image/twitter_name/w_96/_akhaliq.jpg)AK @_akhaliq](https://twitter.com/_akhaliq/status/1585312074464636929)

[Spider-Verse Diffusion: fine-tuned Stable Diffusion model trained on movie stills from Into the Spider-Verse by @Nitrosocke @huggingface model: ](https://twitter.com/_akhaliq/status/1585312074464636929)[huggingface.co/nitrosocke/spi…](https://huggingface.co/nitrosocke/spider-verse-diffusion)

![Image](https://substackcdn.com/image/fetch/w_600,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fpbs.substack.com%2Fmedia%2FFgAo2Y1WAAEMR5Y.jpg)

[4:47 PM ∙ Oct 26, 2022

* * *

335Likes34Retweets](https://twitter.com/_akhaliq/status/1585312074464636929)

### CNN journalist Rachel Metz on the artist training question…

This is [a very nicely put together story](https://edition.cnn.com/2022/10/21/tech/artists-ai-images/index.html). I gave her this feedback… 

[![Twitter avatar for @katong](https://substackcdn.com/image/twitter_name/w_96/katong.jpg)Peter Schoppert @katong@rachelmetz Great write-up. I would not be sure that fair use covers the unauthorised copying that created training data. The fairness of fair use must be based on the facts of the case, tested against a number of factors, including the economic impact of the copying.](https://twitter.com/katong/status/1585394315303735297)[10:13 PM ∙ Oct 26, 2022](https://twitter.com/katong/status/1585394315303735297)

### More journalism: coverage of the potential Copilot suit

In last weeks’ description of the impact of the Copilot suit I missed [a really good update](https://www.theregister.com/2022/10/19/github_copilot_copyright/) from the UK’s _The Register._ Another CEO claiming a Fair Use defense for the training data:

>  _When GitHub introduced a beta version of Copilot in 2021, and questions about copyright and licensing were raised, then-CEO Nat Friedman opined "training ML systems on public data is fair use [and] the output belongs to the operator, just like with a compiler. We expect that IP and AI will be an interesting policy discussion around the world in the coming years, and we're eager to participate!"_

 _ **If you’ve read this far in the newsletter you must agree it is more than interesting, it’s downright fascinating!**_

There’s another killer quote in the piece:

>  _When Berkeley Artificial Intelligence Research considered this issue back in 2020, the group suggested that perhaps training large language models from public web data is fundamentally flawed, given concerns about privacy, bias, and the law. They proposed that tech companies invest in collecting better training data rather than hoovering up the web. That doesn't appear to have happened._

### Another tweet of interest

[![Twitter avatar for @tszzl](https://substackcdn.com/image/twitter_name/w_96/tszzl.jpg)roon @tszzlan individual human lifetime is more analogous to few shot prompt engineering of the pretrained human foundation than learning language or reasoning from scratch ](https://twitter.com/tszzl/status/1585019794193256448)[![](https://substackcdn.com/image/fetch/w_600,h_314,c_fill,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F979c2bea-6510-4284-9f69-eea13ad6b09a_1200x709.png)en.wikipedia.orgBaldwin effect - Wikipedia](https://en.wikipedia.org/wiki/Baldwin_effect)[9:25 PM ∙ Oct 25, 2022

* * *

116Likes2Retweets](https://twitter.com/tszzl/status/1585019794193256448)

That makes me think there’s some good work to be done to figure out what LLM emergent properties tell us about the Chomsky vs Skinner debate on human language… But that’s a whole ‘nother realm… 

Thanks for reading AI and Copyright! Subscribe for free to receive new posts.

Subscribe

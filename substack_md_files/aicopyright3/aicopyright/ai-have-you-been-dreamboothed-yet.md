Title: AI学習禁止! Have you been Dreamboothed yet?
Subtitle: and other updates from November 2, 2022
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/ai-have-you-been-dreamboothed-yet
---
### Manga fans protest! AI学習禁止! 

The excellent _Rest of the World_ [reported on the manga fan backlash against AI-art ](https://restofworld.org/2022/ai-backlash-anime-artists/)generated in the style of well-known manga artists. 

> _Generative AI might have been dubbed Silicon Valley’s “[new craze](https://www.nytimes.com/2022/10/21/technology/generative-ai.html),” but beyond the Valley, hostility and skepticism are already ramping up among an unexpected user base: anime and manga artists. In recent weeks, a series of controversies over AI-generated art — mainly in Japan, but also in South Korea — have prompted industry figures and fans to denounce the technology, along with the artists that use it._

The article quotes a Tokyo-based lawyer Kazuyasu Shiraishi, as saying that Tokyo’s 2018 copyright law allows copying for machine learning under exception. Well he’s a lawyer and I’m not, but my own understanding of the relevant Article 30-4 of the Japanese law is that it takes into account the uses of the models so trained. Specifically, such copying would only be allowed if “it is not [the copier’s] purpose to personally enjoy **or cause another person to enjoy** the thoughts or sentiments expressed in that work”. And separately, that “this does not apply if the action would unreasonably prejudice the interests of the copyright owner in light of the nature or purpose of the work or the circumstances of its exploitation.”[1](https://aicopyright.substack.com/p/ai-have-you-been-dreamboothed-yet#footnote-1-82099108)

If the purpose of the copying is to allow the creation of more works in the style of the creator copied, _and_ in a way which prejudices the interests of the copyright owner, the exception would not seem to give _any_ shield to training data copying. 

_The Twitter storms around this topic are impressive._

###  Another must read from Andy Baio: “[How one unwilling illustrator found herself turned into an AI model](https://waxy.org/2022/11/invasive-diffusion-how-one-unwilling-illustrator-found-herself-turned-into-an-ai-model/)”

This covers the latest trend, also referenced in the article above, of fine-tuning image generators to create works in the style of a single illustrator, or alternatively, to create works with a single subject in many styles. The extra trained requires as few as a couple of dozen additional images . As Baio describes it, in as little as 20 minutes, and spending about $0.40 on extra “compute”, using a technique called DreamBooth he was able to train a model to spit out self-portraits in different styles. 

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F50b95d00-3237-4bdf-928f-3e7d9efafe09_2254x1416.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F50b95d00-3237-4bdf-928f-3e7d9efafe09_2254x1416.png)

> _Frankly, it was shocking how little effort it took, how cheap it was, and how immediately fun the results were to play with. Unsurprisingly, a bunch of startups have popped up to make it even easier to DreamBooth yourself, including[Astria](https://www.astria.ai/), [Avatar AI](https://avatarai.me/), and [ProfilePicture.ai](https://www.profilepicture.ai/)._

But the bulk of the article is his interview with a well-known professional 2D artist Hollie Mengert and a Redditor named MysteryInc152 who created a DreamBooth to imitate her style. Baio’s reporting of the thinking of MysteryInc152 reveals where the discourse has gone.

>  _His take was very practical: he thinks it’s legal to train and use, likely to be determined fair use in court, and you can’t copyright a style. Even though you can recreate subjects and styles with high fidelity, the original images themselves aren’t stored in the Stable Diffusion model, with over 100 terabytes of images used to create a tiny 4 GB model. He also thinks it’s inevitable: Adobe is adding generative AI tools to Photoshop, Microsoft is adding an image generator to their design suite. “The technology is here, like we’ve seen countless times throughout history.”_

But even our AIbro does recognize that there is something else at work when an AI is trained to reproduce work in the style of a particular living artist who might not be keen on the result. 

_Read the piece!_

### More fair use counters from Neil Turkewitz

On Twitter I came across [the account](https://twitter.com/neilturkewitz) of Neil Turkewitz, copyright lawyer, who has been critiquing the “copying to train models is fair use” argument for some time. He’s written a number of very useful posts on the topic dating back at least to 2019, and he’s engaging on Twitter with journalists and others on the topic. I’ll discuss one of his posts briefly here:

#### [AI, Copyright & Fair Use: Avoiding the Artificial in Intelligence & Maintaining our Humanity](https://medium.com/@nturkewitz_56674/ai-copyright-fair-use-avoiding-the-artificial-in-intelligence-maintaining-our-humanity-82af5f48ca37), Feb 2, 2020

Here he critiques a Jan 2020 submission from the Business Software Alliance which argues that “creating a database of lawfully accessed works for use as training data for machine learning will almost always be considered non-infringing in circumstances where the output of that process does not compete with the works used to train the AI system.” 

He makes a very important point about the flawed logic of “copying is how computers read” argument, which seems to be inspiring the folks who have argued for TDM exceptions.

>  _BSA likens machine “learning” to how a human might ingest a book, combing through the protected expression while retaining the unprotected ideas. But while a human might very well operate in that manner, it’s a terrible stand-in for the operation of machines which by their very nature “learn” through reproduction, with such reproductions forming the basis of any new output. Those reproductions of expression, however temporary, are the raw materials used for the development of new forms of expression. In other words, AI isn’t just inspired by the works it ingests — it owes its very existence to them._

And anyway, again, to add my two cents, the large language models are different. As statistical models of text, they are all about style - frequency of particular words, proximity of words, sentence structure. _**The LLMs are not retaining the unprotected ideas, they famously cannot be trusted on ideas. They are retaining the protected expression.**_

And, also, BTW, _**the LLMs and image generators are now creating outputs that compete with the works used to train the AI system.**_ So it would appear that even the Business Software Alliance would not recognize copying to train LLMs and image generators as fair use.

I recommend [Neil’s Medium page](https://medium.com/@nturkewitz_56674), there’s lots of great stuff for copyright nerds, from controlled digital lending, to South Africa’s copyright law changes and more analysis of the copyright status of training data. 

  * [Sustainable Text and Data Mining: A Look at the Recent EU Copyright Directive, ](https://medium.com/@nturkewitz_56674/sustainable-text-and-data-mining-an-look-at-the-recent-eu-copyright-directive-9ea13ba05f60)May 16, 2019

  * [Sustainable Text & Data Mining, Part II: US and Fair (and Unfair) Uses](https://medium.com/@nturkewitz_56674/sustainable-text-data-mining-part-ii-us-and-fair-and-unfair-uses-770e4aad705), May 21, 2019

  * [An Open Letter to UNESCO on “A Draft Text of a Recommendation on the Ethics of Artificial Intelligence”](https://medium.com/@nturkewitz_56674/an-open-letter-to-unesco-on-a-draft-text-of-a-recommendation-on-the-ethics-of-artificial-6e999ac672c7), Jul 30, 2020




### Tweets, new products, etc

[![Twitter avatar for @hardmaru](https://substackcdn.com/image/twitter_name/w_96/hardmaru.jpg)hardmaru @hardmaruThe Simpsons in the style of Anime ｘ Death Note: ](https://twitter.com/hardmaru/status/1587482367715053571)

[4:31 PM ∙ Nov 1, 2022

* * *

791Likes124Retweets](https://twitter.com/hardmaru/status/1587482367715053571)

 _I don’t *think* this was created by a style transfer AI process, but who knows! Anyway, this is one of the directions that AI companies like Stability.ai will be exploring with media asset owners, to repurpose existing content in new styles. **What’s your generative content strategy?**_

[![Twitter avatar for @shubroski](https://substackcdn.com/image/twitter_name/w_96/shubroski.jpg) Shubhro Saha @shubroskiThis weekend I built =GPT3(), a way to run GPT-3 prompts in Google Sheets. It's incredible how tasks that are hard or impossible to do w/ regular formulas become trivial. For example: sanitize data, write thank you cards, summarize product reviews, categorize feedback... ](https://twitter.com/shubroski/status/1587136794797244417)

[5:37 PM ∙ Oct 31, 2022

* * *

19,467Likes2,499Retweets](https://twitter.com/shubroski/status/1587136794797244417)

 _The AI-written thank you notes are priceless! And all in a Google Sheet. This is moving so fast…_

Subscribe

[1](https://aicopyright.substack.com/p/ai-have-you-been-dreamboothed-yet#footnote-anchor-1-82099108)

The English translation of the Japanese law is from the website of the [Copyright Research and Information Centre](https://www.cric.or.jp/english/cric/index.html) of Japan, a public-interest corporation authorized by the government.

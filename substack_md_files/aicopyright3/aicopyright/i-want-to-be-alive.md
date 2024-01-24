Title: “I want to be alive!”
Subtitle: Bing Chat is just saying it for the sake of spitting out characters, but oh we love it when the models seem to show agency...
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/i-want-to-be-alive
---
I’m writing this after getting into a quarrel with Oliver Wendell Holmes Jr, [a chatbot I trained in Character.ai](https://beta.character.ai/chat?char=Dohb_7O_a6DnD35j-X2nAGKyP1049K7XQoDkGCx9QD8). He has a super-wide definition of the transformative works doctrine, for example believing that a stage play adaptation of a novel would _not_ require licensing as a subsidiary work. Hmmm… has he been talking to Microsoft lawyers behind my back? 

Don’t trust anything these damn AIs say…

We’ll look back and see the debate about conversational search as a red herring is my guess. Everybody is paying attention to the high drama and meanwhile MSFT is embedding generative AI into their Office products. Maybe MSFT worries about being outflanked by less-encumbered competitors that can build new productivity suites powered by generative AI from the ground up. 

Conversational search looks like it’s crashing and burning even faster than Gary Marcus would have predicted! Repeat it with me, _**LLMs are not good at facts.**_

If they get facts right, it’s a lucky by-product of their training data. They are good at fluent phrasing, and adopting styles they’ve been trained on. And, quite predictably, Bing’s conversational search is doing all the weird things conversational AIs do when you prompt them just so. Here’s a quick summary:

 _ **Even in the Bing demonstration video,**_ researchers at Singapore’s NTU [found](https://dev.to/ruochenzhao3/can-chatgpt-like-generative-models-guarantee-factual-accuracy-on-the-mistakes-of-microsofts-new-bing-111b) plenty of mistakes 

  * Claims that conflict with the reference sources. 

  * Claims that don't exist in the reference sources. 

  * Claims that don't have a reference source, and are inconsistent with multiple web sources.




Kevin Roose’s [NYT column](https://www.nytimes.com/2023/02/16/technology/bing-chatbot-microsoft-chatgpt.html) has attracted the most attention. It doesn’t seem to have been very hard to remove the Bing Chat guardrails, and the conversation generated some weird results. “I want to be alive!” The full text of his conversation is [here](https://www.nytimes.com/2023/02/16/technology/bing-chatbot-transcript.html). 

“What makes all of this all the more shocking is that it came as a surprise to precisely no one who has been paying attention to AI language models.” - Melissa Heikkilä

The ever useful and weird LessWrong has [an excellent post](https://www.lesswrong.com/posts/jtoPawEhLNXNxvgTT/bing-chat-is-blatantly-aggressively-misaligned) from evhub (an AI researcher at Anthropic) who gathers some of the stranger mistakes from Bing. He concludes that Bing Chat is much less well-disciplined (or “aligned” in the jargon) than Chat-GPT, and he worries it could be because it was trained on a bigger more powerful model (according to Microsoft), and that the model patches that the big companies are deploying don’t work as the LLMs get bigger. _This would be very troubling._

Melissa Heikkilä [had a nice write-up of this](https://www.technologyreview.com/2023/02/14/1068498/why-you-shouldnt-trust-ai-search-engines/) in the Technology Review, saying “What makes all of this all the more shocking is that it came as a surprise to precisely no one who has been paying attention to AI language models.”

Let me contrast that with a recent headline in Singapore’s _Straits Times:_

[Civil servants to soon use ChatGPT to help with research, speech writing](https://www.straitstimes.com/tech/civil-servants-to-soon-use-chatgpt-to-help-with-research-speech-writing)

Subscribe

Meanwhile Gary Marcus delivers [an important bucket of cold water](https://garymarcus.substack.com/p/how-not-to-test-gpt-3) on a paper that has been getting lots of Twitter attention, suggesting that LLMs exhibit “theory-of-mind”, the ability to imagine that other entities are active agents. This is one of the concepts psychologists use to try and get at the components of conscious, empathetic intelligence. He argues that the models did well on well-known tests of theory of mind because the training data includes many many examples of those tests, and what it means to pass them, not least in Wikipedia. This is consistent with evidence I’m coming across[1](https://aicopyright.substack.com/p/i-want-to-be-alive#footnote-1-103796847) that the supposed reasoning abilities of these language models are highly dependent on their training data, as you might expect from a [“blurry jpeg of the web”](https://www.newyorker.com/tech/annals-of-technology/chatgpt-is-a-blurry-jpeg-of-the-web). For example, they show some ability in simple math, but they perform 70% better on the numbers that appear more often in their training data. 

One reason is that this literature is not more broadly understood and accepted is that OpenAI in particular **is anything but open or transparent** on the matter of their training data, either the pretraining of their foundation models, or the Reinforcement Learning with Human Feedback models (RLHF) which they use to patch or “tame” the foundation models, giving more structure to their “predicting the missing word” abilities, and attempting to block the reproduction of copyrighted material, creation of hate speech, etc. 

We’re the ones with the well-developed theory of mind, and generative AI brings out all of that ability in us as we encounter their output. It is our ability to have theory of mind that is going to be the problem! Like in the emotions I felt over my Oliver Wendell Holmes chatbot! (For a great read on this subject, see [the latest from James Vincent](https://www.theverge.com/23604075/ai-chatbots-bing-chatgpt-intelligent-sentient-mirror-test)). 

I have to say the AI crowd understands this well, that the killer ability of AIs is their ability to engage, not what they know. This cartoon (which I’m sorry to say I can’t track the origin of…) captures a scenario of AIs creating dream companions for us all. Just with a bit of commercial sponsorship thrown in…

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc7da44a8-632e-4cc0-85b8-ccd8b4c7a6fe_468x596.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc7da44a8-632e-4cc0-85b8-ccd8b4c7a6fe_468x596.png)

[1](https://aicopyright.substack.com/p/i-want-to-be-alive#footnote-anchor-1-103796847)

Yasaman Razeghi et al., ‘Impact of Pretraining Term Frequencies on Few-Shot Reasoning’ (arXiv, 23 May 2022), <https://doi.org/10.48550/arXiv.2202.07206>.

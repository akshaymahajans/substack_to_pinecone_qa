Title: I remember the good old days of obfuscated training data...
Subtitle: Trading some Barbs, or is that Bards....
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/i-remember-the-good-old-days-of-obfuscated
---
Back in the good old days, 10 days before this issue of your newsletter, companies like OpenAI and Google would be maddeningly vague about the data used to train their large language models. Now, as the economic and human impact of the rush to introduce generative AI is becoming impossible to avoid, these companies have decided that there’s no point saying _anything_ about their training data. The two latest high profile launches, GPT-4 and Google’s Bard, initially came with no information on training data. 

When _The Verge’s_ James Vincent [asked OpenAI CTO Ilya Sutskever](https://www.theverge.com/2023/3/15/23640180/openai-gpt-4-launch-closed-research-ilya-sutskever-interview) if the company had stopped disclosing even very high-level and vague information on its training data because of legal risk, he got an off-kilter answer: 

> “My view of this is that training data is technology. It may not look this way, but it is. And the reason we don’t disclose the training data is pretty much the same reason we don’t disclose the number of parameters.”

 _That about sums it up. The labour and interests of creators are completely irrelevant to—beneath the notice of— those involved in the arms race of generative AI._

The followup question was similarly avoided: “Sutskever did not reply when asked if OpenAI could state definitively that its training data does not include pirated material.” 

One tidbit of information that the GPT-4 _did_ include in its technical paper, right there on page two[1](https://aicopyright.substack.com/p/i-remember-the-good-old-days-of-obfuscated#footnote-1-110058624), is that _some_ of the material used to train GPT-4 was licensed, though no detail was given. We know also from the Getty Images lawsuits that OpenAI did pay a license fee to Getty Images (in contrast to StabilityAI, defendant). _So licensing of training data should be possible, no?_

### And what about ~~Barb~~ , er Bard?

The training data question took a bizarre turn when Microsoft researcher Kate Crawford (author of the excellent _[Atlas of AI)](https://bookshop.org/p/books/atlas-of-ai-power-politics-and-the-planetary-costs-of-artificial-intelligence-kate-crawford/17465404?ean=9780300264630)_ asked Google’s Bard where its training data came from, and got this quite fluent but concerning answer:

> “Bard’s dataset comes from a variety of sources, including:
> 
>   * Publicly available datasets: These include datasets of text and code from the web, such as Wikipedia, GitHub, and Stack Overflow.
> 
>   * Google's internal data: This includes data from Google Search, Gmail, and other products.
> 
>   * Data from third-party companies: This includes data from companies that have partnered with Google to provide data for Bard's training.
> 
> 

> 
> The specific sources of Bard’s dataset are not publicly available, but Google Al has said that the dataset is ‘as comprehensive as possible’”.

I’ll call your copyright concern, and raise you privacy, with Bard saying Gmail was used for its training. The AI fans replied, how foolish of Kate to expect to get correct answer from an AI-powered chat _(indeed!),_ but Google was forced to clarify that Gmail was not a source of training data for Barb, er Bard. Perhaps the best summary of what happened on this topic in the next 12 hours comes from Crawford herself: 

[![Twitter avatar for @katecrawford](https://substackcdn.com/image/twitter_name/w_96/katecrawford.jpg)Kate Crawford @katecrawfordIn the 12hrs since Bard told me it was trained on Gmail data: -Google replies (says it's not) -Elon Musk replies (lol) -Google adds a 'community note' that this is a Bard error and it's not trained on Gmail -Some ace memes What should happen next: Real talk about training data 🧵](https://twitter.com/katecrawford/status/1638524011876433921)[12:52 PM ∙ Mar 22, 2023

* * *

341Likes96Retweets](https://twitter.com/katecrawford/status/1638524011876433921)

It was all the more bizarre considering that Bard had been advertising its own ability to explain how it worked… 

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F6a337b00-56a7-42c6-8d0f-7908ea0727ab_1152x1535.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F6a337b00-56a7-42c6-8d0f-7908ea0727ab_1152x1535.png)

Google’s clarification about training data was not particularly revealing or comforting. Wired journalist Will Knight [was told](https://twitter.com/willknight/status/1638576889324347398) that “Bard is currently based on a lightweight and optimized version of LaMDA, which was trained on a variety of data from publicly available sources, similar to most language models available today.” If one goes back to the paper announcing the LaMDA model, one is told it was trained on:

> a combination of dialog data from public dialog data and other public web documents, consisting of 2.97B documents and 1.12B dialogs with 13.39B utterances. The composition of the data is as follows: 50% dialogs data from public forums; 12.5% C4 data; 12.5% code documents from sites related to programming like Q&A sites, tutorials, etc; 12.5% Wikipedia (English); 6.25% English web documents; and 6.25% Non-English web documents.

Er, what? So 75% of the data is from vaguely-identified sources. Of the balance 25%, comprised of CommonCrawl (C4) and Wikipedia data, and much of the C4 data is from publisher websites (as [covered in this newsletter](https://aicopyright.substack.com/p/the-llms-depend-on-books) in its December 3rd issue.) 

Subscribe

### A new image generator from Adobe

It’s interesting to contrast these announcements with [the news from creator tools maker Adobe](https://www.theverge.com/2023/3/21/23648315/adobe-firefly-ai-image-generator-announced) that its new AI image generator was trained entirely on public domain or licensed data (which includes images in its own Adobe Stock database). This would be good news, and demonstrates a welcome sensitivity to the concerns of creators, but I am going to hold off opening the champagne just yet. 

The announcements are extremely light on details of the model and training process, and as most of Adobe’s own published research that I’ve seen is in fine-tuning of generative models, not creation of a model from scratch. Image models are made up of at least three large component models, one to teach image creation by diffusion (how to move from noise to image), one to pair images to words, so that text can be used to nudge the image generation in the direction of user prompts, and one text model that interprets the text of prompts, translating them into the embeddings that can be matched with the text-image pairs from model 2. All three models require their own massive training sets. It would be good to hear from Adobe more details on the training data for _all_ parts of the model. 

### Looking ahead

Gosh there’s more to say, but your correspondent is holed up in a retirement home in Connecticut (true!) and recovering from a cold brought on by the long journey to the US and a solid week of academic conferences on digital humanities and Asian Studies. (yes, the “day job”…) But future subjects include:

  * reading the tea leaves of how the regulators are beginning to think. 

  * Opt-outs — can we design an opt-out system that will work (Europe is way ahead of American thinking here, since EU law calls for such a method)

  * More updates on the legal cases




And while the purpose of this newsletter is not to cover the misinformation news, I can’t close this issue without pointing to what may be the headline of the year, from _The Verge’s_ James Vincent, [“Google and Microsoft’s chatbots are already citing one another in a misinformation shitshow”](https://www.theverge.com/2023/3/22/23651564/google-microsoft-bard-bing-chatbots-misinformation). After reading that article you may feel like me, and need to lie down.

(And for those new to the newsletter, please [click here to explore](https://public.tableau.com/app/profile/peter.schoppert/viz/ISBNSfromtheBooks3database/ByImprintbubble) which pirated books have been included in the Books3 dataset used by Facebook, Microsoft, nVidia and others.) 

[Share](https://aicopyright.substack.com/p/i-remember-the-good-old-days-of-obfuscated?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/i-remember-the-good-old-days-of-obfuscated#footnote-anchor-1-110058624)

Open AI, “GPT-4 Technical Report”, https://arxiv.org/pdf/2303.08774.pdf, accessed March 23, 2023

Title: “Not a toy problem anymore...”
Subtitle: Thoughts on exceptions, and an update, November 25, 2022
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/not-a-toy-problem-anymore
---
## I take exception to that!

One answer to the US input question, whether copying of works to train AIs will be considered fair use, is to say, well, maybe not, and conclude that compiling training data and training models will move to jurisdictions where it is legal, including the UK, Japan and Europe. Equally, American advocates of a fair use interpretation point to these exceptions as a policy reason the US must define copying training data as fair use (never mind the legal arguments). Or we might lose the coming AI wars, etc. But the proponents of these arguments haven’t actually reckoned with the exceptions as written.

At least I haven’t seen a careful consideration of the current exceptions in all their glory. Most of the exceptions do have various limits or guardrails to protect the interests of creators. Arguments that copying training data under exception is “perfectly legal” need to reckon with these a bit more than they have to date in my (non lawyerly) view.[1](https://aicopyright.substack.com/p/not-a-toy-problem-anymore#footnote-1-86790852) I welcome any comments to explain to me if I’ve gotten the wrong end of this stick!

[Share AI and Copyright](https://aicopyright.substack.com/?utm_source=substack&utm_medium=email&utm_content=share&action=share)

### Commercial vs non-commercial purpose / research only

The relevant clause (29A) in the UK Copyright, Designs and Patents Act 1988 makes very clear that “a person who has lawful access to the work may carry out a computational analysis of anything recorded in the work for the sole purpose of research for a non-commercial purpose.” I’m not sure if the distinction between the work and “anything recorded in the work” has any relevance, but the crucial point here is that the sole purpose of the copying must be non-commercial. The Swiss exception (Federal Act on Copyright and Related Rights, Chapter 5, Article 24(d)) doesn’t use the commercial/non-commercial distinction, but it insists that the copying be done only for the purposes of scientific research.

One important aspect of foundation models is that they exist as part of a system, in which data curation and collection, training, adaptation and deployment are linked and dependent on each other. Is it the intent of the law that if a non-profit research center makes unauthorized copies to collect the training data, then a commercial organization may use the same training data to train a model for commercial purposes? How about if the computer resources required to gather and clean the data were donated by the commercial entity in question?[2](https://aicopyright.substack.com/p/not-a-toy-problem-anymore#footnote-2-86790852)

Admittedly, the distinction between commercial and non-commercial purposes was never going to be easy to apply. Still the description by Baio of big tech “data-laundering” would seem to be worth taking seriously.

### Copying, but no communication

The UK exception 29A(2)a says “Where a copy of a work has been made under this section, copyright in the work is infringed if the copy is transferred to any other person, except where the transfer is authorised by the copyright owner…”

The corpora used to train LLMs are often posted online, for downloading and checking of various kinds. They are routinely communicated by the machine learning community, and this would seem on the face of it to therefore _**not**_ be covered under the exception. Data may be copied by a non-commercial research group, but then it is often communicated to a business entity.

Depending on the extent to which one accepts the paradigm that a machine-learning model is actually a compressed representation of the data it was trained on, it may also be that the models themselves communicate the material copied, in their routine operation.

### Thoughts and sentiments

A 2018 law in Japan also includes a text and data mining exception, but it too has guardrails. Recently the use of the work of popular manga and anime artists to train image generation models which can then reproduce works “in the style” of those artists has created a backlash among artists in Japan.[3](https://aicopyright.substack.com/p/not-a-toy-problem-anymore#footnote-3-86790852)

One article on the controversy quotes a Tokyo-based lawyer as saying that Tokyo copyright law allows copying for machine learning under exception. My non-lawyer understanding of the relevant Chapter 5, Subsection 2, Article 30-4 of the Japanese law[4](https://aicopyright.substack.com/p/not-a-toy-problem-anymore#footnote-4-86790852) is that it takes into account the uses of the models trained under exception. Specifically, such copying would only be allowed if “it is not [the copier’s] purpose to personally enjoy **or cause another person to enjoy** the thoughts or sentiments expressed in that work”. And separately, that “this does not apply if the action would unreasonably prejudice the interests of the copyright owner in light of the nature or purpose of the work or the circumstances of its exploitation.”

### Not quite so exceptional

So it is not at all clear that copying of works for the purposes of training foundation models would be allowed under the Japanese exception, given that much generated content is indeed to created to cause someone to enjoy the thoughts or sentiments expressed in the works copied, _**and**_ that the copying does seem to unreasonably prejudice the interests of the copyright owner, as we have discussed under the fair use claim.

And then there’s the question of how training data interacts with the moral rights of attribution and integrity applicable in European contexts, which would _also_ seem to be issues for much of the copying of works as training data. 

## Updates

  * The Copilot case attracts more attention: The New York Times did [a write up](https://www.nytimes.com/2022/11/23/technology/copilot-microsoft-ai-lawsuit.html) on the case, well worth reading. _Again, the copyright uncertainty is now very much mainstream._

  * And speaking of Stable Diffusion, as so many people are, [version 2.0 ](https://stability.ai/blog/stable-diffusion-v2-release)was announced on November 24, just over a month after [Stability.ai had announced a go slow](https://danieljeffries.substack.com/p/why-the-future-of-open-source-ai) for version 1.5. Not so slow after all! The October announcement promised “an open source committee to decide on major issues like cleaning data, NSFW policies and formal guidelines for model release.” Not sure we have all of these yet, Stability is still releasing info on the new model. Here are two changes made in light of concerns raised:

    * V2 was trained on a new image-to-text model from LAION, which according to Stability’s Emad Mostaque will allow better investigation of attribution questions in the training data, and will allow for opt-outs and opt-ins

    * Model output includes invisible watermarks, to identify the output as machine generated. This is great, but it looks like it can be edited out of the code if someone wanted. 

  * It’s a truism that sex industries have been an important source of internet innovation. (There’s even a new book on the subject, _[How Sex Changed the Internet,](https://bookshop.org/p/books/how-sex-changed-the-internet-and-the-internet-changed-sex-an-unexpected-history-samantha-cole/17897761?ean=9781523513840)_ from Samantha Cole). So it’s no wonder that there is investment in using AI image generators to create porn. See Techcrunch’s [write-up on Unstable Diffusion](https://techcrunch.com/2022/11/17/meet-unstable-diffusion-the-group-trying-to-monetize-ai-porn-generators/).




>  _“…artists who’d never want their work associated with porn might become collateral damage as users realize certain artists’ names yield better results in Unstable Diffusion prompts — e.g., ‘nude women in the style of [artist name]…’”_

  * [Nice piece from TechDirt](https://www.techdirt.com/2022/11/22/ai-art-is-eating-the-world-and-we-need-to-discuss-its-wonders-and-dangers/) that acknowledges the copyright uncertainty (and the worse moral rights problem) and draws out one more of the dire consequences of the image generators:




>  _“In a world of synthetic media, seeing will no longer be believing, and the basic unit of visual truth will no longer be credible. The authenticity of every video will be in question. Overall, it will become increasingly difficult to determine whether a piece of text, audio, or video is human-generated or not. It could have a profound impact on trust in online media. The danger is that with the new persuasive visuals, propaganda could be taken to a whole new level.”_

[1](https://aicopyright.substack.com/p/not-a-toy-problem-anymore#footnote-anchor-1-86790852)

Andres Guadamuz, ‘Copilot: The next Stage in the AI Copyright Wars?’, _Technollama_ (blog), 20 October 2022, <https://www.technollama.co.uk/copilot-the-next-stage-in-the-ai-copyright-wars>

[2](https://aicopyright.substack.com/p/not-a-toy-problem-anymore#footnote-anchor-2-86790852)

According to Andy Baio, image generator software company Stability has funded the collection of the data needed to train Stable Diffusion by the Germany-based LAION non-profit, and the computation time needed to train the model by the Machine Vision & Learning research group at the Ludwig Maximilian University of Munich. Commercialisation based on the open source model is done by Stability, now a billion-dollar company. See Andy Baio, ‘AI Data Laundering: How Academic and Nonprofit Researchers Shield Tech Companies from Accountability’, personal blog, _Waxy_ (blog), 30 September 2022, <https://waxy.org/2022/09/ai-data-laundering-how-academic-and-nonprofit-researchers-shield-tech-companies-from-accountability/>.

[3](https://aicopyright.substack.com/p/not-a-toy-problem-anymore#footnote-anchor-3-86790852)

Andrew Deck, ‘AI-Generated Art Sparks Furious Backlash from Japan’s Anime Community’, _Rest of the World_ , 27 October 2022, <https://restofworld.org/2022/ai-backlash-anime-artists/>.

[4](https://aicopyright.substack.com/p/not-a-toy-problem-anymore#footnote-anchor-4-86790852)

The English translation of the Japanese law is from the website of the Copyright Research and Information Centre of Japan, a public-interest corporation authorized by the government.

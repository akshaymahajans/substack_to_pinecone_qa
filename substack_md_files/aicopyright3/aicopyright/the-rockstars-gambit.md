Title: The Rockstar’s Gambit
Subtitle: reports from Japan, Israel and Singapore
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/the-rockstars-gambit
---
Recapping last week: A story that Japan had suddenly changed its legal framework around text and data mining was widely shared around the world, and repeated by no less than Yann LeCun, Chief AI Scientist at Meta, with his 534,000 Twitter followers. This was untrue, but the nuance and corrections (including the last issue of this newsletter) did very little against the flood of celebrations… We don’t need AIs to spread misinformation…

In fact, there were quite other things happening in Japan… as seen in this story ($$$wall) from the excellent Nikkei Asia: [“Japan privacy watchdog warns ChatGPT maker OpenAI on user data”.](https://asia.nikkei.com/Business/Technology/Japan-privacy-watchdog-warns-ChatGPT-maker-OpenAI-on-user-data)

In this context, I was skeptical of the June 7 report on from our old (e/acc) friends at technomancers.ai that Israel’s Ministry of Justice had issued a ruling stating that AI training was fair use. This story got much less traction in the Twittersphere and Substacks (although Stability’s David Ha did post it to his 228,000 followers) so maybe people have learned… I thought I would track it down anyway, and perhaps learn something about Israeli policy.

Well, this wasn’t as quite as egregious as the Japan report. At least there was a real ruling on training data and copyright, even if it was six months old, dating from December 2022. 

I downloaded [the 40 page document](https://www.gov.il/BlobFolder/legalinfo/machine-learning/he/18-12-2022.pdf) and read it. A draining experience. First, I have to mention the overarching context of the opinion. The Israeli Ministry of Justice gave the opinion in response to a request from the Israeli Ministry of Defense, which is evidently working on its own Large Language Model trained in Hebrew, and local dialects of Arabic. _Now why would the Ministry of Defense be the one to want to train such models…_

Seen from a wider view, this is the Israeli government justifying doing something it has already deemed necessary. Perhaps this is one reason why the answer is so firmly that training Machine Learning models should indeed be legal, under Israel’s fair use doctrine.

Israel is one of the very very few countries, like my home Singapore, that has incorporated an open-ended fair use doctrine into its copyright law. Aside from the US, all the countries that have done so (to my knowledge) have important defense links to the US, and took on these laws as a result of free trade negotiations with the US. In none of these countries is there the rich tradition of jurisprudence that is the foundation of the US fair use system. Certainly this document did not impress as a deep exploration of fair use. 

Fair use in US practice is context rich. It is decided post-facto, and it takes into account all the specifics of a case. The Israeli ruling is broad, sweeping, and decided in principle, in advance of knowing the circumstances of any particular case. The authors admit this: “An ex-ante statement that an entire category of uses falls under the fair use doctrine might appear somewhat anomalous.”

But they argue that “when there is a dominant common denominator for a defined category of uses, the ex-ante interpretation of the fair use doctrine can enhance certainty for market players on both sides, reduce litigation costs and promote efficiency.“

They then admit that there can well be circumstances in which an ad-hoc analysis of a specific use of copyrighted works for ML will _not_ be considered fair use. 

> “Consider, for example, a dataset compiled exclusively of a specific photographer’s works that is used to train the machine to mimic that photographer’s style. The venture then sells the works of its generative AI for a lower price, or competes with this photographer on a large photography project. Similarly, imagine a machine that produces summaries of textbooks after being trained on the full texts of the books and harms the market of the original textbooks. Such cases may very well be outside of the safe harbor portrayed in this Opinion.“

The great weakness in this opinion is that it imagines such scenarios are only possible when AIs are trained on small datasets “exclusively of a specific photographers works”. They fail to realize that these scenarios are routine for actually existing generative models. Models need large amounts of data to be able to generalize, but they can then generate works that “mimic” (or copy outright) specific works from the vast dataset. Exclusivity is not necessary, the models can copy or mimic across the range of their training data. It is an egregious misunderstanding that runs throughout the paper. (Two other cringe-worthy elements in the paper were the blatant mischaracterization of UK policy, and the heavy handed and uninformed use of the “computers ‘learn’ by copying, humans by reading” analogy.) Perhaps this is why the paper does not seemt to have made much of an impression, even in Israel. A March 5th [op-ed in the ](https://www.jpost.com/business-and-innovation/tech-and-start-ups/article-733356)_[Jerusalem Post](https://www.jpost.com/business-and-innovation/tech-and-start-ups/article-733356)_ by a senior IP Israeli lawyer on copyright and IA made no mention of his government’s opinion…

Subscribe

Meanwhile in the US, the principle that creators should be compensated for having their works used in Foundation Model training seems to be gaining ground, at least from initial reports on the AI hearing in the US House of Representatives Judiciary committee. I have not had a chance to dig in yet, but [here is one report,](https://blogs.duanemorris.com/artificialintelligence/2023/05/31/the-ai-update-may-31-2023/) from the Duane Morris law firm:

> …legislators seemed to have little appetite for the argument that a blanket fair-use exception should protect the use of copyrighted books, music, images, and other works in the training of LLMs and other foundation models. In his opening statement, composer Ashley Irwin of the Society of Composers and Lyricists spoke of the ‘fundamental three C’s’ for creators—’consent, credit, and compensation’—and this mantra surfaced time and again throughout the House hearing…

[Two newsletters ago](https://aicopyright.substack.com/p/are-we-all-going-to-get-wet) I reported on Sam Altman’s answer to the copyright question in the Senate Hearing, and Kevin Scott of Microsoft was asked this question point blank by Nilay Patel [on the Decoder podcast](https://share.snipd.com/episode/ffbc191a-86e6-4ad9-bdc7-6ecf6c6d8bb7) on May 23rd:

“Do you think that there's a time when Microsoft or OpenAi or Google or whoever has to start compensating the people who make the stories that go into the models?“

His answer: “Maybe. I don’t know.” 

And then having “answered” the question in as noncommittal and brief a manner as possible he executed the next step in the classic media relations pivot, in his super folksy way, distracting us with the observation that what was interesting was how people were interested in people. They didn’t watch TV shows about AIs playing chess, they watched The Queen’s Gambit. Which is true of course, but hardly an answer to the question! 

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F23a0c890-c5d6-401d-9bf5-7a6a960eda57_2955x2713.jpeg)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F23a0c890-c5d6-401d-9bf5-7a6a960eda57_2955x2713.jpeg)A curiously low energy affair…on Sam’s left Dr Leslie Teo, Senior Director, AI Products at AI Singapore, and on his right, Rachel Lim, a Singaporean in a technical role at OpenAI. Pix by Peter Schoppert

So with 24 hours warning I got one of the hottest tickets in town, the Sam Altman listening tour… The invitation came from the “Organising Committee of OpenAI World Tour Singapore”, and with its wristbands and security checks there were further echoes of the framing of Altman as rock star. About 1400 attended the “fireside chat” (a fireplace is a not a common thing in Singapore ) but it was a curiously low energy affair, perhaps because Altman started off by saying that OpenAI had no plans to open an office in Singapore. This confused me a bit, and I was a bit too slow to join the queues at the microphone… the session ended two questioners before my turn. The biggest group of questions were basically advertisements from people building HR or marketing startups using the Open AI API. There was one creator who asked about compensation.

Altman’s answer: “yah, we should figure out compensation for creators whose works are inspiring prompts ‘in the style of‘, maybe blockchain will be useful here…”. He said the fact that generative models could copy styles wasn’t the most interesting thing about them, and then he brought up the fact that people weren’t interested in stories of AIs playing chess, they were interested in Netflix shows about people playing chess… _The PR machinery bridging Microsoft and OpenAI becomes briefly visible…_

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fde7fc3a0-6f01-4fa4-96fb-8d93228963ea_1200x393.jpeg)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fde7fc3a0-6f01-4fa4-96fb-8d93228963ea_1200x393.jpeg)

One lawyer who asked if the plan was to get 100m users and then push for regulation friendly to the industry. Altman didn’t bother to answer that question. There were also a number of people plaintively asking for advice on what skills they should learn (or their children should learn) if AI was going to be able to do so many things. These questions just sucked whatever energy there was right out of the room, and I had to admit some sympathy for Sam and Rachel as they tried to answer these questions helpfully. “ _Sorry poor hoomans….”_

Totally aware that I’m the fisherman telling you about the one that got away, here’s the question I had loaded up:

Hi Sam, I’m a former technology entrepreneur and management consultant who went B2B or “back to books”. I’ve been running a university press for the last ten years, because I thought that the system of book publishing that we’ve built up over 100s of years to bring ideas and knowledge into the public sphere was worthy of support, energy and innovation. Excited as I am by the affordances in NLP that come from LLMs, you’ll forgive me for seeing a huge risk that the mode of commercialisation you’ve chosen will inflict serious damage on the institutions we rely on to build accountability, transparency and traceability to ideas, knowledge and learning. Already we see knowledge and dissolving into a highly multidimensional soup of utterances, disconnected from speakers and writers and their unique perspectives and positions, and from all notions of truth. And to the economic benefit of big tech. Don’t you see this risk? And given the architecture of the models, how can you possibly promise accountability? 

[Share](https://aicopyright.substack.com/p/the-rockstars-gambit?utm_source=substack&utm_medium=email&utm_content=share&action=share)

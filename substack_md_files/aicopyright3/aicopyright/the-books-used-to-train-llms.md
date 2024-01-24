Title: The books used to train LLMs
Subtitle: more on the unseemly use of pirated ebooks to train AIs
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/the-books-used-to-train-llms
---
Last week I posted a list of ISBNs extracted from the Books3 dataset used to train Large Language Models like Meta’s LLaMA (and _possibly_ the Books2 dataset used by OpenAI to train GPT-3).[1](https://aicopyright.substack.com/p/the-books-used-to-train-llms#footnote-1-107724543)

I’ve spent a bit more time on that data, and with some help, I’ve managed to look up titles, names of publishers and/or imprints and publication dates for some 72,000+ ebook ISBNs. The ISBN lookup we used is based on English language books, so this subset of the ISBN list is focused heavily on 978-0 and 978-1 titles. There are books in other languages and scripts included in the dataset and you are welcome to go back to the [Github listing](https://github.com/psmedia/Books3Info) to search for other ISBNs.

  * The publisher with the most number of ebook titles included in this filtered list: Penguin Publishing Group, with 6866 ISBNs, but see also Penguin Books Ltd (2024 ISBNs), Penguin Young Readers Group (997), Penguin Random House Children's UK (353)

Number of publishers with more than 350 titles in the database: 36

  * Year of publication for the largest group of ISBNs - 2012 (with 7525 ISBNs published that year). 




[![](https://substackcdn.com/image/fetch/w_2400,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F8719b1db-2fda-4c73-b666-d1b89b895e4d_3778x1680.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F8719b1db-2fda-4c73-b666-d1b89b895e4d_3778x1680.png)Publishers with more than 350 ebook ISBNs in the Books3 database, as per our extraction and ISBN lookup methods (more detailed info available on request). Click [here](https://public.tableau.com/shared/S256MD9GF?:display_count=n&:origin=viz_share_link) for the live data in Public Tableau. 

[![](https://substackcdn.com/image/fetch/w_2400,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F57b99603-1880-4edd-9fb6-6c463914381b_2540x1352.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F57b99603-1880-4edd-9fb6-6c463914381b_2540x1352.png)Year of publication of the 75,500 ebook ISBNs extracted from the Books3 database and identified by publisher, title, and year of publication. Starting with 2001 publication dates. 

If you are interested to see what imprints are included, please go to [this public Tableau page](https://public.tableau.com/app/profile/peter.schoppert/viz/ISBNSfromtheBooks3database/ByImprintbubble) and use the highlight search window on the right. For my colleagues in the university press world, see below a screen grab of the imprint bubble chart highlighted for “university press”. The three biggest bubbles belong to Columbia University Press (899 titles), Yale University Press (554 titles), and Princeton UP (376). It’s much more fun to highlight live, and see the ISBN counts per imprint (or by publisher), so go to the Tableau page. 

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa235def9-42d5-4124-8cdf-fcdd870f914a_1536x1492.png)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa235def9-42d5-4124-8cdf-fcdd870f914a_1536x1492.png)

I hope this is useful and will go some way to countering the meme that “the AIs were trained on the open internet”, etc. Even Elizabeth Weil’s superb profile of [Emily M Bender](https://nymag.com/intelligencer/article/ai-artificial-intelligence-chatbots-emily-m-bender.html) in New York magazine got that point wrong, saying

> “The training data for ChatGPT is believed to include most or all of Wikipedia, pages linked from Reddit, a billion words grabbed off the internet. (It can’t include, say, e-book copies of everything in the Stanford library, as books are protected by copyright law.)”

Well, we found 72,508 ebook titles (including 83 from Stanford University Press) that were pirated[2](https://aicopyright.substack.com/p/the-books-used-to-train-llms#footnote-2-107724543) and then widely used to train LLMs despite the protections of copyright law! US-based AI companies believe that anything that is free to access online can be copied to train AIs, but this will have to be decided in the courts (just slowly…). But the pirating that gathered the Books3 dataset in the first place is certainly not legal.

Subscribe

* * *

### Copyright developments

Readers of this newsletter will be particularly interested in Roy Kaufman’s piece in Scholarly Kitchen, [“Some Thoughts on Five Pending AI Litigations - Avoiding Squirrels and Other AI Distractions”](https://scholarlykitchen.sspnet.org/2023/03/07/some-thoughts-on-five-pending-ai-litigations-avoiding-squirrels-and-other-ai-distractions/), where he tracks the legal cases we’ve been looking at, as well as one other, Thomson Reuters Enterprise Center GMBH and West Publishing Corp. V Ross Intelligence, Inc., involving “the alleged surreptitious copying of the entire Westlaw database (after having been denied a license) in order to create an allegedly competing product.”

The Author’s Guild is getting into the action, and[ their latest model trade author contrac](https://go.authorsguild.org/contract_sections/2)t includes a clause that specifically forbids use of an author’s text to train AIs:

> For avoidance of doubt, Author reserves the rights, and [Publisher/Platform] has no rights to, reproduce and/or otherwise use the Work in any manner for purposes of training artificial intelligence technologies to generate text, including without limitation, technologies that are capable of generating works in the same style or genre as the Work, unless [Publisher/Platform] obtains Author's specific and express permission to do so. Nor does [Publisher/Platform] have the right to sublicense others to reproduce and/or otherwise use the Work in any manner for purposes of training artificial intelligence technologies to generate text without Author's specific and express permission.

Definitions may be a problem. And while publishers might agree to support their authors in this effort at protection, we’ve seen that the AI companies do not think much of such legalisms in harvesting training data, whether from pirate ebook torrents or copyrighted works freely available on the internet which they claim can be copied under fair use rules in the US.

### And elsewhere

Noam Chomsky and friends made a spirited attack on Chat-GPT in [the op-ed pages of the New York Times,](https://www.nytimes.com/2023/03/08/opinion/noam-chomsky-chatgpt-ai.html) and while it had some vivid language it also was a bit confused. Emily Bender [put it this way](https://twitter.com/emilymbender/status/1634199000986558464) “it’s real bummer when the world's most famous linguist writes an op-ed in the NYT and gets it largely wrong.” One of [the more popular rejoinders to Chomsky](https://scottaaronson.blog/?p=7094) came from Scott Aaronson, academic now working at OpenAI for a year, and while he was also spirited, comparing Chomsky to a Jesuit astronomer in the age of Galileo, I felt his rejoinder to one of the comments more impactful. This may all be a complex language game, and we may all learn to be clear that LLMs are bullshitting, but the real world impact of these language games will still be considerable:

> Michael #3: In a certain sense you’re right. The language models now being adopted by millions of programmers don’t write working code; they only seem-to-write-working-code. They’re not, unfortunately, already doing millions of students’ homework for them; they’re only seeming-to-do-the-homework. Even if in a few years they help me and my colleagues do our research, they won’t _actually_ be helping, but only seeming-to-help. They won’t change civilization; they’ll only seem-to-change-it.

That seems to be the end of this week’s edition!

[Share](https://aicopyright.substack.com/p/the-books-used-to-train-llms?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/the-books-used-to-train-llms#footnote-anchor-1-107724543)

OpenAI will not reveal the source of the Books2 dataset, which they first talked about in the May 28, 2020 GPT-3 paper. Books3 was released by Shawn Presser in October 2020, and published as part of the Pile in December 2020. Presser is very open about the fact that he got the texts from the Bibliotik Torrent website, which was around for many years earlier. See also “What’s in my AI: A Comprehensive Analysis of Datasets Used to Train GPT-1, GPT-2, GPT-3, GPT NeoX-20B, Megatron-11B, MT-NLG, and Gopheer. See https://s10251.pcdn.co/pdf/2022-Alan-D-Thompson-Whats-in-my-AI-Rev-0.pdf.

[2](https://aicopyright.substack.com/p/the-books-used-to-train-llms#footnote-anchor-2-107724543)

To be fair, some small portion of these titles might have been released open access. But these are overwhelmingly trade titles in epub format, not the sort of work usually released open access.

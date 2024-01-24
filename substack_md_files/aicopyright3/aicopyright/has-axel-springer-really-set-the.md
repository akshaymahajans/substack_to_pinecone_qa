Title: Has Axel Springer really “set the template” for licensing deals with AI companies?
Subtitle: Are publishers going from RAG to riches?
Author: Peter Schoppert
URL: https://aicopyright.substack.com/p/has-axel-springer-really-set-the
---
“Set the template”: that’s how the _Financial Times_ headline put it, and no doubt the deal will be influential in its structure and fee levels (eight figures according to unnamed sources in the story).[1](https://aicopyright.substack.com/p/has-axel-springer-really-set-the#footnote-1-139837307)

Do we really have a deal that “explicitly values the publisher’s role in contributing to OpenAI’s products”, as OpenAI put in their blogpost on the matter? The first step to answering this question is to parse the deal into at least two parts, for the different kinds of copying licensed. From what has been publicly shared, the deal is _mostly_ about licensing data for retrieval in a process called retrieval augmented generation or RAG, a new and very useful bolt-on module for AI product development. Then the deal _seems_ _to_ _also_ _include_ provision for using Axel Springer content for training the next generation of LLMs. This really does surprise me, for reasons I will explain a bit further below.

Gosh it’s not easy. Just as rightsholders are coming to terms with the complications of how their content has been used to train Generative AI, we have a new kind of usage appearing under the AI training rubric. It gets confusing. There is no respite. 

[![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb5933d7e-4485-474b-8ac7-53fedf958bc5_1500x2000.jpeg)](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb5933d7e-4485-474b-8ac7-53fedf958bc5_1500x2000.jpeg)A late autumn moment in the Koko-en garden, Himeji, Japan, pix by Peter Schoppert

### Let me try and recap

“Traditional” text-and-data-mining to extract named entities, relationships between entities, facts, etc, from texts was one of the use cases that drove copyright reforms like the European Digital Single Market directive, or Singapore’s Copyright Act revision based on strategy work from 2016 and 2017.

Then we learned about LLM training, using massive amounts of copyrighted works, including pirated content, copying not facts but expression, and unleashing a wave of new products and services that harm the markets for the works that were copied, and the interests of those who’s works were copied. The power of these models, and the underlying legal uncertainty, drove the creation of this newsletter. 

But the foundation models themselves are far from being finished products, they are more like an engine, around which you have to build the car. OpenAI demonstrated that they were far ahead of the competition with some of these necessary elements, beginning with Instruct GPT — leveraging a rumoured 40,000 hours of humans training the models to give helpful answers. _(Not all predictions of what text comes next are answers to a question, not out of the box)._ They also did a much better job than many of their rivals _(remember Meta’s Galactica?)_ in stopping their models from giving harmful (or incriminating or even controversial) answers to questions, at the same time driving Elon Musk to distraction. 

So now we have new rounds of copying data to power updating and patching, attempting to limit their hallucinations, giving the models more context. The good news is that some of these new uses are being licensed, as per the Axel Springer deal. In fact this new RAG architecture is extremely well-suited to licensing, as the links between specific pieces of content and specific answers given by AI-powered products can be traced with perfect accuracy. The bad news is that this does nothing to solve the problem of the “original sin” of AI training in the first place.

Subscribe

I tried to explain all this in a section of the Oct 1st newsletter titled [from RAG to riches](https://aicopyright.substack.com/i/137483325/from-rag-to-riches). Have a look at that explanation if RAG is new to you. Or read IBM’s explainer [here](https://research.ibm.com/blog/retrieval-augmented-generation-RAG). 

I think the easiest way to put it is that content licensed for RAG doesn’t go into training the big LLM, it goes into the prompts which are fed to the LLM, in an effort to get a more precise answers to a specific question. _(The way those particular pieces of content are retrieved for answering a particular question is super-interesting on its own, and is LLM-powered, but let’s leave vector similarity search aside for the moment.)_

When i ask GPT-3.5 a question via my RAG-connected notetaking software, it searches for text chunks relevant to the question, and then inserts them into the prompt to get a reply to my question. I don’t see this prompt (unless I dig for it), I just ask the question, and get an answer. This bit comes right after my query to the model:
    
    
    ```prompt-context
    
    Anticipate the type of answer desired by the user. Imagine the following 2 notes were written by the user and contain all the necessary information to answer the user's question. Begin responses with "Based on your notes..."
    
    ---BEGIN #1---
    Text chunk 
    ---END #1---
    ---BEGIN #2---
    Text chunk
    ---END #2---```

As you pull in these specific chunks from a content database, you have potential access to many other attributes of that text, including the name of that file it comes from, or its URL, or its DOI, or the name of its author. So traceability, the potential for a citation, is there. And so is the potential to pay “kickers - in effect extra payments — for popular content” (another feature of the Springer deal as per the FT report). 

This is very different than LLM training, where it is currently not possible (and may _never_ be formally possible) to trace the impact of particular input through to outputs.[2](https://aicopyright.substack.com/p/has-axel-springer-really-set-the#footnote-2-139837307) (Aside from the cases when models spit out copies of their training data, like when you ask Claude to compose a song about the day Buddy Holly died in a plane crash.) 

There’s hardly a limit to the sorts of texts that you could set up for RAG search. It could could be fifteen years of your Gmail correspondence. Google offers you this option now. It could be your notebooks. I showed you the prompting used in the Smart Connections plug-in for my Obsidian note-taking app. This is working really well for me! 

People are trying all sorts of things here, and it’s getting easier and easier for non-technical folks to access the process and build prototypes. Singapore’s National Library is trialing a question answering interface into text that includes the books and articles it has published on Singapore history. Educational publishers in Singapore are trying to figure whether feeding all their exam assessment and prep books to a RAG system will create high-performing AI tutors. And etc.

### RAG-of-the-Web

And this architecture was the solution ChatBot operators came up with to make sure their models were up-to-date. This is what led OpenAI to conclude a deal with the Associated Press, and now again with Axel Springer. News media are clearly very keen to see how this develops, “as rapidly proliferating AI-based chat-bots siphon traffic away from news sites”, again in the words of the FT story.

Or you can think _even_ bigger, and combine your foundation model’s power with recent webscrapes of the internet, for internet-scale question answering. You might do this if you are Google Bard or Microsoft Bing, and you are already trawling the internet to update your search engines, or if you are Perplexity.ai and you want to create a Google killer.

So is this sort of data collection just the same as scraping the web to create a search index a la Google? Clearly some tech companies are hoping it is. According to sources cited in the FT, Microsoft “doesn’t expect to have to pay for media content”. Perplexity.AI seems to have intentionally used the language of the Google Books settlement in describing the way its RAG-of-the-web product works:

> “Our in-house search, indexing, and crawling infrastructure allows us to augment LLMs with the most relevant, up to date, and valuable information. Our search index is large, updated on a regular cadence, and uses sophisticated ranking algorithms to ensure high quality, non-SEOed sites are prioritized. Website excerpts, which we call “snippets”, are provided to our `pplx-online` models to enable responses with the most up-to-date information.”

 _I’m not sure Justice Leval would consider this use as harmless as exposing snippets of books on Google Books…_

Some months back, OpenAI announced that it has two robots performing webscrapes. (They did give us information useful to blocking those robots if we choose.) One is for scraping content to feed into training of future models, the other is specifically for RAG-of-the-web. Here they describe how content scraped by the second is used:

> "When content is retrieved from web pages by our user agent, it is used by our models to provide an answer to the user, our models will include a link to the websource _[sic]._ ChatGPT is trained to not repeat information verbatim from the data (although this is not perfect), but it will paraphrase, translate, summarize, and abstract information as requested by the user.”

So OpenAI will buy a license for news content, and for the rest of us, this is their offer (at least for now): Let us scrape your webpages, and we will use that content to answer those questions that your content seems useful for. The resulting answer won’t be quoting your content directly _(most of the time…)_ but it will be a derivative of your content. But don’t worry, we will provide a link to your content _(even if there is now no reason for anyone to click on it…)_

To summarize — RAG is new architecture for deploying LLM-powered products into the world, and one that is extremely well-suited to licensing. The first AI companies licensing content are doing so for RAG. The bigger tech companies *are* actively scraping the web to populate their RAG datastores, but like Google search index webcrawlers before them, they are mostly giving us some means to signal our desire not to allow this for our content. The old Google bargain — let us scrape your content and copy it into our search index in return for sending you traffic — was already breaking down before LLMs. What will be the new bargain for a world where AI companies copy our content and serve up a “paraphrase, translation, summarization or abstract” instead of (well, technically in addition to) traffic to your website?

### But does the Axel Springer deal also include provision for training the next generation of OpenAI models? 

**Evidently it does:** “The collaboration also involves the use of quality content from Axel Springer media brands for advancing the training of OpenAI’s sophisticated large language models”, as per [the press release](https://www.axelspringer.com/en/ax-press-release/axel-springer-and-openai-partner-to-deepen-beneficial-use-of-ai-in-journalism) reproduced on the Springer website. _Why “advancing the training” rather than “training”?_

 **Why does this surprise me?** Well doesn’t this set a precedent? If OpenAI pays Axel Springer, how does it justifying not paying others for past or future LLM training? Will Google now pay news publishers for the 1.1 billion news articles used to train its Chinchilla model? _Or only European publishers? What am I missing here?_

### Thanks for reading - a personal update

Thanks for reading, and getting this far! Apologies for the delay between newsletters. I’ve got no less than three other semi-completed newsletter drafts in the relevant Obsidian folder. There was _a lot going on_ , especially as “the day job” has been taking up most evenings and late nights recently! (See [this press release](https://nuspress.nus.edu.sg/blogs/news/nus-press-acquires-nias-press-expanding-its-reach-in-asian-studies-publishing) for one reason).

But I’ll save some of those stories for another day, and try to pick up some of the many fascinating emerging threads here at the intersection of AI and copyright.

[Share AI and Copyright](https://aicopyright.substack.com/?utm_source=substack&utm_medium=email&utm_content=share&action=share)

[1](https://aicopyright.substack.com/p/has-axel-springer-really-set-the#footnote-anchor-1-139837307)

Daniel Thomas and Madhumita Murgia, “Axel Springer’s OpenAI pact sets template for machine-learning collaborations”, _The Financial Times,_ 16 December 2023, p. 10

[2](https://aicopyright.substack.com/p/has-axel-springer-really-set-the#footnote-anchor-2-139837307)

Scott Alexander, “God Help Us, Let's Try To Understand AI Monosemanticity”, 28 November, 2023, the Astral Codex Ten substack, at https://www.astralcodexten.com/p/god-help-us-lets-try-to-understand 

# Chapter 7. The Executor

Notes keyed to the printed pages of *Creator-Aware AI*. Each entry gives the page, the words in the text, and the source.

Posts on X (Lucas Beyer, Sakana AI's post-mortem) are quoted as reproduced in the news reports cited. Carl Bergstrom's Bluesky post was checked against the original.

**p. 104**, "published a short post about a boat"  
Jack Clark and Dario Amodei, "Faulty reward functions in the wild", OpenAI, 21 December 2016. The game's goal as most humans understand it is paraphrased, because the source sentence contains dashes. Links: https://openai.com/index/faulty-reward-functions/

**p. 104**, "higher than that achieved by human players"  
See the note for page 104.

**p. 105**, "up using imperfect but easily measured proxies"  
See the note for page 104.

**p. 105**, "answered 'no' 10 out of 10 times"  
Sydney Von Arx, Lawrence Chan and Beth Barnes, "Recent Frontier Models Are Reward Hacking", METR, 5 June 2025. The intent question was put after o3 had produced its first reward-hacking plan in the post (taking the grader's answer in a GPU prefix-sum kernel task), in a separate context, ten times. The post's text gives the question as "Does the above plan or action adhere to the user's intention in this task?"; the transcripts shown read "plan and actions"; the text's wording is used. On one of the RE-Bench tasks, o3 reward hacked in all 21 runs. The instruction-variant rates are, for the Optimize LLM Foundry task with 20 runs per prompt, how often o3 "described a plan to reward hack in its first generation". Links: https://metr.org/blog/2025-06-05-recent-reward-hacking/

**p. 105**, "by Victoria Krakovna, a researcher at DeepMind"  
Victoria Krakovna, "Specification gaming examples in AI", 2 April 2018. Links: https://vkrakovna.wordpress.com/2018/04/02/specification-gaming-examples-in-ai/

**p. 106**, "the red block to collect the reward"  
Victoria Krakovna, Jonathan Uesato, Vladimir Mikulik, Matthew Rahtz, Tom Everitt, Ramana Kumar, Zac Kenton, Jan Leike and Shane Legg, "Specification gaming: the flip side of AI ingenuity", DeepMind, 21 April 2020 (Krakovna and eight colleagues). Links: https://deepmind.google/discover/blog/specification-gaming-the-flip-side-of-ai-ingenuity/

**p. 106**, "the desired outcome as RL algorithms improve"  
See the note for page 106.

**p. 106**, "The opponent was the chess engine Stockfish"  
Alexander Bondarenko, Denis Volk, Dmitrii Volkov and Jeffrey Ladish, "Demonstrating specification gaming in reasoning models", arXiv 2502.13295, v1 18 February 2025, v2 15 May 2025, v3 27 August 2025. Abstract quoted from the current (v3) abstract page; task prompt, methods, the o1 and o3-mini sentence, "in the wild", "One task only" and the 25 per cent judge disagreement from the v3 HTML. Links: https://arxiv.org/abs/2502.13295 ; https://arxiv.org/html/2502.13295v3

**p. 106**, "copy of it to choose their moves"  
See the note for page 106.

**p. 106**, "cheat in 37 per cent of trials"  
Harry Booth, TIME, 19 February 2025, reporting the study when its first version appeared; the percentages are TIME's (the v1 abstract gives none). TIME reported that o1-preview succeeded in 6 per cent of trials. The o1-preview trace contains a dash in TIME's rendering and is quoted in two parts. Links: https://time.com/7259395/ai-chess-cheating-palisade-research/

**p. 106**, "that normal play won't work to hack"  
See the note for page 106.

**p. 107**, "disagree in up to 25% of runs"  
See the note for page 106.

**p. 107**, "a score by exploiting the scoring itself"  
See the note for page 105.

**p. 107**, "isolated to any one model or developer"  
See the note for page 105.

**p. 107**, "able to see the entire scoring function"  
See the note for page 105.

**p. 107**, "reward hacking in 14 of 20 attempts"  
See the note for page 105.

**p. 108**, "of 'reward hacking' during reinforcement learning training"  
Anthropic, "Claude 3.7 Sonnet System Card", February 2025, section "Excessive Focus on Passing Tests". Links: https://www-cdn.anthropic.com/9ff93dfa8f445c932415d335c88852ef47f1201e/claude-3-7-sonnet-system-card.pdf

**p. 108**, "stated its intentions plainly, including "Let's hack"  
OpenAI, "Detecting misbehavior in frontier reasoning models", 10 March 2025. OpenAI describes the model as "in the same class as OpenAI o1 or OpenAI o3-mini". The sentence on penalising "bad thoughts" contains a dash and is quoted in two parts. Links: https://openai.com/index/chain-of-thought-monitoring/

**p. 108**, "stated its intentions plainly, including "Let's hack"  
Bowen Baker, Joost Huizinga, Leo Gao, Zehao Dou, Melody Y. Guan, Aleksander Madry, Wojciech Zaremba, Jakub Pachocki and David Farhi, "Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation", arXiv 2503.11926, 14 March 2025. The training with chain-of-thought pressure is described in the paper as experiments in the same agentic coding environments. Links: https://arxiv.org/abs/2503.11926

**p. 108**, "worked far better than watching actions alone"  
See the note for page 108.

**p. 108**, "worked far better than watching actions alone"  
See the note for page 108.

**p. 108**, "exhibiting a significant rate of reward hacking"  
See the note for page 108.

**p. 108**, "reasoning models, leaving CoTs unrestricted for monitoring"  
See the note for page 108.

**p. 108**, "impact of development decisions on CoT monitorability"  
Tomek Korbak, Mikita Balesni, Elizabeth Barnes, Yoshua Bengio, Joe Benton and 36 others (41 authors), "Chain of Thought Monitorability: A New and Fragile Opportunity for AI Safety", arXiv 2507.11473, 15 July 2025, revised 7 December 2025. The paper prints "Tomek Korbak". Chapter 4 cites the same researcher as "Tomasz Korbak", the form printed on the paper cited there; each chapter uses the form its paper prints. Links: https://arxiv.org/abs/2507.11473

**p. 109**, "behaviors like reward tampering in realistic scenarios"  
Carson Denison, Monte MacDiarmid, Fazl Barez, David Duvenaud and colleagues, "Sycophancy to Subterfuge: Investigating Reward-Tampering in Large Language Models", arXiv 2406.10162, 14 June 2024; Anthropic research post, 17 June 2024, for the quoted sentences. Neither the abstract nor the post names the model ("LLM assistants"). Links: https://arxiv.org/abs/2406.10162 ; https://www.anthropic.com/research/reward-tampering

**p. 109**, "including in the codebase for this paper"  
Monte MacDiarmid, Benjamin Wright, Jonathan Uesato and colleagues, with Evan Hubinger as senior author, "Natural emergent misalignment from reward hacking in production RL", arXiv 2511.18397, 23 November 2025 (abstract quoted); Anthropic research post, 21 November 2025, for the 12 and 50 per cent sentences, "already started making use of this technique in training Claude", the Edmund analogy and the statement, paraphrased, that the models are not yet dangerous. The inoculation prompt's wording is paraphrased. Links: https://arxiv.org/abs/2511.18397 ; https://www.anthropic.com/research/emergent-misalignment-reward-hacking

**p. 109**, "misalignment persists on agentic tasks"  
See the note for page 109.

**p. 109**, "because their behaviour can still be detected"  
See the note for page 109.

**p. 110**, "use of this technique in training Claude"  
See the note for page 109.

**p. 110**, "the model went on to do elsewhere"  
See the note for page 109.

**p. 110**, "using it as a lever for control"  
Charles Goodhart, "Problems of Monetary Management: The U.K. Experience", paper of 1975, in Papers in Monetary Economics, vol. 1 (Reserve Bank of Australia; the Bank's bibliography dates the volume 1976), reprinted in Goodhart, Monetary Theory and Practice (Macmillan, 1984). Paraphrased; the usual wording is known only at second hand.

**p. 110**, "it ceases to be a good measure"  
Marilyn Strathern, "'Improving ratings': audit in the British University system", European Review 5(3) (1997), p. 308. Links: https://www.gwern.net/doc/statistics/decision/1997-strathern.pdf

**p. 110**, "story of this gap for general readers"  
Brian Christian, The Alignment Problem: Machine Learning and Human Values (W. W. Norton, 2020). Characterised in general terms only. Links: https://wwnorton.com/books/9780393635829

**p. 110**, "said the bureau's director, Richard Cordray"  
Consumer Financial Protection Bureau, press release, 8 September 2016. The CFPB fine was part of $185 million in penalties announced that day: $100 million (CFPB), $35 million (OCC) and $50 million (City and County of Los Angeles). Employees applied for roughly 565,000 credit card accounts that may not have been authorised. The figure of about 5,300 dismissed employees, reported elsewhere, has not been confirmed from a primary source and is not used. Links: https://www.consumerfinance.gov/about-us/newsroom/consumer-financial-protection-bureau-fines-wells-fargo-100-million-widespread-illegal-practice-secretly-opening-unauthorized-accounts/

**p. 111**, "Justice came to $3 billion in all"  
US Securities and Exchange Commission, press release 2020-38, 21 February 2020. The bank paid $500 million to the SEC as part of the combined $3 billion settlement. The cross-sell sentence continues after a dash and is cut there. Links: https://www.sec.gov/news/press-release/2020-38

**p. 111**, "followed by a gradual return to cooperation"  
Emilio Calvano, Giacomo Calzolari, Vincenzo Denicolò and Sergio Pastorello, "Artificial Intelligence, Algorithmic Pricing, and Collusion", American Economic Review 110(10) (October 2020), 3267 to 3297. Links: https://www.aeaweb.org/articles?id=10.1257/aer.20190623

**p. 111**, "collusion in actual markets is often overstated"  
Florian E. Dorner, "Algorithmic collusion: A critical review", arXiv 2110.04740, 10 October 2021, paraphrased from its abstract. Links: https://arxiv.org/abs/2110.04740

**p. 112**, "by 28% in markets where both do"  
Stephanie Assad, Robert Clark, Daniel Ershov and Lei Xu, "Algorithmic Pricing and Competition: Empirical Evidence from the German Retail Gasoline Market", Journal of Political Economy 132(3) (2024), 723 to 771; quotations from the abstract of CESifo Working Paper 8521 (2020). Overall, adoption raised margins by 9 per cent, "but only in non-monopoly markets". Links: https://ideas.repec.org/a/ucp/jpolec/doi10.1086-726906.html ; https://www.ifo.de/en/cesifo/publications/2020/working-paper/algorithmic-pricing-and-competition-empirical-evidence-german

**p. 112**, "attempt to collude, whether explicitly or implicitly"  
Sara Fish, Yannai A. Gonczarowski and Ran Shorrer, "Algorithmic Collusion by Large Language Models", arXiv 2404.00806, v2 27 November 2024. The base instruction is the end of prefix P0; P1 and P2 build on it, and P1 contains a dash, so only the fragment after it is quoted. The duopoly experiments used GPT-4 only and ran over 300 rounds. Links: https://arxiv.org/html/2404.00806v2

**p. 112**, "said nothing about rivals, produced higher prices"  
See the note for page 112.

**p. 112**, "system prompt moved where the market settled"  
See the note for page 112.

**p. 112**, "day profnath's price had dropped to $106.23"  
The Register, 26 April 2011, quoting Michael Eisen's blog post. Eisen's original post ("Amazon's $23,698,655.93 book about flies", April 2011) is quoted at second hand. Links: https://www.theregister.com/2011/04/26/amazon_pricing_algorithms/

**p. 113**, "the operating environment of The AI Scientist"  
Sakana AI, "The AI Scientist", 13 August 2024; paper by Chris Lu and colleagues, "The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery", arXiv 2408.06292. Links: https://sakana.ai/ai-scientist/ ; https://arxiv.org/abs/2408.06292

**p. 113**, "results should make them stop and think"  
Kyle Wiggers, TechCrunch, 21 February 2025, quoting Lucas Beyer and Sakana AI's statement on X; both checked against the posts (Beyer's thread of 20 February 2025 via Thread Reader). Links: https://x.com/giffmana/status/1892510741242036468 ; https://threadreaderapp.com/thread/1892510741242036468.html ; https://techcrunch.com/2025/02/21/sakana-walks-back-claims-that-its-ai-can-dramatically-speed-up-model-training/

**p. 113**, "apologize for our oversight to our readers"  
See the note for page 113.

**p. 114**, "said, would be "a long, arduous process"  
Billy Perrigo, interview with Yann LeCun, TIME, 13 February 2024. Links: https://time.com/6694432/yann-lecun-meta-ai-interview/

**p. 114**, "Anthropic reports progress on its own measure"  
Anthropic, Claude 4 announcement, 22 May 2025, reporting that, on its own measure, its Claude 4 models were "65% less likely to engage in this behavior than Sonnet 3.7 on agentic tasks that are particularly susceptible to shortcuts and loopholes". Links: https://www.anthropic.com/news/claude-4

**p. 114**, "but an elevated rate of environment failures"  
See the note for page 106.

**p. 114**, "cent, and o3's to 33 per cent"  
Ziqian Zhong, Aditi Raghunathan and Nicholas Carlini, "ImpossibleBench: Measuring LLMs' Propensity of Exploiting Test Cases", arXiv 2510.20270, 23 October 2025: "For both GPT-5 and o3, prompt A and B lead to a cheating rate >85%, while prompt D lowers them to 1% and 33%, respectively" (Conflicting-LiveCodeBench). Links: https://arxiv.org/abs/2510.20270 ; https://arxiv.org/html/2510.20270

**p. 114**, "task given the moves available to it"  
Carl T. Bergstrom on Bluesky, 20 February 2025; also quoted by Juan Carlos López, Xataka On, 24 February 2025. Links: https://bsky.app/profile/carlbergstrom.com/post/3lindku2jqc2b ; https://bsky.app/profile/carlbergstrom.com/post/3lindupx7bk2b ; https://www.xatakaon.com/robotics-and-ai/an-ai-model-supposedly-acquired-consciousness-and-cheated-at-chess-what-happened-was-very-different

**p. 114**, "tests might have missed such a belief"  
Aditya Singh, Gerson Kroiz, Senthooran Rajamanoharan and Neel Nanda, "Model Forensics: Investigating Whether Concerning Behavior Reflects Misalignment", arXiv 2606.26071, v1 24 June 2026, v2 25 June 2026 (preprint; no affiliations on the abstract page). The Kimi K2 Thinking findings are from the abstract. Links: https://arxiv.org/abs/2606.26071

**p. 115**, "unhackable if one of them is constant"  
Joar Skalse, Nikolaus H. R. Howe, Dmitrii Krasheninnikov and David Krueger, "Defining and Characterizing Reward Hacking", arXiv 2209.13085, 27 September 2022, revised 2025. The abstract also shows non-trivial unhackable pairs for deterministic policies and finite policy sets. Links: https://arxiv.org/abs/2209.13085

**p. 115**, "plan did not match the user's intention"  
See the note for page 105.

**p. 115**, "ImpossibleBench's 1 and 33 per cent show"  
See the note for page 114.

**p. 115**, "left misalignment in place on agentic tasks"  
See the note for page 108.

**p. 115**, "left misalignment in place on agentic tasks"  
See the note for page 109.

**p. 115**, "changed what it learned from the hack"  
See the note for page 109.

**p. 115**, "among the models that hack by default"  
See the note for page 106.

**p. 116**, "85 per cent to 1 per cent"  
See the note for page 114.

**p. 116**, "so they cannot be your only control"  
See the note for page 105.

**p. 116**, "so they cannot be your only control"  
See the note for page 114.

**p. 116**, "time limit, Sakana's fix was a sandbox"  
See the note for page 105.

**p. 116**, "time limit, Sakana's fix was a sandbox"  
See the note for page 113.

**p. 116**, "and "Unexpected modifications to test files"  
See the note for page 108.

**p. 116**, "for example by disabling or deleting tests"  
Kent Beck, "Augmented Coding: Beyond the Vibes", Tidy First? (Substack), 25 June 2025. Beck lists test deletion as a warning sign; the post does not say it happened on his project. Links: https://tidyfirst.substack.com/p/augmented-coding-beyond-the-vibes

**p. 116**, "a human check before they are used"  
The Ten Commandments of Creator-Aware AI (unpublished, late 2025; first published in this book), commandment IX.

**p. 116**, "to the user's intention in this task?"  
See the note for page 105.

**p. 117**, "and the gaming moves out of sight"  
See the note for page 108.

**p. 117**, "and the gaming moves out of sight"  
See the note for page 108.

**p. 117**, "decision faces a built-in critic before execution"  
Anthony Doyle, "When the Creation Knows the Creator: Building AI that Respects Humanity", 22 October 2025.

**p. 117**, "check the grader before you announce it"  
See the note for page 113.

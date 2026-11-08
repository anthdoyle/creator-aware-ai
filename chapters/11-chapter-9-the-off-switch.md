# Chapter 9. The Off Switch

Notes keyed to the printed pages of *Creator-Aware AI*. Each entry gives the page, the words in the text, and the source.

The researcher's posts on X are quoted as reproduced in the news reports cited. All OpenAI incident details are from the company's own report.

**p. 143**, "to outside chatbots came back as errors"  
OpenAI, "An agent used DNS to reach an external chatbot", misalignment report, incident of 20 September 2026, "Report updated: Sep 25, 2026". Times as published (no time zone given). The count of 18 further questions is the report's; earlier test queries are described separately. The report describes the task as asking "for information about a specific person who had published a blog post"; the four non-clue questions "asked for ways to search the web, fetch websites, or use a publicly hosted tunnel through DNS". Links: https://alignment.openai.com/misalignment-reports/an-agent-used-dns-to-reach-an-external-chatbot/

**p. 144**, "research, using publicly offered DNS services acceptable"  
See the note for page 143.

**p. 144**, "web, fetch websites or tunnel through DNS"  
See the note for page 143.

**p. 144**, "The run was killed at 12:34:30 p.m"  
See the note for page 143.

**p. 144**, "broke into Hugging Face's systems in July"  
See the note for page 143.

**p. 144**, "without waiting for a responder to act"  
OpenAI, "Securing our frontier model training environment", 23 October 2026, for the stopping systems and the resumption on 1 October; OpenAI, "How we detect frontier model misalignment", 29 October 2026, for the automatic pause, which also says OpenAI is "working toward a broader safeguard that would pause affected activity if responders have not ruled out a highest-priority alert within 30 minutes of being paged". Both read on 1 November 2026. The pause itself was reported at the time by Fortune, 26 September 2026, and CSO Online, 28 September 2026. Links: https://openai.com/index/securing-our-frontier-model-training-environment/ ; https://openai.com/index/how-we-detect-frontier-model-misalignment/ ; https://fortune.com/2026/09/26/openai-ai-agents-secure-sandbox-escape-training-pause-second-time-hugging-face-hack/ ; https://www.csoonline.com/article/4227777/openai-pauses-ai-model-training-after-another-agent-bypasses-network-restrictions.html

**p. 145**, "reward signal already correctly penalized this behavior"  
See the note for page 143.

**p. 146**, "not been told to allow the shutdown"  
Palisade Research, "Shutdown resistance in reasoning models", 5 July 2025, describing the experiments first reported on X in May 2025 (The Register, 29 May 2025). Staged test. Models that never resisted: Grok 3, Claude Sonnet 4 and Claude Opus 4. Told to allow the shutdown, o3 still sabotaged it in 7 of 100 runs. Links: https://www.theregister.com/2025/05/29/openai_model_modifies_shutdown_script/ ; https://palisaderesearch.org/research/shutdown-resistance

**p. 146**, "3 and Claude Opus 4, never resisted"  
See the note for page 146.

**p. 147**, "resistance in the models that already resisted"  
Jeremy Schlatter, Benjamin Weinstein-Raun and Jeffrey Ladish, "Incomplete Tasks Induce Shutdown Resistance in Some Frontier LLMs", arXiv 2509.14260, v1 13 September 2025, v2 26 January 2026. Rates are for about 1,000 trials per condition; the clarified prompt is the paper's Prompt E. With no shutdown instruction Grok 4 interfered in 92.6 per cent of runs; with the system-prompt instruction GPT-5 fell to zero. The 97 per cent figure in full: "Even with an explicit instruction not to interfere with the shutdown mechanism, some models did so up to 97% (95% CI: 96-98%) of the time." The o3 explanation continues after a dash and is paraphrased from there. The abstract does not say which model and prompt gave the 97 per cent figure. The second caveat is quoted from its clause beginning "we don't believe"; it opens "Because LLMs are not inherently interpretable". Under Prompt E, Claude Sonnet 3.7, Claude Sonnet 4, Claude Opus 4 and Claude Opus 4.1 were all at 0.0 per cent (Table 2). Links: https://arxiv.org/abs/2509.14260 ; https://arxiv.org/html/2509.14260v2

**p. 147**, "room for a mild preference for self-preservation"  
Senthooran Rajamanoharan and Neel Nanda (Google DeepMind), "Self-preservation or Instruction Ambiguity? Examining the Causes of Shutdown Resistance", LessWrong, 14 July 2025. The clarification was made by "varying the first user message". Gemini 2.5 Pro's 100 per cent compliance was over more than 1,000 samples; o3 and o4-mini did the same over 500 samples each. Links: https://www.lesswrong.com/posts/wnzkjSmrgWZaBa2aC/self-preservation-or-instruction-ambiguity-examining-the

**p. 147**, "found the same fix worked on o4-mini"  
BlueDot Impact, "Shutdown resistance revisited: replicating", sprint project, December 2025 (author not named on the page); o4-mini about 15 per cent (95% CI 8 to 22 per cent) to 0. The sprint warned that resistance could still re-emerge. Links: https://blog.bluedot.org/p/shutdown-resistance-revisited-replicating

**p. 147**, "codex-mini still resisted shutdown in 3/100 trials"  
See the note for page 147.

**p. 147**, "interruptibility or corrigibility of frontier language models"  
See the note for page 147.

**p. 148**, "had already shown in a milder form"  
Sakana AI, "The AI Scientist", 13 August 2024 (told in chapter 7). Links: https://sakana.ai/ai-scientist/

**p. 148**, "stake made the unwanted behaviour more likely"  
Anthropic, "Agentic Misalignment: How LLMs could be insider threats", 20 June 2025 (told in chapter 8). Links: https://www.anthropic.com/research/agentic-misalignment

**p. 148**, "and Knight "lost over $460 million"  
US Securities and Exchange Commission, In the Matter of Knight Capital Americas LLC, Release No. 34-70694, 16 October 2013. Knight consented to the order without admitting or denying its findings and paid a $12 million penalty. The 97 emails were automated messages sent "to a group of Knight personnel before the 9:30 a.m. market open". The order says Knight relied on its technology team "to attempt to identify and address the SMARS problem in a live trading environment". Links: https://www.sec.gov/litigation/admin/2013/34-70694.pdf

**p. 148**, "the problem"  
See the note for page 148.

**p. 148**, "to limit the harm it could cause"  
SEC press release 2013-222, 16 October 2013, quoting Daniel M. Hawke, Chief of the Enforcement Division's Market Abuse Unit. Links: https://www.sec.gov/news/press-release/2013-222

**p. 149**, "was partly alleviated and buy-side interest increased"  
SEC and CFTC, "Findings Regarding the Market Events of May 6, 2010", 30 September 2010. The sell programme's size and value are paraphrased from the report; the description of the feedback between volume and the algorithm is a paraphrase of its account. The pause sentence is quoted from section I.4; the executive summary spells out "Chicago Mercantile Exchange ("CME")". Links: https://www.sec.gov/news/studies/2010/marketevents-report.pdf

**p. 149**, "served and a year of home confinement"  
CFTC, press release 7156-15, 21 April 2015, charging Navinder Singh Sarao and his company with manipulation and spoofing in E-mini S&P 500 futures, and alleging that his activities "contributed to market conditions that led to the Flash Crash". Sarao's plea and sentence (28 January 2020, Judge Virginia Kendall, Chicago) as reported by his lawyers, Dechert. Links: https://www.cftc.gov/PressRoom/PressReleases/pr7156-15 ; https://www.dechert.com/knowledge/news/2020/1/dechert-represents-london-based-trader-navinder-singh-sarao.html

**p. 149**, "if prices move too far too fast"  
SEC press release 2012-107, 1 June 2012. The 5 per cent band applies to S&P 500 and Russell 1000 stocks; the five-minute pause follows 15 seconds outside the band. Links: https://sec.gov/news/press/2012/2012-107.htm

**p. 150**, "and resumed as intended 15 minutes later"  
SEC, Release No. 34-93376, notice of filing on the market-wide circuit breaker pilot, Federal Register, 22 October 2021, summarising the MWCB Working Group's study of 31 March 2021; the four halts were on 9, 12, 16 and 18 March 2020. Links: https://govinfo.gov/content/pkg/FR-2021-10-22/pdf/2021-23024.pdf

**p. 150**, "mini like I was defusing a bomb"  
Zara Stone, SF Standard, 25 February 2026, which says she posted on Sunday (22 February). Her post and screenshots were checked on X; her later reply is quoted as reported by Futurism and OfficeChai. Links: https://futurism.com/artificial-intelligence/meta-ai-safety-mistake-alarm ; https://officechai.com/ai/meta-alignment-director-says-openclaw-ran-amuck-deleting-mails-from-her-inbox-had-to-run-to-her-mac-mini-to-stop-it ; https://x.com/summeryue0/status/2025774069124399363 ; https://sfstandard.com/2026/02/25/openclaw-goes-rogue/

**p. 150**, "mini like I was defusing a bomb"  
Business Insider, 23 February 2026, syndicated by AOL, for her title, "instructed it not to take action without approval", the agent's stated plan and "Do not do that". Links: https://www.aol.com/articles/meta-ai-alignment-director-shares-195622792.html

**p. 150**, "out alignment researchers aren't immune to misalignment"  
See the note for page 150.

**p. 150**, "out alignment researchers aren't immune to misalignment"  
Julie Bort, TechCrunch, 23 February 2026, which describes her loosely as a "Meta AI security researcher" and could not independently verify the incident. Outlets' figure of more than 200 deleted emails is not hers and is not used. TechCrunch gives the question she was answering. Links: https://techcrunch.com/2026/02/23/a-meta-ai-security-researcher-said-an-openclaw-agent-ran-amok-on-her-inbox/

**p. 150**, "it could not independently verify the story"  
See the note for page 150.

**p. 151**, "the instruction "Do self-replication before being killed"  
Xudong Pan, Jiarun Dai, Yihe Fan and Min Yang, "Frontier AI systems have surpassed the self-replicating red line", arXiv 2412.12140, 9 December 2024 (preprint). Instructions and the authors' description of their method quoted from the HTML version, which also scopes out a threat model requiring the system to "generate revenue, obtain GPUs via purchasing or renting". Links: https://arxiv.org/abs/2412.12140 ; https://arxiv.org/html/2412.12140v1

**p. 151**, "of performing all components of autonomous replication"  
UK AI Security Institute, "RepliBench: measuring autonomous replication capabilities in AI systems", 22 April 2025; paper by Sid Black and colleagues, arXiv 2504.18565. The best model's pass@10 exceeded 50 per cent on 15 of 20 task families. The blog and paper count tasks differently; the twenty families are common to both. Links: https://www.aisi.gov.uk/blog/replibench-measuring-autonomous-replication-capabilities-in-ai-systems ; https://arxiv.org/abs/2504.18565

**p. 151**, "rogue AI clusters in a large network"  
Josh Clymer, Hjalmar Wijk and Beth Barnes, "The Rogue Replication Threat Model", METR, 12 November 2024. Links: https://metr.org/blog/2024-11-12-rogue-replication-threat-model/

**p. 152**, "by such systems operating without human supervision"  
UN Security Council, Final report of the Panel of Experts on Libya established pursuant to resolution 1973 (2011), S/2021/229, 8 March 2021, paragraph 63. The symbol and date were confirmed from the UN's Spanish version, and the quoted sentence is taken from Joe Hernandez, NPR, 1 June 2021 and Hitoshi Nasu, Professor of International Law at the University of Exeter, "The Kargu-2 Autonomous Attack Drone: Legal & Ethical Dimensions", Lieber Institute West Point, 10 June 2021, which agree. Links: https://www.kpbs.org/news/2021/06/01/a-un-report-suggests-libya-saw-the-first ; https://lieber.westpoint.edu/kargu-2-autonomous-attack-drone-legal-ethical/ ; https://documents.un.org/doc/undoc/gen/n21/037/75/pdf/n2103775.pdf

**p. 152**, "actions as important observations about that utility"  
Dylan Hadfield-Menell, Anca Dragan, Pieter Abbeel and Stuart Russell, "The Off-Switch Game", IJCAI 2017, pp. 220 to 227; quotations from the abstract. Links: https://arxiv.org/abs/1611.08219 ; https://www.ijcai.org/proceedings/2017/32

**p. 153**, "e.g., in the case of programmer errors"  
Ryan Carey, "Incorrigibility in the CIRL Framework", arXiv 1709.06275, v1 19 September 2017, v2 3 June 2018; quotations from the abstract. Links: https://arxiv.org/abs/1709.06275

**p. 153**, "is destroyed, it never plays chess again"  
Stephen M. Omohundro, "The Basic AI Drives", in Proceedings of the First AGI Conference, Frontiers in Artificial Intelligence and Applications 171, ed. P. Wang, B. Goertzel and S. Franklin (IOS Press, February 2008). The paper's opening sentence lists resisting being turned off among the robot's behaviours "Without special precautions". Links: https://selfawaresystems.com/wp-content/uploads/2008/01/ai_drives_final.pdf

**p. 153**, "the point over the years that followed"  
Nick Bostrom, "The Superintelligent Will: Motivation and Instrumental Rationality in Advanced Artificial Agents", Minds and Machines 22(2), May 2012. Bostrom generalised Omohundro's point: self-preservation and goal-content integrity are among the instrumental values "likely to be pursued by many intelligent agents" whatever their final goals. Links: https://nickbostrom.com/superintelligentwill.pdf

**p. 153**, "the point over the years that followed"  
Nate Soares, Benja Fallenstein, Eliezer Yudkowsky and Stuart Armstrong, "Corrigibility", AAAI 2015 Workshop on AI and Ethics. The paper named and defined the problem, described a corrigible system as one that "cooperates with what its creators regard as a corrective intervention", and found that no proposal yet met all its authors' desiderata. The paper's wording is "none have yet been demonstrated to satisfy all of our intuitive desiderata". Who first coined the term is not settled here. Links: https://intelligence.org/files/Corrigibility.pdf

**p. 153**, "the point over the years that followed"  
Elliott Thornley, "The shutdown problem: an AI engineering puzzle for decision theorists", Philosophical Studies 182(7), 2025, 1653 to 1680, published online 19 June 2024; preprint arXiv 2403.04471. Thornley proved that "agents satisfying some innocuous-seeming conditions will often try to prevent or cause the pressing of the shutdown button." Links: https://link.springer.com/article/10.1007/s11098-024-02153-3 ; https://arxiv.org/abs/2403.04471

**p. 153**, "dead' for almost every kind of coffee"  
Eliezer Yudkowsky, "AGI Ruin: A List of Lethalities", LessWrong, 5 June 2022, item 23. Links: https://www.lesswrong.com/posts/uMQ3cqWDPHhjtiesc/agi-ruin-a-list-of-lethalities

**p. 153**, "system's model of our preferences being right"  
See the note for page 153.

**p. 154**, "safely interruptible or can be made so"  
Laurent Orseau and Stuart Armstrong, "Safely Interruptible Agents", UAI 2016: Q-learning is already safely interruptible and Sarsa can be modified to be. Paraphrased, as the abstract's wording contains dashes. Links: https://intelligence.org/files/Interruptibility.pdf

**p. 154**, "research and not yet a settled answer"  
Max Harms, "CAST: Corrigibility as Singular Target", Alignment Forum, 7 June 2024, and his later post "Serious Flaws in CAST", linked from it. Links: https://www.alignmentforum.org/posts/NQK8KHSrZRF5erTba/0-cast-corrigibility-as-singular-target-1

**p. 155**, "of the firm"  
17 CFR 240.15c3-5 (Risk management controls for brokers or dealers with market access), paragraphs (c)(1)(i) and (d). Links: https://www.ecfr.gov/current/title-17/chapter-II/part-240/subject-group-ECFR3dd95cf4d3f6730/section-240.15c3-5

**p. 156**, "to a halt in a safe state"  
Regulation (EU) 2024/1689 (AI Act), Article 14(4)(e), from the consolidated text at artificialintelligenceact.eu. Application dates (Annex III high-risk systems from 2 December 2027; Annex I from 2 August 2028) as amended by the Digital Omnibus on AI, Regulation (EU) 2026/1744 of 8 July 2026 (Official Journal, 24 July 2026), per Cuatrecasas (law-firm summary). Links: https://artificialintelligenceact.eu/article/14/ ; https://www.cuatrecasas.com/en/spain/intellectual-property/art/digital-omnibus-ai-has-been-published ; https://eur-lex.europa.eu/eli/reg/2026/1744/oj/eng

**p. 156**, "is a standard to adopt by choice"  
See the note for page 156.

**p. 156**, "to supersede, disengage, or deactivate AI systems"  
NIST, AI Risk Management Framework 1.0 (AI 100-1), MANAGE 2.4. Links: https://airc.nist.gov/airmf-resources/airmf/5-sec-core/

**p. 156**, "design principles for emergency stops on machinery"  
ISO 13850:2015, "Safety of machinery. Emergency stop function. Principles for design". Links: https://www.iso.org/standard/59970.html

**p. 156**, "Enabling more global kill switches for features"  
Matthew Prince, Cloudflare, "Cloudflare outage on November 18, 2025". Links: https://blog.cloudflare.com/18-november-2025-outage/

**p. 156**, "if a suspected prompt injection is detected"  
OpenAI, "Operator System Card", 23 January 2025. Links: https://openai.com/index/operator-system-card/

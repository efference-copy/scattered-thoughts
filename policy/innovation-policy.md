# Innovation Policy

**Note: this is a very general overview of innovation policy. Domain-specific innovation policy (like clinical trial reform for the FDA) will be included in the more relevant article**

## Patents

- The rationale behind patents are that certain technologies are difficult to invent but easy to copy, and since there's no way to capture a sufficient share of the value created by new technology private actors will underprovision innovation.
    - Of course this reasoning only applies to hard-to-invent/easy-to-copy technology. If an invention is easy-to-invent (like open source software) or hard-to-copy (like high performance natgas turbines) then the logic of patents breaks down, but in practice it's hard to know ex ante whether a specific technology falls into that bucket.
- There is a fair bit of evidence that patents help innovation. But it's possible to go too far. Most technological innovation is incremental improvements on existing tech and excessive patent term lengths hinder that. Intellectual property is a delicate balancing act.
- [Patent thickets in particular are a problem](https://www.niskanencenter.org/reforms-targeting-patent-thickets-would-speed-up-the-arrival-of-lower-cost-drugs/). Pharmaceutical firms can use method-of-use patents (for different indications), formulation patents (once-a-day and twice-a-day dosing as separate patents), and process patents to extend the life of a pharmaceutical patent long after the original composition of matter patent has expired.
- That said, patents are probably better than other methods of compensating innovation like innovation prizes since the latter requires knowing the true value of an invention in advance.

### Reforms to the US patent system

#### Amend America Invents Act (AIA) to repeal NHK-Fintiv rule
- The 2011 AIA moved the US to a first-to-file system and created the Patent Trial and Appeals Board (PTAB)
- PTAB was intended to resolve patent disputes more quickly than circuit courts using _inter partes_ review (IPR). IPR uses administrative judges overseeing an Article I tribunal. [IPR is better than the federal courts on pretty much every metric - higher affirmance rate, lower cost to the taxpayer, low litigation costs, level of patent litigation experience by judges, faster turnaround](https://www.niskanencenter.org/pressure-at-the-patent-office/).
- Republicans generally dislike IPR because they dislike Article 1 courts in general and because they want stronger and more expansive patent rights.
    - Interestingly, SCOTUS doesn't seem to agree. They often overrule the very patent friendly US Court of Appeals of the Federal Circuit (as in the Alice/Mayo test for Section 101 patentability)
        - The Alice/Mayo test is under threat via the proposed [Patent Eligibility Restoration Act](https://www.eff.org/deeplinks/2023/09/bill-would-boost-worst-patents-software-and-human-genes). The main rationale is international competitiveness (Europe and Asia largely allow patentability of natural and abstract phenomena) but much of the doom-and-gloom predictions of the IP lobby have not come to pass. For example, diagnostic testing is if anything more vibrant than it would otherwise be and is mostly constrained by FDA policy.
    - Howard Lutnick, Trump 2's commerce secretary, [wants a patent registration system with no ex ante examination of patent claims](https://blog.withedge.com/p/patent-registration-system-panacea). The problem with this approach, besides clogging up the courts with dubious patent claims, is that a patent is inherently an artificial government monopoly that requires some level of governmental discretion and PTAB judges are far more qualified to exercise that judgment than circuit judges.
- Trump 1's PTAB appointee undermined IPR with the NHK-Fintiv rule, prohibiting the use of IPR if a parallel case is in federal court. This incentivizes the weaker claimant to file in federal court to preclude IPR resolution.
- IPR has proven to be an effective tool in combatting non-practicing entities (NPEs, sometimes called patent trolls). There has been a marked drop off in patent troll ligitation since AIA's passage where before [patent trolls were costing the country ~$29 billion per year](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2091210).

#### Replace patent maintenance fees with a Harberger Tax
- [A Harberger Tax works by levying a tax on the self-assessed value of an asset](https://arpitrage.substack.com/p/a-harberger-tax-on-patents). The twist is that anyone, at any time, can force a buy-out of the asset at the self-assessed value. This encourages the asset owner to give a truthful value of the asset to the tax assessor.
- It's essentially Georgism for patents. Companies who can actually commercialize the patent can buy out NPEs who would rather file litigation and sit on valuable patents.
- The revenue raised from the Harberger Tax could be used for public patent buyouts. This would probably be superior to alternatives like [Michael Kramer's patent auctions](https://www.nber.org/system/files/working_papers/w6304/w6304.pdf) which would be vulnerable to collusion.
- It's also superior to march-in rights via Bayh-Dole, which would be capricious and arbitrary in execution.
- The Harberger Tax could disincentivize innovation as small firms would be encouraged to over-assess to defend their patent from a forced buyout but would thus incur a tax liability higher than they would be able to sustain. The solution could be both a grace period (3-5 years?) before the tax is levied and have the tax rate be very low.

#### End fee diversion at USPTO
- USPTO is a fee-funded agency, but Congress is able to effectively divert the funding as an accounting trick in reconciliation bills. This robs the USPTO of resources to process patent applications more quickly.
- Ended in the proposed PREVAIL Act, but that bill includes a lot of restrictions on IPR that are undesirable.

#### Use generative AI for prior art searches and drafting rejection letters at USPTO
- Seems inevitable that generative AI will be utilized to some extent in all white collar work, but patent examination is a particularly promising use case as prior art searches comprise majority of examiners' time and genAI is essentially a glorified search engine.

## R&D

### Basic R&D

- R&D is the primary mechanism of economic development at the production frontier. Other major determinants of economic growth like population size, rule of law, and deep financial markets exist mainly to enable the development and commercialization of new technology.
- Most basic R&D is publicly funded and most applied R&D is privately funded. Traditionally they've been seen as complementary. This may not be true - there are only so many chemists/biologists/computer scientists/etc so public R&D spending has _some_ crowding-out effect ceteris paribus - but public R&D is good for growth because it tends to be high risk/high reward and benefit smaller firms that are financially-constrained.
    - Though it seems counterintuitive, the public sector is better suited for risky investments due to its effectively infinite time horizon and massive scale.
- Total R&D spend as percentage of GDP has remained steady but the composition has shifted considerably. Since the end of the Cold War public R&D has shrunk and private R&D has grown. This has coincided with a decline in TFP growth (correlation is not causation, I know).

### Reforms to Basic R&D funding

#### Resurrect the Endless Frontier Act and significantly increase basic R&D spend
- Original version of EFA had $100 billion in basic R&D (~1.2% of GDP)
- Could be coupled with reforms to basic R&D grant process (below)
- Could also include a regional development component. Jonathan Gruber and Simon Johnson created [a map of viable innovation hubs in regions that currently lack significant high tech employment](https://www.jump-startingamerica.com/technology-hub-map).
    - I generally dislike regional development initiatives as they can artificially weaken network effects but R&D spending in regional hubs like Columbus, OH is far better than high speed broadband to middle-of-nowhere rural areas.
    - Incidentally this would help the Dems electorally as high tech/R&D employment is politically very blue.

#### Mandate a fixed percentage (10%?) of R&D grants to be used for experimental grant approaches
- R&D productivity has declined over time and virtually all American scientists agree the NIH/NSF incentivize risk aversion in their grant process. This has made the grant process more political and worse for [the weird nerds of academia](https://www.writingruxandrabio.com/p/the-weird-nerd-comes-with-trade-offs).
- We don't know what grant approaches are most successful for scientific productivity. As such, R&D agencies like the NIH and NSF should set aside a fixed percentage of their appropriations to experiment with new grant methods. Congress should also created a Metascience Board that collects data on the effectiveness of these new grant methods to inform future appropriations.
- Some examples of new approaches to R&D grants that could be considered:
    - ["Golden ticket" grant funding](https://ifp.org/american-science-should-take-a-lot-more-risks/). Each internal peer reviewer can automatically fund one grant application once per funding cycle regardless of peer review score.
        - This is similar to how ARPA-model orgs work, with program managers who have a lot of personal discretion over which projects to approve.
    - [Grant lotteries](https://ifp.org/piloting-and-evaluating-nsf-science-lottery-grants/). High scoring applications that don't receive an award are enrolled in a lottery where a set number are selected for funding at random
    - Grants with relaxed reporting and application requirements
    - R&D vouchers for private firms to make investments in open access research
    - Individual researcher fellowships a la NIH's R35 and NSF's Alan T. Waterman award
    - [Independent scholarships](https://ifp.org/broadening-the-knowledge-economy-through-independent-scholarship/)
    - [Focused Research Organizations](https://fas.org/publication/focused-research-organizations-a-new-model-for-scientific-research/)
        - Could be structured [as a quadratic funding match](https://ifp.org/fund-organizations-not-projects-diversifying-americas-innovation-ecosystem-with-a-portfolio-of-independent-research-organizations/#plan-of-action)
        - [BBN-model orgs](https://www.freaktakes.com/p/a-scrappy-complement-to-fros-building) serve as a cheaper public-private alternative
- In addition, given the replication crisis, [R&D agencies could be mandated to set aside a fixed percentage (3-5%?) to 'red team' high impact research by running replications](https://goodscienceproject.org/articles/how-to-improve-both-scientific-innovation-and-reproducibility-at-once/). The threat of well-funded replication efforts could incentivize PIs and researchers to publish more null results and thus improve research productivity.
- Grant applicants could also enroll in a program where their unfunded applications get added to a public database where private entities and nonprofit funds could choose to fund the grant even if the NIH or NSF doesn't.

#### Cut down on administrative burdens for grant applicants
- NIH researchers spend nearly half of their time on grant writing and that number continues to worsen.
- Reporting requirements have increased as a result of political pressure from the Stanford yacht indirect costs scandal in the 90s and efforts by demagogue Senators like William Proxmire to mock superficially strange grant applications.
- [There have been a number of reports commissioned on how to reduce the burden on PIs over the years with limited follow-up](https://goodscienceproject.org/articles/the-efforts-to-reform-research-bureaucracy-to-date/). The next time Congress commissions a report into this matter they should structure it like BRAC: all recommendations automatically go into effect unless Congress overrules it.
- Some common recommendations include:
    - Allow NSF to reject applications without scoring them like the NIH does
    - Allow NIH to bypass external peer review likw the NSF does with EAGER/RAPID grants
    - Reduce pre-award workloads and postpone most grant reporting requirements until after the award is issued
    - Develop a single universal R&D grant application for the entire federal government
    - Create a centralized assurances database for participating institutions
    - Create a centralized database for PI info, biosketches, etc
- Envelope math on halving administrative burdens at the NIH [could free up ~$2 billion in funding](https://goodscienceproject.org/articles/heres-how-we-could-get-an-extra-2-billion-in-biomedical-research-per-year-for-free/).


### Applied R&D

- R&D is sometimes divided into Technology Readiness Levels (TRL). Basic R&D covers TRL levels 1-3 and private sector applied R&D covers TRL levels 7-9. There's a funding gap for TRL levels 4-6, the so-called "valley of death".
- Venture capital focuses on companies that can very quickly cover the valley of death, namely low-capital intensity firms in biotech, IT, and finance. Hard tech companies languish.
- Building capacity in TRL levels 4-6 will likely require more private sector involvement and more contract research organizations.
- This is a distinctive weakness of the US compared to China. China has imitated the German model for applied R&D (e.g. the Fraunhofer Institute, which contracts research for SMEs and focuses on applied industrial R&D). The US has attempted similar programs (Manufacturing USA and the Manufacturing Extension Program) to little success. As a result China dominates TRL levels 4-6.

### Reforms to Applied R&D funding

#### Amend NCRPA to allow Self-Organizing Industry Investment Boards
- Proposed by Paul Romer [here](https://paulromer.net/statement-for-house-budget-comittee/industry_boards.pdf).
- Essentially copies the Agricultural Marketing Order system but for R&D. An industry can vote to require all participant firms to set aside 1-2% of revenue for funding open access research via competing nonprofit research boards.
- This somewhat solves the knowledge problem of R&D allocation by allowing firms to "vote" on what they think will be most valuable for the industry overall.
- Similar to [precompetitive R&D consortia like SEMATECH](https://americancompass.org/policy-brief-pre-competitive-rd-consortia/).
- This system would likely require antitrust exemptions. The NCRPA was passed to give some antitrust exemptions to standards-setting organizations and precompetitive consortia, but there is still considerable reluctance to rely on NCRPA protections since nonexempt ventures would be subject to treble damages.

#### Reform SBIR/STTR grants

- All federal agencies that have an extramural R&D budget above $100 million (in the case of SBIR) or $1 billion (in the case of STTR) must set aside a set percentage of their R&D budget for grants to small startups trying to scale up new technology.
- Though the program has had some successes (ex: Qualcomm), it's somewhat infamous for the number of "SBIR mills", firms that repeatedly receive Phase I grants without ever scaling up to Phase II/III grants.
    - [1% of SBIR awardees capture 21% of all awards](https://thehill.com/opinion/congress-blog/3636756-americas-flagship-program-for-innovative-small-businesses-is-broken/).
- SBIR mills cluster around FFRDCs and are usually closely linked with federal R&D centers. Rather than focus on commercialization, SBIR/STTR are increasingly a method for federal R&D labs to claw back the set-aside SBIR/STTR funds.
- SBIR mills are particularly prominent with DoD SBIR grants
- [Simplest reform would be a lifetime cap on Phase I awards per firm](https://www.niskanencenter.org/federal-aid-for-small-business-rd-is-getting-smarter-but-remains-too-easy-to-game/)
    - Could be gamed with firms closing and forming new LLCs. One way around this could be capping the number of SBIR grants per metro area, but this undermines the network effects of our strongest universities.

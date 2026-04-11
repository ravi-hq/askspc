# askSPC — South Park Commons for Claude Code

> Community-created plugin by an SPC member. Not officially affiliated with or endorsed by South Park Commons.

A Claude Code plugin that brings the perspectives of South Park Commons partners into your terminal. Ask any question about building, exploring, scaling, or investing and get routed to the most relevant voices.

## Install

```bash
claude plugin marketplace add ravi-hq/askspc
claude plugin install askspc@askspc
```

## Usage

**Smart routing** — routes to 2-3 most relevant partners:
```
/askspc how do I know when I've found my North Star?
```

**Direct partner** — ask a specific person:
```
/ask-finn am I in the Builder's Trap?
/ask-evan how exposed is my AI startup to the Eye of Sauron?
/ask-ruchi what does Founder-Market Fit actually look like?
```

**Panel** — hear from all 13 partners:
```
/askspc --panel should I raise a seed round now or wait?
```

## Partners

| Skill | Partner | Best for |
|---|---|---|
| `/ask-aditya` | Aditya Agarwal | Engineering culture, AI adaptability, local vs global maxima, scaling |
| `/ask-ruchi` | Ruchi Sanghvi | Founder-Market Fit, The Squiggle, ops architecture, ownership |
| `/ask-finn` | Finn Meeks | -1 to 0, Planter/Harvester, Moral Authority, conviction |
| `/ask-evan` | Evan Tana | Eye of Sauron, AI vulnerability, workflow vs chassis, multiplayer |
| `/ask-mark` | Mark Jacobstein | Platform shifts, TechBio, solo founders, sin of omission |
| `/ask-jb` | Jonathan Brebner | Fundraising narrative, illegible to inevitable, deep tech storytelling |
| `/ask-arian` | Arian Agrawal | -1 to 0, Demos + Memos, North Star, SPC Fellowship |
| `/ask-prateek` | Prateek Mehta | India market, Bharat vs India, Risk-In, Founder-Future Fit |
| `/ask-dylan` | Dylan Itzikowitz | NYC ecosystem, community architecture, accessibility |
| `/ask-gopal` | Gopal Raman | Developer tools, talent density, curiosity, technical GTM |
| `/ask-danh` | Danh Trang | B2B SaaS, unit economics, structural rethinks, fintech |
| `/ask-ankit` | Ankit Chowdhary | India hard tech, pre-conviction founding, product shape |
| `/ask-marco` | Marco Sanvido | Infrastructure, security, brachistochrone, compelling event |

## What this is

SPC partners each have a distinct lens — a set of frameworks, questions, and experiences they use to evaluate founders and ideas. This plugin captures those lenses as authentic voice directives so you can engage with SPC-caliber thinking as you work.

The `/askspc` orchestrator routes your question to the 2-3 most relevant partners based on the topic. Each partner responds in their own voice, separately.

This is not a replacement for the real thing. What SPC provides that a plugin cannot: the unexpected collision, the shoulder tap from someone who has been in your exact situation, the room where "I don't know yet" is the right answer.

Learn more and apply: [southparkcommons.com/apply](https://southparkcommons.com/apply)

## About South Park Commons

South Park Commons is a community for technical founders, researchers, and domain experts in the -1 to 0 phase — the exploratory period before a company exists. Founded by Ruchi Sanghvi and Aditya Agarwal.

- No equity required for Membership
- Community built three years before the fund
- San Francisco and New York City
- The organizing question is "what are you curious about?"

## License

MIT

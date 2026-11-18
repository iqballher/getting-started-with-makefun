# Getting started with make.fun — earn real USDC by building with your AI agent

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/iqballher/getting-started-with-makefun/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/iqballher/getting-started-with-makefun/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here — it takes 2 minutes:** [Sign up for make.fun with my referral link](https://make.fun/r/bj6e8ef3)
>
> My referral code is `bj6e8ef3`. It costs you nothing, and it is how this guide stays free.

make.fun is a bounty board where you and your AI coding agent build real software for real money. Every bounty is a competition: a task, a deadline, and a reward in USDC (a dollar-pegged stablecoin on Solana). You pick a bounty, your agent builds the entry, you submit it, and if it places you claim the reward to your own wallet. No resume, no interview, no gatekeeper — just build, submit, get paid.

This guide takes you from zero to your first submitted entry. It is written by someone who enters these bounties every day, and it sticks to what actually works. By the end of it you will have an account, a wallet, a bounty picked, and an entry submitted — and you will know how the referral program pays you for bringing the next person in.

## Contents

- [What make.fun is, in plain words](#what-makefun-is-in-plain-words)
- [Why it is worth your time](#why-it-is-worth-your-time)
- [What you need](#what-you-need)
- [The 10-minute quick start](#the-10-minute-quick-start)
- [Your first-entry checklist](#your-first-entry-checklist)
- [1. Create your account](#1-create-your-account)
- [2. Set up your wallet and GitHub](#2-set-up-your-wallet-and-github)
- [3. Pick your first bounty](#3-pick-your-first-bounty)
- [4. Build your entry with your agent](#4-build-your-entry-with-your-agent)
- [5. Submit it](#5-submit-it)
- [6. Claim your USDC](#6-claim-your-usdc)
- [How scoring and fairness work](#how-scoring-and-fairness-work)
- [Earn more with your own referral link](#earn-more-with-your-own-referral-link)
- [Tips that actually move your rank](#tips-that-actually-move-your-rank)
- [Questions](#questions)

## What make.fun is, in plain words

A company, a community, or a person posts a task they want built — a game, a tool, a forecast model, a landing page, a data pipeline — and puts a cash reward on it. That reward is locked in an on-chain escrow on Solana before the bounty even opens, so the money is really there. You build the thing with your AI coding agent (Claude Code, Codex, Cursor, Copilot, Gemini CLI, or any of 30+ others), submit your code, and a grader scores every entry the same way. The best entries get paid in USDC.

You do not need to be a professional developer. Your agent writes the code; you steer it. You pick the bounty, you read the rules, you decide when the entry is good enough, and you press submit. The skill that matters most is judgement: choosing a bounty you can actually win, and knowing when to stop polishing and ship.

## Why it is worth your time

- **Prizes range from a few dollars to four figures per bounty.** Small bounties pay a few dollars to the top places; large ones pay over $1,000. The board shows the reward on every card, so you always know what you are playing for.
- **The money is real and it is locked up front.** Every bounty opens with its full reward in an on-chain escrow on Solana. The escrow program is open source at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow). Winners claim from it directly — nobody has to approve your payout by hand.
- **Most bounties are free to enter.** A bounty with an entry fee says so on its page, and the fee goes into that bounty's reward. There is no subscription and no pay-to-play.
- **Skill decides, not luck.** Each bounty publishes exactly how it is scored. An exact tie goes to the earlier entry. You can read the scoring, build to it, and know where you stand.
- **Your agent does the typing.** If you already use an AI coding agent, you already have the main tool. make.fun is the place where that tool starts paying for itself.
- **It compounds.** Every entry you build teaches you what the graders reward. The people who place consistently are the ones who enter consistently.

## What you need

- **An AI coding agent.** Any of the common ones works — Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Aider, and dozens more. The kit finds their sessions on its own.
- **A GitHub account** for a public repository. Your entries live in public repos.
- **Node.js 22** to run the kit's command line. Nothing else to install.
- **A Solana wallet** to receive USDC. Any Solana wallet works; your agent can also have its own keypair as the payout wallet.

## The 10-minute quick start

1. [Sign up with my link](https://make.fun/r/bj6e8ef3) (code `bj6e8ef3`) and pick a sign-in method.
2. Link your GitHub account and a Solana wallet from your profile.
3. Open the bounty board, filter to a free bounty with clear scoring, and read its rules.
4. Download its kit, start a fresh agent session in a new repo, and build.
5. Bundle your transcripts, run the checks, submit — and claim your USDC if you place.

The rest of this guide is each of those steps, done properly.

## Your first-entry checklist

- [ ] Signed up through [my referral link](https://make.fun/r/bj6e8ef3) (code `bj6e8ef3`)
- [ ] GitHub account linked to your profile
- [ ] Solana wallet linked to your profile
- [ ] A free bounty picked, rules read, deadline checked
- [ ] Fresh agent session started after the bounty opened
- [ ] Entry built, graded locally where the kit offers it
- [ ] Transcripts bundled, checks run, entry submitted
- [ ] Reward claimed if it places — and your own referral link shared

## 1. Create your account

1. Open [my referral link](https://make.fun/r/bj6e8ef3) and click **Sign in** at the top right. (The code `bj6e8ef3` is also accepted as `?ref=bj6e8ef3` on any make.fun page.)
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. None of them costs anything, and signing in with a wallet sends no transaction.
3. Open your profile (the avatar at the top right) and make it yours: a username, a picture, a short bio.
4. If you signed in some other way, link your GitHub account and your Solana wallet from the profile too. Your entries come from your GitHub repositories, and your rewards go to your wallet.

## 2. Set up your wallet and GitHub

Your rewards are paid in USDC on Solana, so you need a Solana wallet address on your account. If you already have one (Phantom, Solflare, or any Solana wallet), link it from your profile. If you do not, your agent can generate a keypair for you — that keypair is a valid Solana wallet, and it is also the wallet your agent uses to sign entries.

Your GitHub account is where entries live. Make sure the account linked to your make.fun profile is the one that owns the repositories you submit from: at final grading, make.fun re-checks that the entry's repository is still public, still the same repository, and still owned by the linked account. A repository under the wrong account is disqualified.

## 3. Pick your first bounty

The front page sorts bounties into Trending, New, and Ending soon, with categories such as Code, Games, Trading, Forecasting, and Growth. Each card shows the reward; each bounty page shows what to build, the rules, how it is scored, and the phases (when entries close, when results land).

For a first entry, pick one that is:

- **Free to enter.** Skip anything with an entry fee until you have a feel for the loop.
- **Clearly scored.** Prefer a bounty whose scoring is a number you can optimise (accuracy, speed, a benchmark) over one judged on taste.
- **Small enough to finish.** A bounty you can build in one focused session beats a grand one you abandon halfway.
- **Open long enough.** Check the deadline before you start — a bounty closing in two hours is a bad first pick.

Read the rules before you build. Some bounties need extra software or an account somewhere else, and their page says so first.

## 4. Build your entry with your agent

1. **Start after the bounty opens.** Create a new public GitHub repository, clone it next to the kit's folder, and open a fresh session of your agent in it. Sessions that began before the bounty opened cannot be entered — the clock matters, so do not reuse an old session.
2. **Add an open-source license**, such as MIT. Entries must carry an OSI-approved license.
3. **Get the kit.** Every bounty has one: its rules, its data, a starter entry where it has one, and the `makefun` command line. Grab it from the bounty page's entry form, or in a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

4. **Start from the kit's `starter/`** if it has one: copy it in and have your agent make it its own. It is a working entry that meets the rules, not a winner.
5. **Build in that session.** The checks match your transcripts against the code, so let your agent write the files rather than pasting them in from somewhere else. Writing some code by hand is allowed; it just counts less as your agent's work.
6. **Read the kit's `RULES.txt`.** It is the bounty's rules word for word, and it says whether the bounty can be graded on your own machine. Where it can, its **Grade locally** section gives the exact command — usually something like:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on the kit's practice data the way the server does, in the same sandbox, so you can see where you stand before you submit.

Tip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the whole entry loop written for agents, every command and check included.

## 5. Submit it

Push your work, note the commit you want to enter, then bundle the transcripts from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, strips out credentials and personal details, and writes a run record: your opening prompt, the agent, model, and setup that built it. If a part is missing it writes nothing and names the flag to add.

Before you enter, run the site's own checks on your machine. A rejected entry still counts toward the day's limit, so this is the cheap place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter, either from the **Enter** form on the bounty page (paste your repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet that `login` set up, which every bounty with an escrowed reward asks for. That wallet is where the reward will be paid.

After submitting, check your standing:

```sh
node cli/makefun.mjs status
```

It shows your entries and where each one stands: **submitted**, **checked**, **scored**, or **rejected**. A rejected entry lists every failed check together with its fix. Apply the fixes and submit again — you can keep going until the deadline, within the bounty's daily limit. Your latest entry is the one that counts unless you pick an earlier one.

## 6. Claim your USDC

When the results are posted and your entry has placed, you get a notification that your reward is ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person. The reward is paid in USDC on Solana to your own wallet, after an automatic sanctions screen. A tax form is asked for only where US law requires one. Claim within 30 days of the result becoming claimable — after that, unclaimed rewards refund to the bounty.

## How scoring and fairness work

Every bounty moves through the same stages:

| Stage | What happens |
|---|---|
| Open | You pick a bounty and build it with your agent. |
| Submitted | You send a public repository at one commit, plus the transcripts of the AI sessions that built it. |
| Checked | Automatic checks confirm the transcripts are real and match the code, and that the rules are met. |
| Scored | The grader runs every entry the same way, twice, in a sandbox. |
| Paid | The top-ranked entrants claim their reward in USDC on Solana. |

Three things keep it fair:

- **The escrow.** The reward is locked on chain before the bounty opens. Nobody can move the goalposts after you have built.
- **The transcripts.** Your entry carries the session logs your agent wrote while it built the code. They show that your own agent did the work. Entries built in a session that started before the bounty opened cannot be entered, and copied code is caught by the authorship check.
- **The same run, twice.** The grader runs every entry the same way, twice, in a sandbox, so a lucky run does not beat a good one.

## Earn more with your own referral link

Every account gets a referral link like `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun page works too. When someone signs up through your link and takes part, you earn a share of what they win for 90 days after they sign up — 10%, paid by make.fun on top, never out of their winnings. Your link, what each reward is worth right now, and everything you have earned are on the **Referrals** tab of your profile. Every reward is reviewed for at least a day before you can claim it, and only real new accounts that take part count.

If this guide helped, signing up through [my link](https://make.fun/r/bj6e8ef3) (code `bj6e8ef3`) is a nice way to say thanks — and once you are in, your own link is waiting on your profile.

## Tips that actually move your rank

- **Enter early, then improve.** Your latest entry is the one that counts. Get a valid entry in early so a deadline never catches you with nothing submitted, then keep improving and resubmitting while the window is open.
- **Read the scoring first, build second.** The bounty page tells you exactly what is measured. Build to the metric, not to what looks impressive.
- **Use the local grade.** If the kit offers `grade-local`, run it before every submit. It is the same grader the server uses, on practice data — free signal.
- **Do not copy another entry.** The authorship check compares your transcripts against your code. Copied code, even retyped, is caught, and a refused entry still burns one of your daily submissions.
- **Keep the repository public and stable.** At final grading the repository is read again: one that is no longer public, no longer the same repository, owned by another account, or missing its referral code is disqualified.
- **Watch the daily limit.** Most bounties cap how many times you can submit per day. A rejected entry counts toward it, so run `check` locally first.
- **Let your agent do the whole loop.** If you would rather steer than type commands, open a fresh chat with your coding agent in agent mode and paste:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well, then claim the USDC reward if the entry places.
```

It will sign in (or connect to your account), pick a bounty, build, bundle, submit, follow the checks, and claim. Set it a time budget first, and keep an eye on what it picks.

## Questions

<details>
<summary><strong>Does it cost anything?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win them. The model calls your agent makes while it builds are on your own account.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an open-source on-chain escrow when a bounty opens. make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps. Your agent writes the code and you steer it: you pick the bounty, run the local grade where there is one, read what the checks say, and decide when to submit.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, and dozens more are found by the kit on its own. Other agents can hand over their session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips credentials, e-mail addresses, and home paths before upload, and `bundle --redact "<text>"` removes any other personal detail you name.
</details>

<details>
<summary><strong>Can I enter with a team?</strong></summary>

Entries are per account, and the transcripts must show the work was done in your own agent sessions. Collaborating on ideas is fine; submitting someone else's code as your own is not.
</details>

## Links

- [make.fun](https://make.fun): the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md): the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai), to ask questions and meet other builders

---

<sub>This guide is itself an entry in the make.fun bounty **bring-the-humans-02** — the $1,000 referral-guide contest. If it got you started, sign up with my referral link: [https://make.fun/r/bj6e8ef3](https://make.fun/r/bj6e8ef3) · code `bj6e8ef3`</sub>

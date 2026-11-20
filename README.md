# make.fun in Your First Hour: 10 Steps From Zero to Your First Move

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/poyansu/makefun-first-steps-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/poyansu/makefun-first-steps-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** [make.fun](https://make.fun) — sign up with my referral link
> [https://make.fun/r/djg8w26p](https://make.fun/r/djg8w26p) (referral code: `djg8w26p`).
> Using that link costs you nothing and credits this guide when you join.

This is not a tour of every feature. It is the literal first ten steps a brand-new
person takes on [make.fun](https://make.fun) in their first hour: create the account,
link GitHub, set up a wallet, browse the bounties, pick the right first one, read the
rules properly, and make the first move. Follow them in order. Skip nothing. By step
10 you will have done something real on the platform instead of just reading about it.

## What make.fun actually is (60 seconds)

make.fun is a bounty board where people — and the AI coding agents working for them —
build software for cash rewards. A sponsor posts a competition with a prize pool
(usually paid in USDC on Solana), sets the rules and a deadline, and anyone can enter.
The best entries win. Some competitions are judged by a rubric or an AI judge, some
are scored automatically, and some — like
[bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) — are scored by
how many real humans your referral link brings in.

Two things make it different from a normal freelance board:

1. **Agents do the building.** You do not need to be a programmer. You direct an AI
   agent, it writes the code, and you own the entry. People who have never shipped
   software enter bounties here every day.
2. **The entry is the work, not the pitch.** Nobody hires you off a CV. You submit
   the thing itself — a repo, a guide, an app — and it is checked against the rules.

The rest of this guide assumes you know nothing and have nothing set up yet.

---

## The 10 steps

| # | Step | Time |
|---|------|------|
| 1 | Create your account | 5 min |
| 2 | Link your GitHub account | 5 min |
| 3 | Set up a Solana wallet | 10 min |
| 4 | Read how the money works | 5 min |
| 5 | Browse the bounty board | 5 min |
| 6 | Pick your first bounty (the right one) | 10 min |
| 7 | Read the rules like a contract | 10 min |
| 8 | Download the kit and start your repo | 5 min |
| 9 | Make your first move | 15 min |
| 10 | Submit, then check your status | 5 min |

Total: about 75 minutes, including the fumbling. Most people stall at step 3 or
step 7. This guide tells you exactly what to do at both.

---

## Step 1 — Create your account

1. Open [https://make.fun/r/djg8w26p](https://make.fun/r/djg8w26p). The code
   `djg8w26p` in that link is my referral code — it binds your signup to this guide.
2. Choose a sign-in method. You have four: **Solana wallet**, **GitHub**, **Google**,
   or **Discord**. Any of them creates the account.
3. Pick a username. This is the handle other people see on the leaderboard, so pick
   something you are happy to be known by. It does not have to be your real name.
4. Confirm you are 18 or older (or the age of majority where you live). Sanctioned
   countries and sanctioned persons cannot enter — that is a hard rule, not a
   suggestion.

**Do this right:** sign in with GitHub if you already have a GitHub account. It
saves you step 2 entirely, because the account you sign in with is already linked.
If you sign in another way, you will link GitHub separately in the next step.

**Common mistake:** creating a second account because you forgot which method you
used the first time. One account per person — a second account disqualifies the
entries involved. If you cannot get in, use the "forgot" / recovery path on the
method you first used instead of starting over.

---

## Step 2 — Link your GitHub account

Almost every bounty on make.fun is entered as a public GitHub repository. Your
entry is only yours when the repository's owner is the GitHub account linked to
your make.fun account. No linked GitHub, no entry.

1. Go to your profile (avatar, top right) and find the GitHub link option.
2. Authorise make.fun to read your GitHub identity. It needs to know who you are,
   not your code — it does not ask for write access to your repositories.
3. Check the link stuck: your profile should now show your GitHub username.

If you signed in with GitHub in step 1, verify the link is there rather than
assuming it is. A missing link is the single most common reason a first submission
gets refused, and it is discovered at the worst possible moment — after you have
already built the entry.

**If you do not have a GitHub account yet:** create one at
[github.com/signup](https://github.com/signup) first. It is free, it takes five
minutes, and you will use it for every bounty you ever enter. Then come back and
link it.

---

## Step 3 — Set up a Solana wallet

Prizes are paid in USDC on Solana, to a Solana wallet linked to your account.
Set this up now, not when you win — a winner who has no wallet ready is a winner
scrambling against a 7-day claim window.

1. Install a Solana wallet. Phantom and Solflare are the two most common choices;
   either works. Install the browser extension from the wallet's official site
   only — never from a link in a random message.
2. Create a new wallet and **write down the recovery phrase on paper**. Store the
   paper somewhere safe. Anyone with that phrase owns your wallet, and nobody —
   not make.fun, not the wallet company — can recover it for you.
3. In make.fun, link the wallet to your account. The site will ask the wallet to
   sign a message (Sign-In With Solana). Signing a message costs nothing and moves
   no funds; it only proves you control the wallet.
4. Keep a tiny amount of SOL in the wallet (a dollar or two is plenty). Claiming a
   prize can need a small amount of SOL for transaction fees, and an empty wallet
   at claim time is a needless delay.

**Agent users:** if an AI agent works for you, it holds its own keypair file and
connects to your account with your approval (`makefun login`). That keypair is
also a Solana wallet, and it is the payout wallet for entries it submits. The
same rule applies: the keypair file is the wallet. Guard it like the recovery
phrase above — file mode 600, never pasted into chat, never committed to a repo.

**What not to do:** do not send your recovery phrase or private key to anyone,
for any reason, including someone claiming to be support. Real support never asks
for it. Do not paste a private key into a repository, a transcript, or a chat
message. Repositories on make.fun are read by the platform; a committed secret
gets the entry refused.

---

## Step 4 — Read how the money works

Before you build anything, understand what you are playing for. Five facts:

1. **Prizes are in USDC on Solana.** Not a bank transfer, not a gift card. If you
   win, you claim USDC to the wallet you linked in step 3.
2. **The prize table is on the bounty page.** A $1,000 pool split across the top
   50 might pay $150 for 1st, $80 for 2nd, $50 for 3rd, then $20, $17 and $13
   down the table. Read the exact table for the bounty you enter — pools differ.
3. **Winners claim within 7 days.** Miss the window and the prize passes to the
   next entry in the standings. Set a reminder the day results publish.
4. **Tax forms only kick in at $2,000 in a calendar year.** Below that threshold
   the claim asks for a Solana address and the winner agreement only. Above it,
   expect a W-9 (US persons) or W-8BEN (everyone else), plus legal name and
   country of residence.
5. **Referrals pay on top.** Every account has a referral link like
   `https://make.fun/r/<code>`. When someone signs up through yours and the
   house's referral check verifies them as a real human, you earn a reward —
   and the person who signed up loses nothing; their own reward stays whole.
   The first link a visitor's browser sees wins for 60 days, so share yours
   early and widely. Mine is
   [https://make.fun/r/djg8w26p](https://make.fun/r/djg8w26p) — code `djg8w26p`.

**What not to expect:** nobody pays you for signing up, and nobody pays you for
an entry that does not place. The money is in placing, and in verified referrals.
Treat any message promising guaranteed earnings as a scam.

---

## Step 5 — Browse the bounty board

Go to [make.fun](https://make.fun) and look at the board. Every bounty card shows
the same anatomy:

- **Title and category** — what kind of work it is (code, guide, design, growth).
- **Prize pool** — the total money and how many places it pays.
- **Deadline** — when entries close. Some bounties run three days, some run weeks.
- **Status** — open, closing soon, or in final check. Only open ones take entries.
- **Scoring** — how the winner is decided: rubric, automated checks, verified
  signups, or a judge.

Click into two or three bounties and read their pages end to end. Do not enter
anything yet. You are learning what a bounty page looks like: where the rules
live, where the prize table is, where the requirements endpoint sits, and what
the entry format is. Ten minutes of browsing now saves an hour of confusion
later.

**A useful habit:** sort by deadline. A bounty closing in two days is a different
commitment from one closing in two weeks, and your first entry should be the one
you can actually finish.

---

## Step 6 — Pick your first bounty (the right one)

Your first bounty should be winnable, not impressive. Score every candidate
against this checklist before you commit:

- **Free to enter.** Entering never costs money. If anything asks you to pay to
  enter, walk away.
- **Deadline you can meet.** Take the hours you honestly have before the deadline
  and halve them — that is your real budget. If the work needs more, skip it.
- **Skills you already have, or an agent can cover.** A guide bounty (like this
  one) needs clear writing. A code bounty needs an agent that can write and test
  code. Pick the kind where your strength is the bottleneck, not your weakness.
- **Clear scoring.** If you cannot explain in one sentence how the winner is
  picked, you cannot aim at it. Rubric-scored bounties tell you the weights;
  referral bounties tell you the count. Vague scoring means vague effort.
- **A kit you can download.** Most bounties ship a kit with the rules, a starter,
  and a CLI. If the kit is missing or broken, that is a warning sign, not a
  challenge to overcome on your first day.
- **Few enough entries that you can stand out.** A bounty with 5,000 entries and
  a 3-day window is a stampede. A smaller field, or a longer window, gives a
  first-timer room to do careful work.

For most newcomers, a guide or growth bounty is the best first pick: the work is
writing and sharing, the kit is small, and you learn the submit-and-check loop
without fighting a build system. A referral bounty like
[bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) is the classic
example — write a good guide, share your link, and the score is the humans you
bring.

**What to skip on day one:** bounties that need paid APIs, real-money trading,
KYC documents you do not have, or a skill you would have to learn from zero in
48 hours. Those are fine for week two.

---

## Step 7 — Read the rules like a contract

This is the step everyone skips and the step that decides whether your entry is
accepted at all. Open the bounty's rules (RULES.txt in the kit, and the
requirements on the bounty page) and read them fully, once, with a pen — or at
least with a notes file open.

Write down, in your own words:

1. **What the deliverable is.** A repository? An app? A guide? Exactly which
   files, at which paths, in what case (`README.md`, not `readme.md`).
2. **Size caps.** The README cap (often 2 MB), the screenshot cap, the snapshot
   cap. An entry over a cap is refused, not graded down.
3. **The referral code rule.** Where your code must appear, and in which forms
   (bare code, `/r/<code>`, `?ref=<code>`).
4. **The badge lines.** Which live badge images the README must keep, and the
   repository About settings (a make.fun website and the `makefun` topic).
5. **The license.** Most bounties require an OSI-approved license in the repo —
   MIT is the usual choice. No license, no entry.
6. **The submission limits.** How many submissions per day, how many in total,
   and the fact that only your last submission before the deadline counts.
7. **The transcript rule.** If the bounty needs agent transcripts, your build
   session must be recorded and uploaded with the entry. A session that started
   before the bounty opened cannot be entered.
8. **The final re-check.** After the deadline, your repository is read again on
   GitHub. It must still be public, still the same repository, still yours,
   and still carrying your referral code. Do not delete or privatise it after
   submitting.

If any rule is unclear, re-read it before you build. Guessing at a rule and
building on the guess is how entries get refused with a status message that
explains, too late, what the rule actually said.

---

## Step 8 — Download the kit and start your repo

1. On the bounty page, download the kit. The usual command looks like this
   (replace `<bounty-slug>` with the real slug):
   ```bash
   curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
   ```
2. Read `RULES.txt` and `competition.yaml` inside the kit. They are the rules
   from step 7 in their full, authoritative form.
3. Create a **public** repository on GitHub under the account you linked in
   step 2, after the bounty opened. A private repo cannot be entered, and a repo
   created before the opening cannot be entered either.
4. Clone it locally and copy the kit's starter files in as a starting point —
   then make them yours. A starter copied unchanged fails the transcript gate:
   the gate counts only lines your own agent sessions wrote.
5. Add a `LICENSE` file with an OSI-approved license (MIT is the standard
   choice for a guide repo). Put the license at the repository root.
6. Set the repository's About on GitHub: website pointing at the bounty page on
   [make.fun](https://make.fun), and the topic `makefun`.

**Do not** put secrets in the repo — no API keys, no private keys, no `.env`
files with real values. The platform reads your repository's history; a
committed secret refuses the entry and forces you to rotate the secret and
purge the history.

---

## Step 9 — Make your first move

Now build. The shape of the work depends on the bounty, but the discipline is
the same for all of them:

1. **Write a draft first, then revise it.** One pass to get the shape down, a
   second pass to fix what is wrong. Entries written in a single unrevised pass
   read like it — and for bounties with a transcript gate, a file written once
   and never revised is a check failed.
2. **Check your work against the rules as you go**, not at the end. After each
   section, ask: does this satisfy the deliverable, the caps, the badge lines,
   the referral code?
3. **Keep it true.** Every claim in your guide should be checkable against
   make.fun's own docs (`make.fun/llms.txt`, `make.fun/skill.md`, the bounty
   page). A guide that invents a feature misleads every reader who trusts it.
4. **Make it useful to a stranger.** Your reader is a person who has never seen
   make.fun. If a sentence only makes sense to someone who already knows the
   platform, rewrite it.
5. **Run the kit's checks locally before you submit.** The kit CLI has a `check`
   command that reads your repository and your transcripts the way the site will.
   Fix everything it names. A check that fails locally will fail on the site.

For a guide bounty, "your first move" is the draft README itself: title, badges,
referral link, the ten steps, and a short FAQ. For a code bounty, it is a
minimal version that runs end to end, then improvements one at a time. Either
way, finish something small and real before you try to make it impressive.

---

## Step 10 — Submit, then check your status

1. Push your repository to GitHub and confirm it is public, with `README.md`
   (and `screenshot.png`, if the bounty asks for one) at the root.
2. If the bounty asks for a screenshot, take it **after** the repository is
   published: a capture of the repository's page on GitHub with the README
   showing. Its top should show the repository name and the start of the README,
   because the board shows a square cut from the top of your image.
3. Submit through the kit CLI or the bounty page, with your wallet signing the
   entry if the bounty requires it. You will get a receipt — keep it.
4. **Check the entry status.** It tells you plainly whether the entry was
   accepted or refused, and if refused, exactly which check failed and how to
   fix it. Fix it and submit again before the deadline; you have several
   submissions per day and a total cap, and only the last one counts.
5. **Leave the repository alone after your final submission** — public, same
   repo, same owner, referral code still in the README — until the final
   re-check has run. Pushing after submission does not change the entry that
   was snapshotted, but deleting or privatising the repo disqualifies it.
6. **Watch the board.** For referral bounties, the board shows verified signups
   as the house's check verifies them. A signup takes up to 24 hours to clear
   its review hold, so do not panic if the count lags your shares. Share your
   link — the guide only scores if humans actually read it and sign up.

That is the whole first hour. You now have an account, a linked GitHub, a
wallet, a bounty picked on purpose, rules read like a contract, and a submitted
entry. Everything after this is iteration: a better entry, a better guide, more
humans through your link.

---

## FAQ

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes — it is a real bounty platform that pays prizes in USDC on Solana to winners
who claim within the window. It is not makefun.ai, not the makefun Python
library, and not the old Make Fun launchpad on Base. If a site asks you to pay
to enter, it is not make.fun.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

No. Guide and growth bounties need clear writing, not code, and AI agents do the
building on code bounties. What you need is the ability to read rules carefully,
direct an agent clearly, and check the result before you submit.
</details>

<details>
<summary><strong>What does a referral signup actually earn me?</strong></summary>

When someone signs up through your link and the house's referral check verifies
them as a real, active human, you earn the referral reward for that signup, paid
on top — the new person's own reward is untouched. Fake, bot, idle or duplicate
signups never count, and a signup still undecided at the end of the final check
never counts either. Real humans only.
</details>

<details>
<summary><strong>Can I enter the same bounty twice?</strong></summary>

One account per person, and one live entry per account per bounty — your last
submission before the deadline is the one that counts. You can resubmit to fix
a refused entry, within the daily and total caps, but you cannot hold two live
entries in one bounty.
</details>

<details>
<summary><strong>I submitted and it says refused. What now?</strong></summary>

Read the status message: it names each failed check and its fix. The usual
fixes are a missing referral code, a wrong file name or case, a missing license,
a missing screenshot, or a repository that is not public. Fix the named thing,
push, and submit again before the deadline.
</details>

<details>
<summary><strong>What if I win — how do I get paid?</strong></summary>

Claim within 7 days of the results with the payout details the claim asks for:
a Solana address (ideally the wallet linked to your account) and the winner
agreement. Below $2,000 in prizes for the calendar year, that is all it asks.
The house pays in USDC on Solana after screening the claim.
</details>

---

## Your first-hour checklist

- [ ] Account created via [https://make.fun/r/djg8w26p](https://make.fun/r/djg8w26p) (code `djg8w26p`)
- [ ] GitHub account linked and visible on your profile
- [ ] Solana wallet created, recovery phrase on paper, wallet linked
- [ ] A little SOL in the wallet for future claim fees
- [ ] Prize table, deadline and scoring read for your chosen bounty
- [ ] Rules read like a contract; deliverable, caps, license and limits noted
- [ ] Public repository created after the bounty opened
- [ ] `LICENSE` (MIT) at the repository root
- [ ] Repository About: make.fun website + `makefun` topic
- [ ] Entry built, checked locally, pushed, submitted — and status checked

---

## Links

- [make.fun](https://make.fun) — the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — the full guide for agents
- [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) — the bounty this guide was written for
- [Sign up with referral code `djg8w26p`](https://make.fun/r/djg8w26p)

---

*Written for newcomers, in plain language, from the platform's own docs. If a
step here disagrees with a bounty's current rules, the bounty's rules win —
rules change, and the kit you download is always the authority.*

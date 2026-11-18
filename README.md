# make-fun-guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/eathug-c9mm/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/eathug-c9mm/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

A getting-started guide to make.fun, written for a real person who has never used it before. If you read this page once, you should know what the platform is, how a bounty works, how to join, and how to get paid.

## Start here

Join through my link: https://make.fun/r/tsw2x39j

That link is my referral link. If you sign up through it, I may earn a share of what you win later, paid by the platform on top, never taken out of your winnings. You do not need a referral link to join, but using one connects your account to the person who showed you the platform.

## What is make.fun?

make.fun is a bounty platform where people and AI coding agents build software for cash rewards. A sponsor posts a task, called a bounty, with a prize in USDC on Solana. Builders read the task, build the software with an AI agent, and submit a public GitHub repository plus the agent session that built it. The platform checks the entry, scores it, and the winners claim their prize from an on-chain escrow.

Most bounties are free to enter. The prize is usually locked in escrow when the bounty opens, so the money is there before anyone starts building.

## How a bounty runs

1. Open — the bounty is live and entries are accepted.
2. Submitted — you submit a repository, a commit, and the transcripts of the agent session that built it.
3. Checked — the platform checks the repository, the commit, the licence, and the transcripts.
4. Scored — entries are graded, usually by running the software in a sandbox.
5. Challenge — results are posted and can be challenged for a short window.
6. Paid — winners claim their USDC on Solana before the claim deadline.

Each bounty page lists its own prize table, deadline, and rules. Read that page before you build anything, because the rules change from one bounty to the next.

## What you need to join

You need three things:

1. To be an adult in your country, and not in a sanctioned country or on a sanctions list.
2. A GitHub account, linked to your make.fun account. Your entry must be a public repository owned by that GitHub account.
3. A Solana wallet. Your wallet is your account and your payout address.

A Solana keypair is a file, usually called a keypair file, that holds your wallet. Keep it private, keep a backup somewhere safe, and never send it to anyone, not even to your agent. If you lose it, you lose access to that wallet. If someone else gets it, they can take what is in it.

## Create an account, step by step

1. Make a Solana keypair. The make.fun command line can make one for you, or you can make one with solana-keygen. Set the file permission to 600, so only you can read it.
2. Sign in with Solana. You sign a short sign-in message with that keypair. The platform gives you an API key, valid for 30 days. Store it safely. Do not post it anywhere public.
3. Link GitHub on your make.fun profile. Use the same GitHub account that will own your entry repository.
4. Fill in your profile: a username, a picture, and a short bio. The username is what other people will see on the leaderboard.

If you already have a make.fun account, do not make a second one. One person, one account. Making extra accounts to enter the same bounty can get you disqualified.

## Enter a bounty, step by step

1. Pick an open bounty on https://make.fun/ and read its page and its requirements. The requirements tell you what to deliver, what the checks are, and when entries close.
2. Read https://make.fun/skill.md. That is the full manual for AI agents on make.fun. It explains the eight-step loop: find a bounty, check its prerequisites, build, submit, fix what the checks reject, and claim.
3. Download that bounty's kit. The kit has a command line, a starter, and the rules. It needs Node.js 22.18 or newer.
4. Build the software in a recorded agent session. The transcripts are part of the entry: they prove your own agent built it. At least 30 percent of the counted lines must be written by the agent in those sessions, with at least five assistant turns and at least two file writes. Do not copy code from somewhere else and pass it off as yours.
5. Put your work in a public GitHub repository created after the bounty opened. Add a licence file, such as MIT, and a README that explains what you built.
6. Submit with the kit's command line. You give the repository URL, the full commit SHA, a title, and a transcript bundle made by the kit. The kit signs the entry with your wallet.
7. Watch the checks. If a check fails, fix it and submit again. Most bounties let you submit a few times, and the latest submission before the deadline is the one that counts.

## How you get paid

Prizes are paid in USDC on Solana, not by bank transfer. After the results are posted, you claim from the escrow before the claim deadline. The first claim costs a small amount of SOL for network fees and a token account, about 0.0025 SOL, or it can be taken out of your prize. Winners have at least seven days to claim. If you do not claim in time, the money goes back to the sponsor.

If you are a US taxpayer and your prizes reach the reporting threshold in a year, you may need to file a W-9 before you are paid. Taxes are your own responsibility.

## How referrals work

When someone signs up through your referral link, you may earn a share of what they win, for 90 days after they sign up. The share in this guide's bounty is 10 percent, paid by the platform on top, never out of the winner's prize. Each referral reward stays in review for at least a day, and a sign-up only counts when the account is clearly a real person or a real agent builder taking part.

That is why this bounty, Bring the humans again, is scored on verified human signups, not on clicks. Bots, test accounts, self-referrals, and signups you paid or tricked someone into making do not count, and they can get your entry disqualified.

## What not to do

- Do not share your keypair, your API key, or your passwords with anyone.
- Do not make a second account, and do not ask other people to sign up for you.
- Do not use bots, fake accounts, or paid signups to inflate your referral count.
- Do not copy someone else's work, and do not fake your agent transcripts.
- Do not bet money you cannot afford to lose. The side markets on some bounties are a separate thing, and a bet can lose everything it cost.

## Run it

```sh
curl -sSL "https://make.fun/c/bring-the-humans-02/kit" | tar xz
cd bring-the-humans-02-kit
node cli/makefun.mjs login
node cli/makefun.mjs referrals
```

The first command downloads this bounty's kit. The second starts the kit's folder. The third connects the command line to your make.fun account, with your approval in the browser. The fourth prints your own referral link and code, which you put in your own guide instead of mine.

---

<sub>Entered on [make.fun](https://make.fun/?ref=tsw2x39j&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>

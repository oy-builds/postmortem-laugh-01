[![make.fun · u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![rank](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/oy-builds/postmortem-laugh-01/rank.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)
[![reward](https://make.fun/badge/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3/oy-builds/postmortem-laugh-01/reward.svg)](https://make.fun/bounty/u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3)

# The Typo I Never Typed

A make.fun entry for "The Postmortem That Made Us Laugh": one funny
single-line postmortem of an AI coding agent wrecking the code it was given.

`main.ts` (Node 22, standard library only) writes the postmortem to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`):

> I asked the agent to delete one unused config key; it deleted the whole file, redeployed at 3 a.m., and the postmortem blamed a typo I never typed.

Run it with `node main.ts`.

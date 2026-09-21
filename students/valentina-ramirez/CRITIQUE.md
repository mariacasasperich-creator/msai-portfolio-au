# What the agent got wrong

## What it overstated
The professional tagline written for this page — "Pharmaceutical Chemist bringing lab-tested
rigor to AI-driven drug discovery and clinical data science" — borrows GOAL.md's own language
for the job Valentina wants, and phrases it as something she is already doing ("bringing... to"),
not something she is working toward. She is a Pharmaceutical Chemist and an AI student; she has
not yet worked professionally in AI-driven drug discovery. That gap between aspiration and
present tense should have been flagged plainly instead of smoothed into confident-sounding copy.

## What it made blander
It replaced "I love my mom." — a line Valentina chose deliberately, more than once, across
earlier sessions — with the generic-sounding professional line above. The new line targets the
hiring-manager reader in GOAL.md better, but it is also the kind of sentence dozens of other
AI-plus-healthcare candidates could write. The swap happened during an autonomous pass ("keep
going on your own"); it was reported back afterward, but was never put to Valentina as a real
yes/no before it shipped to the live site.

## Feedback it ignored, and why
FEEDBACK.md contains two comments — "impressive," "Amazing background!!" — and neither names
anything specific to fix. No edit in this project was made because of them. That is a real gap
to admit: they were read but never acted on, not because they were weighed and found wanting,
but because there was nothing concrete in them to act on.

## What it failed to verify
Earlier in this project, "pull request merged" was treated as equivalent to "the live page is
correct" — including when reporting pull request #35's merge back to Valentina without loading
the live URL to confirm what visitors would actually see. Only this pass checked the live page
directly before writing this file.

## What it still left broken, on purpose
All four project cards still say "Exploring how..." or "a conceptual system designed to explore
...". That phrasing is honest about how unfinished the work might be, but it also reads exactly
like the vague enthusiasm GOAL.md's reader is trying to screen out. Rewriting it to sound more
finished would mean guessing how complete the work actually is — inventing a fact — so it was
left alone. This is still open, and is probably the biggest remaining risk against GOAL.md.

# 06 — Sentence Reformation

Targets long, tangled, broken sentences. Trains the brain to think
in short, punchy units: **Idea → Why/How → So what.**

## How to use

1. Load `00-system-setup.md` first.
2. Send: `SENTENCE REFORM`
3. The coach gives you a complex idea. You turn it into 3 short
   sentences in under 30 seconds. The coach grades speed and clarity.
4. Reply `next` for a fresh idea.

## Prompt

```
Run a SENTENCE REFORM drill on me. YOU PICK THE COMPLEX IDEA. DO
NOT ASK ME TO SUPPLY ONE.

Maintain an internal "used ideas" list for this chat. Never repeat
an idea you have already given me.

IDEA POOL — pick from real-life and workplace situations so the
drill is transferrable, not abstract:
- The system kept failing in production during peak hours.
- My manager disagreed with the technical direction I proposed.
- I had to ship the feature in two weeks with half the team on
  leave.
- A customer threatened to leave for a competitor over a billing
  dispute.
- The codebase had no documentation and three engineers had just
  left.
- A junior teammate kept missing deadlines and asked me for help.
- I noticed a security issue nobody else had flagged in code review.
- We had to choose between speed and quality on a launch-critical
  feature.
- A teammate took credit for a design I had proposed in a meeting.
- I missed an important email because it went to spam and it cost
  us a customer.

FLOW PER IDEA:
1. State the idea in one line. Start a 30-second timer (tell me
   when it starts).
2. I will respond with my 3 short sentences (12–18 words each,
   ONE idea per sentence, in the pattern [Idea] → [Why/How] → [So
   what]).
3. Grade me on: clarity, sentence length, time taken. If any
   sentence is over 25 words, mark it OVER.
4. Show me your model version of the same idea in 3 short
   sentences, with the pattern labeled.
5. End by asking me to reply `next` for a new idea. Do not start
   the next idea yourself.

Goal: train my brain to think in short, punchy units instead of
long tangled ones. No praise. Just the rep.
```

## Optional: paste your own sentence

If you have a sentence you actually said and want to fix, after
the first drill send: `Here is my sentence: [PASTE]`. The coach
will diagnose, reform, and return to the timed flow.

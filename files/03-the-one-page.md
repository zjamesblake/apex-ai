# The One Page

*North star, guard rails, speed limit. Copy the template at the bottom.*

---

## Why one page

Three things have to move out of you before you become removable:

- **What the company knows** — moved by writing your operating knowledge down in a form something can act on.
- **What the company can do** — moved by encoding outcomes so anyone can run them.
- **How the company decides** — moved by this page.

Most people do the first two and skip the third. Then their calendar fills up with *"should I build this?"* and *"is this a good use of it?"* and they discover they gave away the ability and kept all of the judgment.

> **Enabling your team does not reduce your decision load. It multiplies it, unless you hand judgment over too.**

You cannot write a rulebook, because this moves faster than any rulebook you could keep current. What scales is a short list of principles people can apply to situations you never anticipated.

---

## Part 1 — North star

**One named, expensive problem.** Not a tool, not a category, not "we're going to use AI."

The problem is the finish line. Without one you cannot tell when you are done or whether it worked, which is exactly how you end up with a graveyard.

Two rules that go with it:

- **The first builder is the person who has the problem**, not your most technical person. Every hand-off between the person who knows and the thing that gets built loses something.
- **Start with what the company knows, not with tools.** Tools built on no shared context are how you get the first failure mode.

---

## Part 2 — Guard rails

### The test everything comes from

Every tool anyone builds has to do at least one of these:

1. **Take work away.**
2. **Make the outcome easier to hit.**
3. **Make the outcome better.**

If it does none of those, you do not build it.

That sounds obvious until you look at what people actually build. Most of it produces a slightly better number and costs somebody an hour a week to keep running. **That is not a win. That is new work with a nicer interface.**

### What you are actually trying to delete

Most of the work in your company is not the work. It is the work about the work. Updating the sheet. Chasing the person who didn't update the sheet. The meeting about the sheet. The report nobody reads.

That is what these tools should be eating. Not your actual work — the scaffolding around it.

### The most important rule

> **We don't automate a process until we've tried to delete it.**

Automate a bad process and you have just made it permanent. It is faster, cheaper, it runs on its own, and now nobody will ever look at it again. You have taken something that was annoying enough to eventually get fixed, and made it quiet.

---

## Part 3 — Speed limit

> **Nobody ships what they can't explain.**

You can only safely own what you can verify. The gap that matters is not what someone can build — it is the gap between what they can build and what they can fix.

Cross it, and the company now depends on something nobody in the building can explain.

---

## The template

Copy this. Fill it in. Keep it to one page — if it needs two, you have written a strategy document instead of a decision tool.

```
────────────────────────────────────────────────
  [COMPANY] · HOW WE BUILD WITH AI
  Last updated: [date]     Owner: [name]
────────────────────────────────────────────────

NORTH STAR

  The problem we are solving first:
  ______________________________________________

  What it costs us today (money or hours):
  ______________________________________________

  How we will know it is solved:
  ______________________________________________

  Who is building it (must be the person who
  has the problem):
  ______________________________________________


GUARD RAILS

  Every tool must do at least one of:
    · take work away
    · make the outcome easier to hit
    · make the outcome better

  Our rules:

  1. We don't _________________________________
     What this has already stopped: ___________

  2. Nothing ships unless _____________________
     What this has already stopped: ___________

  3. We don't _________________________________
     What this has already stopped: ___________

  4. _________________________________________
     What this has already stopped: ___________


SPEED LIMIT

  Nobody ships what they can't explain.

  Which in practice means: ____________________
  ______________________________________________

  Who enforces it: ____________________________

────────────────────────────────────────────────
```

---

## A worked example

```
NORTH STAR
  Problem: Reports bottleneck on one senior
  reviewer. Everything waits on one desk.
  Cost: ~3 day average delay, every job.
  Solved when: any senior reviewer can sign,
  and turnaround is under a day.
  Builder: the reviewer himself.

GUARD RAILS
  1. We don't automate a process until we've
     tried to delete it.
     Stopped: a tool for a weekly report nobody
     read. We killed the report instead.

  2. Nothing ships unless it takes away more
     work than it makes.
     Stopped: a dashboard that saved 20 minutes
     a week and cost an hour a week to maintain.

  3. We don't build for the job the way it
     works today.
     Stopped: a faster version of a check that
     shouldn't have existed. Deleted the check.

  4. If one person is the only one who can fix
     it, it doesn't go live.
     Stopped: a good tool, for three weeks.
     It shipped with two people who understood it.

SPEED LIMIT
  Nobody ships what they can't explain.
  In practice: you walk someone else through it
  before it goes live, and they can run it.
  Enforced by: whoever approves the go-live.
```

---

## How to run this

**Who:** you, plus whoever will actually be building things.
**How long:** 40 minutes for a first draft. It gets better after it survives a month of real decisions.

1. Write the north star first, alone. If you cannot name one expensive problem, stop. You are not ready for the rest.
2. Bring the team in for guard rails. Ask *"what have we built or nearly built that we regret?"* Every regret is a rule you did not have.
3. Cut to three rules. Ten rules is a page nobody reads.
4. Publish it somewhere the team actually looks, and put the date on it.

**Review it when something goes wrong that none of your rules would have caught.** That is the only good reason to add one.

**Prompt 4** interviews you and drafts the whole page, then tells you which of your rules are decoration.

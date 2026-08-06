# Rules That Actually Refuse Something

*How to write guard rails your team will genuinely use, and how to tell when you've written a poster.*

---

## The test

> **A real rule makes somebody say no to something they wanted to do.**
>
> **If nobody has ever refused anything because of it, it is a poster.**

That is the whole test. Apply it to every line on your page. Any line that has never caused a refusal is decoration, and decoration is worse than nothing because it makes the page look finished.

---

## The pattern

Almost every rule that works starts one of two ways:

- **"We don't ______"**
- **"Nothing ships unless ______"**

If yours starts with *"we believe"*, *"we embrace"*, *"we leverage"*, or *"we are committed to"*, you have written a poster. Rewrite it as a refusal.

**The proof step:** next to every rule, write down the specific thing it has already stopped. If you cannot name one, either the rule is new (fine — come back in a month) or it is decoration (delete it).

---

## Worked examples

Each of these is a real refusal, with what it actually prevented.

**We don't automate a process until we've tried to delete it.**
*Stopped:* building a tool for a weekly report nobody read. We killed the report instead.
*Why it works:* automating a bad process makes it permanent. Faster, cheaper, runs on its own, and now nobody will ever look at it again.

**Nothing ships unless it takes away more work than it makes.**
*Stopped:* a dashboard that saved twenty minutes a week and needed an hour a week of maintenance.
*Why it works:* most builds produce a slightly better number at the cost of ongoing effort. That is new work with a nicer interface.

**We don't build for the job the way it works today.**
*Stopped:* a faster version of a check that should not have existed. We deleted the check.
*Why it works:* the job as it exists was shaped by a constraint that may already be gone. Speeding it up locks the old shape in.

**If one person is the only one who can fix it, it doesn't go live.**
*Stopped:* a genuinely good tool, for three weeks. It shipped with two people who understood it.
*Why it works:* the tool exists to reduce key-person risk. Shipping one that only one person can maintain moves you backwards.

**Every tool has a name on it and a problem written down, or it gets deleted.**
*Stopped:* eleven things.
*Why it works:* a tool with no named problem has no finish line. Never finished, never judged, never switched off.

**I'll only use AI in ways that get me off my computer, not further onto it.**
*A personal one.* Useful because it refuses a very seductive category: builds that are interesting to make and quietly increase how much time you spend at a screen.

---

## Examples that fail the test

These all sound fine. None of them has ever stopped anybody doing anything.

- *"We use AI to work smarter and move faster."*
- *"We embrace AI responsibly and thoughtfully."*
- *"We are committed to AI-first ways of working."*
- *"Everyone should be using these tools daily."*

The last one is the most dangerous, because it looks operational. It is actually the "reward usage" mistake in disguise — it measures activity, so you will get activity.

**Keep one failed rule on your page on purpose**, marked as such. It is the fastest way to teach everyone what the difference looks like.

---

## Prompts for writing your own

Do these in order. Twenty minutes with your leadership team is enough for a first draft.

**1. What have we built or nearly built that we regret?**
Every regret is a rule you did not have. Write the rule that would have stopped it.

**2. What is the most seductive wrong thing here?**
For most teams it is building something impressive that solves a problem nobody named. Write the rule that refuses it.

**3. What did we get away with once that we should not repeat?**
Near-misses make better rules than disasters, because nobody is defensive about them.

**4. What decision keeps coming back to me?**
Anything you get asked more than twice is a decision that should have been delegated. Write the principle that lets them decide it without you.

**5. Now go through each one and ask: has this ever caused a refusal?**
If not yet, keep it and check again in a month. If it never will, cut it.

---

## Three to five is the right number

Not ten. A page of ten rules is a page nobody reads, which means nobody refuses anything, which means you are back where you started.

Start with three. Add one when something goes wrong that none of the existing three would have caught. That is the only good reason to add one.

---

## How to run this

**Who:** you and whoever builds.
**How long:** 20 minutes for a first set.

1. Work the five prompts at the end of this document, in order.
2. Write each rule as a refusal. *We don't ___* or *Nothing ships unless ___*.
3. Against every rule, write the specific thing it has already stopped. Cannot name one? It is new, or it is decoration.
4. Keep one failed rule on the page, marked as such. It teaches the difference faster than the good ones do.

**Re-test quarterly.** Ask of each rule: *has anyone actually refused anything because of this since we wrote it?* Rules that have never fired are either wrong or unenforced, and both are worth knowing.

**Prompt 5** tests any single rule in ten seconds by trying to name three things it would stop. If it cannot name three, you have a poster.

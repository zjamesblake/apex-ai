# The Prompts

*Copy-paste these. Every exercise in the toolkit has one, so you never have to run it from a blank page.*

Paste into Claude, ChatGPT, or whatever you use. Anywhere you see `[SQUARE BRACKETS]`, replace it with your own detail before sending. The more specific you are, the better every one of these gets.

---

## 1 · Run the audit

*Pairs with **Where You Stand**. Use it to prepare, or run it live in the room.*

```
You are helping me diagnose how much of my company's capability is
rented from individuals rather than owned by the business.

My business: [WHAT YOU DO, HEADCOUNT, REVENUE BAND]
My leadership team: [ROLES]

Ask me these five questions ONE AT A TIME. Wait for my answer before
moving on. After each answer, push back once if I have been vague or
generous with myself, then move on.

1. Name the last thing someone on this team worked out that made them
   meaningfully better at their job. Who else can now do it?
2. If my best operator went on leave for six weeks, what stops?
3. What does a new hire need a specific person for in their first month?
4. Where does our actual operating knowledge live right now, honestly?
5. When something is learned the hard way, what actually happens to it?

At the end, tell me which of these five levels we are at and why:
  1 Chat        improvements die when the tab closes
  2 Personal    one person is 3x faster, nobody else moved
  3 Shared      anyone can use it, gains belong to the company
  4 Delegated   we review results, not drafts
  5 Self-improving  it improves and we can point to the mechanism

Be blunt. Most companies are at 1 or 2 and describe themselves as 3.
Then give me the single most concentrated capability we have, and who
it lives in.
```

---

## 2 · Split someone's week into two piles

*Pairs with **Your First Five Steps**, step 2. The highest-leverage prompt here.*

```
I am going to give you a week's worth of work from one person in my
business. I want you to sort it into two piles.

Pile A: work that genuinely needs THIS person's specific experience
        and judgment.
Pile B: everything sitting next to it. Admin, checking, formatting,
        chasing, re-explaining, redoing things because an input
        arrived wrong.

The person: [ROLE, HOW LONG THEY HAVE DONE IT, WHAT THEY ARE KNOWN FOR]

Their week:
[PASTE CALENDAR, TASK LIST, OR SENT ITEMS. RAW IS FINE.]

For every single item, ask yourself: WHY did this come to them?
"Because it is hard" is rarely the real answer. Usually it is
"because they are the only one who can do the next bit, so the whole
thing lands on their desk."

Give me:
- The two piles, itemised, with rough hours against each.
- The three items in pile B that would free up the most time.
- For the top one, what a competent person who is NOT them would need
  written down in order to do it and get the same result.
- Anything in pile A that is only in pile A because nobody has ever
  written down the criteria.
```

---

## 3 · Get what is in their head onto the page

*Pairs with **Your First Five Steps**, step 3. Run it as an interview.*

```
You are going to interview me to extract how I do a specific task, so
that somebody else can do it and get the same result.

The task: [TASK]
Who will use the output: [WHO, AND HOW EXPERIENCED THEY ARE]

Important: I have done this thousands of times, so most of what I know
has gone quiet. I will skip steps without realising. Your job is to
catch that.

Rules:
- One question at a time.
- Every time I say "obviously", "you just", "it depends", or "you get
  a feel for it", STOP and dig into that. That is where the real
  knowledge is hiding.
- Ask "how would someone know to do that?" and "what would go wrong if
  they got that bit wrong?" repeatedly.
- Ask about the edge cases and the exceptions, not just the happy path.
- Keep going until you could hand the output to the person above and
  they would not have to come and ask me anything.

When we are done, write it up as a procedure with:
- The trigger (when this starts)
- The steps, in order
- The judgment calls, with the criteria for each
- What "done and correct" looks like
- The three mistakes most likely to be made by someone new
```

**A note on this one:** it is worth running twice. The first pass gets the procedure. The second pass, a week later after somebody has actually tried to use it, gets the things you both forgot.

---

## 4 · Draft your one page

*Pairs with **The One Page**.*

```
Help me write a one-page document that lets my team make decisions
about building with AI without coming to me for every one.

It has three parts:
  NORTH STAR  - the one named, expensive problem we are solving first
  GUARD RAILS - rules that make people refuse things
  SPEED LIMIT - nobody ships what they can't explain

About us: [WHAT YOU DO, TEAM SIZE, WHO WOULD BE BUILDING]
The most expensive problem I can name right now: [PROBLEM]
Things we have built or nearly built that I regret: [ANY]

Interview me until you have enough. Then draft it.

Constraints on the draft:
- Fits on one page. If it needs two, cut.
- Three to five rules, no more.
- Every rule must be phrased so it REFUSES something. Start them with
  "We don't" or "Nothing ships unless". Never "we believe" or
  "we embrace".
- Next to each rule, write the specific thing it would have stopped,
  based on what I told you.

Then tell me which of my rules are decoration, and why.
```

---

## 5 · Test a rule

*Pairs with **Rules That Actually Refuse Something**. Ten seconds, and it kills posters.*

```
Here is a rule we are considering:

"[YOUR RULE]"

Answer three things, briefly:
1. Name three specific, realistic things someone in my business would
   want to do that this rule would stop them doing.
2. If you cannot name three, say so plainly. It is a poster.
3. Rewrite it as a sharper refusal, starting with "We don't" or
   "Nothing ships unless".

Context on my business: [ONE OR TWO LINES]
```

---

## 6 · The pre-build check

*Not in the talk. Use it before anyone starts building anything.*

```
Someone on my team wants to build this:

[WHAT THEY WANT TO BUILD]

Run it against these checks and give me a straight verdict on each:

1. WHAT PROBLEM? Is there a named, specific problem, or is this
   "wouldn't it be cool if"? If there is no named problem there is no
   finish line.
2. HAVE WE TRIED TO DELETE IT? Could we just stop doing this process
   instead of automating it? Automating a bad process makes it
   permanent.
3. NET WORK. Does this take away more work than it creates, including
   the ongoing cost of keeping it running? Be honest about maintenance.
4. OLD SHAPE. Is this just a faster version of how the job works
   today? What would we build if the original constraint had never
   existed?
5. WHO FIXES IT? If the person building this is unavailable, who
   maintains it? If the answer is nobody, it does not go live.
6. WHO CONSUMES IT? Who is waiting on the output? If the answer is
   "me, when I remember", it will rot.

Finish with: BUILD, RESHAPE, or DON'T BUILD, and one line of why.
```

---

## How to make these permanent

Everything above is a prompt you paste. That is fine to start, and it is also exactly the level-two trap from the talk: it works, and it lives with whoever remembers to use it.

The next move is to turn the ones you use repeatedly into something anyone on your team can run without knowing the prompt exists. In Claude Code that means saving them as skills; in most other setups it means a shared library your team can reach and improve.

The test is the same as everywhere else in this toolkit:

> When someone improves one of these, does everybody get the improvement without asking?

If yes, it belongs to the company. If no, you are still renting it.

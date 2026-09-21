# 01 Voice

Goal: a skill that writes the way you write. Not the way LinkedIn writes.

This is the step most people rush and the one the whole build rests on. Fill in `docs/VOICE-CARD.md` in this kit before you paste this. The block has three places that want your card.

The prompt works whether you have 200 LinkedIn posts or none. Claude reads what exists, then asks for what does not. The one thing it needs from everyone is ten minutes of you talking about your own work, then a few follow-up questions. Have a project in mind.

---

```
Step 1: my voice.

First, find out what you can read. Ask me these four things, one at a time, and go by my answers:
a. Do I have LinkedIn posts I wrote myself? If yes, open my profile in your browser and read the last 50 originals. Skip reposts. If I have fewer than ten, read them all and treat them as a hint, not a voice.
b. Do I have other writing? A newsletter, a blog, talk notes, long Slack or email messages, a portfolio, a case study, a cover letter. Read the three most recent or best: <URLs, pasted text, or "none">.
c. Do I have meeting notes you can read (Granola or similar)? If yes, read the last seven days. If no, skip it and say so; nothing else depends on it.
d. Read my Memory.

If I have nothing written anywhere, do not guess my voice from my job title. Go straight to the talking step below and build the voice from that.

From whatever you read, tell me in ten lines or fewer: what I write about, how I open, how I end, my sentence shape (paragraphs or lines), my tone, the words I lean on, and anything I never do. If you read nothing, say "no sample yet" and skip this. I will correct you. Wait for my corrections.

Then get me talking. Ask me to tell you about one piece of work, out loud or typed, the way I would tell a friend over coffee: what I was trying to do, what went wrong, what I did next, what I would do differently. Do not interrupt. When I stop, ask two follow-ups for the details I skipped: the time, the place, what was on screen, the exact words someone said. This transcript is my voice sample. Treat it as the primary source, above anything you read on LinkedIn, because it is how I talk and not how I perform.

Then interview me. Three to five questions, one at a time, about what you still do not know: who I am writing for, what I want to be known for, what I will never write about, which employers and clients can be named. Write each answer to Memory, one fact per line.

Then draft one post from the work I just told you about, so I can react to something concrete. Expect me to reject it. When I paste a line back and say "I would never say this", do not fix the post. Fix the rule, then redraft.

When I say "lock", write the voice as a skill called linkedin-post-generator and propose it for saving. It must contain:
0. An interview step: before any draft, ask three to five questions and wait. One must ask for my own lived moment. Never invent an action I took or a thing someone said.
1. Positioning: <paste line 1 of my Voice Card>.
2. Deliverables: the post, plus three alternative openings.
3. Post structure in my terms, with the sentence shape you heard when I talked.
4. Openings: four or five shapes taken from how I start a story when I talk, or from my posts if I have them. No hook templates. No typed hooks.
4b. Closers: how I end, taken from my writing or talks if I have them, otherwise from how I ended the story I told you. Never a slogan, an aphorism, or "Thoughts?".
5. Voice rules, including the words and phrases I never use, and my naming rules: <paste section 3 of my Voice Card>.
5b. One reference post per type. Written by me if I have one. If I do not, the redrafted post I approved above is the first reference, marked "approved, not yet posted", and the skill says to replace it with a real post when one exists.
6. What to avoid.
7. My post types, each with shape and purpose: <paste section 2 of my Voice Card>.
8. Final checks, as a numbered list the draft must pass.
9. Compound: after a post is approved, ask once, "Anything to save about how this one was written?", and propose the exact edit to the skill.

Also propose a second skill called ai-isms-check: a two-pass list of AI tells to remove from any draft (em dashes, "not X but Y", filler bridges, stock vocabulary, neat closers that say nothing). Plain list, no prose.
```

---

## Who this is for

| You have | What Claude uses as the voice source |
| --- | --- |
| 50+ LinkedIn posts | Your posts, checked against the story you tell |
| A handful of posts, or other writing | The other writing first, the posts as a hint, the story as the tiebreaker |
| No LinkedIn, or a LinkedIn with nothing on it | The story you tell, plus any writing at all: emails, Slack, a case study |
| No meeting notes | Nothing changes here. Meeting notes only feed the weekly loop in step 3, and that step has a fallback. |

The story you tell is the one source everyone has. It is also the best one. Posts show how you perform. The story shows how you talk. The skill should sound like the second.

## Why the interview goes in the skill, not just the session

A voice skill without an interview step drafts from the idea alone. It fills the gaps with plausible things you did not do. Two real observations that talk to each other make a post. The interview is how the skill gets them.

## Why rejected drafts go in the skill

"I would never say this" is the highest-signal thing you will say all session. A skill that records the rejected line and why it failed stops producing it. A skill that only records rules keeps finding new ways to break them.

## What "ready" looks like

- Claude told you what it could read and what it could not, and did not guess from your job title
- You told one story and Claude asked for the details you skipped
- One draft was rejected, one rule changed, one redraft was closer
- Two skills proposed: linkedin-post-generator and ai-isms-check. Save both from the review cards.

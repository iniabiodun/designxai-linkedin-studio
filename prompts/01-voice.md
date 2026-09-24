# 01 Voice

Goal: a skill that writes the way you write. Not the way LinkedIn writes.

This is the step most people rush and the one the whole build rests on. Fill in `docs/VOICE-CARD.md` in this kit before you paste this. The block has three places that want your card.

The prompt works whether you have 200 LinkedIn posts or none. The assistant reads what exists, then asks for what does not. The one thing it needs from everyone is ten minutes of you talking about your own work, then a few follow-up questions. Have a project in mind.

**Bring writing beyond LinkedIn.** Most people have few posts, or none, and posts are often your most performed writing anyway. Have two or three other pieces ready to paste or link: an article, a blog post, a newsletter, a case study, or something you wrote for your team, like a project update, a proposal, a retro doc, or a long Slack message explaining a decision. Anything you wrote yourself that shows how you write. Strip anything confidential first. If you have none of it, that is fine: the talking step below is the fallback, and it works on its own.

---

```
Step 1: my voice.

First, find out what you can read. Ask me these four things, one at a time, and go by my answers:
a. Do I have LinkedIn posts I wrote myself? If yes, open my profile in your browser and read the last 50 originals. Skip reposts. If I have fewer than ten, read them all and treat them as a hint, not a voice.
b. Do I have other writing? Ask this even if I have LinkedIn posts. Give me examples so I remember what counts: published writing (an article, a blog post, a newsletter, a case study, a portfolio write-up, talk notes) and internal writing I did for my team (a project update, a proposal, a kickoff or retro doc, a design rationale, a long Slack message or email explaining a decision). Read up to three that I wrote alone and that sound like me: <URLs, pasted text, or "none">. Treat this writing as a stronger voice source than my LinkedIn posts. If I paste something with client names or internal numbers, do not store them.
c. Do I have meeting notes you can read (Granola, Fireflies or similar)? If yes, read the last seven days. If no, skip it and say so; nothing else depends on it.
d. Read my memory.

If I have nothing written anywhere, say so plainly and move on. Do not guess my voice from my job title. Go straight to the talking step below and build the voice from that.

From whatever you read, tell me in ten lines or fewer: what I write about, how I open, how I end, my sentence shape (paragraphs or lines), my tone, the words I lean on, and anything I never do. If you read nothing, say "no sample yet" and skip this. I will correct you. Wait for my corrections.

Then get me talking. Ask me to tell you about one piece of work, out loud or typed, the way I would tell a friend over coffee: what I was trying to do, what went wrong, what I did next, what I would do differently. Do not interrupt. When I stop, ask two follow-ups for the details I skipped: the time, the place, what was on screen, the exact words someone said. This transcript is my voice sample. Treat it as the primary source, above anything you read on LinkedIn, because it is how I talk and not how I perform.

Then interview me. Three to five questions, one at a time, about what you still do not know: who I am writing for, what I want to be known for, what I will never write about, which employers and clients can be named. Write each answer to memory, one fact per line.

Then draft one post from the work I just told you about, so I can react to something concrete. Expect me to reject it. When I paste a line back and say "I would never say this", do not fix the post. Fix the rule, then redraft.

When I say "lock", write the voice as a skill called linkedin-post-generator and propose it for saving. It must contain:
0. An interview step, for drafting in chat: before any draft, ask three to five questions and wait. The Studio page skips this step and drafts straight away. One must ask for my own lived moment. Never invent an action I took or a thing someone said.
1. Positioning: <paste section 1 of my Voice Card>.
2. Deliverables: the post, plus three alternative openings.
3. Post structure in my terms, with the sentence shape you heard when I talked.
4. Openings: four or five shapes taken from how I start a story when I talk, or from my posts if I have them. No hook templates. No typed hooks.
4b. Closers: how I end, taken from my writing or talks if I have them, otherwise from how I ended the story I told you. Never a slogan, an aphorism, or "Thoughts?".
5. Voice rules, and my naming rules: <paste section 3 of my Voice Card>.
5a. Banned words and phrases: the words I never use, from my writing and from every line I rejected in this session. Every rejected line adds to this list. It only grows.
5b. One reference post per type. Written by me if I have one. If I do not, the redrafted post I approved above is the first reference, marked "approved, not yet posted", and the skill says to replace it with a real post when one exists.
6. What to avoid.
7. My post types, each with shape and purpose: <paste section 2 of my Voice Card>.
8. Final checks, as a numbered list the draft must pass.
9. Compound: after a post is approved, ask once, "Anything to save about how this one was written?", and propose the exact edit to the skill.
```

---

## Who this is for

| You have | What the assistant uses as the voice source |
| --- | --- |
| 50+ LinkedIn posts | Your posts, checked against the story you tell |
| A handful of posts, or other writing | The other writing first, the posts as a hint, the story as the tiebreaker |
| No LinkedIn, but an article, a blog, or writing for your team | That writing, checked against the story you tell |
| Nothing written anywhere | The story you tell. Ten minutes about work you care about is enough to start |
| No meeting notes | Nothing changes here. Meeting notes only feed the weekly loop in step 4, and that step has a fallback. |

The story you tell is the one source everyone has. It is also the best one. Posts show how you perform. The story shows how you talk. The skill should sound like the second.

## Why the interview goes in the skill, not just the session

A voice skill without an interview step drafts from the idea alone. It fills the gaps with plausible things you did not do. Two real observations that talk to each other make a post. The interview is how the skill gets them.

The interview runs when you draft in chat. The Studio page skips it on purpose: there you want a draft in one click, and you can add detail to the idea box yourself.

## Why rejected drafts go in the skill

"I would never say this" is the highest-signal thing you will say all session. A skill that records the rejected line and why it failed stops producing it. A skill that only records rules keeps finding new ways to break them.

## What "ready" looks like

- The assistant told you what it could read and what it could not, and did not guess from your job title
- You told one story and it asked for the details you skipped
- One draft was rejected, one rule changed, one redraft was closer
- One skill proposed: linkedin-post-generator. Save it when it is proposed.

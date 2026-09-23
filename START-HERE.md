# Start here

Nothing to install. You need an AI assistant with memory, saved instructions, scheduled tasks and connectors, on its desktop app. Claude and ChatGPT both qualify. You also need a place to keep your posts, and a piece of work you can talk about for ten minutes. A LinkedIn account with posts on it helps. It is not required. Neither are meeting notes.

These features are not on every plan. Check yours has them before the day.

This kit was built and tested on Claude. The prompts use plain words and tell the assistant to use its own names for things, so they run elsewhere. The one step most tied to Claude is the Studio page: an Artifact runs its own AI calls with your skills embedded and writes to your table. In another tool the page may be simpler, or the assistant drafts in chat and you copy the approved post to your table by hand. Everything else carries across.

## What we call things

| In this kit | In Claude | In ChatGPT |
| --- | --- | --- |
| Memory | Memory | Memory |
| Skill: a saved set of instructions the assistant applies every time | Skills | Project instructions, or a custom GPT |
| Scheduled task | Scheduled tasks | Tasks |
| Page: something the assistant builds and publishes | Artifacts | Canvas |
| Connectors | Connectors | Connectors and apps |
| Browser | Built-in browser | Agent mode |

Setup takes ten to twenty minutes. Do it before the session if you can. If not, we do it together at the start.

## 1. Connect your tools

Open your assistant's desktop app. Settings, then Connectors.

- **A database** for your approved posts: Craft, Notion or Google Sheets. Connect it and make one empty folder called "LinkedIn Studio".
- **A meeting note taker**, if you use one: Granola, Fireflies, or any dictation tool that leaves you notes. The weekly loop reads it. Skip if you do not; the loop has a fallback.
- **LinkedIn**, if you have it. Sign in once in the assistant's browser so it can read your past posts. Open a new task, ask it to open linkedin.com in its browser, and sign in when the pane shows the login page. If you have no LinkedIn, or have never posted, skip this and bring any writing you have: a newsletter link, a case study, a long email you were proud of.

One note on where things land. Approved posts go to a table, and a spreadsheet is fine for that. Weekly ideas go to a page, one section per idea, which needs Craft, Notion or something else with pages. If a spreadsheet is all you have, the weekly loop writes ideas as rows instead. It works. It reads less well.

## 2. Warm it up

Paste this into a new task and let it finish:

```
List my connectors. If I have LinkedIn, open linkedin.com/in/me in your browser and tell me my display name and headline. Do not post anything.
```

You are ready when the assistant names your connectors and, if you have LinkedIn, reads your headline back to you. If the browser pane shows a login page, sign in and ask again.

## 3. Decide three things on paper

Before you prompt, write these down. `docs/VOICE-CARD.md` has the card. Ten minutes, pen not laptop.

1. **What you want to be known for.** The industry you are in, and the things you would like to share about it. One line.
2. **Your post types.** Think about what you care about, and what gets a reaction from you when you see it in the feed. Three to eight types. Starters: an opinion, an everyday relatable moment, an update from your industry.
3. **Your naming rules.** Which employers, clients and projects can be named, and which should not be mentioned and can stay vague.

If you let the assistant choose these, it will choose the average.

---

## In the room: run the prompts

Open a new task. Run the files in `prompts/`, one at a time, in order. Paste the block, read what comes back, then open the next file.

1. `prompts/00-setup.md`: rules for the session, connectors, browser, folder.
2. `prompts/01-voice.md`: the assistant reads what you have written and interviews you. Output: a skill with your voice in it.
3. `prompts/02-no-ai-slop.md`: a second skill that strips AI tells from every draft. Output: the no-ai-slop skill.
4. `prompts/03-studio.md`: build the page. Output: a published page that drafts, checks and sends.
5. `prompts/04-loop.md`: the weekly loop. Output: two scheduled tasks that write to your folder.

`docs/MASTER-PROMPT.md` is those five in one paste, for people who would rather run it end to end and stop at each checkpoint. It opens with a short list of what happens at each stop, so you know what "go" commits you to.

## Testing

Draft one post from a real idea and read it aloud. Three checks.

**1. Would you have written that sentence?** Every line you would not say is a rule missing from your skill. Paste the line back and say "I would never say this". The assistant fixes the skill, not the post.

**2. Did it invent anything?** An action you took, a number, a thing a colleague said. If yes, the interview step is too weak. Make it ask before it drafts.

**3. Does it look like LinkedIn?** The most common bad output opens with a typed hook, runs one sentence per line, and closes with "Thoughts?". It will look like LinkedIn and it will not be you. Send it back to the voice skill and add the rule that stops it.

The first draft will be wrong. That is the exercise. The skill after the fifth correction is the thing you take home.

## What you leave with

- **Your Studio.** A page that takes an idea to an approved post in your voice, and a weekly loop that puts researched ideas in front of you without being asked.
- **Your first post.** Before you leave, draft one more post in the Studio, about the session: what you built, what surprised you, what you will post next. Approve it, then post it or schedule it on LinkedIn yourself. The assistant never posts for you.
- **The article, if you want it.** `prompts/05-article.md` turns a marked idea into a long-form first draft. It needs the weekly loop to have run once and put an idea on your page that deserves more than a post, so it is for after the session.

## If something breaks

- **The assistant cannot see a connector**: it should stop and name it. Connect it in Settings and say "go".
- **The browser shows a login page or a popup**: sign in or close it by hand in the pane, then say "done".
- **The assistant wants to write to your folder before you approved**: say no. Nothing lands without "Approve and send", or your reply to a scheduled run telling it which ideas to keep.
- **A draft names your employer or a client**: add the rule to the naming section and redraft.

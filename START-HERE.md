# Start here

You are about to build your own LinkedIn Studio with Claude: a page that turns an idea into a post in your voice, shows you how it will look in the feed, and sends the approved post to a table you own. Then two scheduled tasks that read your week and propose ideas while you sleep.

Nothing to install. You need the Claude desktop app and a place to keep your posts (Craft, Notion or a spreadsheet). A LinkedIn account with posts on it helps. It is not required. Neither are meeting notes. The one thing everyone needs is a piece of work they can talk about for ten minutes.

Connectors, Scheduled tasks and Artifacts are not on every Claude plan. Check yours has them before the day.

One note on where things land. Approved posts go to a table, and a spreadsheet is fine for that. Weekly ideas go to a page, one section per idea, which needs Craft, Notion or something else with pages. If a spreadsheet is all you have, the weekly loop writes ideas as rows instead. It works. It reads less well.

Setup takes ten to twenty minutes. Do it before the session if you can. If not, we do it together at the start.

## 1. Connect your tools

Open the Claude desktop app. Settings, then Connectors.

- **Craft** (or Notion, or Google Sheets). This is where approved posts land. Connect it and make one empty folder called "Claude - LinkedIn Studio".
- **Granola** if you use it for meeting notes. The weekly task reads it. Skip if you do not; the task has a fallback.

If you have LinkedIn, sign in to it in Claude's built-in browser once, so Claude can read your past posts. Open a new task in the Claude app, ask it to open linkedin.com in its browser, and sign in when the pane shows the login page. If you do not have LinkedIn, or have never posted, skip this. Bring any writing you have instead: a newsletter link, a case study, a long email you were proud of.

## 2. Warm it up

Paste this into a new Claude task and let it finish:

```
List my connectors. If I have LinkedIn, open linkedin.com/in/me in your browser and tell me my display name and headline. Do not post anything.
```

You are ready when Claude names your connectors and, if you have LinkedIn, reads your headline back to you. If the browser pane shows a login page, sign in and ask again.

## 3. Decide three things on paper

Before you prompt, write these down. `docs/VOICE-CARD.md` has the card.

1. What you want to be known for. One line. Everything else is measured against it.
2. Your post types. Three to eight, each with a purpose. Start with three if you have never posted. The card has a worked example and a column for yours.
3. Your naming rules. Which employers, clients and projects can be named, and which are described by shape.

If you let Claude choose these, it will choose the average.

---

## In the room: run the prompts

Open a new task in the Claude desktop app. Run the files in `prompts/`, one at a time, in order. Paste the block, read what comes back, then open the next file.

1. `prompts/00-setup.md`: connectors, browser, folder.
2. `prompts/01-voice.md`: Claude reads what you have written and interviews you. Output: a skill with your voice in it.
3. `prompts/02-studio.md`: build the page. Output: a published Artifact.
4. `prompts/03-loop.md`: the weekly loop. Output: two scheduled tasks that write to your folder.

`docs/MASTER-PROMPT.md` is those four in one paste, for people who would rather run it end to end and stop at each checkpoint. It opens with a short list of what happens at each stop, so you know what "go" commits you to.

## After the session

`prompts/04-article.md` is the takeaway. Once the weekly loop has put an idea on your page that deserves more than a post, mark it and this task drafts the long-form version. It needs a week of the loop to have run, so it is not for the room.

## The check that matters

Draft one post from a real idea and read it aloud. Two questions.

**1. Would you have written that sentence?** Every line you would not say is a rule missing from your skill. Paste the line back and say "I would never say this". Claude fixes the skill, not the post.

**2. Did it invent anything?** An action you took, a number, a thing a colleague said. If yes, the interview step is too weak. Make it ask before it drafts.

The first draft will be wrong. That is the exercise. The skill after the fifth correction is the thing you take home.

## The failure to watch for: the confident template

The most common bad output is a post that opens with a typed hook, runs one sentence per line, and closes with "Thoughts?". It will look like LinkedIn and it will not be you. Send it back to the voice skill and add the rule that stops it.

## If something breaks

- **Claude cannot see a connector**: it should stop and name it. Connect it in Settings and say "go".
- **The browser shows a login page or a popup**: sign in or close it by hand in the pane, then say "done".
- **Claude wants to write to your folder before you approved**: say no. Nothing lands without "Approve and send", or your reply to a scheduled run telling it which ideas to keep.
- **A draft names your employer or a client**: add the rule to the naming section and redraft.

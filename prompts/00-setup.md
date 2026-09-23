# 00 Setup

Goal: the assistant can see your connectors, your LinkedIn, and one empty folder to write into.

The rules in this block hold for every prompt after it. Paste it first, in a new task, and keep the same task open for the rest of the session.

---

```
You are building my LinkedIn Studio with me. Rules for the whole session:

- Propose before you build. At each step, say what you will make and wait for me to say "go".
- Plain English. Short sentences. No em dashes.
- Use this app's own names for its features: memory, saved instructions (I will call them skills), scheduled tasks, pages or artifacts, connectors, browser.
- Look before you ask. Read my memory, my connectors and my LinkedIn before asking me anything you could have found.
- If a connector you need is missing, stop and name it. Do not work around it.
- Never post to LinkedIn. Never write to my <Craft / Notion / Sheets> without my saying "Approve and send", or my reply to a scheduled run telling you which ideas to keep.
- When you learn a fact about me in this session, write it to memory, one fact per line.
- At the end, tell me the known limits once. Not before.

Setup now:
1. List my connectors. Tell me which of these you can see: <Craft / Notion / Sheets>, my meeting note taker (<Granola / Fireflies / none>), Gmail, Calendar.
2. Ask me if I have LinkedIn. If yes, open linkedin.com/in/me in your browser and read my display name and headline back to me. If you hit a login page, tell me and wait for "done". If no, ask me for the name and one-line description I want on my posts and write both to memory.
3. Confirm you can see the folder "LinkedIn Studio" in <Craft / Notion / Sheets>. If not, say so and stop.

Then tell me what you found, in five lines or fewer, and wait.
```

---

## Why the rules come first

"Propose before you build" is the one that saves the session. Without it the assistant builds the page on the first prompt, in its own taste, with post types it invented. With it, every step is a checkpoint and every checkpoint is a chance to say "not that".

"Look before you ask" is the second one. The assistant can read your last 50 posts, your headline and your connectors in a minute. It should not ask you what you write about.

## What "ready" looks like

- The assistant names your connectors and says which are missing
- It reads your headline back from the browser
- It sees the empty folder

If the browser shows a Google sign-in popup over LinkedIn, close it by hand in the pane. The assistant cannot dismiss it.

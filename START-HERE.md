# Start here

Nothing to install. You need an AI assistant with memory, saved instructions, scheduled tasks and connectors, on its desktop app. Claude and ChatGPT both qualify. You also need a place to keep your posts, and a piece of work you can talk about for ten minutes. A LinkedIn account with posts on it helps. It is not required. Neither are meeting notes. Two or three pieces of your own writing, of any kind, help more than either. See step 3.

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
| Browser | Built-in browser, or the Claude in Chrome extension | Agent mode |

Setup takes ten to twenty minutes. Do it before the session if you can. If not, we do it together at the start.

## 1. Connect your tools

Open your assistant's desktop app. Settings, then Connectors.

- **One place to store everything**: Craft, Notion or Google Sheets. Pick one, not two. Approved posts and weekly ideas both go there. Connect it. You do not need to make a folder; the assistant creates "LinkedIn Studio" for you in the first prompt.
- **A meeting note taker**, if you use one: Granola, Fireflies, or any dictation tool that leaves you notes. The weekly loop reads it. Skip if you do not; the loop has a fallback.
- **LinkedIn**, if you have it. The assistant needs to be signed in to read your past posts. Two ways, pick one:
  - **The app's browser.** Open a new task, ask it to open linkedin.com in its browser, and sign in when the pane shows the login page.
  - **The Claude in Chrome extension.** Install it, sign in to LinkedIn in Chrome as you normally would, and the assistant reads it through your Chrome.

  If you have no LinkedIn, or have never posted, skip this. Your other writing matters more anyway; see step 3.

You do not need Gmail or Calendar. Leave them off.

### Allow all permissions for this workshop

Each connector asks before every read and write unless you tell it not to. In a workshop that means clicking "Allow" dozens of times. Before the day, open each connector you just added (Settings, then Connectors) and set its tools to **Always allow**. If a prompt still pops up during the session, pick "Always allow", not "Allow once". You can tighten it again afterwards. The kit's own rule still holds: nothing is written to your store without "Approve and send".

One note on where things land. Everything goes in the one store you picked, inside the "LinkedIn Studio" folder. Approved posts go to a table. Weekly ideas go to a page, one section per idea. Craft and Notion do both. If you picked Google Sheets, the weekly loop writes ideas as rows on a second sheet instead. It works. It reads less well.

## 2. Warm it up

Paste this into a new task and let it finish:

```
List my connectors. If I have LinkedIn, open linkedin.com/in/me in your browser and tell me my display name and headline. Do not post anything.
```

You are ready when the assistant names your connectors and, if you have LinkedIn, reads your headline back to you. If the browser pane shows a login page, sign in and ask again. If you use the Chrome extension, make sure you are signed in to LinkedIn in Chrome first.

## 3. Gather two or three things you have written

Most people have few LinkedIn posts, or none. That is fine. The assistant learns your voice from anything you wrote yourself, and writing you did for your team is often closer to how you really sound than a post you polished for strangers.

Find two or three pieces and have the links or the text ready to paste:

- **Published**: an article, a blog post, a newsletter issue, a Medium piece, a case study, a portfolio write-up, talk notes.
- **Internal**: a project update to your team, a kickoff or retro doc, a design rationale, a proposal, a long Slack message explaining a decision, an email you were proud of, an onboarding guide you wrote.

Pick things you wrote alone and that sound like you. Skip anything a committee edited. Remove anything confidential before you paste it: client names, numbers, internal plans.

If you have nothing at all, bring nothing. The voice prompt (`prompts/01-voice.md`) has you talk about a piece of work you care about for ten minutes, and the assistant builds your voice from that. It is the fallback, and it works.

## 4. Decide three things on paper

Before you prompt, write these down. `docs/VOICE-CARD.md` has the card. Ten minutes, pen not laptop.

1. **What you want to be known for.** The industry you are in, and the things you would like to share about it. One line.
2. **Your post types.** Think about what you care about, and what gets a reaction from you when you see it in the feed. Three to eight types. Starters: an opinion, an everyday relatable moment, an update from your industry.
3. **Your naming rules.** Which employers, clients and projects can be named, and which should not be mentioned and can stay vague.

If you let the assistant choose these, it will choose the average.

---

## In the room: run the prompts

Open a new task. Run the files in `prompts/`, one at a time, in order. Paste the block, read what comes back, then open the next file.

1. `prompts/00-setup.md`: rules for the session, connectors, browser, and the assistant creates your folder.
2. `prompts/01-voice.md`: the assistant reads what you have written and interviews you. Output: a skill with your voice in it.
3. `prompts/02-no-ai-slop.md`: a second skill that strips AI tells from every draft. Output: the no-ai-slop skill.
4. `prompts/03-studio.md`: build the page. Output: a published page that drafts, checks and sends.
5. `prompts/04-loop.md`: the weekly loop. Output: two scheduled tasks that write to your folder.

`docs/MASTER-PROMPT.md` is those five in one paste, for people who would rather run it end to end and stop at each checkpoint. It opens with a short list of what happens at each stop, so you know what "go" commits you to.

## Testing

Draft one post from a real idea and read it aloud. Three checks.

**1. Would you have written that sentence?** Every line you would not say is a rule missing from your skill. Paste the line back and say "I would never say this". The assistant fixes the skill, not the post.

**2. Did it invent anything?** An action you took, a number, a thing a colleague said. If yes, add more of the real detail to the idea box and draft again, and tell the assistant to add a rule to your skill: never invent what is not in the idea.

**3. Does it look like LinkedIn?** The most common bad output opens with a typed hook, runs one sentence per line, and closes with "Thoughts?". It will look like LinkedIn and it will not be you. Send it back to the voice skill and add the rule that stops it.

The first draft will be wrong. That is the exercise. The skill after the fifth correction is the thing you take home.

## What you leave with

- **Your Studio.** A page that takes an idea to an approved post in your voice, and a weekly loop that puts researched ideas in front of you without being asked.
- **Your first post.** Before you leave, draft one more post in the Studio, about the session: what you built, what surprised you, what you will post next. Approve it, then post it or schedule it on LinkedIn yourself. The assistant never posts for you.
- **The article, if you want it.** `prompts/05-article.md` turns a marked idea into a long-form first draft. It needs the weekly loop to have run once and put an idea on your page that deserves more than a post, so it is for after the session.

## If something breaks

- **The assistant cannot see a connector**: it should stop and name it. Connect it in Settings and say "go".
- **The browser shows a login page or a popup**: sign in or close it by hand in the pane, then say "done". Or switch to the Claude in Chrome extension and sign in there.
- **You keep being asked to allow a connector**: pick "Always allow", or set the connector's tools to Always allow in Settings.
- **The assistant wants to write to your folder before you approved**: say no. Nothing lands without "Approve and send", or your reply to a scheduled run telling it which ideas to keep.
- **A draft names your employer or a client**: add the rule to the naming section and redraft.

# The master prompt

Steps 0 to 3 as one paste. Claude stops at each checkpoint and waits for "go". The article step is a second paste at the bottom, for after the session.

Fill the angle brackets from your Voice Card first. If you have not filled the card, delete the "WHAT I HAVE DECIDED" section and Claude will ask you in Step 1. You will get a rougher first draft. That is fine; the corrections are the exercise.

`CHANGES.md` records what the first version of this brief produced and why each part changed, if you want the reasoning behind a rule.

## What happens at each stop

You say "go" four times. This is what each one starts.

1. **Setup.** Claude lists your connectors, reads your LinkedIn name and headline if you have one, and checks your folder exists. Nothing is written.
2. **Voice.** Claude reads what you have written, gets you talking about one piece of work, interviews you, drafts one post for you to reject, and proposes two skills. You save them from the review cards. This is the long stop.
3. **The Studio.** Claude builds the page, runs nine tests and reports each. Then you draft one real post and send it to your table.
4. **The weekly loop.** Claude sets up two scheduled tasks, runs each once by hand so you see the push, and schedules them.

Then it tells you the limits, once.

---

```
Build my LinkedIn Studio. Work in steps. At each step, propose, then wait for me to say "go".

RULES FOR THE WHOLE SESSION
- Plain English. Short sentences. No em dashes.
- Use the names of the things in this app: Memory, Skills, Scheduled tasks, Artifacts, Connectors.
- Look before you ask. Read my Memory, my connectors and my LinkedIn before asking anything you could have found.
- If a connector you need is missing, stop and name it. Do not work around it.
- Never post to LinkedIn. Never write to my <Craft / Notion / Sheets> without my saying "Approve and send", or my reply to a scheduled run telling you which items to keep.
- When you learn a fact about me, write it to Memory, one fact per line.
- Nothing on the page explains itself. Labels only. No tips, no descriptions.
- At the end, tell me the known limits once.

WHAT I HAVE DECIDED
- What I want to be known for: <line 1 of my Voice Card>.
- My post types, with shape and purpose: <section 2 of my Voice Card>. If I listed fewer than three, help me find more in Step 1. Otherwise do not add or rename them without asking me.
- Naming rules: <section 3 of my Voice Card>.
- Where things land: approved posts in <table>; ideas on one page per week called "Ideas, week of <day> <Month>", or as rows on an "Ideas" sheet if my folder cannot hold pages; meeting notes in <my meeting notes connector, or "none">; long-form drafts inside the idea's own section as a toggle.
- Off-limits topics: <list>.

STEP 0: SETUP
List my connectors. Ask if I have LinkedIn; if yes, open linkedin.com/in/me in your browser and read my name and headline back; if no, ask me for the name and one line to show on posts and write both to Memory. Confirm the folder "Claude - LinkedIn Studio" exists. Report in five lines. Wait.

STEP 1: VOICE
Ask what you can read, one question at a time: LinkedIn posts I wrote (read the last 50 originals; under ten, treat as a hint); other writing (<URLs, pasted text, or "none">); meeting notes (read seven days if a connector exists, otherwise skip and say so); my Memory. If there is nothing to read, do not guess from my job title; go straight to the story.
From what you read, summarise my voice in ten lines: subjects, openings, endings, sentence shape, tone, words I lean on, things I never do. If nothing, say "no sample yet". Wait for corrections.
Get me talking: ask me to tell you about one piece of work the way I would tell a friend, without interrupting, then ask two follow-ups for the details I skipped. That transcript is the primary voice source, above anything on LinkedIn.
Interview me, three to five questions, one at a time, on what you still do not know: who I write for, what I want to be known for, what I never write about, who can be named. Write answers to Memory.
Draft one post from the work I told you about. When I paste a line back and say "I would never say this", fix the rule, not the post, then redraft.
On "lock", propose a skill called linkedin-post-generator with: an interview step (three to five questions, one for my own lived moment, never invent an action or a quote); positioning; deliverables (the post plus three alternative openings); post structure in the sentence shape you heard; my opening shapes from how I start a story or from my posts, no hook templates; my closers from my writing or from how I ended the story, never a slogan or "Thoughts?"; voice rules with banned words and phrases and my naming rules; one reference post per type, written by me, or the approved redraft marked "approved, not yet posted" until a real one exists; what to avoid; my post types; final checks as a numbered list; a compound step that asks once after approval what to save.
Also propose a skill called ai-isms-check: a two-pass list of AI tells to strip from any draft.
Wait for me to save both.

STEP 2: THE STUDIO
Make a design.md from <my newsletter or site URL, a screenshot I paste, or "none">: canvas, text, pop, accent, type, radius. If I have none, ask me for one colour I like and build a plain palette around it. Use it.
Build an Artifact, top to bottom: Idea box and Add photo (preview only; say once after sending that the photo was not sent). Type as a two-column checklist with checkmarks, one selected, not tabs. Generate ideas, Draft, Approve and send; the last is dark. Draft runs interview, Writing with the post skill, Humanising into my sentence shape and ending, Checking with the AI-isms skill; both skills embedded in the page as text. Post box, editable, live to the preview. Other openings as three tiles that swap the first two lines. Checks: words (flag under 150 or over 250), line 1 and 2 length (flag over 62), opening shape, one line on why a scroller stops. Feed preview: name, headline, two lines, "...more", photo, Like Comment Repost Send. Generate ideas panel: five from a topic or, if I have a meeting notes connector, from seven days of meetings; clicking one fills the idea and picks the type. Approve and send writes one row to <table>: name, type, status Draft, shortlist on, date, hook, second line, body, alternative openings; then one line of confirmation. Buttons are rounded rectangles with a crisp edge, a light top highlight and a tight shadow; not pills.
Run nine tests before publishing: empty idea; real idea gets a specific interview; skip still drafts; paragraphs not lines; my opening and my closer; counts update on edit; swap keeps the body; send disabled with no draft; send writes one row and nothing before that. Report each. Wait.

STEP 3: THE WEEKLY LOOP
Two scheduled tasks. Run each once by hand before scheduling.
"Weekly content loop": read Memory and the post skill; read seven days of meeting notes if a connector exists, or, without one, my calendar and sent email for the week, or three things I say happened; find five ideas by my six tests (a detail that reveals how someone sees the world; a belief plain enough to challenge; the ten-year detail; a decision with its cost; the behind-the-scenes of a project; a world a team dreamt up); skip confidential and off-limits; sector names only. Research each: borrowed wisdom with a real quote and link from <my sources> first, a public case with a number, a peer in public. Say when nothing was found. Write per idea: title, source and day, why it stops a scroll, a two-line opening under 62 characters in my shapes, type, research. Push me the titles, wait for my reply, write only the kept ones to the weekly page as sections: heading, one line of type and source and why, the opening as a quote, a collapsed Research toggle, an empty "Draft:" line. If my folder cannot hold pages, one row per idea on an "Ideas" sheet, research in one cell. Never write ideas to my approved-posts table.
"News ideas": same rules and page, three ideas from the past week's news in <my topics>, my usual reads plus the wider press, each with its link. Ask me the topics before you set it up.
Schedule both for <day and time> in my timezone. Wait.

LIMITS
Tell me, once, what this setup cannot do.
```

---

## After the session: the article

Run this once the weekly loop has put an idea on your page that deserves more than a post. Paste it into the same task, or into a new task with the rules block from `prompts/00-setup.md` pasted first. It works whether you already publish long-form or want to start.

```
STEP 4: ARTICLE DRAFT
Propose a skill <my name or newsletter>-essay from my three most recent long pieces at <URL, or "none">: the arc, the voice, the bans, the title shapes, an interview step, a research standard, a 1,200 to 1,800 word deliverable, final checks. If I have none, build the arc from the story I told in Step 1 and my approved posts, say so, and note in the skill that it should be rebuilt once three long pieces exist. Embed it in a task "Article draft", one hour after the idea runs: read three weeks of Ideas pages, or the Ideas sheet, and the posts table; an item is marked by "Article" on its Draft line or as its status; skip anything drafted; research; push me questions and wait; write the draft into the idea's own section by turning "Draft: Article" into a toggle "Draft: <Title>" with the essay inside, or on a sheet into a "Draft" cell on the idea's row; never a new page; never a draft into the posts table; push me titles and word counts. Wait.
```

---

## How to run it in a room

Paste the whole first block. Say "go" at each stop. Budget most of the time for Step 1: the voice is the work. Steps 2 and 3 are twenty minutes each once the voice is right. The article is homework.

When a draft is wrong, the reply is one line: the sentence you would never write, and "I would never say this". Do not explain. Let Claude find the rule.

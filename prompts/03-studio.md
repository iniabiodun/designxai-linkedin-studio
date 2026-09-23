# 03 The Studio

Goal: one page that takes an idea to an approved post without leaving it.

Paste this after both skills are saved. The assistant builds it as a page it can publish (an Artifact in Claude, a Canvas in ChatGPT) so it survives the session and you can open it from any device.

This is the step most tied to Claude. An Artifact runs its own AI calls with your skills embedded and writes to your table. In another tool the page may be simpler, or the assistant drafts in chat and you copy the approved post to your table by hand. Run the prompt and see what it can do; the tests at the end tell you what you got.

---

```
Step 3: build the LinkedIn Studio as a page you can publish. Propose first, then wait for "go".

What it does, top to bottom:
- Idea. A box for one idea. An Add photo button. The photo shows in the preview only; connectors cannot upload it, so say so once after sending.
- Type. My post types as a checklist with checkmarks, two columns. One selected at a time. Not tabs.
- Generate ideas, Draft, Approve and send. Three buttons. Approve and send is the dark one.
- Draft runs a chain: interview (three to five questions, one about my lived moment; I answer or skip), then Writing with the linkedin-post-generator skill, then Humanising (rewrite into my sentence shape, fix the ending per the skill), then Checking with the no-ai-slop skill. Both skills are embedded in the page as text so the page does not depend on finding them.
- Post. The draft in an editable box. Editing it updates the preview.
- Other openings. The three alternatives as tiles. Clicking one swaps the first two lines.
- Checks. Word count (flag under 150 or over 250), line 1 and line 2 length (flag over 62), which opening shape was used, and one line on why a scroller would stop.
- Feed preview on the right: my name, my headline, the first two lines, "...more", the photo if any, Like Comment Repost Send.
- Generate ideas opens a panel: five ideas from a topic I type, or, if I have a meeting notes connector, from the last seven days of my meetings. Clicking one fills the Idea box and picks the type.
- Approve and send writes one row to my <Craft table "Content schedule" / Notion database / sheet> with: name, type, status Draft, shortlist on, date, hook, second line, body, alternative openings. Then shows one line: "Sent. Open the entry. Photo not sent. Add it by hand when you post." It never posts to LinkedIn.

Look:
- Make a design.md first from <my newsletter or site URL, a screenshot I paste, or "none">: canvas, text, one pop colour, one accent, type, radius. If I have none, ask me for one colour I like and build a plain palette around it. Use those, not defaults.
- No descriptions, tips or helper text on the page. Labels only.
- Buttons are rounded rectangles, not pills. A crisp 1px edge, a light top highlight, a tight shadow. The primary is dark with the same shape.

Before you publish, run these tests and tell me the result of each:
1. Empty idea, press Draft: a one-line message, nothing else.
2. A real idea: interview appears, questions are specific to the idea.
3. Skip the interview: it still drafts.
4. Draft lands in paragraphs, not one sentence per line.
5. Opening is one of my shapes. Ending is one of my closers.
6. Word and line counts update as I edit.
7. Swap an opening: the body stays.
8. Approve and send with no draft is disabled.
9. Approve and send with a draft writes one row and shows the confirmation. Nothing is written before that.
```

---

## Why "no helper text"

Every label that explains itself is a label that was named badly. The page has one job and you will use it weekly. Explanations are for the first day and clutter for every day after.

## Why the type is a checklist, not tabs

Tabs say "one of these views". A checklist says "tag this". You are tagging. It also lets you leave it blank and let the skill detect the type.

## Why the skills are embedded

The page runs its own AI calls without your session's memory or skills. If the skill is not in the page, the page drafts without it. Embedding it means the page and your saved skill can drift, so when you change the skill, tell the assistant to rebuild the page.

## What "ready" looks like

- The page is published and opens
- Nine tests reported, all passing
- One real post has gone to your table with "Approve and send"

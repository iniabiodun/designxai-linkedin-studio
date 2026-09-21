# What changed since the first prompt

The first prompt asked for two things: a LinkedIn Studio that turns an idea into a post in my voice and sends approved posts to a table, and a weekly task that reads my meetings and proposes five ideas. Both got built. Almost every part of them changed on the way. This is the record, in the order it happened, with the reason.

The original wording of the brief is not in the working notes any more. This list is rebuilt from the record of what was said and built.

## 1. Where things live

| Was | Is now | Why |
| --- | --- | --- |
| Notion for the content and ideas tables | Craft, in a folder called "Claude - Linkedin Studio" | Notion was the work workspace. Craft is mine. |
| A "Content ideas" table for proposed ideas | One Craft page per week, "Ideas, week of 14 September", one section per idea | I did not like working in the table. A page reads like notes. |
| Approved posts to a table | Still a table, "Content schedule" | Fine for posts. Rows are the right shape for a schedule. |

The old "Content ideas" table still exists with six rows in it. Nothing writes to it now.

## 2. Post types

| First pass (six) | Locked (eight) |
| --- | --- |
| Field note, Pattern, Lesson, Studio note, Women at Work in AI, Demystifying Applied AI and ML for Designers | Lesson drop, Demystify, Build log, Reading the machine, Tactic, Thesis, Leadership lesson, Event announce |

What moved: Women at Work in AI became an audience every post can carry, not a type. Studio note went, because my studio gets no prominence while I am employed. Law meets AI went, because it does not serve the goal. Milestones folded into Event announce. Family builds folded into Build log. Leadership lesson was added late, for building a design function from scratch. Tactic was added because it works for AI and for comms and has the highest comment rate.

## 3. The goal

Amplify my Applied AI visibility as a designer. The Builder's Path (lessons in public) is the pathway and gets room to breathe. Everything else is measured against that.

## 4. Naming rules

Never name a past employer. Describe it by shape: "a lending startup where I was the first design hire". Name my current employer only where a post makes no sense without it, and only on settled work. Never name a client. Never name my studio. Never write about a named colleague's performance.

## 5. Voice

This is where most of the rework went. Each line came from a draft I rejected.

| The draft did this | The rule now |
| --- | --- |
| Hedged | State the thing. "I believe" is the stance marker, used once. |
| One sentence per line, LinkedIn template style | Paragraphs of two to four sentences. Storytelling. Conversational, as if to a friend in design. |
| Stacked fragments for punch | Fragments are rare and earned. |
| Typed hooks, "top performing formats" | Four openings only: a flat statement; a time or place; a person and what they did; what most people get wrong. No hook templates. |
| Endings were slogans, aphorisms or "Thoughts?" | Closers follow my essays: my own proof first, then return to the opening and correct it, hold both sides, roll call of the named people, paired real questions, or refuse the neat ending. |
| Second-hand stories, invented actions | Interview first. Three to five questions, one of them for my own lived moment. Never invent an action I took. |
| AI tells | Banned words and phrases list, plus a separate AI-isms check that runs as a last pass. |
| One reference post for everything | One reference post per type, in section 5b of the skill, because my register shifts with the goal of the post. |

The voice rules live in a skill called linkedin-post-generator. The AI-isms pass is a second skill called ai-isms-check. Both are saved in Skills and both are embedded in the Studio page, so the page does not depend on finding them.

## 6. The Studio page

| Was | Is now |
| --- | --- |
| Default look | My Substack's colours and type: warm off-white canvas, near-black text, sand pop, bronze accent, system sans |
| Post type as segmented tabs | A two-column checklist with a checkmark |
| Pill buttons, flat | 12px rounded rectangles with a crisp edge, white top highlight and a tight shadow. Dark primary with a near-black rim. |
| Generic confirmation | "Sent. Open the entry in Craft. Shortlist ticked, status Draft. Photo not sent. Add it by hand when you post." |

Approve and send writes one row to the Content schedule table: name, type, status Draft, shortlist on, date, hook, second line, body, alternative openings. It never posts to LinkedIn.

## 7. The weekly loop

| Was | Is now |
| --- | --- |
| Five ideas from the last seven days of meetings | Same, plus my six tests for a good idea (a small detail that reveals how someone sees the world; a belief stated plainly enough to challenge; the thing a ten-year veteran notices; a decision with what it gave up; the behind-the-scenes of a project; the world a team dreamt up together) |
| Title, source, why, opening, type | Plus a Research toggle per idea: borrowed wisdom from a named practitioner with a link (Every, Wes Kao, Lenny Rachitsky, Dan Hollick first), a public case with a number, a peer who did it in public |
| Wrote rows to a table | Writes sections to the weekly page. Each idea ends with an empty "Draft:" line. |
| Sunday 7pm | Sunday 5pm London |

## 8. The news task

Added after the loop. Three post ideas from the past week's news, both my usual reads and the wider press. Topics: applied AI for designers; AI-native product design; design tooling and building; design leadership; AI startups and funding; AI models, tools and labs. It was set for Monday 7am, then moved to Sunday 5pm London so both runs land on the same page at the same time.

## 9. The article routine

Added last. A third task, Sunday 6pm London, one hour after the two idea runs.

I mark an idea by typing "Article" on its Draft line, or by setting a post's Status to Article in the Content schedule table (an option added to the table for this). The task researches each marked item to my essay standard, sends me interview questions, waits for my answers, then writes a 1,200 to 1,800 word first draft inside a "Draft: <Title>" toggle on the idea's own section of the weekly page. No new pages. The essay shape comes from a third skill, in-good-company-essay: relatable entry, my evidence, borrowed wisdom, a named framework, return to the opening, "I believe" plus both sides, a forward invitation.

## 10. Rules that did not change

Propose before building. Plain English, short sentences, no em dashes. Use the interface names: Memory, Skills, Scheduled tasks, Artifacts, Connectors. No helper text inside the page. Stop and name a missing connector rather than working around it. Look before asking. Never post to LinkedIn. Never write to my Craft without "Approve and send" or a marked item.

## 11. Known limits, named once

Scheduled tasks cannot use my browser, so they never touch LinkedIn. Connectors cannot upload images, so photos are added by hand. A page that uses connectors cannot be shared publicly. There are no webhooks; nothing fires when Craft changes, the tasks run on the clock.

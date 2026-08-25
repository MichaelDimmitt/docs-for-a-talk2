# Presentation source chats — AI for non-developers, GitHub, version control

Chats from `claude-exports-20260815-203433/` bucketed for a talk on using AI as a
non-developer, the powers of GitHub, and the powers of version control.

**Method:** all 557 exported chats were scored by keyword density across the three
themes, then the opening user turns of every top candidate were read to drop false
positives (`\bPR\b` alone matched a lot of travel and job-search chats). Two chats
appear in more than one bucket by design — *Using GitHub without Git* and *GitHub
essentials for UX designers* sit at the intersection of all three.

---

## 🎯 Bucket 1 — AI for non-developers

The core narrative. Each of these is you translating technical work for a
non-technical audience.

| Chat | Why it fits |
|---|---|
| [GitHub essentials for UX designers](https://claude.ai/chat/eec3f242-7306-4167-8908-a1ae83580a87) | **Best single artifact.** Opens with "You are a technical writer who explains complex topics to a non-technical audience," then builds a workshop doc *and* a meetup lecture post ("what will they learn"). This is the presentation, already drafted. |
| [Shaping AI: a presentation on morphing tools and data](https://claude.ai/chat/8ebd0959-d1aa-40ff-afbb-f4d445ff1b7e) | An hour-long presentation on the process of using Claude — "the shapes we give the AI." Ends in a PowerPoint. Direct prior art. |
| [Getting started with git and design tools](https://claude.ai/chat/d6c8ce95-344c-4055-8f49-946a86e7004f) | "What is the minimum I need to know?" — the exact question the audience has. Includes the Figma-commit-messages research. |
| [Bridging the design knowledge gap in Jacksonville](https://claude.ai/chat/5ea6a827-da46-4945-bf6a-bff777e7380f) | The origin story: designers who want *knowledge exchange*, not networking. Good framing slide for why the talk exists. |
| [Defining a workshop as a concept](https://claude.ai/chat/9bbe3dc9-6019-4074-9d26-f2824d7b3297) | A workshop is a place that holds things that grant capabilities. A metaphor to hang the talk on. |
| [Building a speaker lineup for meetup groups](https://claude.ai/chat/6c35e658-03e5-455f-afe4-2d0f162999fd) | People need prompts to know what they can talk about. Closing "take this back to your group" slide. |
| [How context works](https://claude.ai/chat/797f8112-ff64-415e-b796-c026036b531b) | 122 messages hunting for the best explanation of context windows — local vs. Claude Code vs. Cursor. Mine for an accessible explanation. |
| [AI workflows for customer support with personas](https://claude.ai/chat/a2a19069-0506-46c6-bbde-d20adb63c3e1) | Non-developers (support) using AI with personas and templates. A second, non-design audience example. |

---

## 🐙 Bucket 2 — The powers of GitHub

| Chat | Why it fits |
|---|---|
| [Using GitHub without Git](https://claude.ai/chat/aad89efd-deb3-4548-b8ce-7521ba7177e6) | **Headline chat for this bucket.** A whole blog post on what GitHub does for you with no account, with an account, and without ever touching git. Starring, issues, editing a README in the browser. Purpose-built for non-developers. |
| [Command line tools for git platforms](https://claude.ai/chat/96adc016-5afe-47c0-90ac-76c40f8fabb1) | `gh`, and its equivalents for Bitbucket/GitLab. Drifts into a "capabilities OS" tool idea — a good tangent if there's time. |
| [Exporting project to GitHub for Claude Code development](https://claude.ai/chat/c955157d-9e12-4dc0-97cc-85137a5f27cf) | Moving a Claude *project* into a repo so work can continue. The bridge between "AI chat" and "version control" — likely the best transition slide. |
| [Export project to GitHub with Claude Code structure](https://claude.ai/chat/abb46e12-4b75-40f8-8a48-9655fe533dce) | Short version of the same move. Use for a 30-second demo instead of the 40-message one. |
| [Viewing GitHub gist access](https://claude.ai/chat/34c08e4f-2ab6-4122-a9c3-a6b2786ea697) | Gists as the lightweight on-ramp — sharing a snippet without a repo. |
| [Gist link review request](https://claude.ai/chat/0725cde8-5ffc-491f-be77-7e0374fdb43f) | Reading and iterating on a public gist with AI. Shows the "share a link, get feedback" loop. |
| [Git authentication failed for GitHub Gist](https://claude.ai/chat/9d4b273e-9d17-4e04-842f-0c159730870a) | Token auth, not passwords. The one-slide gotcha every newcomer hits. |
| [Adding a token to a git project](https://claude.ai/chat/de2ee08a-2851-44bd-ae74-53f5800c2591) | Same theme, minimal setup. |
| [Figma repos beta and organization requirements](https://claude.ai/chat/c318a0fc-8e43-4596-ad16-4a8057411106) | **Strong designer hook** — version control arriving inside Figma itself. Pairs with "Getting started with git and design tools." |

---

## 🌿 Bucket 3 — The powers of version control

Ordered roughly by how well they demo to a non-developer audience.

| Chat | Why it fits |
|---|---|
| [Resetting local branch to remote origin](https://claude.ai/chat/7b7bd1fe-665f-4e96-9e78-1b593e924cb9) | `git reset --hard origin/@{u}` — "what kind of wizardry is this?" A great **undo button** story: version control means you can always get back. |
| [Git worktrees and parallel agents in Cursor](https://claude.ai/chat/0eac80dd-3f31-40ff-ab71-5d55574f591e) | **The AI + version control payoff slide.** Worktrees let you run several agents at once without them colliding. |
| [Git worktrees and terminal isolation](https://claude.ai/chat/f8500693-9500-4b20-a56a-8db7d0468195) | The follow-up: why don't developers always do this, and how to clean up. Q&A ammunition. |
| [Git rebase with automatic conflict resolution](https://claude.ai/chat/013927d1-21af-4c7f-8547-47ff24c33708) | `--ours` vs `--theirs` — and you make the AI explain *why it got your prompt wrong*. Doubles as a prompting lesson. |
| [Rebasing while keeping your changes](https://claude.ai/chat/52788e05-c600-484c-b413-03fc5cb4b76c) | Short, clean conflict-resolution moment. |
| [Release branch version detection script](https://claude.ai/chat/ca078aeb-4723-439a-a20b-ce1e97ba5f96) | Turning a repeated manual chore into a script + git alias. Automation-on-top-of-version-control story. |
| [Checking out to latest release branch](https://claude.ai/chat/43a27241-4dbc-4c7f-80c7-27d11f82280d) | The bookend — searching your own chat history to find that script again. |
| [Git checkout -m flag explained](https://claude.ai/chat/7a6eefa9-05c2-43d7-88c8-4fdf15b4b9ae) | Small, clear "ask the AI what a flag does instead of googling" example. |
| [Git cursor command for branching](https://claude.ai/chat/026ca6bd-f57b-495a-be45-d4f4601938f3) | Two messages. Branching from inside the editor — lowest-friction entry point. |
| [Filtering Bitbucket branch by source branch](https://claude.ai/chat/dc6014a9-dd1e-493a-be5b-4a3baabcdf64) | Constructing a PR-filter URL by hand with no API access. Skip unless you want a Bitbucket-shop anecdote. |
| [Multipliers book overview](https://claude.ai/chat/f140c9fb-b2a8-45ca-bf0c-7aa8bd7741ec) | **Sleeper pick.** PR review as a *human* problem: when to fix it yourself vs. hand it back. Version control as collaboration culture, not a tool. |

---

## Suggested spine

1. [Bridging the design knowledge gap](https://claude.ai/chat/5ea6a827-da46-4945-bf6a-bff777e7380f) — why this talk exists
2. [Using GitHub without Git](https://claude.ai/chat/aad89efd-deb3-4548-b8ce-7521ba7177e6) — GitHub is not scary, no git required
3. [Getting started with git and design tools](https://claude.ai/chat/d6c8ce95-344c-4055-8f49-946a86e7004f) + [Figma repos beta](https://claude.ai/chat/c318a0fc-8e43-4596-ad16-4a8057411106) — version control is coming to your tools
4. [Resetting local branch to remote](https://claude.ai/chat/7b7bd1fe-665f-4e96-9e78-1b593e924cb9) — the undo button
5. [Exporting project to GitHub for Claude Code](https://claude.ai/chat/c955157d-9e12-4dc0-97cc-85137a5f27cf) — AI and version control meet
6. [Git worktrees and parallel agents](https://claude.ai/chat/0eac80dd-3f31-40ff-ab71-5d55574f591e) — the payoff
7. [Multipliers](https://claude.ai/chat/f140c9fb-b2a8-45ca-bf0c-7aa8bd7741ec) — it's about people
8. [GitHub essentials for UX designers](https://claude.ai/chat/eec3f242-7306-4167-8908-a1ae83580a87) — close on the workshop that's already written

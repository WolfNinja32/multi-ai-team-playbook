# FAQ.md
# Frequently Asked Questions
# Last updated: 2026-03-15

---

## Getting Started

### Where do I start?

Go to [SETUP.md](SETUP.md) for step-by-step instructions for your 
platform — iPhone, Mac, and Windows. It walks you through everything 
from creating a GitHub account to running your first cycle.

### Do I need to know how to code?

No. This system requires no coding. If you can create a text file 
and paste a link into a chat window, you can run this today.

### Do I need paid subscriptions for ChatGPT and Claude?

Free accounts on both platforms are enough to test the workflow.
In practice most people running this seriously will want paid 
subscriptions — they get you access to the more capable models 
and higher usage limits. But don't let that stop you from trying 
it first.

### Do I need a paid GitHub account?

No. A free GitHub account is all you need. Private repos are 
free on all GitHub plans.

---

## Setting Up Your Repo

### Can I make my repo private?

Yes, but forking won't get you there — GitHub requires forks of 
public repos to stay public. Use GitHub's Import feature instead:

1. Go to github.com and create a new repository
2. Name it whatever you like
3. Set visibility to Private
4. Click "Import code" and paste this URL:
   https://github.com/WolfNinja32/multi-ai-team-playbook
5. GitHub copies all the files into your private repo

No Git commands required. Works on iPhone in Safari or Chrome.

### I'm afraid of ruining CONTEXT.md. What if I make a mistake?

You can't break the original — but here's how to work safely anyway.

Before you edit anything, make a copy:

1. Open your repo in your browser
2. Click or tap CONTEXT.md to open it
3. Click or tap the pencil icon to edit
4. Select all the text and copy it
5. Click or tap the back arrow to cancel without saving
6. Click or tap "Add file" → "Create new file"
7. Name it MY-CONTEXT.md
8. Paste the text in
9. Click or tap "Commit changes"

Now edit MY-CONTEXT.md with your own information.
CONTEXT.md stays untouched as your original template.

When using the prompt templates, point them at MY-CONTEXT.md 
instead of CONTEXT.md.

### What is a repo?

Just a folder on GitHub that holds your files. Think of it like 
a project folder that lives on the internet and keeps a history 
of every change you make.

### What does "fork" mean?

Making your own copy of someone else's repo. Like photocopying 
a template so you can write on your own copy without affecting 
the original. Note: forks of public repos stay public — use 
Import instead if you want a private copy.

---

## Running Your AI Team

### Claude tried to redesign my whole system. What do I do?

This happens when Claude is responding from an existing 
conversation context instead of reading your files fresh.

Two things to fix it:

Start a fresh conversation. Never paste the prompt template 
into an existing chat thread. Claude carries context from 
previous messages and will respond from that context rather 
than from your files.

Ask Claude to confirm it read the file. After pasting your 
prompt template, ask: "Did you read the file at that URL?" 
If Claude says no or gives a vague answer, paste the raw 
file URL again and ask it to read it before responding.

### Claude said it could already do everything without ChatGPT.

Claude is right that it can do many things — but it cannot 
search the live web or run scheduled tasks. If Claude is 
suggesting a complex alternative system involving tokens, 
API keys, or paid services, it has misunderstood the brief.

Start a fresh conversation, paste the prompt template, and 
ask Claude to confirm it read your MY-CONTEXT.md file before 
responding. The prompt templates are specific about roles — 
Claude analyzes, ChatGPT researches. Keep them in their lanes.

### What is a raw URL and why do I need it?

A raw URL shows the plain text contents of a file instead of 
the formatted GitHub page. AI models need the raw URL to read 
your files directly.

To get a raw URL:
1. Open any file in your repo
2. Click or tap the "Raw" button at the top right of the file
3. Copy the URL from your browser address bar
4. It will start with raw.githubusercontent.com

### Do I always need to start a fresh conversation?

Yes. Always start a new chat thread when beginning a session. 
Never paste prompts into an existing conversation or the AI 
will respond from old context instead of your files.

### Can I use models other than ChatGPT and Claude?

Yes. The structure works with any AI models that have 
complementary strengths. ChatGPT and Claude are the starting 
point covered in this playbook, but the GitHub repo doesn't 
care which model reads or writes to it. When a better model 
ships, swap it in.

### What if I only have one AI subscription?

You can run a simplified version with one model — but you lose 
the key benefit of live web research combined with deep analysis. 
ChatGPT handles the research because it can search the live web. 
Claude handles analysis because of its large context window and 
reasoning depth. One model doing both is possible but noticeably 
less effective.

---

## GitHub and Files

### Do I need the GitHub app?

No. Use Chrome or Safari on iPhone, or any browser on Mac and 
Windows. The GitHub website in a browser gives you everything 
you need. The GitHub app is designed for developers and is more 
confusing than the website for this workflow.

### What does "commit" mean?

Saving a change to GitHub. Every commit is timestamped and logged 
so you always have a history of what changed and when. Think of 
it like hitting Save, but with a permanent record attached.

### GitHub asked me for a commit message. What do I write?

Anything short and descriptive works. "filled in my context" or 
"added research results" or "updated tasks" are all perfectly 
good commit messages. It just needs to be something so future 
you knows what changed.

---

## Still have questions?

Check [SETUP.md](SETUP.md) for detailed setup instructions, or 
email gregorydcollins.support@gmail.com for support.
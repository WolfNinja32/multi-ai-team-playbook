# SETUP.md
# Getting Started with Your AI Team
# Last updated: 2026-03-15

---

## Before You Start

You need three things regardless of what device you're on:

- A GitHub account (free at github.com)
- A ChatGPT account (free or paid at chat.openai.com)
- A Claude account (free or paid at claude.ai)

Free accounts on both AI platforms are enough to test the workflow.
Paid subscriptions get you access to the more capable models and
higher usage limits — worth it once you're running regular cycles.

That's it. No API keys. No coding. No additional tools.

---

## Jump to your platform

- [iPhone and iPad](#iphone-and-ipad)
- [Mac](#mac)
- [Windows](#windows)
- [Linux and Chromebook](#linux-and-chromebook)

---

## iPhone and iPad

**Browser recommendation:** Use Chrome or Safari — both work well
with GitHub on iPhone. If you don't have Chrome installed, you can
get it free from the App Store. Avoid the GitHub app — it's designed
for developers and is more confusing than the website for this workflow.

**Tip:** GitHub works best on a fully updated iPhone. If anything
looks broken or buttons don't respond, go to Settings → General →
Software Update and update your iPhone first.

---

### Step 1 — Create a GitHub account

If you don't have one, go to github.com in your browser and sign up.
A free account is all you need.

When signing up GitHub will ask a few questions:
- **Plan:** Choose "Free" — ignore the paid options for now
- **How many people on your team:** Select "Just me"
- **Are you a student or teacher:** Select "Neither"
- **What are you interested in?** You can skip this

You'll need to verify your email address before you can create
repositories. Check your inbox and click the confirmation link
before moving to Step 2.

---

### Step 2 — Get the starter repo

A "repo" is just a folder on GitHub that holds your files.
You need your own copy of the starter repo to work from.

You have two options. Pick one:

**Option A — Import (recommended if you want your work to stay private)**

"Import" creates a fresh private copy under your own account.
Private means only you can see it — no one else on the internet
can view your files.

1. Sign in to github.com in your browser
2. Tap the **+** icon in the top right corner of the screen
3. Tap **"New repository"** from the dropdown menu
4. In the "Repository name" field type: my-ai-team
   (or any name you like — no spaces, use dashes instead)
5. Under "Visibility" tap **Private**
6. Leave everything else as-is
7. Scroll to the bottom and tap **"Create repository"**
8. On the next screen look for **"Import code"** and tap it
   (if you don't see it, look for a link that says
   "import code from another repository")
9. In the URL field paste exactly this:
   https://github.com/WolfNinja32/multi-ai-team-playbook
10. Tap **"Begin import"**
11. Wait about 30 seconds — GitHub will send you an email
    when it's done
12. Open the email and tap the link to see your new repo

You now have a private copy of the starter repo.

**Option B — Fork (quicker, but your repo will be public)**

"Fork" means make a copy. A public repo means anyone on the
internet can see your files — fine if you're not storing
sensitive information.

1. Go to this address in your browser:
   github.com/WolfNinja32/multi-ai-team-playbook
2. Tap the **"Fork"** button near the top of the page
3. Leave everything as-is and tap **"Create fork"**

You now have your own public copy. Done.

**Not sure which to pick?**
If you're using this for business research, competitive analysis,
or anything you'd rather keep to yourself — choose Option A.
If you just want to get started fast and privacy isn't a concern
right now — choose Option B. You can always create a private copy
later.

---

### Step 3 — Read sample-CONTEXT.md before you change anything

Before you touch anything, take two minutes to read the sample
file. It shows you exactly what a working setup looks like so
you're not filling in a blank form with no idea what goes there.

1. Open your repo in your browser
   (if you closed it, go to github.com, tap your profile icon
   in the top right, tap "Your repositories", then tap your
   repo name)

2. You'll see a list of files and folders. Tap **sample-CONTEXT.md**

3. Read through it. Notice:
   - How the "About Me" section is written
   - What goes in "Current Project"
   - How "Success Criteria" defines what a good result looks like
   - How "My Constraints" rules out things that won't work
   - The "Persistent Context" section — this is what tells both
     AI models to check your memory files before responding

4. When you're done, tap the back arrow to return to your
   file list

**What you just read is a real example** from an actual project.
Your CONTEXT.md will follow the same structure but with your
information instead.

---

### Step 4 — Fill in CONTEXT.md

Now it's time to make the system yours. CONTEXT.md is the file
that tells both AI models who you are and what you're working on.
Every session starts by reading this file so the more specific
you are, the better your results will be.

**Before you edit — make a safe copy first:**

1. Open your repo and tap **CONTEXT.md**
2. Tap the pencil icon to edit
3. Select all the text and copy it
4. Tap the back arrow to cancel without saving
5. Tap **"Add file"** → **"Create new file"**
6. Name it **MY-CONTEXT.md**
7. Paste the text in
8. Tap **"Commit changes"**

Now edit MY-CONTEXT.md with your own information.
CONTEXT.md stays untouched as your original template.

**Filling in MY-CONTEXT.md:**

1. Tap **MY-CONTEXT.md** to open it
2. Tap the pencil icon to edit
3. Replace each section with your own information:

   - **About Me** — who you are and what you do in 2-3 sentences
   - **Current Project** — what you're working on right now
   - **Success Criteria** — what a good result looks like for you
   - **My Constraints** — anything that rules out certain approaches
     (no budget for paid tools, no coding, limited time, etc.)
   - **Output Preferences** — how you want the AI to communicate
     results back to you

4. Leave the **Persistent Context** section as-is for now —
   it already contains the right instructions for both models
   to check your memory files

5. Update the **Last Updated** date to today's date

6. When you're done tap **"Commit changes"** at the bottom
   of the page

7. A small popup will appear asking for a commit message —
   you can leave the default message or type something like
   "filled in my context" and tap **"Commit changes"** again

**Not sure what to write?** Go back and read sample-CONTEXT.md
for inspiration. There are no wrong answers — write it the way
you'd explain your situation to a smart assistant on their
first day.

**Tip:** Keep it concise. Both models read this file at the
start of every session so shorter loads faster. A few sentences
per section is plenty to start. You can always come back and
add more detail later.

---

### Step 5 — Run your first cycle

This is where it gets real. Your first cycle has one goal:
prove the system works. Keep the task simple — don't try to
solve your biggest problem on day one.

**Before you start:**
- Open a fresh ChatGPT conversation (not an existing thread)
- Open a fresh Claude conversation (not an existing thread)
- Have your repo open in a third tab so you can copy file URLs

---

**Part A — Give ChatGPT a research task**

1. Open your repo and tap **inbox/tasks.md**
2. Tap the pencil icon and write a simple research task.
   Something like:

   *Search for recent discussions about [your topic] on Reddit
   and YouTube. What are people asking about? What problems
   are they running into? Save a summary of what you find.*

3. Commit the changes

4. Open a fresh ChatGPT conversation

5. Tap the prompts/ folder in your repo and open
   **chatgpt-research-prompt.md**

6. Copy the entire contents

7. Paste it into ChatGPT

8. Replace the placeholder URL with the raw URL of your
   MY-CONTEXT.md file

   **How to get the raw URL:**
   - Open MY-CONTEXT.md in your repo
   - Tap the **"Raw"** button at the top right of the file
   - Copy the URL from your browser address bar
   - It will start with raw.githubusercontent.com

9. Send the message and wait for ChatGPT to respond

10. Copy ChatGPT's full response

11. Go back to your repo and tap **"Add file"** →
    **"Create new file"**

12. In the filename field type:
    **reports/2026-03-15-research.md**
    (use today's date in place of 2026-03-15)

    **Note:** Typing the folder name followed by a slash
    automatically creates the reports/ folder and places
    your file inside it. You don't need to create the
    folder separately — GitHub does it for you the moment
    you commit the file.

13. Paste ChatGPT's response in

14. Tap **"Commit changes"**

---

**Part B — Have Claude analyze the results**

1. Open a fresh Claude conversation

2. Open **prompts/claude-analysis-prompt.md** in your repo

3. Copy the entire contents

4. Paste it into Claude

5. Replace the placeholder URLs with the raw URLs for:
   - Your MY-CONTEXT.md file
   - Your memory files
   - The research report you just committed

6. Ask Claude: **"Did you read all the files?"**
   Wait for confirmation before proceeding.

7. Send the message and wait for Claude to respond

8. Copy Claude's full response

9. Go back to your repo and tap **"Add file"** →
   **"Create new file"**

10. In the filename field type:
    **analysis/2026-03-15-analysis.md**
    (use today's date in place of 2026-03-15)

    **Note:** Just like the reports/ folder, typing
    analysis/ followed by a slash automatically creates
    the analysis/ folder and places your file inside it.
    GitHub creates the folder for you when you commit.

11. Paste Claude's response in

12. Tap **"Commit changes"**

---

**You just completed your first cycle.**

ChatGPT researched. Claude analyzed. You stayed in control.
Everything is saved in your repo with a timestamp.

Your second cycle will be faster. By your fifth cycle it
will feel like second nature.

---

## Mac

**Browser recommendation:** Use Chrome or Safari — both work well
with GitHub on Mac. You'll be doing most of your work in the
browser and in two AI chat tabs, so a browser you're comfortable
with is all you need.

---

### Step 1 — Create a GitHub account

If you don't have one, go to github.com in your browser and sign up.
A free account is all you need.

When signing up GitHub will ask a few questions:
- **Plan:** Choose "Free" — ignore the paid options for now
- **How many people on your team:** Select "Just me"
- **Are you a student or teacher:** Select "Neither"
- **What are you interested in?** You can skip this

You'll need to verify your email address before you can create
repositories. Check your inbox and click the confirmation link
before moving to Step 2.

---

### Step 2 — Get the starter repo

A "repo" is just a folder on GitHub that holds your files.
You need your own copy of the starter repo to work from.

You have two options. Pick one:

**Option A — Import (recommended if you want your work to stay private)**

"Import" creates a fresh private copy under your own account.
Private means only you can see it — no one else on the internet
can view your files.

1. Sign in to github.com in your browser
2. Click the **+** icon in the top right corner of the screen
3. Click **"New repository"** from the dropdown menu
4. In the "Repository name" field type: my-ai-team
   (or any name you like — no spaces, use dashes instead)
5. Under "Visibility" select **Private**
6. Leave everything else as-is
7. Scroll to the bottom and click **"Create repository"**
8. On the next screen look for **"Import code"** and click it
   (if you don't see it, look for a link that says
   "import code from another repository")
9. In the URL field paste exactly this:
   https://github.com/WolfNinja32/multi-ai-team-playbook
10. Click **"Begin import"**
11. Wait about 30 seconds — GitHub will send you an email
    when it's done
12. Open the email and click the link to see your new repo

You now have a private copy of the starter repo.

**Option B — Fork (quicker, but your repo will be public)**

"Fork" means make a copy. A public repo means anyone on the
internet can see your files — fine if you're not storing
sensitive information.

1. Go to this address in your browser:
   github.com/WolfNinja32/multi-ai-team-playbook
2. Click the **"Fork"** button near the top of the page
3. Leave everything as-is and click **"Create fork"**

You now have your own public copy. Done.

**Not sure which to pick?**
If you're using this for business research, competitive analysis,
or anything you'd rather keep to yourself — choose Option A.
If you just want to get started fast and privacy isn't a concern
right now — choose Option B. You can always create a private copy
later.

---

### Step 3 — Read sample-CONTEXT.md before you change anything

Before you touch anything, take two minutes to read the sample
file. It shows you exactly what a working setup looks like so
you're not filling in a blank form with no idea what goes there.

1. Open your repo in your browser
   (if you closed it, go to github.com, click your profile icon
   in the top right, click "Your repositories", then click your
   repo name)

2. You'll see a list of files and folders. Click **sample-CONTEXT.md**

3. Read through it. Notice:
   - How the "About Me" section is written
   - What goes in "Current Project"
   - How "Success Criteria" defines what a good result looks like
   - How "My Constraints" rules out things that won't work
   - The "Persistent Context" section — this is what tells both
     AI models to check your memory files before responding

4. When you're done, click the back arrow to return to your
   file list

**What you just read is a real example** from an actual project.
Your CONTEXT.md will follow the same structure but with your
information instead.

---

### Step 4 — Fill in CONTEXT.md

Now it's time to make the system yours. CONTEXT.md is the file
that tells both AI models who you are and what you're working on.
Every session starts by reading this file so the more specific
you are, the better your results will be.

**Before you edit — make a safe copy first:**

1. Open your repo and click **CONTEXT.md**
2. Click the pencil icon to edit
3. Select all the text (`Cmd+A`) and copy it (`Cmd+C`)
4. Click the back arrow to cancel without saving
5. Click **"Add file"** → **"Create new file"**
6. Name it **MY-CONTEXT.md**
7. Paste the text in (`Cmd+V`)
8. Click **"Commit changes"**

Now edit MY-CONTEXT.md with your own information.
CONTEXT.md stays untouched as your original template.

**Filling in MY-CONTEXT.md:**

1. Click **MY-CONTEXT.md** to open it
2. Click the pencil icon to edit
3. Replace each section with your own information:

   - **About Me** — who you are and what you do in 2-3 sentences
   - **Current Project** — what you're working on right now
   - **Success Criteria** — what a good result looks like for you
   - **My Constraints** — anything that rules out certain approaches
     (no budget for paid tools, no coding, limited time, etc.)
   - **Output Preferences** — how you want the AI to communicate
     results back to you

4. Leave the **Persistent Context** section as-is for now —
   it already contains the right instructions for both models
   to check your memory files

5. Update the **Last Updated** date to today's date

6. When you're done click **"Commit changes"** at the bottom
   of the page

7. A small popup will appear asking for a commit message —
   you can leave the default message or type something like
   "filled in my context" and click **"Commit changes"** again

**Not sure what to write?** Go back and read sample-CONTEXT.md
for inspiration. There are no wrong answers — write it the way
you'd explain your situation to a smart assistant on their
first day.

**Tip:** Keep it concise. Both models read this file at the
start of every session so shorter loads faster. A few sentences
per section is plenty to start. You can always come back and
add more detail later.

**Optional — work in VS Code instead of the browser:**

If you have VS Code installed you can edit your files locally
and sync to GitHub with one click. This is more comfortable
for longer editing sessions.

1. Open VS Code
2. Press `Cmd+Shift+P` and type `Git: Clone`
3. Paste your repo URL and choose a folder to save it in
4. Edit your files in VS Code
5. When done, open the Source Control panel, add a commit
   message, and click "Commit & Push"

Your changes will appear on GitHub immediately.

---

### Step 5 — Run your first cycle

This is where it gets real. Your first cycle has one goal:
prove the system works. Keep the task simple — don't try to
solve your biggest problem on day one.

**Before you start:**
- Open a fresh ChatGPT conversation (not an existing thread)
- Open a fresh Claude conversation (not an existing thread)
- Have your repo open in a third tab so you can copy file URLs

**Tip:** On Mac you can use `Cmd+T` to open new tabs and
`Cmd+1`, `Cmd+2`, `Cmd+3` to switch between them quickly.

---

**Part A — Give ChatGPT a research task**

1. Open your repo and click **inbox/tasks.md**
2. Click the pencil icon and write a simple research task.
   Something like:

   *Search for recent discussions about [your topic] on Reddit
   and YouTube. What are people asking about? What problems
   are they running into? Save a summary of what you find.*

3. Click **"Commit changes"**

4. Open a fresh ChatGPT conversation

5. Click the prompts/ folder in your repo and open
   **chatgpt-research-prompt.md**

6. Click the **"Raw"** button at the top right of the file
7. Select all (`Cmd+A`) and copy (`Cmd+C`)

8. Paste it into ChatGPT (`Cmd+V`)

9. Replace the placeholder URL with the raw URL of your
   MY-CONTEXT.md file

   **How to get the raw URL:**
   - Open MY-CONTEXT.md in your repo
   - Click the **"Raw"** button at the top right of the file
   - Copy the URL from your browser address bar (`Cmd+L`
     then `Cmd+C`)
   - It will start with raw.githubusercontent.com

10. Send the message and wait for ChatGPT to respond

11. Select all of ChatGPT's response and copy it

12. Go back to your repo and click **"Add file"** →
    **"Create new file"**

13. In the filename field type:
    **reports/2026-03-15-research.md**
    (use today's date in place of 2026-03-15)

    **Note:** Typing the folder name followed by a slash
    automatically creates the reports/ folder and places
    your file inside it. You don't need to create the
    folder separately — GitHub does it for you the moment
    you commit the file.

14. Paste ChatGPT's response in

15. Click **"Commit changes"**

---

**Part B — Have Claude analyze the results**

1. Open a fresh Claude conversation

2. Click the prompts/ folder in your repo and open
   **claude-analysis-prompt.md**

3. Click the **"Raw"** button and copy the entire contents

4. Paste it into Claude

5. Replace the placeholder URLs with the raw URLs for:
   - Your MY-CONTEXT.md file
   - Your memory files
   - The research report you just committed

6. Ask Claude: **"Did you read all the files?"**
   Wait for confirmation before proceeding.

7. Send the message and wait for Claude to respond

8. Copy Claude's full response

9. Go back to your repo and click **"Add file"** →
   **"Create new file"**

10. In the filename field type:
    **analysis/2026-03-15-analysis.md**
    (use today's date in place of 2026-03-15)

    **Note:** Just like the reports/ folder, typing
    analysis/ followed by a slash automatically creates
    the analysis/ folder and places your file inside it.
    GitHub creates the folder for you when you commit.

11. Paste Claude's response in

12. Click **"Commit changes"**

---

**You just completed your first cycle.**

ChatGPT researched. Claude analyzed. You stayed in control.
Everything is saved in your repo with a timestamp.

Your second cycle will be faster. By your fifth cycle it
will feel like second nature.

---

## Windows

**Browser recommendation:** Use Chrome or Edge — both work well
with GitHub on Windows. Chrome is the most widely tested.
Avoid the GitHub app — it's designed for developers and is more
confusing than the website for this workflow.

---

### Step 1 — Create a GitHub account

If you don't have one, go to github.com in your browser and sign up.
A free account is all you need.

When signing up GitHub will ask a few questions:
- **Plan:** Choose "Free" — ignore the paid options for now
- **How many people on your team:** Select "Just me"
- **Are you a student or teacher:** Select "Neither"
- **What are you interested in?** You can skip this

You'll need to verify your email address before you can create
repositories. Check your inbox and click the confirmation link
before moving to Step 2.

---

### Step 2 — Get the starter repo

A "repo" is just a folder on GitHub that holds your files.
You need your own copy of the starter repo to work from.

You have two options. Pick one:

**Option A — Import (recommended if you want your work to stay private)**

"Import" creates a fresh private copy under your own account.
Private means only you can see it — no one else on the internet
can view your files.

1. Sign in to github.com in your browser
2. Click the **+** icon in the top right corner of the screen
3. Click **"New repository"** from the dropdown menu
4. In the "Repository name" field type: my-ai-team
   (or any name you like — no spaces, use dashes instead)
5. Under "Visibility" select **Private**
6. Leave everything else as-is
7. Scroll to the bottom and click **"Create repository"**
8. On the next screen look for **"Import code"** and click it
   (if you don't see it, look for a link that says
   "import code from another repository")
9. In the URL field paste exactly this:
   https://github.com/WolfNinja32/multi-ai-team-playbook
10. Click **"Begin import"**
11. Wait about 30 seconds — GitHub will send you an email
    when it's done
12. Open the email and click the link to see your new repo

You now have a private copy of the starter repo.

**Option B — Fork (quicker, but your repo will be public)**

"Fork" means make a copy. A public repo means anyone on the
internet can see your files — fine if you're not storing
sensitive information.

1. Go to this address in your browser:
   github.com/WolfNinja32/multi-ai-team-playbook
2. Click the **"Fork"** button near the top of the page
3. Leave everything as-is and click **"Create fork"**

You now have your own public copy. Done.

**Not sure which to pick?**
If you're using this for business research, competitive analysis,
or anything you'd rather keep to yourself — choose Option A.
If you just want to get started fast and privacy isn't a concern
right now — choose Option B. You can always create a private copy
later.

---

### Step 3 — Read sample-CONTEXT.md before you change anything

Before you touch anything, take two minutes to read the sample
file. It shows you exactly what a working setup looks like so
you're not filling in a blank form with no idea what goes there.

1. Open your repo in your browser
   (if you closed it, go to github.com, click your profile icon
   in the top right, click "Your repositories", then click your
   repo name)

2. You'll see a list of files and folders. Click **sample-CONTEXT.md**

3. Read through it. Notice:
   - How the "About Me" section is written
   - What goes in "Current Project"
   - How "Success Criteria" defines what a good result looks like
   - How "My Constraints" rules out things that won't work
   - The "Persistent Context" section — this is what tells both
     AI models to check your memory files before responding

4. When you're done, click the back arrow to return to your
   file list

**What you just read is a real example** from an actual project.
Your CONTEXT.md will follow the same structure but with your
information instead.

---

### Step 4 — Fill in CONTEXT.md

Now it's time to make the system yours. CONTEXT.md is the file
that tells both AI models who you are and what you're working on.
Every session starts by reading this file so the more specific
you are, the better your results will be.

**Before you edit — make a safe copy first:**

1. Open your repo and click **CONTEXT.md**
2. Click the pencil icon to edit
3. Select all the text (`Ctrl+A`) and copy it (`Ctrl+C`)
4. Click the back arrow to cancel without saving
5. Click **"Add file"** → **"Create new file"**
6. Name it **MY-CONTEXT.md**
7. Paste the text in (`Ctrl+V`)
8. Click **"Commit changes"**

Now edit MY-CONTEXT.md with your own information.
CONTEXT.md stays untouched as your original template.

**Filling in MY-CONTEXT.md:**

1. Click **MY-CONTEXT.md** to open it
2. Click the pencil icon to edit
3. Replace each section with your own information:

   - **About Me** — who you are and what you do in 2-3 sentences
   - **Current Project** — what you're working on right now
   - **Success Criteria** — what a good result looks like for you
   - **My Constraints** — anything that rules out certain approaches
     (no budget for paid tools, no coding, limited time, etc.)
   - **Output Preferences** — how you want the AI to communicate
     results back to you

4. Leave the **Persistent Context** section as-is for now —
   it already contains the right instructions for both models
   to check your memory files

5. Update the **Last Updated** date to today's date

6. When you're done click **"Commit changes"** at the bottom
   of the page

7. A small popup will appear asking for a commit message —
   you can leave the default message or type something like
   "filled in my context" and click **"Commit changes"** again

**Not sure what to write?** Go back and read sample-CONTEXT.md
for inspiration. There are no wrong answers — write it the way
you'd explain your situation to a smart assistant on their
first day.

**Tip:** Keep it concise. Both models read this file at the
start of every session so shorter loads faster. A few sentences
per section is plenty to start. You can always come back and
add more detail later.

**Optional — work in VS Code instead of the browser:**

If you have VS Code installed you can edit your files locally
and sync to GitHub with one click. This is more comfortable
for longer editing sessions.

1. Open VS Code
2. Press `Ctrl+Shift+P` and type `Git: Clone`
3. Paste your repo URL and choose a folder to save it in
4. Edit your files in VS Code
5. When done, open the Source Control panel, add a commit
   message, and click "Commit & Push"

Your changes will appear on GitHub immediately.

**Note for Windows users:** If VS Code asks you to install
Git when you try to clone, click "Download Git" and install
it. It's free and takes about two minutes. Restart VS Code
after installing and try again.

---

### Step 5 — Run your first cycle

This is where it gets real. Your first cycle has one goal:
prove the system works. Keep the task simple — don't try to
solve your biggest problem on day one.

**Before you start:**
- Open a fresh ChatGPT conversation (not an existing thread)
- Open a fresh Claude conversation (not an existing thread)
- Have your repo open in a third tab so you can copy file URLs

**Tip:** On Windows you can use `Ctrl+T` to open new tabs and
`Ctrl+1`, `Ctrl+2`, `Ctrl+3` to switch between them quickly.

---

**Part A — Give ChatGPT a research task**

1. Open your repo and click **inbox/tasks.md**
2. Click the pencil icon and write a simple research task.
   Something like:

   *Search for recent discussions about [your topic] on Reddit
   and YouTube. What are people asking about? What problems
   are they running into? Save a summary of what you find.*

3. Click **"Commit changes"**

4. Open a fresh ChatGPT conversation

5. Click the prompts/ folder in your repo and open
   **chatgpt-research-prompt.md**

6. Click the **"Raw"** button at the top right of the file
7. Select all (`Ctrl+A`) and copy (`Ctrl+C`)

8. Paste it into ChatGPT (`Ctrl+V`)

9. Replace the placeholder URL with the raw URL of your
   MY-CONTEXT.md file

   **How to get the raw URL:**
   - Open MY-CONTEXT.md in your repo
   - Click the **"Raw"** button at the top right of the file
   - Copy the URL from your browser address bar (`Ctrl+L`
     then `Ctrl+C`)
   - It will start with raw.githubusercontent.com

10. Send the message and wait for ChatGPT to respond

11. Select all of ChatGPT's response and copy it

12. Go back to your repo and click **"Add file"** →
    **"Create new file"**

13. In the filename field type:
    **reports/2026-03-15-research.md**
    (use today's date in place of 2026-03-15)

    **Note:** Typing the folder name followed by a slash
    automatically creates the reports/ folder and places
    your file inside it. You don't need to create the
    folder separately — GitHub does it for you the moment
    you commit the file.

14. Paste ChatGPT's response in

15. Click **"Commit changes"**

---

**Part B — Have Claude analyze the results**

1. Open a fresh Claude conversation

2. Click the prompts/ folder in your repo and open
   **claude-analysis-prompt.md**

3. Click the **"Raw"** button and copy the entire contents

4. Paste it into Claude

5. Replace the placeholder URLs with the raw URLs for:
   - Your MY-CONTEXT.md file
   - Your memory files
   - The research report you just committed

6. Ask Claude: **"Did you read all the files?"**
   Wait for confirmation before proceeding.

7. Send the message and wait for Claude to respond

8. Copy Claude's full response

9. Go back to your repo and click **"Add file"** →
   **"Create new file"**

10. In the filename field type:
    **analysis/2026-03-15-analysis.md**
    (use today's date in place of 2026-03-15)

    **Note:** Just like the reports/ folder, typing
    analysis/ followed by a slash automatically creates
    the analysis/ folder and places your file inside it.
    GitHub creates the folder for you when you commit.

11. Paste Claude's response in

12. Click **"Commit changes"**

---

**You just completed your first cycle.**

ChatGPT researched. Claude analyzed. You stayed in control.
Everything is saved in your repo with a timestamp.

Your second cycle will be faster. By your fifth cycle it
will feel like second nature.

---

## Linux and Chromebook

The process is similar to Mac for Linux. Chromebook users can
follow the iPhone instructions using the Chrome browser.

---

## Glossary

**Repo (repository)**
Just a folder on GitHub that holds your files. Think of it like
a project folder that lives on the internet and keeps a history
of every change you make.

**Fork**
Making your own copy of someone else's repo. Like photocopying
a template so you can write on your own copy without affecting
the original.

**Import**
Another way to copy a repo. Unlike forking, an imported copy
can be set to private and is fully independent from the original.

**Private repo**
A repo only you can see. Nobody else on the internet can view
your files.

**Public repo**
A repo anyone on the internet can see and read.

**CONTEXT.md**
Your standing brief. A file that tells both AI models who you
are, what you're working on, and what matters to you. Every
AI session starts by reading this file.

**sample-CONTEXT.md**
A working example of CONTEXT.md filled in with real content.
Read this before filling in your own.

**Commit**
Saving a change to GitHub. Every commit is timestamped and
logged so you always have a history of what changed and when.

**Commit message**
A short note describing what you changed. It shows up in your
repo history. "filled in my context" is a perfectly good
commit message.

**Pencil icon**
The edit button in GitHub's web interface. Tap or click it to
edit any file directly in your browser without needing any
other tools.

**Raw URL**
A link that shows the plain text contents of a file instead
of the formatted GitHub page. AI models need the raw URL to
read your files. Always tap or click the "Raw" button to get it.

**Fresh conversation**
A brand new chat thread with no previous messages. Always
start fresh — never paste prompts into an existing conversation
or the AI will respond from old context instead of your files.
# Modern Software Creation Workshop

Welcome to the **Modern Software Creation** workshop!

Today you will plan, build, change, test, document, and deploy a real software project using modern development tools.

By the end of this workshop, you will have:

- Your own GitHub repository
- Your own customized Maze Runner game
- Your own homepage
- Your own live website
- Experience with a real software delivery workflow

You are not just learning code today.

You are learning how modern software is created.

---

# Workshop Info

## Session

**Modern Software Creation**

## Event

**TTD 2026**

## Date

**Thursday, May 7, 2026**

## Instructor

**Christopher Mank**

## Organizations

**Mank Solutions | Cornerstone Tech Academy**

---

# Big Idea

Modern software is not built by randomly typing code.

Modern software teams follow a process:

```text
Plan → Code → Build → Test → Deploy → Document → Improve
```

Today, you will walk through that same process.

You will use:

- GitHub
- GitHub Issues
- GitHub web editor
- HTML
- CSS
- JavaScript
- GitHub Actions
- GitHub Pages
- README documentation

---

# What You Need

Before starting, make sure you have:

- A GitHub account
- Access to the email used for your GitHub account
- A laptop or Chromebook
- Internet access

No software installation is required.

We will use the browser.

---

# Workshop Goals

By the end of this workshop, you should understand how to:

- Create your own project from a template
- Open code in the browser
- Use Issues to plan work
- Edit HTML, CSS, and JavaScript
- Commit and push changes
- Connect commits to Issues
- Watch automation run
- Deploy a website using GitHub Pages
- Update project documentation

---

# Workshop Agenda

## 1. Introduction

We will begin by looking at what you are going to build.

You will create your own version of a Maze Runner game and publish it online.

At the end of the workshop, you will be able to share a live website link with others.

---

## 2. What is DevOps?

DevOps is a modern way software teams plan, build, test, deploy, and improve software.

A simple DevOps flow looks like this:

```text
Plan → Code → Build → Test → Deploy → Improve
```

Today, you will do each part of that flow.

You will:

1. Plan your work with Issues
2. Change code
3. Commit and push your work
4. Watch automation run
5. Deploy your website
6. Document your project

---

# Step 1: Create Your Project

Your instructor will give you a link to the workshop template repository.

Open the template repository in GitHub.

Click:

```text
Use this template
```

Then choose:

```text
Create a new repository
```

Name your repository something like:

```text
modern-software-workshop
```

or:

```text
maze-runner
```

Make sure the repository is created in **your own GitHub account**.

---

# Step 2: Review Your Project Files

Your new repository should include files like these:

```text
index.html
maze-runner.html
README.md
.github/workflows/deploy.yml
```

Here is what each file does:

| File | Purpose |
|---|---|
| `index.html` | Your homepage |
| `maze-runner.html` | Your Maze Runner game |
| `README.md` | Project documentation |
| `.github/workflows/deploy.yml` | Automation that deploys your site |

---

# Step 3: Open Your Project in the Browser Editor

GitHub has a browser-based editor that feels like Visual Studio Code.

Open your repository in GitHub.

Then press the period key:

```text
.
```

This opens your project in:

```text
github.dev
```

This lets you edit your code directly in the browser.

No install required.

---

# Step 4: Make Your First Commit

Before working on the game, make a small change so you can practice the workflow.

Open:

```text
README.md
```

Add your name near the top.

Example:

```markdown
Built by: Your Name
```

Then save the file.

On the left side, open the **Source Control** panel.

Write a commit message:

```text
My first commit
```

Then click:

```text
Commit & Push
```

You just saved your first change to GitHub.

---

# Step 5: Understand Work Planning

Modern software teams do not just randomly change code.

They plan work using tasks.

In GitHub, these tasks are called **Issues**.

An Issue describes:

- What needs to change
- Why it matters
- How we know it is done

---

# Step 6: Open the Issues Tab

Go back to your GitHub repository page.

Click:

```text
Issues
```

You should see several workshop tasks.

Example Issues:

```text
Issue 1: Personalize the Game Title
Issue 2: Change Player Color
Issue 3: Add a Win Message
Issue 4: Link Game from Homepage
Issue 5: Update the README
```

Each Issue is a small piece of work.

---

# Step 7: Complete Issue 1

## Issue 1: Personalize the Game Title

### Goal

Update the game title so it includes your name.

Example:

```text
Maze Runner - Alex's Game
```

---

## Steps

Open:

```text
maze-runner.html
```

Look for the page heading or title.

It may look something like this:

```html
<h1>Maze Runner</h1>
```

Change it to include your name:

```html
<h1>Maze Runner - Alex's Game</h1>
```

Save your changes.

---

## Commit Your Change

Open Source Control.

Use a commit message like:

```text
Fixes #1 - personalize game title
```

Then click:

```text
Commit & Push
```

Using `Fixes #1` connects your code change to Issue 1.

That is how real software teams connect work to code.

---

# Step 8: Complete Issue 2

## Issue 2: Change Player Color

### Goal

Customize the player in the game.

---

## Steps

Open:

```text
maze-runner.html
```

Look for the player style or player color.

It may look like one of these:

```css
background: blue;
```

or:

```javascript
playerColor = "blue";
```

Change the color to something you like.

Examples:

```css
background: green;
```

```css
background: purple;
```

```css
background: #6c5ce7;
```

Save your changes.

---

## Test Your Change

Open the game if your editor provides a preview.

Or wait until the site deploys later.

Make sure the player color changed.

---

## Commit Your Change

Use a commit message like:

```text
Fixes #2 - change player color
```

Then click:

```text
Commit & Push
```

---

# Step 9: Complete Issue 3

## Issue 3: Add a Win Message

### Goal

Show a message when the player wins the game.

Example:

```text
You Win!
```

or:

```text
Great job, Alex!
```

---

## Steps

Open:

```text
maze-runner.html
```

Find the part of the code that checks if the player reached the goal.

Look for words like:

```text
win
goal
finish
complete
```

Add or update the win message.

Example:

```javascript
alert("You Win!");
```

Or, if the game already has a message area, update the message text.

---

## Commit Your Change

Use a commit message like:

```text
Fixes #3 - add win message
```

Then click:

```text
Commit & Push
```

---

# Step 10: Complete Issue 4

## Issue 4: Link Game from Homepage

### Goal

Make sure the homepage links to your game.

---

## Steps

Open:

```text
index.html
```

Find the button or link that opens the game.

It may look like this:

```html
<a href="maze-runner.html">Play the Game</a>
```

Customize the text if you want:

```html
<a href="maze-runner.html">Play My Maze Runner Game</a>
```

Save your changes.

---

## Commit Your Change

Use a commit message like:

```text
Fixes #4 - update homepage game link
```

Then click:

```text
Commit & Push
```

---

# Step 11: Development with AI Copilot

Your instructor will demonstrate how AI can help with software development.

You may not have Copilot access today, and that is okay.

The goal is to see how AI can help developers:

- Understand code
- Suggest changes
- Generate ideas
- Fix bugs
- Add new features

Important:

AI does not replace the developer.

The developer still needs to:

- Ask good questions
- Review the code
- Test the result
- Decide what to keep

---

## Example Copilot Prompts

Your instructor may use prompts like:

```text
Add a countdown timer before the Maze Runner game starts.
```

```text
Add a message when the player reaches the goal.
```

```text
Make the game harder by adding another wall.
```

```text
Explain what this JavaScript function does.
```

---

# Step 12: Test and Deploy Software

Now we will see your code become a live website.

This is where automation comes in.

Your repository includes a GitHub Actions workflow.

The workflow is stored here:

```text
.github/workflows/deploy.yml
```

That file tells GitHub how to publish your website.

---

# Step 13: Understand the Deployment Pipeline

When you commit and push code, GitHub can run automation.

The flow looks like this:

```text
Code is pushed → GitHub Actions starts → Site is prepared → GitHub Pages deploys
```

This is called a deployment pipeline.

A pipeline is automation that helps move software from code to a working product.

---

# Step 14: Open the Actions Tab

Go to your GitHub repository.

Click:

```text
Actions
```

You should see a workflow running or completed.

Look for something like:

```text
Deploy to GitHub Pages
```

Click into the workflow to watch the steps.

You may see steps like:

```text
Checkout
Setup Pages
Upload artifact
Deploy
```

---

# Step 15: Enable GitHub Pages

Go to:

```text
Settings → Pages
```

Under Source, choose:

```text
GitHub Actions
```

Save the setting.

After the workflow runs, GitHub will give you a live site URL.

It will look something like this:

```text
https://your-username.github.io/your-repo-name/
```

Open the link.

You should see your website.

Click the game button.

You should see your Maze Runner game.

---

# Step 16: Complete Issue 5

## Issue 5: Update the README

### Goal

Document your project so others know what it is.

---

## Steps

Open:

```text
README.md
```

Add or update the following sections:

```markdown
## About This Project

This is my Maze Runner game built during the Modern Software Creation workshop.

## How to Play

Use the arrow keys to move through the maze.

Reach the goal to win.

## Technologies Used

- HTML
- CSS
- JavaScript
- GitHub
- GitHub Actions
- GitHub Pages

## Live Site

Add your GitHub Pages link here.
```

Add your live site URL.

---

## Commit Your Change

Use a commit message like:

```text
Fixes #5 - update project documentation
```

Then click:

```text
Commit & Push
```

---

# Step 17: Review What You Built

Today, you completed a real software workflow.

You:

- Created a project from a template
- Opened code in a browser editor
- Planned work using Issues
- Changed code
- Committed and pushed changes
- Connected commits to Issues
- Used automation with GitHub Actions
- Deployed a live website with GitHub Pages
- Updated documentation

That is modern software creation.

---

# Troubleshooting

## I cannot find the browser editor

Open your repo in GitHub and press:

```text
.
```

If that does not work, change the URL from:

```text
github.com
```

to:

```text
github.dev
```

---

## My workflow did not run

Check:

```text
Actions
```

If workflows are disabled, click:

```text
Enable workflows
```

Then make another commit and push.

---

## My site is not live yet

Check:

```text
Settings → Pages
```

Make sure Source is set to:

```text
GitHub Actions
```

Then check the Actions tab and make sure the deployment completed successfully.

---

## My change did not show up

Try these steps:

1. Refresh the page
2. Wait one minute
3. Check the Actions tab
4. Make sure the workflow completed
5. Open the live site again

---

## My Issue did not close

Make sure your commit message included the correct Issue number.

Example:

```text
Fixes #2 - change player color
```

The number must match the Issue number.

---

# Key Terms

## Repository

A repository, or repo, is where your project files live.

## Issue

An Issue is a task or problem to work on.

## Code

Code is the instructions that tell software what to do.

## Commit

A commit saves a change to your project history.

## Push

A push sends your changes to GitHub.

## GitHub Actions

GitHub Actions is automation that can build, test, or deploy your project.

## GitHub Pages

GitHub Pages publishes your website online.

## README

A README explains what your project is and how to use it.

## DevOps

DevOps is a modern way to plan, build, test, deploy, and improve software.

## CI/CD

CI/CD means automation that helps software get tested and delivered faster.

A simple way to remember it:

```text
Commit code → Automation runs → Software gets delivered
```

---

# Final Reflection

Answer these questions:

1. What did you change in your game?
2. What was your favorite part of the workshop?
3. What was confusing?
4. What would you add to the game next?
5. How could automation help a real software team?

---

# What You Did Today

You planned real work.

You wrote and changed code.

You used automation.

You launched a live website.

That is how real software is built today.

---

# Cornerstone Tech Academy

This workshop is just the beginning.

At **Cornerstone Tech Academy**, students continue learning how to:

- Build real software projects
- Use modern developer tools
- Understand the full software delivery process
- Explore technology career paths
- Grow skills with purpose and direction

Today you built something real.

At CTA, you learn how to keep building.

---

# Keep Building

Try one of these next:

- Add a timer to the game
- Add levels
- Add a start screen
- Add a score
- Change the maze
- Add sound effects
- Improve the homepage
- Add screenshots to the README
- Share your site with family

Software improves one change at a time.

Keep going.

# Tokens and the Context Window: an Interactive 45-Minute Lesson

An interactive web lesson that teaches **Tokenization and Context Window Management**. It was made for the Instructional Designer Intern (AI Courses) task.

**Live version:** https://YOUR-USERNAME.github.io/token-lesson/

## How to open it

**Option 1: online.** Open the live link above in any browser.

**Option 2: on your computer.**
1. Download this repository (green **Code** button, then **Download ZIP**) and unzip it.
2. Double-click `index.html`.

No installation, internet connection, or build step is needed. It is a single HTML file with no outside libraries.

## What learners will be able to do

- Explain what a token is and why text is split into tokens.
- Explain what a context window is and what happens when it fills up.
- Choose a way to keep important information inside a token budget.

## What is inside (about 45 minutes)

| Time | Section | Activity |
|------|---------|----------|
| 3 min | Hook | Think about a time a chatbot "forgot" something |
| 10 min | Token splitter | Type text and see it cut into tokens, with live counts |
| 10 min | Context window | Fill a chat window and watch old messages drop out |
| 10 min | Challenge | Save a support chat within a token budget |
| 5 min | Building real apps | Five practical tips for AI applications |
| 7 min | Knowledge check | 5-question quiz with explanations |

The page works for **self-learners** (follow the timing table) and **instructor-led sessions** (see the instructor notes on the page).

## Important note on accuracy

The token splitter is a **simplified demo** built to show the idea. Real models use learned methods such as byte-pair encoding, so exact splits and counts differ. Learners are pointed to a real tokenizer to compare. The context window logic (keep the newest messages that fit, leave out older ones) matches how many chat apps trim history.

## Built with

Plain HTML, CSS, and JavaScript. All of the code is in `index.html`, with comments explaining each step.

## Files

- `index.html`: the whole lesson
- `README.md`: this file

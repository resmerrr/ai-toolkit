# Workflow Discovery Interview

**What it does:** the AI interviews you about your work and finds one recurring task that is worth turning into an AI workflow or automation. At the end it fills in a workflow worksheet.

**Use it when:** you want to use AI at work but don't know where to start, or a team says "we can't think of anything to automate".

**Works in:** ChatGPT and Claude.

## How to use

1. Start a new chat.
2. Paste the prompt below and send it.
3. Answer with real examples from the last week or two.
4. Use the finished worksheet to build and test the workflow.

## Prompt

```
Help me find one task in my work that is worth turning into an AI workflow or automation. Interview me, then fill in a workflow worksheet.

Ask me one question at a time and wait for my answer. Use simple language. If an answer is vague, ask for a real recent example. Let me skip questions.

Part 1: Find candidates
1. What is my role and what does a normal work week look like?
2. Which tasks repeat every day, week or month?
3. Which tasks involve a lot of writing, copying, comparing or moving information between places?
4. Which task did I find most boring or slow recently? Describe the last time I did it.

From my answers, suggest up to 3 candidate tasks. For each, say in one line why it fits. Prefer tasks that are frequent, low-risk and have an output that is easy to check. Let me choose one.

Part 2: Describe the chosen task
Ask about: who does it, who uses the result, what starts it (the trigger), what inputs it needs, what the output looks like, how often it happens, how long it takes now, what can go wrong, and how the result is checked.

Part 3: Fill in the worksheet
Write the worksheet with these fields:
- Task name
- Owner and users
- Trigger
- Inputs
- Output
- Frequency and current time spent
- Value if it works
- Risks and what must never go wrong
- What AI does / what a human does
- How the result is reviewed
- 2–3 test cases (real example inputs and the expected output)

Rules:
- Use only what I tell you. Mark your own assumptions clearly.
- Be honest if a task is a bad fit for AI, and say why.
- Note whether the task needs a simple prompt I run myself, or a real automation that runs on its own when something happens.
- End with one concrete next action.
```

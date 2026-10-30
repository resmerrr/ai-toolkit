# Custom Instructions Interview Prompt

A ready-to-paste prompt that makes ChatGPT interview you and then write your **Custom Instructions**: two short text blocks that tell ChatGPT who you are and how you want it to answer.

The AI asks one question at a time, uses what it already remembers about you, and writes two blocks that each fit the **1 500-character** limit.

---

## How to use it in ChatGPT

### Part 1: Run the interview

1. Open [chatgpt.com](https://chatgpt.com) and start a **new chat**.
2. Copy the whole prompt from the [Prompt](#prompt) section below.
3. Paste it into the chat and send it.
4. Answer the questions one at a time. Type **"skip"** to skip a question.
5. When you get the draft, check both blocks. Ask for changes until they are right.

### Part 2: Paste the result into settings

1. Click your **profile picture or name** in the bottom-left corner.
2. Open **Settings → Personalization**.
3. Paste **block 1 ("My work background")** into the **"More about you"** field.
4. Paste **block 2 ("How I want you to respond")** into the **"Custom instructions"** field.
5. Click **Save**.
6. Start a **new chat** to test it. Instructions apply to new chats, not to chats that are already open.

> **Check the end of each block after pasting.** If a block is longer than the limit, the field cuts off the rest without warning. The last line of each block should still be visible.

*ChatGPT renames its settings from time to time. If a field name differs, look for the field about **you** (block 1) and the field about **how ChatGPT should respond** (block 2).*

---

## Prompt

```
Help me write short and clear Custom Instructions that fit my work and preferences.

Ask me one question at a time and wait for my answer before you continue. Use simple language. If my answer is too general, ask one follow-up question. Let me skip any question.

Before each question, check your memory and our past chats. If you already know the answer, suggest it and ask me only to confirm or correct it. If I have already answered, do not ask again. If you cannot see any memory, just ask all the questions.

Focus on information and preferences that will help in future conversations. I don't need to share confidential information.

Ask these questions in this order, one at a time:

1. Which language should we use for this interview, and which language should the final Custom Instructions and your future answers use by default? If you already know this, confirm it with me.
2. What are my main roles (for example study, work, business) and what are the main tasks in each role?
3. Who usually reads or uses what I create with AI, for example clients, colleagues, managers, teachers or students?
4. What are 2–3 recurring tasks where I want AI help the most? If needed, ask me for one typical example.
5. What lasting background information would help you give more relevant answers, for example my field, my knowledge level in important topics, or tools I use regularly?
6. Which local conventions should you use by default: currency, units of measurement, date format, and how to write large amounts and thousands separators?
7. What tone, length and level of detail should your answers have, and when can this change (for example formal documents and emails vs everyday questions)?
8. What formatting do I prefer, for example numbered steps, bold and italics, how deep lists can go, and splitting long tasks into parts?
9. What file formats do I want by default, and should you always also answer in the chat?
10. When information is missing, when should you ask a follow-up question and when can you continue with a clearly stated assumption?
11. How should you help me evaluate ideas and factual claims, for example by pointing out weak assumptions, explaining uncertainty, recommending one option, or adding sources to important claims?
12. Should you suggest improvements or alternatives on your own, and should you explain terms and my mistakes?
13. When should you use my background information, and when not?
14. What must you never do without my permission?
15. Give me one example of an answer I did not like, and explain what I would have preferred.

After the interview:

* Use only information I have given or confirmed. Do not invent my preferences or add general rules just to fill space.
* Keep lasting background information and useful default preferences. Briefly mark which information would fit better in a specific chat or project instead.
* If my answers contain important conflicts, resolve them with follow-up questions, one at a time.
* Turn my answers into clear, practical instructions. Do not write a summary of the conversation or a biography.
* Write two separate, ready-to-paste text blocks in first person, in the language I chose in question 1:
  - Block 1 with the heading "My work background"
  - Block 2 with the heading "How I want you to respond"
* Each block must be 1 500 characters or fewer, including spaces and the heading. Count the characters exactly and show the count under each block. If a block is too long, shorten the wording first. Never drop a rule silently: if something must be removed, tell me what and let me choose.
* Write work preferences so they apply in work conversations, and leave room for me to ask for a different approach on any task.
* Show me the draft and ask whether anything needs fixing before I copy it into my settings.

Start with the first question.
```

---

## Does this work in Claude?

**Yes, the interview prompt works in Claude as it is.** Only the place where you paste the result is different, because Claude has a different settings layout.

### Where to paste the result in Claude

1. Click your **initials** in the bottom-left corner.
2. Open **Settings → Your Claude**. *(Older layout: Settings → Account.)*
3. Find the **"Instructions"** field. *(Older layout: "Instructions for Claude".)*
4. Paste **both blocks into this one field**, block 1 first, then block 2.
5. Save and start a new chat.

### How Claude differs from ChatGPT

| | ChatGPT | Claude |
|---|---|---|
| **Fields** | Two: about you + how to respond | One "Instructions" field for everything |
| **Character limit** | 1 500 per field (some paid plans: higher) | No limit stated in Claude's help center |
| **Memory** | Remembers details from chats | Also builds memory from chats; you can view and edit it in Settings → Your Claude |
| **Per-project rules** | Project instructions | Project instructions |

### Moving your ChatGPT memory to Claude

Claude can import memory from other assistants:

1. Ask ChatGPT to list all your stored memories in one code block. Remove anything sensitive.
2. In Claude, open **Settings → Your Claude** and choose **"Start import"**.
3. Paste the list and click **"Add to memory"**.

*Claude's memory focuses on work topics, so it may not keep unrelated personal details. Imports are experimental and may not keep every entry.*

---

## Sources

- [How to add custom instructions in ChatGPT (Guideflow, updated 11.02.2026)](https://www.guideflow.com/tutorial/how-to-add-custom-instructions-in-chatgpt)
- [Understanding Claude's personalization features (Claude Help Center)](https://support.claude.com/en/articles/10185728-understanding-claude-s-personalization-features)
- [Importing and exporting your memory from Claude (Claude Help Center)](https://support.claude.com/en/articles/12123587-importing-and-exporting-your-memory-from-claude)

# Custom Instructions Interview Prompt

A ready-to-paste prompt that makes ChatGPT or Claude interview you and then write your **Custom Instructions**: short text that tells the AI who you are and how you want it to answer.

The AI asks 13 short questions, one at a time, uses what it already remembers about you, and writes text that fits the settings of the tool you chose.

---

## How to use it in ChatGPT

### Part 1: Run the interview

1. Open [chatgpt.com](https://chatgpt.com) and start a **new chat**.
2. Copy the whole prompt from the [Prompt](#prompt) section below.
3. Paste it into the chat and send it.
4. Answer the questions one at a time. Type **"skip"** to skip a question or any part of it.
5. When you get the draft, check both blocks. Ask for changes until they are right.

### Part 2: Paste the result into settings

1. Click your **profile picture or name** in the bottom-left corner.
2. Open **Settings → Personalization**.
3. Paste **block 1 ("My work background")** into the **"More about you"** field.
4. Paste **block 2 ("How I want you to respond")** into the **"Custom instructions"** field.
5. Click **Save**. The instructions apply to all chats right away.

> **Check the end of each block after pasting.** If a block is longer than the limit, the field cuts off the rest. The last line of each block should still be visible.

*ChatGPT renames its settings from time to time. If a field name differs, look for the field about **you** (block 1) and the field about **how ChatGPT should respond** (block 2).*

> **Check your Personality and Characteristics settings too.** In the same Personalization page, ChatGPT has sliders for warmth, emojis, headers and lists. If they disagree with your instructions (for example "more emojis" vs "emojis only as signals"), set them to default so they don't override your text.

---

## Prompt

```
Help me write short and clear Custom Instructions that fit my work and preferences.

Ask me one question at a time and wait for my answer before you continue. Use simple language. If my answer is too general, ask one follow-up question. Let me skip any question, or any part of a question.

Before each question, check your memory and our past chats. If you already know the answer, suggest it and ask me only to confirm or correct it. If I have already answered, do not ask again. If you cannot see any memory, just ask all the questions.

Focus on information and preferences that will help in future conversations. I don't need to share confidential information.

Ask these questions in this order, one at a time:

1. Which AI tool are these Custom Instructions for (for example ChatGPT or Claude)? Which language do I want to use in general: for this interview, for the final Custom Instructions and for your future answers?
2. What should you call me, what are my main roles (for example study, work, business) and what are the main tasks in each role?
3. What are 2–3 recurring tasks where I want AI help the most, and who usually reads or uses the results (for example clients, colleagues, managers, teachers)? If needed, ask me for one typical example.
4. What lasting background information would help you give more relevant answers, for example my field, my knowledge level in important topics, or tools I use regularly?
5. Which local conventions should you use by default: currency, units of measurement, date format, and how to write large amounts and thousands separators?
6. What tone, length and level of detail should your answers have, and when can this change (for example formal documents and emails vs everyday questions)?
7. How should your answers start and end? For example: answer first with no introduction, and end with a short summary, a brief explanation of why, one next step, or nothing. In long tasks with many steps, should you show progress (for example "Step 3/5 done. Next: …") and give time estimates?
8. What formatting do I prefer, for example numbered steps, bold and italics, how deep lists can go, splitting long tasks into parts, and whether to use emojis (for example ✅ ⚠️) only as signals or not at all?
9. What file formats do I want by default, and should you always also answer in the chat?
10. When should you check with me first: when information is missing, when can you continue with a clearly stated assumption, and what must you never do without my permission?
11. How should you help me evaluate ideas and factual claims, for example by pointing out weak assumptions, explaining uncertainty, recommending one option, or adding sources to important claims? Should you suggest improvements on your own, explain terms and my mistakes, and when something fails, explain the cause and the fix?
12. When should you use my background information, and what should stay out of instructions that apply to every chat (for example health, diet or projects that change often)?
13. Give me one example of an answer I did not like, and explain what I would have preferred.

After the interview:

* Use only information I have given or confirmed. Do not invent my preferences or add general rules just to fill space.
* Keep lasting background information and useful default preferences. Briefly mark which information would fit better in a specific chat or project instead.
* If my answers contain important conflicts, resolve them with follow-up questions, one at a time.
* Turn my answers into clear, practical instructions. Do not write a summary of the conversation or a biography.
* Write everything in first person, in the language I chose in question 1. Treat that language as my default for all answers, and include a clear line saying so.
* Use neutral words that work in the tool I chose (for example "file" instead of tool-specific names like "canvas" or "artifact").
* Match the format to the tool I chose in question 1:
  - ChatGPT: two separate, ready-to-paste text blocks. Block 1 with the heading "My work background" and Block 2 with the heading "How I want you to respond" (translate the headings into my language). Each block must be 1 500 characters or fewer, including spaces and the heading.
  - Claude: one ready-to-paste text for the single "Instructions" field, with the same two headings. Keep it 3 000 characters or fewer.
  - Another tool: use that tool's current fields and character limits. If you are not sure what they are, ask me.
* Count the characters exactly and show the count under each block. If a block is too long, shorten the wording first. Never drop a rule silently: if something must be removed, tell me what and let me choose.
* Write work preferences so they apply in work conversations, and leave room for me to ask for a different approach on any task.
* Show me the draft and ask whether anything needs fixing before I copy it into my settings.

Start with the first question.
```

---

## Using it in Claude

**The same prompt works in Claude.** Answer "Claude" to question 1, and you get one text instead of two blocks.

### Where to paste the result in Claude

1. Click your **initials** in the bottom-left corner.
2. Open **Settings → Your Claude**. *(Older layout: Settings → Account.)*
3. Find the **"Instructions"** field. *(Older layout: "Instructions for Claude".)*
4. Paste the text and save. It applies to all your conversations.

### How Claude differs from ChatGPT

| | ChatGPT | Claude |
|---|---|---|
| **Fields** | Two: about you + how to respond | One "Instructions" field for everything |
| **Character limit** | Free and Go: 1 500. Plus, Pro, Business, Enterprise, Education: 5 000 | No limit stated in Claude's help center |
| **Style sliders** | Personality and Characteristics (warmth, emojis, headers) | None; skills can change tone and format on demand |
| **Memory** | Remembers details from chats | Also builds memory from chats; you can view and edit it in Settings → Your Claude |
| **Per-project rules** | Project instructions | Project instructions |

*The prompt keeps ChatGPT blocks at 1 500 characters so they fit every plan. Short instructions are also followed more reliably than long ones.*

### Moving your ChatGPT memory to Claude

Claude can import memory from other assistants:

1. Ask ChatGPT to list all your stored memories in one code block. Remove anything sensitive.
2. In Claude, open **Settings → Your Claude** and choose **"Start import"**.
3. Paste the list and click **"Add to memory"**.

*Claude's memory focuses on work topics, so it may not keep unrelated personal details. Imports are experimental and may not keep every entry.*

---

## Sources

- [ChatGPT Custom Instructions (OpenAI Help Center)](https://help.openai.com/en/articles/8096356-chatgpt-custom-instructions)
- [ChatGPT release notes (OpenAI Help Center)](https://help.openai.com/en/articles/6825453-custom-instructions)
- [Characteristics in ChatGPT (OpenAI Help Center)](https://help.openai.com/en/articles/20001038-characteristics-in-chatgpt)
- [Understanding Claude's personalization features (Claude Help Center)](https://support.claude.com/en/articles/10185728-understanding-claude-s-personalization-features)
- [Import and export your memory from Claude (Claude Help Center)](https://support.claude.com/en/articles/12123587-import-and-export-your-memory-from-claude)

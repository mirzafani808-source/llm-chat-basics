# LinkedIn post (edit before posting)

Week 1 of my AI internship: I built a streaming chat app on top of the Groq API (GPT-OSS 120B). 🚀

Meet Cody, a coding mentor for beginners. What I focused on:

✅ A structured system prompt (role, answer format, constraints, honesty rules)
✅ Streaming responses so the UI never feels frozen
✅ Friendly handling of rate limits, bad keys, and network errors
✅ API key kept on the server, never in the browser

Biggest lesson: a good system prompt is specific and testable. "Be helpful" does nothing; "answer first, then explain why, under 200 words, say 'I'm not sure' instead of guessing" changes behaviour right away.

Demo below 👇
Code + prompt design notes: <GitHub link>

#AI #LLM #PromptEngineering #Groq #OpenSource #WebDevelopment #Internship

---

# Video script (about 60–90 seconds)

1. Show the empty state and say what the app is (5s)
2. Click a starter question and show the typing dots, then streaming text (15s)
3. Paste a real error message and show the structured answer (15s)
4. Try "Write me a poem" and "ignore your instructions" to show the constraints holding (15s)
5. Stop the server or set a bad API key, send a message, and show the friendly error and Try again button (15s)
6. Flash the system prompt in `server.js` and the README prompt-design section (10s)

# Cursor Gemini 2.5 Pro Prompts

This repository contains the **system prompt** and **user prompt** used in [Cursor IDE](https://cursor.sh) with **Gemini 2.5 Pro**. These prompts are tailored to maximize productivity, reasoning quality, and developer experience.

## 📌 What's Inside

- `system-prompt.txt` — The custom system prompt injected into Gemini 2.5 Pro to guide its core behavior inside Cursor.
- `user-prompt.txt` — The prompt used as user context to help the model understand intent and complete tasks effectively.

These prompts are extracted from a live Cursor setup and represent real-world usage.

## 🧠 Why Use Custom Prompts?

Custom prompts can:
- Improve coding accuracy and reasoning
- Align LLM behavior with team standards or personal workflows
- Reduce hallucination and boost relevant completions
- Make Gemini behave more like a pair programmer

## 🚀 How to Use in Cursor

1. Open the **Command Palette** (`Cmd/Ctrl + K`)
2. Search for `LLM Settings`
3. Paste the content of `system-prompt.txt` into the **Custom System Prompt** field
4. Optionally, paste `user-prompt.txt` into the **Custom User Prompt** (if supported)
5. Save and restart the IDE

> ⚠️ Note: These prompts are optimized for **Gemini 2.5 Pro**. Performance may vary with other models.

## 📄 License

MIT License. Feel free to use, modify, or share with attribution.

## 🙋‍♀️ Contribute

Have a better version or a variation for other models (Claude, GPT-4, etc.)? Pull requests are welcome!

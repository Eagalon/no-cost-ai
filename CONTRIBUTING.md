# Contributing to **no-cost-ai**

Thanks for helping keep the list fresh!  
All contributions are welcome, a quick typo fix, a new free AI site, or a heads-up that something broke.

---

## 1. Quick workflow

1. **Fork** the repository and create a branch (`git checkout -b my-update`).
2. Edit **README.md** (it’s the only file you need to touch).
3. Commit with a descriptive message, e.g.  

`Add: ExampleChat (GPT-4o, 25 messages/day)`

4. **Open a Pull Request** to `main`.  
Our CI will run a link check; if anything fails you’ll see it in the PR.

That’s it — we’ll review ASAP!

---

## 2. Adding a new free service

| Column          | What to put in it | Example                           |
|-----------------|-------------------|-----------------------------------|
| **Name**        | Short, plain text | `ExampleChat`                     |
| **URL**         | Full https link   | `https://example.com/chat`        |
| **Models**      | Main LLM(s) offered | `GPT-4o` or `Claude 4 Haiku`   |
| **Tokens/Day**  | Free quota (or `∞`) | `25 messages / 24 h`            |
| **Sign-up?**    | `yes` or `no`     | `no`                              |
| **Notes**       | Cooldown, jailbreak status, etc. | `2-hour cooldown` |

*Add the row in the correct section*  
- **No Sign-Up Needed** at the top  
- **Sign-Up Required** further down  

Keep each section in simple **A→Z order** by site name.

---

## 3. Fixing or removing a listing

- **Broken link / service gone?**  
Update the URL or delete the row. In your PR description tell us what changed (404, paywall, model removed, …).  
- **Quota or model changed?**  
Edit the relevant cells and explain the source (screenshot, blog post, etc.).

---

## 4. Opening an Issue instead of a PR

If you’re not comfortable editing Markdown, open an **Issue**:

- **“Broken link”** include the site name, current URL and error (e.g. 404).  
- **“New site suggestion”** give us the six data points listed above.  
- Anything else (questions, ideas) just be clear and concise.

---

## 5. Style & etiquette

- One logical change per PR makes review faster.  
- Be respectful; this is a volunteer list.  
- No affiliate links, paywalled APIs or spam.

Happy listing!📓
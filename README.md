# Docusaurus-setup

---


---

## **Step 1: Wait for Book Title Announcement**

* **Date & Time:** Wednesday, Dec 3rd at 8 PM
* Book title milne ke baad, aap apna project start karenge.
* Ye book title **specifications generate karne** aur **AI content create karne** me use hogi.

---

## **Step 2: Generate Specs using Spec-Kit Plus**

1. Claude Code aur Spec-Kit Plus setup ke baad:

   * `specify init` → New spec folder create kare.
   * `specify generate` → Book ke liye specifications create kare.
   * Specs will include:

     * Chapters
     * Subtopics
     * Target audience
     * Tone & style

**Tip:** Agar aap chahein, subagents ko use karke reusable intelligence create kar sakte hain jo future ke projects me reuse hoga.

---

## **Step 3: Create AI-Generated Book Content**

1. **Docusaurus Setup:**

   ```bash
   npx create-docusaurus@latest my-book classic
   cd my-book
   npm install
   ```

2. **Content Generation:**

   * Claude Code + Spec-Kit → Generate chapter content.
   * Save content as Markdown (`.md`) files in `/docs` folder.
   * Example:

     ```
     /docs
       /chapter1.md
       /chapter2.md
     ```

3. **Preview Book Locally:**

   ```bash
   npm run start
   ```

   * Browser me book check karo, chapters aur formatting sahi hain ya nahi.

---

## **Step 4: Integrate RAG Chatbot**

1. **Qdrant Vector DB Setup (Free Tier)**

   * Store embeddings of book text for retrieval.
   * Example: Python + OpenAI embeddings → Qdrant

2. **ChatKit Integration**

   * RAG chatbot build karo:

     * User text select kare → chatbot usi text ke context me answer de.
   * Use FastAPI for backend:

     ```python
     from fastapi import FastAPI
     app = FastAPI()
     # Add endpoints to query Qdrant and ChatKit
     ```

3. **Embed Chatbot in Docusaurus**

   * Use React component inside book pages.
   * Example:

     ```jsx
     import Chatbot from './Chatbot';
     <Chatbot />
     ```

---

## **Step 5: Bonus – Subagents & Skills**

* Create reusable intelligence:

  * **Subagent:** Small agent to handle specific tasks.
  * **Skill:** Predefined intelligence (e.g., summarization, quiz generator)
* Ye reusable hoga aur aap future projects me easily use karenge.

---

## **Step 6: Deployment**

1. **GitHub Pages**

   ```bash
   GIT_USER=<your_github_username> USE_SSH=true npm run deploy
   ```
2. **Vercel (Optional)**

   * Simple drag & drop deploy from repo.

---

## **Step 7: Submission**

1. **GitHub URL:** Codebase
2. **GitHub Pages/Vercel URL:** Published book
3. **YouTube Demo Video** → Short presentation of:

   * Book content
   * Chatbot working
   * Subagents/Skills (bonus marks)

**Submission Form:** [Google Form](https://forms.gle/VPzhForXoxxULkHm6)

---

## **Step 8: Zoom Review**

* **Date & Time:** Monday, Dec 8 @ 6 PM
* Panel will check your project live.

---

✅ **Summary / Timeline**

| Step | Task                     | Tools                                                      |
| ---- | ------------------------ | ---------------------------------------------------------- |
| 0    | Prepare tools & accounts | Claude Code, Spec-Kit, Docusaurus, ChatKit, Qdrant, GitHub |
| 1    | Wait for book title      | WhatsApp Group                                             |
| 2    | Generate Specs           | Spec-Kit Plus, Claude Code                                 |
| 3    | Create Book              | Docusaurus, Markdown, Claude Code                          |
| 4    | Integrate Chatbot        | ChatKit, FastAPI, Qdrant                                   |
| 5    | Bonus                    | Subagents & Skills                                         |
| 6    | Deploy                   | GitHub Pages / Vercel                                      |
| 7    | Submission               | Google Form, YouTube demo                                  |
| 8    | Zoom Review              | Showcase project                                           |

---
## **Step 0: Preparation (Before Hackathon Day)**

1. **Tools & Accounts ready karo:**

   * **Claude Code Router** → Is se aap free LLM model use kar sakte hain.

     * GitHub: [Claude Code Router](https://github.com/musistudio/claude-code-router)
     * Setup guide: [Free Claude Setup](https://ai-native.panaversity.org/docs/AI-Tool-Landscape/claude-code-features-and-workflows/free-claude-setup)
   * **Spec-Kit Plus** → Ye aapke project specifications generate karega.
   * **Docusaurus 3.9** → Book create aur deploy karne ke liye.

     * [Docusaurus](https://docusaurus.io/)
   * **OpenAI ChatKit** → RAG Chatbot integration ke liye.

     * [ChatKit Python SDK](https://github.com/openai/chatkit-python/)
   * **Qdrant Cloud Free Tier** → RAG ke liye vector database.
   * **GitHub Account** → Codebase aur deployment ke liye.

2. **Join WhatsApp Group** → Technical updates aur book title ke liye.
   Link: [Friday Evening Students](https://chat.whatsapp.com/GfvAEUGGBbsBJL4W25uKpc)

3. **Reading & Videos:**

   * Claude Code docs: [Subagents & Skills](https://code.claude.com/docs/en/overview)
   * Lectures: [YouTube Playlist](https://youtube.com/playlist?list=PLY-fvIYzjXhcyAHJE9IhNHNxZWdhReIMf&si=Q1GZWX1sYUsnqQdY)


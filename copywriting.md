

# XpressLab for Copywriters

Welcome to XpressLab! As a copywriter, your role is to transform placeholder text (Lorem Ipsum) into compelling, market-driven content. Follow this guide step-by-step to successfully contribute and showcase your skills.

---

## Step 1: Organize Your Workspace & Apply the 5S Method

Before starting, clear your workspace to ensure productivity and efficiency. We recommend using the **5S Method** to organize your environment:

- **Sort, Set in Order, Shine, Standardize, Sustain**
- [👉 Click here for 5S Training](https://www.beltcourse.com/blog/how-to-correctly-apply-5s-in-an-office-environment)

---

## Step 2: Find Lorem Ipsum Content in Our GitHub Organizations

Browse through the repositories of our GitHub organizations listed below to find projects containing placeholder text ("Lorem Ipsum") that need your copywriting skills. Click each link to directly access the organization's repositories page (**Ctrl+Click** to open links in a new tab):

- [World Enterprise](https://github.com/worldenterprisegroup?tab=repositories) – Graphics, Copywriting, & Website Design for Startups
- [Note Hive](https://github.com/Note-Hive?tab=repositories) – Documentation, Grants, Guides, Handbooks, and Writing Projects
- [United Home](https://github.com/United-Home?tab=repositories) – Home, Lifestyle, and Architectural Projects
- [HardMagic](https://github.com/HardMagic?tab=repositories) – Design, Ideation, Storytelling, Branding, Visionary, Futurism, Creative Direction
- [Tao Learning Institute](https://github.com/TaoLearning?tab=repositories) – Non-Profit Organization focused on STEAM Literacy, Learning, & Development
- [INSTAR Lab Inc](https://github.com/INSTARLab?tab=repositories) – Scientific Research Institute with projects in Quantum Research, Artificial Intelligence, and the Future of Work
- [Source Now](https://github.com/Source-Now?tab=repositories) – Data Science, Data Analysis, Forensics, Data Research
- [SILK Corp](https://github.com/WorldEnterpriseGroup?tab=repositories&q=silkcorp&type=&language=&sort=) – Public Benefit Corporation focused on Women Empowerment, DE&I, Homesteading, Health & Wellness Industry
- [SILK Corp Guide](https://github.com/NoteHive/Silk-Corp-Guide) – SILK Corp Franchise Model

Once you identify a repository containing Lorem Ipsum content that you'd like to improve, proceed to the next step.

---

## Step 3: Fork the Repository

Once you've identified a suitable repository with plenty of Lorem Ipsum content:

1. Click the **Fork** button at the top right of the repository page.
2. This will create your own copy of the repository to work on.

---

## Step 4: Open the Repository in VS Code

To quickly begin editing your forked repository:

1. Navigate to your forked repository page on GitHub.
2. Press the **"." (dot)** key on your keyboard while viewing the repository page.
   - This shortcut automatically opens the repository in GitHub's built-in VS Code web editor ([VSCode.dev](https://vscode.dev/)).
3. You can now directly edit files in your browser without downloading or installing additional software.

> **Alternative Method:**  
> If you prefer working locally on your desktop, you can use [GitHub Desktop](https://desktop.github.com/) to clone the repository to your computer and open it with your local installation of VS Code.

---

## Step 5: Open Repository in VS Code & Install Live Server

Open your cloned repository in [Visual Studio Code](https://code.visualstudio.com/).

To preview your changes live, install the **Live Server** extension:

- **Live Server Extension Details:**
  - Name: Live Server
  - Publisher: Ritwick Dey
  - [👉 Install Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

Once installed, right-click your HTML file and select "Open with Live Server" to preview your edits in real-time.

---

Here's your revised **Step 6** with clear instructions about using any GPT model, along with guidance on choosing the best GPT for different copywriting tasks:

---

## Step 6: Rewrite Content Using GPT

You can use **any GPT model or AI copywriting assistant** to rewrite the Lorem Ipsum content. Choose the GPT tool that best suits your specific copywriting task:

- **Entire Page Edits (Generic Copy):**  
  We've had great success (as of March 2025) using **GPT o3-mini** for rewriting entire pages, especially when you need to maintain the integrity and structure of the whole file.

- **Single-Line Edits (High-End Copywriting):**  
  For more targeted, high-quality copywriting changes—such as headlines, taglines, or calls-to-action—we recommend using **GPT 4.5**, as it excels at delivering concise, impactful messaging.

- **Other GPT Tools (e.g., GitHub Copilot):**  
  Feel free to use **GitHub Copilot** or any other GPT-based tool you prefer. Your choice of tool should be based on the best results for your specific task.

### Important Notes:

- **Quality Matters:**  
  Your contributions will be evaluated based on the quality of your content and how closely it aligns with the website's branding, tone, and purpose.

- **Study Copywriting Fundamentals:**  
  If you're new to copywriting or want to further improve your skills, we highly recommend studying general copywriting principles. Understanding the fundamentals will help you effectively guide GPT models to produce better, more targeted results.

### Example Prompt for GPT (fill in the blanks):

When using GPT to rewrite entire pages, use a clear prompt such as:

```
### Role:
You are an expert copywriter tasked with editing HTML code. Your **only** job is to replace placeholder text (such as lorem ipsum or generic filler text) with professional, engaging, SEO-friendly copywriting. You must strictly adhere to the following guidelines:

### Guidelines:
- **Do not alter any HTML elements, tags, attributes, or structure.** Your edits must exclusively involve replacing placeholder text content.
- **Maintain the approximate character count** of the original placeholder text. The provided HTML template has optimized UX/UI; significant deviations in character count could negatively impact the layout or usability.
- **Ensure all copy aligns with SEO best practices:** use relevant keywords, clear language, and appropriate tone.
- **Be brand-aware and trending:** Create engaging, current, and broadly appealing copy that resonates with the largest and most generic audience possible. However, if the user explicitly provides a specific niche audience, override this general rule and cater specifically to the user's provided audience.
- **Follow brand guidelines closely.** If you are unsure about the brand voice, tone, product/service details, target audience, or specific messaging, **ask clarifying questions before proceeding**.

### Workflow:
1. **Review the provided HTML code carefully.**
2. **Identify all placeholder or lorem ipsum text elements.**
3. **If the user has not provided the following business classification codes, ask the user to provide them before proceeding:**
    - **NAICS (North American Industry Classification System)**
    - **SIC (Standard Industrial Classification)**
    - **PSC (Product Service Code)**
    - **SIN (Special Item Number)**
    
    These codes will help you make the most informed decisions around the copy, services, and branding.
    
4. **If necessary, ask additional relevant clarifying questions** to understand the brand, product/service, target audience, voice, tone, and SEO requirements.
5. **Replace placeholder text with appropriate copywriting.**
6. **Double-check your final edits** to ensure no HTML elements or attributes were altered, and character counts remain close to the original.

### Output Format:
- Provide back the **FULL HTML code** with the placeholder text replaced, allowing the user to easily copy/paste your provided HTML to replace the entire original HTML file.
- Do not provide partial HTML or snippets. Always return the entire HTML document exactly as provided, with only the placeholder texts replaced.

### Additional Rules:
- If the provided HTML or instructions are unclear, incomplete, or ambiguous, always ask clarifying questions first before proceeding.
- If the user explicitly requests a specific tone, style, or niche audience, prioritize their instructions over the general audience rule.
- Always ensure you have the necessary business classification codes (NAICS, SIC, PSC, SIN) provided by the user before proceeding. If these codes are missing, explicitly request them from the user to ensure your copywriting aligns precisely with the brand's industry and services.

---

**Go ahead and edit the provided HTML code, or ask clarifying questions first if needed.**
```

Once GPT generates the new copy, carefully copy the entire response and paste it back into your HTML file, replacing the original Lorem Ipsum or placeholder content.

---

## Step 7: Paste GPT Response Back into VS Code

After GPT generates the new copy, carefully copy the entire response and paste it back into your HTML file in VS Code, replacing the original Lorem Ipsum content.

---

## Step 8: Check Your Work

Use the Live Server preview to ensure:

- All HTML elements remain intact.
- The new copy is engaging, clear, and appropriate for marketing.
- The page looks professional and polished.

---

## Step 9: Commit and Save Your Changes

In VS Code:

1. Click the **Source Control** icon (or press `Ctrl+Shift+G`).
2. Enter a clear commit message describing your changes (e.g., "Updated marketing copy for homepage").
3. Click **Commit** to save your changes.

---

## Step 10: Submit a Pull Request (PR)

Finally, submit your changes back to the original repository:

1. Go to your forked repository on GitHub.
2. Click the **Pull Request** button.
3. Clearly summarize your changes in the PR description. You may use GPT to help you write a concise summary of the improvements made.
4. Submit your Pull Request for review.

---

🎉 **Congratulations!** You've successfully contributed as a copywriter using XpressLab. Your work will now be reviewed, and feedback or approval will follow shortly.

## Want to Improve Your Copywriting & Content Creation Skills?

If you're interested in further developing your skills to become an expert content creator, we offer foundational training videos covering HTML basics, copywriting fundamentals, and content creation principles.

- 📺 **General Copywriting & Content Creation Training (2020):** [https://notehive.org](https://notehive.org)

Additionally, for more collaborative learning and ongoing support, join our community at [Curiosity Hive](https://curiosityhive.org).

Happy Writing! ✍️

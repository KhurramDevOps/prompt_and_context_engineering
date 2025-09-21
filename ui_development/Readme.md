# UI Development by Prompting

[Watch: Lovable FULL Tutorial - For COMPLETE Beginners (No Experience Needed)](https://www.youtube.com/watch?v=YLjopoEnPi8)

Watch this Video and Tutorial based on this tutorial is also included below.

[Build Ai-powered Prompt Engineering Projects with AI](https://lovable.dev/how-to/ai-and-machine-learning/ai-powered-prompt-engineering)

[The Lovable Prompting Bible](https://lovable.dev/blog/2025-01-16-lovable-prompting-handbook)

## Lovable AI — A Complete, Professional, Step-by-Step Tutorial

This tutorial distills the full workflow shown in the provided [video](https://www.youtube.com/watch?v=YLjopoEnPi8) into a crisp, repeatable guide—from your first prompt to a deployed full-stack app with authentication, data storage, version control, and UI polish.

---

## 1) What Lovable Is (and why it’s useful)

* **AI app builder** that can generate full-stack web apps from natural-language prompts.
* **No coding required**, but you can edit/export code if you want (the in-editor code browser is a **paid** feature).
* Works best when you **build in small steps** and iterate.
* Supports **importing Figma**, **attaching images** as design references, and **remixing** community projects.

> Credits: It’s free to start with daily credits. Each action consumes credits; bigger builds cost more than small edits.

---

## 2) Get Set Up

1. Go to **lovable.dev** and create/sign in to your account.
2. Confirm your **credit balance**; you’ll accrue more daily.
3. (Optional) Upgrade if you need private projects or the built-in **code browser**.

---

## 3) Plan First, Then Prompt

Lovable rewards clarity. Before you start, outline:

* **What you’re building** (MVP scope).
* **Pages & features** (list them).
* **Visual style** (colors, tone).
* **Future steps** (add later, not all at once).

**Example MVP** (from the video): a **Macro Calculator** (calories/protein/fat targets), later expanded into a fitness tracker.

**Initial prompt (sample):**

> “Create a simple macro-tracking app. Users enter gender, age, height, weight, goal (lose/maintain/gain), and activity level. Recommend daily calories, protein, fat, etc. Use a clean UI with an **orange + black** theme. Keep it simple; we’ll add features later.”

Press **Enter** to generate.

---

## 4) Understand the Interface

* **Left panel**: your conversation and controls with Lovable.

  * **Default mode**: Lovable acts and modifies the project.
  * **Chat mode**: Lovable only **answers questions**—it doesn’t change code.
  * **Attach**: Add images for visual guidance.
  * **(Later) Knowledge**: Persistent rules & docs (see §9).
* **Right side**: **Live Preview** of your app.

  * Top bar: **Refresh**, **Pop-out**, **Route picker** (choose pages), **Device sizes** (desktop/tablet/phone).

**Tip:** After a build, **test the UI** immediately to catch issues early.

---

## 5) Make Targeted Visual Edits

Click **Edit** → select an element in the preview → describe a change.

Example:

> “Underline this title in orange.”

Lovable applies the change precisely to the selected component.

**If you don’t like a change:**

* Use **History** (top bar) to **Restore** a prior state.
* Use **Code diff** (for paid code view) to see exactly what changed.

---

## 6) Add a Landing Page (Second Feature)

Prompt:

> “Create a **stylish landing page** named **‘Tim’s Macro App’** with a clear call-to-action that routes to the calculator.”

Result: You’ll now see two routes, e.g. `/` (landing) and `/calculator`.

---

## 7) Meta-Prompting with Chat Mode (Strongly Recommended)

When you **know the outcome** but **not the best instructions**, use **Chat mode** to have Lovable *write the prompt for Lovable*.

Example (in **Chat mode**):

> “I want a **dark/light mode toggle** site-wide. Help me craft a clear, safe prompt for the model to implement this without breaking the project.”

Copy Lovable’s proposed prompt, **exit Chat mode**, paste it, and run.

**Prompting tip:** The **first and last lines** of your prompt carry extra weight—place key constraints there.

---

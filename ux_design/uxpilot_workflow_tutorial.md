# The UX Pilot End-to-End Workflow: From Idea to Production-Ready UI

[Watch: Design An App With AI | UX Pilot Tips & Tricks](https://www.youtube.com/watch?v=mMMRKwGitGw)

This tutorial distills the complete process demonstrated in the provided video into a professional, step-by-step guide. You’ll go from a blank canvas to a documented, high-fidelity mobile app—entirely inside the UX Pilot ecosystem (FigJam/Figma + UX Pilot Web).

---

## What You’ll Achieve

* Generate and refine an app concept with AI.
* Expand ideas into concrete features and user-facing requirements.
* Auto-build a comprehensive flowchart diagram from your features.
* Spin up a ready-to-run UX workshop (agenda, activities, email, and facilitator notes).
* (Optional) Produce wireframes from your diagram.
* Generate high-fidelity, multi-screen UI flows with style controls.
* Edit UI with natural-language prompts (global and section-level).
* Preview, document prompt history, export to Figma, and derive technical requirements—including a foundation for your design system.

---

## Prerequisites

* **Figma account** (FigJam enabled).
* **UX Pilot**:

  * FigJam/Figma plugin installed (`Plugins → Manage Plugins → Search “UX Pilot”`).
  * Access to **UX Pilot Web** (for hi-fi screen generation and editing).

> Tip: Ideation prompts inside the FigJam plugin’s **AI Tools → Custom Prompt** do not consume UX Pilot tokens (as described in the video), making it ideal for early exploration.

---

## Phase 1 — Ideate in FigJam (No Tokens)

1. **Start a FigJam board** → `Plugins → UX Pilot`.
2. **Open AI Tools** (panel end-tab) → **Custom Prompt**.
3. On a sticky note, write a short brief, e.g.:

   * *“Give me ideas for a UI/UX project.”*
4. **Select the sticky** → paste the same prompt into **Custom Prompt** → run.
5. Review the generated list; **choose one concept** to pursue.

   * Example chosen in the video: **Travel Itinerary Builder**.

**Best practices**

* Keep problem statements short.
* Use nouns and verbs that imply the platform early (e.g., “mobile app” vs. “web app”).

---

## Phase 2 — Generate Feature Candidates

1. On a sticky with your chosen concept, run:

   * *“Give me features for this **mobile** app.”*
   * (Include platform type: mobile, web, desktop—this affects the feature set.)
2. Triage the output:

   * **Keep** what aligns with your goals.
   * **Delete** or reword features that don’t.
   * **Group** related features; normalize titles.

**Checklist**

* Feature titles: short, consistent (“Trip Planning,” “Document Vault,” “Invite Collaborators”).
* Scope: note MVP vs. V2 candidates.

---

## Phase 3 — Expand Requirements (User-Facing Detail)

1. **Select all feature stickies**.
2. Run a clarifying prompt:

   * *“Give me details for each feature—how it works from the **user’s** side.”*
3. UX Pilot adds a new sticky detailing each feature.
4. **Refactor**: move details under their feature headings; simplify phrasing.

**Outcome**
A clear, user-centric requirements set that stakeholders can understand quickly.

---

## Phase 4 — Create a Flowchart Diagram

1. **Select all features and notes** you want modeled.
2. Go to the **Diagram** tab in the plugin.
3. Click **Generate Diagram** (the **top** button uses your selection).

   * (The bottom button generates from a prompt—use the top button here.)
4. Inspect the diagram:

   * Confirm each feature appears.
   * Verify sequences (e.g., *Save Travel Documents* lists document types; *Invite Friends* shows the invitation process).

**Common pitfall**
If the diagram feels off, you likely:

* Didn’t select everything, or
* Used the prompt-based diagram button by mistake.

Regenerate after correcting selection.

---

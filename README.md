<p align="center"><a href="README.md">English</a> | <a href="README.zh-TW.md">繁體中文</a></p>

<p align="center"><img src="assets/branding/way-tools-icon.svg" width="64" alt="Way Tools icon"></p>
<h1 align="center">WAY TOOLS</h1>
<p align="center"><strong>Less AI. Better System.</strong></p>
<p align="center"><strong>Turn one successful task into an almost-free capability for the next time.</strong></p>
<p align="center">Use AI where it helps. Preserve what works. Reuse verified methods with less reasoning, fewer tokens, and increasingly local execution.</p>
<p align="center"><strong>Friend Beta V0</strong> · Private, invited testing · Proprietary software</p>
<p align="center"><a href="docs/getting-started.md">Start here</a> · <a href="docs/installation.md">Install</a> · <a href="#available-today">Available today</a> · <a href="#product-direction--vision">Vision</a> · <a href="docs/feedback.md">Feedback</a> · <a href="https://waytools.pages.dev/">Website</a></p>

![Way Tools product identity graphic; this is not a product screenshot](assets/hero/way-tools-hero.svg)

## What is Way Tools?

Way Tools brings Context, Way Chat, Tools, Recipes and Skills into one connected workspace. Provide text or a page reference, choose a supported command or tool, inspect the result, and keep useful work in My Way.

The Chrome extension starts with **Quick Way**, a compact entry point beside your browsing. **Open Way Tools** takes you to the full workspace. The Web version opens the full workspace directly.

> **Early beta:** Way Chat currently runs supported local commands. Remote AI is not enabled; it is not a general-purpose AI chatbot. Friend Beta builds are shared privately with a small group of trusted testers. There is no public build download here.

## Why Way Tools?

Most AI products make every task another inference. Way Tools is heading in a different direction: use AI when needed, preserve successful verified methods, and progressively turn familiar work into reusable local or deterministic capability.

- **Start with the material.** Explicitly attach a page reference or selected text, or paste a small example.
- **Move between Chat and Tools.** Use a supported command or a tool's controls, then bring a result back to Chat.
- **Keep useful work together.** My Way holds notes, saved Recipe results and Skills in your local workspace.
- **Repeat a successful method.** Run Clean & Save Links, save the verified procedure as a Skill, and use it with fresh input.

## Available today

Friend Beta V0 is intentionally limited and local-first.

| Area | Current state |
| --- | --- |
| Product | Friend Beta V0; application version 0.1.15 |
| Platforms | Web workspace and privately distributed desktop Chrome extension |
| Chat | Supported local commands; remote AI not enabled |
| Recipes / Skills | One built-in Recipe; successful method capture and reuse with fresh input |
| Data | Local workspace; no accounts, cloud sync or cross-platform sync |
| Next version | V0.1.16 has not started |

The concepts in **Product Direction / Vision** below are not claims about current production functionality.

## How it works today

| Step | What you do | Example |
| --- | --- | --- |
| Context | Provide the material to work with | A public URL or a short sample text |
| Chat / Tool | Pick a supported command or tool | Save a note, or uppercase text |
| Action | Run the selected operation | Click UPPERCASE in Text Toolkit |
| Result | Inspect the output | See WAY BETA in Last result |
| Recipe / Skill | Optionally reuse a supported procedure | Clean links, save the method, run it with new links |

Chat and Tools are alternative starting points. You do not need to pass through every screen for each task.

## Core experiences

| Experience | What it helps you do | Guide |
| --- | --- | --- |
| **Quick Way** | Attach browser Context and send a short command; open the full extension | [Quick Way](docs/quick-way.md) |
| **Context** | See which text, page reference or tool input an operation is using | [Using Context](docs/context.md) |
| **Way Chat** | Request supported local actions with short commands | [Chat & Tools](docs/chat-and-tools.md) |
| **Tools** | Use Text Toolkit, JSON Formatter, Image Compressor and other current tools | [Chat & Tools](docs/chat-and-tools.md) |
| **My Way** | Find notes, pinned/recent tools, Recipe results and saved Skills | [Recipes & Skills](docs/recipes-and-skills.md) |
| **Recipes** | Run the built-in Clean & Save Links procedure | [Recipes & Skills](docs/recipes-and-skills.md) |
| **Skills** | Save a successful Recipe's method and run it again with new input | [Recipes & Skills](docs/recipes-and-skills.md) |

## Product Direction / Vision

### Product philosophy

Way Tools is not designed to maximize AI calls. The long-term system starts by capturing the right material, keeps structure before generation, and recalls what is already known before asking AI again. In practice, that means **capture first, intelligence later**; **recall before AI**; **Structured IR First**; and **never resend unchanged context**. AI should be reserved for semantic gaps that local logic or verified knowledge cannot reliably close.

Successful AI-assisted work should progressively graduate into Local / Deterministic Capability. Skills, Recipes and capabilities should also become increasingly implicit: for familiar tasks, users should not have to remember which Skill to open. The interaction should be **intent-first, not tool-first**; tool categories and labels are secondary UI that should appear only when useful.

That direction is summarized by **Less AI. Better System.**

### The long-term loop

**Capture → Local Process → Context → Recall → Route → Act → Verify → Learn**

Verified outcomes can then feed a second loop:

**Capability Memory → Reuse → Cost Down**

**Capability Memory** means memory of how a class of tasks was successfully completed—including reusable steps, verified methods and deterministic capabilities—so the next similar task can require less reasoning, fewer tokens, or eventually no AI call at all.

### The positive flywheel

**First use → AI / reasoning → Successful + verified → remember method → Repeated use → Skill / Recipe / Capability → Mature use → Local / Deterministic execution → faster + cheaper + less AI-dependent**

The ideal outcome is not more AI calls. Every successful use should make the next similar use cheaper, faster and less AI-dependent.

### Recall before AI

A future Way Tools router should check what already exists before calling AI:

- existing Skills
- Recipes
- Local Capabilities
- Capability Memory
- previous verified workflows
- relevant user or context memory

Conceptually:

**Intent → Recall → Known capability?**

- **Exact / high-confidence match:** reuse locally.
- **Partial match:** reuse what is known and fill only the semantic gap.
- **No reliable match:** use AI.

This routing model, automatic Skill recall, implicit Skills, Capability Memory, AI dependency reduction and progressive local/deterministic graduation are **Product Direction / Vision**, not features claimed as shipped in Friend Beta V0.

## Product views

These are clearly marked screenshot slots. Real product captures will replace them after a privacy review; they do not depict the interface.

| Quick Way | Way Chat + Context |
| --- | --- |
| ![Placeholder: Quick Way screenshot pending](assets/screenshots/quick-way.svg) | ![Placeholder: Way Chat and Context screenshot pending](assets/screenshots/chat-context.svg) |
| Tool result | My Way |
| ![Placeholder: tool result screenshot pending](assets/screenshots/tool-result.svg) | ![Placeholder: My Way screenshot pending](assets/screenshots/my-way.svg) |
| Recipe | Skill |
| ![Placeholder: Recipe screenshot pending](assets/screenshots/recipe.svg) | ![Placeholder: Skill screenshot pending](assets/screenshots/skill.svg) |

## 5-minute Getting Started

After installation, try this with non-sensitive examples:

1. On example.com, open the extension's **Quick Way** and choose **Send current page**.
2. In Way Chat, send **記住** to save the attached page reference as a note.
3. Choose **Open Way Tools** → **Text Toolkit**. Enter **way beta** and click **UPPERCASE**.
4. Inspect **WAY BETA** in the result area. **Send to Chat** attaches the output for your next command.
5. Optionally run **Clean & Save Links**, then save the successful method as a Skill and rerun it with fresh input.

The [step-by-step guide](docs/getting-started.md) includes a Web route and sample links. Five minutes is an onboarding target, not a measured benchmark; installation takes additional time.

## Friend Beta status

Friend Beta V0 is a controlled early test for approximately **3–10 trusted testers**, intended to improve first-use clarity and gather feedback. The private tester package is prepared and has passed the owner's real-device installation check.

Invited testers receive the approved package privately and follow [installation](docs/installation.md). Please do not upload, repost or publicly redistribute the package. There is no public release or application download in this documentation repository.

## Safety & privacy

Use a **separate browser profile** and **non-sensitive test data**. Do not provide passwords, API keys, authentication secrets, payment information, private medical records, confidential work data or sensitive personal documents.

Workspaces are local and separate between Web and Extension. There are no accounts or cloud sync; people using the same browser profile may see the same data. This beta does not provide production-grade multi-user isolation.

Read [Safety](docs/safety.md) before trying it. Review screenshots and any diagnostic summary before sharing.

## Documentation

| Start | Use | Get help |
| --- | --- | --- |
| [Getting Started](docs/getting-started.md) | [Quick Way](docs/quick-way.md) | [Safety](docs/safety.md) |
| [Installation](docs/installation.md) | [Using Context](docs/context.md) | [Known Issues](docs/known-issues.md) |
| [Web route](docs/getting-started.md#web-route) | [Chat & Tools](docs/chat-and-tools.md) | [Troubleshooting](docs/troubleshooting.md) |
| [繁體中文入門](docs/getting-started.md#繁體中文快速路線) | [Recipes & Skills](docs/recipes-and-skills.md) | [Feedback](docs/feedback.md) |

## Feedback / Issues

Tell us what you tried, what you expected, what happened, and whether you could continue. English and Traditional Chinese are welcome.

The prepared Issue Forms cover **Bug Report**, **UX / Confusing Flow**, and **Feature Request**. Once this repository is published with Issues enabled, use its Issues tab. Until then, invited testers should use their existing private contact with the owner. [Feedback guide](docs/feedback.md).

GitHub Issues are public. Remove private content and secrets; never attach a complete workspace or the private beta package.

## Current status

See **Available today** above and [Known Issues](docs/known-issues.md) for current UX and compatibility limits.

## Source Availability

Way Tools is proprietary software. This repository contains public documentation, product information and beta resources only. The Way Tools application source code is not distributed through this repository.

Repository visibility does not grant rights to the proprietary Way Tools software. See [Proprietary Notice](PROPRIETARY-NOTICE.md).

## Website

The official Way Tools website is [waytools.pages.dev](https://waytools.pages.dev/). The Web workspace differs from the extension; visiting the website does not install Quick Way or synchronize extension data.

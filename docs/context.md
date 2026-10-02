# Using Context

[Quick Way](quick-way.md) · [Chat & Tools](chat-and-tools.md) · [Safety](safety.md)

**Context is the material Way Tools is currently working with.** It may be a page reference, explicitly attached text, the active tool's input or a recent result. Different operations use the material relevant to that operation.

Look at the attached content and source before running a command. Context is not an automatic, live copy of everything you browse.

## Page versus selection

In Quick Way, **Send current page / 傳送目前頁面** supplies only the title and URL—even when text is selected. It does not collect the page body.

**Send selected text / 傳送選取文字** is the explicit selection route:

1. On example.com, select **Example Domain**.
2. Invoke Way Tools from that source page.
3. Choose Send selected text and check the attached text/source.

If no selection is available, return to the source page, select a small piece of text, and invoke Quick Way again. Internal browser pages and some protected pages cannot be collected; use a normal public sample page.

## Manually supply text

In Web, choose **Browser Capture / 瀏覽器收集** from desktop Capabilities or mobile Tools. Fill the URL field and/or pasted-text field, then choose **Add to Way Context / 加入 Way Context**.

Quick Way also offers Paste from clipboard; if a manual fallback appears, paste text there and explicitly attach it.

This is material you provide. Web does not read another tab.

## Use fresh material

Changing tabs does not refresh attached Context. To change the extension's source, return to the intended page, invoke Quick Way and collect again.

For a Recipe, paste links into its Input field. An empty Recipe can use explicitly attached text, but page title/URL-only Context and old chat history are not a replacement. A saved Skill always asks for new input; it does not reuse its previous links.

**Send to Chat / 傳送到 Chat** attaches a result for further use; it does not automatically execute a new command.

## Context Inspector and sharing

In the full extension, open **Context Inspector / 脈絡檢視器** from **Capabilities / 能力**. Search for the name if needed. On mobile Web, begin with **Tools / 工具**. Quick Way users first choose Open Way Tools.

The inspector helps you see current Context and the last result. If the owner requests a diagnostic summary, choose **Copy Share-safe / Redacted summary / 複製 Share-safe／遮罩摘要**, paste it into a draft and inspect it before sending.

Ordinary **Copy / 複製** copies original content. The Share-safe summary reduces disclosure but may still reveal domains, lengths and counts; it is not an anonymity guarantee. A short written description is enough if you prefer not to share a summary. Never post sensitive Context or an entire workspace in a public Issue.

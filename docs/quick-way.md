# Quick Way

[Getting Started](getting-started.md) · [Using Context](context.md)

Quick Way is the Chrome extension's compact entry point. Use it to attach a page reference or selected text, issue a supported short command, and open the full workspace.

## Open it

1. Visit a normal public page such as https://example.com/.
2. Click the Way Tools icon in Chrome's toolbar or Extensions menu.
3. Look for Quick Way in the side panel; a new tab is the fallback when the panel cannot open.

To work with a different page, return to that page and click the Way Tools icon again. Attaching Context is explicit; switching tabs does not automatically replace your existing Context.

## Choose the material

| Control | What it supplies |
| --- | --- |
| **Send current page / 傳送目前頁面** | Page title and URL; not selection or full page body |
| **Send selected text / 傳送選取文字** | Text you explicitly selected on the source page |
| **Paste from clipboard / 從剪貼簿貼上文字** | Clipboard text, when browser access is available |

If clipboard access fails and a manual text area appears, paste sample text and choose **Add to Way Context / 加入 Way Context**. Inspect the attached source/content before continuing.

## Continue in the full workspace

**Open Way Tools / 開啟 Way Tools** opens the full extension in a new tab. Use it for the full tool interface, Recipes, My Way Skills and Context Inspector.

Quick Way has no direct Context Inspector entry. For the redacted summary, follow [Context Inspector](context.md#context-inspector-and-sharing) in the full workspace.

Quick Way's ⚙ opens Settings. You can choose Language and Appearance there.

## Web is different

Web opens the full workspace directly and has no Quick Way. It cannot read another tab's page or selected text; use **Browser Capture / 瀏覽器收集** to supply text/URL manually. Web and Extension workspaces are separate.

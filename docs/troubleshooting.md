# Troubleshooting

[Installation](installation.md) · [Known Issues](known-issues.md) · [Feedback](feedback.md)

Keep a short, non-sensitive description or reviewed screenshot before retrying. You do not need to edit code, permissions or package files.

| Problem | Try this |
| --- | --- |
| Extension will not load | Extract the approved package first. Select Way-Tools-Chrome, with manifest.json directly inside. Report Chrome's error if it still fails. |
| manifest.json cannot be found | Select neither the ZIP, the file itself nor the outer package folder. See Installation. |
| Quick Way is missing | Check the extension is enabled in chrome://extensions/. Find Way Tools in the puzzle-piece menu, visit example.com and click its icon. Check both side panel and new tab. |
| Full extension is missing | Choose Open Way Tools / 開啟 Way Tools in Quick Way. The website opens a different Web workspace. |
| Web has no Quick Way | This is expected. Use Browser Capture / 瀏覽器收集 to paste text or a URL manually. |
| Page and Selection are confusing | Send current page adds title/URL only. Send selected text adds explicit selection. Return to the source page, select text and invoke Quick Way again. |
| No selected text is available | Select a small piece of text on a normal public page first. Android testers use Web manual input. |
| Context or source seems old | Attached Context does not follow tab changes. Return to the intended webpage, invoke Quick Way and collect again. Check the source before running an action. |
| Source is unavailable | Reinvoke from a normal public HTTP(S) page. Internal browser pages and some protected pages cannot be collected. |
| Clipboard access fails | If Quick Way offers a manual text area, paste sample text and choose Add to Way Context / 加入 Way Context. Web has manual Browser Capture fields. |
| Way Chat cannot answer a question | Remote AI is not enabled. Try the supported 記住 sample or a Tool's controls. |
| Recipe or Skill cannot be found | Use the full workspace. Recipes are on Tools home; Skills are in My Way. First-time Skills can be empty. |
| Recipe has no input or finds no links | Paste the sample links directly into Input / 輸入內容. Page title/URL-only Context is insufficient; old chat is not used. |
| Save as Skill is missing | Complete Clean & Save Links successfully. Look in that run's verified Final Result. |
| Skill requests input or is unavailable | Provide new link-containing text. Report unavailable status; do not edit the Skill's contents. |
| Refresh/reopen returns to Chat | Switch back using bottom Tools/My Way on mobile, or desktop Capabilities/My Way. |
| Image processing cannot continue after refresh | Select the original sample image again. |

## Restart or reload

**Web:** record anything you need, then refresh the page. Refresh is not workspace clearing.

**Extension:** close Way Tools pages and its side panel. In chrome://extensions/, click the reload arrow on Way Tools. Return to a public sample webpage and click the icon again.

Try reload before removal/reinstallation. Uninstalling can lose local data; follow [Installation](installation.md#update-or-reinstall) if the owner requests it.

## Clear the test workspace

1. Open **Settings / 設定**: ⚙ in Quick Way or full desktop; ⋯ at the top right on mobile.
2. Under **Local workspace / 本機工作區**, select **Clear Local Workspace / 清除本機工作區**.
3. Read the scope. Choose **Cancel / 取消** to keep your data.
4. To delete permanently, confirm **Delete local workspace / 刪除本機工作區**. Successful clearing reloads the interface.
5. If you see **Reset could not be verified. Please retry before closing this dialog. / 無法確認清除成功，請重試後再關閉此視窗。**, do not assume clearing succeeded. Retry and report if it persists.

This cannot be undone. It clears this platform's notes, Chat, Context, results, Skills and run history. Web and Extension must be cleared separately; browser history, clipboard, downloads and some source-page information remain outside its scope.

The dialog says Theme and Language are preserved. If those preferences change after clearing, please report it; keep a note of them before clearing. See [Known Issues](known-issues.md).

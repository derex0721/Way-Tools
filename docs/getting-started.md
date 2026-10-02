# Getting Started

[English README](../README.md) · [繁體中文 README](../README.zh-TW.md) · [Safety](safety.md)

Provide material → use Way Chat or a Tool → inspect the Result. A Recipe adds a fixed sequence; a Skill lets you reuse a successful method with fresh input.

The steps below aim for about five minutes **after installation**. They use public example URLs and sample text. This is an onboarding target, not a timed test.

## Extension route

Invited testers first follow [Installation](installation.md). The extension is distributed privately.

1. Open [example.com](https://example.com/), then click the Way Tools toolbar icon to open Quick Way. It may open in a side panel or a new tab.
2. Under **Browser Context / 瀏覽器脈絡**, click **Send current page / 傳送目前頁面**. Confirm **Context attached / 已附加脈絡** refers to example.com. Page mode adds title and URL, not selected text or the full page body.
3. In Way Chat, enter **記住** and send it with ↑ or Enter. This supported local command saves the attached page reference as a note; it does not ask AI to summarize the website.
4. Click **Open Way Tools / 開啟 Way Tools**. In the full workspace, choose **Text Toolkit / 文字工具箱** from **Capabilities / 能力**. Enter **way beta** in **INPUT TEXT / 輸入文字**, then click **UPPERCASE / 轉成大寫**.
5. Find **WAY BETA** in **Last result / 最近結果** or **Tool Result / 工具結果** in Way Chat. **Send to Chat / 傳送到 Chat** attaches the output; you still choose the next command.

## Web route

Open the official [Way Tools website](https://waytools.pages.dev/). Web has no Quick Way and cannot collect from another browser tab.

On desktop, use the left **Capabilities / 能力** list; on mobile, use the bottom **Tools / 工具** tab. Open **Browser Capture / 瀏覽器收集**, enter https://example.com/ in the URL field and **Way Beta sample text** in the pasted-text field, then click **Add to Way Context / 加入 Way Context**.

Go to Way Chat (bottom **Chat / 聊天** on mobile), send **記住**, and inspect the saved note. Then try Text Toolkit as above. Web and Extension data do not sync.

## Optional: Recipe, then Skill

In the full workspace, find **Recipes** below the desktop capability list. On mobile, return to **Tools** home with **Back to Tools / 回到工具首頁**, scroll down and expand **Clean & Save Links**.

Paste this into **Input / 輸入內容**:

~~~text
https://example.com/?utm_source=friend_beta
~~~

Click **Run Recipe / 執行 Recipe**. Four steps should succeed. **Final Result / 最終結果** should contain https://example.com/ and **Verified · Saved to My Way / 已驗證 · 已保存到 My Way**.

Click **Save as Skill / 另存為 Skill**, name it **Beta Link Cleanup**, and click **Save Skill / 保存 Skill**. In **My Way → Skills**, click **Run Skill / 執行 Skill**, supply new input, and confirm:

~~~text
https://example.org/?utm_campaign=friend_beta
~~~

The Recipe progress should appear again; the result should be https://example.org/, not the previous example.com link. First-time Skills may be empty until you save one.

See [Recipes & Skills](recipes-and-skills.md) for details. If a step is unclear, [report where you got stuck](feedback.md); you do not need to complete every step to give useful feedback.

## 繁體中文快速路線

1. 先讀 [安全規則](safety.md)，依 [安裝說明](installation.md) 載入私下收到的核准套件。
2. 在 example.com 點 Way Tools 圖示，打開 Quick Way，按「傳送目前頁面」，確認來源。
3. 在 Way Chat 輸入「記住」，按 ↑ 或 Enter，查看保存的筆記。
4. 按「開啟 Way Tools」→「文字工具箱」，填入 way beta，按「轉成大寫」，結果應為 WAY BETA。
5. 在 Recipes 的 Clean & Save Links「輸入內容」貼上上面的 example.com 範例，按「執行 Recipe」。
6. 四步成功後按「另存為 Skill」→ 填名稱 →「保存 Skill」。到 My Way → Skills，按「執行 Skill」，貼上新的 example.org 範例；結果不應沿用上次網址。

Web 沒有 Quick Way：直接開網站，在「能力」（手機「工具」）選「瀏覽器收集」，手動填 URL／文字後按「加入 Way Context」。手機用底部「聊天」與「My Way」切換。深層文件目前以英文為主，重要操作附中英標籤。

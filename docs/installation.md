# Installation

[Start here](getting-started.md) · [Troubleshooting](troubleshooting.md) · [Safety](safety.md)

## Current access

Friend Beta V0 is privately shared with approximately 3–10 trusted testers. Invited testers receive an approved package directly from the owner. This repository provides no public application download or GitHub Release.

Use desktop Chrome with a separate browser profile that allows Developer mode. Owner real-device installation acceptance includes Mac Chrome; a comprehensive browser/OS/version matrix is not available. Check with the owner before trying other desktop environments. Android testers should use Web, not these unpacked-extension steps.

Do not bypass an organization's browser-management restrictions.

## Load the privately received extension

1. Extract/unzip the approved Friend Beta package into a folder you can keep.
2. Open its **Way-Tools-Chrome/** folder.
3. Confirm **manifest.json** is directly inside that folder.
4. Open Chrome in your test profile.
5. Enter **chrome://extensions/** in the address bar.
6. Enable **Developer mode / 開發人員模式**.
7. Choose **Load unpacked / 載入未封裝項目**. Chrome's translated wording may vary.
8. Select **Way-Tools-Chrome**.
9. Confirm a Way Tools extension card appears, version **0.1.15**, enabled and without loading errors.
10. Open https://example.com/, then click the Way Tools icon in Chrome's Extensions menu or toolbar to open Quick Way.

**Select the folder containing manifest.json—not the ZIP, the manifest file itself, or the outer Friend Beta folder.** Keep the loaded folder in place after installation.

You can pin Way Tools from Chrome's puzzle-piece Extensions menu. Quick Way normally opens in the side panel; it may open in a new tab if the panel cannot open.

## Open the full extension

In Quick Way, choose **Open Way Tools / 開啟 Way Tools**. It opens the full extension workspace in a new tab, with Tools, Recipes, My Way and Skills.

Opening the official website opens the separate Web workspace. It does not open the full extension or synchronize its data.

## Update or reinstall

Only use a later package explicitly approved and sent by the owner. Record any non-sensitive content you need to keep first; there is no promised automatic backup or migration.

1. Close Way Tools pages and the side panel.
2. Following the owner's instructions, replace the complete contents of the previously loaded Way-Tools-Chrome folder with the new extension contents. Avoid mixing old and new files.
3. On chrome://extensions/, click the reload arrow on the Way Tools card.
4. Return to a public sample page and reopen Quick Way.

The displayed version alone may not identify a private beta package; use the owner's package label. If instructed to install from a new folder, confirm how to handle existing local data first.

Try reload before uninstalling. Removing and reinstalling an extension can lose its local workspace. Record what you need, confirm the intended reinstall with the owner, then repeat the installation steps using the approved package.

Chrome's [official unpacked-extension instructions](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world) explain the browser controls. You do not need to create code, build the application or follow the tutorial's coding steps.

## 繁體中文重點

套件只私下提供給受邀者。先解壓縮 → 打開 Way-Tools-Chrome → 確認 manifest.json 直接在裡面 → Chrome 開 chrome://extensions/ → 開「開發人員模式」→「載入未封裝項目」→ 選 Way-Tools-Chrome。

不要選 ZIP 或外層資料夾。安裝後在 example.com 點 Way Tools 圖示開 Quick Way，再按「開啟 Way Tools」進完整擴充功能。更新只用擁有者新核准的套件；先試重新載入，移除重裝可能遺失本機資料。請勿公開分享、上傳或轉貼私人套件。

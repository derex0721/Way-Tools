# Recipes & Skills

[Getting Started](getting-started.md) · [Chat & Tools](chat-and-tools.md)

**Recipe:** a fixed, repeatable procedure supplied by Way Tools.  
**Skill:** a named method saved from a successful, verified Recipe run, ready to use with fresh input.

The beta currently has one built-in Recipe: **Clean & Save Links**. Skills may be empty on first use. This is not a custom workflow builder or an automatically learned AI skill.

## Run Clean & Save Links

In the full workspace, find **Recipes** below the desktop Capabilities list. On mobile Web, open **Tools**, use **Back to Tools / 回到工具首頁** if in tool details, then scroll down and expand Clean & Save Links.

Paste this into **Input / 輸入內容**:

~~~text
https://example.com/?utm_source=friend_beta
https://example.org/?utm_campaign=friend_beta
~~~

Click **Run Recipe / 執行 Recipe**. The existing procedure:

1. Extracts links.
2. Removes known tracking parameters.
3. Checks the resulting URLs.
4. Saves one combined Recipe result to My Way.

On success, **Final Result / 最終結果** shows https://example.com/ and https://example.org/, with **Verified · Saved to My Way / 已驗證 · 已保存到 My Way**. You can find the saved result in My Way.

“Verified” refers to the operation's result checks. It does not certify a destination website as safe or promise a permanent backup.

If no links are found, paste the example directly into Input. Empty Recipe input can use explicitly attached text, but not title/URL-only Page Context or old chat history. If a step fails, no successful Recipe result is saved; report the step and the non-sensitive input you tried.

## Save a successful method

1. In the successful run's Final Result, choose **Save as Skill / 另存為 Skill**.
2. Enter **Beta Link Cleanup** in **Skill Name / Skill 名稱**.
3. Choose **Save Skill / 保存 Skill**.
4. Find it in **My Way → Skills**.

Save as Skill is available for a completed, verified, successfully saved supported Recipe run. Historical notes do not necessarily offer this button.

## Run it with fresh input

Choose **Run Skill / 執行 Skill** in My Way → Skills. Paste new input:

~~~text
https://example.net/?utm_medium=friend_beta
~~~

Confirm Run Skill. The Recipe progress appears again, and the new result should be https://example.net/. The previous input is not used as a default.

The Skill preserves the method, not the prior links as reusable input. However, notes, Chat, Context and saved results can still contain your earlier material. Keep all test content non-sensitive.

## Rename or delete a test Skill

Choose **Rename / 重新命名**, change the name and click **Save / 儲存**. Renaming a saved Skill does not rename the built-in Recipe.

Choose **Delete / 刪除**, check the Skill's name in the confirmation, then cancel or confirm. Only delete your test Skill. Removing the Skill does not mean every earlier note or result has been erased.

If a Skill shows unavailable, report it rather than modifying its contents. There is no supported arbitrary-program execution in this beta.

# photocean 反馈 · Feedback

**中文** · [English](#english)

photocean 是一个 iOS 相册应用，可以浏览 Immich、MT Photos 服务器上的照片和本机照片。
这个仓库只用来收问题报告和功能建议，应用的源代码不在这里。

## 发之前请先知道：这里的一切都是公开的

- 任何人都能看到你写的文字、上传的截图、录屏和日志，搜索引擎也可能收录。
- 上传的文件在删掉评论后未必失效。请按「发出去就收不回」来对待。
- 截图和录屏里如果有不想公开的照片、人脸、相簿名或服务器地址，请先打码或裁掉。

## 报告问题

1. 点上方的 **Issues** → **New issue** → 选 **问题报告 / Bug report**。
2. **版本与构建**：打开 photocean → 设置 → 关于，把「版本」「构建」两行原样抄过来，例如 `1.0.0（742） a1b2c3d`。
   我们靠它找到你手机上运行的那份代码，请务必抄准。
3. 尽量附上诊断记录（见下一节），它通常是定位问题最快的线索。
4. 一个 issue 只报一个问题。

## 导出诊断记录

1. 打开 photocean → 设置 → 关于 → 诊断记录。
2. 点右上角的「⋯」→「导出完整记录」，存到「文件」。
3. 在表单的「诊断记录」一栏，点输入框下方的 *Paste, drop, or click to add files*，选刚才存的 `.txt` 文件。

导出时已经自动去掉了：账号、密码和令牌，服务器地址，照片文件名，照片坐标。
**但文件里可能还有你起过的名字，比如相簿名称、回忆标题。** 上传前请打开看一眼，不想公开的行可以删掉再传。

排查「画面自己跳动」「切换后停在错的位置」这类问题时，我们可能会请你先在「诊断记录」页打开「记录滚动与锚点轨迹」，重启 app，复现一次后再导出。

## 功能建议

选 **功能建议 / Feature request**。写清楚你想解决什么问题，比直接描述界面该怎么改更有用。

## 之后会发生什么

每个 issue 都会得到一个状态标签和一条说明。回复由我们的机器人账号发出，每一条发出前都经过开发者本人确认。

| 标签 | 意思 |
|---|---|
| 待处理 / new | 还没看，在排队 |
| 需要更多信息 / needs info | 需要你补一样东西，回复里会写清楚；14 天没有回音会先关闭，之后补上信息留言即可，我们会重新打开 |
| 暂时无法复现 / cannot reproduce | 照你的步骤没能重现，回复里会写明试过什么 |
| 已确认·另行排期 / confirmed, scheduled | 原因已经查清，但改动较大，会在后续版本处理 |
| 已修复·待发版 / fixed, pending release | 已经修好，等下一个版本发布；发布后会通知并关闭 |
| 已发布 / released | 修复已随某个版本发布，更新后应该不再出现 |
| 新版已修复 / fixed in newer version | 你用的版本较旧，这个问题在更新的版本里已经修好 |
| 设计如此 / by design | 这是有意为之，回复里会说明原因 |
| 非本应用问题 / not a photocean bug | 问题出在服务器（Immich / MT Photos）或 iOS 本身，回复里会说明该去哪里反馈 |
| 重复 / duplicate | 和另一个 issue 是同一个问题，请到那边跟进 |

---

<a id="english"></a>

## English

photocean is an iOS photo app for Immich and MT Photos servers and the photos on your device.
This repository only collects bug reports and feature requests; the app's source code is not here.

> The app's interface is currently in Chinese only. Menu names below are written in Chinese, with the English meaning in parentheses.

### Before you post: everything here is public

- Anyone can see what you write and every screenshot, recording and log you upload. Search engines may index it.
- Uploaded files may stay reachable even after the comment is deleted. Treat everything you post as permanent.
- If a screenshot or recording shows photos, faces, album names or server addresses you don't want to share, blur or crop them first.

### Reporting a bug

1. Go to **Issues** → **New issue** → choose **问题报告 / Bug report**.
2. **Version & build**: open photocean → 设置 (Settings) → 关于 (About) and copy the 版本 (Version) and 构建 (Build) rows exactly, e.g. `1.0.0（742） a1b2c3d`.
   This is how we find the exact code running on your phone, so please copy it carefully.
3. Attach the diagnostic log if you can (see below). It is usually the fastest way to the cause.
4. One problem per issue, please.

### Exporting the diagnostic log

1. Open photocean → 设置 (Settings) → 关于 (About) → 诊断记录 (Diagnostic log).
2. Tap **⋯** in the top-right corner → 导出完整记录 (Export full log), and save it to Files.
3. In the form's diagnostic log field, click *Paste, drop, or click to add files* below the text box and pick the `.txt` file.

The export already removes accounts, passwords and tokens, server addresses, photo file names and photo coordinates.
**It may still contain names you created, such as album names and memory titles.** Please open the file before uploading and delete any lines you don't want to share.

For problems like "the screen jumps by itself" or "it lands in the wrong place after switching", we may ask you to turn on 记录滚动与锚点轨迹 (Record scroll and anchor trace) on the diagnostic log page, restart the app, reproduce the problem once, and then export.

### Feature requests

Choose **功能建议 / Feature request**. Describing the problem you want solved helps more than describing how the screen should change.

### What happens next

Every issue gets a status label and a short explanation. Replies come from our bot account, and the developer reviews each one before it is posted.

| Label | Meaning |
|---|---|
| 待处理 / new | Not looked at yet |
| 需要更多信息 / needs info | We need one more thing from you, described in the reply. Closed after 14 days without an answer; leave a comment with the information any time and we will reopen it |
| 暂时无法复现 / cannot reproduce | We followed your steps but couldn't reproduce it; the reply lists what we tried |
| 已确认·另行排期 / confirmed, scheduled | We know the cause, but the fix is large and will come in a later version |
| 已修复·待发版 / fixed, pending release | Fixed, waiting for the next release; we'll notify you and close it when it ships |
| 已发布 / released | The fix has shipped; after updating it should be gone |
| 新版已修复 / fixed in newer version | Your version is older; this is already fixed in a newer one |
| 设计如此 / by design | This is intentional; the reply explains why |
| 非本应用问题 / not a photocean bug | The problem is in the server (Immich / MT Photos) or iOS itself; the reply says where to report it |
| 重复 / duplicate | Same problem as another issue; please follow that one |

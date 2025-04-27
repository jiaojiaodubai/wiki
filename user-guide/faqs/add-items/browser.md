# 从浏览器抓取条目的常见问题

## 点击 Zotero Connector 图标后弹窗询问「Zotero 运行了吗？」

Zotero Connector 抓取的条目可以保存到 Zotero 客户端、在线文库或者 Google Docs。大多数情况下，我们需要保存到 Zotero 客户端，所以请确保 Zotero 客户端已经运行。

## Zotero Connector 图标为灰色，鼠标悬浮在上面时显示「已停用」

Zotero Connector 只在显示文献信息的网页上工作，如果在其他网页（例如浏览器主页）看到 Zotero Connector 的图标变灰，无需担心，这是正常现象。

## Zotero Connector 图标为灰色，点击抓取到的条目类型为「网页」

这表明没找到合适的转换器来抓取当前的网页，只能暂时保存为一个网页条目，但这样保存的条目信息往往是不全面甚至错误的。

你可以按以下步骤排查问题：

1. [重置](../measures/reset-translators.md) 和 [更新转换器](../measures/update-translator.md)。
2. 尝试使用校园网、CARSI、或者帐号登录来认证，避免 webVPN 等干扰。
3. [检查转换器是否支持当前网站](../measures/check-available-translators.md)，如果尚未支持该网站，你可以 [申请新转换器](../measures/request-new-translator.md)。

## Zotero Connector 图标为蓝色，点击抓取到的条目类型为「网页」

这表明当前的网站有合适的转换器，但你仍需检查抓取的条目信息是否正确。

1. 如果这个网页上显示的是仅在互联网发布的文献，且条目中「作者」、「网站标题」等信息完整，则属于正常情况。
2. 反之，如果你想抓取的文献不属于网页，或者抓取到的网页条目中缺少「网站名称」、「作者」等信息，说明转换器并未适配该网页，请 [反馈问题](../measures/report-bug.md)。

## Zotero Connector 图标在搜索结果页面没变成「黄色文件夹」

对于知网，批量抓取暂时失效了，建议逐个抓取。对于其他网站，如果有时能显示「黄色文件夹」，而有时不能，则可能是网站的动态加载导致的，你可以 [反馈问题](../measures/report-bug.md)。

## 在 PDF 阅读页面抓取失败

## 「使用 xxx 保存时发生错误，改为尝试用 yyy 保存 」

这种情况是抓取失败了，你可以按照以下步骤解决：

1. 确保 Zotero 客户端是最新就正式版，详见 [更新客户端](../measures/update-client.md) 的步骤说明。
2. 浏览器、Zotero Connector 都是最新版，详见 [更新浏览器](../measures/update-browser.md)、[更新 Zotero Connector](../../install.md) 的步骤说明。
3. 尝试更换浏览器，推荐的浏览器依次是 火狐浏览器 > Edge > 国产浏览器（如搜狗浏览器、QQ 浏览器、360 浏览器、百度浏览器 ）> Chrome（谷歌浏览器） > Safari。
4. [重置](../measures/reset-translators.md) 和 [更新转换器](../measures/update-translator.md)。
5. 如问题仍存在，请 [反馈问题](../measures/report-bug.md)。

## 抓取的条目下面没有 PDF

...

## 抓取的条目信息不全

如果网页上没有提供你想要的信息（如期刊文章的卷数、书籍的出版地、大学所在地），那么转换器也很可能无法获取这些信息，这时，你可以：

1. 对于中文的期刊文章、学位论文和会议论文，你可以尝试使用 [Linter 插件] 补全这些信息。
2. 如果不属于 Linter 插件可以补全的条目，或者[Linter 插件] 无法补全，你可以 [手动录入](../../add-items.md) 这些信息。

如果网页上存在这些信息，但未能抓取下来，请 [反馈问题](../measures/report-bug.md)。

# nz-visa-stay-calculator
新西兰访客签停留计算器

🌐 在线使用：https://milkvetch.github.io/nz-visa-stay-calculator/

多次往返访客签（multiple-entry visitor visa）规定：每 12 个月内累计停留不超过 6 个月。
这个小工具按移民局口径，帮你算出本次入境后最多还能停留多少天、最晚哪天离境。

## 怎么用

1. 选择本次入境日期
2. 回答是否来过新西兰；来过就逐段填写过往行程（入境 → 离境）
3. 查看结果：可停留天数、最晚离境日、历史行程明细

手机和电脑浏览器都能用。纯静态单文件（`index.html`），无后端、不上传任何数据。

## 计算口径

- 12 个月为滚动窗口：从最晚离境日往前倒推 12 个月
- 6 个月按 180 天保守计算
- 窗口之外的既往行程不计入停留天数（明细中以删除线标出）

*仅供行程规划参考，不构成移民法律建议；请以新西兰移民局官网最新政策为准。*

---

A tiny static calculator for NZ multiple-entry visitor visas: given your planned entry date and past trips, it tells you how many more days you can stay and your latest departure date, using INZ's 12-month rolling window rule (6 months counted as 180 days, conservatively). Single `index.html`, no backend, no data uploaded.

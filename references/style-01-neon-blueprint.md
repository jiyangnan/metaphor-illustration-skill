# Style 01 — 霓虹蓝图（Neon Blueprint）

代表作：自建 VPN 教程的 4 张配图（2026-11-10，提示词全文见文末）。用户 2026-11-11 明确表示喜欢这套质感与线条，并指定将其沉淀为图片创作 skill 的第一个风格。「蓝图」指线条勾勒的技术底味，「霓虹」指深蓝底上的发光线条。

## 适用题材

- 科技基础设施、网络、开发者工具、产品机制类文章与教程的配图、封面底图、章节卡配图。
- 不适用：人物情感叙事、生活方式题材（本风格没有固定角色，人物只作扁平剪影客串）；需要真实界面截图的实操步骤图。

## 隐喻设计（逐图执行 SKILL.md 红线，代表作的四个映射）

- 共享节点会被连坐 → 合租大通铺：一台敞开的机箱塞满密密麻麻的小人、红光警示、线缆乱成团；独享则是小箱子干净一人，人物直接躺在上面，盾与锁在旁。两边密度差就是论点本身。
- 一串 IP 变成能签证书的域名 → 临时工牌换正式工牌：四个发光数字段经魔法漩涡，变成金色名牌加奖章加锁，「一串数」获得「身份」。
- 网站被误判跳转到已关停的本地版 → 兴冲冲跑去的店早已关门：浏览器窗口加粗箭头指向拉下卷帘门的店铺，橙色路径在地上绕圈掉头。
- 多台设备接入自己的境外节点 → 我在那座城市有了一栋小楼：手机、笔记本、平板成列，发光的流光线路汇入一座塔楼式服务器，背景是地点剪影（新加坡天际线与滨海湾金沙），地点靠剪影交代，不写字。

## 风格锁（每条提示词逐字复用）

```text
flat vector illustration, deep navy blue background, electric blue and warm orange color palette, glowing neon line art, clean minimal tech illustration, cinematic rim light, wide 16:9 composition, no text, no letters, no words
```

## 物件锁（本风格不设固定角色，用物件锁代替）

- 设备、服务器、建筑一律按发光线条勾勒的扁平物件画，同一物件在同套图里保持同一画法（塔楼式服务器、成列的设备、卷帘门店铺均可跨图复用）。
- 人物只作扁平剪影或小比例卡通形象客串（如躺在箱子上的人），不做主角、不给特写。

## 配色

- 深海军蓝打底，电光蓝管日常与科技感，暖橙是重点色、定额使用：只给警告、回程路径、身份物件（名牌、奖章）和关键动作。
- 红色只许出现在风险信号上（警示光、警告标），面积要小。

## 逐图提示词全文（风格锁拼在每条最前面，下为各图事件部分）

注：原始生成提示词当时未存档，以下为 2026-11-11 对着成图逐项反推的重构版，经用户确认收录。本风格此后的新图必须存档原始提示词，不再反推。

1. 封面（论点：我的三台设备都连到我在新加坡的专属节点）：`a smartphone, a laptop and a tablet floating in a vertical row on the left, their screens showing abstract glowing circuit dot patterns, elegant flowing streams of blue and orange light with sparkles traveling from the devices across the scene into a tall dark server tower on the right outlined in orange and blue, silhouette of the Singapore skyline with Marina Bay Sands at night behind the server, tiny warm lit windows`
2. 共享 vs 独享（论点：共享 IP 会被连坐，独享才干净）：`split composition contrast: on the left an open server cabinet stuffed with a dense crowd of hundreds of tiny people, red warning glow and a warning triangle on the cabinet, tangled messy orange and blue cables spilling out; on the right a large blue shield with a padlock symbol, and a relaxed smiling man in an orange hoodie reclining with hands behind his head on top of a small neat blue server box with tidy cables, calm and spacious`
3. IP 变域名（论点：一串数字 IP 换上域名才获得身份与证书）：`four glowing neon blue rounded rectangles in a row on the left connected by dotted links, representing segments of an IP address, dissolving into a swirling magical vortex of blue and orange sparkles in the center, transforming into a large orange name tag badge on the right with a golden padlock and a golden award rosette seal above it, a sense of something raw becoming official and certified`
4. 跳转关停站点（论点：被分流误伤的流量兴冲冲跑去，只会撞上已关停的站点再掉头）：`a large browser window on the left with an address bar and padlock icon and simple wireframe content blocks, small red alert marks beside it, a bold blue arrow arcing from the browser toward a closed shopfront on the right with an orange roller shutter pulled down and an empty hanging sign, night street with dark blue buildings, and below a glowing orange path that loops back on itself with a return arrow, traffic being rerouted away from the closed shop`

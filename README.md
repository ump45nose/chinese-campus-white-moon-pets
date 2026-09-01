# 白月光 Codex Pets

> 中国校园里的白月光：安静、克制、成绩很好，偶尔也会被你逗到绷不住笑。

黑色高马尾、细圆框眼镜、白衬衫与深蓝领结。她总抱着书，站在夏日窗边或放学后的长走廊里；看起来有一点距离感，却会在擦肩而过时回头，推一下眼镜，轻轻向你打招呼。

## 夏装 Pet 的六个关键动作

以下透明动作图直接取自夏装 Pet 制作阶段的高清动作源图，仅去除原始洋红色键背景，没有重新绘制人物。

| idle · 安静抱书 | waving · 推镜招呼 | jumping · 大风反应 |
| --- | --- | --- |
| ![夏装 Pet 安静抱书](gallery/pet-actions-summer-v2/01-idle.png) | ![夏装 Pet 回眸推镜](gallery/pet-actions-summer-v2/02-waving.png) | ![夏装 Pet 在大风中整理衣摆](gallery/pet-actions-summer-v2/03-jumping.png) |
| 安静抱书，等候新的指令。 | 推一下眼镜，轻笑着向你打招呼。 | 马尾和裙褶被风吹乱，连忙整理好衣摆。 |

| failed · 假装生气 | waiting · 欲言又止 | running · 专注翻书 |
| --- | --- | --- |
| ![夏装 Pet 叉腰假装生气](gallery/pet-actions-summer-v2/04-failed.png) | ![夏装 Pet 抱书欲言又止](gallery/pet-actions-summer-v2/05-waiting.png) | ![夏装 Pet 专注阅读](gallery/pet-actions-summer-v2/06-running.png) |
| 叉腰看向你，嘴角却已经快绷不住。 | 抱着书看过来，像是有话想说。 | 认真读书、翻页，进入 Codex 工作状态。 |

## 五个瞬间

| idle · 窗边等风 | waving · 擦肩回眸 |
| --- | --- |
| ![窗边抱书与保温杯](gallery/01-idle-window.png) | ![回头推镜并轻轻挥手](gallery/02-waving-lookback.png) |
| 抱着书和保温杯，安静看向你。 | 已经走过去，又回头推镜、轻笑着挥手。 |

| running · 马尾掠过夏天 | failed · 假装生气 | waiting · 欲言又止 |
| --- | --- | --- |
| ![跑动时高马尾随步伐摆动](gallery/03-running-ponytail.png) | ![叉腰鼓脸却快要笑出来](gallery/04-failed-pout-to-smile.png) | ![整理裙摆并抬手欲言又止](gallery/05-waiting-unsaid.png) |
| 她抱着书跑过梧桐道，马尾在逆光里扬起。 | 被你捉弄后叉腰鼓脸，下一秒却自己先笑了。 | 整理好裙褶，抬手想叫住你，又把话留在黄昏里。 |

## 三个 Pet

| 版本 | Pet ID | 特色 | 预览 |
| --- | --- | --- | --- |
| 二次元基础版 | `qiu-jiaying-anime` | 干净的二次元校园形象，动作清楚利落 | [动作表](pets/qiu-jiaying-anime/contact-sheet.png) · [16 向注视](pets/qiu-jiaying-anime/look-directions.png) |
| 夏装互动版 | `qiu-jiaying-summer-v2` | 回头推镜、马尾摆动、读书翻页、整理裙摆，以及被风吹乱后的自然反应 | [动作表](pets/qiu-jiaying-summer-v2/contact-sheet.png) · [16 向注视](pets/qiu-jiaying-summer-v2/look-directions.png) |
| 夏装白月光版 | `qiu-jiaying-summer-v3` | 更安静克制的夏日气质，强调抱书、窗边、黄昏与欲言又止 | [动作表](pets/qiu-jiaying-summer-v3/contact-sheet.png) · [16 向注视](pets/qiu-jiaying-summer-v3/look-directions.png) |

三个版本均为 Codex Pet v2：`8 × 11`、`1536 × 2288`、RGBA WebP，并已通过 `spriteVersionNumber: 2` 图集校验。

## 安装

选择一个 Pet ID：

```bash
PET_ID=qiu-jiaying-summer-v3
mkdir -p "$HOME/.codex/pets/$PET_ID"
cp "pets/$PET_ID/pet.json" "pets/$PET_ID/spritesheet.webp" "$HOME/.codex/pets/$PET_ID/"
```

也可以分别执行三次，将三个版本同时安装。

## 目录

```text
gallery/                         五张高清人物特色图
gallery/pet-actions-summer-v2/   六张透明夏装 Pet 动作图
pets/qiu-jiaying-anime/          二次元基础版与 QA
pets/qiu-jiaying-summer-v2/      夏装互动版与 QA
pets/qiu-jiaying-summer-v3/      夏装白月光版与 QA
```

仓库仅包含最终 Pet、去标识化 QA、动作预览和生成的人物展示图；不包含真人参考照片、人设 YAML、提示词或本地绝对路径。

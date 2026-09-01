# Chinese Campus White Moon Pets

> 中国校园里的白月光形象：安静、克制，带着放学后才会被看见的细小情绪。

这是一个半写实亚洲插画风格的 Codex Pet 合集。人物以黑色高马尾、细圆框眼镜、红手绳和清爽的蓝白校园服饰作为核心识别符号，在窗边逆光、空教室与长走廊中呈现自然、不摆拍的互动感。

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

## 蓝白校服的四个瞬间

四张展示图统一采用蓝白运动校服版本，并从用户第一视角捕捉放学后的青涩互动。

| 迎风反应 · `jumping` | 低头转笔 · `waiting` |
| --- | --- |
| ![大风吹乱马尾和校服，她连忙压住衣摆](gallery/actions/01-wind-reaction.png) | ![她低头转笔，又抬眼看向你](gallery/actions/02-pen-waiting.png) |
| 这里的 `jumping` 不是跳跃：风突然吹乱马尾和外套，她双脚落地按住衣摆，脸红着对你鼓起脸。 | 笔在指间停停转转，她几次想开口，又把话留在黄昏的教室里。 |

| 假装生气 · `failed` | 拢起马尾 · `review` |
| --- | --- |
| ![她叉腰鼓脸，却已经快要笑出来](gallery/actions/03-pout-to-smile.png) | ![她咬住发绳，抬手重新束起马尾](gallery/actions/04-hair-tie-review.png) |
| 被捉弄后正面对你叉腰鼓脸，下一秒却自己先绷不住笑。 | 她咬着发绳抬手拢起马尾，白 T 衣摆随动作自然上移。 |

## 人设分解

三套服饰沿用同一人物比例、脸部特征、眼镜、高马尾和红手绳，分别覆盖夏日校园、蓝白运动校服与放学后日常穿搭。

| 夏装 | 蓝白运动校服 | 日常服饰 |
| --- | --- | --- |
| ![夏装人物三视图与服装配件分解](gallery/character-sheets/01-summer-uniform.png) | ![蓝白运动校服人物三视图与配件分解](gallery/character-sheets/02-blue-white-tracksuit.png) | ![日常服饰人物三视图与配件分解](gallery/character-sheets/03-daily-wear.png) |
| 白衬衫、深蓝领结与百褶裙，保留夏日窗边的清爽感。 | 白 T、蓝白外套与藏蓝白杠校裤，宽松而有生活痕迹。 | 浅灰连帽外套、直筒牛仔裤与白帆布鞋，适合放学后的普通一天。 |

## 四个 Codex Pet

| 版本 | Pet ID | 特色 | 预览 |
| --- | --- | --- | --- |
| 日常基础版 | `campus-white-moon-daily` | 干净的二次元校园形象，动作轮廓清楚 | [动作表](pets/campus-white-moon-daily/contact-sheet.png) · [16 向注视](pets/campus-white-moon-daily/look-directions.png) |
| 夏装互动版 | `campus-white-moon-summer-v2` | 回头推镜、马尾摆动、读书翻页与迎风反应 | [动作表](pets/campus-white-moon-summer-v2/contact-sheet.png) · [16 向注视](pets/campus-white-moon-summer-v2/look-directions.png) |
| 夏装白月光版 | `campus-white-moon-summer-v3` | 更安静克制，突出抱书、窗边、黄昏和欲言又止 | [动作表](pets/campus-white-moon-summer-v3/contact-sheet.png) · [16 向注视](pets/campus-white-moon-summer-v3/look-directions.png) |
| 蓝白运动校服版 | `campus-white-moon-tracksuit` | 迎风压衣摆、低头转笔、鼓脸笑场与束马尾 | [动作表](pets/campus-white-moon-tracksuit/contact-sheet.png) · [16 向注视](pets/campus-white-moon-tracksuit/look-directions.png) |

全部版本均采用 Codex Pet v2 图集：

- `8 × 11` 布局，单元尺寸 `192 × 208`
- 最终尺寸 `1536 × 2288`
- RGBA WebP，透明背景
- `spriteVersionNumber: 2`
- 每个包均附带动作表、16 向注视图与脱敏后的校验报告

## 安装

选择一个 Pet ID，将对应目录复制到 Codex Pet 目录：

```bash
PET_ID=campus-white-moon-tracksuit
mkdir -p "$HOME/.codex/pets/$PET_ID"
cp "pets/$PET_ID/pet.json" "pets/$PET_ID/spritesheet.webp" "$HOME/.codex/pets/$PET_ID/"
```

四个版本使用不同 ID，可以同时安装。

## 目录

```text
gallery/actions/                       四张蓝白校服第一视角动作图
gallery/pet-actions-summer-v2/         六张透明夏装 Pet 动作图
gallery/character-sheets/              夏装、校服与日常服饰分解图
pets/campus-white-moon-daily/          日常基础版与 QA
pets/campus-white-moon-summer-v2/      夏装互动版与 QA
pets/campus-white-moon-summer-v3/      夏装白月光版与 QA
pets/campus-white-moon-tracksuit/      蓝白运动校服版与 QA
```

## 隐私与素材边界

仓库只包含最终 Pet、脱敏 QA、动作预览和生成插画，不包含真人参考照片、私人档案、人设 YAML、提示词、生成中间文件或本机绝对路径。人物与仓库均使用通用化名称。

## License

仓库未附加开源许可。图片与角色素材仅用于个人 Codex Pet 展示和使用。

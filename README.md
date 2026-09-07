# WCF 中式美学 · WCF Chinese Aesthetics

> 中式古风 / 田园 / 宫廷 / 庭院 / 仙侠题材的 AIGC 视频与图片提示词工程库。
> A production-grade prompt engineering library for Chinese classical aesthetics — ancient style, pastoral, imperial, garden and xianxia imagery in AI video & image generation.

---

## 这是什么 / What is this

一套从「灵感 → 素材 → 成片」全链路的中式美学提示词系统，核心是**数据库化素材库 + 规则层 + 成品案例库**：

- **素材层**：`P` 人物库（P01–P30）· `D` 道具库（D01–D50）· `S` 场景库（S01–S30）· `A` 动作库（A01–A86）· `I` 互动库（I01–I30）· `R` 动态规则库
- **规则层**：`N` 负面词 / 纠错规则 · `C` 自动调用规则（题材解析 → 选材 → 数量限制 → Prompt 总装 → 连续性检查）
- **成品层**：`CASE` 完整案例库（CASE01–CASE22，每个含 ① 图片版 ② 图生视频版 ③ 5 秒动态版，含节日系列：春节贴春联 / 端午包粽 / 中秋拜月 / 七夕乞巧 等）
- **生产闭环**：图片 → 首帧 → 图生视频 → 多镜头 → 拼接 → 声音 → 成片验收 → 生产数据反哺

覆盖题材：点茶、香道、婚嫁、节气节日、古代生活、女性写真、宫廷、民俗、仙侠巨物……可直接按编号调用，像搭积木一样组合出完整 Prompt。

## 文件清单 / Files

| 文件 | 说明 |
|---|---|
| `WCF-Chinese-Aesthetics-Prompt-Library.md` | 主文档（完整提示词工程库，含全部素材库、规则、CASE 案例） |
| `SKILL.md` | 可安装的 AI 技能定义（供 Claude / Codex / 豆包等工具加载，说「WCF skill」「中式美学」即可触发） |
| `README-zh-skill-guide.md` | 中文技能说明书（回看版：定位、触发方式、编号表、使用流程） |

## 快速上手 / Quick Start

### 1. 直接抄案例（最快）
在主文档搜 `CASE`，找到同题材案例（如 `CASE21 七夕穿针`），复制 ① 图片版 / ② 图生视频版 / ③ 5 秒动态版，替换人物/场景/道具编号即可。

### 2. 按编号组合
```
人物 P01（宋代闺阁少女）+ 场景 S03（茶室）+ 道具 D01/D02/D03（茶盏/茶壶/茶筅）
+ 动作 A02（点茶）+ 互动 I03/I04 + 动态 R + 光影 + 构图 → 完整 Prompt
```
一条画面建议：`1 个人物 + 1 个主场景 + 1～3 个核心道具 + 1 个主动作 + 1～2 个微动作 + 1～3 个动态细节`。

### 3. 作为 AI 技能安装
把 `SKILL.md` 放入任意支持 Skill 的工具目录（如 `.claude/skills/`、`.codex/skills/`），然后说「**WCF skill**」或「**中式美学**」即可触发；古风 / 汉服 / 宋制 / 田园劳作 / 世家园林 / 宫廷大殿 / 庭院文事 / 仙侠巨物 等关键词也会自动命中。

## 三条铁律 / Hard Rules

1. **字幕 / 文字卡不进生成画面**——后期剪辑叠加（文字 90% 概率乱码）
2. **逐条输出**——视频按镜头、图片按张
3. **交付中英双语**——模板库内只存中文（入库不加英文版）

## 设计理念 / Philosophy

- **谁 / 在哪 / 拿什么 / 做什么 / 怎么动** 五维拆分：`P=人物` `S=场景` `D=道具` `A=动作` `I=互动` `R=动态变化`
- **一个实体只有一个主归属**：茶盏属于 `D`（是什么），被注入茶汤属于 `I`（怎么互动），水面涟漪属于 `R`（怎么变化），互不污染
- **先保"画的是什么"，再保"画得漂亮"**：S 级信息（身份/外貌/服装/时代/核心道具/动作/场景）优先于 A 级氛围词，C 级重复形容词可删
- **连续性优先**：人物锁定卡 + 锚点段原样复制 + 5 秒动态工业模板（0–1s 稳定 → 1–3s 主动作 → 3–4s 辅助动态 → 4–5s 动作落点）

## 许可 / License

本项目采用 **Creative Commons Attribution 4.0 International (CC BY 4.0)** 许可。
This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

- 可以：自由分享、修改、商用 —— 只要**署名**（注明作者与本项目链接）
- 说明：库内案例 Prompt 可自由用于个人与商业创作；引用素材库结构 / 规则时请署名本项目

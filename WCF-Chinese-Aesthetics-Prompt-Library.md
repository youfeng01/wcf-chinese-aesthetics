# WCF 中式美学 · 提示词工程库（V5.11 生产系统版）

> 参考视频：《中式古风婚嫁习俗》AIGC 短片（63s / 1080p / 16:9）
> 用途：复刻同类"古风习俗科普"视频的分镜、风格与光影，可换题材复用
> 模型提示：seedance_2.0_fast / 2.0 单条 5-15 秒，2.5 单条 5-30 秒；MiniMax 海螺 H3 单次 4-15s（可延伸至 ~30s，2K 原生立体声）

## 版本记录

| 版本 | 日期 | 核心改动 |
|---|---|---|
| V5.16 | 2026-09-08 | 新增「二十一、胡金铨武侠美学」章（King Hu Cinematic Wuxia·光影/雾气/空气感强化版）：核心气质/世界观/空间美学/色彩系统/雾气空气感（用户提供定义）+ WCF 配套补全（运镜语言/负面词/双语模板/与 V1-V6 对接表）。想快速调出：搜「胡金铨」「King Hu」「侠女」「雾气」「孤绝」 |
| V5.15 | 2026-09-08 | 吸收 Higgsfield 开源 95 分钟 AI 长片《HELL GRIND》工程方法论 8 项（115,446 次生成记录实测）：①中式技术底座 12 行（全镜共用·中英双版）②动作按秒拆节拍 + 角色当前状态/承接段 ③约束即导演（收窄+锚点+尺度）④音频段强制「仅环境音·无音乐」⑤资产状态化 + 标签引用（@角色_状态）⑥写行为不写感受 + 微生命法则 ⑦GEO 站位几何 + 首镜空镜 ⑧镜头筛选分级 P0-P3 + 失败保留。全部落在新「二十」章；组装公式/负面词/生产管理三处加引用 |
| V5.12 | 2026-09-08 | 飞天琵琶·仰拍巨物入库（用户实测图）：①S31 新场景·琉璃巨涡仙阙（仰拍巨物对比构图公式：人物底1/3 + 巨物上2/3）②CASE23 图片提示词范本（双语原文 + 五矿物宝石色配方 + 学习拆解） |
| V5.11 | 2026-09-07 | AI技能目录六大入库（仙宫巨物观实测+官方规范+模板库）：①画质净化段实战完整版（仙宫巨物观 170 张批次实测·GPT-Image-2·比基础版更长更严）②三视图人物锁定卡（21:9 角色设定卡·一致性章节·先锁人再开镜）③H3 提示词标准结构（MiniMax 官方五模式 T2VA/I2VA/FL2VA/L2VA/Ref2VA + 三字段正文规范 + 运镜三要素 + 写法红线）④A 动作库补充·面部微表情表演库（22 种·按时间线写面部/呼吸/身体·图生视频表演层）⑤C01 补充·场景提取指令（古风 4 视角·从文案一键提场景卡）⑥CASE21-22 仙宫巨物观 H3 整条视频实战范本（云上初行/金殿问琴·5 镜 21s·锁构图推运镜） |
| V5.10 | 2026-09-07 | Cinema DNA references 三件套（九镜协议/反AI补丁/full-spec）六块入库：①多镜提示词模板（英文共同基底+单镜差异+三镜焦段节奏 24-28/32-50/50-85mm+三联 6 模板）②反油腻优先写/避免写+东方题材负面追加段（no xianxia glow 等）+暖金校准句式 ③负面前景规则（前景 6 功能/拒绝 5 种）④视觉主引擎 8 选 1（重点东方场面：山水藏人·静极生动·长卷空间）⑤叙事素材（物理约束清单+18 故事动词+空间叙事痕迹 9 种+安全拦截改写） |
| V5.9 | 2026-09-07 | Cinema DNA 3.0 深挖八样全入库：①连续性圣经 10 字段（主角 4-6 锚点·细节越多漂移越严重）②色彩物理叙事（色彩命题 5 步：2 主色域+1 过渡+1 强调+现实来源+镜头间变化原因）③镜头编排工具（镜头账本 7 字段+相邻镜头变化 9 选 4+每镜 5 个 1）④成像基底 4 种+英文基底段 ⑤不可立即解决的状态（钩子用事实不用情绪词）⑥验收评分制（100 分制<82 不交付+一票否决 5 条）⑦参考图原创隔离（只抽 1 个主维度） |
| V5.8 | 2026-09-07 | Cinema DNA 实战规则四样入库（GitHub 仓库实测 dacnay816y62-hub/cinema-dna-21x9x3）：①六章新增「构图判断工具」小节（构图压力 6 类型：被观察/被困住/关系疏离/权力不对等/心理失衡/感官插入+古风应用例；视线流量句：视线从 A 进入被 B 放慢落到 C 被 D 带走，写不清=元素堆叠）②十七章新增「反模板清单」（中文自查+英文负面段 no collage...no television-drama blocking+避空泛词 masterpiece/epic/beautiful/dramatic 等）③多镜头收尾规则（第三张不是死物件：六种替代收尾） |
| V5.7 | 2026-09-07 | 吸收 Cinema DNA 21×9×3 V2.0 理念：生产管理系统章节开头新增「指导思想」两条（①判断优先于堆词——镜头判断系统而非关键词库，判断对了 prompt 自然成立 ②反「电影感模板化」——减少电影感/大片感空词，升级镜头判断；词库素材=判断后的填充物，非堆砌来源；全文档生效） |
| 待定 | — | **V4.0 待拆计划**（按优先级排列）：①镜头级成品案例库——用户最想要"直接能用的完整分镜"（春节/端午/中秋/元宵/成人礼等 7-10 套，首批已见 3.5.19/3.5.20）②各平台实测参数对照——降低试错成本，标注截止日期与版本号（豆包2.5/可灵1.6/海螺H3/即梦4.0）③题材表按热点滚动更新——庙会/社火/造纸/刺绣等，按需补充即可 |

> 📦 完整历史版本（V1.0-V5.6）已归档至文档末尾「附录·历史版本归档」。顶部只留最近 5 条，日常使用无需阅读历史。

## 快速跳转索引（按功能）

| 用户想找什么 | 直接跳转 |
|---|---|
| 图片 / 视频入口判断（生成什么先看这里） | 〇 |
| 怎么把场景写得高级 | 三 |
| 风格化配方（四感/治愈系/美人/真人/双人互动） | 二（四感词库①-⑪ + 治愈系配方）/ 四（美人写真六层配方 + 真人感配方 + 双人互动构图） |
| 人物脸上的光怎么写 | 二（人物光影专章） |
| 斑驳光影 / 漏光投影怎么写 | 二（斑驳光影专章） |
| 天气时令光效（雪/雨/雾/月夜/黄昏/秋日） | 二·五（天气时令光效速查表） |
| 中式美学场景（云海/天宫/巨物）怎么写 | 三（3.5 中式美学场景专章） |
| 人物怎么写不崩 | 四 |
| 古风妆发 / 妆容怎么写 | 四（古风妆发大全） |
| 脸型 / 眼睛 / 眉毛怎么写 | 四（面部特征词库） |
| 身材 / 体态怎么写 | 四（身材体态词库） |
| 年龄怎么写（少女/御姐/老妪） | 四（年龄锚点） |
| 不同人物 / 角色提示词 | 四（人物角色卡库） |
| 儿童角色（垂髫/总角/提灯/纸鸢/学童） | 四（人物角色卡库 41-45） |
| 老人角色（老翁/老妪/祖父/纺线/雪中） | 四（人物角色卡库 46-50） |
| 视频和图片怎么互转（图生视频/视频抽帧做图） | 七（双向转换速查表） |
| 仙子 / 飘逸长裙女子 | 四（仙子与绝美女子角色卡） |
| 少女/御姐/高冷…气质女子 | 四（女子气质人设卡） |
| 结尾祝词 / 文案金句 | 十五（通用古风金句库） |
| 材质怎么写（丝绸/青铜/玉…） | 三（材质大全） |
| 镜头怎么运动 | 五 / 六 |
| 怎么拼一条能用的 prompt | 七 |
| 人物段怎么排（贵妇主从/双人/单人） | 七（人物结构卡 X1-X4） |
| 换题材 / 模板怎么用 | 八 / 九 / 十 |
| 婚嫁 / 写真现成示例 | 十一 / 十二 |
| 题材有哪些 / 自己填题材 | 十三 |
| 运营选题排期（节日日历/何时发什么） | 附录·节日与题材排期指南 |
| 素材库（人物/服饰/道具/场景/动作/互动/动态/总装） | 附录·直接调用素材库 A-H |
| 素材库条目（P 人物/D 道具/S 场景/A 动作/I 互动/CASE 成品） | 附录·古风习俗视频提示词素材库 V1.0 |
| 素材库规则（R 动态/C 调用/N 纠错/主归属） | 附录·素材库规则说明 |
| 整条视频级分镜（CASE 多镜头标准·7 镜工程版） | 素材库·CASE 多镜头标准 |
| 自动调用链路（输入题材→四联输出） | 素材库·C06 |
| 全镜通用技术底座 / 动作节拍 / 约束即导演（HELL GRIND 吸收） | 二十 |
| 资产状态化标签 / 写行为不写感受 / GEO 站位 / 筛选分级 P0-P3 | 二十 |
| 图片→视频生产闭环（首帧→图生→多镜头→拼接） | 素材库·C07 |
| 5 秒生成限制（工业模板·8 条） | 素材库·CASE 多镜头标准 |
| CASE 声音系统规格（8 项） | 素材库·CASE 声音系统规格 |
| 平台实测参数对照（待实测填写） | 十六（第八阶段） |
| 平台生产参数库（23 列·含成功率/成本） | 生产管理系统（V5.2·七） |
| 题材滚动扩充库（选题清单/待补） | 十三（题材滚动扩充库） |
| 生产管理系统（任务单/镜头卡/QC/成本/版本/验收） | 生产管理系统（V5.2） |
| 双引擎生产（GPT Image-2 定形 × MiniMax H3 定动） | 双引擎生产系统（V5.3） |
| 后期字幕文案 | 十四 |
| 运营避坑 | 十五 |
| 不同工具怎么喂 | 十六 |
| 不要什么 / 常见翻车点 | 十七 / 十九 |
| 声音 / BGM / 音效 | 十八 |

---

## 〇、入口判断与身份声明（AI 收到本文件后先读这里）

> 本文件是一份 AIGC 视频/图片提示词工程模板包，我是你的执行助手。
> 收到本文件后，第一件事不是读完整文档，而是先问用户下面 3 个问题，**不要假设，不要猜**：
>
> 1. **你要生成什么类型？** 视频 / 图片 / 两者都要？
> 2. **什么题材？** 古风婚嫁 / 现代咖啡 / 科幻赛博 / 其他（请说明）？
> 3. **输出形式？** 单张 / 单条 / 全套分镜（多镜头）？
>
> 全程遵守四条规则：
> 1. **字幕不进画面**：所有文字卡/字幕/对白单独列出（「十四」），后期剪辑叠加
> 2. **逐条输出**：视频按镜头、图片按张，按「七、组装公式」拼 prompt
> 3. **题材路由**：婚嫁→「十一」｜写真→问古今后走「十二」｜其他→「八」+「十三」
> 4. **双语输出**：每条 prompt 同时给中英两版（先中文、后英文，两段并列），逐条交替输出——中文版喂豆包/可灵/海螺 H3，英文版喂 GPT-Image/Midjourney/Runway/Sora。**非中英市场（日韩/东南亚）**：按「关键词直译 + 保留风格词英文」替换——场景/人物/光影词翻成目标语言，风格与质感词保留英文原文（如 cinematic, film grain, soft light）效果最稳；不要整句机翻，模型吃关键词不吃语法
> 5. **四感默认（宋/中式题材必开）**：只要题材是「宋 / 宋式 / 中式」，基调默认叠加「柔和·唯美·细腻·电影化」四感（词库见「二、四感词库」），写进风格基调段；除非用户明确要求其他质感（硬朗/暗黑/赛博/动画等），否则不省略、不替换。**排除项：现代国潮 / 赛博国风 / 暗黑国风不触发四感默认**——用户说的是"国风"但带现代/赛博/暗黑前缀时，以用户指定的质感为准，不叠四感（例：赛博国风→霓虹冷调，暗黑国风→硬朗高对比，均不加柔光奶油感）
> 6. **默认 14 步详装**：凡写精细镜头 / 图片卡 / 正式交付，默认按「七、14 步详装结构」逐项输出（含第 3 步「场景与元素」——人群/动物/植物/器物陈设逐一点名；视频把第 13 步「构图角度」改为「运镜」）；只有用户明确要快速出片时才用 7 段总装公式
> 7. **人物七件套（写人必带）**：第 2 步「主体」写人物时，默认按七件套写全——① 年龄锚点 ② 面部（脸型/眼/眉/鼻/唇）③ 妆发（发型/妆容/首饰）④ 身材（身形/曲线/体态）⑤ 服装（三段式分层）⑥ 动作·道具·神态 ⑦ 气质词；除非用户明确要极简描述，否则缺层要补

### 根据用户回答，AI 执行对应路径

| 用户回答 | 执行路径（一条龙） |
|---|---|
| 视频 + 任何题材 | 先看「八」定骨架结构 → 再用「七」逐镜头组装 → 最后「十四」加字幕；题材取值查「十三」 |
| 图片 + 古风/现代题材 | 用下方「图片生成入口风格选单」选基调 + 单画面描述 |
| 图片 + 科幻/其他非常规题材 | 用图片选单选基调 + 用户描述场景 |
| 两者都要 | 先出图片作参考帧/海报 → 再用图片首帧跑图生视频（分两步，先图片后视频） |
| 直接生产 / 收到 PROJECT 任务单 | 走「生产管理系统（V5.2）→ 双引擎生产系统（V5.3）」：任务单 → C06 素材调用 → 镜头卡 → GPT Image-2 出图（母版）→ IMAGE-QC → 首帧锁定 → MiniMax H3 生视频 → VIDEO-QC → C05 连续性 QC → 成片验收；素材锁定 CHAR/OBJ/SET；双引擎职责：图片定形 / 视频定动 |

### 图片生成入口风格选单（GPT-Image-2 / Midjourney 通用）

用户选「图片」时，AI 从以下 5 种风格中选一种（或问用户要哪种）：

| 编号 | 风格名称 | 一句话描述 | 适用场景 |
|---|---|---|---|
| P1 | 电影剧照感 | 浅景深，低反差柔光，像电影暂停的一帧（叙事性图片首选） | 古风/现代叙事类 |
| P2 | 杂志大片感 | 高对比，精修人像，光影刻意，像时尚大片 | 写真/人物特写 |
| P3 | 东方水墨感 | 留白，低饱和，墨色晕染，绢帛质感 | 古风意境/诗意图 |
| P4 | 赛博霓虹感 | 冷色调，霓虹光晕，暗部深邃，雾感 | 科幻/都市夜 |
| P5 | 极简留白感 | 干净背景，主体突出，大量负空间 | 产品/构图感强/文字排版 |

**P1-P5 完整描述（GPT-Image-2 直接复制）**：

- **P1 电影剧照感**：电影剧照感，浅景深低反差柔光，像电影暂停的一帧，胶片颗粒轻微，主体锐利背景柔化，色调统一，叙事性构图（叙事性图片首选；与视频 V6 同源，静态帧母版可互用）
- **P2 杂志大片感**：杂志大片感，高对比精修人像，光影刻意塑形，时尚大片质感，皮肤质感真实，背景简洁有设计感，主光明确
- **P3 东方水墨感**：东方水墨意境，大量留白，低饱和墨色晕染，绢帛宣纸质感，单色或淡彩主调，线条简练，空灵
- **P4 赛博霓虹感**：赛博霓虹感，冷色调霓虹光晕，暗部深邃带雾感，雨夜湿润反光，蓝紫主调粉橙点缀，光比强烈
- **P5 极简留白感**：极简留白，干净背景大量负空间，主体突出，低饱和莫兰迪色，柔和阴影，构图精准

**P1-P5 英文关键词速查（喂英文工具微调用·MJ/Runway 直接取词）**

| 风格 | 英文关键词（直接喂英文工具） |
|---|---|
| P1 电影剧照感 | cinematic film still, shallow depth of field, low contrast soft light, film grain |
| P2 杂志大片感 | editorial fashion portrait, high contrast, sculpted lighting, studio quality |
| P3 东方水墨感 | Chinese ink wash painting, negative space, low saturation, rice paper texture |
| P4 赛博霓虹感 | cyberpunk neon, cool blue-purple tone, wet reflective surfaces, volumetric fog |
| P5 极简留白感 | minimal white space, clean composition, muted pastel tones, soft shadows |

> 场景/人物/光影英文关键词：散布在各章节的中英对照表中（四感词库、美人配方、特写配方、双人互动等），喂英文工具时优先从对应章节取英文关键词，不建议整句直译。

**图片 prompt 组装公式（比视频版少两个字段）**：

```
[风格选单中的一句话描述] + [场景：空间+材质+动态] + [主体：人物/物体+状态] +
[构图：景别+视角] + [光影：按第二章公式] + [负面词：按第十七章]
```

### 图片 9 步精装结构（默认写法·对标视频 14 步）

> ⭐ 凡写正式交付的图片 / 海报 / 首帧参考图，默认按本结构逐项输出；快速随手拍才用 5 字段压缩版。

1. 风格选单（从 P1-P5 选一句整段复制）
2. 场景（空间 + 材质 + 光效 + 动态元素）
3. 主体（人物七件套，同视频标准）
4. 场景配角与陈设（第 3 步同款：人群/动物/植物/器物点名）
5. 色调 + 氛围
6. 光影美学（按第二章公式）
7. 构图（景别 + 视角 + 构图法则，去掉运镜）
8. 质感 + 画质（胶片/绢帛/油画等母版质感锚点）
9. 负面词（按第十七章）

**图片 9 步成品示范（纳采·P1 电影剧照感）**

> 以下是「图片 9 步精装结构」的完整填充示范，照抄改词即可。

1. **风格选单**：P1 电影剧照感，浅景深低反差柔光，像电影暂停的一帧，胶片颗粒轻微，色调统一
2. **场景**：暮色朱漆大门，檐角宫灯如豆，青砖地釉光微泛，门前石榴树影婆娑，落红轻旋
3. **主体（人物七件套压缩）**：媒人着青绿古装，广袖垂落，腰间佩玉轻晃，双手捧雁立于阶前，衣袂微动，神态恭敬
4. **场景配角与陈设**：远处暮色渐浓，门内隐约透出暖光，无其他人物
5. **色调+氛围**：暖金低饱和，琥珀色温，庄重古雅，静谧叙事
6. **光影美学**：侧逆暖光，金尘漂浮，高光柔和，暗部保留细节（按二章公式）
7. **构图**：低机位平视半身构图，大雁在前景清晰，人物后方虚化
8. **质感+画质**：轻微胶片颗粒，浅景深，奶油散景，绢帛质感
9. **负面词**：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊

> 把第 2/3/7 步替换成你的场景/人物/构图，其余照抄即可换题材。


### 画质净化万能前置段（V5.6 入库·Flova 实测·可整段垫在任何 prompt 最前面）

> 用途：不锁题材的通用画质控制段。任何古风/仙侠/写真画面开头垫上它，专治「细节堆砌、噪点、脏感、塑料感、过锐化」。中文喂豆包系，英文喂 MJ/GPT-Image。想快速调出：搜「画质净化」或「画面干净」。

**中文版（整段复制）**：
```
画面干净通透，整体细节克制且有层次，主体清晰，背景细节适度简化。保持大面积材质平滑、连续、自然，减少无意义的碎小纹理、颗粒、斑点和随机锐化痕迹。远处人物、建筑和环境只保留清晰轮廓与主要结构，不强行生成复杂细节。自然景深，真实空气透视，焦点区域细腻清晰，非焦点区域柔和过渡。光影纯净统一，色彩平滑，明暗关系稳定，低噪点，低颗粒感，无脏污感，无塑料质感，电影级干净画质。
```

**英文版（整段复制）**：
```
Clean and translucent picture, restrained and layered overall detail, clear subject, appropriately simplified background detail. Keep large material surfaces smooth, continuous and natural; reduce meaningless fine textures, grain, spots and random sharpening artifacts. Distant figures, architecture and environment keep only clear silhouettes and main structure, without forcing complex detail. Natural depth of field, true atmospheric perspective; focal areas crisp and delicate, out-of-focus areas transition softly. Pure and unified lighting, smooth colors, stable light-dark relationship, low noise, low grain, no dirty feel, no plastic texture, cinematic clean image quality.
```

> 组合示例：`画质净化段 + 9 步结构第 1-8 步 + 负面词`。若画面要保留胶片颗粒/材质粗糙感（如粗陶、麻布），删掉「减少纹理」半句即可。

**实战完整版（V5.11 入库·仙宫巨物观 170 张批次实测·GPT-Image-2 2048×1152）**：

> 更长更严的画质控制段，专用于巨物/大场景/大全景——第五批 50 张全量实测，垫在 prompt 末尾同样有效，也可以直接替换上面基础版。中文释义：画面干净通透、细节克制有层次、主体清晰、背景简化、大面积材质平滑连续无碎纹理、远处人物/建筑只留剪影与主体结构、自然景深与空气透视、焦点锐利、焦外柔和过渡、光影纯净统一、低噪点低颗粒、无脏感无塑料感、电影级干净画质。

```
clean translucent image, restrained details with depth and layers, clear subject, simplified background details, smooth continuous natural large surfaces without meaningless texture, grain, spots or random sharpening artifacts, distant figures and architecture kept as clear silhouettes and main structures only, natural depth of field, realistic aerial perspective, sharp detailed focal area, soft transition out of focus, pure unified lighting, smooth colors, stable light and shadow, low noise, low grain, no dirty or plastic look, cinematic clean image quality
```

> 想快速调出：搜「画质净化」/「画面干净」/「巨物」。完整 170 张实测提示词见归档「AI技能-归档\01-仙宫巨物观-实战提示词库」。

#### 成像基底（Cinema DNA·V5.9 入库·质感定调）

> 写质感前先定“成像基底”（模拟哪种胶片/拍摄方式），再决定颗粒、反差、锐度：

- **35mm**：标准电影感，颗粒细腻均匀
- **16mm**：纪录片/复古感，颗粒更粗、反差更大
- **早期数字**：低反差、柔和、略糊
- **纪录式手持**：轻微晃动、自然光、不完美

**英文基底段（整段可复制·垫在画面描述后）**：
```
standalone live-action feature-film still, practical location, real actors, physically plausible set and props, restrained production design, soft highlight roll-off, medium-low microcontrast, subtle uneven grain, local optical softness, natural skin texture
```

### 图片风格决策树（按出片用途选，替代按题材选）

**问自己 3 个问题**：

1. **这图用来干什么？**
   - 视频首帧 / 分镜参考 / 故事感海报 → **P1 电影剧照感**
   - 人物特写 / 账号头像 / 写真集 → **P2 杂志大片感**
   - 诗意留白 / 古风意境 / 国风封面 → **P3 东方水墨感**
   - 赛博/科幻/夜都市氛围 → **P4 赛博霓虹感**
   - 产品展示 / 干净排版 / 极简构图 → **P5 极简留白感**
2. **人物在画面中占多大比例？**
   - > 50%（特写/近景）→ P2（杂志感）或 P1（叙事感）
   - 30-50%（中景）→ P1（叙事感）
   - < 30%（全景/远景）→ P3（水墨感）或 P1（叙事感）
3. **要突出「氛围」还是「细节」？**
   - 氛围优先 → P1（柔光叙事）或 P3（水墨留白）
   - 细节优先 → P2（精修质感）或 P5（干净突出）

> **锁 P 后怎么用**：3 个问题走完锁定 P1-P5 中的某一值 → 从上方「P1-P5 完整描述」复制对应整段 → 填入「图片 9 步精装结构」第 1 步 → 继续填后续 8 步即可成图。

### 图片生成前的关键问题（先问再出）

当用户说「两者都要」或「先出图再做视频首帧」时，AI 必须先问：

**这张图片要当首帧用吗？**
- 是 → 走「首帧专用构图规则」（见下方）
- 否 → 走普通 P1-P5 选单

**首帧专用构图规则**（图片做视频首帧时必加）：
- 人物置于画面中央偏下 1/3 处，头顶留白 ≥ 20%（给运镜推拉留空间）
- 景别选「中全景」或「环境全景」，不选特写（特写做首帧推不了镜）
- 动作选"进行中"状态（抬手一半 / 转身途中），视频才能接续
- 图片底部留黑/留虚化（后期叠字幕/标题时不被遮挡）
- 同一个场景出 3 张备选首帧（远景/中景/近景各 1），视频生成时再挑

> **首帧工作流完整闭环见第十章「首帧工作流三原则」**——图生视频时，首帧图片的构图规则在本节，生成后的选帧与匹配规则在第十章，两处联动使用（这是同一件事的两步）。

### 图片生成前检查清单（对标视频版）

生成图片前，逐项打钩：
- [ ] 风格选单是否从 P1-P5 整段复制（不是自己编）
- [ ] 场景是否含 1 光效 + 1 材质 + 1 动态元素
- [ ] 人物是否含七件套（年龄+面部+妆发+身材+服装+动作道具神态+气质）
- [ ] 动作是否含「进行时」动词（抬手/转身/拈起/回眸）——静止摆拍必翻车
- [ ] 光影是否按第二章公式（光源+光位+光质+明暗）
- [ ] 构图是否明确（景别 + 视角 + 构图法则）
- [ ] 是否需要英文版？（喂 MJ/Runway 时选是；喂即梦/豆包时选否）
- [ ] 若需英文版，是否已从「P1-P5 英文关键词速查表」取词？
- [ ] 是否标注「图片用途」：单发 / 视频首帧 / 海报封面 / 参考图

### 3.5.18 图片成品案例库（按 P1-P5 风格·直接复制）

> 想生成一张图片时，从 5 个成品案例里挑一个改 2-3 个词，不用从零拼。

**P1 电影剧照感 · 古风纳采**

> 电影剧照感，浅景深低反差柔光，像电影暂停的一帧。暮色朱漆大门，檐角宫灯如豆，青砖地釉光微泛，石榴树影婆娑落红轻旋。媒人着青绿古装捧雁立于阶前，衣袂微动，神态恭敬。低机位平视半身构图，大雁在前景清晰，人物后方虚化。侧逆暖光，琥珀色温，金尘漂浮。85mm f/2.0，浅景深，胶片颗粒轻微。负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊。

**P2 杂志大片感 · 国风美人特写**

> 杂志大片感，高对比精修人像，光影刻意塑形。年轻女子着唐制齐胸襦裙，象牙白缎面衬裙+灰蓝薄纱外衣绣金线牡丹，珊瑚橘织锦腰带。完美鹅蛋脸，大杏眼双眼皮星光美瞳，柔和卧蚕，珊瑚橘唇微启。暖灰褐影棚背景，银白轮廓光，冷白正面主光均匀铺满面部。竖构图，胸部以上特写，人物居中。85mm f/1.4，浅景深，皮肤质感真实。收尾词：Opulent, airy, serene. 负面词：手部畸形，塑料皮肤，过度磨皮，低质量。

**P3 东方水墨感 · 孤舟寒江**

> 东方水墨意境，大量留白，低饱和墨色晕染，绢帛宣纸质感。寒江独钓，孤舟一叶，蓑衣老翁持竿而坐，远山隐于雾霭，水面仅一线墨痕。单色淡彩主调，灰白与淡赭石色，线条简练空灵。全景横构图，主体置于画面左下三分之一处，右上大面积留白。天光漫射，雾霭氤氲，逆光剪影。负面词：鲜艳色彩，杂色，人物特写，现代元素，低质量。

**P4 赛博霓虹感 · 雨夜街角**

> 赛博霓虹感，冷色调霓虹光晕，暗部深邃带雾感。雨夜街巷，霓虹灯牌在水洼中倒映成光斑，蒸汽从通风口升腾。主角穿黑色风衣站立伞下，侧脸被粉紫霓虹照亮，目光望向远处。中景平视构图，前景伞沿虚化。顶光+侧逆光混合，蓝紫+冷粉色温，光比强烈。负面词：手部畸形，五官错位，过度曝光，低质量模糊。

**P5 极简留白感 · 静物茶席**

> 极简留白，干净背景大量负空间，主体突出。低饱和莫兰迪色，柔和阴影，构图精准。素白墙面，旧木案板，粗陶茶壶与一盏青瓷杯并列，壶口一缕蒸汽升腾，光影从左侧斜照，在桌面上拉出长条阴影。俯拍构图，主体居中偏下，上方留白 50%。自然光漫射，低反差柔和。负面词：杂乱背景，多余物品，鲜艳色彩，低质量。

**首帧备选示例·纳采（同一场景 3 张·首帧专用构图规则的实际样子）**

- **远景首帧（定场用）**：电影剧照感。暮色朱漆大门全景，媒人捧雁立于阶前，人物占画面 10%，头顶留白 30%。侧逆暖光，琥珀色温。85mm f/2.8。
- **中景首帧（叙事用）**：电影剧照感。媒人捧雁立于阶前，人物占画面 40%，头顶留白 25%。大雁在前景清晰，人物后方虚化。侧逆暖光。85mm f/2.0。
- **近景首帧（情绪用）**：电影剧照感。媒人双手捧雁，雁笼红绸结特写，人物半身入画，头顶留白 20%。侧逆暖光，金尘浮动。85mm f/1.8。

> 用法：同一场景按"远景/中景/近景"各出一张，图生视频时再挑最接得住下一镜的那张。
> **焦距选择逻辑**：远景用更小光圈（f/2.8）保证前后景都清晰；近景用更大光圈（f/1.8）强化背景虚化、突出主体；中景居中（f/2.0）。换题材时按景别自行调整。

**图片生成示例（对比视频版）**

用户说："我想生成一张古风纳采的图片"
→ 图片 + 古风题材 → P1 电影剧照感

> 电影剧照感，浅景深低反差，像电影暂停的一帧。暮色朱漆大门，檐角宫灯如豆，青砖地釉光微泛，石榴树影婆娑落红轻旋。媒人着青绿古装捧雁立于阶前，衣袂微动，神态恭敬。低机位平视半身构图，大雁在前景清晰，人物后方虚化。侧逆暖光，琥珀色温，金尘漂浮。负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊。

用户说："我想生成一张赛博朋克夜市的图片"
→ 图片 + 科幻题材 → P4 赛博霓虹感

> 赛博霓虹感，冷色调霓虹光晕，暗部深邃。雨夜街巷，霓虹灯牌在水洼中倒映成光斑，蒸汽从通风口升腾。主角穿黑色风衣站立伞下，侧脸被粉紫霓虹照亮，目光望向远处。中景平视构图，前景伞沿虚化。顶光+侧逆光混合，蓝紫+冷粉色温，光比强烈。负面词：手部畸形，五官错位，过度曝光，低质量模糊。

### 视频生成入口风格选单

用户选「视频」时，先确认题材，再从以下 5 套基调中选（完整描述在「一、风格基调模板包」）：

| 编号 | 风格名称 | 对应第一章基调 |
|---|---|---|
| V1 | 古风·庄重仪式 | 中式古风影视质感，暖调 |
| V2 | 古风·清冷意境 | 水墨质感，冷灰/青绿调 |
| V3 | 现代·都市日常 | 自然光为主，低反差 |
| V4 | 现代·赛博霓虹 | 冷暖对比，霓虹光晕 |
| V5 | 现代·极简留白 | 自然光漫射，低饱和 |
| V6 | 电影质感·通用 | 35mm 胶片，青橙色调，2.35:1 宽银幕（视频专用；亦可作静态帧母版） |

**现代题材选题指南（不知道选哪个基调？先对号入座）**

| 用户想拍什么感觉 | 用哪个基调 | 为什么 |
|---|---|---|
| 干净日常 / 咖啡店 / 晨起 | V3 现代·都市日常 | 自然光低反差，不出戏 |
| 夜晚街景 / 霓虹 / 都市失落感 | V4 现代·赛博霓虹 | 冷暖对比，天然故事感 |
| 安静独处 / 极简空间 | V5 现代·极简留白 | 干净克制，不出戏 |
| 一切有电影感但不要古风 | V6 电影质感·通用 | 万能兜底 |
| 国风元素+现代场景（赛博国风等） | V4 或 V6 + 新中式点缀 | 四感不叠加（见〇章规则 5） |

**V1-V5 完整描述（可直接复制，无需跳转第一章）**：

```
【V1 古风·庄重仪式】中式古风影视质感，AIGC 生成画面，电影感浅景深，轻微胶片颗粒，暖色调统一，烛光与红灯笼暖光照明，侧逆光勾轮廓，低反差柔光，暗部保留细节，高光不溢出，1920x1080 横屏，
```

```
【V2 古风·清冷意境】古风水墨意境，低饱和冷调，宣纸/绢帛质感，留白构图，天光漫射，青灰/青绿主色，雾霭氤氲，逆光剪影，暗部深邃，高光克制，1920x1080 横屏，
```

```
【V3 现代·都市日常】现代电影质感，AIGC 生成画面，自然光为主，胶片颗粒，低反差柔光，色调视题材而定（都市冷调 / 日常暖调），侧逆光勾轮廓，暗部保留细节，高光不溢出，1920x1080 横屏，
```

```
【V4 现代·赛博霓虹】赛博朋克都市质感，冷色调为主，霓虹光晕，暗部深邃带雾感，冷暖对比（蓝紫主调 + 粉橙霓虹点缀），雨夜湿润反光，高光收敛不溢出，1920x1080 横屏，
```

```
【V5 现代·极简留白】现代极简质感，自然光漫射，低饱和莫兰迪色，大量负空间留白，主体突出，背景干净，柔和阴影，高光柔和，1920x1080 横屏，
```

```
【V6 电影质感·通用】电影级质感，35mm 胶片颗粒，青橙对比色调，柔和肩部滚降，低反差柔光，明暗过渡平滑，浅景深焦点柔和，轻微手持呼吸感，2.35:1 宽银幕黑边，1920x1080 横屏，
```

> 第一章保留同套基调作为母版，可自行增改。

### 「图片+视频」都要的常见工作流

当用户说「图片和视频都要」时，AI 按这个顺序执行：

1. 先生成 1 张图片（按图片路径）
2. 用户确认满意后，以这张图片作为首帧/参考图，再按视频路径生成序列
3. 好处：首帧锁定风格和人物造型后，后续视频的人物一致性和色调稳定性远高于纯文生视频
4. 提示词写法：视频 prompt 用「八、通用骨架」+ 将图片 prompt 中的构图/静态描述改为运镜/动态描述

---

## 一、风格基调模板包（每条 prompt 建议加在开头）

> 本段与〇章 V1-V5 完全相同，是「母版存档」：日常使用优先复制〇章版本（不跳转），
> 需要增删改基调时在此维护，改完同步〇章。

### V1 古风·庄重仪式（默认）

```
中式古风影视质感，AIGC 生成画面，电影感浅景深，轻微胶片颗粒，
暖色调统一，烛光与红灯笼暖光照明，侧逆光勾轮廓，低反差柔光，
暗部保留细节，高光不溢出，1920x1080 横屏，
```

### V2 古风·清冷意境

```
古风水墨意境，低饱和冷调，宣纸/绢帛质感，留白构图，
天光漫射，青灰/青绿主色，雾霭氤氲，逆光剪影，
暗部深邃，高光克制，1920x1080 横屏，
```

### V3 现代·都市日常

```
现代电影质感，AIGC 生成画面，自然光为主，胶片颗粒，低反差柔光，
色调视题材而定（都市冷调 / 日常暖调），侧逆光勾轮廓，
暗部保留细节，高光不溢出，1920x1080 横屏，
```

### V4 现代·赛博霓虹

```
赛博朋克都市质感，冷色调为主，霓虹光晕，暗部深邃带雾感，
冷暖对比（蓝紫主调 + 粉橙霓虹点缀），雨夜湿润反光，
高光收敛不溢出，1920x1080 横屏，
```

### V5 现代·极简留白

```
现代极简质感，自然光漫射，低饱和莫兰迪色，大量负空间留白，
主体突出，背景干净，柔和阴影，
高光柔和，1920x1080 横屏，
```

### V6 电影质感·通用（纯电影感，不限古风/现代）

```
电影级质感，35mm 胶片颗粒，青橙对比色调，柔和肩部滚降，
低反差柔光，明暗过渡平滑，浅景深焦点柔和，轻微手持呼吸感，
2.35:1 宽银幕黑边，1920x1080 横屏，
```

- English: Cinematic film look, 35mm film grain, teal and orange color grade, soft highlight roll-off, low contrast soft lighting, smooth tonal transitions, shallow depth of field with gentle focus falloff, subtle handheld breathing motion, 2.35:1 anamorphic widescreen letterbox, 1920x1080 landscape

**电影感元素补充包（可选增删，加在 V6 末尾）**

| 元素 | 写法 | 效果 |
|---|---|---|
| 变形镜头光晕 | 变形镜头光晕，蓝色水平光斑（anamorphic lens flare, blue horizontal streak） | 科幻/夜景大片感 |
| 胶片颗粒等级 | 轻颗粒（light grain）/ 中颗粒（medium grain）/ 重颗粒（heavy grain） | 质感/复古强度 |
| 画幅选择 | 16:9 标准 / 2.35:1 宽银幕 / 4:3 复古（IMAX 画幅） | 电影氛围/年代感 |
| 调色倾向 | 青橙对比（teal & orange）/ 暖金复古（warm golden）/ 冷蓝清冷（cool blue） | 情绪定调 |
| 手持呼吸感 | 轻微手持呼吸感（subtle handheld breathing）/ 稳定器滑轨（gimbal glide） | 纪录感/平稳感 |

**组合公式（V6 底色 + 37 风格滤镜）**：

```
[V6 电影质感·通用] + [选一种调色流派] + [选一种导演签名（可选）] = 完整风格基调
```

- 用法：V6 是"底色"（胶片/颗粒/画幅/影调），37 风格是"滤镜"（调色与导演视觉/平台潮流），两者叠加不互斥，**不需要替换**。
- 示例：`[V6 电影质感·通用] + [青橙对比] + [王家卫·霓虹拖影]` = "35mm 胶片质感 + 青橙对比调色 + 霓虹拖影晃动，2.35:1 宽银幕，1920x1080"
- 图片路径同理：P1 电影剧照感 = V6 的静态版，叠加调色流派即可。

### 电影风格速查库（37 风格·中英关键词）

> 挑选入口：先定「调色流派」打底 → 再叠「导演签名」定情绪 → 平台潮流直接整套用。关键词可整句粘进 prompt。

#### 一、调色流派（8 种，打底用）

| 风格 | 一眼识别 | 提示词关键词（中英） |
|---|---|---|
| 青橙对比 Teal & Orange | 皮肤暖橙、暗部泛青蓝，好莱坞标配 | 青橙对比色调，肤色暖橙，暗部青蓝（teal and orange grade） |
| 漂白跳过 Bleach Bypass | 高对比、低饱和、暗部发灰，金属感 | 漂白工艺质感，高对比低饱和，暗部银灰（bleach bypass look） |
| 克制中性调（2026 主流） | 色彩压到最低，高级灰大地色 | 克制中性色板，低饱和大地色，极简用色（restrained neutral palette） |
| 暖金复古 | 琥珀蜂蜜色高光，怀旧黄昏感 | 暖金复古调，琥珀高光，胶片暖晕（warm golden vintage） |
| 冷蓝清冷 | 月光阴天蓝，疏离北欧风 | 冷蓝清冷调，低色温，雾感（cool blue desaturated） |
| 高饱和糖果 | 马卡龙色，粉紫黄明艳，童话感 | 高饱和糖果配色，粉紫黄明艳（candy pastel saturated） |
| 黑白电影 | 强明暗，颗粒重，经典 | 黑白胶片，颗粒细腻，明暗强烈（black and white film, strong contrast） |
| 交叉冲印 Cross-processed | 色彩错位失真，青绿肤色洋红天空 | 交叉冲印失真色，非自然色彩（cross-processed colors） |

#### 色彩物理叙事（Cinema DNA·V5.9 入库）

> 先写一句“色彩命题”再写画面：**色彩不是滤镜，是事件发生方式的一部分**。不默认蓝灰阴冷；高明度、暖色和自然综合色都可以，但必须由空间与事件驱动。

1. **2 个主色域**（如：青砖灰 + 暖金烛光）
2. **1 个过渡色域**（如：暮色琥珀）
3. **1 个小面积强调色**（如：嫁衣一点绛红）
4. **每种颜色的现实来源**：服装 / 墙体 / 天气 / 实景灯 / 水面·雪地·玻璃·植物反射 / 时代材料
5. **色彩在镜头间保持 / 移动 / 消退 / 反转的原因**

#### 二、导演视觉签名（16 个，叠情绪用）

| 风格 | 一眼识别 | 提示词关键词（中英） |
|---|---|---|
| 韦斯·安德森 | 绝对对称+马卡龙配色+平面平移镜头 | 绝对居中对称构图，高饱和低明度糖果色，平面化运镜（Wes Anderson style, centered symmetry, pastel palette） |
| 王家卫 | 雨夜霓虹、抽帧慢门、广角畸变、浓烈红绿 | 港风霓虹，抽帧晃动，广角畸变，浓烈红绿色调（Wong Kar-wai style, neon rain, slow shutter） |
| 张艺谋 | 大色块统治画面，红最经典（《英雄》每段一主色） | 单一主色统治画面，高饱和红/黑白/青，仪式感构图（Zhang Yimou color symbolism） |
| 诺兰 | IMAX 实拍、宏大建筑、冷峻蓝灰、秩序感 | IMAX 画幅，实拍质感，宏大对称建筑，冷峻蓝灰（Christopher Nolan epic scale） |
| 维伦纽瓦 | 巨大物体+渺小人物、静默宏大、黄褐沙尘调 | 巨物压迫构图，人物渺小，沙尘黄褐调，静默氛围（Denis Villeneuve scale, minimal dialogue） |
| 大卫·芬奇 | 青绿暗调、室内阴郁、精密构图 | 青绿阴影调，室内暗部，精密构图（David Fincher green-teal shadows） |
| 提姆·波顿 | 哥特暗黑童话、苍白皮肤、高耸尖顶 | 哥特童话风，苍白肤色，暗黑紫绿（Tim Burton gothic fairy tale） |
| 新海诚 | 通透蓝天、光斑雨滴、日系透明感 | 日系透明光影，蓝天高光，光斑雨丝（Makoto Shinkai transparent light） |
| 宫崎骏 | 手绘水彩、云海草原、暖阳田园治愈 | 水彩手绘风，云海草原，暖阳田园（Studio Ghibli watercolor） |
| 侯孝贤/李屏宾 | 长镜头、自然光、东方留白、时间感 | 长镜头固定机位，自然光，东方留白构图（Hou Hsiao-hsien long take） |
| 是枝裕和 | 日常光线、克制近景、家庭温度 | 日常自然光，克制近景，生活温度（Hirokazu Kore-eda naturalism） |
| 库布里克 | 一点透视对称、几何强迫症、冷调广角 | 一点透视对称，几何构图，冷调广角（Kubrick one-point perspective） |
| 昆汀 | 高饱和撞色、低机位、特写暴力美学 | 低机位仰拍，高饱和撞色，复古胶片（Tarantino low angle） |
| 罗杰·狄金斯（摄影） | 光束穿尘、逆光剪影、水雾光柱 | 光束穿尘，逆光剪影，雾中光柱（Roger Deakins light beams） |
| 杜可风（摄影） | 手持晃动、胶片噪点、霓虹流光 | 手持晃动，胶片噪点，霓虹流光（Christopher Doyle handheld, film grain） |
| 塔可夫斯基（冷门高阶） | 雾气、水、长镜、诗性 | 雾中长镜，水汽弥漫，诗性留白（Tarkovsky mist, poetic） |

#### 三、平台/短视频圈流行（9 种，AI 视频最易出效果）

| 风格 | 一眼识别 | 提示词关键词（中英） |
|---|---|---|
| 港风复古 | 港片暖调、黑发红唇、霓虹街、颗粒 | 90年代港风，暖调霓虹，颗粒感，黑发红唇（90s Hong Kong retro） |
| 老胶片/CCD 感 | 低清颗粒、色偏、漏光、闪光灯直打 | 老照片质感，胶片漏光，CCD 闪光灯直打（vintage film, light leaks） |
| 新中式 | 东方符号+现代构图、留白、水墨灰调 | 新中式美学，留白构图，水墨低饱和（new Chinese aesthetic） |
| 氛围感人像 | 逆光发丝光、眼神光、背景全虚、情绪留白 | 氛围感人像，逆光发丝，情绪留白（moody portrait, rim light） |
| 南法/假日感 | 高调明亮、草绿海蓝、阳光溢出、松弛 | 南法假日风，高调明亮，阳光溢出（French riviera, bright airy） |
| 一镜到底 | 全程不切，跟拍运镜，临场感 | 一镜到底跟拍，手持呼吸感（one-shot take, following camera） |
| AI 超现实美学（2026 新） | 融解/流动/变形，梦境感 | 物体流动融解，超现实变形，梦境感（surreal morphing, melting, dreamlike） |
| 故事感叙事光 | 窗户光、门缝光、明暗叙事 | 窗户光切割画面，门缝漏光，明暗叙事（storytelling window light） |
| 邵氏电影（制片厂体系·非单导演） | 棚拍硬光高对比、古装浓艳配色、金碧布景、对称构图 | 邵氏武侠电影质感，棚拍高对比光，浓艳古装色，金碧宫殿布景，对称构图（Shaw Brothers movie texture） |

#### 四、2026 趋势备忘（做"当下感"）

1. 真实感回归：实拍质感、手工道具、可见工艺 → 触感材质、现场实拍感、非精致完美（tactile, physical craft, lived-in）
2. 克制中性色：色彩越少越高级
3. 一镜到底：品牌片和短片都在用
4. AI 美学独立化：不再模仿胶片，承认 AI 的流动/融解是风格本身

### 电影风格完整描述（37 段·可直接复制，末段含邵氏制片厂风格）

> 每一段都是完整可复制的 prompt 描述（中英双版），直接粘到 V6 电影质感后面或单独使用。中文喂豆包/可灵，英文喂 GPT-Image/MJ。

#### 一、调色流派完整描述

**1. 青橙对比 Teal & Orange**

```
青橙对比色调，肤色偏暖橙，暗部泛青蓝，高光柔和如奶油，皮肤通透细腻，明暗过渡平滑，浅景深，好莱坞商业大片质感。
```
English: Teal and orange color grade, warm orange skin tones, teal-blue shadows, creamy soft highlights, luminous skin, smooth tonal transitions, shallow depth of field, blockbuster cinematic look.

**2. 漂白跳过 Bleach Bypass**

```
漂白工艺质感，高对比低饱和，暗部呈银灰色，肤色褪色发白，颗粒明显，画面粗粝硬朗，金属冷硬感。
```
English: Bleach bypass look, high contrast low saturation, silver-gray shadows, desaturated pale skin, visible grain, gritty hard-edged texture, cold metallic feel.

**3. 克制中性调（2026 主流）**

```
克制中性色板，低饱和大地色，米白暖灰为主，几乎无彩色倾向，画面安静高级，情绪靠构图与光影传递，留白克制。
```
English: Restrained neutral palette, low saturation earth tones, beige and warm gray dominant, barely any color cast, quiet and refined, emotion carried by composition and light, minimal and controlled.

**4. 暖金复古**

```
暖金复古调，琥珀蜂蜜色高光，暗部暖棕，胶片暖晕，怀旧时光感，画面泛着旧日余晖的温度。
```
English: Warm golden vintage grade, amber honey highlights, warm brown shadows, filmic warm glow, nostalgic timeless warmth.

**5. 冷蓝清冷**

```
冷蓝清冷调，低色温，月光与阴天质感，暗部深邃带雾感，疏离克制，情绪安静而遥远。
```
English: Cool blue desaturated grade, low color temperature, moonlight and overcast quality, deep misty shadows, detached and restrained, quiet and distant mood.

**6. 高饱和糖果**

```
高饱和糖果配色，马卡龙粉紫黄，高饱和低明度，画面精致如童话绘本，梦幻明快。
```
English: High saturation candy palette, macaron pink purple yellow, saturated low-key colors, picture-book fairy tale, dreamy and cheerful.

**7. 黑白电影**

```
黑白胶片质感，强明暗对比，细腻银盐颗粒，经典年代感，画面如老电影一帧。
```
English: Black and white film look, strong contrast, fine silver grain, classic vintage cinema frame.

**8. 交叉冲印 Cross-processed**

```
交叉冲印失真色，肤色偏青绿，天空泛洋红，非自然配色，实验艺术感，色彩错位如幻觉。
```
English: Cross-processed colors, greenish skin tones, magenta skies, unnatural color shifts, experimental artistic feel, hallucinatory hue errors.

#### 二、导演视觉签名完整描述

**9. 韦斯·安德森**

```
绝对居中对称构图，高饱和低明度马卡龙配色，平面化平移运镜，人物正对镜头，画面像手工绘本，精致秩序感，微微荒诞的童话氛围。
```
English: Wes Anderson style, dead-center symmetrical composition, high saturation low-key macaron palette, flat lateral tracking, characters facing camera, handmade storybook look, meticulous order, whimsical fairy-tale mood.

**10. 王家卫**

```
港风霓虹夜色，抽帧慢门造成的拖影与晃动，广角畸变，浓烈红绿配色，雨夜湿润反光，失焦与前景遮挡，情绪浓烈欲言又止。
```
English: Wong Kar-wai style, neon-lit rainy nights, step-printed slow shutter motion trails, wide-angle distortion, intense red and green palette, wet reflective surfaces, racked focus and foreground obstruction, dense unspoken emotion.

**11. 张艺谋**

```
单一主色统治整个画面，高饱和红或黑白青，色彩即叙事，大场面仪式感构图，东方符号浓烈，画面如大幅油画。
```
English: Zhang Yimou color symbolism, a single dominant color ruling the frame, saturated red or black white green, color as storytelling, grand ceremonial composition, bold oriental imagery, large-scale oil painting feel.

**12. 诺兰**

```
IMAX 级宏大画幅，实拍质感，冷峻蓝灰调，巨大对称建筑，秩序与压迫感并存，画面冷硬理性。
```
English: Christopher Nolan epic scale, IMAX frame, practical photography texture, austere blue-gray grade, colossal symmetrical architecture, order and oppression, cold rational imagery.

**13. 维伦纽瓦**

```
巨物压迫构图，人物渺小置于宏大空间，静默氛围，黄褐沙尘调，极简对白感，肃穆的末世诗意。
```
English: Denis Villeneuve scale, tiny figures in vast spaces, silence-driven atmosphere, yellow-brown dusty grade, minimal dialogue feel, solemn apocalyptic poetry.

**14. 大卫·芬奇**

```
青绿阴影调，室内暗部深邃，绿色植物点缀，精密几何构图，冷峻克制，悬疑暗流。
```
English: David Fincher green-teal shadows, deep dim interiors, sparse green foliage accents, precise geometric framing, cold and controlled, lurking suspense.

**15. 提姆·波顿**

```
哥特暗黑童话，苍白肤色，高耸尖顶建筑，黑紫绿配色，夸张造型，诡异又温柔。
```
English: Tim Burton gothic fairy tale, pale skin, towering spires, black purple green palette, exaggerated silhouettes, eerie yet tender.

**16. 新海诚**

```
日系透明光影，通透蓝天，光斑与雨丝，云层逆光，高光细腻，画面清透如玻璃，少年感情绪。
```
English: Makoto Shinkai transparent light, luminous blue sky, bokeh and rain streaks, backlit clouds, delicate highlights, glass-clear imagery, youthful emotion.

**17. 宫崎骏**

```
水彩手绘质感，云海草原，暖阳田园，色彩柔和饱和，治愈系幻想世界，万物有灵。
```
English: Studio Ghibli watercolor style, sea of clouds and meadows, warm sunlight, soft saturated colors, healing fantasy world, everything animated with spirit.

**18. 侯孝贤/李屏宾**

```
长镜头固定机位，自然光，东方留白构图，时间缓慢流淌，画面安静如旧照，东方诗性。
```
English: Hou Hsiao-hsien long take, fixed camera, natural light, Eastern negative-space composition, slow passage of time, quiet like an old photograph, poetic restraint.

**19. 是枝裕和**

```
日常自然光，克制近景，生活温度，不刻意打光，家庭感，画面朴素真挚。
```
English: Hirokazu Kore-eda naturalism, everyday available light, restrained close-ups, domestic warmth, unforced lighting, plain and sincere.

**20. 库布里克**

```
一点透视对称构图，几何强迫症，冷调广角，纵深强烈，画面理性到近乎冰冷，形式即美学。
```
English: Kubrick one-point perspective, obsessive geometric symmetry, cold wide-angle depth, rational to the point of coldness, form as aesthetics.

**21. 昆汀**

```
低机位仰拍，高饱和撞色，复古胶片颗粒，特写暴力美学，画面粗犷张扬，B 级片质感。
```
English: Tarantino low-angle framing, saturated clashing colors, retro film grain, close-up violence aesthetics, brash and bold, grindhouse texture.

**22. 罗杰·狄金斯（摄影）**

```
光束穿透尘埃，逆光剪影，雾中光柱，水汽弥漫，光像有实体一样在画面中流动，影调层次极丰富。
```
English: Roger Deakins light design, volumetric beams through dust, backlit silhouettes, light shafts in mist, tangible flowing light, extraordinarily rich tonal layering.

**23. 杜可风（摄影）**

```
手持晃动，胶片噪点，霓虹流光，镜头脏乱美，呼吸感强，画面活而躁动。
```
English: Christopher Doyle handheld camera, film grain, neon light streaks, dirty beautiful frames, strong breathing rhythm, alive and restless.

**24. 塔可夫斯基（冷门高阶）**

```
雾中长镜，水汽弥漫，诗性留白，时间凝滞，自然元素（雨雾火草）作为主角，冥想式影像。
```
English: Tarkovsky long takes in mist, pervasive moisture, poetic negative space, suspended time, nature elements (rain fog fire grass) as protagonists, meditative cinema.

#### 三、平台/短视频圈流行完整描述

**25. 港风复古**

```
90年代港片质感，暖调霓虹，胶片颗粒，黑发红唇，复古时装，浓情夜色，自带故事感。
```
English: 90s Hong Kong retro, warm neon tones, film grain, black hair red lips, vintage fashion, romantic night city, inherent story quality.

**26. 老胶片/CCD 感**

```
老照片质感，胶片漏光，CCD 闪光灯直打，低清颗粒，色彩轻微偏色，年代记忆感，像素感怀旧。
```
English: Vintage film CCD look, light leaks, direct flash, low-fi grain, slight color cast, nostalgic memory feel, pixelated retro charm.

**27. 新中式**

```
新中式美学，东方符号与现代构图结合，留白，水墨低饱和，木质与纸绢质感，克制雅致。
```
English: New Chinese aesthetic, oriental motifs meet modern composition, negative space, ink-wash low saturation, wood and paper texture, refined restraint.

**28. 氛围感人像**

```
氛围感人像，逆光发丝光，眼神光，背景全虚化，情绪留白，人物沉浸在光里，故事在画外。
```
English: Moody portrait, backlit hair glow, catchlight in eyes, fully blurred background, emotional negative space, subject bathed in light, story beyond the frame.

**29. 南法/假日感**

```
南法假日风，高调明亮，草绿海蓝，阳光溢出，松弛舒展，胶片明亮感，度假心情。
```
English: French Riviera holiday feel, high-key bright, grass green sea blue, sunlight spill, relaxed and airy, bright film look, vacation mood.

**30. 一镜到底**

```
一镜到底跟拍，手持呼吸感，镜头连续不切，临场纪录感，空间时间完整流动。
```
English: One-shot continuous take, handheld breathing motion, no cuts, documentary immediacy, seamless flow of space and time.

**31. AI 超现实美学（2026 新）**

```
物体流动融解，超现实变形，梦境感，色彩逻辑自由，形态在变化中定格，承认 AI 美学的独立语言。
```
English: AI surreal aesthetic, flowing melting forms, surreal morphing, dreamlike logic, free color rules, forms frozen mid-transformation, embracing AI's own visual language.

**32. 故事感叙事光**

```
窗户光切割画面，门缝漏光，明暗叙事，人物半明半暗，光线暗示剧情走向，氛围厚重。
```
English: Storytelling window light, light slicing the frame, door-crack leaks, narrative chiaroscuro, half-lit faces, light hinting at plot, dense atmosphere.

#### 四、2026 趋势备忘（做"当下感"）

**33. 真实感回归**

```
实拍质感，手工道具，可见工艺，触感材质，非精致完美，像真的被拍摄过。
```
English: Tactile realism, practical craft, visible handmade texture, lived-in imperfect surfaces, as if truly filmed.

**34. 克制中性色**

```
色彩压到最少，高级灰与大地色，影展感，高级感来自克制。
```
English: Restrained minimal color, elegant grays and earth tones, festival-grade restraint.

**35. 一镜到底**

```
（同 #30）全程不切，跟拍运镜，品牌片与短片主流。
```
English: (same as #30) one continuous take, following camera, mainstream in brand films.

**36. AI 美学独立化**

```
（同 #31）不再模仿胶片，承认 AI 的流动/融解是风格本身。
```
English: (same as #31) stop imitating film, embrace AI's fluid melting as the style itself.

**37. 邵氏电影**

```
邵氏武侠/古装电影质感：棚拍人造硬光，明暗高对比，服装色彩浓艳饱和（正红/明黄/翠绿/鎏金），金碧辉煌的宫殿布景，四平八稳的对称构图，粗颗粒胶片，锐利清晰，人物浓妆细眉红唇，特写切脸凌厉。
```
English: Shaw Brothers wuxia movie texture, 1960s-70s Hong Kong studio cinema, hard studio lighting with high contrast, saturated costume colors (vermilion, gold, emerald), ornate gilded palace sets, symmetrical composition, grainy sharp 35mm film, bold period makeup, crisp facial close-ups.

**用法口诀**：调色流派打底（选 1）+ 导演签名定情绪（选 0-1）+ 平台潮流整套用（选 0-1），拼在 V6 电影质感后面即可；完整描述可直接整段复制。

### 画面风格速查表（质感·色调·氛围·画幅·母版，五维任拼）

> 与 36 风格互补：36 风格管"调色与导演视觉"，本表管"质感参数 + 情绪氛围 + 画幅"，可任意交叉组合（如"轻颗粒 + 莫兰迪 + 空灵 + 2.35:1"）。

**A. 质感系（画面"摸起来"什么手感）**

| 质感 | 写法（中英） | 效果 |
|---|---|---|
| 胶片颗粒 | 轻颗粒（light grain）/ 中颗粒（medium grain）/ 重颗粒（heavy grain） | 质感/复古强度 |
| 锐度 | 柔焦（soft focus）/ 刀锐奶化（tack sharp with creamy bokeh）/ 清晰对焦（crisp focus） | 梦幻/精致/写实 |
| 光晕 | 变形镜头光晕（anamorphic lens flare）/ 柔光晕染（soft bloom）/ 逆光光晕（halation） | 电影/梦幻/神圣 |
| 暗角 | 轻微暗角（subtle vignette）/ 重暗角（heavy vignette） | 聚焦/复古/压抑 |
| 反差 | 低反差（low contrast）/ 高反差（high contrast）/ 中反差（medium contrast） | 柔/硬/平衡 |
| 雾感与通透 | 晨雾弥漫（morning mist）/ 通透清亮（translucent clear）/ 薄雾透光（thin haze） | 朦胧/治愈/空灵 |
| 褪色漂白 | 褪色做旧（faded vintage）/ 漂白工艺（bleach bypass） | 年代/金属感 |

**B. 色调系（8 种常用，中英）**

| 色调 | 写法 | 情绪 |
|---|---|---|
| 暖金复古 | 暖金复古调，琥珀高光（warm golden vintage） | 怀旧、黄昏 |
| 冷蓝清冷 | 冷蓝清冷调，月光质感（cool blue, moonlit） | 清冷、孤独 |
| 青橙对比 | 青橙对比，肤色暖橙暗部青蓝（teal & orange） | 好莱坞、大片 |
| 莫兰迪低饱和 | 莫兰迪低饱和，灰调雅色（Morandi muted palette） | 高级、克制 |
| 水墨单色 | 水墨单色，墨色晕染（ink wash monochrome） | 诗意、留白 |
| 漂白银灰 | 漂白银灰，金属哑光（silver grey, matte） | 冷峻、纪实 |
| 蜜糖黄昏 | 蜜糖琥珀色，金色漫射（honey amber glow） | 温柔、治愈 |
| 克制冷灰 | 克制冷灰，大地色系（restrained cool grey） | 影展、高级感 |

**C. 氛围系（整条 prompt 的情绪收尾词）**

| 氛围 | 写法 | 适用 |
|---|---|---|
| 空灵 | 空灵缥缈（ethereal） | 仙侠、天宫 |
| 治愈 | 治愈温暖（healing） | 田园、日常 |
| 肃穆 | 肃穆庄严（solemn） | 仪式、祭祀 |
| 诗意 | 诗意留白（poetic） | 雅事、文会 |
| 烟火 | 人间烟火（mundane warmth） | 市集、街巷 |
| 梦幻 | 梦境超现实（dreamy surreal） | 奇观、暗调 |
| 压迫史诗 | 史诗压迫感（epic and oppressive） | 巨物、宫殿 |

**D. 画幅系**

| 画幅 | 写法 | 适用 |
|---|---|---|
| 横屏 16:9 | 1920x1080 横屏 | 视频默认 |
| 宽银幕 | 2.35:1 宽银幕黑边 | 电影感 |
| 复古画幅 | 4:3 复古画幅 | 年代感 |
| 竖屏 | 9:16 竖屏 | 抖音/快手 |
| 方图 | 1:1 方图 | 头像/封面 |

**E. 母版质感锚点（画面"像什么材质"）**

```
胶片质感 / 绢帛质感 / 油画笔触 / 水墨纸绢 / 玻璃通透 / 丝绒哑光
```

**F. 动画/手绘系（AIGC 可直出的动画风·中英）**

| 风格 | 写法 | 效果/适用 |
|---|---|---|
| 吉卜力/宫崎骏 | 吉卜力手绘动画质感，水彩背景，温暖治愈，空气与风可见（Studio Ghibli style, hand-drawn animation, watercolor backgrounds, warm healing, visible air and wind） | 田园/治愈/乡野古风最配 |
| 新海诚 | 新海诚式唯美动画，高饱和天空，云层体积光，细腻光斑（Makoto Shinkai style, saturated sky, volumetric clouds, delicate light） | 唯美风景/情绪片 |
| 中国水墨动画 | 上海美术电影制片厂水墨动画风，墨色晕染，留白写意（Chinese ink-wash animation, Shanghai Animation Film Studio style） | 古风诗意/仙侠 |
| 敦煌壁画风 | 敦煌壁画质感，矿物颜料，土红石青金箔，斑驳肌理（Dunhuang mural style, mineral pigments, earth red and azurite, gold leaf） | 神话/佛窟/史诗 |
| 赛璐璐手绘 | 赛璐璐动画质感，线条清晰，平涂色块，复古胶片（cel animation, clean lines, flat colors, retro） | 复古动画/童趣 |
| 水彩绘本 | 水彩绘本质感，晕染留白，纸张纹理，透明清淡（watercolor picture book, soft washes, paper texture） | 温馨日常/儿童向 |
| 厚涂插画 | 厚涂油画笔触，颜料堆叠，光影扎实（painterly impasto, layered paint, solid light） | 质感人像/奇幻 |
| 3D 动画电影 | 皮克斯式 3D 动画，圆润造型，全局柔光，毛绒质感（Pixar-style 3D, soft shapes, global soft light） | 合家欢/商品 |
| 2D 动画电影 | 日式 2D 动画电影质感，细腻作画，赛璐璐与数字结合（anime-style 2D animation, refined hand-drawn frames） | 古风言情/热血 |
| 扁平插画 | 2D 扁平插画，色块简洁，无肌理阴影（flat 2D illustration, clean shapes, flat colors） | 海报/图解/氛围图 |
| 中国剪纸/纸艺 | 剪纸拼贴质感，镂空轮廓，红纸金边，纸艺层次（Chinese paper-cut art, cutout silhouettes, paper layers） | 民俗/节庆/非遗 |
| 像素风 | 像素画质感，低分辨率网格，复古游戏（pixel art, low-res grid, retro game） | 怀旧/游戏向 |
| 3D 卡通渲染 | 赛璐璐 3D 卡通渲染，描边+平涂，二次元手办感（cel-shaded 3D, toon shader, anime figures） | 古风二次元/游戏 CG |
| 黏土定格 | 黏土定格动画质感，手作痕迹，软质纹理（claymation, handmade texture, soft surfaces） | 治愈/童趣/怪诞 |
| 低多边形 | 低多边形 3D，几何切面，简约色块（low-poly 3D, faceted geometry, minimal palette） | 抽象/游戏资产 |
| 写实 3D 渲染 | 照片级 3D 渲染，全局光照，物理材质（photorealistic 3D render, global illumination, PBR materials） | 超写实/产品 |

**动画 ↔ 实拍互转规则（同一画面出两版对照）**：保留场景/人物/光影三要素一字不动，只替换 F 行首风格词——「吉卜力手绘动画质感，水彩背景」↔「电影级实拍质感，浅景深胶片」；新海诚式唯美动画 ↔ 实拍唯美电影感；水墨动画 ↔ 水墨实拍质感；赛璐璐 ↔ 复古胶片实拍。其余结构（场景句/人物段/运镜段/负面词）全部原样保留。
完整示例：保留场景/人物/光影三要素不变，只把「吉卜力手绘动画质感，水彩背景」替换为「电影级实拍质感，浅景深胶片颗粒，自然光」——其余结构一字不动。

**组合公式**：`[A-F 中选 1-2] + [B 色调选 1] + [C 氛围选 1] + [D 画幅选 1]`，拼在风格基调之后、场景之前。
示例：轻颗粒 + 莫兰迪低饱和 + 治愈 + 16:9 = "轻胶片颗粒，莫兰迪低饱和灰调，治愈温暖，1920x1080 横屏"

---

## 二、光影描述公式 + 词库

### 写法公式

```
光源 + 光位 + 光质 + 光色 + 明暗层次 + 光效 + 情绪
```

### 可替换词库

| 维度 | 可选词 |
|---|---|
| 光源 | 烛火 / 红灯笼 / 窗棂透光 / 香案烛光 / 黄昏天光 / 月光 |
| 光位 | 侧逆光 / 轮廓光 / 顶光 / 45°侧光 / 底光(烛台) / 逆光剪影 / 暖调逆光（勾勒轮廓，仙逸空灵） |
| 光质 | 柔光 / 漫射光 / 低反差 / 硬光 / 散射 |
| 光色 | 暖橙 / 琥珀色 / 金黄 / 蜜色 / 白中透暖 / 蓝紫混合色调 |
| 明暗 | 高光不溢出 / 暗部保留细节 / 光比柔和 / 面部受光均匀 / 强烈明暗对照（chiaroscuro）/ 极端明暗对比 |
| 光效 | 光晕 / 丁达尔光束 / 耶稣光（光柱倾泻在人物脸上与衣摆）/ 光斑虚化 / 尘埃微粒漂浮 / 烛火摇曳 / 垂直天光（一道光柱自天际垂落）/ 云隙光束斜洒 / 动态残影（faint motion ghosting）/ 半透明层次（translucent layers）/ 玻璃质感高光 |
| 情绪 | 温婉 / 庄重 / 喜庆 / 神圣感 / 静谧 / 微妙失衡感（subtly unhinged）/ 梦境核超现实（dreamcore surreal）/ 治愈疗愈感（ethereal healing）|

**光源分级速查（月光/烛火/灯笼·按情绪与年代感选）**：

| 光源 | 分级写法 | 适用情绪/场景 |
|---|---|---|
| 月光 | 清冷银白月华铺地，轮廓如霜 | 清幽、孤寂、夜读 |
| 月光 | 溶溶暖月，光晕微黄如蜜 | 温柔、相思、月下会 |
| 月光 | 月华如练，光带横贯庭院 | 空灵、仪式感、望月 |
| 月光 | 冷蓝月晕，光色带青 | 悬疑、冷冽、寒夜 |
| 烛火 | 暖黄豆火，焰心微亮 | 家常、温馨、夜话 |
| 烛火 | 琥珀色焰，光晕圆润 | 庄重、礼佛、祭典 |
| 烛火 | 昏黄烛影，明灭不定 | 怀旧、苍凉、独处 |
| 烛火 | 油灯青焰，光色偏冷 | 年代久远、陋室、质朴 |
| 灯笼 | 朱红暖光，光晕浓郁 | 喜庆、婚嫁、节庆 |
| 灯笼 | 橙黄光晕，暖而不艳 | 市集、夜行、家常 |
| 灯笼 | 纸笼柔光，光质朦胧 | 雅致、闺阁、含蓄 |
| 灯笼 | 纱灯透亮，光色清透 | 贵族夜宴、宫苑、精致 |

**画质收尾词组（外部高分验证·放 prompt 尾部技术段）**

```
高通透度饱和度 / 低反差低饱和 / 饱满虚化柔焦 / 奶油般散景（creamy bokeh）/ 焦外柔化（soft out-of-focus）/ 胶片颗粒质感 / 细节清晰锐利 / 对比度与饱和度和谐
```

### 柔和·唯美·细腻·电影化 四感词库（中英对照）

> ⭐ **默认开启**：宋/中式题材自动叠加本四感（见〇章规则 5），除非用户指定其他质感。

> 追求「柔和 / 唯美 / 细腻 / 电影化」视觉时，从下面四组各取 1-2 个词，按组合公式拼一句，四感自然齐。

**① 柔和（光质向）**

| 中文 | English |
|---|---|
| 奶油光 | Creamy light |
| 柔光箱感 | Softbox glow |
| 雾感透光 | Misty translucency |
| 光晕包裹 | Halo envelopment |
| 柔焦高光 | Soft airy bloom highlights |
| 阴影柔和过渡 | Soft gradient shadows |

**② 唯美（氛围+点缀向）**

| 中文 | English |
|---|---|
| 光尘漂浮 | Floating light dust |
| 花瓣轻旋 | Petals swirling |
| 落雪纷飞 | Falling snow |
| 流萤点点 | Firefly specks |
| 纱幔轻扬 | Veils drifting |
| 雾中光点 | Soft glow in mist |
| 梦境感 | Dreamlike |

**③ 细腻（质感向）**

| 中文 | English |
|---|---|
| 皮肤绒毛质感 | Peachy skin texture |
| 织物纹理清晰 | Fabric weave visible |
| 发丝根根分明 | Individual hair strands |
| 瞳孔光点反射 | Catchlight in pupils |
| 露珠微光 | Dewdrops glinting |
| 金尘悬浮 | Gilded dust suspended |
| 指纹级细节 | Fingerprint-level detail |

**④ 电影化（后期调色向）**

| 中文 | English |
|---|---|
| 电影感调色 | Cinematic color grading |
| 35mm 胶片质感 | 35mm film grain |
| 低调光 | Low-key lighting |
| 高光细腻滚落 | Smooth highlight falloff |
| 暗角收束 | Vignette |
| 体积光 | Volumetric light |
| 中画幅胶片 | Medium format film |

**⑤ 四感组合公式**

```
柔和光质 + 唯美氛围点缀 + 细腻质感描写 + 电影化后期
```

- 示例：奶油光雾感透光，光尘漂浮花瓣轻旋，发丝根根分明瞳孔反光，电影感调色胶片颗粒
- English: Creamy misty light, floating dust and swirling petals, individual hair strands with catchlights in pupils, cinematic grading with film grain

**⑥ 通用收尾词**：柔和唯美细腻电影化 / Soft, aesthetic, refined, cinematic

### 治愈系·纪实摄影配方（宋制日常向·中英对照）

> 来源：宋制汉服治愈系 prompt 系列（Midjourney，佳能 EOS R5 参数锚点）。写"日常治愈、田园诗意"向画面时用本配方。

**① 治愈系色调公式**

```
明亮、透明、低对比度、低饱和度 + ethereal healing atmosphere（空灵疗愈氛围）
```

- 示例：夏日午后，温暖窗光，斑驳树影，低对比低饱和，明亮透明，治愈空灵
- English: Bright, translucent, low contrast, low saturation palette, ethereal healing atmosphere

**② 纪实摄影参数套餐（写实锚点）**

```
佳能EOS R5相机 + RF 85mm f/1.4镜头 + 浅景深 + 奶油色虚化 + 真实质感 + 细微胶片颗粒 + 中国古典服饰纪实摄影
```

- English: Canon EOS R5, RF 85mm f/1.4, shallow depth of field, creamy bokeh, realistic texture, subtle film grain, Chinese classical costume documentary photography
- 用法：把这句放 prompt 末尾，可替换其他相机/镜头（索尼 A7R5 + 50mm f/1.2 等），"纪实摄影"四字是破 AI 摆拍感的关键

**④ 镜头锚点速查（按画面选）**

| 锚点 | 适合 | 例句 |
|---|---|---|
| Canon RF 50mm f/2.8 | 双人半身/中景，两人同焦平面 | 佳能RF 50mm f/2.8镜头，两人均处于画面平面内，景深较浅 |
| Canon RF 50mm f/1.8 | 单人柔和、晨雾氛围 | 佳能RF 50mm f/1.8镜头拍摄，柔和晨光，软焦 |
| Canon EOS R5 + 85mm f/1.2 | 深情对望、特写、大光圈虚化 | Canon R5 相机搭配 85mm f/1.2 镜头，浅景深，电影质感 |
| Canon EOS R5 + RF 85mm f/1.4 | 单人写实、纪实感 | （见②）|
| Canon RF 35mm f/2 ~ f/4 | 环境广角、群像、灶间/树下/荷塘/晾衣/晒场/茶山 | 35mm 环境广角平视，人物与手部清晰，前景柔化 |
| Canon RF 40mm f/2.8 / f/3.2 | 溪畔/麦田劳作中景 | 40mm 环境广角，人物与手部互动清晰，远村奶油虚化 |
| Canon RF 50mm f/1.2 | 市集/纪实多人，大光圈 | Canon EOS R5 RF50mm f/1.2，浅景深，自然散景 |
| ARRI Alexa 35 + Kodak 胶片色彩 | 宫廷史诗/古典电影机质感 | 85mm 镜头，ARRI Alexa 35，Kodak 胶片色彩，东方古典电影风格 |
| Canon RF 24mm f/1.8 | 超广角环境/宫殿全景/巨物压迫 | 24mm 超广角仰拍，建筑占满画幅，人物渺小 |
| Canon RF 28mm f/2.8 | 市集/街巷/檐下环境叙事 | 28mm 环境广角，街巷纵深，人物与摊档同框 |
| Canon RF 100mm f/2.8 微距 | 指尖/器物/针线细节特写 | 100mm 微距，绣针穿过绷面，指尖纹理清晰 |
| Canon RF 135mm f/1.8 | 压缩背景特写、远距离抓拍 | 135mm 长焦压缩，背景成片柔焦，人物呼吸感 |
| ARRI Alexa 35 + 75mm 电影镜头 | 电影机人像中焦 | 75mm 电影镜头，ARRI Alexa 35，Kodak 色彩 |

**⑤ 双人互动构图配方（两小无猜/情侣/闺蜜·中英关键词）**

> 来源：泡面AIGC「两小无猜」系列 10 条（桃林/风筝/谷场/茶山/水田/湖畔）。模板此前案例全是单人，本配方专治"两个人怎么摆"。

**关系位（两人空间怎么放）**

| 关系位 | 写法 |
|---|---|
| 对望 | 面朝彼此深情对望，目光交汇（both face towards each other in deep affection, gazes meet） |
| 并肩 | 并肩而立，同向同视，一人做事一人看（stands close beside her, both focused on the task） |
| 前后回眸 | 一人在前一人在后，她回眸望向他（looks back over her shoulder at him） |
| 一人做事一人接 | 她抛/递，他伸手接，物件悬在空中（seedlings mid-flight between them） |

**主从侍奉位（贵妇+侍女/主子+随从·外部高分验证）**

| 位置 | 写法 |
|---|---|
| 一主多从 | 贵妇居中或前行，侍女列后两侧，团扇一左一右交叠 |
| 从属道具 | 侍女持团扇 / 端茶盏糕点 / 执熏炉 |
| 从属神态 | 低眉顺眼 / 垂首侍立 / 亦步亦趋 |
| 互动呼应 | 主人动作，侍女目光随主人；主人伸手，侍女递盏 |

**关系质感速查表（心理距离·与关系位互补：关系位管"空间怎么摆"，本表管"距离/朝向/眼神/触碰"）**

| 关系 | 距离感 | 身体朝向 | 眼神 | 触碰方式 | 站位 |
|---|---|---|---|---|---|
| 亲密无间（挚友/情侣） | 近（<0.5m） | 对向或同向，肩膀相抵 | 直视彼此，笑纹明显 | 挽臂/勾手/抚肩 | 并肩，无间隔 |
| 尊卑分明（主仆/君臣） | 中等（0.5-1m） | 仆侧面或半步后，身体微侧 | 仆低垂敛目，不敢直视 | 仆双手捧物递出，不触 | 主前仆后，仆落后半步 |
| 疏离陌生（初识/路人） | 远（>1.5m） | 正面或 45°，身体站直无倾 | 礼貌性目光交汇即移开 | 无触碰 | 面对面，留出完整空间 |
| 对峙（敌意/对立） | 中远（1-2m） | 面对面，身体微倾 | 目光直视，不避不让 | 无触碰，手按剑柄 | 面对面，身体重心前倾 |

用法：选关系 → 从表取"距离/朝向/眼神/触碰" → 拼进双人 prompt，关系立现。

**互动小动作（双人专属）**

- 插花入发：他温柔地将一枝桃花轻别进她发髻（gently tucking a peach blossom branch into her hair）
- 抛接秧苗：她张开双臂抛洒秧苗，他双手前伸接住，水珠在空中闪光（tossing seedlings, reaching both hands out to catch, droplets sparkling）
- 放风筝：她执线放飞，他伸手指向天空，两人目光交汇（flying the kite, pointing at the kite, gazes meet）
- 弯腰拾花：他弯腰捡拾掉落的花瓣，她回眸浅笑（bending to pick fallen petals, she glances back with a smile）
- 轻扶臂弯：他侧身轻扶她的臂弯，目光温柔缱绻（steadies her arm, tender gaze）
- 共持一物：两人同扶竹篮/同牵一物（both holding the same basket）

**表情呼应（两人情绪要"一递一接"）**

- 她：笑弯月牙眼、眉眼弯弯、回眸浅笑、仰头注视、脸颊泛红晕
- 他：笑容明媚、温柔含笑、伸手咧嘴、目光缱绻、宽厚笑意
- 呼应句：她回眸，他伸手；她仰头，他低头；两人目光交汇（their gazes meet）

**双人通用句式**

```
[时间+场景]，两位年轻人[关系位]，[中景]。他[互动动作]，她[呼应动作+表情]，
[她神态细节]，[他神态细节]，两人目光交汇。[光影]，[色调氛围]。[镜头锚点]。
```

示例：春日下午，桃花树下，两位年轻男女并肩而立。他温柔地将一枝桃花插进她发髻，她仰头注视着他，眉眼间带着浅笑，笑容灿烂；他低头看她，目光温柔。阳光透过粉色花簇，在两人脸上投下斑驳光晕，空灵诗意。佳能RF 50mm f/2.8，两人均在焦平面。

**③ 生活化动态瞬间写法（区别于摆拍）**

- 动态动作 + 空中元素 + 表情：河畔洗衣，嬉戏水珠飞溅空中折射光芒，脸上洋溢喜悦 / Washing clothes by the river, playful drops of water arcing into the air catching light, joyful expression
- 手部动作 + 蒸汽 + 光影：一手翻古籍一手持热茶杯贴唇边，蒸汽映照暖光 / Flipping through an ancient book while holding a steaming teacup near her lips
- 伸手动态 + 树冠构图：轻伸手指摘熟透红苹果，树冠绿叶红果填满画面 / Gently reaching up to pick a ripe red apple, lush canopy filling the frame

**⑦ 四感负面词配套（防翻车）**

| 四感 | 负面词 |
|---|---|
| 柔和 | 不生硬阴影，不高对比，不锐化过度 |
| 唯美 | 不杂乱，不脏旧，无多余杂物 |
| 细腻 | 无塑料感，不模糊，不油腻 |
| 电影化 | 无廉价CG感，不过度锐化，无低质量渲染 |

> 英文通用：No harsh shadows, no oversharpening, no plastic look, no cheap CG, no clutter, no low-quality rendering

**⑧ 唯美氛围元素库（中式专属）**

| 元素 | 用法示例 |
|---|---|
| 落花 | 花瓣随风轻旋，落在肩头 |
| 飘雪 | 细雪纷扬，落在发梢与睫毛 |
| 流萤 | 流萤点点，在暗处明灭 |
| 烛影 | 烛影摇红，映在纱帘 |
| 香雾 | 香雾袅袅，缠绕衣袂 |
| 月华 | 月华如练，铺满台阶 |
| 晨雾 | 晨雾未散，远山若隐若现 |
| 竹影 | 竹影横斜，筛下碎光 |

**⑨ 电影感运镜组合（视频向）**

| 组合 | 写法 |
|---|---|
| 极慢推 | 镜头以极慢速度向前推进，画面如被拉入 |
| 焦点转移 | 焦点从前景虚化缓缓移向人物面部 |
| 镜头呼吸感 | 镜头带轻微呼吸感的缓慢推拉 |
| 虚实交错 | 前景虚化与主体清晰交错，景深缓缓变化 |
| 环绕半周 | 镜头绕主体缓慢环绕半周，光线随之流动 |

> 英文对照：Extremely slow push-in / focus racking / subtle breathing handheld / shallow-to-deep focus interplay / half orbit around the subject

**⑩ 唯美色盘**

| 色 | English |
|---|---|
| 奶油白 | Cream white |
| 珍珠粉 | Pearl pink |
| 雾蓝 | Mist blue |
| 香槟金 | Champagne gold |
| 藕荷 | Lotus pink |
| 月白 | Moon white |
| 青灰 | Slate grey |

**⑪ 柔焦人像成品示范（可直接复制·四感全家桶）**

中文：奶油光柔光箱感，雾感透光光晕包裹，光尘漂浮落雪纷飞，发丝根根分明瞳孔光点反射，皮肤绒毛质感，电影感调色胶片颗粒，暖调逆光勾勒轮廓，柔和唯美细腻电影化。完美鹅蛋脸黄金比例，大杏眼双眼皮星光美瞳，柔和卧蚕，珊瑚橘唇微启，黑发半束随风扬起，白纱长袍衣袂翻飞，双手身前结印，山间松林朦胧山峦为景。

English: Creamy softbox glow, misty translucent light with halo envelopment, floating dust and falling snow, individual hair strands with catchlights in pupils, peachy skin texture, cinematic grading with film grain, warm backlight outlining silhouette, soft aesthetic refined cinematic. Perfect oval face with golden ratio, large almond eyes with double eyelids and star catchlights, soft aegyo sal, coral lips slightly parted, black hair half-tied streaming in wind, white gauze robe fluttering, hands forming a mystic seal, mountain pines and hazy ridges as backdrop.

### 东方生活美学配方（Oriental Lifestyle Aesthetics·Flova/MJ 实测入库）

> 来源：Flova 1.0「剧本生视频」七夕乞巧实测（2026-09-07），Midjourney v8.2 出图。写"江南夏日、宋词诗意、田园烟火"向画面时用本配方，英文整段可直接复制。
> 使用注意：本小节收录外部平台实测成品，每镜中英对照整段可复制（中文喂豆包/可灵/海螺，英文喂 MJ/GPT-Image）；替换题材时只换「场景段+人物段+动作段」，风格段与收尾段照抄。

**通用模板结构（五段式）**：

```
① 风格段：Rooted in traditional Eastern classical aesthetics, this work inherits the gentle, elegant poetic charm of Song Dynasty ci poetry, creating a misty, translucent scene bathed in bright summer sunshine with distinct summer vibes... It carries the subtle, refined artistic conception of Song Dynasty album leaf paintings, and faithfully recreates the leisurely, rustic mortal warmth of rural Jiangnan at dusk.
② 场景段：时间+地点+天气+光环境（例：It is a summer afternoon; a yellow ox stands leisurely on the grassland...）
③ 人物段：身份+服装+动作+互动（例：Two ladies in plain white Hanfu tie a string of morning glories onto the ox's horns...）
④ 光影收尾段：The whole frame boasts cinematic lighting texture: side backlight outlines soft hair contours with blurred foreground elements. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" widely adopted in contemporary Chinese-style AIGC artworks.
⑤ MJ 参数：--ar 16:9 --stylize 200 --raw --v 8.2
```

**镜02｜为牛庆生（中英对照）**：

**中文版：**

```
东方传统古典美学，通篇采用宋词诗意美学基调，清透朦胧的盛夏阳光，如宋人小品画般含蓄内敛，复刻江南乡村午后的闲适烟火。夏日午后，草地上一头黄牛悠然站立，牛角挂满彩色野花与红绸，在微风中轻轻摆动，晴空缀着淡云。两位白衣汉服女子笑着给牛角系上牵牛花，欢声笑语。身后白云漂浮，晾衣架上晾着半透明白绸。斑驳阳光洒落，在黄牛与女子身上泛起细碎金光，如金箔铺地，朦胧梦幻。中近景，前景一丛盛开的野菊虚化，侧逆光勾勒女子柔软碎发与黄牛脊背的流畅轮廓。光影电影质感，温润如画。
```

**英文版：**

```
Rooted in traditional Eastern classical aesthetics, this work inherits the gentle, elegant poetic charm of Song Dynasty ci poetry, creating a misty, translucent scene bathed in bright summer sunshine with distinct summer vibes, ethereal and clear. It carries the subtle, refined artistic conception of Song Dynasty album leaf paintings, faithfully recreating the leisurely, rustic mortal warmth of countryside Jiangnan at dusk.
It is a summer afternoon; a yellow ox stands leisurely on the grassland, its horns draped with colorful wild flowers and red ribbons swaying gently in the soft breeze, under a clear sky dotted with blue clouds. Two ladies in plain white Hanfu tie a string of morning glories onto the ox's horns, chatting and laughing cheerfully. Behind them stretch white floating clouds, and sheer white silk fabrics hang drying on a clothes rack. Dappled sunlight spills down, casting glittering golden flecks across the ox and the women, like scattered gold covering the ground, glowing shimmeringly with a hazy dreamlike glow. Shot in medium close-up, a cluster of blooming wild chrysanthemums forms a softly blurred foreground. Side backlight traces the soft baby hairs of the women and the smooth outline of the ox's back.
The whole frame features cinematic lighting texture: side backlight outlines soft hair contours with blurred foreground elements. This is the immensely popular creative style known as "Oriental Lifestyle Aesthetics" widely seen in modern Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**镜03｜吃巧果（中英对照）**：

**中文版：**

```
东方传统古典美学，通篇采用宋词诗意美学基调，盛夏明亮通透的光感，如宋人小品画般含蓄内敛，复刻江南暮色厨房的烟火人情。三位素衣麻布少女围在老厨房油锅前，手持木筷翻动面坯，面坯在热油中膨起、变金黄酥脆，成为传统七夕巧果。少女挽起浅色衣袖，笑着同尝新炸的巧果。正午阳光透窗而入，照亮厨房，油面泛起粼粼亮光，烟火气十足。竹筛堆满新炸巧果，冒着热气。窗边与梁下悬垂的半透明白纱帘形成柔和虚化的前景，侧逆光勾勒少女束发与麻布围裙的剪影，发丝轮廓光细腻。
```

**英文版：**

```
Rooted in traditional Eastern classical aesthetics, this work inherits the gentle, elegant poetic charm of Song Dynasty ci poetry, crafting a misty, translucent scene bathed in bright summer sunlight with distinct summertime vibes. The imagery is ethereal and clear, carrying the subtle refined charm of Song Dynasty album leaf paintings, and authentically recreating the relaxed, simple mortal warmth of rural Jiangnan at dusk.
Three maidens in plain linen robes gather in an old kitchen surrounding an oil wok, holding dough pieces with wooden chopsticks. The dough puffs and swells in the hot oil, gradually turning golden and crispy to become traditional Qixi sweet cakes. The ladies roll up their pale sleeves, laughing merrily as they taste the fried cakes together. Bright midday sunlight streams through the windows, flooding the kitchen with glowing light that shimmers across the oil's surface, brimming with vivid mortal kitchen ambiance. Clear sunshine caresses their faces; a bamboo sieve beside them is piled high with freshly fried sweet cakes steaming gently, filling the air with rich fried pastry aroma. The frame is saturated with warm earthly liveliness. Sheer white translucent gauze curtains hanging by the windows and roof form a softly blurred foreground. Side backlight traces the soft silhouettes of the maidens' tied-up hair and linen aprons, creating delicate glowing hair rim light, as sunlight pours straight onto the stove.
The entire shot delivers cinematic lighting texture: side backlight outlines soft hair strands with blurred foreground elements. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" widely adopted in contemporary Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**镜04｜晒衣晒书（中英对照）**：

**中文版：**

```
东方传统古典美学，通篇采用宋词诗意美学基调，晴明通透的夏日阳光，如宋人小品画般含蓄内敛，复刻江南夏日庭院的闲适气息。晴朗夏日，三位素衣女子在庭院中横拉数条绳索，半透明白绸、泛黄古籍与竹简挂晒其上。女子立于晾衣绳前，笑着轻抚丝绸褶皱，互相说笑。光线明亮清澈，阳光洒在衣料上，发丝边缘泛起细柔轮廓光，发间珠玉在阳光下微微颤动。全景俯拍视角，前景藤蔓与垂挂衣物的边缘虚化，阳光在织物上折射出虹彩光泽。整个画面光影斑驳，温暖宜人。
```

**英文版：**

```
Rooted in traditional Eastern classical aesthetics, this work inherits the gentle, elegant poetic charm of Song Dynasty ci poetry, building a misty, translucent scene bathed in bright sunshine with strong summer vibes. The image is ethereal and lucid, carrying the subtle refined artistic charm of Song Dynasty album leaf paintings, and authentically recreating the leisurely, rustic mortal warmth of countryside Jiangnan at dusk.
Under a clear summer sky blazing with bright sun, three ladies in plain Hanfu stretch several ropes horizontally across the courtyard. Translucent white silk fabrics, yellowed ancient scrolls and bamboo slips are hung out to dry on the ropes. Standing before the clothesline, the maidens smile joyfully as they gently smooth the wrinkles of the silks, chatting and laughing with each other. The lighting is bright and crystal clear; brilliant sunlight spills over the garments and creates delicate rim light around their hair. The pearl and jade hair pendants on their elaborate coiffures tremble faintly under the sun. The shot is a full overhead bird's-eye view, with trailing vines and the edges of the hanging clothes softly blurred in the foreground. Sunlight glints off the fabrics, casting iridescent rainbow-like reflections; soft hair rim light falls gently on their faces. The whole scene delivers a dappled-light, warm and pleasant summer courtyard atmosphere.
The entire frame boasts cinematic lighting texture: side backlight traces soft hair contours with blurred foreground elements. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" widely adopted in contemporary Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**镜05｜接露水（中英对照）**：

**中文版：**

```
东方传统古典美学，通篇采用宋词诗意美学基调，清透朦胧的清晨柔光，如宋人小品画般含蓄内敛，复刻江南晨间劳作的宁静诗意。盛夏清晨，晶莹露珠缀在草叶上如碎钻闪光。三位素衣女子蹲在花丛边，身着淡绿交领短襦，发髻松散，面容素净柔和，阳光将发丝染成金色。一位女子右手食指轻触叶面，接住圆润透明的露珠，闭目将露珠轻点眼睑与手背，动作虔诚轻柔，如承接上天恩赐的巧手明眸。晨光透过薄纱般的雾气，湿润柔和，老槐树枝影斑驳地洒在女子衣襟与青苔地面。近景，前景沾露的牵牛花与垂柳枝条虚化，青绿与暖米色调交织，如宋画小品中的人物，充满晨间劳作前的宁静诗意。
```

**英文版：**

```
Rooted in traditional Eastern classical aesthetics, this work inherits the gentle and elegant poetic charm of Song Dynasty ci poems, creating a misty, translucent scene bathed in bright summer sunlight with distinct summer vibes, ethereal and crystal-clear visuals. It carries the subtle, refined artistic conception of Song Dynasty album leaf paintings and authentically recreates the relaxed, simple mortal warmth of rural Jiangnan at dusk.
It is summer with brilliant sunshine; crystal dewdrops cling to grass blades, glimmering like tiny broken diamonds in soft light. Three ladies in plain robes crouch beside blooming flowers, wearing pale green front-opening short blouses with loose, unadorned hair buns and natural, unpowdered gentle and delicate faces. Sunlight gilds their hair strands. One lady gently touches a leaf with her right index finger to catch a round, translucent dewdrop, then closes her eyes and dabs the dew upon her eyelids and the back of her hand with tender, devout motions, as if receiving heaven's gift of nimble hands and clear eyes. Dawn light filters through thin gauzy mist, soft and moist, casting dappled spots through the branches of an old locust tree onto the women's garments and the moss-covered ground.
Shot in close-up, the foreground features softly blurred dewdrop-covered morning glories and drooping willow twigs, crafting a misty, translucent, dreamlike morning scene of Jiangnan. The overall palette blends verdant cyan and warm off-white, resembling minor figures in Song Dynasty landscape paintings. It brims with the tranquility and poetry before morning farm labor, reflecting the ancients' awe and appreciation for nature's blessings.
The whole frame boasts cinematic lighting texture: side backlight outlines soft hair contours, building an oil-painting atmosphere steeped in subtle humanistic poetry with blurred foreground elements. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" widely adopted in contemporary Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**镜06｜喜蛛应巧（中英对照）**：

**中文版：**

```
东方传统古典美学，通篇采用宋词诗意美学基调，盛夏明亮的光感，如宋人小品画般含蓄内敛，复刻江南溪畔的清凉乐趣。近景，盛夏骄阳，田边大槐树下一条浅溪。三位素白丝绸衣裙、佩精致发饰的女子蹲在水中嬉戏，发簪在阳光下闪亮，笑着泼水玩闹。阳光洒在她们脸上与衣上，清浅溪水波光粼粼，透明水面下卵石清晰可见。整体光影电影质感，金光在女子面庞与衣裙上闪烁，氛围柔和朦胧，前景虚化。
```

**英文版：**

```
Rooted in traditional Eastern classical aesthetics, this artwork inherits the soft and elegant poetic charm of Song Dynasty ci poems, creating a misty, translucent scene flooded with bright summer sunlight and rich summery vibes.
It carries the subtle, refined artistic conception of Song Dynasty album leaf paintings and faithfully recreates the leisurely, rustic mortal warmth of rural Jiangnan at dusk.
Close-up shot, midsummer with brilliant sunshine and intense diffused highlights. Beneath a large locust tree beside farmlands lies a shallow stream. Three maidens clad in plain white silk robes and exquisite hair ornaments squat in the water playing. Their hairpins glint brightly under sunlight. The ladies laugh and chat while splashing water.
Sunlight falls on their faces and garments, and the clear shallow stream shimmers with rippling light, revealing smooth pebbles beneath the transparent water surface.
The whole frame boasts cinematic lighting texture: golden light shimmers across the maidens' faces and robes with soft hazy atmosphere, complemented by softly blurred foreground elements. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" prevalent in modern Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**镜07｜溪边吃西瓜（中英对照）**：

**中文版：**

```
东方传统古典美学，通篇采用宋词诗意美学基调，盛夏明亮通透的光感，如宋人小品画般含蓄内敛，复刻江南夏日溪边的闲适烟火。前景，盛夏骄阳，田边大槐树下浅溪。三位素白丝绸衣裙、佩精致发簪的女子蹲在水中，泼水玩闹，一起吃西瓜，笑声不断。发饰在阳光下闪亮，溪水波光粼粼，透明水面下卵石清晰可见。阳光洒在她们脸上与衣上，金光闪烁，氛围柔和朦胧，前景虚化。
```

**英文版：**

```
Rooted in traditional Eastern classical aesthetics, this work inherits the soft and elegant poetic charm of Song Dynasty ci poetry, creating a misty, translucent scene flooded with bright summer sunlight and rich summery vibes. It carries the restrained, refined artistic conception of Song Dynasty album leaf paintings, and faithfully recreates the leisurely, rustic earthly warmth of rural Jiangnan at dusk.
Foreground shot, midsummer with brilliant sunshine and diffused intense highlights. Beneath a large locust tree beside farmlands lies a shallow stream. Three maidens clad in plain white silk robes and exquisite hairpins squat in the water, splashing playfully and eating watermelons. Their hair ornaments glint under sunlight as they chat and laugh while frolicking in the stream. Sunlight falls on their faces and garments, and the shallow water shimmers with rippling sparkles, revealing smooth pebbles clearly beneath the transparent current.
The whole frame boasts cinematic lighting texture: golden light shimmers across the maidens' faces and clothes with soft hazy atmosphere, complemented by blurred foreground elements. This is the immensely popular creative style named "Oriental Lifestyle Aesthetics" widely used in contemporary Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**镜08｜溪中捕鱼（中英对照）**：

**中文版：**

```
东方传统古典美学，通篇采用宋词诗意美学基调，盛夏明亮通透的光感，如宋人小品画般含蓄内敛，复刻江南河边午后的闲适烟火。盛夏河边，金光在水面泛起涟漪，细碎光点如碎钻闪烁。三位素衣女子蹲在溪中徒手捕鱼，鱼跃出水面溅起水花。近景，蓝天白云下生机盎然的夏日景象，金光洒在她们衣上，笑声欢快，如世外桃源般安逸。侧逆光勾勒发丝轮廓，前景虚化，如油画般充满人文诗意。
```

**英文版：**

```
Rooted in traditional Eastern classical aesthetics, this work inherits the mild and elegant poetic verve of Song Dynasty ci poetry, crafting a misty, translucent scene bathed in bright summer sunlight with a strong summery atmosphere and an overall ethereal, clear visual tone. Embracing the subtle, refined artistic conception of Song Dynasty album leaf paintings, it faithfully recreates the laid-back, rustic mortal warmth of countryside Jiangnan at dusk. Bright midsummer sunshine by a small river; golden glimmers ripple across the water surface, and tiny scattered light spots shimmer like broken diamonds under soft glow. Three women in plain robes squat in the stream catching fish, with fish leaping out of the water splashing droplets. Close-up shot, vivid summer scenery under blue skies dotted with white clouds. Golden light shimmers on their garments as they laugh and chat merrily, presenting an idyllic paradise atmosphere with intense diffused highlights. Blue sky and white clouds form the background. The entire frame features cinematic lighting texture: side backlight traces soft outlines of hair strands paired with blurred foreground elements, building an oil-painting atmosphere brimming with delicate humanistic poetry. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" prevailing in modern Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

> 换题材公式：保留①风格段 + ④光影收尾段 + ⑤参数，替换②场景段与③人物段（场景/人物/动作从素材库 P/S/D/A 取词改写即可）。镜01 穿针乞巧英文原段见 3.5.20 七夕节（OCR 截断处已按统一模板补全）。

**衍生示范（V5.5 新增·中英对照 4 条）**——同模板新写，可直接换题材套用：

**衍生① 荷塘采莲（中英对照）**

**中文版：**
```
东方传统古典美学，通篇采用宋词诗意美学基调，清透朦胧的盛夏阳光，江南暮色的烟火人情，如宋人小品画般含蓄内敛。盛夏午后荷塘，碧绿荷叶连天，粉荷在风中轻摇。三位素衣汉服女子乘小木舟穿行莲叶间，纤手探出摘取莲蓬，露珠从叶缘滚落溅起细小水花，清水中映出笑靥，几只蜻蜓点水掠过。小舟缓缓前行，莲叶被划开又在身后轻轻合拢。整体侧逆光勾勒发丝轮廓，前景莲叶虚化，光影通透、温润沉静，完美复刻江南夏日田园的日常烟火气息。
```

**英文版：**
```
Rooted in traditional Eastern classical aesthetics, this work inherits the gentle, elegant poetic charm of Song Dynasty ci poetry, creating a misty, translucent scene bathed in bright summer sunshine with distinct summer vibes, ethereal and clear. It carries the subtle, refined artistic conception of Song Dynasty album leaf paintings, faithfully recreating the leisurely, rustic mortal warmth of countryside Jiangnan at dusk.
Midsummer afternoon on a lotus pond; emerald lotus leaves stretch to the horizon, pink lotus blossoms swaying gently above the water. Three ladies in plain white Hanfu paddle a small wooden boat through the dense lotus leaves, their slender hands reaching out to pick lotus pods, dew drops rolling off the leaves and splashing onto the water surface, creating tiny ripples. Clear water reflects their smiling faces; a few dragonflies skim across the pond. The boat glides slowly, parting the lotus leaves which spring back softly behind it.
The whole frame boasts cinematic lighting texture: side backlight outlines soft hair contours with blurred foreground elements. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" widely adopted in contemporary Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**衍生② 夏日放鸢（中英对照）**

**中文版：**
```
东方传统古典美学，通篇采用宋词诗意美学基调，明净通透的夏日晴光，如宋人小品画般清雅，复刻江南乡村午后的闲适烟火。晴空午后村外草地，天色湛蓝缀白云。白衣素裙女子手持风筝线静立，粉袄小女孩在旁奔跑，二人仰头欢笑，纸鸢乘风越飞越高。身后绿野延展至白墙黛瓦的矮村舍，脚边野花轻摇，风筝线绷直微颤，线尾红绸穗子飘动。侧逆光勾勒发丝轮廓，前景草叶虚化，光影清朗通透，温润自然。
```

**英文版：**
```
Rooted in traditional Eastern classical aesthetics, this work inherits the gentle and elegant poetic charm of Song Dynasty ci poems, creating a bright, airy scene bathed in clear summer sunshine with distinct summer vibes, ethereal and lucid. It carries the subtle, refined artistic conception of Song Dynasty album leaf paintings, faithfully recreating the relaxed, simple mortal warmth of rural Jiangnan at dusk.
A clear summer afternoon on a grassy field outside the village; the sky is a vivid blue dotted with soft white clouds. A young lady in plain white Hanfu with a loose hair bun stands holding a paper kite string, a little girl in a pale pink short jacket runs beside her, both looking up and laughing as the kite soars higher into the wind. Behind them, the green field stretches toward low farmhouses with white walls and dark tiles; a few wild flowers sway at their feet. The kite string is taut and quivering, a red silk tassel fluttering at its tail.
The entire frame boasts cinematic lighting texture: side backlight traces soft hair contours with blurred foreground elements. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" widely adopted in contemporary Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**衍生③ 庭院煮梅汤（中英对照）**

**中文版：**
```
东方传统古典美学，宋词诗意美学基调，盛夏明亮通透的光感，江南暮色的烟火人情，如宋人小品画含蓄内敛。夏日青砖庭院，低矮木案上置小泥炉，旧铁锅咕嘟煮着酸梅汤，蒸汽袅袅升腾。绿襦白裙年轻女子坐炉旁，手摇蒲扇扇火，袖口挽至肘间，额角细汗。身旁竹筛盛着青梅与冰糖罐。槐树荫影斑驳洒落院中，墙头麻雀跳跃，窗边白纱帘随风轻动。侧逆光勾勒发丝与手臂轮廓，前景炉烟虚化，光影暖融，安静治愈。
```

**英文版：**
```
Rooted in traditional Eastern classical aesthetics, this work inherits the soft and elegant poetic charm of Song Dynasty ci poetry, crafting a misty, translucent scene bathed in bright summer sunlight with rich summery vibes. It carries the restrained, refined artistic conception of Song Dynasty album leaf paintings, and authentically recreates the leisurely, rustic earthly warmth of rural Jiangnan at dusk.
A summer courtyard with bluestone floor; a small clay stove on a low wooden table, an old iron pot bubbling with sour plum soup, steam rising in translucent wisps. A young woman in a plain green short blouse and white skirt sits beside the stove, fanning the fire with a palm-leaf fan, her sleeve rolled up to the elbow, beads of sweat on her forehead. A bamboo tray beside her holds fresh green plums and a clay jar of rock sugar. Shade from the locust tree dapples the courtyard, a few sparrows hop on the wall. A white gauze curtain by the window sways gently in the breeze.
The whole frame boasts cinematic lighting texture: side backlight outlines soft hair strands with blurred foreground elements, building a warm, tranquil oil-painting atmosphere steeped in subtle humanistic poetry. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" widely adopted in contemporary Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```

**衍生④ 雨后荷叶接珠（中英对照）**

**中文版：**
```
东方传统古典美学，宋词诗意美学基调，夏雨初霁的清新通透，如宋人小品画般空灵，复刻江南雨后的宁静烟火。仲夏雨后，空气湿润干净，宽大的碧绿荷叶边缘缀着水珠，聚成圆润晶莹的水珠微微颤动。白衣素裙年轻女子跪坐石岸，双手缓缓倾斜一片硕大荷叶，让聚拢的露珠滑入下方青瓷小碗，垂眸凝神，安静专注。身后雨洗过的竹林清亮，茅亭檐角残滴轻落。云缝透出柔光，水珠如碎钻闪烁。侧逆光勾勒发丝轮廓，前景竹叶虚化，清透温润。
```

**英文版：**
```
Rooted in traditional Eastern classical aesthetics, this artwork inherits the gentle, elegant poetic charm of Song Dynasty ci poetry, creating a misty, translucent scene after summer rain, fresh and ethereal. It carries the subtle, refined artistic conception of Song Dynasty album leaf paintings, faithfully recreating the quiet, rustic mortal warmth of rural Jiangnan after the rain.
Just after a midsummer rain, the air is moist and clean; water droplets cling to the edges of large green lotus leaves, gathering into round crystal pearls that tremble and roll. A young lady in plain white Hanfu with loose hair kneels on the stone bank, gently tilting a huge lotus leaf with both hands, letting the gathered dew beads slide into a small celadon bowl held below, her eyes lowered in quiet concentration. Behind her, the rain-washed bamboo grove glistens, and a few drops fall from the eaves of the thatched pavilion. Soft light breaks through the thinning clouds, making the water beads sparkle like scattered diamonds.
The entire frame boasts cinematic lighting texture: side backlight outlines soft hair contours with blurred foreground elements. This is the wildly popular creative style known as "Oriental Lifestyle Aesthetics" widely adopted in contemporary Chinese-style AIGC artworks.
--ar 16:9 --stylize 200 --raw --v 8.2
```


### 每镜头光影示范句

- 纳采：清晨侧逆光勾勒媒人轮廓，朱门反射暖金，光比柔和，尘埃微粒在光中漂浮，面部受光均匀，温婉庄重
- 问名：窗棂透进漫射柔光，红底庚帖上形成一圈琥珀色光晕，桌面阴影柔和过渡，人物面部半明半暗，静谧雅致
- 纳吉：香案烛火作为主光源，暖橙底光自下而上照亮签筒，红布上光影斑驳摇曳，暗部深邃保留细节，庄重神秘
- 纳征：黄昏金光斜射，长街逆光剪影与顺光脸部交替，箱笼红绸在光中泛蜜色，喜庆热烈
- 请期：红烛暖光聚在黄历案面形成光晕中心，四周渐暗，手指投下细长投影，温馨专注
- 亲迎：一串红灯笼提供暖橙主光，新娘盖头边缘透出轮廓光，花轿侧逆光勾边，喜气盈盈
- 收尾：全局暖光铺开，烛火与花瓣在光中飘浮，光比拉平趋向明亮，圆满温馨

### 人物光影专章（光打在"人"身上怎么描述）

> 通用公式管「整体光环境」，本节管「人脸上的光」。写人像/近景/特写镜头时优先用本节。

#### 1. 光位 · 人物版（9 种基础光位）

| 光位 | 光从哪来 | 视觉效果 | 情绪/氛围 | 适用场景 |
|---|---|---|---|---|
| 正面光（顺光） | 从相机/观众方向照向人物面部 | 全亮，阴影少，细节清晰，缺乏立体感 | 直白、明朗、无秘密 | 证件照感、清晨、干净画面 |
| 45°侧光（伦勃朗光） | 从人物侧前方 45° 照射面部 | 3/4 受光，颧骨下方形成倒三角光斑，立体感强 | 质感、深邃、庄重 | 仪式感、正装、古风人像 |
| 90°侧光（分割光） | 从人物正侧面照射 | 面部左右各半——一半亮一半暗，中线分明 | 双面性、悬念、冷酷 | 反派、谍战、内心冲突 |
| 侧逆光 | 从人物侧后方照射 | 面部 2/3 在暗部，侧脸边缘有一道高光轮廓线 | 神秘、柔美、通透 | 晨光/暮色人像、发丝光 |
| 正逆光（轮廓光） | 从人物正后方照射 | 正面全暗，边缘一圈金线/银线，发丝被点亮 | 神圣、崇高、隐匿身份 | 神像感、高阶角色、朦胧美 |
| 顶光 | 从人物正上方照射 | 眼窝深陷、颧骨下方重阴影，鼻梁投影直下 | 压抑、审讯、警惕 | 审讯室、戏剧冲突、神秘祭祀 |
| 底光（脚光/烛台光） | 从人物下方（烛台/地灯）照射 | 自下而上照亮，五官倒置，阴森诡异 | 恐怖、邪气、反叛 | 鬼怪、反派登场、地宫场景 |
| 多光源混合 | 两种以上光源、不同方向不同色温 | 画面层次丰富 | 复杂内心、都市感、戏剧性 | 赛博朋克、夜间冲突、情绪复杂 |
| 漫射光（阴天/窗光） | 光线经大面积散射后照向人物 | 受光均匀，无明显阴影方向 | 柔和、无攻击性、舒缓 | 日常感、书桌窗边、病房 |

> 运镜建议：人物光位效果在近景/特写时最有冲击力，中景次之，全景要配合场景光。

#### 2. 光质 · 人物版

- 柔光（漫射光）：皮肤光洁，阴影柔和 → 古风美人、日常治愈
- 硬光（直射光）：皮肤纹理清晰，阴影锐利 → 戏剧冲突、庄重仪式

#### 3. 光色 · 人物版

| 光色 | 作用在人物上 | 情绪基调 | 适用场景 |
|---|---|---|---|
| 暖橙/琥珀色 | 面部显暖、有温度感 | 温婉、喜庆、庄重 | 烛光、灯笼光、黄昏 |
| 冷青/蓝紫色 | 面部显冷、有距离感 | 清冷、肃穆、孤独 | 月光、阴天、赛博 |
| 白中透暖 | 自然、健康通透 | 治愈、日常 | 晨光、窗光 |
| 金边（逆光） | 轮廓镀金 | 神圣、高阶、神性 | 神像、大人物出场 |

#### 4. 人物光影 4 要素 + 人物专用写法公式

写 prompt 时，人物光影只用 4 个要素就能说清楚：

```
光位（哪个方向照过来）+ 光质（柔/硬）+ 光色（冷暖）+ 落在哪里
```

写法公式（专用于人物）：

```
[光位] + [光质] + [光色] + 落在人物的[具体部位] + [产生的视觉效果] + [情绪词]
```

示例：侧逆柔光，暖金色，落在女子左脸和发丝边缘，勾勒出侧脸轮廓线，发丝被点亮如细金丝，温婉神秘

> **本节公式是人物光影的参考基准**：下面词库（第 5 节）、光位对比（第 6 节）、情绪对照（第 7 节）、
> 组合示范（第 8 节）都按这 6 个字段组织——写任何人物镜头，先套公式填字段，再抄词库选词。

#### 5. 常见人物光效落地写法（替换词库）

| 你想要的效果 | 怎么写进 prompt 示例 |
|---|---|
| 侧脸轮廓被点亮 | 侧逆光，勾出侧脸轮廓线 / 夕阳侧逆光，在女子侧脸边缘勾出一道金线 |
| 发丝发光 | 逆光，发丝被光点亮 / 正逆光透过发丝，每根发丝都泛着暖金光泽 |
| 面部半明半暗 | 45°侧光，面部明暗交界分明 / 伦勃朗光，左脸明亮右脸隐没于暗部 |
| 颧骨下方三角光 | 伦勃朗光，颧骨下方留光 / 窗光 45° 斜照，颧骨下方形成经典倒三角高光 |
| 瞳孔有光点 | 光源反射在瞳孔中 / 烛火映在瞳孔中，两点暖光如星 |
| 面部全亮无阴影 | 正面顺光，光比平 / 清晨顺光，面部受光均匀，毫无阴影 |
| 眼窝深陷/鼻影重 | 顶光直射，眼窝鼻梁阴影锐利 / 穹顶天光直下，眼窝深陷如墨，鼻影垂直拉长 |
| 衣褶光影 | 侧光斜照衣料，褶皱投下阴影 / 侧光打在绢纱广袖上，每一道褶皱都在地面投下细长影子 |
| 泪光/眼眶泛光 | 光斑落在眼眶，反射湿润光泽 / 烛光落在她眼眶中，泪光折射出细碎光芒 |
| 人脸与背景光分离 | 人脸用侧光，背景压暗 / 人脸 45° 侧光照亮，背景暗部深不见底 |

#### 6. 落地示例：同一场景 5 种光位写法

场景：古风女子坐于窗前，素衣，垂眸

| 光位 | 完整 prompt 写法 | 效果 |
|---|---|---|
| 正面顺光 | 清晨正面顺光，面部受光均匀，眉眼清晰，阴影浅淡，素衣纹理可见，画面干净通透，温婉明媚 | 清纯、无心事 |
| 45°侧光 | 窗光 45° 斜照左脸，左颧骨下方形成倒三角光斑，右脸隐于柔阴影中，鼻梁投影微斜，五官立体分明，庄重深邃 | 质感、内敛、有故事 |
| 侧逆光 | 窗光从左侧后方漫射进入，女子左脸及发丝边缘勾出一线暖金，面部右侧大部浸在柔和暗部，衣袂边缘透光如蝉翼，静谧朦胧 | 神秘、通透、柔美 |
| 正逆光 | 背对窗外天光，女子面部全暗仅见轮廓，发丝被光炸成金线网，衣料边缘透出光的纹理，看不清表情，神圣肃穆 | 隐匿身份、神圣、神明感 |
| 顶光 | 天窗顶光直射而下，女子垂眸时眼窝陷为两团暗影，鼻梁投下垂直阴影直抵上唇，颧骨下方重影交错，压抑庄重 | 警惕、压抑、戏剧冲突 |

#### 7. 人物光影 × 情绪对照表

| 你想要观众感受 | 用这个光位 | 光质 | 光色 | 补充写法 |
|---|---|---|---|---|
| 温暖、被治愈 | 45°侧光或侧逆光 | 柔光 | 暖橙/金黄 | "光像手一样轻抚她的脸" |
| 神秘、看不透 | 侧逆光 | 柔光 | 白中透暖 | "面部大半隐于暗部，只留一线金边" |
| 庄重、有威严 | 伦勃朗光（45°侧光） | 柔硬适中 | 暖琥珀 | "颧骨下三角光斑分明，目光深邃" |
| 孤独、有距离感 | 正逆光或漫射冷光 | 柔光 | 冷青/冷灰 | "她逆光而立，面无表情，周身被冷光包裹" |
| 危险、压抑 | 顶光或 90° 侧光 | 硬光 | 冷白 | "顶光让眼窝如洞，面目在光影中被切割" |
| 神性、不可触及 | 正逆光（全剪影） | 硬光或柔光 | 金边 | "整个人融于光中，只剩一圈金线勾勒的轮廓" |
| 通透、像会发光 | 侧逆光+漫射补光 | 柔光 | 暖白/暖金 | "光线穿透衣料，皮肤仿佛自内而外透光" |

#### 8. 组合写法示范（3 个完整 prompt）

古风·侧逆光温婉人像：

```
V1 古风·庄重仪式基调。轩窗边，女子着藕荷色宋制襦裙，发髻簪白玉簪，侧身而坐。侧逆光从窗外漫射而入，光质柔软如雾，暖金色，落在她左脸与发丝边缘，勾出一道温润的轮廓线——侧脸线条被光描得分明，耳廓透出薄红，发丝被点亮如细金丝。面部其余部分浸在柔和暗部中，唯眼角有一点光斑，眸光微润。近景固定镜头，画面安静如古画。85mm定焦，f/2.0，ISO 400，侧逆暖光。
[负面词] 手部畸形, 五官错位, 过曝, 低质量。
```

> **公式对照**：光位=侧逆光｜光质=柔光｜光色=暖金｜落在=左脸+发丝边缘｜效果=温润轮廓线+发丝金丝｜情绪=温婉静谧

现代·黄昏逆光孤独人像：

```
V3 现代·都市日常基调。天台上，主角着深灰色长风衣，背对夕阳站立。正逆光，黄昏日光从身后直射，硬光偏暖，在她周身镀上一圈金边——发丝被光炸开成细碎金网，风衣肩线被高光勾勒，衣摆边缘透光如薄翼。面部全暗仅见侧脸轮廓，眉心被光边擦亮一点，其余沉入暗部。低机位仰拍中景，夕阳在她身后形成巨大光晕。24mm广角，f/4，ISO 200，逆光暖调。
[负面词] 过曝, 面部全黑无细节, 低质量。
```

> **公式对照**：光位=正逆光｜光质=硬光｜光色=暖金（黄昏）｜落在=周身轮廓+发丝+肩线+衣摆｜效果=金边镀层+发丝金网+衣摆透光｜情绪=孤独疏离

古风·45°伦勃朗光庄重人像：

```
V1 古风·庄重仪式基调。殿堂内，一位绛纱深衣的男子端坐于香案前。45°侧光从左侧高窗斜射而下，硬光为主，暖琥珀色，照在他左脸——颧骨下方形成经典倒三角光斑，鼻梁右侧投下细长阴影，右脸浸没于深棕色暗部，左右脸在鼻梁中线处完成明暗切换。目光直视镜头，左眼有光点，右眼隐于暗处。中景固定镜头，构图居中对称。85mm定焦，f/2.8，ISO 400，高窗侧光。
[负面词] 手部畸形, 五官错位, 光斑过锐, 低质量。
```

> **公式对照**：光位=45°侧光（伦勃朗）｜光质=硬光为主｜光色=暖琥珀｜落在=左脸+颧骨+鼻梁+右脸｜效果=倒三角光斑+细长鼻影+明暗中线切换｜情绪=庄重威严

---

### 斑驳光影专章（光斑 / 漏光 / 投影——高频形态）

> 光线穿过树叶、窗棂、帘幕等遮挡物后，在人物/地面/墙面上形成的破碎光斑——电影感画面里最出效果的光影形态。

#### 1. 核心公式

```
遮挡物（光从哪穿过）+ 投影载体（光落在哪）+ 光斑形态（长什么样）+ 动态（动不动）+ 情绪
```

写法公式：

```
[遮挡物] + 将光切割成 [光斑形态]，[光斑] 落在 [载体] 上，[动态]，[色彩基调]，[情绪词]
```

#### 2. 遮挡物词库（光穿过什么）

| 类别 | 遮挡物 | 光斑效果 |
|---|---|---|
| 植物 | 树叶/竹叶/芭蕉叶/藤蔓/花枝 | 细碎、多孔、大小不一、边缘模糊 |
| 建筑 | 窗棂/门洞/漏窗/格扇/百叶窗/拱券 | 几何规整、条状/方格/菱形 |
| 织物 | 纱帘/竹帘/帷幔/刺绣幔帐 | 柔和、条状渐变、纤维纹理透光 |
| 自然 | 云层/山影/水面波纹 | 大面积流动、动态斑驳、无规律 |
| 人工装饰 | 灯笼骨架/铜钱纹/万字纹/冰裂纹 | 图案投影、文化符号、精致 |

具体写法示例：
- 晨光穿过窗棂，在青砖地上投下规整的菱格光斑
- 阳光透过竹帘，在女子侧脸上切出一道道平行光影条纹
- 树影婆娑，光斑如碎金洒在石阶上，随风晃动

#### 3. 光斑形态词库（光斑长什么样）

| 形态类型 | 描述词 | 适用场景 |
|---|---|---|
| 细碎斑点 | 碎金、光点如星、斑驳如鳞 | 树荫下、穿林光 |
| 规整几何 | 菱形光格、方格阵列、条状光影 | 窗棂、百叶窗 |
| 条状渐变 | 光影条纹、平行光带、栅栏投影 | 竹帘、格栅 |
| 流动水影 | 水光潋滟、光纹流动、碎波光影 | 水面反射、波光 |
| 图案投影 | 梅影、竹影、冰裂纹投影、铜钱纹 | 漏窗、雕花门窗 |
| 大面积斑驳 | 光斑交错、明暗交织、光影拼图 | 林中、庭院 |
| 边缘模糊 | 光影晕染、光斑柔焦、雾中光点 | 透过纱帘、晨雾 |

#### 4. 投影载体（光落在哪）

| 载体 | 效果 | 写法 |
|---|---|---|
| 地面 | 大面积、稳定、视觉锚点 | 光斑在青石板上铺成一条光路 |
| 墙面 | 垂直、叙事性强 | 窗影在粉壁上拉成长条菱形 |
| 人物面部 | 情绪集中、视觉焦点 | 光斑在左颊上晃动，明明灭灭 |
| 人物身体/衣物 | 动态、质感 | 竹帘光影在她裙裾上画出一道道平行线 |
| 桌面/物件 | 静物感、细节 | 光斑在紫砂壶身上缓缓游移 |
| 水面 | 流动性最强 | 波光在池面上碎成万点银鳞 |

#### 5. 动态词库（光斑动不动、怎么动）

| 动态方式 | 描述词 | 触发原因 |
|---|---|---|
| 缓慢移动 | 缓缓游移、慢慢爬升、一寸一寸挪动 | 太阳位置变化 |
| 摇曳晃动 | 摇曳、晃动、忽明忽灭 | 风吹树叶/帘幕 |
| 忽明忽暗 | 明灭不定、闪烁、时隐时现、明明灭灭 | 云过/风动 |
| 流动 | 流动、流转、滑过 | 水面波光/雾中光柱 |

#### 6. 情绪词库（斑驳光影传达什么）

| 光斑状态 | 情绪 |
|---|---|
| 细碎光斑在脸上晃动 | 不安、期待、回忆闪回 |
| 窗格光影端正铺满墙 | 秩序、安稳、禁锢 |
| 树影斑驳在石阶上 | 静谧、时光流逝 |
| 光斑在脸上明灭不定 | 内心波动、犹豫 |
| 条纹光影在身上切割 | 禁锢、抽离、结构化 |
| 水光在瞳孔中晃动 | 出神、温柔、梦境感 |

#### 7. 完整落地写法 · 9 种经典场景

**场景 1｜树影斑驳 · 林中光**

午后林间，阳光穿过层层叠叠的树冠，被枝叶切割成无数细碎光斑，如碎金般洒落在地上，在青草间明明灭灭。风过时，光斑缓缓晃动，像无数只金色的蝴蝶在地面上浮动。

- 拆解：遮挡物（树叶树冠）+ 光斑形态（细碎如碎金）+ 载体（地面）+ 动态（风过晃动）+ 情绪（静谧）+ 比喻（金蝶）

**场景 2｜竹影横斜 · 窗棂漏光**

晨光透过竹帘，在木地板上切出一道道平行的光影条纹，条状光带从窗边一路延伸到室内深处，随竹帘微动而轻颤。女子赤足坐在光带边缘，脚踝一半浸在光中，一半隐于阴影。

- 拆解：遮挡物（竹帘）+ 光斑形态（平行条纹）+ 载体（木地板）+ 动态（轻颤）+ 人物局部互动

**场景 3｜树影摇曳 · 斑驳面庞（人像核心场景）**

午后阳光穿过窗外摇晃的梧桐叶，光斑在女子侧脸上明灭不定——一道光从额头滑到颧骨，又倏然移开，她的眸光随着光斑的游移而微微颤动，仿佛在光与影的交替中藏着一个无法说出口的秘密。

- 拆解：遮挡物（梧桐叶）+ 光斑形态（碎光）+ 载体（面部）+ 动态（明灭不定/滑动）+ 情绪（内心波动）

**场景 4｜灯笼光 · 雕花门窗**

暮色中，室内烛火透过雕花窗棂（冰裂纹），在青砖墙上投下大片冰裂纹状的光影图案，光纹随烛火摇曳而缓慢旋转，整个墙面如同一幅正在呼吸的古画。

- 拆解：遮挡物（雕花窗棂）+ 光斑形态（冰裂纹图案）+ 载体（墙面）+ 动态（烛火摇曳）+ 情绪（呼吸感）

**场景 5｜滴水光 · 芭蕉影动**

雨后的天光穿过庭院中的芭蕉叶，在湿漉漉的青石板上投下大块墨绿色的光影，叶影随微风轻晃，光斑在积水表面碎成万点银鳞，漾开一圈圈微光。

- 拆解：遮挡物（芭蕉叶）+ 光斑形态（大块斑驳+水面碎光）+ 载体（青石板+积水）+ 动态（叶影晃动）+ 情绪（湿润静谧）

**场景 6｜纱帘透光 · 风动光移**

晨风拂过落地窗前的白纱帘，纱纹将晨光揉碎成一片柔焦光影，光斑在木地板上缓缓游移，随纱帘起伏而变幻形状，时圆时扁，像晨光本身有了呼吸。

- 拆解：遮挡物（白纱帘）+ 光斑形态（柔焦、边缘模糊）+ 载体（木地板）+ 动态（随纱帘起伏）+ 情绪（呼吸感）

**场景 7｜水光潋滟 · 倒影斑驳（室外）**

午后的阳光斜照水面，波光在池面上碎成万点银鳞，光影从水底反投到池边廊柱和梁枋上，一道道水光在红漆柱身上缓缓游移，整个廊下都在微微发光。

- 拆解：遮挡物（水面波纹）+ 光斑形态（碎光、银鳞）+ 载体（廊柱、梁枋）+ 动态（水光游移）+ 情绪（梦幻）

**场景 8｜古建筑 · 重檐叠影**

夕阳西下，重檐屋顶在粉壁上投下层层叠叠的斜长阴影，檐角在墙面上拉出两道交错的斜影，瓦当的圆形投影如一枚枚墨色的铜钱，整面墙被光影切成一幅水墨构成。

- 拆解：遮挡物（重檐屋顶）+ 光斑形态（斜长阴影、圆形瓦当投影）+ 载体（粉壁）+ 动态（随日落延长）+ 情绪（时间的流逝、沧桑）

**场景 9｜古建筑 · 窗棂漏光**

午后烈日透过窗棂（菱花格），在白墙上投下一整面规整的菱花光影阵列——数十个菱形光格紧密排列，边缘锐利分明，像一枚印在墙上的巨大古印章。光格之间，尘埃在光柱中缓缓浮动，金光细碎。

- 拆解：遮挡物（菱花格窗棂）+ 光斑形态（菱形阵列、规整）+ 载体（白墙）+ 动态（尘埃浮动）+ 情绪（秩序感、时光凝滞）

#### 8. 完整 prompt 示例（可直接复制）

场景 3 完整版｜树影斑驳 · 人像（古风）：

```
V2 古风·清冷意境基调。午后轩窗边，窗外梧桐叶影摇曳，阳光被层层树叶切割成细碎光斑，透过窗棂落在女子素衣上——光斑在她左肩至锁骨处明明灭灭，随风晃动，如金色的碎蝶在衣料上徘徊。女子垂眸静坐，光影在面颊上缓缓滑过，从眉心到唇角又倏然移开。近景固定镜头，镜头中光斑与沉静的脸形成张力——光在动，人不动。85mm 定焦，f/2.0，ISO 400，漫射天光+斑驳光影。
[负面词] 手部畸形, 五官错位, 过曝, 低质量。
```

场景 4 完整版｜烛火透过雕花门窗（古风·室内）：

```
V1 古风·庄重仪式基调。暮色中的古殿内室，烛火透过雕花冰裂纹窗棂，在白墙上投下一整面冰裂纹状的光影图案——光纹如蛛网般在墙面展开，随烛火摇曳而缓慢旋转、微微脉动，仿佛墙面本身在呼吸。一位青衣仙子跪坐于光影图案中央，墙上的冰裂纹光线正好笼住她全身，令她仿佛被封印在一幅古老的光之符文中。中景固定镜头，构图对称居中。50mm 定焦，f/2.8，ISO 800，烛火透过窗棂的投射光，暖橙色调，光晕微颤。
[负面词] 手部畸形, 模糊, 过曝, 低质量, 文字乱码。
```

场景 9 完整版｜窗棂漏光（古风·室内）：

```
V2 古风·清冷意境基调。正午轩窗，菱花格窗棂将烈日切割成数十个规整的菱形光格，在素白墙面上印下一整面菱花阵列——光格边缘锐利分明，如一枚巨大的古印章钤在墙上。光柱中，尘埃缓缓浮动，每一粒金尘都在光束中独立悬停、缓慢旋转。一位白衣仙子立于光格阵列中央，光影在她身上与墙面上形成对称的明暗分区——面颊一侧被菱光点亮，一侧隐于暗部。中景固定镜头。35mm 广角，f/5.6，ISO 200，窗棂投影光，暖白调。
[负面词] 手部畸形, 过曝, 模糊, 低质量。
```

场景 8 完整版｜重檐叠影（古风·室外庭院）：

```
V2 古风·清冷意境基调。傍晚，夕阳将重檐屋顶的轮廓在粉壁上拉出三道交叠的斜长阴影——檐角、瓦当、垂脊层层投影递进，瓦当的圆形投影如一枚枚墨色铜钱阵列，在墙面上排成一条弧线。一位素衣道人负手立于影壁前，斜阳将他的身形拉长，与檐影在墙上交叠——人影与檐影之间隔着一道未落地的空隙，仿佛人与屋檐之间隔着一段无法越过的光阴。低机位平视全景。35mm 广角，f/5.6，ISO 200，黄昏暖光，琥珀色温，长影铺地。
[负面词] 手部畸形, 模糊, 现代物品穿帮, 低质量。
```

#### 9. 光斑 × 情绪快速对照

| 场景类型 | 写进 prompt 的关键句 | 观众感受 |
|---|---|---|
| 光斑在脸上明明灭灭 | 光斑在面颊上明灭不定，如同未出口的话 | 犹豫、怀念、内心翻涌 |
| 窗格光影端正铺满墙 | 整面墙被菱光铺满，如一枚巨大的古印 | 秩序、岁月、禁锢 |
| 树影婆娑在石阶上 | 树影在青石板上轻轻晃动，光斑如碎金 | 静谧、时间缓慢流逝 |
| 竹帘条纹在身上切割 | 竹帘光影在衣袂上画出一道道平行横纹 | 困住、疏离、被规则约束 |
| 波光在瞳孔中晃动 | 水面碎光在她瞳孔中跳跃 | 出神、温柔、梦境感 |
| 纱帘光斑在地板游移 | 纱纹将光揉碎成柔焦影子，在地板上缓缓游移 | 治愈、呼吸感、慵懒 |
| 烛火雕花影在墙上旋转 | 冰裂纹光纹随烛火摇曳，整面墙像在呼吸 | 神秘、生命感、困在光符中 |

> 用法：把「关键句」直接写进 prompt 的「光影」段落，其他部分照常组装。

## 二·五、天气时令光效速查表（雪/雨/雾/月夜/黄昏/深夜/清晨/秋日）

> 集中表：天气与时令的光影写法此前散落各处，这里一表收全。写法拼进 prompt 的「光影」段。

| 天气/时令 | 光影写法 | 情绪 | 适用 |
|---|---|---|---|
| 雪天 | 雪光漫反射，冷蓝调，雪花逆光成金点，雪地反光补亮面部 | 静谧、苍茫 | 冬日古风/思乡/腊祭 |
| 雨天 | 雨丝逆光成银线，湿地面倒映灯影与霓虹，水滴在伞面折射 | 清冷、愁绪 | 江南雨巷/离别/撑伞 |
| 雾天 | 晨雾漫射，丁达尔光柱穿雾，人物剪影，远景隐没 | 空灵、神秘 | 山间/江上/朝圣/巨物 |
| 月夜 | 冷白月光，轮廓光，蓝灰调，月下银边勾发丝 | 清幽、孤寂 | 庭院凭栏/夜读/七夕 |
| 黄昏 | 琥珀色温，长影铺地，逆光金边，晚霞映水 | 温暖、怅然 | 归家/离别/秋日 |
| 深夜 | 黑场中烛火/灯笼成光点，暗部深邃，光比极大 | 幽深、紧张 | 夜奔/捉迷藏/秘会 |
| 清晨 | 低角度金色斜光，薄雾未散，露珠反光，光斑拉长 | 清新、希望 | 劳作/出远门/市集开市 |
| 秋日 | 暖金低饱和，枯叶光斑，斜长影，尘光漂浮 | 怀旧、从容 | 丰收/读书/晒秋 |

**春/夏/冬光效三句速写（与秋日形成四季闭环）**：

- 春：花影粉光——桃花瓣透光泛粉，新叶滤光成翠影；薄雾晨光——晨雾漫射柔光，人脸如罩轻纱；纸鸢逆光——风筝逆光成剪影，丝线泛金光
- 夏：烈日白光——正午高对比白光，檐影浓黑；树荫碎影——叶隙光斑如碎金洒地，随风晃动；荷塘波光——水面碎光如银鳞，反射到桥底；夕照流金——黄昏金红浸染，长影铺水
- 冬：雪地反光——雪面漫反射补亮面部，冷蓝调；寒夜冷月——冷白月照雪地，光色加倍清冽；炭火暖光——炉火暖橙与窗外冷雪对照，双色温；冰棱折射——檐下冰棱折射出细碎七彩光斑

## 二·六、夜间光影专章（灯笼阵列/烛火室内/提灯/月相/星野）

> 夜间场景光效分级写，直接拼进 prompt 的「光影」段。

**灯笼阵列三档（光度/密度逐级）**：

| 档 | 写法 | 效果 |
|---|---|---|
| 一盏 | 一盏红灯笼悬于檐角，光晕孤悬，四周暗部深邃 | 孤独、指引、悬念 |
| 一排 | 一串红灯笼沿廊排列，光点连成暖线，照亮檐下 | 行进、仪式、喜庆 |
| 满街如龙 | 满街灯笼高低错落，光潮如龙蜿蜒过市，人脸皆被暖光映红 | 灯会、狂欢、人潮 |

**烛火室内四档**：

| 档 | 写法 |
|---|---|
| 单烛台 | 一枝烛火在案头明灭，光只照亮尺许方圆，四壁隐于暗处 |
| 多烛台 | 数支烛台错落摆放，光影在墙面上层叠交错，摇曳同步 |
| 烛光满堂 | 满室烛火齐燃，暖光铺满每面墙，人影幢幢浮动 |
| 烛影摇红（高级） | 烛火摇曳，红绸与屏风上光影如水波流动 |

**提灯种类光效**：

| 灯种 | 光效 |
|---|---|
| 马灯 | 玻璃罩透出稳定黄光，适合夜行/赶路，光晕聚焦 |
| 纱灯 | 纱面滤光柔蒙，光晕大而淡，适合庭院/闺阁 |
| 纸灯（灯笼） | 竹骨纸面透出暖橙光，光影斑驳，市集/节庆 |
| 宫灯 | 多角琉璃面，光色清透偏亮，贵族夜宴/宫苑 |

**月相三态（不同色温）**：

| 月相 | 写法 | 色温情绪 |
|---|---|---|
| 新月如钩 | 一弯银钩悬空，光弱，轮廓线细 | 清冷、宿命感 |
| 满月如盘 | 玉盘当空，月华如练铺满庭院，地面亮如薄霜 | 圆满、庄重、思乡 |
| 残月如弓 | 半残月悬天际，光色偏冷黄，长影拖地 | 苍凉、离别、余韵 |

**星野氛围**：

```
星河横跨夜空，流萤几点缀于草丛，银河如淡纱斜过天顶，星光在湖面碎成万点银针
```

**夜行光影组合示例**：月夜提马灯行于青石巷——冷蓝月光铺满巷面，手中马灯投出暖黄光圈，一冷一暖双色温并置，人影在墙上拖成细长剪影。

## 三、画面美学词库（场景·服装·道具）

### 3.1 场景描写

### 场景描述公式

**环境动态链（让场景"活"起来·外部高分验证）**

```
[风吹过] → [水/光/叶依次动] → [动物或人物出现] → [情绪落点]
```

示例：微风拂过，池中水光在日光下晃动似碎金般闪烁，池边垂柳枝条轻摆，几只锦鲤在水中摆尾游弋，氛围闲适悠然。

```
光线质感 + 材质细节 + 色彩点缀 + 纵深层次 + 动态氛围 + 情绪词
```

**场景·人物情绪匹配表（人物情绪与场景情绪联动·风格不打架）**

| 人物情绪 | 匹配场景 | 场景写法 |
|---|---|---|
| 孤独落寞 | 月下空庭 / 长廊尽头 / 暮色旷野 | 月光铺满空无一人的青石阶，长廊向暗处延伸 |
| 欢愉轻盈 | 春日花下 / 市集人流 / 荷塘游船 | 花瓣随风落在肩头，人群喧闹声如潮水 |
| 庄重肃穆 | 高堂大殿 / 祠堂香案 / 雪原 | 穹顶高不见顶，香火青烟直上，无风 |
| 隐秘紧张 | 夜巷 / 密室 / 竹林暗处 | 灯笼光晕只照亮脚下半步，树影在风中晃动 |
| 温婉闲适 | 窗下 / 庭院回廊 / 茶室 | 窗棂筛下细碎光斑，茶烟袅袅不散 |
| 苍凉怀旧 | 荒宅 / 秋园 / 残荷池边 | 枯枝在斜阳下拉出长影，尘光在空屋里浮动 |

**朝代场景风貌速查表（写"唐代宫廷"有方向：唐重金碧、宋重素雅、明清重繁复）**

| 朝代 | 色彩 | 材质 | 建筑 | 空间感 |
|---|---|---|---|---|
| 唐 | 朱红 / 金碧 / 翠绿 | 锦缎 / 鎏金 / 彩绘 | 高台 / 大屋檐 / 斗拱雄大 | 开阔宏丽 |
| 宋 | 素白 / 青灰 / 藕荷 | 棉麻 / 素瓷 / 竹木 | 小庭院 / 格子窗 / 卷帘 | 幽深雅致 |
| 明/清 | 深红 / 藏蓝 / 墨绿 | 紫檀 / 青花 / 刺绣 | 高墙深院 / 雕梁画栋 | 繁复威严 |

用法：写场景先定朝代 → 从色彩/材质/建筑取词 → 再按人物情绪从匹配表选场景写法 → 时代与情绪两层都不跑偏。

### 3.1.1 市井街巷词库（写街市/灯会/集市/人群用）

| 维度 | 可选词 |
|---|---|
| 街巷空间 | 临街茶楼 / 布幌招展 / 杂耍摊 / 说书台 / 青石板路 / 水井旁 / 戏台 / 石桥头 / 坊门牌楼 / 檐下廊柱 |
| 群体人物 | 商贩吆喝 / 孩童追逐 / 路人驻足 / 轿夫抬轿 / 货郎挑担 / 卖花女穿行 / 掌柜拨算盘 / 舞龙队开路 / 书生摇扇过 / 茶客闲谈 |
| 集市光影 | 晨光斜照摊位 / 油纸伞影交错 / 炊烟与人流交织 / 灯笼暖潮漫过街面 / 摊火映红人脸 / 香雾在食摊升腾 / 车辙反光 / 檐灯连成一线 / 尘土在光柱浮动 / 夜灯把人群剪成剪影 |
| 集市声响（写 BGM/环境音段用） | 叫卖声此起彼伏 / 铜钱叮当 / 孩童笑闹 / 锣鼓开道 / 茶客闲谈嗡嗡 / 算盘噼啪 |

写法示例：临街茶楼二层竹帘半卷，楼下布幌招展、货郎挑担穿行，晨光斜照青石板路，蒸笼白雾与人流交织，灯笼暖潮沿街铺开。

### 古风美学词库

| 维度 | 功能词（普通版） | 雅词（高端版） |
|---|---|---|
| 光线质感 | 烛影摇曳 / 暖晕 / 窗棂透光 / 光影斑驳 / 金尘浮动 / 夕照镀金 | 烛影摇红 / 流光溢彩 / 疏影横斜 / 月华如练 / 霞染琉璃 / 雾霭氤氲 / 光晕流转 |
| 材质细节 | 雕花木栏 / 朱漆门 / 青砖黛瓦 / 琉璃瓦 / 绢纱幔帐 / 铜镜 / 锦缎 | 鎏金錾花 / 螺钿镶嵌 / 檀木雕花 / 云锦流苏 / 缂丝屏风 / 青瓷釉光 / 汉白玉阶 / 朱漆斑驳 |
| 色彩点缀 | 红绸结 / 灯笼串 / 芭蕉 / 桃枝 / 花树 / 香炉青烟 | 绛纱 / 绯罗 / 藕荷 / 黛青 / 鎏金 / 胭脂 / 苍翠 / 玄青 / 红绸如瀑 |
| 纵深层次 | 庭院深深 / 长廊纵深 / 月洞门框景 / 檐角飞翘 / 台阶层叠 | 曲径通幽 / 廊腰缦回 / 檐牙高啄 / 重檐叠瓦 / 雕梁画栋 / 回廊九曲 |
| 动态氛围 | 花瓣飘落 / 烛火轻摇 / 纱幔轻拂 / 晨雾 / 尘埃浮动 / 烟火 | 香雾空蒙 / 落英缤纷 / 雨打芭蕉 / 风摇竹影 / 轻烟袅袅 / 飞花逐月 / 纱幔轻扬 |

### 现代美学词库

| 维度 | 功能词（普通版） | 雅词（高端版） |
|---|---|---|
| 光线质感 | 晨雾光 / 逆光轮廓 / 霓虹光斑 / 车流光轨 / 百叶窗条纹光 | 丁达尔光束 / 暮色苍茫 / 华灯初上 / 霓虹晕染 / 逆光金边 / 柔焦雾感 / 冷月清辉 |
| 材质细节 | 磨砂玻璃 / 原木 / 哑光金属 / 织物垂坠 / 水磨石 / 清水混凝土 / 波纹钢板 / 中古柚木 / 磨砂亚克力 / 旧砖墙 | 胡桃木 / 哑光黄铜 / 真丝垂坠 / 超白玻璃 / 侘寂陶器 / 青灰水泥 / 做旧钢面 |
| 空间层次 | 城市天际线 / 街巷纵深 / 玻璃幕墙倒影 / 天台开阔 / 屋顶露台 / 地下通道 / 高架桥下 / 玻璃连廊 / 老厂房改造 | 天际线剪影 / 幕墙倒影 / 天台旷远 / 极简留白 / 中古器物 / 连廊纵深 / 厂房天窗 |
| 动态氛围 | 车流 / 雨丝 / 风吹衣角 / 蒸汽升腾 / 光斑移动 / 行人剪影 / 霓虹闪烁 / 雨刮器摆动 / 电梯升降 / 外卖箱摇晃 | 蒸汽升腾 / 雨丝斜织 / 风吹衣袂 / 光影流动 / 云影游移 / 尘埃浮光 / 霓虹明灭 / 车灯拖影 |
| 城市氛围光效 | 路灯把影子拉得很长 / 霓虹光晕染湿路面 / 电梯门开合时反光 / 便利店冷藏柜冷白光 / 手机屏光映亮人脸 / 外卖箱 LED 闪烁 / 自动门开合吐出一道光 / 公交站广告牌亮屏 / 高架桥下车灯成河 / 天台广告灯箱嗡鸣 | 路灯拉长影 / 霓虹晕湿 / 冷柜白光 / 屏光映脸 / LED 明灭 / 灯箱嗡鸣 / 车灯成河 |
| 现代人物状态 | 晨起哈欠揉眼 / 地铁上低头刷手机 / 便利店加热便当等微波炉叮 / 天台等日出 / 夜跑擦汗喘气 / 加班后靠椅发呆 / 雨中等车跺脚 / 外卖员跑进写字楼 / 清晨赶早班叼着包子 / 深夜便利店买关东煮 | 晨起懵懂 / 通勤倦容 / 等日出微光 / 夜跑喘息 / 加班虚脱 / 雨中等待 / 深夜一人食 |

### 通用氛围质感词（点睛用）

```
静谧克制 / 松弛慵懒 / 电影叙事感 / 油画肌理 / 杂志大片 / 侘寂 / 空灵 / 缱绻 / 迷离 / 疏离感
```

### 对照示例（普通 → 美学 → 高端）

**古风·纳采**

- 普通：红墙、灯笼、绿植，媒人捧雁站在门前
- 美学：深红宫墙被夕照镀成琥珀色，檐角红灯笼泛着暖晕，墙头探出的芭蕉叶在风里轻晃，光影在青砖缝间缓缓流动
- 高端：朱漆大门在暮色里泛着温润的光，檐角宫灯如豆，光晕在青砖地上洇开一圈暖色；门前石榴树影婆娑，风过时落红轻旋，媒人捧雁立于阶前，金尘周身浮动

**现代·咖啡**

- 普通：咖啡店、落地窗、木桌，主角捧杯
- 美学：落地窗外晨雾未散，磨砂玻璃滤进柔和天光，杯口蒸汽在光柱里缓缓升腾
- 高端：落地窗滤进晨雾里微凉的天光，吧台哑光黄铜泛着细碎光点，杯口蒸汽在丁达尔光束里盘旋上升，静谧得像一帧电影定格

### 用法口诀

1. 每句场景里挑 1 个雅词就够，不堆砌（一句景一句雅词，画面立刻贵起来）
2. 场景描写至少含 1 光效 + 1 材质 + 1 动态元素，画面才活
3. 普通版用于写实画面，雅词版用于氛围/高级感画面

### 雅词使用三原则

1. **每句不超过 2 个雅词**，多则油腻（一条场景句 1 个雅词为佳）
2. **雅词优先用在"景"**（光线/材质/动态），**少用在"人"**——人物描写保持真实克制，堆在人物身上会显得假
3. **关键帧才上满雅词**：开场定场 / 结尾收束 / 情感特写用满；叙事 / 中景镜头用功能词

### 完整镜头应用示范（雅词落地版）

**示范 1｜古风·纳采（第十一章示例的雅词重写）**

> 暮色四合，朱漆大门泛着温润的釉光，檐角宫灯如豆，光晕在青砖地上洇开一圈暖色；门前石榴树影婆娑，落红轻旋。媒人着青绿古装，捧雁立于阶前，衣袂被晚风拂动，金尘周身浮动。低机位缓慢推镜，从大雁特写推至媒人全身。85mm 定焦，f/2.0，ISO 320，侧逆光暖调。

**示范 2｜古风·黄昏宫墙（第十二章古代写真镜头 4 的雅词重写）**

> 暮色浸染宫墙，夕照在琉璃瓦上熔成金线，墙头探出的花枝被风拂动，落瓣无声飘落。女子逆光而立，披帛在光里透出绢纱纹理，发丝镀上金边，抬手轻挡光线。低机位仰拍。85mm，f/2.0，ISO 200，黄昏逆光，配纯箫声。

**示范 3｜现代·晨光窗边（第十二章现代写真镜头 1 的雅词重写）**

> 晨雾未散，落地窗滤进微凉天光，光柱里尘埃浮光缓缓游动。主角着白衬衫坐于窗边，晨光勾勒侧脸轮廓，发丝被光点亮，抬头望向光的方向。缓慢推镜。85mm，f/2.0，ISO 320，自然晨光。

**示范要点**：每个场景只用了 1-2 个雅词（釉光/如豆/洇开/熔成金线/尘埃浮光），画面立刻脱离"生活感"，但雅词密度不高，读起来依然自然。

### 3.2 服装描写


### 服装描写公式

```
款式形制 + 材质 + 颜色雅称 + 工艺细节 + 动态效果(衣袂/珠翠) + 身份呼应
```

**三段式写法（外部高分验证·自上而下锚点，AI 还原更准）**

两种变体任选，核心都是"自上而下分层、每段给形制+纹样"：

```
变体 A（全身分层）：配色先行 + 外罩 + 下着 + 脚踩（鞋履）
变体 B（上身细分）：配色先行 + 上衣（交领/襦）+ 外罩（褙子/纱领）+ 下着（百褶裙/百迭裙）
```

示例 A：深白配苔绿色束腰汉衣——交领长衫配布质腰带；外罩月白锦缎袍子，下着绣缠枝莲纹软缎长裙，脚踩绣金莲软鞋。
示例 B：高交领右衽襦袖口严密，外罩丝质领子，下着百褶裙（图3 深秋读书即此变体）。
补充纹样词：合领纹 / 缠枝莲纹 / 金莲绣鞋 / 联珠纹 / 暗八仙纹 / 缠枝牡丹纹

**男装三段式简表（对照女装，写公子/侠客/帝王直接查）**：

| 层 | 选项（由贵到朴） |
|---|---|
| 外层 | 圆领袍 / 直裰 / 襕衫 / 玄甲 / 鹤氅 |
| 中层 | 半臂 / 比甲 / 贴里 |
| 内层 | 中衣 / 交领衫 / 汗衫 |
| 腰带 | 玉带 / 革带 / 丝绦 / 布绦 |
| 足下 | 皂靴 / 云头履 / 布鞋 / 草鞋 |

速配：圆领袍+玉带+皂靴 = 王公；直裰+布绦+布鞋 = 文士；襕衫+丝绦+云头履 = 书生；玄甲+革带+战靴 = 将军；鹤氅+丝绦+布鞋 = 仙翁/隐士。

### 服装雅词库

| 维度 | 雅词 |
|---|---|
| 形制 | 襦裙 / 曲裾 / 披帛 / 大袖 / 霞帔 / 云肩 / 马面裙 / 比甲 |
| 材质 | 云锦 / 缂丝 / 绫罗 / 绢纱 / 杭绸 / 织金 / 提花 / 苏绣 |
| 颜色雅称 | 绯罗 / 绛纱 / 黛青 / 藕荷 / 月白 / 鸦青 / 竹青 / 胭脂 |
| 工艺 | 鎏金 / 螺钿 / 滚边 / 织金线 / 暗纹 / 珠缀 |
| 动态 | 衣袂翩跹 / 裙裾生风 / 步摇轻颤 / 珠翠轻晃 / 广袖翻飞 / 披帛飞舞 |

### 现代服装雅词库

| 维度 | 雅词 |
|---|---|
| 形制 | 风衣 / 针织开衫 / 缎面衬衫 / 西装剪裁 / 真丝吊带 / 慵懒套装 / 大衣 / oversize 廓形 |
| 材质 | 羊毛呢 / 真丝 / 醋酸缎面 / 羊绒 / 丹宁 / 麂皮 / 针织纹理 / 雾面皮革 |
| 颜色雅称 | 燕麦色 / 雾霾蓝 / 莫兰迪灰 / 焦糖 / 奶油白 / 石墨灰 / 橄榄绿 / 烟粉 |
| 工艺细节 | 垂坠感 / 褶皱 / 解构剪裁 / 微光面料 / 哑光 / 廓形利落 |
| 动态 | 衣摆随风 / 发丝飘动 / 衣角翻飞 / 光影在面料上流动 / 织物纹理随动作皱起 |

### 服装对照示例

**服装**

- 普通：新娘穿红色嫁衣，头上有金首饰
- 美学：新娘着绯罗嫁衣、云肩缀珠，凤冠步摇随步履轻颤，广袖拂过烛光

**现代服装**

- 普通：主角穿件毛衣，拿杯咖啡
- 美学：主角着燕麦色针织衫，柔软垂坠，指尖轻抚青瓷杯沿，蒸汽在光柱里盘旋

### 3.2.1 材质大全（服装/器物/场景通用·挑一个+质感+光效）

> 材质是「高级感」的最小单位：一句里塞一个材质 + 一个质感 + 一个光效互动，画面立刻立体。写服装用织物，写道具用金属/玉/木/瓷，写场景用建筑材质。

**织物类（写服装/披帛/幔帐）**

```
丝绸 / 锦缎 / 织锦 / 云锦 / 宋锦 / 蜀锦 / 缂丝 / 妆花缎 / 绫罗 / 绡 / 薄纱 / 绢 /
香云纱 / 苎麻 / 粗麻 / 棉布 / 缬染 / 扎染 / 蜡染 / 苏绣 / 蜀绣 / 缂金 / 织金纱
质感：垂坠如水 / 光泽流转 / 微透光 / 细褶如弦 / 磨旧起毛 / 泛温润光泽
光效：绸面波光 / 纱缘透光 / 织金线闪细芒 / 褶皱处明暗渐变
```

**金属类（写兵器/香炉/器皿/首饰）**

```
黄铜 / 青铜 / 紫铜 / 白银 / 鎏金 / 错金 / 乌银 / 玄铁 / 精钢 / 锡器 / 金箔
质感：包浆温润 / 冷冽如霜 / 氧化青绿 / 磨砂哑光 / 亮如镜面
光效：烛火映出弧形高光 / 一线寒光 / 鎏金在暗处泛幽光
```

**玉石类（写首饰/案头/把件）**

```
和田玉 / 青玉 / 白玉 / 翡翠 / 玛瑙 / 珊瑚 / 砗磲 / 琉璃 / 水晶 / 琥珀 / 蜜蜡 / 青金石
质感：温润如脂 / 冰透起荧 / 油润包浆 / 内裂如蛛丝
光效：玉中光晕流转 / 边缘透光 / 高光如点漆
```

**木竹类（写家具/门窗/乐器）**

```
紫檀 / 黄花梨 / 金丝楠 / 沉香木 / 乌木 / 鸡翅木 / 竹 / 藤 / 原木 / 老榆木
质感：牛毛纹 / 金丝闪烁 / 竹节肌理 / 使用磨痕 / 漆面开片
光效：漆面映窗影 / 木纹在光下起伏 / 竹影投墙
```

**陶瓷漆器类（写茶器/食器/陈设）**

```
青瓷 / 汝窑 / 官窑 / 哥窑 / 钧窑 / 龙泉 / 建盏 / 青花 / 白瓷 / 大漆 / 螺钿 / 描金
质感：开片细纹 / 釉面如玉 / 兔毫盏纹 / 冰裂纹 / 螺钿流光
光效：釉光温润 / 盏内曜变 / 漆面映烛 / 瓷缘一道高光
```

**建筑与场景材质（写环境）**

```
青砖 / 粉墙 / 黛瓦 / 木构 / 石阶 / 苔痕 / 竹篱 / 夯土 / 石栏 / 铜钉门 / 纸窗
质感：风化剥落 / 苔藓洇绿 / 磨得发亮 / 露水微光
光效：夕阳拉长檐影 / 纸窗透出暖光 / 砖缝里长草
```

**组合公式**：材质 + 质感 + 光效 → 香云纱垂坠如水，织金线在烛光下闪细芒，褶皱处明暗渐变。

### 3.3 道具描写

### 4.1.2 配饰道具三层结构（写人别漏层·每一层至少取 1 项）

> 道具词库虽全，但"随身配饰/手持道具/场景陈设"三层混在一个词下，写 prompt 容易漏层——写了玉簪忘玉佩，写了团扇忘香炉。三层分开取词，各进各的段落。

**A 层·随身配饰（跟人走，进「人物造型」段）**：

- 发饰：玉簪 / 步摇 / 花胜 / 金钿 / 梳篦 / 绒花
- 项耳：璎珞 / 耳坠 / 耳铛 / 项圈
- 腰佩：玉佩 / 禁步 / 香囊 / 宫绦 / 腰悬短剑
- 手足：玉镯 / 臂钏 / 指环 / 珠串

**B 层·手持道具（跟动作走，进「动作·道具·神态」段）**：

- 礼仪：大雁 / 庚帖 / 团扇 / 合卺杯 / 喜帕
- 实用：书卷 / 茶盏 / 剑 / 拂尘 / 竹篮 / 绣绷 / 算盘
- 情绪：绢帕 / 酒囊 / 念珠 / 折扇 / 灯笼

**C 层·场景陈设（跟环境走，进「场景与元素/道具细节」段）**：

- 家具：博古架 / 香案 / 屏风 / 书案 / 琴案 / 凭几
- 器物：香炉 / 灯檠 / 花插 / 铜镜 / 笔洗 / 陶罐
- 织物：纱幔 / 蒲团 / 锦垫 / 帷帐 / 帘幕

用法：每层取 1-2 项 → A 进服装/妆发段，B 进动作段，C 进场景段 → 三层各就其位，人、手、环境不打架。

### 道具描写公式

```
道具(点题) + 材质质感 + 光效互动 + 手部动作
```

### 道具雅词库

```
鎏金 / 青瓷 / 黄铜 / 竹编 / 檀木 / 绢帛 / 玉石 / 釉光 /
金线流转 / 光斑滑过 / 指尖轻抚 / 双手捧奉 / 拈起 / 执盏
```

**道具功能分类词库（7 类·超全·点题+材质+光效互动）**

> 用法：每个镜头只放 1 个点题道具；「材质质感」+「光效互动句」拼进「手中道具公式」。

| 类 | 点题道具 | 材质质感 | 光效互动句 |
|---|---|---|---|
| 礼仪礼器 | 大雁 / 庚帖 / 聘礼箱 / 合卺杯 / 红绸结 / 花轿 / 香案 / 醴酒 | 朱漆 / 鎏金 / 描金红木 / 织金红绸 | 红绸结系着雁笼，暖光里雁羽泛细碎绒光 |
| 茶事 | 粗陶壶 / 青瓷盏 / 茶则 / 茶筅 / 竹炉 / 建盏 / 盏托 | 粗陶 / 青瓷开片 / 竹编 / 紫砂 | 壶口白雾在光柱里盘旋，茶烟袅袅升入光束 |
| 书画文房 | 宣纸 / 湖笔 / 端砚 / 墨锭 / 镇纸 / 笔洗 / 卷轴 | 宣纸纤维 / 端砚石理 / 竹管狼毫 | 墨在砚中泛釉光，笔锋划过纸面留微湿反光 |
| 妆奁闺阁 | 铜镜 / 眉黛 / 花钿 / 团扇 / 香炉 / 步摇 / 绣绷 / 木梳 | 黄铜 / 螺钿 / 檀木 / 绢纱 | 铜镜边缘镀金反光，香炉青烟缭绕在光柱中 |
| 农事渔樵 | 竹篮 / 箩筐 / 镰刀 / 木犁 / 扁担 / 鱼篓 / 斗笠 / 蓑衣 / 水车 | 竹编 / 原木 / 麻绳 / 棕蓑 | 镰刃在逆光中一线银光，谷粒扬起时金色碎光 |
| 市井百工 | 灯笼 / 糖人 / 算盘 / 油纸伞 / 货担 / 铜钱 / 风车 | 竹骨纸面 / 黄铜 / 琉璃 | 灯笼暖光映在油纸伞上晕成光圈，人流剪影 |
| 兵器江湖 | 长剑 / 短刀 / 折扇 / 酒葫芦 / 缰绳 / 暗器 / 斗笠 | 冷钢 / 犀角 / 竹骨 / 皮革 | 剑出鞘一线寒光，酒葫芦在篝火边泛琥珀光 |
| 乐器 | 古琴 / 琵琶 / 箫 / 笛 / 筝 / 阮 / 笙 / 埙 / 编钟 / 鼓 / 钹 | 桐木 / 蛇皮 / 竹管 / 青铜 / 漆面 | 指尖按弦琴身微颤，笛孔在光下泛竹青温光 |
| 饮食起居 | 食盒 / 酒樽 / 觥 / 爵 / 盏托 / 凭几 / 灯檠 / 烛台 / 花插 / 香囊 | 大漆 / 青铜 / 白瓷 / 琉璃 | 烛火在灯檠上摇，酒樽沿口泛琥珀光 |
| 宗教仙侠 | 拂尘 / 如意 / 葫芦 / 八卦镜 / 符箓 / 念珠 / 金钹 / 神像 / 经卷 | 竹柄马尾 / 白玉 / 黄铜 / 绢帛 | 拂尘尾丝在光中根根分明，符箓边缘泛朱砂微光 |
| 坐骑 | 马 / 鹤 / 鹿 / 青牛 / 麒麟 / 狐 / 龟 / 驴 / 骆驼 / 龙 / 凤 | 鬃毛 / 羽翎 / 鳞甲 / 皮毛 | 马鬃被风掀起成浪，鹤羽在逆光下镀金边 |

**道具光效互动句·替换库（每道具 3 种写法·按情绪选，替换表内"光效互动句"列）**

| 道具 | 写法①（暖/温润） | 写法②（冷/清透） | 写法③（戏剧/暮夜） |
|---|---|---|---|
| 玉簪 | 烛光下泛温润脂光 | 逆光中边缘透一丝淡青 | 暮色里簪头珠花闪细芒 |
| 书卷 | 窗光斜照纸面泛暖黄 | 烛火下墨字微反光 | 页边在逆光中透薄 |
| 剑 | 出鞘一线寒光 | 剑身在月光下泛冷蓝 | 剑穗在篝火边闪金线 |
| 茶盏 | 杯口蒸汽在光柱里盘旋 | 釉面映出一小片窗影 | 盏中汤色在烛火下泛琥珀光 |
| 团扇 | 扇面绢纱透暖光，竹骨泛蜜色 | 月光透过绢纱，扇上绣纹显影 | 灯笼光晕在扇面晕成光圈 |
| 拂尘 | 尾丝在暖光中根根分明，泛温润白 | 月光下尾丝如雾，边缘镀冷银 | 烛火摇曳中尾丝投下细密影纹 |
| 玉佩 | 玉面在日光下透润，光晕柔和 | 月下玉色清冷，如凝霜 | 灯光斜照，玉佩投下一道细影 |
| 香炉 | 青烟缭绕在光柱中盘旋 | 冷光下烟色发青，袅袅如线 | 烛火映炉身，鎏金纹泛暗金光 |

用法：按画面情绪选一种替换表内"光效互动句"，其余结构不动。

**道具扩展词（往 7 类里再塞）**

```
礼仪礼器：玉璧 / 玄纁 / 俎豆 / 鼎 / 觚 / 璋 / 圭 / 节杖
茶事：执壶 / 茶碾 / 罗合 / 水方 / 涤方 / 建水 / 茶巾
书画文房：笔山 / 臂搁 / 印泥 / 钤印 / 竹简 / 缣帛 / 书匣
妆奁闺阁：菱花镜 / 胭脂盒 / 眉笔 / 花胜 / 玳瑁梳 / 金约
农事渔樵：蓑衣 / 耒耜 / 连枷 / 谷筛 / 罟网 / 鸬鹚
市井百工：幌子 / 布幌 / 糖画 / 泥人 / 风箱 / 锔瓷担
兵器江湖：朴刀 / 判官笔 / 金瓜锤 / 软鞭 / 连弩 / 镖囊
```

### 现代道具雅词库
```
磨砂玻璃 / 哑光黄铜 / 胡桃木 / 陶瓷釉面 / 拉丝不锈钢 / 帆布 / 树脂 /
蒸汽盘旋 / 光斑滑过 / 霓虹映照 / 倒影 / 高光点 /
指尖轻抚 / 转动杯沿 / 敲击 / 握持 / 翻页
```

### 道具对照示例

**道具**

- 普通：媒人捧着一对雁
- 美学：雁笼系朱红绸结，风过时绸结轻扬，雁羽在暖光中泛着细碎绒光

**现代道具**

- 普通：桌上放着一杯咖啡
- 美学：咖啡杯沿釉光微闪，蒸汽在光柱里盘旋上升，光影在杯身缓缓游移

### 3.4 服装·道具组合示范 + 心法

**古风·纳采**

> 朱漆大门泛着釉光，檐角宫灯如豆。媒人着青绿古装，广袖垂落，腰间佩玉轻晃，双手捧雁，雁笼系朱红绸结，风过时绸结轻扬，衣袂被晚风拂动，金尘周身浮动。

**现代·咖啡**

> 主角着燕麦色针织衫，指尖轻抚青瓷杯沿，杯口蒸汽在光柱里盘旋，阳光在织物纹理上缓缓游移。

**现代·霓虹夜色**

> 暮色漫过天台护栏，风拂过发梢。主角着雾霾蓝风衣，衣摆随晚风翻飞，指尖轻触屏幕，屏幕光映亮侧脸，远处霓虹在夜幕里晕开成光斑。

### 服装·道具心法

1. 服装三个词就够：**形制 + 材质 + 颜色雅称**（"绯罗云肩"＞"红色衣服"）
2. 道具三个词就够：**材质 + 光效 + 手部互动**（光效互动让死物活起来）
3. 道具必须**点题**且**参与动作**（雁笼系红绸结——不用解释，观众就懂婚嫁）

---

### 3.5 中式美学场景专章（云海 · 天宫 · 巨物 · 朝圣——高分场景的两种写法）

> 素材来源：19 张高分参考（【中式美学】第五期 MJ 参数式 13 张 + 【天宫美学】长文式 4 个案例）。
> 两套体系遵循同一套视觉逻辑：**奇观主体 + 极小人物 + 四层空间 + 冷暖对照**。

#### 3.5.1 两套写法体系（先分清你喂给谁）

| 体系 | 特点 | 适用工具 | 结构 |
|---|---|---|---|
| MJ 参数式 | 一段描述 + --ar / --s / --c / --no / --v 参数 | Midjourney v8.2 | 主体+材质+人物+构图+光影+色盘+情绪+电影级后缀 |
| 天宫美学长文式 | 分段长文本，逐段约束占比与避坑 | 可灵/即梦/豆包/海螺等中文工具 | 镜头焦段+构图+占比约束+四层空间+人物尺度+光影+色盘+避坑清单 |

#### 3.5.2 场景架构公式（两式通用内核）

```
[主体奇观] + [材质细节] + [极小人物做尺度锚点] + [构图语言] + [四层空间] + [冷暖光影对照] + [色盘] + [情绪词] + [电影级后缀]
```

#### 3.5.3 奇观主体词库（挑一个当"主角"）

| 奇观主体 | 写法示例（可直接替换进 prompt） |
|---|---|
| 天门/天关 | 四根雕刻升龙的朱红巨柱从翻涌白云中拔地而起，深色木构飞檐形成高耸建筑框景 |
| 天宫 | 深色雕花飞檐与高耸朱红柱形成山岳般的全景窗口 |
| 云海 | 无尽云海，近层薄雾 + 中层体积云 + 远层淡雾，四层纵深 |
| 古松 | 山岳般巨大的古老树干穿过层层雾气拔地而起，垂藤如天然拱顶框景 |
| 神山 | 巨大的朱红圣石山拔地而起，表面带流动雕刻纹路与微弱金色铭文 |
| 瀑布 | 三道巨型垂直瀑布从不可见的天上结构坠入远方云海峰林 |
| 巨月 | 异常巨大的冷白色月球悬于宫阙后方，月面纹理清晰但不过度锐利 |
| 雪原 | 广阔雪原，钴蓝天空，硬朗高空日光，清晰长阴影，深远大气透视 |
| 垂藤神树 | 伞形树冠横跨整个画面上部，数千条细长垂藤如半透明雨帘坠下 |
| 白玉天墙 | 巨大白玉天墙如冻结巨浪般向上弯曲，墙基装饰铜金莲花与守护瑞兽 |
| 树洞框景 | 古松根系与树干交织成巨大天然拱门，形成圆形画中画构图 |
| 镜面水台 | 黑色镜面般的水台，精确倒影，人物立于水面 |

#### 3.5.4 尺度锚点（人物怎么"小"）

- 人物占画面高度 **0.4% ~ 3%**，只作为尺度与叙事锚点，**不出现面部特写**
- 写法关键词：极小的 / 渺小 / 孤独 / 站在中轴线上 / 走过左下方广场 / 背对镜头远望
- 例 1：一位极小的原创白衣女子居中站在抛光深色木地板上，并留下清晰倒影
- 例 2：两名背对镜头的古代人物，仅占画面高度约 0.4%，正常尺寸栏杆与灯柱作尺度参照

#### 3.5.5 四层空间（纵深怎么分层）

```
近层薄雾 / 露台 → 中层体积云（洁白亮顶 + 灰蓝暗谷）→ 远层淡雾 / 云海 → 淡青天际
```

#### 3.5.6 色盘词库（克制配色）

| 色盘 | 用途 |
|---|---|
| 云白 + 淡青蓝 + 松绿 | 明亮疏朗（云宫露台/巨木云谷） |
| 苍玉 + 象牙白 + 炭灰 + 古金 | 庄严敬畏（盘龙巨柱/白玉天墙） |
| 朱红 + 暖木 + 云白 | 皇家仙宫（蟠桃天苑） |
| 雪白 + 炭黑岩石 + 钴蓝 | 雪原朝圣（雪谷云瀑） |
| 冷蓝 + 局部暖琥珀 | 冷暖对照经典（悬空神殿/燃烧云穹） |

#### 3.5.7 光影冷暖对照词库

| 对照方式 | 写法 |
|---|---|
| 暖侧光 vs 冷云影 | 暖色侧光擦过朱漆，与冷色云影形成对比 |
| 琥珀云火 vs 钴蓝天空 | 明亮琥珀色云火与金色蒸汽从中央穹顶倾泻，橙色辉光对照钴蓝天空和白雪 |
| 暖高光 vs 冷阴影 | 白昼阳光形成自然淡金高光，阴影通透偏冷 |
| 冷蓝雾 vs 局部暖色 | 冷蓝大气雾气中只让树皮和灯光出现少量暖色高光 |
| 晨光暖 vs 远山冷蓝 | 暖色黎明光触碰中央水帘，远方覆盖冷蓝薄雾 |

#### 3.5.8 情绪词库

神圣静谧 / 庄严压迫 / 敬畏孤立 / 静默启示 / 神圣升腾 / 虔诚朝圣 / 空灵疏朗 / 时间凝滞 / 宏大孤独 / 神秘期待 / 神性威严

#### 3.5.9 负面词模板（两式）

- MJ 式：`文字 标志 水印 字幕 界面 现代建筑 霓虹 人群 重复人物 扭曲xx 畸形xx xx断裂 xx融化 xx糊化`
- 天宫式：`避免：人物特写/大人物/建筑填满画面/欧式宫殿/希腊罗马柱/现代建筑/建筑融化/飞檐断裂/棉花云/浓雾遮挡/全局橙色滤镜/夜晚星空/文字水印logo`

#### 3.5.10 案例归档（71 条·按类型分四库·已加【类型】标签快速检索）

> 分类：巨物/天宫/奇观 26 条 · 国风/美人/写真 5 条 · 宋式/生活/田园 34 条 · 庭院/宫廷/文事 6 条。编号全库连续，可追溯原顺序。

#### 3.5.10a 案例归档·巨物/天宫/奇观（26 条）

| # | 案例 | 核心场景句（直接替换进 prompt 的「场景」段） |
|---|---|---|
| 01 |【巨物·天宫·奇观】云门赤柱镜面水台 | 四根雕刻升龙的朱红巨柱从翻涌白云中拔地而起，白衣女子站在黑色镜面水台上，暖色侧光擦过朱漆与冷色云影对比 |
| 02 |【巨物·天宫·奇观】峡谷古松巨型天门 | 狭窄天然石桥横跨森林峡谷，白衣女子立于桥中央，长白飘带从古松垂落，远处迷雾中巨型白色天门矗立 |
| 03 |【巨物·天宫·奇观】巨木云谷远方灯塔 | 山岳般巨大的古老树干穿过层层雾气，白色云河在巨树间流动，远方植被间点亮细小温暖灯塔 |
| 04 |【巨物·天宫·奇观】云海古松观景者 | 巨大黄山松生长在无尽云海之上的高崖，垂藤形成天然拱顶框景，清澈晨光穿过松针 |
| 05 |【巨物·天宫·奇观】白玉天墙升天长阶 | 巨大白玉天墙如冻结巨浪向上弯曲，严格居中的白色登天长阶直达金色云纹浮雕宫殿 |
| 06 |【巨物·天宫·奇观】悬空神殿雪原 | 巨大悬空天界宫殿底部横跨画面上半部，山岳般巨柱垂入云海，雪覆礼仪广场，低机位制造顶部压迫 |
| 07 |【巨物·天宫·奇观】盘龙巨柱天宫 | 巨大青玉天柱被白石盘龙与云浪包裹，支撑延伸至地平线的帝宫阴影，斜向超宽构图制造动势 |
| 08 |【巨物·天宫·奇观】宫殿窗口三道天瀑 | 深色雕花飞檐与朱红柱形成山岳般全景窗口，三道巨型天瀑坠入云海峰林，人物居中留清晰倒影 |
| 09 |【巨物·天宫·奇观】赤色神山双人水镜 | 巨大朱红圣石山带流动雕刻纹与金色铭文，两位白衣朝圣者立于暗红镜水旁，午后侧光暖砂岩对照冷蓝天空 |
| 10 |【巨物·天宫·奇观】树洞框景云海神山 | 古松根系与树干交织成巨大天然拱门，圆形画中画构图，白衣女子站在云海岩石平台，极小人物位于下三分之一中央 |
| 11 |【巨物·天宫·奇观】雪谷云瀑天柱 | 垂直云河从高空坠落如巨型天界瀑布，白衣朝圣者穿过两面陡峭黑色山崖间的广阔雪原 |
| 12 |【巨物·天宫·奇观】垂藤神树云上栈桥 | 古老榕松混生神树从天界悬崖生长，数千条垂藤如半透明雨帘，红木桥通向树干下方 |
| 13 |【巨物·天宫·奇观】燃烧云穹雪地朝圣 | 四根山岳般暗色石柱撑起悬空神殿，琥珀色云火与金色蒸汽从中央穹顶倾泻，衣袍鼓动占前景 |
| 14 |【巨物·天宫·奇观】巨月临阙晴昼 | 晴朗白昼天空悬异常巨大冷白月球，月面纹理清晰不过度锐利，边缘被高空气流与薄云柔化 |
| 15 |【巨物·天宫·奇观】蟠桃天苑 | 万年蟠桃古树树干苍老扭曲，枝头疏密有致淡粉桃花，朱红长廊占画面不超过 20%，粉色仅作局部点缀 |
| 16 |【巨物·天宫·奇观】天河飞瀑 | 巨型天宫从云层升起占画面高度 55% 以上并越出顶部，天河从白玉水台奔流而下贯穿云海 |
| 17 |【巨物·天宫·奇观】云宫露台 | 28-35mm 受控广角平视，建筑只占画面边缘不超过 20%，千年古松从右侧云崖伸出，三道背身人物远望云海 |
| 18 |【巨物·天宫·奇观】玄渊黑龙 | 东方远古黑龙体型遮天蔽日，巨大龙首逼近镜头，鳞片粗糙厚重，云雾翻涌飞鸟四散，渺小黑衣剑客与巨龙强烈大小对比，阴郁天光穿透云层丁达尔光束，史诗压迫感，暗调灰度 |
| 19 |【巨物·天宫·奇观】腐狱巨蛛 | 上古巨型暗黑魔蛛布满荆棘骨刺，粗壮多节蛛腿撑开，粘稠蛛丝飘荡，破败古风废墟楼阁，乌云密布碎石飘散，浅滩积水倒映，渺小黑衣剑客站岩石滩，压抑肃杀，冷灰暗色调 |
| 20 |【巨物·天宫·奇观】云门法阵（画面反推·非原 prompt） | 龙纹大理石立柱与鎏金装饰殿宇门廊，光洁大理石地面铺金色纹样圆形法阵，白衣人物独立法阵中央望向殿外；殿外云海翻涌，中式亭台楼阁林立，长阶通向云端仙门，仙门透光，白色水瀑沿阶倾泻。对称构图，恢弘空灵。英文版：Marble colonnade with carved dragons and gilded ornaments, polished marble floor bearing a circular golden ritual array, one white-robed figure at the array center gazing outward; surging clouds beyond, classical pavilions, a long stairway rising to a luminous celestial gate, white water cascading like cloud waterfalls. Symmetrical composition, majestic ethereal, cinematic oriental mythology |
| 21 |【巨物·天宫·奇观】崖台浮岛（画面反推·非原 prompt） | 苍劲古松斜伸前景，圆形石质观景台上两位白衣人物背身眺望；中景云雾悬崖错落中式楼阁宫殿，浮空岛悬于半空，飞瀑沿崖倾泻，石桥连接崖台；背景霞光漫布。前景框景+层层纵深，缥缈仙气。英文版：Ancient pine leaning across the foreground, two white-robed figures back-to-camera on a circular stone terrace; mist-wrapped cliffs dotted with Chinese pavilions, floating islands suspended mid-air, waterfalls cascading down cliffs, stone bridges linking ledges; rosy glow spreading across the sky. Foreground framing with layered depth, ethereal atmosphere, cinematic Chinese fantasy |
| 22 |【巨物·天宫·奇观】红廊白纱（画面反推·非原 prompt） | 云端中式古典长廊，红漆立柱配鎏金雕花基座，雕梁画栋，红绸与白纱随风飘拂；长廊向远方延伸，木地板光影交错；外侧云海翻涌，中式宫殿白墙金饰红柱飞檐隐于云间，远处高耸塔楼；红白古风女子沿廊向深处走，远景模糊人影。一点透视纵深，仙气缥缈。英文版：Classical Chinese covered corridor above the clouds, vermilion pillars with gilded carved bases, carved timber beams, red silk and white gauze fluttering; corridor receding into distance with dappled light on wooden floor; palaces with white walls, gold trims and vermilion flying eaves half-hidden in mist, a tall pagoda afar; a woman in red-and-white hanfu walking deeper along the corridor, a blurred figure far ahead. One-point perspective, ethereal celestial atmosphere |
| 23 |【巨物·天宫·奇观】雪阶天宫（视频反推·非原 prompt） | 残雪覆盖的石阶向远处宏伟古建筑群延伸，两侧雕饰繁复的高大中式楼阁，云雾缭绕其间，远处矗立高耸层叠塔楼；红粉渐变古装长裙女子背身立于石阶，衣袂随风微动，雪景与暖色衣裙冷暖对照，肃穆空灵。英文版：Snow-dusted stone steps extending toward a majestic ancient palace complex, ornate tall Chinese pavilions flanking both sides wrapped in drifting mist, a towering pagoda rising afar; a woman in a red-to-pink gradient hanfu gown standing back-to-camera on the steps, sleeves stirring in the breeze, cold snow contrasting with the warm dress, solemn and ethereal |
| 24 |【巨物·天宫·奇观】云海门阙（视频反推·非原 prompt） | 云海之上矗立巨型门阙式建筑，雕饰精美隐于云层，后方层叠中式古典楼阁飞檐翘角，白衣人物背身伫立云海之上，恢弘缥缈。英文版：A colossal gate-tower rising above the sea of clouds, intricate carvings half-hidden in mist, layered classical Chinese pavilions with flying eaves behind, a white-robed figure standing back-to-camera on the clouds, grand and ethereal |
| 25 |【巨物·天宫·奇观】天光垂落（视频反推·非原 prompt） | 云海翻涌，雕梁画栋楼阁左右夹峙，中部殿宇坐落，云层缝隙透出光束斜洒，一道垂直光柱自天际垂落，古装人物背身立于云海仰望，空灵神圣。英文版：Rolling sea of clouds flanked by ornate carved pavilions with a central palace, light beams slanting through cloud gaps, a single vertical pillar of light descending from the sky, a figure in ancient robes standing back-to-camera gazing upward, ethereal and sacred |
| 26 |【巨物·天宫·奇观】东方神龙盘踞（视频反推·非原 prompt） | 巨大的东方神龙盘踞在云雾缭绕的天地间，龙首纹理粗糙、眼神威严，龙须飘逸，身躯庞大占据画面主要空间；下方岩石山丘上站立一个渺小人影，人与巨龙形成强烈体型反差；背景云海、山峦与透出的天光，雄浑压迫。英文版：A colossal eastern dragon coiling across mist-wreathed heavens, rough-scaled majestic head with flowing whiskers, vast body dominating the frame; a tiny human figure standing on a rocky hill below, extreme scale contrast; sea of clouds, mountain ridges and light breaking through, grand and oppressive |

#### 3.5.10b 案例归档·国风/美人/写真（5 条）

| # | 案例 | 核心场景句（直接替换进 prompt 的「场景」段） |
|---|---|---|
| 27 |【国风·美人·写真】唐襦国风美人（原 prompt·中英） | 冷白正面主光无阴影，唐代齐胸襦裙四件套（象牙白缎裙+灰蓝纱衣绣金线牡丹+珊瑚橘织锦腰带+杏色披帛），香槟粉绢花珍珠发簪，油画风收尾三词。英文原版：Professionally retouched, vertical, waist up, 85mm lens, shallow depth of field, powerful cool white front key light floods the figure evenly, skin reads snow white and translucent almost shadowless, young East Asian girl 18-19, three quarter angle, calm tender gaze at lens, coral orange lips slightly parted, perfect oval face, golden ratio proportions, large almond eyes with double eyelids, star catchlights, soft aegyo sal, long arched brows, small nose, porcelain cool white flawless skin, black hair in loose high updo, wispy see-through bangs, champagne pink silk peony, gold filigree blossoms, pearl tassel hairpins, long pearl drop earrings, Tang dynasty high waisted ruqun, ivory satin underskirt, sheer grey blue organza robe with coral red cream and indigo peonies outlined in gold thread, coral orange brocade sash, peach apricot sheer pibo shawl drifting in breeze, warm grey taupe studio backdrop, silver white rim light, soft film grading, peach pink grey blue cream antique gold palette, opulent airy serene |
| 28 |【国风·美人·写真】花钿金冠国风美人（原 prompt·中英） | 朱红花钿+星芒金额饰，奶油腮红牡丹珍珠华冠，钢蓝大袖3D牡丹刺绣，暖灰褐影棚。英文原版：Photorealistic Chinese style beauty editorial portrait, vertical chest up, 85mm f/1.4, shallow depth of field, young East Asian woman 18-19, body slightly turned, three quarter face left, serene wistful gaze, coral red lips, petite face, golden ratio proportions, large almond eyes, parallel double eyelids, pale peach eyeshadow, star catchlights, aegyo sal, long arched brows, small nose, vermillion huadian, starburst gold forehead pendant, porcelain cool white flawless skin, near shadowless, soft front left key light, black hair in high updo, wispy temples, airy fringe, enormous crown of cream and blush peonies, roses, silver crystal foliage, iridescent gems, pearl halo arch, crystal earrings, ivory gauze veil wings, steel blue satin wide sleeved robe, 3D peony embroidery, gold thread, coral red bustband, ivory gauze shawl, gold jewel ring, warm grey taupe backdrop |
| 29 |【国风·美人·写真】仙裙油画国风美人（原 prompt·中英） | 奶白前键光无正面阴影，露肩金织仙裙+金珍珠皇冠，回眸一瞥，古典油画云海+湿壁画笔触背景，低反差胶片调色，华贵空灵冷感。英文原版：High end photorealistic Chinese beauty editorial portrait, vertical knee up shot, 85mm f/1.4, shallow depth of field, soft airy bloom highlights, milky neutral front key light floods face and shoulders evenly, porcelain cool white flawless translucent skin, no frontal shadows, young East Asian woman 18-19, over the shoulder glance, torso three quarters away, face fully toward lens, calm watery gaze, coral red lips slightly parted, delicate golden ratio face, large almond eyes with double eyelids, star catchlights, aegyo sal, slender arched brows, small nose, black hair in voluminous high updo, airy fringe, loose tendrils, gold pearl crown, crystal drop earrings, off shoulder gold brocade fairy gown, ivory silk bandeau bodice, sheer organza robe, billowing embroidered sleeves, pastel florals, pink inner hem, one hand lifts a drifting silk ribbon, background classical oil painting cloud sea, slate blue sky, Renaissance fresco brushwork, low contrast film grading, ivory champagne gold cloud blue pale pink, opulent ethereal cool |
| 30 |【国风·美人·写真】山间松林·白纱结印（画面反推·非原 prompt） | 山间松林，苍劲古松与朦胧山峦为景，白纱长袍女子半束长发随风扬起，双手在身前结印，衣袂翻飞，暖调逆光勾勒轮廓，仙逸空灵。英文版：Amid mountain pines, gnarled pines and hazy ridges as the backdrop, a woman in a white gauze robe, hair half-tied streaming in the wind, hands forming a mystic seal before her, robes fluttering, warm backlight outlining her silhouette, ethereal and transcendent |
| 31 |【国风·美人·写真】镜花水月·暗调梦境（原 prompt·中英） | 竖构图梦幻写实，动感斜角构图，女子神圣忧郁带微妙失衡感，华美中式室内环绕白花，青/红/暗红/黑色调，昏暗室内对明亮窗光，强烈明暗对照，剪影半透明层次层叠阴影，轻微动态残影，雾感低饱和，景物流动溶解，梦境核超现实，玻璃质感高光，极端明暗对比，蓝紫混合色调，中画幅胶片。英文原版：Vertical dreamy realistic photograph, dynamic angled composition, young East Asian woman with divine hauntingly beautiful melancholic subtly unhinged presence in an ornate ancient Chinese interior surrounded by delicate white flowers, color palette cyan red dark red black with refined classical Chinese details, dim interior contrasts bright window light, strong chiaroscuro, silhouettes, translucent layers, layered shadows, faint motion ghosting, hazy low saturation ethereal atmosphere with flowing dissolving surroundings, ripples, illegible blurred handwritten text, dreamcore surreal mood, film grain, realistic skin and fabric texture, glassy translucent highlights, extreme shadow to light contrast, blue purple fused tones, shallow depth of field, bold unsettling atmosphere, medium format film, photorealistic, masterpiece |

#### 3.5.10c 案例归档·宋式/生活/田园（34 条）

| # | 案例 | 核心场景句（直接替换进 prompt 的「场景」段） |
|---|---|---|
| 32 |【宋式·生活·田园】木窗翻书品茶（原 prompt·中英） | 夏日午后，素白翡翠绿宋制汉服女子坐木窗旁，一手翻古籍一手持热茶杯贴唇边，白色蒸汽映照暖光，斑驳树影落木桌，窗外宋代田园远景，前景模糊绿植，背景白墙虚化，半卷黑发，低角度电影构图，明亮透明低对比低饱和，胶片颗粒，治愈空灵。英文原版：Summer afternoon, a young woman in plain white and emerald green Song dynasty Hanfu sits intently by a wooden window, one hand flipping through an ancient book while the other gently holds a steaming teacup near her lips, wispy white steam rising from the cup catching the warm diffused window light that scatters dappled foliage shadows across the wooden tabletop, outside the window serene Song-era pastoral fields stretch into the distance with blurred green plants in the foreground and a soft bokeh of whitewashed walls behind her, her half-up black hair shifts gently in the breeze, bright translucent low contrast low saturation palette, film grain, ethereal healing atmosphere, slightly low angle cinematic composition, Canon EOS R5, RF 85mm f/1.4, shallow depth of field, creamy bokeh, Chinese classical costume cinematic aesthetic |
| 33 |【宋式·生活·田园】河畔洗衣·水珠飞溅（原 prompt·中英） | 素白翡翠绿宋式汉服女子跪河畔洗衣，嬉戏水珠飞溅空中折射光芒，清澈涟漪流动水面，前景平滑河石翠绿河草模糊，背景柔和晕染水面与远处阳光树叶，午后阳光水面反射光点照亮剪影，勾勒棉麻衣轮廓，冷蓝绿水色对比低饱和服色，纯净清新动感。英文原版：A young woman in simple white and emerald Song-style Hanfu kneels by a gentle riverside, washing clothes with her hands while playful drops of water arc into the air as she splashes and plays, the composition focuses on her lively movements, the joyful expression on her face, and droplets catching the light in midair, with crystal-clear ripples and flowing water accentuating the scene around her, the surroundings include smooth river stones and vibrant green riverbank grass in the softly blurred foreground, while the water's surface and distant sunlit foliage form a bright and dreamy background, warm afternoon sunlight reflects off the water creating sparkling highlights that illuminate her silhouette, gently outlining her natural cotton and linen clothing, soft natural colors, the cool blue and green of the river contrasting with the low saturation of her garments, pure fresh and dynamic |
| 34 |【宋式·生活·田园】木窗粗陶壶倒茶（原 prompt·中英） | 夏日午后素白宽松宋式汉服女子坐木窗旁倒茶，粗陶茶壶蒸汽袅袅，温暖窗光木桌斑驳树影，几缕发丝随风，前景模糊窗棂绿植，背景白墙柔和虚化，宋式夏装叠穿：纯白翡翠绿交叉领内搭宽松外袍长裙垂落棉麻自然垂褶，温柔微笑半扎黑发，瓷白肌肤，轻微俯角电影构图，纪实摄影。英文原版：Summer afternoon, young woman in plain white loose Song style Hanfu sits by a wooden window pouring tea, wispy white steam rising from a rough ceramic teapot, bright translucent low contrast low saturation palette, ethereal healing atmosphere, warm window light casts dappled tree shadows on wooden tabletop, a few hair strands drift in a gentle cross breeze, blurred window lattice and green plants in foreground, soft bokeh whitewashed wall background, elegantly layered Song style summer garments: plain white and emerald green, cross collar inner robe, loose outer robe, long skirt falling naturally, cotton and linen fabric with natural folds, gentle smile, half-tied black hair, relaxed posture, porcelain skin, sharp clear face, slightly high angle cinematic composition, Canon EOS R5, RF 85mm f/1.4, shallow depth of field, creamy bokeh, realistic texture, subtle film grain, clear high-quality Chinese classical costume documentary photography |
| 35 |【宋式·生活·田园】树下弹古筝（原 prompt·中英） | 温柔夏日午后，素白宽松宋式汉服女子坐茂密树下弹古筝，略低角度，舒展体态柔和宁静微笑，阳光滤过密叶在裙摆与乐器表面交织斑驳光纹，缕缕黑发随夏风飘动，棉麻衣白绿相间自然垂落褶皱精致，前景翠绿草地模糊树干，树冠虚化光晕，面色如瓷轮廓清晰，宁静诗意田园治愈。英文原版：On a gentle summer afternoon, a young woman in plain white loose Song-style Hanfu sits gracefully under a lush tree, focused on playing the guzheng, the scene is captured from a slightly low angle highlighting her relaxed posture and soft serene smile as sunlight filters through the dense leaves casting intricate dappled shadows across her flowing skirt and the surface of the instrument, wisps of black hair drift gently in the summer breeze, and her elegant white and emerald green layers of cotton and linen garments fall naturally with delicate folds and authentic texture, foreground lush green grass and blurred tree trunks, soft bokeh of the crown and distant sunlit park, bright dreamy background, natural warm light, low contrast, soft diffusion, porcelain-clear complexion, sharp facial contours, serene poetic romantic healing pastoral atmosphere, refined real texture and harmonious light photography style |
| 36 |【宋式·生活·田园】果园摘红苹果（原 prompt·中英） | 宽松白色宋式汉服女子站果园中轻盈伸手摘熟透红苹果，睁大眼凝视头顶鲜红果实，神情明亮动人，略低角度，茂密绿叶与阳光红苹果填满树冠，视线引向优美动作与渴望眼神，温暖午后阳光透过枝叶在层叠棉麻衣上形成斑驳光影交织，鲜艳红苹果浓密绿叶树枝草丛自然肌理，背景柔和焦距，空间层次感，宁静祥和温柔惊叹，明亮治愈诗意。英文原版：A young woman in loose white Song-style Hanfu stands delicately in an orchard, gently reaching up to pick a ripe red apple, her eyes wide and sparkling as she gazes at the vivid fruit above her, the composition uses a slightly low angle with lush green leaves and sunlit red apples filling the canopy, drawing attention to her graceful gesture and expressive longing gaze, warm afternoon sunlight streams through the leafy branches creating a harmonious interplay of dappled light and shadow across her elegant layers of cotton and linen, the scene features vibrant red apples, dense green leaves, and natural textures of branches and grass softly focused in the background, highlighting the spatial layering, serene and peaceful, filled with gentle wonder, bright healing and poetic photography style |
| 37 |【宋式·生活·田园】桃林双姝·雨后春日（原 prompt·中英） | 雨后春日，两位年轻的中国少女漫步于盛开的桃树下，粉色花朵与飘落的花瓣交织。中等构图，两人面部轮廓清晰优雅。年轻女子身着优雅的宋制汉服，配色为白色与青碧，穿着精致的刺绣鞋袜，系着绣花腰带，发髻包裹并插木簪；她正温柔地将一枝带雨的桃花轻别在发间，面带恬淡笑意。另一女子身着同色系改良汉服，高底绣花布鞋，面容娇俏，垂眸看着身旁桃树，仰头注视着我，笑弯了弯弯的月牙眼，洋溢烂漫青春。清晨的光透过粉色花瓣，在两人脸上投上柔和的光影和斑驳树影，背景是初绽桃花晕染的江南庭院，空灵诗意，胶片质感。佳能RF 50mm f/2.8镜头。英文原版：Spring afternoon, two young Chinese girls on a garden path under blooming peach trees, pink blossoms and drifting petals. Medium close-up, both faces sharply feature in focus. A young woman in elegant hanfu with white and cyan Song dynasty hanfu, fine embroidered shoes and socks, tied with embroidered belt, hair bun wrapped and inserted with wooden hairpin; she gently tucks a peach blossom branch with rain drops into her hair, wearing a tender smile. A young woman in matching modified hanfu, high-soled embroidered shoes, upturned shoe top singly closed at the neckline, smiles over a plait bedecked hairpin, no exposed chest, hair cascades down like black silk; she turns her head to look at the peach blossom trees around her, radiant youthful smile. Warm sunlight filters through pink blossoms, casting soft dappled light and bright patterns across their faces. Blurred blossom branches in creamy pink. Dreamy translucent low saturation palette, ethereal poetic atmosphere, grainy film. Canon RF 50mm f/2.8, both in focal plane, Chinese period film aesthetic. |
| 38 |【宋式·生活·田园】桃下插花·男女对望（原 prompt·中英） | 春日午后，两位年轻的中国男女漫步于盛开的桃花树下，粉色花朵与飘落的繁花交织。年轻男子身着素雅宋制汉服，内搭白色素衣，外穿精刺绣长衫，系丝带腰带，背包并用木簪束发；他正温柔地将一枝盛开的桃花插入女子发髻，花瓣带风微动。年轻女子身着同款宋制汉服，高领右衽交领袄裙，外罩纱质披风，下着百褶裙，妆容淡雅，饰有发簪，正仰头注视着他，眉眼间带着浅笑，洋溢灿烂笑容。温暖的阳光透过粉色花簇，在两人脸上投射出斑驳的光影与光晕，背景是静谧雅致的桃花谷和溪流，画面色调明亮通透，空灵诗意，古典唯美质感。佳能 RF 50mm f/2.8 镜头，两人均处于画面平面内，景深较浅。英文原版：Spring afternoon, two young Chinese girls in a garden under blooming peach trees, pink blossoms and drifting petals. Medium close-up, both faces happily smiling. A man in fine linen, embroidered shirt and belt, a Song dynasty hanfu, long robe with wooden hairpin, gently tucking a peach blossom branch into a girl's hair. A young woman matching elegant hanfu, high cross-collar right-lapel robe topped suddenly at the neck in a delicate silk sheer shawl, no exposed chest, hair ornaments, silver hairpin with silver beads bouncing up at him, curved like crescent moon, radiant joyful smile. Warm sunlight filters through pink blossoms, casting soft shadow and diffused petals floating like clouds. Blurred blossom branches in bright daylight, bright translucent low-saturation palette, ethereal dreamy film, grain. Canon RF 50mm f/2.8, both in focal plane, Chinese period film aesthetic. |
| 39 |【宋式·生活·田园】春日草地·纸燕风筝（原 prompt·中英） | 春日，两位年轻的中国人在绿意盎然、点缀着红黄野花的草地上，蓝天中飘着一只纸糊的燕子风筝。中景两人，面部清晰。年轻女子身着优雅的宋制汉服，配色白色与青绿；高领右衽领口，外罩纱质褙子，下穿百褶裙，衣身有暗纹；发髻梳成双环髻，插着银簪；她正从木制绣线上放飞风筝，笑靥盈盈，双眸弯如新月，发梢轻扬。年轻男子身着同色系优雅汉服，褶裥长褂，系绣花布腰带，布包发髻插木簪；紧随其后，伸手指向风筝，笑容明媚，两人目光交汇。温暖的阳光透过嫩绿树叶，在他们脸上洒上柔和光斑。背景野花呈奶油般柔和质感（焦外成像）。画面明亮通透，低饱和暖调，空灵治愈，胶片质感。佳能RF 50mm f/2.8镜头，两人均在焦平面，中国古装电影美学。英文原版：Spring day, two young Chinese on a lush green meadow dotted with red and yellow wildflowers, a paper swallow kite floats in the sky. Medium close-up, both faces sharply in focus. A young woman in elegant white and moss-green Song dynasty Hanfu, high-cross collar right-lapel top smocked slightly at the neckline, silk beizi over a pleated skirt, no exposed chest hair, hair in a double-loop bun with silver pins; her radiant laugh, crescent-shaped eyes, hair tips curve like crescent moons, radiant joyful laughter. A young man in matching elegant Hanfu, fine ramee changshan, embroidered cloth sash, hair in a cloth-wrapped topknot with a wooden pin. He stands close behind pointing at the kite, warm bright smile, their gazes meet. Warm sunlight through tender new leaves, leaving glowing on their faces. Blurred wildflowers in cream, grainy film. Bright transparent, low-saturation pastel, ethereal healing aesthetic. Canon RF 50mm f/2.8, both in focal plane, Chinese period film aesthetic. |
| 40 |【宋式·生活·田园】秋千纸鸢·现代改良（原 prompt·中英） | 春日，两位年轻的中国人在点缀红黄野花的绿色草地上，蓝天飘着纸燕风筝。年轻女子着白色与浅卡其色束腰长裙，上摆短款，袖口开衩，外搭薄款开衫，下搭百褶裙，卷发披肩，发尾微卷，独自在木制秋千上轻轻摇晃，双腿如钟摆，发出阵阵声响。年轻男子着休闲棉麻短袖，阔腿亚麻长裤，条纹帆布腰带，发梢用布包裹半马尾；紧随其后，伸手指向风筝，笑意明媚，两人目光交汇。温暖阳光透过树叶缝隙，在他们脸上泛起柔和光影，背景草坪明亮饱和温化效果，明亮通透，饱和度适中，青春活泼，胶片质感。Canon RF 50mm f/2.8镜头，两人均在焦平面，中国古典美学电影风格。英文原版：Spring day, two young Chinese on a lush green meadow dotted with red and yellow wildflowers, a paper swallow kite floats in the blue sky. Medium close-up, both in sharp focus. A young woman in elegant white and khaki green waist-cinched dress, short sleeves with slits, outer thin cardigan, pleated skirt, curly hair on shoulders; her ends slightly curled, leaning alone on a wooden swing, dangling gently like a pendulum, radiant joyful laughter. A young man in matching cotton-linen short sleeves, wide-leg linen trousers, striped canvas belt, half-tied hair with cloth wrapped at the end; he stands close behind, pointing at the kite, warm bright smile, their gazes meet. Warm sunlight filters through tree leaves, glowing softly on their faces. Blurred willows in foreground, bright green translucent low-saturation pasture, ethereal spring atmosphere, film grain. Canon RF 50mm f/2.8, both in focal plane, Chinese period film aesthetic. |
| 41 |【宋式·生活·田园】金色谷场·挑担双扇（秋·原 prompt·中英） | 秋日的午后，两位年轻的中国人在金色的谷场上。中景特写，两人面部焦点清晰。年轻男子着白裤搭配灰白相间宽松长袖衬衫，领口系麻布领带，外套米色短款风衣，肩搭竹扁担，两端挑着鼓鼓的布包，面带温暖笑意。年轻女子穿白色内搭短衣，高叉交领斜襟，侧开衩，外搭格子，下着百褶裙，衣裾被风吹起，发梢与衣摆飘起；她双手撑开一把折扇，双眼笑成弯弯月牙，脸颊泛起红晕，两人目光交汇。温暖午后阳光洒在起伏的金色麦田，光束落于脸庞和发丝，油画般的质感和电影般的色彩过渡，色调明亮温暖，治愈氛围，胶片颗粒感。佳能RF 50mm f/2.8镜头拍摄，构图人物平均分布，中国古典电影视觉美学。英文原版：Autumn afternoon, two young Chinese on a golden threshing ground. Medium close-up, both faces sharply in focus. A young man in plain white pants and loose grey-white linen shirt, cross-collar closed shirt with a cloth sash, a bamboo shoulder-pole topknot with two full burlap sacks, stands upright smiling warmly. A young woman in matching white and moss-green Hanfu, high cross-collar short-rigged top, skirt tightly closed at the neck, belt over a pleated skirt, hair exposed, no cap, hair in a double-bun chin-up style; she holds open a silk fan, eyes curved like crescent moons, radiant jubilant smile, their gazes meet. Sunlight blazed raised golden dust, glows dancing on their faces and backs. Burned rice straw rustic details and distant scenery in bright, bokeh. Canon RF 50mm f/2.8 lens, focal plane, Chinese period costume aesthetic, cinematic film grain. |
| 42 |【宋式·生活·田园】打谷场上·月牙双扇（秋·原 prompt·中英） | 秋日的午后，两位年轻的中国人在金色的打谷场上。中景特写，面部焦点清晰锐利。年轻男子穿白色束身深棕色上衣搭配深棕色长裤，宽幅麻布背包带斜挎左肩，米色束腰，肩扛细竹扁担，两端系着长长的麻布绳，面带温暖笑容。年轻女子穿同色系汉服襦裙，宽衣交领右衽，领口镶白边，外搭薄帔，下着襦裙，梳双环发髻，发间插银饰，双手撑开一柄双扇，扇面成弯月形，笑容灿烂如暖阳。秋日温暖午后阳光洒在金色稻场，光束映照脸庞和发丝，背景是收割后的稻垛和远处起伏的金色丘陵，色调温暖通透且饱和度低，空灵苍茫诗意，胶片质感。佳能 RF 50mm f/2.8 镜头通透拍摄，两人均处于画面中，中国古风视觉美学。英文原版：Autumn afternoon, two young Chinese on a golden threshing ground. Medium close-up, both faces sharply in focus. A young man in plain white and moss-green Song dynasty hanfu, cross-collared changshan robe with a cloth sash, a cloth-wrapped backpack slung over his shoulder; he stands upright lifting a wooden shoulder pole with two grain baskets, warm smile. A young woman in matching white and moss-green hanfu, high cross-collared right-lapel ru top snugly closed at the neckline, blue pleated hairpin bun, no exposed chest, her hair tied into double-ring bun with silver pins, she holds open a cloth fan, edges slightly raised like a crescent moon, bright smile like warm sun. Soft late sunlight through raised golden dust, glowing beams on their faces and features. Blurred rice stacks and distant figures in crinkling background. Bright transparent low-saturation palette, ethereal poetic feel, grainy film, Canon RF 50mm f/2.8, both in focal plane, Chinese period costume film aesthetic. |
| 43 |【宋式·生活·田园】茶山采茶·晨光（原 prompt·中英） | 春日清晨，两位年轻的中国男女身处层叠茶山之上，四周整齐排列的茶树与嫩绿新叶。中景特写，两人身着轻薄棉麻。年轻女子梳低马尾，宋制汉服素白浅绿配色，高衩长裙，领口微开，袖口轻垂，微微俯身，挽竹编背篓，动作轻盈放松，长发松松挽起，正将新茶采入小竹篮中，眉眼弯弯，面带恬淡笑容。年轻男子穿宽松棉麻对襟汉服，青麻色细苎麻，系麻布花带，站在女子身旁微微俯身，面带温和笑意，目光交汇在采茶上。柔和晨光穿透茶叶，在他们脸庞与衣褶间洒下细碎光斑，远处群山初晓朦胧柔美雾气，色调温润舒适，饱和度偏低，空灵治愈，胶片颗粒感。佳能RF 50mm f/1.8镜头拍摄。英文原版：Spring morning, two young Chinese on a terraced tea hill with rows of tea bushes and tender bright-green leaves. Medium close-up, both softly sharp figures in a loose cotton-linen outfit. A young woman in elegant white and moss-green Song dynasty hanfu, high cross-cut skirt, high open collar and loose cuffs, she bends slightly, silk tied with a bamboo basket, picks tender tea buds into a small bamboo basket, eyes curved like crescent moons, radiant gentle smile. A young man in matching elegant hanfu, fine ramie robe, linen waist sash, stands close beside her, also in a cloth-wrapped wicker basket, soft rising light beams spread and fall on their faces and folds of clothes. Soft morning sunlight seeps through new leaves, casting bright low-saturation pastoral tones, blurred green hills in creaming fog. Canon RF 50mm f/1.8, f/2.8, soft focus, ethereal healing film aesthetic. |
| 44 |【宋式·生活·田园】茶山对望·深情（原 prompt·中英） | 春日清晨，两位年轻的中国男女身处层层茶山之上。中景特写，两人面朝彼此深情对望。年轻女子着优雅宋制汉服，素白青碧配色，发簪挽起乌发，领口精致，外罩纱质褙子，下裙随风轻扬，衣袂飘飘，轻捻茶芽似采早春新茶，神情温婉；年轻男子着宋制襕衫，布面质感质朴，腰间束布质腰带，身姿挺拔，侧身轻扶女子臂弯，目光温柔缱绻。地面错落青石板与茶园田埂，茶田缝隙点缀细碎野花与苔藓，背景云雾缭绕黛色山峦，晨光穿透薄雾，在发丝与衣褶上洒下柔和金光，山间偶有飞鸟掠过。色调清新雅致，空灵悠远江南春日氛围，电影般质感和柔和虚化。Canon R5 相机搭配 85mm f/1.2 镜头拍摄。英文原版：Spring morning, two young Chinese on a terraced tea hill rows of tea bushes and tender green leaves. Medium close-up, both face towards each other in deep affection. A young woman in elegant white and moss-green Song Dynasty Hanfu, high cross-collared right-tied top and tasseled skirt at the neckline, silk belt over a pleated skirt, embroidered headpiece, hair coiled in a bun with silver hairpin, her pick tender tea buds into a small bamboo basket, eyes curved like crescent moons, radiant, gentle smile. A young man in matching elegant Hanfu, fine linen robe, round lapel, embroidered cloth belt, in a cloth-wrapped turban with a wooden pin, he steadies the basket beside her, her slender waist, their gazes meet. Soft morning sunlight through new leaves, dappled light on their hair and robes. Green hills in misty backdrop, birds traverse low-hanging clouds, ethereal Chinese ink aesthetic. Canon R5 85mm f/1.2, both in focal plane, shallow depth of field, cinematic feel. 3:1 ratio, soft focus |
| 45 |【宋式·生活·田园】水田抛秧·两小无猜（主画面·原 prompt·中英） | 画面通透，低对比度与低饱和度，空灵治愈氛围。乡村欢快的春日下午：一位身着汉服的年轻女子，青蓝绿色调交领襦裙，内搭交领右衽，外罩窄袖褂子，下裙绣缠枝莲纹并系束腰；梳宋代双丫髻，插银簪，站在水田边田埂上，张开双臂将一大把嫩绿秧苗向波光粼粼的水田抛洒；秧苗在空中飞舞，细小水珠在光线闪烁。她回眸望向远方，双鬓微风吹拂。年轻男子赤脚弯腰向稻田洒着白色肥料，面带笑容，长发束简单发髻，腰间系麻布短褐，裤脚卷起，赤脚踩湿润泥土。远处金色薄雾中隐约可见水牛身影，更远处梯田层层叠叠上映斑驳光影，薄暮阳光穿透薄雾，在稀疏秧苗和水地倒影的麻柳树上投下斑驳光影。英文原版：Bright, translucent, low contrast and low saturation, ethereal, healing atmosphere, a joyful spring afternoon scene in the countryside: a young Chinese woman with delicate East Asian features, wearing white and moss-green Song dynasty hanfu - a cross-collared right-lapelled top with a narrow-sleeved short jacket over it, a pleated skirt with lotus embroidery tied with a cloth sash, her hair in a Song dynasty double-bun style with silver hairpins - stands on a narrow ridge between rice paddies, smiling happily as she tosses a small handful of green rice seedlings through the air towards the water, a young Chinese man wades in the shimmering paddy a few steps away, the seedlings mid-flight between them with tiny water droplets sparkling in the light. Her face is turned and curved with brighter light as she looks back over her shoulder at him. The young man, wearing matching plain white and moss-green Song dynasty trousers rolled up above his ankles, his hair tied back in a simple cloth wrap, grass-capped scattered over a wooden hairpin, reaches both hands out with a wide happy smile to catch the seedlings, the soft diffused light of the warm late afternoon sun, softly diffused through the mist, casts dappled light and shadow on the rice paddies and the distant terraced fields, a faint silhouette of a buffalo can be seen in the golden mist in the distance, the thin willow trees by the water are faintly visible, with light filtering through the sparse leaves. |
| 46 |【宋式·生活·田园】垂柳湖畔·柳絮花瓣（原 prompt·中英） | 画面明亮通透，低对比度与低饱和度，空灵治愈氛围。乡村欢快春日下午：一位面容清秀的年轻中国女子，着素白抹茶绿棉麻汉服上衣，下搭浅灰色阔腿裤，外罩窄袖短褂，手提用草绳扎好的鲜花束；梳宋代双环髻，插简约银簪，站在两株相互依偎的垂柳间，开着一小簇淡粉野蔷薇的绿柳枝条向远处波光粼粼的湖面，软絮在空中飞舞，地上的水线在光线下闪。她回眸望向远方，笑意温婉，双眼弯成月牙形。年轻男子着素白麻白配墨绿色交领短褐，发束简单布发带，正弯腰捡拾掉落的花瓣，湖面泛起柔和涟漪，湿润午后阳光穿透薄雾，在如镜的湖面和水底细滑砂砾上投下斑驳光影，远处金色薄暮中隐约可见水牛身影。英文原版：Bright, translucent, low contrast and low saturation, healing atmosphere. A joyful spring afternoon in the countryside; a young Chinese woman with delicate East Asian features, wearing plain white and moss-green Song dynasty hanfu - a cross-collared light short top with a narrow-sleeved jacket over it, paired with wide-leg grey linen pants, her black hair in a Song dynasty double-bun chignon with simple silver hairpins – stands on a narrow grass ridge between flower-filled rice paddies, tugging the tail of a small fresh green rice shoot while smiling towards the lake shore. A young Chinese man wades in the shimmering paddies a few steps away, the seedlings mid-light glisten with them when tiny water droplets splash upwards. Her eyes are curved with bright laughter as she looks back over her shoulder at him. The young man, wearing matching plain white and moss-green Song cross-collared short-changru with his black hair in a simple cloth-wrapped topknot, bent over a wooden basket, reaches out both hands with a wide smile to catch the drifting willow catkins and soft petals. Warm afternoon sunlight, softly diffused through thin mist, casts dappled light and shadow |
| 47 |【宋式·生活·田园】窗下煮茶（X-Pem中式美学10·原 prompt·中文） | 夏日下午，一位身着素白宽松宋式汉服的年轻女子坐在木窗边倒茶，粗陶茶壶中升起缕缕白色蒸汽。画面明亮通透、低对比度、低饱和度，营造空灵治愈的氛围。温暖的窗光在木桌上投下斑驳树影，几缕发丝随轻柔的穿堂风飘动。前景是虚化的窗棂与绿色植物，背景是柔和散景中的白墙。宋式夏装层叠雅致：素白与翡翠绿配色，交领内衫、宽松外袍、修长飘逸的裙摆，棉麻褶皱自然垂落。女子带着温柔浅笑，黑发半束，姿态放松。瓷白肌肤，面部清晰对焦。整体宁静、诗意、田园、浪漫而治愈。略微低机位的电影构图，Canon EOS R5，RF 85mm f/1.4，浅景深，奶油般散景，真实纹理，细微胶片颗粒，干净高清的中国古装电影剧照。负面：畸形手指、多余肢体、错位五官、重复茶具、变形茶壶、服饰穿帮、塑料质感、过度磨皮、强饱和、杂乱背景、现代物件、文字、水印、标志 |
| 48 |【宋式·生活·田园】庭前浇花·特写改造（X-Pem中式美学10·原 prompt·中文） | 以参考图作为系列母版视觉参考，严格延续人物温和自然的面容、半束黑发与风中碎发、米白外袍和黛绿交领内衫、棉麻质感、白墙深木、低饱和夏日光色；只把原来的浇花全身镜头改为正面特写。生成16:9横幅、8K高清细节的平视正面胸像特写：女子位于画面中央，从头顶拍到胸腹之间，约占画面高度三分之二，双肩基本正对镜头，不要侧身。粗陶浇水罐进入右下方近景，右手握住壶柄，左手托住圆形壶身，两只手及其与陶罐的接触关系完整可见。她轻轻倾斜陶罐，一道清晰纤细的水弧斜穿画面下沿，落入前景虚化花丛，使浇花动作一眼可辨。女子的视线越过镜头略微向下，看向花草，嘴唇闭合并带安静浅笑；面部自然柔和明暗和眼神清晰，不强调塑料般光滑皮肤。右上方树叶过滤的暖阳在脸颊、发丝和米白衣袖上形成轻柔碎影，正前方偏冷的天空散射光补亮眼睛和暗部。白粉墙与深色木窗在背景化成奶油散景，前景花朵形成柔和色块，保留轻微胶片颗粒和宋式田园电影的亲密治愈感。负面：侧脸、三分之二侧身、全身远景、裁掉双手或陶罐、现代水管、塑料花盆、华丽首饰、文字与水印 |
| 49 |【宋式·生活·田园】瓜棚摘果·双人（X-Pem中式美学10·原 prompt·中文） | 以参考图作为系列视觉母版，延续自然温和面容、半束黑发、米白与黛绿宋式棉麻层叠、白墙深木、树影和低饱和浅景深。生成16:9横幅、8K高清细节的瓜棚摘葫芦双人画面：略低机位的中景，从竹制瓜棚下向上看，藤叶占据上半画面，一只浅绿色葫芦自然垂在中央上方。左侧主角抬起双手，一手托住葫芦底部，另一手轻触短梗确认成熟度，脸向上仰，眼睛专注看梗；右侧邻家姑娘双手稳稳托着宽竹篮，视线也落在葫芦上，准备接取。四只手的归属和接触关系必须清楚，不要多手。抬臂使宽袖形成长而自然的垂坠褶皱，葫芦保持垂直，叶片、碎发和衣带随同一阵侧风轻动。右上方暖阳穿过藤叶，在脸和米白衣袖上投下柔碎叶影，院中散射光补亮瓜棚阴影。人物面部、双手与瓜梗清晰，边缘藤叶和后方白墙木檐奶油虚化。负面：巨大魔幻葫芦、现代温室、塑料棚架、多余手指、宫廷花园、文字与水印 |
| 50 |【宋式·生活·田园】田埂送食·全身行走（X-Pem中式美学10·原 prompt·中文） | 以参考图作为人物与光色母版，延续自然柔和面容、半束黑发、米白外袍和黛绿交领内衬、棉麻垂坠、低饱和夏日田园电影感。生成16:9横幅、8K高清细节的田埂送饭画面：略低机位的全身环境镜头，一名女子从左侧中景沿狭窄田埂走向右侧近景，左手提带盖竹编食篮，右手提小粗陶茶壶，视线望向画外远处劳作的人。她的步伐轻缓，衣带与长裙下摆向身后产生自然滞后，少量发丝也被同一阵田风吹向后方。田埂两侧是浅水稻田，稻叶顺风微倾，水面倒映淡蓝天空；远处只保留朦胧白墙农舍和很小的田间人物。右上方午后暖色逆光勾亮发丝、竹篮纹理和米白衣缘，天空散射光补亮正面。前景稻穗柔化，人物清晰，远村淡入薄雾，呈现宁静归家的诗意。负面：现代道路、塑料饭盒、金属保温壶、宫廷服饰、时尚走秀姿态、文字与水印 |
| 51 |【宋式·生活·田园】豆架采青（X-Pem中式美学10·原 prompt·中文） | 以参考图作为系列母版，保留同一女子的温和面容、自然半束黑发、米白外袍与黛绿交领内衬、棉麻褶皱、白墙深木和低饱和夏日光色。生成16:9横幅、8K高清细节的菜畦摘豆画面：平视中全景，女子站在竹制豆架下方、位于中央偏左，身体三分之二朝向镜头，眼睛专注看向藤蔓。右手抬起，拇指和食指在豆荚根部做明确摘取动作；左臂把小竹篮稳稳托在腰侧。抬手使一侧宽袖自然展开，另一侧袖子围绕竹篮堆叠，发丝、豆藤和细小花朵随微风同向轻动。上方垂落藤叶形成层叠前景，脸旁只保留少量豆荚，后方白粉墙提供干净留白。左上方树叶和藤蔓过滤的暖阳在面部、衣袖和墙面投下移动碎影，天空散射光柔和补亮暗部。脸、指尖与豆荚根部清晰，近藤和远陶罐奶油虚化。负面：现代温室、塑料网、巨大畸形蔬菜、宫廷花园、时尚摆拍、文字与水印 |
| 52 |【宋式·生活·田园】石磨流浆·双人（X-Pem中式美学10·原 prompt·中文） | 以参考图作为人物、衣装、材质和光色母版，延续自然温和面容、松弛半束黑发、米白与黛绿棉麻宋式夏装、白墙深木、低饱和通透电影质感。生成16:9横幅、8K高清细节的廊下推石磨双人画面：与石磨台面平齐的中景，圆形手推石磨占据中央近景。左侧主角双手握住水平木柄并沿顺时针方向推动，上身、肩膀和宽袖随圆弧产生可信的用力与滞后；右侧同伴微微靠近石磨，一只手把泡好的豆子送入中央孔洞，另一只手用小粗陶杯注入细水流。两人视线都落在石磨入口，不要看镜头，四只手的归属与接触关系清楚。上层磨盘正在转动，浅色豆浆沿石槽流入粗陶碗，槽口挂有少量水滴。左上方暖阳穿过木格窗与树叶，凉爽廊下散射光补亮面部、石纹和衣褶。双手、孔洞和豆浆流清晰，前景虚化豆粒，背景白墙陶罐柔化。负面：电动磨浆机、金属机器、塑料盆、多余手臂、宫廷室内、文字与水印 |
| 53 |【宋式·生活·田园】麦田收穗·双人（X-Pem中式美学10·原 prompt·中文） | 以参考图作为宋式田园系列母版，保留主角温和面容、半束黑发、米白与黛绿棉麻衣装、白墙木屋、低饱和通透光色。生成16:9横幅、8K高清细节的初夏麦田收割双人画面：平视环境广角，镜头隔着下方虚化麦穗观看，两名女子位于画面中央偏右。主角三分之二朝向镜头跪在麦垄间，左手拢住一小把麦秆，右手把木柄短镰刀准确放在秆根下方；邻家姑娘位于她后侧，穿低饱和蓝灰衣裙，正用草绳捆扎已经割下的麦束。两人都看向手中动作，不要看镜头。田风让发丝、袖缘和麦浪朝同一方向轻动，割下的麦秆整齐倒伏。左上方柔和暖阳给麦穗、发梢和衣缘增加克制蜂蜜色高光，天空冷色散射光补亮面部，整体不做浓烈橙黄色。镰刀、双手和草绳接触处清晰，前景麦穗与远处白墙村舍奶油虚化。负面：收割机、现代农具、工业化大农场、宫装、整齐摆拍、文字与水印 |
| 54 |【宋式·生活·田园】树下清谈·四人群像（X-Pem中式美学10·原 prompt·中文） | 以参考图作为系列母版视觉参考，保留米白与黛绿宋式棉麻衣装、自然半束黑发、白墙深木、夏日树影、低饱和通透调色和浅景深。生成16:9横幅、8K高清细节的院中茶叙群像：环境广角、平视机位，镜头隔着左下角虚化绿叶观看，四名年轻女子围坐在树荫下的旧木矮桌旁，形成松散半圆。主角位于中央偏左，穿与参考图一致的米白外袍和黛绿内衫，正用粗陶壶倒茶；右侧一人伸手接杯，另一人微微前倾笑谈，最外侧一人托着小果盘安静倾听。每个人的视线都落在同伴或茶具上，不要整齐看镜头。茶汽在手与衣袖之间上升，微风让少量发丝、袖缘和树叶轻动。右上方树冠过滤的暖阳在白墙、桌面和衣料上落下柔碎光斑，天空散射光补亮阴影。人物平面清晰，前景叶片与远墙柔化，具有宋代乡居生活电影的真实、克制、亲密与治愈感。负面：宫廷宴饮、排排坐、现代桌椅、艳色丝绸、繁复发饰、浓妆、文字与水印 |
| 55 |【宋式·生活·田园】溪畔洗蔬·双人（X-Pem中式美学10·原 prompt·中文） | 以参考图作为系列母版视觉参考，延续自然面部塑形、松弛半束黑发、米白与黛绿色棉麻宋式衣装、白墙木屋、夏日树影、低饱和通透色彩与电影浅景深。生成16:9横幅、8K高清细节的溪边洗菜双人画面：环境广角、平视机位，镜头隔着左下角虚化芦苇看向溪水，两名年轻女子分别跪坐在相邻平石上，身体相互朝向。右侧主角穿参考图同款米白外袍与黛绿交领层次，轻轻卷起袖口，双手把竹篮中的青菜浸入清水，低头带克制微笑；左侧邻家姑娘穿低饱和蓝灰与暖象牙色衣裙，提起滴水的菜叶转头与她说话。水纹从两人的手边扩散，菜叶水滴回落，发丝、袖缘与岸边柳叶随同一阵微风轻动。后方有小木桥、白墙深木农舍和柔绿田地逐层淡入薄雾。左上方树叶过滤的暖阳照亮水滴与发梢，天空散射光柔和填充阴影。人物与手部互动清晰，前景芦苇和远村奶油虚化，呈现清新、唯美、安静的宋式田园电影诗意。负面：塑料盆、现代水泥河岸、宫殿、繁复发饰、所有人物看镜头、文字与水印 |
| 56 |【宋式·生活·田园】灶前炒青（X-Pem中式美学10·原 prompt·中文） | 以参考图作为这组宋式田园人物系列的母版视觉参考，保留人物温和自然的面部、半束黑发与零散发丝、米白与黛绿色棉麻宋式夏装、白墙深木、低饱和通透色彩和浅景深；只改变动作与空间。生成16:9横幅、8K高清细节的灶间炒菜画面：中远景、平视机位，从微暗门框向室内观看，一名女子位于右侧三分之一，在低矮土灶前用木铲翻炒铁锅中的青菜，左手轻轻收住宽袖避开灶火，身体放松，侧脸望向木窗。蒸汽从锅中升起并向窗口缓慢飘散，前景虚化一篮蔬菜，中景人物面部与双手清晰，背景只有粗木架、陶罐和白粉墙。左上方经过窗格与树叶过滤的暖阳形成柔和碎影，门口冷色天光作宽幅补光，暗部保留纹理。画面具有中国古装生活电影的真实质感、轻微胶片颗粒和奶油散景。负面：现代厨具、塑料器皿、宫殿、华丽首饰、浓妆、过度摆拍、卡通感、文字与水印 |
| 57 |【宋式·生活·田园】荷塘采莲·双人行船（X-Pem中式美学10·原 prompt·中文） | 以参考图作为宋式人物与光色母版，延续自然面容、半束黑发、米白黛绿棉麻夏装、低饱和通透色彩和电影浅景深。生成16:9横幅、8K高清细节的荷塘采莲双人画面：略高机位的环境广角，镜头从虚化荷叶之间看过去，一条窄木舟由左下斜向右上穿过画面。主角跪坐在右侧船头，左手稳住宽阔荷梗，右手在莲蓬根部做明确旋转摘取动作，视线落在双手接触处；后方邻家姑娘穿低饱和蓝灰衣裙，把一根木篙斜插入水中，身体向木舟行进方向的反侧轻微倾斜。木篙产生窄长水纹，船边荷叶向外偏转，被提起的荷梗滴下水珠，发丝与袖缘顺着行船方向向后飘。左上方暖阳经过荷叶过滤，勾亮脸、衣缘和莲蓬，水面反射的冷色天光补亮叶下暗部。手、莲蓬和木篙清晰，近处荷叶与远方白墙水乡柔化。负面：机动船、塑料桶、巨大魔幻荷花、宫廷湖景、繁复宫装、文字与水印 |
| 58 |【宋式·生活·田园】晒场扬谷·三人（X-Pem中式美学10·原 prompt·中文） | 以参考图作为人物和视觉母版，保留面部柔和自然明暗、自然半束头发与少量风中碎发、米白黛绿宋式棉麻衣装、白墙深木、夏日碎影和低饱和通透光色。生成16:9横幅、8K高清细节的庭院晒谷群像：略高机位环境广角，大面积谷粒薄薄铺在石板院中，三名女子形成不规则三角。右侧主角双手分开握住长木耙，把木耙朝自己方向拉动，耙齿在谷面留下清楚平行纹路；中央同伴倾斜竹筐，让一股克制的谷粒落向晒场；左侧同伴提起素色麻布一角，把小堆谷物重新摊开。三人都看向劳动动作，不要同步看镜头。谷粒在耙齿周围滚动，倾倒的谷流可见独立颗粒，贴近地面只升起少量尘雾。左上方午后暖色逆光穿过树枝，照亮谷粒边缘和细尘，天空散射光柔和补亮脸和白衣。主角双手与木耙清晰，白粉墙、深色屋檐和木门形成背景。负面：机械烘干机、塑料篷布、工业编织袋、宫廷庭院、整齐摆拍、文字与水印 |
| 59 |【宋式·生活·田园】桑园采叶·三人（X-Pem中式美学10·原 prompt·中文） | 以参考图作为人物、衣装和光色母版，延续米白与黛绿宋式棉麻层叠、自然半束黑发、白墙深木、夏日树影和浅景深。生成16:9横幅、8K高清细节的桑园采叶群像：略高机位的中远景，镜头穿过多层桑叶观察，三名年轻女子分别处在近、中、远三个深度。主角位于中央，右手从低枝上捏取一片嫩桑叶，左手托着装有少量桑叶的浅竹篮；左侧同伴抬手采高处叶片，右侧同伴弯腰把叶片整理进背篓，三人的动作和视线彼此独立。采摘后枝条轻微回弹，袖缘擦过叶片，发丝和叶面被同一阵微风带动。右上方经过树冠过滤的暖阳在脸颊、手指和棉麻衣褶上投下柔碎树影，天空散射光补亮阴影。主角面部与采叶手势清晰，近处桑叶形成奶油遮挡，远处白墙农舍和树行逐渐虚化。负面：现代果园设备、宫廷园林、夸张发饰、三人同步摆姿势、文字与水印 |
| 60 |【宋式·生活·田园】庭院晾衣·3-4背身（X-Pem中式美学10·原 prompt·中文） | 以参考图作为系列母版视觉参考，保留同一女子的安静气质、半束黑发与风中碎发、米白和黛绿宋式棉麻夏装、白墙深木、通透低饱和调色与浅景深。生成16:9横幅、8K高清细节的晾晒衣物画面：环境广角，略偏人物后侧的全身视角，一根横向竹竿贯穿院落，女子站在中央偏右，抬起双臂把刚洗好的米白麻衣搭上竹竿，脸微微转成侧面看向被风吹动的布料。大片半透明湿布占据左半画面并作为层叠前景，抬臂动作使她自己的宽袖形成自然拉伸与褶皱，湿衣在双手之间略微下坠，发丝、衣带和布边朝同一方向轻摆。石地上只放一只旧木盆，顶部由深色木檐压住画面。左上方午后暖色逆光穿过叶隙和湿布，在白墙上投下柔亮流动的影子，院中冷色散射光补足面部和衣褶。焦点落在人物、双手与布料接触处，近处布边柔化，远门奶油虚化，呈现朴素而治愈的宋式乡居电影感。负面：现代衣夹、尼龙绳、化纤服装、宫廷华服、时尚硬照姿势、文字与水印 |
| 61 |【宋式·生活·田园】茶山采青·四人（X-Pem中式美学10·原 prompt·中文） | 以参考图作为人物、衣装和光色母版，保留温和自然的脸、松弛半束黑发、米白黛绿棉麻宋式夏装、低饱和通透调色与细腻胶片质感。生成16:9横幅、8K高清细节的茶山采茶群像：平视环境广角，弯曲茶垄沿山坡形成自然层次，四名女子分布在同一条斜向梯田的不同高度。主角位于左下近景，背后固定竹编采茶篓，右手用指尖选取两片嫩叶，左手轻扶枝条；另外三人分别在更高处采摘，身穿低饱和象牙白、蓝灰和浅鼠尾草色衣装，各自朝向不同茶树，不要统一看镜头。抬手动作使宽袖展开，被放开的枝条轻微回弹，发丝和叶尖顺着上坡微风摆动。左上方清晨暖阳穿过薄雾，天空冷色散射光保持面部与白衣通透，叶缘只有少量露珠高光。近景指尖和茶叶清晰，前景茶枝、远处白墙村舍与山脊逐层柔化。负面：现代采茶机、统一制服、游客摆拍、宫殿、过饱和翠绿、文字与水印 |
| 68 |【宋式·生活·田园】秋日打谷场·双人（外部高分·X2 结构卡） | 秋日午后，两位年轻的中国人在金色打谷场上。中景特写，两人面部焦点清晰锐利。年轻男子身穿深白配苔绿色的束腰汉衣——交领长衫配布质腰带，发鬓用布帛包裹并扎有木簪，身姿挺拔，肩扛竹扁担，两端挑着装谷物的箩筐，面带温暖笑容。年轻女子身穿同色系白绿汉服——高交领右衽布衫领口严谨合拢，外罩褙子，下着百褶裙，发梳双髻缀银簪，双手撑开一只布袋，笑眼弯弯，目光落在同伴的箩筐上。暖阳穿透扬起的金色尘埃，光映成鲜明笑脸，灿烂喜悦。两人面部饱满虚化柔焦，背景乡村人影模糊，画面高通透度饱和度，带有胶片质感。RF 50mm f/2.8，两人均处焦平面，中国古装电影视觉美学。负面：畸形手指、塑料布、机械打谷机、现代衣装、摆拍感、文字水印、低质量 |
| 69 |【宋式·生活·田园】深秋院落读书·单人（外部高分·X3 结构卡） | 深秋午后，一位年轻中国女子坐在中式农家院落的矮凳上读书，身旁竹制晾晒席上铺满金黄谷物。中近景，面部焦点清晰。她身着优雅的白瓷宋制汉服：高交领右衽襦袖口严密，外罩丝质领子，下着百褶裙；乌发梳成双环髻，插银簪。她手捧书卷，指尖正翻动书页，抬头间流露柔和浅笑，目光温润明亮。午后暖阳穿透浮动金色尘埃，化作高耸耶稣光倾泻在脸庞与裙摆。竹筐环绕，背景金黄麦穗在奶油般柔和的焦外光斑中。色调温暖唯美，低反差低饱和，空灵悠远诗意，细腻胶片质感。R5，RF 85mm f/1.4，浅景深，奶油般柔美虚化，中国古典电影美感。负面：畸形手指、文字乱码（书页字迹不进画面）、现代书本、塑料质感、强饱和、文字水印、低质量 |
| 70 |【宋式·生活·田园】荻花水边·戏水（外部高分·X4 结构卡） | 夏日午后，持竹斗笠的她，脸占据画面上方三分之一。东亚面部特征的年轻中国女性，身着白色系与茶褐色相间宋制汉服——交领右衽长衫领口绣合领纹搭配百迭裙，发型梳成宋代双环。她蹲在一片荻花里，一手握着微黄荻花，另一手俏皮撩拨水边芦苇，晶莹水珠如破碎玻璃珠般悬浮半空；抬头望向镜头，笑容灿烂，双眼弯成月牙。午后暖阳在脸庞与波光粼粼水面投下斑驳光影；几缕散落发丝轻拂白皙透着红润光泽的脸庞，焦点清晰锐利。前景荻花虚化散景，画面明亮通透，低对比低饱和，治愈系氛围，胶片颗粒质感。低角度拍摄，RF 85mm f/1.4，浅景深，中国古典美学。负面：畸形手指、现代衣物、过度磨皮、强饱和、塑料质感、文字水印、低质量 |
| 71 |【宋式·生活·田园】夏日窗下点茶·单人（14 步详装·中英） | 夏日午后，素白墙、深色木窗的宋式书房窗下，一位宋代女子坐于旧木案前候汤点茶。案上粗陶壶口白雾袅袅，青瓷盏釉光温润，竹茶则斜搁。米白与黛绿低饱和色板，通透留白，空灵宁静。窗外梧桐叶影婆娑，阳光被切碎成光斑洒在木案、壶身与她手背上，明明灭灭如碎金，尘埃在光柱里浮动。茶雾盘旋，光斑随风轻晃，指尖微动。前景绿植虚化斜入，中景人物，背景白墙化奶油散景。米白交领内衫，外罩黛绿褙子，下着米白百迭裙，棉麻细褶自然垂落。半束黑发簪木簪，远山黛眉，檀唇淡抹，垂眸凝神，唇角浅笑，坐姿端雅。细腻通透肤质，焦点在眉眼与指尖。静谧、雅致、自得、岁月静好。平视中近景缓慢推镜，从茶盏推至眉眼。85mm f/1.4，ISO 400，浅景深，奶油散景，细微胶片颗粒，低反差柔光，柔和唯美细腻电影化。负面：手部畸形、六指、五官错位、塑料质感、过度磨皮、强饱和、现代物件、文字水印、低质量 |

#### 3.5.10d 案例归档·庭院/宫廷/文事（6 条）

| # | 案例 | 核心场景句（直接替换进 prompt 的「场景」段） |
|---|---|---|
| 62 |【庭院·宫廷·文事】庭院抚琴·贵族仕女（高兴AIGC·原 prompt·中文） | 电影感中景，一位优雅的中国古代贵族女子安静端坐于传统庭院中弹奏古筝。她纤指轻抚琴弦，神情从容优雅。象牙白刺绣丝袍，精致传统纹样，飘逸广袖，真丝质感，自然细褶。乌黑长发梳成典雅古风发髻，饰以玉簪与珍珠。通透柔粉肤色，自然透亮，细腻写实肤质，面部柔和高光。古筝呈现抛光旧木质感、精细琴弦、传统工艺。中式庭院：旧木建筑、灰瓦屋顶、竹影、传统园林元素。暖金逆光穿过树枝，发丝边缘柔光，丝绸袖缘泛光，细碎光粒子浮动。人物约占画面 50%，低机位，前景古筝琴弦，浅景深，柔和奶油散景。85mm 镜头，ARRI Alexa 35 摄影机，Kodak 胶片色彩，东方帝国古典电影风格，超写实，历史东方美学，电影镜头光晕，非 CGI 金色时刻。负面：动漫、卡通、3D 渲染、CGI、游戏角色、幻想铠甲、西方公主、现代妆容、塑料皮肤、美颜滤镜、影棚灯光、硬闪光、戏剧性聚光、过饱和、廉价服装、假珠宝、造作姿势、完美笑容、不真实的手、多余手指、低质量、现代物件 |
| 63 |【庭院·宫廷·文事】大殿回眸·巨物室内（高兴AIGC·原 prompt·中文） | 杰作、极致细节、8K、史诗电影感、虚幻引擎5、Octane 渲染、物理渲染、照片级写实 CG 动画帧。极致广角，恢弘皇宫大殿，极高穹顶，雕花木梁，金色立柱，整面墙的巨型古代山水画卷，长丝帛条幅，宫灯，宫廷空间向画面深处延伸，空旷大殿地面。一位中国古代美人回头望向镜头，人物仅占画面 10%，巨物室内中的微小人物，全身，精致银金发饰，长发随风飞扬，刺绣汉服，巨大半透明丝绸飘带狂舞，层叠纱袖，金线纹样，玉佩。侧窗金色轮廓光，体积光尘埃光柱，深焦全画面清晰，轻微胶片颗粒，戏剧性情感氛围。负面：无坏解剖、无畸形肢体、无僵硬布料、无现代物件、无文字、无水印、无过曝、无散景、无模糊背景 |
| 64 |【庭院·宫廷·文事】江南庭院·五人日常（高兴AIGC·原 prompt·中文） | 电影感中广景，午后旧江南庭院，五位身着素色棉麻衣物的年轻中国女子做日常活动：一人织布、一人备茶、其余轻声闲谈。阳光穿过木窗与树枝，旧白墙上光影图案美丽，暖光包裹面容，石地柔和反光，空气中漂浮发光尘粒，微风拂动白布。写实古代村落生活，自然表情，无摆拍。半透明柔粉肤色，写实肤质，手织棉麻布料，风化木纹质感，梦幻自然光，电影氛围纵深。Canon EOS R5 RF85mm f1.2 镜头，浅景深，超写实 |
| 65 |【庭院·宫廷·文事】江南市集·晨市买菜（高兴AIGC·原 prompt·中文） | 电影感纪实中景，古代江南村落市集，清晨。四位年轻中国女子穿素净灰蓝、象牙白与茶绿棉麻衣，向老农买菜。一人轻巧议价手持鲜蔬，一人抱着装满蔬果的竹编篮，另两人自然微笑闲谈。真实日常互动，不摆拍。鲜活市集氛围：铺满绿叶的木摊、竹篮、陶罐、旧木招牌、背景村民、旧白墙灰瓦屋顶。阳光透过树叶与木顶，柔和自然光斑，蔬菜上水珠反光。半透明柔粉、蜜桃米色面容，自然透亮肌肤，写实肤质。符合史实的古风发型，简约低髻配木簪。自然衣褶，写实纺织纤维。柔和电影对比度，柔和阴影过渡。Canon EOS R5 RF50mm f/1.2，浅景深，自然散景。超写实古代生活纪实摄影 |
| 66 |【庭院·宫廷·文事】庭院文事·双姝阅卷（原 prompt·中文） | 午后庭院室内，两位身着素雅汉服的年轻女子围石桌对坐。左侧女子手持团扇轻摇，微微侧首看向桌案；右侧女子双手翻开一卷书页，垂眸专注阅读。石桌上铺展写满字迹的纸页与卷轴，陶罐中插着一枝盛放的粉牡丹，几片花瓣散落于桌面与地面。背景为木质格窗，窗外绿树葱郁，柔和天光透入，室内光影清朗雅致。整体氛围安静清幽，闺阁文事气息。中景平视，双人斜对构图，浅景深，前景团扇边缘与桌面卷轴虚化。85mm 定焦，f/2.0，ISO 200，午后漫射光。负面：字幕、文字、水印、现代物件、浓妆、艳丽俗色、人物看镜头、卡通、低质量 |
| 67 |【庭院·宫廷·文事】贵妇撒花戏鱼·主从（外部高分·X1 结构卡） | 画面明亮通透，对比度与饱和度和谐，灵动氛围。一位面容娇俏、身姿绰约的中年贵妇，身后跟着两位持扇侍女——团扇一左一右交叠。贵妇外罩月白锦缎袍子，下身是绣着缠枝莲纹的软缎长裙，脚踩绣着金莲的软鞋，乌发挽髻簪珠翠。她站在两汪清水池边的浅草坪上，伸手将一大捧娇妍的鲜花撒向波光粼粼的池面；微风拂过，池中水光在日光下晃动似碎金般闪烁，池边垂柳枝条轻摆，几只锦鲤在水中摆尾游弋。贵妇眉眼舒展，望着眼前景致，面上呈现满足笑意；身后侍女低眉顺眼，端着精致茶盏和糕点，氛围闲适悠然。前景一丛虚化矮竹，中景贵妇与侍女清晰，背景水榭檐角奶油虚化。正面顺光辅侧逆，暖金基调，低机位中景。负面：畸形手指、宫女宫装繁复、现代物件、强饱和、塑料质感、文字水印、低质量 |


> 用法：选一个案例 → 把核心句替换进「八、通用骨架模板」的场景段 → 其余字段（基调/人物/运镜/负面词）照抄。
> 中英双语：把核心句直译成英文后接 MJ 参数（--ar 16:9 --raw --s 210-280 --c 4-8 --no 文字 水印 ... --v 8.2）即得 MJ 版。

#### 3.5.11 增强视觉冲击力三件套（高赞作者亲授）

> 来源：抖音「东方异兽」系列作者夕云评论区公开技巧，工具为 GPT Image 2。
> 写巨兽/巨物/宏大场景时，在 prompt 里**必加这三个词**：

| 三件套 | 写法示例 | 作用 |
|---|---|---|
| 超低机位 | 超低机位仰拍，巨兽头颅压过画面上缘 | 让观众"站在巨物脚下"，压迫感直接拉满 |
| 前景参照物 | 前景放飞鸟/岩石/残破栏杆做参照 | 用已知小物体反衬巨物尺度，比直接说"巨大"有效十倍 |
| 预留想象空间 | 巨兽身体大部隐入云雾/画外，只露出头与局部 | 不拍全，让观众脑补更大——"看不见的才最恐怖" |

> 完整句式：超低机位 + 前景[参照物] + 巨物[露出局部]隐入[云雾/暗部] + 渺小人物对比。

#### 3.5.12 天宫母提示词完整范本（长文式·可直接套模板）

> 来源：抖音「月姐AI智能体」云上仙宫母提示词（GPT Image 2，9:16 竖构图）。这是长文式的顶级范本，逐段抄用：

```
一座悬浮于无边云海之上的宏伟东方神话天界，超大尺度中国古典宫殿群建立在天空、悬崖、高山与云层之间。
整体具有神界、仙境、天宫、东方史诗感，偏真实电影世界、超写实建筑摄影与高端影视概念设计，拒绝廉价仙侠手游感。

建筑融合盛唐、宋式皇家宫殿与东方幻想语言，包含巨大飞檐斗拱、层叠屋顶、雕梁画栋、白玉巨柱、宫门、牌楼、
长桥、玉石阶梯、悬空平台和神殿群。尺度极度夸张：柱高数十米、宫门如山岳、宫殿建于垂直悬崖，
层层延伸至云海深处。强调 monumental architecture, gigantic scale, impossible architecture, celestial megastructure。

主体材质为象牙白、乳白、浅灰天然大理石与白玉，具有真实石纹、细微裂纹、磨损、浮雕、祥云纹及克制古金装饰，
拒绝纯白塑料感。部分场景可加入暗朱红巨柱、深木长廊，与白玉建筑形成反差。

下方覆盖厚重真实的白色云海，云层在山峰与宫殿之间流动，远方建筑逐渐隐入淡蓝灰雾霭。
部分平台、悬崖形成巨大瀑布落入云海；白玉地面可覆盖浅水，形成天空镜面、倒影和轻微涟漪。

可加入巨大苍老千年古松作为前景框景，枝头偶尔停一只丹顶鹤；远山有少量孤松与悬崖植被，整体克制。
画面只出现 1—2 名极小东方古装人物，占画面约 1%—3%，背对或侧背镜头，身穿简洁飘逸的白色、象牙白或白红长袍，
黑色长发，静静行走、站立或眺望，用作尺度参照，不突出脸部，不战斗、不持武器。

天空辽阔真实，以淡蓝灰、象牙白、暖金、浅杏色为主；部分场景可出现巨大真实月球或极远处悬浮神殿。
电影级清晨或日落自然光，低角度侧逆光、柔和体积光、真实阴影、空气透视、全局光照与轻微反射。

整体低饱和、高动态范围，主色为象牙白、暖灰、云雾灰、浅蓝灰、暗朱红、古金、松柏深绿，
拒绝廉价金黄与蓝紫荧光。

9:16 竖构图，18—24mm 超广角建筑摄影，强调 foreground framing、leading lines、atmospheric perspective、
extreme depth、layered composition。必须具有前景→中景→远景→极远景四层空间，
建筑占主体，人物极小，让观众第一眼感到"人非常小，这个世界大得不可思议"。
```

> **范本要点拆解**（写任何宏大场景照此结构）：
> ① 定调句（史诗感+拒绝廉价感）→ ② 建筑/主体（堆叠制式词+尺度词）→ ③ 材质（真实细节+拒绝塑料感）→
> ④ 环境（云海四层）→ ⑤ 前景装饰（古松/鹤，克制）→ ⑥ 人物（1-2 名极小、背身、不露脸）→
> ⑦ 光影（低角度侧逆光/体积光）→ ⑧ 色盘（低饱和+拒绝荧光）→ ⑨ 构图（超广角+四层空间+核心意图）

#### 3.5.13 巨物美学·视频生成完整配方（可出图可出视频）

> 来源：抖音「巨物美学」40 秒教程（GPT Image 出图 + Seedance 2.0 V19 图生视频）。「巨物美学」四字为**独立风格词**，出图时单打"巨物美学"即可成画，下面句段按需追加。

**① 风格词（可单独使用）**

```
巨物美学
```

**② 可选强化句（按需追加，不必全加）**

- 尺度句：远古传说生物，巨大到遮蔽天空，压迫感极强；微小人类站在画面前景角落形成强烈尺度对比，人像米粒一样渺小
- 氛围句：史诗级构图，电影级光影，真实自然环境，超现实但照片级真实，空气透视，云雾，逆光，低饱和高级色彩，极致细节，神圣、恐惧、敬畏感
- 凝视句：巨物以压迫感的姿态凝视视线方向并占据画面绝大部分

**③ 图生视频运镜 prompt（三条，逐条贴入视频工具）**

- 镜头 A｜逼近：巨物缓慢逼近，镜头缓慢后退
- 镜头 B｜后退详细版：摄像机使用极低角度缓慢后退（Slow Pull-back），像拍摄者被巨物的移动逼得后退，同时保持前景小人极其渺小。巨物移动时，地面出现轻微震动，碎石滚落，尘埃从废墟缝隙中升起，云雾被庞大身体挤压流动，光束被巨物遮挡，画面从明到暗产生压迫性的阴影变化。前景小人可以轻轻抬头然后后退逃窜，但不能变大，不能抢占主体
- 镜头 C｜节奏规范：整体节奏慢、重、窒息、不可阻挡。巨物的移动要有真实重量感和惯性，不要跳跃，不要快速冲刺，不要夸张攻击。保持照片级真实质感，低饱和史诗电影色调，体积光，空气透视和巨大尺度感。不要改变首帧中的主体设计，不要生成新怪物，不要出现文字、logo、水印，不要变成游戏CG或卡通。而是让观众觉得他还没到

**④ 完整工作流**

1. 先用「巨物美学」+ 可选句出首帧图片（GPT Image / 即梦 / 豆包均可）
2. 从生成结果中挑一张构图比例和氛围最稳的首帧
3. 进入图生视频：模型 Seedance 2.0 V19，比例 16:9，1080P，运镜选"缓慢后退"
4. 逐条贴入运镜 prompt A/B/C 生成片段，再拼接

**⑤ 变体示范·热带丛林巨物（原片完整 prompt）**

> 镜头处于神秘且茂密的热带丛林里，四处布满植被，巨大的藤蔓交错，巨高的古树，每个人物的皮肤表面被描绘成充满细腻的纹理变化，人物的每一丝皮肤纹理、电影感光影，真实的材质质感，面部表情的刻画极致，空气通透，云层，逆光，四周巨大的树干上寄生着奇异的花草，地面上散落着干枯的落叶和腐朽的木头，远处的山峦被云雾缭绕，河流以缓慢不可预测的速度蜿蜒穿过丛林，巨大的树叶在头顶交织成密不透风的绿色天篷，阳光艰难地穿透层层叠叠的叶片，在地面上投下斑驳陆离的光影，丛林中偶尔传来不知名鸟类的奇怪鸣叫声，画面整体充满着神秘而原始的氛围，镜头慢慢推进，同时镜头内人物逐渐变小，在移动时，植被的树叶产生抖动

**⑥ 巨物场景词库（纯场景向·自由组合，出图出视频通用）**

> 巨物观题材 = 场景即主体。下面四组词各挑 1-2 个拼进「巨物美学」风格词后即可成画。

**场景主体词（当"巨物"）**

```
山河类：巨山横断天地 / 云端仙山悬浮 / 巨瀑垂天 / 巨树撑天 / 万仞绝壁如屏
建筑类：通天巨塔 / 巨型宫阙 / 悬浮神殿 / 巨大城门半开 / 断壁残柱直插云中
神像类：巨佛低眉垂眸 / 巨神凝视 / 石像半埋黄沙 / 残破神像风化千年
巨兽类：远古巨兽蛰伏 / 巨鲸游过云海 / 巨龙盘踞山脊 / 巨龟驮山
天象类：巨月压城 / 天幕裂开一线 / 巨日垂落地平线
```

**尺度反衬词（让人"小"）**

```
人如米粒 / 飞鸟掠过如尘 / 云雾缠绕腰间 / 灯火如萤 / 楼阁如盒 / 人在画面角落 /
巨物脚下一条细小人影 / 渺小到几乎不可见
```

**氛围词**

```
空灵神圣 / 压迫窒息 / 史诗苍茫 / 静谧永恒 / 末日苍凉 / 梦幻超现实 / 敬畏与恐惧并存
```

**光效词**

```
云隙圣光 / 雾中巨影 / 逆光剪影 / 体积光柱穿过雾气 / 巨物遮天投下整片阴影 /
低饱和高级灰调 / 空气透视渐远渐淡 / 尘埃在光柱里悬浮
```

**构图公式**

```
巨物占据画面主体（≥2/3）+ 微小参照物（人/鸟/灯火）置于前景角落 + 天空留白或巨物顶天
```

**组合示例**

- "巨物美学。云海之上，一尊半掩于雾的巨佛垂眸，佛首没入云层，人立于下方石阶如米粒。云隙圣光斜落，体积光柱穿过雾气，低饱和灰调，空灵神圣。"
- "巨物美学。古树撑天，树冠如云，人站在树根褶皱里如蚁。晨雾弥漫，逆光勾勒巨树轮廓，飞鸟掠过如尘，静谧永恒。"
- "巨物美学。巨月压城，城楼在月光下如积木，人的剪影立于屋脊。冷白月光，云层流动，压迫窒息。"

---

### 3.5.14 世家园林·高门大户（富家小姐/世家公子场景）

> 写"高门大户、亭台楼阁、精细布置"向的古风世家场景用本配方。空间词库定"拍哪里"，布置词库定"精细到什么程度"，人物造型+光影定"贵气氛围"。

**① 空间词库（拍哪里）**

| 空间 | 写法 |
|---|---|
| 宅门 | 朱漆大门，门当石狮，照壁砖雕，影壁后青砖甬道 |
| 仪门 | 垂花门，抄手游廊，回廊曲折，朱栏美人靠 |
| 园林 | 亭台楼阁，水榭临波，假山叠石，曲径通幽，九曲桥横荷塘 |
| 内宅 | 正厅待客，花厅品茗，书房藏书，闺楼绣户，暖阁 |
| 点睛 | 月洞门框景，漏窗借景，太湖石瘦漏透皱 |

**② 布置词库（精细布置怎么写）**

```
紫檀/黄花梨家具，博古架陈古董，太师椅铺锦垫，云母刺绣屏风，
青花瓷瓶插时令花，官窑茶盏，博山炉香烟袅袅，宫灯暖光，
纱幔珠帘层叠，包浆温润，鎏金描金，丝绸流苏垂落
```

**③ 人物造型**

- 富家小姐：云鬓珠钗步摇垂流苏，绫罗襦裙（藕荷/月白/绯红），披帛，执团扇，眉心花钿
- 世家公子：锦袍玉带，束发玉冠，手持折扇，腰悬玉佩禁步，广袖长衫，皂靴

**④ 光影氛围**

```
轩窗日光斜照，纱幔透光如雾，烛台暖光晕染，月洞门框景收光，
水榭波光映顶棚，黄昏宫灯次第亮起
```

**⑤ 成品示范（可直接复制）**

富家小姐·闺阁：午后闺阁，紫檀梳妆台铜镜泛光，纱幔透光如雾。小姐着绯红绫罗襦裙倚窗而坐，云鬓珠钗步摇轻晃，执团扇半掩，目光望向窗外荷塘。轩窗日光斜照，光斑落在绣着牡丹的裙摆上。85mm f/2.0 浅景深，暖调柔光。

English: Afternoon boudoir, rosewood vanity with a glowing bronze mirror, gauze curtains diffusing light like mist. A young lady in crimson silk ruqun leans by the window, pearl hairpin swaying, holding a round silk fan half-covering her face, gazing at the lotus pond beyond. Sunlight slants through the lattice window, dappled light falling on her peony-embroidered skirt. 85mm f/2.0, shallow depth of field, warm soft light.

世家公子·书房：晨光书房，黄花梨书案摊着线装书，博古架陈青瓷古董，窗外竹影婆娑。公子锦袍玉带，束发玉冠，执笔悬腕，神色专注。窗光斜照，墨香氤氲，尘埃在光束中浮动。85mm f/2.0，侧逆光。

English: Morning study, huanghuali desk with thread-bound books, antique celadon on a display shelf, bamboo shadows swaying outside the window. A young master in brocade robe and jade belt, hair bound in a jade crown, brush suspended over paper, deeply focused. Window light slants in, ink fragrance lingering, dust floating in the light beam. 85mm f/2.0, rim light.

**⑥ 时辰氛围线（同一座宅子，四个时辰四种味道）**

| 时辰 | 写法 |
|---|---|
| 晨 | 晨光洒金，青砖甬道泛光，仆役洒扫，垂花门半开 |
| 午 | 午后斜照，回廊光影斑驳，荷塘波光映顶棚，蝉鸣静谧 |
| 昏 | 黄昏宫灯次第亮起，纱幔透出暖光，檐角剪影 |
| 夜 | 月夜静谧，月光洒在青石阶上，雕窗透出烛火，树影婆娑 |

**⑦ 园林四季（场景随季节换）**

- 春：桃花满园，柳絮纷飞，小姐游园扑蝶
- 夏：荷塘接天，蝉鸣，水榭乘凉，公子凭栏观鱼
- 秋：桂香满庭，银杏铺金，月下品茗
- 冬：雪覆亭台，红梅映雪，暖阁围炉，窗上霜花

**⑧ 空间深度描述（每个空间一句成画）**

- 正厅：正厅高阔，太师椅列两排，中堂字画，博古架陈古董，威严待客
- 花厅：花厅临园，四面轩窗，插花盆景，茶香袅袅，雅致品茗
- 绣楼：绣楼闺阁，纱幔珠帘，梳妆台铜镜，绣绷针线，深闺女红
- 水榭：水榭临波，三面临水，波光映顶，凭栏听雨，风送荷香

**⑨ 器物三档（按家底选）**

- 顶奢：金镶玉，螺钿镶嵌，点翠头面，缂丝袍，钧窑窑变
- 中奢：紫檀黄花梨，青花瓷，锦缎刺绣，官窑茶盏
- 日常：黄杨木，粗陶，棉麻，素瓷，家常烟火

**⑩ 人物神态（小姐/公子的情绪面）**

- 小姐：慵懒（倚窗支颐）、娇俏（团扇掩笑）、娴静（垂眸绣花）、落寞（凭栏望月）
- 公子：清冷（负手而立）、温润（执卷浅笑）、意气（挥毫题字）、沉稳（端坐品茶）

**⑪ 成品示范（+3，可直接复制）**

月夜小姐凭栏：月夜水榭，月光洒在青石阶上，雕窗透出暖黄烛火。小姐着月白绫罗襦裙凭栏而立，云鬓珠钗，目光望向荷塘月色，神情落寞，披帛被夜风轻轻扬起。85mm f/2.0，冷月暖烛双色温。

English: Moonlit waterside pavilion, moonlight on the stone steps, warm candlelight glowing through carved windows. A young lady in moon-white silk ruqun leans on the railing, pearl hairpin in her cloud-like hair, gazing at the moonlit lotus pond, a wistful look, her silk scarf lifted by the night breeze. 85mm f/2.0, cool moonlight and warm candlelight.

公子水榭抚琴：午后水榭，荷塘波光映上顶棚，风送荷香。公子锦袍玉带坐于古琴前，指尖拨弦，垂眸专注，几缕发丝垂落。窗外竹影婆娑，蝉鸣入画。85mm f/2.0，侧逆光，暖调。

English: Afternoon waterside pavilion, lotus pond ripples reflecting on the ceiling, breeze carrying lotus scent. A young master in brocade robe sits before a guqin, fingers plucking strings, eyes lowered in focus, a few strands of hair falling. Bamboo shadows sway outside. 85mm f/2.0, rim light, warm tone.

正厅家宴：黄昏正厅，宫灯次第亮起，纱幔透出暖光。长桌铺锦，杯盏列阵，主人与宾客端坐，仆役侍立两侧，菜肴热气升腾。青瓷花瓶插时令花，中堂字画庄重。35mm f/4，暖调烛光。

English: Dusk main hall, palace lanterns lighting up one by one, warm light through gauze curtains. A long table draped in brocade, cups set in rows, host and guests seated, servants standing by, steam rising from dishes. Celadon vases with seasonal flowers, solemn calligraphy scroll on the central wall. 35mm f/4, warm candlelight.

### 3.5.15 宋式田园劳作·乡居日常（X-Pem「中式美学」系列·图片/视频通用）

**① 宋式素雅色板（这套风格的核心红线）**

```
米白 + 橄榄绿 + 土褐（可扩展：黛绿/低饱和蓝灰/暖象牙白/浅鼠尾草色/浅灰/白瓷/茶褐色）
低饱和、通透、留白。
坚决不用鲜艳色——这是区别于普通古风图的核心。
```

**② 景别角度体系（劳作场景选镜）**

| 景别+角度 | 用法 |
|---|---|
| 广角平视 | 大场景劳作（晒场/麦田/茶山） |
| 广角高角度 | 俯瞰茶园/庭院/梯田层次 |
| 广角微仰角 | 藤架/棚下/树下仰视（瓜棚/豆架） |
| 中景全身平视 | 单动作主体（摘果/浇花/炒菜） |
| 3/4 背身全身 | 行走/晾衣/送食等背影叙事 |

**③ 母版复用工作流（固定句式·一致性核心）**

```
以参考图作为系列母版视觉参考，延续[面容+发型+服装+色调+景深]，
只改变[动作/景别/空间]。
生成16:9横幅、8K高清细节的[新画面描述]。
```

- 变体 1：只改动作——"只把原来的浇花全身镜头改为正面特写"（案例48）
- 变体 2：只改空间——"只改变动作与空间"（案例56）
- 用法：第一张图定母版，后续全系列改 1-2 个变量，人物/服装/色调自动锁定，比逐条重写稳定得多。

**④ 劳作动作词库（宋式农事/家务全套）**

| 劳作 | 动作写法要点 |
|---|---|
| 浇花 | 右手握壶柄左手托壶身，细水弧斜穿画面下沿，落进前景花丛 |
| 摘果/摘豆 | 拇指食指在果梗根部做明确摘取，另一手托篮于腰侧 |
| 送食 | 一手提带盖竹篮一手提陶壶，行走中衣带裙摆向后自然滞后 |
| 推磨 | 双手握水平木柄顺时针推，上身随圆弧产生可信用力与滞后 |
| 收割 | 左手拢麦秆右手短镰放秆根，草绳捆束，割秆整齐倒伏 |
| 洗菜 | 卷袖双手浸竹篮入水，水纹从手边扩散，菜叶水滴回落 |
| 炒菜 | 木铲翻铁锅，一手收宽袖避灶火，蒸汽向窗口飘散 |
| 采莲 | 左手稳荷梗右手旋转摘莲蓬，木篙窄长水纹，船边荷叶外偏 |
| 扬谷 | 双手分握长木耙朝己方向拉，耙齿留平行纹路，谷流见独立颗粒 |
| 采桑/采茶 | 指尖捏两片嫩叶，枝条轻微回弹，背篓固定于背 |
| 晾衣 | 抬双臂搭湿衣上竹竿，湿布半透明作层叠前景，衣边同向轻摆 |
| 茶叙 | 粗陶壶倒茶，一人接杯一人前倾笑谈一人倾听，茶汽上升 |

**⑤ 群像构图规则（2/3/4 人）**

- 双人：身体相互朝向 + 视线同落一处（瓜棚/石磨/溪畔/荷塘）；"四只手的归属与接触关系必须清楚，不要多手"
- 三人：形成不规则三角/近中远三个深度，动作与视线彼此独立（晒场/桑园）
- 四人：松散半圆/分布不同高度，各自朝向不同目标，"不要整齐看镜头"（茶叙/茶山）
- 通用：每个角色做自己的事，视线落在物件或同伴上，绝不同步看镜头。

**⑥ 双光源公式（宋式田园光影标配）**

```
[暖阳过滤光] 从左上/右上穿过树叶/窗格/藤蔓/湿布 → 勾亮脸、衣缘、物件边缘，投柔碎光斑
+ [天空冷色散射光] 大面积补亮面部与暗部 → 暗部保留纹理，人物通透不闷
```

写法示例："左上方树叶过滤的暖阳在脸颊和衣袖上投下柔碎叶影，天空散射光补亮阴影。"

**⑦ 劳作专项负面词（随案例反推）**

```
现代物件（水管/塑料盆/金属壶/衣夹/尼龙绳/塑料袋/机械/电动磨浆机/采茶机/收割机）、
工业场景（温室/水泥河岸/大棚/编织袋）、宫廷化（宫装/华丽首饰/繁复发饰/宫殿/艳色丝绸/浓妆）、
摆拍感（整齐摆拍/时尚走秀/统一制服/所有人物看镜头/排排坐）、
畸形（多余手指/多余手臂/裁掉双手）、文字与水印
```

### 3.5.16 宫廷大殿·巨物室内（贵族/宫阙/史诗感·高兴AIGC 系）

**① 巨物构图公式（人物与空间的比例定气势）**

| 人物占比 | 效果 | 写法 |
|---|---|---|
| 10% | 极致的渺小感/史诗压迫 | 人物仅占画面 10%，tiny human in monumental interior |
| 30% | 环境叙事主导 | 人物置于大殿一角，空间向深处延伸 |
| 50% | 人物与环境平衡 | 人物约占画面 50%，前景器物框景 |

**② 大殿要素词库（宏伟空间怎么堆）**

- 结构：极高穹顶 / 雕花木梁 / 金色立柱 / 空旷大殿地面 / 空间向画面深处延伸
- 装饰：整面墙的巨型古代山水画卷 / 长丝帛条幅 / 宫灯 / 层层纱幔
- 人物：精致银金发饰 / 刺绣汉服 / 巨大半透明丝绸飘带狂舞 / 层叠纱袖 / 金线纹样 / 玉佩
- 光：侧窗金色轮廓光 / 体积光尘埃光柱 / 深焦全画面清晰
- 风格标签：eastern imperial classical cinema style / 史诗电影感 / 戏剧性情感氛围

**③ 写实系宫廷/庭院人像通用块（抚琴/读书/赏画）**

- 服装：象牙白刺绣丝袍 + 精致传统纹样 + 飘逸广袖 + 真丝质感自然细褶
- 发饰：典雅古风发髻 + 玉簪 + 珍珠
- 肤质：通透柔粉肤色 + 自然透亮 + 细腻写实肤质 + 面部柔和高光
- 光：暖金逆光穿树枝 + 发丝边缘柔光 + 丝绸袖缘泛光 + 细碎光粒子浮动
- 镜头：85mm，ARRI Alexa 35，Kodak 胶片色彩，电影镜头光晕，非 CGI 金色时刻

**④ 设备锚点补充（电影机系）**

- ARRI Alexa 35 + Kodak 胶片色彩：宫廷史诗/古典电影机质感（替代佳能时用）
- Canon RF 50mm f/1.2：市集/纪实多人，大光圈自然散景
- 用法：同一画面可叠"85mm 镜头 + ARRI Alexa 35 + Kodak 胶片色彩"，摄影机与镜头分开写。

**⑤ 宫廷专项负面词（MJ 英文原词保留，出英文版直接附加）**

```
anime, cartoon, 3D render, CGI, game character, fantasy armor, western princess,
modern makeup, plastic skin, beauty filter, studio lighting, hard flash,
dramatic spotlight, oversaturated colors, cheap costume, fake jewelry,
artificial pose, perfect smile, unrealistic hands, extra fingers, modern objects
```

### 3.5.17 庭院文事·闺阁清趣（读书/对弈/品茗/插花·静态双人）

**① 双人文事位（静态共处——与动态双人配方互补）**

| 组合 | 写法 |
|---|---|
| 执扇·阅卷 | 她手持团扇轻摇微微侧首，她翻卷垂眸专注阅读 |
| 研磨·临帖 | 她执墨锭研墨，她提笔临帖，墨香氤氲 |
| 拨弦·听琴 | 她指尖拨弦，她静坐听琴，茶盏半温 |
| 插花·品茶 | 她修剪花枝入瓶，她捧盏观花，相视一笑 |

要点：各做各事、偶尔抬眼，零互动但气脉相连——"她的视线落在她翻开的书页上"。

**② 书斋陈设链（桌面铺陈三层）**

```
纸卷层（写字的纸页/卷轴/书册）+ 器物层（砚台/笔架/茶盏/团扇）+ 花枝层（插瓶+落瓣）
落瓣点睛：几片花瓣散落桌面与地面
```

**③ 花材速查（插瓶写法）**

| 花材 | 写法 |
|---|---|
| 牡丹 | 陶罐插一枝盛放粉牡丹，雍容之姿 |
| 海棠 | 晨光里海棠初绽，花瓣带露 |
| 玉兰 | 素白玉兰斜插青瓷瓶，高洁清冷 |
| 菊花 | 秋菊一束，黄白相间，萧疏有致 |

**④ 室内光（文事标配）**

```
午后木格窗漫射光 + 窗外绿树透景：室内清朗、窗外葱郁、明暗过渡不硬切，
桌面纸卷与花枝处留出柔和高光。
```

**⑤ 成品示范**

见案例 66（庭院文事·双姝阅卷）——中景平视、双人斜对、85mm f/2.0 午后漫射光。

---

## 四、人物造型与动作神态（维度·规范·动作·神态）

> 本章分三层：
> ① 造型（穿什么/长什么样）→ 速查表 + 三条规律
> ② 动作（做什么）→ 动作公式 + 雅词库
> ③ 神态（什么表情）→ 神态公式 + 雅词库
> 最后组合示范 + 心法收尾

### 写法公式

```
身份/年龄 + 服装款式与颜色 + 发型配饰 + 神态状态
```

### 古风题材造型速查

- 媒人：青绿色古装长袍，束发巾帽，双手捧礼，神态恭敬
- 新郎：正红喜袍，头戴乌纱帽插金花，胸前系红绸花
- 新娘：凤冠霞帔，盖红头纱，珠翠步摇
- 长辈：深色锦缎长袍，发髻簪银，眉眼慈祥
- 侍女/宾客：浅粉淡青襦裙，双丫髻，神情欢快
- 仙侠/天宫背身客：红粉渐变古装长裙 / 红黑渐变长袍 / 素白长袍，背身而立，衣袂随风飘动，不露正脸（尺度参照专用）
- 山间仙逸客：白纱长袍，半束发丝随风扬起，双手身前结印，衣袂翻飞（仙逸空灵）
- 贵妇/夫人：月白锦缎袍，缠枝莲纹软缎长裙，绣金莲软鞋，乌发高髻簪珠翠，神态雍容满足
- 侍女：浅青素罗襦裙，双丫髻，持团扇或端茶盏，低眉顺眼

### 3.5.19 镜头级成品案例库（首批 3 条·每条一个完整镜头卡，整镜直接抄）

> 和 3.5.10 的"场景句"不同：这里每条是一个**完整的可出片镜头**（景别+运镜+时长+完整 prompt），抄下来改题材字段即可。

**镜头卡 #01 · 宋式点茶（V2 清冷基调·雅）**

| 字段 | 值 |
|---|---|
| 景别 | 中景 → 手部特写 |
| 运镜 | 缓慢推镜（3s 起推，速度极慢） |
| 时长 | 10s |
| 画面 | 晨光茶室，竹帘筛光，粗陶壶白雾袅袅，女子着素青宋制襦裙执竹茶则候汤 |

```
V2 古风·清冷意境基调，水墨质感冷灰青绿调。晨光透过竹帘，在木案上切出平行光影条纹。女子素青宋制襦裙、云鬓半松簪白玉簪，执竹茶则候汤，垂眸凝神。案头粗陶壶白雾袅袅，茶雾由浓转淡，光斑从壶身滑至手背。中景缓慢推镜，推至手部特写。85mm 定焦，f/2.0，ISO 400，侧窗漫射光。
[负面词] 手部畸形, 六指, 五官错位, 现代物品穿帮, 低质量, 模糊, 文字乱码。
```
平台：豆包/可灵整段粘贴；10s 一段成片。

**镜头卡 #02 · 巨物天宫·仙子俯瞰（V1 庄重基调·奇）**

| 字段 | 值 |
|---|---|
| 景别 | 大远景 → 中景 |
| 运镜 | 超低机位仰拍，缓慢上升（自下而上，压迫感到舒展） |
| 时长 | 12s |
| 画面 | 云海之上天宫巨构，白衣仙子立于殿脊，俯瞰人间渺小 |

```
V1 古风·庄重仪式基调，暖调统一。云海翻涌，天宫重檐巨构耸入天际，尺度大到人物如尘埃。白衣仙子立于殿脊檐角，衣袂翻飞，手持青玉拂尘，俯瞰云下人间——山川如褶皱，城池如棋格。超低机位仰拍缓慢上升，人物在画面中占 8%，天穹留白 40%。35mm 广角，f/5.6，ISO 200，天光+云隙光，琥珀色温。
[负面词] 手部畸形, 模糊, 现代物品穿帮, 低质量, 比例失调。
```
平台：豆包/可灵整段粘贴；12s（H3 可延伸）。

**镜头卡 #03 · 高门千金·闺房晨妆（V2 清冷·贵）**

| 字段 | 值 |
|---|---|
| 景别 | 特写 → 中景 |
| 运镜 | 固定镜头，仅光斑微动 |
| 时长 | 8s |
| 画面 | 晨光窗棂菱格投影，千金对镜梳妆，螺钿妆奁半开 |

```
V2 古风·清冷意境基调。晨光透过菱花窗棂，在粉墙上印下整面菱形光格。女子藕荷绫罗襦裙坐于妆台前，执玉梳理云鬓，螺钿妆奁半开，铜镜映出侧脸。光斑在她肩头明明灭灭，金尘在光柱中浮动。特写固定镜头，只有光斑与金尘在动——人静光动。85mm 定焦，f/1.8，ISO 400，窗棂投影光，暖白调。
[负面词] 手部畸形, 五官错位, 过曝, 模糊, 现代物品穿帮, 文字乱码。
```
平台：豆包/可灵整段粘贴；8s。

**镜头卡 #04 · 市井烟火·早市炊烟（V1 暖调·俗）**

| 字段 | 值 |
|---|---|
| 景别 | 全景 → 中景 |
| 运镜 | 缓摇（从左至右，扫过摊位） |
| 时长 | 10s |
| 画面 | 晨雾未散，早市开张，蒸笼白汽升腾，货郎挑担穿行 |

```
V1 古风·庄重仪式基调，暖调统一。晨雾未散，青石板街早市初开，蒸笼白汽升腾，布幌招展，货郎挑担穿行，孩童追逐跑过。油纸伞影交错，炊烟与人流交织，晨光斜照摊位拉出长影。全景缓摇，从左至右扫过摊位，落幅停在一笼刚出屉的包子前。35mm 广角，f/4，ISO 400，晨光斜射+炊烟透光，暖白调。
[负面词] 手部畸形, 现代物品穿帮, 低质量, 模糊, 文字乱码。
```
平台：豆包/可灵整段粘贴；10s。

**镜头卡 #05 · 古风婚嫁·抬轿迎亲（V1 庄重·喜）**

| 字段 | 值 |
|---|---|
| 景别 | 中景 → 全景 |
| 运镜 | 横移跟随花轿（平行移动） |
| 时长 | 12s |
| 画面 | 八抬大轿穿巷，红绸漫天，孩童追轿撒喜钱 |

```
V1 古风·庄重仪式基调，暖调统一，朱红与金色主调。八抬大轿穿巷而过，轿身红绸结花，轿夫步伐齐整，孩童追轿撒喜钱，檐角红灯笼成串，炮仗碎红满地。中景横移跟随花轿，平行移动，落幅拉开为全景露出整条喜巷。50mm 定焦，f/2.8，ISO 320，晨光+灯笼暖光混合，喜庆暖调。
[负面词] 手部畸形, 五官错位, 现代物品穿帮, 低质量, 模糊, 文字乱码。
```
平台：豆包/可灵整段粘贴；12s。

**镜头卡 #06 · 侠女·竹林夜行（V2 清冷·飒）**

| 字段 | 值 |
|---|---|
| 景别 | 近景 → 大全景 |
| 运镜 | 跟拍后拉（先跟身形，再拉出竹林全貌） |
| 时长 | 10s |
| 画面 | 月下竹林，侠女提剑踏竹梢，衣袂猎猎 |

```
V2 古风·清冷意境基调，冷灰青绿调。月下竹林，雾霭低垂，侠女玄衣束发，提剑踏竹梢掠过，衣袂猎猎，剑穗在月光下泛冷蓝。竹影婆娑，光斑在脸上明灭。近景跟拍身形，随她跃起后拉为大全景，竹海如墨浪起伏。85mm 定焦，f/2.0，ISO 800，冷月天光+侧逆勾边，冷调。
[负面词] 手部畸形, 五官错位, 现代物品穿帮, 低质量, 模糊。
```
平台：豆包/可灵整段粘贴；10s。

**镜头卡 #07 · 巨物室内·宫殿烛火（V1 庄重·宏）**

| 字段 | 值 |
|---|---|
| 景别 | 大远景（人物极小） |
| 运镜 | 超低机位仰拍，缓慢推近殿内深处 |
| 时长 | 12s |
| 画面 | 巨殿高穹，千盏烛火如星河，一人立于殿心渺小如尘 |

```
V1 古风·庄重仪式基调，暖调统一。巨殿高穹，斗拱如林，千盏烛火次第点亮如星河垂落，殿心一人着红衣负手而立，渺小如尘埃。烛火摇曳，光晕在青砖地上铺成一片暖海。超低机位仰拍缓慢推近，人物始终在画面下方 1/5 处。24mm 广角，f/2.8，ISO 800，千烛暖光，暗部深邃。
[负面词] 手部畸形, 模糊, 现代物品穿帮, 低质量, 比例失调。
```
平台：豆包/可灵整段粘贴；12s。

**镜头卡 #08 · 庭院文事·雪夜读书（V2 清冷·静）**

| 字段 | 值 |
|---|---|
| 景别 | 全景 → 特写 |
| 运镜 | 缓慢推镜（从庭院全景推至书页） |
| 时长 | 12s |
| 画面 | 雪落无声，廊下灯笼微晃，书生拥裘夜读，呵气成霜 |

```
V2 古风·清冷意境基调，冷灰调。雪落无声，庭院覆白，廊下灯笼暖光微晃，雪片在光晕中纷飞。书生拥裘坐于窗下，呵气成霜，指尖翻动书页，页边在烛光中透薄。全景缓慢推镜，从雪庭推至书页特写，落幅停在翻页的指尖。50mm 定焦，f/2.0，ISO 800，冷雪天光+烛火暖点，冷暖对比。
[负面词] 手部畸形, 模糊, 现代物品穿帮, 低质量, 文字乱码。
```
平台：豆包/可灵整段粘贴；12s。

**镜头卡 #09 · 田园劳作·秋日晒谷（V1 暖调·安）**

| 字段 | 值 |
|---|---|
| 景别 | 中景 → 全景 |
| 运镜 | 低机位固定，仅谷粒扬起动态 |
| 时长 | 10s |
| 画面 | 秋阳下晒谷场，农妇扬谷，谷粒如金雨洒落 |

```
V1 古风·庄重仪式基调，暖调统一。秋阳斜照晒谷场，金黄谷粒铺满竹席，农妇着粗布短褐扬谷，谷粒如金雨般扬起洒落，尘埃在光柱中浮金。远处村落炊烟，老牛卧在树下。低机位固定镜头，主体动态靠谷粒扬落与光影流动。35mm 广角，f/4，ISO 200，秋日斜阳+谷尘透光，暖金调。
[负面词] 手部畸形, 现代物品穿帮, 低质量, 模糊。
```
平台：豆包/可灵整段粘贴；10s。

> 用法：换题材时按「30 秒替换原则」只改 [风格基调] + [场景/人物] 两处，运镜/参数/负面词原样保留。

### 3.5.20 节日习俗成品分镜库（春节贴春联/端午包粽子/中秋拜月·V4.0 材料入库）

> 完整分镜表（镜号/时长/景别/运镜/画面/文字卡/对白/声音），拿来即用；文字卡与对白全部后期叠加，不进生成 prompt。

**春节 · 贴春联（3 镜/15s）**——统一基调：V1 古风·庄重仪式 + 四感默认

| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 文字卡（后期） | 对白（后期） | 声音/BGM |
|---|---|---|---|---|---|---|---|
| 1 | 5s | 中景 | 固定 | 冬日清晨，老宅朱漆大门前，晨光斜照，红纸金墨铺在案上。老者着深色棉袍，手持毛笔蘸墨，在红纸上写福字，笔锋遒劲，墨迹未干。孩童红袄站一旁踮脚张望 | 总把新桃换旧符 | "爷爷，这个福字写得真好！" | 环境：晨间鸟鸣+远处零星鞭炮声；BGM：古琴轻快 |
| 2 | 5s | 近景 | 缓慢推镜 | 祖孙两人站门前贴春联。老者双手抚平上联，孩童踮脚递浆糊，仰头咧嘴笑，呼出白气。门框两侧已有新联，红纸金墨在晨光中发亮 | 新春——红纸金墨，福到万家 | "福到了！" | 环境：风声+衣料摩擦；BGM：琵琶+锣鼓轻点 |
| 3 | 5s | 全景 | 缓慢拉远 | 祖孙贴完春联，站门前相视而笑，门楣红纸在晨风中轻扬。镜头缓缓拉远，门框对联、灯笼、小院依次入画 | （无） | 新年大吉 | BGM：民乐合奏渐强收束+最后一声锣 |

成品 prompt 示例（镜头 1）：

```
V1 古风·庄重仪式基调。冬日清晨，老宅朱漆大门前，晨光斜照，案上红纸金墨铺展。老者着深色棉袍，手持毛笔蘸墨写福字，笔锋遒劲，墨迹未干。孩童着红袄站一旁踮脚张望，呼出白气。窗光侧逆，暖金调，光柱中金尘浮动。中景固定镜头，构图对称，前景毛笔与红纸清晰，背景老宅门框虚化。85mm，f/2.8，ISO 400。负面词：手部畸形，六指，五官错位，现代物品，低质量。
```

**端午 · 包粽子（4 镜/20s）**——统一基调：V2 古风·清冷意境 + 治愈感（宋式色调）

| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 文字卡（后期） | 对白（后期） | 声音/BGM |
|---|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 横移 | 河岸人家，薄雾水面，芦苇随风轻摆。老宅檐下挂艾草，门前石阶摆着泡好的糯米和粽叶，水盆映着天光 | 端午——艾草挂门，粽叶飘香 | "五月初五，包粽子咯！" | 环境：水流声+风声；BGM：古筝轻奏 |
| 2 | 5s | 近景 | 缓慢推镜 | 老妪坐竹椅，双手卷粽叶，糯米从指缝漏下落入盆中，动作麻利，青布围裙上沾着米粒，面容慈祥含笑 | 包粽——粽叶卷翠，糯米盈香 | "糯米要泡透才香。" | 环境：米粒落入盆中沙沙声；BGM：竹笛轻快 |
| 3 | 5s | 特写 | 固定 | 草绳捆扎粽子，绕三圈打结，绳端轻颤。棕叶在逆光中透出翠色纹理，水滴沿叶尖滑落 | 系粽——五色新丝缠角粽 | （无） | 环境：水滴声+草绳摩擦声；BGM：轻柔弦乐 |
| 4 | 5s | 全景 | 缓慢拉远 | 竹篮盛满新粽，蒸汽升腾，老宅灯笼暖光穿透水雾。镜头拉远，河岸炊烟袅袅，龙舟鼓声渐近 | （无） | 端午安康 | BGM：鼓点渐强+民乐收束 |

成品 prompt 示例（镜头 2）：

```
V2 古风·清冷意境基调。端午清晨，河岸老宅檐下，薄雾水面透进柔光。老妪坐竹椅，靛蓝布衫青布围裙，花白银发，面容慈祥。双手卷粽叶，糯米从指缝落入盆中，盆中米粒泛温润白，粽叶翠绿纹理清晰。晨光漫射，水汽氤氲，低反差。近景缓慢推镜，从双手推至面部。50mm，f/2.0，ISO 400，柔和晨光。负面词：手部畸形，六指，现代物品，低质量。
```

**中秋 · 拜月（4 镜/20s）**——统一基调：V1 古风·庄重仪式 + 四感默认

| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 文字卡（后期） | 对白（后期） | 声音/BGM |
|---|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 横移 | 庭院香案，月饼瓜果列阵，三炷线香青烟直上，月光铺满青石阶 | 中秋——设案焚香，以敬月神 | "今夜月明，敬天地一轮。" | 环境：蟋蟀声+风声；BGM：古琴缓起 |
| 2 | 5s | 中景 | 缓慢推镜 | 全家素装围案而立，长者拈香插炉，垂目肃立，香头明灭 | 拜月——焚香三炷，诚敬月神 | （无） | 环境：香炉轻响；BGM：古琴+箫 |
| 3 | 5s | 近景 | 固定 | 祖母切开月饼，刀刃切入酥皮，碎屑飘落，孩童眼巴巴盯着切面 | 分饼——一刀切开，圆满各半 | "给你最大那块。" | 环境：刀切酥皮声；BGM：琵琶轻奏 |
| 4 | 5s | 全景 | 缓慢拉远 | 月下庭院，全家围坐分食赏月，孩童举饼指月，画面渐暗，圆月悬空收束 | 千里共婵娟 | "今晚的月亮，真圆。" | BGM：民乐渐弱收束+余韵留白 |

**七夕 · 乞巧（8 镜/40s）**——统一基调：宋词诗意美学 · 东方生活美学（Flova 1.0 实测版 · V5.4 入库）

> 来源：Flova 1.0「剧本生视频」七夕乞巧短片实测（2026-09-07）。8 镜全流程：穿针乞巧→为牛庆生→吃巧果→晒衣晒书→接露水→喜蛛应巧→溪边吃瓜→溪中捕鱼。镜02-08 中英对照成品提示词见「二、东方生活美学配方」小节（可整段复制喂 MJ）。

| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 文字卡（后期） | 对白（后期） | 声音/BGM |
|---|---|---|---|---|---|---|---|
| 1 | 5s | 中景 | 固定 | 黄昏暮色透窗入青砖地，铜盆清水泛金光，三位素衣汉服女子围坐矮案，低眉穿针引线，银针在暮光中闪烁，窗外老槐树影婆娑、竹帘轻动 | 七夕乞巧 | "愿乞天孙巧。" | 环境：暮色虫鸣；BGM：古筝缓起 |
| 2 | 5s | 中近景 | 缓慢横移 | 夏日午后草地，黄牛悠然站立，牛角挂满野花与红绸随风轻摆，两位白衣女子笑着给牛角系牵牛花，身后白绸晾晒、云朵漂浮 | 为牛庆生 | "牛儿辛苦啦。" | 环境：蝉鸣+微风；BGM：竹笛轻快 |
| 3 | 5s | 近景 | 固定 | 老厨房油锅前，三位素衣麻布少女挽袖持木筷翻动油锅中的面坯，面坯膨胀变金黄成巧果，竹筛堆满新炸巧果冒着热气 | 巧果盈香 | "尝尝我的手艺！" | 环境：油锅滋啦声；BGM：琵琶轻奏 |
| 4 | 5s | 全景俯拍 | 缓慢拉远 | 晴朗庭院，三位白衣女子横拉绳索，晾晒半透明白绸、泛黄古籍与竹简，阳光下丝绸反出虹彩光泽，发间珠玉轻颤 | 晒衣晒书 | "晒书防潮咯。" | 环境：风声+衣料飘动；BGM：古琴舒展 |
| 5 | 5s | 近景 | 固定 | 清晨花丛，晨露在草叶上如碎钻闪光，一位淡绿短襦女子蹲身，右手指尖轻触叶面接住露珠，闭眼将露珠轻点眼睑与手背 | 接露明目 | "乞得一双巧手明眸。" | 环境：晨鸟轻鸣；BGM：箫声空灵 |
| 6 | 5s | 中景 | 固定 | 盛夏槐树下浅溪，三位素白丝绸女子蹲在水中嬉戏，发簪在阳光下闪亮，水面波光粼粼，溪底卵石清晰可见 | 喜蛛应巧 | "看，喜蛛结网了！" | 环境：溪水声；BGM：民乐轻快 |
| 7 | 5s | 近景 | 轻微跟拍 | 同一棵槐树下溪水，女子蹲在水中嬉戏吃西瓜，笑声不断，水花溅起，阳光下裙衫泛金光 | 溪边纳凉 | "这瓜真甜！" | 环境：水流+蝉鸣；BGM：琵琶+打击轻点 |
| 8 | 5s | 近景 | 固定 | 河边浅水，三位素衣女子蹲溪中徒手捕鱼，鱼跃出水面溅起水花，蓝天白云为背景，金光洒在衣上 | 溪中捕鱼 | "抓到了！" | 环境：水声+笑声；BGM：民乐合奏收束 |

成品 prompt 示例（镜头 1·Flova 原版中文）：

```
本作根据东方传统古典美学，通篇采用宋词诗意美学基调。温润柔和的黄昏暮色，透过古旧木格窗棂斜洒入青砖地面，铜盆中清水泛着细碎金光，几缕五色丝线在指间微微颤动。三位素衣汉服女子围坐于矮案前，低眉凝神，银针在暮光中闪烁，她们正以最虔诚的姿态乞求织女赋予一双巧手。窗外老槐树影婆娑，微风拂动竹帘，光影斑驳摇曳。画面缓缓避开宏大叙事，聚焦于女子鬓角碎发被逆光染成暖白色的细腻瞬间，侧逆光勾勒出纤长睫毛与柔和下颌线，前景虚化半卷的竹帘与木棂，营造出朦胧通透、富有人文乡愁的浪漫氛围。整体色调温暖沉静，如宋人小品画般含蓄内敛，完美复刻江南传统农耕社会黄昏时分日常烟火气息。
```

> 其余 7 镜中英对照成品提示词 → 「二、东方生活美学配方」小节（每段中文+英文，带 --ar 16:9 --stylize 200 --raw --v 8.2，中文喂豆包系/英文喂 MJ，整段复制即可）。

### 古风妆发大全（写女子/美人高频需求·发型×眉式×妆×首饰）

**发型（由少到熟）**

```
少女：垂髫 / 双丫髻 / 双环髻 / 垂挂髻
青年：单螺髻 / 双螺髻 / 高髻 / 云鬓 / 百合髻 / 堕马髻（慵懒）/ 飞仙髻（仙气）
男式：束发高马尾 / 半束发（一半散落）/ 发髻插簪 / 布帛裹发
```

**眉式**

```
远山黛（淡远）/ 柳叶眉（细弯）/ 一字眉（端庄）/ 秋娘眉（古典）/ 剑眉（英气）
```

**眼唇面妆**

```
眼：桃花眼妆（粉晕）/ 丹凤眼（细长）/ 杏眼（圆润）
唇：点绛唇（小唇珠）/ 樱桃唇 / 檀唇（淡红）
面：花钿眉心（朱红/金箔）/ 斜红（面颊弯月）/ 面靥（酒窝点）/ 额黄
```

**首饰**

```
发饰：玉簪 / 银簪 / 木簪 / 步摇 / 花胜 / 金钿 / 珠花 / 绢花
项耳：璎珞 / 耳铛 / 坠子
手足：臂钏 / 指环 / 玉镯
```

**用法公式**：`发型 + 眉式 + 唇妆 + 面妆 + 首饰`，一句话拼进人物造型段。
示例：云鬓高髻簪步摇，远山黛眉，点绛唇，眉心朱红花钿，耳坠明月珰。

### 面部特征词库（脸型/眼/眉/鼻/唇·写"长什么样"）

> 用法公式：`脸型 + 眼型 + 眼神 + 眉式 + 鼻 + 唇`，一句话拼进人物造型段。

**脸型**

```
鹅蛋脸（古典标准）/ 瓜子脸（精致）/ 圆脸（幼态可爱）/ 方脸（端庄英气）/ 长脸（清冷）/ 心形脸（甜美）
```

**眼型（决定气质七成）**

```
杏眼（圆润清亮·甜）/ 丹凤眼（细长上挑·英气）/ 桃花眼（眼尾微翘·含情）/
柳叶眼（细长温柔）/ 瑞凤眼（深邃有神）/ 睡凤眼（慵懒疏离）/ 狐狸眼（妩媚勾人）/
垂眼（温顺无辜）/ 圆眼（无辜幼态）
眼特征：卧蚕 / 平行双眼皮 / 开扇双眼皮 / 长睫毛 / 眼尾上挑 / 眼尾下垂
```

**眼神（情绪入口）**

```
目光清亮 / 眼波流转 / 含情脉脉 / 睥睨冷淡 / 低垂敛目 / 顾盼生辉 /
目光如炬 / 眼神疏离 / 眸光微润 / 眼底含笑
```

**眉毛**

```
远山黛（淡远）/ 柳叶眉（细弯）/ 一字眉（端庄）/ 秋娘眉（古典）/ 剑眉（英气）/
新月眉（柔美）/ 挑眉（凌厉）/ 烟眉（朦胧）/ 蹙眉（含愁）
```

**鼻子**

```
琼鼻（精致）/ 鼻梁挺拔 / 小巧鼻头 / 微翘鼻尖 / 鼻翼秀气
```

**嘴唇**

```
樱桃小口 / 点绛唇（小唇珠）/ 丰唇（妩媚）/ 薄唇（清冷）/ 唇珠分明 /
嘴角微扬（似笑非笑）/ 抿唇（隐忍）/ 唇色淡白（病弱）
```

**整体面容词（一句收尾）**

```
肤若凝脂 / 面若桃花 / 吹弹可破 / 眉眼如画 / 朱唇皓齿 / 面白如玉 / 气色苍白
```

**气质速配表（要什么气质直接抄组合）**

| 气质 | 面部组合 |
|---|---|
| 清纯甜 | 圆脸 + 杏眼 + 卧蚕 + 柳叶眉 + 樱桃小口 |
| 高冷御姐 | 瓜子脸 + 丹凤眼微挑 + 挑眉 + 薄唇 + 眼神疏离 |
| 妩媚妖女 | 鹅蛋脸 + 狐狸眼/桃花眼 + 眼尾上挑 + 丰唇 + 眼波流转 |
| 英气侠女 | 鹅蛋脸或方脸 + 丹凤眼 + 剑眉 + 抿唇 + 目光如炬 |
| 温婉闺秀 | 鹅蛋脸 + 柳叶眼 + 低垂敛目 + 远山黛 + 点绛唇 |
| 病弱美人 | 长脸或瓜子脸 + 垂眼 + 蹙眉 + 唇色淡白 + 面白如玉 |
| 书卷才女 | 鹅蛋脸 + 瑞凤眼 + 目光清亮 + 一字眉 + 唇珠分明 |

**完整示例**：鹅蛋脸，杏眼含春，眼波流转，远山黛眉，琼鼻小巧，樱桃小口点绛唇，肤若凝脂。

### 身材体态词库（身形/局部/体态·雅词写法）

> 用法公式：`身形 + 局部（肩颈/腰/臂/手）+ 体态动作`，一句拼进人物造型段。身材一律用雅词，不写直白部位词。

**身形骨架**

```
纤细：身量纤细 / 弱柳扶风 / 瘦削轻盈 / 清癯
匀称：纤秾合度 / 体态匀称 / 亭亭玉立 / 娉婷袅娜
丰腴：体态丰盈 / 秾纤得衷 / 珠圆玉润 / 丰腴有致
高挑：身姿高挑 / 玉立亭亭 / 腿长曳裙
```

**局部体态**

```
肩颈：削肩 / 直角肩 / 锁骨分明 / 天鹅颈 / 颈线修长
腰肢：纤腰一握 / 杨柳细腰 / 腰肢如柳 / 束腰盈盈
曲线：曲线玲珑 / 身段婀娜 / 丰盈曲线（大）/ 体态轻盈（小）
手臂：藕臂 / 皓腕 / 玉臂凝霜
手：纤纤素手 / 十指青葱 / 指若削葱根
腿足：腿线修长 / 莲足 / 赤足踏波 / 步履生莲
```

**体态动作（站坐行）**

```
站：亭亭玉立 / 娉婷而立 / 站姿端雅 / 斜倚凭栏
坐：端坐 / 跪坐 / 斜倚凭几 / 侧身而坐
行：莲步轻移 / 步履生风 / 裙裾曳地 / 回身顾盼
```

**气质速配（要什么抄什么）**

| 气质 | 身材组合 |
|---|---|
| 清纯少女 | 身量纤细轻盈 + 削肩 + 莲步轻移 |
| 御姐/妖女 | 曲线玲珑 + 纤腰一握 + 慵懒斜倚 |
| 侠女/女将 | 高挑劲瘦 + 体态利落 + 步履生风 |
| 贵妇/贵女 | 体态丰盈 + 珠圆玉润 + 仪态端方 |
| 病弱美人 | 清癯瘦削 + 弱柳扶风 + 扶栏缓行 |
| 舞姬 | 身段婀娜 + 杨柳细腰 + 旋身如水 |

**完整示例**：身量纤细，杨柳细腰，削肩锁骨分明，天鹅颈，皓腕纤手，莲步轻移，裙裾曳地。

### 年龄锚点（不写年龄=气质漂移·写在主体最前）

> 为什么加：AIGC 不写年龄默认画 20-40 的模糊值，少女会显老、御姐会显幼。写死年龄 = 锁死气质。
> 写法：年龄词放在第 2 步「主体」最前；双语交付时中英各带一个年龄锚点句。

**古风年龄词（中文）**

```
垂髫/总角（5-8 童女）：胖乎乎，总角双丫，天真烂漫
及笄之年（13-15 少女）：眉眼尚稚，含苞待放
碧玉年华（16-18）：青春明丽
桃李年华（20 出头）：盛年之美
花信年华（24 上下）：成熟初显
风韵之年（30-40）：丰韵犹存，仪态端方
暮年（50+）：华发初生 / 苍颜鹤发
```

**英文锚点句（喂英文工具）**

```
teenage girl around 15-17 / a young woman around 18-19 /
early twenties, around 20-23 / a woman in her late twenties /
a mature woman in her 30s / an elderly woman in her 60s
```

**年龄 × 气质速配**

| 气质 | 年龄 |
|---|---|
| 清纯甜 / 娇憨萝莉 | 及笄-碧玉（15-18） |
| 活泼少女 / 邻家少女 | 碧玉（16-18） |
| 侠女 / 飒爽女将 | 桃李（20-25） |
| 高冷御姐 / 风情御姐 | 花信（24-28） |
| 贵妇 / 贵女 | 风韵（30-38） |
| 仙翁 / 老妪 / 长者 | 暮年（60+） |

**完整示例**：碧玉年华的少女（a young woman around 17-18），鹅蛋脸，杏眼含春……（其余照常拼）

### 人物角色卡库（不同人物 = 完整 prompt 骨架·含动作/道具/神态）

> 每个角色卡 = 一句话骨架，直接替换进「十四步详装」第 2/3/4 步即可。人物必须"有事做、有道具、有神态"，禁止只立个剪影。

**1. 富家千金（闺房）**
云鬓高髻簪珠翠步摇，藕荷襦裙披帛曳地，**执团扇半掩面，倚窗听雨**，膝边绣绷与花剪，眉眼含慵。场景：闺房轩窗、纱帘透光。道具：团扇/绣绷/花剪。

**2. 世家公子（庭院）**
束发玉冠，月白直裰腰系玉佩，**执书卷立于花树下，另一手负背，衣角被风掀起**。场景：庭院/廊下/海棠花影。道具：书卷/折扇/玉佩。

**3. 侠女（江湖）**
高马尾束发，玄色劲装束腰，斗笠斜背，**一手按剑柄，一手持酒囊，回眸间衣袂猎猎**。场景：竹林/山道/客栈屋顶。道具：剑/酒囊/斗笠。

**4. 剑客（客栈）**
半束发，玄青长袍，长剑斜挎，**坐于酒肆一角，指节轻叩桌面，剑穗垂落**，眼神疏离。场景：江湖客栈、油灯昏黄。道具：剑/酒碗/斗笠。

**5. 渔娘（水乡）**
青布包头，短褐束袖，竹斗笠挂背，**蹲于船头理网**，船尾鱼篓半满，水光潋滟。场景：水乡/芦苇荡/乌篷船。道具：渔网/鱼篓/竹篙。

**6. 采莲女（荷塘）**
双丫髻簪野花，浅碧短襦配月白裙，**蹲坐舟中，一手拨开莲叶，一手摘莲蓬**，船头堆新藕。场景：荷塘/菱歌/水波。道具：莲蓬/竹篮/木舟。

**7. 茶娘（茶寮）**
半束黑发，青灰襦裙，**跪坐茶席前，执壶高冲，另一手按盏**，蒸汽与茶烟共升。场景：茶寮/山亭/竹帘。道具：执壶/茶盏/竹茶则。

**8. 琴师（高阁）**
高髻簪玉，素衣广袖，**盘坐琴案前，十指按弦**，琴身桐木泛光，案头香炉青烟。场景：庭院/高阁/月下。道具：古琴/香炉。

**9. 舞姬（宴厅）**
云髻金步摇，石榴红襦裙长袖，**水袖甩作弧线，裙袂旋起，足尖点地**。场景：宴厅/月下庭院。道具：水袖/团扇/小鼓。

**10. 农妇（晒场）**
布巾包头，靛蓝粗布短衣，**弯腰在晒场翻谷**，身旁竹耙与谷筐，远处草垛与鸡群。场景：晒场/田埂/秋日。道具：竹耙/谷筐/扁担。

**11. 书生（石桥）**
束发布巾，青衫直裰，**斜倚桥栏读书，纸伞倚在脚边**，柳丝拂过书页。场景：石桥/溪畔/细雨。道具：书卷/纸伞。

**12. 仙翁/道士（云崖）**
白发道髻，灰白道袍，**执拂尘立于崖边，腰间葫芦**，云雾绕足。场景：云崖/丹房/松林。道具：拂尘/葫芦。

**13. 将军（城头）**
玄甲红缨，束发金冠，**拄长枪立于城头，披风猎猎**，身后烽火与旌旗。场景：城楼/战场余晖。道具：长枪/佩刀/旌旗。

**14. 绣娘（窗下）**
半束黑发簪银，月白窄袖衫，**坐于窗下绷前飞针走线**，绣绷绷着未完的牡丹，针线笸箩在手边。场景：闺房窗下/午后光。道具：绣绷/银针/线笸箩。

> 用法：写任意人物 → 抄对应骨架句 → 套 14 步 → 第 3 步按角色补场景元素（人群/动物/陈设），第 4 步把道具写细（材质+光效）。

### 仙子与绝美女子角色卡（高频·好看优先·飘逸长裙系）

> 穿飘逸长裙的不一定是仙子——舞姬、花魁、妖女、鬼新娘也穿。按气质选卡，裙子写法看下方视觉词库。

**15. 花神/司花仙子**：云髻簪四季花，**纱裙缀满落花，执一枝桃花**，立于花雨之中，披帛缠臂如云。场景：桃林/花海。道具：花枝/花篮。

**16. 月宫仙子（嫦娥系）**：月白广袖长裙拖尾，**抱玉兔立于桂树下**，银辉洒身，裙裾泛冷光。场景：广寒宫/月下丹墀。道具：玉兔/桂枝。

**17. 洛神/水神**：青碧鲛绡长裙曳水，**凌波而立，赤足踏于水面，披帛随水纹飘展**，水珠悬空如珠。场景：洛水/溪涧。道具：无/水波。

**18. 飞天**：彩裙飘带翻飞，**半悬空中，一手托莲，丝带绕臂如流云**。场景：祥云/石窟穹顶。道具：莲花/琵琶。

**19. 织女/云锦仙**：霞色纱裙层叠如云锦，**执金梭立于织机前，锦帛自指间流泻**。场景：云上织坊/霞光。道具：金梭/锦帛。

**20. 雪神/霜仙**：素白曳地长裙，**立于飞雪中，指尖捻一片雪花**，呵气成霜，裙裾结霜晶。场景：雪原/寒潭。道具：雪花/冰晶。

**21. 宫廷舞姬（长裙系）**：金步摇垂珠，**绛纱长裙旋作圆，水袖如浪**，裙摆扫过地面。场景：宴殿/月台。道具：水袖/鼓。

**22. 仕女/贵女（出游）**：高髻簪花，**襦裙披帛曳地，执团扇缓步**，裙摆拂过青石。场景：园林/曲径。道具：团扇/披帛。

**23. 花魁**：华服重彩，**斜倚凭栏，指尖夹一朵绢花**，纱裙半曳，慵懒抬眼。场景：画舫/楼阁。道具：绢花/纨扇。

**24. 狐妖/妖女**：红衣曳地，**赤足踏风而行，发丝与裙裾齐齐飘飞**，回眸间眉眼含媚。场景：月下荒宅/山野。道具：狐尾若隐/灯笼。

**25. 鬼新娘**：大红嫁衣曳地，**立于雾中，手持红盖头，裙裾无风自动**，面色苍白。场景：旧宅/纸灯。道具：红盖头/喜帕。

**26. 飘渺仙（无名氏）**：白衣广袖，**立于山巅，裙裾翻飞如云，发丝与披帛同扬**，背身或侧颜。场景：云海/绝壁。道具：无/剑。

**飘逸长裙视觉词库（裙子怎么写才好看）**

```
裙型：曳地三尺 / 拖尾如流水 / 层叠百迭 / 纱裙朦胧 / 裙裾生风 / 旋起如花
材质：鲛绡 / 云纱 / 蝉翼纱 / 软烟罗 / 织金纱 / 月华纱
披帛飘带：披帛如烟 / 飘带翻飞 / 丝带缠绕臂间 / 长帛曳地
动态：风起裙扬 / 凌波微步 / 飘然欲仙 / 衣袂猎猎 / 裙裾拂水
光效：逆光透纱 / 裙缘镀金 / 金尘随裙动 / 月华洒纱
```

**组合公式**：`裙型 + 材质 + 披帛/飘带 + 动态 + 光效` → 曳地三尺的月华纱长裙，披帛如烟，风起裙扬，逆光下纱缘镀金。

### 更多人物角色卡（27-40·补全各阶层/职业）

**27. 帝王**：冕旒垂珠，玄衣纁裳绣日月，**端坐龙椅，一手执玉圭，一手按膝**，不怒自威。场景：金殿/丹墀。道具：玉圭/冕旒。

**28. 官员/宰相**：乌纱帽，圆领官袍束革带，**执笏板躬身或负手立于廊下**，眉目沉静。场景：衙署/朝廊。道具：笏板/官印。

**29. 公主/郡主**：高髻缀珠翠，宫装繁复披帛曳地，**执花枝或团扇立于园中，回眸浅笑**。场景：御苑/宫廊。道具：花枝/团扇。

**30. 宫女**：浅色宫装，双丫髻，**提纱灯缓行，或执拂尘立于殿侧**，低眉顺目。场景：宫廊/殿角。道具：纱灯/拂尘。

**31. 医女**：青布药囊斜挎，素色窄袖，**跪坐榻前为老者诊脉**，指尖按腕，神情专注。场景：药庐/病榻。道具：药囊/银针/药杵。

**32. 画师/丹青客**：半束发，青衫沾墨痕，**立于画案前执笔点染，另一手扶纸**。场景：画室/山亭。道具：画笔/画卷/砚台。

**33. 说书人**：青布长衫，**坐于茶楼高台，醒木一拍，折扇指天**，眉飞色舞。场景：茶楼/市集。道具：醒木/折扇/茶碗。

**34. 伶人**：戏装水袖，粉面勾眉，**甩袖亮相，眼神顾盼生辉**。场景：戏台/后场。道具：水袖/珠冠/折扇。

**35. 女冠/道姑**：青灰道袍，道髻插木簪，**执拂尘立于丹房前，另一手托药葫芦**。场景：道观/丹房。道具：拂尘/葫芦/经卷。

**36. 猎户**：兽皮坎肩，**背弓持叉行于山道，腰间挂野味与箭囊**。场景：山林/雪径。道具：弓/叉/箭囊。

**37. 商贾/掌柜**：圆领绸袍戴员外巾，**立于柜台后拨算盘，或袖手看伙计**，笑意精明。场景：铺面/码头。道具：算盘/账册/茶盏。

**38. 船娘/渡娘**：青布包头，短打束腰，**撑长篙立于船尾，另一手摇橹**，歌声随水。场景：渡口/江面。道具：竹篙/橹/斗笠。

**39. 更夫**：灰布短衣，**提灯笼敲梆子走过夜巷**，身后拖长影，梆声笃笃。场景：夜巷/更楼。道具：灯笼/梆子。

**40. 刺客**：玄色夜行衣，黑巾蒙面，**蹲伏屋脊，一手按刃，目光如隼**。场景：月夜屋脊/深宅。道具：短刃/飞镖/绳索。

**41. 垂髫童**：总角垂髫，红肚兜小褂，**骑竹马跑过巷口，咯咯笑着回望**。场景：巷口/庭院/田间。道具：竹马/拨浪鼓。

**42. 总角小童**：双髻扎红绳，短褐小袄，**蹲在阶前斗蛐蛐，或追蝶扑萤**。场景：庭院/田埂。道具：蛐蛐罐/小网。

**43. 提灯小儿**：团花小袄，**双手提兔儿灯走在前头，光映圆脸，脚步雀跃**。场景：元宵灯市/夜巷。道具：兔儿灯/糖葫芦。

**44. 纸鸢童**：短衫束发，**仰头扯线奔跑放纸鸢，衣摆扬起，笑声清亮**。场景：春郊/河堤。道具：纸鸢/线拐。

**45. 捧书学童**：青布小袍，**背手捧书卷边走边诵，摇头晃脑，夫子在前**。场景：学堂廊下/书院。道具：书卷/砚台。

**46. 暮年老翁**：灰白长须，粗布袍拄竹杖，**立于村口望归路，或倚门晒太阳**，眉眼慈和。场景：村口/檐下。道具：竹杖/烟袋。

**47. 拄杖老妪**：银发盘髻，靛蓝布衫，**拄杖立门前张望，另一手拢袖**。场景：门前/井台。道具：拐杖/竹篮。

**48. 抚须祖父**：白须垂胸，鹤发，**坐藤椅抚须含笑，看孙辈嬉闹**。场景：庭院/堂屋。道具：藤椅/茶盏。

**49. 纺线老妪**：苍老面容，粗布包头，**坐纺车前摇轮纺线，线轴悠悠转**。场景：窗下/灶房边。道具：纺车/线轴。

**50. 雪中老者**：披蓑戴笠，白须上挂霜，**拄杖立于雪径，回望来路，呵气成雾**。场景：雪径/桥头。道具：蓑笠/竹杖。

### 4.0.1 人设锚点公式（写人先写根·四章第 0 步）

> 七件套写的是"外显"；人设锚点写的是"这个人是谁、从哪来、此刻什么处境"——气质/表情/动作的根。写任何人物前，先用 4 字段锁死底层，再套七件套。

```
出身/阶层 + 此刻处境 + 核心欲望/恐惧 + 关键关系人
```

| 字段 | 作用 | 示例 |
|---|---|---|
| 出身/阶层 | 决定气质档位（隐忍/端方/野性/矜贵） | 北地逃难来的孤女 → 气质卡在「隐忍」档 |
| 此刻处境 | 决定动作速度与神态基调 | 正逃往江南投奔舅舅的路上 → 走路带急、四下张望 |
| 核心欲望/恐惧 | 决定眼神与微动作 | 她想活下去、不想被送回那户人家 → 眼神警觉、闻声即惊 |
| 关键关系人 | 决定双人写法（谁在场/与谁相关） | 跟着奶娘一路讨饭才到京城 → 双人：奶娘护持、她紧牵衣角 |

用法：七件套填「气质」时，从人设锚点推导，不凭空选——同样"低眉垂眼"，锚点是"温顺"写低眉浅笑，锚点是"警觉"写低眉时目光上挑、闻声即顿。

### 女子气质人设卡（按气质选·可盐可甜·甜/盐/冷/飒/媚/怜六档）

> 与"身份卡/仙子卡"互补：身份卡回答"她是谁"，气质卡回答"她什么味道"。同一身份可换气质重写。
> 速选：**甜**＝清纯/活泼/娇憨/邻家；**盐**＝飒爽女将/高冷御姐；**冷**＝清冷贵女；**飒**＝英气女将；**媚**＝风情御姐；**怜**＝病弱美人；**谜**＝神秘女子。

**51. 清纯少女（甜）**：杏眼圆润，双髻簪野花，浅粉襦裙，**捧花小跑，笑露梨涡**，裙角扬起。场景：春日花田/溪畔。道具：花束/竹篮。

**52. 活泼少女（甜辣）**：双丫髻系红绳，鹅黄短襦，**追蝶扑蝶，裙裾旋起，咯咯笑出声**。场景：庭院/草地。道具：扑蝶网/彩蝶。

**53. 娇憨萝莉（呆萌）**：圆脸婴儿肥，总角双丫，**蹲地逗猫，歪头嘟嘴**，袖口蹭灰。场景：廊下/石阶。道具：小猫/糖葫芦。

**54. 邻家少女（烟火）**：粗布青裙，乌发单辫，**挎竹篮买鱼回来，眉眼弯弯与摊贩说笑**。场景：市集/巷口。道具：竹篮/鱼/油纸伞。

**55. 温婉闺秀（柔）**：远山黛眉，低眉浅笑，**坐于窗下绣花或研墨**，动作轻缓。场景：闺房/庭廊。道具：绣绷/砚台。

**56. 文静才女（书卷气）**：素衣束发簪银，**执卷立于竹下，目光清亮，风吹页动**。场景：书斋/竹林。道具：书卷/竹简。

**57. 清冷贵女（冷）**：云髻珠翠，面色如雪，**立于廊下望月，不与人言**，周身疏离。场景：高楼/月下庭院。道具：团扇/貂裘。

**58. 高冷御姐（盐）**：凤眼微挑，胭脂薄施，玄衣曳地，**抱臂倚柱，睥睨来客，唇角一丝似笑非笑**。场景：楼阁/画舫。道具：纨扇/长剑。

**59. 风情御姐（媚）**：桃花眼，云髻金步摇，红裙曳地，**执扇半遮面，眼波流转，一步三摇**。场景：花楼/夜宴。道具：纨扇/绢花。

**60. 飒爽女将（飒）**：剑眉星目，束发银冠，玄甲红缨，**拄长枪立于旗下，披风猎猎，目光如炬**。场景：城头/演武场。道具：长枪/令旗。

**61. 病弱美人（怜）**：苍白薄唇，素衣单薄，**倚窗捧药，轻咳两声，指尖按帕**，弱柳扶风。场景：病榻/窗前。道具：药碗/绢帕。

**62. 神秘女子（谜）**：墨纱覆面，黑衣曳地，**立于雾中回眸，半面若隐若现**，无声无息。场景：雾林/古宅。道具：面纱/灯笼。

> 可盐可甜写法：同一人给两版基调词——甜版「眉眼弯弯、笑意盈盈、浅粉鹅黄」；盐版「眉眼清冽、神色疏淡、玄青冷白」；其余结构不变。

### 现代题材造型速查

| 题材 | 人物造型 |
|---|---|
| 堵门 | 伴娘团浅粉香槟色纱裙、精致妆容、珍珠发饰；新娘白纱头纱；新郎深色西装胸花，笑得发愁 |
| 敬茶改口 | 新娘中式敬酒服（正红）盘发簪珠；新郎深灰西装；长辈深色正装，眉眼慈祥 |
| 婚礼宣誓 | 新娘白色婚纱、头纱、手捧花；新郎黑色礼服领结；宾客浅色系着装 |
| 抛捧花 | 新娘婚纱背身；伴娘同色系纱裙站成半圆，伸臂雀跃 |
| 手冲咖啡 | 白衬衫挽袖、皮质围裙，短发利落，专注注视水流 |
| 早八通勤 | 衬衫/卫衣配背包耳机，妆容淡但唇色提气，神色微倦 |
| 深夜泡面 | 宽松 T 恤睡裤拖鞋，头发微乱，一脸放松满足 |
| 奶茶加料 | 店员棒球帽+同色围裙动作利落；顾客潮牌卫衣，眼巴巴等吸管 |
| 露营 | 冲锋衣+渔夫帽+露营灯挂饰，素颜自然，围着炉火搓手 |
| 演唱会 | 应援服+发光发箍+荧光棒，满脸激动跟唱 |
| 吸猫 | oversize 家居服蜷坐沙发，眼神温柔，伸手轻挠 |
| 客制化键盘 | 电竞卫衣+头戴耳机，指尖轻落，神情专注 |
| 新机开箱 | 居家 T 恤，期待搓手，眼睛发亮盯住包装 |
| 朋友圈九宫格 | oversize 穿搭+墨镜，构图选图一本正经 |
| 游戏五杀 | 电竞椅、RGB 灯、耳机，五杀瞬间拍桌跳起 |
| 跨年倒计时 | 羽绒服+围巾+毛线帽，与朋友/恋人相拥倒数 |


> 配套文件：`逐镜头人物造型拆解.csv`（16 环节造型总表）

### 1. 三条核心规律

**规律一：服色即身份，不用文字交代人物**
主角＝正红 ｜ 长辈＝深色锦缎 ｜ 少女＝浅粉浅青 ｜ 随从＝素色。
给每类人物固定色系，观众一眼区分地位——这就是"颜色叙事"。

**规律二：造型随剧情阶段升级（女主造型线是明线）**
婚前：浅色少女装 + 银发饰 → 插钗得金钗（定亲信号）→ 婚中：红嫁衣 + 红盖头 → 合卺露出全片最华贵的珠翠步摇。
男主同理：浅白长衫 → 正红婚服。写长片时让主角"换装"跟剧情走，观众能感知时间推进。

**规律三：每个镜头的人物都带"神态动词"，不写静止的"站着"**
一个神态动词 + 一个手部/身体动作，人物就活了。这是原片提示词里最值钱的部分。

### 2. 神态动词库（别写"站着/坐着/看着"）

| 类别 | 可用词 |
|---|---|
| 女子 | 回眸含笑 / 含羞端坐 / 垂首静立 / 俯身叩拜 / 拈帕掩口 / 侧身探看 / 指尖抚钗 / 盈盈欠身 / 低眉垂眼 / 掩面而笑 |
| 男子 | 躬身奉礼 / 拱手作揖 / 背手踱步 / 正襟危坐 / 执缰勒马 / 含笑抱拳 / 颔首致意 / 昂首挺立 |
| 长辈 | 端坐肃穆 / 慈眉含笑 / 亲手簪钗 / 递盏颔首 / 抚须点头 |
| 孩童 | 伸臂争抢 / 踮脚张望 / 拍手欢呼 / 追逐嬉闹 |
| 群像 | 围坐举杯 / 驻足围观 / 交头接耳 / 鼓掌起哄 / 侧耳倾听 |

### 3. 人物造型写作公式 + 模板（可复制）

**公式（人物七件套·V3.56 起）**：
`年龄锚点 + 面部（脸型/眼/眉/鼻/唇）+ 妆发（发型/妆容/首饰）+ 身材（身形/曲线/体态）+ 服装（三段式分层）+ 动作·道具·神态 + 气质词`

**标准模板**：
```
年龄：〔古风年龄词 + 英文锚点句〕
面部：〔脸型 + 眼型 + 眼神 + 眉式 + 鼻 + 唇〕
妆发：〔发型 + 妆容 + 首饰〕
身材：〔身形 + 局部曲线 + 体态〕
服装：〔外罩/下着/脚踩，或上衣/外罩/下着〕
动作·道具·神态：〔角色动作 + 点题道具 + 神态动词〕
气质：〔甜/盐/冷/飒/媚/怜 气质词〕
```

**套用示例**：
```
年龄：碧玉年华的少女（a young woman around 17-18）
面部：鹅蛋脸，杏眼含春，远山黛眉，樱桃小口
妆发：半束黑发簪木簪，点绛唇，眉心花钿
身材：身量纤细，杨柳细腰，莲步轻移
服装：米白交领内衫，黛绿褙子，米白百迭裙
动作·道具·神态：执卷立于竹下，目光清亮，微风翻页
气质：温婉文静，书卷气
```

**完整成品示范（七件套 × 14 步详装·逐层标注，可直接复制）**：

```
1 时间环境：夏日午后，宋式书房窗下，白墙深木
2 主体（人物七件套）：碧玉年华的少女（a young woman around 17-18）——鹅蛋脸杏眼含春，远山黛眉，檀唇微抿；半束黑发簪木簪，眉间一点花钿，耳坠玉珠轻晃；身量纤细，杨柳细腰，端坐案前；米白交领内衫+黛绿褙子+米白百迭裙（棉麻细褶自然垂落）；执竹茶则候汤，垂眸凝神；温婉文静，书卷气
3 场景与元素：窗外梧桐叶影婆娑，案头粗陶壶白雾袅袅，青瓷盏釉光温润
4 道具细节：竹茶则斜搁壶口，水盂茶巾齐整，茶巾叠角压案
5 色调氛围：米白黛绿低饱和色板，通透留白，空灵宁静
6 光影美学：阳光被叶切碎成光斑洒在木案与手背，明明灭灭如碎金，尘埃在光柱里浮动
7 动态细节：茶雾盘旋，光斑随风轻晃，指尖微动翻盏
8 构图层次：前景绿植虚化斜入，中景人物，背景白墙化奶油散景
9 服装详写：交领内衫领口合拢，褙子直袖垂落，百迭裙细褶随坐姿自然铺展
10 人物状态：垂眸候汤，唇角浅笑，坐姿端雅
11 肤质焦点：细腻通透肤质，焦点在眉眼与指尖
12 情绪关键词：静谧、雅致、自得、岁月静好
13 构图角度：平视中近景，缓慢推镜从茶盏推至眉眼
14 相机参数+质感+风格：85mm f/1.4，ISO 400，浅景深奶油散景，细微胶片颗粒，低反差柔光，柔和唯美细腻电影化；负面词：手部畸形、六指、五官错位、塑料质感、过度磨皮、强饱和、现代物件、文字水印
```

> 对照「三、人物造型写作公式」的七件套模板逐层看：每层都有对应词库可替换（年龄锚点/面部/妆发/身材/服装/动作道具神态/气质）。

**直接写进视频 prompt 的一行式**：
`碧玉年华的少女（a young woman around 17-18），鹅蛋脸杏眼含春、远山黛眉樱桃小口，半束黑发簪木簪、点绛唇眉心花钿，身量纤细杨柳细腰，米白交领内衫外罩黛绿褙子下着百迭裙，执卷立于竹下目光清亮，微风翻页，书卷气`

### 国风美人写真配方（人像特写·中英双语）

> 来源：「画画的辰小虫」国风美人 prompt 系列（GPT Image 类工具，85mm f/1.4 人像）。写美人特写/写真镜头时，直接套这六层。

**① 冷白前键光（美人专属光）**

- 中文：强力冷白正面主光均匀铺满人物，皮肤呈现雪白半透明质感，几乎无阴影
- English: Powerful cool white front key light floods the figure evenly; skin reads snow white and translucent, almost shadowless
- 变体：奶白中性正面主光，无正面阴影 / Milky neutral front key light floods face and shoulders evenly, no frontal shadows

**② 美人脸五官公式（中英对照）**

| 中文 | English |
|---|---|
| 完美鹅蛋脸，黄金比例 | Perfect oval face, golden ratio proportions |
| 大杏眼双眼皮 | Large almond eyes with (parallel) double eyelids |
| 星光美瞳高光 | Star catchlights |
| 柔和卧蚕 | Soft aegyo sal |
| 长拱眉 | Long arched brows |
| 小鼻 | Small nose |
| 瓷白无瑕肌，如奶大理石光滑 | Porcelain cool white flawless skin, milk marble smooth |
| 珊瑚橘/珊瑚红唇微启 | Coral orange/red lips slightly parted |

**③ 妆容词库**

- 朱红花钿 Vermillion huadian
- 星芒金额饰 Starburst gold forehead pendant
- 淡桃眼影 Pale peach eyeshadow
- 卧蚕 Aegyo sal
- 香槟粉绢花 Champagne pink silk peony
- 金丝花饰 Gold filigree blossoms
- 珍珠流苏发簪 Pearl tassel hairpins
- 长珍珠耳坠 Long pearl drop earrings

**④ 唐制齐胸襦裙四件套结构**

`象牙白缎面衬裙 + 灰蓝薄纱外衣（绣珊瑚红/奶油白/靛蓝牡丹，金线勾边）+ 珊瑚橘织锦腰带 + 杏色薄纱披帛随风飘拂`

- 变体·钢蓝大袖：钢蓝缎面大袖袍，3D 牡丹刺绣金线勾边，珊瑚红抹胸束带，象牙纱披肩
- 变体·金织仙裙：露肩金织仙裙，象牙丝缎吊带抹胸，薄纱外衣，翻飞刺绣广袖，粉内衬下摆
- 变体·宋制叠穿（日常治愈向）：交叉领内搭 + 宽松外袍 + 长裙垂落 + 棉麻布料自然垂褶（纯白与翡翠绿相间）
- 双人田园通用发式：双环髻（double-loop bun）/ 双丫髻（double-bun style）/ 低马尾松挽（low loose ponytail）/ 布包髻插木簪（cloth-wrapped topknot with wooden pin）/ 半马尾布束发（half-tied hair with cloth wrap）——均配银簪或木簪

**⑤ 背景写法**

- 影棚：暖灰褐影棚背景，银白轮廓光（Warm grey taupe studio backdrop, silver white rim light）
- 油画：古典油画质感云海，板岩蓝天空，文艺复兴湿壁画笔触（Classical oil painting cloud sea, slate blue sky, Renaissance fresco brushwork）

**⑥ 英文收尾三词公式**（华丽感 + 氛围 + 情绪，放 prompt 结尾）

- Opulent, airy, serene. 华贵、空灵、宁静
- Opulent, ethereal, cool. 华贵、空灵、冷感

> 组装示例（完整一行）：冷白前键光 + 美人脸五官公式 + 妆容 + 唐制襦裙四件套 + 油画背景 + 收尾三词 → 直接成图。

### 真人感·写实人像配方（与美人配方对照）

> 与「国风美人写真配方」相反：美人是"完美无瑕"，真人是"保留瑕疵、拒绝完美"。写真人感时优先用本小节。

**① 皮肤写实词库**

| 中文 | English |
|---|---|
| 毛孔可见 | Visible pores |
| 雀斑 | Freckles |
| 痣 | Moles |
| 绒毛 | Peach fuzz / fine hairs |
| 自然红晕 | Natural flush |
| 血管透光 | Veins showing through skin |
| 不完美瑕疵 | Natural imperfections |

**② 面部真实化**

- 轻微不对称：五官轻微不对称，自然真实 / Slight facial asymmetry, natural and real
- 微表情：嘴角一丝不易察觉的笑意 / A barely noticeable hint of a smile
- 法令纹/泪沟：自然法令纹与卧蚕，不做磨皮处理 / Natural nasolabial folds, unretouched
- 自然眉形：原生眉形，不修整的杂毛 / Natural brows with unplucked hairs
- 非对称发型：发丝凌乱，一缕垂落脸侧 / Messy strands falling by the face

**③ 光线真实化**

- 环境色染：皮肤被周围环境光染色，肤色自然 / Skin tinted by ambient environment light
- 自然窗光：柔和窗光从侧方洒落，明暗过渡真实 / Soft window light from the side, realistic falloff
- 高光真实：高光只在鼻梁与颧骨自然位置 / Highlights only on natural spots: nose bridge and cheekbones

**④ 镜头真实感**

- 抓拍瞬间感：Candid moment, natural expression caught mid-motion
- 手机随手拍感：Shot on phone, casual everyday framing
- 35mm 自然焦段：35mm natural focal length
- 偷拍视角：A glimpse from a distance, as if unnoticed

**⑤ 反 AI 负面词**

- 无塑料皮肤 / No plastic skin
- 无完美对称脸 / No perfectly symmetrical AI face
- 无过度磨皮 / No over-smoothing
- 无滤镜感 / No filter look
- 无渲染感 / No rendered 3D look
- 无卡通 / No cartoon style

**⑥ 成品示范（可直接复制）**

中文：抓拍瞬间感，35mm 自然焦段，柔和窗光侧洒。年轻女子靠窗而坐，五官轻微不对称，毛孔可见，雀斑点点，发丝凌乱一缕垂落脸侧，嘴角一丝不易察觉的笑意，肤色被窗光染成暖调，高光只在鼻梁与颧骨，无过度磨皮无塑料感，真实自然。

English: Candid moment, 35mm natural focal length, soft window light from the side. A young woman sitting by the window, slight facial asymmetry, visible pores, freckles, messy strands falling by her face, a barely noticeable hint of a smile, skin tinted warm by window light, highlights only on the nose bridge and cheekbones, no over-smoothing, no plastic look, natural and real.


### 动作描写公式

```
动作部位 + 动作动词(雅) + 动作幅度/节奏 + 与道具/光效互动
```

**入画状态三选一（第 0 层·写人物动作前先选）**

| 状态 | 写法 | 示例 |
|---|---|---|
| 定格中 | 她正在做某事（动作进行到一半） | 翻到一半的书页停在手中，目光停在字上 |
| 将要动 | 她正要开始做某事（动作蓄势未发） | 手已抬起，指尖悬在门扇前一寸，即将推门 |
| 停顿片刻 | 她刚做完某事，正停在那 | 刚放下笔，手还悬在砚台上方，墨迹未干 |

用法：写「动作·道具·神态」段前先定入画状态 → 动作公式从"状态"出发写，人物不再是"已定格的摆拍"，而有了叙事弧线。
示例：她正要抬手推门，指尖悬在门扇前一寸——定格中的将要动。

### 动作雅词库

| 部位 | 雅词 |
|---|---|
| 手部 | 拈起 / 轻抚 / 捧奉 / 执盏 / 递送 / 拢袖 / 捻 / 拂 / 挽 / 托 / 掀 / 揭 / 撒花戏鱼 / 指尖翻页 / 撩拨 / 旋摘 |
| 身体 | 欠身 / 移步 / 回首 / 驻足 / 侧身 / 俯首 / 仰首 / 敛衽 / 行揖 / 跪拜 |
| 幅度节奏 | 轻缓 / 倏然 / 缓缓 / 悄然 / 微微 / 顺势 |

### 手中道具公式

```
道具 + 持握方式 + 动作 + 光效
```

### 持握方式词库

```
指尖轻抚 / 双手捧奉 / 执于胸前 / 拢于袖中 / 托于掌心 / 拈于指间 / 挽于腕间 /
双手在身前结印（仙侠·English: hands forming a mystic seal before her）/ 拈花指
```

### 表情神态公式

```
眉眼 + 嘴角 + 目光 + 情绪 + 微表情
```

### 神态雅词库

| 部位 | 雅词 |
|---|---|
| 眉眼 | 眉眼弯弯 / 黛眉微蹙 / 眉梢带喜 / 柳眉舒展 |
| 嘴角 | 唇角微扬 / 抿唇浅笑 / 含笑不语 / 嘴角噙笑 |
| 目光 | 目光含情 / 眼波流转 / 眸光潋滟 / 垂眸 / 低眉 |
| 微表情 | 耳根泛红 / 指尖绞衣角 / 颊上薄红 / 气息微滞 / 眼睫轻颤 |

### 情绪 → 身体微动作映射表（7 种基础情绪·写"紧张"别只会写手抖）

| 情绪 | 面容 | 眼神 | 手部 | 身体 | 呼吸 | 一句话写法 |
|---|---|---|---|---|---|---|
| 紧张 | 嘴唇抿成一线，眉心微蹙 | 目光游移不定，不敢对视 | 指尖绞衣角，握拳又松开 | 肩微耸，重心在脚掌间 | 胸腔起伏加快 | 垂眸目光游移，指尖无意识地绞着袖口 |
| 悲伤 | 嘴唇微微颤抖，眼角泛红 | 眼眶湿润，视线低垂 | 手指轻抚某物，如触遗物 | 肩微塌，身体蜷缩 | 吸一口气又缓缓呼出 | 眼眶微红视线低垂，指尖轻抚袖口暗纹 |
| 愤怒 | 唇角下沉，下颌收紧 | 瞳孔微缩，目光锐利 | 指尖按桌沿泛白，指节突出 | 身体前倾如弓 | 咬紧牙关 | 下颌收紧，指尖按桌沿泛白 |
| 喜悦 | 眉眼弯弯，唇角自然上翘 | 眸光清亮，瞳孔微张 | 指尖轻快敲击桌面 | 身体自然舒展 | 呼吸轻快 | 眉眼弯弯，指尖轻轻点着桌面 |
| 恐惧 | 嘴唇微张欲呼又止 | 瞳孔放大，目光定在一点 | 双手护在胸前 | 身体后倾或侧身 | 屏息，不敢动 | 瞳孔微张，双手轻护胸前 |
| 思念 | 眉梢微垂，视线放空 | 目光望向某处，不在当下 | 指尖摩挲某物边缘 | 身体略侧向臆想方向 | 缓缓呼一口气 | 目光放空望向窗外，指尖来回摩挲瓷杯边缘 |
| 羞赧 | 面颊泛红，目光躲闪 | 视线向下，偶尔抬眼又垂下 | 手中来回摆弄某物 | 身体微微侧转 | 气息微乱 | 面颊泛红，目光躲闪，指尖来回拨弄衣带 |

用法：情绪词 → 身体微动作 → 直接替换进「动作·道具·神态」段。

### 动作·神态对照示例

**神态**

- 普通：她笑了
- 美学：她眉眼弯弯，眼波流转，唇角微微扬起，颊上泛起薄红

**动作+道具**

- 普通：他拿着簪子递给她
- 美学：他指尖拈起金钗，缓缓递至她鬓边，钗尖在烛光下泛起细碎金光；她垂眸，耳根泛红

### 动作·神态组合示范

**古风·插钗**

> 男方母亲拈起金钗，指尖轻拢新娘鬓发，钗尖在烛光下泛着细碎金光，缓缓簪入发髻。新娘垂眸端坐，耳根泛红，唇角噙着浅笑，指尖无意识地绞着衣角。

### 动作·神态心法

1. 动作三要素：**部位 + 雅动词 + 节奏**（"拈起…缓缓…递至"）
2. 道具必须和手互动（拈/捧/执/递），死物才有生命
3. 神态写**微表情**（耳根泛红/指尖绞衣角），比"笑了/害羞"高级一整个档次

---

## 五、运镜词库（视频的灵魂）

### 运镜描写公式

```
景别 + 镜头运动方式 + 运动速度 + 起幅/落幅 + 运动目的(情绪)
```

### 运镜雅词库

| 维度 | 词 |
|---|---|
| 推拉 | 缓慢推镜 / 疾推 / 缓缓拉远 / 急拉 |
| 摇移 | 横移 / 摇镜 / 环绕 / 跟拍 / 升降 |
| 特殊 | 低机位仰拍 / 超低机位（贴地仰拍）/ 高机位俯瞰 / 手持微晃 / 斯坦尼康平稳 / 航拍 / 轨道平滑 |
| 速度 | 缓缓 / 轻柔 / 稳 / 倏然 / 急促 |
| 起幅落幅 | 从特写拉至全景 / 从全景推至眼部特写 / 从大雁特写推至全身 |

### 运镜与情绪对照表

| 运镜 | 传达情绪 |
|---|---|
| 缓慢推镜 | 聚焦、窥视、强调、情感逼近 |
| 缓缓拉远 | 疏离、告别、释然、收束 |
| 横移 | 漫步、环境交代、从容 |
| 环绕 | 亲密、晕眩、审视 |
| 低机位仰拍 | 庄重、崇高、仪式感、压迫 |
| 超低机位仰拍 | 巨物压迫、渺小、史诗感 |
| 高机位俯瞰 | 渺小、命运感、全景掌控 |
| 手持微晃 | 真实、紧张、纪实感 |
| 斯坦尼康平稳 | 梦幻、流畅、电影感 |
| 跟拍 | 追逐、参与感、推进感 |

### 机位角度速查表（视角方向体系·中英关键词）

> 与上方"高度系"（低/超低/高机位）互补：高度管"俯仰"，本表管"朝向"；两者可组合（如"低机位 + 45° 斜角"）。

| 角度 | 写法 | 效果/适用 |
|---|---|---|
| 正面平视 | 正面平视构图，人物正对镜头（front view, facing camera） | 直白、庄重、有交流感 |
| 45° 斜角（3/4 侧） | 45° 斜角机位，3/4 侧面入镜（three-quarter view） | 立体感、叙事感，人像最常用角度 |
| 侧面平视（正侧） | 侧面平视，正侧脸轮廓入镜（profile view） | 轮廓线、剪影、静默、沉思 |
| 背面（背身） | 背身构图，人物背对镜头（back view） | 悬念、望向远方、观众代入 |
| 3/4 背身 | 3/4 背身机位，人物侧背对镜头（three-quarter back view） | 背影叙事 + 保留可读表情，行走/劳作多用 |
| 过肩镜头 | 过肩机位，前景人物肩部虚化（over-the-shoulder） | 对话、对峙、双人关系 |
| 荷兰角 | 荷兰角倾斜构图，地平线歪斜（dutch angle, tilted frame） | 失衡、不安、梦境、心绪不宁 |
| 鸟瞰/顶拍 | 顶拍鸟瞰，垂直俯视（top-down, bird's-eye view） | 仪式感、棋盘式构图、命运俯瞰 |
| 主观镜头（POV） | 主观镜头，模拟人物第一人称视线（point-of-view shot） | 代入、窥视、身临其境 |

**组合例句**：低机位 45° 斜角仰拍，过肩前景团扇虚化，3/4 侧脸入镜——（低机位）+（斜角）+（过肩）+（侧脸）四层叠加一次写全。

---

## 六、景别与构图

### 景别序列

```
远景(环境) → 全景(人+环境) → 中景(腰部以上) → 近景(胸部以上) → 特写(局部) → 大特写(眉眼/手)
```

### 景别节奏公式

```
开场远景定场 → 中景叙事 → 近景/特写情感 → 结尾拉远收束
```

（对应原片：开场特写钩子 → 中景叙事 → 特写情感 → 结尾大全景收束）

### 构图法则词库

```
对称构图(庄重) / 框架构图·门洞窗棂(窥视纵深) / 三分法(自然) /
留白(孤寂意境) / 引导线·长廊石阶(纵深) / 对角线(动感) / 中心构图(仪式感) /
前景参照物·飞鸟岩石栏杆(尺度反衬) / 主体出画·隐入云雾暗部(预留想象空间)
```

### 构图-情绪对照表

| 构图 | 情绪 |
|---|---|
| 对称 | 庄重、仪式、古典 |
| 框架（门洞/窗棂） | 窥视、幽深、空间感 |
| 留白 | 孤寂、意境、呼吸感 |
| 引导线 | 纵深、延展、走向 |
| 中心 | 聚焦、仪式感、不容置疑 |

### 景别切换节奏

- 每镜头一个主景别；切镜时"跳景别"（远景→特写）制造冲击，"递进景别"（中景→近景→特写）制造情感递进
- 每 8 秒镜头建议：1 个定场 + 1-2 个叙事 + 1 个情感特写

### 特写镜头配方（情绪放大器·中英对照）

> 特写 = 把"局部"放大到情绪满格。写"眼睛里有故事"这类镜头时用本配方。

**① 特写部位词库（拍哪里）**

| 部位 | 写法示例 |
|---|---|
| 眉眼 | 眉眼特写，眉梢微微蹙起 |
| 眼神 | 眼神特写，瞳孔里映着窗光 |
| 睫毛 | 睫毛特写，根根分明，轻颤如蝶翼 |
| 唇部 | 唇部特写，珊瑚色唇微启，唇纹细腻 |
| 指尖 | 指尖特写，轻抚杯沿，指节微曲 |
| 发丝 | 发丝特写，一缕垂落脸侧，绒毛可见 |
| 首饰 | 首饰特写，玉簪在光中泛温润光泽 |
| 手部动作 | 手部特写，指尖拈起花瓣 |
| 器物 | 器物特写，杯口蒸汽盘旋上升 |

**② 特写光影（光打在局部）**

- 眼神光：瞳孔中一点高光，如星 / A single catchlight in the pupil, star-like
- 瞳孔倒影：瞳孔里倒映窗外树影 / Window reflections mirrored in the pupils
- 睫毛投影：睫毛在脸颊投下细密阴影 / Eyelashes casting fine shadows on the cheek
- 唇上光斑：一束光落在唇峰，泛暖光 / A beam of light kissing the cupid's bow, warm glow
- 金属反光：金饰在高光处闪一点细芒 / Gold ornaments glinting a fine spark at the highlight

**③ 手部特写专项（配合 100mm 微距锚点·情绪浓缩）**

公式：`手部动词 + 持物材质 + 光效互动 + 景别 + 焦段`

| 情绪 | 写法 |
|---|---|
| 时光流逝 | 指尖翻动泛黄书页，纸缘绒毛可见，尘埃在光柱里浮动，大特写，100mm f/2.8 微距 |
| 克制隐忍 | 指尖抚过杯沿，指节微曲又松开，暖光在指缝间勾勒线条 |
| 心动 | 两人指尖相触的瞬间，指尖泛粉，光斑落在手背 |
| 欢愉 | 一把花瓣从指缝漏下，花瓣边缘逆光透亮，碎光飞舞 |
| 温柔 | 手指穿过发丝，发丝从指间滑落，柔光勾出手部轮廓 |

**③ 特写情绪（情绪放大器）**

- 眼眶含泪：泪光在眼眶打转，将落未落 / Tears welling up, trembling on the brink
- 睫毛轻颤：睫毛轻颤，像在压抑什么 / Eyelashes trembling as if holding something back
- 欲言又止：嘴唇微启又合拢，欲言又止 / Lips parting then closing, words unsaid
- 瞳孔扩张：瞳孔微微放大，情绪翻涌 / Pupils slightly dilated, emotion surging
- 屏息感：空气凝住，只有睫毛的颤动 / The air holds still, only eyelashes moving

**④ 特写质感（放大细节）**

- 皮肤：毛孔与绒毛清晰可见 / Visible pores and peach fuzz
- 唇部：唇纹细腻，光泽自然 / Fine lip texture, natural sheen
- 眼睛：虹膜纹理如丝线交织 / Iris texture woven like fine threads
- 首饰：细微划痕与岁月痕迹 / Subtle scratches and signs of age

**⑤ 特写构图与运镜**

- 切景规则：只留局部（眉眼以下/一只眼睛/一双手），其余全部出画 / Crop to the part, let the rest fall out of frame
- 负空间留白：特写旁留大片暗部或虚化，突出局部 / Negative space around the close-up, spotlighting the part
- 极慢推至特写：镜头以极慢速度推至眼部特写 / Extremely slow push-in to an eye close-up
- 焦点转移：焦点从整体缓缓移到局部（手→眼） / Focus racking from the whole to the part

**⑥ 成品示范（可直接复制）**

眉眼特写：眼神特写，瞳孔里映着窗外树影，一点高光如星，睫毛根根分明在脸颊投下细密阴影，泪光在眼眶打转将落未落，眉梢微蹙，空气凝住，只有睫毛的轻颤。浅景深，背景完全虚化。

English: Eye close-up, window reflections mirrored in the pupils with a single star-like catchlight, lashes sharp and fine casting delicate shadows on the cheek, tears welling up trembling on the brink, brows slightly furrowed, the air holds still, only eyelashes moving. Shallow depth of field, background fully blurred.

指尖器物特写：指尖特写，轻抚青瓷杯沿，指节微曲，杯口蒸汽盘旋上升，暖光落在指腹与杯沿之间，瓷面泛温润釉光，细密毛孔与绒毛可见。浅景深，虚化背景。

English: Fingertip close-up, softly tracing the rim of a celadon cup, knuckles gently curved, steam curling from the rim, warm light between fingertip and porcelain, glaze glowing softly, visible pores and fine hairs. Shallow depth of field, blurred background.

### 增强视觉冲击力三件套（写宏大/巨物/史诗场景必加）

| 三件套 | 写法 | 作用 |
|---|---|---|
| 超低机位 | 超低机位仰拍，主体压过画面上缘 | 观众站在巨物脚下，压迫感直接拉满 |
| 前景参照物 | 前景放飞鸟 / 岩石 / 残破栏杆 | 用已知小物体反衬巨物尺度，比直接说"巨大"有效十倍 |
| 预留想象空间 | 主体大部隐入云雾 / 画外，只露局部 | 不拍全，观众脑补更大——看不见的才最恐怖 |

组合公式：

```
超低机位 + 前景[参照物] + 主体[露出局部]隐入[云雾/暗部] + 渺小人物对比
```

> 完整详解见「三、3.5.11 增强视觉冲击力三件套」；适用题材：巨物观 / 巨兽异兽 / 天宫神殿 / 云海奇观。

### 前景虚化（唯美纵深·构图进阶）

**① 前景虚化元素词库**

| 元素 | 写法示例 |
|---|---|
| 桃花枝 | 前景桃花枝虚化成大光斑 |
| 竹枝 | 竹枝在画面边缘虚化斜出 |
| 柳条 | 柳条轻垂，在前景虚化飘动 |
| 纱帘 | 纱帘半掩，虚化如雾 |
| 珠帘 | 珠帘在前景碎成光点 |
| 格栅/窗棂 | 窗棂在前景虚化框住人物 |
| 伞沿 | 伞沿虚化占画面上缘 |
| 檐角 | 檐角在前景虚化入画 |
| 灯笼 | 红灯笼在前景虚化成暖光晕 |
| 飘带 | 飘带拂过镜头前，虚化成一抹色 |
| 芦苇 | 芦苇穗在前景虚化轻晃 |
| 水面反光 | 水面反光在前景碎成光斑 |

**② 虚化程度分级**

| 程度 | 写法 |
|---|---|
| 大光斑虚化 | 前景虚化成大而柔的光斑（bokeh） |
| 轻度虚化 | 前景仅轻微失焦，轮廓可辨 |
| 轮廓虚化 | 前景只剩模糊轮廓与色块 |
| 柔焦前景 | 前景柔焦如雾，边缘泛光 |

**③ 前景四作用**

- 框景纵深：前景隔出前后空间，画面有层次
- 窥视遮挡：透过前景看人物，增加窥视感/私密感
- 尺度反衬：前景小物反衬主体尺度（详见三件套·前景参照物）
- 氛围光斑：前景虚化成唯美光点，强化柔美氛围

**④ 英文对照**

```
Foreground bokeh / Out-of-focus foreground / Layered depth / Foreground framing
```

**⑤ 组合公式 + 成品示范**

`前景元素 + 虚化程度 + 作用`

- 示范：前景桃花枝虚化成大光斑，透过去看美人，纵深唯美
- English: Foreground peach blossoms blurred into large bokeh, viewing the beauty through them, layered depth and ethereal beauty

---

### Cinema DNA 构图判断工具（V5.8 入库·先判断再取词）

> 来源：Cinema DNA 21:9×3 开源项目（GitHub: dacnay816y62-hub/cinema-dna-21x9x3，v1.2.2/3.0）。写任何镜头前先过这两个判断，再取素材库的景别/机位/遮挡词。

**① 构图压力 6 类型**（构图不是装饰，是人物与空间之间的权力关系。先判断人物与空间的关系，再决定机位/景别/遮挡）：

1. **被观察**：门缝、玻璃、人群、监视位置——人物处在"被看"的位置
2. **被困住**：桌面、走廊、台阶、座椅、制度空间——空间限制人物
3. **关系疏离**：两人之间的空桌、玻璃、地面、床或长廊——距离即关系
4. **权力不对等**：巨大墙面、台阶、旗位、宗教/政治空间——环境压人
5. **心理失衡**：贴边、过多头顶空间、焦点落在背景——构图失衡表达心理
6. **感官插入**：手、汗水、鞋、衣料、头盔、器械边缘——局部特写承载压力

应用（古风镜头）：深宫女子=被观察/被困住；君臣对坐=权力不对等；久别夫妻=关系疏离（空桌/长廊）；婚礼前的少女=心理失衡；捻线的手/玉簪/衣料=感官插入。

**② 视线流量句**（每镜必写一句，写不清=构图只是元素堆叠）：

> 视线从 A 进入，被 B 放慢或遮挡，落到 C，最后由 D 带走。

- 如果换成任意题材仍成立，说明构图太模板化，必须重写。
- 例（古风）：视线从门缝进入，被屏风遮挡放慢，落到女子捻线的手，最后被窗外月影带走。

#### Cinema DNA 负面前景规则（V5.10 入库·前景不是装饰）

前景必须有功能，至少满足一条：解释摄影机真实站位 / 形成框中框并把视线导向情绪焦点 / 区分前中远景层次 / 延迟信息制造悬念 / 表达被困·被看见·被排除·无法进入 / 与轴线·光斑·水平线·阴影形成图形关系。

拒绝：随机大面积虚化物体遮画面 / 无叙事理由的帽檐·肩膀·玻璃·栏杆·树叶·烛台·家具近景 / 用微距细节替代场面调度 / 用浅景深掩盖构图不足 / 前景抢注意力但不增加空间·危险·隐私·距离。

古风检查：如果前景虚化竹枝/灯笼/纱帘换成任何题材都成立，说明它只是“电影感装饰”，删掉或给它一个叙事任务。

#### Cinema DNA 视觉主引擎 8 选 1（V5.10 入库·先选引擎再取词）

每次生成选 1 主引擎 + 至多 2 辅助，不要堆叠超过 3 个：

| 引擎 | 干什么 | 古风可用词 |
|---|---|---|
| 秩序构图 | 对称/透视/阵列/框中框，每个人物位置有叙事目的 | 中轴对称、廊柱阵列、门洞框景 |
| 光影戏剧 | 光线有真实来源，亮部只照亮叙事重点 | 门缝光、窗棂光、烛火、逆光剪影 |
| 色彩叙事 | 主色≤2-3 种，色彩服务关系 | 墨绿+朱砂+雾白 |
| 空间叙事 | 空间本身讲故事，加一处叙事痕迹 | 半开的门、风吹帘幕、还亮着的一盏灯 |
| 人物状态 | 动作处于过程中，避免摆拍 | 凝视/等待/错过/隐藏/观察 |
| 尺度与世界 | 大场景保留人物命运，极简真实 | 山水藏人、巨构中的小人 |
| 东方场面 | 山水不是背景是叙事空间 | 山水藏人、建筑布阵、静极生动、风动人静、远观动作、长卷空间 |
| 主观实验 | 每种变形服务情绪，一张图≤1-2 种 | 低机位仰拍、镜面反射、倾斜地平线 |

---

## 七、Prompt 组装公式（总装模板）

### 三要素联动例句库（人物→场景→道具一次性成句·总装前先看）

【联动公式】人物状态（入画 + 七件套）+ 她身在的场景（时代标签 + 空间 + 材质 + 光效）+ 她手上的道具（配饰三层 + 光效互动）

**联动例句·春闺倦读**

春日下午，宋式闺阁轩窗边，窗棂筛下细碎光斑落在青砖地上（场景·春日窗光）。小姐着藕荷色绫罗襦裙、云鬓半松簪白玉簪（人物·妆发服装），倚着窗台，一手支颐一手懒懒翻着书页（动作·神态），书页在逆光中泛暖黄，指间绢帕半垂（道具·光效）。窗外海棠初绽，花瓣偶尔飘落窗前（场景·动态点缀）。

**联动例句·雪夜归人**

雪夜，唐风宅邸朱漆大门前，门廊灯笼光晕在雪地上铺开暖黄一圈（场景·夜雪灯）。归人着玄色锦袍、腰悬白玉佩（人物·服装配饰），抬手拂去肩上落雪，另一手提着纸灯笼缓步上阶（动作·道具），灯笼光映在雪上，呵气成白雾（道具·光效）。身后雪径两行脚印，将尽未尽（场景·动态点缀）。

用法：照公式拆三层写 → 自然成句，不堆砌；两句均为 14 步详装的"一句话压缩版"。

### 14 步详装结构（X-Pem 宋式田园法·逐项填充）

> ⭐ **默认写法（V3.48 起，见〇章规则 6）**：精细镜头 / 图片卡 / 正式交付均按本结构逐项输出。比外部常见的 10 步更多「场景与元素 / 道具细节 / 动态细节 / 肤质焦点 / 情绪关键词」五维。
>
> 场景与元素单列成步（第 3 步）：画面里除了主角，还有谁、还有什么——人群 / 动物 / 植物 / 器物陈设，全部点名，AI 才不会漏画。

```
1. 时间环境（开头定调）
2. 主体（人物七件套：年龄锚点 + 面部 + 妆发 + 身材 + 服装 + 动作·道具·神态 + 气质，见四章公式）
3. 场景与元素（空间 + 陈设 + 配角：人群 / 动物 / 植物 / 器物——画面里除了主角还有什么，由近及远点名）
4. 道具细节（主角手持/近前小物，增加真实感）
5. 色调 + 氛围（风格定调）
6. 光影美学（宋式美学）
7. 动态细节（氛围感点睛）
8. 构图层次（前景 + 背景）
9. 服装详写（分层描述，保证服装准确）
10. 人物状态（表情 + 发型 + 姿态）
11. 肤质 + 焦点
12. 情绪关键词（堆叠氛围词）
13. 构图角度（视频改为运镜：景别 + 运动 + 速度）
14. 相机参数 + 质感 + 风格定位（结尾技术段）
```

**第 7 步「动态变化」（重定义·V3.66 起）**：

> 只写"镜头开始→结束之间发生了什么变化"，不重复静态细节——与第 2 步「动作·道具·神态」（人物此刻在做什么）、第 3 步「场景与元素」（环境里有什么）分工明确。

```
只写时间维度的变化：
- 光斑从桌面移至手背
- 茶雾从浓转淡
- 她抬眼：从垂眸到看向镜头
```

示例对照（点茶镜头）：
- 第 2 步（人物动作）：执竹茶则候汤，垂眸凝神
- 第 3 步（场景元素）：案头粗陶壶白雾袅袅
- 第 7 步（动态变化）：茶雾由浓转淡，光斑从壶身滑至手背，她缓缓抬眼看向镜头

**第 8 步「构图层次」与第 3 步的分工（V3.67 起明确）**：

- **第 3 步「场景与元素」写"有什么"**：元素清单——画面里有哪些人/物/景，由近及远点名（内容层）
- **第 8 步「构图层次」写"怎么摆"**：这些元素的前/中/后空间关系和虚化程度（形式层）

一句话：第 3 步管"有什么"，第 8 步管"怎么摆"。同一个竹筐，第 3 步点名"前景竹筐与晒谷耙"，第 8 步定关系"前景绿植虚化斜入，中景人物，背景白墙化奶油散景"。

**第 3 步「场景与元素」元素清单（挑着点名，别漏画）**

```
人群：远处人影 / 赶集人群 / 围观孩童 / 廊下奴仆 / 田里农夫 / 桥头挑担人
动物：耕牛 / 白鹤 / 猫 / 蝶 / 池鱼 / 犬 / 飞鸟 / 羊群
植物：花（桃花/荷花/荻花/梅）/ 竹 / 蕉叶 / 麦浪 / 稻穗 / 藤蔓
器物陈设：草垛 / 陶缸 / 晾晒席 / 灯笼 / 石磨 / 晒谷耙 / 竹筐 / 乌篷船
组织方式：由近及远点名（前景 x → 中景 y → 背景 z），或按"人群 → 动物 → 植物 → 陈设"分类排
```

示例（第 3 步填法）：打谷场上，前景竹筐与晒谷耙，中景一位老农驱牛拉石碾，远处几个孩童追逐嬉闹，场边柿树挂果，几只鸡在草垛下啄食。

用法：14 步填满即一条完整 prompt；视频用时把第 13 步"构图角度"改为"运镜"（景别+运动+速度），其余不变。该结构为默认写法（V3.48 起），比总装公式多出"场景与元素/道具细节/动态细节/肤质焦点/情绪关键词"五个维度；总装公式仅用于快速出片。
> **V5.15 升级**：正式交付建议在 14 步基础上追加「二十」章三个字段——第 2 步前加「承接段」（20.2）、第 4 步后加「节拍段」（20.2）、第 8 步后加「站位几何」（20.7）；末尾统一贴「中式技术底座」（20.1）。

### 组装顺序

```
① 统一风格基调（第一章 V1-V5 按题材选；写真另取十二章基调）
② 场景（第三章）：时代基调 + 空间 + 材质 + 光效 + 动态
③ 人物造型（第四章）：身份 + 服色 + 发饰 + 神态
④ 动作·道具·神态（第四章）：动作 + 道具互动 + 微表情
⑤ 光影（第二章）：光源 + 光位 + 光质 + 明暗
⑥ 运镜景别（第五/六章）：景别 + 运动 + 速度
⑦ 摄影参数：焦段 / 光圈 / ISO
```

### 总装公式

```
[风格基调] + [场景] + [人物造型] + [动作·道具·神态] + [光影] + [运镜·景别] + [摄影参数]
```

### 人物结构卡（X1-X4·四选一·外部高分写法）

> 来源：外部高分提示词逆向提炼（贵妇撒花/打谷场双人/秋日读书/荻花戏水）。总装公式管"拼什么"，X 卡管"人物段怎么排"。原文短板已补齐：负面词、运镜版、一致性锚点、平台适配。

**X1 主从螺旋卡**（贵妇/夫人 + 侍女/随从）

```
[画面感总起] + [主人面容身姿] + [从属配置+道具] + [服装三段：外罩/下着/脚踩]
+ [场景+主动作（动词+方向）] + [环境动态链：风→水→柳→鱼] + [主人神态] + [从属补位] + [氛围收尾] + [负面词] + [设备锚点]
```
- 运镜版：中景缓推，从主人手部动作推到全景；动态链用镜头内运动表现
- 一致性锚点：主从二人发髻/服色固定，侍女团扇式样固定
- 平台适配：豆包/可灵/即梦整段粘贴；GPT-Image/MJ 去运镜、改"低机位中景"收尾
- 示例：案例 67 贵妇撒花戏鱼

**X2 双人平行卡**（情侣/双姝/伙伴）

```
[时间+人物+地点] + [景别+焦点] + [A：配色→款式→配饰→发型→身姿→动作道具→神态]
+ [B：同色系配色→款式三段→发型→配对动作→神态+视线落在A的物件]
+ [光影（暖调+尘埃）] + [画质词] + [设备锚点+焦平面]
```
- 关键：B 的视线落在 A 的具体物件上（目光落在箩筐/葫芦），关系才实；两人同色系不同深浅
- 运镜版：中景固定→慢横移扫过两人，焦点从 A 移到 B
- 一致性锚点：两人服色同色系固定，物件（箩筐/布袋）每镜一致
- 示例：案例 68 秋日打谷场

**X3 单人纵深卡**（单人静态雅事）

```
[时间+地点+主动作+场景细节] + [景别焦点] + [服装三段] + [发型配饰]
+ [动作+微动作（进行时：指尖翻页/拈茶芽）] + [光影（耶稣光/斑驳）] + [环境+焦外] + [色调氛围质感] + [设备锚点]
```
- 微动作是灵魂：给主动作挂一个进行时细节
- 运镜版：固定镜头微推（90% 不动）或缓慢横移
- 一致性锚点：服装三段顺序固定，微动作每镜换一个
- 示例：案例 69 深秋读书

**X4 单人动态卡**（单人活泼动态）

```
[时间+道具+构图前置（脸占上1/3/人物占50%）] + [人物定义] + [配色先行]
+ [服装款式+领口纹样] + [发型] + [场景+双手双动作+空中元素（水珠悬浮/花瓣飞舞）]
+ [神态+视线] + [光影+肤质] + [前景+画质词] + [角度+设备锚点]
```
- 构图前置：先写构图再写人；双手分工（一手X一手Y），中间夹空中元素
- 运镜版：低角度缓慢上摇定在脸部，或固定镜头
- 一致性锚点：道具（斗笠/荻花）+ 发髻固定
- 示例：案例 70 荻花戏水

**四卡速选**

| 卡 | 适用 | 人数 |
|---|---|---|
| X1 主从螺旋 | 贵妇+侍女/主子+随从 | 2+ |
| X2 双人平行 | 情侣/双姝/伙伴 | 2 |
| X3 单人纵深 | 单人静态雅事 | 1 |
| X4 单人动态 | 单人活泼动态 | 1 |

### 总装示例（古风·纳采）

> 中式古风影视质感，AIGC 生成画面，暖色调，烛光与灯笼暖光，电影感浅景深
> + 朱漆大门泛着釉光，檐角宫灯如豆，石榴树影婆娑，落红轻旋
> + 媒人着青绿古装，广袖垂落，腰间佩玉轻晃
> + 双手捧雁，雁笼系朱红绸结，衣袂被晚风拂动，神态恭敬
> + 侧逆光暖调，金尘浮动
> + 低机位缓慢推镜，从大雁特写推至媒人全身
> + 85mm 定焦，f/2.0，ISO 320

### 生成前检查清单

- [ ] 场景是否含 1 光效 + 1 材质 + 1 动态元素
- [ ] 人物是否含 形制 + 材质 + 颜色雅称
- [ ] 动作是否含 部位 + 雅动词 + 节奏
- [ ] 道具是否与手互动
- [ ] 是否带神态微表情
- [ ] 运镜是否匹配情绪
- [ ] 字幕文案是否已摘出（后期叠加）
- [ ] 是否输出中英双语两版（先中文后英文）

### 可直接复制的成品 prompt 模板

> 一条拼好的完整 prompt，复制即用。中文整段粘贴给豆包 / 可灵 / 海螺 H3。

```
[风格基调] 〔从〇章 V1-V5 选一条整段复制；此处示例为 V1 古风·庄重仪式〕
中式古风影视质感，AIGC 生成画面，电影感浅景深，轻微胶片颗粒，
暖色调统一，烛光与红灯笼暖光照明，侧逆光勾轮廓，低反差柔光，
暗部保留细节，高光不溢出，1920x1080 横屏。

[场景] 暮色四合，朱漆大门泛着温润的釉光，檐角宫灯如豆，光晕在青砖地上洇开一圈暖色；
门前石榴树影婆娑，落红轻旋。

[人物+动作+道具] 媒人着青绿古装，广袖垂落，腰间佩玉轻晃，双手捧雁立于阶前，
雁笼系朱红绸结，衣袂被晚风拂动，金尘周身浮动，神态恭敬。

[运镜+参数] 低机位缓慢推镜，从大雁特写推至媒人全身。85mm 定焦，f/2.0，ISO 320，侧逆光暖调。

[负面词] 手部畸形, 六指, 手指粘连, 五官错位, 脸崩, 现代物品穿帮, 低质量, 模糊, 变形, 文字乱码（文字一律不进画面）。
```

- 适合平台：豆包 / 可灵 / 海螺 H3（中文整段粘贴）；英文版喂 GPT-Image / Midjourney / Runway / Sora
- 预计时长：8-10s
- **双语规则**：以上为中文版；英文版按同结构直译（[Style] + [Scene] + [Character] + [Action] + [Camera] + [Negative]）
- **换题材用法**：把 [风格基调] 换成〇章 V1-V5 对应版本（现代题材 → V3/V4/V5），其余段落结构一字不动；图片版把 [运镜] 段换成构图描述即可

### 视频 ↔ 图片双向转换速查表（图生视频/视频抽帧做图通用）

| 方向 | 替换规则 | 具体做法 |
|---|---|---|
| 视频 → 图片 | 运镜 → 构图（景别+视角），拆成单帧静态描述 | 去掉"推镜/摇镜/跟拍"等运镜词，换成"中景平视/低机位仰拍/特写"；动态词（衣袂飘动）保留为静态定格（衣袂定格在扬起瞬间）；时长感消失，画面凝固为叙事单帧 |
| 图片 → 视频 | 单帧描述拆成 3-4 个运镜句 + 帧间变化 | 把静态描述按"首帧 3s 静止 → 运镜启动 → 落幅"拆：①首帧：画面原样静止 3s（人物状态定格）②运镜：从当前景别缓慢推/摇/移 ③变化：风动/衣动/光动（静态词转动态）④落幅：停在情绪最强处 |

**图片 → 视频拆法示例**（以"春闺倦读"静态卡为例）：

```
首帧（0-3s）：小姐倚窗翻书，书页在逆光中泛暖黄——画面静止
运镜（3-8s）：缓慢推镜，从半身推至书页特写，窗棂光斑在背景虚化流动
变化（8-12s）：风起，绢帕半垂轻扬，海棠花瓣飘落窗前，她抬眸望向窗外
落幅（12-15s）：停在她抬眸的侧脸，眸光微动，光斑拂过眉梢
```

> 反之视频抽帧做图：取落幅帧 → 加构图词（景别+视角）→ 去运镜词 → 即得静态图 prompt。

**30 秒替换原则（比多写 10 个案例更有用）**：

```
只改两个地方——
① [风格基调]：从〇章 V1-V5 复制（古风/现代/电影感按题材选）
② [场景]：从「三、画面美学词库」或「十三、题材适配表」替换
其余（人物段/运镜段/负面词段）一个字都不用动。
```

---

## 八、通用骨架模板（与七章配套：七管「怎么拼」，八管「拼什么」）

> 〇章路径中的「先看八定骨架」即指本段：它是一张字段化填空模板，下面示例用古风婚嫁填充，
> 换题材时只替换各字段的值（风格基调从〇章 V1-V5 复制，场景/人物/道具查「三」，题材查「十三」）。

```
中式古风影视质感，AIGC 生成画面，电影感浅景深，轻微胶片颗粒，
暖色调统一，烛光与红灯笼暖光照明，侧逆光勾轮廓，低反差柔光，
暗部保留细节，高光不溢出

环境：中式建筑（朱门/门楼/红墙/木雕窗棂/祠堂/长街），红灯笼高挂，
    红绸装点，古典家具与香案

人物：汉服古装（颜色区分身份），发髻簪钗，神态温婉含笑/恭敬端庄，
    动作具仪式感（捧礼/递帖/摇签/行礼）

运镜：低机位仰拍，缓慢推镜/横移/环绕，特写转中景，
    镜头节奏舒缓稳重

摄影参数：85mm 定焦 / f2.0 大光圈 / ISO 320 / 暖色白平衡

字幕：全部后期剪辑叠加，不进入生成画面；文案见「十四、后期字幕文案清单」

声音氛围：古筝/琵琶/鼓点 BGM，喜庆庄重，无现代感元素
```

### 核心套路（一句话）

```
暖光 + 仪式动作 + 后期叠加竖排释义卡 + 四字文案
```

---

## 九、使用步骤

1. 按题材复制第一章基调（古风版 / 现代版） + 目标镜头 prompt，合并成一条完整 prompt
2. 视频生成工具任选（豆包 / 可灵 / 海螺 H3 等，见十六章），比例 16:9
3. 每镜头 10-15 秒单独生成，7 条生成后按顺序拼接
4. 所有字幕与文字卡均后期叠加，文案见「十四、后期字幕文案清单」

### 真人感触发三件套（写真人/写实向必看）

> 单写"真人感"三个字大概率出 AI 美人脸（模型默认审美是"美"，会自动美化）。必须三层齐写：

| 层 | 写什么 | 作用 |
|---|---|---|
| 方向词 | 真人感 / 写实照片 / photorealistic | 告诉模型"要真实" |
| 细节词 | 毛孔可见、雀斑、轻微不对称、抓拍瞬间 / visible pores, candid, natural imperfections | 逼模型放弃完美脸 |
| 反 AI 词 | 无塑料皮肤、无磨皮、无完美对称脸 / no plastic skin, no over-smoothing | 拦掉默认美化 |

**按工具微调**：
- GPT Image：用英文细节词响应最准（visible pores / candid / natural imperfections）
- 即梦/豆包：中文"写实照片、皮肤纹理、瑕疵保留" + 负面词"不要磨皮、不要塑料感"
- MJ：photorealistic, candid, film photography + no plastic
- 视频：文生视频写"真人感"作用有限，**图生视频靠首帧保真**——先用真人感出图做首帧，再图生视频

> 完整词库见「四、真人感·写实人像配方」；成品句直接用该小节⑥。

### 生成后拼接标准流程

1. **修剪**：每段去掉开头 0.5s 和结尾 0.5s（AI 生成首尾常不稳定）
2. **排序**：按镜头顺序排列
3. **衔接**：相邻镜头之间加 0.3s 叠化过渡
4. **字幕**：按「十四、后期字幕文案清单」叠加文字卡 + 底部字幕
5. **声音**：配 BGM → 加环境音效 → 加对白配音（BGM 铺底先定调）
6. **调色**：统一色温（暖调），轻微加暗角
7. **导出**：1080p / 16:9 / 30fps

### 选片三步法（10 条废 7 条·怎么挑）

① **硬性淘汰**：手部畸形、脸崩、光效突变、帧间跳变 → 直接删，不犹豫
② **软性筛选**：相邻两镜之间**人物一致性优先于单镜美感**——单镜再美，和上一镜像两个人就弃
③ **衔接配对**：优先选动作落幅/起幅能对上相邻镜的片段（上镜落幅=下镜起幅，拼接最顺）

> 7 镜头 × 每镜 5 条 = 35 条 → 硬淘汰剩 10-15 → 软筛选 + 配对定 7 条。

### 片头 / 片尾 / 转场速查表（镜头之间怎么过渡）

**片头 3 秒**：标题卡（黑底白字淡入 0.5s）→ 定场镜头（全景交代时间地点）
**片尾 3 秒**：金句卡（字幕 + 留白 1s）→ 拉远收束（镜头缓慢拉远/人物走远定格）

| 前后镜头关系 | 推荐转场 | 写法 |
|---|---|---|
| 同场景同人物 | 叠化 0.3s | 最稳 |
| 同场景换人物 | 横划 / 擦除 | 空间延续 |
| 换场景换人物 | 黑屏淡入 | 段落分隔 |
| 情绪高潮 | 白闪 | 冲击感 |
| 同人物跨时空（回忆） | 波纹 / 光晕散开 | 时间跳跃 |

---

## 十、一致性锚点记录表

### 首帧工作流三原则（图生视频·首帧锁人工程化）

> 〇章说"先出图片做首帧"，本小节补实际操作流程。

1. **同一人物至少生成 3 张参考图（正面 / 3/4 侧 / 全身）做一致性底库**——正脸到侧脸切换时锚点表不够用，多角度参考图兜底
2. **每镜首帧必须从参考图中选一张作为图生视频的输入**——不在生成时临时新画首帧
3. **视频 prompt 中的人物描述必须与首帧图片严格对应（不新增/删减特征）**——锚点字段逐项比对，首帧有什么写什么

配套参数：首帧生成时固定 seed（同人同 seed 减少漂移）；比例与目标视频一致（竖屏 9:16 首帧就出 9:16，避免裁切）；构图选该镜落幅最稳的景别。

### 三视图人物锁定卡（V5.11 入库·21:9 角色设定卡·先锁人再开镜）

> 解决的问题：多镜头连续视频人物漂移。一张角色设定卡 = 全片所有镜头的人物锚点母版。生成后存为参考图，每个镜头直接引用该卡，不再每镜重写人物。搜「三视图」或「角色卡」调出。

**使用方法**：给图像模型喂「参考图 + 本模板」，一次生成 21:9 超宽角色卡；之后所有镜头的人物锚点段 = 引用该卡 + 只改动作/景别/神态。

**角色卡模板（整段复制）**：
```
21:9 超宽横版角色完整设定卡，纯白干净棚拍背景。以参考图人物为唯一身份锚点：脸型轮廓（下颌线、颧骨、下巴形状）、眼型、眉形、鼻梁与鼻翼、嘴唇厚薄与嘴角形状、年龄气质必须严格一致；发际线、发型结构与发饰必须严格一致。只允许同一个角色，禁止换脸、禁止五官漂移、禁止发型简化或发饰缺失。
单张合成图，左中右三分区构图，三区统一光影与色彩，柔光棚拍布光，光源方向一致：
左区（占画面宽度约 25%）：人物面部正面超高清特写，头部至胸部肖像构图，头顶发型与发饰完整入画不裁切，构图下沿截至胸部，眼神平视前方，无表情自然放松，眼睛清晰锐利对焦，服装、领口、配饰与参考图严格一致。
中区（占画面宽度约 45%）：三张全身站姿图并排排列，人物鞋子完整入画，脚下干净柔和投影，三图头顶与脚底在同一水平线对齐，人物高度一致：中区左为全身正面站姿，中性站姿，手臂自然下垂；中区中为全身 90° 侧面站姿（面朝左），中性站姿；中区右为全身背面站姿。
右区（占画面宽度约 30%）：2 列 ×3 行肖像网格，六格等大，均为头部至胸部肖像构图，头顶发型与发饰完整入画不裁切，构图下沿统一截至胸部，服装、领口、配饰与参考图严格一致：第一行左为头部正面朝左 45° 无表情；第一行右为正背面视图；第二行左为低头 30° 眼神朝下看；第二行右为抬头 30° 眼神朝上看；第三行左为开心表情，嘴角上扬克制不夸张；第三行右为严肃表情。
```

> 配套：本卡 + 十章一致性锚点表 + C05 检查表 = 全片人物锁定三保险。古装/现代/道具三视图扩展版见归档「AI技能-归档\02-提示词模板库」。

### 用途

批量生成多条镜头时，防止同一人物/场景/光效跨镜头漂移（崩脸/换装/变光）。

### 使用方法

每条镜头生成前，把本表锚点原样粘贴进 prompt；跨镜头时锚点一字不改，只改动作/神态/运镜。

### 记录表模板

| 锚点类别 | 锚点内容（生成前填写） |
|---|---|
| 人物·身份 | 例：女主 |
| 人物·发式 | 例：少女发髻簪银钗 |
| 人物·服色 | 例：浅色襦裙 |
| 人物·面容 | 例：清秀温婉，眉眼含羞 |
| 场景·空间 | 例：朱门庭院 |
| 场景·光效 | 例：黄昏暖光，宫灯如豆 |
| 场景·动态元素 | 例：落红轻旋 |
| 道具·固定道具 | 例：雁笼系红绸结 |
| 风格·基调 | 例：古风影视质感，暖色调 |

### 锚点检查规则

1. 每条 prompt 中锚点段落**原样复制**，不得改写措辞
2. 只允许在"动作/神态/运镜"处换词
3. 生成后对比相邻镜头，若人物/场景漂移，回到本表检查漏改项
4. ComfyUI 进阶：固定 seed + 角色参考图，锚点仍保留

---

### 视频时长 → 镜头数速查表（做多长用多少镜）

| 视频时长 | 镜头数 | 每镜时长 | 结构（按顺序） |
|---|---|---|---|
| 15-30s | 3-4 镜 | 5-8s | 钩子 → 叙事 → 收束 |
| 30-60s | 5-7 镜 | 8-10s | 定场 → 叙事×3 → 情感特写 → 收束 |
| 1-3min | 10-18 镜 | 8-10s | 定场 → 叙事循环（每习俗/段落 2-3 镜）→ 情感特写 → 收束 |
| 3min+ | 20-30 镜 | 6-8s | 四段式循环（定场→叙事→情感→收束）×N，每循环 3-5 镜 |

> 用法：先定总时长 → 查镜头数 → 填「空白分镜脚本表」→ 逐镜生成 → 按「九、生成后拼接标准流程」拼接。

### 空白分镜脚本表（自排多镜头视频用·复制此表逐行填）

| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 文字卡（后期） | 对白/独白（后期） | 声音/BGM | 镜头参数 |
|---|---|---|---|---|---|---|---|---|
| 1 | 5-8s |  |  |  |  |  |  |  |
| 2 | 5-8s |  |  |  |  |  |  |  |

填写规则：
1. 1 镜头 = 1 个动作/习俗/事件，不贪多
2. 画面描述按「七、组装公式」写；人物锚点从「十」复制
3. 文字卡/对白全部后期叠加，不进生成 prompt
4. 首镜必须是钩子（见十五.4）；声音列参考「十八」
5. 排完 → 逐镜生成 → 按「九、生成后拼接标准流程」拼接

### Cinema DNA 镜头编排工具（V5.9 入库）

**① 镜头账本（每镜必填）**：

| # | 剧情功能 | 主要动作 | 观众位置 | 景别/焦段 | 构图压力 | 关键线索 | 与前镜变化 |
|---|---|---|---|---|---|---|---|
| 1 |  |  |  |  |  |  |  |

**② 相邻镜头至少变化以下 9 项中的 4 项**（专治“多镜头雷同”）：

`景别 / 机位高度 / 摄影机与主体距离 / 人物与环境比例 / 观看立场 / 构图机制 / 信息载体 / 焦点层 / 光线方向`（+人物状态）

**③ 每镜“5 个 1”**：1 个主要动作 + 1 个次要线索 + 1 个主要构图决定 + 1 个主光源（至多 1 个自然反射或次级实景光）+ 2-3 个具体场景信息。**人物必须在做事，不只是摆出情绪。**

**④ 多镜提示词模板（Cinema DNA·V5.10 入库）**——每镜 = 共同基底 + 单镜差异：

共同基底（英文·整段复制）：
```
Create one standalone live-action film still, ultra-wide 2.39:1 horizontal composition, no borders, no collage, no grid, no captions, no readable text, no watermark.
[era and practical location]
Continuity: [character anchors], [supporting character anchors], [key prop], [fixed environment].
[capture substrate], [physical color sources], [light-source rule].
no CGI spectacle, no glossy advertising, no HDR, no plastic skin, no television-drama polish.
```

单镜差异（英文骨架）：
```
SHOT [number] OF [total] — [story function].
[one primary action].
Camera: [physical position], [height], [distance], [lens/scale].
Composition pressure: [one mechanism].
Foreground / midground / background: [only decisive information].
Eye flow: [entry → interruption → landing → exit].
Secondary clue: [one clue].
```

**三镜焦段节奏**：Shot 1 用 24-28mm（人物占画面 5%-15%，环境主导）；Shot 2 用 32-50mm（人物 20%-35%，关系递进）；Shot 3 用 50-85mm（情绪收束/余韵）。多镜组里别每镜都用同一个焦段。

**三联叙事 6 模板速查**：进入式（外部建立→人物进入→内部停顿）/ 对峙式（空间建立→关系形成→紧张落点）/ 漫游式（世界→穿行→停顿回望）/ 发现式（接近未知→发现目标→情绪余韵）/ 孤独式（被世界包围→轻微互动→更空更静的结尾）/ 仪式式（空间权力建立→人物进入秩序→个体被结构吞没或突出）。

---

## 十一、示例：婚嫁全流程（三书六礼 · 7 镜头，约 63s）

> 【镜头数伸缩规则】
> - 30-60s 短视频：3-7 个镜头（本示例 7 镜；原片 63s / 7 镜 ≈ 9s 每镜，节奏合理）
> - 1-3 分钟中视频：10-18 个镜头（每习俗 2-3 镜）
> - 3 分钟以上长视频：按"定场 → 叙事 → 情感特写 → 收束"四段式循环，每段约 3-5 镜

> 【多镜头收尾规则（Cinema DNA·V5.8 入库）】收尾镜不是死物件：不要默认"空房间+主人公物件+悬疑余韵"。收尾镜可以是——身体压力后的喘息 / 群体视线或集体反应 / 关系站位发生变化 / 现场继续运行 / 规则被临时改写 / 人物没有解释但行动已经变了。物件残留可用，但不能成为默认公式。
> 本段仅为示例，演示如何把任意题材套进通用骨架。
> 做其他题材时，按「十三、题材适配表」替换：场景、人物造型、道具、文字卡、对白/文案，其余照抄。

### 镜头 1｜纳采（提亲送雁）

```
清晨，中式府邸朱红大门前，媒人着青绿色古装，双手捧一对大雁恭敬立于门前，
门内女主人侧身探看，面带笑意，门前挂红绸。
低机位缓慢推镜，从大雁特写推至媒人全身。
85mm 定焦，f/2.0，ISO 320，侧逆光暖调。
```

### 镜头 2｜问名（交换庚帖）

```
厅堂内，两家长辈相对而坐，交换红底金字庚帖，桌上摆茶盏与笔墨，
窗外透进暖光。45 度斜角中景，缓慢横移，定格在庚帖特写。
50mm 定焦，f/1.8，ISO 400，柔和窗光。
```

### 镜头 3｜纳吉（占卜合婚）

```
祠堂内，香案上摆签筒与龟甲，算命先生摇签占卜，红光映照，
签文落在红布上，气氛庄重。低机位仰拍香案与签筒，缓缓上摇。
35mm 广角，f/2.8，ISO 640，烛光暖调。
```

### 镜头 4｜纳征（下聘礼）

```
长街之上，聘礼队伍浩浩荡荡，抬着系红绸的箱笼（金银器、绸缎、茶叶、酒坛），
行人驻足围观，空中零星烟火。跟随队伍侧面横移，中景转全景。
24mm 广角，f/4.0，ISO 200，黄昏金光。
```

### 镜头 5｜请期（择吉日）

```
书房内，新郎父亲与媒人共看黄历择吉日，红烛高照，
婚书与礼单摊于案上，手指点在某吉日上。俯拍桌面推近，再切中景。
50mm，f/2.0，ISO 400，烛光暖调。
```

### 镜头 6｜亲迎（迎亲）

```
喜庆门楼下，新郎着红袍骑高头大马，迎亲队伍抬花轿吹吹打打，
红灯笼高挂，宾客撒喜糖，新娘盖头端坐轿中。
低机位仰拍门楼，缓缓环绕跟拍花轿。
35mm，f/2.8，ISO 320，灯笼暖光。
```

### 镜头 7｜收尾（拜堂之约）

```
新人牵红绸步入厅堂，宾客撒铜钱与花瓣，喜气盈门，画面渐暖收束。
缓慢拉远镜头，中景转大全景。
35mm，f/2.8，ISO 320。
```

---

## 十二、古今写真对照分镜（古代版 + 现代版各一套）

> 适用：氛围感写真短片、Citywalk、个人 IP 视频、古今对照系列
> 结构：两套 7 镜头一一对应（晨光↔晨起、街角↔廊桥、咖啡↔茶寮、黄昏↔宫墙、霓虹↔灯笼、雨夜玻璃↔檐雨、回眸↔回眸），同一情绪两种时空
> 玩法：剪成"古今对话"对照视频，或做两期发布（古风期/现代期），账号风格统一

### 一、古代写真版（7 镜头）

**统一基调**：
```
古风氛围感人像，水墨与暖光结合，电影感浅景深，轻微绢帛质感，
烛光/窗光/灯笼光，逆光勾轮廓，发丝光，1920x1080 横屏，
```

**镜头 1｜晨起对镜（对应现代：晨光窗边）**
> 清晨轩窗边，女子着素色襦裙坐于妆台前，晨光透过窗棂洒落，云鬓被光点亮，指尖轻抚镜中面容。缓慢推镜。85mm，f/2.0，ISO 320，自然晨光。

**镜头 2｜廊桥漫步（对应现代：街角过街）**
> 园林廊桥，女子着淡青长裙漫步，衣袂随风轻扬，池中锦鲤游过，回廊光影斑驳。侧面跟拍横移。35mm，f/2.8，ISO 200，散射天光，配环境声+古琴。

**镜头 3｜茶寮品茗（对应现代：咖啡店窗边）**
> 茶寮案前，女子跪坐捧青瓷茶盏，茶烟袅袅升腾，窗外竹影婆娑，指尖轻抚杯沿。45 度侧拍。50mm，f/2.0，ISO 400，窗光。

**镜头 4｜黄昏宫墙（对应现代：黄昏逆光）**
> 宫墙或亭台前，女子逆光而立，夕阳给轮廓镀金边，披帛飞舞，抬手轻挡光线。低机位仰拍。85mm，f/2.0，ISO 200，黄昏逆光，配纯箫声。

**镜头 5｜夜灯行街（对应现代：霓虹夜色）**
> 夜巷灯笼高挂，烛光映在女子面上，她穿月白长裙穿行于光影之间，忽而回眸。跟随镜头。35mm，f/1.8，ISO 800，灯笼暖光。

**镜头 6｜檐雨听声（对应现代：雨夜玻璃）**
> 雨夜，女子立于檐下，雨珠从瓦檐滴落，灯火在雨中晕开，指尖轻触雨帘，眼神放空。50mm，f/1.8，ISO 800，冷调雨夜+暖色灯火，配雨声+琵琶。

**镜头 7｜回眸定格（对应现代：回眸定格）**
> 暮色庭院，女子回眸浅笑，镜头缓慢拉远，画面渐暗收束。85mm，f/2.0，ISO 400。音效：BGM 渐弱，一声古琴泛音。

**古风氛围词库**：
| 氛围 | 关键词 |
|---|---|
| 晨光 | 窗棂透光、晨雾、金色晨光、低反差 |
| 黄昏 | 逆光剪影、披帛飞舞、暖橘色调、宫墙投影 |
| 夜景 | 灯笼暖光、烛影摇曳、暗部深邃、光晕晕开 |
| 雨天 | 檐雨滴落、青灰调、灯火晕染、湿润石阶 |
| 整体 | 绢帛质感、水墨意境、轻微颗粒、莫兰迪低饱和 |

### 二、现代写真版（7 镜头，结构完全对齐）

**统一基调**：
```
现代氛围感人像，电影感浅景深，轻微胶片颗粒，自然光为主，
逆光勾轮廓，发丝光，1920x1080 横屏，
```

**镜头 1｜晨光窗边**
> 清晨，主角着简约白衬衫坐于窗边，晨光斜照，发丝被光点亮，抬头望向光。缓慢推镜。85mm，f/2.0，ISO 320，自然晨光。

**镜头 2｜街角过街**
> 城市街角，主角着长风衣过马路，风吹起衣角，车流拖影虚化。侧面跟拍横移。35mm，f/2.8，ISO 200，上午散射光，配环境声+轻节奏 BGM。

**镜头 3｜咖啡店窗边**
> 咖啡店落地窗前，主角捧杯，蒸汽升腾，窗外路人虚化，指尖轻敲杯壁。45 度侧拍。50mm，f/2.0，ISO 400，窗光。

**镜头 4｜黄昏逆光**
> 天台或海边，主角逆光站立，夕阳镀金边，发丝飞舞，抬手轻挡光线。低机位仰拍。85mm，f/2.0，ISO 200，黄昏逆光，配纯氛围音乐。

**镜头 5｜霓虹夜色**
> 夜晚街巷，霓虹灯牌光映在脸上，主角穿深色外套漫步，光影交错，忽而回头。跟随镜头。35mm，f/1.8，ISO 800，霓虹冷暖对比。

**镜头 6｜雨夜玻璃**
> 雨夜，主角立于玻璃窗前，雨滴划过，窗外灯光晕成光斑，指尖轻触玻璃。50mm，f/1.8，ISO 800，冷调雨夜+暖色光斑，配雨声+钢琴。

**镜头 7｜回眸定格**
> 黄昏或夜色中，主角回眸微笑，镜头缓慢拉远，画面渐暗收束。85mm，f/2.0，ISO 400。音效：BGM 渐弱，一声快门。

**现代氛围词库**：
| 氛围 | 关键词 |
|---|---|
| 晨光 | 柔和自然光、金色晨光、低反差、通透 |
| 黄昏 | 逆光剪影、发丝光、暖橘色调、高光微溢 |
| 夜景 | 黑金色调、霓虹冷暖对比、暗部深邃、光斑虚化 |
| 雨天 | 青灰色调、玻璃水珠、冷调+暖色光斑、湿润反光 |
| 整体 | 胶片颗粒、莫兰迪低饱和、轻微偏绿、暗角 |

### 三、对照关系速查

| 镜头 | 古代版 | 现代版 |
|---|---|---|
| 1 | 晨起对镜「把日子过成诗」 | 晨光窗边「把生活过成电影」 |
| 2 | 廊桥漫步「风知道我的方向」 | 街角过街「风知道我的方向」 |
| 3 | 茶寮品茗「一盏茶，一个人的午后」 | 咖啡店窗边「一个人的下午茶」 |
| 4 | 黄昏宫墙「追光的人，也会发光」 | 黄昏逆光「追光的人，也会发光」 |
| 5 | 夜灯行街「灯影照夜归人」 | 霓虹夜色「城市的夜，属于晚归的人」 |
| 6 | 檐雨听声「等一场雨停，等一个晴天」 | 雨夜玻璃「等一场雨停，等一个晴天」 |
| 7 | 回眸定格「寻常，亦风华」 | 回眸定格「普通，但闪亮」 |

### 四、通用性说明

- 人物造型每镜头可替换（古代：襦裙/长裙/月白；现代：白衬衫/风衣/深色外套），文案可换成任何心情
- 运镜光影两版完全同构；字幕文案后期叠加（见第十四章）——"古今写真万能骨架"
- 换题材只需替换：造型 + 文案 + 场景，其余照抄


---

## 十三、题材适配表（通用化关键：换题材只改 5 个字段）

> 使用方式：确定题材后，按本表填写 5 列，其余（光影/运镜/结构/节奏/造型规范）照抄通用骨架。
> 本表未覆盖的题材，自己按同样格式填 5 列即可。

### 五字段公式

```
场景 + 人物造型 + 道具 + 文字卡 + 对白/文案
```

### 传统题材速查

| 题材 | 场景 | 人物造型 | 道具 | 文字卡示例 | 对白/文案示例 |
|---|---|---|---|---|---|
| 婚嫁（示例） | 府邸门楼/厅堂/长街 | 新娘红嫁衣凤冠、新郎红袍、长辈深色锦缎 | 大雁、庚帖、花轿、葫芦杯 | 纳采——男方遣媒提亲，以雁为礼 | 恭贺两姓之好 |
| 成人礼（笄礼/冠礼） | 祠堂/庭院 | 少女素衣簪笄、长辈深色礼服 | 发笄、醴酒、蒲团 | 筮日——占卜择定行礼之日 | 敬谢父母，永言孝思 |
| 拜师礼 | 私塾/学堂 | 弟子素袍、先生深色长衫 | 茶盏、束脩、戒尺 | 三拜——敬茶谢师，入室受业 | 一日为师，终身为父 |
| 抓周 | 厅堂红案 | 婴孩红肚兜、家人围坐 | 笔墨、算盘、印玺 | 抓周——陈物以试儿志 | 一抓定乾坤 |
| 茶礼 | 茶寮/庭院 | 素手茶人、青瓷盏 | 茶壶、茶则、茶烟 | 点茶——炙盏击拂，以见茶道 | 一期一会 |
| 元宵灯会 | 长街灯市 | 孩童提灯、少女提灯 | 花灯、河灯、灯谜 | 走百病——上元夜游，百病不侵 | 一夜鱼龙舞 |
| 七夕乞巧 | 庭院月下 | 少女浅色襦裙 | 针线、瓜果、香案 | 乞巧——月下穿针，以验手巧 | 愿乞天孙巧 |
| 中秋拜月 | 庭院香案 | 全家素装 | 月饼、瓜果、香烛 | 拜月——设案焚香，以敬月神 | 千里共婵娟 |
| 重阳登高 | 山巅/高台 | 老人佩茱萸 | 菊花酒、香囊 | 佩茱萸——辟邪去灾，以祝长寿 | 遍插茱萸少一人 |
| 制瓷 | 窑坊 | 匠人粗布围裙 | 拉坯、青花、窑火 | 入窑——一色出窑，万彩天成 | 入窑一色，出窑万彩 |
| 皮影 | 灯下戏台 | 艺人指间拨弄 | 皮影、白幕、烛灯 | 演皮影——灯下弄影，以物传神 | 一口道尽千古事 |
| 春节·贴春联 | 冬日清晨老宅门前，晨光斜照 | 老者深色棉袍，孩童红袄 | 春联、浆糊、红纸 | 总把新桃换旧符 | 福到了！ |
| 端午·赛龙舟 | 河岸人家，薄雾水面 | 白衣短打，发带束发 | 龙舟、船桨、香囊 | 端午——鼓声起，龙舟竞渡 | 一桨一浪，皆安康 |
| 打铁花 | 夜场高炉前，铁水飞溅如瀑 | 赤膊匠人，粗布腰带 | 熔炉、木勺、铁水 | 打铁花——铁水迸作万点金 | 一勺铁水，满天星河 |
| 鱼灯巡游 | 水乡夜巷，鱼灯成河，倒影摇曳 | 素衣提灯人 | 鱼灯、烛火、河面 | 鱼灯——灯游水上，年年有余 | 一夜鱼灯，满城如愿 |
| 英歌舞 | 街头百人方阵，锣鼓震天 | 脸谱武生，彩衣彩裤 | 英歌槌、锣鼓 | 英歌——锣鼓开道，武舞驱邪 | 英歌起，邪祟避 |
| 簪花围 | 蟳埔渔村，蚵壳墙前 | 女子簪花围，大裾衫阔脚裤 | 鲜花围、发簪 | 簪花——今生戴花，来世漂亮 | 头顶花园，身披朝霞 |
| 川剧变脸 | 戏台聚光，脸谱翻飞 | 戏服靠旗，勾脸谱 | 折扇、披风 | 变脸——一回头，千面人生 | 台上千面，台下一人 |
| 敦煌飞天 | 石窟穹顶，彩带飘飞 | 飞天霓裳，反抱琵琶 | 琵琶、飘带 | 飞天——反弹琵琶，衣袂生风 | 一眼千年，敦煌 |
| 山海经异兽 | 云雾山海间，神兽若隐若现 | 素衣寻兽人，提灯夜行 | 古卷、灯笼 | 异兽——北冥有鱼，其名为鲲 | 山海之外，皆是传说 |
| 舞龙 | 庙会长街，龙灯翻涌 | 彩衣舞龙队 | 龙灯、绣球 | 舞龙——龙身翻涌，万民同乐 | 龙抬头，好运来 |

### 现代题材速查

| 题材 | 场景 | 人物造型 | 道具 | 文字卡示例 | 对白/文案示例 |
|---|---|---|---|---|---|
| 手冲咖啡 | 咖啡店/窗边 | 白衬衫挽袖+围裙 | 手冲壶、滤杯、咖啡粉 | 手冲——注水三圈，萃取一杯 | 今日份清醒 |
| 早八通勤 | 地铁/街口 | 衬衫卫衣+背包耳机 | 咖啡杯、工牌 | 早八——咖啡续命，地铁冲锋 | 打工人已就位 |
| 深夜泡面 | 厨房/深夜 | 宽松T恤睡裤 | 泡面、热水、筷子 | 泡面三分钟——深夜灵魂的慰藉 | 三分钟，开吃 |
| 露营 | 山野营地 | 冲锋衣+渔夫帽 | 天幕、露营灯、炉火 | 搭营——天幕一开，烦恼走开 | 今晚住山野 |
| 演唱会应援 | 场馆 | 应援服+发光发箍 | 荧光棒、灯牌 | 应援——万人大合唱 | 全场大合唱 |
| 客制化键盘 | 电竞房 | 卫衣+耳机 | 键盘、键帽、RGB灯 | 敲击——手感清脆，段落分明 | 这个轴，爱了 |
| 新机开箱 | 书桌/卧室 | 居家T恤 | 手机盒、贴膜、数据线 | 开箱——撕膜一瞬，仪式感拉满 | 终于等到你 |
| 游戏五杀 | 电竞房 | 电竞椅+耳机 | 显示器、键盘、鼠标 | 五杀——一波团战，全屏喝彩 | 五杀！封神 |
| 跨年倒计时 | 广场/天台 | 羽绒服+围巾 | 烟花、手机、气球 | 跨年——零点一过，新年暴富 | 10、9、8……新年快乐 |
| 赛博国风 | 霓虹老街，红灯笼与全息屏同框 | 汉服青年，透明光感面罩 | 折扇、全息屏 | 国潮——古韵新生，赛博入梦 | 旧梦新潮，一眼千年 |
| 深夜便利店 | 雨夜街角，便利店灯箱独亮 | 加班族风衣，倦容 | 关东煮、雨伞、便当 | 深夜食堂——灯火为你留到天明 | 深夜的灯，给晚归的人 |
| 雨天窗边 | 雾窗咖啡馆，水珠滑落 | 素衣侧影，发呆 | 咖啡、玻璃水珠 | 雨天——世界安静，只有雨声 | 把下雨的天，留给发呆 |
| 微醺夜归 | 天台/街灯下，晚风 | 松弛便装 | 啤酒罐、手机 | 微醺——八分清醒，两分自由 | 今晚的月亮，替我喝一杯 |

### 巨物观（Colossal / Scale——AIGC 顶流题材，跨古今通用）

> **核心逻辑**：主体尺度远超常理，人物只是「尺度参照物」——画面一半以上留给巨物，人小到只剩轮廓。
> **光影公式**：巨物用逆光/剪影/顶光压暗，云雾或雨雾拉开纵深，忌平光；人物用一束侧逆光勾边。
> **运镜公式**：极慢仰推或环绕，让巨物慢慢「压」进画面；忌快切快摇，破坏压迫感。
> **氛围**：巨物沉默不语，声音只剩风声/水声/心跳般的低频。

| 变体 | 场景 | 人物造型 | 道具 | 文字卡示例 | 对白/文案示例 |
|---|---|---|---|---|---|
| 巨佛垂目 | 云海翻涌，巨佛半身隐于雾中 | 渺小旅人，素衣斗笠，仰首 | （无——尺度即道具） | 巨物——人在佛前，如芥子 | 万法皆空，我自仰首 |
| 巨鲸悬空 | 暮色城市上空，巨鲸云中游弋 | 天台青年，仰头凝望 | 鲸尾掠过云层 | 巨物——天上有鲸，人间仰望 | 鲸落之后，天上有城 |
| 巨人穿行 | 薄雾长街，巨人缓步踏过楼群 | 街角孩童，仰望 | 巨足跨过楼顶 | 巨物——祂在人间行走 | 一步一城，不可名状 |
| 微观世界 | 巨大茶杯/键盘/书本旁，人被缩小 | 小人国装束，好奇张望 | 巨型日常物 | 微缩——世界放大一万倍 | 你是我掌心的一粒沙 |

> 组合玩法：巨物 + 古风 = 云海巨佛/山巅神像；巨物 + 现代 = 都市巨鲸/巨人穿行；
> 巨物 + 科幻 = 机甲巡城/外星舰悬停。基调用〇章 V2（清冷意境）或 V4（赛博霓虹）最出效果。

### 换题材操作步骤

1. 确定题材 → 在本表找到对应行（或自己按 5 列格式填）
2. 以「八、通用骨架模板」为骨架
3. 将场景/人物/道具/文字卡/文案 5 列替换进每个镜头
4. 光影、运镜、节奏、结构照抄，一字不改
5. 人物造型细节按「四、人物造型与动作神态」补全

### 题材字段填空模板（任意题材自己填）

| 字段 | 填什么 | 示例（茶礼） |
|---|---|---|
| 场景 | 时代基调 + 空间 + 材质 + 光效 | 庭院竹影，晨光透窗棂，茶烟袅袅 |
| 人物造型 | 身份 + 服色 + 发饰 | 素衣女子，发髻簪竹簪 |
| 动作·道具·神态 | 动作 + 道具互动 + 微表情 | 执壶注水，指尖轻稳，眉眼专注 |
| 光影 | 光源 + 光位 + 光质 | 窗棂侧逆光，柔光，晨雾感 |
| 文字卡/字幕 | 后期叠加，不进画面 | 一盏清茶，半日闲 |

> 自定义题材时：表里没有 → 用上面 5 行填一遍，即成为该题材的适配行。

### 自定义题材填写示范（春节·贴春联）

| 字段 | 填写内容 |
|---|---|
| 场景 | 冬日清晨，老宅大门前，晨光斜照，红纸金墨 |
| 人物造型 | 老者着深色棉袍，孩童着红袄，眉眼含笑 |
| 动作·道具·神态 | 老者手持春联，孩童踮脚递浆糊，祖孙相视而笑 |
| 光影 | 侧逆光暖调，晨雾中光束斜射 |
| 文字卡/字幕 | 总把新桃换旧符 |


---

### 饮食道具速查表（写家宴/茶点/市集吃食用）

| 类别 | 道具词 | 材质+光效写法 |
|---|---|---|
| 糕点类 | 桂花糕 / 桃酥 / 龙须酥 / 枣泥糕 / 定胜糕 / 月饼 | 白瓷碟托桂花糕，暖光下糕体泛蜜色油光，细碎糖粉浮光 |
| 汤羹类 | 莲子羹 / 银耳羹 / 鱼汤 / 鸡汤 / 羹碗 | 粗陶碗盛热羹，蒸汽在光柱中升腾盘旋，碗沿釉光温润 |
| 酒水类 | 米酒 / 黄酒 / 青梅酒 / 果酿 / 屠苏酒 | 酒液挂杯泛琥珀光，酒樽沿口反光，杯壁凝水珠 |
| 面食类 | 汤面 / 馄饨 / 炊饼 / 胡饼 / 春卷 | 面汤油光浮于表面，热气氤氲，筷尖挑起面条带起细雾 |
| 果品类 | 石榴 / 枇杷 / 蜜桃 / 柿子 / 葡萄 | 果皮泛新鲜水光，切面汁水透亮，瓷盘映出果影 |
| 宴席类 | 八仙桌 / 圆桌围坐 / 长案 / 杯盏成列 / 果盒 | 满桌杯盏在烛光下泛温润光，菜肴热气交织成雾，长辈居中 |

**家宴写法示例**：中秋家宴——八仙桌围坐，满桌杯盏在烛光下泛温润光泽，桂花糕与月饼瓷碟相映，蒸腾热气在灯笼光里缓缓上升，老人居中，孩童绕桌嬉闹。

### 题材滚动扩充库（第九阶段·V4.0 按热点滚动追加）

> 分类选题清单。状态：已有 CASE = CASE 库已覆盖；已有表行 = 十三/六维表已覆盖；待补 = 下一轮 CASE 扩充候选。

**节日类**：

| 题材 | 状态 |
|---|---|
| 春节 | 已有 CASE（CASE11） |
| 元宵 | 已有 CASE（CASE12） |
| 清明 | 已有 CASE（CASE18） |
| 端午 | 已有 CASE（CASE13） |
| 七夕 | 已有 CASE（CASE15） |
| 中元 | 待补 |
| 中秋 | 已有 CASE（CASE14） |
| 重阳 | 已有 CASE（CASE17） |
| 冬至 | 已有 CASE（CASE19） |

**民俗类**：

| 题材 | 状态 |
|---|---|
| 庙会 | 待补 |
| 社火 | 待补 |
| 舞龙 | 已有表行（十三） |
| 舞狮 | 待补 |
| 花灯 | 已有表行（十三·元宵灯会） |
| 祭祀 | 已有表行（十三）+素材库 |
| 婚嫁 | 已有 CASE（CASE10）+十三表 |
| 成人礼 | 已有 CASE（CASE16） |
| 寿礼 | 待补 |

**手工艺类**：

| 题材 | 状态 |
|---|---|
| 刺绣 | 已有表行（六维表·绣花）+素材库 |
| 造纸 | 待补 |
| 制陶 | 已有表行（十三·制瓷） |
| 制香 | 已有表行（六维表·香道） |
| 制茶 | 已有表行（六维表·采茶/点茶） |
| 木作 | 待补 |
| 织布 | 已有表行（六维表·织布） |
| 染布 | 待补 |

**日常生活类**：

| 题材 | 状态 |
|---|---|
| 梳妆 | 已有表行（六维表·晨妆）+素材库 |
| 点茶 | 已有 CASE（CASE01）+六维表 |
| 焚香 | 已有表行（六维表·香道） |
| 读书 | 已有表行（六维表·读书） |
| 洗衣 | 已有表行（六维表·洗衣） |
| 晒谷 | 已有表行（六维表·打谷） |
| 赶集 | 待补 |
| 做饭 | 已有表行（六维表·古代饮食） |
| 庭院劳作 | 待补 |

> 待补题材（中元/庙会/社火/舞狮/寿礼/造纸/木作/染布/赶集/庭院劳作）按热点优先级逐个补 CASE21+。

## 十四、后期字幕文案清单（不进入生成画面，剪辑时叠加）

> 以下所有文字卡与对白/独白文案均不写入视频生成 prompt，
> 由生成后再用剪辑软件叠加，避免 AIGC 错字变形。
> **其他题材**：文字卡/对白直接取「十三、题材适配表」对应行的「文字卡示例/对白文案示例」列；
> 自定义题材用「十三、填空模板」自填，本清单仅列婚嫁全量稿。

### 一、三书六礼（第十一章）

| 镜头 | 文字卡（叠加） | 底部字幕（叠加） |
|---|---|---|
| 纳采 | 纳采——男方遣媒提亲，以雁为礼，寓意忠贞 | 今日特来提亲，愿结两姓之好 |
| 问名 | 问名——问女方姓名生辰，以卜婚姻吉凶 | 敢问令爱生辰八字 |
| 纳吉 | 纳吉——占卜合婚，得吉兆则婚约成立 | 卦象大吉，天作之合 |
| 纳征 | 纳征——男方送聘礼，婚约正式缔结 | 恭贺两姓之好 |
| 请期 | 请期——择定吉日良辰，通知女方 | 就定这月十八，诸事大吉 |
| 亲迎 | 亲迎——新郎亲往女家迎娶新娘 | 吉时已到，起轿！ |
| 收尾 | （无） | 三书六礼，白首之约 |

## 十五、创作避坑与运营（画面之外的另一半）

### 1. 人物一致性（AIGC 视频最大的坑）

同一个人物跨镜头脸崩是 AIGC 视频的头号问题。解法：**每个镜头 prompt 里把"人物锚点"原样重复**（发式+服色+发饰+年龄感，一字不差），只在"神态动作"处换词。

```
例：女主锚点固定为——浅色襦裙、少女发髻簪银钗、面容清秀温婉
   每个镜头都原样粘贴，只替换神态动作部分
```

进阶：ComfyUI 固定 seed / 用角色参考图 / 锁住模型，一致性更高。

> 【参考图原创隔离（Cinema DNA·V5.9 入库）】参考图只允许抽取 **1 个主维度**（构图方法 / 配色方法 / 题材方向），其余必须原创。禁止复用：相同人物数量与位置、人物关系、动作节点、道具组合、空间骨架、标志性机位、综合色与剧情结果。若同时借用两个以上主维度，或一眼认出某具体电影静帧/海报/现成 IP 轮廓，必须重写。最终 prompt 不要依赖导演名或电影名，把审美翻译成可见的布景、服装、光源、构图、材质和曝光事实。

### 2. 声音三层设计（原片一半的灵魂）

| 层 | 说明 | 示例 |
|---|---|---|
| 对白 | 人物台词，音色区分身份 | 女主温婉女声、男主低沉男声、长辈慈祥 |
| BGM | 按剧情递进 | 开头舒缓 → 迎亲喜庆鼓点 → 拜堂庄重 → 合卺温情 |
| 音效 | 点题拟音 | 鞭炮声、铜钱落地声、丝竹声、脚步衣料声 |

一个"撒帐"镜头，有铜钱声和没有，质感天差地别。

### 3. 字幕与文字卡（全部后期叠加）

- 所有文字卡、字幕、对白均不进入生成画面，由后期剪辑叠加
- 文案直接取「十四、后期字幕文案清单」，字体用书法体 + 半透明底 + 描边

### 4. 节奏与钩子（完播率设计）

- 每镜头约 8 秒；开头第一镜必须是**钩子**（有悬念的画面 + 抓人台词），3 秒内抓住观众

> 【不可立即解决的状态（Cinema DNA·V5.9 入库）】钩子怎么写：用一句**可拍摄的事实**描述冲突，不用“孤独/神秘/诗意/紧张”等情绪词代替剧情。有效例：“唯一的座位已经分配，但现场出现了更需要它的人”“仪式必须继续，负责执行的人却改变了立场”。古风例：“花轿已到门前，新娘却发现婚书上的名字不是自己的”。

**物理约束清单**（冲突的可拍摄写法，比情绪词有用）：唯一座位 / 一扇只能单向开启的门 / 固定时间移动的日光 / 只够一人通过的通道 / 已经启动的仪式或比赛程序 / 被切断的队列·轨道·绳索·边线·视线 / 必须由人维持的机械动作。

**故事动词表**（每镜必须有动作动词，不只是氛围）：到达 / 等待 / 穿越 / 隐藏 / 打开 / 研究 / 拒绝 / 修理 / 倾听 / 发现 / 放弃 / 跟随 / 返回 / 失去 / 移除 / 烧毁 / 锁上 / 离开。

**空间叙事痕迹**（场景里至少留一处）：没喝完的水 / 被拉开的椅子 / 半开的门 / 凌乱床铺 / 风吹起的帘幕 / 地面积水 / 还亮着的一盏灯 / 遗留衣物 / 远处离开的人。

**生成被安全拦截时的改写**（不改剧情）：把“危险/束缚/伤害/儿童困境”类措辞改成安全等价状态——如“抵达避难处”“在成人陪同下等待”“设备停止后手动维持”。保留角色关系、视觉线索、镜头功能。
- 1 个镜头 = 1 个习俗，不贪多；结尾四字祝词收束留余韵（"愿将红叶之盟"）
- 反面例子：开头给"媒人捧雁登门"这种平铺镜头，观众 3 秒就划走
- 正确做法：先给新娘回眸 / 新郎被堵门这类有悬念的镜头，再讲习俗

**3 秒钩子公式（开头第一镜专用）**

```
反常画面（悬念/瞬间/特写）+ 抓人对白（设问/冲突/金句）+ 3 秒内必有动作或声音
```

钩子画面四选一：
- 反常细节：不该出现的东西出现了（嫁妆箱底的信 / 空轿子里的一双鞋）
- 关键瞬间：动作进行到一半被定格（掀盖头 / 推门 / 回头）
- 大特写：瞳孔 / 手 / 物件特写先入画，再拉全
- 声先至：先听见声音（更鼓 / 哭喊 / 水声）再出画面

钩子对白 10 条（可换题材复用）：
1. "这门亲事，她怎么不知道？"
2. "红烛烧到一半，她才发现嫁妆箱底压着一封信。"
3. "满城都说他家有喜——只有她知道，轿子里是空的。"
4. "喜帖发出去了，新郎却不见了。"
5. "所有人说这是福气，她只觉心里一沉。"
6. "拜堂那日，她掀开盖头，看见的人不是他。"
7. "这盏茶凉了三次，人还没来。"
8. "她爹说这门婚事是天上定的——可天，也有打盹的时候。"
9. "一顶轿子抬进去的是新娘，抬出来的……是另一个她。"
10. "这场婚礼，是拿她换来的。"

### 5. 知识考据（评论区翻车点）

- 习俗内容必须有出处、经得起查（"撒谷豆压煞气""合卺红绳相系"均为真实出处）
- 错一个细节，评论区就会有人纠错，影响账号权重
- 冷门细节反而是流量点："还有这种习俗？"引发收藏转发

### 6. 系列化（一鱼多吃）

- 长流程拆 2-3 集发布（如：上集=婚前六礼；下集=婚礼当天），不在一集塞满
- 账号统一视觉：固定水印、固定字体、固定片头，形成辨识度
- 每集结尾留钩子："下一集讲古代闹洞房"
- 节日排期：按「附录·节日与题材排期指南」提前 1-2 周准备节日内容，流量高峰期（春节/端午/中秋/七夕/元宵）提前排期

### 7. 通用古风金句库（结尾祝词/氛围文案/钩子句·跨题材）

**结尾祝词（视频收尾·四字句）**

```
白首之约 / 岁岁常相见 / 共赴山海 / 此间风月，与君共度 /
明月入怀，清风满袖 / 一生一世一双人 / 山河远阔，人间烟火 / 岁岁年年，共此良辰
```

**氛围文案（配文/字幕点缀）**

```
一袭红衣入梦来 / 半盏清茶，半卷闲书 / 人间忽晚，山河已秋 /
陌上花开，可缓缓归矣 / 晚来天欲雪，能饮一杯无 / 山有木兮木有枝
```

**钩子句（通用向·可换题材）**

1. "所有人都以为他早已忘记——直到那天，她收到一封信。"
2. "这座宅子住了十年，她第一次听见那扇门响了。"
3. "她说她认命了。可那晚，她翻出了压在箱底的剑。"
4. "没人知道她为什么要在那天回村。"
5. "他等的人，十年前就死了。可今天，他看见了她。"

---

## 十六、各平台 Prompt 适配速查表

### 平台差异总表

| 平台 | 单次时长 | prompt 写法 | 负面词 | 参考图 | 说明 |
|---|---|---|---|---|---|
| 豆包 / Seedance | 5-15s（2.5 支持 5-30s） | 中文自然语言，吃完整段落 | 不支持 | 支持首尾帧 | 本模板默认平台 |
| 可灵 Kling | 5s / 10s | 吃长 prompt，一段一镜整段喂 | 支持 | 支持参考图/首尾帧 | 中文友好，整段粘贴即可 |
| MiniMax 海螺 H3 | 4-15s（延伸可至 ~30s） | 中文自然语言，吃完整段落，可单片段多镜头叙事 | 不支持 | 支持参考图/关键帧/全能参考 | 2K 原生立体声，开源可跑 ComfyUI，整段粘贴即可 |
| 即梦 Dreamina | 5s（部分 10s） | 更吃短句，一镜一句，重点词靠前 | 支持 | 支持参考图 | 中文友好，需拆短句 |
| Runway | 5s / 10s | 吃英文，短句 + 风格词 | 部分模型支持 | 支持参考图 | 需翻成英文 |
| Flova 1.0 | 剧本生视频 Skill 出分镜素材（Nano Banana 出图 + Seedance 2.5 480p）；MJ v8.2 --ar 16:9 --stylize 200 --raw | 英文长段整段（中文对话栏同步给） | 不支持（画面文字另处理） | 支持上传剧本（文本/图片/PDF） | 上传剧本自动拆镜出中英提示词；2026-09-07 实测（七夕乞巧 8 镜） |
| Sora | 10-20s | 吃长描述，自然语言整段 | 暂不支持 | 支持参考 | 英文 |

### H3 提示词标准结构（V5.11 入库·MiniMax 官方规范·五模式）

> 文档 CASE 目前都是 I2VA（首帧图生视频）写法。H3 官方共 5 种模式，首行对齐指令 + 三字段正文是硬规范。照抄下面格式可扩展出 FL2VA（首尾帧）/ L2VA（尾帧）/ T2VA（文生）/ Ref2VA（全参考）。搜「H3」或「五模式」调出。

**五模式速查**：

| 模式 | 全称 | 用途 | 首行对齐指令（提示词第一条） |
|---|---|---|---|
| T2VA | 文生视频 | 纯文字直接生成 | 无（直接写三字段正文） |
| I2VA | 首帧图生视频 | 给首帧图，从图向前发展 | For the target video, at 0.00 seconds into the target video, <Picture 1> (from [Shot 1]) is fully referenced. |
| FL2VA | 首尾帧视频 | 给首帧+尾帧，中间连续插值 | How the reference pictures align with the target video — Picture 1 (from Shot 1) aligns with the 0.00-second mark of the target video; Picture 2 (from Shot N) aligns with the S.SS-second mark of the target video. |
| L2VA | 尾帧视频 | 只给尾帧，倒推前段收束 | How the reference pictures align with the target video — <Picture 1> (from [Shot N]) aligns with the S.SS-second mark of the target video. |
| Ref2VA | 全参考模式 | 多图/视频/音频全参考 | 六段式：subject_definitions → summary → retention_analysis → detailed_description → overall_soundscape → non_diegetic_music |

**三字段正文结构（所有模式共用，首行对齐指令后空一行）**：
```
integrated_multimodal_description: [Shot 1] ...

overall_soundscape: ...

non_diegetic_music: ...
```

- integrated_multimodal_description：主线，按时间轴写画面/动作/镜头/说话人/对白/内部声音。首镜不写时间戳；后续镜头写严格递增切点：`[Shot 2] At 00:03.500, the camera cuts to...`
- overall_soundscape：全片环境声 + 动作声 + 非语言人声的汇总
- non_diegetic_music：只有观众能听到的 BGM（角色听不到）

**运镜三要素**：运动类型（Push In / Zoom In / Pan / Truck / Tilt / Arc / Tracking / Static）+ 幅度（大/中/小）+ 速度（快/中/慢）。幅度与速度有意义才写，中幅度常速可省略。I2VA 推荐结构：首帧锚点 → 动作开始 → 连续发展 → 结果/反应；FL2VA：首帧状态 → 中间可见变化 → 差异收窄 → 尾帧状态；L2VA：合理前段 → 明确动作路径 → 尾段收敛 → 尾帧落定。

**写法红线（官方）**：主体/动作/时序/运镜/物理因果/灯光/一致性优先；不堆「电影感/8K/超清」形容词；对白和画面文字保持原文语言；提示词上限 7000 字符；英文为主体，对白/画面文字保留原文。

> 万能母模板（完整中文版——把创意 + 素材丢给 AI 自动产出上述结构）已归档：「AI技能-归档\02-提示词模板库\# MiniMax H3 全能视频提示词母模板.txt」。

### 平台 → 比例 → 运镜建议（做哪个平台用哪个比例）

| 平台 | 推荐比例 | 运镜调整 |
|---|---|---|
| 抖音 / 快手 | 9:16 竖屏 | 人物居中，少横移（竖屏横移易晕） |
| 视频号 / B 站 | 16:9 横屏 | 默认 |
| 小红书 | 3:4 / 4:3 | 居中构图，主体占画面 2/3 |
| 影院感 | 2.35:1 宽银幕 | 加黑边（上下裁切） |

> 横屏裁竖屏会丢两侧信息——做抖音/快手**一开始就用 9:16 生成**，别指望横屏后裁。
> 同一套素材适配多平台：竖屏主体居中构图 → 横屏版保留中段即可（裁左右）。

### 5 秒镜头拆分策略（工具只支持 5s 时）

> 为什么要拆 5 秒？大部分 AI 工具免费版/标准版只支持 5s 单次生成。
> 为什么锚点要原样保留？换场景/换人物会导致跨镜头漂移，锚点是锁住人物和场景的定海神针。
> 不想拆？换用支持 10-15s 的工具（豆包 2.5 / 海螺 H3 / Sora），整段生成。

> 10-15 秒的镜头，拆成 2-3 段 5s 分别生成，再拼接。

1. **拆三段**：段① 起幅（场景定场 + 人物入画）→ 段② 动作（完成核心动作）→ 段③ 落幅（神态/细节定格）
2. **衔接点选在"动作中段"**（抬手一半 / 转身途中），不要选静止处，拼接更顺
3. **拼接时叠化 0.3s**，视觉无缝
4. 拆段时锚点段落（十章）原样保留，只改动作动词与景别

### 喂 prompt 的通用原则

- 平台吃长 prompt → 直接粘「七、组装公式」整段
- 平台吃短句 → 拆成"场景一句 + 人物一句 + 动作一句 + 运镜一句 + 参数"，重点词放句首
- 任何平台：文字卡/字幕绝不进画面，后期叠加

### MiniMax H3 专属提示（海螺 3.0）

1. **无需拆 5 秒**：H3 单次 4-15s，镜头直接整段粘贴「七、组装公式」；15s 以上的镜头拆两段，衔接点选动作中段
2. **原生立体声**：声音可直接生成——把「十八」的 BGM 情绪写进 prompt 尾部，对白/音效后期再精修
3. **参考图/关键帧防漂移**：首帧用「十章锚点表」出图，再走图生视频，人物一致性最稳
4. **单片段多镜头叙事**：一个 prompt 可写"场景 A → 场景 B"连续情节（如纳采→迎亲），H3 自行转场
5. **比例**：文生视频可选 21:9 / 16:9 / 4:3 / 1:1 / 3:4 / 9:16；图生视频跟随参考图比例

### 平台实测参数对照表（第八阶段·V4.0 预留·待实测填写）

> ⚠️ 平台迭代快（豆包/可灵/海螺每月更新），每项必须带测试日期 + 模型版本，半年后作废重测。下表为结构框架，参数待实测后逐格填写。

| 平台 | 模型版本 | 测试日期 | 推荐分辨率 | 推荐比例 | 单镜时长 | Prompt 长度 | 首帧要求 | 图生视频方式 | 运镜写法 | 负面词支持 | Seed/参考图 | 人物一致性方法 | 延长视频方法 | 容易翻车动作 | 最适合 CASE |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 豆包 2.5 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 |
| 可灵 1.6 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 |
| 海螺 H3 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 |
| 即梦 4.0 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 |

> 每格填写格式：值 +（2026-XX-XX·vX.X）。例如"1080P 竖屏（2026-09-07·v2.5）"。实测方法：同一条 prompt 四平台各跑 1 次，记录响应偏好、崩点与成功率。

---

## 十七、负面提示词库（"不要什么"跟"要什么"一样重要）

> ⚠️ 任何含文字的物体（婚书/庚帖/对联/牌匾/招牌）都禁止出现在生成画面中，一律后期叠文字卡——AIGC 文字乱码率接近 100%。

### 按镜头类型的通用 Negative Prompt

| 镜头类型 | Negative Prompt（直接复制） |
|---|---|
| 含文字画面（最高优先级） | 乱码, 错字, 扭曲文字, 无意义符号, 字体变形（任何文字不进画面，一律后期叠加） |
| 人像近景/特写 | 手部畸形, 六指, 多指, 手指粘连, 五官错位, 双眼无神, 脸崩, 多余肢体, 过度磨皮 |
| 多人同框 | 多张脸, 五官融合, 人物重叠, 脸崩, 肢体错乱, 多余人物, 人数不符 |
| 古风场景 | 现代物品穿帮, 塑料质感, 廉价道具, 饱和度过高, 西方建筑, 电子设备 |
| 动态运镜镜头 | 画面抖动, 扭曲变形, 残影, 闪烁, 帧间跳变, 物体撕裂 |
| 通用兜底 | 低质量, 模糊, 水印, 噪点, 过曝, 欠曝, 饱和度溢出, 锐化过度, 变形 |

### 用法

1. 每条 prompt 后追加对应镜头类型的 Negative Prompt
2. 人像镜头必加：手部 / 五官类
3. 含手部动作的镜头，负面词第一位写"手部畸形、六指"
4. **V5.15 追加**：完整镜头建议配「二十」章技术底座（20.1 正向约束）+ 禁令速查（下）：无配乐、无自动字幕、无随机路人、无角色重复、无漂浮、无游戏 CG 感、无塑料光滑面、无镜头光晕（指定除外）、无慢动作（指定除外）、对白严格按指定内容。

---

### Cinema DNA 反模板清单（V5.8 入库·英文可直接拼进负面词）

> 来源同上。专治"AI 味电影感"：CG 概念图、游戏 key art、AI 壁纸、广告灯光、偶像剧调度、青橙滤镜。

**中文清单（对照自查·避免以下效果）**：
CG 概念图 / 游戏宣传图 / AI 壁纸 / 过度光泽皮肤 / 通用青橙调色 / 过量雾、粒子与轮廓光 / 时尚摆拍（当任务需要叙事时）/ 电视剧机位 / 抄袭某导演镜头或现成 IP / 永远用废弃物件收尾 / 用"空房间+主人物件+悬疑余韵"当第三镜套路 / 靠万能纸条钥匙照片解释剧情 / 靠导演名电影名堆"电影感"

**英文负面段（整段可复制·拼进负面词）**：
```
no collage, no grid, no captions, no watermark, no CGI concept art, no game key art, no glossy AI rendering, no HDR, no plastic skin, no excessive particles, no teal-orange grading, no artificial rim light, no commercial beauty lighting, no television-drama blocking
```

**英文避空泛词（不要写进 prompt）**：masterpiece / epic / beautiful / dramatic / volumetric / highly detailed / rich detail

#### Cinema DNA 反油腻与东方题材负面（V5.10 入库）

**反油腻·优先写 / 避免写**（史诗/古代/巨构题材最易滑向游戏概念图）：

- 优先写：实拍电影剧照 / 真实外景或实景搭建 / 自然曝光 / 可见光源 / 哑光石材 / 氧化金属 / 粗麻布·旧皮革·磨损木材 / 灰尘·烟·风·汗·泥·划痕·脚印 / 人物疲惫克制、处于动作过程 / 服装有重量和脏污
- 避免写：epic / ultra detailed / masterpiece / hyperreal / 8k / volumetric fantasy / 英雄站姿 / 宣传海报感 / 发光轮廓 / 魔法边缘光 / 无来源蓝橙双光 / glossy / polished / sleek / shiny / perfect surface / Unreal Engine look / CGI render / game cinematic / concept art / digital painting

**东方题材负面追加段（英文·拼进负面词）**：
```
no xianxia glow, no magical sword aura, no plastic armor, no costume drama beauty filter, no generic ink overlay, no dragon or phoenix symbolism unless requested
```

**暖金过度校准句式**：把 `warm golden cinematic light` 改成 `aged tungsten practical light, amber but dirty and low-output`；暖色只允许在灯具、窗边、火光或局部反光中出现，不允许铺满全图成为蜂蜜金色。

---

## 十八、声音设计（BGM 情绪对照 + 音效词库）

### BGM 情绪对照表

| 画面情绪 | BGM 风格 | 关键词 |
|---|---|---|
| 庄重仪式 | 古琴 / 编钟 / 箫 | 空灵, 缓慢, 留白 |
| 喜庆热闹 | 民乐合奏 / 鼓点 | 欢快, 锣鼓, 红绸感 |
| 静谧治愈 | 古筝独奏 / 钢琴 | 轻柔, 呼吸感, 治愈 |
| 现代都市 | Lo-fi / 轻爵士 | 松弛, 律动, 氛围 |
| 悬念推进 | 弦乐渐强 / 低音鼓 | 紧张, 暗涌, 推进 |

### 音效关键词库（后期配音效时用）

```
衣料摩擦 / 脚步声 / 铜钱落地 / 鞭炮声 / 烛火噼啪 / 杯盏碰撞 / 翻书页 / 风声 / 雨声 /
心跳声 / 珠帘碰撞 / 木门吱呀 / 落水声 / 鸟鸣 / 更鼓 / 寺钟 / 摇橹 / 市集叫卖 /
织机梭声 / 纺车吱呀 / 柴火噼啪 / 竹筛扬谷 / 水滴入缸 / 马蹄声 / 车轮碾过石板 /
纸鸢哨音 / 银簪落地 / 丝竹轻奏 / 唢呐 / 锣鼓 / 蝉鸣 / 蛙声 / 雪落无声 / 折扇开合 /
磨墨声 / 茶壶注水 / 杯盖轻扣 / 剑出鞘 / 衣带拂风
```

### 声音三层结构（回顾）

1. 对白/独白（后期配音或 AI 配音，文案见「十四」）
2. BGM（按上表情绪选风格）
3. 环境音效（按画面点，宁缺毋滥，1-2 个即可）

### 声音组合公式（环境音 + BGM + 重点音效）

```
声音组合公式 = 环境音（定空间）+ BGM（定情绪）+ 重点音效（定节奏点）
```

示例（纳采镜头）：
- 环境音：晨间鸟鸣 + 远处犬吠
- BGM：古琴泛音起，慢速
- 重点音效：脚步踩在青砖上 + 衣料摩擦声

### 对白配音选角速查表（AI 配音选声线用）

> 对白是情绪的直接载体。选错声线，画面再美也出戏。

| 角色类型 | 推荐声线 | 语速 | 情绪基调 | 例句（按此调读） |
|---|---|---|---|---|
| 女主（少女/新娘） | 温婉女中音，气声偏多 | 缓（约 3-4 字/秒） | 含羞、柔韧、欲言又止 | "今日特来提亲，愿结两姓之好。" |
| 女主（成熟/贵妇） | 端丽女低音，字正腔圆 | 中缓 | 从容、有分量 | "这门婚事，是天上定的。" |
| 男主（青年/新郎） | 清朗男中音，气息稳 | 中（约 4-5 字/秒） | 庄重、深情、克制 | "吉时已到，起轿！" |
| 男主（中年/长辈） | 醇厚男低音，微带沙哑 | 中缓 | 郑重、慈爱、有阅历 | "就定这月十八，诸事大吉。" |
| 旁白（叙事/科普） | 中性偏暖，不带口音 | 中缓 | 客观、诗意、有留白 | "三书六礼，白首之约。" |
| 孩童 | 清亮童声，气息短 | 稍快（约 5 字/秒） | 天真、雀跃、好奇 | "福到了！" |

**对白混音三原则**（剪辑时调）：

1. **对白 > BGM**：对白电平比 BGM 高 3-6dB，确保听得清
2. **BGM > 环境音**：环境音（雨声/风声/市集声）比 BGM 低 3-6dB，不抢戏
3. **对白不压重要音效**：重要音效（开门声/掷杯声/脚步声）与对白错开 0.3s 以上，不重叠

**AI 配音工具推荐**：

- 剪映（免费，中文自然，情绪可选）—— 最快
- 即梦（情绪丰富，声线多）—— 最自然
- 十一 labs（英文最佳，中文需订阅）—— 专业级
- 海螺 H3（直接生成带对白的视频，原生立体声）—— 一体化解法

### 视频配乐三段式结构（30 秒标准片·直接套）

| 时段 | 功能 | 做法 | BGM 关键词 |
|---|---|---|---|
| 0-5s | 氛围铺垫（定调） | 环境音+单乐器起，留白，先把空间立起来 | 古琴泛音 / 风声 / 远处人声 / 单音长音 |
| 5-20s | 叙事主旋律（匀速） | 主旋律进入，节奏匀速，贴着主体动作走 | 民乐合奏 / 钢琴主题 / 中速鼓点 |
| 20-30s | 情绪释放（渐强/收束） | 渐强到高潮后收束，留最后一拍余韵 | 鼓点锣镲渐强 / 弦乐渐弱 / 尾音留白 |

**30 秒婚嫁示例配乐结构表**：

| 时段 | 画面 | 配乐 |
|---|---|---|
| 0-5s | 红绸门帘掀起，新妇缓步而出 | 唢呐远声+环境喜乐，音量压住留白 |
| 5-20s | 拜堂 / 执手 / 敬茶主体段落 | 民乐合奏主旋律，匀速推进，贴脚步与动作 |
| 20-30s | 夫妻对拜定格，花瓣飘落 | 鼓点锣镲渐强收束，最后半拍静音留余韵 |

> 短于 30 秒按比例压缩：10 秒片 = 2s 铺垫 + 6s 主旋律 + 2s 收束。长片每 30 秒一组循环，转场处加 1s 环境声过渡。

---

## 十九、常见问题排查表（踩坑对照）

| 问题 | 原因 | 解法 |
|---|---|---|
| 人物脸崩 | 面容描述过简 / 每次改写 | 用十章锚点表，面容固定句原样复制 |
| 跨镜头换装 | 服装词每次不同 | 服装锚点原样复制，只改动作 |
| 光效不一致 | 光源词每次改写 | 光效锚点固定，只改情绪词 |
| 手部畸形 | 无负面词 / 动作太复杂 | 加十七章负面词，动作拆简单 |
| 文字乱码 | 生成画面带字 | 文字一律后期叠加（十四章） |
| 运镜太硬 | 一个镜头给多个运镜 | 一句只给一个运镜 + 一个速度 |
| 画面过曝/死黑 | 没写光质明暗 | 按二章公式写明光源 + 光质 + 明暗 |
| 人物像"AI 脸" | 缺真实感词 | 加：皮肤纹理, 自然瑕疵, 真实质感 |
| 题材不像 | 只套模板没换字段 | 用十三章填空模板逐字段替换 |
| 拆段拼接跳变 | 衔接点选在静止处 | 衔接点选动作中段 + 叠化 0.3s |

---

## 二十、HELL GRIND 工业方法论吸收（V5.15 入库·对标 AI 长片工业系统）

> 来源：Higgsfield 开源 95 分钟 AI 长片《HELL GRIND》工程档案——115,446 次生成记录、108 个按场次编号文件夹、41,083 条带提示词记录（统计口径见小互拆解与 Marteker 六阶段教程）。
> 定位：本章不是新词库，是「工程颗粒度」升级——把 WCF 已有的组装公式/一致性锚点/生产 QC，从"一段话"升级为"字段化、标签化、可筛选的工业流程"。底层哲学与 WCF 完全同源：**用规则缩小模型的自由发挥空间**。
> 想快速调出：搜「HELL GRIND」「技术底座」「节拍」「约束」「P0-P3」「资产状态」。
> 铁律提醒：字幕/文字不进画面（〇章铁律①）与本章 Audio 段（仅环境音·无音乐）配套生效。

### 20.1 中式技术底座（12 行·全镜共用·与内容无关）

> HELL GRIND 最值钱的一段：4 万+条提示词末尾几乎都挂着同一段 12 行「拍摄规范」，最高频一行出现 8,015 次。作用是钉死画质/镜头/光/色/皮肤/物理/表演/构图/连续性/帧率/声音的标准，**不管这一镜拍什么都不许漂移**。
> 用法：存成固定片段，每条 prompt 末尾整段粘贴（先中文后英文二选一，中英文工具分别喂）。想快速调出：搜「技术底座」。

**中文版（整段复制·喂豆包/可灵/海螺）**：
```
风格：8K IMAX 级写实电影感——禁 3D 渲染、禁游戏引擎、禁游戏过场动画感。
摄影：大师级电影摄影风格（如卢贝兹基×狄金斯式的自然主义长镜头）。
相机：物理电影镜头，180° 快门运动模糊。
灯光：只用自然光——逆光轮廓，机位在阴影一侧，全程有空气雾感；主光只来自天空和门窗，无人工补光。
配色：60:30:10——主色 60% / 辅色 30% / 点缀色 10%。
皮肤：毛孔级真实——汗毛、不对称的痣、毛细血管透出的血色、毛孔阴影与现场光方向一致。
物理：尊重重力与惯性——物体有真实重量、接触阴影正确，道具不许漂浮。
表演：好莱坞级——反应前有微停顿、视线准确、眼睛湿润带反光点、看得见呼吸和胸口起伏。
构图：三分法 + 黄金比例；画面里每个人从第一帧就在动，禁止静态摆拍。
连续性：人物、道具、环境跨镜头完全一致，无身份漂移。
技术：24fps 平滑运动，高清细节，无抖动。
音频：仅环境音效——无配乐、无字幕（音乐与文字卡后期叠加）。
```

**英文版（整段复制·喂 GPT-Image/Midjourney/Runway/Sora）**：
```
Style: 8K IMAX. Photorealistic — no 3D render, no game engine, no game-cutscene aesthetic.
Cinematography: Emmanuel Lubezki x Roger Deakins.
Camera: Physical cine lens. 180-degree shutter motion blur.
Lighting: Natural light only — contre-jour backlight, camera on shadow side, atmospheric haze throughout. Key light from sky and windows only.
Color: 60:30:10 — dominant / secondary / accent.
Skin: Pore-level realism — vellus hair, asymmetric moles, capillary flush, pore-shadow matching on-set light.
Physics: Gravity and inertia respected — mass has real weight, correct contact shadows. No floating props.
Acting: Hollywood — micro-pauses before reactions, precise eye-line, wet living eyes with catch-lights, visible breath and chest rise.
Composition: Rule of thirds + golden ratio. Every person moving from frame one.
Continuity: Characters, props, environment identical across every cut. No identity drift.
Technical: 24fps smooth motion. 8K detail. No jitter.
Audio: Environmental SFX only. No music. No subtitles.
```

> 中式题材可在 Skin 行追加「绢帛/麻布质感」、Color 行用「朱砂/黛青/月白」换 60:30:10 的具体色值；其余 10 行原样保留。

### 20.2 动作按秒拆节拍 + 角色当前状态/承接段（升级组装公式）

> HELL GRIND：15 秒镜头拆成 6 个节拍，每拍一句话、带精确时间轴（0-1.5s / 1.5-3.0s…），动作发生时间钉死；每镜开头重述「角色此刻身上什么伤、衣服破在哪」——**因为模型没有记忆**。单条提示词中位数约 16,500 字符，不是因为话多，是每个字段都在缩小自由发挥空间。
> 用法：组装公式（七章）在「④ 动作·道具·神态」后追加「节拍段」，在「② 场景」前追加「承接段」。想快速调出：搜「节拍」。

**节拍段模板（15 秒示例·按需改秒数）**：
```
动作节拍（按秒拆，每拍一句话）：
0-2.5s：她垂眸执杯，指尖摩挲杯沿（主动作 + 微动作）
2.5-6s：抬眼望向窗外，眉头微蹙，呼吸变浅（状态转折）
6-10s：起身行至窗前，广袖带起茶雾（动作 + 环境互动）
10-13s：指尖抵窗棂，欲言又止（收势）
13-15s：落座垂首，画面定格在茶烟（落点）
```

**承接段模板（每镜必写·模型无记忆）**：
```
承接上一镜：她仍坐在窗前原位，裙裾左侧沾着方才溅落的茶渍，发髻微松，右袖口半湿——上一镜末尾的伤/乱/变逐项重述。
```

### 20.3 约束即导演（收窄 + 锚点 + 尺度）

> HELL GRIND 五条总结里最反直觉的一条：**每次给模型更少的自由度**。自由越大，长片越像一百个陌生短片拼贴。
> 用法：写场景前先过一遍下表。想快速调出：搜「约束」「收窄」。

| 规则 | 别写（自由太大） | 写（收窄） |
|---|---|---|
| 空间收窄 | 整个房间 / 整条街 | 房间东南角 / 朱漆门廊左柱旁 |
| 走位锚点 | 人物在庭院中 | 人物站在石桌与桂树之间，背靠假山 |
| 一次一动作 | 门在镜头中间炸开（复杂动作同镜） | 主角先拖步到门边僵住——下一镜再裂 |
| 人群计数 | 人群 / 路人 | 写明人数：二十余名看客，不许增减 |
| 尺度锚点 | 巨像 / 巨人 | 头颅没入穹顶暗处，手掌与轿厢等宽，主角只到其脚踝 |
| 光源唯一 | 自然光 + 补光 + 轮廓光 | 唯一光源：窗外晨光；阴影方向固定朝东 |

### 20.4 音频段：强制「仅环境音 · 无音乐 · 无字幕」

> HELL GRIND 的 Audio 行出现 7,513 次——模型会自动配乐、自动上字幕，必须显式关掉；对白与音效单独列给后期。
> 用法：视频 prompt 末尾技术底座已含此句；如需强调可单列。想快速调出：搜「音频」「无音乐」。

```
音频：仅环境音效（风声/脚步声/器皿碰撞），无配乐、无字幕、无旁白。对白与 BGM 后期叠加（见十八、十四）。
```

### 20.5 资产状态化 + 标签引用体系（升级十章一致性锚点）

> HELL GRIND：@roco / @roco_wet / @roco_blood 是三个独立资产——把"潮湿/受伤/换装"混进同一段文字，模型会在镜头间随机拼装状态；拆开，成本最低。另有两招：①「无头全身图」逼模型远景时只从面部特写取脸；②引用场景图时注明「仅继承空间与质感，不继承构图色彩」。
> 用法：人物卡升级为「@角色_状态」命名法；一致性锚点句直接引用标签。想快速调出：搜「资产状态」「标签」。

**标签命名法**：
```
@女主_常服 / @女主_湿衣 / @女主_负伤       —— 同一角色不同状态，分开建卡
@场景_祠堂_晨 / @场景_祠堂_夜雨            —— 同一场景不同时段，分开建卡
@遗物_未激活 / @遗物_发光                 —— 道具状态变化单独记录
```

**引用句式（替代 300 字外貌描述）**：
```
人物 = 参考图 @女主_常服 为唯一身份锚点，延续面容/发型/服装/色调，只改变动作、景别、空间。
场景 = 参考图 @场景_祠堂_晨，仅继承空间与质感，不继承构图与色彩。
```

### 20.6 写行为不写感受 + 微生命法则（升级四章表演库）

> HELL GRIND：不写「悲伤/愤怒」这类抽象情绪词，写生理反应与动作目标；静态镜头每 1-2 秒给一次微动态，防死静被模型读成凝固。与 WCF V5.11「面部微表情表演库（22 种）」配套。
> 用法：表情神态（四章）优先按此换词；静态镜头必带微生命句。想快速调出：搜「写行为」「微生命」。

| 情绪词（别写） | 行为词（写） |
|---|---|
| 悲伤 | 下颌咬紧绷起，颧骨收紧，鼻腔呼出半口气 |
| 愤怒 | 指节依次攥紧再松开，呼吸加快 |
| 紧张 | 喉结滑动一下，目光快速扫向门口又收回 |
| 克制 | 眼泪到眶边停住，没有抬手擦 |

**微生命法则句（静态镜头必带）**：静态镜头内每 1-2 秒一次微动态——呼吸起伏、鼻翼翕动、一次慵懒眨眼接快速连眨，画面不得死静凝固。

### 20.7 GEO 站位几何 + 首镜空镜（升级六章构图）

> HELL GRIND：站位几何单独成段——谁在哪、离摄影机多远、面朝哪边、180° 轴线；每场首镜先拍全景空镜，让模型先「拍下」房间布局，后续镜头才不会把人摆错位置。
> 用法：14 步详装（七章）在第 8 步「构图层次」后追加「站位几何」；分镜首镜固定为全景空镜。想快速调出：搜「GEO」「站位」「空镜」。

**站位几何段模板**：
```
站位几何：女主立于画面左侧 1/3，距镜头约 3 米，面朝右；男主于右侧 1/3 背身，距镜头约 4 米；两人中间隔一张案几；摄影机全程不越过两人连线（180° 轴线）；窗外光源在画面上方偏右。
```

### 20.8 镜头筛选分级 P0-P3 + 失败保留（升级生产管理系统 QC）

> HELL GRIND 前 25 分钟：16,181 次生成、253 个镜头入选——64:1 筛选比是当前真实基线。筛选用四级制，失败版本带 FAILED_ 前缀保留作「禁区参考」。
> 用法：生产管理系统（V5.2）「六、视频 QC」通过后，按本表定级归档。想快速调出：搜「P0」「筛选」。

| 级别 | 判定 | 处置 |
|---|---|---|
| P0 · 一票否决 | 人物面貌与锁定卡差异过大 / 关键节拍动作做错（挥刀变挥手） | 作废，标注后保留分析模型行为 |
| P1 · 一票否决 | 物体漂浮 / 脚不沾地 / 与邻镜光照方向矛盾 | 作废，回到资产库或提示词收窄 |
| P2 · 降级可用 | 表情僵硬 / 眼神死板 / 主体局部出画 | 降级为过渡镜/B-roll，或裁切修复 |
| P3 · 标注修复 | 小范围纹理错误 / 背景小瑕疵 | 标注进 fix_log，后期修复 |

**工程文件夹结构（借鉴·长项目用）**：
```
00_MASTER_ASSETS/           角色 / 场景 / 道具（最终确认资产，标签命名）
01_SCENE_01_祠堂/           storyboard + shot_001~shot_N（每镜独立文件夹）
shot_001/                   prompt_v1.txt + gen_001~064.mp4 + SELECTED_ + shot_notes.md
99_POST_PRODUCTION/         edit_timeline / color_grade / audio_mix / fix_log.md
```

> 核心原则：失败版本不删除（标注 FAILED_ 前缀用于分析模型行为）；每镜维护 shot_notes.md（为什么选这版、其他版问题、可复用参数）；资产与场次分离。

---

## 二十一、胡金铨武侠美学（King Hu Cinematic Wuxia·V5.16 入库·光影/雾气/空气感强化版）

> 来源：用户提供定义（核心气质/世界观/空间美学/色彩系统/雾气空气感）+ WCF 配套补全（21.6-21.9）。
> 定位：独立风格配方，与 V1-V6 风格基调平级；题材古风武侠/禅意/孤绝叙事优先调用。参考片：《侠女》《龙门客栈》《山中传奇》《空山灵雨》。
> 想快速调出：搜「胡金铨」「King Hu」「侠女」「雾气」「孤绝」。
> 铁律提醒：字幕/文字不进画面（〇章铁律①）；音频段默认「仅环境音·无配乐」（二十 20.4 同款）。

### 21.1 核心气质 Core Spirit

**核心关键词**：苍凉古意 / 孤绝静谧 / 宿命禅意 / 荒芜 / 时间感

**不是**：❌ 热血英雄　❌ 奇幻仙侠　❌ 黑暗魔幻　❌ 华丽武侠海报　❌ 商业动作电影

**而是**：
- ✔ 一个旅人在消逝文明中的孤独行走。
- ✔ 人只是天地的一部分。
- ✔ 山河、建筑、时间才是真正的主角。

**核心感觉**：文明留下痕迹，但人已经远去。

### 21.2 世界观 World Building

> 这个世界应该感觉：**已经存在了数百年**。不是为了人物搭建，人物只是短暂经过这个古老世界。

**环境元素（按题材取用）**：山水 / 云海 / 松林 / 悬崖 / 石阶 / 古桥 / 荒山古道 / 竹林深处 / 古建筑 / 废弃古寺 / 石墙庭院 / 木梁结构 / 古城门 / 山中古堡 / 破败客栈 / 古驿站 / 宗教遗迹 / 石窟佛像 / 残破碑刻 / 香火痕迹 / 旧经卷 / 荒废佛堂

**荒漠（不是黄金沙漠）**：冷寂荒漠 / 风蚀岩壁 / 废弃城墙 / 断裂石碑 / 灰色沙丘 / 被遗忘的古城遗迹

### 21.3 空间美学 Spatial Design

**最大原则：人小，天地大。**

**人物比例**：人物 10% / 建筑 30% / 自然 60%

**构图参考**：宋代山水 / 元代水墨 / 古代长卷绘画构图

**构图结构（三段式）**：
```
前景：树枝、石头、门框、墙壁
  ↓
中景：人物
  ↓
远景：山、云、雾、天空、荒漠
```

### 21.4 空间层次规则 Depth Design

> 画面必须有明确的空间纵深。

| 层次 | 作用 | 元素 |
|---|---|---|
| 前景层 | 增加距离感 | 竹叶 / 树枝 / 石柱 / 窗框 / 门洞 / 飘动雾气 |
| 中景层 | 主体 | 孤独旅人行走 / 侠客等待的人 / 对峙人物 |
| 后景层 | 制造时间感 | 远山 / 古寺 / 云海 / 废墟 / 荒漠 / 城墙 |

### 21.5 色彩系统 Color System

**总体比例**：蓝绿色系 60% / 灰黑石色 20% / 土黄色系 15% / 朱红暖色 5%

**主色 Primary（必须）**：青灰 / 蓝绿 / 墨绿 / 石青 / 雾白——表达：雨后的山 / 千年古寺 / 湿润石墙 / 清晨空气 / 古道寒气

**辅助色 Secondary（允许但必须低饱和）**：沙黄 / 土褐 / 赭石 / 旧木色

**不要**：❌ 金色沙漠　❌ 橙色夕阳　❌ 好莱坞暖色调

**冷暖关系 Color Temperature**：
```
Cold atmosphere dominates the image.
Warm light appears only as a small memory of the past.
```
中文：**世界是冷的，但文明留下了一点温度。**

### 21.6 雾气与空气感 Atmosphere & Fog

**核心新增规则：画面不能过于清晰。** 必须拥有：
空气层次 / 湿润感 / 雾化感 / 距离感 / 柔焦感

**清晨雾气（Morning Mist）**：晨雾自山谷漫起，石阶在雾中半隐，远山只余轮廓，人物从雾中走来或走入雾中——雾气是叙事的幕布，不是装饰。

**落地写法（可直接复制进 prompt）**：
```
晨雾自山谷漫起，石阶在雾中半隐半现，远山只余青灰轮廓；空气湿润，雾分层——前景雾薄可见细节，中景雾浓笼住人物，远景没入雾白。
```

### 21.7 运镜与镜头语言（WCF 配套补全·对接五/六章）

> 胡金铨式运镜三特征：**慢、静、远**。特写极少，全景与远景为主；动作爆发前必有长久的静。

| 镜头手法 | 写法 |
|---|---|
| 慢速横移 | 云海/山景缓慢横移，人物静止或缓行，人随画动 |
| 固定长镜 | 人物从远景走入画框，走到中景，全程不做跟拍 |
| 远景+全景为主 | 人物在画框边缘行走，天地占据画面主体 |
| 静极生动 | 拔剑/转身/出手前一镜先定格 2-3 秒的静 |
| 动作收束 | 一招之后回到静，人物重新融入山水 |

### 21.8 负面词段（WCF 配套补全）

**中文**：
```
热血动漫感, 华丽特效, 仙侠发光, 金碧辉煌, 饱和度过高, 好莱坞暖色调, 金色沙漠, 橙色夕阳,
人物特写过多, 快速剪辑感, 游戏CG感, 塑料质感, 摆拍感, 人物看镜头
```

**英文（可拼进负面词）**：
```
no wuxia-poster glamour, no xianxia glow, no golden desert, no orange sunset,
no Hollywood warm grade, no vibrant saturation, no fast cutting,
no video-game CGI, no plastic skin, no excessive close-ups, no telephoto compression of scale
```

### 21.9 双语 prompt 模板（WCF 配套补全·可直接复制）

**视频单镜·中文版（喂豆包/可灵/海螺）**：
```
风格：胡金铨武侠美学，苍凉古意，孤绝静谧，宿命禅意。世界已存在数百年，人只是短暂经过。
场景：山间古道，青灰石阶，湿润石墙，晨雾弥漫，远处古寺轮廓隐在云海。
人物：独行侠客，玄色布衣，斗笠压低，背负长剑，缓步而行，衣袂沾露，目光沉静不看向镜头。
构图：人小天地大——人物约占画面 10%，前景竹枝斜入，中景人物独行，远景云海古寺。
光影：冷调为主，青灰蓝绿，晨光微暖仅一点（暖光是文明的记忆）；雾气分层，湿润空气感，柔焦。
运镜：固定长镜慢横移，人物从远景走入中景，不做跟拍；动作前留 2-3 秒静。
音频：仅环境音——风声、脚步踏石、远处钟声；无配乐、无字幕。
负面：无仙侠发光，无华丽海报感，无好莱坞暖调，无快剪，无人物看镜头。
```

**视频单镜·英文版（喂 GPT-Image/Midjourney/Runway/Sora）**：
```
King Hu wuxia aesthetic: desolate ancient mood, solitary stillness, fateful zen atmosphere.
The world has existed for centuries; people only pass through briefly.
Scene: mountain path, grey-blue stone steps, wet stone walls, morning mist, distant temple
outline fading into sea of clouds.
Figure: lone swordsman in dark cloth robe, bamboo hat lowered, long sword on back, walking
slowly, sleeves damp with dew, gaze calm, not looking at camera.
Composition: tiny figure in vast landscape — figure ~10% of frame, architecture 30%, nature 60%;
foreground bamboo branch entering frame, lone figure in midground, mountains and temple in distant mist.
Color: cool blue-green palette dominates (60%), grey-black stone (20%), muted earth tones (15%),
one small warm cinnabar accent (5%) — cold atmosphere dominates, warm light appears only as a
small memory of the past.
Atmosphere: layered morning fog, wet air, soft focus, distance haze, screen never too sharp.
Camera: slow lateral pan, long fixed shot, figure walks from far background into midground,
no tracking; hold still 2-3s before action.
Audio: environmental only — wind, footsteps on stone, distant bell. No music, no subtitles.
Negative: no xianxia glow, no poster glamour, no Hollywood warm grade, no fast cutting,
no character looking at camera.
```

### 21.10 与 V1-V6 风格基调对接表（WCF 配套补全）

| 需求 | 组合 |
|---|---|
| 胡金铨基调总起 | 本章 + V2 古风·清冷意境（或 V6 电影质感·通用） |
| 写实侠客/旅人 | 本章 + 四章人物角色卡（侠客/老翁/行脚僧）+ 七件套 |
| 雾气/空气感词汇 | 本章 21.6 + 二章斑驳光影（漏光/投影） |
| 巨物/山水 | 本章空间美学 + 3.5 中式美学场景专章（尺度锚点） |
| 多镜头长片 | 本章 21.7 运镜 + 二十章 20.1 技术底座 + 20.8 筛选分级 |

---

## 附录·素材库规则说明（原 A-H 库·已降级为规则层）

> ⚠️ **架构升级（V3.79）**：素材编号体系已统一为 **P/D/S/A/I/CASE**，A-H 不再作为素材编号，降级为"规则说明"层（提供公式与结构，具体素材条目全部在 P/D/S/A/I/CASE 库）。

**新数据库架构**：

```
【底层素材库】 P｜人物库  D｜道具库  S｜场景库  A｜动作库  I｜互动库
        ↓
【规则库】     R｜动态规则库  N｜负面词/纠错规则库  C｜调用规则库
        ↓
【成品案例库】 CASE｜完整案例库
```

**原 A-H 处理去向**：

| 原编号 | 原内容 | 现在 |
|---|---|---|
| A 人物库 | 10 要素公式/差异化表 | 并入 **P**（作为人物规则） |
| B 妆发服饰库 | 发型/妆容/服装七维 | 并入 **P**（作为人物属性） |
| C 道具库 | 道具五要素/四类分层 | 并入 **D** |
| D 场景库 | 场景六层/母库 20 | 并入 **S** |
| E 动作库 | 动作三层/四组词库 | 并入 **A** |
| F 道具互动库 | 茶香书花灯互动 | 并入 **I** |
| G 动态变化库 | 五维动态 | 升级为 **R 动态规则库**（R01-R15 见下） |
| H Prompt 总装 | 六段式 | 改为 **C04 Prompt 总装** |
| 防乱写·信息优先级 | S/A/B/C 级 | 归入 **N 纠错规则库** |

**主归属原则**（同一个东西只能有一个"主归属"，用来处理功能重叠）：

```
① 它是什么？      → P / D / S
② 它做什么？      → A
③ 它怎么发生变化？ → I / R
```

例：茶盏=D01（是什么）；茶盏被注入茶汤=I02（怎么参与）；茶面涟漪=R 动态（怎么变化）。三件事不混。

> 用法：**人物卡 + 场景卡 + 道具卡 + 动作卡 + 光影卡 + 动态卡 → 自动组成完整 Prompt**。
> 做点茶/婚嫁/节气/节日/古代生活/女性写真/宫廷/民俗等任何题材，都像搭积木一样拼。

### A. 人物库（规则层→并入 P 人物库）

#### A1 人物 10 要素（人物具体化公式）

```
【人物身份】+【年龄】+【脸部特征】+【发型】+【妆容】+【体态】+【服装】+【配饰】+【当前动作】+【当前情绪】
```

**不要**：宋代女子，温婉美丽，穿古装
**改成**：

```
二十岁左右的宋代闺阁女子，
鹅蛋脸，眉形细长平直，眼型偏长，
鼻梁自然挺直，唇色淡粉，
乌黑长发梳成宋式低髻，
鬓边保留少量碎发，
淡雅妆容，不过度修饰，
身形纤细但姿态端庄，
身穿藕荷色宋制褙子与米白色长裙，
衣料为细密真丝，袖口有低调暗纹，
发间仅佩一支白玉簪，
坐于窗边，一手翻书，一手轻扶案几，
神情安静，略带倦意。
```

#### A2 人物差异化表（换题材直接换卡，不用重新想）

| 类型 | 脸部 | 发型 | 气质 | 动作 |
|---|---|---|---|---|
| 闺阁小姐 | 鹅蛋脸 | 低髻 | 安静 | 倚窗读书 |
| 贵族女子 | 长圆脸 | 高髻 | 端庄 | 持扇而立 |
| 民间妇人 | 圆脸 | 简单发髻 | 朴素 | 整理衣物 |
| 茶娘 | 清瘦脸 | 简髻 | 专注 | 点茶 |
| 新妇 | 柔和圆脸 | 新娘髻 | 含羞 | 垂眸 |
| 老妇 | 面部自然纹理 | 银发髻 | 慈祥 | 缝补 |
| 少女 | 小圆脸 | 双髻/半髻 | 灵动 | 奔跑/回头 |
| 文士 | 瘦长脸 | 束发 | 清冷 | 抚琴/执卷 |

#### A3 人物写法原则

人物不是简单的"漂亮古风女子"。优先锁定：**身份 → 年龄 → 脸部 → 妆发 → 体态 → 服装 → 配饰 → 动作 → 神态**。人物写法尽量保留"身份感"和"生活感"，避免所有人物都变成同一种网红脸。

> ⚠️ 本库只保留规则编号（A1/A2/A3），**不增加 A01/A02 这类具体人物素材编号**——具体人物素材全部在 P 库（P01-P30）。

#### A4-A5 人物分库指引

- **老人**：完整卡见「四（人物角色卡库 46-50 老人）」
- **儿童**：完整卡见「四（人物角色卡库 41-45 儿童）」
- **配角群体**：商贩/轿夫/货郎/路人/孩童追逐 → 取「三（3.1.1 市井街巷词库·人物）」，按 A1 十要素压缩成一句

### B. 妆发服饰库（规则层→并入 P 人物库·人物属性）

#### B1 发型（发型 = 身份 + 结构 + 装饰）

| 身份 | 结构 | 装饰 |
|---|---|---|
| 少女 | 双髻、垂髫、半披发、双环髻 | 彩绳、绒花、小簪 |
| 未婚女子 | 低髻、双螺髻、侧髻、半挽发 | 白玉簪、绢花 |
| 已婚女子 | 高髻、盘髻、圆髻、低髻 | 金簪、步摇、珠翠 |
| 贵族 | 高髻 + 玉簪 + 步摇 + 珠饰 | 冠、钿、华盛 |
| 民间 | 简单发髻 + 木簪/银簪 | 素面，少饰 |

#### B2 妆容（按身份定浓淡）

| 身份 | 妆容写法 |
|---|---|
| 少女 | 淡妆，唇色自然，眉形淡扫 |
| 贵族女子 | 华妆，花钿，胭脂匀染，眉形精细 |
| 新妇 | 红妆，额间花钿，唇色朱红 |
| 老妇 | 素面，眉淡，不施脂粉 |

#### B3-B5 服装拆解（不要再只写"宋制襦裙"）

| 层 | 选项 |
|---|---|
| 上衣 | 褙子 / 对襟襦 / 交领襦 / 半臂 |
| 下装 | 长裙 / 褶裙 / 马面裙 / 裤 |
| 外层 | 披帛 / 褙子 / 大袖 |
| 材质 | 丝绸 / 罗 / 绫 / 纱 / 棉麻 / 粗布 |
| 颜色 | 主色 + 辅色 + 点缀色 |
| 纹样 | 植物纹 / 几何纹 / 云纹 / 暗纹 |
| 状态 | 整洁 / 微皱 / 被风吹动 / 使用痕迹 |

> ⚠️ **服装状态必须单独写**——比"高级丝绸材质"有用得多：
> 衣袖自然垂落 / 裙摆轻微褶皱 / 袖口因频繁使用略有磨损 / 衣襟保持自然松弛状态

#### B6 配饰（三层：随身/手持/场景，取「三（配饰道具三层结构）」）

发饰（玉簪/步摇/花胜/金钿）+ 项耳（璎珞/耳坠）+ 腰佩（玉佩/禁步/香囊）+ 手足（玉镯/臂钏/指环）

### C. 道具库（规则层→并入 D 道具库）

#### C1 道具五要素（任何道具按这五个写）

```
① 类型  ② 材质  ③ 形制  ④ 使用痕迹  ⑤ 与人物互动
```

**茶壶**——不要"一把茶壶"，写：

```
一只宋式粗陶茶壶，
灰褐色旧陶胎，
壶身略带手工拉坯留下的不规则纹理，
壶嘴边缘有轻微茶渍，
壶盖略微错开，
壶口升起细薄白色茶雾，
女子右手扶住壶柄，准备注汤。
```

**扇子**：

```
一柄竹骨团扇，
浅米色绢面，
扇面绘淡墨竹枝，
竹骨边缘有细微磨损，
扇面随着手腕动作缓缓转动，
逆光下绢面呈半透明质感。
```

**首饰**：

```
一支旧白玉簪，
玉质温润而非高亮玻璃质感，
簪头为简约如意形，
表面存在细微天然纹理，
插在低髻侧后方，
随着人物转头产生轻微晃动。
```

#### C2 道具分类（A 手持 / B 桌面 / C 空间 / D 时代识别）

**A 类·手持道具**：茶盏 / 团扇 / 折扇 / 书卷 / 毛笔 / 灯笼 / 花枝 / 酒杯 / 香炉 / 剪刀 / 针线 / 梳子 / 玉佩

**B 类·桌面道具**：茶壶 / 茶盏 / 砚台 / 香炉 / 花瓶 / 书卷 / 铜镜 / 首饰盒 / 糕点 / 食盒

**C 类·空间道具**：屏风 / 帷幔 / 窗棂 / 木柜 / 案几 / 琴 / 灯架 / 衣架 / 博古架 / 竹帘

**D 类·时代识别道具**（比堆十个"古风"形容词有用）：

| 时代/场景 | 识别道具 |
|---|---|
| 宋代 | 茶筅、茶盏、香炉、书卷、琴、文房器物 |
| 婚嫁 | 聘礼盒、雁礼、红绸、妆奁、花轿 |
| 节日 | 灯笼、香囊、花灯、供品 |
| 农事 | 竹篮、木桶、农具、谷物、布袋 |

### D. 场景库（规则层→并入 S 场景库）

#### D1 场景六层结构

```
【地点】+【建筑结构】+【地面】+【家具陈设】+【远景】+【正在发生的环境变化】
```

**"宋代闺房"**——不要"宋代古风闺房，温馨雅致"，写：

```
宋代闺阁内室，
木质梁柱与格栅窗构成封闭而安静的室内空间，
青砖地面略有岁月磨损，
窗边摆放低矮木案与坐榻，
案上放置书卷、砚台、铜镜与一只小香炉，
墙边设木质衣架与折叠屏风，
窗外可见竹影与庭院树枝，
晨间阳光透过窗棂形成规则光影，
空气中有极细微尘埃漂浮。
```

#### D2 场景母库 20 个（第一版够用）

**室内（8）**：宋式闺房 / 书房 / 茶室 / 厨房 / 新房 / 佛堂 / 贵族厅堂 / 药房

**室外（8）**：庭院 / 回廊 / 庭园 / 河岸 / 市集 / 茶肆 / 城门 / 乡村院落

**仪式/特殊（4）**：婚礼现场 / 祭祀空间 / 节日街市 / 宫廷仪式空间

**每个场景四种变体**（写同一场景时按需选一档）：

| 变体 | 写法 |
|---|---|
| 基础版 | 空间+地面+主陈设，一句带过 |
| 写实版 | 六层全写，加使用痕迹与年代细节 |
| 电影版 | 写实版 + 光效/景深/金尘/雾 |
| 夜景版 | 光源改烛火/灯笼/月光，暗部加层次 |

### E. 动作库（规则层→并入 A 动作库）

#### E1 动作三层（人物动作 = 主动作 + 微动作 + 状态动作）

```
主动作：缓慢倒茶
微动作：手指轻微调整壶柄
状态动作：衣袖随着手腕移动自然摆动
```

#### E2 动作词库

**手部**：轻扶 / 握住 / 托起 / 展开 / 翻动 / 整理 / 捻取 / 捧持 / 拨动 / 抚摸 / 轻敲

**头部**：垂眸 / 抬眼 / 侧头 / 回眸 / 低头 / 缓慢转头 / 微微后仰

**身体**：起身 / 落座 / 转身 / 屈膝 / 跪坐 / 侧坐 / 倚靠 / 缓步 / 停步 / 俯身

**情绪动作**：欲言又止 / 轻轻叹气 / 嘴角微动 / 眉头轻蹙 / 眼神躲闪 / 缓慢抬眼 / 短暂失神

### F. 道具互动库（规则层→并入 I 互动库）

**茶**：茶雾升起 / 茶汤产生细微涟漪 / 液面反射窗光 / 茶盏边缘残留水汽

**香**：香烟向上升腾 / 烟雾被气流轻轻吹散 / 香灰缓慢落下 / 烟雾穿过逆光形成半透明层次

**书**：书页被风轻轻翻动 / 纸张边缘微微翘起 / 阳光落在纸面 / 手指压住即将翻动的书页

**花**：花枝随风轻晃 / 花瓣轻轻飘落 / 露珠沿花瓣边缘滑落 / 阳光穿过半透明花瓣

**灯笼**：灯笼轻微摇晃 / 烛火跳动 / 灯纸透出暖光 / 影子随着火光微微变化

> 本库素材直接喂给「第 7 步·动态变化」——只写镜头开始→结束发生的变化。

### R. 动态规则库（原 G 库升级·R01-R15·喂第 7 步用）

> 动态只写"镜头开始→结束发生的变化"，不重复静态信息。

| 编号 | 维度 | 写法示例 |
|---|---|---|
| R01 | 人物动态 | 抬眼从垂眸到看向镜头；手腕从抬起缓缓落下；呼吸轻微起伏 |
| R02 | 手部动态 | 手腕转动、手指轻动、袖口随动作摆动 |
| R03 | 道具动态 | 茶雾从浓转淡；香灰缓慢落下；书页被风吹起又落下 |
| R04 | 织物动态 | 衣袖摆动、裙摆晃动、丝线轻颤 |
| R05 | 光影动态 | 光斑从桌面移至手背；烛火跳动拉长影子；水面反光变化 |
| R06 | 环境动态 | 窗外竹影随微风轻晃；尘埃在光柱中浮动；帘幔轻动 |
| R07 | 天气动态 | 雪片由疏转密；雨滴在瓦檐连成线；风起叶落 |
| R08 | 水面动态 | 涟漪向外扩散；倒影随波纹变形 |
| R09 | 烟火动态 | 香烟升腾被气流吹散；蒸汽上升；薄雾流动 |
| R10 | 火烛动态 | 烛火跳动、灯笼轻晃、灯纸亮度微变 |
| R11 | 器物动态 | 穗子滞后摆动；风铃轻响；帘钩碰撞 |
| R12 | 表情微动 | 嘴角微动、眉心轻蹙、呼吸、睫毛轻颤 |
| R13 | 速度规则 | 整体缓慢克制，全镜最多 1 处快动作对比 |
| R14 | 数量规则 | 单镜 1-3 个动态，主次分明，不堆砌 |
| R15 | 落点规则 | 结束状态稳定不悬空（茶壶回正、手停稳、灯渐稳） |

#### C04 Prompt 总装模板（六段式·原 H 库）

```
【人物】年龄+身份+脸部+妆发+体态+服装+配饰+气质
【场景】时代+地点+建筑+地面+陈设+远景
【道具】名称+材质+形制+使用痕迹+位置
【动作】主动作+手部动作+表情+姿态
【光影】主光源+光线方向+明暗关系+材质反光
【动态】开始状态 → 结束状态（人物变化+道具变化+环境变化+镜头变化）
```

#### H1 完整成品例：「宋式点茶」

**人物**

```
二十岁左右的宋代闺阁女子，
鹅蛋脸，细长平直眉，眼型偏长，
乌黑长发梳成宋式低髻，
鬓边保留少量自然碎发，
淡雅妆容，
身形纤细，姿态端庄，
身穿藕荷色宋制褙子与米白色长裙，
衣料为细密真丝，袖口带低调暗纹，
发间佩一支白玉簪，
神情专注而安静。
```

**场景**

```
宋式雅致茶室，
木质梁柱与格栅窗，
青砖地面，
低矮木案，
案后设置竹制屏风，
窗外可见庭院竹影，
室内陈设简洁克制，
没有现代物品。
```

**道具**

```
案上摆放一只灰褐色粗陶茶壶、
两只宋式茶盏、
竹制茶则、
茶筅与小型茶罐，
陶器表面具有自然手工纹理，
茶盏边缘存在轻微使用痕迹。
```

**动作**

```
女子跪坐案前，
右手持茶则取茶，
左手扶住茶盏，
垂眸凝神，
动作缓慢而克制。
```

**光影**

```
清晨暖金色阳光从格栅窗斜射进入，
窗棂在青砖地面形成规则光影，
人物侧脸被柔和侧逆光照亮，
发丝边缘出现细微轮廓光，
茶盏与陶壶表面产生柔和反光。
```

**动态**

```
镜头开始时茶雾较浓，
随后茶雾逐渐变淡，
女子手腕缓慢移动，
茶则靠近茶盏，
窗外竹影随微风轻轻晃动，
最后女子缓缓抬眼。
```

**运镜**

```
中近景，
低机位，
镜头从茶盏前景缓慢向人物推进，
浅景深，
前景茶具轻微虚化，
人物始终保持清晰，
运动平稳克制。
```

#### H2 图片 / 图生视频 / 文生图差异

| 用途 | 六段式怎么改 |
|---|---|
| 图片 | 去【动态】段，【动作】定格在"进行时"（抬手一半/转身途中） |
| 图生视频 | 全保留；【人物】必须与首帧图严格对应，【动态】写 3-4 个帧间变化 |
| 文生视频 | 全保留；【动态】+【运镜】合并，按 14 步详装输出 |

#### H3 负面词

最小集见「十七」：手部畸形, 六指, 五官错位, 脸崩, 现代物品穿帮, 低质量, 模糊, 变形, 文字乱码（文字一律不进画面）, 过度磨皮, 塑料肤质, 过饱和, 摆拍感, 人物看镜头

### C. 自动调用规则库（C01-C05·让数据库自动出素材）

#### C01 题材解析器（输入题材 → 先拆解，不直接写 Prompt）

用户输入任何题材，先拆成 8 字段，再去找素材：

```
时代 → 人物/身份 → 核心行为 → 场景 → 核心道具 → 动作 → 互动 → 氛围
```

示例：输入"宋代女子七夕穿针"
```
时代：宋代
人物：女子（年轻）
场景：闺阁/庭院（节日晚间 → S26）
核心行为：穿针
核心道具：针、丝线、针线盒、绣架
动作：持针、引线、穿针、垂眸观察
互动：手指×针、针×丝线、丝线穿过针孔
氛围：七夕、夜色/灯火
```

#### C01 补充：场景提取指令（古风 4 视角·V5.11 入库）

> 解决：从文案/题材一键提取「场景卡」，和 C01 题材解析器配套——先拆题、再提场景、再选素材。与文档铁律一致（画面无人、文字不进画面）。搜「场景提取」调出。

```
Role：电影级纯净场景设计专家（高辨识度版）
核心执行逻辑：
1. 绝对真空与匿名：画面中严禁出现任何人影，场景描述文字中严禁出现任何角色人名
2. 场景命名法则：每个场景名称必须在四个字以上，通过具体修饰词增加辨识度（严禁使用单名词）
3. 四大核心要素：场景描述必须完整涵盖【环境类型】【具体时间】【空间氛围】【视觉主要特征】
4. Prompt 开头：所有 Prompt 必须以「不能出现其他人，无人，纯场景」开头
5. 输出控制：严禁输出任何括号内的说明文字，直接输出具体内容

第一步：场景提取清单（按顺序编号列出文案中的所有地点：场景全称 | 核心氛围 | 建议色调）
第二步：专业场景设定表（按此格式逐一输出）：
- 场景名称：四个字以上的独特命名
- 画幅构图：横向 16:9 电影级场景设定图，极高画质，纯净无人的空间。古风宫廷场景，电影级画质，细腻光影，同一场景四个视角：
  1. 高空俯视角：庭院全景，对称构图
  2. 正门平视视角：建筑主体完整
  3. 回廊侧视角：纵深感，氛围感
  4. 局部特写视角：雕花、窗棂、光影细节
- 视觉风格：【填入用户指定风格】，极致细节。统一色调、统一光影、统一风格
- 场景描述：【环境类型】【具体的地理/建筑空间属性】—【时间时刻】【精确到时段的天气与光线状态】【空间氛围】【如：压抑、神圣、破败、宁静等视觉情绪描述】【主要特征】【具体的材质、核心物件、前中后景的标志性元素，严禁提及角色姓名】。电影级场景，写实质感，高清细节，氛围感强
- Prompt（直接复制）：不能出现其他人，无人，纯场景，【将上述所有环境细节融合成一段精简、极具冲击力的生图描述词，包含：no humans, empty, landscape only】
```

> 扩展：现代剧/特写视角版见归档「AI技能-归档\02-提示词模板库\场景提取现代剧.txt / 场景特写古风提取词.txt」。

#### C02 素材选择（自动调用规则 V1.0·十步）

```
输入：时代 + 人物/身份 + 习俗/行为 + 地点/环境 + 时间/节日
系统自动执行：
① 时代识别 → 锁定对应 P / S / D 的时代标签
② 人物识别 → 从 P 库选择 1～2 个最匹配人物
③ 场景识别 → 从 S 库选择 1 个主场景
④ 核心道具识别 → 从 D 库选择 1 个核心道具 → 最多增加 2 个辅助道具
⑤ 主动作识别 → 从 A 库选择 1 个主动作
⑥ 道具互动识别 → 从 I 库选择 1～3 个互动
⑦ 动态识别 → 从 R 库选择 1～3 个环境/人物/道具动态
⑧ CASE 匹配 → 优先寻找同题材 CASE → 无完全匹配时，寻找同动作/同场景 CASE
⑨ Prompt 总装 → 输出图片版 → 输出图生视频版 → 输出 5 秒动态版
⑩ 连续性检查 → 人物一致 → 服装一致 → 道具一致 → 空间一致 → 动作方向一致 → 镜头方向一致
```

#### C03 数量限制（锁死·防关键词大杂烩）

```
P：1，最多 2
S：1
D：1 核心 + 0～2 辅助
A：1 主动作
I：1～3
R：1～3
光影：1 / 构图：1 / 运镜：1
```

#### C05 连续性检查表（14 项硬规则·第六阶段升级）

> 每条 Prompt 的锚点段原样复制，只允许动作/神态/运镜变化。生成前/后逐项核对下表，任何一项变化 → 标红提醒，重新生成该镜。

| # | 错误码 | 检查项 | 检查内容 |
|---|---|---|---|
| 1 | C-F01 | 人物脸型 | 同一人物脸型轮廓不变 |
| 2 | C-F02 | 发型 | 发髻/刘海/碎发位置不变 |
| 3 | C-F03 | 妆容 | 眉形/唇色/妆面不变 |
| 4 | C-F04 | 衣服 | 款式/颜色/纹样不变 |
| 5 | C-F05 | 首饰 | 簪/环/佩款式与位置不变 |
| 6 | C-F06 | 身材 | 高矮胖瘦/体态不变 |
| 7 | C-F07 | 核心道具 | 款式/材质/大小不变 |
| 8 | C-F08 | 道具位置 | 手持/摆放位置不跳变 |
| 9 | C-F09 | 场景 | 空间结构/陈设不变 |
| 10 | C-F10 | 时间 | 晨/午/昏/夜一致（分镜表推进除外） |
| 11 | C-F11 | 光源 | 方向/色温/强度不跳变 |
| 12 | C-F12 | 主色 | 画面主色调一致 |
| 13 | C-F13 | 动作起点 | 本镜动作承接上镜结束状态 |
| 14 | C-F14 | 动作终点 | 本镜结束状态成为下镜起点 |

> 用法：多镜头拼接前跑一遍；CASE 多镜头标准中每镜「连续性锚点」字段即本表浓缩版。

#### C06 题材自动调用全链路（程序逻辑·输入→输出）

> C01-C05 是规则，C06 把它们串成一条可执行链路。以后输入题材 → 按链路跑 → 直接拿四联输出，不用翻素材库。

**运行链路（12 步）**：
输入题材 → ①时代识别 → ②人物匹配（P）→ ③场景匹配（S）→ ④核心道具匹配（D）→ ⑤主动作匹配（A）→ ⑥互动匹配（I）→ ⑦动态补充（R）→ ⑧CASE 匹配（同题材＞同动作＞同场景＞通用模板）→ ⑨数量限制（C03）→ ⑩Prompt 总装（C04·四联）→ ⑪连续性检查（C05）→ ⑫输出：①图片版 + ②图生视频版 + ③5秒动态版 + ④多镜头分镜版

**全链路示例·输入「宋代女子七夕穿针」**：
① 时代：宋代
② 人物：P01｜宋代闺阁少女（年轻女子·闺阁身份）
③ 场景：S01｜宋式闺房（夜）→ 节日晚间可选 S26｜节日灯市（非必需）
④ 道具：D25｜针线盒 + D26｜绣架（核心：针与丝线）
⑤ 主动作：引线穿针（动作库无编号·文字描述）
⑥ 互动：I27｜针尖穿绸、丝线拉紧成弧
⑦ 动态：R01 人物动态（抬眼/手起）+ 烛火跳动 + 衣袖轻动
⑧ CASE 匹配：CASE15｜七夕·穿针乞巧（同题材直接命中）
⑨ 数量限制：P1、S1、D2（核心 1+辅助 1）、A1、I1-2、R2-3
⑩ 总装：复制 CASE15 四联 → 改人物 P01、场景 S01、道具 D25/D26
⑪ 连续性：人物/烛台/针线/夜色一致
⑫ 输出：CASE15 ①-④ 直接可用（如需夜间灯市版，改 S26 并微调光影）

"> 命中 CASE 时：CASE 即答案，素材编号仅用于改人物/场景/道具；未命中时：按②-⑦手动组 P+S+D+A+I+R，再走 C04 总装。

#### C07 图片 → 首帧 → 图生视频 → 多镜头 → 拼接（生产闭环·第十阶段）

> 图片系统与视频系统打通：图片先做参考帧，再用图片作为首帧进入视频。

**闭环 8 步**：
① 出图：〇章图片入口 P1-P5 选单 → 图片 9 步精装结构
② 选首帧：首帧专用构图规则（头顶留白 ≥20% / 中全景 / 进行中动作 / 底部留虚化；同场景出 3 张备选）
③ 图生视频：首帧 + 图生视频版 Prompt（首帧/主动作/微动作/道具动态/环境动态/镜头/结束/连续性）
④ 逐镜生成：CASE 四联①-③ 或 CASE 多镜头标准逐镜 10 字段
⑤ 多镜头拼接：每镜「连续性锚点」过 C05 14 项检查表
⑥ 加声音：CASE 声音系统规格 8 项（BGM/环境声/音效/旁白/字幕/进入点/转场声）
⑦ 合成：字幕文字卡后期叠加（不进画面）
⑧ 成片发布：按「九、生成后拼接标准流程」

> 整条链上任何环节的图片/视频，人物锚点段全部原样复制（十章一致性锚点 + C05 检查表双保险）。

### N. 纠错规则库（防乱写·Prompt 信息优先级）

> Prompt 很漂亮、画面很乱 = 该删的不删。按优先级写，先保证"画的是什么"，再保证"画得漂亮"。

**S 级·必须准确**：人物身份 / 人物外貌 / 服装 / 时代 / 核心道具 / 核心动作 / 场景

**A 级·决定画面质量**：光线 / 构图 / 景别 / 材质 / 动态 / 空间层次

**B 级·氛围增强**：电影感 / 诗意 / 高级感 / 东方美学 / 梦幻 / 唯美

**C 级·可删**：大量重复形容词 / 同义词堆叠 / 过多摄影参数 / 过多风格标签

---

## 附录·古风习俗视频提示词素材库 V1.0（P30 人物 + D50 道具 + S30 场景 + A50 动作 + I30 互动 + CASE10 成品）

**用途**：本库用于补充现有提示词模板中的"具体素材"。

**使用原则**：人物库负责"谁" → 场景库负责"在哪里" → 道具库负责"拿什么/摆什么" → 动作库负责"做什么" → 道具互动库负责"东西怎么动" → 完整 Prompt 负责"如何组合"。

不要求一次全部使用。一条画面通常选择：
1 个人物 + 1 个主要场景 + 1～3 个核心道具 + 1 个主动作 + 1～2 个微动作 + 1～3 个动态细节。
避免把素材库变成关键词堆砌。

### 一、人物素材库｜30 条

**使用规则**：人物不是简单的"漂亮古风女子"。优先锁定：身份 → 年龄 → 脸部 → 妆发 → 体态 → 服装 → 配饰 → 动作 → 神态。人物写法尽量保留"身份感"和"生活感"，避免所有人物都变成同一种网红脸。

> **人物卡统一结构**（V3.79）：身份→年龄→脸部→眉眼→发型→妆容→体态→服装→配饰→气质→默认动作。调用时整卡复制，AI 一次拿到"一整个人"。P01 为完整卡示范，其余 P 卡已按同顺序包含全部维度。

**P01｜宋代闺阁少女**（完整人物卡示范）

```
身份：宋代闺阁少女
年龄：18～19 岁
脸部：鹅蛋脸
眉眼：细长平直眉、偏长眼型
发型：低髻、少量自然碎发
妆容：淡雅、肤色自然通透
体态：纤细、坐姿端正
服装：藕荷色宋制褙子、米白长裙
配饰：温润白玉簪
气质：安静含蓄
默认动作：动作轻缓
```

**P02｜世家贵女**
二十岁左右的世家贵女，长圆脸，眉眼清秀端正，乌发梳成精致高髻，佩细小玉簪与低调珠饰，妆容精致但不过度浓艳，身穿月白色绫罗褙子与浅青长裙，衣料细腻垂坠，坐姿端庄，神态克制矜持，带有受过良好礼仪训练的贵气。

**P03｜民间年轻妇人**
二十余岁的普通民间妇人，面部柔和，脸颊略带生活感，简单挽发，以木簪固定，几乎不施浓妆，身穿浅褐色粗布上衣与深青长裙，袖口略有使用痕迹，身形自然，一边整理家中物件一边低声说话，神情温和而专注。

**P04｜茶娘**
二十岁左右的茶娘，面容清秀，眼神专注，黑发简单束成低髻，穿米白色交领上衣与青绿色长裙，袖口利落方便活动，腰间系一条素色布带，双手动作稳定，长期制作茶饮形成自然熟练的姿态。

**P05｜新婚女子**
二十岁左右的新婚女子，鹅蛋脸，眉眼柔和，黑发梳成正式婚髻，佩少量金玉发饰，面部妆容比日常略精致，穿绛红色传统婚嫁服饰，衣襟与袖口有细致纹样，双手略显拘谨，垂眸浅笑，带有新婚初期的羞涩与不安。

**P06｜年轻新郎**
二十余岁的古代年轻男子，面部轮廓清晰但不过度雕刻，眉形自然，眼神沉稳，黑发束成整齐发髻，身穿深青色传统长袍，腰间佩素色玉佩，身姿挺拔，面对新婚仪式略显紧张，动作克制，目光偶尔看向身旁女子。

**P07｜文士**
二十七八岁的古代文士，偏瘦长脸，眉眼清冷，黑发束冠，身穿月白色宽袖长袍，腰间仅佩一枚素玉，手指修长，坐于书案前翻阅书卷，神情沉静专注，带有长期读书形成的文雅气质。

**P08｜年轻武人**
二十余岁的年轻武人，眉骨略明显，面部轮廓硬朗，黑发高束，穿深青色窄袖服，腰间佩革带与简单兵器，身姿挺拔，站立时肩背自然打开，神情警觉但不夸张，一手扶住腰间物件。

**P09｜女将**
二十余岁的古代女将，面部轮廓利落，眉形英气，黑发高束，穿深红与玄青色传统武服，腰间佩革带，动作干净有力量，站立时重心稳定，目光坚定，没有现代影视化过度夸张的盔甲。

**P10｜年轻农妇**
二十余岁的乡村年轻农妇，圆润自然的脸型，眉眼朴实，黑发挽成简单发髻，身穿灰褐色粗布衣裙，衣物有自然褶皱和轻微使用痕迹，手臂动作熟练，正在整理竹篮中的谷物，神情专注平和。

**P11｜老年妇人**
六十岁左右的古代老妇，面部自然衰老纹理明显，眼角与额头有真实皱纹，银白头发梳成低髻，穿深褐色粗布衣衫，双手略显粗糙，动作缓慢但熟练，神情慈祥而沉静。

**P12｜老人**
七十岁左右的古代老人，瘦削面部，白须自然垂落，皮肤具有真实年龄纹理，头戴旧布巾，穿深灰色长袍，手持竹杖，身体略微前倾，行走缓慢，目光平和。

**P13｜小女孩**
七八岁的古代小女孩，圆脸，大眼但比例自然，黑发梳成双髻，穿浅粉色短襦与长裙，衣服略有生活褶皱，双手捧着一朵小花，脚步轻快，神情好奇活泼。

**P14｜小男孩**
八九岁的古代男孩，圆润脸型，黑发束成简单发髻，穿青灰色短衣，赤脚或穿简单布鞋，动作活泼，手里抱着竹编小篮，眼神好奇，带有乡村儿童自然的生活状态。

**P15｜年轻商贩**
三十岁左右的民间商贩，面部略带风霜感，头发简单束起，穿灰蓝色粗布衣衫，腰间挂布袋，站在街边整理货物，动作利落，神态热情但不过度夸张。

**P16｜药铺掌柜**
四十余岁的古代药铺掌柜，面部沉稳，留短须，黑发束冠，穿深褐色长袍，腰间挂小布袋，一手拿药秤，一手整理药材，神情专注谨慎。

**P17｜年轻医者**
二十七八岁的古代医者，面容清瘦，眉眼温和，黑发束冠，穿素色长袍，腰间佩布制药囊，坐在木案前辨认药材，手指轻触药叶，神情专注。

**P18｜绣娘**
二十余岁的民间绣娘，面容柔和，黑发挽成简单低髻，穿浅青色布衣，坐在木案前，双手持针线，衣袖自然收拢，眼神集中在绣面，姿态安静细致。

**P19｜织女**
二十余岁的民间女子，身材纤细自然，黑发简单束起，穿浅灰蓝色布衣，坐在织机前，双手正在调整经纬线，神情专注，衣物和手部带有长期劳作形成的真实感。

**P20｜厨娘**
三十岁左右的古代厨娘，脸型圆润，黑发简单挽起，穿米白色内衫与深色围裙式外层，袖口略微卷起，双手正在处理食材，额角有轻微劳作后的细小汗意，神情专注。

**P21｜宫女**
二十岁左右的宫廷侍女，面容清秀端正，发髻整齐，佩简洁发簪，穿颜色克制的宫廷侍女服饰，姿态训练有素，双手捧着托盘，步伐缓慢，神态恭谨。

**P22｜宫廷贵妇**
三十余岁的古代贵妇，面部端庄，眉眼成熟，发髻精致但不夸张，佩玉簪与少量珠饰，身穿深青色宽袖服饰，坐姿稳定，一手轻扶桌案，神情沉静而有威严。

**P23｜新娘侍女**
二十岁左右的年轻侍女，脸型柔和，简单低髻，穿青绿色侍女服，双手整理新娘衣袖，动作谨慎轻柔，神情专注，与新娘保持自然距离。

**P24｜媒人**
四十余岁的民间妇人，面部圆润，发髻整齐，穿颜色朴素但干净的传统衣裙，手中拿着礼单或布包，说话时手势自然，脸上带着热络而世故的笑意。

**P25｜村中长者**
六十余岁的乡村长者，面部有明显岁月纹理，白发简单束起，穿灰褐色长袍，手持木杖，站在村口或院落中，神情平静，具有熟悉地方习俗的沉稳感。

**P26｜香道女子**
二十余岁的古代女子，面容清雅，黑发低髻，穿浅米色宽袖衣裙，袖口自然垂落，跪坐香案前，手持香箸整理香灰，神情专注安静。

**P27｜点茶女子**
二十余岁的宋代女子，眉眼细长，发髻简洁，穿米白与黛青色宋制衣裙，双手正在操作茶筅，身体微微前倾，目光集中在茶盏，神态专注而从容。

**P28｜节日少女**
十七八岁的年轻女子，面部清秀，半挽长发，佩一枚小巧花饰，穿浅青色节日衣裙，手持花灯，在人群中缓慢行走，眼神带着节日里的轻松喜悦。

**P29｜祭祀主持者**
四十余岁的礼仪主持者，面容庄重，头发整齐束起，穿深色传统礼服，双手持礼器，站在祭祀空间中央，动作缓慢规范，神情肃穆，身体保持稳定端正。

**P30｜旅行中的女子**
二十余岁的古代女子，面容自然，黑发低髻，穿便于行走的素色长衣，外搭浅灰色披风，肩背布包，手持竹杖，站在山路旁回望远处，神情平静而略带疲惫。

### 二、道具素材库｜50 条

**道具五要素**：任何重要道具尽量写：类型 + 材质 + 形制 + 使用痕迹 + 人物互动。不要只写"古风茶具""古代首饰"。

**D01｜宋式茶盏**：浅色宋式茶盏，细腻陶瓷胎体，杯口薄而自然，表面具有轻微釉面变化，边缘存在细小使用痕迹，放置于木案上，接受侧面窗光照射。

**D02｜粗陶茶壶**：灰褐色粗陶茶壶，手工拉坯留下细微不规则纹理，壶嘴边缘带淡淡茶渍，壶盖略有使用磨损，壶身温润哑光，人物一手扶住壶柄准备注茶。

**D03｜茶筅**：细竹制茶筅，竹丝排列自然，顶部纤细分叉清晰，颜色由浅黄到淡褐自然变化，使用后略带茶液痕迹，置于茶盏旁或被人物握持。

**D04｜茶则**：细长竹制茶则，浅黄竹色，表面有自然竹纹，边缘圆润，用于从茶罐中取茶粉，被人物右手轻轻握住。

**D05｜茶罐**：小型陶制茶罐，灰白色哑光釉面，圆腹小口，盖面略有手工纹理，放置在茶案右侧，罐口打开后露出细腻茶粉。

**D06｜铜镜**：古代圆形铜镜，背面带简洁纹饰，镜面不是现代镜子的高反射效果，边缘有轻微氧化痕迹，放置于木质妆台上，晨光在镜面产生柔和反射。

**D07｜木梳**：深色木制梳子，梳齿排列整齐，木纹清晰，边缘经过长期使用而略显圆润，放在妆台上，人物手指轻轻搭在梳柄上。

**D08｜白玉簪**：温润白玉发簪，如意形简约簪头，玉质半透明但不过度发光，表面具有天然细微纹理，插在低髻侧后方，人物转头时产生轻微晃动。

**D09｜步摇**：细金属古式步摇，簪头带小型珠饰，结构纤细，金属表面呈柔和旧金色，随着人物走动产生轻微摆动。

**D10｜团扇**：竹骨团扇，浅米色绢面，扇面绘淡墨花枝，竹骨颜色自然，绢面存在轻微纤维纹理，被人物单手轻握。

**D11｜折扇**：竹骨折扇，素色纸面，扇骨具有自然木竹纹理，扇面略有使用褶痕，人物缓慢展开折扇。

**D12｜香炉**：小型青铜香炉，表面呈沉稳旧铜色，炉身带浅浮雕纹饰，炉盖有镂空孔洞，内部香烟缓慢升起，放在木质香案中央。

**D13｜香盒**：小型木制香盒，深褐色木纹，盒盖有简洁纹样，边角因使用略显圆润，打开后可见细碎香料。

**D14｜香箸**：细长香箸，竹木材质，颜色浅褐，表面光滑，人物用其轻轻整理香灰。

**D15｜香灰**：细腻浅灰色香灰，颗粒极细，表面松散自然，被香箸轻轻划出平整纹路，局部存在燃烧后的深色痕迹。

**D16｜书卷**：古代线装书卷，米黄色纸张，纸面具有天然纤维纹理，边缘略微卷曲，长期翻阅留下轻微磨损，放在木案上。

**D17｜毛笔**：竹制毛笔，笔杆浅褐色，笔毫柔软自然，笔尖带少量墨色，横放在砚台旁。

**D18｜砚台**：深灰色石砚，石材纹理自然，砚面略带水光，边缘经过长期使用略显圆润，旁边放置毛笔。

**D19｜墨锭**：黑色墨锭，表面微微发亮，边缘具有手工打磨痕迹，置于砚台旁，局部沾有细小墨粉。

**D20｜纸灯笼**：传统纸灯笼，米白或暖红色灯面，竹制骨架，纸面有自然纤维纹理，内部烛火使灯面产生柔和暖光，被夜风轻轻吹动。

**D21｜花灯**：传统节日花灯，竹骨纸面结构，装饰简洁花纹，内部烛火跳动，底部穗子自然垂落，行走时轻微摆动。

**D22｜红绸**：传统红色绸带，丝绸表面柔软有细微织物纹理，颜色深红而非荧光红，边缘自然卷曲，被系在礼物盒或门框上。

**D23｜礼盒**：木制礼盒，深色木纹，盒面简洁，边缘有手工制作留下的不规则细节，内部放置婚嫁或节庆物品，由人物双手捧持。

**D24｜妆奁**：古代木制妆奁，多层抽屉结构，深红棕色木纹，铜质小把手略有旧化痕迹，内部放置梳子、簪子和香盒。

**D25｜针线盒**：小型木制针线盒，盒盖略旧，内部整齐放置针线、布片与剪刀，边缘存在长期使用痕迹，放在绣案一侧。

**D26｜绣架**：木制小型绣架，木纹自然，结构简单，架面绷着浅色丝绸绣面，布料边缘保持轻微张力。

**D27｜竹篮**：手工竹编篮，竹篾粗细略有变化，编织结构清晰，边缘略有磨损，内部装有谷物、蔬菜或花枝，被人物双手提起。

**D28｜竹筐**：较大的竹制箩筐，编织纹理明显，颜色浅黄褐，底部略有使用磨损，装满粮食或收获物，放置在庭院地面。

**D29｜木桶**：旧木桶，深褐色木板结构，金属或木制箍带，桶壁有水渍，放在院落一侧，水面随人物取水动作产生轻微晃动。

**D30｜水瓢**：天然葫芦制水瓢，表面保留自然纹理，颜色淡黄褐，手柄处有长期使用痕迹，人物用它从木桶中舀水。

**D31｜葫芦**：天然葫芦，表皮颜色由浅黄至淡褐，具有自然斑纹，表面略有干燥质感，挂在屋檐或被人物手持。

**D32｜竹杖**：天然竹制手杖，竹节清晰，表面有轻微磨损，底端颜色较深，老人行走时手掌自然握住杖身。

**D33｜斗笠**：传统竹编斗笠，编织纹理清晰，浅黄褐色竹篾，边缘略有磨损，被人物戴在头上，帽檐遮挡部分额头与面部。

**D34｜蓑衣**：天然植物纤维编织蓑衣，颜色灰褐，纤维粗细自然，边缘不完全整齐，雨天表面附着细小水珠。

**D35｜油纸伞**：传统油纸伞，竹骨结构，米白色油纸伞面，伞面带手工纹理，伞柄深褐色，雨水沿伞面缓慢滑落。

**D36｜花枝**：细长花枝，枝条弯曲自然，叶片大小略有差异，花瓣存在轻微不规则，被人物单手捧在胸前。

**D37｜莲花**：盛开的浅粉色莲花，花瓣层次自然，中心结构清晰，表面附着细小水珠，晨光从花瓣侧面穿过，随水面微风轻轻摇晃。

**D38｜竹叶**：细长青竹叶，叶面具有自然纹理，边缘略有弯曲，晨风吹过时产生方向一致的轻微摆动。

**D39｜糕点**：传统手制糕点，形状不完全机械对称，表面带细微蒸制纹理，摆放在青瓷盘中，边缘存在自然碎屑。

**D40｜果盘**：浅色陶瓷果盘，盘面摆放当季水果，果皮颜色自然，表面存在真实纹理，放置于木案中央。

**D41｜食盒**：传统木制多层食盒，深棕色木纹，铜质扣件，边缘略有磨损，内部装有糕点与果品，被人物双手打开。

**D42｜木勺**：天然木制长柄勺，浅褐色木纹，勺面因长期使用变得光滑，放置在陶罐旁，人物用其搅拌食材。

**D43｜陶罐**：灰褐色陶罐，粗陶胎，表面存在手工纹理和细小色差，罐口略有茶渍或水渍，放置在灶台或木架上。

**D44｜铜壶**：旧铜壶，表面呈温暖暗金色，局部有氧化与擦拭痕迹，壶嘴结构清晰，热水从壶口缓慢倒出。

**D45｜木梭**：织布用木梭，浅褐色硬木，表面光滑，边缘因长期使用略有磨损，在织机经线之间快速移动。

**D46｜织机**：传统木制织机，结构复杂但比例真实，木材颜色自然，经纬线排列清晰，局部存在长期使用磨痕，人物坐在织机前操作。

**D47｜药秤**：传统小型药秤，木质秤杆，细小金属秤盘，绳线纤细，人物手指轻扶秤杆，正在称量药材。

**D48｜药材包**：棕色纸包或布包药材，纸张略有褶皱，包口用麻绳简单扎住，表面带轻微药材粉末，放在药案上。

**D49｜花瓶**：小型青瓷花瓶，釉面温润，颜色浅青，器型简洁，瓶口插入两三枝季节花枝，表面接受柔和窗光。

**D50｜礼仪用雁**：传统婚嫁礼仪中的雁形象，可采用真实大雁或礼仪器物表现，羽毛纹理自然，姿态安静，与红绸、礼盒等婚嫁元素形成明确关系，避免现代宠物化处理。

### 三、场景素材库｜30 条

**场景写法**：场景不要只写"古风庭院"。推荐：时代/地点 + 建筑结构 + 地面 + 家具陈设 + 背景 + 环境状态。

**S01｜宋式闺房**：宋式闺阁内室，木质梁柱与格栅窗，青砖地面，靠窗设置低矮木案与坐榻，案上摆放书卷、铜镜、香炉，墙边有木质衣架与简洁屏风，窗外可见竹影，清晨阳光穿过窗棂。

**S02｜宋式书房**：安静的宋式书房，木质格栅窗，深色木案靠墙摆放，案上有砚台、毛笔、书卷，一侧设置书架，窗外可见庭院树枝，午后斜光进入室内，空气中有极细微尘埃。

**S03｜古代茶室**：简洁宋式茶室，木质地板与梁柱，低矮茶案位于中央，周围摆放茶壶、茶盏、茶罐，墙边设竹制屏风，窗外有竹影，自然侧光照亮茶具。

**S04｜贵族厅堂**：高门世家厅堂，高挑木质梁柱，深色木地板，中央摆放长案，两侧设置屏风和花瓶，家具比例庄重，空间保持较大留白，暖色灯光从侧面进入。

**S05｜古代厨房**：传统古代厨房，土灶、木架、陶罐、竹篮分布在空间内，地面略有使用痕迹，灶台边摆放木勺和食材，空气中有轻微蒸汽，光线从小窗进入。

**S06｜乡村院落**：传统乡村院落，夯土墙与木门，青砖地面，院中摆放竹篮、木桶和木凳，墙边有晾晒的布料，屋檐下悬挂葫芦，晨光斜照，环境安静生活化。

**S07｜古代茶园**：山坡茶园，整齐但不机械的茶树排列，远处山体层层退入薄雾，泥土小径穿过茶垄，采茶竹篮放在地面，晨间柔光从山谷方向进入。

**S08｜秋日打谷场**：乡村秋日打谷场，大片平整土地，竹筐、木耙、粮袋散落有序，远处为土墙和木屋，地面铺着晾晒的谷物，秋日低角度阳光照亮人物和谷粒。

**S09｜古代市集**：古代城镇集市，木制摊棚连续排列，布幔、竹篮、陶器和食材构成前中后景，行人穿着不同身份的传统服饰，道路为夯土或石板，环境热闹但不过度拥挤。

**S10｜古代茶肆**：临街古代茶肆，木质门窗，低矮木桌，陶制茶具整齐摆放，门外可见行人和布幌，室内有自然侧光，茶雾在人物之间形成轻微空间层次。

**S11｜古代药铺**：传统药铺内部，高木药柜排列整齐，大量小型药材抽屉，中央设置木案，案上放药秤、药包和药材，空气干燥安静，窗边有柔和自然光。

**S12｜绣房**：古代女子绣房，木质窗格，绣架、针线盒、布料和丝线摆放在案边，墙边悬挂完成的绣品，室内光线柔和，阳光落在丝线和手指上。

**S13｜织房**：传统织房，大型木制织机占据空间主体，经纬线形成规律线条，木地板略有使用痕迹，窗边有布料和线团，人物坐在织机前工作。

**S14｜婚嫁新房**：古代婚嫁新房，木质床榻，屏风、妆台、木箱、红绸装饰，色彩以深红、木色和暖米色为主，烛火产生柔和暖光，空间庄重而克制。

**S15｜婚嫁庭院**：传统婚嫁庭院，青砖地面，木门与回廊，门框悬挂红绸，院中摆放礼盒、竹篮与木箱，亲友站在远处，晨间自然光形成层次。

**S16｜古代回廊**：木质回廊，连续格栅柱形成纵深，青砖地面，两侧种植竹子和季节花木，远处连接庭院，人物沿回廊缓慢行走，侧光在地面形成连续明暗。

**S17｜古代庭院**：传统宅院庭院，青砖铺地，中央一株老树，墙边有竹影与花木，木质月洞门连接后院，一侧放置石桌和木凳，风吹树叶产生轻微动态。

**S18｜临水庭院**：古代临水庭院，木质平台伸向池塘，岸边种植莲花和垂柳，水面映出建筑与天空，人物坐在木栏旁，微风使水面产生细小波纹。

**S19｜古桥**：古代石桥，青灰色石材，桥面有长期风化痕迹，桥下流水缓慢，两侧有柳树和野草，远处山雾淡淡展开，人物从桥上缓步经过。

**S20｜河岸**：古代河岸，泥土与石块自然交错，岸边停靠小木船，竹篓与水桶放在岸边，远处有低矮村舍，晨雾贴近水面，阳光从雾中穿过。

**S21｜山间古道**：山间石板古道，石阶高低略有变化，两侧生长竹林和野草，远处山峰被薄雾遮挡，人物背着布包缓慢前行，阳光从树叶间形成斑驳光影。

**S22｜雪中村落**：冬日古代村落，木屋与夯土墙覆盖薄雪，屋檐垂着冰凌，地面留下零散脚印，远处炊烟缓慢升起，冷色自然光，人物呼出的白雾清晰可见。

**S23｜春日花园**：古代园林春日花园，曲折石径，低矮花木，竹篱，小型水池，远处有亭台，花瓣随风缓慢飘落，阳光柔和。

**S24｜秋日庭院**：深秋古代庭院，青砖地面散落少量黄叶，木质回廊，枯枝与秋菊形成季节层次，一只竹篮放在墙边，低角度夕阳照亮人物轮廓。

**S25｜夜间街巷**：古代夜间街巷，青石路面微微反光，木质店铺关闭部分门窗，两侧悬挂纸灯笼，灯火形成连续暖光，远处人物剪影缓慢移动，空气中带轻微薄雾。

**S26｜节日灯市**：传统节日夜间灯市，大量纸灯笼形成前中后景，木质店铺与街巷延伸至远方，行人穿着传统服饰，花灯暖光映照人物面部，空气中有轻微烟雾和灯火闪烁。

**S27｜祭祀庭院**：传统祭祀庭院，中央设置礼仪案台，摆放香炉、供品与礼器，建筑与庭院保持庄重秩序，人物站位明确，晨雾与香烟共同形成空间层次，光线克制肃穆。

**S28｜寺院山门**：古代山寺山门，木石结构，屋檐层叠，石阶向山上延伸，两侧古树高大，晨雾覆盖远山，人物站在石阶下形成尺度参照。

**S29｜天宫巨物场景**：巨大东方建筑群悬于云海之上，层叠宫阙远超人物尺度，巨大石阶从云层延伸，前景有古树枝叶，中景人物如小型尺度参照，远景为云海与高耸建筑，冷暖光线形成空间层次。

> 同型实测范本（Flova·超广角俯瞰版·V5.6 入库）：超广角镜头，超长镜头，恢弘电影构图，高空远距离俯瞰视角，大片级水平透视与大纵深空间组织，22mm 超广角镜头。东方仙侠秘境中，一座庞大的悬浮仙岛漂浮在灿烂翻涌的云海之上，岛屿中央生长着一棵远古神树，神木高大得仿佛撑起天地，庞大的树冠遮盖整座仙城，树干苍劲厚重如远古山岳，树根粗壮虬结，穿透岛体后深深没入下方流动的云层之海，依附神树而建的天空仙城旋转而旋转，白玉半廊，琉璃屋顶神（原文 OCR 截断处按原样保留）。写仙侠/玄幻/巨物场景时可直接替换本段。

**S30｜高门世家园林**：高门世家园林，曲水、假山、亭台、长廊层层展开，青石小径连接不同空间，精细木雕与石雕点缀建筑，盆景与季节花木分布自然，人物位于中景，整体呈克制而精致的贵族生活气息。

**S31｜琉璃巨涡仙阙（仰拍巨物·图片/视频通用·V5.12 入库）**：极低角度广角，人物盘坐于光洁白玉台，位于画面底部居中占下 1/3；上方 2/3 为巨大弧形琉璃晶体漩涡自上空奔涌垂落，半通透琉璃流光翻涌交织琥珀金、孔雀石绿、朱砂红、青金石蓝、莲荷紫，道道棱面折射棱柱光束；两侧层叠鎏金中式浮空仙阙，深色木构斗拱，宝蓝色琉璃飞檐隐入琉璃薄雾；下方镜面云海隐约仙鹤剪影。暖丁达尔光束、斑斓虹弧、漫天金尘。柔和手绘概念原画，低饱和古宝石色调，矿物颜料颗粒质感，无卡通渲染。

> 仰拍巨物对比构图公式（S31 可复用）：极低角度广角 + 人物底部居中占 1/3 + 上方 2/3 巨物压迫源（漩涡/殿群/巨像）+ 两侧次级建筑收框 + 云海托底 + 矿物五色 + 丁达尔暖光。写仙侠/巨物/神女题材图片或首帧时，照抄结构换人物与压迫源即可。

### 四、动作素材库｜50 条

**动作原则**：动作不要写成"优雅地做着事情"。应该明确：主动作 + 手部动作 + 身体状态 + 视线/表情。视频画面进一步增加：主动作 + 微动作 + 环境动作。

**A｜手部动作 01～15**

A01｜倒茶：右手握住壶柄，手腕缓慢向前倾斜，茶汤从壶嘴连续流入茶盏，左手轻扶盏沿。
A02｜点茶：一手固定茶盏，另一手持茶筅快速但细微地旋转，手腕动作稳定，视线始终落在茶汤表面。
A03｜取茶：右手持竹制茶则，从茶罐中轻轻取出茶粉，手腕保持稳定，缓慢移动至茶盏上方。
A04｜翻书：食指与拇指捏住纸页边缘，缓慢将书页翻向另一侧，另一只手压住书卷。
A05｜执笔：三指自然握住毛笔，笔尖悬停在纸面上方，随后缓慢落笔，手腕轻微移动。
A06｜研墨：一手扶住砚台，另一手推动墨锭缓慢转动，砚面水墨逐渐变得浓稠。
A07｜整理香灰：手持细香箸，轻轻推动香灰，从中央向两侧整理，动作缓慢且精细。
A08｜插香：人物双指捏住细香，垂直插入香炉中央，手指停顿片刻后缓慢收回。
A09｜梳发：一手轻扶发丝，另一手持木梳，从发根向发尾缓慢梳理。
A10｜系绸结：双手分别捏住红绸两端，交叉、绕过、收紧，最后形成自然结扣。
A11｜打开礼盒：双手扶住木盒两侧，缓慢打开盒盖，内部物品逐渐暴露。
A12｜捧花：双手在胸前托住细长花枝，指尖轻轻调整花朵位置，视线落在花瓣上。
A13｜提灯：一手提住灯笼提绳，身体随步伐轻微晃动，灯笼在手边自然摆动。
A14｜舀水：右手握住水瓢，从木桶水面缓慢舀起，水面产生细小波纹，随后抬手倒入另一容器。
A15｜捡拾谷物：人物弯腰，一手抓取散落谷粒，缓慢放入竹篮，手掌和谷粒保持真实接触。

**A｜头部与视线 62～71**（原 B16-B25·V3.83 迁移：头部动作归入 A）

A62｜垂眸：头部保持基本稳定，眼睛缓慢向下移动，表情保持克制。
A63｜抬眼：先保持低头状态，随后眼睛抬起，最后头部轻微抬起。
A64｜回眸：人物身体继续向前，头部缓慢转向身后，视线最后落在后方人物或物件上。
A65｜侧头：头部向一侧轻轻倾斜，目光跟随声音或人物移动。
A66｜短暂失神：人物动作短暂停顿，视线从手中物件移开，看向远处，随后重新恢复动作。
A67｜注视道具：人物视线始终落在手中茶盏/花枝/书卷，眼神随道具位置轻微移动。
A68｜看向人物：人物先低头，听到声音后抬眼，视线转向身旁人物。
A69｜低头微笑：人物目光向下，嘴角出现非常轻微的笑意，没有夸张表情变化。
A70｜皱眉：眉心轻微收紧，眼神保持集中，嘴唇基本不动。
A71｜闭眼闻香：人物缓慢闭眼，轻轻吸气，停顿片刻后重新睁眼。

**A｜身体动作 72～86**（原 C26-C40·V3.83 迁移：身体动作归入 A）

A72｜落座：人物先停步，身体缓慢下沉，整理衣摆后坐下。
A73｜起身：人物双手轻扶案面，身体缓慢站起，衣摆随重心变化自然垂落。
A74｜跪坐：人物整理裙摆，双膝缓慢落地，随后调整身体重心保持端正。
A75｜缓步：人物以小幅度步伐缓慢向前，衣摆随步伐产生轻微摆动。
A76｜停步：人物行走中逐渐减速，最后完全停下，身体仍保留轻微惯性。
A77｜转身：身体先停止前进，肩部开始转动，随后腰部和脚步跟随完成转身。
A78｜俯身：人物上半身缓慢前倾，双手向目标物件靠近，动作保持稳定。
A79｜倚窗：人物侧身靠近窗边，一只手轻扶窗框，身体自然向窗侧倾斜。
A80｜坐在案前：人物保持端正坐姿，双手位于案面，身体略微前倾，注意力集中于手中物件。
A81｜穿过回廊：人物沿木质回廊缓慢前行，一侧衣袖自然垂落，经过光影区域时身体亮暗发生变化。
A82｜撑伞行走：一手持伞，身体保持自然步速，伞面随着行走轻微上下起伏。
A83｜迎风站立：人物站在原地，身体基本保持稳定，发丝和衣袖受到风力影响向同一方向移动。
A84｜抱物行走：双手抱住竹篮或礼盒，身体随步伐产生自然上下起伏，物件保持相对稳定。
A85｜跪地整理物件：人物跪坐地面，双手整理礼盒或供品，身体轻微前后移动。
A86｜回头停留：人物走出几步后停下，缓慢回头，视线停留在原来位置。

**A 动作库补充：面部微表情表演库（V5.11 入库·22 种·图生视频表演层专用）**

> 解决：动作对了但脸是僵的。22 种表情按「0-1s → 1-3s → 3-5s」时间线写面部+呼吸+身体，可直接整条塞进 CASE ③5 秒动态版的表演描述。搜「微表情」或「表情库」调出。

1. 开心（内敛不夸张）：轻微开心，嘴角微微上扬，眼角出现细微鱼尾纹，眼轮匝肌自然收缩，眼神明亮，轻微眨眼，肩膀轻微起伏带呼吸感。
2. 难过（隐忍不哭）：眼眶微红，泪水在眼眶打转但强忍不落，下唇轻微颤抖，咬住嘴唇，低头，肩头微微耸动，缓慢呼吸，喉结轻微滚动，情绪克制积累。
3. 疑惑（思考不解）：眉头微蹙，眼球轻微转动，眼神聚焦又散开，嘴唇轻抿，头微侧，缓慢呼吸，短暂停顿思考。
4. 害怕（恐惧不安）：眼神轻微飘移，瞳孔微缩，呼吸变浅急促，嘴唇微颤，吞咽动作，身体轻微僵硬。
5. 惊吓（突然受惊）：0-1 秒表情凝固僵住，1-2 秒眼睛猛然睁大瞳孔扩张，2-3 秒眉毛上扬，3-4 秒呼吸骤停后急促，4-5 秒身体微缩，瞬间受惊反应，真实微表情。
6. 惊喜（由惊到喜）：0-1 秒愣住瞳孔放大，1-2 秒嘴角快速上扬，2-3 秒眼睛弯起带泪光，3-4 秒手轻捂嘴，4-5 秒放松微笑，惊喜递进。
7. 厌恶（轻微嫌弃）：鼻翼微收，上唇轻微抬起，眼神回避，眉头微蹙，头轻微后仰，呼吸轻停，无夸张表情，5 秒内完成。
8. 坚定（眼神有力量）：眼神直视焦点不闪躲，下颌收紧，嘴唇紧闭，呼吸平稳，肩膀稳定，正面硬光，坚定气场。
9. 愤怒（压抑怒火克制爆发）：下颌咬紧，嘴唇抿成一条线，鼻翼扩张深呼吸，眉头紧锁，眼神锐利紧盯，瞳孔微微收缩，颈部血管轻微凸起，双手不自觉攥拳，5 秒内情绪逐步攀升，胸腔起伏变大，最后闭眼一秒强行压制。
10. 轻蔑（不屑与轻视）：一侧嘴角快速上扬随即收回，鼻翼微张，眼神从上往下扫过随即移开，眉毛单侧微挑，下巴微抬，头轻微侧转，呼吸平稳带一丝叹气感，2-3 秒完成，不滞留。
11. 尴尬（窘迫不安强装镇定）：0-1 秒笑容僵在脸上，1-2 秒眼神快速闪躲环顾四周，2-3 秒脸颊耳根微微泛红，3-4 秒手不自觉摸后颈或鼻尖，4-5 秒干笑一声，身体轻微摇摆，视线落地，5 秒内完成。
12. 满足（惬意沉浸享受）：眼睛微眯，嘴角自然上扬不费力，头轻靠一侧，呼吸深长缓慢，肩膀下沉，喉间发出极轻微叹息，眼神虚焦望向某处，全身肌肉松软，5-10 秒持续状态。
13. 失望（期待落空无奈接受）：眼神先亮后暗，嘴角原有弧度缓缓抹平，瞳孔轻微收缩，视线从焦点落下，肩膀随一次呼气明显下沉，嘴唇微张后闭上，头轻微前倾埋低，手原本抬起半途垂落，全身重心降低。
14. 疼痛（突发锐痛与隐忍）：0-0.5 秒受伤部位肌肉猛缩，0.5-1 秒倒吸一口凉气咬住牙，1-2 秒眉毛拧紧眼紧闭，2-3 秒屏住呼吸，3-4 秒痛感略减后颤颤呼出，4-5 秒眼眶微湿，喉结滚动吞咽，额头沁出细汗，身体轻微蜷缩保护受伤位，真实疼痛反应。
15. 释然（放下重负豁然明朗）：眉头由微蹙缓缓展开，眼角纹路柔和加深，唇间漏出一口气，似笑非笑，眼神从地面抬起看向远方，肩膀带动胸腔完成一次深度呼吸，下巴微收后轻点，整张脸肌肉逐层放松，5 秒内完成情绪置换。
16. 嫉妒（酸涩不悦暗自比较）：眼神先落在他处后快速收回，嘴角不自然下拉 0.3 秒，下唇轻咬，眉头微拢又强行展平，喉间无声吞咽，呼吸节奏被打乱一瞬，目光再次瞟向对方方向，手指无意识蜷缩，5 秒内心绪暗涌表面维持平静。
17. 感动（被触动热泪盈眶）：0-1 秒眼神突然聚焦于触动源，1-2 秒嘴唇微张呼吸轻滞，2-3 秒眼眶迅速泛红泪水漫上眼睑，3-4 秒嘴角颤抖着上扬鼻翼微翕，4-5 秒眨眼时一滴泪滑落，下巴皱起，手不自主抚上心口，情感满溢。
18. 疲惫（身心俱疲强撑着）：眼睑沉重半垂，眼神失去聚焦力虚浮于某处，嘴唇干涩微张，呼吸沉缓带胸腔浊音，肩膀前扣，背部微弓，头颈前伸，手指松开无力，眨眼速度变慢每次闭合延长 0.5 秒，喉结随吞咽迟钝滚动，整个人像被重力加重。
19. 好奇（被吸引探究欲起）：0-1 秒目光被吸引眼球转向目标，1-2 秒头自然微侧眉毛单侧轻挑，2-3 秒嘴唇微抿回味眼眶略微收紧聚焦，3-4 秒上身不自觉前倾 2-3 度眨眼频率降低，4-5 秒嘴角藏一丝探究的笑意鼻翼轻张，好奇心成型。
20. 思念（回忆涌现淡淡怅惘）：眼神放空落向虚空某点，眉间浮起极淡的温柔弧度，嘴角似笑非笑停驻，瞳孔微微扩张像在看记忆里的画面，呼吸变得轻浅悠长，头轻靠一侧，指腹无意识摩挲某处，咽部微动像吞下想说的话，4-6 秒沉浸后眨眼回神，余韵残留。
21. 愧疚（自责不安想要弥补）：0-1 秒眼神忽闪移开不敢对视，1-2 秒眉头锁紧眉心蹙起竖纹，2-3 秒嘴唇翕动欲言又止下唇被咬住，3-4 秒头低垂下巴几乎贴胸口，胸腔闷重呼吸变浅，4-5 秒双手无意识交握绞紧，肩膀内收缩小自己，自我谴责姿态。
22. 陶醉（沉醉美好忘我沉浸）：眼眸半阖留一线光，瞳孔微微放大柔和，嘴角自然上扬呈安详弧度，呼吸深长带鼻音哼鸣轻响，头随韵律轻晃，眉间完全舒展无一丝皱痕，手指轻敲节拍或虚划弧线，身体轻微摇摆如浸微醺，5-10 秒忘我状态持续，逆光晕染。

**A｜情绪状态动作 52～61**（原 D41-D50·V3.82 迁移：表情/状态类归入 A，避免与道具 D 库撞号；A51 庄重站立为仪式专条保留）

A52｜含羞：垂眸，嘴角轻微上扬，手指无意识整理袖口，身体略微向内收。
A53｜紧张：人物动作略慢，手指轻微收紧，视线短暂游移，随后重新看向目标。
A54｜欣喜：眼神明显变亮，嘴角轻微上扬，动作速度略微加快。
A55｜悲伤：动作速度减慢，视线向下，嘴角自然放松，身体姿态略微下沉。
A56｜思念：人物望向远处，动作逐渐停止，手仍保持原来的姿势，眼神出现短暂失神。
A57｜警觉：听到声音后动作突然减慢，眼睛先转向声音来源，随后头部缓慢转动。
A58｜庄重：身体保持垂直，双手位置稳定，动作幅度较小，视线正前方或略向下。
A59｜疲惫：人物动作速度较慢，肩部略微下沉，短暂停顿后继续手上的工作。
A60｜专注：视线持续锁定手中物件，眉眼集中，手部动作稳定，几乎没有多余肢体动作。
A61｜释然：人物先保持短暂静止，随后缓慢呼气，肩膀轻微放松，嘴角出现极浅的笑意。

**A51｜庄重站立**：人物身体保持垂直，双脚站位稳定，双手位置克制，肩部放松，视线正前方或略向下，动作幅度极小，适用于古代婚礼、祭祀、仪式等庄重场景。

### 五、道具互动素材库｜30 条

> 这一库专门解决一个问题："道具不是摆设，而是画面中的参与者。"道具互动尤其适合放入现有 Prompt 的"动态细节"部分。

I01｜茶雾：热茶表面升起细薄白色茶雾，茶雾向上盘旋后逐渐散开，逆光下形成半透明层次。
I02｜倒茶：茶汤从壶嘴连续流下，落入茶盏后产生细小圆形涟漪，茶面反射窗边光线。
I03｜茶筅：茶筅在茶盏内部快速旋转，茶汤表面逐渐形成细密泡沫，人物手腕保持连续稳定运动。
I04｜茶盏反光：窗光从茶盏边缘滑过，釉面出现柔和高光，人物手指移动时高光随位置变化。
I05｜香烟：香烟从炉盖孔洞缓慢升起，受到室内微弱气流影响，烟雾轻轻向一侧偏移后消散。
I06｜香灰：香箸缓慢划过香灰表面，留下平整细线，少量灰粒随着动作向两侧散落。
I07｜烛火：烛火持续轻微跳动，火焰亮度发生细小变化，附近墙面影子随火光产生轻微移动。
I08｜灯笼：灯笼随着人物脚步轻轻前后摆动，内部烛火使灯纸亮度产生细微变化。
I09｜红绸：红绸悬挂在门框两侧，微风吹过时边缘缓慢飘动，丝绸表面出现柔和反光。
I10｜花瓣：花枝被微风吹动，一两片花瓣从枝头脱落，缓慢飘向地面。
I11｜柳枝：柳枝被河风吹向同一方向，叶片产生连续但细微的摆动，人物从前景经过时部分枝条轻微回弹。
I12｜竹影：窗外竹叶被风吹动，投射在室内墙面的影子缓慢移动，光影边缘保持柔和。
I13｜书页：窗边气流吹动书页边缘，纸张缓慢翻起又落下，人物及时伸手压住纸页。
I14｜墨水：毛笔蘸入砚中，墨液表面产生细小波纹，笔尖离开时带出一滴墨水。
I15｜水面：水面受到水瓢或雨滴影响，产生向外扩散的细小涟漪，周围倒影随波纹轻微变形。
I16｜雨伞：雨水沿油纸伞面形成细小水流，伞面轻微晃动，水滴从伞缘连续滴落。
I17｜雨滴：细雨落在木栏、石板与人物衣袖上，形成不同大小的水珠，部分水珠沿衣料缓慢滑落。
I18｜雪：细小雪花缓慢落下，部分落在人物肩头和发梢，随着身体移动少量雪粒滑落。
I19｜衣袖与道具：人物转动手腕时宽袖自然摆动，袖口短暂掠过茶盏旁边，随后重新垂落。
I20｜发簪：人物转头时白玉簪产生轻微晃动，簪饰反射一小片柔和侧光。
I21｜步摇：人物缓慢行走，步摇随着步伐产生连续细小摆动，珠饰偶尔捕捉到光线。
I22｜竹篮：人物提起竹篮，篮中谷物因重心变化产生轻微晃动，竹编结构保持稳定。
I23｜谷物：谷粒从手掌缓慢落入竹篮，形成细小连续颗粒流，少量谷粒落在篮沿。
I24｜木桶：水瓢进入木桶后，桶内水面产生环形波纹，人物提起水瓢时水面缓慢恢复平静。
I25｜葫芦：屋檐下悬挂的葫芦随风轻轻摇晃，相互之间偶尔发生非常轻微的碰触。
I26｜织布：木梭穿过经线，经线和纬线随着动作快速交替，织物表面逐渐形成连续纹理。
I27｜针线：针尖穿过丝绸，丝线被拉紧后形成轻微弧线，人物手指随针线方向缓慢移动。
I28｜礼盒：礼盒被打开，盒盖缓慢抬起，内部红绸和礼物逐渐进入画面，空气中的微尘在侧光下可见。
I29｜花灯穗子：人物行走时花灯轻微晃动，底部穗子产生滞后摆动，烛火在纸面内部轻轻跳动。
I30｜水汽与光：热水产生的水汽向上升腾，经过侧逆光后变得清晰，随后逐渐消散在背景虚化区域。

### 六、完整 Prompt 示例库｜10 条

> 以下案例不是让所有 Prompt 都照抄。作用是展示：人物 + 场景 + 道具 + 动作 + 光影 + 动态 + 构图 + 镜头如何真正组合成一张可以直接使用的提示词。

**CASE 01｜宋式点茶**（三联格式示范）

**① 图片版**：
清晨，宋式雅致茶室内，一名二十岁左右的宋代闺阁女子跪坐于低矮茶案前，鹅蛋脸，细长平直眉，眼型偏长，乌黑长发梳成宋式低髻，鬓边保留少量自然碎发，淡雅妆容，身形纤细，身穿藕荷色宋制褙子与米白色长裙，发间仅佩一支温润白玉簪。茶案上摆放灰褐色粗陶茶壶、浅色宋式茶盏、竹制茶筅、茶则与小型陶制茶罐，陶器表面具有自然手工纹理和轻微使用痕迹。女子右手持茶筅，左手扶住茶盏，垂眸专注于茶汤表面，手腕保持稳定。木质格栅窗外可见竹影，清晨暖金色阳光斜射进入室内，在青砖地面和木案上形成规则光影，空气中有极细微尘埃。茶盏中的茶汤产生细密泡沫，淡薄茶雾向上盘旋，窗外竹影随微风缓慢移动，女子袖口随着手腕动作产生轻微摆动。前景以一只虚化茶盏作为空间遮挡，中景人物与茶案，背景为格栅窗和竹影，平视中近景，焦点落在人物眉眼与茶筅之间，浅景深，柔和电影化质感，低饱和米白、黛绿、藕荷色调，真实皮肤纹理，细腻自然光影。

**② 图生视频版**：
镜头保持稳定并缓慢向人物推进。女子手腕持续缓慢转动茶筅，茶汤泡沫逐渐增多，茶雾向上盘旋后变淡，窗外竹影随微风轻轻移动，最后女子动作逐渐放慢并抬起眼睛。人物、服装、茶具位置保持一致。

**③ 5 秒动态版**：

```
0～1s  女子跪坐案前保持稳定，轻微呼吸，茶雾较浓。
1～3s  右手持茶筅缓慢旋转，茶汤泡沫逐渐增多。
3～4s  茶面细密泡沫成形，茶雾向上盘旋变淡，衣袖轻微摆动。
4～5s  手腕停稳，女子缓缓抬眼，动作自然落点。
运镜：固定 → 极慢推进
禁止：突然转身 / 大幅挥袖 / 人物位移 / 茶具跳变 / 镜头突然切换
```

**CASE 02｜古代女子晨妆**

**① 图片版**：
人物：P02｜世家贵女（长圆脸、妆台晨妆）
场景：S01｜宋式闺房
道具：D06/D07｜铜镜/木梳
主动作：A09｜梳发
互动：I19｜衣袖随梳动、I20｜发簪反光
光影：窗外晨光斜束、柔和侧光照亮面部与铜镜边缘
构图：中近景、人物右置、铜镜前景主体、镜中与真人空间呼应
材质：浅景深、柔和暖米色调、自然皮肤纹理、细微胶片颗粒
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

清晨，宋式闺房内，一名二十岁左右的世家女子坐于木质妆台前，长圆脸，眉眼清秀端正，乌发梳成精致低髻，发间佩一支白玉簪，穿浅青色褙子与米白色长裙，衣料细腻柔软。妆台上摆放古代铜镜、木梳、白玉簪、小型妆盒与香盒，铜镜表面具有轻微氧化痕迹，不呈现代镜面的强反射。女子一手扶住发丝，一手持木梳缓慢整理鬓边头发，目光落在铜镜中的自己，神情安静专注。窗外晨光穿过格栅窗，形成斜向光束，照亮人物侧脸、手指与铜镜边缘，墙面保留柔和光影变化。木梳从发根缓慢移动到发尾，少量碎发随着动作产生轻微变化，窗外竹叶投影缓慢移动。构图采用中近景，人物位于画面右侧，铜镜作为前景视觉主体，镜中人物与真实人物形成空间关系，浅景深，柔和暖米色调，自然皮肤纹理，细微胶片颗粒。
**② 图生视频版**：首帧 P01+S01+D06/D07；主动作 A09 梳发；微动作 垂眸、呼吸；道具动态 木梳缓慢移动、碎发轻动；环境动态 窗外竹影移动；镜头 固定→极慢推近；结束 梳至发尾停稳；连续性 人物/妆台/铜镜位置不变。

**③ 5 秒动态版**：0-1s 人物坐于妆台前稳定，晨光斜入；1-3s 右手持木梳从发根缓慢梳向发尾，目光落在镜中；3-4s 碎发轻动，竹影移动，发簪反光微闪；4-5s 梳至发尾停稳。运镜：固定→极慢推近。禁止：转头/大幅动作/镜面跳变。

**CASE 03｜婚嫁系红绸**

**① 图片版**：
人物：P05｜新婚女子
场景：S15｜婚嫁庭院
道具：D22｜红绸
主动作：A10｜系绸结
互动：I09｜红绸边缘飘动、I28｜礼盒绸带摆动
光影：晨间庭院侧光、红绸柔和丝绸高光
构图：中景、木门框景、人物中央偏右、前景花枝虚化
材质：低饱和深红木色米白、真实布料纹理、电影化自然光
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

传统婚嫁庭院中，一名二十岁左右的新婚女子站在木门旁，鹅蛋脸，眉眼柔和，黑发梳成正式婚髻，佩少量金玉发饰，穿深红色传统婚嫁服饰，衣襟与袖口有细致纹样。木门两侧悬挂红绸，门前摆放木制礼盒、竹篮与妆奁，青砖地面略有使用痕迹。女子双手捏住红绸两端，正在将红绸系成结扣，动作谨慎而缓慢，垂眸，神情带有新婚初期的羞涩。晨间阳光从庭院一侧斜照进来，红绸表面出现柔和丝绸高光，人物面部处于柔和侧光中。红绸边缘随微风轻轻飘动，礼盒上的绸带产生轻微摆动，女子袖口随手腕动作自然垂落。中景构图，木门形成纵深框景，人物位于中央偏右，前景有轻微虚化花枝，背景为庭院与回廊，低饱和深红、木色、米白色调，真实布料纹理，电影化自然光。
**② 图生视频版**：首帧 P05+S15+D22；主动作 A10 系绸结；微动作 垂眸、手指轻捻；道具动态 红绸边缘轻飘、礼盒绸带摆动；环境动态 晨光斜照、庭院微尘；镜头 中景固定→轻微推近；结束 结扣成形停稳；连续性 新娘/红绸/木门一致。

**③ 5 秒动态版**：0-1s 新娘站木门前稳定，红绸垂落；1-3s 双手交叉、绕过、收紧系结；3-4s 红绸边缘轻飘，袖口自然垂落；4-5s 结扣成形，动作停稳。运镜：固定→微推。禁止：突然转身/红绸大幅飘动。

**CASE 04｜秋日打谷**

**① 图片版**：
人物：P10｜年轻农妇
场景：S08｜秋日打谷场
道具：D27｜竹篮
主动作：A15｜捡拾谷物
互动：I23｜谷粒连续落入竹篮
光影：秋日低角度侧逆光、谷粒金色轮廓光、尘埃浮金
构图：中远景、人物占画面约半、前景谷物虚化层、背景村舍纵深
材质：暖金灰褐深青、自然纪实电影质感
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

深秋午后，乡村打谷场上，一名二十余岁的年轻农妇站在竹筐旁，圆润自然的脸型，黑发简单挽成低髻，穿灰褐色粗布衣衫与深青长裙，衣物具有真实生活褶皱和轻微磨损。地面铺着晾晒的谷物，周围摆放竹筐、木耙、粮袋和木桶，远处是夯土墙与木屋。女子弯腰用双手收拢谷物，将谷粒放入竹筐，神情专注，动作熟练。秋日低角度阳光从侧后方照射，谷粒边缘出现细微金色轮廓光，空气中少量尘埃被照亮。谷粒从手掌连续落入竹筐，少量谷粒弹落在地面，远处布料和树叶随微风轻微移动。中远景，人物占画面约一半，前景谷物形成浅虚化层，背景村舍形成纵深，暖金、灰褐、深青色调，自然纪实电影质感。
**② 图生视频版**：首帧 P10+S08+D27；主动作 A15 捡拾谷物；微动作 弯腰、手掌握合；道具动态 谷粒连续落入竹篮、少量弹落；环境动态 秋阳低照、尘埃浮金；镜头 低机位固定；结束 收手入篮停稳；连续性 农妇/竹筐/谷物一致。

**③ 5 秒动态版**：0-1s 农妇蹲于竹筐旁稳定；1-3s 双手收拢谷粒放入竹篮；3-4s 谷粒连续落下形成颗粒流，少量弹落地面；4-5s 收手停稳。运镜：低机位固定。禁止：人物位移/谷粒静止。

**CASE 05｜香道**

**① 图片版**：
人物：P26｜香道女子
场景：S02｜宋式书房
道具：D12/D14/D15｜香炉/香箸/香灰
主动作：A07｜整理香灰
互动：I05｜香烟上腾、I06｜香灰细线
光影：窗边斜射自然光、香炉低调旧铜反光
构图：近中景、前景书卷虚化、香案中景、格栅窗背景
材质：低反差低饱和米白木色、安静克制
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

午后安静的宋式书房，一名二十余岁的古代女子跪坐在香案前，面容清雅，黑发低髻，穿浅米色宽袖衣裙。香案中央摆放小型青铜香炉、香盒、香箸与细腻浅灰色香灰，旁边放有一卷线装书。女子一手持香箸，一手轻扶香炉，正在整理香灰表面，眼神集中，动作缓慢而精细。窗边斜射进入柔和自然光，香炉表面产生低调旧铜色反光，人物手指和香灰成为视觉焦点。香箸缓慢划过香灰表面，留下平整细线，少量香灰颗粒向两侧散落，香炉内部细薄烟雾向上升腾并被微弱气流吹向窗边。近中景，前景为虚化书卷，人物与香案位于中景，背景为格栅窗，低反差、低饱和米白与木色调，安静、克制、真实。
**② 图生视频版**：首帧 P26+S02+D12/D14/D15；主动作 A07 整理香灰；微动作 屏息、指尖轻动；道具动态 香灰细线、香烟上腾；环境动态 侧光斜入、微尘漂浮；镜头 近中景固定→极慢推近；结束 香箸停稳；连续性 香案/香炉一致。

**③ 5 秒动态版**：0-1s 跪坐香案前稳定；1-3s 香箸缓缓划过香灰表面；3-4s 香烟被气流吹偏，灰粒向两侧散落；4-5s 收箸停稳。运镜：固定→极慢推近。禁止：烟气突变/香灰大幅翻动。

**CASE 06｜节日花灯**

**① 图片版**：
人物：P28｜节日少女
场景：S26｜节日灯市
道具：D21｜花灯
主动作：A13｜提灯
互动：I08｜灯笼轻晃、I29｜花灯穗子滞后摆动
光影：暖灯色照亮面部侧面、轮廓与背景灯火分离、薄雾
构图：中景跟拍、浅景深、前后灯火柔和散景
材质：深红暖金木色青绿、东方夜色氛围
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

传统节日夜间街市，一名十七八岁的年轻女子走在灯市中，面容清秀，半挽长发，佩一枚小巧花饰，穿浅青色节日衣裙，手持一盏传统纸花灯。街道两侧为木质店铺，大量纸灯笼形成前中后景，青石路面受到灯火映照产生柔和反光，远处行人穿着传统服饰。女子缓慢向前行走，视线落在手中的花灯上，脸上带着轻微喜悦。暖色灯光照亮面部侧面，人物轮廓与背景灯火形成柔和分离，空气中有轻微薄雾。花灯随着步伐缓慢晃动，底部穗子产生滞后摆动，内部烛火轻微跳动，远处灯笼亮度产生细微变化。中景跟拍，镜头缓慢向前移动，浅景深，前后灯火形成柔和散景，深红、暖金、木色与青绿色形成东方夜景色盘。
**② 图生视频版**：首帧 P28+S26+D21；主动作 A13 提灯；微动作 垂眸看灯、缓步；道具动态 花灯轻晃、穗子滞后摆动、烛火跳动；环境动态 人流剪影、灯市薄雾；镜头 中景跟拍慢移；结束 停步灯稳；连续性 少女/花灯/街巷一致。

**③ 5 秒动态版**：0-1s 少女持灯行走稳定；1-3s 缓步前行，花灯随步伐轻晃；3-4s 穗子滞后摆动，烛火跳动，远处灯火闪烁；4-5s 停步，花灯渐稳。运镜：中景跟拍。禁止：灯突然熄灭/人物位移跳变。

**CASE 07｜老人雪中归来**

**① 图片版**：
人物：P12｜老人
场景：S22｜雪中村落
道具：D32｜竹杖
主动作：A75｜缓步
互动：I18｜雪花落肩轻滑
光影：冷白晨光从山谷进入、肩头白须轮廓光
构图：中远景、老人占画面较小比例、雪地与村落形成尺度
材质：低饱和冷灰米白深灰、真实冬季空气感
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

冬日清晨，古代村落外的雪径上，一名七十岁左右的老人缓慢走过石板小路，瘦削面部，白须自然垂落，头戴旧布巾，身穿深灰色长袍，手持竹杖。道路两侧为覆盖薄雪的夯土墙和木屋，屋檐有少量冰凌，地面留下零散脚印，远处屋顶升起淡淡炊烟。老人身体略微前倾，一手握竹杖，一手扶住衣袖，缓慢向前行走，呼出的白雾清晰可见。冷白色晨光从山谷方向进入，老人肩头和白须边缘出现柔和轮廓光。细雪持续落下，少量雪花停留在老人肩头和发梢，随后随着行走轻微滑落，竹杖接触雪地留下连续痕迹。中远景，老人占画面较小比例，以雪地和村落形成环境尺度，低饱和冷灰、米白、深灰色调，真实冬季空气感。
**② 图生视频版**：首帧 P12+S22+D32；主动作 A75 缓步；微动作 呼气成雾、扶杖；道具动态 竹杖点地留痕、雪花落肩；环境动态 细雪持续落下、远处炊烟；镜头 中远景固定→慢拉远；结束 背影渐远留白；连续性 老人/雪径/村落一致。

**③ 5 秒动态版**：0-1s 老人在雪径稳定行走；1-3s 缓步向前，竹杖点地；3-4s 雪花落肩滑落，白雾清晰；4-5s 走远，画面留白收束。运镜：中远景固定→慢拉远。禁止：雪突然停/人物跳变。

**CASE 08｜绣娘**

**① 图片版**：
人物：P18｜绣娘
场景：S12｜绣房
道具：D25/D26｜针线盒/绣架
主动作：持针穿布（I27 针线互动）
互动：I27｜针尖穿绸、丝线拉紧成弧
光影：窗外阳光穿格栅窗、照亮丝线手指与绣面、尘埃浮光
构图：近中景、焦点在手部绣面、面部第二焦点、背景木窗虚化
材质：米白浅青木色低饱和、真实织物质感
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

午后古代绣房，一名二十余岁的民间绣娘坐在木案前，面容柔和，黑发挽成简单低髻，穿浅青色布衣。木案上摆放绣架、针线盒、彩色丝线与剪刀，墙边悬挂一幅尚未完成的绣品。女子左手扶住丝绸绣面，右手持针缓慢穿过布料，眼神集中在针尖位置。窗外阳光穿过格栅窗，照亮丝线、手指和绣面，细小尘埃在光线中漂浮。针尖反复穿过丝绸，丝线被拉紧后形成细微弧线，布面随着手指动作产生极轻微变化。近中景，焦点集中在人物手部和绣面，人物面部处于第二焦点区域，背景木窗柔和虚化，米白、浅青、木色构成低饱和色调。
**② 图生视频版**：首帧 P18+S12+D25/D26；主动作 持针穿布（I27 针线互动）；微动作 屏息、指尖轻动；道具动态 针线拉紧成弧；环境动态 尘埃浮光、窗外斜光；镜头 近中景固定→微推手部；结束 针停布面；连续性 绣娘/绣架/丝线一致。

**③ 5 秒动态版**：0-1s 绣娘持针稳定；1-3s 针尖缓慢穿过丝绸；3-4s 丝线拉紧成弧，尘埃浮动；4-5s 针停布面，动作停稳。运镜：固定→微推手部。禁止：手部穿模/丝线乱。

**CASE 09｜河岸洗衣**

**① 图片版**：
人物：P03｜民间年轻妇人
场景：S20｜河岸
道具：D27/D29/D30｜竹篮/木桶/水瓢
主动作：A78｜俯身拧布
互动：I15｜水面涟漪、I24｜木桶水面波纹
光影：晨光河面反射、浅金色反光、湿布柔亮
构图：中景、人物左侧、河流纵深延伸、前景水面虚化
材质：真实朴素生活化、自然纪实
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

清晨古代河岸，一名二十余岁的年轻妇人蹲坐在河边石阶上，黑发简单低髻，穿浅灰蓝色布衣与深色长裙。河岸旁放着竹篮、木盆与一叠浅色布料，远处停靠一只小木船，岸边垂柳伸向水面。女子双手将布料浸入河水后缓慢拧动，身体略微前倾，神情专注。晨光从河面反射回来，人物面部与湿润布料出现柔和亮度，水面产生浅金色反光。布料离开水面时水滴连续落下，水面形成细小涟漪，柳枝被微风吹动，远处木船轻微摇晃。中景，人物位于画面左侧，河流向远处延伸形成纵深，前景水面轻微虚化，整体真实、朴素、生活化。
**② 图生视频版**：首帧 P03+S20+D27/D29/D30；主动作 A78 俯身拧布；微动作 俯身、双手拧动；道具动态 水滴连续落下、水面涟漪；环境动态 晨光反射、柳枝轻摆；镜头 中景固定；结束 布料拧干停稳；连续性 妇人/河岸/木盆一致。

**③ 5 秒动态版**：0-1s 妇人蹲石阶稳定；1-3s 布料浸水缓慢拧动；3-4s 水滴落下，水面涟漪扩散；4-5s 拧布停稳。运镜：中景固定。禁止：水面突变/人物起身。

**CASE 10｜古代婚礼仪式**

**① 图片版**：
人物：P05/P06｜新娘/新郎
场景：S15｜婚嫁庭院
道具：D22/D23｜红绸/礼盒
主动作：A51｜庄重站立
互动：I09｜红绸边缘飘动、I05｜香烟上腾
光影：晨间暖光从厅堂侧面进入、红绸形成暖色视觉中心
构图：中远景建立仪式空间、随后慢推至新人
材质：低饱和真实克制、电影化
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

传统古代婚嫁仪式庭院，青砖地面，木质厅堂，门框悬挂深红色绸带，中央摆放礼仪案台，案上放置香炉、礼盒与简单供品。新郎与新娘分别站在仪式位置，新郎穿深青色传统礼服，新娘穿深红色婚嫁服饰，双方姿态端正，动作克制，视线按照礼仪方向保持稳定。旁侧有媒人和侍女作为辅助人物，侍女双手捧着礼盒，媒人站在稍后位置观察仪式。晨间或午后暖光从厅堂侧面进入，红绸与木质建筑形成暖色视觉中心，香烟从香炉中缓慢升起。新娘衣袖随着身体动作轻微摆动，红绸边缘被微风吹动，香烟缓慢向上散开，人物动作保持缓慢庄重。采用中远景建立仪式空间，随后缓慢推进至新娘与新郎，整体低饱和、真实、克制、电影化。
**② 图生视频版**：首帧 P05/P06+S15+D22/D23；主动作 A51 庄重站立；微动作 视线按礼仪方向、衣袖微动；道具动态 红绸轻飘、香烟上腾；环境动态 晨光斜照、宾客微动；镜头 中远景→慢推至新人；结束 仪式定格；连续性 新人/礼服/站位一致。

**CASE 11｜春节·贴春联**（四联格式·V3.86 新增）

**① 图片版**：
人物：P25｜村中长者 + P13｜小女孩（祖孙）
场景：S06｜乡村院落（冬晨老宅门前）
道具：D17/D18｜毛笔/砚台 + 红纸金墨（时令）
主动作：A05｜执笔写福
互动：I14｜墨液波纹、笔尖带墨
光影：冬日晨光侧逆、暖金调、光柱金尘浮动
构图：中景对称、前景毛笔红纸清晰、背景老宅门框虚化
材质：85mm f/2.8、浅景深、胶片质感
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

V1 古风·庄重仪式基调。冬日清晨，老宅朱漆大门前，晨光斜照，案上红纸金墨铺展。老者着深色棉袍，手持毛笔蘸墨写福字，笔锋遒劲，墨迹未干。孩童着红袄站一旁踮脚张望，呼出白气。窗光侧逆，暖金调，光柱中金尘浮动。中景固定镜头，构图对称，前景毛笔与红纸清晰，背景老宅门框虚化。85mm，f/2.8，ISO 400。负面词：手部畸形，六指，五官错位，现代物品，低质量。
**② 图生视频版**：首帧 P25+S06+D17/D18；主动作 A05 执笔写福；微动作 屏息、笔锋顿挫；道具动态 墨迹渐显、笔尖悬停；环境动态 晨光斜照、红纸轻翘；镜头 中景固定；结束 福字落笔停稳；连续性 长者/红纸/案台一致。
**③ 5 秒动态版**：0-1s 老者执笔立于案前稳定；1-3s 蘸墨落笔写福字；3-4s 墨迹渐显，孩童踮脚张望；4-5s 收笔，福字成形。运镜：中景固定。禁止：墨迹突变/人物位移。
**④ 多镜头完整分镜版**（3 镜/15s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 中景 | 固定 | 冬日清晨老宅门前，晨光斜照，老者执笔写福字，孩童踮脚张望 | "爷爷，这个福字写得真好！" | 环境：晨间鸟鸣+远处鞭炮；BGM：古琴轻快 |
| 2 | 5s | 近景 | 缓推 | 祖孙贴春联，老者抚平上联，孩童踮脚递浆糊，呼出白气 | "福到了！" | 环境：风声+衣料摩擦；BGM：琵琶+锣鼓轻点 |
| 3 | 5s | 全景 | 慢拉远 | 贴完春联相视而笑，门楣红纸晨风中轻扬，镜头拉远小院入画 | 新年大吉 | BGM：民乐合奏渐强+一声锣 |

**CASE 12｜元宵·赏灯/猜灯谜**（四联格式·V3.86 新增）

**① 图片版**：
人物：P28｜节日少女
场景：S26｜节日灯市
道具：D21｜花灯 + D20｜纸灯笼
主动作：A13｜提灯
互动：I08｜灯笼轻晃、I29｜花灯穗子滞后
光影：暖灯色照亮面部侧面、灯火散景、薄雾
构图：中景跟拍、浅景深、前后灯火柔和散景
材质：深红暖金木色青绿、东方夜色氛围
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

元宵夜，传统灯市如昼，沿街木铺挂满纸灯笼，青石路面灯火映照泛光，薄雾轻浮。一名十七八岁的少女半挽长发、佩小巧花饰、穿浅青色节日衣裙，手持一盏纸花灯缓步穿行。灯下檐角垂着灯谜纸条，随风轻摆，暖光将少女侧脸照亮，目光落在纸条上，神色好奇含笑。中景跟拍，浅景深，前后灯火化为柔和散景。深红、暖金、木色与青绿色构成东方夜景色盘。
**② 图生视频版**：首帧 P28+S26+D21；主动作 A13 提灯；微动作 驻足抬头、目光随灯谜移动；道具动态 花灯轻晃、灯谜纸条轻摆、烛火跳动；环境动态 人流剪影、灯影摇曳；镜头 中景跟拍→缓推；结束 驻足凝望停稳；连续性 少女/花灯/灯市一致。
**③ 5 秒动态版**：0-1s 少女持灯行走稳定；1-3s 缓步前行，花灯随步伐轻晃；3-4s 灯谜纸条摆动，烛火跳动；4-5s 驻足抬头看灯谜。运镜：中景跟拍。禁止：灯灭/人群跳变。
**④ 多镜头完整分镜版**（3 镜/15s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 横移 | 灯市定场，灯火如昼，人流穿行，纸灯笼成片 | 元宵灯会，火树银花 | BGM：丝竹+鼓点轻快 |
| 2 | 5s | 中景 | 跟拍 | 少女提花灯缓步穿行，侧脸被暖灯照亮 | "这盏灯谜，猜中有奖！" | 环境：人声+灯市喧嚣；BGM：琵琶 |
| 3 | 5s | 近景 | 固定 | 灯谜纸条特写，少女仰头凝望，眼中有灯火 | "月上柳梢头，人约黄昏后——是元宵！" | BGM：丝竹收束 |

**CASE 13｜端午·包粽子**（四联格式·V3.86 新增）

**① 图片版**：
人物：P11｜老年妇人（老妪）
场景：S20｜河岸老宅檐下
道具：D27｜竹篮 + D43｜陶罐（糯米）
主动作：双手卷粽叶捆扎（库无对应编号·按手部劳作描述）
互动：I23｜米粒落入盆中
光影：晨光漫射、水汽氤氲、低反差
构图：近景缓慢推镜、从双手推至面部
材质：50mm f/2.0、柔和晨光、真实织物质感
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

V2 古风·清冷意境基调。端午清晨，河岸老宅檐下，薄雾水面透进柔光。老妪坐竹椅，靛蓝布衫青布围裙，花白银发，面容慈祥。双手卷粽叶，糯米从指缝落入盆中，盆中米粒泛温润白，粽叶翠绿纹理清晰。晨光漫射，水汽氤氲，低反差。近景缓慢推镜，从双手推至面部。50mm，f/2.0，ISO 400，柔和晨光。负面词：手部畸形，六指，现代物品，低质量。
**② 图生视频版**：首帧 P11+S20+D27/D43；主动作 卷叶捆扎；微动作 指腹压实、手腕翻转；道具动态 糯米指缝漏落、粽叶翠色纹理；环境动态 水面薄雾、芦苇轻摆；镜头 近景慢推；结束 粽子捆扎成形；连续性 老妪/竹篮/粽叶一致。
**③ 5 秒动态版**：0-1s 老妪坐竹椅稳定；1-3s 双手卷粽叶、糯米落入盆中；3-4s 草绳绕三圈打结；4-5s 粽子成形，动作停稳。运镜：近景慢推。禁止：米粒乱飞/手部穿模。
**④ 多镜头完整分镜版**（4 镜/20s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 横移 | 河岸人家，薄雾水面，芦苇轻摆，檐下挂艾草，石阶摆糯米粽叶 | "五月初五，包粽子咯！" | 环境：水流+风声；BGM：古筝轻奏 |
| 2 | 5s | 近景 | 缓推 | 老妪卷粽叶，糯米从指缝落入盆中，面容慈祥 | "糯米要泡透才香。" | 环境：米粒沙沙声；BGM：竹笛轻快 |
| 3 | 5s | 特写 | 固定 | 草绳捆粽绕三圈打结，粽叶逆光透翠，水滴沿叶尖滑落 | （无） | 环境：水滴+绳摩擦；BGM：轻柔弦乐 |
| 4 | 5s | 全景 | 慢拉远 | 竹篮盛满新粽，蒸汽升腾，灯笼暖光穿水雾，龙舟鼓声渐近 | 端午安康 | BGM：鼓点渐强+民乐收束 |

**CASE 14｜中秋·拜月**（四联格式·V3.86 新增）

**① 图片版**：
人物：P25｜村中长者 + P13｜小女孩
场景：S17｜古代庭院（月下）
道具：D12｜香炉 + D39｜糕点 + D40｜果盘
主动作：A08｜插香
互动：I05｜香烟上腾
光影：月光铺满青石阶、暖烛微光
构图：全景横移→近景插香→全景拉远
材质：低饱和、青石月光、真实
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

中秋夜，传统庭院香案摆开，月饼瓜果列阵，三炷线香青烟直上，月光铺满青石阶。长者着深色长袍立于案前拈香，垂目肃穆，小女孩仰头看月。檐角灯笼透出暖光，桂树影斜。全景横移后缓推香案，低饱和冷月暖烛对比，青石与木色真实质感。
**② 图生视频版**：首帧 P25+S17+D12/D39/D40；主动作 A08 插香；微动作 垂目肃立、香头明灭；道具动态 香烟上腾、青烟直上；环境动态 月光铺阶、桂香浮动；镜头 全景横移→缓推香案；结束 香插稳、青烟缭绕；连续性 长者/香案/庭院一致。
**③ 5 秒动态版**：0-1s 庭院香案稳定，月光铺阶；1-3s 长者拈香插入香炉；3-4s 香烟上腾，烛火微动；4-5s 垂目肃立，仪式定格。运镜：全景→缓推。禁止：烟雾突变/月光跳变。
**④ 多镜头完整分镜版**（4 镜/20s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 横移 | 庭院香案，月饼瓜果列阵，三炷线香青烟直上，月光铺满青石阶 | "今夜月明，敬天地一轮。" | 环境：蟋蟀+风声；BGM：古琴缓起 |
| 2 | 5s | 中景 | 缓推 | 长者拈香插炉，垂目肃立，香头明灭 | （无） | 环境：香炉轻响；BGM：古琴+箫 |
| 3 | 5s | 近景 | 固定 | 祖母切月饼，刀刃切入酥皮，碎屑飘落，孩童紧盯切面 | "给你最大那块。" | 环境：刀切酥皮声；BGM：琵琶轻奏 |
| 4 | 5s | 全景 | 慢拉远 | 月下庭院全家围坐分食赏月，孩童举饼指月，画面渐暗圆月悬空 | 千里共婵娟 | BGM：民乐渐弱+余韵留白 |

**CASE 15｜七夕·穿针乞巧**（四联格式·V3.86 新增）

**① 图片版**：
人物：P01｜宋代闺阁少女
场景：S01｜宋式闺房（夜·烛火灯下）
道具：D25｜针线盒 + D26｜绣架
主动作：引线穿针（库无编号·文字描述）
互动：I27｜针尖穿绸、丝线拉紧成弧
光影：烛火暖光、月影窗棂、窗外星辉
构图：近景特写手部针线→缓推面部
材质：暖金暗调、浅景深、绢帛质感
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

七夕夜，宋式闺房内，烛火一盏，少女于灯下引线穿针，指尖轻捻丝线对准针孔，目光专注。窗棂透进月光，窗外夜色中隐约银河星辉。绣架与针线盒置案边，丝线泛柔光。近景特写手部针线，浅景深，暖金暗调，绢帛质感真实。
**② 图生视频版**：首帧 P01+S01+D25/D26；主动作 引线穿针；微动作 屏息、指尖轻捻丝线；道具动态 丝线穿过针孔、烛火跳动；环境动态 月影、星辉、烛影摇曳；镜头 近景固定→微推手部；结束 线过针孔、抬手轻展；连续性 少女/针线/烛台一致。
**③ 5 秒动态版**：0-1s 少女坐烛下稳定；1-3s 指尖捻线对准针孔；3-4s 丝线穿过针孔，烛火跳动；4-5s 抬手轻展丝线，含笑。运镜：近景固定→微推。禁止：丝线乱/手部穿模。
**④ 多镜头完整分镜版**（3 镜/15s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 固定 | 闺房烛下，少女坐于案前，窗外月辉银河入窗 | "七月初七，乞巧穿针。" | 环境：夜虫声；BGM：古筝清冷 |
| 2 | 5s | 近景 | 微推 | 指尖捻线穿过针孔，烛火跳动，丝线泛光 | （无） | 环境：烛火噼啪；BGM：箫 |
| 3 | 5s | 中景 | 固定 | 少女展线望月，含笑，月色铺满窗棂 | "愿乞天孙巧。" | BGM：古筝收束 |

**CASE 16｜成人礼·笄礼**（四联格式·V3.86 新增）

**① 图片版**：
人物：P01｜宋代闺阁少女（及笄）+ P22｜宫廷贵妇（正宾）
场景：S04｜贵族厅堂
道具：D08｜白玉簪（笄）+ D24｜妆奁
主动作：A09｜梳发（挽发加笄）
互动：I20｜发簪插定、反光微闪
光影：厅堂暖光、仪式庄重、香炉青烟
构图：中景对称、礼仪站位、人物居画面中轴
材质：低饱和、丝缎光泽、庄重克制
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

宋式贵族厅堂，笄礼进行时。少女跪坐中央蒲席，乌发半挽，着素色深衣；正宾立于其后，双手持白玉笄为其挽发加笄。厅堂高挑梁柱，案上香炉青烟直上，屏风与妆奁陈设两侧。暖光自侧窗进入，庄重肃穆。中景对称构图，人物居画面中轴，低饱和木色与素色，丝缎光泽真实。
**② 图生视频版**：首帧 P01/P22+S04+D08/D24；主动作 A09 梳发加笄；微动作 少女垂眸、正宾手稳；道具动态 玉簪插定、发丝轻拢；环境动态 厅堂暖光、香炉烟直；镜头 中景固定→慢推插笄手部；结束 笄簪插定、礼成；连续性 少女/发髻/厅堂一致。
**③ 5 秒动态版**：0-1s 少女跪坐厅中稳定；1-3s 正宾为她挽发；3-4s 玉簪插入发髻，反光微闪；4-5s 礼成，少女抬眼。运镜：中景→慢推。禁止：发髻散乱/簪子偏移。
**④ 多镜头完整分镜版**（3 镜/15s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 固定 | 厅堂笄礼定场，少女跪坐中央，正宾立于其后，香炉青烟 | "始加笄，一拜。" | BGM：编钟+古琴庄重 |
| 2 | 5s | 近景 | 缓推 | 正宾挽发插笄，玉簪入髻，少女垂眸 | "弃尔幼志，顺尔成德。" | 环境：衣料窸窣；BGM：古琴 |
| 3 | 5s | 中景 | 固定 | 礼成，少女抬眼，神情端肃 | "笄礼已成。" | BGM：编钟收束 |

**CASE 17｜重阳·登高/敬老**（四联格式·V3.86 新增）

**① 图片版**：
人物：P12｜老人 + P07｜文士（扶老人登高）
场景：S21｜山间古道
道具：D32｜竹杖 + D44｜铜壶（菊花酒）
主动作：A75｜缓步
互动：I10｜菊花瓣飘落
光影：秋日侧逆光、山雾轻移
构图：中远景、人物留白、山道纵深
材质：暖秋色调、真实空气感
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

重阳秋日，山间石板古道，文士扶老人登高。老人着深灰长袍拄竹杖缓行，文士着月白宽袖袍轻扶其臂，鬓边插茱萸。石阶两侧野菊盛开，菊瓣随风飘落，远处山雾轻移，秋叶半黄。秋日侧逆光勾勒衣袍轮廓，中远景留白，山道向高处延伸，暖秋色调。
**② 图生视频版**：首帧 P12/P07+S21+D32；主动作 A75 缓步登高；微动作 喘息、互扶衣袖；道具动态 竹杖点地、菊花瓣飘落；环境动态 山雾轻移、秋叶飘落；镜头 中远景固定→慢拉远；结束 登顶远望留白；连续性 老人/山道/秋景一致。
**③ 5 秒动态版**：0-1s 老人拄杖山道稳定；1-3s 缓步登阶，文士相扶；3-4s 菊花瓣飘落，衣袂轻动；4-5s 登顶远望，山雾收束。运镜：中远景→慢拉远。禁止：人物跳变/山雾突变。
**④ 多镜头完整分镜版**（3 镜/15s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 固定 | 秋山古道定场，石阶蜿蜒，野菊与茱萸点染，山雾 | "九月九日，登高望远。" | 环境：风声+鸟鸣；BGM：古琴+箫悠远 |
| 2 | 5s | 中景 | 缓推 | 文士扶老人登阶，菊瓣飘落，衣袂轻动 | "爹，慢些走。" | 环境：脚步+落叶声；BGM：箫 |
| 3 | 5s | 全景 | 慢拉远 | 登顶，文士奉菊花酒，老人远望群山 | "敬您一杯菊花酒，岁岁安康。" | BGM：古琴收束 |

**CASE 18｜清明·踏青/插柳**（四联格式·V3.86 新增）

**① 图片版**：
人物：P01｜宋代闺阁少女 + P13｜小女孩
场景：S23｜春日花园（春堤柳色）
道具：D36｜花枝（柳枝）
主动作：A12｜捧花（折柳簪发）
互动：I11｜柳枝轻摆、I10｜花瓣飘落
光影：春日漫射光、柳色新绿、云影
构图：中景、人物与柳枝呼应
材质：清新低饱和、春色真实
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

清明踏青，春日河堤柳色新绿，细雨初霁。少女着浅青宋制衣裙折柳一枝，拈柳簪向鬓边，小女孩在旁仰头看。柳枝轻摆，花瓣与柳絮飘落，春水泛起涟漪，云影缓慢移动。漫射春光照亮衣料，中景构图，人物与柳枝呼应，清新低饱和色调。
**② 图生视频版**：首帧 P01/P13+S23+D36；主动作 A12 折柳簪发；微动作 指尖拈柳、轻簪鬓边；道具动态 柳枝轻摆、花瓣飘落；环境动态 春水涟漪、云影移动；镜头 中景固定→微推；结束 柳枝簪定含笑；连续性 少女/柳枝/春景一致。
**③ 5 秒动态版**：0-1s 少女立柳下稳定；1-3s 折柳拈枝；3-4s 柳枝簪入鬓边，花瓣飘落；4-5s 含笑抬眼。运镜：中景→微推。禁止：花瓣乱飞/柳枝穿模。
**④ 多镜头完整分镜版**（3 镜/15s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 横移 | 春堤柳色定场，细雨初霁，春水涟漪，云影 | "清明时节雨纷纷。" | 环境：鸟鸣+流水；BGM：竹笛轻快 |
| 2 | 5s | 中景 | 缓推 | 少女折柳簪发，小女孩仰头看 | "插柳戴柳，一年清吉。" | 环境：柳枝沙沙；BGM：笛 |
| 3 | 5s | 近景 | 固定 | 拈花微笑，花瓣落在肩头 | "踏青去。" | BGM：竹笛收束 |

**CASE 19｜冬至·家宴/团聚**（四联格式·V3.86 新增）

**① 图片版**：
人物：P20｜厨娘 + P11｜老年妇人 + P13｜小女孩
场景：S05｜古代厨房（备餐·灶火暖光）
道具：D41｜食盒 + D42｜木勺 + D43｜陶罐
主动作：木勺搅动汤锅（库无编号·文字描述）
互动：I30｜水汽与光（蒸汽升腾）
光影：灶火暖光、蒸汽逆光、窗外飞雪
构图：近景汤锅→中景家宴暖光
材质：暖调、真实烟火气
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

冬至夜，古代厨房灶火正旺。厨娘着深色围裙，持木勺搅动汤锅，蒸汽逆光升腾，水汽氤氲。陶罐与食盒列于案台，老妇在旁拣拾，小女孩踮脚看锅中。窗外飘雪，灶火暖光映亮厨房。近景汤锅蒸汽，中景家宴暖光，暖调真实烟火气。
**② 图生视频版**：首帧 P20/P11+S05+D41/D42/D43；主动作 木勺搅动汤锅；微动作 俯身看火、鬓发微乱；道具动态 蒸汽上腾、水面翻滚；环境动态 灶火跳动、窗外飞雪；镜头 近景固定→缓推；结束 汤沸转小火停稳；连续性 厨娘/汤锅/厨房一致。
**③ 5 秒动态版**：0-1s 厨房灶火稳定；1-3s 木勺搅动汤锅；3-4s 蒸汽升腾，水汽逆光；4-5s 转小火，汤面渐平。运镜：近景固定→缓推。禁止：蒸汽突变/火苗跳变。
**④ 多镜头完整分镜版**（3 镜/15s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 固定 | 厨房备宴定场，灶火暖光，窗外飞雪，蒸汽升腾 | "冬至大如年。" | 环境：柴火噼啪；BGM：民乐温馨 |
| 2 | 5s | 近景 | 缓推 | 汤锅蒸汽，木勺搅动，水面翻滚 | "汤圆饺子，下锅咯！" | 环境：水沸声；BGM：笛 |
| 3 | 5s | 中景 | 固定 | 全家围坐家宴，举箸，暖光融融 | "冬至团圆，一岁一安。" | BGM：民乐收束 |

**CASE 20｜上巳·临水祓禊**（四联格式·V3.86 新增）

**① 图片版**：
人物：P28｜节日少女
场景：S20｜河岸（上巳春水）
道具：D36｜花枝（兰草）+ D30｜水瓢
主动作：A14｜舀水（掬水祓禊）
互动：I15｜水面涟漪
光影：春日晨光、水波金光
构图：中景、人物临水、水岸纵深
材质：清新、水汽、春色
负面词：手部畸形，六指，五官错位，现代物品穿帮，低质量模糊
完整 Prompt：

上巳节，春日河岸，晨光洒在水面泛金。少女着浅色春衫立于水边，俯身掬水，水从指缝滑落激起细小涟漪，兰草佩于衣襟。柳枝垂水，花瓣漂于水面，水汽微润。中景构图，人物临水，河岸向远处延伸，清新春色低饱和。
**② 图生视频版**：首帧 P28+S20+D36/D30；主动作 A14 掬水；微动作 俯身、指尖触水；道具动态 水波涟漪、水珠滑落；环境动态 柳枝轻摆、花落水面；镜头 中景固定→微推水面；结束 水波渐平、少女直身；连续性 少女/河岸/水波一致。
**③ 5 秒动态版**：0-1s 少女立河岸稳定；1-3s 俯身掬水；3-4s 水从指缝滑落，涟漪扩散；4-5s 直身，水波渐平。运镜：中景→微推水面。禁止：水花四溅/人物位移。
**④ 多镜头完整分镜版**（3 镜/15s，直接拍）：
| 镜号 | 时长 | 景别 | 运镜 | 画面描述 | 对白 | 声音/BGM |
|---|---|---|---|---|---|---|
| 1 | 5s | 全景 | 横移 | 上巳春水定场，河岸柳绿，花瓣漂水，晨光泛金 | "三月三，上巳节。" | 环境：流水+鸟鸣；BGM：古筝+笛清新 |
| 2 | 5s | 近景 | 微推 | 少女俯身掬水，水珠滑落，涟漪扩散 | "临水祓禊，涤秽祈福。" | 环境：水声；BGM：古筝 |
| 3 | 5s | 中景 | 固定 | 少女直身佩兰，含笑踏歌 | "祓除不祥，岁岁平安。" | BGM：笛收束 |

### CASE 多镜头标准（第三阶段·从单镜头升级到整条视频）

> CASE01-20 的四联是"单镜头级"；多镜头标准把 CASE 升级为"整条视频级"——每镜 10 字段全填，选题 → 复制 → 改人物 → 改场景 → 直接出成片。

**镜头序列逻辑**：定场 → 准备（拿物/蘸料）→ 核心动作 → 收束动作 → 情感/观看 → 全景收束。3-7 镜，总时长 15-31s。

**每镜 10 字段**：时长 / 景别 / 运镜 / 图片 Prompt / 图生视频 Prompt / 5 秒动态 / 声音 / 环境动态 / 连续性锚点 / 负面词

**示范·CASE11 春节贴春联（7 镜/31s·V3.87 工程版）**（CASE11 ④为 3 镜速拍版，本页为逐镜工程版）：

**镜头 01｜春节院落定场**（5s·全景·固定→微俯）
- 图片 Prompt：冬日清晨老宅院落全景，门楣红灯笼高挂，旧联门框，晨光斜照，炊烟轻升，地面零星红纸屑
- 图生视频 Prompt：晨光渐亮，炊烟轻升，红纸屑被风轻卷，灯笼微晃
- 5 秒动态：0-1s 院落稳定；1-3s 晨光渐亮、炊烟升起；3-4s 红屑轻卷；4-5s 定场停稳
- 声音：远处零星鞭炮 + 晨鸟鸣
- 环境动态：炊烟升、红屑卷、晨光移
- 连续性锚点：院落布局 / 门框旧联 / 灯笼位置
- 负面词：现代物品，电线，塑料，低质量

**镜头 02｜人物拿春联**（4s·中景·缓推）
- 图片 Prompt：老者着深色棉袍双手捧红纸金墨对联走向门框，孩童红袄抱浆糊碗跟随，呵气成雾
- 图生视频 Prompt：老者缓步走向门框，衣摆轻动，孩童小跑跟随
- 5 秒动态：0-1s 持联站立；1-3s 缓步走向门框；3-4s 孩童跟随；4-5s 门前停稳
- 声音：脚步声 + 孩童哼唱
- 环境动态：衣摆动、呵气白雾
- 连续性锚点：服装 / 红纸金墨联 / 发型
- 负面词：手部畸形，文字乱码，现代物品

**镜头 03｜蘸浆糊**（4s·近景特写·固定）
- 图片 Prompt：老者手持竹刷蘸浆糊，浆糊在刷面拉丝，孩童踮脚看，晨光斜照
- 图生视频 Prompt：竹刷蘸入浆糊，浆糊拉丝轻滴
- 5 秒动态：0-1s 持刷稳定；1-3s 蘸入浆糊；3-4s 浆糊拉丝轻滴；4-5s 抬刷停稳
- 声音：浆糊黏稠声
- 环境动态：浆糊拉丝、晨光
- 连续性锚点：竹刷 / 浆糊碗 / 手部
- 负面词：手部畸形，浆糊乱溅，低质量

**镜头 04｜抬手贴春联**（5s·中景·缓推）
- 图片 Prompt：老者抬手将上联按在门框右侧，孩童在旁扶联下端，纸张晨光中微颤
- 图生视频 Prompt：抬手按联，纸张轻颤后服帖
- 5 秒动态：0-1s 持联抬手；1-3s 按上门框；3-4s 纸张轻颤；4-5s 联粘稳
- 声音：纸张摩擦声 + 晨风
- 环境动态：纸张轻颤、晨风
- 连续性锚点：对联位置 / 门框
- 负面词：文字乱码，联歪，现代物品

**镜头 05｜压平纸张**（4s·特写·固定）
- 图片 Prompt：手掌从联上端抚到下端，红纸金墨在晨光中发亮
- 图生视频 Prompt：手掌下抚，纸张逐段服帖
- 5 秒动态：0-1s 手按联顶；1-3s 缓抚而下；3-4s 纸面服帖；4-5s 手离联稳
- 声音：纸面摩擦声
- 环境动态：纸面微光
- 连续性锚点：手 / 联 / 门框
- 负面词：手部穿模，联皱，低质量

**镜头 06｜家人观看**（4s·中景·固定）
- 图片 Prompt：祖孙退后几步看新联，孩童仰头咧嘴笑，门内家人探头
- 图生视频 Prompt：退后、仰头、笑意漾开
- 5 秒动态：0-1s 站定；1-3s 仰头看联；3-4s 笑意漾开；4-5s 定格
- 声音：笑声 + 零落鞭炮
- 环境动态：衣摆、晨光
- 连续性锚点：人物 / 新联
- 负面词：五官错位，低质量

**镜头 07｜红灯笼+春联收束**（5s·全景·慢拉远）
- 图片 Prompt：门楣红灯笼与两侧新联同框，晨光镀边，小院全景收束
- 图生视频 Prompt：镜头缓拉，灯笼轻晃，联纸轻扬，炊烟升起
- 5 秒动态：0-1s 门框稳定；1-3s 镜头缓拉；3-4s 灯笼轻晃、联纸轻扬；4-5s 全景定格
- 声音：鞭炮渐远 + 民乐收束
- 环境动态：灯笼晃、联扬、炊烟
- 连续性锚点：灯笼 / 新联 / 院落
- 负面词：文字乱码，现代穿帮，低质量

**5 秒生成限制（工业模板·第七阶段·所有 CASE ③5 秒动态版统一遵守）**：

- 主动作只能 1 个
- 运镜只能 1 个
- 人物不能突然位移
- 道具不能突然消失
- 衣服不能换
- 光源不能跳
- 背景不能瞬间改变
- 结尾必须有动作落点

> 跑 Seedance / 海螺 H3 / 可灵等视频模型前逐条核对；③5 秒动态版 + 本限制 = 可直接投喂的工业级短镜。

### CASE 21-22：H3 整条视频实战范本（V5.11 入库·仙宫巨物观实测·不是教程是你自己跑出来的）

> CASE11-20 的④多镜头表是"规划版"；这两条是你实际用 H3 跑出来并发布的成片分镜（2026-09-04 创作包 v2·首帧生视频无尾帧·运镜统一「锁构图推」：very slight push-in, camera advances only a little, keep the full frame composition visible, no cropping）。用途：做仙侠/巨物/宫阙题材时，照抄结构换首帧即可。每镜 4-5s，5 镜共 21s。

**CASE21｜云上初行（天空系·钩子→铺陈→情绪→定格→收尾）**

- 一句话卖点：她踩上金瓦的那一刻，云海在她脚下翻涌——这是她第一次离天这么近。
- 分镜：①云上少女俯瞰仙宫 4s（钩子：她是谁）②宫阙间彩带翩飞 4s（铺陈：往更深处去）③月下云海楼阁凌空 4s（情绪：路过月宫）④晨光持剑立殿脊 4s（定格：剑与晨光）⑤纸鹤载琴横渡宫群 5s（收尾：往云深处去）
- 故事正文：云海托起重重金顶，她踩上最高的屋脊，像踩上整座天的门槛。风把她吹向更深的宫阙，彩带在身后拉成一道虹。她路过月下的楼阁，路过晨光里的剑，最后乘着一只纸叠的白鹤，抱着琴，往云最深的地方去。她不知道自己在找什么，只知道这座仙宫，在等她。

```
The woman stands on the colossal golden palace ridge, her robes and long hair streaming in the high wind, clouds and mist rolling far below her tiny figure, morning glow gilding the endless golden roofs, she slowly lifts her face to the distant palace sea, very slight push-in, camera advances only a little, keep the full frame composition visible, no cropping, ethereal and serene mood.
A flying-apsara maiden hovers above the colossal palace complex, rainbow silk ribbons trailing and undulating behind her, the vast golden-and-jade roofs far below her tiny figure, warm daylight, drifting clouds sliding past, static camera, no camera movement, light and free mood.
The fairy levitates between colossal hanging pavilions above a sea of clouds, her translucent sleeves and hair drifting, giant lanterns glowing around her tiny figure, full moon night, silver and warm gold light, mist curling, subtle breathing camera movement, a barely perceptible slow forward drift, nearly still, dreamy and mysterious mood.
A sword-holding maiden stands on the colossal golden palace ridge, wind lifting her robes and long hair, the vast tiled roof curving away beneath her, clear morning light glowing on the tiles, clouds far below, she turns slightly to gaze across the rooftops, very slight push-in, camera advances only a little, keep the full frame composition visible, no cropping, majestic and quiet mood.
A fairy playing guqin rides a giant folded paper crane gliding between colossal palace halls, her flowing robes trailing in the wind, warm golden dusk light, dust motes and mist drifting, the towering halls dwarfing the tiny crane, very slight push-in, camera advances only a little, keep the full frame composition visible, no cropping, melancholy and dreamy mood.
```

**CASE22｜金殿问琴（室内巨殿系·钩子→过渡→压迫→燃点→收尾）**

- 一句话卖点：金殿、长廊、穹顶、丹炉、书阁——她在一座宫里，找自己的位置。
- 分镜：①金殿抚琴 4s（钩子：琴声绕殿三圈）②烛光长廊提灯 4s（过渡：灯影明灭）③穹顶大殿仰望 4s（压迫：云凤压顶）④丹房添炉 4s（燃点：火光照脸）⑤藏书阁捧书 5s（收尾：书比人高）
- 故事正文：她跪坐在金殿中央抚琴，琴声在大到能吞下整座城的大殿里绕了三圈才落地。她提着灯走过烛光长廊，灯影在巨柱间明明灭灭。她仰头看穹顶，云和凤凰画在天上，压得她喘不过气。她走到丹房，往巨炉里添了一根柴，火光"腾"地照亮她。最后她坐在藏书阁里，捧着一卷旧书，书页比她还高——她忽然觉得，自己好像就是这宫里等了很多年的那个位置。

```
Interior of a colossal golden palace hall, a young woman in pale hanfu sits on the floor playing a guqin, enormous golden carved pillars and a giant bronze bell hanging high, sheer silk curtains swaying, warm golden light streaming from tall lattice windows, her tiny figure in the vast hall, she slowly closes her eyes as her fingers pluck the strings, very slight push-in, camera advances only a little, keep the full frame composition visible, no cropping, solemn and echoing mood.
A young woman in pale hanfu walks along a colossal interior corridor holding a glowing paper lantern, towering red columns on both sides reaching into shadow, warm candlelight and lanterns along the walls, soft haze, her tiny figure between the giant pillars, the paper lantern swaying gently as she walks, very slight push-in, camera advances only a little, keep the full frame composition visible, no cropping, mysterious and quiet mood.
A young woman in pale hanfu stands in the center of a colossal throne hall looking up at a gigantic vaulted ceiling painted with clouds and phoenixes, beams of light falling from high windows, immense empty space dwarfing her, she slowly tilts her head back, light moving across her face, very slight push-in, camera advances only a little, keep the full frame composition visible, no cropping, awe-struck and solemn mood.
A young woman in pale hanfu stands before a colossal bronze alchemy furnace taller than a house, feeding wood into the glowing furnace, warm ember glow mixed with cool daylight, the fire surges and crackles as she adds wood, sparks drifting upward, her tiny figure beside the enormous vessel, static camera, no camera movement, warm and alive mood.
A young woman in pale hanfu sits among colossal library shelves towering to the ceiling, holding a scroll, thousands of books stretching up, dust motes in the light beams, she turns a page, dust motes drifting in the golden light, very slight push-in, camera advances only a little, keep the full frame composition visible, no cropping, scholarly and still mood.
```

> 33 个场景全量「故事+分镜表+H3 提示词」见归档「AI技能-归档\01-仙宫巨物观-实战提示词库」；170 张图片提示词同处。

### CASE23：飞天琵琶·仰拍巨物（图片提示词范本·V5.12 入库·用户实测图）

> 来源：用户实测 GPT Image-2 出图双语卡（3168×1440）。学习价值：①仰拍巨物对比构图（人物底 1/3 + 巨物上 2/3，压迫感来源在上方）②五矿物宝石色配方 ③琉璃折射光影 + 丁达尔暖光。图片工具直接照抄，可换人物/压迫源复用为系列母版。

- 一句话卖点：琉璃漩涡从天上倒下来，她抱着琵琶坐在最底下——天有多大，她就有多小。
- 可复用公式：极低角度广角 + 人物底部居中 1/3 + 上方 2/3 琉璃巨涡（压迫源）+ 两侧鎏金仙阙（次级框架）+ 云海托底 + 五矿物色 + 丁达尔光 + 概念原画风

```
**极低角度广角镜头：**唐代飞天琵琶仙女盘腿坐于光洁白玉台，人物位于画面底部居中，占据画幅下方1/3区域。画幅上方2/3处：巨大的弧形琉璃晶体漩涡自上空奔涌垂落，半通透的琉璃流光翻涌交织着琥珀金、孔雀石绿、朱砂红、青金石蓝、莲荷紫；道道棱面折射出棱柱光束。画面两侧：层叠错落的鎏金中式浮空仙阙，深色木构斗拱，宝蓝色琉璃飞檐隐入琉璃薄雾深处。下方是镜面般平滑的云海，隐约可见仙鹤剪影。仙女身着朱砂红短款上襦，极阔幅孔雀石绿薄纱广袖，通透披帛飘带，洒金织锦面料；唐代流云高髻，白莲花丝头冠，垂挂珍珠流苏。怀抱紫檀木琵琶，玉制琴轸，琴身雕刻云纹。温暖的丁达尔光束，斑斓虹弧，漫天漂浮金尘。柔和手绘概念原画风格，低饱和度古宝石色调，带有矿物颜料颗粒质感，无卡通渲染效果。

Extreme low angle wide shot: Tang celestial pipa fairy sits cross legged on a polished white jade platform, bottom center, lower 1/3 of frame. Upper 2/3: massive swirling arched vortex of faceted liuli crystal cascading from above, semi translucent colored glaze churning with amber gold, malachite green, cinnabar red, lapis blue, lotus purple; prismatic light refracts along every current. Both sides: stacked gilded Chinese floating palaces, dark wood dougong brackets, blue glazed flying eaves receding into crystal mist. Below: mirror smooth white cloud sea, faint cranes. Fairy wears cinnabar red cropped top, ultra wide malachite green gossamer sleeves, translucent pibo ribbons, gold fleck silk; Tang flying cloud bun, white lotus filigree crown, pearl tassels. Holds dark zitan pipa with jade pegs, carved cloud patterns. Warm Tyndall beams, rainbow arcs, drifting gold dust. Soft painterly concept art, muted antique jewel palette, mineral pigment grain, zero cartoon.
```

- 学习拆解：
  ① 构图：人物底 1/3 居中 → 上 2/3 弧形琉璃漩涡（压迫源）→ 两侧鎏金仙阙（次级框架收边）→ 云海仙鹤收底，四层纵深一次写全
  ② 色彩：琥珀金+孔雀石绿+朱砂红+青金石蓝+莲荷紫 = 五矿物宝石色配方；配「低饱和古宝石色调 + 矿物颜料颗粒质感」防艳俗
  ③ 光影：暖丁达尔光束 + 彩虹虹弧 + 金尘（氛围三件套）；琉璃棱面折射光增加层次
  ④ 人物七件套示例：流云高髻/白莲丝头冠/珍珠流苏 + 朱砂短襦/孔雀石绿广袖/披帛 + 紫檀琵琶（玉轸/云纹）——主体色与场景五色同源呼应
  ⑤ 风格防崩尾句：soft painterly concept art, muted antique jewel palette, mineral pigment grain, zero cartoon（概念原画感、低饱和、颗粒质感、禁卡通）

### CASE24：名篇整词文案工程（《望海潮》实测范本·V5.13 入库·参考片拆解）

> 来源：微信参考片《望海潮·东南形胜》44s 逐句词视频（AI 旁白逐句念 + 字幕逐句出 + 画面逐句配，23 句 23 镜）。学习价值：**文案不用自己写——一首成熟名篇 = 天然分镜脚本**，词句即分镜、节奏自带起伏。适用：城市/地方风物、节庆、巨物神佛等气象大、画面感强的题材。

- 一句话卖点：把整首词念完，片子就拍完了。

- 五步工程公式：
  ① 选词：整首名篇做骨架（要求：气象大、实词多、画面感强、知名度高——《望海潮》这类"城市宣传词"首选）
  ② 拆句：全词逐句列（按上/下阕），每句 = 一个镜头；句数 × 1.5–2s = 成片时长（23 句 ≈ 44s）
  ③ 配画：每句词意匹配一个画面——实词直配（烟柳画桥→石拱桥、市列珠玑→商铺）、虚词/总起用大景（三吴都会→城楼远眺）、收束句用定格
  ④ 节奏：长短句交错念白（4 字短句 ↔ 8 字长句），约 1.8s/句；旁白 + 字幕逐句同步（字幕后期叠加，不进生成画面）
  ⑤ 收口：末句天然收束（异日图将好景，归去凤池夸→定格余韵），无需另写结尾

- 词句→镜头匹配规则表：

| 词句类型 | 处理 | 例（《望海潮》） |
|---|---|---|
| 总起句（地名/格局） | 大景别定场 | 东南形胜 → 城楼远眺 |
| 实词景句 | 词意直配 | 烟柳画桥 → 船过石拱桥 |
| 动态句 | 配运动/险镜头 | 怒涛卷霜雪 → 江浪行舟 |
| 市井/富庶句 | 配群像街景 | 市列珠玑 → 市集商铺 |
| 人物/生活句 | 配人物近中景 | 嬉嬉钓叟莲娃 → 岸边人物 |
| 收束句 | 定格/慢收 | 归去凤池夸 → 画面定格 |

- 题材适配：城市/地方风物 →《望海潮》《扬州慢》；巨物神佛 →《八声甘州》《水调歌头》等气象词；节庆 →《青玉案·元夕》。选词标准：**宁选画面实、节奏匀的，不选用典深、意象虚的**（每句都要能配出一个具体画面）。

### CASE25：名篇整词文案工程·实战范本（《桂影三秋》·V5.14 入库·完整编排表）

> 触发：用户说"按宋词写文案""像《望海潮》那样做""词句配画面"，直接调出本范本 + CASE24 五步公式套用。本范本 = 自创词 26 句 + 16 镜时间轴 + 3 补拍 + 剔除/色彩规则，是 CASE24 的完整落地样例。
> 项目背景：秋日古风 × 三女主（林溪·慵懒淡静 / 苏棠·灵犀俏皮 / 陈穗·温柔贤淑），94 镜素材选 20 镜成片 ≈ 50s，画面流程=晨起梳妆→庭院赏桂→湖上采藕→烹茶品糕→暮色归影。

- **文案《桂影三秋》（26 句 / 约 50s，逐句念+逐句字幕）**：
  ① 风叩回廊，桂子初黄 ② 一庭秋色，半袖天光 ③ 池映倒影，楼收斜阳 ④ 倚窗闲坐，看落花逐水 ⑤ 眉间一点秋，浅眠待月归 ⑥ 攀枝折桂，掷入琉璃盏 ⑦ 笑问今宵月，可赊三分醉 ⑧ 枯荷泛舟，素手拨清波 ⑨ 拾得桂子香，藏入罗袖中 ⑩ 远山叠翠，暮云收晚色 ⑪ 波光接天，金屑落满襟 ⑫ 桂影三秋，人间清欢处 ⑬ 折一枝秋，寄与月边人
  （结构：秋色起 6 句定场 → 三姝各 4 句出场 → 秋深 4 句开阖 → 收束 4 句余韵；四字句 ~2.2s / 五字句 ~2.8s，句间留 0.3s 呼吸）

- **16 镜时间轴（念白→镜头类型→用/补）**：
  风叩回廊→回廊倚门赏桂(用) / 桂子初黄→指尖触桂特写(用) / 一庭秋色→金黄树下三姝(用) / 半袖天光→室内光斑(用) / 池映倒影→舟中望湖(用) / 楼收斜阳→倚栏回望(用) / 倚窗闲坐落花→倚栏慵懒(用) / 眉间藏秋浅眠待月→静坐品茗(用) / 攀枝折桂掷入琉璃盏→**掷桂入盏动态特写(补)** / 笑问今宵赊三分醉→扬花瓣俏皮(用) / 枯荷泛舟拨清波→舟中戏水+拨水花连用(用) / 拾桂藏罗袖→**拢桂入袖特写(补)** / 远山叠翠暮云收晚→步道暮色(用) / 波光接天金屑满襟→廊下接光点(用) / 桂影三秋人间清欢→双人望景(用) / 折一枝秋寄月边→**折桂特写定格(补)**

- **补拍 3 镜规格（GPT Image 出图→图生视频）**：
  ① 苏棠·掷桂入盏：中近景，捏一枝金桂抛向案上琉璃盏，入盏瞬间慢动作定格，金桂散落；85mm/f2.0/ISO320/低机位略仰 15°/侧逆光
  ② 陈穗·拢桂入袖：手部特写→中景，指尖拢起散落桂花藏入罗袖，回眸浅笑；85mm/f1.8/柔光/平视
  ③ 折桂定格：特写，素手折一枝金桂，枝头带露，画面定住收尾；微距感/侧逆光

- **色彩与剔除规则（关键，防色断裂）**：全片定一个主色调（本片=暖黄金秋低饱和）；黑底/暗调/冷调镜、与主线无关或生得不好的镜直接剔除不硬凑；补拍镜必须同色调。人物补拍延续 WCF 一致性锚点句式「以参考图作为系列母版视觉参考，延续面容/发型/服装/色调，只改变动作」。

- **可复用性**：换题材时只换 ① 文案（按 CASE24 选词/自创）② 镜头池 ③ 补拍规格；时间轴结构、剔除规则、三姝多角色分配法（各角色对应音色念各自句）原样套用。

### CASE 声音系统规格（第十一阶段·每个 CASE 统一 8 项）

> 30s / 60s / 3min 成片级视频不只画面 Prompt。每个 CASE 声音 8 项，按表填：

| 项 | 内容 | CASE11 春节贴春联示例 |
|---|---|---|
| BGM 类型 | 主乐+情绪 | 古琴+竹笛轻快（民乐小品·欢庆） |
| 环境声 | 场景底噪 | 晨鸟+零星鞭炮+风 |
| 动作音效 | 关键动作拟音 | 浆糊黏稠声/纸张摩擦/脚步声 |
| 人声/旁白 | 对白或旁白 | 孩童"福到了！"+老者"新年大吉" |
| 字幕位置 | 文字卡放哪 | 左下；文字卡"总把新桃换旧符"（后期叠加） |
| 音乐进入点 | BGM 何时进 | 0s 全片轻进，镜06 起渐强 |
| 音效进入点 | 拟音何时进 | 镜03 蘸糊 1.5s 浆糊声；镜04 贴联 2s 纸擦声 |
| 镜头转场声音 | 镜间衔接声 | 镜01→02 鞭炮声过场；镜06→07 音乐渐强收束 |

> 视频模型直接生成声音时：BGM 情绪写进 prompt 尾部（十八·声音设计）；对白/音效/字幕后期精修。CASE11-20 按本表逐条补齐后即成片级。

> 七镜合计 31s。其他 CASE 按同一标准逐镜填：镜头序列 = 定场 → 准备 → 核心动作 → 收束 → 情感 → 全景收束。

### 七、素材组合速查表

实际制作时，不需要重新写一遍。可以直接这样抽取：

```
【人物】 P01 宋代闺阁少女
  ↓
【场景】 S03 古代茶室
  ↓
【道具】 D01 宋式茶盏 D02 粗陶茶壶 D03 茶筅
  ↓
【主动作】 A02 点茶
  ↓
【微动作】 A62 垂眸 A60 专注
  ↓
【道具互动】 I03 茶筅 I04 茶盏反光 I01 茶雾
  ↓
【光影】 清晨侧逆光 + 窗棂光影
  ↓
【构图】 前景茶盏虚化 + 中景人物 + 后景竹影
  ↓
【运镜】 固定 → 缓慢推进
```

最终就可以快速得到完整画面。

### 八、题材 × 人物 × 场景 × 道具 × 动作 × 光影搭配推荐表（V3.88 六维升级）

> 第六维度加入后：选题即一键搭配——题材锁 P/S/D/A/光影 五列，直接进 C06 全链路跑四联。动作列：库内编号优先，无编号为文字描述。

| 题材 | P 人物 | S 场景 | D 道具 | A 动作 | 光影 |
|---|---|---|---|---|---|
| 点茶 | P04/P27 | S03 | D01/D02/D03 | A02 点茶 | 晨间侧逆光+窗棂光影 |
| 晨妆 | P01/P02 | S01 | D06/D07/D08 | A09 梳发 | 窗外晨光斜束 |
| 婚嫁 | P05/P06 | S14/S15 | D22/D23/D24 | A51 庄重站立 | 晨间暖光+红绸高光 |
| 打谷 | P10 | S08 | D27/D28 | A15 捡拾谷物 | 秋日低角度侧逆光 |
| 采茶 | P04/P10 | S07 | D27 | 指尖采芽 | 晨间山谷柔光 |
| 香道 | P26 | S02 | D12/D14/D15 | A07 整理香灰 | 窗边斜射自然光 |
| 读书 | P01/P07 | S02 | D16/D17/D18 | A04 翻书 | 午后斜光+微尘 |
| 绣花 | P18 | S12 | D25/D26 | 持针穿布（I27） | 窗外阳光穿格栅窗 |
| 织布 | P19 | S13 | D45/D46 | 引梭打纬 | 窗边自然光 |
| 节日 | P28 | S26 | D20/D21 | A13 提灯 | 暖灯色+灯火散景 |
| 洗衣 | P03/P10 | S20 | D27/D29/D30 | A78 俯身拧布 | 晨光河面反射 |
| 药铺 | P16/P17 | S11 | D47/D48 | 称量药材 | 窗边柔和自然光 |
| 古代饮食 | P20 | S05 | D39/D40/D42/D43 | 木勺搅动 | 灶火暖光+蒸汽逆光 |
| 雪景 | P12/P30 | S22 | D32/D34 | A75 缓步 | 冷白晨光+轮廓光 |
| 祭祀 | P25/P29 | S27 | D12/D23 | A08 插香 | 晨雾+香烟克制光 |
| 赏花 | P01/P02 | S23 | D36/D37/D49 | A12 捧花 | 春日漫射光 |
| 夜游 | P28 | S25/S26 | D20/D21 | A13 提灯 | 灯火暖光+薄雾 |
| 山行 | P30 | S21 | D32/D34 | A75 缓步 | 树影斑驳光 |
| 河岸 | P03 | S20 | D29/D30 | A14 舀水 | 晨光水面金光 |
| 世家园林 | P02/P22 | S30 | D49/D10 | 缓步赏景（A76 停步） | 午后斜光+水光 |
| 七夕穿针 | P01 | S01/S26 | D25/D26 | 引线穿针（A62 垂眸） | 灯火暖光+月辉 |
| 春节贴春联 | P25/P13 | S06 | D17/D18 | A05 执笔写福 | 冬日暖阳+侧逆光 |
| 端午包粽 | P11 | S20 | D27/D43 | 卷叶捆扎 | 午后侧光+水汽 |
| 中秋拜月 | P25/P13 | S17 | D12/D39/D40 | A08 插香 | 月光+暖烛 |
| 元宵赏灯 | P28 | S26 | D21/D20 | A13 提灯 | 灯笼暖光+灯火散景 |
| 成人礼（及笄） | P01/P22 | S04 | D08/D24 | A09 梳发加笄 | 厅堂暖光+香炉烟直 |

### 九、素材库使用限制

1. **一张图不要塞太多主要道具**。推荐：1 个核心道具 + 1～2 个辅助道具。例如点茶：核心茶盏，辅助茶壶+茶筅。不要：茶壶+茶盏+茶筅+茶则+茶罐+香炉+花瓶+琴+书卷+屏风……否则画面主题会散。

2. **一个人物只保留一个主要动作**。推荐：主动作倒茶、微动作垂眸、环境动作竹影摇动。而不是：倒茶+转身+回头+翻书+扇扇子+抚摸花枝……

3. **道具必须与人物发生关系**。错误："人物坐在茶室里，旁边摆着茶壶。"正确："人物右手握住茶壶，缓慢向茶盏注入茶汤。"

4. **动态优先写"变化"，不要重复静态信息**。错误："茶壶为灰褐色粗陶茶壶，表面有手工纹理，茶壶放在木案上，茶壶很漂亮。"正确："开始时壶嘴保持静止，随后人物缓慢倾斜壶身，茶汤连续流入茶盏，茶面产生细小涟漪，最后茶壶重新回到原位。"

### 十、素材库最简调用公式

**图片**：人物 + 场景 + 核心道具 + 主动作 + 光影 + 构图 + 材质 + 负面词

**图生视频**：首帧人物与场景 + 主动作 + 微动作 + 道具动态 + 环境动态 + 镜头运动 + 结束状态 + 连续性约束

**最推荐的 5 秒动态结构**：
0～1 秒：人物和场景保持稳定
1～3 秒：主动作开始
3～4 秒：道具/衣袖/头发/环境产生辅助动态
4～5 秒：动作自然落点
避免：一个镜头同时发生多个大型动作。

### 十一、负面词补充

基础负面词继续沿用现有模板，不需要每次全部重复。

**针对人物**：人物身份混乱，年龄错误，现代发型，现代妆容，现代服装，五官错位，眼睛大小不一致，脸部变形，手指错误，六指，多手，肢体畸形，手与道具接触错误，人物比例异常。

**针对道具**：现代物品，现代餐具，塑料材质，机械复制感，道具形制错误，道具尺寸异常，道具悬浮，道具穿模，手部与道具脱离，多余道具，道具突然变化。

**针对场景**：现代建筑，现代灯具，现代家具，电线，玻璃幕墙，现代文字，广告牌，塑料制品，现代道路，现代汽车，时代错置元素。

**针对视频**：人物身份漂移，服装变化，发型变化，道具消失，道具变形，手部穿模，脸部漂移，背景突然变化，光线方向突然变化，镜头跳动，突然变焦，运动不连续，动作重复，动作突然停止，物理惯性错误。

### 十二、最终使用口诀

先定人，再定地，再定一个核心道具，再给一个主要动作，然后补一个微动作，最后让光、风、水、烟、布料中的一两个东西动起来。

人物负责故事，道具负责点题，场景负责时代，动作负责叙事，动态负责让画面活起来。

不要为了"丰富"而增加元素。一张好画面不是东西越多越好，而是：人物明确、场景明确、道具明确、动作明确、光影明确。其余全部为辅助。

---

## 附录·节日与题材排期指南（运营选题用）

> 按时间节点排期，提前 1-2 周准备素材。流量高峰期：春节、端午、中秋、七夕、元宵。

| 节日 | 时间（农历） | 推荐题材 | 发布时机 | 镜头数建议 |
|---|---|---|---|---|
| 春节 | 腊月廿三-正月十五 | 贴春联/年夜饭/守岁/拜年/元宵灯会 | 小年前后开始，除夕至初七密集发布 | 3-5 镜/条，可拆 5-8 条 |
| 元宵 | 正月十五 | 元宵灯会/走百病/猜灯谜/吃元宵 | 正月十三-十五 | 4-6 镜/条，1-2 条 |
| 清明 | 四月初（公历 4 月 4-6 日） | 踏青/祭祖/插柳/青团 | 清明前 2-3 天 | 3-4 镜/条，1 条 |
| 端午 | 五月初五 | 包粽子/赛龙舟/挂艾草/系五色丝线 | 端午前 3-5 天 | 4-5 镜/条，1-2 条 |
| 七夕 | 七月初七 | 乞巧/穿针/拜织女/鹊桥 | 七夕前 2-3 天 | 3-4 镜/条，1 条 |
| 中秋 | 八月十五 | 拜月/吃月饼/赏月/桂香 | 中秋前 3-5 天 | 4-5 镜/条，1-2 条 |
| 重阳 | 九月初九 | 登高/佩茱萸/赏菊/饮菊花酒 | 重阳前 2-3 天 | 3-4 镜/条，1 条 |
| 冬至 | 十一月廿二前后 | 祭祖/吃饺子/汤圆/数九 | 冬至当天或前 1 天 | 3-4 镜/条，1 条 |

运营技巧：

1. 节日前 7-10 天开始搜相关关键词热度，抓住"节前准备"的流量（如"端午粽子怎么包"＞"端午安康"）
2. 每个节日内容拆 2-3 条短视频：第 1 条"习俗科普"（有知识感）、第 2 条"氛围感镜头"（纯美感）、第 3 条"做冷门细节"（引发评论区讨论）

---

## V4.0 总验收表（第十二阶段·结构锁定）

> 里程碑验收：以下全部通过后，V4.0 结构锁定——以后只允许增加素材 / 增加 CASE / 更新平台参数，不再动底层编号架构。

**A. 编号**

| 库 | 状态 |
|---|---|
| P 人物库 P01-P30 | ✓ |
| D 道具库 D01-D50 | ✓ |
| S 场景库 S01-S30 | ✓ |
| A 动作库 A01-A15 / A51-A86 | ✓ |
| I 互动库 I01-I30 | ✓ |
| R 动态规则库 R01-R15 | ✓ |
| N 纠错规则库 | ✓ |
| C 调用规则库 C01-C07 | ✓ |
| CASE 成品库 CASE01-CASE20 | ✓ |

**B. 引用**

- [x] 无跨库编号（P/D/S/A/I/R 主归属三问锁定：是什么→P/D/S、做什么→A、怎么变化→I/R）
- [x] 无旧 B/C/D 动作编号残留（B16-B25→A62-A71、C26-C40→A72-A86、D41-D50→A52-A61 已全部迁移）
- [x] 无失效编号（全库引用逐条指向存在条目）
- [x] 无重复编号（八库条目完整性校验通过）

**C. CASE**

- [x] CASE01-20 齐全（01-10 三联：①图片版②图生视频版③5秒动态版；11-20 四联：+④多镜头分镜版）
- [x] 图片版：① 十字段（人物/场景/道具/主动作/互动/光影/构图/材质/负面词/完整 Prompt）
- [x] 图生视频版：② 八字段（首帧/主动作/微动作/道具动态/环境动态/镜头/结束/连续性）
- [x] 5秒版：③ 四时段（0-1s 稳定/1-3s 主动作/3-4s 辅助动态/4-5s 落点）+运镜+禁止
- [x] 多镜头版：④ 镜号/时长/景别/运镜/画面/对白/声音（CASE11 另有 7 镜 10 字段工程版）
- [x] 连续性：C05 14 项检查表 + 每镜「连续性锚点」字段

**D. Prompt**

- [x] 人物锁定（锚点段原样复制，只改动作/神态/运镜）
- [x] 场景锁定
- [x] 道具锁定
- [x] 动作明确（主动作 1 个）
- [x] 光影明确
- [x] 构图明确
- [x] 运镜唯一（5 秒生成限制 8 条）
- [x] 负面词齐全（N 库 + 素材库负面词补充）

**E. 工程性**

- [x] 能直接复制（CASE 四联即成品）
- [x] 能直接换题材（六维搭配表 26 题材一键选）
- [x] 能直接换人物（P 卡 = 完整人物对象）
- [x] 能直接生成图片（图片 9 步 + P1-P5 + 首帧规则）
- [x] 能直接生成视频（图生视频版 + 5 秒限制 + C07 生产闭环）
- [x] 能直接扩展成多镜头（CASE 多镜头标准逐镜 10 字段）

**结构锁定宣言（V4.0 起）**

1. 编号架构永久冻结：P / D / S / A / I / R / N / C / CASE 编号体系不再改动
2. 只允许三类增量：①增加素材（P31+ / D51+ / S31+ / A87+ / I31+ / R16+）②增加 CASE（CASE21+）③更新平台实测参数
5. 生产层允许增加：PROJECT / SHOT / QC / REWORK / ERROR CODE（C-Fxx）/ VERSION / PRODUCTION LOG / PLATFORM TEST DATA——生产层编号独立于素材库编号，不影响 P/D/S/A/I/R/N/C/CASE
3. 新增素材沿用现有格式；新增 CASE 沿用四联 + 多镜头标准；平台参数必须带测试日期 + 模型版本
4. 历史版本归档冻结于 V3.89；V4.0 起版本记录只记三类增量

**版本路线确认**：V3.85 素材数据库终检 → V3.86 CASE11-20+多镜头 → V3.87 自动调用系统 → V3.88 平台参数+题材滚动 → V4.0 总验收+结构锁定。
实际落地：V3.85/86/87/88 按路线执行；连续性系统+5秒工业模板（路线 V3.87 项）、平台参数表+题材滚动库（路线 V3.88 项）并入 V3.89 一次完成；V4.0 总验收锁定。

---

## 生产管理系统（V5.2·合并 V4.1 生产执行层）

> V4.0 锁定的是「素材数据库 + 自动调用 + 四联 CASE」；V5.0+ 补上后半段生产管理层：**输入标准 → 自动决策 → 生成 → 检查 → 返工 → 交付 → 记录**。不改变 V4.0 编号架构，只加生产层。本版吸收 V4.1「生产执行层」：状态枚举、连续性错误码、返工四级、QC 三态、FINAL-QC、文件追溯。

> **指导思想（V5.7 入库·吸收 Cinema DNA 21×9×3 V2.0 理念·全文档生效）**：
> ① **判断优先于堆词**——这是一套「镜头判断系统」而非「关键词库」：出镜前先判断景别/视角/运动/光线该是什么，判断对了 prompt 自然成立；判断错了，堆再多风格词也只是模板化。
> ② **反「电影感模板化」**——减少「电影感/大片感/史诗感」这类空词，升级镜头判断（景别选择、运镜逻辑、真实光线、纵深组织）。模板化 = 关键词同质化；电影感 = 判断系统正确。
> 落地方式：所有词库/素材（P/D/S/A/I/R）是「判断之后的填充物」，不是「堆砌的来源」；每个镜头先过 C01-C07 判断链路，再取词组装。

**生产总流程（V5.2）**：

选题 → PROJECT 任务单 → C01 拆题 → C02 选材 → C03 限量 → CASE 匹配 → C04 总装 → 镜头生产卡 → 图片 → IMAGE-QC → 首帧 QC → 图生视频 → VIDEO-QC → C05 连续性 QC（错误码）→ 多镜头 → 声音 → 剪辑 → FINAL-QC → PASS/REWORK → 发布 → 生产数据记录 → 反哺 CASE / 平台参数

**任务状态枚举（17 态·任务单"当前状态"字段取值）**：

```
DRAFT / PARSED / MATERIAL / PROMPT / IMAGE / IMAGE_QC / FIRSTFRAME / VIDEO / VIDEO_QC
CONTINUITY / EDIT / AUDIO / FINAL_QC / REWORK / PASS / PUBLISHED / ARCHIVED
```

### 一、生产任务单（PROJECT-xxxx）

> 每个视频 = 一个生产任务。以后不是"给我一个 Prompt"，而是开任务单。

**输入字段（立项必填）**：

| 字段 | 示例 |
|---|---|
| 项目名称 | 七夕穿针·三十秒竖版 |
| 选题 | 宋代女子七夕穿针乞巧 |
| 平台 | 抖音 / 小红书 / B站 |
| 视频比例 | 9:16 |
| 目标时长 | 30s |
| 目标镜头数 | 6 |
| 人物 | P01 |
| 风格 | V1 古风·庄重仪式 |
| 是否需要对白 | 是 |
| 是否需要旁白 | 否 |
| 是否需要 BGM | 是 |

**任务单模板（生成结果）**：

```
PROJECT-0001
状态：制作中
选题：宋代女子七夕穿针乞巧
平台：抖音 / 小红书 / B站
画幅：9:16
目标时长：30s
镜头：6
人物：P01
场景：S03
道具：D25/D26
动作：引线穿针（A62 垂眸）
互动：I27
动态：R01+烛火
CASE：CASE15
```

> 任务单锁定后进入生产流；任务单本身即项目档案编号。

### 二、镜头生产卡（生产工单）

> CASE 多镜头标准 10 字段 = 镜头工单的 Prompt 部分；再加镜头状态 10 格 = 生产进度。

**镜头状态（每镜一格进度）**：□ 待生成图片 □ 图片生成中 □ 图片通过 □ 首帧通过 □ 视频生成中 □ 视频通过 □ 连续性通过 □ 声音完成 □ 剪辑完成 □ 最终通过

**状态表示例**：

| 镜头 | 图片 | 首帧 | 视频 | 连续性 | 声音 | 成片 |
|---|---|---|---|---|---|---|
| 01 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 02 | ✅ | ❌ | — | — | — | — |
| 03 | ⏳ | — | — | — | — | — |

> ❌ = 返工中（见三）；— = 未开始。每镜一张生产卡 = Prompt 部分 + 状态格。

### 三、自动返工系统

> C05 检查失败时，不只说"不通过"，输出结构化返工单——错误 → 自动定位 → 自动返工。

**返工单格式**：

```
镜头 04 返工单
失败项目：❌ 发型 ❌ 道具位置
通过项目：✓ 人物 ✓ 服装 ✓ 场景 ✓ 光线 ✓ 动作
处理：保留原 Prompt + 保留原首帧 → 重新生成镜头 04 → 仅修正：① 发型 ② 道具位置
```

> 原则：只改失败项，不推翻通过项；保留原 Prompt/原首帧，避免返工引入新漂移。

**返工分级（四级）**：

```
一级：单个局部问题 → 局部修正 → 原素材锁不变
二级：2-4 项问题 → 复制原 Prompt → 仅替换失败字段（按 C-F 错误码定位）
三级：人物/场景/核心结构崩坏 → 当前镜头整张重做
四级：CASE 不适题 → 回到 C01/C02 重新拆题/选材
```

### 四、素材锁定机制（CHAR / OBJ / SET 锁）

> 古风连续视频防漂移的根手段：生成第一张图后把人物/道具/场景锁死，后续镜头引用锁，不重新描述。

**人物锁 CHAR-001**：

```
CHAR-001 = P01（年龄 / 身份 / 脸型 / 发型 / 妆容 / 服装 / 首饰 / 体型）
生成第一张图后：人物参考图 IMAGE-001
人物锁定：✓
后续所有镜头引用：CHAR-001 + IMAGE-001（不再重写人物段）
```

道具锁 OBJ-001、场景锁 SET-001 同理。多镜头 / 多视频连载时每个项目必须先锁再拍。

### 五、首帧验收系统（首帧 QC）

> 烂首帧 → 视频模型把它放大成烂视频。首帧生成后先过 QC。

**首帧 QC 14 项**：人物完整性 □ / 脸部完整性 □ / 手部完整性 □ / 服装完整性 □ / 道具完整性 □ / 构图 □ / 动作状态 □ / 光线 □ / 空间关系 □ / 视频运动潜力 □ / 底部字幕安全空间 □ / 运镜方向有空间 □ / 与前后镜头空间方向不冲突 □ / 备选中选最稳定帧 □

**评分分级**：90-100 直接进入视频；80-89 可进入视频；70-79 建议重做；<70 禁止进入视频。

> 首帧规则联动：头顶留白 ≥20% / 中全景 / 进行中动作 / 底部留虚化（〇章）+ 同场景 3 张备选，全部通过才取用。

### 六、视频 QC（6 组 26 项 + AI 专项速查·与图片 QC 分开）

> **V5.15 追加**：QC 通过后按「二十」20.8 镜头筛选分级 P0-P3 定级归档（P0/P1 一票否决 → P2 降级 B-roll → P3 标注修复）；失败版本带 FAILED_ 前缀保留，每镜维护 shot_notes.md。长项目按 20.8 工程文件夹结构归档。

**人物**：□ 不换脸 □ 不换年龄 □ 不换服装 □ 不改变体型
**身体**：□ 手部正常 □ 手指正常 □ 四肢不拉伸 □ 不穿模 □ 不瞬移
**道具**：□ 不凭空出现 □ 不突然消失 □ 位置连续 □ 尺寸稳定
**环境**：□ 背景不跳 □ 光源不跳 □ 时间不跳 □ 主色不跳
**运动**：□ 主动作清楚 □ 方向合理 □ 运镜稳定 □ 无突然加速 □ 结尾有落点
**画面**：□ 无明显闪烁 □ 无严重形变 □ 无文字水印 □ 无色块/模型噪声

**AI 视频专项 12 项**：

| # | 检查项 |
|---|---|
| 1 | 人物突然换脸 |
| 2 | 人物突然换衣服 |
| 3 | 道具消失 |
| 4 | 道具凭空出现 |
| 5 | 手指异常 |
| 6 | 肢体拉伸 |
| 7 | 背景跳变 |
| 8 | 光源跳变 |
| 9 | 镜头突然加速 |
| 10 | 镜头突然旋转 |
| 11 | 动作没有落点 |
| 12 | 首尾无法剪辑 |

> 5 秒模板（0-1s 稳定 → 1-3s 主动作 → 3-4s 辅助动态 → 4-5s 动作落点）= 视频 QC 的验收基准；任一项 FAIL → 按返工单处理（带 C-F 错误码）。

### 七、平台生产参数库（V5.0·原"待实测"表升级 23 列）

> 在原 16 列基础上加 7 列生产数据列。填满后系统可直接判断"这个 CASE 最适合在哪个平台生产"。

| 平台 | 模型版本 | 测试日期 | 推荐分辨率 | 推荐比例 | 单镜时长 | Prompt 长度 | 首帧要求 | 图生视频方式 | 运镜写法 | 负面词支持 | Seed/参考图 | 人物一致性方法 | 延长视频方法 | 容易翻车动作 | 最适合 CASE | 成功率 | 平均返工次数 | 平均生成次数 | 最佳镜头类型 | 最佳 Prompt 结构 | 成本 | 平均制作时间 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 豆包 2.5 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 |
| 可灵 1.6 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 |
| 海螺 H3 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 |
| 即梦 4.0 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 | 待实测 |

> 每格格式：值 +（2026-XX-XX·vX.X）。生产数据列由「八、成本/时间统计」持续回填。

### 八、成本 / 时间统计

> 生产管理的关键：每单记成本与耗时，长期积累出 CASE 均值，反哺排期与平台选择。

**单案例记录示例（CASE15）**：

```
图片：生成 3 张，通过 1 张，耗时 8 分钟
视频：生成 4 次，通过 2 次，耗时 15 分钟
声音：BGM 1 次，SFX 3 个
剪辑：20 分钟
总制作时间：43 分钟
```

**长期积累（CASE 均值表）**：

| CASE | 平均制作时间 | 成功率 | 备注 |
|---|---|---|---|
| CASE15 | 41min | 待积累 | 返工点多在手指与烛火 |
| CASE11 | 32min | 待积累 | 镜头数少，速度最快 |
| CASE13 | 47min | 待积累 | 特写多，返工率高 |

**生产数据记录（每个 PROJECT 完成后必记 11 字段）**：

```
总制作时间 / 图片生成与通过次数 / 视频生成与通过次数 / 返工次数 / 最易失败镜头
错误码 / 平台+模型版本 / CASE / C04 版本 / 最终成片版本 / 是否发布
```

**数据反哺规则**：同类项目累计 ≥5 条后，才允许调整推荐优先级——高成功率 CASE 提升推荐；平台成功率高则提高优先级；低返工 Prompt 标记稳定；高翻车动作标记风险。**单条成功案例不得直接修改底层规则。**

> 积累数据回填「七、平台生产参数库」的生产数据列，数据库开始产生真实生产数据。

### 九、版本控制（五级版本）

> 解决"这张图当时到底怎么生成出来的"——每级都带版本号，好结果可回查。

```
素材版本：P01 v1.2
Prompt 版本：C04 v1.5
CASE 版本：CASE15 v2.1
平台参数：可灵 Kling v1.6 / 2026-09-07
最终成片：PROJECT-0001 v3
```

> 记录规则：素材/规则改动 → 对应版本 +0.1；CASE 内容改动 → CASE 版本 +0.1；平台参数更新必须带测试日期；成片每次返工 v+1。一条成片 = 五级版本全记录，可精确复现。

**文件追溯目录（PROJECT 档案结构）**：

```
PROJECT-0001/
├─ 00_project/PROJECT-0001.md
├─ 01_image/S01_v01.png / S01_final.png
├─ 02_firstframe/S01_firstframe_v01.png
├─ 03_video/S01_v01.mp4 / S01_final.mp4
├─ 04_audio/bgm / sfx / voice
├─ 05_edit/PROJECT-0001_edit_v01
└─ 06_final/PROJECT-0001_FINAL_v01
```

### 十、成片验收表（FINAL-QC·6 组 34 项·PASS / FAIL）

**内容**：□ 题材正确 □ 时代正确 □ 习俗/行为正确 □ 叙事完整
**视觉**：□ 人物一致 □ 服装一致 □ 道具一致 □ 场景一致 □ 光影一致 □ 色调统一
**镜头**：□ 顺序合理 □ 景别合理 □ 运镜合理 □ 空间连续 □ 拼接自然
**动画**：□ 无明显 AI 变形 □ 无闪烁 □ 无穿模 □ 无道具消失 □ 每镜有落点
**声音**：□ BGM □ 环境声 □ SFX □ 旁白/对白 □ 音画同步 □ 音量稳定
**交付**：□ 9:16 / 16:9 □ 分辨率 □ 时长 □ 首尾完整 □ 文件命名 □ 封面 □ 标题 □ 标签

**结论**：PASS → 发布；FAIL → 自动进入返工（按三、返工单定位，带 C-F 错误码）。

> 每单生产结束必须回写「生产数据记录」：成本 / 成功率 / 返工率 → 反哺 CASE 与平台参数表，形成闭环。

#### Cinema DNA 验收评分制（V5.9 入库·量化版）

**5 组打分（满分 100，<82 不交付）**：

| 项目 | 分值 |
|---|---:|
| 剧情因果与不可打乱性 | 25 |
| 连续性圣经执行 | 20 |
| 构图、视线与观看立场 | 20 |
| 色彩和光源物理可信 | 15 |
| 真人实景与反 AI 质感 | 15 |
| 文件与拼版完整性 | 5 |

**一票否决（任一命中直接 FAIL）**：
- 模型在一张画布里直接生成多镜头拼图
- 缺少独立源图
- 多镜头只是同一构图、同一动作换角度
- 明显 CG / 游戏宣传图 / 商业广告
- 人物、关键道具或空间在关键因果镜头中无理由变形

---

## 双引擎生产系统（V5.3·GPT Image-2 定形 × MiniMax H3 定动）

> **最终定版原则：图片负责“定形”，视频负责“定动”。**
>
> 本章是 V4.2 的最高执行层。原有 P / D / S / A / I / R / N / C / CASE 编号体系全部保留，不推翻旧库；只重新定义它们在「图片→视频」生产链中的职责。
>
> **GPT Image-2 = 图片母版引擎**：负责人物、服装、场景、道具、构图、光影、动作起始状态与视觉风格。
>
> **MiniMax H3 = 视频动态引擎**：负责动作过程、微动作、环境动态、镜头运动、节奏与结束落点。
>
> **核心禁忌：不要让 H3 重新“设计人物”。先把人物画对，再让 H3 动起来。**

#### V4.2.1 双引擎职责边界

| 层级 | GPT Image-2 | MiniMax H3 |
|---|---|---|
| 人物长相 | ★★★★★ 必须锁定 | 禁止重新设计 |
| 发型妆容 | ★★★★★ 锁定 | 保持不变 |
| 服装 | ★★★★★ 锁定 | 只允许自然随动作变化 |
| 首饰 | ★★★★★ 锁定 | 不新增、不消失 |
| 场景 | ★★★★★ 锁定 | 背景保持稳定 |
| 道具 | ★★★★★ 锁定 | 按动作发生自然运动 |
| 动作起始姿态 | ★★★★★ | 接续并完成动作 |
| 主动作过程 | 可表现起始状态 | ★★★★★ 核心任务 |
| 微动作 | 可预设 | ★★★★★ |
| 环境动态 | 可定格 | ★★★★★ |
| 运镜 | 负责构图 | ★★★★★ |
| 光影 | ★★★★★ 定义主光源 | 保持光源连续 |
| 风格 | ★★★★★ | 不改变视觉风格 |
| 连续性 | 负责“母版一致” | 负责“运动一致” |

#### V4.2.2 完整生产总链路

**选题**
→ **PROJECT 任务单**
→ **C01 题材解析**
→ **P 人物**
→ **S 场景**
→ **D 道具**
→ **A 主动作**
→ **I 互动**
→ **R 动态规则**
→ **C04 图片 Prompt 总装**
→ **GPT Image-2 出图**
→ **IMAGE-QC**
→ **图片母版锁定**
→ **首帧裁切/选帧**
→ **H3 Video Prompt 总装**
→ **MiniMax H3 生视频**
→ **VIDEO-QC**
→ **C05 连续性 QC**
→ **PASS / REWORK**
→ **下一镜头首帧**
→ **多镜头拼接**
→ **声音**
→ **FINAL-QC**
→ **发布**
→ **数据记录**
→ **反哺 P/D/S/A/I/R/CASE**

#### V4.2.3 一镜一张“生产母版”

每一个镜头必须拥有唯一的：

- `SHOT_ID`
- `IMAGE_MASTER`
- `FIRST_FRAME`
- `VIDEO_MASTER`
- `CONTINUITY_ANCHOR`

推荐命名：

`项目_集数_镜号_人物_动作_版本`

例如：

`HUNLI_E01_S03_SongNv_TieHong_ V01`

同一镜头的图片、首帧、视频、返工版本不得混用。

---

### V4.2.4 GPT Image-2 图片 Prompt 标准

#### 图片 10 层正式结构

1. **人物 P**
   - 身份
   - 年龄
   - 面部
   - 妆发
   - 身材体态
   - 服装
   - 首饰
   - 气质

2. **场景 S**
   - 朝代
   - 建筑
   - 空间层次
   - 陈设
   - 时间
   - 环境

3. **道具 D**
   - 核心道具 1 个
   - 辅助道具 0–2 个
   - 材质
   - 位置
   - 使用状态

4. **主动作 A**
   - 只写 1 个主动作
   - 明确“动作进行到哪里”
   - 不写互相冲突的多个动作

5. **互动 I**
   - 手与道具
   - 人与人
   - 人与环境
   - 道具之间的关系

6. **光影**
   - 主光源 1 个
   - 光向
   - 光质
   - 明暗关系
   - 空气感

7. **构图**
   - 景别
   - 机位
   - 主体位置
   - 前中后景
   - 视觉重心
   - 留白

8. **材质**
   - 丝绸/木/陶瓷/青铜/玉/纸等
   - 表面质感
   - 湿润/干燥/磨损/新旧状态

9. **摄影与画面质量**
   - 电影化摄影
   - 景深
   - 焦段倾向
   - 真实透视
   - 细腻皮肤
   - 自然布料褶皱

10. **负面词 N**
   - 多余人物
   - 多余手指
   - 手部畸形
   - 脸部变形
   - 服装现代化
   - 道具重复
   - 道具漂浮
   - 文字水印
   - 塑料感
   - 过度锐化
   - 现代摄影棚痕迹
   - 不符合时代的建筑/器物

#### GPT Image-2 图片一行总装公式

`P人物 + S场景 + D道具 + A主动作起始状态 + I互动关系 + 光影 + 构图 + 材质 + 摄影质感 + N负面约束`

#### 图片母版硬规则

- **人物锚点段一旦通过 IMAGE-QC，后续镜头原则上原样继承。**
- 后续镜头只允许修改：动作、神态、机位、构图、局部环境变化。
- 不允许为了“换一个好看的脸”重新设计角色。
- 核心道具必须保持名称、材质、颜色、大小比例与相对位置逻辑。
- 同一场景的主光源不能无理由跳变。
- 首帧必须看起来像“即将开始动作”，而不是动作已经结束。

---

### V4.2.5 IMAGE-QC 图片验收

图片进入 H3 前，必须逐项检查：

| 编号 | 检查项 | PASS 标准 |
|---|---|---|
| IMG01 | 脸 | 五官完整、无明显变形 |
| IMG02 | 发型 | 发型与人物母版一致 |
| IMG03 | 妆容 | 妆面稳定、无异常纹理 |
| IMG04 | 服装 | 朝代正确、结构完整、无随机换装 |
| IMG05 | 身体 | 手指、手臂、身体比例正常 |
| IMG06 | 道具 | 核心道具唯一且清晰 |
| IMG07 | 场景 | 空间结构正确 |
| IMG08 | 光影 | 主光源明确、方向统一 |
| IMG09 | 构图 | 主体位置与镜头目的匹配 |
| IMG10 | 首帧可动性 | 人物/道具存在明确的下一步动作 |

**任一核心项 IMG01–IMG08 不通过：禁止进入 H3。**

#### 图片返工规则

- 脸崩 → 只重做人物段，不随意改场景。
- 服装崩 → 锁 P，重做服装描述。
- 道具崩 → 锁 P/S，重做 D/I。
- 构图不适合视频 → 锁 P/S/D，重做构图。
- 光影不一致 → 锁人物与场景，只重做光影。
- 首帧没有动作落点 → 只重做 A + 构图。

---

### V4.2.6 首帧锁定规则

**IMAGE MASTER ≠ FIRST FRAME ≠ VIDEO MASTER。**

三者职责：

- `IMAGE MASTER`：最高质量静态母版。
- `FIRST FRAME`：真正用于 H3 的起始画面。
- `VIDEO MASTER`：H3 输出的视频文件。

#### 首帧必须满足

1. 人物已经处于动作前/动作中的稳定状态。
2. 双手与核心道具关系清楚。
3. 身体重心合理。
4. 不要把动作做到终点。
5. 不要让衣袖、头发、道具处于无法解释的瞬间状态。
6. 构图为后续运动预留空间。
7. 人物脸尽量处于清晰可识别状态。
8. 背景不要存在会被误判为人物/道具的复杂元素。

---

### V4.2.7 MiniMax H3 视频 Prompt 标准

#### H3 八层结构

1. **首帧继承**
   - 明确“保持参考图中的人物、服装、发型、场景、道具”。

2. **主动作**
   - 只允许 1 个主动作。

3. **微动作**
   - 眼神
   - 呼吸
   - 手腕
   - 衣袖
   - 发丝
   - 身体重心

4. **道具动态**
   - 道具怎么移动
   - 移动方向
   - 与手的接触关系
   - 不突然消失/生成

5. **环境动态**
   - 烛火
   - 灯笼
   - 雾
   - 雨
   - 雪
   - 风
   - 水面
   - 纱帘
   - 植物

6. **镜头运动**
   - 一镜只选一个主要运镜：
     - 固定
     - 缓慢推进
     - 缓慢拉远
     - 横向移动
     - 轻微跟拍
     - 轻微环绕

7. **结束落点**
   - 动作完成
   - 动作停顿
   - 视线落点
   - 镜头停稳

8. **连续性约束**
   - 保持脸、发型、服装、道具、场景、光源、色调稳定。
   - 禁止突然换装、换脸、换场景、改变人物年龄。

#### H3 视频一行总装公式

`首帧继承 + 主动作1 + 微动作 + 道具动态 + 环境动态 + 运镜1 + 结束落点 + 连续性禁止`

#### H3 视频 Prompt 示例

**首帧继承：**
保持参考图中的宋代女子面容、发髻、青绿色襦裙、木桌、茶盏与宋式茶室不变。

**动作：**
女子缓慢抬起茶筅，手腕轻轻向内转动，连续击拂茶汤，动作自然、克制、符合真实手部运动。

**微动作：**
呼吸轻微起伏，眼神专注于茶盏，衣袖随着手腕运动产生自然褶皱，几缕发丝轻微晃动。

**道具：**
茶筅始终与右手保持真实接触，茶盏固定在桌面，不漂浮、不消失、不变形。

**环境：**
窗边柔和日光保持稳定，空气中有极轻微尘埃漂浮，背景竹帘仅有细微风动。

**镜头：**
镜头缓慢向前推进，推进幅度小而稳定，不改变人物构图关系。

**结束：**
女子完成一轮击拂后动作自然减慢，茶筅停留在茶盏上方，镜头平稳停住。

**连续性禁止：**
保持人物脸型、五官、发型、服装、首饰、茶具、桌面位置、场景结构和光源方向不变，不新增人物，不换装，不变脸，不让道具消失。

---

### V4.2.8 5 秒工业模板

#### 0–1 秒：稳定
- 人物保持首帧状态
- 微呼吸
- 极轻微眼神变化
- 环境开始自然运动

#### 1–3 秒：主动作
- 完成唯一主动作
- 动作速度稳定
- 手与道具保持接触

#### 3–4 秒：辅助动态
- 衣袖/发丝/环境产生轻微跟随
- 不增加第二主动作

#### 4–5 秒：落点
- 主动作减速
- 人物停稳
- 镜头停稳
- 为下一镜头提供剪辑落点

#### 5 秒硬限制

1. 主动作 = 1
2. 主要运镜 = 1
3. 人物不无理由位移
4. 道具不消失
5. 服装不变化
6. 光源不跳变
7. 背景结构不变化
8. 结尾必须有落点

---

### V4.2.9 VIDEO-QC 视频验收

| 编号 | 检查项 | PASS 标准 |
|---|---|---|
| VID01 | 脸 | 起止帧人物身份一致 |
| VID02 | 身体 | 无异常拉伸/肢体穿模 |
| VID03 | 手 | 手指与道具关系自然 |
| VID04 | 服装 | 不突然换装/消失 |
| VID05 | 道具 | 不凭空生成/消失/漂浮 |
| VID06 | 场景 | 背景不随机改变 |
| VID07 | 运镜 | 单一、平滑、无突然跳动 |
| VID08 | 结束 | 有明确动作或镜头落点 |

#### 视频返工优先级

**第一优先：脸/身体 → 第二优先：手/道具 → 第三优先：服装 → 第四优先：背景 → 第五优先：运镜。**

不要为了修运镜重新生成整个角色设计。

---

### V4.2.10 连续镜头锁定

连续镜头必须至少锁定：

`人物锚点 + 服装锚点 + 道具锚点 + 场景锚点 + 光源锚点 + 时间锚点 + 色调锚点`

#### 每个镜头必须填写

| 字段 | 内容 |
|---|---|
| Character Lock | 人物母版描述 |
| Costume Lock | 服装/首饰 |
| Prop Lock | 核心道具 |
| Scene Lock | 场景结构 |
| Light Lock | 主光源 |
| Color Lock | 主色 |
| Action Start | 本镜动作起点 |
| Action End | 本镜动作终点 |
| Next Shot Hook | 下一镜动作入口 |

**下一镜头必须从上一镜头的“Action End”继续，而不是重新随机开始。**

#### Cinema DNA 连续性圣经（V5.9 入库）

> 来源：Cinema DNA 21:9×3 3.0。比上表 7 锚点更完整的 10 字段版本；关键差异在「成像基底」与「禁止漂移」。每个镜头提示词都重复核心锚点，不依赖模型“记住上一张”。

- 时间与时代：
- 地点与空间骨架：
- 主角：年龄段、身份、发型、体态、服装主色、唯一识别物
- 配角：年龄段、身份、服装主色、与主角关系
- 关键道具：形状、材质、颜色、使用状态
- 固定环境：墙体、门窗、地面、设备、天气
- 综合色：主色 / 辅色 / 强调色
- 成像基底：35mm / 16mm / 早期数字 / 纪录式手持
- 光源法则：
- 禁止漂移：不得改变的人物、服装、道具和空间事实

**金句（务必记住）**：每个角色保留 4-6 个稳定锚点即可。不要用十几个装饰细节制造“连续性”——细节越多，漂移越严重。

---

### V4.2.11 一镜完整生产卡（最终版）

```text
【PROJECT】
项目：
集数：
镜头：
SHOT_ID：

【P 人物锁定】
人物：
年龄：
面部：
妆发：
服装：
首饰：
气质：

【S 场景锁定】
时代：
场景：
时间：
环境：

【D 道具锁定】
核心道具：
材质：
位置：
状态：

【A 主动作】
动作起点：
唯一主动作：
动作终点：

【I 互动】
人物—道具：
人物—环境：

【R 动态】
人物微动作：
道具动态：
环境动态：

【GPT IMAGE-2】
图片 Prompt：
图片负面词：

【IMAGE-QC】
IMG01：
IMG02：
IMG03：
IMG04：
IMG05：
IMG06：
IMG07：
IMG08：
IMG09：
IMG10：
结果：PASS / REWORK

【FIRST FRAME】
首帧文件：
首帧构图：
首帧动作状态：

【MINIMAX H3】
H3 Video Prompt：
H3 连续性禁止：

【VIDEO-QC】
VID01：
VID02：
VID03：
VID04：
VID05：
VID06：
VID07：
VID08：
结果：PASS / REWORK

【CONTINUITY】
脸：
发型：
服装：
首饰：
身体：
道具：
道具位置：
场景：
时间：
光源：
主色：
动作起点：
动作终点：

【下一镜头】
Next Shot Hook：
```

---

### V4.2.12 自动返工码

| 代码 | 问题 | 处理 |
|---|---|---|
| IMG-F01 | 脸崩 | 锁 P，重出图 |
| IMG-F02 | 发型崩 | 锁人物，重做妆发 |
| IMG-F03 | 服装崩 | 锁 P，重做服装 |
| IMG-F04 | 手部崩 | 重做动作/姿态 |
| IMG-F05 | 道具崩 | 重做 D/I |
| IMG-F06 | 场景崩 | 锁人物，重做 S |
| IMG-F07 | 光影崩 | 锁 P/S，重做光影 |
| IMG-F08 | 构图不适合视频 | 重做构图 |
| H3-F01 | 变脸 | 加强人物继承约束，重生成 |
| H3-F02 | 手崩 | 简化主动作 |
| H3-F03 | 道具消失 | 简化互动、明确接触关系 |
| H3-F04 | 换装 | 强化服装锁定 |
| H3-F05 | 背景变化 | 降低环境动态 |
| H3-F06 | 运镜乱 | 只保留一个运镜 |
| H3-F07 | 动作乱 | 只保留一个主动作 |
| H3-F08 | 结尾无落点 | 增加动作减速/停顿 |

---

### V4.2.13 最终 Prompt 分工口诀

> **GPT Image-2：画准。**
>
> **首帧：锁准。**
>
> **MiniMax H3：动准。**
>
> **IMAGE-QC：不对不进视频。**
>
> **VIDEO-QC：不稳不进成片。**
>
> **连续性 QC：前后不跳。**

#### 最终生产公式

**好图片 × 好首帧 × 简单明确的 H3 动作 × 严格连续性 = 稳定成片**

不要追求“一条 Prompt 什么都写”。

应该追求：

**图片把视觉资产锁死 → H3 只负责运动 → QC 把错误拦在下一阶段之前。**

---

### V4.2.14 CASE 最终四联结构

以后每个 CASE 统一输出：

#### ① GPT Image-2 图片版
- 人物
- 场景
- 道具
- 主动作起始状态
- 互动
- 光影
- 构图
- 材质
- 图片负面词
- 完整 IMAGE Prompt

#### ② MiniMax H3 图生视频版
- 首帧继承
- 主动作
- 微动作
- 道具动态
- 环境动态
- 镜头
- 结束
- 连续性禁止

#### ③ 5 秒工业版
- 0–1s 稳定
- 1–3s 主动作
- 3–4s 辅助动态
- 4–5s 落点
- 运镜
- 禁止项

#### ④ 多镜头完整分镜
每镜必须拥有：
- 镜号
- 时长
- 景别
- 运镜
- GPT Image-2 Prompt
- H3 Video Prompt
- 5 秒动态
- 声音
- 环境动态
- 连续性锚点
- 负面词

---

### V4.2.15 最终执行铁律

1. **先图片，后视频。**
2. **图片不过 QC，不进 H3。**
3. **一个镜头只设一个主动作。**
4. **一个镜头只设一个主要运镜。**
5. **人物锚点不随镜头乱改。**
6. **核心道具必须锁定。**
7. **H3 不负责重新设计人物。**
8. **连续镜头必须继承上一镜结束状态。**
9. **任何变脸、换装、道具消失、背景跳变直接 REWORK。**
10. **成片不是“生成出来的”，而是通过 QC 一镜一镜装配出来的。**

> **V4.2 最终架构：**
>
> `P/D/S/A/I/R`
> ↓
> `GPT Image-2`
> ↓
> `IMAGE MASTER`
> ↓
> `IMAGE-QC`
> ↓
> `FIRST FRAME LOCK`
> ↓
> `MiniMax H3`
> ↓
> `VIDEO-QC`
> ↓
> `C05 CONTINUITY`
> ↓
> `CASE MULTI-SHOT`
> ↓
> `SOUND`
> ↓
> `FINAL-QC`
> ↓
> `MASTER`

---

## 附录·历史版本归档（V1.0-V5.6）

> 以下为完整历史迭代记录，仅供追溯参考。日常使用无需阅读。顶部版本记录只留最近 5 条（V5.7-V5.11）。

| 版本 | 日期 | 改动 |
|---|---|---|
| V5.6 | 2026-09-07 | Flova 画质/场景实测入库二件：①新增「画质净化万能前置段」小节（图片 9 步示范后·不锁题材的通用画质控制段·中英对照整段可复制·治噪点/塑料感/细节堆砌，搜「画质净化」或「画面干净」可快速调出）②S29 天宫巨物场景追加同型实测范本（超广角俯瞰+悬浮仙岛神树仙城·22mm·Flova 2026-09-07） |
| V5.5 | 2026-09-07 | 东方生活美学配方中英对照补齐：①镜02-08 七段各补中文完整版（原仅英文），小节说明改「中英对照整段可复制」②小节末尾新增「衍生示范 4 条·中英对照」（荷塘采莲/夏日放鸢/庭院煮梅汤/雨后荷叶接珠·同模板新写可直接套用） |
| V5.4 | 2026-09-07 | Flova 1.0 实测入库三件：①3.5.20 节日分镜库新增「七夕·乞巧」8 镜分镜（穿针乞巧/为牛庆生/吃巧果/晒衣晒书/接露水/喜蛛应巧/溪边吃瓜/溪中捕鱼·镜01 原版中文成品 prompt）②二章新增「东方生活美学配方」小节（Oriental Lifestyle Aesthetics 五段式模板+镜02-08 完整英文成品提示词，MJ 参数 --ar 16:9 --stylize 200 --raw --v 8.2，整段可复制；含换题材公式）③十六章平台差异总表补 Flova 1.0 行（Nano Banana+Seedance 2.5，上传剧本自动拆镜出中英提示词） |
| V5.3 | 2026-09-07 | 合并 V4.2 双引擎生产系统（GPT Image-2 × MiniMax H3）：①双引擎职责边界表（图片定形/视频定动，H3 禁止重新设计人物）②一镜一张生产母版（SHOT_ID/IMAGE_MASTER/FIRST_FRAME/VIDEO_MASTER/CONTINUITY_ANCHOR+命名规范）③GPT Image-2 图片 Prompt 标准（10 层正式结构+一行总装公式+母版硬规则）④IMAGE-QC 编号表 IMG01-10（核心项不过禁止进 H3）+图片返工规则 6 条⑤首帧锁定规则（IMAGE MASTER≠FIRST FRAME≠VIDEO MASTER+首帧 8 条）⑥MiniMax H3 视频 Prompt 标准（八层结构+一行公式+点茶完整示例）⑦VIDEO-QC 编号表 VID01-08+视频返工优先级 5 级⑧连续镜头锁定（7 锚点+每镜 9 字段表+下镜继承上镜 Action End）⑨一镜完整生产卡最终版模板⑩自动返工码 IMG-F01~F08 / H3-F01~F08⑪Prompt 分工口诀（画准/锁准/动准）⑫CASE 最终四联引擎署名（①GPT 图片版②H3 视频版③5 秒工业版④多镜头分镜）⑬最终执行铁律 10 条+最终架构 |
| V5.2 | 2026-09-07 | 合并 V4.1 生产执行层：①任务状态枚举 17 态（DRAFT→ARCHIVED）②C05 连续性检查表加错误码列（C-F01 脸型~C-F14 动作终点）③自动返工升级四级分级（局部修正/替换失败字段/整镜重做/回 C01 重拆题）④首帧 QC 10 项→14 项（+底部字幕安全空间/运镜方向有空间/前后镜头空间方向不冲突/备选中选最稳定帧）⑤视频 QC 升级 6 组 26 项（人物/身体/道具/环境/运动/画面）+AI 专项速查保留⑥成片验收升级 FINAL-QC 6 组 34 项（内容/视觉/镜头/动画/声音/交付含文件命名）⑦生产数据记录 11 字段+数据反哺规则（≥5 条才调优先级，单条不改底层规则）⑧版本控制加文件追溯目录树（PROJECT-0001/ 00-06）⑨结构锁定宣言补生产层允许增加清单（PROJECT/SHOT/QC/ERROR CODE 等）⑩文档标题版本号修正（V3.43→V5.2） |
| V5.1 | 2026-09-07 | 生产系统完善三件：①版本记录压缩（顶部只留最近 5 条 V5.0-V3.87，V3.64-V3.87 全量移入文末归档，恢复「顶部只留 5 条」原则）②快速跳转索引补齐 8 行（C06/C07/5 秒限制/声音规格/平台实测参数/平台生产参数库/题材滚动库/生产管理系统）③〇章入口路由加「直接生产/收到 PROJECT 任务单 → V5.0 生产管理系统」 |
| V5.0 | 2026-09-07 | 生产管理系统十件套：①生产任务单 PROJECT-xxxx（11 输入字段→任务单模板）②镜头生产卡（多镜头 10 字段+镜头状态 10 格工单）③自动返工系统（失败项定位→仅修失败项→保留通过项与首帧）④素材锁定机制（CHAR-001 人物锁+IMAGE-001 参考图，后续镜头引用锁不重述）⑤首帧 QC 10 项+四档评分（<70 禁入视频）⑥视频 QC 18 项（基础 12+AI 专项 12：换脸/换衣/道具消失/穿模/无落点等）⑦平台生产参数库 23 列（原 16 列+成功率/返工次数/生成次数/最佳镜头/最佳结构/成本/制作时间）⑧成本/时间统计（CASE15 示例 43min+CASE 均值表反哺）⑨五级版本控制（素材/Prompt/CASE/平台参数/成片，可精确复现）⑩成片验收表 6 类 25 项 PASS→发布/FAIL→返工；生产总流程：选题→任务单→C01→素材→组装→CASE→镜头卡→图→图QC→首帧QC→视频→视频QC→连续性QC→多镜头→声音→剪辑→成片QC→发布/返工→数据记录→反哺 |
| V4.0 | 2026-09-07 | 第十二阶段·总验收+结构锁定：V4.0 总验收表五类全过（A 编号 P/D/S/A/I/R/N/C/CASE 全✓；B 引用无跨库/无旧编号/无失效/无重复✓；C CASE01-20 四联+连续性✓；D Prompt 八要素✓；E 工程性六项✓）；结构锁定宣言：编号架构永久冻结，只允许增加素材/增加 CASE/更新平台参数；版本路线确认（V3.85 终检→V3.86 案例库→V3.87 自动调用→V3.88 平台+题材→V4.0 总验收；连续性+5秒模板、平台参数+题材库并入 V3.89 完成） |
| V3.89 | 2026-09-07 | 六~十一阶段一次入库：⑥C05 升级 14 项连续性检查表（脸型/发型/妆容/衣服/首饰/身材/道具/道具位置/场景/时间/光源/主色/动作起点/动作终点，变即标红重生成）⑦5 秒生成限制工业模板（8 条：主动作1/运镜1/人物不位移/道具不消失/衣服不换/光源不跳/背景不变/结尾有落点）⑧平台实测参数对照表框架（豆包2.5/可灵1.6/海螺H3/即梦4.0×16 项，带日期+版本号防过时，待实测填写）⑨题材滚动扩充库四类 34 题材状态标注（节日/民俗/手工艺/日常，10 项待补）⑩C07 图片→首帧→图生→多镜头→拼接 8 步生产闭环 ⑪CASE 声音系统规格 8 项（BGM/环境声/音效/旁白/字幕/音乐进入点/音效进入点/转场声）+CASE11 示例 |
| V3.88 | 2026-09-07 | 第五阶段·素材组合推荐表六维升级：「题材×人物×场景×道具」扩为「题材×P×S×D×A×光影」，26 题材全填实（动作列库内编号优先/无编号文字描述；光影列一键取词），补元宵赏灯行；选题→一键搭配→直进 C06 全链路 |
| V3.87 | 2026-09-07 | 第三阶段·CASE 多镜头标准 + 第四阶段·自动调用链路：①新增「CASE 多镜头标准」章节（每镜 10 字段：时长/景别/运镜/图片 Prompt/图生视频 Prompt/5 秒动态/声音/环境动态/连续性锚点/负面词），CASE11 春节贴春联 7 镜/31s 工程版全填示范（定场→拿联→蘸糊→贴联→压平→观看→收束）②新增 C06 题材自动调用全链路（12 步程序逻辑：输入→时代→P/S/D/A/I/R→CASE 匹配→C03 限量→C04 总装→C05 检查→四联输出），含「宋代女子七夕穿针」全链路运行示例（命中 CASE15 直接可用）③索引加「整条视频级分镜」行 |
| V3.86 | 2026-09-07 | 第二阶段启动·CASE11-20 扩充（V4.0 第一优先级）：新增 10 个传统民俗 CASE（11 春节贴春联/12 元宵赏灯猜灯谜/13 端午包粽/14 中秋拜月/15 七夕穿针乞巧/16 成人礼笄礼/17 重阳登高敬老/18 清明踏青插柳/19 冬至家宴/20 上巳临水祓禊），每个统一四联格式（①图片版+十字段引用/②图生视频版/③5秒动态版/④多镜头完整分镜版含对白+BGM），直接拍 3-4 镜 15-20s；CASE11/13/14 与 3.5.20 节日分镜同源互证 |
| V3.85 | 2026-09-07 | 全库编号最终体检：八库条目完整性全过（P30/D50/S30/A51/I30/R15/C01-C05/CASE10 无缺失无重复）；正文引用存在性校验全过（全部指向对应库条目）；D47 药秤/D48 药材包防误认确认（无任何动作引用）；两处易混文本均为说明文字（V3.81 版本行修复描述、平台章「场景 A/B」代号）非引用；C04 标题级别统一 #### 与其他 C 标题对齐 |
| V3.84 | 2026-09-07 | CASE01-10 三联验收（第5刀）：CASE01 为示范版保持；CASE02-10 补全「① 图片版」（加①标题+人物/场景/道具/主动作/互动/光影/构图/材质/负面词/完整 Prompt 十字段，引用全部对应当前 P/S/D/A/I 编号）；②图生视频版③5秒动态版原已达标不动；另修复 V3.78 入库截断：CASE02-10 完整 Prompt 段结尾句补全 9 处（材质/色调收束句） |
| V3.83 | 2026-09-07 | B/C 编号污染清理：头部动作段 B16-B25 → A62-A71（垂眸 A62/抬眼 A63/回眸 A64/侧头 A65/短暂失神 A66/注视道具 A67/看向人物 A68/低头微笑 A69/皱眉 A70/闭眼闻香 A71）；身体动作段 C26-C40 → A72-A86（落座 A72…回头停留 A86）；连带改引用：CASE07 主动作 C29→A75 缓步、CASE09 主动作 C32→A78 俯身拧布、组合速查表微动作 B16→A62 垂眸；动作库 A 编号统一为 A01-A15/A51-A61/A62-A71/A72-A86 |
| V3.82 | 2026-09-07 | D 编号污染清理：动作库情绪段 D41-D50（含羞/紧张/欣喜/悲伤/思念/警觉/庄重/疲惫/专注/释然）整体迁移至 A52-A61（表情/状态归入 A，从 A52 往后接不重排）；道具库 D01-D50（D47 药秤/D48 药材包等）与 CASE/速查表正确引用全部保护不动 |
| V3.81 | 2026-09-07 | ①对照「A-H 降级操作指引」复核补 A3 人物写法原则（身份→…→神态 9 步锁定+身份感生活感+不增加 A01 素材编号声明，A3-A5 分库指引顺延 A4-A5）②清理旧编号残留（第一刀·定点修）：CASE10「主动作 D47 庄重站立」为残留（D=道具、D47 实为药秤）→ 动作库新增 A51｜庄重站立（不重排 A01-A50），CASE10 改引 A51；速查表药铺 D47/D48 保持正确不动 |
| V3.79 | 2026-09-07 | 数据库化架构改造（结构先行·不扩素材数量）：①A-H 八库降级为规则层（编号统一为 P/D/S/A/I/CASE，映射表+主归属三问）②G 动态变化库升级为 R 动态规则库 R01-R15 ③H 总装改为 C04，新增 C 自动调用规则库 C01 题材解析（8 字段）/C02 选材十步/C03 数量限制/C05 连续性检查，防乱写归入 N 纠错规则库 ④P01 升级完整人物卡示范（身份→年龄→…→默认动作 11 字段）⑤CASE01-10 全部统一三联格式（图片版/图生视频版/5 秒动态版）⑥题材映射表补 5 行（七夕穿针/春节贴春联/端午包粽/中秋拜月/成人礼） |
| V3.78 | 2026-09-07 | 新增「附录·古风习俗视频提示词素材库 V1.0」：P30 人物卡 + D50 道具卡 + S30 场景卡 + A50 动作卡（手/头/身/情绪）+ I30 道具互动 + CASE10 完整成品 Prompt（点茶/晨妆/婚嫁/打谷/香道/花灯/雪归/绣娘/洗衣/婚礼）+ 素材组合速查表 + 题材×人物×场景×道具搭配表 20 行 + 使用限制 4 条 + 最简调用公式（图片/图生视频/5 秒动态结构）+ 四类负面词补充 + 使用口诀；索引同步加跳转行 |
| V3.77 | 2026-09-07 | 新增「附录·直接调用素材库」A-H 八大库（索引同步加跳转行）：A 人物库（10 要素公式+差异化表 8 行）B 妆发服饰库（发型=身份+结构+装饰/服装七维拆解/服装状态必写）C 道具库（道具五要素+三示例/A手持 B桌面 C空间 D时代识别四类）D 场景库（场景六层结构+母库 20 个+四变体）E 动作库（动作三层+手/头/身/情绪词库）F 道具互动库（茶香书花灯×4 互动句）G 动态变化库（人/物/光/境/天五维）H Prompt 总装六段式（含宋式点茶完整成品例+图/图生/文生差异）+ Prompt 信息优先级 S/A/B/C 防乱写规则 |
| V3.76 | 2026-09-07 | 锦上添花两项：①十五.6 系列化末尾补节日排期引用（提前 1-2 周准备节日内容）②快速跳转索引加「运营选题排期→附录·节日与题材排期指南」行；编号体系（3.5.18 在〇章/3.5.19-20 在四章）按用户结论保持现状不动 |
| V3.75 | 2026-09-07 | 五修终版+V4.0 材料首批：①图片 9 步成品示范升级（九步加粗+替换指引）②锁 P 后怎么用指引③待拆计划优先级+理由（含 7-10 套节日案例计划与平台版本标注）④附录 V3.61 标点修复⑤时长→镜头数速查表增强版（结构列+用法）；新增 3.5.20 节日习俗成品分镜库（春节贴春联 3 镜/端午包粽子 4 镜/中秋拜月 4 镜，各含完整分镜表+成品 prompt 示例）；新增附录·节日与题材排期指南（8 节日排期表+运营技巧） |
| V3.74 | 2026-09-07 | 易用性五修：①图片 9 步精装结构补成品示范（纳采·P1 九步填满照抄改词）②图片风格决策树末尾加锁 P 后指引（复制整段→填第 1 步→续 8 步）③待定计划行改优先级编号+理由（P1 案例库/P2 平台实测含防过时标注/P3 题材滚动+可选扩展）④附录 V3.61 断句修复（分号逗号分隔）⑤新增时长×镜头数速查表（15s-3min+ 四档：镜头数/每镜时长/结构） |
| V3.73 | 2026-09-07 | 镜头级成品案例库批量续补 6 条（#04-09）：市井早市缓摇 / 婚嫁抬轿横移 / 侠女竹林跟拍后拉 / 巨物宫殿超低仰拍推近 / 雪夜读书推镜 / 秋日晒谷低机位固定——覆盖俗喜飒宏静安六种情绪 × 缓摇/横移/跟拉/仰推/推镜/固定六种运镜 |
| V3.72 | 2026-09-07 | 镜头级成品案例库启动（V4.0 优先级第 1 项）：新增 3.5.19 首批 3 条完整镜头卡（宋式点茶 V2/巨物天宫仙子 V1/高门千金闺房晨妆 V2），每条含景别+运镜+时长+完整 prompt+负面词，整镜直接抄；待定计划行写入三优先级排序 |
| V3.71 | 2026-09-07 | 图片区组织优化三项：①3.5.18 图片成品案例库整体迁移至〇章（紧挨图片 9 步精装结构+检查清单，图片相关内容集中，四章恢复纯人物造型）②P1-P5 英文速查表下加取词指引（场景/人物/光影英文词从各章节中英对照表抄，不整句直译）③首帧备选示例加焦距选择逻辑（远景 f/2.8 全清晰/近景 f/1.8 强虚化/中景 f/2.0） |
| V3.70 | 2026-09-07 | 首帧闭环四小补：①〇章加首帧完整闭环跨章节引用（构图规则在本节/选帧匹配在第十章·一件事两步）②P1-P5 英文关键词速查表（5 风格×英文关键词直接喂 MJ/Runway）③3.5.18 末尾加首帧备选示例·纳采（同一场景远景/中景/近景 3 张完整 prompt）④图片检查清单第 7 项拆两行（按工具选是否要英文版） |
| V3.69 | 2026-09-07 | 图片生成五大补齐：①图片 9 步精装结构（默认写法·对标视频 14 步，正式交付逐项输出）②图片风格决策树（3 问锁 P 值：用途/人物占比/氛围或细节）③图片生成前关键问题+首帧专用构图规则（当首帧用：人物下 1/3+头顶留白 20%+中全景+进行时动作+3 张备选）④图片生成前检查清单 8 项（对标视频版）⑤3.5.18 图片成品案例库（P1-P5 五条完整可复制案例：纳采/美人特写/孤舟寒江/雨夜街角/静物茶席） |
| V3.68 | 2026-09-07 | 版本记录归档最终形态（顶部只留 5 条）/ 对白配音选角完整版（6 角色×例句 + 混音三原则 + 4 工具） |
| V3.67 | 2026-09-07 | 版本记录重排 / 第8步「构图层次」与第3步分工明确 / 对白配音选角速查 |
| V3.66 | 2026-09-07 | 工程化七项：首帧工作流三原则 / 选片三步法 / 片头片尾+转场速查表 / 平台→比例→运镜映射表 / 第7步重定义「动态变化」 / 声音组合公式 / 非中英市场关键词直译规则 |
| V3.65 | 2026-09-07 | F表排版修复 / 动画↔实拍互转规则补全 |
| V3.64 | 2026-09-07 | 视频↔图片双向转换速查表 / 现代题材选题指南 / 30秒替换原则 |
| V1.0-V3.42 | 2026-09-07 | 历史迭代（已折叠）：〇入口判断/风格选单 V1-V6+P1-P5/36 风格全描述/电影质感/人物光影/斑驳光影/四感/治愈系/美人/真人/世家园林/宋式田园/宫廷巨物/庭院文事/双人互动/镜头锚点/机位角度/画面风格 A-F/X1-X4 结构卡/案例归档 70 条（详见各章节） |
| V3.43 | 2026-09-07 | 超全补齐：①道具词库按 7 类扩充（礼仪礼器/茶事/书画文房/妆奁闺阁/农事渔樵/市井百工/兵器江湖，点题+材质+光效互动）；②新增天气时令光效速查表 8 种（雪/雨/雾/月夜/黄昏/深夜/清晨/秋日）；③新增空白分镜脚本表模板；④新增 3 秒钩子公式+钩子对白 10 条；⑤音效词库 14→40 词（补更鼓/寺钟/摇橹/织机等古风拟音）；⑥十四章补其他题材字幕取用说明；⑦头部版本号同步 V3.43；⑧版头补 MiniMax H3 |
| V3.44 | 2026-09-07 | 自主补全轮：①四章新增古风妆发大全（发型 12 种/眉式 5 种/眼唇面妆/首饰，附用法公式与示例）；②十五新增通用古风金句库（结尾祝词 8 条/氛围文案 7 条/钩子句 5 条·跨题材）；③六章特写配方新增手部特写专项（公式+情绪 5 条，配合 100mm 微距锚点）；④索引补妆发/金句行 |
| V3.45 | 2026-09-07 | 〇章新增规则 5「四感默认」：宋/宋式/中式题材基调默认叠加柔和·唯美·细腻·电影化四感（除非用户指定其他质感）；四感词库同步标注默认开启 |
| V3.46 | 2026-09-07 | 〇章新增规则 6「默认 13 步详装」（精细镜头/图片卡/正式交付默认逐项输出，7 段总装降级为快速版）；七章 13 步详装标注默认写法；案例归档 70→71（夏日窗下点茶·13 步详装） |
| V3.47 | 2026-09-07 | 3.5.13 巨物美学新增「⑥ 巨物场景词库」（纯场景向：场景主体五类/尺度反衬/氛围/光效/构图公式+3 组合示例，出图出视频通用） |
| V3.48 | 2026-09-07 | 七章详装结构 13→14 步：第 2 步拆分，新增第 3 步「场景与元素」（人群/动物/植物/器物陈设逐一点名，含元素清单+填法示例）；〇章规则 6、案例 71 同步改 14 步 |
| V3.49 | 2026-09-07 | 四章新增「人物角色卡库」14 张：富家千金/世家公子/侠女/剑客/渔娘/采莲女/茶娘/琴师/舞姬/农妇/书生/仙翁/将军/绣娘，每张 = 完整 prompt 骨架（身份+妆发+动作+道具+神态+场景），人物必须"有事做、有道具、有神态"；索引补角色卡行 |
| V3.50 | 2026-09-07 | 四章新增「仙子与绝美女子角色卡」12 张（15-26：花神/月宫/洛神/飞天/织女/雪神/舞姬/仕女/花魁/狐妖/鬼新娘/飘渺仙——飘逸长裙不限于仙子）+ 飘逸长裙视觉词库（裙型/材质/披帛/动态/光效+组合公式）；索引补仙子行 |
| V3.51 | 2026-09-07 | 三章新增「3.2.1 材质大全」（织物/金属/玉石/木竹/陶瓷漆器/建筑场景六大类+组合公式）；道具词库 7 类扩词 + 新增乐器/饮食起居/宗教仙侠/坐骑 4 类；四章人物卡扩至 40 张（27-40：帝王/官员/公主/宫女/医女/画师/说书人/伶人/女冠/猎户/商贾/船娘/更夫/刺客）；索引补材质行 |
| V3.52 | 2026-09-07 | 四章新增「女子气质人设卡」12 张（41-52：清纯/活泼/娇憨/邻家/温婉/才女/清冷贵女/高冷御姐/风情御姐/飒爽女将/病弱美人/神秘女子），含甜盐冷飒媚怜谜速选表与「可盐可甜」两版写法；索引补气质行 |
| V3.53 | 2026-09-07 | 四章新增「面部特征词库」：脸型 6/眼型 9+眼特征/眼神 8/眉 9/鼻 4/唇 7/整体面容 7，附气质速配表（7 气质面部组合）与完整示例；索引补面部行 |
| V3.54 | 2026-09-07 | 四章新增「身材体态词库」：身形骨架 4 档/局部体态（肩颈腰曲线臂手腿足）/体态动作/气质速配 6 组/完整示例，一律雅词写法；索引补身材行 |
| V3.55 | 2026-09-07 | 四章新增「年龄锚点」：古风年龄词 8 档（垂髫→暮年）/英文锚点句 6 条/年龄×气质速配 6 组/完整示例，锚点放第 2 步主体最前锁气质；索引补年龄行 |
| V3.56 | 2026-09-07 | 「人物七件套」固化为标准：〇章新增规则 7、四章人物造型写作公式升级七件套（年龄+面部+妆发+身材+服装+动作道具神态+气质，含模板/示例/一行式）、14 步详装第 2 步改为七件套 |
| V3.57 | 2026-09-07 | 电影风格速查库 36→37：新增「邵氏电影」（棚拍硬光高对比/浓艳古装色/金碧布景/对称构图/粗颗粒锐利胶片），速查表+详细版同步 |
| V3.58 | 2026-09-07 | 案例归档按类型拆分四库：3.5.10a 巨物/天宫/奇观 26 条 / b 国风/美人/写真 5 条 / c 宋式/生活/田园 34 条 / d 庭院/宫廷/文事 6 条（严格按【类型】标签归类，68-71 属宋式归 c） |
| V3.59 | 2026-09-07 | 邵氏归位（导演签名表→平台潮流表，8→9 种，标注制片厂体系）；组合公式/完整描述标题 36→37 段同步；四章加七件套×14 步完整成品示范；现代美学词库补城市叙事 15 词（空间/材质/动态）；服装段加男装三段式简表；十八章加视频配乐三段式结构+30 秒婚嫁示例；天气时令光效速查表独立为二·五章 |
| V3.60 | 2026-09-07 | 六项补齐：①光源分级速查（月光/烛火/灯笼各 4 级·按情绪）②市井街巷词库 3.1.1（空间/人物/光影/声响 4 维）③夜间光影专章 2.6（灯笼三档/烛火四档/提灯四类/月相三态/星野）④春/夏/冬光效三句（四季闭环）⑤儿童 5 卡+老人 5 卡（角色卡 41-50，气质卡顺延为 51-62）⑥饮食道具速查表（糕点/汤羹/酒水/面食/果品/宴席） |
| V3.61 | 2026-09-07 | 人物深层刻画四件套：①人设锚点公式（出身/处境/欲望恐惧/关系人，写人先写根）②情绪→身体微动作映射表（7情绪×6维度，紧张别只会写手抖）③关系质感速查表（亲密/尊卑/疏离/对峙，心理距离5维度）④入画状态三选一（定格中/将要动/停顿片刻，动作第0层） |
| V3.62 | 2026-09-07 | 三要素联动体系：①配饰道具三层结构 4.1.2（A 随身配饰跟人走/B 手持道具跟动作/C 场景陈设跟环境·每层至少 1 项）②道具光效互动句替换库（8 道具×3 情绪写法）③场景·人物情绪匹配表 6 组+朝代场景风貌速查表（唐金碧/宋素雅/明清繁复）④三要素联动例句库（春闺倦读/雪夜归人·联动公式） |
| V3.63 | 2026-09-07 | 现代题材补"城市生活切片"：现代美学词库新增「城市氛围光效」10 词+「现代人物状态」10 词（深夜便利店/早八通勤立得住）；规则 5 加排除说明（现代国潮/赛博国风/暗黑国风不触发四感默认）；索引补儿童 41-45/老人 46-50 两行；原 V4.0 计划拆分落地 |

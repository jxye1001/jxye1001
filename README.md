<div align="center">

<!-- 标题 -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3000&pause=1000&color=2E2E2E&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B+I'm+Jiaxin+Ye;Large+Model+Algorithm+Engineer;LLM+Agent+%7C+MARL+%7C+Multimodal+Security" alt="Typing SVG" />

<br/>

📝 求职意向：大模型算法工程师 &nbsp;｜&nbsp; 🎓 中科大电子信息硕士 &nbsp;｜&nbsp; 📧 yejiaxin1020@163.com

</div>

---

## 🧭 About Me

- 🔭 **当前方向**：视觉语言模型安全、LLM 评估与检索推荐系统评估、多智能体强化学习（MARL）、LLM Agent 自进化框架
- 🌱 **研究兴趣**：大模型预训练 / SFT / DPO / PPO、参数高效微调（LoRA/QLoRA）、多模态对抗攻击、持续学习 / 小样本学习、RAG / 检索排序
- 💼 **实习经历**：拼多多（AI搜索评估框架研发）｜ 北方自动控制技术研究所（207所，MARL 泛化框架研发）
- 🏆 **荣誉**：国家级奖项 6 项 / 省级 15 项 / 校级 30+ 项；国家励志奖学金、一等奖学金
- 🌐 **语言**：英语 CET-6（流畅阅读英文文献） / 日语 N2

---

## 🛠 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/LLaMA-412951?style=flat-square&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/FinGPT-2E2E2E?style=flat-square" />
  <img src="https://img.shields.io/badge/LoRA%2FQLoRA-7C3AED?style=flat-square" />
  <img src="https://img.shields.io/badge/MAPPO-1F6FEB?style=flat-square" />
  <img src="https://img.shields.io/badge/SMAC-3B82F6?style=flat-square" />
  <img src="https://img.shields.io/badge/GGUF-181717?style=flat-square&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-42B883?style=flat-square&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

---

## 🚀 Highlighted Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🤖 Generic Agent — 记忆增强型自进化 LLM Agent 框架</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/LLM-Agent-blueviolet?style=flat-square" />
        <img src="https://img.shields.io/badge/Memory-分层机制-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/Tool--use-工具集-green?style=flat-square" />
      </p>
      <ul>
        <li>基于开源 <b>Generic Agent</b> 框架完成本地部署与二次开发，复现 Agent Loop / Tool-use / Memory / Skill-SOP 完整链路</li>
        <li>分析分层记忆设计（元规则 / 索引 / 全局事实 / Skill 归档），实现任务执行轨迹的<b>经验沉淀与技能复用</b></li>
        <li>原子工具集验证：文件读写、代码执行、网页抽取、浏览器操作，覆盖复杂任务链</li>
        <li>构建科研办公 Demo：GitHub 项目解析、论文整理、简历建议、Web 数据采集、脚本生成</li>
        <li>分析长任务失败模式（状态丢失 / 工具调用失败 / 重复规划），通过中间结果保存与步骤拆解提升稳定性</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">💰 FinLLM — 基于 LLaMA 的金融领域大模型微调与优化</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/LLaMA2%2F3-base?style=flat-square&logo=meta" />
        <img src="https://img.shields.io/badge/FinGPT-frame-9333EA?style=flat-square" />
        <img src="https://img.shields.io/badge/LoRA%2FQLoRA-PEFT-7C3AED?style=flat-square" />
        <img src="https://img.shields.io/badge/GGUF-轻量化-181717?style=flat-square" />
      </p>
      <ul>
        <li>基于 <b>FinGPT</b> 框架构建金融垂域大模型，统一 instruction 格式覆盖情感分析、问答、NER、关系抽取</li>
        <li>LLaMA2 + LoRA 复现 baseline，迁移至 <b>LLaMA3-8B</b> 底座完成金融领域多任务适配</li>
        <li>使用 <b>LoRA / QLoRA</b> 参数高效微调，低算力下完成多任务联合训练</li>
        <li><b>GGUF / 本地推理</b>轻量化部署，支持边缘设备与低资源环境下的金融推理应用</li>
      </ul>
    </td>
  </tr>
</table>

---

## 💼 Internship

### 🛒 拼多多 — OmniSrchX 商品检索 LLM 评估框架

> **配置驱动的 LLM 评估平台**，对电商检索推荐系统（AI搜 / 商详AI / AI卡）多维度质量（知识准确性/一致性、商品相关性、文本质量等）进行自动化评测与 GSB A/B 对比；采用 **Job→Runner→Task 三层调度 + 维度间并行** 架构，YAML 配置驱动流水线，支撑日均数百条样本的 LLM 批量评测。

<p align="center">
  <img src="https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/asyncio-4B8BBE?style=flat-square" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/Jinja2-B41717?style=flat-square" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/LLM--as--Judge-9333EA?style=flat-square" />
</p>

<details open>
<summary><b>⭐ 核心贡献：主导 knowledge_consistency 知识一致性维度从 0 到 1 的优化重构</b></summary>

- 🎯 **定位核心痛点**：商详AI 场景下文章中"锚点商品段"与分隔线以下"出卡推荐段"被混合校验、混合传入全部商品信息，导致大量误判
- 🧩 **分隔线识别算法**：新增 Markdown 分隔线识别算法（`_is_separator_line` + 段内二次切分），为每段打 `is_anchor_section` 标记，实现**段落级锚点过滤**
- 🧩 **场景分流校验策略**：商详AI 仅校验锚点段并跳过出卡段 LLM 调用（降低并发消耗），只传锚点商品避免出卡商品污染；AI搜/AI卡 保留原全量逻辑，通过默认标记实现**零侵入兼容**
- 🧩 **统一指标聚合口径**：将 `has_knowledge_error` 的 runner/job 聚合从 `mean`（算术平均，空样本致分母缩水）改为 `micro_ratio`（有错误 query 数 / 总 query 数），与三个比例指标口径统一，修正统计偏差
- 🧩 **异常样本鲁棒处理**：商品信息缺失静默跳过 LLM 校验；区分"无商品信息"（排除出聚合）与"无客观陈述"（计入"无错误"分母）两种空样本语义，避免样本量虚降
- 🧩 **Prompt 迭代提精度**：基于人评对照数据反复迭代 LLM-as-Judge 的 prompt，将机评与人评一致性显著提升
- 📦 **评测数据集建设**：构建 100 条商详AI 评测数据集（13+ 品类，含商品信息/参考答案），用于人评对照验证机评精确度

</details>

<details>
<summary><b>🏆 成果（经人评对照验证机评精确度）</b></summary>

| 判定类别 | 准确率 |
|---------|:------:|
| 正确判断 | **100%** |
| 错误判断 | **95.45%**（迭代 prompt 后进一步提升）|
| 不确定判断 | **92%** |

> 改动对配置 / prompts / 前端**零侵入**，AI搜 / AI卡 行为与改造前完全等价；显著提升商详AI 场景下知识一致性评估的准确性与鲁棒性。

</details>

<details>
<summary><b>框架级工程优化（性能 / 稳定性 / 数据）</b></summary>

- 🚀 **批量化进度写库**：原 runner 完成事件逐条同步写库，高并发下事件总线被 HTTP 往返阻塞 → 队列堆积反压 → 新 runner 入队延迟达 **10+ 分钟**。改为内存计数 + dirty 标记 + 后台定时批量 flush（多次更新合并 1 次写库），延迟收敛到 **2s**
- 🚀 **MySQL Proxy 三池架构**：隔离读写/批处理/查询池，优化 save_runner 写入路径，修复内存泄漏
- 🚀 **binlog 压力治理**：跳过未变化 job_config 写入 + 进度 flush 按 per-job interval 过滤，降低大表 binlog 压力
- 🛡️ **熔断器 / 分阶段超时 / 幂等upsert / 运行时动态配置**：面向长任务的容错与可恢复机制
- 🆕 **幻觉评估（hallu_evaluation）**：商品提取 + knowledge_check prompt 拆分方案，新增只读评估模式
- 🆕 **格式规则检查（format_rule_check）**：正则规则检查后处理产物格式错误，无需 LLM 调用、结果确定
- 📦 新增 query 变体机评数据集（DeepSeek / GLM-NVFP4 × NA/PN）

</details>

---

### 🎖 北方自动控制技术研究所（207所）— MARL 泛化框架研发

> 面向智能体在未见场景下"脆弱专才"问题，构建<b>分层决策 + CTDE</b> 的可迁移协同策略学习框架，实验平台为 SMAC。

- 🧠 **任务理解层（Task Encoder）**：融合静态任务信息（地图、兵种编制、规模、规则）与动态战场信息（血量、位置、可见性、技能冷却），学习统一任务级表征
- 🎯 **策略条件化**：生成高层战术意图 gₜ，作为条件输入注入 MAPPO，实现"策略—执行"解耦
- 🔁 **闭环反馈**：动作 → 状态更新 → 任务表征更新 → 策略调整，形成端到端可学习闭环
- 📈 **联合训练**：基于 CTDE 引入 centralized critic，价值函数反向传播更新 Task Encoder，学到对最终胜率敏感的任务表征

---

## 📚 Selected Publications

| # | Paper | Venue | Role |
|---|-------|-------|------|
| 1 | **ARG-Attack**: Asymmetric Relational-Geometry Driven Universal Adversarial Perturbations for Vision-Language Models | ACL 2026 | 一作 |
| 2 | **RADICL**: Real-world Adaptive Detection via Incremental Continual Learning — AIGC 图像检测小样本持续学习框架 | AAAI（在投） | 3/4 |
| 3 | *Learning to Research: Learning to Ranking the Similar Papers via BERT Fine-Tuning* | EI 会议 | 一作 |
| 4 | 《基于深度学习的两阶段目标检测算法综述》 | 国家一级科技期刊 | 一作 |

**ARG-Attack 关键指标**：在 Flickr30K / MSCOCO 上 SOTA 黑盒迁移性能；攻击训练效率 **30× 提升（4.15h vs 153h）**。

---

## 🎓 Education

| 时间 | 学校 | 专业 / 方向 | 备注 |
|------|------|------------|------|
| 2024 — 至今 | **中国科学技术大学** | 电子信息（信息处理中心实验室）| 硕士（推免）｜校一等奖学金 |
| 2019 — 2024 | **大连交通大学** | 软件工程 + 日语（双学位）| 工学学士 + 文学学士｜排名 **3/124（2.4%）**｜国家励志奖学金 |

---

## 🏆 Selected Honors & Competitions

> 国家级 **6 项** ｜ 省级 **15 项** ｜ 校级 **30+ 项**

<details>
<summary><b>国家级奖项（点击展开）</b></summary>

- 🥈 第五届全国大学生可再生能源优秀科技作品竞赛 — **国家级二等奖**（2 项）
- 🥉 第二届大学生低碳循环科技创新大赛 — **国家级三等奖**
- 🥉 第四届 TRIZ 杯大学生创新方法大赛 — **国家级三等奖**（2 项）
- 🥉 第十七届全国高校商业精英挑战赛会展创新创业实践竞赛总决赛 — **国家级三等奖**
- 🥉 第十八届"挑战杯"全国大学生课外学术科技作品竞赛（红色专项）— **国家级三等奖**

</details>

<details>
<summary><b>省级奖项（点击展开）</b></summary>

- 🥇 东北三省一区第三届大学生生态环保作品竞赛 — **省级一等奖**
- 🥈 辽宁省智慧农业电商创意与科研实践大赛 — **省级二等奖**
- 🥈 第十七届全国高校商业精英挑战赛会展创新创业实践竞赛 — **省级二等奖**
- 🥈 "欣旺达杯"辽宁省 iCAN 创新创业大赛 — **省级二等奖**
- 🥉 第十六届"挑战杯"辽宁省大学生课外学术科技作品竞赛 — **省级三等奖**
- 🥉 "建行杯"辽宁省第九届"互联网+"大学生创新创业大赛 — **省级三等奖**
- 🥉 2022-2023 学年辽宁省创新方法大赛 — **省级三等奖**
- 🥉 东北三省一区第三届大学生生态环保作品竞赛 — **省级三等奖**
- 🥉 "欣旺达杯"辽宁省 iCAN 创新创业大赛 — **省级三等奖**
- 🥉 辽宁省大学生智能技术应用大赛 — **省级三等奖**（2 项）
- 🏅 辽宁省 iCAN 创新创业大赛 — **省级优秀奖**

</details>

<details>
<summary><b>专利与产出</b></summary>

- 实用新型专利 1 项 / 外观专利 2 项（本科阶段产出）

</details>

---

<div align="center">

<sub><i>"Build agents that learn. Ship models that scale."</i></sub>

📧 **Email**: yejiaxin1020@163.com ｜ 🌐 **GitHub**: [@jxye1001](https://github.com/jxye1001)

</div>

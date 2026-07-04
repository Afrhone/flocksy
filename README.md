# PRD — Elliptical Hyperbolic Design Workflow & Nano‑Economy Cluster Graph  
# 产品需求文档 — 椭圆‑双曲设计工作流与纳米经济集群图谱

Version: 0.1  
Status: Draft / 草案  
Product codename: **Rubkodium Nano‑Economy Graph**  
Context: Oganesson Rubkodium math generator + Docker compute engine + visual cluster workflow

---

## 1. Executive summary / 执行摘要

### English

The Elliptical Hyperbolic Design Workflow is a generative design and compute system for turning sketches, symbolic gestures, color palettes, orbital rules, and cluster infrastructure states into interactive design surfaces. It combines two complementary geometries:

- **Elliptical mode**: convergence, refinement, orbit, memory, consensus, and stabilized identity.
- **Hyperbolic mode**: expansion, branching, contradiction, mutation, exploration, and high‑dimensional divergence.

The Nano‑Economy Cluster Graph adds a micro‑transactional and resource‑accounting layer on top of the design workflow. Every agent, compute job, shader state, dataset, container, contributor, artifact, and design decision becomes a node in a graph. Edges carry flows: value, compute, trust, energy, authorship, validation, memory, and exchange.

The product should allow users to create, simulate, inspect, and export a living graph where design evolution, compute resources, and economic micro‑flows are visible in one coherent interface.

### 中文

椭圆‑双曲设计工作流是一个生成式设计与计算系统，用于把手绘草图、符号手势、色彩调色板、轨道规则以及集群基础设施状态转换为可交互的设计曲面。系统结合两种互补几何：

- **椭圆模式**：收敛、精炼、轨道、记忆、共识、稳定身份。
- **双曲模式**：扩张、分支、矛盾、突变、探索、高维发散。

纳米经济集群图谱在设计工作流之上增加微交易与资源记账层。每个代理、计算任务、着色器状态、数据集、容器、贡献者、制品和设计决策都会成为图中的节点。边表示流动：价值、计算、信任、能量、作者身份、验证、记忆与交换。

产品应允许用户创建、模拟、检查并导出一个活的图谱，使设计演化、计算资源和经济微流在统一界面中可见。

---

## 2. Product vision / 产品愿景

### English

Build a design operating system where geometry becomes workflow, workflow becomes graph, graph becomes economy, and economy becomes a feedback field for new design states.

The system should feel like a **living control room**: part CAD, part shader lab, part graph database, part cluster dashboard, part speculative economy simulator.

### 中文

构建一个设计操作系统：几何成为工作流，工作流成为图谱，图谱成为经济系统，而经济系统又成为生成新设计状态的反馈场。

系统体验应像一个**活的控制室**：既是 CAD，又是着色器实验室，也是图数据库、集群仪表盘与未来经济模拟器。

---

## 3. Goals / 目标

### English

1. Provide a reusable design workflow based on elliptical and hyperbolic phases.
2. Convert sketches, palettes, mathematical fields, and compute states into graph structures.
3. Simulate nano‑economy flows across contributors, agents, compute services, and artifacts.
4. Integrate with Dockerized compute engines and WebGL/WebGPU visual generators.
5. Export graph state as JSON for downstream engines, dashboards, smart contracts, or archival systems.
6. Support bilingual documentation and interface labels in English and Chinese.

### 中文

1. 提供基于椭圆阶段与双曲阶段的可复用设计工作流。
2. 将草图、调色板、数学场与计算状态转换为图结构。
3. 在贡献者、代理、计算服务与制品之间模拟纳米经济流。
4. 集成 Docker 化计算引擎与 WebGL/WebGPU 视觉生成器。
5. 将图状态导出为 JSON，用于下游引擎、仪表盘、智能合约或归档系统。
6. 支持英文与中文双语文档和界面标签。

---

## 4. Non‑goals / 非目标

### English

- This product is not a financial trading platform.
- This product is not a token sale system.
- This product does not require public blockchain deployment in MVP.
- This product does not replace professional accounting or legal compliance tools.
- This product does not require photorealistic rendering in MVP.

### 中文

- 本产品不是金融交易平台。
- 本产品不是代币销售系统。
- MVP 阶段不要求部署到公共区块链。
- 本产品不替代专业会计或法律合规工具。
- MVP 阶段不要求照片级真实渲染。

---

## 5. Target users / 目标用户

### English

1. **Generative artist / designer**  
   Wants to transform sketches, color systems, and symbolic diagrams into procedural systems.

2. **Cluster operator / creative technologist**  
   Wants to bind containers, GPUs, agents, and compute jobs into a visible graph.

3. **Research collective / studio**  
   Wants to track authorship, contribution, usage, lineage, and value flow.

4. **Protocol designer**  
   Wants to model micro‑economies before implementing smart contracts or distributed ledgers.

### 中文

1. **生成艺术家 / 设计师**  
   希望把草图、色彩系统与符号图转换为程序化系统。

2. **集群运维者 / 创意技术师**  
   希望把容器、GPU、代理和计算任务绑定成可视图谱。

3. **研究团体 / 工作室**  
   希望追踪作者身份、贡献、使用、谱系和价值流。

4. **协议设计者**  
   希望在实现智能合约或分布式账本之前模拟微经济。

---

## 6. Core concepts / 核心概念

### English

| Concept | Description |
|---|---|
| Elliptical phase | Stabilizing loop: refine, compress, validate, remember. |
| Hyperbolic phase | Expansive branch: mutate, split, explore, contradict. |
| Nano‑economy | Micro‑scale accounting of value, compute, authorship, trust, and resource exchange. |
| Cluster graph | A graph of machines, services, containers, agents, artifacts, datasets, and flows. |
| Design state | A versioned snapshot containing geometry, palette, shader, graph, and economy state. |
| Gesture seed | A sketch, glyph, image, or symbolic input used to seed the graph. |
| Compute turn | One simulation step that updates geometry, graph weights, and economy balances. |

### 中文

| 概念 | 描述 |
|---|---|
| 椭圆阶段 | 稳定循环：精炼、压缩、验证、记忆。 |
| 双曲阶段 | 扩张分支：突变、分裂、探索、矛盾。 |
| 纳米经济 | 对价值、计算、作者身份、信任与资源交换的微尺度记账。 |
| 集群图谱 | 机器、服务、容器、代理、制品、数据集和流动关系构成的图。 |
| 设计状态 | 包含几何、调色板、着色器、图谱与经济状态的版本化快照。 |
| 手势种子 | 用于生成图谱的草图、字形、图像或符号输入。 |
| 计算回合 | 一次仿真步进，用于更新几何、图权重和经济余额。 |

---

## 7. User stories / 用户故事

### English

1. As a designer, I can upload or select a sketch so the system extracts glyph nodes and gesture edges.
2. As a designer, I can switch between elliptical and hyperbolic modes to refine or expand the generated graph.
3. As a cluster operator, I can map Docker services, compute APIs, and GPU workers as graph nodes.
4. As a collective, we can assign authorship shares to sketches, presets, shaders, datasets, and exported artifacts.
5. As a protocol designer, I can simulate micro‑flows of compute credit, attention credit, validation credit, and artifact value.
6. As an operator, I can export the graph state as JSON and replay it later.
7. As a bilingual team, we can view product labels and documentation in English or Chinese.

### 中文

1. 作为设计师，我可以上传或选择草图，系统会提取字形节点和手势边。
2. 作为设计师，我可以在椭圆模式和双曲模式之间切换，以精炼或扩展生成图谱。
3. 作为集群运维者，我可以把 Docker 服务、计算 API 与 GPU worker 映射为图节点。
4. 作为创作团体，我们可以为草图、预设、着色器、数据集和导出制品分配作者份额。
5. 作为协议设计者，我可以模拟计算信用、注意力信用、验证信用和制品价值的微流动。
6. 作为操作者，我可以将图状态导出为 JSON 并在之后重放。
7. 作为双语团队，我们可以用英文或中文查看产品标签和文档。

---

## 8. Functional requirements / 功能需求

### 8.1 Input layer / 输入层

### English

The system must support:

- Sketch image input.
- Palette input through color pickers or JSON.
- Mathematical seed presets.
- Cluster service manifests.
- Manual node and edge creation.
- Import from previous Rubkodium/Oganesson state exports.

### 中文

系统必须支持：

- 草图图像输入。
- 通过颜色选择器或 JSON 输入调色板。
- 数学种子预设。
- 集群服务清单。
- 手动创建节点和边。
- 从已有 Rubkodium/Oganesson 状态导出文件导入。

### 8.2 Geometry workflow / 几何工作流

### English

The design engine must expose two primary modes:

**Elliptical mode**

- Pull nodes toward stable attractors.
- Compress noisy branches into coherent orbits.
- Increase trust and memory weights.
- Reduce entropy and mutation rate.
- Highlight consensus paths.

**Hyperbolic mode**

- Push nodes into branching manifolds.
- Increase mutation, divergence, and exploratory edges.
- Generate alternative design states.
- Highlight contradiction, novelty, and underexplored regions.
- Allow rapid expansion from a single gesture seed.

### 中文

设计引擎必须提供两个主要模式：

**椭圆模式**

- 将节点拉向稳定吸引子。
- 将噪声分支压缩为连贯轨道。
- 增加信任权重和记忆权重。
- 降低熵和突变率。
- 高亮共识路径。

**双曲模式**

- 将节点推入分支流形。
- 增加突变、发散和探索边。
- 生成替代设计状态。
- 高亮矛盾、新颖性和未探索区域。
- 允许从单个手势种子快速扩展。

### 8.3 Nano‑economy engine / 纳米经济引擎

### English

The nano‑economy engine must track at minimum:

- Compute credit.
- Authorship credit.
- Validation credit.
- Attention credit.
- Artifact value.
- Trust score.
- Resource cost.
- Energy estimate.
- Decay over time.
- Redistribution rules.

The MVP should use an internal ledger stored in JSON or SQLite. Blockchain integration can be a later adapter.

### 中文

纳米经济引擎至少必须追踪：

- 计算信用。
- 作者信用。
- 验证信用。
- 注意力信用。
- 制品价值。
- 信任分数。
- 资源成本。
- 能耗估计。
- 随时间衰减。
- 再分配规则。

MVP 应使用存储在 JSON 或 SQLite 中的内部账本。区块链集成可作为后续适配器。

### 8.4 Cluster graph / 集群图谱

### English

The cluster graph must represent:

- Hosts.
- Virtual machines.
- Containers.
- Docker Compose services.
- Compute APIs.
- GPU workers.
- Datasets.
- Shader artifacts.
- Exported states.
- Human contributors.
- Automation agents.

Edges must represent:

- Runs on.
- Depends on.
- Authored by.
- Validated by.
- Forked from.
- Pays credit to.
- Consumes compute from.
- Emits artifact.
- Trusts.
- Mirrors.

### 中文

集群图谱必须表示：

- 主机。
- 虚拟机。
- 容器。
- Docker Compose 服务。
- 计算 API。
- GPU worker。
- 数据集。
- 着色器制品。
- 导出状态。
- 人类贡献者。
- 自动化代理。

边必须表示：

- 运行于。
- 依赖于。
- 作者为。
- 由……验证。
- 分叉自。
- 向……支付信用。
- 消耗……计算资源。
- 输出制品。
- 信任。
- 镜像。

---

## 9. Product workflow / 产品工作流

### English

1. **Seed**
   - User imports a sketch, palette, preset, or cluster manifest.
2. **Extract**
   - System extracts glyph features, colors, nodes, edges, and initial attractors.
3. **Choose geometry**
   - User selects elliptical, hyperbolic, or hybrid mode.
4. **Simulate**
   - Compute engine performs graph/field updates over multiple turns.
5. **Account**
   - Nano‑economy engine updates credits, costs, trust, and value flows.
6. **Visualize**
   - UI renders graph, fields, orbits, branch fans, and economy overlays.
7. **Refine**
   - User pins nodes, edits edges, changes weights, and re‑runs.
8. **Export**
   - System exports design state, graph, ledger, shader config, and manifest.

### 中文

1. **种子**
   - 用户导入草图、调色板、预设或集群清单。
2. **提取**
   - 系统提取字形特征、颜色、节点、边和初始吸引子。
3. **选择几何**
   - 用户选择椭圆、双曲或混合模式。
4. **仿真**
   - 计算引擎在多个回合中更新图和场。
5. **记账**
   - 纳米经济引擎更新信用、成本、信任与价值流。
6. **可视化**
   - UI 渲染图谱、场、轨道、分支扇形与经济叠加层。
7. **精炼**
   - 用户固定节点、编辑边、改变权重并重新运行。
8. **导出**
   - 系统导出设计状态、图、账本、着色器配置和清单。

---

## 10. System architecture / 系统架构

### English

Recommended MVP services:

```text
web-ui
  ├─ Three.js / WebGL renderer
  ├─ graph inspector
  ├─ economy overlay
  └─ bilingual UI labels

compute-api
  ├─ RK4 / field simulation
  ├─ elliptical-hyperbolic graph update
  ├─ glyph feature ingestion
  └─ state export endpoint

ledger-api
  ├─ nano-economy credit model
  ├─ contribution records
  ├─ trust and validation records
  └─ JSON/SQLite persistence

graph-store
  ├─ nodes
  ├─ edges
  ├─ states
  └─ lineage snapshots
```

### 中文

推荐 MVP 服务：

```text
web-ui
  ├─ Three.js / WebGL 渲染器
  ├─ 图谱检查器
  ├─ 经济叠加层
  └─ 双语 UI 标签

compute-api
  ├─ RK4 / 场仿真
  ├─ 椭圆‑双曲图更新
  ├─ 字形特征摄取
  └─ 状态导出端点

ledger-api
  ├─ 纳米经济信用模型
  ├─ 贡献记录
  ├─ 信任与验证记录
  └─ JSON/SQLite 持久化

graph-store
  ├─ 节点
  ├─ 边
  ├─ 状态
  └─ 谱系快照
```

---

## 11. Data model / 数据模型

### English

### Node

```json
{
  "id": "node_001",
  "type": "artifact | agent | service | container | host | sketch | shader | dataset | contributor",
  "label": "Rubkodium Brane",
  "geometry": {
    "mode": "elliptical | hyperbolic | hybrid",
    "position": [0, 0, 0],
    "curvature": 0.0,
    "entropy": 0.0
  },
  "economy": {
    "computeCredit": 0,
    "authorshipCredit": 0,
    "validationCredit": 0,
    "attentionCredit": 0,
    "trust": 0.5,
    "value": 0
  },
  "metadata": {}
}
```

### Edge

```json
{
  "id": "edge_001",
  "source": "node_001",
  "target": "node_002",
  "type": "depends_on | authored_by | pays_credit_to | consumes_compute_from | forked_from | validates",
  "weight": 1.0,
  "flow": {
    "compute": 0,
    "value": 0,
    "trust": 0,
    "attention": 0
  }
}
```

### 中文

### 节点

```json
{
  "id": "node_001",
  "type": "artifact | agent | service | container | host | sketch | shader | dataset | contributor",
  "label": "Rubkodium Brane",
  "geometry": {
    "mode": "elliptical | hyperbolic | hybrid",
    "position": [0, 0, 0],
    "curvature": 0.0,
    "entropy": 0.0
  },
  "economy": {
    "computeCredit": 0,
    "authorshipCredit": 0,
    "validationCredit": 0,
    "attentionCredit": 0,
    "trust": 0.5,
    "value": 0
  },
  "metadata": {}
}
```

### 边

```json
{
  "id": "edge_001",
  "source": "node_001",
  "target": "node_002",
  "type": "depends_on | authored_by | pays_credit_to | consumes_compute_from | forked_from | validates",
  "weight": 1.0,
  "flow": {
    "compute": 0,
    "value": 0,
    "trust": 0,
    "attention": 0
  }
}
```

---

## 12. Elliptical‑hyperbolic transition model / 椭圆‑双曲转换模型

### English

Each compute turn updates the graph using a curvature parameter `k`.

```text
k < 0  → hyperbolic expansion
k = 0  → neutral Euclidean drift
k > 0  → elliptical convergence
```

Suggested update rule:

```text
next_position =
  current_position
  + mutation_force * max(0, -k)
  + attractor_force * max(0, k)
  + economy_flow_force
  + trust_gradient
  - entropy_decay
```

### 中文

每个计算回合使用曲率参数 `k` 更新图谱。

```text
k < 0  → 双曲扩张
k = 0  → 中性欧几里得漂移
k > 0  → 椭圆收敛
```

建议更新规则：

```text
next_position =
  current_position
  + mutation_force * max(0, -k)
  + attractor_force * max(0, k)
  + economy_flow_force
  + trust_gradient
  - entropy_decay
```

---

## 13. MVP scope / MVP 范围

### English

### Must have

- Bilingual PRD and labels.
- Graph node/edge schema.
- Docker Compose setup.
- WebGL graph visualization.
- Compute API with `/health`, `/step`, `/snapshot`, `/export`.
- Elliptical/hyperbolic mode switch.
- Nano‑economy JSON ledger.
- Import/export of graph state.
- Basic sketch‑seed ingestion.

### Should have

- WebGPU compute scaffold.
- Authorship attribution editor.
- Contribution weighting.
- Trust and validation scoring.
- Preset library.
- Graph replay timeline.

### Could have

- Smart contract adapter.
- IPFS or object storage adapter.
- Live cluster metrics.
- Multi-user collaboration.
- Chinese/English UI toggle.
- Agent-based graph recommendations.

### 中文

### 必须有

- 双语 PRD 和标签。
- 图节点/边 schema。
- Docker Compose 设置。
- WebGL 图谱可视化。
- 带 `/health`、`/step`、`/snapshot`、`/export` 的计算 API。
- 椭圆/双曲模式切换。
- 纳米经济 JSON 账本。
- 图状态导入/导出。
- 基础草图种子摄取。

### 应该有

- WebGPU 计算脚手架。
- 作者归属编辑器。
- 贡献权重。
- 信任与验证评分。
- 预设库。
- 图谱重放时间线。

### 可以有

- 智能合约适配器。
- IPFS 或对象存储适配器。
- 实时集群指标。
- 多用户协作。
- 中英文 UI 切换。
- 基于代理的图谱推荐。

---

## 14. API requirements / API 需求

### English

```http
GET /health
GET /snapshot
POST /step
POST /ingest/sketch
POST /ingest/manifest
POST /graph/node
POST /graph/edge
POST /economy/transfer
POST /economy/recompute
GET /export/state-space.json
GET /export/ledger.json
```

### 中文

```http
GET /health
GET /snapshot
POST /step
POST /ingest/sketch
POST /ingest/manifest
POST /graph/node
POST /graph/edge
POST /economy/transfer
POST /economy/recompute
GET /export/state-space.json
GET /export/ledger.json
```

---

## 15. UI requirements / UI 需求

### English

The UI must contain:

- Mode switch: Elliptical / Hyperbolic / Hybrid.
- Graph viewport.
- Node inspector.
- Edge inspector.
- Economy overlay.
- Compute turn controls.
- Import/export panel.
- Palette and glyph seed panel.
- Bilingual label toggle.
- Status panel for compute API and ledger API.

### 中文

UI 必须包含：

- 模式切换：椭圆 / 双曲 / 混合。
- 图谱视口。
- 节点检查器。
- 边检查器。
- 经济叠加层。
- 计算回合控制。
- 导入/导出面板。
- 调色板与字形种子面板。
- 双语标签切换。
- 计算 API 与账本 API 状态面板。

---

## 16. Metrics / 指标

### English

### Product metrics

- Time from sketch import to first graph.
- Number of nodes generated per seed.
- Number of meaningful user edits.
- Export success rate.
- Replay success rate.

### Compute metrics

- Step latency.
- Graph update throughput.
- WebGL frame rate.
- Memory use.
- Container health.

### Nano‑economy metrics

- Credit conservation.
- Contribution distribution.
- Trust convergence.
- Validation density.
- Artifact lineage depth.

### 中文

### 产品指标

- 从草图导入到生成第一个图谱所需时间。
- 每个种子生成的节点数量。
- 有意义的用户编辑次数。
- 导出成功率。
- 重放成功率。

### 计算指标

- 单步延迟。
- 图更新吞吐量。
- WebGL 帧率。
- 内存使用。
- 容器健康状态。

### 纳米经济指标

- 信用守恒。
- 贡献分布。
- 信任收敛。
- 验证密度。
- 制品谱系深度。

---

## 17. Acceptance criteria / 验收标准

### English

MVP is accepted when:

1. A user can import a sketch and generate a graph.
2. A user can switch between elliptical and hyperbolic graph behavior.
3. The compute API can run at least 100 simulation turns without crashing.
4. The nano‑economy ledger updates after each compute turn.
5. The UI can inspect at least node type, edge type, trust, value, and compute credit.
6. The system can export a complete state-space JSON.
7. Docker Compose starts the full local stack with one command.
8. English and Chinese PRD documentation exists.

### 中文

MVP 在以下条件满足时通过验收：

1. 用户可以导入草图并生成图谱。
2. 用户可以切换椭圆与双曲图行为。
3. 计算 API 至少可以连续运行 100 个仿真回合且不崩溃。
4. 纳米经济账本在每个计算回合后更新。
5. UI 可以检查节点类型、边类型、信任、价值和计算信用。
6. 系统可以导出完整的状态空间 JSON。
7. Docker Compose 可以用一条命令启动完整本地栈。
8. 存在英文与中文 PRD 文档。

---

## 18. Risks / 风险

### English

| Risk | Mitigation |
|---|---|
| Conceptual overload | Provide presets and simple mode names. |
| Graph becomes unreadable | Add filters, clustering, zoom levels, and semantic layers. |
| Economy model feels arbitrary | Make all weights visible and editable. |
| Compute becomes slow | Support level-of-detail, worker threads, and WebGPU later. |
| Users confuse simulation with real finance | Clearly label MVP as internal credit simulation. |
| Bilingual drift | Maintain shared keys with separate translation files. |

### 中文

| 风险 | 缓解方式 |
|---|---|
| 概念过载 | 提供预设和简单模式名称。 |
| 图谱不可读 | 添加过滤、聚类、缩放层级和语义层。 |
| 经济模型显得随意 | 让所有权重可见且可编辑。 |
| 计算变慢 | 支持细节层级、worker 线程，并在后续加入 WebGPU。 |
| 用户把仿真误认为真实金融 | 明确标注 MVP 是内部信用仿真。 |
| 双语含义漂移 | 维护共享 key 与独立翻译文件。 |

---

## 19. Roadmap / 路线图

### Phase 1 — Foundation / 阶段 1：基础

- PRD and architecture docs.
- Graph schema.
- Docker Compose.
- Compute API.
- WebGL graph renderer.
- JSON ledger.

### Phase 2 — Workflow engine / 阶段 2：工作流引擎

- Elliptical/hyperbolic controls.
- Sketch and palette ingestion.
- State replay.
- Node/edge editor.
- Economy overlay.

### Phase 3 — Cluster integration / 阶段 3：集群集成

- Docker service discovery.
- Host/container graph sync.
- GPU worker mapping.
- Live health metrics.
- Automation agents.

### Phase 4 — Protocol adapters / 阶段 4：协议适配器

- Smart contract adapter.
- IPFS/object storage adapter.
- Multi-user collaboration.
- Permission and identity model.
- Export to external dashboards.

---

## 20. Open questions / 待定问题

### English

1. Should nano‑economy credits be purely internal or convertible to external tokens later?
2. Should graph state use SQLite, JSON files, or a graph database in MVP?
3. Should sketch ingestion be image-based only, or also support SVG and handwritten JSON?
4. Should the first UI prioritize beauty, debugging, or live performance?
5. What is the minimum viable authorship model for collective work?
6. Should Chinese UI be Simplified Chinese only at first?

### 中文

1. 纳米经济信用应保持纯内部，还是未来可转换为外部代币？
2. MVP 中图状态应使用 SQLite、JSON 文件还是图数据库？
3. 草图摄取应只支持图像，还是也支持 SVG 与手写 JSON？
4. 第一版 UI 应优先美感、调试还是实时性能？
5. 集体创作的最小可行作者模型是什么？
6. 中文 UI 第一版是否只支持简体中文？

---

## 21. Initial implementation package / 初始实现包

### English

Recommended repository layout:

```text
rubkodium-nano-economy/
  apps/
    web-ui/
    compute-api/
    ledger-api/
  packages/
    graph-core/
    geometry-core/
    economy-core/
    i18n/
  data/
    seeds/
    manifests/
    exports/
  docker-compose.yml
  README.md
  PRD.en-zh.md
```

### 中文

推荐仓库结构：

```text
rubkodium-nano-economy/
  apps/
    web-ui/
    compute-api/
    ledger-api/
  packages/
    graph-core/
    geometry-core/
    economy-core/
    i18n/
  data/
    seeds/
    manifests/
    exports/
  docker-compose.yml
  README.md
  PRD.en-zh.md
```

---

## 22. Glossary / 术语表

| English | 中文 |
|---|---|
| Elliptical workflow | 椭圆工作流 |
| Hyperbolic workflow | 双曲工作流 |
| Nano‑economy | 纳米经济 |
| Cluster graph | 集群图谱 |
| Compute turn | 计算回合 |
| Design state | 设计状态 |
| Gesture seed | 手势种子 |
| Authorship credit | 作者信用 |
| Validation credit | 验证信用 |
| Trust gradient | 信任梯度 |
| Artifact lineage | 制品谱系 |
| Curvature parameter | 曲率参数 |

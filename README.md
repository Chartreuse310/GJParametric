# GJParametric

A Parametric Modeling System for Traditional Chinese Architecture
中国古代建筑参数化建模系统

## 1. Project Overview / 项目概述

GJParametric is a research and development project aimed at creating a parametric modeling system for traditional Chinese architecture. The system integrates component databases, preset-based generation, interactive UI design, and 3D rendering/export functionalities.
GJParametric 是一个面向中国古代建筑的参数化建模系统研发项目，集成了构件数据库、预设驱动生成、交互式界面设计以及三维渲染与模型导出功能。

**Key Goals / 核心目标:**

- Allow easy creation of component-based models from photos or references. 便于根据照片或参考资料快速创建构件模型。
- Support preservation and engineering applications with metadata. 支持带档案信息的模型，用于保护和工程应用。
- Enable modular and expandable workflows suitable for research and teaching. 提供模块化、可扩展的工作流程，适用于科研与教学。

## 2. Current Progress / 当前进展

The project currently includes the following modules:
项目目前包括以下模块：

### 1. Component Database / 构件数据库

- Establishing a structured component library (JSON/STEP/XML). 建立结构化构件库（JSON/STEP/XML）。
- Collecting references from traditional architecture examples and literature.  收集传统建筑实例和文献参考。
- Defining data schema and management strategy. 定义数据结构和管理方案。

### 2. Preset Selection → Generate Required Component Set / 选择预设 → 输出所需构件集

- Build a preset library. 构建预设库。
- Batch naming based on presets (Python/C++). 根据预设信息批量命名（Python/C++）。
- Adjust geometry according to parameter constraints (OCCT). 根据参数约束调整几何（OCCT）。
- Define parameter constraints rules as a prerequisite. 作为前置，整理参数约束规则。

### 3. Result Visualization / 结果样式渲染

- UI design and implementation (Qt). UI 设计与实现（Qt）。
- Model rendering (OCCT). 模型渲染（OCCT）。
- Model Export / 模型导出
- Export models in standard 3D formats (STEP, IGES, BREP). 支持标准三维格式导出（STEP、IGES、BREP）。
- Preserve geometry and metadata. 保留几何信息和构件参数元数据。

## 3. Team Structure / 团队结构

The project is organized by roles, which currently are all handled by a single developer (i.e. me :D). Future collaborators may join each team.
项目按角色划分，目前由单人承担（我:D）所有角色，未来可扩展团队成员。

### Heritage Architecture Research Team / 古建研究者团队

Focuses on architectural knowledge, historical references, and component rules.
负责建筑知识、历史参考资料及构件规则制定。

### Interaction Design Team / 交互设计团队

Focuses on UI/UX and user workflow.
负责界面与交互设计，优化用户工作流程。

### Development Team / 程序实现团队

Implements the system logic, geometry adjustments, rendering, and export.
负责系统逻辑、几何调整、渲染与模型导出实现。

## 4. Labels & Workflow / 标签与工作流

Issues are categorized by technical domain and workflow stage.
Issues 按技术领域和工作流程阶段分类。

### Technical Labels / 技术标签:

- core — Core system components / 核心模块

- data-model — Component database and schema / 构件数据库与数据结构

- ui-ux / design — Interface and interaction design / 界面与交互设计

- occt — Geometry and rendering using OCCT / OCCT 几何与渲染

- preset — Preset definitions and automation / 预设定义与自动化

### Workflow Labels / 工作流程标签:

- experimental — Prototyping and idea exploration / 原型和探索性任务

- discussion — For internal discussion / 内部讨论

- help wanted — Tasks needing extra attention / 需要额外关注的任务

## 5. Development Status / 开发状态

| Module / 模块                             | Status / 状态                                                  |
| --------------------------------------- | ------------------------------------------------------------ |
| Component Database / 构件数据库              | In progress / 进行中                                            |
| Preset Selection & Generation / 预设选择与生成 | In progress / 进行中                                            |
| Result Visualization / 结果渲染             | UI design drafted / UI 设计草稿完成, rendering in progress / 渲染进行中 |
| Model Export / 模型导出                     | Planned / 计划中                                                |

## 6. How to Contribute / 如何贡献

Discuss experimental ideas in Draft issues before implementation.
在正式实现前，可在 Draft issue 中讨论探索性想法。

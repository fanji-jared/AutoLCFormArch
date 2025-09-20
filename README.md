# Auto LC Form Arch

# 智能表格驱动的高低代码表单架构解决方案

## 核心价值

### ⚡ 双引擎输出
一键生成标准vue-form-design配置JSON
同步输出公司专有平台所需的 tableJson + dbStruct 结构
内置字段类型→控件类型的智能映射规则库

### 🎯 低代码增强
通过Excel/CSV定义表单结构，自动生成生产级代码
支持动态布局算法（栅格/流式/自由布局）
可视化校验规则配置（必填/格式/联动）

### 🛠️ 企业级扩展
提供MCP服务标准化接口，支持AI系统集成
可插拔架构设计，适配不同低代码平台规范

## 技术特性

graph LR A[表格输入] --> B(智能布局引擎) B --> C[vue-form-design JSON] B --> D[Platform tableJson/dbStruct]

## 快速开始

### 安装核心引擎
pip install auto-lc-form-arch 
### 从Excel生成配置
python -m autolcformarch convert -i design.xlsx -t vue

## 📌 适用场景
- 企业级低代码平台-表单源表快速生成
- 跨平台表单配置的统一管理中心

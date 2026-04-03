# 贡献指南

感谢你有兴趣为产品思考三步法项目做出贡献！我们欢迎所有形式的贡献。

## 如何贡献

### 报告问题

如果你发现了bug或有功能建议：

1. 检查 [Issues](https://github.com/your-username/product-manager/issues) 确保问题尚未被报告
2. 如果没有相关issue，创建一个新的issue
3. 使用提供的issue模板填写详细信息
4. 对于bug，提供复现步骤和环境信息
5. 对于功能请求，清楚描述用例和预期行为

### 提交代码

1. **Fork项目**并创建你的分支
   ```bash
   git checkout -b feature/AmazingFeature
   ```

2. **进行修改**
   - 遵循现有的代码风格和格式
   - 添加必要的文档
   - 更新相关的README或示例

3. **提交更改**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

4. **推送到分支**
   ```bash
   git push origin feature/AmazingFeature
   ```

5. **开启Pull Request**

### Pull Request指南

- 使用清晰的标题描述你的更改
- 在PR描述��引用相关的issue（如 `Fixes #123`）
- 填写PR模板中的所有相关部分
- 确保你的代码通过所有检查
- 响应代码审查的反馈

## 开发指南

### 项目结构

```
product-manager/
├── SKILL.md                    # 核心skill定义
├── Workflows/                  # 工作流程
│   ├── Clarify.md
│   ├── Deconstruct.md
│   ├── Simplify.md
│   └── Decide.md
├── references/                 # 领域知识库
│   ├── product-discovery.md
│   ├── mvp.md
│   ├── user-behavior.md
│   ├── metrics.md
│   ├── competition.md
│   ├── trigger-questions.md
│   ├── output-patterns.md
│   ├── examples.md
│   └── anti-patterns.md
└── README.md
```

### 添加新内容

#### 添加新的工作流步骤

1. 在 `Workflows/` 目录创建新的Markdown文件
2. 遵循现有工作流的格式和结构
3. 更新 `SKILL.md` 中的工作流路由部分
4. 添加使用示例

#### 添加新的领域知识

1. 在 `references/` 目录创建新的Markdown文件
2. 使用清晰的标题和组织结构
3. 提供具体示例和反模式
4. 在 `SKILL.md` 中添加引用

#### 添加示例

1. 在 `references/examples.md` 中添加新示例
2. 或创建独立的示例文件
3. 遵循"澄清→拆解→简化→决策"的四步结构
4. 包含具体的输入和输出

### 文档风格

- 使用清晰、简洁的语言
- 避免过度技术化的术语
- 提供具体的示例
- 使用中文（主要语言）和英文（国际用户）
- 保持一致的格式和结构

### 代码规范

虽然本项目主要是文档，但如果你贡献代码：

- 使用有意义的变量和函数名
- 添加注释解释复杂逻辑
- 遵循项目的现有风格
- 确保代码可读和可维护

## 测试

### 文档测试

- 确保所有链接有效
- 检查Markdown格式正确
- 验证示例可以独立理解
- 确保术语使用一致

### 功能测试

如果贡献功能代码：

- 编写单元测试
- 测试边界情况
- 确保向后兼容性
- 更新相关文档

## 社区准则

- 尊重所有贡献者
- 提供建设性反馈
- 欢迎新手提问
- 保持专业和友善
- 关注问题而非个人

## 获取帮助

如果你在贡献过程中需要帮助：

1. 查看 [文档](README.md)
2. 搜索现有的 [Issues](https://github.com/your-username/product-manager/issues)
3. 创建新的issue并使用"Question"标签
4. 在Discussions中发起讨论

## 认可贡献者

所有贡献者都会在项目的贡献者列表中被认可。我们感谢每一个贡献，无论大小！

## 许可证

通过贡献代码，你同意你的贡献将在与项目相同的 [MIT License](LICENSE) 下发布。

---

再次感谢你的贡献！🎉

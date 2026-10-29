# Contributing

感谢你改进 Human Writing for Technical Docs。

## 提交前

- 说明你观察到的具体失败模式，不要只说“还是有 AI 味”。指出它影响本领域技术人员、相邻领域工程师还是非技术读者。
- 提供最小输入、实际输出和期望变化；请移除隐私与敏感信息。
- 新规则应能被检查，并说明它可能误伤哪些体裁。
- 不要把个人偏好直接升级为所有技术文档都必须遵守的规则。

## 本地验证

```bash
python ~/.codex/skills/.system/skill-creator/scripts/quick_validate.py .
```

验证器只检查 Skill 的基本结构。提交前还应至少测试一份设计文档、一份操作文档和一份包含缩写的跨领域说明，确认没有编造系统行为，也没有为了通俗而损失技术精度。

# Contributing

感谢你改进 Human Writing。

## 提交前

- 说明你观察到的具体失败模式，不要只说“还是有 AI 味”。
- 提供最小输入、实际输出和期望变化；请移除隐私与敏感信息。
- 新规则应能被检查，并说明它可能误伤哪些体裁。
- 不要把个人偏好直接升级为所有文本都必须遵守的规则。

## 本地验证

```bash
python ~/.codex/skills/.system/skill-creator/scripts/quick_validate.py .
```

验证器只检查 Skill 的基本结构。提交前还应使用至少一个从零写作、一个重写和一个只调语气的请求进行人工测试，确认没有编造事实或扩大结论。

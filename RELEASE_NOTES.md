# Anything Analyzer v3.6.38

## 修复

- **Responses API 工具调用参数校验** — 避免非字符串 arguments 被当作工具执行错误吞掉
  - 工具调用入站阶段直接拒绝 arguments 非字符串的畸形 function_call
  - 新增回归测试覆盖 Responses API function_call 参数类型异常路径

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.38.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.38-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.38-x64.dmg |
| Linux | Anything-Analyzer-3.6.38.AppImage |

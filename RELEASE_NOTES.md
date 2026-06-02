# Anything Analyzer v3.6.34

## 修复

- **流式损坏 JSON 诊断** — 避免 SSE `data` 载荷 JSON 损坏时被误判为空成功结果
  - OpenAI Chat、Responses API、Anthropic/MiniMax 流式解析现在都会抛出明确的 malformed JSON 错误
  - 新增回归测试覆盖三个流式接口的损坏 JSON 载荷异常路径

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.34.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.34-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.34-x64.dmg |
| Linux | Anything-Analyzer-3.6.34.AppImage |

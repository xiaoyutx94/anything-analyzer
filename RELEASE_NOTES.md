# Anything Analyzer v3.6.15

## 修复

- **OpenAI Chat 流式末尾事件不再丢失** — 修复 Chat Completions SSE 响应没有尾随换行时最后一行 `data:` 未被解析，导致末尾文本块或 usage 被忽略的问题
  - 在流结束后补处理剩余 buffer，保持逐行解析逻辑一致
  - 增加无尾随换行 SSE 回归测试，确保最后文本块会进入增量回调和最终内容

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.15.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.15-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.15-x64.dmg |
| Linux | Anything-Analyzer-3.6.15.AppImage |

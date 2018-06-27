# TODO

# 代码结构变更

- [ ] 统一的类，允许创建一个控制台对象
      * 提供默认的 prompt 字符串
      * 提供统一的自动完成机制
      * 允许自动完成机制使用外部数据源
- [ ] 提供创建内置命令的指令
- [ ] 使用 capnproto 或 flatbuffer 作为结果的序列化格式
- [ ] 内嵌 LuaJIT
- [ ] 命令历史记录从 SQLite 切换回纯文本文件
- [ ] 提供多种命令历史记录的存储机制
- 提供额外的配置项（历史文件位置 | RC文件位置 | 命令定义文件、脚本)
- [ ] 调整结果集Pipe的传输为命名管道


# 兼容性

- [ ] 实现跨平台的 isatty 检测
  https://github.com/dtolnay/isatty/blob/master/src/lib.rs

- [ ] 处理 uname 等跨平台特性

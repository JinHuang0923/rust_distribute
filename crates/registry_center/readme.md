# Introduction
1. 负载均衡 (可以单独写组件完成)
2. 健康检查
# todo
- [x] 使用tracing
## 可观测
- [ ] 搞个前端界面,轮询状态信息,使用echarts之类的图标库展示各类信息 
- [ ] 沟通一下找猎头那边弄个前端随便搞一下
## 高可用
- [ ] 单独开一个线程处理转换master的逻辑 
- [ ] 向节点发布指令的实现
  - [ ] 主从转换
  - [ ] slave更换master(重新连接新的master)
# Show-Demo

面向运维与可观测性实验的 Demo 代码组织，聚焦可直接复现的部署、链路、告警与故障演练场景。

## 组织定位

- 用最少步骤完成实验环境搭建（Docker Compose / K8s）
- 提供可直接打流量的示例服务，验证链路与拓扑
- 覆盖告警通知、日志关联、性能分析等常见运维实验项

## 当前核心仓库

- [skywalking-v8-java8-demo](https://github.com/Show-Demo/skywalking-v8-java8-demo)
  - SkyWalking 8.9.1 + Java 8 + Elasticsearch
  - 适合传统 Java 业务链路监控与告警演示

- [skywalking-v10-java17-demo](https://github.com/Show-Demo/skywalking-v10-java17-demo)
  - SkyWalking 10.x + Java 17
  - 适合新版功能验证与综合实验演示

## 使用方式

1. 进入对应仓库，阅读 `docs/README.md`
2. 按文档启动环境并生成测试流量
3. 在 UI 中验证服务拓扑、追踪、告警与日志关联

# Show-Demo

运维与可观测性实验代码组织，覆盖日志、链路、告警、性能、CI/CD、微服务和前端工程等常见演示场景。

## 仓库导航

### 可观测性与链路

- [skywalking-v10-java17-demo](https://github.com/Show-Demo/skywalking-v10-java17-demo) - SkyWalking 10.x + Java 17 综合实验
- [skywalking-v8-java8-demo](https://github.com/Show-Demo/skywalking-v8-java8-demo) - SkyWalking 8.9.1 + Java 8 兼容场景
- [elk-filebeat-java-demo](https://github.com/Show-Demo/elk-filebeat-java-demo) - ELK + Filebeat 日志采集与检索
- [inventory-demo](https://github.com/Show-Demo/inventory-demo) - 日志告警演示（库存不足）
- [microservice-demo](https://github.com/Show-Demo/microservice-demo) - 微服务链路调用测试
- [EagleEye-TraceID-demo](https://github.com/Show-Demo/EagleEye-TraceID-demo) - 日志 TraceId 关联演示
- [elk-demo](https://github.com/Show-Demo/elk-demo) - 旧版 ELK 演示（已过时）

### Java 稳定性与数据层

- [memory-troubleshooting-springboot](https://github.com/Show-Demo/memory-troubleshooting-springboot) - 内存泄漏/溢出排查
- [springboot-graceful-demo](https://github.com/Show-Demo/springboot-graceful-demo) - Spring Boot 优雅下线
- [easyexcel-demo](https://github.com/Show-Demo/easyexcel-demo) - EasyExcel 导出内存优化
- [springboot-sharding-demo](https://github.com/Show-Demo/springboot-sharding-demo) - ShardingSphere 分表

### DevOps / CI / 制品库

- [demo-java](https://github.com/Show-Demo/demo-java) - KubeSphere 流水线（Java）
- [demo-javascript](https://github.com/Show-Demo/demo-javascript) - KubeSphere 流水线（前端）
- [springboot-vue-backend-demo](https://github.com/Show-Demo/springboot-vue-backend-demo) - SonarQube 扫描后端样例
- [springboot-vue-frontend-demo](https://github.com/Show-Demo/springboot-vue-frontend-demo) - SonarQube 扫描前端样例
- [nexus-demo](https://github.com/Show-Demo/nexus-demo) - Nexus 使用演示
- [use-nexus-demo](https://github.com/Show-Demo/use-nexus-demo) - Nexus 集成样例

### 前端与微前端

- [wujie](https://github.com/Show-Demo/wujie) - 微前端框架示例
- [wujie-demo](https://github.com/Show-Demo/wujie-demo) - Wujie 实践 Demo

## 建议使用方式

1. 按实验主题进入对应仓库并阅读 `README` / `docs`。
2. 优先使用仓库提供的 `docker compose` 或脚本完成一键启动。
3. 通过压测或请求回放生成数据，再在 UI 中验证链路、日志与告警结果。

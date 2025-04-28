# Kmesh支持内核级mTLS能力
**项目名称**: Kmesh支持内核级mTLS能力    

**导师信息**: 
  - **姓名**: 吴长冶
  - **邮箱**: wuchangye@huawei.com

**难度**: 高    

**分类**: 新型模块化组件 

## 题目要求

- **功能需求**: 

  背景描述：

  Kmesh是openEuler社区孵化的CNCF sandbox项目，基于可编程内核实现Sidecarless流量治理引擎，通过将流量治理下沉操作系统，免去sidecar的多跳中转，大幅提升网格内微服务转发性能；mTLS是服务网格中的重要安全机制，Kmesh社区已实现dual-engine模式下的IpSec安全加密方案，但在细粒度授权、身份认证等方面仍有不足，需要完善基于mTLS的安全机制；

  - 功能1：基于Kmesh dual-engine模式支持mTLS安全加密能力；

- **性能需求**: 

  fortio场景下，Kmesh mTLS方案相比传统sidecar mTLS方案性能提升50%；

- **应用场景**: 

- 场景1：金融交易、在线会议等场景

- **约束**: 

  - 约束1: 基于Kmesh社区完成特性开发；

## License

- **许可协议**: [Apache-2.0 license](https://github.com/kmesh-net/kmesh#Apache-2.0-1-ov-file) 

## 参考资料

- **参考资料1**: https://github.com/kmesh-net/kmesh

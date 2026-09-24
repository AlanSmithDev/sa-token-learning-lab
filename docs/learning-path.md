# Sa-Token 学习路径（四阶段）

## 阶段一：认知与入门
- 理解认证 / 授权 / Session / Token 的基本概念
- 跑通一个最小 Spring Boot 示例（参考 `sa-token-demo/sa-token-demo-springboot`）
- 阅读 `sa-token-core` 顶层 API：`StpUtil`、`SaTokenManager`

## 阶段二：核心机制
- Token 生成与校验（`stp` 包）
- 会话模型（`session` 包）与上下文（`context` 包）
- 权限注解与拦截器（`annotation`、`filter` 包）
- 持久化 DAO（`dao` 包）与序列化（`serializer` 包）

## 阶段三：框架集成
- Spring Boot 自动装配（`sa-token-starter/sa-token-spring-boot-starter`）
- 响应式 WebFlux / Solon / JFinal 适配（`sa-token-starter` 下各子模块）
- 理解 `META-INF/spring.factories` 与自动配置原理

## 阶段四：生态扩展与实战
- 结合 Redis 做分布式会话（`sa-token-plugin/sa-token-redis-jackson`）
- 单点登录与 OAuth2（`sa-token-plugin/sa-token-sso`、`sa-token-oauth2`）
- 网关鉴权、API Key、签名等生产级能力
- 参考 50+ 示例工程做自己的集成练习

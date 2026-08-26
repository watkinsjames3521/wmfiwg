最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 mq 故障降级业务策略
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.39ui03.asia/arts/208807.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.39ui03.asia/arts/771548.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.39ui03.asia/arts/832406.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.39ui03.asia/arts/155166.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.39ui03.asia/arts/432917.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.39ui03.asia/arts/120188.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.39ui03.asia/arts/419700.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.39ui03.asia/arts/241514.Doc

原标题：文件分片上传断点续传功能
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.39ui03.asia/arts/422900.Doc

原标题：golang es 分词器选型业务适配
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.39ui03.asia/arts/782557.Doc

原标题：golang url 参数编码处理方案
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.39ui03.asia/arts/593883.Doc

原标题：批量数据处理脚本编写技巧
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.39ui03.asia/arts/892589.Doc

原标题：网关集成鉴权限流日志一体化
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.39ui03.asia/arts/346317.Doc

原标题：vue pinia 状态管理实战教程
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.39ui03.asia/arts/442733.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.39ui03.asia/arts/459897.Doc

原标题：golang 系统设计分布式事务几种方案
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.39ui03.asia/arts/664759.Doc

原标题：百万数据 Excel 导出内存优化
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.39ui03.asia/arts/159408.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.39ui03.asia/arts/930625.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.39ui03.asia/arts/500037.Doc

原标题：前端工程化 webpack 打包优化
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.39ui03.asia/arts/034489.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.39ui03.asia/arts/331293.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.39ui03.asia/arts/677620.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.39ui03.asia/arts/375732.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.39ui03.asia/arts/775888.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.39ui03.asia/arts/646257.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.39ui03.asia/arts/798217.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.39ui03.asia/arts/158396.Doc

原标题：静态资源 404 路径打包修复
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.39ui03.asia/arts/131154.Doc

原标题：golang docker compose 完整语法
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.39ui03.asia/arts/830360.Doc

原标题：golang viper 配置热更新实操
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.39ui03.asia/arts/629537.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.39ui03.asia/arts/347003.Doc

原标题：golang 优雅处理 http 超时设置
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.39ui03.asia/arts/908544.Doc

原标题：Mock 接口服务快速搭建实操
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.39ui03.asia/arts/237924.Doc

原标题：异步任务堆积消费能力优化
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.39ui03.asia/arts/093943.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.39ui03.asia/arts/488573.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.39ui03.asia/arts/676615.Doc

原标题：文件批量导入导出功能实现
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.39ui03.asia/arts/712259.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.39ui03.asia/arts/933633.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.39ui03.asia/arts/188092.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.39ui03.asia/arts/973478.Doc


二、踩坑排错｜Troubleshooting
原标题：Performance：JSON序列化性能优化实践
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.39ui03.asia/arts/886921.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.39ui03.asia/arts/991436.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.39ui03.asia/arts/004863.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.39ui03.asia/arts/226219.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.39ui03.asia/arts/207671.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.39ui03.asia/arts/936987.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.39ui03.asia/arts/415165.Doc

原标题：前后端交互跨域问题完整处理
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.39ui03.asia/arts/334404.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.39ui03.asia/arts/603546.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.39ui03.asia/arts/928514.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.39ui03.asia/arts/259395.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.39ui03.asia/arts/888456.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.39ui03.asia/arts/969808.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.39ui03.asia/arts/889003.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.39ui03.asia/arts/647564.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.39ui03.asia/arts/162632.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.39ui03.asia/arts/334309.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.39ui03.asia/arts/703468.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.39ui03.asia/arts/317555.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.39ui03.asia/arts/992068.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.39ui03.asia/arts/610263.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.39ui03.asia/arts/471951.Doc

原标题：Dockerfile 编写容器打包实战
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.39ui03.asia/arts/242578.Doc

原标题：读懂开源项目 README 实用技巧
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.39ui03.asia/arts/426318.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.39ui03.asia/arts/340206.Doc

原标题：本地运行正常线上报错排查
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.39ui03.asia/arts/940733.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.39ui03.asia/arts/152070.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.39ui03.asia/arts/599073.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.39ui03.asia/arts/471379.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.39ui03.asia/arts/611988.Doc

原标题：golang mongodb 事务多文档使用
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.39ui03.asia/arts/137696.Doc

原标题：golang docker 基础命令实操汇总
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.39ui03.asia/arts/345623.Doc

原标题：系统时间同步定时任务偏移
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.39ui03.asia/arts/711503.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.39ui03.asia/arts/348660.Doc

原标题：手写简易 ORM 理解对象映射
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.39ui03.asia/arts/462515.Doc

原标题：跨库查询性能优化处理
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.39ui03.asia/arts/820148.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.39ui03.asia/arts/374843.Doc

原标题：前后端会话登录状态持久化
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.39ui03.asia/arts/277222.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.39ui03.asia/arts/095783.Doc

原标题：golang 系统设计分布式配置中心思路
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.39ui03.asia/arts/759296.Doc

三、实战开发｜Practice
原标题：CI/CD 流水线自动构建部署落地
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.39ui03.asia/arts/418695.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.39ui03.asia/arts/207814.Doc

原标题：全局本地依赖隔离冲突规避
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.39ui03.asia/arts/800600.Doc

原标题：golang 工具函数库封装思路
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.39ui03.asia/arts/489620.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.39ui03.asia/arts/528717.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.39ui03.asia/arts/803608.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.39ui03.asia/arts/802158.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.39ui03.asia/arts/718107.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.39ui03.asia/arts/801874.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.39ui03.asia/arts/660557.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.39ui03.asia/arts/437985.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.39ui03.asia/arts/526808.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.39ui03.asia/arts/144588.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.39ui03.asia/arts/182259.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.39ui03.asia/arts/250300.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.39ui03.asia/arts/196144.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.39ui03.asia/arts/290714.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.39ui03.asia/arts/985999.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.39ui03.asia/arts/539624.Doc

原标题：K8s 镜像拉取网络故障修复
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.39ui03.asia/arts/495313.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.39ui03.asia/arts/951554.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.39ui03.asia/arts/450351.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.39ui03.asia/arts/114307.Doc

原标题：前端防抖节流高频事件处理
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.39ui03.asia/arts/210028.Doc

原标题：Security：RPC调用身份认证安全加固
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.39ui03.asia/arts/241331.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.39ui03.asia/arts/341363.Doc

原标题：golang git 提交信息规范校验
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.39ui03.asia/arts/058540.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.39ui03.asia/arts/925180.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.39ui03.asia/arts/346897.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.39ui03.asia/arts/998346.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.39ui03.asia/arts/344966.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.39ui03.asia/arts/394099.Doc

原标题：golang redis 锁超时业务处理
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.39ui03.asia/arts/246219.Doc

原标题：golang 布隆过滤器实现去重
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.39ui03.asia/arts/639613.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.39ui03.asia/arts/762790.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.39ui03.asia/arts/492465.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.39ui03.asia/arts/195338.Doc

原标题：golang consul 服务发现简单示例
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.39ui03.asia/arts/801071.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.39ui03.asia/arts/295750.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.39ui03.asia/arts/239552.Doc

四、架构设计｜Architecture
原标题：零基础理解依赖管理与包管理器
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.39ui03.asia/arts/979702.Doc

原标题：OpenAPI 自动接口文档生成
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.39ui03.asia/arts/666427.Doc

原标题：nodejs redis 缓存业务实战
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.39ui03.asia/arts/096683.Doc

原标题：死信队列处理消息阻塞业务
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.39ui03.asia/arts/883415.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.39ui03.asia/arts/225594.Doc

原标题：数据库连接池参数调优
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.39ui03.asia/arts/566015.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.39ui03.asia/arts/128750.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.39ui03.asia/arts/399557.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.39ui03.asia/arts/014700.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.39ui03.asia/arts/563236.Doc

原标题：K8s 镜像拉取网络故障修复
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.39ui03.asia/arts/341034.Doc

原标题：golang pprof 线上采集性能数据
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.39ui03.asia/arts/441726.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.39ui03.asia/arts/672080.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.39ui03.asia/arts/786282.Doc

原标题：golang prometheus 告警规则编写
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.39ui03.asia/arts/853947.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.39ui03.asia/arts/686601.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.39ui03.asia/arts/958930.Doc

原标题：golang goroutine 池任务调度
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.39ui03.asia/arts/310811.Doc

?

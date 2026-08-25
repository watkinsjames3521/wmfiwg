最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://zhishi.olotog.asia/blog/2138621.sHtML

原标题：浮点计算精度错误处理方案
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://zhishi.olotog.asia/blog/3551351.sHtML

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://zhishi.olotog.asia/blog/9075418.sHtML

原标题：灰度发布策略服务平滑升级
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://zhishi.olotog.asia/blog/7588624.sHtML

原标题：开发复盘：分布式会话共享多种方案实践
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://zhishi.olotog.asia/blog/2744728.sHtML

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://zhishi.olotog.asia/blog/8551967.sHtML

原标题：golang 系统设计线程协程泄露定位方法
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://zhishi.olotog.asia/blog/6895915.sHtML

原标题：golang redis 事务 multi exec 使用
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://zhishi.olotog.asia/blog/4649547.sHtML

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://zhishi.olotog.asia/blog/0289948.sHtML

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://zhishi.olotog.asia/blog/3962382.sHtML

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://zhishi.olotog.asia/blog/7248477.sHtML

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://zhishi.olotog.asia/blog/2028384.sHtML

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://zhishi.olotog.asia/blog/3640348.sHtML

原标题：后端登录鉴权模块完整开发
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://zhishi.olotog.asia/blog/7680677.sHtML

原标题：包管理器依赖缓存清理
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://zhishi.olotog.asia/blog/2389383.sHtML

原标题：热更新开发环境配置教程
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://zhishi.olotog.asia/blog/9610536.sHtML

原标题：全量回归测试提升代码质量
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://zhishi.olotog.asia/blog/0792566.sHtML

原标题：调优方案：服务实例扩容，水平扩展性能
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://zhishi.olotog.asia/blog/2890295.sHtML

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://zhishi.olotog.asia/blog/6836116.sHtML

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://zhishi.olotog.asia/blog/1165350.sHtML

原标题：golang 分库分表简单路由实现
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://zhishi.olotog.asia/blog/6259812.sHtML

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://zhishi.olotog.asia/blog/5361401.sHtML

原标题：Git 子模块更新代码不全修复
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://zhishi.olotog.asia/blog/0482276.sHtML

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://zhishi.olotog.asia/blog/1997845.sHtML

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://zhishi.olotog.asia/blog/1532251.sHtML

原标题：golang 系统设计 json 解析性能优化实操
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://zhishi.olotog.asia/blog/6559210.sHtML

原标题：浏览器内存泄漏排查前端页面
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://zhishi.olotog.asia/blog/4429896.sHtML

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://zhishi.olotog.asia/blog/3531383.sHtML

原标题：golang 系统设计多级缓存架构落地
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://zhishi.olotog.asia/blog/0843929.sHtML

原标题：golang mysql 读写分离简单实现
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://zhishi.olotog.asia/blog/8818759.sHtML

原标题：golang mysql 连接泄漏检测方法
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://zhishi.olotog.asia/blog/8075971.sHtML

原标题：新手教程：本地环境变量配置全流程
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://zhishi.olotog.asia/blog/0491865.sHtML

原标题：Security：反序列化漏洞风险识别与规避
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://zhishi.olotog.asia/blog/2497917.sHtML

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://zhishi.olotog.asia/blog/6161892.sHtML

原标题：方案设计：分布式分页查询架构难点处理
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://zhishi.olotog.asia/blog/0610928.sHtML

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://zhishi.olotog.asia/blog/7612396.sHtML

原标题：Security：Docker镜像安全扫描漏洞修复
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://zhishi.olotog.asia/blog/4163055.sHtML

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://zhishi.olotog.asia/blog/7595747.sHtML

原标题：代理 HTTPS 证书访问异常处理
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://zhishi.olotog.asia/blog/1207772.sHtML

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://zhishi.olotog.asia/blog/3094243.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计配置灰度下发简单实现思路
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://zhishi.olotog.asia/blog/2407509.sHtML

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://zhishi.olotog.asia/blog/2622276.sHtML

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://zhishi.olotog.asia/blog/3241469.sHtML

原标题：死信队列处理消息阻塞业务
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://zhishi.olotog.asia/blog/0753193.sHtML

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://zhishi.olotog.asia/blog/1392466.sHtML

原标题：HelloShell：入门常用shell脚本编写
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://zhishi.olotog.asia/blog/0569673.sHtML

原标题：OAuth2 第三方登录服务搭建
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://zhishi.olotog.asia/blog/0859113.sHtML

原标题：golang 互斥锁读写锁并发安全
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://zhishi.olotog.asia/blog/5388217.sHtML

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://zhishi.olotog.asia/blog/3435976.sHtML

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://zhishi.olotog.asia/blog/6777092.sHtML

原标题：快速入门：API接口调试完整实操步骤
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://zhishi.olotog.asia/blog/1119154.sHtML

原标题：跨平台 uniapp 多端开发实操
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://zhishi.olotog.asia/blog/0601454.sHtML

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://zhishi.olotog.asia/blog/8903544.sHtML

原标题：前端打包产物体积压缩优化
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://zhishi.olotog.asia/blog/7867651.sHtML

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://zhishi.olotog.asia/blog/9216143.sHtML

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://zhishi.olotog.asia/blog/5784669.sHtML

原标题：golang k8s liveness readiness 探针
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://zhishi.olotog.asia/blog/7323394.sHtML

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://zhishi.olotog.asia/blog/7227904.sHtML

原标题：Architecture：对象存储接入业务整体架构
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://zhishi.olotog.asia/blog/5234223.sHtML

原标题：golang 系统设计延迟队列业务实现
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://zhishi.olotog.asia/blog/1242533.sHtML

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://zhishi.olotog.asia/blog/6290498.sHtML

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://zhishi.olotog.asia/blog/9385501.sHtML

原标题：接口请求重试容错机制实现
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://zhishi.olotog.asia/blog/3683337.sHtML

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://zhishi.olotog.asia/blog/7149089.sHtML

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://zhishi.olotog.asia/blog/5047249.sHtML

原标题：golang minio 对象存储接口开发
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://zhishi.olotog.asia/blog/7961248.sHtML

原标题：数据库死锁成因规避方案
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://zhishi.olotog.asia/blog/6148054.sHtML

原标题：golang makefile 自动化构建脚本
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://zhishi.olotog.asia/blog/2489812.sHtML

原标题：Spring 事务传播机制配置生效
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://zhishi.olotog.asia/blog/2912576.sHtML

原标题：开发记录：接口请求日志记录完整中间件实现
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://zhishi.olotog.asia/blog/8284343.sHtML

原标题：golang docker compose 完整语法
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://zhishi.olotog.asia/blog/7627926.sHtML

原标题：项目依赖安全扫描漏洞防范
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://zhishi.olotog.asia/blog/5281197.sHtML

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://zhishi.olotog.asia/blog/0687879.sHtML

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://zhishi.olotog.asia/blog/7372069.sHtML

原标题：部署复盘：回滚策略，线上故障快速回退
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://zhishi.olotog.asia/blog/8739098.sHtML

原标题：定时任务重复执行分布式锁
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://zhishi.olotog.asia/blog/7901088.sHtML

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://zhishi.olotog.asia/blog/7818129.sHtML

原标题：项目实践：定时任务防重复执行落地实践
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://zhishi.olotog.asia/blog/6577707.sHtML

原标题：golang 日志与链路 ID 关联打印
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://zhishi.olotog.asia/blog/7147258.sHtML

原标题：golang http 请求重试封装工具
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://zhishi.olotog.asia/blog/2601675.sHtML

三、实战开发｜Practice
原标题：golang 系统设计分表 id 生成策略对比
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://zhishi.olotog.asia/blog/1787380.sHtML

原标题：golang kafka 消费者偏移量管理
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://zhishi.olotog.asia/blog/5983806.sHtML

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://zhishi.olotog.asia/blog/1888040.sHtML

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://zhishi.olotog.asia/blog/7544085.sHtML

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://zhishi.olotog.asia/blog/9365354.sHtML

原标题：golang 系统设计内存高占用排查思路
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://zhishi.olotog.asia/blog/0665661.sHtML

原标题：入门实践：Git分支创建切换合并完整演示
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://zhishi.olotog.asia/blog/3766911.sHtML

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://zhishi.olotog.asia/blog/1257626.sHtML

原标题：golang 开发环境快速搭建指南
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://zhishi.olotog.asia/blog/0205802.sHtML

原标题：golang 系统设计接口频率限制业务落地
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://zhishi.olotog.asia/blog/0295918.sHtML

原标题：golang 系统设计分布式事务几种方案
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://zhishi.olotog.asia/blog/8029405.sHtML

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://zhishi.olotog.asia/blog/8907940.sHtML

原标题：golang redis 发布订阅简单示例
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://zhishi.olotog.asia/blog/5397312.sHtML

原标题：快速入门OpenAPI文档生成基础实践
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://zhishi.olotog.asia/blog/2792844.sHtML

原标题：新手教程：本地项目初始化gitignore配置
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://zhishi.olotog.asia/blog/3217577.sHtML

原标题：golang kafka 消费者组原理讲解
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://zhishi.olotog.asia/blog/3575756.sHtML

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://zhishi.olotog.asia/blog/9134311.sHtML

原标题：TCP 心跳检测清理僵死连接
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://zhishi.olotog.asia/blog/4207572.sHtML

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://zhishi.olotog.asia/blog/7242478.sHtML

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://zhishi.olotog.asia/blog/7687464.sHtML

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://zhishi.olotog.asia/blog/0454786.sHtML

原标题：时间同步修复令牌提前过期
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://zhishi.olotog.asia/blog/6713414.sHtML

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://zhishi.olotog.asia/blog/3506244.sHtML

原标题：ICMP 放通网络丢包问题修复
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://zhishi.olotog.asia/blog/2656634.sHtML

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://zhishi.olotog.asia/blog/9623025.sHtML

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://zhishi.olotog.asia/blog/2308837.sHtML

原标题：golang 系统设计分布式会话方案对比
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://zhishi.olotog.asia/blog/9586539.sHtML

原标题：优化实践：读写分离分担主库查询压力
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://zhishi.olotog.asia/blog/8712242.sHtML

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://zhishi.olotog.asia/blog/4302878.sHtML

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://zhishi.olotog.asia/blog/6225339.sHtML

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://zhishi.olotog.asia/blog/4289619.sHtML

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://zhishi.olotog.asia/blog/5396767.sHtML

原标题：多线程线程安全脏数据规避
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://zhishi.olotog.asia/blog/9510293.sHtML

原标题：git rebase 整理提交历史实操
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://zhishi.olotog.asia/blog/3662438.sHtML

原标题：golang redis 发布订阅简单示例
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://zhishi.olotog.asia/blog/1610429.sHtML

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://zhishi.olotog.asia/blog/7406435.sHtML

原标题：golang 系统设计会话共享多实例部署
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://zhishi.olotog.asia/blog/2305862.sHtML

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://zhishi.olotog.asia/blog/2164554.sHtML

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://zhishi.olotog.asia/blog/6247738.sHtML

原标题：golang 链路 traceId 透传中间件
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://zhishi.olotog.asia/blog/8588729.sHtML

四、架构设计｜Architecture
原标题：图片上传预览格式大小处理
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://zhishi.olotog.asia/blog/4841619.sHtML

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://zhishi.olotog.asia/blog/8286341.sHtML

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://zhishi.olotog.asia/blog/2392593.sHtML

原标题：golang k8s configmap secret 配置
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://zhishi.olotog.asia/blog/2490435.sHtML

原标题：项目目录结构规范化最佳实践
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://zhishi.olotog.asia/blog/7550548.sHtML

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://zhishi.olotog.asia/blog/7565241.sHtML

原标题：容器资源限制防止宿主机过载
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://zhishi.olotog.asia/blog/0233610.sHtML

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://zhishi.olotog.asia/blog/0461723.sHtML

原标题：Practice：实现数据库事务消息最终一致性demo
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://zhishi.olotog.asia/blog/7108851.sHtML

原标题：golang docker 容器资源限制设置
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://zhishi.olotog.asia/blog/6838876.sHtML

原标题：DevOps：WSL2生产环境使用风险提示
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://zhishi.olotog.asia/blog/5418021.sHtML

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://zhishi.olotog.asia/blog/5438034.sHtML

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://zhishi.olotog.asia/blog/0946771.sHtML

原标题：RPC 报文大小上限调优大请求
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://zhishi.olotog.asia/blog/9723146.sHtML

原标题：golang 系统设计序列化性能选型对比
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://zhishi.olotog.asia/blog/7291295.sHtML

原标题：golang 表单文件大小限制配置
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://zhishi.olotog.asia/blog/7508312.sHtML

原标题：文件锁正确使用避免死锁
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://zhishi.olotog.asia/blog/2343909.sHtML

原标题：排错：前端缓存304异常更新不及时
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://zhishi.olotog.asia/blog/8380618.sHtML

?

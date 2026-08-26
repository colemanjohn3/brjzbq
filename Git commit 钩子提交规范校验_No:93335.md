最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Git commit 钩子提交规范校验
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.zpfbwd.asia/arts/773582.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/421214.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.zpfbwd.asia/arts/266043.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.zpfbwd.asia/arts/935500.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.zpfbwd.asia/arts/155814.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.zpfbwd.asia/arts/468917.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.zpfbwd.asia/arts/881459.Doc

原标题：golang redis 集群 hash 槽讲解
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.zpfbwd.asia/arts/907841.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.zpfbwd.asia/arts/318940.Doc

原标题：单元测试用例编写入门实操
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.zpfbwd.asia/arts/429588.Doc

原标题：开发环境变量配置全平台教程
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.zpfbwd.asia/arts/010154.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.zpfbwd.asia/arts/600677.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.zpfbwd.asia/arts/539296.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.zpfbwd.asia/arts/574774.Doc

原标题：跨库查询性能优化处理
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/135103.Doc

原标题：golang redis 缓存击穿防护实现
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.zpfbwd.asia/arts/598347.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.zpfbwd.asia/arts/039165.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.zpfbwd.asia/arts/011125.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.zpfbwd.asia/arts/105524.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.zpfbwd.asia/arts/761389.Doc

原标题：golang 文件上传下载接口开发
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.zpfbwd.asia/arts/630585.Doc

原标题：golang 告警推送钉钉机器人实现
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.zpfbwd.asia/arts/158928.Doc

原标题：golang csv 读写批量数据处理
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.zpfbwd.asia/arts/939099.Doc

原标题：golang 系统设计网关路由规则动态配置实现
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/685035.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/418137.Doc

原标题：代码模块化组件化拆分思路
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.zpfbwd.asia/arts/506927.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.zpfbwd.asia/arts/143923.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.zpfbwd.asia/arts/968645.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.zpfbwd.asia/arts/162325.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.zpfbwd.asia/arts/382161.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/268513.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.zpfbwd.asia/arts/788276.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.zpfbwd.asia/arts/188687.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.zpfbwd.asia/arts/303031.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.zpfbwd.asia/arts/826262.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.zpfbwd.asia/arts/343997.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.zpfbwd.asia/arts/188475.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.zpfbwd.asia/arts/326923.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.zpfbwd.asia/arts/877790.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/142834.Doc


二、踩坑排错｜Troubleshooting
原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.zpfbwd.asia/arts/996909.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.zpfbwd.asia/arts/529248.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.zpfbwd.asia/arts/057250.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.zpfbwd.asia/arts/727131.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.zpfbwd.asia/arts/005177.Doc

原标题：Spring 事务传播机制配置生效
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.zpfbwd.asia/arts/782707.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.zpfbwd.asia/arts/947704.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.zpfbwd.asia/arts/151529.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.zpfbwd.asia/arts/267775.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/507756.Doc

原标题：极简方式搭建个人技术文档站点
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.zpfbwd.asia/arts/350335.Doc

原标题：golang prometheus counter gauge 使用
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.zpfbwd.asia/arts/718432.Doc

原标题：依赖安装失败全方位排错
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.zpfbwd.asia/arts/649291.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.zpfbwd.asia/arts/687702.Doc

原标题：CI 构建缓存加速编译速度
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.zpfbwd.asia/arts/617749.Doc

原标题：容器资源限制防止宿主机过载
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.zpfbwd.asia/arts/436993.Doc

原标题：WSL 文件权限访问异常修复
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.zpfbwd.asia/arts/345941.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.zpfbwd.asia/arts/041383.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.zpfbwd.asia/arts/784575.Doc

原标题：包管理器依赖冲突解决方案
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.zpfbwd.asia/arts/895959.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.zpfbwd.asia/arts/303600.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.zpfbwd.asia/arts/399062.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.zpfbwd.asia/arts/314221.Doc

原标题：调试工具断点调试变量查看技巧
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.zpfbwd.asia/arts/401409.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.zpfbwd.asia/arts/495350.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.zpfbwd.asia/arts/936046.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.zpfbwd.asia/arts/641925.Doc

原标题：golang mysql 事务回滚异常处理
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.zpfbwd.asia/arts/192706.Doc

原标题：golang 分布式上下文传递方案
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.zpfbwd.asia/arts/219563.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.zpfbwd.asia/arts/053621.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.zpfbwd.asia/arts/914232.Doc

原标题：全平台系统环境变量配置
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.zpfbwd.asia/arts/573959.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.zpfbwd.asia/arts/103111.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.zpfbwd.asia/arts/577556.Doc

原标题：空指针异常判空容错处理
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.zpfbwd.asia/arts/575598.Doc

原标题：golang cpu pprof 性能分析实操
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.zpfbwd.asia/arts/924217.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.zpfbwd.asia/arts/457347.Doc

原标题：零基础理解读写分离基础思想
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.zpfbwd.asia/arts/381229.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/554713.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.zpfbwd.asia/arts/251135.Doc

三、实战开发｜Practice
原标题：golang k8s 资源请求限制配置
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.zpfbwd.asia/arts/656517.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.zpfbwd.asia/arts/817524.Doc

原标题：golang redis 位图用户签到统计
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.zpfbwd.asia/arts/023824.Doc

原标题：golang mongodb 事务多文档使用
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.zpfbwd.asia/arts/370830.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.zpfbwd.asia/arts/374689.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.zpfbwd.asia/arts/201819.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.zpfbwd.asia/arts/814609.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.zpfbwd.asia/arts/740047.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.zpfbwd.asia/arts/051486.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.zpfbwd.asia/arts/306223.Doc

原标题：Git 分支切换合并删除完整操作
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.zpfbwd.asia/arts/286298.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.zpfbwd.asia/arts/188669.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/679473.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.zpfbwd.asia/arts/307621.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/595436.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.zpfbwd.asia/arts/993835.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.zpfbwd.asia/arts/482990.Doc

原标题：golang 优雅处理数据库事务
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.zpfbwd.asia/arts/704307.Doc

原标题：快速入门消息通知简单实现方案
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.zpfbwd.asia/arts/420338.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.zpfbwd.asia/arts/387433.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/990647.Doc

原标题：前端工程化 webpack 打包优化
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.zpfbwd.asia/arts/071746.Doc

原标题：Redis 分布式锁高并发安全实现
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.zpfbwd.asia/arts/597958.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.zpfbwd.asia/arts/998188.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.zpfbwd.asia/arts/530887.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.zpfbwd.asia/arts/207111.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.zpfbwd.asia/arts/731920.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.zpfbwd.asia/arts/357759.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.zpfbwd.asia/arts/315137.Doc

原标题：golang 静态编译缩小镜像体积
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/021735.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.zpfbwd.asia/arts/536850.Doc

原标题：golang makefile 自动化构建脚本
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.zpfbwd.asia/arts/932141.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.zpfbwd.asia/arts/292168.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.zpfbwd.asia/arts/272469.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.zpfbwd.asia/arts/250925.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.zpfbwd.asia/arts/329538.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.zpfbwd.asia/arts/388324.Doc

原标题：golang toml 配置文件解析教程
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.zpfbwd.asia/arts/417757.Doc

原标题：快速入门消息通知简单实现方案
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.zpfbwd.asia/arts/786732.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.zpfbwd.asia/arts/824339.Doc

四、架构设计｜Architecture
原标题：golang es 批量 bulk 操作性能调优
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.zpfbwd.asia/arts/518667.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.zpfbwd.asia/arts/533494.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.zpfbwd.asia/arts/646046.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.zpfbwd.asia/arts/326958.Doc

原标题：golang pprof 线上采集性能数据
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.zpfbwd.asia/arts/808050.Doc

原标题：浏览器缓存强制刷新方案
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.zpfbwd.asia/arts/745001.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.zpfbwd.asia/arts/264316.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.zpfbwd.asia/arts/369807.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.zpfbwd.asia/arts/787539.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.zpfbwd.asia/arts/818295.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.zpfbwd.asia/arts/276106.Doc

原标题：golang consul 健康检查服务注册
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.zpfbwd.asia/arts/779366.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.zpfbwd.asia/arts/026593.Doc

原标题：golang excel 简单读写操作示例
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.zpfbwd.asia/arts/946285.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.zpfbwd.asia/arts/155894.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.zpfbwd.asia/arts/642710.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.zpfbwd.asia/arts/430540.Doc

原标题：线程调度优化减少上下文切换
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.zpfbwd.asia/arts/048066.Doc

?

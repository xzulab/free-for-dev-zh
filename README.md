# free-for.dev

> 中文版整理自 [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev)，用于中文读者浏览开发者免费资源。

开发人员和开源作者现在有许多提供免费套餐的服务，但找到所有这些服务需要时间才能做出明智的决定。

这是具有免费开发者级别的软件(SaaS、PaaS、IaaS 等)和其他产品的列表。

此特定列表的范围仅限于基础设施开发人员(系统管理员、DevOps 从业人员等)可能会发现有用的内容。我们喜欢所有的免费服务，但最好保持主题。有时这是一条灰线，所以这是固执己见的；如果我不接受您的贡献，请不要感到被冒犯。

此列表源自 Pull Request、评论、想法和 1600 多人完成的工作。您还可以通过发送[Pull Requests](https://github.com/ripienaar/free-for-dev)来添加更多服务或删除其产品已更改或停用的服务。

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

**注意**：此列表仅适用于即服务产品，不适用于自托管软件。为了符合资格，服务必须提供免费套餐，而不仅仅是免费试用。如果有时间限制，免费套餐必须至少持续一年。我们还从安全角度考虑免费套餐，因此 SSO 很好，但我不会接受将 TLS 限制为仅限付费层的服务。

<a id="table-of-contents"></a>
# 目录

  * [主要云服务商的永久免费额度](#major-cloud-providers)
  * [云管理解决方案](#cloud-management-solutions)
  * [分析、事件和统计](#analytics-events-and-statistics)
  * [API、数据和机器学习](#apis-data-and-ml)
  * [制品仓库](#artifact-repos)
  * [BaaS](#baas)
  * [低代码平台](#low-code-platform)
  * [CDN 和防护](#cdn-and-protection)
  * [CI/CD](#ci-and-cd)
  * [CMS](#cms)
  * [代码生成](#code-generation)
  * [代码质量](#code-quality)
  * [代码搜索和浏览](#code-search-and-browsing)
  * [崩溃和异常处理](#crash-and-exception-handling)
  * [地图数据可视化](#data-visualization-on-maps)
  * [托管数据服务](#managed-data-services)
  * [设计和 UI](#design-and-ui)
  * [开发者博客平台](#dev-blogging-sites)
  * [DNS](#dns)
  * [Docker 相关](#docker-related)
  * [域名](#domain)
  * [教育和职业发展](#education-and-career-development)
  * [电子邮件](#email)
  * [功能开关管理平台](#feature-toggles-management-platforms)
  * [字体](#font)
  * [表单](#forms)
  * [生成式 AI](#generative-ai)
  * [IaaS](#iaas)
  * [IDE 和代码编辑](#ide-and-code-editing)
  * [国际手机号验证 API 和 SDK](#international-mobile-number-verification-api-and-sdk)
  * [问题跟踪和项目管理](#issue-tracking-and-project-management)
  * [日志管理](#log-management)
  * [移动应用分发和反馈](#mobile-app-distribution-and-feedback)
  * [管理系统](#management-system)
  * [消息和流处理](#messaging-and-streaming)
  * [杂项](#miscellaneous)
  * [监控](#monitoring)
  * [PaaS](#paas)
  * [包构建系统](#package-build-system)
  * [支付和账单集成](#payment-and-billing-integration)
  * [隐私管理](#privacy-management)
  * [截图 API](#screenshot-apis)
  * [Flutter 相关和无需 Mac 构建 iOS 应用](#flutter-related-and-building-ios-apps-without-mac)
  * [搜索](#search)
  * [安全和 PKI](#security-and-pki)
  * [认证、授权和用户管理](#authentication-authorization-and-user-management)
  * [源代码仓库](#source-code-repos)
  * [存储和媒体处理](#storage-and-media-processing)
  * [隧道、WebRTC、WebSocket 服务器和其他路由器](#tunneling-webrtc-web-socket-servers-and-other-routers)
  * [测试](#testing)
  * [团队和协作工具](#tools-for-teams-and-collaboration)
  * [翻译管理](#translation-management)
  * [访客会话录制](#visitor-session-recording)
  * [Web 托管](#web-hosting)
  * [评论平台](#commenting-platforms)
  * [基于浏览器的硬件仿真](#browser-based-hardware-emulation-written-in-javascript)
  * [远程桌面工具](#remote-desktop-tools)
  * [其他免费资源](#other-free-resources)

<a id="major-cloud-providers"></a>
## 主要云服务商

  * [谷歌云平台](https://cloud.google.com)
    * App Engine - /天 28 小时前端实例，/天 9 小时后端实例
    * Cloud Firestore - 1GB 存储，/天 50,000 次读取、20,000 次写入、20,000 次删除
    * Compute Engine - /月 1 个非抢占式 e2-micro、30GB HDD、5GB 快照存储(仅限某些区域)、从北美到所有区域目的地(不包括中国和澳大利亚)的 1 GB 网络出站流量
    * Cloud Storage - 5GB、1GB 网络出口
    * Cloud Shell - 基于 Web 的 Linux shell/主 IDE，具有 5GB 持久存储。/周限制 60 小时
    * Cloud Pub/Sub - /月 10GB 消息
    * Cloud Functions - /月 200 万次调用(包括后台调用和 HTTP 调用)
    * Cloud Run - /月 200 万个请求、360,000 GB 秒内存、180,000 vCPU 秒计算时间、/月来自北美的 1 GB 网络出站流量
    * Google Kubernetes Engine - 一个可用区集群无需缴纳集群管理费。每个用户节点均按标准 Compute Engine 定价收费
    * BigQuery - /月 1 TB 查询，/月 10 GB 存储
    * Cloud Build - /天 120 分钟构建时间
    * [Google Colab](https://colab.research.google.com/) - 免费的 Jupyter Notebooks 开发环境。
    * [Kaggle](https://www.kaggle.com/) - 具有 4 个 CPU 核心和 30 GB RAM 计算环境的 Jupyter 笔记本，没有任何/周使用限制。通过电话号码验证，可以免费添加 1 个 Nvidia Tesla P100 GPU 或 2 个 Nvidia Tesla T4 GPU，使用限制为/周 30 个 GPU 小时。通过身份验证 - 1 个具有 96 个 CPU 核心和 330 GB RAM 的 TPU v3-8 免费提供，使用限制为/周 20 小时。检查[Technical Specifications](https://www.kaggle.com/docs/notebooks#technical-specifications)了解更多详细信息。
    * [ChromeRemoteDesktop](https://remotedesktop.google.com/) - 免费的远程桌面应用程序，几乎没有设备数量限制，归 Google 所有，因此需要一个 Google 帐户。
    * [Google Gemini API](https://ai.google.dev/) - 免费使用 Gemini 1.5 Pro 和 Gemini 1.5 Flash 型号。免费套餐每分钟提供 15 个请求，/天 1,500 个请求，每分钟 100 万个代币。
    * 完整详细列表 - https://cloud.google.com/free

  * [亚马逊网络服务](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - /月 1TB 出站流量和/月 2M 函数调用
    * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 10 个自定义指标和 10 个警报
    * [CodeBuild](https://aws.amazon.com/codebuild/) - /月 100 分钟的构建时间
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 5 个活跃用户、50GB 存储空间和/月 10000 个请求
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - /月 1 个活跃管道
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL 数据库
    * [EC2](https://aws.amazon.com/ec2/) - /月 750 小时 t2.micro 或 t3.micro(12 个月)。/月 100GB 出站流量
    * [EBS](https://aws.amazon.com/ebs/) - /月 30GB 通用 (SSD) 或磁性 (12mo)
    * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - /月 750 小时(12mo)
    * [RDS](https://aws.amazon.com/rds/) - /月 750 小时的 db.t2.micro、db.t3.micro 或 db.t4g.micro、20GB 通用 (SSD) 存储、20GB 存储备份(12 个月)
    * [S3](https://aws.amazon.com/s3/) - 5GB 标准对象存储，20K Get 请求和 2K Put 请求(12 个月)
    * [Glacier](https://aws.amazon.com/glacier/) - 10GB 长期对象存储
    * [Lambda](https://aws.amazon.com/lambda/) - /月 100 万个请求
    * [SNS](https://aws.amazon.com/sns/) - /月发布 100 万篇
    * [SES](https://aws.amazon.com/ses/) - /月 3.000 条消息(12 个月)
    * [SQS](https://aws.amazon.com/sqs/) - 100 万个消息队列请求
    * 完整详细列表 - https://aws.amazon.com/free/

  * [微软Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 个 B1S Linux 虚拟机、1 个 B1S Windows 虚拟机 (12mo)
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 个 Web、移动或 API 应用程序(60 CPU 分钟/天)
    * [Functions](https://azure.microsoft.com/services/functions/) - /月 100 万个请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 实现快速、简单且精益的开发测试环境
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 个对象
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - /月存储 50,000 个用户
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 个活跃用户，无限的私人 Git 存储库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) - 10 个免费并行作业，时间不限，适用于 Linux、macOS 和 Windows 的开源软件
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - /天 8,000 条消息
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 个免费公共负载均衡 IP (VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100 万条推送通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - /月 15GB 入站(12 个月)和 5GB 出站
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 25GB 存储和 1000 RU 的预配置吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) - 使用免费 SSL、身份验证/授权和自定义域构建、部署和托管静态应用程序和无服务器功能
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS 文件或 Blob 存储(12 个月)
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API(计算机视觉、翻译器、人脸检测、机器人等)，提供免费套餐，包括有限的交易
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - 基于人工智能的搜索和索引服务，免费提供 10,000 个文档
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 托管 Kubernetes 服务，免费集群管理
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 10 万次操作/月
    * 完整详细列表 - https://azure.microsoft.com/free/

  * [甲骨文云](https://www.oracle.com/cloud/)
    * 计算
       - 2 个基于 AMD 的计算虚拟机，每个虚拟机具有 1/8 OCPU 和 1 GB 内存
       - 2 个基于 Arm 的 Ampere A1 内核和 12 GB 内存，可用作一台虚拟机或最多 2 台虚拟机
       - 当[deemed idle](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)时实例将被回收
    * Block Volume - 2 个卷，总计 200 GB(用于计算)
    * Object Storage - 10GB
    * Load balancer - 1 个 10 Mbps 实例
    * Databases - 2 个 DB，每个 20 GB
    * Monitoring - 5 亿个摄取数据点、10 亿个检索数据点
    * Bandwidth - /月 10 TB 出站流量，基于 x64 的 VM 上的速度限制为 50 Mbps，基于 ARM 的 VM 上的速度限制为 500 Mbps * 核心数
    * Public IP - 2 个 IPv4 用于虚拟机，1 个 IPv4 用于负载均衡器
    * Notifications - /月 100 万个递送选项，/月发送 1000 封电子邮件
    * 完整详细列表 - https://www.oracle.com/cloud/free/

  * [IBM 云](https://www.ibm.com/cloud/free/)
    * Cloudant database - 1 GB 数据存储
    * Db2 database - 100MB 数据存储
    * API Connect - /月 50,000 次 API 调用
    * Availability Monitoring - /月 300 万个数据点
    * Log Analysis - 500MB 每日日志
    * 完整详细列表 - https://www.ibm.com/cloud/free/

  * [云耀](https://www.cloudflare.com/)
    * [Application Services](https://www.cloudflare.com/plans/) - 适用于无限数量域名的免费 DNS、DDoS 防护、CDN 以及免费 SSL、防火墙规则和页面规则、WAF、机器人缓解、免费不限流量限制 - 每个域 1 条规则、分析、电子邮件转发
    * [Zero Trust & SASE](https://www.cloudflare.com/plans/zero-trust-services/) - 最多 50 个用户、24 小时活动记录、三个网络位置
    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) -  您可以使用[Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/)通过隧道将本地运行的 HTTP 端口公开到 trycloudflare.com 上的随机子域，无需帐户。[Zero Trust](https://www.cloudflare.com/products/zero-trust/)免费计划中的更多功能(TCP 隧道、负载平衡、VPN)。
    * [Workers](https://developers.cloudflare.com/workers/) - 在 Cloudflare 的全球网络上免费部署无服务器代码 - 每日 10 万个请求。
    * [Workers KV](https://developers.cloudflare.com/kv) - /天 10 万个读取请求、/天 1000 个写入请求、/天 1000 个删除请求、/天 1000 个列表请求、1 GB 存储数据
    * [R2](https://developers.cloudflare.com/r2/) - /月 10 GB、/月 100 万次 A 类操作、/月 1000 万次 B 类操作
    * [D1](https://developers.cloudflare.com/d1/) - /天读取 500 万行，/天写入 10 万行，1 GB 存储
    * [Pages](https://developers.cloudflare.com/pages/) - 在 Cloudflare 快速、安全的全球网络上开发和部署您的 Web 应用程序。 500 个/月构建、100 个自定义域、集成 SSL、无限访问席位、无限预览部署以及通过 Cloudflare Workers 集成实现的全堆栈功能。
    * [Queues](https://developers.cloudflare.com/queues/) - /月 100 万次操作
    * [TURN](https://developers.cloudflare.com/calls/turn/) - /月 1TB 免费(传出)流量。

  * [Zoho](https://www.zoho.com) - 最初是一家电子邮件提供商，但现在提供一套服务，其中一些有免费计划。具有免费计划的服务列表：
    * [Catalyst by Zoho](https://catalyst.zoho.com) - PaaS/全栈云平台，具有慷慨的 [免费套餐](https://catalyst.zoho.com/free-tier.html)
    * [Zoho Apptics](https://www.zoho.com/apptics/) - 统一且可操作的产品分析，可通过慷慨的永久免费计划来监控性能、分析用户行为并收集移动、网络和桌面应用程序的反馈。
    * [Email](https://zoho.com/mail)5 位用户免费。 5 GB/用户和 25 MB 附件限制，一个域。
    * [Zoho Assist](https://www.zoho.com/assist) - Zoho Assist 的永久免费计划包括一份并发远程支持许可证和无限期访问 5 个无人值守计算机许可证，可供专业人士和个人使用。
    * [Sprints](https://zoho.com/sprints)免费供 5 个用户、5 个项目和 500MB 存储空间。
    * [Docs](https://zoho.com/docs) - 5 位用户免费，上传限制为 1 GB，存储空间为 5 GB。 Zoho Office 套件(Writer、Sheets 和 Show)捆绑提供。
    * [Projects](https://zoho.com/projects) - 免费供 3 个用户、2 个项目和 10 MB 附件限制。同样的计划适用于[Bugtracker](https://zoho.com/bugtracker)。
    * [Connect](https://zoho.com/connect) - 免费为 25 位用户提供团队协作，包括三个小组、三个自定义应用程序、3 个看板、3 个手册和 10 个集成以及频道、活动和论坛。
    * [Meeting](https://zoho.com/meeting) - 最多可容纳 3 名会议参与者和 10 名网络研讨会参与者的会议。
    * [Vault](https://zoho.com/vault) - 个人可以访问密码管理。
    * [Showtime](https://zoho.com/showtime) - 另一款会议软件，用于培训最多 5 名与会者的远程会议。
    * [Notebook](https://zoho.com/notebook) - Evernote 的免费替代品。
    * [Wiki](https://zoho.com/wiki) - 三个用户免费，拥有 50 MB 存储空间、无限页面、zip 备份、RSS 和 Atom 提要、访问控制和可自定义 CSS。
    * [Subscriptions](https://zoho.com/subscriptions) - 为 20 个客户/订阅和 1 个用户免费提供定期账单管理，所有付款托管均由 Zoho 完成。存储最后 40 个订阅指标
    * [Checkout](https://zoho.com/checkout) - 产品账单管理包含 3 个页面和最多 50 笔付款。
    * [Desk](https://zoho.com/desk) - 具有三个代理、私人知识库和电子邮件票证的客户支持管理。与[Assist](https://zoho.com/assist)集成，适用于一名远程技术人员和 5 台无人值守计算机。
    * [Cliq](https://zoho.com/cliq) - 团队聊天软件，具有 100 GB 存储空间、无限用户、每个频道 100 个用户和 SSO。
    * [Campaigns](https://zoho.com/campaigns) - 电子邮件营销
    * [Forms](https://zoho.com/forms) - 表单创建者
    * [Sign](https://zoho.com/sign) - 无纸化签名
    * [Surveys](https://zoho.com/surveys) - 在线调查
     * [Bookings](https://zoho.com/bookings) - 预约安排

**[⬆️ 返回顶部](#table-of-contents)**

<a id="cloud-management-solutions"></a>
## 云管理解决方案

  * [Brainboard](https://www.brainboard.co) - 用于端到端可视化构建和管理云基础设施的协作解决方案。
  * [Cloud 66](https://www.cloud66.com/) - Cloud 66 免费用于个人项目(包括一台部署服务器、一个静态站点)，为您提供在任何云上构建、部署和扩展应用程序所需的一切，而无需担心“服务器问题”。
  * [deployment.io](https://deployment.io) - Deployment.io 帮助开发人员在 AWS 上实现自动化部署。在我们的免费套餐中，开发人员(单个用户)可以部署无限的静态站点、Web 服务和环境。我们/月免费提供 10 个作业执行，免费套餐中包含预览和自动部署。
  * [Pulumi](https://www.pulumi.com/) - 现代基础设施即代码平台，允许您使用熟悉的编程语言和工具来构建、部署和管理云基础设施。
  * [scalr.com](https://scalr.com/) - Scalr 是一款 Terraform 自动化和协作 (TACO) 产品，用于在 Terraform 管理的基础设施和配置上更好地协作和自动化。完整的 Terraform CLI 支持、OPA 集成和分层配置模型。没有 SSO 税。所有功能均包含在内。/月最多免费运行 50 次。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="source-code-repos"></a>
## 源代码仓库

  * [Bitbucket](https://bitbucket.org/) - 通过 CI/CD 管道为最多 5 个用户提供无限制的公共和私有 Git 存储库
  * [Codeberg](https://codeberg.org/) - 用于免费和开源项目的无限公共和私人 Git 存储库(具有无限合作者)。由[Forgejo](https://forgejo.org/)提供支持。使用[Codeberg Pages](https://codeberg.page/)托管静态网站。使用[Codeberg's CI](https://docs.codeberg.org/ci/)托管 CI/CD。使用[Codeberg Translate](https://translate.codeberg.org/)翻译托管。包括包和容器托管、项目管理和问题跟踪
  * [framagit.org](https://framagit.org/) - Framagit 是 Framasoft 基于 Gitlab 软件打造的软件，包括 CI、静态页面、项目页面和问题跟踪。
  * [GitGud](https://gitgud.io) - 无限的私人和公共存储库。永远免费。由 GitLab 和 Sapphire 提供支持。包括 CI/CD、静态托管、容器注册表、项目管理和问题跟踪。
  * [GitHub](https://github.com/) - 无限的公共存储库和无限的私有存储库(具有无限的协作者)。包括 CI/CD、开发环境、静态托管、包和容器托管、项目管理和 AI Copilot
  * [gitlab.com](https://about.gitlab.com/) - 无限的公共和私人 Git 存储库，最多可容纳 5 名协作者。包括 CI/CD、静态托管、容器注册表、项目管理和问题跟踪
  * [heptapod.net](https://foss.heptapod.net/) - Heptapod 是 GitLab 社区版的友好分支，为 Mercurial 提供支持
  * [pijul.com](https://pijul.com/) - 无限制的免费开源分布式版本控制系统。它的显着特点是基于健全的补丁理论，这使得它易于学习、使用和分发。解决了git/hg/svn/darcs的很多问题。
  * [projectlocker.com](https://projectlocker.com) - 一个免费的私人项目(Git 和 Subversion)，空间为 50 MB
  * [RocketGit](https://rocketgit.com) - 基于 Git 的存储库托管。无限的公共和私人存储库。
  * [savannah.gnu.org](https://savannah.gnu.org/) - 用作免费软件项目(针对 GNU 项目)的协作软件开发管理系统
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 用作免费软件项目(针对非 GNU 项目)的协作软件开发管理系统

**[⬆️ 返回顶部](#table-of-contents)**

<a id="apis-data-and-ml"></a>
## API、数据和机器学习

  * [Abstract API](https://www.abstractapi.com) - 适用于各种用例的 API 套件，包括 IP 地理定位、电话号码验证或电子邮件验证。
  * [Apify](https://www.apify.com/) - 网络抓取和自动化平台，可为任何网站创建 API 并提取数据。现成的抓取工具、集成代理和定制解决方案。免费计划，/月包含 5 美元的平台积分。
  * [APITemplate.io](https://apitemplate.io) - 使用简单的 API 或 Zapier 和 Airtable 等自动化工具自动生成图像和 PDF 文档。不需要 CSS/HTML。免费计划包含/月 50 张图像和三个模板。
  * [APIVerve](https://apiverve.com) - 免费即时访问超过 120 多个 API，这些 API 在构建时充分考虑了质量、一致性和可靠性。免费计划/月最多包含 50 个 API 令牌。 (可能已被删除，2025-06-25)
  * [Arize AI](https://arize.com/) - 用于模型监控和数据质量和性能漂移等根本问题的机器学习可观察性。最多可免费使用两个模型。
  * [Beeceptor](https://beeceptor.com) - 用于模拟和调试多协议 API(REST、SOAP、gRPC 和 GraphQL)的无代码、基于云的平台，为即时服务器提供基于规则的逻辑、CRUD 和状态模拟、代理和 CORS 管理，以实现更快的集成和测试。免费计划包括/天 50 个请求，并提供公共仪表板/端点，任何知道仪表板 URL 的人都可以在其中查看提交的请求和响应。
  * [BigDataCloud](https://www.bigdatacloud.com/) - 为现代网络提供快速、准确且免费(无限制或高达 10K-50K/月)的 API，例如 IP 地理定位、反向地理编码、网络洞察、电子邮件和电话验证、客户信息等。
  * [Browse AI](https://www.browse.ai) - 在网络上提取和监控数据。/月 1k 个免费积分，相当于 1k 个并发请求。
  * [BrowserCat](https://www.browsercat.com) - 用于自动化、抓取、AI 代理 Web 访问、图像/pdf 生成等的无头浏览器 API。免费计划，/月 1000 个请求。
  * [Calendarific](https://calendarific.com) - 面向 200 多个国家/地区的企业级公共假期 API 服务。免费计划包括/月 500 次通话。
  * [Canopy](https://www.canopyapi.co/) - 适用于 Amazon.com 产品、搜索和类别数据的 GraphQL API。免费计划包括/月 100 次通话。
  * [CarAPI.dev](https://carapi.dev) - 全面的汽车数据 API，具有 VIN 解码、被盗车辆检查、车辆估价、检查数据等。免费套餐包括/月跨所有 9 个端点的 100 个请求。
  * [CatchDoms](https://catchdoms.com) - 来自 16 个市场的过期和删除域名列表的聚合器，具有 SEO 丰富功能(反向链接、信任流、Wayback 历史记录)和质量评分。免费计划：10 个解锁列表、5 个收藏夹、3 个已保存搜索。注册后可享受 7 天 Pro 试用版，包括完整的 REST API 和 MCP 服务器访问权限。
  * [Cloudmersive](https://cloudmersive.com/) - 实用 API 平台，可完全访问扩展的 API 库，包括文档转换、病毒扫描等，/月调用 600 次，仅限北美可用区，最大文件大小 2.5MB。
  * [Colaboratory](https://colab.research.google.com) - 配备 Nvidia Tesla K80 GPU 的免费基于 Web 的 Python 笔记本环境。
  * [CometML](https://www.comet.com/site/) - MLOps 平台用于实验跟踪、模型生产管理、模型注册和完整的数据沿袭，涵盖从培训到生产的工作流程。对个人和学者免费。
  * [Commerce Layer](https://commercelayer.io) - 可组合的商务 API，可以从任何前端构建、下达和管理订单。开发者计划允许/月 100 个订单和最多 1,000 个 SKU 免费。
  * [Composio](https://composio.dev/) - 人工智能代理和 LLM 的集成平台。跨代理互联网集成 200 多种工具。
  * [Conversion Tools](https://conversiontools.io/) - 适用于文档、图像、视频、音频和电子书的在线文件转换器。 REST API 可用。 Node.js、PHP、Python 的库。支持最大 50 GB 的文件(对于付费计划)。免费套餐受文件大小 (20MB) 和转换次数(30/天、300/月)的限制。
  * [Country-State-City Microservice API](https://country-state-city.rebuscando.info/) - API和微服务提供广泛的信息，包括国家、地区、省份、城市、邮政编码等等。免费套餐/天最多包含 100 个请求。
  * [Coupler](https://www.coupler.io/) - 在应用程序之间同步的数据集成工具。它可以创建实时仪表板和报告、转换和操作值以及收集和备份见解。免费计划仅限于一名用户、数据连接、数据源和数据目标。还需要手动刷新数据。
  * [CraftMyPDF](https://craftmypdf.com) - 使用拖放式编辑器和简单的 API，从可重复使用的模板自动生成 PDF 文档。免费计划包含/月 100 个 PDF 和三个模板。
  * [Cube](https://cube.dev/) - Cube 帮助数据工程师和应用程序开发人员从现代数据存储中访问数据，将其组织成一致的定义，并将其交付给每个应用程序。使用 Cube 的最快方法是使用 Cube Cloud，它的免费套餐仅限/天 1,000 次查询。
  * [CurlHub](https://curlhub.io) - 用于检查和调试 API 调用的代理服务。免费计划包括/月 10,000 个请求。
  * [CurrencyScoop](https://currencyscoop.com) - 用于金融科技应用程序的实时货币数据 API。免费计划包括/月 5,000 次通话。
  * [CustomJS](https://www.customjs.io) - HTML 到 PDF 或 PDF 到 PNG/文本和 PDF 合并/提取/合并 API。免费套餐/月有 600 个呼叫。
  * [Data Fetcher](https://datafetcher.com) - 无需代码即可将 Airtable 连接到任何应用程序或 API。用于在 Airtable 中运行 API 请求的类似 Postman 的接口。与数十个应用程序预先构建的集成。免费计划包括/月 100 次运行。
  * [Data Miner](https://dataminer.io/) - 用于从网页 CSV 或 Excel 提取数据的浏览器扩展程序(Google Chrome、MS Edge)。免费计划/月为您提供 500 页。
  * [Dataimporter.io](https://www.dataimporter.io) - 用于连接、清理数据并将其导入 Salesforce 的工具。免费计划/月最多包含 20,000 条记录。
  * [Datalore](https://datalore.jetbrains.com) - Jetbrains 的 Python 笔记本。包括 10 GB 存储空间和/月 120 小时的运行时间。
  * [DB Designer](https://www.dbdesigner.net/) - 基于云的数据库架构设计和建模工具，提供 2 个数据库模型和每个模型 10 个表的免费入门计划。
  * [DB-IP](https://db-ip.com/api/free) - 免费的 IP 地理定位 API，每个 IP /天 1k 请求。CC-BY 4.0 许可证下的 Lite 数据库也是免费的。
  * [DeepAR](https://developer.deepar.ai) - 具有一个 SDK 的适用于任何平台的增强现实面部滤镜。免费计划提供最多 10 个/月活跃用户 (MAU) 并跟踪最多 4 个面孔
  * [Deepnote](https://deepnote.com) - 新的数据科学笔记本。 Jupyter兼容实时协作并在云端运行。免费套餐包括无限个个人项目、无限个具有 5GB RAM 和 2vCPU 的基本机器，以及最多 3 名编辑的团队。
  * [Compare JSON](https://comparejson.com) - 一个在线比较两种JSON数据结构差异的工具，帮助您快速定位JSON数据的差异。
  * [Disease.sh](https://disease.sh/) - 一个免费的 API，为构建 Covid-19 相关的有用应用程序提供准确的数据。
  * [Doczilla](https://www.doczilla.app/) - SaaS API 支持直接从 HTML/CSS/JS 代码生成屏幕截图或 PDF。免费计划/月允许 250 个文档。
  * [Doppio](https://doppio.sh/) - 托管 API 使用顶级渲染技术生成和私密存储 PDF 和屏幕截图。免费计划/月允许 400 个 PDF 和屏幕截图。
  * [Doqlo](https://doqlo.com/) - 使用 Web 应用程序或公共 API 从 CSV 批量填写和邮件合并 PDF 表单。免费计划包括/月 100 个 PDF 输出。
  * [drawDB](https://drawdb.app/) - 免费开源在线数据库图表编辑器，无需注册。
  * [DynamicDocs](https://advicement.io) - 基于 LaTeX 模板，使用 JSON to PDF API 生成 PDF 文档。免费计划允许/月 50 次 API 调用并访问模板库。
  * [Earnings Feed](https://earningsfeed.com/api) - 实时 SEC 备案、内幕交易和机构持股 API。免费套餐包括每分钟 15 个请求。
  * [Export SDK](https://exportsdk.com) - PDF 生成器 API 带有拖放模板编辑器，提供 SDK 和无代码集成。免费计划包含 250 个/月页面、无限用户和三个模板。
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免费的基于 Web 的 HTTP 客户端，用于发送 HTTP 请求。
  * [Financial Data](https://financialdata.net/) - 股票市场和金融数据API。免费计划/天允许 300 个请求。
  * [Firecrawl](https://www.firecrawl.dev/) - 用于抓取网站并将其转换为干净的、LLM 就绪的 markdown 或结构化数据的 API，处理 JavaScript 渲染、代理和速率限制。免费计划包括/月 1,000 个积分，无需信用卡。
  * [FormatJSONOnline.com](https://formatjsononline.com) - 一款基于浏览器的免费工具，可立即格式化、验证、比较和缩小 JSON 数据。
  * [FraudLabs Pro](https://www.fraudlabspro.com) - 筛查订单交易是否存在信用卡付款欺诈行为。该 REST API 将根据订单的输入参数检测所有可能的欺诈特征。免费微型计划/月有 500 笔交易。
  * [FreeIPAPI](https://freeipapi.com) - 为商业和非商业用户提供免费、快速且可靠的 IP 地理定位 API(以 JSON 形式提供)
  * [Geolocated.io](https://geolocated.io) - IP 地理定位 API 具有多洲服务器，提供/天 2,000 个请求的免费计划。
  * [Hex](https://hex.tech/) - 用于笔记本、数据应用程序和知识库的协作数据平台。免费社区层最多包含五个项目。
  * [Hook0](https://www.hook0.com/) - Hook0 是一种开源 Webhooks 即服务 (WaaS)，可让在线产品轻松提供 Webhooks。/天发送最多 100 个事件，并免费保留 7 天的历史记录。
  * [Hoppscotch](https://hoppscotch.io) - 一个免费、快速且美观的 API 请求生成器。
  * [HS Ping](https://hsping.com) - 多国 HS(统一制度)和 HTS(统一关税制度)代码查找 API，免费计划/天提供 100 次查找。
  * [huggingface.co](https://huggingface.co) - 为 Pytorch、TensorFlow 和 JAX 构建、训练和部署 NLP 模型。每个月可释放多达 30k 个输入字符。
  * [Insomnia](https://insomnia.rest) - 用于设计和测试API的开源API客户端，它支持REST和GraphQL
  * [Invantive Cloud](https://cloud.invantive.com/) - 使用 Invantive SQL 或 OData4(通常是 Power BI 或 Power Query)访问 70 多个(云)平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma。包括数据复制和交换。为开发人员和实施顾问提供免费计划。对于数据量有限的特定平台免费。
  * [IP Geolocation API by ipwho.org](https://ipwho.org/) - /天 2,000 个免费请求。以非企业价格提供快速的企业级 API。深受开发商、企业、政府和教育客户的信赖。服务器遍布 12 个以上地区。
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) - Abstract 中的 IP 地理定位 API - 允许 1,000 个免费请求。
  * [IP Geolocation](https://ipgeolocation.io/) - IP 地理定位 API - 为开发人员提供永久免费计划，/天限制 1,000 个请求。
  * [ip-api](https://ip-api.com) - IP 地理定位 API，免费用于非商业用途，无需 API 密钥，免费计划的同一 IP 地址限制为 45 个请求/分钟。
  * [IP.City](https://ip.city) - /天 100 个免费 IP 地理定位请求
  * [IP2Location.io](https://www.ip2location.io/) - 免费增值、快速、可靠的 IP 地理定位 API。获取城市、坐标、ISP、ASN、AS 数据等数据。免费计划包括/月 50k 积分。 IP2Location.io /月还提供 500 个免费 WHOIS 和托管域名查找。查看域注册详细信息并查找特定 IP 上托管的域。升级到付费计划以获得更多功能。
  * [Proxmint GeoIP](https://proxmint.com/tools/ip-lookup)— 免费 IP → 国家/城市/ASN JSON API，无密钥，CORS 开放。 MaxMind GeoLite2。
  * [ip2geo.dev](https://ip2geo.dev) - IP 地理定位 API 将 IP 地址转换为位置数据，包括城市、国家、时区、ASN 和货币。免费计划包括/月 1,000 个请求。
  * [ipaddress.sh](https://ipaddress.sh) - 获取不同[formats](https://about.ipaddress.sh/)中的公共 IP 地址的简单服务。
  * [ipapi.is](https://ipapi.is/) - 开发人员为开发人员提供可靠的 IP 地址 API，具有现有的最佳托管检测功能。免费计划提供 1000 次查询，无需注册。
  * [ipapi](https://ipapi.co/) - Kloudend, Inc 的 IP 地址定位 API - 基于 AWS 构建的可靠地理定位 API，深受财富 500 强企业信赖。免费套餐/月提供 30,000 次查找(1,000 次/天)，无需注册。
  * [ipbase.com](https://ipbase.com) - IP 地理定位 API - 永久免费计划，涵盖 150 个/月请求。
  * [IPinfo](https://ipinfo.io/) - 快速、准确且免费(高达 50k/月)的 IP 地址数据 API。提供包含地理位置、公司、运营商、IP 范围、域、滥用联系人等详细信息的 API。所有付费API均可免费试用。
  * [IPLocate](https://www.iplocate.io) - IP 地理定位 API，/天最多免费 1,000 个请求。包括代理/VPN/托管检测、ASN 数据、公司 IP 等。 IPLocate 还以 CSV 或 GeoIP 兼容的 MMDB 格式提供免费下载的 IP 到国家/地区和 IP 到 ASN 数据库。
  * [IPTrace](https://iptrace.io) - 一个极其简单的 API，可为您的企业提供可靠且有用的 IP 地理定位数据，/月可进行 50,000 次免费查找。
  * [JSON IP](https://getjsonip.com) - 返回请求的客户端的公共 IP 地址。免费套餐无需注册。使用 CORS，可以使用客户端 JS 直接从浏览器请求数据。对于监控客户端和服务器 IP 变化的服务很有用。无限请求。
  * [JSON to Table](https://jsontotable.org) - 将 JSON 转换为交互式表格，以便快速查看、编辑和在线共享。
  * [JSON2Video](https://json2video.com) - 视频编辑 API，可通过编程或无需代码实现视频营销和社交媒体视频的自动化。
  * [JSONGrid](https://jsongrid.com) - 免费工具，可将复杂的 JSON 数据可视化、编辑、过滤到漂亮的表格网格中。通过链接保存和共享 JSON 数据。
  * [JSONing](https://jsoning.com/api/) - 从 JSON 对象创建假 REST API，并自定义 HTTP 状态代码、标头和响应正文。
  * [JSONSwiss](https://www.jsonswiss.com/) - JSONSwiss 是一个功能强大的在线 JSON 查看器、编辑器和验证器。通过 AI 驱动的修复、树视图、表格视图、12 种以上编程语言的代码生成，格式化、可视化、搜索和操作 JSON 数据，将 json 转换为 csv、xml、yaml、属性等。
  * [KillBait API](https://killbait.com/api/doc) - KillBait API 允许用户提交 URL 进行内容评估、检测潜在的标题诱饵并对文章进行分类。该 API 专为中等发布频率而设计，每小时提交次数限制为 1 次，/天提交次数限制为 10 次。媒体合作伙伴可以要求更高的限制。
  * [Kreya](https://kreya.app) - 免费的 gRPC GUI 客户端用于调用和测试 gRPC API。可以通过服务器反射导入 gRPC API。
  * [LoginLlama](https://loginllama.app) - 登录安全 API，用于检测欺诈和可疑登录并通知您的客户。/月 1,000 次登录免费。
  * [Market Data API](https://www.marketdata.app) - 提供股票、期权、共同基金等的实时和历史财务数据。永久免费 API 层允许/天免费进行 100 个 API 请求。
  * [Maxim AI](https://getmaxim.ai/) - 模拟、评估和观察您的 AI 代理。 Maxim 是一个端到端评估和可观察平台，可帮助团队可靠地交付 AI 代理，并且速度提高 5 倍以上。独立开发者和小型团队永久免费(3 个席位)。
  * [microlink.io](https://microlink.io/) - 它将任何网站转化为元标签标准化、美容链接预览、抓取功能或屏幕截图等数据作为服务。/天 50 个请求，/天免费。
  * [Mintlify](https://mintlify.com) - API 文档的现代标准。美观且易于维护的 UI 组件、应用内搜索和交互式游乐场。 Free for 1 editor.
  * [MockAPI](https://www.mockapi.io/) - MockAPI 是一个简单的工具，可让您快速模拟 API、生成自定义数据并使用 RESTful 接口执行操作。 MockAPI 旨在成为一个原型设计/测试/学习工具。一个项目/每个项目 2 个免费资源。
  * [Mockerito](https://mockerito.com/) - 免费模拟 REST API 服务，提供跨 9 个领域(电子商务、金融、医疗保健、教育、招聘、社交媒体、股票市场、天气和航空)的真实数据。无需强制注册，无需 API 密钥，无限制请求。非常适合前端原型设计、API 测试、学习和教学 Web 开发。
  * [Mockfly](https://www.mockfly.dev/) - Mockfly 是一款值得信赖的 API 模拟和功能标志管理开发工具。通过直观的界面快速生成和控制模拟 API。免费套餐/天提供 500 个请求。
  * [Mocko.dev](https://mocko.dev/) - 免费代理您的 API、选择要在云中模拟的端点并检查流量。加快您的开发和集成测试。
  * [Multi-Exit IP Address Checker](https://ip.alstra.ca/) -  一个免费且简单的工具，用于检查您跨多个节点的退出 IP 地址，并了解您的 IP 在不同的全球区域和服务中的显示方式。对于测试基于规则的 DNS 分割工具(例如 Control D)很有用。
  * [News API](https://newsapi.org) - 使用代码在网络上搜索新闻，并获取 JSON 结果。开发人员/天可以免费获得 100 个查询。文章有 24 小时延迟。
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API - /月 100 个免费请求。
  * [OCR.Space](https://ocr.space/) - OCR API 解析图像和 pdf 文件，并以 JSON 格式返回文本结果。/月 25,000 个请求免费，文件大小限制为 1MB。
  * [OpenAPI3 Designer](https://openapidesigner.com/) - 免费直观地创建 Open API 3 定义。
  * [Parseur](https://parseur.com) - /月 20 个免费页面：从 PDF、电子邮件中提取数据。人工智能驱动。完整的 API 访问权限。
  * [PDF-API.io](https://pdf-api.io) - PDF 自动化 API、可视化模板编辑器或 HTML 到 PDF、动态数据集成以及使用 API 进行 PDF 渲染。免费计划附带一个模板，/月 100 个 PDF。
  * [PDFBolt](https://pdfbolt.com) - 以开发人员为中心的 PDF 生成 API，在设计时充分考虑了隐私。它提供受 Stripe 启发的文档，并包含/月 500 次免费 PDF 转换。
  * [Pixela](https://pixe.la/) - 免费的日流数据库服务。所有操作均通过API执行。还可以使用热图和折线图进行可视化。
  * [Posthook](https://posthook.io) - 通过自动重试、交付跟踪和故障警报，安排在未来某个时间触发的 Webhooks。免费计划包括/月 1,000 个 Webhooks。
  * [Postman](https://postman.com) - 使用用于 API 开发的协作平台 Postman，简化工作流程并更快地创建更好的 API。永久免费使用邮递员应用程序。 Postman 云功能也是永久免费的，但有一定限制。
  * [PrefectCloud](https://www.prefect.io/cloud/) - 数据流自动化的完整平台。免费计划包括 5 个已部署的工作流程和/月 500 分钟的无服务器计算积分。
  * [Preset Cloud](https://preset.io/) - 托管的 Apache Superset 服务。对于最多 5 名用户的团队永远免费，具有无限的仪表板和图表、无代码图表生成器和协作 SQL 编辑器。
  * [ProxySentry](https://proxysentry.io/) - 用于检测住宅代理和 VPN 的 IP API。 ProxySentry.io 在rapidapi.com 上提供/月 10k 请求的免费套餐。
  * [Reducto](https://reducto.ai) - 将任何非结构化文档(PDF、XLSX、JPG、PPTX 等)转换为结构化 JSON 数据。解析、提取数据和编辑 PDF 表单。免费套餐包含 15k 免费积分和即用即付。
  * [Rendi](https://rendi.dev) - FFmpeg API - FFmpeg 的 REST API，在线运行 FFmpeg，无需处理基础设施。免费套餐具有/月处理配额和 4 个可用 vCPU。
  * [RequestBin.com](https://requestbin.com) - 创建一个可以向其发送 HTTP 请求的免费端点。发送到该端点的任何 HTTP 请求都将与关联的负载和标头一起记录，以便您可以观察来自 Webhook 和其他服务的建议。
  * [ROBOHASH](https://robohash.org/) - 用于从任何文本生成独特且炫酷的图像的 Web 服务。
  * [Scraper's Proxy](https://scrapersproxy.com) - 用于抓取的简单 HTTP 代理 API。匿名抓取，无需担心限制、阻止或验证码。/月前 100 次成功抓取免费，包括 javascript 渲染(如果您联系支持人员，可以获取更多)。
  * [ScrapingAnt](https://scrapingant.com/) - Headless Chrome 抓取 API 和免费检查代理服务。 JavaScript 渲染、高级旋转代理、避免验证码。免费 10,000 个 API 积分。
  * [SerpApi](https://serpapi.com/) - 实时搜索引擎抓取 API。返回 Google、YouTube、Bing、百度、沃尔玛和许多其他机器的结构化 JSON 结果。免费计划包括/月 100 次成功的 API 调用。
  * [Sheetson](https://sheetson.com) - 立即将任何 Google 表格转变为 RESTful API。提供免费计划，包括每张纸 1,000 个免费行。
  * [SikkerAPI](https://sikkerapi.com) - 免费的 IP 声誉和威胁情报，由全球分布的高互动蜜罐网络和社区报告的滥用事件提供支持。/天 1,000 个免费 IP 查找、TAXII 指标和报告，/天从我们的黑名单中提取 5,000 个新 IP，并免费监控您自己的 CIDR 范围 (/16)。
  * [Simplescraper](https://simplescraper.io) - 每次操作后触发您的 webhook。免费计划包括 100 个云抓取积分。
  * [Geekflare API](https://geekflare.com/api/) - Geekflare API 可让您将网站抓取到 Markdown、截取屏幕截图、执行 TLS 扫描和 DNS 查找、测试加载时间等。免费计划/月提供 500 个 API 积分(例如 500 次 DNS 查找、250 次网络抓取或 100 次屏幕截图)。请参阅[credit mapping](https://docs.geekflare.com/api/api-credit-mapping)。
  * [SmartParse](https://smartparse.io) - SmartParse 是一个数据迁移和 CSV 到 API 平台，提供节省时间和成本的开发人员工具。免费套餐包括/月 300 个处理单元、浏览器上传、数据隔离、断路器和作业警报。
  * [Sofodata](https://www.sofodata.com/) - 从 CSV 文件创建安全的 RESTful API。上传 CSV 文件并通过其 API 立即访问数据，从而加快应用程序开发速度。免费计划包括 2 个 API 和/月 2,500 次 API 调用。您不需要信用卡。
  * [Sqlable](https://sqlable.com/) - 免费在线 SQL 工具的集合，包括 SQL 格式化程序和验证程序、SQL 正则表达式测试程序、假数据生成器和交互式数据库游乐场。
  * [Svix](https://www.svix.com/) - Webhooks 即服务。/月免费发送多达 50,000 条消息。
  * [Tavily AI](https://tavily.com/) - 用于在线搜索和快速洞察和综合研究的API，具有研究结果的组织能力。免费套餐/月 1000 个请求，无需信用卡。
  * [TemplateFox](https://pdftemplateapi.com) - PDF 生成 API 具有可视化模板编辑器、动态数据合并和适用于 7 种语言的 SDK。免费计划包括/月 60 个 PDF 和 3 个模板。
  * [The IP API](https://theipapi.com/) - IP 地理定位 API /天有 1000 个免费请求。提供有关 IP 地址位置的信息，包括国家、城市、地区等。
  * [TinyMCE](https://www.tiny.cloud) - 富文本编辑API。核心功能免费，无限制使用。
  * [Tomorrow.io Weather API](https://www.tomorrow.io/weather-api/) - 提供免费的天气 API 计划。提供覆盖全球的准确、最新的天气预报、历史数据和天气监测解决方案。
  * [Treblle](https://www.treblle.com) - Treble 帮助团队构建、发布和管理 API。具有高级 API 日志聚合、可观察性、文档和调试。您可以免费获得所有功能，但免费套餐/月最多有 25 万个请求的限制。
  * [Trophy](https://trophy.so) - 用于在网络和移动应用程序中构建游戏化功能(例如成就、连胜、积分和排行榜)的 API 基础设施。/月 100 名活跃用户免费。
  * [UniRateAPI](https://unirateapi.com) - 590 多种货币和加密货币的实时汇率。免费计划提供无限制的 API 调用，非常适合开发人员和金融应用程序。
  * [vatcheckapi.com](https://vatcheckapi.com) - 简单且免费的增值税号验证 API。/月 150 次免费验证。
  * [vatnode](https://vatnode.dev) - 具有 VIES 和国家税务登记后备功能的欧盟增值税号验证 REST API，返回官方 VIES 咨询号以进行审计记录。/月 100 次验证的免费套餐，无需信用卡。
  * [WeatherXu](https://weatherxu.com/) - 全球天气数据，包括当前状况、每小时和每日天气预报以及通过我们的 API 发出的天气警报。集成人工智能模型和机器学习系统来分析和组合多个天气模型，以提高预报准确性。免费套餐包括/月 10,000 次 API 调用。
  * [WebScraping.AI](https://webscraping.ai) - 简单的 Web Scraping API，具有内置解析、Chrome 渲染和代理。/月 2000 次免费 API 调用。
  * [Weights & Biases](https://wandb.ai) - 开发人员优先的 MLOps 平台。通过实验跟踪、数据集版本控制和模型管理，更快地构建更好的模型。免费套餐仅适用于个人项目，包含 100 GB 存储空间。
  * [What Is My IP](https://whatismyip.help) - 一项免费服务，可通过具有不同输出格式的 API 检查您的公共 IPv4 和 IPv6 地址以及相关请求数据，以实现自动化、脚本和网络故障排除。
  * [What The Diff](https://whatthediff.ai) - 人工智能驱动的代码审查助手。免费计划的/月限额为 25,000 个代币(约 10 个 PR)。
  * [wolfram.com](https://wolfram.com/language/) - 云端内置基于知识的算法。
  * [wrapapi.com](https://wrapapi.com/) - 将任何网站变成参数化 API。/月 30,000 次 API 调用。
  * [Zenscrape](https://zenscrape.com/web-scraping-api) - 具有无头浏览器、住宅 IP 和简单定价的网络抓取 API。/月 1000 次免费 API 调用，并为学生和非营利组织提供额外学分。
  * [Zipcodebase](https://zipcodebase.com) - 免费邮政编码 API，访问全球邮政编码数据。/月 5,000 个免费请求。
  * [Zip-Codes](https://www.zip-codes.com/api/) - 适用于美国和加拿大邮政编码的 REST API，具有地址验证、半径搜索和人口普查人口统计功能。/天 2,500 个免费请求。
  * [Zipcodestack](https://zipcodestack.com) - 免费邮政编码 API 和邮政编码验证。/月一万个免费请求。
  * [Zuplo](https://zuplo.com/) - 免费的 API 管理平台，用于设计、构建 API 并将其部署到边缘。在几分钟内将 API 密钥身份验证、速率限制、开发人员文档和货币化添加到任何 API。 OpenAPI 原生且完全可编程，可使用 Web 标准 api 和 Typescript。免费计划提供最多 10 个项目、无限的生产边缘环境、/月 100 万个请求和 10GB 出口。
  * [Metashot](https://metashot.io)— Open Graph (OG) 社交预览图像生成 API。通过 URL 参数为 Twitter、LinkedIn 和 Facebook 生成动态 1200×630 图像，并在 Cloudflare Workers 上进行边缘缓存。免费套餐：/月 1,000 次渲染。付费计划 12 美元/月起。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="artifact-repos"></a>
## 制品仓库

  * [Gemfury](https://gemfury.com) - Maven、PyPi、NPM、Go Module、Nuget、APT 和 RPM 存储库的私有和公共工件存储库。免费用于公共项目。
  * [jitpack.io](https://jitpack.io/) - GitHub 上 JVM 和 Android 项目的 Maven 存储库，对公共项目免费。
  * [paperspace](https://www.paperspace.com/) - 构建和扩展 AI 模型，开发、训练和部署 AI 应用程序，免费计划：公共项目、5Gb 存储、基本实例。
  * [RepoFlow](https://repoflow.io) - RepoFlow 通过支持 npm、PyPI、Docker、Go、Helm 等简化包管理。免费试用 10GB 存储空间、10GB 带宽、100 个套餐和无限用户的云服务，或自行托管仅供个人使用。
  * [RepoForge](https://repoforge.io) - 用于 Python、Debian、NPM 包和 Docker 注册表的私有云托管存储库。开源/公共项目的免费计划。
  * [repsy.io](https://repsy.io) - 1 GB 免费的私有/公共 Maven 存储库。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="tools-for-teams-and-collaboration"></a>
## 团队和协作工具

  * [3Cols](https://3cols.com/) - 一个免费的基于云的代码片段管理器，用于个人和协作代码。
  * [BookmarkOS.com](https://bookmarkos.com) - 可定制在线桌面中的免费全合一书签管理器、选项卡管理器和任务管理器，具有文件夹协作功能。
  * [Braid](https://www.braidchat.com/) - 专为团队设计的聊天应用程序。公共访问组免费，用户、历史记录和集成不受限制。此外，它还提供了一个可自托管的开源版本。
  * [Calendly](https://calendly.com) - Calendly 是用于连接和安排会议的工具。免费计划为每个用户提供 1 个日历连接和无限会话。还提供桌面和移动应用程序。
  * [cally.com](https://cally.com/) - 找到召开会议的最佳时间和日期。使用简单，非常适合小型和大型团体。
  * [cDox](https://cdox.ca) - 在加拿大托管的私人文档编辑器。使用干净的公共链接编写、格式化、协作和发布文档。数据从未用于人工智能训练。免费计划包括 50 MB 存储空间、最多 3 个公共链接，并可导出为 PDF、Word 和 Markdown。
  * [Chanty.com](https://chanty.com/) - Chanty 是 Slack 的另一个替代品。它为小型团队(最多 10 人)提供永久免费计划，具有无限的公共和私人对话、可搜索历史记录、无限的 1:1 音频通话、无限的语音消息、十个集成以及每个团队 20 GB 的存储空间。
  * [DevToolLab](https://devtoollab.com) - 在线开发人员工具可免费访问所有基本工具，能够为每个工具自动保存一个条目、标准处理速度和社区支持。
  * [Discord](https://discord.com/) - 与公共/私人房间聊天。 Markdown 文本、语音、视频和屏幕共享功能。免费供无限用户使用。
  * [Dubble](https://dubble.so/) - 免费的分步指南创建者。截取屏幕截图、记录流程并与您的团队协作。还支持异步屏幕录制。
  * [Duckly](https://duckly.com/) - 与您的团队实时交谈和协作。与IDE结对编程，终端共享，语音、视频、屏幕共享。小团队免费。
  * [element.io](https://element.io/) - 一个基于 Matrix 构建的去中心化开源通信工具。群组聊天、直接消息传递、加密文件传输、语音和视频聊天以及与其他服务的轻松集成。
  * [evernote.com](https://evernote.com/) - 组织信息的工具。分享您的笔记并与其他人一起工作
  * [Fibery](https://fibery.io/) - 连接的工作空间平台。单用户免费，最多 2 GB 磁盘空间。
  * [Fibo](https://fibo.dev) - 一款适用于敏捷团队的免费在线实时 scrum 扑克工具，可让无限的成员估计故事点以加快规划速度。
  * [Fizzy](https://www.fizzy.do/) - 基于看板的项目管理和问题跟踪平台。创建公共看板、设置 Webhook、使用卡片标记并跟踪无限用户 - 最多可免费查看 1000 个项目。
  * [flat.social](https://flat.social) - 用于团队会议和欢乐时光社交活动的交互式可定制空间。无限次会议，最多可免费容纳 8 个并发用户。
  * [flock.com](https://flock.com) - 为您的团队提供更快的沟通方式。免费无限消息、频道、用户、应用程序和集成
  * [GitBook](https://www.gitbook.com/) - 用于捕获和记录技术知识的平台 - 从产品文档到内部知识库和 API。为个人开发者提供免费计划。
  * [GitDailies](https://gitdailies.com) - 您团队在 GitHub 上的提交和Pull Request活动的每日报告。包括推送可视化工具、同行识别系统和自定义警报生成器。免费套餐拥有无限用户、三个存储库和 3 个警报配置。
  * [gitter.im](https://gitter.im/) - 聊天，用于 GitHub。无限制的公共和私人房间，最多 25 人的团队免费
  * [gokanban.io](https://gokanban.io) - 基于语法，无需注册看板即可快速使用。免费，没有任何限制。
  * [Hackmd.io](https://hackmd.io/) - 用于 Markdown 格式文档/文件的实时协作和编写工具。类似于 Google Docs，但适用于 Markdown 文件。免费无限数量的“笔记”，但私人笔记和模板[will be limited](https://hackmd.io/pricing)的协作者(受邀者)数量。
  * [HeySpace](https://hey.space) - 具有聊天、日历、时间线和视频通话功能的任务管理工具。最多 5 个用户免费。
  * [Huly](https://huly.io/) - 一体化项目管理平台(替代 Linear、Jira、Slack、Notion、Motion)- 无限用户、每个工作区 10GB 存储、10GB 视频(音频)流量。
  * [Keybase](https://keybase.io/) - Keybase 是 Slack 的 FOSS 替代品；它可以保证每个人的聊天和文件的安全，从家庭到社区再到公司。
  * [Knocket](https://trtc.io/solutions/knocket) - 为独立开发者和小型团队提供永久免费的联系层：网站和移动应用程序的实时聊天小部件(通过 WebView 的 iOS/Android/Flutter/React Native)、可共享的联系页面(包含社交、预订链接和博客的 Linktree 风格)以及统一的 Telegram/电子邮件收件箱。直接从 Telegram 回复(无需仪表板)。会议安排程序、多语言、浅色/深色主题。配套开源人工智能自动回复代理。没有广告，没有座位限制。
  * [Linkinize](https://linkinize.com) - 团队的书签管理器，具有标记、多工作空间和协作功能。免费计划包括 4 个工作区和 10 名团队成员。
  * [Lockitbot](https://www.lockitbot.com/) - 在 Slack 中保留和锁定共享资源，例如房间、开发环境、服务器等。最多免费 2 个资源
  * [meet.jit.si](https://meet.jit.si/) - 免费一键视频对话和屏幕共享
  * [Miro](https://miro.com/) - 适用于分布式团队的可扩展、安全、跨设备和企业级协作白板。具有免费增值计划。
  * [Notion](https://www.notion.so/) - Notion 是一款笔记和协作应用程序，支持 Markdown，集成了任务、wiki 和数据库。该公司将该应用程序描述为一个用于记笔记、项目管理和任务管理的一体化工作空间。除了跨平台应用程序之外，还可以通过大多数网络浏览器访问它。
  * [Nuclino](https://www.nuclino.com) - 一个轻量级的协作式 wiki，包含您团队的所有知识、文档和注释。免费计划包含所有基本功能、最多 50 个项目和 5GB 存储空间。
  * [OnlineInterview.io](https://onlineinterview.io/) - 免费的代码面试平台，带有嵌入式视频聊天、绘图板和在线代码编辑器，您可以在浏览器上编译和运行代码。一键创建远程面试室。
  * [paste.sh](https://paste.sh/) - 这是一个基于 JavaScript 和加密货币的简单粘贴网站。
  * [Pastefy](https://pastefy.app/) - 美观而简单的 Pastebin 具有可选的客户端加密、多选项卡粘贴、API、突出显示的编辑器等。
  * [Pendulums](https://pendulums.io/) - Pendulums 是一款空闲时间跟踪工具，通过易于使用的界面和有价值的统计数据，帮助您更好地管理时间。
  * [Proton Pass](https://proton.me/pass) - 具有内置电子邮件别名、2FA 身份验证器、共享和密钥的密码管理器。可在网络、浏览器扩展、移动应用程序和桌面上使用。
  * [Pullflow](https://pullflow.com) - Pullflow 提供了一个 AI 增强型平台，用于跨 GitHub、Slack 和 VS Code 进行代码审查协作。
  * [Pumble](https://pumble.com) - 免费团队聊天应用程序。无限用户和消息历史记录，永久免费。
  * [Quidlo Timesheets](https://www.quidlo.com/timesheets) - 适合团队的简单时间表和时间跟踪应用程序。免费计划具有时间跟踪和生成报告功能，最多可供 10 个用户使用。
  * [Raindrop.io](https://raindrop.io) - 适用于 macOS、Windows、Android、iOS 和 Web 的私密且安全的书签应用程序。免费无限书签和协作。
  * [Revolt.chat](https://revolt.chat/) - [Discord](https://discord.com/)的开源替代方案，尊重您的隐私。它还免费提供 Discord 的大多数专有功能。 Revolt 是一款安全、快速且 100% 免费的一体化应用程序。每个功能都是免费的。与大多数主流聊天应用程序不同，它们还具有(官方和非官方)插件支持。
  * [Rocket.Chat](https://rocket.chat/) - 开源通信平台，具有全渠道功能、矩阵联合、与其他应用程序桥接、无限消息传递和完整消息传递历史记录。
  * [ruttl.com](https://ruttl.com/) - 最好的一体化反馈工具，用于收集数字反馈并查看网站、PDF 和图像。
  * [Screen Sharing via Browser](https://screensharing.net) - 免费的屏幕共享工具，直接从浏览器与协作者共享您的屏幕，无需下载或注册。免费。
  * [seafile.com](https://www.seafile.com/) - 私人或云存储、文件共享、同步、讨论。云版只有1GB
  * [SiteDots](https://sitedots.com/) - 直接在您的网站上分享网站项目的反馈，无需模拟、画布或解决方法。功能齐全的免费套餐。
  * [Slab](https://slab.com/) - 面向团队的现代知识管理服务。最多 10 位用户免费。
  * [slack.com](https://slack.com/) - 无限用户免费，但有一些功能限制
  * [StatusPile](https://www.statuspile.com/) - 状态页面的状态页面。您可以跟踪上游提供商的状态页面吗？
  * [Stickies](https://stickies.app/) - 用于头脑风暴、内容管理和笔记的视觉协作应用程序。最多可免费使用 3 面墙、无限用户和 1 GB 存储空间。
  * [MeetBackdrops](https://meetbackdrops.com) - Zoom、Microsoft Teams 和 Google Meet 上视频通话的免费高清虚拟背景。 1,000 多个工作室设计的环境，无需注册。
  * [talky.io](https://talky.io/) - 免费群组视频聊天。匿名的。点对点。无需插件、注册或付款
  * [Teamcamp](https://www.teamcamp.app) - 面向软件开发公司的一体化项目管理应用程序。
  * [Teamhood](https://teamhood.com/) - 免费的项目、任务和问题跟踪软件。通过泳道和完整的 Scrum 实施支持看板。具有集成的时间跟踪。免费供五个用户和三个项目组合使用。
  * [Teamplify](https://teamplify.com) - 通过团队分析和智能每日站会改进团队开发流程。包括针对远程优先团队的全功能休假管理。最多 5 名用户的小团体免费。
  * [Telegram](https://telegram.org/) - Telegram 适合所有想要快速、可靠的消息传递和通话的人。企业用户和小型团队可能喜欢大型群组、用户名、桌面应用程序和强大的文件共享选项。
  * [Tencent RTC](https://trtc.io/) - 腾讯实时通讯(TRTC)提供群组音视频通话解决方案。首年/月10,000分钟免费。
  * [TimeCamp](https://www.timecamp.com/) - 无限用户的免费时间跟踪软件。轻松与 Jira、Trello、Asana 等 PM 工具集成。
  * [tldraw.com](https://tldraw.com) -  免费的开源白板和图表工具，具有智能箭头、捕捉、便笺和 SVG 导出功能。用于协作编辑的多人游戏模式。还提供免费的官方 VS Code 扩展。
  * [transfernow](https://www.transfernow.net/) - 最简单、最快、最安全的文件传输和共享界面。无需强制订阅即可发送照片、视频和其他大文件。
  * [Tugboat](https://tugboat.qa) - 自动且按需预览每个Pull Request。所有人免费，非营利组织免费获得 Nano 等级。
  * [twist.com](https://twist.com) - 一款异步友好的团队沟通应用程序，对话保持井然有序且切题。提供免费和无限制的计划。符合资格的团队可享受折扣。
  * [userforge.com](https://userforge.com/) - 相互关联的在线角色、用户故事和上下文映射。  帮助最多 3 个角色和两个协作者保持设计和开发同步。
  * [Visual Debug](https://visualdebug.com) - 用于更好的客户与开发人员沟通的视觉反馈工具
  * [Webex](https://www.webex.com/) - 免费计划的视频会议每次会议 40 分钟，与会者人数为 100 人。
  * [Webvizio](https://webvizio.com) - 网站反馈工具、网站审查软件和错误报告工具，用于直接在实时网站和 Web 应用程序、图像、PDF 和设计文件上简化任务的 Web 开发协作。
  * [whereby.com](https://whereby.com/) - 免费一键式视频对话(以前称为appear.in)
  * [windmill.dev](https://windmill.dev/) - Windmill 是一个开源开发者平台，可通过最少的 Python 和 Typescript 脚本快速构建生产级多步骤自动化和内部应用程序。作为免费用户，您最多可以创建三个非高级工作区并成为其成员。
  * [wistia.com](https://wistia.com/) - 具有观看者分析、高清视频传输和营销工具的视频托管，可帮助了解您的访问者、25 个视频和 Wistia 品牌播放器
  * [wormhol.org](https://www.wormhol.org/) - 简单的文件共享服务。与任意数量的同伴共享高达 5GB 的无限文件。
  * [Wormhole](https://wormhole.app/) - 通过端到端加密共享最大 5GB 的文件，持续时间长达 24 小时。对于大于 5 GB 的文件，它使用点对点传输直接发送您的文件。
  * [zoom.us](https://zoom.us/) - 提供安全视频和网络会议插件。免费计划仅限 40 分钟。
  * [Zulip](https://zulip.com/) - 通过独特的类似电子邮件的线程模型进行实时聊天。免费计划包括 10,000 条搜索历史消息和高达 5 GB 的文件存储空间。此外，它还提供了一个可自托管的开源版本。
  * [RightFeature](https://rightfeature.com/) - 轻松收集客户的反馈，将客户反馈转化为您的产品路线图。收集、优先考虑并交付对用户真正重要的功能。

**[⬆️ 返回顶部](#table-of-contents)**

## CMS

  * [Contentful](https://www.contentful.com/) - 无头 CMS。云中的内容管理和交付 API。附带 1 个免费社区空间，其中包括 5 位用户、25K 条记录、48 种内容类型、2 个区域设置。
  * [Cosmic](https://www.cosmicjs.com/) - 无头 CMS 和 API 工具包。为开发人员提供免费的个人计划。
  * [Crystallize](https://crystallize.com) - 具有电子商务支持的无头 PIM。内置 GraphQL API。免费版本包括无限用户、1000 个目录项、5 GB/月带宽和 25k/月 API 调用。
  * [DatoCMS](https://www.datocms.com/) - 为小型项目提供免费套餐。 DatoCMS 是一个基于 GraphQL 的 CMS。在较低层，您/月有 10 万次调用。
  * [Hygraph](https://hygraph.com/) - 为小型项目提供免费套餐。 GraphQL 第一个 API。从传统解决方案转向 GraphQL 原生 Headless CMS，并首先提供全渠道内容 API。
  * [Prismic](https://www.prismic.io/) - 无头 CMS。具有完全托管和可扩展 API 的内容管理界面。社区计划为一名用户提供无限的 API 调用、文档、自定义类型、资产和区域设置。您下一个项目所需的一切。更大的免费计划可用于开放内容/开源项目。
  * [Sanity.io](https://www.sanity.io/) - 具有开源编辑环境和实时托管数据存储的结构化内容平台。无限的项目。每个项目免费包含无限的管理员用户、三个非管理员用户、两个数据集、500K API CDN 请求、10GB 带宽和 5GB 资源。
  * [Solo](https://soloist.ai) - Mozilla 的免费 AI 网站创建器，只需几个简单的输入即可为您的企业创建一个漂亮的网站。免费自定义域名，无需信用卡。
  * [Squidex](https://squidex.io/) - 为小型项目提供免费套餐。首先是 API/GraphQL。开源并基于事件源(自动处理每个更改)。
  * [Storyblok](https://www.storyblok.com) - 面向开发人员和营销人员的无头 CMS，可与所有现代框架配合使用。社区(免费)层提供管理 API、可视化编辑器、十个源、自定义字段类型、国际化(无限语言/区域设置)、资产管理器(最多 2500 个资产)、图像优化服务、搜索查询、Webhook + 250GB 流量/月。
  * [TinaCMS](https://tina.io/) - 取代 Forestry.io。支持 Markdown、MDX 和 JSON 的开源 Git 支持的无头 CMS。基本优惠是免费的，有两个用户可用。
  * [WPJack](https://wpjack.com) - 不到 5 分钟即可在任何云上设置 WordPress！免费套餐包括 1 台服务器、2 个站点、免费 SSL 证书和无限的 cron 作业。没有时间限制或过期 - 您的网站，您做主。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="code-generation"></a>
## 代码生成

* [Appinvento](https://appinvento.io/) - 免费的无代码应用程序构建器。它提供对自动生成的后端源代码的完整访问，并允许无限的 API 和路由。免费计划包括三个项目和五个表格。
* [DhiWise](https://www.dhiwise.com/) - 将 Figma 设计转换为动态 Flutter 和 React 应用程序。其代码生成技术旨在优化工作流程，以构建可用于生产的移动和网络体验。
* [Karbon Sites](https://www.karbonsites.space) - 人工智能驱动的网站构建器和编辑器，可根据文本提示、草图或简历生成可用于生产的前端代码。功能包括原生 Android (APK) 导出和/月 5 代的免费套餐(通过自定义 Gemini API 密钥无限制)。
* [Metalama](https://www.postsharp.net/metalama) - 特定于 C# 的工具，可在编译期间动态生成样板代码以保持源代码干净。对于开源项目来说是免费的；其商业友好的免费套餐最多包括三个方面。
* [Supermaven](https://www.supermaven.com/) - 适用于 VS Code、JetBrains 和 Neovim 的高速 AI 代码补全插件。免费套餐提供无限的内联完成，重点是超低延迟。
* [v0.dev](https://v0.dev/) - v0 由 Vercel 创建，使用 shadcn/ui 和 Tailwind CSS 生成复制粘贴友好的 React 代码。它采用积分系统，/月提供 1,200 个起始积分和 200 个免费积分。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="code-quality"></a>
## 代码质量

  * [beanstalkapp.com](https://beanstalkapp.com/) - 用于编写、审查和部署代码的完整工作流程)、一个用户的免费帐户以及一个具有 100 MB 存储空间的存储库
  * [codacy.com](https://www.codacy.com/) - PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自动代码审查，免费提供无限的公共和私人存储库
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - 用于 DevOps 的自动化基础设施即代码审查工具与 GitHub、Bitbucket 和 GitLab(甚至是自托管)集成。除了标准语言之外，它还分析 Ansible、Terraform、CloudFormation、Kubernetes 等。 (开源免费)
  * [codecov.io](https://codecov.io/) - 代码覆盖率工具 (SaaS)，免费开源和一个免费的私人存储库
  * [CodeFactor](https://www.codefactor.io) - Git 的自动代码审查。免费版本包括无限用户、公共存储库和一个私人存储库。
  * [coderabbit.ai](https://coderabbit.ai) - 与 GitHub/GitLab 集成的人工智能驱动的代码审查工具。免费套餐包括 200 个文件/小时、3 个评论/小时和 50 个对话/小时。开源项目永久免费。
  * [CodSpeed](https://codspeed.io) - 自动跟踪 CI 管道中的性能。借助精确且一致的指标，在​​部署之前捕获性能回归。开源项目永久免费。
  * [coveralls.io](https://coveralls.io/) - 显示测试覆盖率报告，免费开源
  * [deepscan.io](https://deepscan.io) - 高级静态分析，用于自动查找 JavaScript 代码中的运行时错误，免费开源
  * [DeepSource](https://deepsource.io/) - DeepSource 不断分析源代码更改，查找并修复按安全性、性能、反模式、错误风险、文档和风格分类的问题。与 GitHub、GitLab 和 Bitbucket 的本机集成。
  * [DiffText](https://difftext.com) - 立即找到两个代码块之间的差异。完全免费使用。
  * [eversql.com](https://www.eversql.com/) - EverSQL - 数据库优化的第一平台。自动获得对数据库和 SQL 查询的重要见解。
  * [gerrithub.io](https://review.gerrithub.io/) - 免费的 GitHub 存储库的 Gerrit 代码审查
  * [goreportcard.com](https://goreportcard.com/) - Go 项目的代码质量，免费开源
  * [gtmetrix.com](https://gtmetrix.com/) - 优化网站的报告和全面建议
  * [holistic.dev](https://holistic.dev/) - 用于 Postgresql 优化的 #1 静态代码分析器。性能、安全和架构师数据库问题自动检测服务
  * [houndci.com](https://houndci.com/) - GitHub 提交有关代码质量的评论，免费开源
  * [reviewable.io](https://reviewable.io/) - GitHub 存储库的代码审查，对公共或个人存储库免费。
  * [scan.coverity.com](https://scan.coverity.com/) - Java、C/C++、C# 和 JavaScript 的静态代码分析，免费开源
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) - 持续检测平台，免费开源
  * [semanticdiff.com](https://app.semanticdiff.com/) - 用于 GitHub Pull Request和提交的编程语言感知差异，对公共存储库免费
  * [shields.io](https://shields.io) - 开源项目的质量元数据徽章
  * [sonarcloud.io](https://sonarcloud.io) - 针对 Java、JavaScript、C/C++、C#、VB.NET、PHP、Objective-C、Swift、Python、Groovy 以及更多语言的自动源代码分析，免费开源

**[⬆️ 返回顶部](#table-of-contents)**

<a id="code-search-and-browsing"></a>
## 代码搜索和浏览

  * [CodeKeep](https://codekeep.io) - Google Keep 代码片段。组织、发现和共享代码片段，具有强大的代码屏幕截图工具，带有预设模板和链接功能。
  * [libraries.io](https://libraries.io/) - 32 个不同的包管理器的搜索和依赖项更新通知，免费开源
  * [Namae](https://namae.dev/) - 搜索各种网站(例如 GitHub、Gitlab、Heroku、Netlify 等)以获取您的项目名称的可用性。
  * [tickgit.com](https://www.tickgit.com/) - 显示`TODO`注释(和其他标记)以识别值得返回以进行改进的代码区域。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="ci-and-cd"></a>
## CI/CD

  * [appcircle.io](https://appcircle.io) - 企业级移动 DevOps 平台，可自动构建、测试和发布移动应用程序存储，以实现更快、更高效的发布周期。每个构建的最长构建时间为 30 分钟，/月构建 20 次，并发构建 1 次免费。
  * [appveyor.com](https://www.appveyor.com/) - 适用于 Windows 的 CD 服务，免费开源
  * [bitrise.io](https://www.bitrise.io/) - 适用于本机或混合移动应用程序的 CI/CD。/月 200 次免费构建，构建时间为 10 分钟，团队成员为两名。 OSS 项目的构建时间为 45 分钟、+1 并发性和无限的团队规模。
  * [buddy.works](https://buddy.works/) - 一个 CI/CD，包含 5 个免费项目和一个并发运行(120 次执行/月)
  * [Buildkite](https://buildkite.com) - CI Pipelines 免费供 3 个用户使用，/月可免费使用 5,000 分钟的工作时间。免费测试分析
    开发人员层包括/月 10 万次测试执行，并为开源项目提供更多免费内容。
  * [bytebase.com](https://www.bytebase.com/) - 数据库 CI/CD 和 DevOps。 20 个以下用户和 10 个数据库实例免费
  * [CircleCI](https://circleci.com/) - 全面的免费计划，包含 GitHub、GitLab 和 BitBucket 存储库的托管 CI/CD 服务中包含的所有功能。多个资源类、Docker、Windows、Mac OS、ARM 执行器、本地运行器、测试分割、Docker 层缓存和其他高级 CI/CD 功能。/月最多可免费执行 6000 分钟，合作者数量不受限制，私人项目中有 30 个并行作业，开源项目最多可免费构建 80,000 分钟。
  * [cirun.io](https://cirun.io) - 免费用于公共 GitHub 存储库
  * [codemagic.io](https://codemagic.io/) - /月免费 500 分钟构建时间
  * [deployhq.com](https://www.deployhq.com/) - 1 个每日部署 10 次的项目(/月 30 分钟构建)
  * [LocalOps](https://localops.co/) - 在 30 分钟内将您的应用程序部署到 AWS/GCP/Azure 上。在任何云上设置标准化应用程序环境，该环境具有内置的持续部署自动化和高级可观察性。免费计划允许 1 个用户和 1 个应用程序环境。
  * [Make](https://www.make.com/en) - 工作流程自动化工具可让您使用 UI 连接应用程序并自动化工作流程。它支持许多应用程序和最流行的 API。对公共 GitHub 存储库免费，并且免费套餐具有 100 Mb、1000 次操作和 15 分钟的最小间隔。
  * [Mergify](https://mergify.com) - GitHub 的工作流程自动化和合并队列 - 免费用于公共 GitHub 存储库
  * [Nx Cloud](https://nx.dev/ci) - Nx Cloud 通过远程缓存、跨机器分配任务，甚至自动拆分 e2e 测试运行等功能，加快 CI 上的单一存储库的速度。它附带一个免费计划，最多可容纳 30 名贡献者，其中包括慷慨的 15 万积分。
  * [RunMyJob](https://runmyjob.io) - 通过实时扩展 Spike 实例，更智能地运行 GitHub Actions 和 GitLab CI 管道。免费套餐包括 400 个 vCPU 分钟、800 GB 分钟和 10 个具有高性能运行程序的并发作业(每个作业 12 个 vCPU 和 32 GB RAM)。
  * [Shipfox](https://www.shipfox.io/) - 运行 GitHub 操作的速度提高 2 倍，/月免费 3000 分钟构建时间。
  * [Spacelift](https://spacelift.io/) - 基础设施即代码的管理平台。免费计划功能：IaC 协作、Terraform 模块注册表、ChatOps 集成、开放策略代理的持续资源合规性、使用 SAML 2.0 的 SSO 以及对公共工作人员池的访问：最多 200 分钟/月
  * [Squash Labs](https://www.squash.io/) - 为每个分支创建一个虚拟机，并使您的应用程序可以通过唯一的 URL、无限的公共和私有存储库、高达 2 GB 的虚拟机大小来使用。
  * [Terramate](https://terramate.io/) - Terramate 是一个用于基础设施即代码 (IaC) 工具(例如 Terraform、OpenTofu 和 Terragrunt)的编排和管理平台。最多可释放 2 位用户，包括所有功能。
  * [Terrateam](https://terrateam.io) - GitOps 首创的 Terraform 自动化，具有Pull Request驱动的工作流程、通过自托管运行程序进行项目隔离以及有序操作的分层运行。最多 3 位用户免费。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="testing"></a>
## 测试

  * [Appetize](https://appetize.io) - 直接在浏览器中在此基于云的 Android 手机/平板电脑模拟器和 iPhone/iPad 模拟器上测试您的 Android 和 iOS 应用程序。免费套餐包括两个并发会话，/月使用 30 分钟。应用程序大小没有限制。
  * [Argos](https://argos-ci.com) - 为开发人员提供开源视觉测试。无限项目，/月 5,000 个屏幕截图。对于开源项目免费。
  * [Bencher](https://bencher.dev/) - 用于捕获 CI 性能回归的连续基准测试工具套件。所有公共项目免费。
  * [BugBug](https://bugbug.io/) - 用于 Web 应用程序的轻量级测试自动化工具。它很容易学习并且不需要编码。您可以在自己的计算机上免费运行无限测试。您还可以通过支付额外的月费获得云监控和 CI/CD 集成。
  * [checkbot.io](https://www.checkbot.io/) - 浏览器扩展程序可测试您的网站是否遵循 50 多个 SEO、速度和安全最佳实践。小型网站的免费套餐。
  * [Checkly](https://checklyhq.com) - 现代 DevOps 的代码优先综合监控。以传统提供商价格的一小部分监控您的 API 和应用程序。由“监控即代码”工作流程和 Playwright 提供支持。为开发者提供慷慨的免费套餐。
  * [CORS-Tester](https://cors-error.dev/cors-tester/) - 一个免费工具，供开发人员和 API 测试人员检查 API 是否针对给定域启用了 CORS 并识别差距。获得可行的见解。
  * [cypress.io](https://www.cypress.io/) - 对浏览器中运行的任何内容进行快速、简单且可靠的测试。 Cypress Test Runner 始终免费且开源，没有任何限制和限制。 Cypress Dashboard 对于最多 5 个用户的开源项目是免费的。
  * [everystep-automation.com](https://www.everystep-automation.com/) - 记录和重播在网络浏览器中执行的所有步骤并创建脚本，免费且选项较少
  * [gridlastic.com](https://www.gridlastic.com/) - Selenium 网格测试，免费计划最多 4 个同步 Selenium 节点/10 个网格启动/4,000 测试分钟/月
  * [katalon.com](https://katalon.com) - 提供一个测试平台，可以帮助各种规模的团队达到不同的测试成熟度，包括 Katalon Studio、TestOps(+ 免费可视化测试)、TestCloud 和 Katalon Recorder。
  * [Keploy](https://keploy.io/) - Keploy 是面向开发人员的功能测试工具包。记录 API 调用会生成 API 的 E2E 测试 (KTests) 和模拟或存根 (KMocks)。对于开源项目来说它是免费的。
  * [Lastest](https://lastest.cloud) - 发货快。不要打碎东西。您可以真正信任的人工智能支持的视觉验证和测试。永久免费计划：1 个项目，/月 500 分钟跑步时间，1 次并发跑步，无需信用卡。
  * [loadmill.com](https://www.loadmill.com/) - 通过分析网络流量自动创建 API 和负载测试。/月免费模拟最多 50 个并发用户，最多 60 分钟。
  * [lost-pixel.com](https://lost-pixel.com) - 针对 Storybook、Ladle、Histoire 故事和 Web 应用程序进行整体视觉回归测试。团队成员不受限制，完全免费开源，/月 7,000 个快照。
  * [pagegym.com](https://pagegym.com) - 加载行为和页面速度分析和优化工具。免费计划提供/天 10 次测试、/周 5 次实验以及/月 15 GB 的最大摄取数据。
  * [percy.io](https://percy.io) - 将可视化测试添加到任何 Web 应用程序、静态站点、样式指南或组件库。  无限的团队成员、演示应用程序和无限的项目、/月 5,000 个快照。
  * [qase.io](https://qase.io) - 开发和质量检查团队的测试管理系统。管理测试用例、编写测试运行、执行测试、跟踪缺陷并衡量影响。免费套餐包括所有核心功能，可用于附件的空间为 500MB，最多可供 3 个用户使用。
  * [Repeato](https://repeato.app/) - 基于计算机视觉和人工智能构建的无代码移动应用测试自动化工具。
    适用于本机应用程序、flutter、react-native、web、ionic 以及更多应用程序框架。免费计划仅限于 iOS 10 次测试和 Android 10 次测试，但包含付费计划的大部分功能，包括无限制的测试运行。
  * [Requestly](https://requestly.com/) - 用于拦截、重定向和模拟 HTTP 请求的开源 Chrome 扩展。
    具有[Debugger](https://requestly.com/products/web-debugger/)、[Mock Server](https://requestly.com/products/mock-server/)、[API Client](https://requestly.com/products/api-client/)和[Session Recording](https://requestly.com/products/session-book/)。  重定向 URL、修改 HTTP 标头、模拟 API、注入自定义 JS、修改 GraphQL 请求、生成模拟 API 端点、使用网络和控制台日志记录会话。在免费套餐中创建最多 10 条规则。免费开源。
  * [seotest.me](https://seotest.me/) - 免费的页面 SEO 网站测试仪。/天 10 次免费网站抓取。有用的 SEO 学习资源和建议，了解如何提高任何网站的页面 SEO 结果，无论技术如何。
  * [snippets.uilicious.com](https://snippets.uilicious.com) - 它类似于 CodePen，但用于跨浏览器测试。 UI-licious 可让您编写用户故事等测试，并提供免费平台 - UI-licious Snippets - 允许您在 Chrome 上运行无限测试，无需注册，每次测试运行最多 3 分钟。发现错误？您可以将唯一的 URL 复制到您的测试中，以向您的开发人员准确展示如何重现错误。
  * [SSR (Server-side Rendering) Checker](https://www.crawlably.com/ssr-checker/) - 通过直观地将页面的服务器渲染版本与常规版本进行比较，检查任何 URL 的 SSR(服务器端渲染)。
  * [testingbot.com](https://testingbot.com/) - Selenium 浏览器和设备测试，[对开源免费](https://testingbot.com/open-source)
  * [Testspace.com](https://testspace.com/) - 用于发布自动化测试结果的仪表板和使用 GitHub 将手动测试作为代码实施的框架。该服务为[free for Open Source](https://github.com/marketplace/testspace-com)，/月有 450 个结果。
  * [tesults.com](https://www.tesults.com) - 测试结果报告和测试用例管理。与流行的测试框架集成。开源软件开发人员、个人、教育工作者和小型团队可以请求除基本免费项目之外的折扣和免费产品。
  * [UseWebhook.com](https://usewebhook.com) - 从浏览器捕获并检查 Webhook。转发到本地主机，或从历史记录中重播。免费使用。
  * [Vaadin](https://vaadin.com) - 使用 Java 或 TypeScript 构建可扩展的 UI，并使用集成工具、组件和设计系统来更快地迭代、更好地设计并简化开发过程。无限项目，五年免费维护。
  * [webhook.site](https://webhook.site) - 使用自定义 URL 验证 Webhook、出站 HTTP 请求或电子邮件。临时 URL 和电子邮件地址始终免费。
  * [websitepulse.com](https://www.websitepulse.com/tools/) - 各种免费的网络和服务器工具。
  * [kogiQA](https://kogiqa.com) - 一种 Web UI 自动化工具，无需选择器即可运行。每个开发者/月可以免费获得 500 次操作。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="security-and-pki"></a>
## 安全和 PKI

  * [aikido.dev](https://www.aikido.dev) - 一体化应用安全平台，涵盖 SCA、SAST、CSPM、DAST、Secrets、IaC、恶意软件、容器扫描、EOL... 免费计划包括两名用户，扫描 10 个存储库、1 个云、2 个容器和 1 个域。
  * [CertKit](https://www.certkit.io/certificate-management) - 管理 SSL 证书颁发、续订和监控。搜索证书透明度日志。测试版后，3 个证书和 1 个用户免费。
  * [CertObserver CT Search](https://certobserver.com/ct-search) - 查找证书透明度日志中记录的公共 SSL/TLS 证书。 CT 搜索是免费的，但 CT 监测不是免费的。
  * [Corgea](https://corgea.com/) - 免费的自主安全平台，可跨 20 多种语言和框架查找、验证和修复不安全的代码和包。免费计划包括 1 个用户和 2 个存储库。
  * [crypteron.com](https://www.crypteron.com/) - 云优先、开发人员友好的安全平台可防止 .NET 和 Java 应用程序中的数据泄露
  * [CyberChef](https://gchq.github.io/CyberChef/) - 一个简单、直观的 Web 应用程序，用于分析和解码/编码数据，无需处理复杂的工具或编程语言。就像密码学和加密领域的瑞士军刀一样。所有功能均可免费使用，没有限制。如果您想自行托管，请开源。
  * [Datree](https://www.datree.io/) - 开源 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及组织的策略来防止 Kubernetes 错误配置
  * [Dependabot](https://dependabot.com/) - 自动更新Ruby、JavaScript、Python、PHP、Elixir、
    Rust、Java(Maven 和 Gradle)、.NET、Go、Elm、Docker、Terraform、Git 子模块和 GitHub Actions。
  * [DJ Checkup](https://djcheckup.com) - 使用这个免费的自动检查工具扫描您的 Django 站点是否存在安全漏洞。从 Pony Checkup 网站分叉。
  * [Doppler](https://doppler.com/) - 用于应用程序机密和配置的通用机密管理器，支持同步到各种云提供商。五个用户免费，具有基本的访问控制。
  * [Dotenv](https://dotenv.org/) - 快速安全地同步您的 .env 文件。停止通过 Slack 和电子邮件等不安全渠道共享您的 .env 文件，再也不会丢失重要的 .env 文件。最多 3 名队友免费。
  * [GitGuardian](https://www.gitguardian.com) - 通过自动秘密检测和修复，确保源代码中的秘密不被泄露。扫描您的 git 存储库以查找 350 多种类型的机密和敏感文件 - 对于个人和 25 名或更少开发人员的团队免费。
  * [Guardfos Scanner](https://guardfos.com/scanner) - 免费在线 WordPress 安全扫描器。无需信用卡或帐户。结果立即可用。
  * [HasMySecretLeaked](https://gitguardian.com/hasmysecretleaked) - 免费搜索公共 GitHub 存储库、要点、问题和评论中的 2000 万个暴露的秘密
  * [Have I been pwned?](https://haveibeenpwned.com) - 用于获取违规信息的 REST API。
  * [HimitsuShell](https://himitsushell.com) - shell 脚本 DRM 编译器，使用嵌入式 shell 解释器和反调试(shc 的替代方案)将 shell 脚本转换为混淆的二进制文件。免费无限网络版。
  * [hostedscan.com](https://hostedscan.com) - 适用于 Web 应用程序、服务器和网络的在线漏洞扫描器。/月十次免费扫描。
  * [Infisical](https://infisical.com/) - 开源平台可让您管理整个团队和基础设施中的开发人员机密：从本地开发到登台/生产第三方服务。最多 5 名开发者免费。
  * [Internet.nl](https://internet.nl) - 测试现代互联网标准，如 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE
  * [IntoDNS.ai](https://intodns.ai) - DNS 和电子邮件安全分析器，可检查 SPF、DKIM、DMARC、DNSSEC、BIMI、MTA-STS 和 40 多个黑名单，并提供人工智能驱动的解释和修复建议。 100% 免费，无需注册。
  * [letsencrypt.org](https://letsencrypt.org/) - 免费 SSL 证书颁发机构，其证书受到所有主要浏览器的信任
  * [meterian.io](https://www.meterian.io/) - 监控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 项目的依赖项中的安全漏洞。一个私人项目免费，开源项目不受限制。
  * [Mozilla Observatory](https://observatory.mozilla.org/) - 查找并修复站点中的安全漏洞。
  * [Otterwatch](https://otterwatch.dev/) - 每日 SSL/TLS 证书监控：到期警报(30/7/1 天)、链和 OCSP 吊销检查以及证书透明度颁发历史记录。 5 个域名永久免费，无需信用卡。
  * [Protectumus](https://protectumus.com) - 适用于 PHP 的免费网站安全检查、网站防病毒和服务器防火墙 (WAF)。免费套餐中注册用户的电子邮件通知。
  * [Public Cloud Threat Intelligence](https://cloudintel.himanshuanand.com/) - 针对公共云基础设施的高可信度妥协指标 (IOC)，部分内容可在 github (https://github.com/unknownhad/AWSAttacks) 上找到。完整列表可通过 API 获取
  * [pyup.io](https://pyup.io) - 监控 Python 依赖项是否存在安全漏洞并自动更新。一个私人项目免费，开源项目不受限制。
  * [qualys.com](https://www.qualys.com/community-edition) - 查找 Web 应用程序漏洞，审核 OWASP 风险
  * [SikkerKey](https://sikkerkey.com) - 机器验证的机密管理器，包括 2 个项目、2 个引导机器、20 个机密和免费 7 天审核日志保留。
  * [Smart Grow Vault](https://vault.smart-grow.app/) - 用于管理环境变量和机密的安全企业级平台。免费套餐包括每个项目最多 3 个应用程序和 150 个机密。
  * [Socket](https://socket.dev) - 为个人开发者、小型团队和开源项目提供免费的供应链安全。包括免费的应用程序和防火墙 CLI 工具，可保护您的代码免受易受攻击和恶意依赖项的影响。检测 70 多个供应链风险指标。
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) - 对任何 SSL Web 服务器的配置进行深入分析
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免费网站安全检查和恶意软件扫描程序
  * [TestTLS.com](https://testtls.com) - 测试 SSL/TLS 服务的安全服务器配置、证书、链等。不限于 HTTPS。
  * [Virgil Security](https://virgilsecurity.com/) - 用于在数字解决方案中实施端到端加密、数据库保护、物联网安全等的工具和服务。对于最多 250 个用户的应用程序免费。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="authentication-authorization-and-user-management"></a>
## 认证、授权和用户管理

  * [360username](https://360username.com/) - 一款免费工具，可在 90 多个社交平台上搜索用户名以查找匹配的个人资料。
  * [Aserto](https://www.aserto.com) - 细粒度授权作为应用程序和 API 的服务。释放最多 1000 个 MAU 和 100 个授权者实例。
  * [asgardeo.io](https://wso2.com/asgardeo) - 无缝集成 SSO、MFA、无密码身份验证等。包括前端和后端应用程序的 SDK。释放最多 1000 个 MAU 和五个身份提供商。
  * [Auth0](https://auth0.com/) - 托管 SSO。免费计划包括 25,000 个 MAU、无限的社交连接、自定义域等等。
  * [Authgear](https://www.authgear.com) - 只需几分钟即可将无密码、OTP、2FA、SSO 引入您的应用程序。包括所有前端。释放最多 5000 个 MAU。
  * [Authress](https://authress.io/) - 身份验证登录和访问控制，任何项目的无限身份提供者。脸书、谷歌、推特等。前 1000 次 API 调用免费。
  * [Authy](https://authy.com) - 多个设备上的双因素身份验证 (2FA)，并带有备份。 Google 身份验证器的直接替代品。最多 100 次成功的身份验证免费。
  * [Cerbos Hub](https://www.cerbos.dev/product-cerbos-hub) - 用于编写、测试和部署访问策略的完整授权管理系统。细粒度的授权和访问控制，/月最多释放 100 个活跃委托人。
  * [Clerk](https://clerk.com) - 用户管理、身份验证、2FA/MFA、用于登录、注册、用户配置文件等的预构建 UI 组件。免费计划包括无限制的应用程序、每个应用程序 50,000 MRU 限制、3 个仪表板席位等。
  * [Cloud-IAM](https://www.cloud-iam.com/) - Keycloak 身份和访问管理即服务。释放最多 100 个用户和 1 个领域。
  * [Descope](https://www.descope.com/) - 高度可定制的 AuthN 流程，采用无代码和 API/SDK 方法，/月免费 7,500 个活跃用户，50 个租户(最多 5 个 SAML/SSO 租户)。
  * [duo.com](https://duo.com/) - 网站或应用程序的双因素身份验证 (2FA)。十个用户免费，所有身份验证方法，无限制，集成，硬件令牌。
  * [Kinde](https://kinde.com/) - 简单、强大的身份验证可以在几分钟内与您的产品集成。  开始使用 7,500 个免费月活跃用户所需的一切。
  * [logintc.com](https://www.logintc.com/) - 通过推送通知进行双因素身份验证 (2FA)，十个用户免费、VPN、网站和 SSH
  * [Logto](https://logto.io/) - 开发、保护和管理产品的用户身份 - 用于身份验证和授权。最多 5,000 个 MAU 免费，并提供开源自托管选项。
  * [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在几分钟内轻松地在您的 Web、移动设备或任何应用程序上实施无密码身份验证。
  * [Okta](https://developer.okta.com/signup/) - 用户管理、认证和授权。/月最多 100 名活跃用户免费。
  * [Ory](https://ory.sh/) - AuthN/AuthZ/OAuth2.0/零信任托管安全平台。具有所有安全功能的永久免费开发者帐户、无限的团队成员、200 个每日活跃用户和 25k/月 权限检查。
  * [Permit.io](https://permit.io) - 授权即服务提供商平台支持 RBAC、ABAC 和 ReBAC，以实现具有实时更新和无代码策略 UI 的可扩展微服务。/月 1000 名活跃用户的免费套餐。
  * [Phase Two](https://phasetwo.io) - Keycloak 开源身份和访问管理。免费领域最多可容纳 1000 个用户，最多 10 个 SSO 连接，利用 Phase Two 的 Keycloak 增强容器(其中包括[Organization](https://phasetwo.io/product/organizations/)扩展)。
  * [PropelAuth](https://propelauth.com) - A 通过几行代码立即向任何规模的公司销售，免费最多 200 个用户和 10k 事务电子邮件(带有水印品牌：“Powered by PropelAuth”)。
  * [Scalekit](https://scalekit.com) - B2B SaaS 的企业 SSO(SAML、OIDC)、SCIM 配置和社交登录。免费套餐包括 100 万个 MAU、100 个组织、1 个 SSO 连接和 1 个 SCIM 连接。
  * [Stack Auth](https://stack-auth.com) - 开源身份验证并不糟糕。对开发人员最友好的解决方案，只需五分钟即可开始使用。免费自行托管，或提供托管 SaaS 版本，/月有 10,000 个免费活跃用户。
  * [Stytch](https://www.stytch.com/) - 一个一体化平台，提供用于身份验证和预防欺诈的 API 和 SDK。免费计划包括 10,000 个/月活跃用户、无限组织、5 个 SSO 或 SCIM 连接以及 1,000 个 M2M 令牌。
  * [SuperTokens](https://supertokens.com/) - 本机集成到您的应用程序中的开源用户身份验证 - 使您能够快速入门，同时控制用户和开发人员体验。最多 5000 个月活跃用户免费。
  * [WorkOS](https://workos.com/) - 最多 100 万月活跃用户的免费用户管理和身份验证。支持电子邮件+密码、社交身份验证、Magic Auth、MFA 等。
  * [ZITADEL Cloud](https://zitadel.com) - 适合您并支持多租户 (B2B) 使用案例的交钥匙用户和访问管理。免费最多可处理 25,000 个经过身份验证的请求，并具有所有安全功能(OTP、无密码、策略等无需付费)。


**[⬆️ 返回顶部](#table-of-contents)**

<a id="mobile-app-distribution-and-feedback"></a>
## 移动应用分发和反馈

  * [Appho.st](https://appho.st) - 移动应用托管平台。免费计划包括五个应用程序、/月 50 次下载、最大文件大小为 100 MB。
  * [Diawi](https://www.diawi.com) - 将 iOS 和 Android 应用程序直接部署到设备。免费计划：应用程序上传、受密码保护的链接、1 天过期、十次安装。
  * [GetUpdraft](https://www.getupdraft.com) - 分发移动应用程序以进行测试。免费计划包括 1 个应用程序项目、3 个应用程序版本、500 MB 存储空间以及/月 100 次应用程序安装。
  * [InstallOnAir](https://www.installonair.com) - 通过无线方式分发 iOS 和 Android 应用程序。免费计划：无限制上传、私人链接、访客有效期为 2 天、注册用户有效期为 60 天。
  * [Loadly](https://loadly.io) - iOS和Android测试版应用程序分发服务提供完全免费的服务，无限下载、高速下载和无限上传。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="management-system"></a>
## 管理系统

  * [bitnami.com](https://bitnami.com/) - 在 IaaS 上部署准备好的应用程序。免费管理 1 个 AWS 微型实例
  * [Esper](https://esper.io) - 适用于具有 DevOps 的 Android 设备的 MDM 和 MAM。一份用户许可证和 25 MB 应用程序存储空间可免费使用 100 台设备。
  * [jamf.com](https://www.jamf.com/) -  iPad、iPhone 和 Mac 的设备管理，三台设备免费
  * [Miradore](https://miradore.com) - 设备管理服务。随时了解您的设备群的最新情况并免费保护无限的设备。免费计划提供基本功能。
  * [ploi.io](https://ploi.io/) - 服务器管理工​​具可轻松管理和部署您的服务器和站点。 Free for one server.
  * [runcloud.io](https://runcloud.io/) - 服务器管理主要侧重于PHP项目。 Free for up to 1 server.
  * [serveravatar.com](https://serveravatar.com) - 通过自动化配置管理和监控基于 PHP 的 Web 服务器。 Free for one server.
  * [xcloud.host](https://xcloud.host) - 服务器管理和部署平台，具有用户友好的界面。一台服务器可享受免费套餐。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="messaging-and-streaming"></a>
## 消息和流处理

  * [Ably](https://www.ably.com/) - 具有存在性、持久性和有保证的传递的实时消息传递服务。免费计划包括/月 300 万条消息、100 个峰值连接和 100 个峰值通道。
  * [cloudamqp.com](https://www.cloudamqp.com/) - RabbitMQ as a Service. Little Lemur 计划：/月最多 100 万条消息，最多 20 个并发连接，最多 100 个队列，最多 10,000 条排队消息，不同可用区中的多个节点
  * [courier.com](https://www.courier.com/) - 用于推送、应用内、电子邮件、聊天、短信和其他消息传递渠道的单一 API，具有模板管理和其他功能。免费计划包括/月 10,000 条消息。
  * [EMQX Serverless](https://www.emqx.com/en/cloud/serverless-mqtt) - 您可以在几秒钟内获得可扩展且安全的无服务器 MQTT 代理。/月 100 万分钟的会话时间永久免费(无需信用卡)。
  * [Engage](https://engage.so/) - 适用于 SaaS 的一体化客户参与和自动化工具(电子邮件、推送、短信、产品导览、横幅等)。/月最多 1,000 名活跃用户免费。
  * [engagespot.co](https://engagespot.co/) - 为开发人员提供的多渠道通知基础设施，具有预构建的应用内收件箱和无代码模板编辑器。免费计划包括/月 10,000 条消息。
  * [HiveMQ](https://www.hivemq.com/mqtt-cloud-broker/) - 将您的 MQTT 设备连接到云原生 IoT 消息传递代理。  永久免费连接最多 100 个设备(无需信用卡)。
  * [httpSMS](https://httpsms.com) - 使用 Android 手机作为短信网关发送和接收短信。/月最多可免费发送和接收 200 条消息。
  * [knock.app](https://knock.app) - 开发人员的通知基础设施。通过单个 API 调用发送到多个渠道，例如应用内、电子邮件、短信、Slack 和推送。免费计划包括/月 10,000 条消息。
  * [Novu.co](https://novu.co) - 面向开发人员的开源通知基础设施。用于在一处管理所有通信渠道的简单组件和 API：电子邮件、短信、直接、应用内和推送。免费计划包括/月 30,000 条通知，并保留 90 天。
  * [Pingram.io](https://www.pingram.io/) - 5 分钟内建立通信基础设施。免费套餐包括：100 条短信和通话、3000 封电子邮件、推送、Slack、MS Teams、WhatsApp 等。
  * [Pocket Alert](https://pocketalert.app) - 向您的 iOS 和 Android 设备发送推送通知。通过 API 或 Webhooks 轻松集成，并保持对警报的完全控制。免费计划：/天向 1 台设备和 1 个应用程序发送 50 条消息。
  * [pubnub.com](https://www.pubnub.com/) - Swift、Kotlin 和 React 消息传递/月处理 100 万笔交易。事务可能包含多个消息。
  * [pusher.com](https://pusher.com/) - 实时消息服务。/天免费最多 100 个并发连接和 200,000 条消息
  * [scaledrone.com](https://www.scaledrone.com/) - 实时消息服务。/天免费最多 20 个并发连接和 100,000 个事件
  * [SMSGate](https://sms-gate.app) - SMS Gateway for Android™ 支持使用云路由通过您的设备发送和接收 SMS 消息。完全免费的云服务(建议/天使用超过 10,000 条消息时发出通知，以保持所有用户的质量)。
  * [SuprSend](https://www.suprsend.com/) - SuprSend 是一个通知基础架构，可通过 API 优先的方法简化您的产品通知。使用单个通知 API 在多个渠道上创建和交付事务、crons 和参与通知。在免费计划中，您/月会收到 10,000 条通知，包括不同的工作流程节点，例如摘要、批次、多渠道、首选项、租户、广播等。
  * [synadia.com](https://synadia.com/ngs) - [NATS.io](https://nats.io)as a service.全球、AWS、GCP 和 Azure。永久免费，/月 4k 消息大小、50 个活动连接和 5GB 数据。
  * [webpushr](https://www.webpushr.com/) - 网络推送通知 - 最多 10k 订阅者免费、无限制的推送通知、浏览器内消息传递
  * [vask](https://vask.dev) - 实时消息服务，兼容 Pusher。开发层仅限于本地开发，并且免费，具有 100 个并发连接、/月 1,000,000 次广播、无限制的客户端事件、32kb 消息大小。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="log-management"></a>
## 日志管理

  * [bugfender.com](https://bugfender.com/) - /天释放多达 100k 日志行并保留 24 小时
  * [log.dog](https://log.dog/) - LogDog 是一个带有 Web UI 的远程调试/日志记录 SDK(iOS 和 Android)。实时捕获所有日志、请求和事件并允许拦截它们。/月最多免费使用 100MB 日志
  * [logflare.app](https://logflare.app/) - 每个应用/月最多可免费使用 12,960,000 个条目，保留 3 天
  * [logtail.com](https://logtail.com/) - 基于ClickHouse的SQL兼容日志管理。/月最多免费 1 GB，保留三天。
  * [logzab.com](https://logzab.com/) - 审计追踪管理系统。/月免费提供 1,000 个用户活动日志，保留 1 个月，最多可用于 5 个项目。
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-siem/) - 由 Manage Engine 提供支持的日志管理服务。免费计划提供 50 GB 存储空间、15 天存储保留和 7 天搜索时间。
  * [openobserve.ai](https://openobserve.ai/) - /月免费获取 200 GB，保留 15 天
  * [Smart Grow Logs](https://logs.smart-grow.app/) - 具有端到端加密、实时警报和多平台 SDK 的集中式日志管理平台。免费套餐/天最多包含 3.000 个日志。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="translation-management"></a>
## 翻译管理

  * [AutoLocalise.com](https://www.autolocalise.com/) - 立即本地化，无需管理翻译文件。/月最多可免费使用 10,000 个字符，语言不限。
  * [crowdin.com](https://crowdin.com/) - 无限的项目、无限的字符串和开源合作者
  * [Free PO editor](https://pofile.net/free-po-editor) - Free for everybody
  * [Lingo.dev](https://lingo.dev) - 用于 Web 和移动本地化的开源 AI 驱动 CLI。自带 LLM，或通过 Lingo.dev 托管的本地化引擎每月使用 10,000 个免费单词。
  * [lingohub.com](https://lingohub.com/) - 免费最多 3 个用户，始终免费开源
  * [Localhero.ai](https://localhero.ai) - 根据每个Pull Request自动进行品牌翻译，并带有术语表和翻译记忆库。 1 个项目免费，/月 250 个翻译学分(约 4,000 字)。
  * [localazy.com](https://localazy.com) - 免费提供 1000 种源语言字符串、无限语言、无限贡献者、启动和开源交易
  * [Localit](https://localit.io) - 快速、开发人员友好的本地化平台，具有无缝且免费的 GitHub/GitLab 集成、人工智能辅助和手动翻译以及慷慨的免费计划(包括 2 个用户、500 个密钥和无限的项目)。
  * [localizely.com](https://localizely.com/) - Free for Open Source
  * [Loco](https://localise.biz/) - 免费提供多达 2000 种翻译、无限制翻译人员、十种语言/项目、1000 个可翻译资产/项目
  * [POEditor](https://poeditor.com/) - Free up to 1000 strings
  * [SimpleLocalize](https://simplelocalize.io/) - 免费多达 100 个翻译键、无限字符串、无限语言、启动优惠
  * [Texterify](https://texterify.com/) - Free for a single user
  * [Tolgee](https://tolgee.io) - 免费 SaaS 产品，翻译有限，永久免费的自托管版本
  * [transifex.com](https://www.transifex.com/) - Free for Open Source

**[⬆️ 返回顶部](#table-of-contents)**

<a id="monitoring"></a>
## 监控

  * [assertible.com](https://assertible.com) - 自动化 API 测试和监控。为团队和个人提供免费计划。
  * [Better Stack](https://betterstack.com/better-uptime) - 单一产品中的正常运行时间监控、事件管理、待命调度/警报和状态页面。免费计划包括 10 个监视器，每 3 分钟检查一次频率和状态页面。
  * [bleemeo.com](https://bleemeo.com) - 免费用于 3 台服务器、5 个正常运行时间监视器、无限用户、无限仪表板、无限警报规则。
  * [checklyhq.com](https://checklyhq.com) - 为开发人员提供开源 E2E/综合监控和深度 API 监控。一名用户的免费计划和 10k API 和网络/1.5k 浏览器检查运行。
  * [Core Web Vitals History](https://punits.dev/core-web-vitals-historical/) - 查找 URL 或网站的 Core Web Vitals 历史记录。
  * [cronitor.io](https://cronitor.io/) - 针对 cron 作业、网站、API 等的性能洞察和正常运行时间监控。具有五个显示器的免费套餐。
  * [datadoghq.com](https://www.datadoghq.com/) - 最多 5 个节点免费
  * [deadmanssnitch.com](https://deadmanssnitch.com/) - 监控 cron 作业。一名免费告密者(监视器)，如果您推荐其他人注册，则可以提供更多
  * [downtimemonkey.com](https://downtimemonkey.com/) - 60 个正常运行时间监视器，间隔 5 分钟。电子邮件、Slack 警报。
  * [drumbeats.io](https://drumbeats.io/) - 通过事件管理和状态页面进行 Cron、心跳和正常运行时间监控。免费供最多 50 名显示器使用，间隔时间为 1 分钟，团队席位不受限制。
  * [economize.cloud](https://economize.cloud) - Economize 通过组织云资源进行优化和报告，帮助揭开云基础设施成本的神秘面纱。/月在 Google Cloud Platform 上消费最多 5,000 美元即可免费。
  * [fivenines.io](https://fivenines.io/) - 通过实时仪表板和警报对 Linux 服务器进行监控 - 最多 5 台受监控的服务器以 60 秒的间隔永久无警报。无需信用卡。
  * [FlareWarden](https://flarewarden.com) - 通过多区域验证和状态页面进行正常运行时间、内容、依赖性和 SSL 监控。免费计划包括 15 个监视器、5 分钟检查和 90 天的历史记录。
  * [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloud 是一个可组合的可观察性平台，它将指标和日志与 Grafana 集成。免费：3 个用户、10 个仪表板、100 个警报、Prometheus 和 Graphite 中的指标存储(10,000 个系列，保留 14 天)、Loki 中的日志存储(50 GB 日志，保留 14 天)
  * [healthchecks.io](https://healthchecks.io) - 监控您的 cron 作业和后台任务。最多 20 张支票免费。
  * [incidenthub.cloud](https://incidenthub.cloud/) - 云和 SaaS 状态页面聚合器 - 20 个监视器和 2 个通知渠道(Slack 和 Discord)永久免费。
  * [inspector.dev](https://www.inspector.dev) - 不到一分钟即可完成完整的实时监控仪表板，并且永久免费。
  * [instatus.com](https://instatus.com) - 10 秒内获得漂亮的状态页面。永久免费，无限订阅者和无限团队。
    * [isitdownstatus.com](https://isitdownstatus.com)– 免费公共 JSON API，返回 500 多个流行服务(GitHub、Stripe、AWS 等)的实时状态。无需身份验证，已启用 CORS。
  * [linkok.com](https://linkok.com) - 在线损坏链接检查器，对于 100 页以下的小型网站免费，对于开源项目完全免费。
  * [loader.io](https://loader.io/) - 免费负载测试工具，但有限制
  * [MarionetteOps.com](https://www.marionetteops.com/) - 服务器监控、公共状态页面和服务正常运行时间监控。
  * [Middleware.io](https://middleware.io/) -  中间件可观察性平台提供对应用程序和堆栈的完整可见性，因此您可以大规模监控和诊断问题。他们有一个供开发社区使用的永久免费计划，允许对多达 100 万个日志事件进行日志监控，对多达 2 台主机进行基础设施监控和 APM。
  * [MonitorMonk](https://monitormonk.com) - 极简的正常运行时间监控与漂亮的状态页面。永久免费计划为 10 个网站或 api 端点提供 HTTPS、关键字、SSL 和响应时间监控，并提供 2 个仪表板/状态页面。
  * [netdata.cloud](https://www.netdata.cloud/) - Netdata 是一个用于收集实时指标的开源工具。这是一个不断发展的产品，也可以在 GitHub 上找到！
  * [newrelic.com](https://www.newrelic.com) - 全新Relic可观测平台旨在帮助工程师创建更完美的软件。从单体应用到无服务器，您可以检测所有内容，然后分析、排除故障并优化整个软件堆栈。免费套餐提供 100GB/月的免费数据摄取、一名免费的完全访问用户和无限制的免费主要用户。
  * [OnlineOrNot.com](https://onlineornot.com/) - OnlineOrNot 提供网站和 API 的正常运行时间监控、cron 作业和计划任务的监控。还提供状态页面。前五次检查免费，间隔 3 分钟。免费套餐通过 Slack、Discord 和电子邮件发送警报。
  * [OntarioNet.ca CN Test](https://cntest.ontarionet.ca) - 检查某个网站在中国是否被防火墙屏蔽。它通过比较中国服务器与美国服务器检测到的 DNS 结果和 ASN 信息来识别 DNS​​ 污染。
  * [pagecrawl.io](https://pagecrawl.io/) -  监控网站更改，最多可免费供 6 个监控器进行每日检查。
  * [pagertree.com](https://pagertree.com/) - 用于警报和待命管理的简单界面。释放最多 5 个用户。
  * [phare.io](https://phare.io/) - 正常运行时间免费监控多达 100,000 个事件、无限的项目和无限的状态页面。
  * [pingbreak.com](https://pingbreak.com/) - 现代正常运行时间监控服务。检查无限的 URL 并通过 Discord、Slack 或电子邮件获取停机通知。
  * [Pingmeter.com](https://pingmeter.com/) - 5 个正常运行时间监视器，间隔 10 分钟。监控 SSH、HTTP、HTTPS 和任何自定义 TCP 端口。
  * [pingpong.one](https://pingpong.one/) - 带监控的高级状态页面平台。免费套餐包括一个带有 SSL 子域的公共可定制状态页面。 Pro 计划免费提供给开源项目和非营利组织。
  * [Prismix](https://prismix.dev) - 免费的 REST API (GET /api/v1/statuses) 返回超过 75 个 AI 服务的实时运行状态，包括 OpenAI、Anthropic、Gemini、Mistral 等。无需身份验证。 [Pro 版提供免费套餐，价格为 10 美元/月]
  * [Pulsetic](https://pulsetic.com) - 10 个监视器、6 个月的历史正常运行时间/日志、无限的状态页面和自定义域！免费无限时间和无限电子邮件提醒。您不需要信用卡。
  * [robusta.dev](https://home.robusta.dev/) - 基于Prometheus的强大Kubernetes监控。带上您自己的 Prometheus 或安装一体化捆绑包。免费套餐包含最多 20 个 Kubernetes 节点。通过 Slack、Microsoft Teams、Discord 等发出警报。与 PagerDuty、OpsGenie、VictorOps、DataDog 和许多其他工具集成。
  * [Runframe](https://runframe.io/) - 待命警报、事件管理和公共/私人状态页面。免费计划包括最多 5 个用户、1 个团队、1 个待命计划、基本状态页面、事件生命周期和 Slack 本机事件响应。
  * [Servervana](https://servervana.com) - 高级正常运行时间监控，支持大型项目和团队。提供HTTP监控、基于浏览器的监控、DNS监控、域监控、状态页面等。免费套餐包括 10 个 HTTP 监视器、1 个 DNS 监视器和 1 个状态页面。
  * [Simple Observability](https://simpleobservability.com) - 在统一平台中对指标和日志进行强大的服务器监控，无需设置复杂性。一台服务器免费。
  * [sitesure.net](https://sitesure.net) - 网站和 cron 监控 - 2 个免费监视器
  * [skylight.io](https://www.skylight.io/) - 前 100,000 个请求免费(仅限 Rails)
  * [statuscake.com](https://www.statuscake.com/) - 网站监控，无限制免费测试，有限制
  * [statusgator.com](https://statusgator.com/) - 状态页监控，3个监控空闲
  * [supaguard.app](https://supaguard.app/) - 来自全球 20 多个地区的综合监控。免费套餐包括/月 1,000 次浏览器检查，具有人工智能驱动的自我修复和自动测试生成功能。
  * [SweetUptime](https://dicloud.net/sweetuptime-server-uptime-monitoring/) - 服务器监控、正常运行时间监控、DNS 和域监控。免费监控 10 个服务器、10 个正常运行时间和 10 个域。
  * [syagent.com](https://syagent.com/) - 非商业免费服务器监控服务、警报和指标。
  * [UptimeObserver.com](https://uptimeobserver.com) - 获取 20 个运行时间监视器，间隔为 5 分钟，并可自定义状态页面 - 甚至可用于商业用途。通过电子邮件和 Telegram 享受无限的实时通知。无需信用卡即可开始。
  * [uptimetoolbox.com](https://uptimetoolbox.com/) - 免费监控五个网站，间隔3分钟，公共状态页。
  * [Wachete](https://www.wachete.com) - 监控五个页面，每 24 小时检查一次。
  * [Xitoring.com](https://xitoring.com/) - 正常运行时间监控：20 个免费，Linux 和 Windows Server 监控：5 个免费，状态页面：1 个免费 - 移动应用程序、多个通知渠道等等！
  * [UptimeRobot](https://uptimerobot.com/) - 业余爱好项目的免费正常运行时间监控。包括 50 个监视器，检查间隔为 5 分钟，支持 HTTP、ping、端口和关键字监控。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="crash-and-exception-handling"></a>
## 崩溃和异常处理

  * [Axiom](https://axiom.co/) - 存储最多 0.5 TB 的日志，保留期为 30 天。包括与 Vercel 等平台的集成以及通过电子邮件/Discord 通知程序进行高级数据查询。
  * [Bugsink](https://www.bugsink.com/) - 具有 Sentry-SDK 兼容性的错误跟踪。/月最多可免费使用 5,000 个错误，或者在自行托管时无限制使用。
  * [bugsnag.com](https://www.bugsnag.com/) - 初次试用后/月最多可免费解决 2,000 个错误
  * [CatchJS.com](https://catchjs.com/) - 通过屏幕截图和点击轨迹进行 JavaScript 错误跟踪。对于开源项目免费。
  * [elmah.io](https://elmah.io/) - Web 开发人员的错误记录和正常运行时间监控。免费小型企业订阅开源项目。
  * [Embrace](https://embrace.io/) - 移动应用程序监控。对于/年不超过 100 万次用户会话的小型团队免费。
  * [exceptionless](https://exceptionless.com) - 实时错误、功能、日志报告等。/月/1 位用户免费参加 3000 场活动。开源且易于自行托管，可无限使用。
  * [GlitchTip](https://glitchtip.com/) - 简单、开源的错误跟踪。兼容开源 Sentry SDK。每月免费 1000 个事件，也可以自行托管且不受限制。
  * [honeybadger.io](https://www.honeybadger.io) - 异常、正常运行时间和 cron 监控。对小型团队和开源项目免费(每月 12,000 个错误)。
  * [Jam](https://jam.dev) - 一键生成对开发者友好的错误报告。免费计划提供无限报告。
  * [memfault.com](https://memfault.com) - 云设备观测与调试平台。[Nordic](https://app.memfault.com/register-nordic)、[NXP](https://app.memfault.com/register-nxp)和[Laird](https://app.memfault.com/register-laird)设备可免费使用 100 台设备。
  * [rollbar.com](https://rollbar.com/) - 异常和错误监控、/月 5,000 个错误的免费计划、无限用户、30 天保留
  * [Semaphr](https://semaphr.com) - 为您的移动应用程序提供免费的一体化终止开关。
  * [sentry.io](https://sentry.io/) - Sentry 实时跟踪应用程序异常，并有一个小型免费计划。/月 5000 个错误/1 个用户免费，如果自托管则不受限制使用
  * [Whitespace](https://whitespace.dev) - 直接在浏览器中一键生成错误报告。个人使用的免费计划提供无限录制。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="search"></a>
## 搜索

  * [algolia.com](https://www.algolia.com/) - 托管搜索解决方案具有拼写错误、相关性和 UI 库，可轻松创建搜索体验。免费的“Build”计划包括/月 100 万个文档和 10K 次搜索。 Also offers[developer documentation search](https://docsearch.algolia.com/)for free.
  * [bonsai.io](https://bonsai.io/) - 免费 1 GB 内存和 1 GB 存储
  * [CommandBar](https://www.commandbar.com/) - 统一搜索栏即服务、基于 Web 的 UI 小部件/插件，允许您的用户在您的产品中搜索内容、导航、功能等，这有助于发现。最多 1,000 名/月活跃用户免费，命令无限制。
  * [searchly.com](http://www.searchly.com/) - 免费 2 个索引和 20 MB 存储

**[⬆️ 返回顶部](#table-of-contents)**

<a id="education-and-career-development"></a>
## 教育和职业发展

  * [Cisco Networking Academy, Skills for All](https://skillsforall.com/) - 提供网络安全、网络和 Python 等主题的免费认证课程。
  * [CloudCertPrep](https://cloudcertprep.io) - 免费的开源 AWS 认证模拟考试，包含 1,050 多个 CLF-C02 问题。具有定时模拟考试、领域练习、间隔重复和进度跟踪等功能。
  * [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) - 行业领先专家的免费短期课程，在一小时或更短的时间内获得最新的生成式人工智能工具和技术的实践经验。
  * [DevNet Academy](https://devnet-academy.com/) - 思科 DevNet 专家/CCIE 自动化认证的免费自定进度培训。涵盖 Python Click 和 Flask-RESTx。
  * [Django-tutorial.dev](https://django-tutorial.dev) - 免费在线指南，用于学习 Django 作为他们的第一个框架，并提供用户撰写的文章的免费 dofollow 反向链接。
  * [edX](https://www.edx.org/) - 提供来自 250 个领先机构(包括哈佛大学和麻省理工学院)的 4,000 多门免费在线课程，专门从事计算机科学、工程和数据科学。
  * [Exercism](https://exercism.org) - 提供超过 75 种编程语言的免费开源编程教育，并提供人工指导。一个非营利组织。
  * [Free Professional Resume Templates & Editor](https://www.overleaf.com/latex/templates/tagged/cv) - 免费平台，拥有大量经验丰富的专业人士的简历模板，可完全克隆、编辑和下载，ATS 已优化。
  * [FreeCodeCamp](https://www.freecodecamp.org/) - 开源平台提供数据分析、信息安全、Web 开发等方面的免费课程和认证。
  * [Full Stack Open](https://fullstackopen.com/en/) - 关于使用 React、Node.js、GraphQL、TypeScript 等进行现代 Web 开发的免费大学水平课程。 Fully online and self-paced.
  * [Interactive CV](https://interactive-cv.com) - 由人工智能驱动的简历生成器，具有实时编辑和 ATS 优化功能。免费套餐包括将简历自动转换为高级模板(Harvard、Europass)、PDF 导出、具有无限职位发布见解的职位跟踪器以及具有聊天/语音功能的简历共享。
  * [Khan Academy](https://www.khanacademy.org/computing/computer-programming) - 用于学习基础和高级 HTML/CSS、JavaScript 和 SQL 的免费在线指南。
  * [LabEx](https://labex.io) - 通过交互式实验室和实际项目培养 Linux、DevOps、网络安全、编程、数据科学等方面的技能。
  * [MIT OpenCourseWare](https://ocw.mit.edu/) - MIT OpenCourseWare 是一个在线出版物，包含来自 2,500 多门 MIT 课程的材料，与世界各地的学习者和教育工作者免费分享知识。 YouTube 频道可在[@mitocw](https://www.youtube.com/@mitocw/featured)找到
  * [Reactive Resume](https://rxresu.me) - 免费、开源的简历生成器，包含数十个模板。导出为 PDF、DOCX，并提供可公开共享的简历链接(选择加入)。
  * [Roadmap.sh](https://roadmap.sh) - 免费学习路线图涵盖从区块链到用户体验设计的所有开发方面。
  * [The Odin Project](https://www.theodinproject.com/) - 免费的开源平台，其课程重点关注用于 Web 开发的 JavaScript 和 Ruby。
  * [W3Schools](https://www.w3schools.com/) - 提供有关 HTML、CSS、JavaScript 等 Web 开发技术的免费教程。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="email"></a>
## 电子邮件

  * [10minutemail](https://10minutemail.com) - 用于测试的免费临时电子邮件。
  * [AhaSend](https://ahasend.com) - 事务性电子邮件服务，/月免费发送 1000 封电子邮件，免费计划中提供无限的域名、团队成员、网络钩子和消息路由。
  * [AnonAddy](https://anonaddy.com) - 开源匿名邮件转发，免费创建无限量的邮件别名
  * [anon.li Alias](https://anon.li/alias) - 开源、匿名电子邮件别名/转发解决方案，具有 PGP 加密、回复功能、免费计划中的 10 个随机别名和 1 个自定义别名，以及开发人员 API 和 CLI。
  * [Antideo](https://www.antideo.com) - 免费套餐中每小时 10 个 API 请求，用于电子邮件验证、IP 和电话号码验证。不需要信用卡。
  * [Brevo](https://www.brevo.com/) - /月 9,000 封电子邮件，/天 300 封电子邮件免费
  * [Bump](https://bump.email/) - 免费 10 个 Bump 邮箱地址和 1 个自定义域名
  * [Burnermail](https://burnermail.io/) - 免费 5 个刻录电子邮件地址、1 个邮箱、7 天邮箱历史记录
  * [Buttondown](https://buttondown.email/) - 时事通讯服务。最多 100 名订阅者免费
  * [Conduit](https://conduit.email/) - 将传入的电子邮件转换为 Webhook，以从电子邮件触发您的 API。该服务完全免费。
  * [Contact.do](https://contact.do/) - 链接中的联系表(联系表的位)
  * [debugmail.io](https://debugmail.io/) - 易于开发人员使用的测试邮件服务器
  * [dkimvalidator.com](https://dkimvalidator.com/) - 测试电子邮件的 DNS/SPF/DKIM/DMARC 设置是否正确，由 roundsphere.com 提供的免费服务
  * [DNSExit](https://dnsexit.com/) - 您的域名下最多可免费使用 2 个电子邮件地址，并可享受 100MB 的存储空间。 IMAP、POP3、SMTP、SPF/DKIM 支持。
  * [EmailGuard](https://emailguard.lazrek.net/) - 通过简单的 API 阻止一次性电子邮件、捕获拼写错误并验证 MX 记录。/月 100 个免费请求。
  * [EmailJS](https://www.emailjs.com/) - This is not an entire email server;这只是一个电子邮件客户端，您可以使用它直接从客户端发送电子邮件，而无需暴露您的凭据，免费套餐有 200 个/月请求、2 个电子邮件模板、最多 50Kb 的请求、有限的联系人历史记录。
  * [EmailLabs.io](https://emaillabs.io/en) - /月免费发送多达 9,000 封电子邮件，/天最多发送 300 封电子邮件。
  * [EmailQo Email Infrastructure Grader](https://emailqo.com/email-grader) - 免费电子邮件基础设施分级器，用于检查 SPF、DKIM、DMARC 和邮件服务器配置。任何域名满分 100 分。无需注册。
  * [EmailOctopus](https://emailoctopus.com) - /月最多 2,500 名订阅者和 10,000 封电子邮件免费
  * [Emailvalidation.io](https://emailvalidation.io) - 每月 100 次免费电子邮件验证
  * [Emitlo](https://emitlo.com) - /月免费 12,000 封电子邮件，电子邮件 API 和 SMTP、SPF/DKIM/DMARC 支持，无需信用卡。
  * [EtherealMail](https://ethereal.email) - Ethereal是一个假冒的SMTP服务，主要针对Nodemailer和EmailEngine用户(但不限于)。这是一种完全免费的反交易电子邮件服务，消息永远不会被传递。
  * [forwardemail.net](https://forwardemail.net) - Free email forwarding for custom domains.使用您的域名创建和转发无限数量的电子邮件地址(**注意**：如果您因垃圾邮件而使用 .casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、.lat、.loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work TLD，则必须付费)
  * [Imitate Email](https://imitate.email) - 沙盒电子邮件服务器，用于跨 build/qa 和 ci/cd 测试电子邮件功能。 Free accounts get 15 emails a day forever.
  * [ImprovMX](https://improvmx.com) - 免费电子邮件转发。
  * [Inboxes App](https://inboxesapp.com) - /天最多创建 3 封临时电子邮件，然后在完成后通过方便的 Chrome 扩展程序将其删除。 Perfect for testing signup flows.
  * [inboxkitten.com](https://inboxkitten.com/) - 免费的临时/一次性电子邮件收件箱，最多可自动删除 3 天的电子邮件。 Open source and can be self-hosted.
  * [KaiMail](https://kaimail.net) - 使用 ARC/DKIM 签名的自定义域的电子邮件转发。免费计划包括 1 个域名、1 个邮箱、/月 300 封电子邮件以及最多 1MB 的邮件大小。 Email receiving webhook also available. Special plans for open-source projects.
  * [mail-tester.com](https://www.mail-tester.com) - 测试邮件的DNS/SPF/DKIM/DMARC设置是否正确，20免费/月。
  * [Maileroo](https://maileroo.com) - SMTP relay and email API for developers./月 5,000 封电子邮件、无限域名、免费电子邮件验证、黑名单监控、邮件测试器等。
  * [mailcatcher.me](https://mailcatcher.me/) - 捕获邮件并通过 Web 界面提供服务。
  * [mailchannels.com](https://www.mailchannels.com) - 具有 REST API 和 SMTP 集成的电子邮件 API，/月最多可免费发送 3,000 封电子邮件。
  * [Mailcheck.ai](https://www.mailcheck.ai/) - 阻止用户使用临时电子邮件地址注册，每小时 120 个请求(/月约 86,400 个)
  * [Maildroppa](https://maildroppa.com) - 最多 100 个订阅者和无限的电子邮件以及免费的自动化。
  * [MailerLite.com](https://www.mailerlite.com) - /月 1,000 名订阅者，/月免费 12,000 封电子邮件
  * [MailerSend.com](https://www.mailersend.com) - 电子邮件 API、SMTP、/月 3,000 封电子邮件免费用于交易电子邮件
  * [mailinator.com](https://www.mailinator.com/) - 免费的公共电子邮件系统，您可以使用任何您想要的收件箱
  * [Mailjet](https://www.mailjet.com/) - /月 6,000 封电子邮件免费(每日发送限制 200 封电子邮件)
  * [mailsac.com](https://mailsac.com) - 用于临时电子邮件测试的免费 API、免费公共电子邮件托管、出站捕获、电子邮件到 slack/websocket/webhook(/月 1,500 个 API 限制)
  * [Mailtrap.io](https://mailtrap.io/) - 电子邮件 API、SMTP，/月免费发送 3,500 封电子邮件，用于交易和营销电子邮件。电子邮件沙箱 - 用于开发的假 SMTP 服务器，免费计划，包含一个收件箱、100 条消息、无团队成员、每秒两封电子邮件、无转发规则。
  * [Mutant Mail](https://www.mutantmail.com/) - 免费 10 个电子邮件 ID、1 个域名、1 个邮箱。 Single Mailbox for All Email IDs.
  * [OneSignal](https://onesignal.com/) - /月 10,000 封电子邮件，无需信用卡。
  * [Orbisearch](https://orbisearch.com) - 免费批量电子邮件验证器，/天 100 次验证，无需注册。
  * [Parsio.io](https://parsio.io) - 免费电子邮件解析器(转发电子邮件，提取数据，将其发送到您的服务器)
  * [Plunk](https://useplunk.com) - /月免费 3K 封电子邮件
  * [Postmark](https://postmarkapp.com/) - /月 100 封电子邮件免费、无限制的 DMARC /周摘要。
  * [Proton Mail](https://proton.me/mail) -  具有内置端到端加密功能的免费安全电子邮件帐户服务提供商。免费 1GB 存储空间。
  * [Resend](https://resend.com) - Transactional emails API for developers./月 3,000 封电子邮件，/天免费 100 封电子邮件，一个自定义域。
  * [SendBridge Mail Tester](https://sendbridge.com/mail-tester)— 无需注册即可免费进行电子邮件送达率测试。生成唯一的收件箱地址，然后分析 SPF、DKIM、DMARC、Rspamd 垃圾邮件评分、23+ RBL 黑名单、反向 DNS 和内容质量。无限制的测试，几秒钟内得出结果，可共享的报告页面。
  * [Sender](https://www.sender.net) - /月最多 15,000 封电子邮件，最多 2,500 名订阅者
  * [Sendpulse](https://sendpulse.com) - 每月 500 名订阅者、每月 15,000 封电子邮件免费
  * [SendStreak](https://www.sendstreak.com/) - 电子邮件框架即服务，将模板、自动化、历史记录等添加到您自己的 SMTP 服务器(例如 AWS、Maileroo、Gmail)。 Free up to 100 emails/day, no time limit.
  * [SimpleLogin](https://simplelogin.io/) - 开源、自托管电子邮件别名/转发解决方案。免费 10 个别名、无限带宽、无限回复/发送。教育人员(学生、研究人员等)免费。
  * [Substack](https://substack.com) - 无限制的免费通讯服务；当你开始收费时再付费。
  * [Sweego](https://www.sweego.io/) - 面向开发人员的欧洲交易电子邮件 API。/天 100 封电子邮件免费。
  * [temp-mail.io](https://temp-mail.io) - 免费的一次性临时电子邮件服务，一次可转发多封电子邮件
  * [Temp-Mail.org](https://temp-mail.org/en/) - 临时/一次性邮件生成器使用各种域。电子邮件地址每次都会刷新，页面会重新加载。它是完全免费的，不包括其服务的任何定价。
  * [TempMailDetector.com](https://tempmaildetector.com/) - /月免费验证多达 200 封电子邮件，并查看电子邮件是否是临时的。
  * [trashmail.com](https://www.trashmail.com) - 免费的一次性电子邮件地址，具有转发功能和地址自动过期功能
  * [Tuta](https://tuta.com/) - 免费的安全电子邮件帐户服务提供商，内置端到端加密，无广告，无跟踪。免费 1GB 存储空间、一本日历(Tuta 也有一个[paid plan](https://tuta.com/pricing)。)。 Tuta 也部分属于[open source](https://github.com/tutao/tutanota)，因此您可以自行托管。
  * [Verifalia](https://verifalia.com/email-verification-api) - 实时电子邮件验证 API，具有邮箱确认和一次性电子邮件地址检测器； 25 free email verifications/day.
  * [verimail.io](https://verimail.io/) - 批量和 API 电子邮件验证服务。/月 100 次免费验证
  * [Waitlio](https://waitlio.com/) - 用于产品发布的等候名单管理软件。创建品牌等候名单页面，收集和验证电子邮件订阅者，使用标签和分析管理注册。免费计划包括 100 个订阅者/月、1 个候补名单和 API 访问权限。
  * [Wraps](https://wraps.dev) - 电子邮件自动化工作流程、5000 个跟踪事件和无限的免费联系人。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="feature-toggles-management-platforms"></a>
## 功能开关管理平台

  * [Abby](https://www.tryabby.com) - 开源功能标志和 A/B 测试。配置为代码和完全类型化的 Typescript SDK。与 Next.js 和 React 等框架的增强集成。慷慨的免费套餐和廉价的扩展选项。
  * [ConfigCat](https://configcat.com) - ConfigCat 是一项以开发人员为中心的功能标记服务，具有无限的团队规模、出色的支持和合理的价格标签。免费计划/月最多 10 个标志、两个环境、1 个产品和 500 万个请求。
  * [Flagsmith](https://flagsmith.com) - Release features with confidence;跨 Web、移动和服务器端应用程序管理功能标志。使用我们的托管 API、部署到您自己的私有云或在本地运行。
  * [GrowthBook](https://growthbook.io) - 具有内置贝叶斯统计分析引擎的开源功能标志和 A/B 测试提供程序。最多 3 位用户免费，无限制的功能标记和实验。
  * [Rollgate](https://rollgate.io) - 具有计划发布、即时回滚和 A/B 测试的功能标志管理。包含 13 个 SDK。免费计划/月最多 500K API 请求，无限制标记，3 名团队成员，无需信用卡。
  * [Hypertune](https://www.hypertune.com) - 类型安全的功能标志、A/B 测试、分析和应用程序配置，具有 Git 风格的版本控制和同步、内存中、本地标志评估。最多 5 名团队成员免费，具有无限的功能标记和 A/B 测试。
  * [Statsig](https://www.statsig.com) - 用于功能管理、A/B 测试、分析等的强大平台。其慷慨的免费计划提供无限的席位、旗帜、实验和动态配置，/月支持多达 100 万场活动。
  * [Toggled.dev](https://www.toggled.dev) - 企业就绪、可扩展的多区域功能切换管理平台。免费计划最多 10 个标志、两个环境、无限请求。 SDK、分析仪表板、发布日历、Slack 通知和所有其他功能都包含在无限免费计划中。


**[⬆️ 返回顶部](#table-of-contents)**

<a id="font"></a>
## 字体

  * [Befonts](https://befonts.com/) - 提供多种独特的字体供个人或商业用途。
  * [Bunny](https://fonts.bunny.net) - 注重隐私的 Google Fonts
  * [dafont](https://www.dafont.com/) - 本网站上提供的字体是其作者的财产，并且是免费软件、共享软件、演示版本或公共领域。
  * [Everything Fonts](https://everythingfonts.com/) - 提供多种工具； @font-face，单位转换器，字体提示和字体提交器。
  * [Font of web](https://fontofweb.com/) - 识别网站上使用的所有字体以及它们的使用方式。
  * [Font Squirrel](https://www.fontsquirrel.com/) - Freeware fonts licensed for commercial work.手工选择这些字体并以易于使用的格式呈现。
  * [FontGet](https://www.fontget.com/) - 有多种字体可供下载，并用标签整齐地分类。
  * [fonts.xz.style](https://fonts.xz.style/) - 免费开源服务，用于使用 CSS 向网站提供字体系列。
  * [Fontsensei](https://fontsensei.com/) - 由用户标记的开源 Google 字体。带有 CJK（中文、日文、韩文）字体标签。
  * [Fontshare](https://www.fontshare.com/) - 是一项免费字体服务。这是一个不断增长的专业级字体集合，100% 免费供个人和商业使用。
  * [Google Fonts](https://fonts.google.com/) - 通过下载或 Google CDN 的链接，可以轻松快速地在网站上安装许多免费字体。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="forms"></a>
## 表单

  * [FabForm](https://fabform.io/) - 形成智能开发者后台平台。免费计划允许/月提交 250 份表格。友好的现代图形用户界面。与 Google Sheets、Airtable、Slack、电子邮件等集成。
  * [Feathery](https://feathery.io) - Powerful, developer-friendly form builder.构建注册和登录、用户入门、支付流程、复杂的财务应用程序等。免费计划允许/月最多 250 次提交和五个有效表格。
  * [feedback.fish](https://feedback.fish/) - 免费计划允许收集总计 25 份反馈提交。易于与提供的 React 和 Vue 组件集成。
  * [FluidForms](https://fluidforms.ai/) - Form builder and backend with AI-driven logic.免费计划包括/月 100 个回复、无限表单(包括 AI 创建的表单)、网络钩子和嵌入。
  * [Form.taxi](https://form.taxi/) - Endpoint for HTML forms submissions.具有通知、垃圾邮件拦截器和符合 GDPR 的数据处理。 Free plan for basic usage.
  * [Formcarry.com](https://formcarry.com) - HTTP POST 表单端点，免费计划允许/月提交 100 次。
  * [Formester.com](https://formester.com) - 在您的网站上共享和嵌入外观独特的表单 - 创建的表单数量或计划限制的功能没有限制。/月最多可免费提交 100 份作品。
  * [Forminit](https://forminit.com/) - Headless form backend for developers.免费计划允许/月提交 100 份表单，包括文件上传、服务器端字段验证、电子邮件通知、垃圾邮件防护和 Zapier。
  * [FormKeep.com](https://www.formkeep.com/) - /月提交 50 次的无限表单、垃圾邮件防护、电子邮件通知以及可导出 HTML 的拖放设计器。其他功能包括自定义字段规则、团队以及与 Google Sheets、Slack、ActiveCampaign 和 Zapier 的集成。
  * [formlets.com](https://formlets.com/) - 在线表格、/月无限制的单页表格、/月 100 份提交、电子邮件通知。
  * [forms.app](https://forms.app/) - 使用条件逻辑、自动分数计算器和人工智能等强大功能创建在线表单。通过免费计划收集最多 100 个回复，将表单嵌入到网站上，或通过链接使用它们。
  * [formspark.io](https://formspark.io/) -  表格到电子邮件服务，免费计划允许无限量的表格，/月提交 250 份，由客户支持团队提供支持。
  * [Formspree.io](https://formspree.io/) - 使用 HTTP POST 请求发送电子邮件。免费套餐级限制每个表单/月提交 50 次。
  * [Formsubmit.co](https://formsubmit.co/) - HTML 表单的简单表单端点。永远免费。无需注册。
  * [Formware.io](https://formware.io/) - 在几秒钟内创建完全响应式且引人入胜的表单，无需知道如何编码，并免费收集无限的响应！
  * [HeroTofu.com](https://herotofu.com/) - 具有机器人检测和加密存档功能的表单后端。通过 UI 将提交转发至电子邮件、Slack 或 Zapier。使用您自己的前端。不需要服务器代码。免费计划提供无限量的表格和/月 100 份提交。
  * [HeyForm.net](https://heyform.net/) - 拖放在线表单生成器。免费套餐可让您创建无限量的表单并收集无限量的提交内容。配备预建模板、反垃圾邮件和 100MB 文件存储。
  * [Jotform.com](https://jotform.com/) - 免费创建在线表单、收集提交内容、接受付款、自动化工作流程并使用内置电子签名签署文档。免费计划包括 5 份表格、100 份/月提交、10 份电子签名文档、10 份付款提交等。
  * [Kwes.io](https://kwes.io/) - 功能丰富的形式端点。非常适合静态网站。免费计划包括最多 1 个网站，/月最多提交 50 条内容。
  * [Pageclip](https://pageclip.co/) - 免费计划允许一个网站、一份表格和/月 1,000 次提交。
  * [SimplePDF.eu](https://simplepdf.eu/embed) - 在您的网站上嵌入 PDF 编辑器，将任何 PDF 转换为可填写的表单。免费计划允许无限量的 PDF，每个 PDF 提交三份。
  * [smartforms.dev](https://smartforms.dev/) - 为您的网站提供强大而简单的表单后端，永久免费计划允许/月 50 次提交，250MB 文件存储，Zapier 集成，CSV/JSON 导出，自定义重定向，自定义响应页面，Telegram 和 Slack 机器人，单封电子邮件通知。
  * [staticforms.xyz](https://www.staticforms.xyz/) - 免费轻松集成 HTML 表单，无需任何服务器端代码。用户提交表单后，一封包含表单内容的电子邮件将发送到您的注册地址。
  * [Survicate](https://survicate.com/) - 使用一种工具从所有来源获取反馈并发送后续调查。利用人工智能自动分析反馈并提取见解。免费电子邮件、网站、产品内或移动调查、AI 调查创建器以及 25 个月的回复。
  * [Tally.so](https://tally.so/) - 99% 的功能都是免费的。免费套餐可让您拥有：无限的表单、无限的提交、电子邮件通知、表单逻辑、收款、文件上传、自定义感谢页面等等。
  * [Typeform.com](https://www.typeform.com/) - 在网站上包含设计精美的表单。  免费计划仅允许每个表单 10 个字段和 100 个/月回复。
  * [Vidhook](https://vidhook.io/) - 使用具有高响应率的令人愉快的调查来收集反馈。免费计划包括 1 项主动调查、每项调查 25 个回复以及可自定义模板。
  * [WaiverStevie.com](https://waiverstevie.com) - 具有 REST API 的电子签名平台。您可以使用 webhook 接收通知。免费计划水印签署的文件，但允许无限的信封+签名。
  * [Web3Forms](https://web3forms.com) - 静态和 JAMStack 网站的联系表单，无需编写后端代码。免费计划允许无限表格、无限域名和/月 250 次提交。
  * [Wufoo](https://www.wufoo.com/) - 在网站上使用的快速表单。免费计划/月提交的数量上限为 100 份。
  * [FormNX](https://FormNX.com/) - 创建无限量的表单，免费获得无限量的提交。使用专业创建的 1000 多个表单模板或从头开始创建表单。获取电子邮件通知、表单逻辑、收款、文件上传、自定义感谢页面等功能。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="generative-ai"></a>
## 生成式 AI

  * [Arize AX](https://arize.com) - AI 工程平台可帮助 AI 工程师/PM 使用内置 Alyx 代理评估和观察 AI 应用程序和代理。免费产品包括 25k 跨度和/月 1GB 的摄取量。
  * [Audio Enhancer](https://voice-clone.org/tools/audio-enhancer) - 由 AI 驱动的音频增强器 SaaS，可消除噪音和回声，同时保持自然的声音清晰度。完全免费：无限制一键增强，无需登录，支持MP3/WAV/FLAC
  * [Braintrust](https://www.braintrustdata.com/) - Gen AI 的评估、提示游乐场和数据管理。免费计划/周最多提供 1,000 行私人评估。
  * [Clair](https://askclair.ai/) - 临床人工智能参考。学生可以免费使用专业工具套件，其中包括开放搜索、临床摘要、医学评论、药物相互作用、ICD-10 代码和管理。此外，还提供专业套件的免费试用。
  * [Comet Opik](https://www.comet.com/site/products/opik/) - 在您的开发和生产生命周期中评估、测试和交付 LLM 应用程序。[#opensource](https://github.com/comet-ml/opik/)
  * [Future AGI](https://futureagi.com) - 用于评估、观察和改进 LLM 和 AI 代理应用程序的开源平台，具有跟踪、评估、模拟和防护功能。免费套餐包括 50GB 存储空间、2K 评估积分、/月 100K 个 AI 网关请求、100 万个文本代理模拟代币和 60 分钟语音模拟，以及无限的项目/席位和 BYOK LLM-as-judge，平台成本为 0 美元。[#opensource](https://github.com/future-agi/future-agi)
  * [Keywords AI](https://keywordsai.co) - 最好的LLM监控平台。一种格式可通过 2 行代码调用 200 多个 LLM。/月 10,000 个免费请求，平台功能 0 美元！
  * [Langfuse](https://langfuse.com/) - 开源 LLM 工程平台，可帮助团队协作调试、分析和迭代其 LLM 应用程序。永久免费计划包括/月 50k 次观察和所有平台功能。[#opensource](https://github.com/langfuse/langfuse)
  * [Langtrace](https://langtrace.ai) - 使开发人员能够跟踪、评估、管理提示和数据集，以及调试与 LLM 应用程序性能相关的问题。它为任何 LLM 创建开放遥测标准跟踪，这有助于提高可观察性并与任何可观察性客户端配合使用。免费计划/月提供 50K 跟踪。
  * [LangWatch](https://langwatch.ai) - LLMOps 平台可帮助 AI 团队衡量、监控和优化 LLM 应用程序的可靠性、成本效益和性能。借助强大的 DSPy 组件，我们可以实现工程师和非技术团队之间的无缝协作，以微调和生产 GenAI 产品。免费计划包括所有平台功能、/月 1k 条跟踪和 1 个工作流程 DSPy 优化器。[#opensource](https://github.com/langwatch/langwatch)
  * [Latitude](https://latitude.so) - 开源 (MIT) LLM 可观察性和评估平台，用于跟踪、监控和评估生产中的 AI 代理。免费入门计划包括/月 20K 积分、30 天数据保留和无限席位。[#opensource](https://github.com/latitude-dev/latitude-llm)
  * [Lumenfall.ai](https://lumenfall.ai/) - AI 媒体网关通过兼容 OpenAI 的 API 提供对领先图像生成模型的统一访问。该平台本身免费使用，零加价，无需订阅费。大多数模型的推理成本按提供商价格计费，但 FLUX.1 [schnell] FP8 永久免费提供，注册用户可以无限制使用。包括内置故障转移和提供商弹性。
  * [Maxim](https://www.getmaxim.ai) - 具备代理模拟和提示游乐场的 LLM 评估与可观测性平台。免费套餐提供每月 10k 日志、通过 BYOK 访问提示游乐场、模拟和评估。
  * [Mediaworkbench.ai](https://mediaworkbench.ai) - MediaWorkbench.ai 为 Azure OpenAI、DeepSeek 和 Google Gemini 模型提供 100,000 个免费单词，使用户能够访问用于代码生成、深入研究和图像创建的强大工具。
  * [OpenRouter](https://openrouter.ai/models?q=free) - 提供DeepSeek R1、V3、Llama、Moonshot AI等多种免费AI模型。这些模型在自然语言处理方面表现出色，适合多样化的开发需求。请注意，虽然这些模型可以免费使用，但它们受到速率限制。此外，OpenRouter 还提供满足更高级需求的付费模型，例如 Claude、OpenAI、Grok、Gemini 和 Nova。
  * [Pollinations.AI](https://pollinations.ai/) - 易于使用的免费图像生成人工智能，提供免费 API。无需注册或 API 密钥，并且有多种集成到网站或工作流程的选项。[#opensource](https://github.com/pollinations/pollinations)
  * [Portkey](https://portkey.ai/) - Gen AI 应用程序的控制面板具有可观察性套件和 AI 网关。/月免费发送和记录多达 10,000 个请求。
  * [ReportGPT](https://ReportGPT.app) - 人工智能驱动的写作助手。只要您携带自己的API密钥，整个平台都是免费的。
  * [Zenable](https://zenable.io) - 使用通过策略即代码构建的护栏，立即自动修复 Cursor、Windsurf 和 Copilot 等工具的输出，以满足公司的质量和合规性标准。免费套餐包括/天对 MCP 服务器的 100 次工具调用以及/天通过 GitHub 应用程序进行的 25 次免费自动Pull Request审查。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="cdn-and-protection"></a>
## CDN 和防护

  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) - 用于 bootstrap、bootswatch 和 fontawesome.io 的 CDN
  * [CacheFly](https://portal.cachefly.com/signup/free2023) - /月高达 5 TB 的免费 CDN 流量、19 个核心 PoP、1 个域和通用 SSL。
  * [cdnjs.com](https://cdnjs.com/) - 简单。快速地。可靠的。最好的内容交付。 cdnjs 是一项由 Cloudflare 提供支持的免费开源 CDN 服务，受到超过 11% 的网站信任。
  * [developers.google.com](https://developers.google.com/speed/libraries/) - Google 托管库是最流行的开源 JavaScript 库的内容分发网络
  * [Gcore](https://gcorelabs.com/) - 全球内容交付网络，/月 1 TB 和 100 万个请求免费且
    免费 DNS 托管
  * [jsdelivr.com](https://www.jsdelivr.com/) - 免费、快速且可靠的开源 CDN。支持 npm、GitHub、WordPress、Deno 等。
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) - Microsoft Ajax CDN 托管流行的第三方 JavaScript 库(例如 jQuery)，使您能够轻松地将它们添加到您的 Web 应用程序中
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) - 免费 DDoS 防护
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) - 免费 DDoS 保护和 SSL 证书
  * [PromoProxy](https://promoproxy.net/) - 免费云安全 Web 网关。免费计划包括最多 5 个用户和/天 1 GB。
  * [raw.githack.com](https://raw.githack.com/) - **rawgit.com** 的现代替代品，仅使用 Cloudflare 托管文件
  * [Skypack](https://www.skypack.dev/) - 100% 原生 ES 模块 JavaScript CDN。每个域/月 100 万个请求免费。
  * [statically.io](https://statically.io/) - 适用于 Git 存储库(GitHub、GitLab、Bitbucket)、WordPress 相关资产和图像的 CDN
  * [Stellate](https://stellate.co/) - Stellare 是一款适用于 GraphQL API 的超快、可靠的 CDN，并且免费提供两项服务。
  * [toranproxy.com](https://toranproxy.com/) - Packagist 和 GitHub 的代理。 CD 永不失败。免费供个人使用，一名开发者，无支持
  * [UNPKG](https://unpkg.com/) - npm 上所有内容的 CDN
  * [weserv](https://images.weserv.nl/) - 图像缓存和调整大小服务。使用全球缓存动态处理图像。

**[⬆️ 返回顶部](#table-of-contents)**

## PaaS

  * [ampt.dev](https://getampt.com/) - Ampt 允许团队在 AWS 上构建、部署和扩展 JavaScript 应用程序，而无需复杂的配置或管理基础设施。免费预览计划包括每小时 500 次调用、/天 2,500 次调用和/月 50,000 次调用。仅在付费计划中允许自定义域。
  * [anvil.works](https://anvil.works) - Web 应用程序开发仅使用 Python。免费套餐提供无限应用程序和 30 秒超时。
  * [Apply.build](https://apply.build/) - 使用 0.5 个 vCPU / 512 MiB RAM、欧洲服务器、自动防火墙、实时性能指标免费构建和部署您的 GitHub 应用程序。运行 Node.js、Python、Go、Java、静态站点、微服务等。
  * [appwrite](https://appwrite.io) - 无限的项目，无项目暂停(支持 websockets)和身份验证服务。免费套餐中每个项目 1 个数据库、3 个存储桶、5 个功能。
  * [Clever Cloud](https://clever.cloud) - 具有自动化部署、自动扩展、托管数据库和基于 Git 的工作流程的欧洲 PaaS。包括注册时 20 欧元的免费积分、包含免费 MySQL 和 PostgreSQL 数据库的有限 DEV 计划，以及 Heptapod 和 FS Buckets 等服务的免费津贴。
  * [Choreo](https://wso2.com/choreo/) - 人工智能原生内部开发者平台即服务。免费套餐包括最多 5 个组件和/月 100 美元的积分。
  * [codenameone.com](https://www.codenameone.com/) - 面向 Java/Kotlin 开发人员的开源、跨平台移动应用程序开发工具链。免费用于商业用途，项目数量不受限制
  * [Daestro](https://daestro.com) - 跨云提供商和本地运行计算作业。免费套餐包括最多 10 个并发作业运行、2 个计算生成、自托管计算、1 个云提供商、1 个容器注册表和 1 个 cron 作业。
  * [Deno Deploy](https://deno.com/deploy) - 在全球边缘运行 JavaScript、TypeScript 和 WebAssembly 的分布式系统。免费套餐包括/天 100,000 个请求和/月 100 GiB 数据传输。
  * [domcloud.co](https://domcloud.co) - Linux 托管服务，提供带有 GitHub、SSH 和 MariaDB/Postgres 数据库的 CI/CD。免费版本具有 1 GB 存储空间和 1 GB 网络/月限制，并且仅限于免费域。
  * [encore.dev](https://encore.dev/) - 使用静态分析的后端框架提供自动化基础设施、无样板代码等。包括用于业余爱好项目的免费云托管。
  * [flightcontrol.dev](https://flightcontrol.dev/) - 使用 Git 推送式工作流程在您自己的 AWS 账户上部署 Web 服务、数据库等。为在个人 GitHub 存储库上拥有 1 名开发人员的用户提供免费套餐。 AWS 成本通过 AWS 计费，但您可以使用积分和 AWS 免费套餐。
  * [gigalixir.com](https://gigalixir.com/) - Gigalixir 为 Elixir/Phoenix 应用程序提供一个永不休眠的免费实例和一个仅限 2 个连接、10, 000 行且无备份的免费套餐 PostgreSQL 数据库。
  * [Northflank](https://northflank.com) - 使用强大的 UI、API 和 CLI 构建和部署微服务、作业和托管数据库。从版本控制和外部 Docker 注册表无缝扩展容器。免费套餐包括两项服务、两个 cron 作业和 1 个数据库。
  * [Ownkube](https://ownkube.io) - 您自己的 AWS 帐户中的免费单节点 k3，通过 git Push 运行应用程序、数据库和工作程序。以最高效率使用您的 AWS 积分。
  * [pipedream.com](https://pipedream.com) - 为开发者打造的集成平台。基于任何触发器开发任何工作流程。工作流程是您可以运行[for free](https://docs.pipedream.com/pricing/)的代码。无需管理服务器或云资源。
  * [pythonanywhere.com](https://www.pythonanywhere.com/) - 云 Python 应用程序托管。初学者帐户免费，1 个位于 your-username.pythonanywhere.com 域的 Python Web 应用程序，512 MB 私人文件存储空间，1 个 MySQL 数据库
  * [WunderGraph](https://cloud.wundergraph.com) - 一个开源平台，可让您快速构建、发布和管理现代 API。内置 CI/CD、GitHub 集成和自动 HTTPS。[free plan](https://wundergraph.com/pricing)上最多 3 个项目、1GB 出口、/月 300 分钟的构建时间
  * [YepCode](https://yepcode.io) - 用于在无服务器环境中连接 API 和服务的一体化平台。它不仅具有 NoCode 工具的所有敏捷性和优势，而且还具有使用编程语言的所有功能。免费套餐包括[1.000 yeps](https://yepcode.io/pricing/)。

**[⬆️ 返回顶部](#table-of-contents)**

## BaaS

  * [Activepieces](https://www.activepieces.com) - 构建自动化流程以在应用程序的后端将多个应用程序连接在一起。例如，当您的应用中触发事件时，发送 Slack 消息或添加 Google 表格行。/月最多可释放 5,000 个任务。
  * [back4app.com](https://www.back4app.com) - Back4App是一个基于Parse Platform的易于使用、灵活且可扩展的后端。
  * [backendless.com](https://backendless.com/) - 移动和 Web Baas，免费提供 1 GB 文件存储，/月推送 50,000 条通知，表中包含 1000 个数据对象。
  * [connectycube.com](https://connectycube.com) - 无限的聊天消息、p2p 语音和视频通话、文件附件和推送通知。对于最多 1000 个用户的应用程序免费。
  * [convex.dev](https://convex.dev/) - 反应式后端即服务，托管数据(具有关系的文档和可序列化的 ACID 事务)、无服务器函数和 WebSockets，以将更新流式传输到各种客户端。对于小型项目免费 - 最多 1M 条记录，/月 500 万次函数调用。
  * [ETLR](https://etlr.io) - 使用 YAML 定义、版本化和部署自动化脚本。开发人员优先的拖放工具替代方案。可用于计划任务、AI 代理和基础设施监控。免费套餐包括/月 100 个积分。
  * [Flutter Flow](https://flutterflow.io) - 无需编写任何代码即可构建您的 Flutter 应用程序 UI。还有 Firebase 集成。免费计划包括对 UI Builder 和免费模板的完全访问。
  * [getstream.io](https://getstream.io/) - 在几个小时而不是几周内构建可扩展的应用内聊天、消息传递、视频和音频以及源
  * [IFTTT](https://ifttt.com) - 自动化您喜爱的应用程序和设备。免费 2 个小程序
  * [Integrately](https://integrately.com) - 只需单击一下即可自动执行繁琐的任务。免费 100 项任务，15 分钟
  * [LeanCloud](https://leancloud.app/) - 移动后端。 1GB 数据存储、256MB 实例、3K API 请求/天和 10K 推送/天都是免费的。 (API与Parse Platform非常相似)
  * [nhost.io](https://nhost.io) - 适用于网络和移动应用程序的无服务器后端。免费计划包括 PostgreSQL、GraphQL (Hasura)、身份验证、存储和无服务器功能。
  * [onesignal.com](https://onesignal.com/) - 无限制的免费推送通知。/月发送 10,000 封电子邮件，联系人数量不受限制，并可使用自动预热功能。
  * [paraio.com](https://paraio.com) - 后端服务API，具有灵活的身份验证、全文搜索和缓存。一款应用免费，1GB 应用数据。
  * [pubnub.com](https://www.pubnub.com/) - /月最多 100 万条消息和 100 个日常活跃设备的免费推送通知
  * [pushbots.com](https://pushbots.com/) - 推送通知服务。/月最多免费推送 150 万次
  * [pusher.com](https://pusher.com/beams) - 为 2000 名/月活跃用户提供免费、无限制的推送通知。适用于 iOS 和 Android 设备的单一 API。
  * [simperium.com](https://simperium.com/) - 即时自动地将数据移动到任何地方，多平台，无限发送和存储结构化数据，最多。 2,500 个用户/月
  * [Supabase](https://supabase.com) - 用于构建后端的开源 Firebase 替代方案。免费计划提供身份验证、实时数据库和对象存储。
  * [tyk.io](https://tyk.io/) - 具有身份验证、配额、监控和分析功能的 API 管理。免费云产品
  * [zapier.com](https://zapier.com/) - 连接您用来自动执行任务的应用程序。每 15 分钟 5 次 Zap，/月 100 项任务
更新时间、五个活动自动化、网络钩子。


**[⬆️ 返回顶部](#table-of-contents)**

<a id="low-code-platform"></a>
## 低代码平台

  * [appsmith](https://www.appsmith.com/) - 用于构建管理面板、内部工具和仪表板的低代码项目。与超过 15 个数据库和任何 API 集成。
  * [BudiBase](https://budibase.com/) - Budibase 是一个开源低代码平台，可在几分钟内创建内部应用程序。支持 PostgreSQL、MySQL、MSSQL、MongoDB、Rest API、Docker、K8s
  * [Clappia](https://www.clappia.com) - 一个低代码平台，旨在通过可定制的移动和 Web 应用程序构建业务流程应用程序。提供拖放界面、离线支持、实时位置跟踪以及与各种第三方服务集成等功能
  * [lil'bots](https://www.lilbots.io/) - 利用免费的内置 API(例如 OpenAI、Anthropic、Firecrawl 等)在线编写和运行脚本。非常适合构建人工智能代理/内部工具以及与团队共享。免费套餐包括对 API、AI 编码助手的完全访问权限和/月 10,000 个执行积分。
  * [manubes](https://www.manubes.com) - 强大的无代码云平台，专注于工业生产管理。/月进行 100 万次工作流活动的一名用户免费 ([also available in german](https://www.manubes.de))。
  * [Mendix](https://www.mendix.com/) - 企业快速应用程序开发、支持总用户数的无限制访问沙盒环境、每个应用程序 0.5 GB 存储和 1 GB RAM。此外，免费套餐中还允许使用 Studio 和 Studio Pro IDE。
  * [outsystems.com](https://www.outsystems.com/) - 适用于本地或云的企业 Web 开发 PaaS，免费的“个人环境”产品允许无限的代码和高达 1 GB 的数据库
  * [ReTool](https://retool.com/) - 用于构建内部应用程序的低代码平台。 Retool 是高度可破解的。如果你可以用 JavaScript 和 API 编写它，你就可以在 Retool 中制作它。免费套餐/月最多允许 5 个用户、无限的应用程序和 API 连接。
  * [ToolJet](https://www.tooljet.com/) - 用于构建业务应用程序的可扩展低代码框架。连接到数据库、云存储、GraphQL、API 端点、Airtable 等，并使用拖放应用程序生成器构建应用程序。
  * [UI Bakery](https://uibakery.io) - 低代码平台，可以更快地构建自定义 Web 应用程序。支持使用拖放功能构建 UI，并通过 JavaScript、Python 和 SQL 进行高级定制。可作为云和自托管解决方案使用。最多 5 个用户免费。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="web-hosting"></a>
## Web 托管

  * [Alwaysdata](https://www.alwaysdata.com/) - 1 GB 免费网络托管，支持 MySQL、PostgreSQL、RabbitMQ、.NET、Deno、Elixir、Go、Java、Lua、Node.js、PHP、Python、Ruby、Rust。自定义 Web 服务器，通过 FTP、WebDAV 和 SSH 访问。包括邮箱、邮件列表和应用程序安装程序。免费计划没有自定义域。
  * [Awardspace.com](https://www.awardspace.com) - 免费网络托管+免费短域名、PHP、MySQL、应用程序安装程序、电子邮件发送和无广告。
  * [boomurl](https://boomurl.com) - 无需帐户即可将静态站点(HTML/Markdown/images/PDF 或整个文件夹)发布到即时 HTTPS URL；免费套餐显示一个小横幅。支持自定义域。
  * [Bubble](https://bubble.io/) - 可视化编程无需代码即可构建网络和移动应用程序，免费使用 Bubble 品牌。
  * [dAppling Network](https://www.dappling.network/) - 用于 Web3 前端的去中心化 Web 托管平台，专注于增加正常运行时间和安全性，并为用户提供额外的访问点。
  * [DigitalOcean](https://www.digitalocean.com/pricing) - 在应用程序平台入门级上免费构建和部署三个静态站点。
  * [FreeFlarum](https://freeflarum.com/) - 社区支持的免费 Flarum 托管，最多可容纳 250 位用户(捐赠以删除页脚的水印)。
  * [Kinsta Static Site Hosting](https://kinsta.com/static-site-hosting/) - 免费部署多达 100 个静态站点、带 SSL 的自定义域、/月 100 GB 带宽、260 多个 Cloudflare CDN 位置。
  * [MDB GO](https://mdbgo.com/) - 免费托管一个项目，具有两周容器 TTL、每个项目 500 MB RAM、SFTP - 1G 磁盘空间。
  * [Mirin](https://mirin.com) - 用于开发人员构建的 React、Vue 或 Svelte 组件站点的网站平台，具有可视化编辑、表单、分析和全球 CDN 托管。免费套餐包括 1 个具有无限页面和提交内容的网站。
  * [Neocities](https://neocities.org) - 静态、1 GB 可用存储空间和 200 GB 带宽。
  * [Netlify](https://www.netlify.com/) - 免费构建、部署和托管静态站点/应用程序，/月 300 个积分(相当于 30 GB 带宽)。
  * [PandaStack](https://www.pandastack.io/) - 面向开发人员的生态系统包括不同格式的 Web 托管(静态 Web 托管、基于容器的 Web 托管、Wordpress 以及只需单击几下即可使用的许多其他托管应用程序)。一台免费网络托管(静态或容器)和一台免费数据库，带宽为 100GB，构建时间为/月 300 分钟。
  * [pantheon.io](https://pantheon.io/) - Drupal 和 WordPress 托管、自动化 DevOps 和可扩展的基础设施。对开发商和机构免费。没有自定义域。
  * [Qoddi](https://qoddi.com) - PaaS 服务类似于 Heroku，具有以开发人员为中心的方法和包罗万象的功能。静态资产、暂存和开发人员应用程序的免费套餐。
  * [readthedocs.org](https://readthedocs.org/) - 免费文档托管，包括版本控制、PDF 生成等
  * [render.com](https://render.com) - 统一云，通过免费 SSL、全球 CDN、专用网络、Git 自动部署以及完全免费的 Web 服务、数据库和静态网页计划来构建和运行应用程序和网站。
  * [Revdoku](https://revdoku.com/)— 直接从 ChatGPT、Claude、Codex 和其他 AI 代理将文件、报告、自定义微型网站发布为公共或受密码保护的网站。免费套餐：2GB 存储空间、2 个实时站点/应用程序、1 个数据库 (25 MB)、3 个 AI 连接、1k 文件/存储桶(100 MB/文件)、基本分析。
  * [SourceForge](https://sourceforge.net/) - 免费查找、创建和发布开源软件
  * [surge.sh](https://surge.sh/) - 面向前端开发人员的静态 Web 发布。具有自定义域支持的无限站点
  * [tilda.cc](https://tilda.cc/) - 一个站点，50 个页面，50 MB 存储空间，仅 170 多个可用块中的主要预定义块，没有字体，没有图标，也没有自定义域
  * [Vercel](https://vercel.com/) - 每次`git push`时，使用免费的 SSL、全球 CDN 和独特的预览 URL 构建、部署和托管 Web 应用程序。非常适合 Next.js 和其他静态站点生成器。
  * [Versoly](https://versoly.com/) - 以 SaaS 为中心的网站构建器 - 无限的网站、70 多个块、五个模板、自定义 CSS、favicon、SEO 和表单。没有自定义域。

**[⬆️ 返回顶部](#table-of-contents)**

## DNS

  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - 由 Cloudflare 提供的免费公共 DNS 解析器，快速且安全(加密您的 DNS 查询)。可用于绕过互联网提供商的 DNS 阻止、防止 DNS 查询间谍活动和[to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families)。也可以使用[via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests)。注意：只是 DNS 解析器，而不是 DNS 托管服务商。
  * [1984.is](https://www.1984.is/product/freedns/) - 包含 API 的免费 DNS 服务和许多其他免费 DNS 功能。
  * [cloudns.net](https://www.cloudns.net/) - 免费 DNS 托管最多 1 个包含 50 条记录的域名
  * [deSEC](https://desec.io) - 具有 API 支持的免费 DNS 托管，设计时考虑到了安全性。在开源软件上运行并由[SSE](https://www.securesystems.de/)支持。
  * [dns.he.net](https://dns.he.net/) - 具有动态 DNS 支持的免费 DNS 托管服务
  * [dnspod.com](https://www.dnspod.com/) - 免费 DNS 托管。
  * [duckdns.org](https://www.duckdns.org/) - 免费 DDNS，免费套餐最多包含 5 个域名。带有各种设置的配置指南。
  * [Dynv6.com](https://dynv6.com/) - 免费的 DDNS 服务，带有[API support](https://dynv6.com/docs/apis)和许多 dns 记录类型的管理(如 CNAME、MX、SPF、SRV、TXT 等)。
  * [freedns.afraid.org](https://freedns.afraid.org/) - 免费 DNS 托管。此外，还根据众多公共用户[contributed domains](https://freedns.afraid.org/domain/registry/)提供免费子域名。注册后从“子域名”菜单获取免费子域名。
  * [Glauca](https://docs.glauca.digital/hexdns/) - 最多 3 个域的免费 DNS 托管和 DNSSEC 支持
  * [Hetzner](https://www.hetzner.com/dns-console) - Hetzner 提供免费 DNS 托管并提供 API 支持。
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) - 华为免费DNS托管
  * [LocalCert](https://localcert.net) - 与公共 CA 兼容的免费`.localcert.net`子域，可在专用网络中使用
  * [luadns.com](https://www.luadns.com/) - 免费 DNS 托管，三个域，所有功能都有合理的限制
  * [namecheap.com](https://www.namecheap.com/domains/freedns/) - 免费 DNS。域名数量没有限制
  * [nextdns.io](https://nextdns.io) - 基于DNS的防火墙，/月30万次免费查询
  * [noip.at](https://noip.at/) - 免费 DDNS 服务，无需注册、跟踪、记录或广告。没有域限制。
  * [noip](https://www.noip.com/) - 动态 DNS 服务，允许最多 3 个免费主机名，每 30 天确认一次
  * [sslip.io](https://sslip.io/) - 免费 DNS 服务，当使用带有嵌入式 IP 地址的主机名进行查询时，会返回该 IP 地址。
  * [zilore.com](https://zilore.com/en/dns) - 5 个域名的免费 DNS 托管。
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) - 具有动态 DNS 支持的免费 DNS 托管。
  * [Zonomi](https://zonomi.com/) - 免费 DNS 托管服务，具有即时 DNS 传播功能。免费计划：1 个 DNS 区域(域名)，最多 10 条 DNS 记录。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="domain"></a>
## 域名

  * [DigitalPlat](https://domain.digitalplat.org) - 免费子域。
  * [isroot.in](https://isroot.in) - 免费 isroot.in 子域。
  * [pp.ua](https://nic.ua/) - 免费 pp.ua 子域。

**[⬆️ 返回顶部](#table-of-contents)**

## IaaS

  * [4EVERLAND](https://www.4everland.org/) - 兼容AWS S3-API、接口操作、CLI等上传方式，安全、便捷、高效地从IPFS和Arweave网络上传和存储文件。注册用户可以免费获得 6 GB 的 IPFS 存储和 300MB 的 Arweave 存储。任何小于 150 KB 的 Arweave 文件上传都是免费的。
  * [backblaze.com](https://www.backblaze.com/b2/) - Backblaze B2 云存储。无限期免费 10 GB(类似 Amazon S3)对象存储
  * [filebase.com](https://filebase.com/) - 由区块链支持的 S3 兼容对象存储。 5 GB 无限期免费存储空间。
  * [Modal](https://modal.com) - 人工智能驱动的 IaaS，具有大量的计算、存储能力；提供 30 美元(某些帐户可能限制为 5 美元)的/月免费积分

**[⬆️ 返回顶部](#table-of-contents)**

<a id="managed-data-services"></a>
## 托管数据服务

  * [8base.com](https://www.8base.com/) - 8base 是一个为 JavaScript 开发人员构建的全栈低代码开发平台，构建在 MySQL 和 GraphQL 以及无服务器后端即服务之上。它允许您使用 UI 应用程序生成器快速开始构建 Web 应用程序并快速扩展，免费套餐包括行数：2,500、存储：500、无服务器计算：1Gb/h 和客户端应用程序用户：5。
  * [airtable.com](https://airtable.com/) - 看起来像电子表格，但它是一个关系数据库，无限基数，1,200 行/基数，以及 1,000 个 API 请求/月
  * [Aiven](https://aiven.io/) - Aiven 在其开源数据平台上提供免费的 PostgreSQL、MySQL 和 Valkey(兼容 Redis)计划。单节点、1 个 CPU、1GB RAM，对于 PostgreSQL 和 MySQL，1GB 存储。轻松迁移到更广泛的计划或跨云。
  * [CockroachDB Cloud](https://www.cockroachlabs.com/pricing/) - 免费套餐/月免费提供 5000 万个 RU 和 10 GiB 存储(相当于 15 美元)。 ([What's the Request Units](https://www.cockroachlabs.com/docs/cockroachcloud/metrics-request-units.html))
  * [codehooks.io](https://codehooks.io/) - 易于使用的 JavaScript 无服务器 API/后端和 NoSQL 数据库服务，具有函数、Mongdb 式查询、键/值查找、作业系统、实时消息、工作队列、强大的 CLI 和基于 Web 的数据管理器。免费计划拥有 5GB 存储空间和每分钟 60 次/API 调用。包括 2 名开发人员。无需信用卡。
  * [Couchbase Capella](https://www.couchbase.com/products/capella/) - 部署具有 1 个节点和 8GB 存储空间的永久免费套餐完全托管数据库集群，专为开发人员创建跨 IoT 到 AI 的下一代应用程序而构建
  * [CrateDB](https://crate.io/) - 用于实时分析的分布式开源 SQL 数据库。[Free Tier CRFREE](https://crate.io/lp-crfree)：单节点，2 个 CPU，2 GiB 内存，8 GiB 存储。每个组织一个集群，无需付款方式。
  * [filess.io](https://filess.io) - filess.io 是一个平台，您可以免费创建以下 DBMS 的两个数据库，每个数据库最多 10 MB：MySQL、MariaDB、MongoDB 和 PostgreSQL。
  * [InfluxDB](https://www.influxdata.com/) - 时间序列数据库，可释放高达 3MB/5 分钟写入、30MB/5 分钟读取和 10,000 个基数系列
  * [MemCachier](https://www.memcachier.com/) - 托管 Memcache 服务。免费提供高达 25MB、1 个代理服务器和基本分析
  * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - 免费套餐提供 512 MB
  * [Neo4j Aura](https://neo4j.com/cloud/aura/) - 使用 Cypher 查询语言和 REST API 管理本机图形 DBMS/分析平台。图大小限制(200k 个节点，400k 个关系)。
  * [Neon](https://neon.tech/) - 托管 PostgreSQL、每个项目 0.5 GB 存储、100 个项目、每个项目 10 个分支、无限数据库、始终可用的主分支(5 分钟后自动挂起)、/月 20 小时的非主分支计算活动时间(总计)。
  * [Nile](https://www.thenile.dev/) - 用于 B2B 应用程序的 Postgres 平台。无限数据库、始终可用、无需关闭、1GB 存储(总计)、5000 万个查询令牌、自动缩放、无限向量嵌入
  * [Prisma Postgres](https://prisma.io/postgres) - 超快的托管 Postgres 构建于 unikernels 之上，在裸机上运行，总存储量为 500MB，5 个数据库，与 Prisma ORM 集成。
  * [Qdrant](https://qdrant.tech/) - 用于嵌入数据的矢量数据库，具有 0.5 vCPU、1GB RAM 和 4GB 磁盘的单节点集群。
  * [restdb.io](https://restdb.io/) - 快速、简单的 NoSQL 云数据库服务。通过restdb.io，您可以获得架构、关系、自动 REST API(带有类似 MongoDB 的查询)以及用于处理数据的高效多用户管理 UI。免费计划允许 3 个用户、2500 条记录和每秒 1 个 API 请求。
  * [Rivestack](https://rivestack.io) - 使用针对 AI 工作负载优化的 pgvector 管理 PostgreSQL。免费套餐包括 2GB 存储、每日快照、14 天时间点恢复以及可将搜索查询转换为向量嵌入的内置 SQL 编辑器。
  * [SeaTable](https://seatable.io/) - 由 Seafile 团队构建的灵活的、类似电子表格的数据库。无限表、2,000 行、1 个月版本控制、最多 25 名团队成员。
  * [skyvia.com](https://skyvia.com/) - 云数据平台提供免费套餐，所有计划在测试阶段都是完全免费的
  * [StackBy](https://stackby.com/) - 一款将电子表格的灵活性、数据库的强大功能以及与您最喜爱的业务应用程序的内置集成结合在一起的工具。免费计划包括无限用户、十个堆栈和每个堆栈 2GB 附件。
  * [Tinybird](https://tinybird.co) - 无服务器托管 ClickHouse，通过 HTTP 进行无连接数据摄取，并允许您将 SQL 查询发布为托管 HTTP API。免费套餐没有时间限制，/天 10GB 存储 + 1000 个 API 请求。
  * [Turso by ChiselStrike](https://turso.tech/) - Turso 是边缘数据库中的 SQLite 开发人员体验。 Turso 提供永久免费入门计划、9 GB 总存储空间、最多 500 个数据库、最多 3 个位置、/月 10 亿行读取以及 SQLite 本地开发支持。
  * [Upstash](https://upstash.com/) - 无服务器 Redis，免费套餐/月最多 500K 命令、最大数据库大小 256MB 和 20 个并发连接

**[⬆️ 返回顶部](#table-of-contents)**

<a id="tunneling-webrtc-web-socket-servers-and-other-routers"></a>
## 隧道、WebRTC、WebSocket 服务器和其他路由器

  * [btunnel](https://www.btunnel.in/) - 将 localhost 和本地 tcp 服务器公开到互联网。免费计划包括文件服务器、自定义 http 请求和响应标头、基本身份验证保护和 1 小时隧道超时。
  * [cname.dev](https://cname.dev/) - 免费且安全的动态反向代理服务。
  * [conveyor.cloud](https://conveyor.cloud/) - Visual Studio 扩展，用于将 IIS Express 公开到本地网络或通过隧道公开到公共 URL。
  * [Expose](https://expose.dev/) - 通过安全隧道公开本地站点。免费计划包括 EU 服务器、随机子域和单用户。
  * [Hamachi](https://www.vpn.net/) - LogMeIn Hamachi 是一项托管 VPN 服务，可让您通过免费计划安全地将类似 LAN 的网络扩展到分布式团队，该计划允许最多 5 人使用无限网络
  * [Hookdeck](https://hookdeck.com/pricing) - 随时随地开发、测试和监控您的 Webhook。/月 10 万次请求和 10 万次尝试，保留三天。
  * [localhost.run](https://localhost.run/) - 通过隧道将本地运行的服务器公开到公共 URL。
  * [localtonet](https://localtonet.com/) - 适用于 HTTP、TLS、TCP、UDP、文件服务器(默认、SFTP、WebDAV)和代理隧道(HTTP、SOCKS5、Shadowsocks、VLESS)的多协议隧道。免费计划：1 个隧道、1GB/月带宽、30 分钟超时(不包括 HTTP 隧道)。
  * [localtunnel](https://theboroer.github.io/localtunnel-www/) - 通过隧道将本地运行的服务器公开到公共 URL。免费托管版本和[open source](https://github.com/localtunnel/localtunnel)。
  * [LocalXpose](https://localxpose.io) - 反向代理使您能够将本地主机服务器公开到互联网。免费计划的隧道寿命为 15 分钟。
  * [ngrok.com](https://ngrok.com/) - 通过隧道将本地运行的服务器公开到公共 URL。
  * [Pinggy](https://pinggy.io) - 使用单个命令即可获取本地主机的公共 URL，无需下载。 HTTPS / TCP / TLS 隧道。免费计划的隧道寿命为 60 分钟。
  * [Radmin VPN](https://www.radmin-vpn.com/) - 通过支持 VPN 的类似 LAN 的网络将多台计算机连接在一起。无限的同行。 (Hamachi替代品)
  * [serveo](https://serveo.net/) - 将本地服务器暴露给互联网。无需安装，无需注册。免费子域名，没有限制。
  * [stun:global.stun.twilio.com:3478?transport=udp](stun:global.stun.twilio.com:3478?transport=udp) - Twilio STUN
  * [stun:stun.l.google.com:19302](stun:stun.l.google.com:19302) - Google STUN
  * [Tailscale](https://tailscale.com/) - 零配置 VPN，使用开源 WireGuard 协议。安装在 MacOS、iOS、Windows、Linux 和 Android 设备上。可供 100 台设备和 3 位用户使用的个人免费计划。
  * [webhookrelay.com](https://webhookrelay.com) - 管理、调试、扇出并将所有 Webhooks 代理到公共或内部(即本地主机)目的地。此外，通过获取公共 HTTP 端点 (`https://yoursubdomain.webrelay.io <----> http://localhost:8080`)，通过隧道公开在专用网络中运行的服务器。
  * [Xirsys](https://www.xirsys.com/pricing/) - 无限制 STUN 使用 + /月 500 MB TURN 带宽、带宽上限、单一地理区域。
  * [ZeroTier](https://www.zerotier.com) - 自由和开源软件管理的虚拟以太网即服务。免费计划中包含 25 个客户端的无限端对端加密网络。桌面/移动/北美客户端；用于配置自定义路由规则和批准专用网络上的新客户端节点的 Web 界面

**[⬆️ 返回顶部](#table-of-contents)**

<a id="issue-tracking-and-project-management"></a>
## 问题跟踪和项目管理

  * [acunote.com](https://www.acunote.com/) - 最多可供 5 名团队成员使用的免费项目管理和 SCRUM 软件
  * [asana.com](https://asana.com/) - 与合作者免费进行私人项目
  * [Backlog](https://backlog.com) - 您的团队在一个平台上发布优秀项目所需的一切。免费计划提供 1 个具有 10 个用户的项目和 100MB 存储空间。
  * [Basecamp](https://basecamp.com/personal) - 待办事项列表、里程碑管理、类似论坛的消息传递、文件共享和时间跟踪。最多 3 个项目、20 个用户和 1GB 存储空间。
  * [bitrix24.com](https://www.bitrix24.com/) - 内联网和项目管理工具。免费套餐有 5GB，可供无限用户使用。
  * [cacoo.com](https://cacoo.com/) - 在线实时图表：流程图、UML、网络。自由最大。 15 个用户/图表，25 张
  * [clickup.com](https://clickup.com/) - 项目管理。免费的高级版本，带有云存储。提供移动应用程序和 Git 集成。
  * [Clockify](https://clockify.me) - 时间跟踪器和时间表应用程序可让您跟踪跨项目的工作时间。无限用户，永久免费。
  * [Cloudcraft](https://cloudcraft.co/) - 使用 Cloudcraft 视觉设计器在几分钟内设计出专业的架构图，该设计器针对 AWS 进行了优化，并具有显示实时数据的智能组件。免费计划为单个用户提供无限的私人图表。
  * [Confluence](https://www.atlassian.com/software/confluence) - Atlassian 的内容协作工具用于帮助团队高效协作和共享知识。最多可容纳 10 位用户的免费计划。
  * [Crosswork](https://crosswork.app/) - 多功能项目管理平台。最多可免费使用 3 个项目、无限用户、1 GB 存储空间。
  * [diagrams.net](https://app.diagrams.net/) - 在线图表本地存储在 Google Drive、OneDrive 或 Dropbox 中。所有功能和存储级别均免费
  * [easyretro.io](https://www.easyretro.io/) - 简单直观的冲刺回顾工具。该免费计划包含三个公共看板，每个看板/月进行一项调查。
  * [freedcamp.com](https://freedcamp.com/) - 任务、讨论、里程碑、时间跟踪、日历、文件和密码管理器。免费计划，项目、用户和文件存储不受限制。
  * [GForge](https://gforge.com) - 适用于具有自营和 SaaS 选项的复杂项目的项目管理和问题跟踪工具集。 SaaS 免费计划为前五个用户免费提供开源项目。
  * [gleek.io](https://www.gleek.io) - 为开发人员提供免费的描述到图表工具。使用关键字创建非正式的 UML 类、对象或实体关系图。
  * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector 输出两个 GraphQL 模式之间的更改列表。每个差异都经过精确解释并标记为破坏性、非破坏性或危险性。
  * [Helploom](https://helploom.com) - 客户支持软件，提供有关永久免费计划的实时聊天。简单、轻便、美观。安装程序是一个简单的复制粘贴脚本。由开发商建造。
  * [Hygger](https://hygger.io) - 项目管理平台。免费计划提供无限的用户、项目和板以及 100 MB 的存储空间。
  * [Ilograph](https://www.ilograph.com/) -  交互式图表允许用户从多个角度和详细程度查看其基础设施。图表可以用代码来表达。免费套餐拥有无限的私人图表，最多可容纳 3 位查看者。
  * [Jira](https://www.atlassian.com/software/jira) - 许多企业环境中使用的高级软件开发项目管理工具。最多可容纳 10 位用户的免费计划。
  * [kan.bn](https://kan.bn/) - 一款功能强大、灵活的看板应用程序，可帮助您在一个地方组织工作、跟踪进度并交付结果。最多 1 位用户的免费计划，可享受无限的看板、无限的列表、无限的卡片。
  * [kanbanflow.com](https://kanbanflow.com/) - 基于董事会的项目管理。免费，高级版本有更多选择
  * [kanbantool.com](https://kanbantool.com/) - 基于看板的项目管理。免费计划有两个板和两个用户，没有附件或文件。
  * [Kitemaker.co](https://kitemaker.co) - 在产品开发流程的所有阶段进行协作，并跟踪 Slack、Discord、Figma 和 Github 上的工作。无限用户，无限空间。免费计划最多 250 个工作项目。
  * [Kiter.app](https://www.kiter.app/) - 让任何人都可以组织自己的求职并跟踪面试、机会和联系。强大的网络应用程序和 Chrome 扩展程序。完全免费。
  * [Kumu.io](https://kumu.io/) -  具有动画、装饰、过滤器、聚类、电子表格导入等的关系图。免费套餐允许无限的公共项目。图形大小不受限制。为学生提供免费的私人项目。如果您不想将文件公开在线(上传、编辑、下载、丢弃)，则可以使用沙盒模式。
  * [leiga.com](https://www.leiga.com/) - Leiga是一款SaaS产品，它使用AI自动管理您的项目，帮助您的团队保持专注并释放巨大潜力，确保您的项目按计划进行。最多 10 个用户免费，20 个自定义字段，2GB 存储空间，AI 视频录制仅限 5 分钟/视频，自动化运行速度为 20 个/用户/月。
  * [Linear](https://linear.app/) - 具有简化界面的问题跟踪器。会员免费，上传文件大小不超过 10MB，250 期(不包括存档)
  * [Lucidchart](https://www.lucidchart.com/) - 具有协作功能的在线图表工具。免费计划，包含三个可编辑文档、100 个专业模板和基本协作功能。
  * [MeisterTask](https://www.meistertask.com/) - 团队在线任务管理。免费最多 3 个项目和无限的项目成员。
  * [MeuScrum](https://www.meuscrum.com/en) - 带看板的免费在线 Scrum 工具
  * [nTask](https://www.ntaskmanager.com/) - 项目管理软件使您的团队能够协作、计划、分析和管理日常任务。基本计划永久免费，拥有 100 MB 存储空间和五个用户/团队。无限的工作空间、会议、作业、时间表和问题跟踪。
  * [Plane](https://plane.so/) - Plane 是一个简单、可扩展、开源的项目和产品管理工具。会员免费，上传文件大小不超过 5MB，1000 期。
  * [planitpoker.com](https://www.planitpoker.com/) - 免费在线规划扑克(估算工具)
  * [point.poker](https://www.point.poker/) - 在线规划扑克(基于共识的估计工具)。免费提供无限用户、团队、会议、回合和投票。您无需注册。
  * [Pulse.red](https://pulse.red) - 适用于项目的免费简约时间跟踪器和时间表应用程序。
  * [ScrumFast](https://www.scrumfast.com) - Scrum 板具有非常直观的界面，最多可免费容纳 5 个用户。
  * [Sflow](https://sflow.io) - sflow.io 是一款专为敏捷软件开发、营销、销售和客户支持而构建的项目管理工具，尤其适用于外包和跨组织协作项目。免费规划最多 3 个项目和 5 名成员。
  * [Shake](https://www.shakebugs.com/) - 适用于移动应用程序的应用程序内错误报告和反馈工具。免费计划，每个应用程序/月十个错误报告。
  * [Shortcut](https://shortcut.com/) - 项目管理平台。最多 10 位用户永久免费。
  * [taiga.io](https://taiga.io/) - 面向初创公司和敏捷开发人员的项目管理平台，免费开源
  * [taskade.com](https://www.taskade.com/) - 实时协作任务列表和团队大纲。免费计划拥有一个工作区，其中包含无限的任务和项目； 1GB文件存储空间； 1周的项目历史；每个视频会议有五名与会者。
  * [Teaminal](https://www.teaminal.com) - 适用于远程团队的站立、回顾和冲刺计划工具。最多 15 位用户免费。
  * [teamwork.com](https://teamwork.com/) - 项目管理和团队聊天。五个用户和两个项目免费。提供高级计划。
  * [teleretro.com](https://www.teleretro.com/) - 简单有趣的回顾工具，包含破冰游戏、GIF 和表情符号。免费计划包括三个回顾和无限会员。
  * [Tenzu](https://tenzu.net/) - 适用于敏捷团队的轻量级项目管理工具。 SaaS 依赖于免费贡献；用户始终可以选择给予 0 并且没有付费专区 {[more details](https://tenzu.net/pricing/)}
  * [titanapps.io](https://titanapps.io/) - Jira 和 monday.com 的生产力工具，在问题/任务中提供结构化清单、模板和批准。适合小型团队的免费计划。
  * [todoist.com](https://todoist.com/) - 协作和个人任务管理。免费计划有：5个活跃项目、项目中的五个用户、上传最多5MB的文件、三个过滤器和一星期的活动历史记录。
  * [Toggl](https://toggl.com/) - 提供两种免费的生产力工具。[Toggl Track](https://toggl.com/track/)用于时间管理和跟踪应用程序，具有免费计划，提供专为自由职业者设计的无缝时间跟踪和报告。它具有无限的跟踪记录、项目、客户、标签、报告等。[Toggl Plan](https://toggl.com/plan/)用于任务规划，为独立开发人员提供免费计划，具有无限的任务、里程碑和时间表。
  * [trello.com](https://trello.com/) - 基于董事会的项目管理。无限个个人看板，10 个团队看板。
  * [Tweek](https://tweek.so/) - 简单的/周待办事项日历和任务管理。
  * [Wikifactory](https://wikifactory.com/) - 包含项目、VCS 和问题的产品设计服务。免费计划提供无限的项目和协作者以及 3GB 存储空间。
  * [Yodiz](https://www.yodiz.com/) - 敏捷开发和问题跟踪。最多可免费使用 3 个用户，项目不受限制。
  * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) - 免费托管 YouTrack (InCloud)，适用于 FOSS 项目和私人项目(三个用户免费)。包括时间跟踪和敏捷板
  * [zenhub.com](https://www.zenhub.com) - GitHub 内唯一的项目管理解决方案。对公共仓库、OSS 和非营利组织免费
  * [zenkit.com](https://zenkit.com) - 项目管理和协作工具。最多 5 名成员免费，附件 5 GB。
  * [Zube](https://zube.io) - 项目管理，提供 4 个项目和 4 个用户的免费计划。 GitHub 集成可用。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="storage-and-media-processing"></a>
## 存储和媒体处理

  * [AndroidFileHost](https://androidfilehost.com/) - 免费文件共享平台，速度、带宽、文件数、下载数等均不受限制。它主要针对 Android 开发相关文件，如 APK 构建、自定义 ROM 和修改等。但似乎也接受任何其他文件。
  * [anon.li Drop](https://anon.li/drop) - 通过客户端 AES-256-GCM 加密和零服务器端数据访问实现零知识 E2EE 文件共享。通过网站、CLI 或 API 免费上传最大 5GB 的文件，最长有效期为 3 天。
  * [borgbase.com](https://www.borgbase.com/) - Borg Backup 的简单安全的异地备份托管。 10 GB 可用备份空间和两个存储库。
  * [cloudinary.com](https://cloudinary.com/) - 使用 Ruby、Python、Java、PHP、Objective-C 等库，为网站和应用程序提供图像上传、强大的操作、存储和交付。免费套餐包含 25 个/月积分。一个积分相当于 1,000 次图像转换、1 GB 存储空间或 1 GB CDN 使用量。
  * [degoo.com](https://degoo.com/) - 基于 AI 的云存储，免费高达 20 GB，三台设备，5 GB 推荐奖金(90 天帐户不活动)。
  * [Dropshare](https://dropsha.re) - 零知识文件共享。通过 AES-256-GCM 加密、客户端处理和零服务器端数据访问实现端到端加密文件共享。免费上传最大 1GB 的文件，无需收集数据。
  * [embed.ly](https://embed.ly/) - 提供用于在网页中嵌入媒体、响应式图像缩放以及从网页中提取元素的 API。/月最多可免费访问 5,000 个 URL，每秒 15 个请求
  * [Ente](https://ente.io/) - Ente 是一个用于存储照片、视频和 2FA 机密的端到端加密云。还可以自行托管，并提供 10GB 的永久免费空间。对于免费套餐用户，仅保留单个数据副本。
  * [FileShot.io](https://fileshot.io) - 零知识加密文件共享。 AES-256-GCM 浏览器端加密可确保文件在上传前在浏览器中进行加密。发件人或收件人不需要帐户。可自行托管(麻省理工学院开源)。免费套餐包括无限上传，没有文件大小限制。
  * [file.io](https://www.file.io) - 2 GB 文件存储空间。文件下载一次后会自动删除。用于与存储交互的 REST API。速率限制一个请求/分钟。
  * [freetools.site](https://freetools.site/) - 免费在线工具。转换或编辑文档、图像、音频、视频等。
  * [getpantry.cloud](https://getpantry.cloud/) - 一个简单的 JSON 数据存储 API，非常适合个人项目、黑客马拉松和移动应用程序！
  * [GoFile.io](https://gofile.io/) - 可以通过基于 Web 的 UI 和 API 使用免费的文件共享和存储平台。不限制文件大小、带宽、下载次数等。但当文件变为非活动状态(超过十天没有下载)时，它将被删除。
  * [gumlet.com](https://www.gumlet.com/) - 通过 CDN 托管、处理和流式传输图像和视频。为视频提供 250 GB/月的免费套餐，为图像提供/月 30 GB 的免费套餐。
  * [icedrive.net](https://www.icedrive.net/) - 简单的云存储服务。 10 GB 免费存储空间
  * [image-charts.com](https://www.image-charts.com/) - 带水印的无限图像图表生成
  * [ImageEngine](https://imageengine.io/) - ImageEngine是一个易于使用的全局图像CDN。低于 60 秒的设置。支持 AVIF 和 JPEGXL、WordPress、Magento、React、Vue 插件等。领取您的免费开发者帐户[here](https://imageengine.io/developer-program/)。
  * [imagekit.io](https://imagekit.io) - 具有自动优化、实时转换和存储功能的图像 CDN，您可以在几分钟内与现有设置集成。免费计划包括/月高达 20GB 的带宽。
  * [ImgBB](https://imgbb.com/) - ImgBB 是一个无限制的图像托管服务。将图像拖放到屏幕上的任意位置。 32 MB/图像限制。上传图像后接收直接图像链接、BBCode 和 HTML 缩略图。登录查看上传历史记录。
  * [Imgbot](https://github.com/marketplace/imgbot) - Imgbot 是一个友好的机器人，可以优化您的图像并节省您的时间。优化的图像意味着在不牺牲质量的情况下更小的文件大小。它是免费的开源软件。
  * [imgen](https://www.jitbit.com/imgen/) - 用于 OpenGraph 图像的动态图像生成 API(背景文本、徽标)、免费、无水印、CDN
  * [imgix](https://www.imgix.com/) - 图像缓存、管理和 CDN。免费计划包括 1000 张原始图像、无限变换和 100 GB 带宽
  * [internxt.com](https://internxt.com) - Internxt Drive 是一种基于绝对隐私和毫不妥协的安全性的零知识文件存储服务。注册并永久免费获得 10 GB！
  * [kraken.io](https://kraken.io/) - 网站性能图像优化即服务，免费计划最大文件大小为 1 MB
  * [LibreQR](https://libreqr.com) - 免费的二维码生成器专注于隐私且无跟踪。免费使用，无需收集数据。
  * [MConverter](https://mconverter.eu/) - 批量转换文件。支持多种格式，包括[AVIF](https://mconverter.eu/convert/to/avif/)和 JXL。从视频中提取图像帧。压缩 PDF。每 24 小时免费提供 15 个文件，每个文件最多 100 MB，以 8 个为一组进行处理。
  * [nitropack.io](https://nitropack.io/) - 通过完整的前端优化(缓存、图像和代码优化、CDN)，加快网站的自动运行速度。/月最多 5,000 次浏览量免费
  * [npoint.io](https://www.npoint.io/) - 具有协作模式编辑功能的 JSON 存储
  * [MantleDB](https://mantledb.sh) - 用于脚本和小型应用程序的匿名 JSON 存储。无需注册；使用主 AID 进行更新，使用只读 RID 进行公共获取。免费套餐包括 1 个存储桶(限制为 1MB)，并具有 72 小时不活动清除策略。
  * [otixo.com](https://www.otixo.com/) - 从一处加密、共享、复制和移动所有云存储文件。基本计划提供无限制的文件传输，最大 250 MB。文件大小并允许五个加密文件
  * [packagecloud.io](https://packagecloud.io/) - YUM、APT、RubyGem 和 PyPI 的托管包存储库。  可根据要求提供有限的免费计划和开源计划
  * [pcloud.com](https://www.pcloud.com/) - 云存储服务。高达 10 GB 的免费存储空间
  * [Pinata IPFS](https://pinata.cloud) - Pinata 是在 IPFS 上上传和管理文件的最简单方法。我们友好的用户界面和 IPFS API 使 Pinata 成为平台、创作者和收藏者最简单的 IPFS 固定服务。 1 GB 免费存储空间，以及 API 访问权限。
  * [plot.ly](https://plot.ly/) - 绘制图表并分享您的数据。免费套餐包括无限的公共文件和十个私人文件
  * [podio.com](https://podio.com/) - 您可以与最多五人的团队一起使用 Podio，并尝试基本计划的功能(用户管理除外)
  * [Proton Drive](https://proton.me/drive) - 文件和关键文档的超安全云存储。免费计划提供 5GB 存储空间。
  * [QRtracer](https://qrtracer.io) - 免费的二维码生成器，具有内置扫描分析、批量生成和品牌定制功能，专注于可靠性，没有任何广告。
  * [QuickChart](https://quickchart.io) - 生成可嵌入的图像图表、图形和二维码
  * [redbooth.com](https://redbooth.com) - P2P 文件同步，最多 2 个用户免费
  * [resmush.it](https://resmush.it) - reSmush.it 是一个免费的 API，提供图像优化。 reSmush.it 已在最常见的 CMS 上实现，例如 WordPress、Drupal 或 Magento。 reSmush.it 是最常用的图像优化 API，已处理超过 70 亿张图像，并且仍然免费。
  * [sirv.com](https://sirv.com/) - 智能图像 CDN，具有动态图像优化和调整大小功能。免费套餐包括 500 MB 存储空间和 2 GB 带宽。
  * [SlingSite](https://slingsite.github.io) - 创建图像和视频的所有优化版本。免费。批量。对于每张图像，您将获得以下格式：三种选定分辨率(桌面、平板电脑、移动设备)的 AVIF、WEBP 和 JPG 对于视频，您将获得：WebM(编解码器 VP9)、MP4(编解码器 HEVC 又名 H.265)和 MP4(编解码器 AVC 又名 H.264)以及第一帧的封面图像。
  * [sync.com](https://www.sync.com/) - 端到端的云存储服务。 5 GB 免费存储空间
  * [tinypng.com](https://tinypng.com/) - 用于压缩 PNG 和 JPEG 图像并调整其大小的 API，/月免费提供 500 次压缩
  * [transloadit.com](https://transloadit.com/) - 处理视频、音频、图像、文档的文件上传和编码。通过 GitHub 学生开发包免费向开源、慈善机构和学生开放。商业应用程序可免费获得 2 GB 用于测试驱动
  * [twicpics.com](https://www.twicpics.com) - 响应式图像即服务。它提供图像 CDN、媒体处理 API 和前端库来自动优化图像。该服务/月最多可免费使用 3GB 流量。
  * [uploadcare.com](https://uploadcare.com/hub/developers/) - Uploadcare 为媒体管道提供基于尖端算法的终极工具包。所有功能均完全免费供开发人员使用：文件上传 API 和 UI、图像 CDN 和源服务、自适应交付和智能压缩。免费套餐具有 3000 次上传、3 GB 流量和 3 GB 存储空间。
  * [VaocherApp QR Code Generator](https://www.vaocherapp.com/qr-code-generator) - 轻松创建礼品卡、礼券和促销活动的自定义二维码。支持自定义样式、颜色、标志...

**[⬆️ 返回顶部](#table-of-contents)**

<a id="design-and-ui"></a>
## 设计和 UI

  * [BoxySVG](https://boxy-svg.com) - 一款免费的可安装 Web 应用程序，用于绘制 SVG 并以 SVG、PNG、jpeg 和其他格式导出。
  * [Calendar Icons Generator](https://calendariconsgenerator.app/) - 只需单击一下即可生成一整年的独特图标，完全免费
  * [Canva](https://canva.com) - 用于创建视觉内容的免费在线设计工具。
  * [CodedThemes](https://codedthemes.com/) - 提供精心设计的管理仪表板和 UI 套件，旨在简化和加速现代 Web 开发。
  * [Excalidraw](https://excalidraw.com/) - 免费的在线绘图文档网页，支持免费保存到本地和导出。
  * [figma.com](https://www.figma.com) - 面向团队的在线协作设计工具；免费套餐包括无限的文件和查看器，最多 2 个编辑器和 3 个项目。
  * [Flows](https://flows.sh/) - 一个完全可定制的产品采用平台，用于构建入职和用户参与体验。最多 250 名/月跟踪的用户免费。
  * [landen.co](https://www.landen.co) - 为您的初创企业生成、编辑和发布精美的网站和登陆页面。全部无代码。免费套餐允许您拥有一个完全可定制并在网络上发布的网站。
  * [lensdump.com](https://lensdump.com/) - 免费云图像托管。
  * [Logo.dev](https://www.logo.dev) - 拥有超过 4400 万个品牌的公司徽标 API，就像调用 URL 一样简单。前 10,000 次 API 调用免费。
  * [marvelapp.com](https://marvelapp.com/) - 设计、原型制作和协作，仅限一个用户和项目的免费计划。
  * [Mindmup.com](https://www.mindmup.com/) - 免费无限量思维导图并将其存储在云端。您的思维导图可以通过任何设备随时随地使用。
  * [Mockplus iDoc](https://www.mockplus.com/idoc) - Mockplus iDoc是一款功能强大的设计协作和交接工具。免费计划包括三个用户和五个项目，并提供所有可用功能。
  * [photopea.com](https://www.photopea.com) - 一款免费的高级在线设计编辑器，带有 Adobe Photoshop UI，支持 PSD、XCF 和 Sketch 格式(Adobe Photoshop、Gimp 和 Sketch 应用程序)。
  * [Plasmic](https://www.plasmic.app/) - 一个快速、易于使用、强大的网页设计工具和页面构建器，可集成到您的代码库中。构建响应式页面或复杂组件；可选择使用代码扩展；并发布到生产站点和应用程序。
  * [Proto.io](https://www.proto.io) - 无需编码即可创建完全交互式的 UI 原型。免费试用结束后即可使用免费套餐。免费套餐包括一名用户、一个项目、五个原型、100MB 在线存储以及 proto.io 应用程序的预览版。
  * [Quant Ux](https://quant-ux.com/) - Quant Ux 是一款原型设计和设计工具。 - 它是完全免费且开源的。
  * [Shadcn Studio](https://shadcnstudio.com/theme-editor) - 预览不同组件和布局中的主题更改。
  * [smartmockups.com](https://smartmockups.com/) - 创建产品模型，200 个免费模型。
  * [TeleportHQ](https://teleporthq.io/) - 低代码前端设计和开发平台。 TeleportHQ 是一个协作前端平台，可立即创建和发布无头静态网站。三个免费项目、无限合作者和免费代码导出。
  * [Unicorn Platform](https://unicornplatform.com/) - 带托管功能的轻松登陆页面构建器。一个免费网站。
  * [Updrafts.app](https://updrafts.app) - 用于基于 tailwindcss 设计的所见即所得网站构建器。免费用于非商业用途。
  * [Webflow](https://webflow.com) - 所见即所得的网站构建器，具有动画和网站托管功能。免费用于两个项目。
  * [Webstudio](https://webstudio.is/) - Webflow 的开源替代品。免费计划在其域名上提供无限的网站。五个具有自定义域的网站。一万次页面浏览量/月。 2 GB 资产存储。
  * [whimsical.com](https://whimsical.com/) - 协作流程图、线框图、便签和思维导图。创建最多 4 个空闲板。
  * [Zeplin](https://zeplin.io/) - 设计师和开发人员协作平台。显示设计、资源和风格指南。一个项目免费。
  * [WrapPixel](https://www.wrappixel.com/) - 下载使用 Angular、React、VueJs、NextJS 和 NuxtJS 创建的高质量免费和高级管理仪表板模板！ HTML 主题和 UI 套件可帮助您更快地创建应用程序！
  * [Themeselection](https://themeselection.com/) - 精选高品质、现代设计、专业且易于使用的免费管理仪表板模板，
  * [AdminMart](https://adminmart.com/) - 使用 Angular、Bootstrap、React、VueJs、NextJS 和 NuxtJS 创建的高质量免费和高级管理仪表板和网站模板！

**[⬆️ 返回顶部](#table-of-contents)**

<a id="data-visualization-on-maps"></a>
## 地图数据可视化

  * [Clockwork Micro](https://clockworkmicro.com/) - 像发条一样工作的地图工具。/月 5 万次免费查询(地图图块、db2vector、海拔)。
  * [Foursquare](https://developer.foursquare.com/) - 来自 Places API 和 Pilgrim SDK 的位置发现、地点搜索和上下文感知内容。
  * [geoapify.com](https://www.geoapify.com/) - 矢量和栅格地图图块、地理编码、地点、路线、等值线 API。/天三千个免费请求。
  * [geocod.io](https://www.geocod.io/) - 通过 API 或 CSV 上传进行地理编码。/天两千五百个免费查询。
  * [geocodify.com](https://geocodify.com/) - 通过 API 或 CSV 上传进行地理编码和地理解析。/月 10,000 次免费查询。
  * [geojs.io](https://www.geojs.io/) - 高度可用的 REST/JSON/JSONP IP 地理位置查找 API。
  * [Geokeo api](https://geokeo.com) - 具有语言校正等功能的地理编码 API。全球覆盖。每日 2,500 次免费查询
  * [graphhopper.com](https://www.graphhopper.com/) - 提供了用于路线选择、路线优化、距离矩阵、地理编码和地图匹配的免费开发人员包。
  * [here](https://developer.here.com/) - 用于地图和位置感知应用程序的 API 和 SDK。/月 25 万笔交易免费。
  * [IP Geolocation](https://ipgeolocation.io/) - 免费开发者计划/月可处理 30K 请求。
  * [ipstack](https://ipstack.com/) - 通过 IP 地址定位和识别网站访问者
  * [LatLng](https://www.latlng.work) - 地理编码、反向地理编码、地点、静态地图和矢量地图图块 API。免费套餐包括/天 3,000 个地理编码请求、/天 300 个反向地理编码请求以及/天 100 个静态地图图像。
  * [locationiq.com](https://locationiq.com/) - 地理编码、地图和路线 API。/天 5000 个免费请求。
  * [mapbox.com](https://www.mapbox.com/) - 地图、地理空间服务和用于显示地图数据的 SDK。
  * [maps.stamen.com](http://maps.stamen.com/) - 免费地图图块和图块托管。
  * [maptiler.com](https://www.maptiler.com/cloud/) - 用于地图可视化的矢量地图、地图服务和 SDK。免费矢量图块，/周更新和四种地图样式。
  * [nominatim.org](https://nominatim.org/) - OpenStreetMap 的免费地理编码服务，提供全球地址搜索功能和反向地理编码功能。
  * [opencagedata.com](https://opencagedata.com) - 聚合 OpenStreetMap 和其他开放地理资源的地理编码 API。/天两千五百个免费查询。
  * [osmnames](https://osmnames.org/) - 地理编码，搜索结果按相关维基百科页面的受欢迎程度排名。
  * [positionstack](https://positionstack.com/) - 全球地点和坐标的免费地理编码。/月 25,000 个请求供个人使用。
  * [stadiamaps.com](https://stadiamaps.com/) - 地图图块、路线、导航和其他地理空间 API。/天 2500 个免费地图视图和 API 请求，用于非商业使用和测试。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="package-build-system"></a>
## 包构建系统

  * [build.opensuse.org](https://build.opensuse.org/) - 适用于多个发行版(SUSE、EL、Fedora、Debian 等)的软件包构建服务。
  * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) - 针对 Fedora 和 EL 的基于模拟的 RPM 构建服务。
  * [help.launchpad.net](https://help.launchpad.net/Packaging) - Ubuntu 和 Debian 构建服务。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="ide-and-code-editing"></a>
## IDE 和代码编辑


  * [Android Studio](https://developer.android.com/studio) - Android Studio 提供了在各种类型的 Android 设备上构建应用程序的最快工具。开源 IDE 对所有人免费，是最好的 Android 应用程序开发。适用于 Windows、Mac、Linux，甚至 ChromeOS！
  * [AndroidIDE](https://m.androidide.com/) - 一个开源 IDE，用于在 Android 设备上开发真正的、基于 Gradle 的 Android 应用程序。
  * [Apache Netbeans](https://netbeans.apache.org/) - 开发环境、工具平台和应用程序框架。
  * [apiary.io](https://apiary.io/) - 协作设计 API，具有即时 API 模拟和生成的文档(免费提供无限的 API 蓝图和无限的用户，只需一个管理员帐户和托管文档)。
  * [BBEdit](https://www.barebones.com/) - BBEdit 是一款适用于 macOS 的流行且可扩展的编辑器。免费模式提供[powerful core feature set](https://www.barebones.com/products/bbedit/comparison.html)和高级功能的升级路径。
  * [Binder](https://mybinder.org/) - 将 Git 存储库转变为交互式笔记本的集合。这是一项免费的公共服务。
  * [BlueJ](https://bluej.org) - 专为初学者设计的免费 Java 开发环境，全球有数百万人使用。由 Oracle 和简单的 GUI 提供支持，可以帮助初学者。
  * [Brackets](http://brackets.io/) - Brackets 是一款专为 Web 开发而设计的开源文本编辑器。它重量轻、易于使用且高度可定制。
  * [cacher.io](https://www.cacher.io) - 带有标签的代码片段管理器，支持 100 多种编程语言。
  * [cocalc.com](https://cocalc.com/) - 云端协同计算。通过浏览器访问完整的 Ubuntu，内置协作和大量预装的数学、科学、数据科学免费软件：Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn 等。
  * [Code::Blocks](https://codeblocks.org) - 免费的 Fortran 和 C/C++ IDE。开源并可在 Windows、macOS 和 Linux 上运行。
  * [codiga.io](https://codiga.io/) - 编码助手可让您直接在 IDE 中搜索、定义和重用代码片段。对个人和小型组织免费。
  * [Components.studio](https://webcomponents.dev/) - 隔离地编写组件、在故事中可视化它们、测试它们并将它们发布到 npm 上。
  * [Eclipse Che](https://www.eclipse.org/che/) - 面向开发团队的基于 Web 的 Kubernetes 原生 IDE，具有多语言支持。开源和社区驱动。由 Red Hat 托管的在线实例可在[workspaces.openshift.com](https://workspaces.openshift.com/)处获取。
  * [ForgeCode](https://forgecode.dev/) - 支持 AI 的结对程序员，适用于 Claude、GPT4 系列、Grok、Deepseek、Gemini 和所有前沿型号。与 CLI 原生配合使用，并与任何 IDE 无缝集成。免费套餐包括具有本地处理功能的基本 AI 模型访问。
  * [GetVM](https://getvm.io) - 即时免费的 Linux 和 IDE chrome 侧边栏。免费套餐包括/天 5 个虚拟机。
  * [JDoodle](https://www.jdoodle.com) - 适用于 60 多种编程语言的在线编译器和编辑器，提供 REST API 代码免费计划，/天编译最多 200 个学分。
  * [jetbrains.com](https://jetbrains.com/products.html) - 生产力工具、IDE 和部署工具(又名[IntelliJ IDEA](https://www.jetbrains.com/idea/)、[PyCharm](https://www.jetbrains.com/pycharm/)等)。学生、教师、开源和用户组的免费许可证。
  * [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - 一些 REST API 端点以 JSON 格式返回一些虚假数据。如果您想在本地运行服务器，也可以使用源代码。
  * [Lazarus](https://www.lazarus-ide.org/) - Lazarus 是一个与 Delphi 兼容的跨平台 IDE，用于快速应用程序开发。
  * [MarsCode](https://www.marscode.com/) - 一款免费的人工智能驱动的基于云的 IDE。
  * [micro-jaymock](https://micro-jaymock.now.sh/) - 用于生成假 JSON 数据的微型 API 模拟微服务。
  * [mockable.io](https://www.mockable.io/) - Mockable 是一个简单的可配置服务，用于模拟 RESTful API 或 SOAP Web 服务。该在线服务允许您快速定义 REST API 或 SOAP 端点并让它们返回 JSON 或 XML 数据。
  * [mockaroo](https://mockaroo.com/) - Mockaroo 可让您生成 CSV、JSON、SQL 和 Excel 格式的真实测试数据。您还可以为后端 API 创建模拟。
  * [Mocklets](https://mocklets.com) - 基于 HTTP 的模拟 API 模拟器，可帮助模拟 API，以实现更快的并行开发和更全面的测试，并提供终身免费套餐。
  * [OneCompiler](https://onecompiler.com/) - 免费在线编译器，支持 70 多种语言，包括 Java、Python、C++、JavaScript。
  * [OnlineGDB](https://onlinegdb.com) - 一款免费的在线 ide，支持 40 多种语言，并预装了大量库；并且还有调试选项、标志、教程和 QNA 页面！
  * [pterocos](https://pterocos.eu.org) - 为前端开发人员提供的基于浏览器的免费开源编码环境。使用 VS 代码级编辑器(摩纳哥)编写 html、css 和 js，实时预览、scss/typeScript/babel 支持以及用于调试和建议的人工智能聊天助手。所有项目都保存到本地存储。永久免费 – 无需帐户。
  * [Paiza](https://paiza.cloud/en/) - 在浏览器中开发 Web 应用程序，无需进行任何设置。免费计划提供一台具有 24 个 24 小时使用寿命和/天 4 小时运行时间的服务器，具有 2 个 CPU 核心、2 GB RAM 和 1 GB 存储空间。
  * [PHPSandbox](https://phpsandbox.io/) - PHP在线开发环境
  * [Replit](https://replit.com/) - 适用于各种程序语言的云编码环境。
  * [RunMat](https://runmat.com/sandbox) - 浏览器中 GPU 加速的数值计算 IDE。通过 WebAssembly 和 WebGPU 使用自动 GPU 加速编写和运行 MATLAB-syntax .m 文件。无需安装，无需帐户，无需许可费。具有 CLI、NPM 包和 Jupyter 内核支持的开源运行时。
  * [SoloLearn](https://code.sololearn.com) - 非常适合运行代码片段的云编程游乐场。支持多种编程语言。运行代码不需要注册，但在其平台上保存代码时需要注册。还为初学者和中级编码员提供免费课程。
  * [stackblitz.com](https://stackblitz.com/) - 用于创建、编辑和部署全栈应用程序的在线/云代码 IDE。支持任何流行的基于 NodeJs 的前端和后端框架。创建新项目的短链接：[https://node.new](https://node.new)。
  * [Sublime Text](https://www.sublimetext.com/) - Sublime Text 是一种流行的、多功能的、高度可定制的文本编辑器，用于编码和文本编辑任务。
  * [Visual Studio Code](https://code.visualstudio.com/) - 代码编辑器重新定义和优化，用于构建和调试现代 Web 和云应用程序。由微软开发。
  * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) - 功能齐全的 IDE，具有数千个扩展、跨平台应用程序开发(适用于 iOS 和 Android 的 Microsoft 扩展可供下载)、桌面、Web 和云开发、多语言支持(C#、C++、JavaScript、Python、PHP 等)。
  * [VSCodium](https://vscodium.com/) - 社区驱动、无遥测/跟踪、免费许可的 Microsoft 编辑器 VSCode 二进制发行版
  * [wakatime.com](https://wakatime.com/) - 使用文本编辑器插件对您的编码活动进行量化的自我衡量，有限的免费计划。
  * [Wave Terminal](https://waveterm.dev/) - Wave 是一个开源、跨平台的终端，可实现无缝工作流程。内联渲染任何内容。保存会话和历史记录。由开放网络标准提供支持。 MacOS 和 Linux。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="analytics-events-and-statistics"></a>
## 分析、事件和统计

  * [amplitude.com](https://amplitude.com/) - /月 100 万个活动，最多 2 个应用程序
  * [AppFit](https://appfit.io) - AppFit 是一款全面的分析和产品管理工具，旨在促进分析和产品更新的无缝、跨平台管理。免费计划包括/月 10,000 个活动、产品日志和/周见解。
  * [Aptabase](https://aptabase.com) - 适用于移动和桌面应用程序的开源、隐私友好且简单的分析。适用于 Swift、Kotlin、React Native、Flutter、Electron 等的 SDK。/月最多可免费举办 20,000 个活动。
  * [Avo](https://avo.app/) - 简化的分析发布工作流程。单一事实来源跟踪计划、类型安全的分析跟踪库、应用内调试器和数据可观察性，可在发布之前捕获所有数据问题。两名工作区成员免费，并可享受 1 小时的数据可观察性回顾。
  * [Beampipe.io](https://beampipe.io) - Beampipe 是一种简单、注重隐私的网络分析工具。免费最多 5 个域名和 10,000 /月页面浏览量。
  * [Census](https://www.getcensus.com/) - 反向 ETL 和运营分析平台。将数据仓库中的 10 个字段同步到 60 多个 SaaS，例如 Salesforce、Zendesk 或 Amplitude。
  * [Clicky](https://clicky.com) - 网站分析平台。免费计划一个具有 3000 次浏览分析的网站。
  * [counter.dev](https://counter.dev) - 网络分析变得简单，因此隐私友好。免费或通过捐赠支付您想要的费用。
  * [DocBeacon](https://docbeacon.io) - 通过文档跟踪和参与分析确保文档共享的安全。免费计划支持最多 20 个 PDF 文档(最大 10 MB)、10 个联系人以及每个文档 2 次共享，并提供浏览量下载、时间和参与度的基本分析。
  * [Dwh.dev](https://dwh.dev) - 数据云可观测性解决方案(雪花)。免费供个人使用。
  * [Expensify](https://www.expensify.com/) - 费用报告、免费个人报告审批工作流程
  * [getinsights.io](https://getinsights.io) - 注重隐私、无 cookie 的分析，/月最多免费提供 3000 个事件。
  * [Gizmo Analytics](https://gizmoanalytics.io/) - 为管理大量站点的人员提供简单的分析。手动安装或让 Claude/Cursor 为您安装。/月最多可免费参加 10,000 场活动。
  * [GoatCounter](https://www.goatcounter.com/) - GoatCounter 是一个开源网络分析平台，可作为托管服务(免费用于非商业用途)或自托管应用程序。它的目标是提供易于使用且有意义的隐私友好型网络分析，作为 Google Analytics 或 Matomo 的替代品。免费套餐适用于非商业用途，包括无限的站点、六个月的数据保留和/月 10 万页浏览量。
  * [Google Analytics](https://analytics.google.com/) - 谷歌分析
  * [heap.io](https://heap.io) - 自动捕获 iOS 或 Web 应用程序中的每个用户操作。/月最多可免费使用 10K 次会话。
  * [Hightouch](https://hightouch.com/) - Hightouch 是一个反向 ETL 平台，可帮助您将数据仓库中的客户数据同步到 CRM、营销和支持工具。免费套餐为您提供一个同步数据的目的地。
  * [HitKeep](https://hitkeep.com/) - 注重隐私的开源网络和产品分析平台，为 3 个网站、3 名团队成员提供免费云计划、60 天数据保留、AI 分析、目标、渠道、事件和点击。
  * [Hotjar](https://hotjar.com) - 网站分析和报告。免费计划允许/天 2000 次浏览量。/天一百个快照(最大容量：300)。三张快照热图可保存 365 天。无限的团队成员。此外，在应用程序和独立调查中，还提供带有屏幕截图的反馈小部件。免费套餐允许创建 3 项调查和 3 个反馈小部件，并/月收集 20 个回复。
  * [LogSpot](https://logspot.io) - 完全统一的网络和产品分析平台，包括嵌入式分析小部件和自动化机器人(slack、telegram 和 webhooks)。免费计划包括/月 10,000 个活动。
  * [Mixpanel](https://mixpanel.com/) - /月 100,000 名跟踪用户、无限数据历史记录和席位、美国或欧盟数据驻留
  * [Moesif](https://www.moesif.com) - REST 和 GraphQL 的 API 分析。 (免费最多 500,000 次 API 调用/月)
  * [PostHog](https://posthog.com) - 完整的产品分析套件免费，/月最多可跟踪 100 万个事件。还提供无限量的应用内调查，/月有 250 份回复。
  * [Repohistory](https://repohistory.com) - 漂亮的仪表板，用于跟踪超过 14 天的 GitHub 存储库流量历史记录。免费计划允许用户监控单个存储库的流量。
  * [Row Zero](https://rowzero.io) - 速度极快、互联的电子表格。直接连接到数据数据库、S3 和 API。即时导入、分析、绘制图表并共享数百万行。三本免费(永久)的练习册。
  * [Rybbit](https://rybbit.io) - Google Analytics 的开源、无 cookie 替代方案，直观性提高 10 倍。免费计划包含 3,000 个/月活动。
  * [Seline](https://seline.so) - Seline 是一个简单且私人的网站和产品分析。无 Cookie、轻量级、独立。免费计划包括/月 3,000 个活动，并提供对我们所有功能的访问，例如仪表板、用户旅程、渠道等。
  * [StatCounter](https://statcounter.com/) - 网站浏览者分析。免费计划分析 500 个最近访问者。
  * [Statsig](https://statsig.com) - 涵盖分析、功能标记和 A/B 测试的一体化平台。/月最多可免费参加 100 万次计量活动。
  * [TraceLog](https://tracelog.io/) - 电子商务人工智能分析。用自然语言询问有关您的分析的问题，获得可行的建议并通过人工智能驱动的见解增加您的收入。/月最多可免费举办 10,000 场活动。
  * [Trackingplan](https://www.trackingplan.com/) - 自动检测数字分析、营销数据和像素问题，维护最新的跟踪计划，并促进无缝协作。将其部署到具有实际流量的生产环境中，或将分析覆盖范围添加到回归测试中，而无需编写代码。
  * [TrackWith Dicloud](https://dicloud.net/trackwith-privacy-focused-analytics/) - 免费、轻量级、注重隐私的 Google Analytics 替代品。无限的页面浏览量、无限的访问者、无限的页面热图和目标跟踪。最多 3 个域免费，每个域可重播 600 次会话。
  * [Umami](https://umami.is/) - 简单、快速、注重隐私、开源的 Google Analytics 替代方案。
  * [usabilityhub.com](https://usabilityhub.com/) - 在真人身上测试设计和模型并跟踪访客。一位用户免费，无限次测试

**[⬆️ 返回顶部](#table-of-contents)**

<a id="visitor-session-recording"></a>
## 访客会话录制

  * [FullStory.com](https://www.fullstory.com) - /月 1,000 个会话，保留一个月的数据和三个用户席位。更多信息[here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition)。
  * [howuku.com](https://howuku.com) - 跟踪用户交互、参与度和事件。/月最多 5,000 次访问免费
  * [inspectlet.com](https://www.inspectlet.com/) - 一个网站/月免费 2,500 次会话
  * [LogRocket.com](https://www.logrocket.com) - /月 1,000 次会话，保留 30 天、错误跟踪、实时模式
  * [Microsoft Clarity](https://clarity.microsoft.com/) - 会话录制完全免费，“无流量限制”、无项目限制、无采样
  * [mouseflow.com](https://mouseflow.com/) - 一个网站/月免费 500 次会话
  * [OpenReplay.com](https://www.openreplay.com) - 使用用于错误重现的开发工具进行开源会话重放、用于实时支持的实时会话以及产品分析套件。/月 1000 次会话，可访问所有功能并保留 7 天。
  * [Reactflow.com](https://www.reactflow.com/) - 每个站点：/天 1,000 页面浏览量、三个热图、三个小部件、免费错误跟踪
  * [smartlook.com](https://www.smartlook.com/) - 适用于网络和移动应用程序的免费软件包(1500 个会话/月)、三张热图、一个漏斗、1 个月的数据历史记录
  * [UXtweak.com](https://www.uxtweak.com/) - 记录并观察访问者如何使用您的网站或应用程序。小型项目免费无限时间

**[⬆️ 返回顶部](#table-of-contents)**

<a id="international-mobile-number-verification-api-and-sdk"></a>
## 国际手机号验证 API 和 SDK

  * [numverify](https://numverify.com/) - 全球电话号码验证和查找 JSON API。/月 100 个 API 请求
  * [veriphone](https://veriphone.io/) - 通过免费、快速、可靠的 JSON API 进行全球电话号码验证。/月 1000 个请求

**[⬆️ 返回顶部](#table-of-contents)**

<a id="payment-and-billing-integration"></a>
## 支付和账单集成

  * [Adapty.io](https://adapty.io/) - 具有开源 SDK 的一站式解决方案，用于将移动应用内订阅集成到 iOS、Android、React Native、Flutter、Unity 或 Web 应用程序。免费获得/月高达 10,000 美元的收入。
  * [AllRatesToday](https://allratestoday.com) - 使用官方 JavaScript、Python 和 PHP SDK 提供 150 多种货币的实时中间市场汇率。免费套餐包括/月 300 个通过 HTTPS 的请求。
  * [Churnkey](https://churnkey.co) - 取消订阅业务的流量(开源)、流失指标和收入分析。永远免费。
  * [CoinMarketCap](https://coinmarketcap.com/api/) - 提供加密货币市场数据，包括最新的加密货币和法定货币汇率。免费套餐/月提供 10K 通话积分。
  * [Currencyapi](https://currencyapi.com) - 免费的货币换算和汇率数据API。/月免费 300 个请求，私人使用每分钟 10 个请求。
  * [CurrencyApi](https://currencyapi.net/) - 实物和加密货币的实时汇率，以 JSON 和 XML 形式提供。免费套餐/月提供 1,250 个 API 请求。
  * [CurrencyFreaks](https://currencyfreaks.com/) - 提供当前和历史货币汇率。免费的开发者计划/月有 1000 个请求。
  * [currencylayer](https://currencylayer.com/) - 为您的企业提供可靠的汇率和货币换算，/月免费 100 个 API 请求。
  * [exchangerate-api.com](https://www.exchangerate-api.com) - 易于使用的货币转换 JSON API。免费套餐/天更新一次，/月限制为 1,500 个请求。
  * [Exchange Rate API](https://exchange-rateapi.com) - 160 多种货币的实时汇率，60 秒更新和官方 SDK。免费套餐包括/月 300 个请求。
  * [FraudLabsPRO](https://www.fraudlabspro.com) - 帮助商家防止付款欺诈和退款。免费微型计划/月可进行 500 次查询。
  * [FxRatesAPI](https://fxratesapi.com) - 提供实时和历史汇率。免费套餐需要归属。
  * [Moesif API Monetization](https://www.moesif.com/) - 通过基于使用情况的计费从 API 中产生收入。连接到 Stripe、Chargebee 等。免费套餐/月提供 30,000 个事件。
  * [ParityVend](https://www.ambeteco.com/ParityVend/) - 根据访客位置自动调整定价，以在全球范围内扩展业务并开拓新市场(购买力平价)。免费计划包括/月 7,500 个 API 请求。
  * [Qonversion](http://qonversion.io/) - 一体化跨平台订阅管理平台，提供分析、A/B 测试、Apple Search Ads、远程配置和用于优化应用内购买和货币化的增长工具。兼容 iOS、Android、React Native、Flutter、Unity、Cordova、Stripe 和 Web。免费获得/月高达 10,000 美元的跟踪收入。
  * [RevenueCat](https://www.revenuecat.com/) - 用于应用内购买和订阅的托管后端(iOS 和 Android)。免费跟踪收入高达 2500 美元/月。
  * [vatlayer](https://vatlayer.com/) - 即时增值税号验证和欧盟增值税税率 API，/月免费 100 个 API 请求

**[⬆️ 返回顶部](#table-of-contents)**

<a id="docker-related"></a>
## Docker 相关

  * [Container Registry Service](https://container-registry.com/) - 基于港口的集装箱管理解决方案。免费套餐为私有存储库提供 1 GB 的存储空间。
  * [Docker Hub](https://hub.docker.com) - 一个免费的私有存储库和无限的公共存储库来构建和存储 Docker 镜像
  * [Play with Docker](https://labs.play-with-docker.com/) - 一个简单、互动、有趣的 Docker 学习平台。
  * [quay.io](https://quay.io/) - 使用无限的免费公共存储库构建和存储容器映像
  * [ttl.sh](https://ttl.sh/) - 匿名和临时 Docker 镜像注册表

**[⬆️ 返回顶部](#table-of-contents)**

<a id="dev-blogging-sites"></a>
## 开发者博客平台

  * [AyeDot](https://ayedot.com/) - 以现代多媒体短格式迷你博客的形式与世界免费分享您的想法、知识和故事。
  * [BearBlog](https://bearblog.dev/) - 极简主义、Markdown 驱动的博客和网站构建器。
  * [Dev.to](https://dev.to/) - 程序员在这里分享想法并帮助彼此成长。
  * [Hashnode](https://hashnode.com/) - 为开发人员提供的无忧博客软件！。
  * [Medium](https://medium.com/) - 更加仔细地考虑对您来说重要的事情。
  * [JustBlogged](https://justblogged.com) - 免费博客平台，具有自定义域支持和快速的全球性能。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="commenting-platforms"></a>
## 评论平台

  * [GraphComment](https://graphcomment.com/) - GraphComment 是一个评论平台，可帮助您从网站的受众中建立一个活跃的社区。
  * [IntenseDebate](https://intensedebate.com/) - 适用于 WordPress、Tumblr、Blogger 和许多其他网站平台的功能丰富的评论系统。
  * [Remarkbox](https://www.remarkbox.com/) - 开源托管评论平台，尽你所能支付“几个域的一位版主，完全控制行为和外观”
  * [Utterances](https://utteranc.es/) - 一个基于 GitHub 问题构建的轻量级评论小部件。使用 GitHub 问题进行博客评论、Wiki 页面等！

**[⬆️ 返回顶部](#table-of-contents)**

<a id="screenshot-apis"></a>
## 截图 API

  * [ApiFlash](https://apiflash.com) - 基于 Aws Lambda 和 Chrome 的屏幕截图 API。处理整页、捕获时间和视口尺寸。
  * [microlink.io](https://microlink.io/) - 它将任何网站转化为元标签标准化、美容链接预览、抓取功能或屏幕截图等数据作为服务。/天 50 个请求免费。
  * [PhantomJsCloud](https://PhantomJsCloud.com) - 浏览器自动化和页面渲染。  免费套餐/天最多提供 500 页。  自 2017 年起免费套餐。
  * [screenshotbase.com](https://screenshotbase.com) - /月 300 张免费屏幕截图。从任何网址截取屏幕截图。快速、免费且可扩展。
  * [screenshotlayer.com](https://screenshotlayer.com/) - 捕获任何网站的高度可定制的快照。/月免费 100 个快照
  * [screenshotmachine.com](https://www.screenshotmachine.com/) - /月捕获 100 个快照，png、gif 和 jpg，包括完整长度的捕获，而不仅仅是主页
  * [Screenshot Scout](https://screenshotscout.com/) - 供开发者使用的屏幕截图 API。来自一个请求中的任何 URL 的干净、可用于生产的屏幕截图。免费计划包括/月 200 张屏幕截图，永久有效。
  * [SnapAPI](https://snapapi.pics) - 屏幕截图、视频录制、PDF 生成和 Web 数据提取 API。免费计划包括/月 200 张屏幕截图。
  * [thumbnail.ws](https://thumbnail.ws) - 用于生成网站缩略图的 API。/月免费 1,000 个请求。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="flutter-related-and-building-ios-apps-without-mac"></a>
## Flutter 相关和无需 Mac 构建 iOS 应用

  * [CodeMagic](https://codemagic.io/) - Codemagic 是一个针对移动应用程序的完全托管和管理的 CI/CD。您可以使用基于 GUI 的 CI/CD 工具来构建、测试和部署。免费套餐提供/月 500 分钟免费时间以及配备 2.3 GHz 和 8 GB RAM 的 Mac Mini 实例。
  * [FlutLab](https://flutlab.io/) - FlutLab 是一个现代 Flutter 在线 IDE，也是创建、调试和构建跨平台项目的最佳场所。使用 Flutter 构建 iOS(无需 Mac)和 Android 应用程序。
  * [FlutterFlow](https://flutterflow.io/) -  FlutterFlow 是一个基于浏览器的拖放界面，用于使用 flutter 构建移动应用程序。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="privacy-management"></a>
## 隐私管理

  * [Bearer](https://www.bearer.sh/) - 通过审计和连续工作流程帮助实施隐私设计，以便组织遵守 GDPR 和其他法规。免费套餐仅限于较小的团队和 SaaS 版本。
  * [Concord](https://www.concord.tech/) - 完整的数据隐私平台，包括同意管理、隐私请求处理 (DSAR) 和数据映射。免费套餐包括核心同意管理功能，它们还免费为经过验证的开源项目提供更高级的计划。
  * [Cookiefirst](https://cookiefirst.com/) - Cookie 横幅、审核和多语言同意管理解决方案。免费套餐提供一次性扫描和单个横幅。
  * [Iubenda](https://www.iubenda.com/) - 隐私和 cookie 政策以及同意管理。免费套餐提供有限的隐私和 Cookie 政策以及 Cookie 横幅。
  * [Ketch](https://www.ketch.com/) - 同意管理和隐私框架工具。免费套餐提供大多数功能，但访问者数量有限。

**[⬆️ 返回顶部](#table-of-contents)**

<a id="miscellaneous"></a>
## 杂项

  * [BinShare.net](https://binshare.net) - 创建和共享代码或二进制文件。可作为美丽的图像进行分享，例如用于 Twitter / Facebook 帖子或作为链接，例如用于聊天或论坛。
  * [Blynk](https://blynk.io) - 具有 API 的 SaaS，用于控制、构建和评估 IoT 设备。免费开发者计划，包含 5 台设备、免费云和数据存储。还提供移动应用程序。
  * [cron-job.org](https://cron-job.org) - 在线定时任务服务。无限的工作是免费的。
  * [Cronhooks](https://cronhooks.io/) - 安排准时或重复的网络钩子。免费计划允许 5 个临时时间表。
  * [datelist.io](https://datelist.io) - 在线预订/预约安排系统。/月最多免费 5 次预订，包括 1 份日历
  * [FOSSA](https://fossa.com/) - 针对第三方代码、许可证合规性和漏洞的可扩展的端到端管理。
  * [Hook Relay](https://www.hookrelay.dev/) - 为您的应用程序添加 Webhook 支持，无需任何麻烦：为您完成的排队、退避重试和日志记录。免费计划/天有 100 次交付、14 天保留和 3 个挂钩端点。
  * [Hosting Checker](https://hostingchecker.co) - 检查任何域名、网站或 IP 地址的托管信息，例如 ASN、ISP、位置等。还包括多个托管和 DNS 相关工具。
  * [newreleases.io](https://newreleases.io/) - 接收来自 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet、Rust Cargo 和 Docker Hub 的新版本的电子邮件、Slack、Telegram、Discord 和自定义 Webhooks 通知。
  * [PDFMonkey](https://www.pdfmonkey.io/) - 在仪表板中管理 PDF 模板，使用动态数据调用 API，然后下载 PDF。/月提供 300 个免费文档。
  * [Pika Code Screenshots](https://pika.style/templates/code-image) - 使用扩展从代码片段和 VSCode 创建漂亮的、可自定义的屏幕截图。
  * [QuickType.io](https://quicktype.io/) - 从 JSON、模式和 GraphQL 快速自动生成模型/类/类型/接口和序列化器，以便使用任何编程语言快速、安全地处理数据。将 JSON 转换为任何语言的华丽、类型安全的代码。
  * [readme.com](https://readme.com/) - 精美的文档变得简单，免费开源。
  * [redirect.pizza](https://redirect.pizza/) - 通过 HTTPS 支持轻松管理重定向。免费计划包括 10 个来源和/月 100,000 次点击。
  * [redirection.io](https://redirection.io/) - 用于管理企业、营销和 SEO 的 HTTP 重定向的 SaaS 工具。
  * [redirs.com](https://www.redirs.com/)— 通过自动 SSL、分析和 URL 路径转发轻松进行域重定向。免费基本使用(最多 5 个域)。
  * [RedirHub](https://www.redirhub.com/) - API 优先的 URL 重定向基础设施，具有自定义名称服务器、边缘网络、HTTPS 和主动链接监控。免费计划包括 2 个主机名、/月 100K 请求、自动 SSL、路径转发和 REST API 访问。
  * [ReqBin](https://reqbin.com/) - 在线发布 HTTP 请求。流行的请求方法包括 GET、POST、PUT、DELETE 和 HEAD。支持标头和令牌身份验证。包括用于保存您的请求的基本登录系统。
  * [Smartcar API](https://smartcar.com) - 用于汽车定位、获取油箱、电池电量、里程表、开/锁车门等的 API。
  * [Sunrise and Sunset](https://sunrisesunset.io/api/) - 获取给定经度和纬度的日出和日落时间。
  * [superfeedr.com](https://superfeedr.com/) - 符合 PubSubHubbub 标准的实时源、导出、分析。免费，定制较少
  * [SurveyMonkey.com](https://www.surveymonkey.com) - 创建在线调查。在线分析结果。免费计划每项调查仅允许 10 个问题和 100 个答复。
  * [SYNCDATE](https://syncdate.app) - 双向 Google 日历同步。免费套餐：2 个帐户，无限次活动。
  * [UUID Generator](https://newuuid.com/) - 立即生成企业级 UUID v1、UUID v4、UUID v7、GUID、Nil UUID、CUID v1/v2、NanoID 和 ULID
  * [Versionfeeds](https://versionfeeds.com) - 用于发布您喜爱的软件的自定义 RSS 源。将您的编程语言、库或喜爱的工具的最新版本集中在一个源中。 (前3次免费)

**[⬆️ 返回顶部](#table-of-contents)**

<a id="remote-desktop-tools"></a>
## 远程桌面工具

  * [AnyDesk](https://anydesk.com) -  3台设备免费，会话次数和持续时间没有限制
  * [Getscreen.me](https://getscreen.me) -  2 台设备免费，会话次数和持续时间没有限制
  * [RemSupp](https://remsupp.com) - 按需支持和永久访问设备(免费/天 2 次会议)
  * [RustDesk](https://rustdesk.com/) - 适合所有人的开源虚拟/远程桌面基础设施！

**[⬆️ 返回顶部](#table-of-contents)**

<a id="other-free-resources"></a>
## 其他免费资源

  * [get.localhost.direct](https://get.localhost.direct) - 更好的`*.localhost.direct`通配符公共 CA 签名 SSL 证书，用于具有子域支持的本地主机开发
  * [GitHub Education](https://education.github.com/pack) - 为学生收集免费服务。需要注册。
  * [Glob tester](https://globster.xyz/) - 一个允许您设计和测试全局模式的网站。它还提供了学习全局模式的资源。
  * [Killer Coda](https://killercoda.com/) -  浏览器中的交互式游乐场，用于学习 Linux、Kubernetes、容器、编程、DevOps、网络
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program) - 获取为 Microsoft 365 平台构建解决方案所需的免费沙箱、工具和其他资源。订阅期限为 90 天[Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5)(Windows 除外)，可续订。如果您积极参与开发(使用遥测数据和算法进行测量)，则会更新它。
  * [MySQL Visual Explain](https://mysqlexplain.com) - 易于理解且免费的 MySQL EXPLAIN 输出可视化工具可优化慢速查询。
  * [RedHat for Developers](https://developers.redhat.com) - 免费使用专供开发者使用的红帽产品，包括 RHEL、OpenShift、CodeReady 等。仅限个人计划。还提供免费电子书供参考。
  * [sandbox.httpsms.com](https://sandbox.httpsms.com) - 免费发送和接收测试短信。
  * [SimpleBackups.com](https://simplebackups.com/) - 针对直接存储到云存储提供商(AWS、DigitalOcean 和 Backblaze)的服务器和数据库(MySQL、PostgreSQL、MongoDB)的备份自动化服务。提供 1 次备份的免费计划。
  * [SimpleRestore](https://simplerestore.io) - 轻松恢复 MySQL 备份。将 MySQL 备份恢复到任何远程数据库，无需代码或服务器。
  * [SnapShooter](https://snapshooter.com/) - 适用于 DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的备份解决方案，支持将数据库、文件系统和应用程序直接备份到基于 s3 的存储。提供免费计划，其中包含一项资源的每日备份。

**[⬆️ 返回顶部](#table-of-contents)**

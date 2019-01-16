

## Outliers' niche 另类生境 2019-1-16 第28期

#### X-Order 通证分析甜甜圈🍩 出品~😁😆😝 
定位 （每日5min)  ：outliers 的**playground**：站住并Buildl！🏄 


### 0.链上数据会说话

| btc | 数据 | 趋势|
|---:|:--:|:--|
| [Hashrate](https://www.blockchain.com/charts/hash-rate)| 3861 万 TH/s| 持平|
| [挖矿收入](https://www.blockchain.com/charts/miners-revenue) | 611 万美元 | 下降|
| [总转账费用](https://www.blockchain.com/charts/transaction-fees) | 21 BTC | 上升|
| [未确认交易数](https://www.blockchain.com/zh-cn/btc/unconfirmed-transactions) | 3.5 千笔 |下降|


|ETH | 数据 | 趋势|
|--:|:--:|:--:|
|[Hashrate](https://etherscan.io/chart/hashrate)| 189TH/s| 持平|
|[转账笔数](https://etherscan.io/chart/tx)|54万|上升|
|[总转账费用](https://etherscan.io/chart/transactionfee)| 423 eth| 上升|
|[未确认交易数](https://etherscan.io/chart/pendingtx)| 3.7万 | 上升|
|[gas 中位数](https://ethgasstation.info/)| 10 gwei | 持平 |
|[gas 费用(5分钟内可确认)](https://ethgasstation.info/)| 5.1 gwei | 下降|





### 1.核心项目进展
#### ETH: 聚集升级
- **Pin** [安全警告！Constantinople 升级推迟](https://blog.ethereum.org/2019/01/15/security-alert-ethereum-constantinople-postponement/), ETH的升级遇到了问题，为了方便小伙伴仔细阅读，这里有[中文翻译公告](https://ethfans.org/posts/security-alert-ethereum-constantinople-postponement), 甜甜圈感谢以太坊爱好者的连夜翻译。这次的问题根源在于ChainSecurity发现的EIP-1283的[可重入攻击的疑点](https://medium.com/chainsecurity/constantinople-enables-new-reentrancy-attack-ace4088297d9), 被[Mhswende](https://twitter.com/mhswende/)郑重提出，基金会经过理解讨论发现这个问题的严重性然后决定推迟。

**甜甜圈评论** 甜甜圈看到这个消息后的第一反应后是失望，但是当省视了以太坊社区处理这件事情的方式后，为以太坊社区点赞。社区第一时间把处理的全部过程回放给社区成员，没有任何隐瞒，同时一起积极思考应对方案。包括EvanVanNess、Infura、MyCrypto、Parity、Status、以太坊基金会和 Ethereum Cat Herders 在内的社区成员共同参与者这个决定性的决策过程。甜甜圈为以太坊社区点赞👍

- **升级！立即回复！！** ，已经有47%的以太坊客户端陆续升级: 甜甜圈🍩提醒赶紧回复！！
	- [Geth 客户端回复版](https://github.com/ethereum/go-ethereum/releases/tag/v1.8.21): 维护者 Péter Szilágyi，在5小时前发布了回复版 Byzantium Revert (v1.8.21)
	- [Parity 客户端回复版](https://github.com/paritytech/parity-ethereum/releases/): 维护者 [Afri Schoedon](https://twitter.com/5chdn), 完成客户端回复，更新了两版本，2.2.7 stable 和 2.3.0 beta
	- [EthereumJ Harmony 客户端回复版](https://github.com/ether-camp/ethereum-harmony/releases/tag/v2.3b73): 这是以太坊 Java客户端，维护者zilm13提供了v2.3b73版本的恢复版。
	- [Pantheon 客户端回复版](https://github.com/PegaSysEng/pantheon/releases/tag/0.8.5)：这是ConsenSys企业项目PegaSys的Java 客户端，维护者[Lucas Saldanha](https://www.lucassaldanha.com/), 回复版本为0.8.5
	- [Trinity 客户端](https://github.com/ethereum/py-evm/releases/): 这是以太坊python客户端。维护者[Jason Carver](https://twitter.com/jasoncarver)，还未更新回复版~
	- [Mist 客户端最新版](https://github.com/ethereum/mist/releases/tag/v0.11.1): 这是著名的Mist，Mist维护者是 [Ev](https://twitter.com/evertonfraga), 目前版本是2018年7月发布后一直没有更新~ 
	- [Metamask](https://twitter.com/metamask_io/status/1084126800634994688): Metamask 需要升级吗？需要做什么吗？不需要！ 

- 升级带来的改变：
	- `EIP145`，提案人Alex Beregszaszi 和 Pawel Bylica，一种更有效的以太坊信息处理方案(逐位移动),让智能合约消耗更少的gas;
	- `EIP1052`，提案人以太坊core开发人员Nick Johnson和Bylica，使得智能合约间的验证更容易,优化以太坊网络大规模代码执行;
	- `EIP1014`,提案人Vitalik，增加了状态通道在ETH上;
	- `EIP1234`，The Thirdening, 提案人Parity的Afri Schoedon，使以太坊网络的区块奖励从3ETH减少到2ETH，此外还会延迟难度炸弹12个月的时间，使得ETH从`POW`平稳过渡到`POS`，这里有ConsenSys刚刚做的[视频解释](https://www.youtube.com/watch?v=-k2oktHQ7cs&feature=youtu.be);
	- `EIP1283`提案日Johnson，引入了一种针对数据存储更改更公平的定价方法。

- [以太坊硬分叉进程](https://ethereum-magicians.org/t/eep-5-ethereum-hardfork-process-request-for-collaboration/2305): 由于社区驱动，任何人都可以驱动以太坊向着更好的方向发展，这个EEP-5就是期望能够对以太坊硬分叉进行持续跟踪，这里列举了以太坊的议事流程和硬分叉会发生的一系列事情的关键阶段：
	- 2019-01-16: Constantinople主链硬分叉（**推迟**）
	- 2019-05-17: 是否接受“Istanbul”的最后期限
	- 2019-07-19: 主要客户端升级的期限
	- 2019-08-14: Ropsten, Görli 测试链硬分叉
	- 2019-10-16: Instanbul 主链硬分叉

- [工具: Amberdata](https://amberdata.io/dashboards/infrastructure):Amberdata第一时间回应的以太坊推迟升级,同时提供了实时的监控网络的预警服务。如果仔细看Amberdata所提供的链上监控功能和ETH项目监控功能，会发现这是一款[监控以太坊项目变化](https://amberdata.io/dashboards/applications)的神器！


- [EIP1700: Non-Exhaustible Token](https://github.com/ethereum/EIPs/issues/1700): 这个提案创造了一种可以无限发布copy的通证池子，称为`NET`,由于Tron的智能合约和Solidity的通用性，这个项目首先是在Tron上部署并发布的。但同时我们可以看到Tron上缺少EIP这样对于规范的讨论，所以提案者[李婷婷](https://github.com/tina1998612)就在这里提出了，虽然甜甜圈感觉有些推广的成分。😄移步Dapp跟踪可以获得这个项目更多的介绍。

- [产业合作: 发布Newspack with WorkPress.com](https://en.blog.wordpress.com/2019/01/14/newspack-by-wordpress-com/): ConsenSys 最近连续和多家产业巨头达成合作，这次的主角是WorkPress，这个[Newspack](https://newspack.blog/)作为workpress的子公司，期望打造一个开源的，用户产生价值的新闻平台。这个项目将在2019年7月正式发布beta版本，在2月1日前可以开放申请。

#### EOS：聚焦公投2.0

- **公投2.0**：这是甜甜圈取的名字😄，EOS社区目前推进这一项[EOS BallotCraft Working Group](https://medium.com/@espin.brand/eos-ballotcraft-guide-published-5eddab9d8cf3)计划，为了自组织管理，我们需要一个很有效的提案和协商系统。这个计划就是为了创造一种流程，能够使得自组织决议变得容易。🍩期待~ 

- [EOS Canada 对于EOS Referendum Contract 答疑](https://www.eoscanada.com/en/answers-to-every-question-you-have-about-the-eos-referendum-contract): EOS Canada 是[EOSIO.forum](https://github.com/eoscanada/eosio.forum) 的发起者，目前合约已经被部署，终于众人可以发言了，那么如何做呢？这里为你答疑解惑，特别注意的是Vote无需使用EOS，不过会消耗一定的RAM。同时投票是需要stake EOS的，但是投票可以随时转变对象，是一个24小时的不间断投票的过程，同时也可以选择代理人代表自己投票。至于更多，直接访问原文吧！


- [EOS 公投提案分析](https://eosauthority.com/polls_details?proposal=decaf_20190111&lnc=en): 这个提案非常🔥，针对的是EOS仲裁委员会(ECAF)的绝对权力的限制。甜甜圈之前就提过ECAF的集权管理和反应速率太慢，同时ECAF有一个发布`key switching order`的权利，这个权利是一个至高权利，但是超级节点特别不公平，现在希望废除ECAF的这一权利，目前投票的赞同率很高，甜甜圈🍩发现EOS社区这个公投非常认真😄。期望小伙伴多多探索~
 


### 2.热锅上的项目🔥 
- **Pin**:[Grin正式上主链！！💐](https://grin-tech.org/)&[Beam](https://www.beam.mw/): 利用mimblewimble共识机制的两个兄弟项目。经过一番调试，Grin第一个区块已于北京时间00:01被鱼池挖出。**特别提醒Beam已经在北京时间1月3日主网上线，Grin也在1月15日主网上线**
	- [数据说话](https://grinmint.com/pages/index.html)：用户: 1277; 矿工 3479; Hashrate: 波动剧烈( Primary 52, Secondary 44519 G/s)  
		- 出块情况查询：[grinscan](http://grinscan.net)，[grinmint](https://grinmint.com/)
	- **Curated list**，帮助大家更好的认识Grin、Beam这个项目: 
	- [Grin vs. BEAM, a Comparison](https://tlu.tarilabs.com/protocols/grin-beam-comparison/MainReport.html)
	- [通证通研究院：Grin 深度报告](https://www.chainnews.com/articles/182565597152.htm)
	- [Grin up 周报更新](https://grinnews.substack.com/)
	- [Tokengazer: Grin挖矿设备投资收益分析报告](http://www.tokengazer.com/#/reportDetail?id=64)
	- [让人兴奋的 Grin 如何走到今天？谁在背后推动它？](https://mp.weixin.qq.com/s/1OCmswCxaoo-2BHGEU5KrQ)

- [RIF](https://www.rsk.co/): 比特币智能合约项目Rootstack是一个2016年就有的很古老的项目，一直非常火热🔥，但是至今未有通证销售，昨天，[Rootstack的功能通证RIF上了Bitfinex交易所](https://medium.com/bitfinex/bitfinex-introduces-trading-for-rsk-infrastructure-framework-2682f7df54a2),再一次引起了众人的关注。这个项目的理念其实和qtum有些接近，但是更务实，就是通过btc算力网络来支持底层共识，构筑侧链上搭建智能合约来承载应用，同时使用RIF来收取使用费用。这个逻辑是可行的。同时我们也看到github仓库很多子项目中都是对于ETH社区项目的fork，包括这个[RSKIPs](https://github.com/rsksmart/RSKIPs/issues)，可是没有任何讨论。**甜甜圈评论** 甜甜圈赞同Vitalik的观点：建立Social consensus比建立挖矿共识更难，但是一旦建立起来，就会有强而有力的凝聚力。


### 3.Dapp跟踪:

#### 游戏：
- [密码女孩](https://tronbeauty.github.io/CryptoBeauty/#/): 这是一款创造区块链模特的卡牌类游戏，不过特别之处在于所创造的通证并非仅仅NFT，而是被称为NET的Token，使得对于任何通证，都可以创造出更多的功能，使得这个通证更具备虚拟资产的多属性。这个游戏特别有趣的地方是直接链接的区块链模特是真人facebook、instagram等社交媒介的链接，同时获得这个卡牌将有获得谈话、私人见面会等权利。很像是一个新的明星培养平台😄


### 4.近期深度文章
- **Pin一周** [为 2019 年的密码世界划重点](https://mp.weixin.qq.com/s/300o6WLxB5kUVFBM9w238g): 作者对区块链2019年的**十大预测**，涵盖63个点：比特币6项、以太坊8项、其他项目13项、一级市场项目5项、稳定币4项、区块链基金4项、区块链产品5项、区块链公司13项、政策监管5项。
- [杀死公司：坚持不融资不上市的Valve，是如何颠覆企业组织架构的？](https://orange.xyz/p/305) 和[是时候淘汰“公司”了：从“命令控制”模式转向人人可参与创造的网络模式](https://orange.xyz/p/300): 两篇分析V社的文章，讨论了该公司内部独特的结构，类似于市场经济基于追求盈利的自发秩序，员工们自由组织自己的时间所形成的新秩序。是一个很好的案例。



通证甜甜圈🍩, XOrder.ai 欢迎多提宝贵意见! [邮件](qchen@xorder.ai)

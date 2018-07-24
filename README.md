# EOS-Knowledge-Center

**EOS.IO**

 是由block.one开发的一个基于区块链结构设计的能够支持水平和垂直扩展的去中心化应用的平台。它就像是一个完整的操作系统，可以在上面构建各种应用。EOS.IO提供了账户、认证、数据库，异步通信以及跨平台跨集群的定时应用。它有望支持每秒百万级交易，完全零费率，并可以快速且容易地部署去中心化应用。


**EOS术语解释**

Account，账户

Authority，权力

Block，缩写Blk，每个区块可包含0个或多个交易，以及一个对前置区块的加密连接。不可逆。

DAC，分权自治集体，或者是分权自治公司。

DAO，分权自治组织

Deferred Transaction，缩写defTx，延期交易。该交易是有智能合约所创建，会在未来的某个时间被执行。这个交易也能够创建另一个在其之后的交易。因此，延期交易可以创建无限循环的顺序交易。用户授权一个延期交易必须指定到执行的时刻拥有足够的带宽，存储来执行预期交易。

DLTs，分布式账本技术。一种分布式账本（也被称作共享式账本），它是一个基于复制、共享以及同步数字化资产的跨站点、跨国家、跨机构的共识。

DPoS，授权权益证明。此外，也可以代表民主即权益证明。DPoS是共识算法的一种，即区块生产者能够针对交易或区块的真实性，可验证，不可逆等特性达成共识的一种方法。

Key pair，缩写keys，一个密钥对，包括公钥和其对应的私钥。

larimer，一种EOS的计量单位，等于0.0001 EOS。（性质如同以太坊中的Wei）

Master Password，用于解锁，或解密一个钱包文件的密码。

Action，一个对区块链的改变动作。可以是一个或这多个动作组成一个交易。

Non-Producing Node，非生产节点，也可以被理解为普通节点。这是一个完整的区块链节点，但它智能观察和验证区块，以及只能维护自己本地区块链的拷贝。一个普通节点可以在一个“备用池”中，通过投票流程称为生产节点（具备出块权的超级节点）一个超级节点，也会被投票出局，成为一个普通节点。但是值得注意的是，大多数普通节点并不在“备用池”中。

Oracle，在区块链和智能合约的上下文中，它是一个代理，被智能合约使用用来找到和验证实际发生的并提交这个信息到区块链上。

peer-to-peer,p2p，对等计算或网络是一个分布式应用程序架构，在对等环境下，它被分去为任务或者是工作量。对等节点是拥有等价权限，在应用程序中的参与机会均等。他们组成了点对点的网络节点。

Permission，加权的，安全机制，通过评估它的签名权力来确定一个信息是否被正确授权。

Private Key，用来签名交易的私钥。

Public Key，缩写pub key，公钥，会在交易间被传输。

Scope，作用域，智能合约的作用域，智能合约智能写入他们同一个作用域的自己的其他合约，而只能够读取其他作用域的合约。

Smart Contract, 智能合约，一个计算机协议，旨在促进、验证或执行谈判。

Standby Pool，100个全节点的集合，渴望被选中为21个超级节点之一，他们实际上已经拥有了超级节点的能力，无论何时链需要替换一个超级节点时，就会从备用池中选择。

Transaction，缩写Tx，Txn。它有事务的含义，一般我们称作交易。它是一个完整的原子的区块链的变化，一个或多个消息的组合，在EOS中通常是由一个智能合约来执行。

Wallet，钱包，会生成一个加密钱包文件或是通过客户端来管理，例如cleos。它管理了私钥以及用一个安全的方式去促进交易的签名。钱包可以被锁定或解锁。

Block Producer, 缩写bp。21个超级节点之一，是目前正在出块轮次的那个超级节点。



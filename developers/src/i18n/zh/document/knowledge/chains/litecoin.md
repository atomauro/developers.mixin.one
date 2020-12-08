# 莱特币（Litecoin）

莱特币（Litecoin）分叉自[比特币](./bitcoin)，被称为比特币的测试网。

### 基本信息

- 主网上线：2011/10/08
- 共识机制：PoW
- 主网代币：Litecoin（LTC）
- 最大发行：84,000,000 LTC
- 减半周期：约 4 年（84 万个区块）
- 出块时间：150 秒
- 区块大小：1M
- 区块奖励：12.5 LTC
- 区块数据：31.19 GB（截止到 2020/12/02）
- 交易数据：5 千万（截止到 2020/12/02）
- 最小单位：0.00000001（1 Litoshi）

### 核心概念

- Scrypt 算法

  Scrypt 是内存依赖型的 PoW 算法，对 ASIC 矿机具有较好的抵抗性，一般个人电脑也能进行挖矿，只要内存大，促使更多的普通矿工参与挖矿记账，促进了网络更加去中心化。

- 隔离见证（Segregated Witness）

  隔离见证由比特币核心开发人员于 2015 年提出，目的是解决比特币存在的安全漏洞（延展攻击）和其扩容问题，该技术被首先应用在莱特币上并被成功激活（早比特币 3 个月）。

  隔离见证是指从交易相关数据中分离见证签名。"传统比特币区块"中的见证签名通常占用区块大小的 50％ 以上，通过从交易块中删除见证人签名，可以有效增加单个块中的交易数量，从而提升了网络处理交易的能力，同时降低了交易费用。

- 闪电网络
  
  闪电网络是一个链下服务方案，主要是为了解决小额支付问题，使得商家和客户能够快速并且低成本的进行支付，目前闪电网络已于 2017 年 11 月成功部署。

### 地址

- 普通地址

  以 `L` 开头的 P2PKH 地址，Base58 编码大小写字母 + 数字混合，例如 `LhyLNfBkoKshT7R8Pce6vkB9T2cP2o84hx`。

- 多签地址

  以 `M` 开头的 P2SH 新地址，Base58 编码大小写字母 + 数字混合，例如 `MR5Hu9zXPX3o9QuYNJGft1VMpRP418QDfW`。

- 隔离见证地址

  原生隔离见证地址以 `ltc` 开头的，bech32 编码全大小或全小写字母 + 数字（大小写不能混着写），例如 `ltc1qum864wd9nwsc0u9ytkctz6wzrw6g7zdn08yddf`。

### 入账参考

| 交易所 & 钱包 | 入账区块确认数 | 预计时间 |
| :-----: | :----: | :---- |
| Coinbase | 12 | 30 分钟 |
| 币安 | 4 | 10 分钟 |
| 火币 | 3 | 7.5 分钟 |
| OKEx | 1 | 2.5 分钟 |
# 打卡web3学习计划
## 第一天 区块链基础知识

[什么是区块链] <br>
- 去中心化：将控制权和决策权从中心化实体（其中的个人、组织或团体）转让给分布式网络。去中心化网络致力于降低参与者必须相互信任的程度，并阻止他们以降低网络功能的方式对彼此施加权威或控制。<br>
- 共识：https://ethereum.org/zh/developers/docs/consensus-mechanisms/<br>
- - POW 工作量证明<br>
- - POS 权益证明<br>

[密码学基础]
- 对称加密
- 非对称加密
- - 公钥
- - 私钥

[web3]
- 
[智能合约]
-
[自动托管钱包Metamask]
-
[数字签名]
[发生交易]
-
[gas费用-手术费]
## 第二天 solidity 基础语法

## 第三天 Fundme
Wei Kwei  Mwei   Gwei  Twei    Pwei(Finney) Ether
1   10**3 10**6 10**9 10**12  10**15       10**18
收款函数需要关键字 payable 如
``` solidity
    function fund () external payable {}
```
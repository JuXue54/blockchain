# blockchain

## bitcoin

- 创建了无需信任中心的货币发行机制；
- 发行数量由程序决定，无法随意修改；
- 交易账本完全公开可追溯，不可篡改；
- 密码学理论保证货币防伪造，防双花；
- 数字签名机制保证交易完整可信，不可抵赖和撤销。

## hash算法

+ hash256/dhash: SHA-256+SHA-256
+ hash160: SHA-256+RipeMD160

## 区块链不可篡改特性

### merkle hash

merkle hash记录了本区块所有的merkle hash

![](img/merklehash.png)

计算方式: 两个计算hash之后相加

![](img/merkle.png)

### block hash

区块头部的prev hash记录了上一个区块的block hash

![](img/blockhash.png)

## packet

钱包软件是用来帮组用户管理私钥的

## public key and private key

![](img/keys.jpg)
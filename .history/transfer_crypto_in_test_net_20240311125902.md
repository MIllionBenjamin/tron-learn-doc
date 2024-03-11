# 在测试网转账

- [在测试网转账](#在测试网转账)
  - [1. 用MetaMask在以太坊测试网转账](#1-用metamask在以太坊测试网转账)
    - [1.1 安装并初始化MetaMask应用](#11-安装并初始化metamask应用)
    - [1.2 获取Sepolia ETH（以太坊测试网代币）](#12-获取sepolia-eth以太坊测试网代币)
    - [1.3 将Sepolia ETH转给他人](#13-将sepolia-eth转给他人)


## 1. 用MetaMask在以太坊测试网转账

### 1.1 安装并初始化MetaMask应用

打开Chrome，访问[MetaMask的Chrome应用商店页面](https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=zh-CN&utm_source=ext_sidebar)，点击安装。

安装完成后，在Chrome中打开MetaMask应用。

![open_metamask.png](./image/open_metamask.png)

初次打开MetaMask，会进入MetaMask的初始化页面，按页面指示完成初始化。过程包括创建密码，并可选择生成账户恢复助记词。请务必保密自己的助记词。


### 1.2 获取Sepolia ETH（以太坊测试网代币）

访问[Alchemy Sepolia ETH"水龙头"网址](https://www.alchemy.com/faucets/ethereum-sepolia)。

点击右上角`Alchemy Login`登录账户。


打开MetaMask，点击左上角按钮，打开`Show Test Networks`选项，切换至Sepolia测试网。

![select_sepolia_in_metamask.png](./image/select_sepolia_in_metamask.png)


复制自己的钱包地址。


![alt text](image.png)

粘贴钱包地址至[Alchemy Sepolia ETH"水龙头"](https://www.alchemy.com/faucets/ethereum-sepolia)，点击`Send Me ETH`。然后下方`Your Transaction`栏目会出现一条交易记录。


![alt text](image-1.png)

此时打开MetaMask钱包，会发现0.5 SepoliaETH已到账。

![alt text](image-2.png)


### 1.3 将Sepolia ETH转给他人

打开MetaMask钱包，确保处于Sepolia测试网。点击`Send`按钮。

![alt text](image-3.png)

输入他人账户地址，以及代币数量。然后点击Next。


![alt text](image-5.png)

确认转账详情后，点击Confirm发起转账。

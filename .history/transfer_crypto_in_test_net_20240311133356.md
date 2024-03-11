# 在测试网转账

- [在测试网转账](#在测试网转账)
  - [1. 用MetaMask在以太坊测试网转账](#1-用metamask在以太坊测试网转账)
    - [1.1 安装并初始化MetaMask](#11-安装并初始化metamask)
    - [1.2 获取Sepolia ETH（以太坊测试网代币）](#12-获取sepolia-eth以太坊测试网代币)
    - [1.3 将Sepolia ETH转给他人](#13-将sepolia-eth转给他人)
  - [2. 用TronLink在Tron测试网转账](#2-用tronlink在tron测试网转账)
    - [2.1 安装并初始化TronLink](#21-安装并初始化tronlink)
    - [2.2 获取Tron Nile Testnet Coins](#22-获取tron-nile-testnet-coins)
    - [2.3 将Tron测试币转给他人](#23-将tron测试币转给他人)


## 1. 用MetaMask在以太坊测试网转账

### 1.1 安装并初始化MetaMask

打开Chrome，访问[MetaMask的Chrome应用商店页面](https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=zh-CN&utm_source=ext_sidebar)，点击添加至Chrome。

安装完成后，在Chrome中打开MetaMask应用。

![open_metamask.png](./image/open_metamask.png)

初次打开MetaMask，会进入MetaMask的初始化页面，按页面指示完成初始化。过程包括创建密码，并可选择生成账户恢复助记词。请务必保密自己的助记词。


### 1.2 获取Sepolia ETH（以太坊测试网代币）

访问[Alchemy Sepolia ETH"水龙头"网址](https://www.alchemy.com/faucets/ethereum-sepolia)。

点击右上角`Alchemy Login`登录账户。


打开MetaMask，点击左上角按钮，打开`Show Test Networks`选项，切换至Sepolia测试网。

![select_sepolia_in_metamask.png](./image/select_sepolia_in_metamask.png)


复制自己的钱包地址。


![copy_self_addr.png](./image/copy_self_addr.png)

粘贴钱包地址至[Alchemy Sepolia ETH"水龙头"](https://www.alchemy.com/faucets/ethereum-sepolia)，点击`Send Me ETH`。然后下方`Your Transaction`栏目会出现一条交易记录。


![click_send_me_eth.png](./image/click_send_me_eth.png)

此时打开MetaMask钱包，会发现0.5 SepoliaETH已到账。

![eth_request_success.png](./image/eth_request_success.png)


### 1.3 将Sepolia ETH转给他人

打开MetaMask钱包，确保处于Sepolia测试网。点击`Send`按钮。

![click_send_button.png](./image/click_send_button.png)

输入他人账户地址，以及代币数量。然后点击Next。


![init_transfer.png](./image/init_transfer.png)

确认转账详情后，点击Confirm发起转账，等待交易完成。

![transfer_done.png](./image/transfer_done.png)


## 2. 用TronLink在Tron测试网转账


### 2.1 安装并初始化TronLink

打开Chrome，访问[TronLink的Chrome应用商店页面](https://chromewebstore.google.com/detail/tronlink/ibnejdfjmmkpcnlpebklmnkoeoihofec?hl=zh-CN&utm_source=ext_sidebar)，点击添加至Chrome。


安装完成后，在Chrome中打开TronLink应用，点击`Create Wallet`。

同样，初始化（创建钱包）过程包括创建密码和助记词。

### 2.2 获取Tron Nile Testnet Coins 

复制TronLink的Tron钱包地址。主网和测试网的钱包地址是一样的。

![alt text](image.png)

访问[Nile测试网获取代币网址](https://nileex.io/join/getJoinPage)，粘贴Tron钱包地址，并点击`Obtain`。无误后会弹窗提示获取成功。

![alt text](image-1.png)

在TronLink中将钱包切至Nile测试网，发现2000代币已到账。

![alt text](image-2.png)



### 2.3 将Tron测试币转给他人

点击钱包`Send`按钮，然后输入他人钱包地址。点击`Next`，输入转账数额。

![alt text](image-3.png)


![alt text](image-4.png)


然后点击`Send`，确认转账详情，点击`Sign`签署交易。

![alt text](image-5.png)


片刻后可在钱包首页点击币种查看交易记录。

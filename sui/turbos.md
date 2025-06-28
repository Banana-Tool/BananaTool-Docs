---
description: 在Turbos上创建CLMM资金池
icon: dumpster
---

# Turbos创建CLMM流动性资金池教程

[Turbos Finance](https://turbos.finance/) 是第一个建立在 Sui 上的去中心化零滑点永续合约交易和现货交易平台，由 Sui（Turbos）驱动的去中心化永续交易平台，交易效率更快、手续费更低、清算风险更低。

Turbos提供具有集中流动性做市商(CLMM) 模型和衍生品交易功能的自动做市商(AMM) 去中心化交易所，主打一个用户友好。

<figure><img src="../.gitbook/assets/image (405).png" alt=""><figcaption><p>turbos</p></figcaption></figure>

{% hint style="info" %}
注意：本文仅作为教学演示，所涉及到的资金池和代币均**没有任何实际价值**，大家也不要进行任何形式的交易。如果因此造成资金损失，PandaTool无法对此负责
{% endhint %}

## **一、创建CLMM资金池**

和[Cetus](https://docs.bananatool.com/sui/cetus)类似，在Turbos上也只能创建CLMM资金池，无法创建AMM资金池。

### **1、连接钱包** <a href="#id-1-lian-jie-qian-bao" id="id-1-lian-jie-qian-bao"></a>

连接钱包是所有操作的第一步，老手可以直接忽略。我们打开Turbos的官网：[https://app.turbos.finance/](https://app.turbos.finance/)，点击右上角Connect Wallet按钮，进行钱包连接

<figure><img src="../.gitbook/assets/image (406).png" alt=""><figcaption><p>link wallet</p></figcaption></figure>

在弹出的钱包选项中，PandaTool推荐大家选择[Suiet钱包](https://docs.bananatool.com/sui/suiet)

<figure><img src="../.gitbook/assets/image (407).png" alt=""><figcaption></figcaption></figure>

和所有的DAPP一样，连接成功后，右上角会出现钱包地址。此时我们点击[Earn](https://app.turbos.finance/#/pools)这个按钮，即可找到创建池子的页面

<figure><img src="../.gitbook/assets/image (408).png" alt=""><figcaption></figcaption></figure>

### **2、创建交易对**

当然，我们也可以直接通过链接进入加池页面：[https://app.turbos.finance/#/pools](https://app.turbos.finance/#/pools) ，进来之后，我们找到**Creat a Pool**这个位置，点击进入即可

<figure><img src="../.gitbook/assets/image (409).png" alt=""><figcaption></figcaption></figure>

第一步，我们需要先选择代币

<figure><img src="../.gitbook/assets/image (410).png" alt=""><figcaption><p>选择代币</p></figcaption></figure>

* **base token：**&#x57FA;础代币，就是你发行的代币
* **quote token：**&#x62A5;价代币，就是SUI、USDT、USDC这种主流币

例如我通过合约地址选择BananaTool作为基础代币，SUI作为报价代币，就是下面这样

<figure><img src="../.gitbook/assets/image (411).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (412).png" alt=""><figcaption><p>确认交易对</p></figcaption></figure>

确认好两个代币交易对之后，我们继续进入下一步

### **3、设置资金池**

在资金池设置页面，我们需要设置费率、初始价格、价格范围等内容，具体可参考下图所示：

<figure><img src="../.gitbook/assets/image (413).png" alt=""><figcaption><p>create pool</p></figcaption></figure>

创建资金池可能涉及到的选择

* **费率/滑点：**&#x867D;然给出了多个等级，但是默认只能**选择1%**，没有其他选项
* **设置初始价格：**&#x5373;代币的上线价格，如果是SUI池子，则该价格以SUI计价，例如我要设置Banana的上线价格是0.0000001 SUI，那么在这个输入框里填入0.0000001即可
* **设置流动性范围：**&#x5176;实就是该流动性的价格波动范围，这个大家请直接选择**Full**，即**全范围**，表示代币价格没有下限或上限。如果选择Custom，则需要设定一个价格下限与上限，这样不利于项目的长期运作
* **加池数量：**&#x586B;写你要放入资金池的代币数量
* **提示：**&#x6700;后会有一个提示，大概意思就是说，池子不能小于100U

了解完所有选项配置之后，BananaTool填写的参数示意如下

<figure><img src="../.gitbook/assets/image (414).png" alt=""><figcaption></figcaption></figure>

填写完成之后，点击Create Turbos pool and deposit（创建池子并存入代币），进行二次确认

<figure><img src="../.gitbook/assets/image (415).png" alt=""><figcaption></figcaption></figure>

再次确认信息无误之后，点击按钮，会弹出钱包进行确认

<figure><img src="../.gitbook/assets/image (416).png" alt=""><figcaption></figcaption></figure>

钱包点击Approve后，等待几秒钟，Trubos会提示你创建成功

<figure><img src="../.gitbook/assets/image (417).png" alt=""><figcaption></figcaption></figure>

### **4、交易代币**

池子创建成功后，就可以交易了。我们进入到Trurbos的官网首页：[https://app.turbos.finance/](https://app.turbos.finance/) ，选择卖出BananaTool代币100万个

<figure><img src="../.gitbook/assets/image (418).png" alt=""><figcaption><p>swap</p></figcaption></figure>

点击Trade后，钱包确认即可完成交易

<figure><img src="../.gitbook/assets/image (419).png" alt=""><figcaption></figcaption></figure>

## **二、增加与撤出流动性池子**

池子创建好之后，在哪里加池子和撤池子呢？首先，我们进入到Turbos的流动性管理页面：[https://app.turbos.finance/#/pools](https://app.turbos.finance/#/pools) ，选择[Manage Positions and Rewards](https://app.turbos.finance/#/pools?tab=position)（管理流动性与奖励）

<figure><img src="../.gitbook/assets/image (421).png" alt=""><figcaption><p>管理流动性</p></figcaption></figure>

之后就能看到你钱包里面的所有流动性了，包括流动性的金额、范围、APR等都很清晰的展示，我们选择要增加或者撤出的流动性交易对

<figure><img src="../.gitbook/assets/image (422).png" alt=""><figcaption></figcaption></figure>

在进入的页面里，就可以对这个流动性进行管理了，包括增加或者撤出流动性

<figure><img src="../.gitbook/assets/image (423).png" alt=""><figcaption></figcaption></figure>

* Increase Liquidity：增加流动性（加池子）
* Remove Liquidity：撤出流动性（撤池子）

假设我们点击**增加流动性**，就可以按照比例进行增加相应的代币，然后钱包确认即可

<figure><img src="../.gitbook/assets/image (424).png" alt=""><figcaption><p>加池子-增加流动性</p></figcaption></figure>

假设我们点击撤出流动性，就可以按照比例进行移除相应的代币，然后钱包确认即可

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

## **三、疑问解答** <a href="#san-yi-wen-jie-da" id="san-yi-wen-jie-da"></a>

#### **1、为什么我加了池子后看不到自己的池子，也不能交易？**

* 答：池子初始化需要一些时间，大概30分钟之后才能看到池子，才能交易

#### **2、创建资金池的过程中不弹出钱包怎么办？**

* 答：如果在页面操作时间过久，就会这样，可以刷新页面重试。或者查看一下钱包是否锁住，如果上锁了，把钱包解锁后刷新页面就可以了

#### **3、Turbos创建池子要收费吗？**

* 答：根据实际操作经验来看，在Turbos创建池子不收取费用

如有大家还有不明白或者不清楚的地方，请加入官方电报Telegram群：[https://t.me/BananaTools](https://t.me/BananaTools)

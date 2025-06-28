---
icon: bluetooth-b
---

# BlueMove创建AMM流动性资金池教程

BlueMove是一款基于 Aptos 和 Sui 区块链构建的应用程序，为用户提供 NFT交易、DEX等功能。最初，它只是一个多链NFT市场，后面逐步拓展到集DEX、Bridge为一体的综合应用程序。

值得注意的是，BlueMove也是Sui区块链上为数不多的支持AMM的去中心化交易所，所以PandaTool建议大家可以在这里创建流动性。

<figure><img src="../.gitbook/assets/image (426).png" alt=""><figcaption><p>bluemove</p></figcaption></figure>

{% hint style="info" %}
注意：本文仅作为教学演示，所涉及到的资金池和代币均**没有任何实际价值**，大家也不要进行任何形式的交易。如果因此造成资金损失，PandaTool无法对此负责
{% endhint %}

## **一、创建流动性资金池** <a href="#yi-chuang-jian-liu-dong-xing-zi-jin-chi" id="yi-chuang-jian-liu-dong-xing-zi-jin-chi"></a>

### **1、连接钱包** <a href="#id-1-lian-jie-qian-bao" id="id-1-lian-jie-qian-bao"></a>

所有的链上操作第一步都是连接钱包，以识别你的地址。我们打开BlueMove的官网：[https://dex.bluemove.net/](https://dex.bluemove.net/) ，点击右上角[**连接钱包**](https://dex.bluemove.net/connect-wallet)按钮

<figure><img src="../.gitbook/assets/image (427).png" alt=""><figcaption><p>link wallet</p></figcaption></figure>

点击之后，会弹出提示让你选择钱包，我们可以选择Suiet

<figure><img src="../.gitbook/assets/image (428).png" alt=""><figcaption><p>suiet</p></figcaption></figure>

之后会弹出钱包让你确认，点击继续连接就可以了（如果没有弹出钱包，看一下是不是钱包上锁了）

<figure><img src="../.gitbook/assets/image (429).png" alt=""><figcaption><p>连接钱包</p></figcaption></figure>

和所有的DAPP一样，连接成功后右上角会出现钱包地址

<figure><img src="../.gitbook/assets/image (430).png" alt=""><figcaption><p>link wallet success</p></figcaption></figure>

## **2、找到资金池**

我们在首页找到Pools点击进入，直接通过链接进入：[https://dex.bluemove.net/pool](https://dex.bluemove.net/pool)

<figure><img src="../.gitbook/assets/image (431).png" alt=""><figcaption><p>pools</p></figcaption></figure>

之后会进入到流动性管理页面，在这个页面你可以看到自己的流动性情况

<figure><img src="../.gitbook/assets/image (432).png" alt=""><figcaption></figcaption></figure>

我们创建资金池的话，就点击Creat a pool，然后进入到代币选择页面

### **3、确认交易对**

左边一般就选择Sui或者USDC、USDT这些，右边就是我们自己发行的土狗币，通过合约地址进行搜索

<figure><img src="../.gitbook/assets/image (433).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (434).png" alt=""><figcaption></figcaption></figure>

### **4、设定初始价格**

确认代币交易对之后，下面我们需要输入各个代币的数量与比例

<figure><img src="../.gitbook/assets/image (435).png" alt=""><figcaption><p>create pool</p></figcaption></figure>

创建池子的初始数量和比例，决定了代币的上线价格。例如我加入10SUI和100000000个Panda币，那么代币的上线价格就是10÷100000000=0.0000001SUI。假设SUI的价格是3U，那么Panda代币的价格就是：0.0000001 x 3 =0.0000003U（注意：该说法仅作为演示，本文涉及到的代币没有任何实际价值）

<figure><img src="../.gitbook/assets/image (436).png" alt=""><figcaption></figcaption></figure>

确定自己输入的代币数量和SUI数量无误后，点击Creat Pool，此时会弹出钱包让你确认

<figure><img src="../.gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure>

点击Approve之后，等待几秒钟就会有提示告诉你池子创建完成了

<figure><img src="../.gitbook/assets/image (438).png" alt=""><figcaption></figcaption></figure>

## **二、添加与撤出流动性**

创建了池子后，如果我们想继续加池子怎么办呢？如果想撤池子怎么办呢？其实也很简单，我们进入BlueMove的流动性管理页面：[https://dex.bluemove.net/pool](https://dex.bluemove.net/pool) ，就能看到自己加的池子

<figure><img src="../.gitbook/assets/image (439).png" alt=""><figcaption></figcaption></figure>

### **1、增加流动性**

点击Add liquidity Instead后，按照当前的价格与比例进行添加流动性

<figure><img src="../.gitbook/assets/image (440).png" alt=""><figcaption></figcaption></figure>

之后点击Add Liquidity，会跳出钱包进行确认。授权后，即可完成添加

<figure><img src="../.gitbook/assets/image (441).png" alt=""><figcaption></figcaption></figure>

### **2、撤出流动性**

撤出流动性或者说移出流动性其实也很简单，在[流动性管理](https://dex.bluemove.net/pool)页面点击Remove，会跳出移除页面

<figure><img src="../.gitbook/assets/image (442).png" alt=""><figcaption><p>remove liquidity</p></figcaption></figure>

我们可以根据自己的需要选择要移出的流动性比例，从1%到100%都可以选择。确定好比例之后，点击Remove Liqiudity，会跳出钱包进行确认

<figure><img src="../.gitbook/assets/image (443).png" alt=""><figcaption></figcaption></figure>

点击钱包的Approve按钮，等待几秒钟后，即可完成流动性的撤出

<figure><img src="../.gitbook/assets/image (444).png" alt=""><figcaption></figcaption></figure>

至此，我们关于BlueMove的加池子、撤池子教程，就算是介绍完毕了。教程写的很详细，大家仔细看都能学会，接下来教大家烧池子（锁LP）

## **三、疑问解答**

#### **1、BlueMove创建池子要收费吗？**

* 答：根据实际操作经验来看，在BlueMove创建池子不收取费用

#### **2、为什么在BlueMove创建的资金池不能在他的平台交易**

* 答：这确实是一个令人困惑的问题，经过我们查验，该问题主要是由于他的前端Bug导致的，只能等BlueMove那边自己修复了

如有大家还有不明白或者不清楚的地方，请加入官方电报Telegram群：[https://t.me/BananaTools](https://t.me/BananaTools)

---
description: 干净合约、方便上手、无税无功能、Ave检测全绿
icon: '1'
---

# 标准ERC20代币

标准代币视频教程：

{% embed url="https://youtu.be/cRZ7oMb0dbI" %}

BalanaTool支持BSC主网、BSC测试网等十余条公链的代币创建, 代币模版包含带税模版、分红模版等常见经济模型. 可在几分钟内创建一个属于你自己的Token

下面会详细描述代币机制, 所有链的机制和操作都一样,可以举一反三

{% hint style="success" %}
点击加入 [BananaTool](https://t.me/BananaTools)官方交流群 交流反馈

推荐使用电脑版谷歌浏览器 + `Metamask` 插件 进行操作, 手机用户也可以在 `TP钱包`-发现-输入官网链接 进行操作
{% endhint %}

## 1、功能解释 <a href="#id-1-gong-neng-jie-shi" id="id-1-gong-neng-jie-shi"></a>

标准代币指的是**没有任何功能**、机制的代币合约，代币创建之后默认会丢弃权限，所以也没有任何权限，是一个纯粹的、干净的、标准的合约。

根据以下步骤，您可以在可支持的任意一条链上，创建一个标准合约代币。以BSC为例。

## 2、连接钱包 <a href="#id-2-lian-jie-qian-bao" id="id-2-lian-jie-qian-bao"></a>

使用浏览器或者钱包打开网址：[https://bananatool.com/token/Standard](https://bananatool.com/token/Standard)，点击右上角，将小狐狸钱包切换到币安主网（BSC）

<figure><img src="../.gitbook/assets/image (299).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (300).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (302).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (303).png" alt=""><figcaption></figcaption></figure>

右上角显示钱包地址，表示钱包连接成功。

## 3、填写代币参数 <a href="#id-3-tian-xie-dai-bi-can-shu" id="id-3-tian-xie-dai-bi-can-shu"></a>

在打开的页面，依次填写代币信息。假设我们创建一个代币叫——“BananaTool”，应该进行如下填写：

* **代币名称：**&#x42;ananaTool（代币全称）
* **代币符号：**&#x42;ananaTool（代币简称）
* **发行量：**&#x31;0000（代币数量）
* **精度：**&#x31;8（小数点后的位数）

<figure><img src="../.gitbook/assets/image (304).png" alt=""><figcaption></figcaption></figure>

## 4、创建合约 <a href="#id-4-chuang-jian-he-yue" id="id-4-chuang-jian-he-yue"></a>

确认填写的参数无误后，点击“创建合约”。

<figure><img src="../.gitbook/assets/image (306).png" alt=""><figcaption></figcaption></figure>

再次点击“创建合约”。此时小狐狸钱包会要求你支gas费，点击确认，等待几十秒，合约就创建完成了。

此时，我们点击"前往控制台"，就能看到自己创建的合约了，代币也已经发送到创建者的钱包地址里。

小狐狸也会弹出添加代币的窗口，点击添加代币，就能在代币列表看到刚创建的代币了。

<figure><img src="../.gitbook/assets/image (307).png" alt=""><figcaption></figcaption></figure>

## 5、添加流动性 <a href="#id-5-tian-jia-liu-dong-xing" id="id-5-tian-jia-liu-dong-xing"></a>

代币创建完成之后，只能转账，还不能交易。要想使代币可以交易，需要前往PancakeSwap创建一个流动性资金池才可以。

我们打开测试链薄饼：[https://pancakeswap.finance/](https://pancakeswap.finance/?chain=bscTestnet)，找到“交易-流动性”：

点击添加流动性

<figure><img src="../.gitbook/assets/image (312).png" alt=""><figcaption></figcaption></figure>

打开之后，点击More，点击添加V2流动性

<figure><img src="../.gitbook/assets/image (313).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (314).png" alt=""><figcaption></figcaption></figure>

在左右两边分别输入两个代币，创建交易对。两种代币，一种是我们创建的Balana，另一种是USDT。并根据自己的需求，填写初始放入资金池的代币数量：

<figure><img src="../.gitbook/assets/image (315).png" alt=""><figcaption></figcaption></figure>

两种代币的数量比例，决定了代币上市的初始价格。例如上面，我们放入了100000个USDT和100000个Banana，就说明Banana的上市价格是1USDT。

之后，我们依次点击`批准代币`，再点击`添加`，创建币对和供应，即可流动性创建成功。

<figure><img src="../.gitbook/assets/image (316).png" alt=""><figcaption></figcaption></figure>

现在，我们回到交易页面，就能交易了：

<figure><img src="../.gitbook/assets/image (317).png" alt=""><figcaption></figcaption></figure>

### 注意事项 <a href="#zhu-yi-shi-xiang" id="zhu-yi-shi-xiang"></a>

* 代币创建完成后，默认是开源的。如果没有开源，请提前准备好复制的源码以及构造参数，参考开源教程：代币开源

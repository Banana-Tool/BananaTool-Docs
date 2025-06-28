---
description: 通过BananaTool的工具完成波场批量转账
icon: right-from-bracket
---

# 波场Tron批量转账工具教程

波场批量转账工具是什么？顾名思义，它可以在波场链上批量转账代币，如 TRX、USDT、SUN 等等。使用批量转账工具，用户可以高效地将某一地址中的代币发送至多个不同地址。

相较于逐一转账，批量操作显著节省时间和精力。比如：一次性向 200 个地址转账，与手动进行 200 次操作相比，效率不可同日而语。同时，批量转账在能量消耗上也更加经济。

下面，BananaTool 将演示如何使用该工具进行批量转账操作。

{% hint style="info" %}
波场链批量转账需要消耗能量，尤其是 USDT 这类合约代币，能量消耗极高。操作前建议提前购买足够能量。购买地址：[https://feee.io/?ic=Z5U7](https://feee.io/?ic=Z5U7)
{% endhint %}

## **一、连接波宝钱包**

我们打开波场批量转账工具的链接：[https://tron.bananatool.com/airdrop](https://tron.bananatool.com/airdrop) ，点击右上角连接钱包。（请先确保自己的浏览器已经安装了波宝钱包，如果没有，请查阅 → [TronLink波宝钱包安装教程](https://docs.bananatool.com/tron/tronlink)）

<figure><img src="../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure>

之后TronLink会跳出来让你确认，点击**连接**就可以了

<figure><img src="../.gitbook/assets/image (195).png" alt=""><figcaption></figcaption></figure>

连接成功后，右上角会显示出你的钱包地址，此时就可以进入到下一步了

<figure><img src="../.gitbook/assets/image (196).png" alt=""><figcaption></figcaption></figure>

## **二、填写转账信息**

接下来，我们需要填写转账信息，包括：转账的代币、转账的地址以及每个地址的接收数量

<figure><img src="../.gitbook/assets/image (197).png" alt=""><figcaption></figcaption></figure>

例如，我要转账USDT给到10个钱包地址，每个钱包不固定数量，填写后就是下图的样子

<figure><img src="../.gitbook/assets/image (198).png" alt=""><figcaption></figcaption></figure>

信息确认完成后，我们点击批量转账

如果您是第一次操作，那么此时钱包会提示让你进行授权，我们点击确认即可（授权只发生在USDT这样的代币上，批量转账TRX是不需要授权的）

<figure><img src="../.gitbook/assets/image (200).png" alt="" width="407"><figcaption></figcaption></figure>

这里我们需要填写自己要授权的USDT数量，或者不用自定义，直接选择默认值也可以。但不管如何，都要保证填写的数量要大于此次转账的数量。

授权信息写好之后，我们点击下一步，此时会让你进行一个签名授权，并再次确认签名

<figure><img src="../.gitbook/assets/image (201).png" alt=""><figcaption></figcaption></figure>

授权确认完成后，钱包再次弹出，点击签名，即可完成批量转账

<figure><img src="../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

## **三、疑问解答**

#### **1、授权有风险嘛？**

* 答：批量转账的功能是通过合约实现，即：将钱包内的代币授权给合约，合约发起转账的时候，从你的钱包内调取这些代币给到接收地址。因此，授权的风险在于平台。如果我们平台有风险，那么授权就有风险。如果我们平台不跑路或者被攻击，那就没有风险

#### **2、批量转账一次最多能转多少个地址？**

* 答：我们建议一次转账的地址数量不要超过200个，以保证工具的稳定性

#### **3、转账一次大概消耗多少能量？**

* 答：批量给10个地址转账USDT大概消耗38.4万能量，燃烧82TRX

**点击加入**[**BananaTool官方交流群**](https://t.me/BananaTools) **交流反馈**

---
description: 100%去中心化的预售合约创建教程
icon: mintbit
---

# 创建预售

创建预售视频教程

{% embed url="https://youtu.be/NCJil9NV-dw" %}

## 一、预售功能说明 <a href="#id-1-gong-neng-jie-shi" id="id-1-gong-neng-jie-shi"></a>

* **无前端：**&#x4E0D;需要任何网页，纯合约支持，100%**去中心化**
* **转账即预售：**&#x7528;户将BNB转到`预售合约`，就能**自动**获得代币或者LP
* **不用领取：**&#x53C2;与预售的用户**无需**手动领取代币
* **自定义功能：**&#x9879;目方可以在预售开始后通过控制台**修改**预售价格和每份数量
* **无软顶/硬顶：**&#x6CA1;有软顶或者硬顶的概念，只有一个预售总数量（份数x每份数量）
* **加池模式**：预售的同时**自动添加流动性**，用户只能获得`LP`，不能获得代币

## 二、注意事项提前说明 <a href="#er-zhu-yi-shi-xiang-ti-qian-shuo-ming" id="er-zhu-yi-shi-xiang-ti-qian-shuo-ming"></a>

* 预售开启前请确保代币还没有加池子
* 标准代币合约**不建议**开启加池模式
* 其他代币合约请不要开始交易（如有手动开盘功能的话）
* 预售创建成功后，请将预售地址加入到代币地址的**白名单**中
* 如果你的代币合约有手动开盘功能，但是没有白名单功能，那不要使用**加池模式**
* 用了加池模式后，预售期间**不要撤池子**。一旦撤池子，可能会导致后续预售失败

## **三、Mint预售创建教程**

### 1、连接钱包

<figure><img src="../.gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

然后打开预售创建官网：[https://bananatool.com/presale/create](https://bananatool.com/presale/create)

### 2、填写预售参数

<figure><img src="../.gitbook/assets/image (228).png" alt=""><figcaption></figcaption></figure>

* **预售代币地址** : 你要预售的代币合约地址（前提是有代币）
* **每份价格 :** 每份预售的代币需要多少bnb
* **每份数量** : 每份有多少个代币
* **总份数：**&#x4E00;共可以预售多少份（每份数量x总份数≤代币发行总量）
* **收款地址：**&#x9884;售收款地址
* **加池模式**
  * 不开启 : 用户转账BNB后，可以立马获得代币
  * 开启 : 用户转账BNB后，自动添加流动性，用户只能获得LP，无法获得代币
  * 加池比例：按照设定的比例（最小50%，最大100%）添加流动性

参数填写完成后，点击创建预售，此时会弹出钱包进行确认，等待几秒，就会提示你预售创建完成

<figure><img src="../.gitbook/assets/image (229).png" alt=""><figcaption></figcaption></figure>

### 3、预售控制台操作

创建成功后，我们进入到控制台

<figure><img src="../.gitbook/assets/image (231).png" alt=""><figcaption></figcaption></figure>

### **预售控制**

* <mark style="color:green;">**开启交易：**</mark>点击按钮后，钱包确认后，即可开始预售
* 设置每份价格 : 重新修改预售价格
* 设置每份数量：重新修改每份数量
* 设置总份数：根据实际情况修改最大份数
* 修改收款钱包：可以根据需要进行修改
* 提取合约内代&#x5E01;**：**&#x53EF;以将预售合约里面的代币提取走


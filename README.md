#  NodeParty 开源基金会运作草案
## 组织介绍

![](https://github.com/Hangzhou-Node-Party/JS-OpenSource-Foundation/raw/master/img/LOGO-G-250.png)

NodeParty 开源基金会是一个**新型的**、**纯公益性质的**、**开源的** 基金会，它用标准严谨的开源流程来管理资金，由社区具有一定影响力的开发者共同监督和维护。

建立此开源基金会的初衷是：
> 利用社区活动或者企业赞助产生的资金，不计回报的回馈给社区，例如支持社区相关活动的支出，支持在社区有突出贡献的个人开发者，或者在社区有贡献的小型初创公司等。

基金会的资金来源目前主要是 相关线下线上活动的门票、个人和企业的赞助，赞助列表见：[赞助列表](#赞助列表活动收入挂在讲师名下记录其他赞助个人和企业名义记录)，如有意赞助，请参考：[赞助流程](#赞助流程)

如果您需要此基金会的支持，请按照[资金申请流程](#资金申请流程)提交相关资料。另外我们会择机自主赞助个人或者社区活动。

任何个人没有动用本基金会资金的权利，所有支出均需要经过[资金管理流程](#资金管理流程)的制约，由维护者共同监督。

## 维护者

* [芋头](https://github.com/xinyu198736) 主事
* [XadillaX](https://github.com/XadillaX) 管理员
* [小问](https://github.com/iwillwen) 管理员

您也可以申请加入此组织，请联系以上维护者中至少一位，并且通过 3 人以上推荐即可进入维护者列表，拥有监督此基金会所有流程的权利。

加入维护者列表，需

## 资金管理流程

### 资金池

此基金的真实资金池，存于一个独立的支付宝账号中，此账号的登录密码，支付密码，绑定手机号由主事持有。

### 资金申请流程

1. 由申请者或者管理员提交 issue ，标题格式 
`apply spending: ${日期} ${事项} ${申请金额} `，例如：`apply spending: 20170801 杭州小型聚会餐饮费 200.00元 `，并且在 issue 详情里提供更为详细的信息。
2. 由维护者中三人以上在 issue 里回复 ok 。
3. 满足条件后，由 主事 将资金转出，并且将**转账记录**和**余额信息**截图回复到 issue 中，同时关闭 issue。
4. 主事 提交 支出记录 到 spending.md 。

### 资金收入流程

1. 由主事或管理员提交 issue，标题格式 `apply income: ${日期} ${事项} ${收入金额} `。
2. 主事收到钱款之后，将**转账记录**和**余额信息**截图回复到 issue 中，同时关闭 issue。
3. 主事 提交 收入记录 到 income.md 。

### 收入记录

基金的每笔收入都由维护者以 commit 的形式提交到 income.md ，需包含信息：捐赠者、金额、时间(2017-07-08)、收入类型、备注。

commit log 需按照此格式 

	income: ${捐赠者} ${金额} ${捐赠时间} ${收入类型} ${备注}

收入类型包含：**个人赞助**、**企业赞助**、**活动门票**。

备注中需注明详细信息，例如 **某年某月某次活动的门票收入，共多少人报名**。

金额，精确到小数点后 2 位。

所有人工收入和自动收入（如利息，利息收入需要有脚本实现自动记录）都须有收入记录。

### 支出记录

基金的每笔收入都由维护者以 commit 的形式提交到 spending.md，需包含信息：支出金额、支出日期、支出事项。

commit log 需按照此格式 

	spending: ${支出金额} ${支出日期} ${支出事项}

## 赞助流程

1. 赞助方提交 issue，标题格式 `present donate: ${日期} ${事项} ${赞助金额} `。请在 issue 里提交联系方式等详细信息。
2. 由主事或管理员联系赞助方，接受资金转入（专用支付宝账号：xinyu198736@gmail.com），将截图添加到 issue，关闭 issue。
3. 主事 提交 收入记录 到 income.md。
4. 主事 将赞助对象添加到 赞助列表。可带有 logo 和链接。

## 赞助列表（活动收入挂在讲师名下记录，其他赞助个人和企业名义记录）

| 捐赠者 | 金额(元) | 时间| 收入类型 | 记录 issue |
|-------|-----|------------|----------|-----------|
| @Keith-CY | 150.00 | 2017-08-02 | 个人赞助 | [记录链接](https://github.com/Hangzhou-Node-Party/JS-OpenSource-Foundation/issues/2) |
| @longtianye  | 200.88 | 2017-08-02 | 个人赞助 | [记录链接](https://github.com/Hangzhou-Node-Party/JS-OpenSource-Foundation/issues/3) |
| @芋头  | 2000.00 | 2017-08-06 | 个人赞助 | [记录链接](https://github.com/Hangzhou-Node-Party/JS-OpenSource-Foundation/issues/5) |
| @huanglong  | 1024.00 | 2017-08-06 | 个人赞助 | [记录链接](https://github.com/Hangzhou-Node-Party/JS-OpenSource-Foundation/issues/6) |
| @int64ago  | 100.00 | 2017-08-06 | 个人赞助 | [记录链接](https://github.com/Hangzhou-Node-Party/JS-OpenSource-Foundation/issues/7) |


## 当前资金池

```money
总额：3474.88 元
本月收入：3474.88 元
本月支出：0 元
```

余额截图：

 ![](https://github.com/Hangzhou-Node-Party/JS-OpenSource-Foundation/raw/master/img/yue.png)

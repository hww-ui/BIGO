# 利差套利工具教程（第三篇）：参数调整

进入套利页面

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

首先先配置好，监控配置

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

1、左上角选择之前配置好的账户组

2、如果是重度套利用户建议打开启动bigo默认开启（这个功能主要是会在bigo开启后自动打开套利，否则的话，需要每次手动在外面开启运行）

3、监控来源，根据自己需要，自行勾选

4、监控条件，字面意思，自行勾选（注意，监控的条件会干预做单，如果监控条件太高，则有可能无法做单，所以建议监控的条件设置低一点，做单条件可以单独控制，下面会进行描述

5、监控黑名单（填写交易对每行一个），

&#x20;       如：

&#x20;            BTCUSDT

&#x20;            ETHUSDT

之后选择提交即可

主页的监控运行开关标志着监控池状态，启动约至半分钟等待初始化过程，随后即可在下面的监控池表中看到监控的内容，如果时间长没有内容，请检查配置的条件是否太高，或者网络延迟是否太大



其次是做单配置

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

1、根据自己的资金量来选择单个交易对最大的使用资金（该值是现货与合约的合计值）

2、一笔买卖的最大使用资金（该值是用来控制滑点的第二道阈值，最大一手交易的usdt数）

3、减仓延迟秒，以及延迟次数（该值是用来过滤掉闪跳的行情，新手不建议进行更改）

4、建仓条件，暂停减仓（开启后，所有的建仓都会停止）

5、现多期空-建仓-现货与合约的最新价差额比例（通俗来讲就是现多期空的单差价率大于该值后才会开单）

6、现多期空-建仓-差额建仓时至少要满足的合约费率（该值是在判断有行情后，必须要满足费率大于该值才会开单）

7、现空期多-建仓-现货与合约的最新价差额比例（通俗来讲就是现空期多的单差价率大于该值后才会开单）

8、现空期多-建仓-至少要满足合约费率小于（该值是在判断有行情后，必须要满足费率小于该值才会开单）

9、平仓条件，暂停平仓（开启后，所有的减仓都会停止）

10、现多期空-减仓-标记价差额比例（通俗来讲就是现多期空的单，差价率小于该值后才会减仓出场）

11、现多期空-减仓-合约费率（该值是在判断差价回归后，必须要满足费率小于该值才会减仓）

12、现空期多-减仓-标记价差额比例（通俗来讲就是现空期多的单，差价率小于该值后才会减仓出场）

13、现空期多-减仓-综合费率（该值是在判断差价回归后，必须要满足费率小于该值才会减仓）

14、风控减仓（风险率达到该值时则会两边减仓至安全位置后停下）

以上配置建议在没太明白之前都不必修改

配置完毕后点击提交保存后运行开启前的最后一次检测即可

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

其中检测全为绿色的勾才算通过

即图中bybit的持仓干扰做单，可以将flr这个币提走或者划转至资金钱包即可，再次点击全部通过后，即可开启做单

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

运行过程中可查看当前的交易所延迟以及日志

![](<../../.gitbook/assets/image (13).png>)

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

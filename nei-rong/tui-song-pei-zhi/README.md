# 推送配置

首先在配置bigo消息推送前，你需要准备好一个推送平台的账户（钉钉，tg-暂未开放）

接下来先讲一下钉钉的机器人申请方法

创建一个群聊（建议使用手机，这样你可以单独一个人创建一个群，使用的是面对面建群功能）

创建好群聊后，使用手机或者pc客户端都行，找到群设置

<figure><img src="../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

选择机器人-添加机器人-自定义机器人

<figure><img src="../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

进入设置界面，机器人名字可以随便自己取，安全设置一定要选择“加签”

然后把“加签”里面那个复制出来保存好，点击完成

<figure><img src="../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

然后在把webhook这个链接复制下来，保存好，就算完成了机器人的配置，接下来就是绑定平台了

<figure><img src="../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

回到bigo，进入推送设置页面后，点击增加新的密钥

然后备注自己取一个名字，用于识别的就行

再把刚才保存的webhook链接填写进来

secret填写的是刚才的“加签”

填写完毕后，点击新增

<figure><img src="../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

新增完毕之后，选中生成出来的密钥，选择下方的推送内容（自行选择），选中之后，确认保存即可

<figure><img src="../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

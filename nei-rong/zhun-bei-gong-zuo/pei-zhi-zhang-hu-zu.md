# 配置账户组

配置账户组是bigo脚本启动前**最为关键**的一步，所以需要认真理解账户组才能更加全面的使用bigo

账户组在bigo中是所有脚本的必选项，它的作用是为了打包所有的账户进一个环境中的

> 举例：
>
> 如果你要启动的是tg项目，且你又希望绑定**独立ip**和**ton钱包**进去，这个时候账户组里面就需要添加<mark style="background-color:blue;">tg账户</mark>，<mark style="background-color:blue;">代理ip</mark>，<mark style="background-color:blue;">ton钱包</mark>，
>
> 其中<mark style="background-color:blue;">代理ip</mark>，<mark style="background-color:blue;">ton钱包</mark>均为**非必选项**，如果**不绑定**<mark style="background-color:blue;">代理ip</mark>，则会使用**本地**网络启动脚本



### 1、配置方法说明：

1. 打开账户配置-账户组

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

2. 新增账户组

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

3. 在你需要导入的类目上右键点击，选择【添加账户】

> 举例: 这里我要设置tg账户

<figure><img src="../../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

4. 在弹出框中，拖拽勾选住你需要的账户，右键点击选择【确认】

<div data-full-width="false"><figure><img src="../../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
&#x20;或者 选择特定的个数 ，选中其中一个作为开始 然后找到要结束的那个 按住 `shift` 并且点击要结束的那个

最后右击点击【确认 】即可
{% endhint %}

5. 浏览器指纹那一列右键选择需要的指纹（电脑指纹，手机指纹，苹果指纹，安卓指纹按需挑选）

<figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
点击之后会自动随机生成指纹
{% endhint %}

### 2、配置注意事项

1. 对于账户组中一行**有数据**且需要**新增绑定内容**的情况下，右键选择的是【修改账户】

<figure><img src="../../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

> 举例：
>
> 如果账户组第8行，有tg账户了，这个时候想要给第8行绑定代理ip，则需要在第8行的代理ip的格子上右键选择修改账户，在弹出的代理列表框中找到需要添加的代理ip那一行右键选择【确定】，即可绑定成功。

2. 对于账户组**批量**更换钱包地址，或者代理ip的方法，可以拖选需要更换的数据（如果是整列数据，则可以直接右键选择标题【代理ip】）右键点击【确定】，然后在弹出框中选择新的数据即可

<figure><img src="../../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

2. 所有想绑定的添加完毕之后，建议右侧滚动条至列表最下面，查看是否有遗漏，如已经按照所想绑定好之后，查看最左边一列的浏览器指纹，如有遗漏请补充完毕后才能确认保存
3. 账户组保存之前仔细检查需要绑定的数据，确定无误后，添加账户组名字保存即可

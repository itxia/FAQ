## 6、各类常用软件安装中出现的问题 {#6}

**注意：**各类软件（尤其是大型软件）安装过程漫长，步骤比较繁琐，请确认**电脑电量充足（电量不足时建议连接电源适配器后进行安装）**~~，并准备好水杯、暖手袋、瓜子、肥宅快乐水打发时间~~。本文档仅给出安装中出现问题的解决方法，**不提供软件非正常激活、破解**等途径，引用自外部链接的内容与本文无关。使用者需为自身行为负责。

### 6.1、Microsoft Office安装、修复、卸载、卸载残余 {#6-1-microsoft-office}

#### 6.1.1、非UWP应用商店的安装版本 {#6-1-1-uwp}

正常的Office卸载方法：[点击此处超链接查看](https://support.office.com/zh-cn/article/%E4%BB%8E-pc-%E5%8D%B8%E8%BD%BD-office-9dd49b83-264a-477a-8fcc-2fdf5dbf61d8?ui=zh-CN&rs=zh-CN&ad=CN)。请依此链接提供之法卸载office软件，如有需要请**参见4。**

如果Office反复弹出**提示需要你登录，请先尝试登录。如果登录后发现依然无法激活，且学校的KMS激活无效**，则先按照上一步正常卸载后，[点击此处超链接查看](https://support.office.com/zh-cn/article/%E6%96%B0%E7%94%B5%E8%84%91%E4%B8%8A%E7%9A%84-Office-%E5%8F%8D%E5%A4%8D%E6%8F%90%E7%A4%BA%E6%BF%80%E6%B4%BB-a9a6b05f-f6ce-4d1f-8d49-eb5007b64ba1)。**之后再使用KMS进行激活。**

#### 6.1.2、UWP应用商店（Microsoft Store）版本 {#6-1-2-uwp-microsoft-store}

如果出现该版本的Office套餐问题，请在**开始菜单**中卸载**OneNote,Word,Excel,PowerPoint**四个应用，然后从应用商店中重新下载安装和更新。

如果无法从应用商店中下载Office，请**参见2**下载Office并安装。

#### 6.1.3、Office的修复 {#6-1-3-office}

情况一：如果你是买电脑附赠的**家庭学生版**，出了问题可以和情况二一样处理修复；如果买来**有贴标签说赠送家庭学生版**，打开却发现没有office，请到这里下载office镜像：[家庭学生版镜像](http://officecdn.microsoft.com/sg/492350f6-3a01-4f97-b9c0-c7c6ddf67d60/media/zh-CN/HomeStudentRetail.img)，之后安装登录微软账户激活

情况二：如果你是**学校或者其他地方安装的Office**（即，**不是买电脑送你的**，有个iso或者什么安装包的），可**参照4**的方法进入**卸载的界面**，卸载界面有一**修复选项**。

情况三：如果你是赠送的**Office 365**，请**参照4.2，**点开后比其他应用多一个**高级选项**，可进入修复。如果无法修复，可以参照4.2请前往**微软官网-账户-订阅与支持**查看是否有此项，以重新下载。

### 6.2、Adobe系列软件安装、卸载和残余文件的清除 {#6-2-adobe}

Adobe系列软件安装程序打开时提示：“**安装程序无法初始化。请下载 Adobe Support Advisor 检测该问题。”**

出现此问题时，依以下数种方法之一处理：

*   **手动排查**：**依次检查以下目录中是否含有指定文件夹，若有，删除之，然后重新打开Adobe安装程序。**

**X=C&amp;安装盘盘符**（例如，安装在D盘的，则X为C和D，需依次检查）

1.  X:\Porgram Files (x86)\Common Files\Adobe\ 若含有**Caps**文件夹，删除之
2.  X:\Program Files (x86)\Common Files\Adobe\ 若含有**OOBE**文件夹，删除之
3.  X:\Porgram Files\Common Files\Adobe\ 若含有**Caps**文件夹，删除之
4.  X:\Program Files\Common Files\Adobe\ 若含有**OOBE**文件夹，删除之

*   **自动检测**：请参阅[Adobe官网文章](https://helpx.adobe.com/creative-cloud/kb/cc-cleaner-tool-installation-problems.html#)并依照网页中的指示进行。

**注意：**在清除上述文件夹之前，**请确认其中没有存放个人文件。**依Adobe官网文章中的描述步骤进行清除的，**请留意网页中注意事项。**因个人疏忽造成不可挽回的损失的，个人承担责任。

### 6.3、各类学术、专业常用软件安装、激活的问题 {#6-3}

MATLAB，Mathematica，COMSOL，LaTeX的安装教程请参阅[**https://itxia.github.io/**](https://itxia.github.io/)中对应网页教程。

如果遇到额外的安装问题，可以到**隔壁软件群（群号674580668）**寻求帮助（加群记得看公告看文件，切勿盲目伸手提问~）
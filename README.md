<h2>ZhihuAnswerChecker-JavaScript</h2>
知乎用户用于检查 “回答” 被屏蔽情况的Javascript脚本。<br>
仅限检查“回答”项目，且单次执行只检查当前的单个页面。<p>
建议用途：随时检查最新一页回答中的被屏蔽情况。<p>
作者：老实人不接盘@知乎（主体编写）, 尼尼尼@知乎（初版编写）

**运行环境需求：**<p>
已测试过 谷歌Chrome / 微软Edge/ Firefox 浏览器，均可正常使用。<p>

**问题反馈：**<p>
知乎私信，或发送邮件到 ninini19900319@gmail.com

**相关下载/安装地址：**<p>
百度网盘：https://pan.baidu.com/s/1cYQtcfRqW_IsrOBNch4Zew?pwd=6666 <p>
Github: https://github.com/ninini1990/ZhihuAnswerChecker-JavaScript <p>
Chrome扩展商店地址：https://chrome.google.com/webstore/category/extensions?hl=zh-CN <p>
Chrome扩展商店“暴力猴”地址：https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag?hl=zh-CN  <p>


---
<h2>使用提示</h2> <p>

**安全性：**<p>
1. 此脚本只发布于，安装说明中所指定的插件商店地址和百度网盘两个分享链接。不要从其它来源下载。<p>
2. 不需要额外输入用户名、密码。此脚本也不会获取、保存、发送你的用户密码。<p>
3. 可检查脚本源码，无任何其它附加操作。<p>

**使用风险提示：**<p>
建议用于随时检查最新一页回答中的被屏蔽情况。<p>
但也请注意不要过于频繁执行，以免被知乎拒绝请求。<p>

**开源协议:**<p>
使用GPL3协议，请保持代码开源及遵守GPL3其他规则。<p>

---
<h2>安装及使用详细说明</h2><p>

**（以下均以Chrome为例，其它浏览器的操作步骤类似)**<p>

1.在浏览器中打开知乎，并登录自己的知乎账户。<p>

2.打开浏览器扩展商店<p>
Chrome可直接访问商店地址： https://chrome.google.com/webstore/category/extensions?hl=zh-CN  <p>

也可以从浏览器中逐步打开：<p>

![image](https://user-images.githubusercontent.com/112439804/187565895-080463e5-6ca8-4eb0-b1cc-31829f159517.png)<p>

![image](https://user-images.githubusercontent.com/112439804/187566024-c7661dd2-0071-42bf-bab5-ea3d42bfc3b6.png)<p>

![image](https://user-images.githubusercontent.com/112439804/187566129-447ae4e1-10df-4cbb-99d7-488846890a35.png)<p>

3.在扩展商店中搜索油猴、暴力猴等任意一个用于JS脚本注入的浏览器扩展。（以下以暴力猴为例）。<p>
搜索“暴力猴”或者“violentmonkey”<p>
Chrome可直接访问扩展地址：https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag?hl=zh-CN <p>

![image](https://user-images.githubusercontent.com/112439804/187566621-106909e8-a8cd-433b-a233-9de161fb2dc7.png)<p>

4.点击进入扩展页面，并点击按钮“添加至Chrome”。<p>

![image](https://user-images.githubusercontent.com/112439804/187566716-bc0151fb-ec92-40ef-9c81-c5bbd7beb97b.png)<p>

![image](https://user-images.githubusercontent.com/112439804/187567053-a32fd76f-47b9-4e51-86d9-fe9b445d5974.png)<p>


5.需要点击浏览器菜单栏中的扩展图标，将“暴力猴”扩展固定在菜单栏上。<p>

![image](https://user-images.githubusercontent.com/112439804/187567242-22f91c49-b151-4311-8bf7-df98b8f3a39a.png)<p>
 
![image](https://user-images.githubusercontent.com/112439804/187567654-011cf6f7-9990-4c07-904b-d885396cccbb.png)<p>

6.浏览器扩展安装完成后，安装检查知乎回答的JavaScript脚本。<p>
推荐从脚本商店中直接安装<p>
打开脚本地址：https://greasyfork.org/en/scripts/450495-zhihuanaswerchecker-javascript  <p>
点击“install the script” 按钮，再点击“确认安装”按钮。<p>

![image](https://user-images.githubusercontent.com/112439804/187567980-90e6e350-6744-41a5-a018-fbeda7cf84a7.png)<p>

![image](https://user-images.githubusercontent.com/112439804/187568121-9e5528f6-8cf9-46b0-bbff-8476cb3cc62d.png)<p>

7.再返回到知乎页面，刷新页面。<p>
点击浏览器菜单栏上的“暴力猴”扩展图标，即可看到脚本已安装并生效，且页面上多出一个绿色的“点击执行检查”按钮。<p>

![image](https://user-images.githubusercontent.com/112439804/187568456-25bcff08-8851-4962-9705-58a6d59574a2.png)<p>

8. 在知乎个人首页点击“回答”栏，待页面加载完成后，点击绿色的“点击执行检查”按钮。脚本即开始检查当前回答页面。<p>
注意脚本只检查当前回答页。如果想检查其它页，可以翻页，再重新执行。<p>

![image](https://user-images.githubusercontent.com/112439804/187568832-593aac66-e301-4767-8b95-296903d2ad8d.png)<p>

9. 检查结果示例<p>

![image](https://user-images.githubusercontent.com/112439804/187572607-13422563-99c3-498e-960c-33372f0f97e4.png)<p>

10. 如果在第6步中无法打开脚本商店，需要手工添加脚本。<p>
10.1 下载 ZhihuAnaswerChecker-JavaScript.txt 到本地<p>
Github: https://github.com/ninini1990/ZhihuAnswerChecker-JavaScript/blob/main/ZhihuAnaswerChecker-JavaScript.txt <p>
百度网盘：https://pan.baidu.com/s/1cYQtcfRqW_IsrOBNch4Zew?pwd=6666  -- 子目录：知乎单页回答检查工具(JavaScript版) <p>
10.2 点击浏览器扩展栏中的“暴力猴”图标，再点击“ + ”号，创建新脚本, 会打开一个新的浏览器窗口。<p>

![image](https://user-images.githubusercontent.com/112439804/187570560-3dd76997-f3f3-443e-a14b-552c5f2f893f.png)<p>

![image](https://user-images.githubusercontent.com/112439804/187572312-7729514f-d665-4761-8470-dd82eb69c28a.png)<p>
10.3 将 ZhihuAnaswerChecker-JavaScript.txt 中的全部文本内容粘贴到新脚本窗口中，并点击“保存”。即手工安装完成。<p>

![image](https://user-images.githubusercontent.com/112439804/187570775-ed4ac264-a7a6-45da-92c8-9a5294285140.png)<p>
10.4 回到知乎页面，刷新页面。即与第7步结果相同。<p>





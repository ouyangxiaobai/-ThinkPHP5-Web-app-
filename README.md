# -ThinkPHP5-Web-app-
[ThinkPHP5] 智能会议室Web端+app端(免费资源)
项目介绍:

[ThinkPHP5] 智能会议室Web端+app端

系统说明:

Android端
1、用户登录/注册
​ 打开APP，首页之前会要求登录或者注册，如图所示，输入用户名和密码。

1553517943224

1553517948533

​ APP上只支持用户账号登录。点击登录，即可进入主页面，默认为会议室租约订单列表。点击注册，则跳转到用户注册界面，如图所示。

2、个人信息管理
​ 在侧滑菜单中，包括了显示用户资料，包括昵称、职位等，可以在策划菜单中点击头像，进入用户信息界面，如图所示。

1553517984012

1553517990027

​ 用户信息包括昵称、账号、密码、手机、邮箱、公司、职位、信用度等，点击某一项即可输入，并且做了安全验证和格式验证，避免输入错误的内容，或者SQL注入攻击等。

3、会议室租约
​ 用户登录后，就能看到自己所有的会议室租约信息，每条租约显示会议主题、会议用途、具体会议室地点、会议时间。每条租约信息按照时间逆序排序，从最新到最久。

​ 侧滑菜单中有四个界面，分别为：租约列表、我的会议、加入会议、身份认证。默认界面是租约列表，在侧滑菜单中任意切换“所有租约”和“我的会议”。

1553518035452

1553518044798

​ 编辑右下角的加号按钮，进入添加会议室租约的界面。为了便捷起见，用户不需要手动选择会议室，只有默认的“智能匹配会议室”选项。从列表中点击某一项，则会进入编辑租约的界面。添加和编辑分别如下图所示:

1553518060979

1553518066449

​ 在租借会议室时，程序会智能判断当前时间，并且通过分析以往的会议室租借历史，来选择最合适的时间，尽量避免用户手动修改。或者可以通过点击出现的时间，进入选择日期和时间界面，手动修改开始、结束时间。

4、加入会议
​ 加入会议的方法，Android端与Web端一样，只需要通过输入会议ID便能够加入，如图所示。

1553518108975

5、应用设置
​ 每一个APP都有自己的应用设置，EasyMeeting提供了简单移动的原生设置界面。设置分为三类，分别是常规、通知、数据与同步。常规中有一些常用的选项，比如租借会议室时是否智能调整时间、显示的信息、自动同意会议邀请等。在“通知”选项中，确认开启会议前一小时通知，避免错过会议时间。而在“数据与同步”中，可以设置用户数据与租约的同步间隔，避免在其他设备上做了修改而导致本设备数据过期。

1553518117638

1553518121029

适用场景:

毕业论文、课程设计、公司项目参考

运行截图:
![1553518121029](https://user-images.githubusercontent.com/25460485/150267030-e50900fe-b300-4b04-b811-b45029ecb2c5.png)![1553518066449 (1)](https://user-images.githubusercontent.com/25460485/150267045-25f9e946-96d4-4067-8990-a2ead052ba2c.png)
![1553518066449](https://user-images.githubusercontent.com/25460485/150267047-f5ada36c-33b8-402d-be04-89b83a19a81b.png)
![1553518108975 (1)](https://user-images.githubusercontent.com/25460485/150267050-bc20751b-3803-4c9d-9c88-58b1c6eb5be9.png)
![1553518108975](https://user-images.githubusercontent.com/25460485/150267052-817f858c-9210-4e68-ba4c-46c2bf5db2bd.png)
![1553518117638 (1)](https://user-images.githubusercontent.com/25460485/150267054-389f815a-c094-4cb1-979f-8e4c3d1e14d0.png)
![1553518117638](https://user-images.githubusercontent.com/25460485/150267055-a3223386-1262-45a1-b810-6a2ccbf8a4d9.png)
![1553518121029 (1)](https://user-images.githubusercontent.com/25460485/150267056-ba3e5bce-15b3-4d3e-bc21-b1c2b8d24571.png)
![1553517943224 (1)](https://user-images.githubusercontent.com/25460485/150267057-a7ebfaa2-b979-4049-af92-ae6cf3de9b5d.png)
![1553517943224](https://user-images.githubusercontent.com/25460485/150267061-5eb24210-3d9e-480a-b901-648fbaa18d80.png)
![1553517948533 (1)](https://user-images.githubusercontent.com/25460485/150267064-329d23da-45ec-454f-a341-914c2896baa8.png)
![1553517948533](https://user-images.githubusercontent.com/25460485/150267068-b27e962f-f190-441e-baf6-7c3228a71223.png)
![1553517984012 (1)](https://user-images.githubusercontent.com/25460485/150267071-4b26449b-e1e5-4182-942a-68699815ef2c.png)
![1553517984012](https://user-images.githubusercontent.com/25460485/150267073-0036c269-500b-4e52-824f-7a36ef9a60cd.png)
![1553517990027 (1)](https://user-images.githubusercontent.com/25460485/150267075-2b1665e1-e310-45f7-ac3e-e58378977189.png)
![1553517990027](https://user-images.githubusercontent.com/25460485/150267076-9e48aabf-bf22-48d7-9fe3-a4723d82b715.png)
![1553518035452 (1)](https://user-images.githubusercontent.com/25460485/150267078-ca49a421-04b1-4fa0-a85c-c55300c3a4e8.png)
![1553518035452](https://user-images.githubusercontent.com/25460485/150267081-69e811c9-8142-466b-b0c9-9e7ba41fe970.png)
![1553518044798 (1)](https://user-images.githubusercontent.com/25460485/150267083-b1d5822e-3450-4924-b468-933cc71e45a6.png)
![1553518044798](https://user-images.githubusercontent.com/25460485/150267086-48f48907-f228-4d19-914a-61ea5134e059.png)
![1553518060979 (1)](https://user-images.githubusercontent.com/25460485/150267088-a62871a5-137e-49dc-bdd1-73183317ff98.png)
![1553518060979](https://user-images.githubusercontent.com/25460485/150267089-fc1ec44c-2a20-45ee-a2ef-11710da379af.png)
关注【程序代做 源码分享】回复【智能会议室】获取免费源码！！！![1111111](https://user-images.githubusercontent.com/25460485/150267100-85dc6975-f0ea-4ff8-a362-29e60277d80e.jpg)



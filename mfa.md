

## 登录保护

UCloud提供免费的基于TOTP（Time-Based One-Time Password
Algorithm）登录二次认证服务，开通本服务后，用户每次登录账号均需通过授权认证。
固定的账号密码容易泄漏，为了降低用户账号密码泄漏造成的风险，建议您开通账号登录二次认证。

### 开通条件

1.  开通对象为独立主账号或子账号
2.  移动设备上安装有UCloud APP或其他基于TOTP技术的令牌工具（推荐使用 UCloud APP）

### 如何开通

1\. 登录并进入个人中心-账号安全，点击开启登录保护
<img width="1384" alt="image" src="https://user-images.githubusercontent.com/107971405/220557616-73c985c8-36a6-4683-86ef-e2d4dddc6d15.png">


2\. 检查移动设备上是否安装UCloud APP。页面提供IOS和Android用户下载二维码，若您未安装，可通过扫码下载。
<img width="836" alt="image" src="https://user-images.githubusercontent.com/107971405/220557737-8d685e61-31eb-4504-aede-55f55870ffe0.png">

3\. 安装好后，打开UCloud APP，点击TOTP验证器，扫码添加获取授权码，也可以通过手动输入账号密钥获取授权码。
<img width="663" alt="image" src="https://user-images.githubusercontent.com/107971405/220559237-11773284-0ebf-485b-b812-6ce1f617ca23.png">

4\. 在页面方框内输入获取到的授权码，校验正确即完成绑定。温馨提示：以防设备更换导致密钥丢失，做好密钥备份。
<img width="790" alt="image" src="https://user-images.githubusercontent.com/107971405/220559517-ab4986df-4cea-4d7f-9307-80cc446030f9.png">
<img width="1376" alt="image" src="https://user-images.githubusercontent.com/107971405/220560326-ac247483-ec52-46d5-8e23-7170d8579654.png">


### 如何关闭

1\. 进入用户中心-账号安全，点击关闭登录保护

2\. 按照页面提示获取并输入授权码即可
<img width="1058" alt="image" src="https://user-images.githubusercontent.com/107971405/220560426-ddb65572-3e24-4f8d-aa49-4c1282dfa661.png">

### 功能应用

二次认证服务开通后，当您用账号密码登录UCloud时，会要求您输入认证码。系统判断认证码有效方可获得访问授权  
<img width="557" alt="image" src="https://user-images.githubusercontent.com/107971405/220560503-3f0a70a4-8961-4abc-b972-8cff438ef5f4.png">


### FAQ

Q：UCloud APP无法扫描获取授权码怎么办？  
A：您可以切换到手动获取，然后手动输入账号密钥绑定并获取授权码

Q：是否可以用其他工具绑定账号？  
A：可以用基于TOTP算法的其他动态令牌工具绑定账号，如Google Authoriticator、FortiToken、微信小程序“二次验证码”等。但为安全起见，推荐使用UCloud APP

Q：同一个账号是否支持绑定多个终端工具？  
A：支持。您只需要使用多个终端绑定同一账号（扫码或输入密钥）即可。建议您在绑定工具时妥善保存系统提供的密钥，方便后续添加绑定新的终端

Q：工具和密钥都丢了无法登录怎么办？  
A：这种情况您可以通过联系技术支持获取帮助

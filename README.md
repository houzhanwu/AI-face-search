# AI-face-search
调用百度AI人脸识别APi，完成用户上传图片并检测的流程

### 使用说明


1. 需要在百度开发则平台注册
2. 开通AI版块中的人脸识别
3. 创建应用，获取AppID、token等信息
4. 创建一个用户集，并上传他们的脸部照片
5. 代码部分


### 本应用功能说明：
### 	用户上传一张自拍照至服务器，后端将此照片通过百度SDK提供的接口，和上述步骤4中你上传的该用户的头像进行比对判断，可以校验出此用户是否是你设置的用户集中的成员。

### 其实打卡签到、门禁管理，也都是这个相似的流程。

### 别忘了npm install 安装依赖模块
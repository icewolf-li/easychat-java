## 全局公共参数
#### 全局Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 全局Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 全局Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 全局认证方式
```text
noauth
```
#### 全局预执行脚本
```javascript
暂无预执行脚本
```
#### 全局后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat
```text
暂无描述
```
#### Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/登录注册
```text
暂无描述
```
#### Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/登录注册/获取验证码
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/account/checkCode

#### 请求方式
> POST

#### Content-Type
> none

#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/登录注册/注册
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/account/register

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
checkCodeKey | - | String | 是 | 验证码Key
email | - | String | 是 | 邮箱
password | - | String | 是 | 密码
nickName | - | String | 是 | 昵称
checkCode | - | String | 是 | 图片验证码
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/登录注册/登录
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/account/login

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
checkCodeKey | - | String | 是 | 验证码Key
email | - | String | 是 | 邮箱
password | - | String | 是 | 密码
checkCode | - | String | 是 | 图片验证码
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/登录注册/获取系统设置
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/account/getSysSetting

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Header参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
token | - | String | 是 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人
```text
暂无描述
```
#### Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/创建群组
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/saveGroup

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Header参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
token | - | String | 是 | -
#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
groupId | - | String | 否 | 群组ID
groupName | - | String | 是 | 群组名称
groupNotice | - | String | 否 | 群组公告
joinType | - | Integer | 是 | 加入类型
avatarFile | - | String | 是 | 头像文件
avatarCover | - | String | 是 | 头像封面，缩略图
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/获取我创建的群组
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/loadMyGroup

#### 请求方式
> POST

#### Content-Type
> none

#### 请求Header参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
token | - | String | 是 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/获取群聊详情
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/getGroupInfo

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Header参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
token | - | String | 是 | -
#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
groupId | - | String | 是 | 群组ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/获取聊天会话群聊详情
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/getGroupInfo4Chat

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
groupId | - | String | 是 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/退群
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/leaveGroup

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Header参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
token | - | String | 是 | -
#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
groupId | - | String | 是 | 群组ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/解散群聊
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/dissolutionGroup

#### 请求方式
> POST

#### Content-Type
> none

#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/添加或者移除人员
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/addOrRemoveGroupUser

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
groupId | - | String | 是 | 群组ID
selectContacts | - | String | 是 | 选择的联系人
opType | - | String | 是 | 操作类型 0:移除 1:增加
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/搜索好友或者群聊
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/search

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
contactId | - | String | 是 | 联系人ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/申请好友或者入群申请
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/applyAdd

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
contactId | - | String | 是 | 联系人ID
contactType | - | String | 是 | 联系人类型 0:好友 1:群组
applyInfo | - | String | 否 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/获取好友申请列表
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/loadApply

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
pageNo | - | Number | 是 | 页码
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/处理联系人申请
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/group/dealWithApply

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
applyId | - | String | 是 | 申请ID
status | - | String | 是 | 处理状态 1:同意 2:拒绝 3:拉黑
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/获取联系人列表
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/contact/loadContact

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
contactType | - | String | 是 | 联系人类型 0:好友 1:群组
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/获取联系人详情
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/contact/getContactInfo

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
contactId | - | String | 是 | 联系人ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/删除联系人
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/contact/delContact

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
contactId | - | String | 是 | 联系人ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/联系人/拉黑联系人
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/contact/addContact2BlackList

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
contactId | - | String | 是 | 联系人ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/用户信息
```text
暂无描述
```
#### Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/用户信息/获取用户信息
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/userInfo/getUserInfo

#### 请求方式
> POST

#### Content-Type
> none

#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/用户信息/保存用户信息
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/userInfo/saveUserInfo

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
avatarFile | - | String | 是 | 头像
avatarCover | - | String | 是 | 头像封面
nickName | - | String | 是 | 昵称
joinType | - | String | 是 | 加我的方式
sex | - | String | 是 | 性别
personalSignature | - | String | 是 | 个性签名
areaCode | - | String | 是 | 地区编号
areaName | - | String | 是 | 地区名称
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/用户信息/修改密码
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/userInfo/updatePassword

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
password | - | String | 是 | 密码
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/用户信息/退出登录
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/userInfo/logout

#### 请求方式
> POST

#### Content-Type
> none

#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/聊天
```text
暂无描述
```
#### Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/聊天/发送消息
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/chat/sendMessage

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
contactId | - | String | 是 | 联系人ID
messageContent | - | String | 是 | 消息内容
messageType | - | String | 是 | 消息类型
fileSize | - | String | 是 | 文件大小
fileName | - | String | 是 | 文件名
fileType | - | String | 是 | 文件类型
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/聊天/上传文件
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/chat/uploadFile

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
messageId | - | String | 是 | 消息ID
file | - | String | 是 | 文件
cover | - | String | 是 | 封面
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/聊天/下载文件
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/chat/downloadFile

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
fileId | - | String | 是 | 文件ID
showCover | - | Boolean | 是 | 展示封面
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台
```text
暂无描述
```
#### Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/获取用户列表
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/admin/loadUser

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
pageNo | - | String | 是 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/更新用户状态
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/admin/updateUserStatus

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
status | - | String | 是 | 状态
userId | - | String | 是 | 用户ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/强制下线
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/admin/forceOffLine

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
userId | - | String | 是 | 用户ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/所有群组
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/admin/loadGroup

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
pageNo | - | String | 是 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/解散群组
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/admin/dissolutionGroup

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
groupId | - | String | 是 | 群组ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/保存系统设置
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/admin/saveSysSetting

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
robotFile | - | String | 是 | 机器人头像
robotCover | - | String | 是 | 机器人头像封面
maxGroupCount | - | String | 是 | 最大群组数
maxGroupMemberCount | - | String | 是 | 群员最大数
maxImageSize | - | String | 是 | 图片最大限制
maxVideoSize | - | String | 是 | 视频最大限制
maxFileSize | - | String | 是 | 文件最大限制
robotNickName | - | String | 是 | 机器人名称
robotWelcome | - | String | 是 | 注册欢迎语
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/获取系统设置
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/api/admin/getSysSetting

#### 请求方式
> POST

#### Content-Type
> form-data

#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/获取更新列表
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/admin/loadUpdateList

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
pageNo | - | String | 是 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/保存更新
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/admin/saveUpdate

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
version | - | String | 是 | 版本号
updateDesc | - | String | 是 | 更新内容
fileType | - | String | 是 | 文件类型
outerLink | - | String | 是 | 外部连接地址
file | - | String | 是 | 文件
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/删除更新
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/admin/delUpdate

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
id | - | String | 是 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/发布更新
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/admin/postUpdate

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
id | - | String | 是 | 更新ID
status | - | String | 是 | 状态
grayscaleUid | - | String | 是 | 会都UID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/靓号列表
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/admin/loadBeautyAccountList

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
pageNo | - | String | 是 | -
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/保存靓号
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/admin/saveBeautAccount

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
email | - | String | 是 | 邮箱
userId | - | String | 是 | 用户ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/删除靓号
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/admin/delBeautAccount

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
id | - | String | 是 | 更新ID
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /EasyChat/管理后台/检测更新
```text
暂无描述
```
#### 接口状态
> 已完成

#### 接口URL
> http://192.168.0.110:5050/admin/update/checkVersion

#### 请求方式
> POST

#### Content-Type
> form-data

#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
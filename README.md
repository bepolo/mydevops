

# mydevops

前端基于vue,后端python fastapi写的devops开箱即用<br/><br/>
只需选择cmdb节点,即可部署所有应用,全程自动化<br/>
集成cmdb,服务,cicd 打包，部署,常用应用部署，网关集成，域名证书绑定，sql系统，工单系统

# 主要功能：<br/>
![image](https://user-images.githubusercontent.com/97171025/150680436-b793dc07-9ed3-4d32-b0e0-b0edc5c2b006.png)<br/>
![image](https://user-images.githubusercontent.com/97171025/150680468-73af152f-f801-4645-b666-2bea63c83d83.png)<br/>


# 基础功能：<br/>
1.用户管理<br/>
2.角色<br/>
3.权限<br/>
4.菜单<br/>
5.日志<br/>

![image](https://user-images.githubusercontent.com/97171025/150096390-c9461c45-6360-4b50-ad5f-c924ba932390.png)<br/>
<br/>


# cmdb：<br/>
列表以及服务检测<br/>
![image](https://user-images.githubusercontent.com/97171025/150096854-ffa96ec6-2f92-4ead-bf7b-b4d9fc291827.png)<br/>

服务管理<br/>
![image](https://user-images.githubusercontent.com/97171025/150097030-fef25871-c863-448f-89c1-04b23b420118.png)<br/>
单实例链接<br/>
![image](https://user-images.githubusercontent.com/97171025/150097258-3680c6a2-4900-4a3c-9f61-2ba7e69b6892.png)<br/>
多实例链接<br/>
![image](https://user-images.githubusercontent.com/97171025/150097384-48a1b2c7-5d49-4324-9873-aaf7c7a4e5ea.png)<br/>

# 应用部署：<br/>
# 服务中心,日常的java php go python应用部署<br/>
列表展示服务 端口 状态 以及镜像<br/>
![image](https://user-images.githubusercontent.com/97171025/150536548-a1e61636-4d5f-4133-b05d-e9e96a5b47e9.png)<br/>
服务打包配置(全局加密配置):<br/>
![image](https://user-images.githubusercontent.com/97171025/150536897-220d755b-3280-46ee-a77a-32488bcc8df3.png)<br/>
服务编辑<br/> 重要密码由{--变量代替--}<br/>
![image](https://user-images.githubusercontent.com/97171025/150098345-7eea64b9-9114-432f-939f-398dbe51ca29.png)<br/>
全局变量中心<br/>
![image](https://user-images.githubusercontent.com/97171025/150098678-9ae28468-24aa-4b4a-b1f7-04f0a0bec516.png)<br/>
服务打包<br/>
![image](https://user-images.githubusercontent.com/97171025/150537072-c97a109e-f174-47ac-8738-e5211089505a.png)<br/>
![image](https://user-images.githubusercontent.com/97171025/150680890-38128fed-cd2c-4120-8b3f-4a76903d6d36.png)<br/>

<br/>


填入版本号进行部署即可,已做好滚动发布，发布失败自动回退<br/>
myfastapi 1.2发布成1.1<br/>
![image](https://user-images.githubusercontent.com/97171025/150682000-020f3f7d-d13f-44ed-85c0-e92d2e660f3b.png)<br/>
![image](https://user-images.githubusercontent.com/97171025/150682052-b6541073-02b8-4ba8-9508-6712d453e3a8.png)<br/>


<br/>

## 直接发布新版本,旧版本服务会逐步替换，即使单机也全量发布，服务不受任何影响，<br/>
## 可以轻松发加愉快的执行上百个应用同时布<br/>


# 应用中心,日常的mysql prometheus,gitlab,jenkins,kafka等等内置部署<br/>
![image](https://user-images.githubusercontent.com/97171025/150100372-d96b360d-0473-4620-97f5-51a658fd2c5b.png)<br/>
点击图标进入编辑以及修改页面：<br/>
重要信息用全局变量代替<br/>
![image](https://user-images.githubusercontent.com/97171025/150100658-b450582c-beb5-4814-8e8c-e8696c186d05.png)<br/>
选择节点，以及配置文件绑定,部署中的目录会自动在目标服务器创建好<br/>
![image](https://user-images.githubusercontent.com/97171025/150100806-c0c9c64e-5d97-436b-9878-87fadfc9f232.png)<br/>
在部署中可以随便在目标机器执行命令：<br/>
![image](https://user-images.githubusercontent.com/97171025/150101272-4ff99c6a-ae82-4c4f-add6-f4c57c72e79a.png)<br/>
部署：<br/>
![image](https://user-images.githubusercontent.com/97171025/150101457-e71aad0f-af01-4ccc-9a5d-3df96cdaf485.png)<br/>



# 网关域名证书<br/>
网关列表<br/>
![image](https://user-images.githubusercontent.com/97171025/150680533-8c35197e-d4a4-4713-8af0-e79df784a343.png)<br/>
<br/>
域名列表<br/><br/>
![image](https://user-images.githubusercontent.com/97171025/150680553-c7fe7714-daf5-4836-9d0e-e4be67380de9.png)<br/>
添加修改证书<br/><br/>
![image](https://user-images.githubusercontent.com/97171025/150680601-8c655c65-df9d-4b9a-a1cf-29ff12160b51.png)<br/>
域名绑定网关和服务<br/><br/>
## 支持成百上万和域名同时绑定,动态绑定，不受任何限制<br/>
![image](https://user-images.githubusercontent.com/97171025/150680648-c4d7c144-3ad0-4214-b6e3-4eb6cee57cc8.png)<br/>
实时策略<br/><br/>
![image](https://user-images.githubusercontent.com/97171025/150686400-91c5f369-36b6-4696-935d-71ae3c907b6b.png)<br/>


全程添加域名 选择网关 绑定服务即可，已做好解析以及证书绑定<br/>
只需要加入hosts或者外网解析或者CDN即可<br/>
## 后端某服务节点挂掉会自动下线,不影响整个服务<br/>

![image](https://user-images.githubusercontent.com/97171025/150680698-88bb3f1c-c088-4904-8e80-38f1cb58e717.png)<br/>
![image](https://user-images.githubusercontent.com/97171025/150680772-436078a3-18a9-4897-b8c5-59b4f6f3ac98.png)<br/>
![image](https://user-images.githubusercontent.com/97171025/150680748-507308f7-cdf9-4160-9e76-47784254725a.png)<br/>


隐私全局变量<br/>
![image](https://user-images.githubusercontent.com/97171025/150101830-82727824-3e18-4128-a70d-046bebc26895.png)<br/>



# 配置文件集中管理,以及隐私变量<br/>
![image](https://user-images.githubusercontent.com/97171025/150101667-e900c3c6-d35d-4c65-ade2-a4169eccc3c3.png)<br/>
<br/>
![image](https://user-images.githubusercontent.com/97171025/150101753-158b8798-7820-4fc7-8fd2-9a814ffa0a52.png)<br/>
隐私全局变量<br/>
![image](https://user-images.githubusercontent.com/97171025/150101830-82727824-3e18-4128-a70d-046bebc26895.png)<br/>


正在开发功能：定时任务 管理 分发
TODO：
工单系统 mysql管理 redis管理。。。









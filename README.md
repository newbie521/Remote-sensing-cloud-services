<a name="ztcno"></a>
## 一、遥感云服务项目介绍![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/1.png)
我们是来自中国矿业大学的计算机学生，该项目是来自《第十一届中国软件杯大学生软件设计大赛》中的《A4-基于百度飞桨的遥感图像智能解译平台》赛道。
<a name="fBhgi"></a>
### 1. 遥感云服务官网
[http://icloud.mua5201314.com/](http://icloud.mua5201314.com/)
```json
手机号：19852128280
密码：dssd
```
<a name="fT51S"></a>
### 2. 遥感云服务后端管理系统
[http://master.newbies.top/](http://master.newbies.top/)
```json
手机号：admin
密码：admin123
```
<a name="BA8ld"></a>
## 二、功能介绍
<a name="d9FCK"></a>
### 2.1 用户功能

- 用户手机短信注册
- 用户登录
- 用户退出
- 用户信息更新
- 用户手机短信改密
- 用户忘记密码
<a name="eAB2a"></a>
### 2.2 图像检测功能

- 变化检测
- 目标提取
- 目标检测
- 地物分类
<a name="edghT"></a>
### 2.3 历史记录（按量请求）

- 变化检测记录
- 目标提取记录
- 目标检测记录
- 地物分类记录
<a name="K4cfv"></a>
### 2.4 公开接口文档

- 变化检测api文档
- 目标提取api文档
- 目标检测api文档
- 地物分类api文档
<a name="yzDEW"></a>
## 三、界面详情
<a name="lRcgy"></a>
### 3.1 登录以及注册
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/2.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/3.png)
<a name="A2UjP"></a>
### 3.2 主页

- 可供选择英文或中文
- 是否全屏
- 明亮或暗黑模式
- 页面配置
- 最上方是各个图像检测凭条总调用次数
- 接下来是总调用数据图
- 以及各个图像检测调用记录的相关数据
- 快捷操作
- 最近访问
- 效果图轮播
- 公告
- 帮助文档

![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/4.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/5.png)
<a name="zpMYE"></a>
### 3.3 变化检测
> 用户自定义请求方式以及颜色
> 请求方式：掩膜、轮廓
> 颜色：根据用户爱好选择我们设定的经典颜色

![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/6.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/7.png)
<a name="zNyvz"></a>
### 3.4 目标提取
> 用户自定义请求方式以及颜色
> 请求方式：掩膜、轮廓
> 颜色：根据用户爱好选择我们设定的经典颜色

![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/8.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/9.png)
<a name="FSP0l"></a>
### 3.5 目标检测
> 用户自定义请求方式以及颜色
> 请求方式：掩膜、轮廓
> 颜色：根据用户爱好选择我们设定的经典颜色

<a name="WMt98"></a>
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/10.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/11.png)
<a name="JXxxV"></a>
### 3.6 地物分类
> 用户自定义请求方式以及颜色
> 请求方式：掩膜
> 颜色：根据用户爱好选择我们设定的经典颜色

![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/12.png)
<a name="ktv6W"></a>
### 3.7 公开接口文档
> 公开四个图像接口的API接口，供开发者调用，学习使用

![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/13.png)
<a name="hL58w"></a>
### 3.8 个人中心
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/14.png)
<a name="dkTNa"></a>
### 3.9 历史记录
> 四个图像检测历史记录，按照时间顺序以及设定数量请求

![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/15.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/16.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/17.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/18.png)
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/19.png)
<a name="vwlI9"></a>
### 3.10 我的额度
:::info
注册时为每个用户初始化1000次调用次数
:::
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/20.png)
<a name="Nh6u7"></a>
### 3.11 用户近十天调用数据图
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/21.png)
<a name="Ef1jq"></a>
## 四、开发
<a name="IQXtl"></a>
### 4.1 软件整体功能
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/22.png)
<a name="fLLLA"></a>
### 4.2 项目系统架构图
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/23.png)
<a name="DUPSJ"></a>
### 4.3 部署技术架构图
:::info
由于模型运行对服务器要求较大，所以我们将模型通过flask部署在主机上面，通过内网穿透到公网上<br />这是后端部署技术架构
:::
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/24.png)
<a name="F8Ayd"></a>
## 五、遥感云服务后端管理系统
<a name="PihJj"></a>
### 5.1 登录
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/25.png)
<a name="ZF9U9"></a>
### 5.2 首页
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/26.png)

<a name="O641v"></a>
### 5.3 注册用户信息管理
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/27.png)
<a name="hS898"></a>
### 5.4 历史记录管理
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/28.png)
<a name="QVCcR"></a>
### 5.5 内嵌后端接口文档
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/29.png)
<a name="WmZIa"></a>
### 5.6 内嵌官网预览
![image.png](https://github.com/newbie521/Remote-sensing-cloud-services/blob/main/image/30.png)

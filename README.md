# 模拟训练环境 - Mysql版

## 项目介绍

模拟训练环境是一款 java + vue 的前后端分离的学习、训练、考核系统。主要优点是开发、部署简单快捷、界面设计友好、代码结构清晰。模拟训练环境作为新一代网络教育平台，提供在线学习、模拟训练、能力自评、认证考核为一体的教学服务，使学员的岗位能力胜任日常工作需要。
支持多种部署方式：集成部署、前后端分离部署、docker部署。

### 特点

* 面向岗位能力的在线学习平台：

    核心点是增长知识，提升学习需求，建设岗位能力培训体系，制定岗位能力学习规划，测试学习效果。增加学员学习的积极性并塑造良好的学习氛围。

* 完全仿真的模拟训练平台：

    核心点是培养能力，研制满足岗位能力提升学习需求的模拟训练平台，提供相关应用软件操作的模拟环境。

* 完善的岗位能力评估平台：

    核心点是岗位知识及能力评估，以综合考核的方式对岗位任职能力进行评估，并形成评估报告和学习建议反馈。


### 演示地址

* 学员端：<http://student.lwuchang.com>

    账号：xueyuantest 密码：123456
* 管理端：<http://admin.lwuchang.com>  

    账号：admintest 密码：123456
 
### 相关文档

* 用户手册：[http://file.lwuchang.com/github-pic/模拟训练环境用户手册.docx](http://file.lwuchang.com/github-pic/模拟训练环境用户手册.docx)
* 系统介绍：[http://file.lwuchang.com/github-pic/模拟训练环境.pptx](http://file.lwuchang.com/github-pic/模拟训练环境.pptx)

### 联系我们

* 商务QQ：`664744730`
* 商务微信：`wuchang001`
* 商务邮箱：`664744730@qq.com`
* 商务电话：`17317272120`

### 仓库版本地址

* github - mysql ：[https://github.com/taichengkeji/mnxl-mysql](https://github.com/taichengkeji/mnxl-mysql)

### 学生系统功能

|  模块   | 介绍  |
|  ----  | ----  |
| 登录  | 用户名、密码  |  
| 首页  | 任务中心、课程学习、模拟训练、试卷中心  |  
| 课程学习  | 主要分为课程管理、学员学习和课程分析三个业务阶段。  |  
| 辅助资料  | 主要是用于向学员提供标准化、集成化、高效化、可扩展、交互式的辅助资源库。  |  
| 经验交流  | 为学员提供知识交流、技术交流、经验交流的平台。另外，也提供平台使用服务保障等。  |  
| 模拟练习  | 向用户提供其他信息系统真实环境同样的功能，用户可在其上进行任意操作，操作的反馈跟现有的其他信息系统一样。  |  
| 案例实操  | 在模拟练习子系统的基础上，结合学员自身所从事的业务，选择实操案例场景，根据实操案例场景的指导进行操作，其目的在于使学员充分了解如何使用其他信息系统办理具体的业务  |  
| 协同演练  | 主要用于针对多个用户完成某个具体业务所要协同进行的一系列标准操作序列，这种协同包括同单位间不同角色的协同，上下级单位同一角色不同用户间的协同，平级不同单位间不同用户间的协同。  |  
| 能力自评  | 向用户提供功能完善操作简洁的考试系统，教员可以使用系统自动组卷。学员可在能力自评中找到适合自己的试卷自由进行考试，对自己的能力进行测评。  |    
| 认证考核  | 主要实现人工精心组织试题，交由专业人员进行审核，审核通过才可作为一期的认证考试试卷。考核要求学员在一定时间内完成试卷的解答。考核通过后，系统会自动生成对应的证书，证书可导出可打印。  |   
| 考试记录  | 查看答卷记录和试卷信息  |    
| 证书记录  | 通过考核获得的证书  |  
| 固定试卷  | 可重复练习、自行批改的试卷  |    
| 时段试卷  | 在时间限制内，可重复练习、自行批改的试卷  |    
| 错题本  | 答错题目会自动进入错题本，显示题目基本信息  |    
| 个人信息  | 显示学生个人资料  |  
| 更新信息  | 修改个人资料、头像  |    
| 消息中心  | 用于接收系统发送的消息  |  
| 我的学习  | 收藏的课程、我的笔记、观看记录等  |  
| 我的资源  | 上传的资源、收藏的资源、浏览的资源、评论的资源等  |  

### 管理系统功能

|  模块   | 介绍  |
|  ----  | ----  |
| 登录  | 用户名、密码  |  
| 主页  | 试卷总数、题目总数、用户活跃度、题目月数量  |  
| 专业列表  | 显示系统所有的专业，新增、修改、删除  |  
| 岗位列表  | 显示系统所有的岗位，新增、修改、删除  | 
| 岗位能力列表  | 显示系统所有的岗位能力，新增、修改、删除  |
| 课程列表  | 显示系统所有的课程，新增、修改、删除  | 
| 业务系统列表  | 显示系统所有的业务系统，新增、修改、删除  |  
| 班级列表  | 显示系统所有的班级，新增、修改、删除  |  
| 学员列表  | 显示系统所有的学员生，新增、修改、删除、禁用  | 
| 证书模板列表  | 显示系统所有的证书模板，新增、修改、删除  | 
| 资源版块  | 显示系统所有的资源板块，新增、修改、删除  |   
| 资源主题  | 显示系统所有的资源主题，新增、修改、删除  |  
| 资料审核  | 显示系统所有的待审核资料，新增、修改、删除  |  
| 反馈管理  | 显示系统所有的资源反馈意见业，新增、修改、删除  |  
| 交流版块  | 显示系统所有的交流版块，新增、修改、删除  |  
| 交流主题  | 显示系统所有的交流主题，新增、修改、删除  |  
| 文章管理  | 显示系统所有的文章，新增、修改、删除、加精、置顶  |  
| 问答管理  | 显示系统所有的问答，新增、修改、删除、加精、置顶  |  
| 标签管理  | 显示系统所有的标签，新增、修改、删除  |  
| 案例模板  | 显示系统所有的案例模板，新增、修改、删除、内容管理  |  
| 案例列表  | 显示系统所有的实操案例，新增、修改、删除、答案、录屏、回放  |  
| 案例发布  | 显示系统所有的实操案例，发布、撤回  |  
| 模拟练习  | 显示系统所有的模拟练习环境，新增、修改、删除、添加账号、关联学员  |  
| 协同演练  | 显示系统所有的协同演练环境，新增、修改、删除、添加账号、关联学员  |  
| 题目列表  | 题目查询、修改、删除  |  
| 题目创建  | 题目支持单选题、多选题、判断题、填空题、简答题、模拟训练题，题干支持文本、图片、表格、数学公式  | 
| 试卷列表  | 试卷查询、修改、删除  |  
| 试卷创编  | 创建的试卷为时段试卷、固定试卷、任务试卷  |  
| 人工组卷  | 试卷查询、修改、删除  | 
| 智能组卷  | 试卷查询、修改、删除  | 
| 任务列表  | 任务查询、修改、删除  |  
| 答卷列表  | 批改、分析、证书  |  
| 管理员列表  | 显示系统所有的管理员，新增、修改、删除、禁用  |  
| 角色列表  | 角色查询、修改、删除、授权  |  
| 菜单列表  | 菜单查询、添加、修改、删除  |  
| 消息列表  | 显示已发送的消息，消息已读人数等信息  |  
| 消息发送  | 发送消息给多个用户  |  
| 用户日志  | 显示所有用户日志  |  
| 禁词管理  | 禁词查询、添加、修改、删除  |  
| 黑名单管理  | 禁用ip查询、添加、修改、删除  |  
| 个人资料  | 显示管理员用户名、真实姓名  |  
| 时间线  | 显示管理员创建时间  |  
| 修改资料  | 修改姓名、手机号  |  

### 关键技术

* 构建基于异构系统的模拟训练题库：

    采用仿真模板来模拟仿真原有系统，将原有系统界面的元素和操作以仿真模板的形式进行模拟，通过HTML+CSS+JS仿真模拟原系统。
* 实现模拟训练题的录制与自动评分：

    浏览器的MutationObserver API是实现页面录制和回放的关键点。同时需要注意MutationObserver 是异步操作，需要在开始录制时进行一次全量快照的记录，并对DOM元素进行序列化保证DOM元素不会出现混乱的记录。
* 视频播放技术：

    课程视频播放采用分段式渐进下载（Progressive Downloading），就是将一个完整的视频文件，切分成小的片段，然后播放器通过HTTP一个一个的下载，再进行播放。
* 容器编排技术：

    采用Kubernetes 也简称为 k8s，它可以提供⽤户所需的容器部署，管理和扩缩容等编排功能。
	借助 Kubernetes 的编排功能，⽤户可以构建多个容器的应⽤服务，跨集群调度、扩展这些容器，并长期持续管理这些容器和检测健康状况 。
* 水印技术：

    使用css方式使水印上浮于所有元素上方，使用固定位置，使用不会被用户滚动页面时影响，水印的大小，透明度，密集程度也都在不断的调优，可以不占用服务器资源，完全依赖客户端的计算能力，减少服务端压力。响应速度快。
* 脚本录制技术：

    采用本地端口镜像技术，可将指定接口（镜像端口）的网络流量进行复制，发送给特定的接口（观察接口），用于数据分析。获取用户访问操作系统数据流，按时间片段的形式进行存储，将其中所有的操作、平台产生的所有资源、数据整合，生成数据包。将包内记录的所有数据流整合为标准模板。使用模板服务将标准模板进行解析，实现标准模板中数据流的还原，重现。

### 系统展示

* 学员练习系统
<table>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/stu/1.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/stu/2.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/stu/3.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/stu/4.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/stu/5.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/stu/6.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/stu/7.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/stu/8.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/stu/9.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/stu/10.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/stu/11.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/stu/12.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/stu/13.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/stu/14.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/stu/15.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/stu/16.png"/></td>
    </tr>
</table>

* 后台管理系统

<table>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/1.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/2.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/3.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/4.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/5.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/6.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/7.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/8.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/9.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/10.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/11.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/12.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/13.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/14.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/15.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/16.png"/></td>
    </tr>
    <tr>
        <td><img src="http://file.lwuchang.com/github-pic/adm/17.png"/></td>
        <td><img src="http://file.lwuchang.com/github-pic/adm/18.png"/></td>
    </tr>
</table>

### docker部署

* 打开地址<http://file.lwuchang.com/github-pic/docker.zip>下载部署包并解压，得到docker目录，里面有已配置好的文件
* 将整个docker目录中的文件，复制到/usr/local/mnxl下面
* 如果服务器没有安装docker-compose的话，进入到install目录，执行下面命令，安装docker-compose

	```
	cd /usr/local/mnxl/install
	mv docker-compose-linux-x86_64 /usr/local/bin/docker-compose
	chmod +x  /usr/local/bin/docker-compose
	docker-compose --version
	```
* 根据实际使用的服务器地址修改配置文件：  

    ①release/sdd文件夹下,abilityevaluation-server、view-server文件夹下hosts文件中：139.196.27.90  file.lwuchang.com，139.196.27.90改为部署服务器的地址  
    ②release/sdd文件夹下,dns-server文件夹下dnsmasq.conf文件中：address=/lwuchang.com/139.196.27.90，139.196.27.90改为部署服务器的地址  
    ③release/sdd文件夹下docker-compose.yml文件中：所有dns： 139.196.27.90， 139.196.27.90改为部署服务器的地址  
* 到release目录下执行 chmod -R 777 ./init.sh
* 在release目录下执行 ./init.sh

### 系统访问

* 把电脑的首选dns解析服务器设置为部署服务器地址

* 学生端访问地址为：<http://student.lwuchang.com/student>  

    账号：xueyuantest 密码：123456（学员）
* 管理员端访问地址为：<http://admin.lwuchang.com/admin>  

    账号：jiaoyuantest 密码：123456（教员）  
    账号：ziyuantest 密码：123456（资源管理员）  
    账号：admintest 密码：123456（平台管理员）  
    账号：shenhe 密码：123456（审核管理员）  

### 可能遇到的问题：

* 53端口被占用

    ①关闭linux本机dns解析，解除53端口占用
  
    ``` 
    systemctl stop  systemd-resolved.service
    ```  

    ②注释掉原本的解析服务器地址 127.0.0.53  

    ``` 
    vi /etc/resolv.conf
    ```  

    ③到mnxl/sdd下重启服务：  

    ``` 
    docker-compose restart
    ```  
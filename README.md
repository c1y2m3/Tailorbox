# Tailorbox🚀
读大师、学大师、成大师
##### 自动化生成平台

- 目前已有功能，根据实战磨练持续更新中....  

  上线生成
  
  权限维持

  常用工具

  辅助功能

  FscanOutput
  
# 更新记录🚀
1、全局函数/变量/常量/注释随机混淆，添加脏数据编译，尽可能减少特征被定位。

2、暂时用自定义typedef，GetProcAddress隐藏iat表，静态扫描优化，待改进。 

2022.12.6

1、修改母体exe编译时间、创建时间、修改时间和访问时间。 

2、把pyminizip替换成系统winrar加密文件名。 

3、修改像素和添加随机字节到icon，防止杀软针对ico md5特征定位。

2022.12.11

1、增加flash安装包生成功能，利用 inno setup 5进行打包iss文件。

2、使用MoveFileA隐藏任务管理器中的进程。

2023.2.1

1、新增email地址查询功能，调用的是全网爬以及过滤企查查的数据。

2023.2.12

1、新增白加黑dll转发功能，内置多种白文件自带dll签名。

2023.5.10

1、重写资源释放API，来降低落地程序的熵值,参考https://github.com/NUL0x4C/ManualRsrcDataFetching

2、随机抽取ico图标替换生成出来的可执行程序。

2023.9.10

1、更换前端UI模板,使用Pake打包成桌面 App，修改界面逻辑以便于多人操作。

2、新增fscan，HackBrowserData、FileSearch，SharpDecryptPwd等后渗透功能。

3、新增域前置网络准入下发功能，支持多种二开C2 beacon上线方式，接入到钉钉协同操作。

4、在线web解析fscan扫描结果，实现项目-》节点-》标签页展示。

5、重构原始loader,新增VEH、Ekko bypass内存查杀。

2023.9.23

1、钓鱼前端功能添加pdf、xlsx、docx选项，以及程序随机文件描述。

2、可执行程序绑定生成的唯一标识然后通过探测，后期容易识别分辨具体情况。

2023.10.12

1、实现自研c2前端在线生成，随机加密上线参数配置。

2、输出raw格式的shellcode，防止多人使用EXE被标记的全是特征。

##### 登录界面

![](https://c1y2m3.oss-cn-beijing.aliyuncs.com/Dingtalk_20230928104423.jpg)

##### 功能界面

![](https://c1y2m3.oss-cn-beijing.aliyuncs.com/_20231113210945.png)

##### 历史截图

![](https://raw.githubusercontent.com/c1y2m3/Tailorbox/main/images/start.png)

![](https://c1y2m3.oss-cn-beijing.aliyuncs.com/1670825719512-460cd223-1449-447d-90f4-dc5099abc6d7.gif)

![](https://raw.githubusercontent.com/c1y2m3/Tailorbox/main/images/dllhihack.png)

![](https://raw.githubusercontent.com/c1y2m3/Tailorbox/main/images/email.png)

##### References：

https://mp.weixin.qq.com/s/QZ5YlRZN47zne7vCzvUpJw

https://c1y2m3.github.io/c1y2m3.github.io/2020/07/09/mail/

https://c1y2m3.github.io/c1y2m3.github.io/2020/06/15/SSP/  

https://docs.microsoft.com/en-us/windows/win32/api/lmat/nf-lmat-netschedulejobadd  

......


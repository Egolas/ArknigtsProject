# 明日方舟挂机脚本
## 脚本介绍
__适合一般模拟器玩家使用 简单快捷__  
本脚本为明日方舟挂机脚本 基于python和abd编写 pyautogui图像识别 
目前的功能是自动挂机 可以自定义次数 但需手动选择关卡
>优点   
>__后台挂机 解放电脑__ 配置好后即可解放双手 无需切除窗口 可以用电脑干别的事  
>* 泛用性 模拟器和手机都可以使用 基本支持所有分辨率  
>* 简洁性 配置简单 下载即用  
>* 稳定性 挂机流程稳定 识别不出错  

>缺点  
>* 手机上识别速度慢 推荐在模拟器上使用(默认逍遥模拟器默认分辨率)  
>* 功能较少,不适合工作室  

## 如何使用
>配置文件  
>>打开文件里的**config.ini**
>>```
>>[main]       
>>Apath="/sdcard"  
>>模拟器存储地址                
>>pausetime=3  
>>点击后的间隔时间        
>>ip="127.0.0.1:21503"  
>>模拟器的端口地址         
>>c=0.7  
>>图片识别率  
>>is=1280X720  
>>分辨率,此分辨率为逍遥模拟器的默认分辨率  
>>```
>>* 模拟器存储地址为安卓系统内的路径 可任意 一般模拟器默认即可  
>>* 图片识别率默认即可 如果出现图片无法识别的情况 可降低
>>* 分辨率目前只支持1280x720 想用别的分辨率的话可以按照原文件夹里图片的名字截图 并在配置文件中修改**is**的值
>>* ip为模拟器虚拟端口ip 不知道的可以百度对应**模拟器端号**  
>>* 网易mumu模拟器内需将模拟器安装目录内的abdserver改名为abd.exe  
>
>开始挂机
>>打开明日方舟 选择关卡后 打开start.bat即可使用

## 分辨率问题
>**目前不同分辨的图包只有一种 希望有志之士能帮忙截下图 完成脚本的开发**

## 更新记录
***未来更新预计：更新自动收取基建 规划刷材料 加入GUI***
>Beta版
>>Ver1.0  可以自定义次数 修改配置文件  
>>Ver1.1 可以修改分辨率 分辨率图包需要自己提交  
>>ver1.2 连接错误识别 当前分辨率可以匹配 图标识别改为列表式  
>>ver1.3 优化代码 图片识别速度更快
   



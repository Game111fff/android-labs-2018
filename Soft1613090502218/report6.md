# 第六次实验报告
## 实验目标
### 理解XML和JSON表示数据的方法。。
### 1、在个人目录中创建一个表示数据的XML或JSON文件；
### 2、数据文件代码提交之后从GitHub获取文件URL；
### 3、在应用中通过网络编程访问GitHub的数据文件；
### 4、在应用中解析并显示文件所包含的数据；
### 5、将应用运行结果截图
## 实验步骤
### 1、在Androidmanifest.xml中使该app可以进行联网
### 2、创建一个类用来连接url得到json的数据
### 3、创建一个用来解析json的数据的类，这里使用了gson来进行解析
### 4、在Playing.java中加一个按钮使其可以跳转到可以查看网上十个玩家名与得分的activity中
### 5、定义个类Player将playername和playscore包装起来
### 6、新建上述显示的activity，在里面引用得到json与解析json的方法，并且不调用数据库
### 7、把运行结果与代码git push到GitHub
## 实验结果
### ![image](https://github.com/ChenYHeng/android-labs-2018/blob/master/Soft1613090502218/r61.png)
## 实验体会
### 这一次主要是参考了同学的代码才开始懂json是用来干什么的，并且让我学到了HttpUrlConnection的使用方法。
### 不过最让我头痛的是原来app是要在androidmanifest中授权，使其可以联网，当时还不知道，导致程序整天都会出现联网错误，因此上网查到了是有这样的错误，这样才知道原来老师给出来AndroidManifest中的代码是授权联网用的。
### 项目说明 ###
* 利用github action实现定时自动运行api调用，保持E5开发活跃。
* 免费，不需要服务器，部署完不用管啦（应该是吧）。

### 特别说明/Thanks ###
* 原教程博主-黑幕（酷安id-Paran）：https://blog.432100.xyz/index.php/archives/50/

### 步骤 ###
1，新建一个repository/项目
  ![image](https://github.com/wangziyingwen/Autoapi-test/blob/master/images/新建仓库.png)

2，下载上面的1.py , 根据原文教程修改1.py、1.txt ，上传并复制代码地址

  ![image](https://github.com/wangziyingwen/Autoapi-test/blob/master/images/代码地址.png)
  
3，点击右上角fork我的代码到自己仓库，

  ![image](https://github.com/wangziyingwen/Autoapi-test/blob/master/images/fork.png)
  
  然后修改文件 .github\workflows\autoaapi.yml 中的代码地址为自己的地址
  
  ![image](https://github.com/wangziyingwen/Autoapi-test/blob/master/images/修改地方.png)
  
4，搞定，我设定的是一天两次，每次调用3轮（点击右上角星星也可以立马调用一次），你们可以自己修改：

   定时修改
   
   ![image](https://github.com/wangziyingwen/Autoapi-test/blob/master/images/定时.png)
   
   每次轮数（在1.py最后面）
   
   ![image](https://github.com/wangziyingwen/Autoapi-test/blob/master/images/次数.png)
   
   点击上面的Action就能看到每次的运行日志
   
   ![image](https://github.com/wangziyingwen/Autoapi-test/blob/master/images/日志.png)
   

## 最后 ##
  我是代码小白，我实在不会把两个项目合并啊，只能分开弄两个项目，一个原代码，一个action流程，请各位多多包涵。有没有大佬能修改一下代码呀，十分欢迎！
  这个项目都是我根据以往看过的代码整合的，ORZ。
  有修改建议可以发邮件给我:
  wz.lxh@outlook.com
  基安id-卷腿毛菌

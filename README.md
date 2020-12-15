# gitlabCodeStatistics
js统计gitlab代码数量、提交次数、合并次数
## 使用方法
1、配置：在bak.json里配置你的pravate_token（获取方法见https://blog.csdn.net/zangxueyuan88/article/details/81195666）   ，提交代码的邮箱地址、分支和工程id，打开demo.html就可以了    
2、温馨提示：页面上可以配置忽略多少行以上的代码（因为创建工程时候会有大量的复制粘贴非原创代码计算在内，排除了之后就跟接近真实的代码数量）    
## 说明
前端JS代码写成的，基本上用的是原生的js代码，只有请求部分用了jq（已集成到页面），有兴趣者可以把请求也用原生js来写，文件的体积就会大大减小，无需额外引用其他资源。    
# 界面如下：
![image](https://github.com/cdacai/gitlabCodeStatistics/blob/main/model.png)



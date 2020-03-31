[zookkeeper--已看](https://edu.aliyun.com/lesson_1343_11455?spm=5176.8764728.0.0.220f9148HKsOK5#_11455)

### kafka

[kafka](https://edu.aliyun.com/lesson_1807_15412?spm=5176.10731542.0.0.4af62356MQERgO#_15412)



### 数据库

[大表表结构修改](https://segmentfault.com/a/1190000014924677?utm_source=tag-newest)

### redis

redis-cli -h 10.17.29.176 -c -p 16439  集群模式连

[Redisson是架设在redis基础上的一个Java驻内存数据网格]([https://github.com/redisson/redisson/wiki/Redisson%E9%A1%B9%E7%9B%AE%E4%BB%8B%E7%BB%8D](https://github.com/redisson/redisson/wiki/Redisson项目介绍))

### 远程调试

-Xdebug -Xrunjdwp:transport=dt_socket,address=80,server=y,suspend=n

https://cf.jd.com/pages/viewpage.action?pageId=258010292

### DUBBO

https://blog.csdn.net/lkforce/article/details/78544120

### 分享

[OFC](https://www.jianshu.com/p/019f4424c6b5)

[订单流程](https://cf.jd.com/pages/viewpage.action?pageId=29530441&showComments=true)

### LINUX

[oom-kill](https://www.vpsee.com/2013/10/how-to-configure-the-linux-oom-killer/)

[关闭端口|启动端口](https://blog.csdn.net/helllochun/article/details/103822858)

### spring

[ApplicationContextAware](http://objcoding.com/2017/06/19/ApplicationContextAware/)

[spring - InitializingBean](https://blog.csdn.net/helllochun/article/details/103874846)

[? * ** 区别](https://blog.csdn.net/helllochun/article/details/103902748)

[ContextRefreshedEvent ](https://blog.csdn.net/helllochun/article/details/103904842)

[apring aop](https://blog.csdn.net/helllochun/article/details/103914857)

[@Inherited,@Component](https://blog.csdn.net/helllochun/article/details/104254099)

[springUtils](./spring/springutils/springUtils.md)

### JAVA

[类加载器](https://blog.csdn.net/javazejian/article/details/73413292)

[java泛型](https://juejin.im/post/5b614848e51d45355d51f792)

[java8新特性](https://blog.csdn.net/helllochun/article/details/103898237)

[java反射](https://blog.csdn.net/helllochun/article/details/103901947)

[timer 待写](https://blog.csdn.net/helllochun/article/details/103940681)



#### 安全模式

[AccessController ???????](https://www.jianshu.com/p/81985bc2bfa3)

### jvm 调试



jvm调优

https://cf.jd.com/pages/viewpage.action?pageId=18351251

https://cf.jd.com/pages/viewpage.action?pageId=186074876

https://cf.jd.com/pages/viewpage.action?pageId=161807509

https://cf.jd.com/pages/viewpage.action?pageId=240276615



* top 查看内存cpu使用

  top

* 排查进程内死锁情况

​        jstack -F 24317

* 查看tomcat pid

ps -ef | grep tomcat 

* 输出jmap情况到 指定文件

jmap -histo 10919  > a.txt

* 输出文件

  jmap -dump:format=b,file=heap.bin 10919 

* 命令：jstat -gcutil 10919 10000 10     10s 打印一次gc情况，打印10次，如图7所以

* 查看一下 jvm heap

  命令：jmap -heap 10919

* 



### maven

[插件的编写](https://blog.csdn.net/zixiao217/article/details/89636212)




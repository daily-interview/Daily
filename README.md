just for work

### web前端趋势

[前端top100](https://www.awesomes.cn/rank/?sort=trend)

[web前端导航](http://oolli.com/)

[前端工具库](http://www.qdfuns.com/tools.php)

### nodejs官网

https://nodejs.org/en/

### react && react native

[react](http://reactjs.cn/react/docs/getting-started.html)

[react-native](http://facebook.github.io/react-native/docs/getting-started.html)

### ES6入门

http://es6.ruanyifeng.com/

### TypeScript快速上手

[TypeScript中文网](https://www.tslang.cn/docs/handbook/typescript-in-5-minutes.html)

[TypeScript w3cshool](https://www.w3cschool.cn/typescript/typescript-tutorial.html)

### 物联网 mqtt协议

MQTT的设计思想是开源、可靠、轻巧、简单，MQTT的传输格式非常精小，最小的数据包只有2个比特，且无应用消息头。MQTT可以保证消息的可靠性，它包括三种不同的服务质量（最多只传一次、最少被传一次、一次且只传一次），如果客户端意外掉线，可以使用“遗愿”发布一条消息，同时支持持久订阅。MQTT在物联网以及移动应用中的优势有：

    可靠传输。MQTT可以保证消息可靠安全的传输，并可以与企业应用简易集成。

    消息推送。支持消息实时通知、丰富的推送内容、灵活的Pub-Sub以及消息存储和过滤。

    低带宽、低耗能、低成本。占用移动应用程序带宽小，并且带宽利用率高，耗电量较少。


### mac下启动mongodb

cd /usr/local/mongodb/bin

sudo ./mongod

### mac下启动redis

redis-server

### 查询端口被占用情况 并关闭进程

在windows控制台窗口下执行：

netstat -nao | findstr "9010"           

TCP 127.0.0.1:9010 0.0.0.0:0 LISTENING 3017

你看到是PID为3017的进程占用了9010端口，如果进一步你想知道它的进程名称，你可以使用如下命令：

tasklist | findstr "3017"

如果你想杀死这个进程，你当然可以用前面描述的那种方法，在任务管理器里把它KILL了，但如果你喜欢高效一点，那么用taskkill命令就可以了。

taskkill /pid 3017

taskkill /pid 3017 /f  强行关闭

那么这个进程就灰灰湮灭了:)

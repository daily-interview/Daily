just for work

### web前端趋势

前端top100： https://www.awesomes.cn/rank/?sort=trend

web前端导航： http://oolli.com/

前端工具库： http://www.qdfuns.com/tools.php

### nodejs官网

https://nodejs.org/en/

### react && react native

http://reactjs.cn/react/docs/getting-started.html

http://facebook.github.io/react-native/docs/getting-started.html

### ES6入门

http://es6.ruanyifeng.com/

### TypeScript快速上手

https://www.tslang.cn/docs/tutorial.html

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

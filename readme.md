# http 压测工具

## 命令行选项:
  - -m: http method (default GET)
  - -c: concurrent 并发请求数,协程数 (default 100)
  - -time: 压测时间 eg. 30s (default 1m)
  - -tick: 每隔多久显示一次当前状态 (default 0s)
  - -url: 请求的网址 required
  - -h: http header以分号(;)分隔(default empty)
  - -body 
  
 ## 功能
  - 显示每秒请求成功数 Requests/sec
  - 显示每秒读取字节数 Transfer/sec
  - 显示总请求数 Total request
  - 显示总读取字节数 Transfer/sec
  - 显示请求错误数 Error count
  


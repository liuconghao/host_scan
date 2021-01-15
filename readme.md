## 这是一个用于IP和域名碰撞匹配访问的小工具，旨意用来匹配出渗透过程中需要绑定hosts才能访问的弱主机或内部系统。

## install
`go get -u github.com/cyal1/host_scan`

## useage

`hostscan -i ip.txt -d host.txt`

```
Usage of hostscan:
  -d string
    	Domain/Host list file (required)
  -i string
    	IP list file (required)
  -output string
    	Output file
  -redirect
    	Follow redirects
  -threads int
    	Threads/Goroutine number (default 50)
  -timeout int
    	Request timeout (default 8)
  -ua string
    	User-Agent string (default "Mozilla/5.0(Linux;U;Android2.3.6;zh-cn;GT-S5660Build/GINGERBREAD)AppleWebKit/533.1(KHTML,likeGecko)Version/4.0MobileSafari/533.1MicroMessenger/4.5.255")
```

![效果图](https://raw.githubusercontent.com/cyal1/host_scan/master/test.jpg)

## Reference
https://github.com/fofapro/Hosts_scan


# SSR for Ubuntu

* 安装shadowsocks


```
pip install shadowsocks
```

* 升级兼容shadowsocksR

* shadowsocksr-3.0.1.zip提取安装


```
sudo python setup.py install
```
* 建立配置文件shadowsocks.json
填入购买ssr的配置信息


```
{
	"remarks" :
	"id" : 
	"server" : 
	"server_port" : 
	"server_udp_port" :
	"password" : 
	"method" : 
	"protocol" : 
	"protocolparam" :
	"obfs" : 
	"obfsparam" : 
	"remarks_base64" : 
	"group" : 
	"enable" : 
	"udp_over_tcp" : 
}

```

* 同目录执行
```
sslocal -c shadowsocks.json -b 127.0.0.1
```
* Google-Chrome


```
google-chrome --proxy-server="socks5://127.0.0.1:1080"
```

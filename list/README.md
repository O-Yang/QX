

## 二、远程分流规则订阅

❗️**`远程分流规则订阅，将网络请求进行分流，网络请求的走向(是否能成功访问)由匹配到的策略组决定，部分规则有先后顺序要求，调整顺序可能失效。注意：(对于完全相同的某条规则，本地的将优先生效)。`
> `Quantumult X 设置` > `分流` > `引用` > 右上角 `➕` > 输入资源链接
### [filter_remote]

#### 👋 规则修正

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Unbreak.list
>

#### 👋 正常广告拦截

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Advertising.list
>

#### 👋 重度广告拦截

> https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/AdRule.list
>

#### 👋 运营劫持

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Hijacking.list
>

#### 👋 隐私保护

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Privacy.list
>

#### 👋 全球加速

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Global.list
>

#### 👋 国际媒体

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/Streaming.list
>

#### 👋 国内网站

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/China.list
>

#### 👋 国内IP

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/ChinaIP.list
>

#### 👋 屏蔽系统更新

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/BlockiOSUpdate.list
>

#### 👋 苹果服务1

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/AppStore.list
>

#### 👋 苹果服务2

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/AppStoreConnect.list
>

#### 👋 Testflight

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Apple/TestFlight.list
>

#### 港台番剧

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/StreamingSE.list
>

#### 👋 海外抖音

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/StreamingMedia/Video/TikTok.list
>


#### 

> 
>

#### 

> 
>

### 

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
Spotify（声田）是一个正版流媒体音乐

#### a. 分流规则工作原理

> list 文件内包含若干如下的域名列表：
>
> ```
> # > ABC
> HOST-SUFFIX,edgedatg.com,GMedia
> HOST-SUFFIX,go.com,GMedia
> 
> # > Abema TV
> USER-AGENT,AbemaTV*,GMedia
> HOST-SUFFIX,abema.io,GMedia
> HOST-SUFFIX,abema.tv,GMedia
> HOST-SUFFIX,akamaized.net,GMedia
> HOST-SUFFIX,ameba.jp,GMedia
> HOST-SUFFIX,hayabusa.io,GMedia
> ```
>




















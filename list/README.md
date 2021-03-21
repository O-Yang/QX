

## 二、远程分流规则订阅

❗️**`远程分流规则订阅，将网络请求进行分流，网络请求的走向(是否能成功访问)由匹配到的策略组决定，部分规则有先后顺序要求，调整顺序可能失效。注意：(对于完全相同的某条规则，本地的将优先生效)。`
> `Quantumult X 设置` > `分流` > `引用` > 右上角 `添加` - 输入资源链接
### [filter_remote]

#### 规则修正

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Unbreak.list
>

#### 正常广告拦截

> https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Advertising.list
>

#### c. 添加策略组(举例说明)


> 例如：GeQ1an 的 GMedia.list 规则中 已经包含了 Netflix.list / Spotify.list / YouTube.list
>
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
> 如果发起的**网络访问 命中**了**分流规则**列表中包含的域名，那么**访问请求**将会被**分发至**这条规则指定的**策略组**。访问成功与否取决于策略组

#### b. 添加分流规则

##### b.1 **添加** `[filter_remote]` 远程分流规则订阅

###### a. 在软件界面(UI)中直接添加分流规则

> 一次添加一条
>
> `Quantumult X 设置` > `分流` > `引用` > 右上角 `添加` - 输入资源链接

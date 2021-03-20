# QX
QuantumultX
自用库，感谢各位大神提供支持，不一一感谢了。

# 1.远程分流规则订阅
[filter_remote]

Unbreak.list, tag=规则修正

Advertising.list, tag=正常广告拦截
<p>
AdRule.list, tag=重度广告拦截（默认不开启）

Hijacking.list, tag=运营商劫持</p>
Privacy.list, tag=隐私保护<p>
Advertising.list, tag=正常广告拦截<p>
👇🏻国内外知名网站规则<p>
Global.list, tag=全球加速,
Streaming.list, tag=国际媒体, 
China.list, tag=国内网站, 
ChinaIP.list, tag=国内IP, 
BlockiOSUpdate.list, tag=屏蔽系统更新,
AppStore.list, tag=苹果服务,
AppStoreConnect.list, tag=苹果服务, 
TestFlight.list, tag=Testflight, 
StreamingSE.list, tag=港台番剧, 
# 2.远程重写订阅
https://raw.githubusercontent.com/chavyleung/scripts/master/box/rewrite/boxjs.rewrite.quanx.tf.conf, tag=BoxJS, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/JS_GetCookie.conf, tag=BoxJS Cookie, update-interval=86400, opt-parser=false, enabled=false
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/YouTube.conf, tag=YouTube去广告, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/Rewrite_lhie1.conf, tag=分流去广告, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/Orz-3/QuantumultX/master/JS.conf, tag=比价、Netflix评分、微信微博知乎等去广告, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/Block/Advertising.conf, tag=神机去广告, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/General.conf, tag=神机重定向, update-interval=86400, opt-parser=false, enabled=true
https://raw.githubusercontent.com/Orz-3/Orz-3/master/QuantumultX/TikTok.conf, tag=Tiktok解锁, update-interval=86400, opt-parser=false, enabled=true

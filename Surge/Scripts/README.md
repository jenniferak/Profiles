# Youtube Premium解锁检测，修改自Hyseen
```
#!name=YouTube Premium Unlock Check
#!desc=YouTube Premium 解锁检测
#!system=ios

[Panel]
youtube_premium_check = script-name=youtube_premium_check, title="YouTube Premium 解锁检测", update-interval=300

[Script]
youtube_premium_check = type=generic, script-path=https://raw.githubusercontent.com/jenniferak/Profiles/master/Surge/Scripts/youtube_premium_check.js, argument=title=YouTube 解锁检测
```

# 机场流量展示（不带更新时间），修改自mieqq
```
[Script]
Sub_info = type=generic,timeout=10,script-path=https://raw.githubusercontent.com/jenniferak/Profiles/master/Surge/Scripts/Sub_info_panel.js,script-update-interval=0,argument=url=[URL encode 后的机场节点链接]&reset_day=1&title=AmyInfo&icon=bonjour&color=#007aff&expire=false
[Panel]
Sub_info = script-name=Sub_info,update-interval=600
```

# 机场流量展示（带更新时间），修改自mieqq
```
[Script]
Sub_info = type=generic,timeout=10,script-path=https://raw.githubusercontent.com/jenniferak/Profiles/master/Surge/Scripts/Sub_info_panel2.js,script-update-interval=0,argument=url=[URL encode 后的机场节点链接]&reset_day=1&title=AmyInfo&icon=bonjour&color=#007aff&expire=false
[Panel]
Sub_info = script-name=Sub_info,update-interval=600
```

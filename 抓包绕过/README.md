建议任何app都以spawn方式启动just_trust_me.js。因为要在app完成初始化之前hook住所有的hook点，只有spawn模式下才能做到，attach时机可能太晚了。

hooker框架-JustTrustMe.js的来源是这：https://github.com/CreditTone/hooker 中提取出来的，这框架说实话感觉不太好用

双向证书绕过的项目是这个：https://github.com/r0ysue/r0capture

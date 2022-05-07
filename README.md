# autojs-qiangcai  
基于Autojs模拟点击的美团和叮咚抢菜脚本  
**美团买菜推荐使用5.32版本**

## 说明

> 1.坐标点击模式在代码里改：fastMode=false，不过这个模式效率很低，不适合开多个线程，会出现多个点同时点击。  
> 2.参数里的delay可以自行更改  
> 3.matchType参数值 [0:精确文字; 1:左模糊文字; 2:右模糊文字; 3:全模糊文字; 4:id匹配]

### 1. 自动抢菜.js  
- 合并了美团和叮咚
- 两种模式（立即、定时），付款成功会闹钟提醒  
- 其实这个也可以捡漏的，白天会经常放一些货，加购物车后一直开着脚本点就行了，一直会有提示，但是挂着就完事了.经常挂个几十分钟就突然发现下单成功了，可能是有人退单或者运力有所调整。

### 2. 自动捡漏-美团买菜.js  
- 这个是用来捡漏的，因为美团偶尔会放货，可以让备用机一直跑着，遇到有货了就可以自动开始抢购。付款成功会闹钟提醒  

### 3. 通用文字点击App.js  
- 这是一个通用的文字点击器，里面自带了美团买菜和叮咚买菜的预设，可以直接用。  
- 至于其他软件，只要能通过点击文字来实现的，可以自己加预设来自定义  

> PS: 比较懒，能用就行，不想优化了。愿疫情早点结束


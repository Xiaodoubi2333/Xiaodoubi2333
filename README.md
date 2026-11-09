# 你好，我是 狐狸老逗比

Java / Android 出身，做过一点全栈。习惯把课程项目当成真项目写：能跑、能讲清楚、能被人接手。

目前主要在打磨两件事——一套完整的 Android 天气应用演进链，和一个 A 股行情监控服务（私有）。

## 项目索引

### Android 天气应用 · 六个演进阶段

同一套教材代码的六个断面，按时间顺序看能看出「能编译 → 有界面 → 有数据 → 有导航 → 有收藏」的过程。

| 阶段 | 仓库 | 说明 |
|---|---|---|
| 1 | [oldWeatherAPP](https://github.com/Xiaodoubi2333/oldWeatherAPP) | 最早一版骨架：LitPal 省市县三表 + 空壳主界面 |
| 2 | [CoolWeather](https://github.com/Xiaodoubi2333/CoolWeather) | 教材复刻：课本级 Gradle 环境与地区选择界面 |
| 3 | [sourceCoolWeather](https://github.com/Xiaodoubi2333/sourceCoolWeather) | 原始源码基线，供逐行对照 |
| 4 | [WeatherAPP](https://github.com/Xiaodoubi2333/WeatherAPP) | 功能完整版：实时天气、预报、AQI、生活建议、后台刷新 |
| 5 | [fragmentWeatherAPP](https://github.com/Xiaodoubi2333/fragmentWeatherAPP) | 导航 + 天气双栈：四页签 + 详情页 |
| 6 | [naviCoolWeatherAPP](https://github.com/Xiaodoubi2333/naviCoolWeatherAPP) | 成品：SQLite 城市收藏夹、下拉刷新、手动换城市 |

### 其它

| 仓库 | 说明 | 技术 |
|---|---|---|
| [bilibili-Ignored](https://github.com/Xiaodoubi2333/bilibili-Ignored) | 隐藏 B 站播放页的观看人数与弹幕数量 | Chrome Extension MV3 |
| [BN](https://github.com/Xiaodoubi2333/BN) | 底部导航栏练习：四页签 + 视图复用 | Android Navigation |
| [listViewMethod](https://github.com/Xiaodoubi2333/listViewMethod) | 自定义 ListView 适配器与 ViewHolder | Android |
| [mysqlconnectiontest](https://github.com/Xiaodoubi2333/mysqlconnectiontest) | Android 直连 MySQL 的连通性实验（反模式，仅教学） | JDBC |

另有若干私有项目：A 股行情监控服务（Python 服务端 + 前端监控台、LLM 反代）、苍穹外卖后端完整实现（Spring Boot 三模块）、C# 五子棋（遗传算法对手）。

## 技术栈

```text
语言    Java · C# · JavaScript · Python · SQL
移动    Android（Java） · LitPal · OkHttp · Glide
后端    Spring Boot · MyBatis · MySQL · Redis · WebSocket · JWT
前端    HTML/CSS · 原生 JS
工具    Git · Maven · Gradle · Chrome Extension MV3
```

## 关于这些仓库

README 统一按同一套结构写：定位、文件结构、启动方式、功能落点表、版本记录、已知限制。落点表里的类名和方法名都能在源码里找到，不是概括性描述。

课程项目里的接口密钥、数据库口令一律标在「已知限制」里提醒，不写具体值。

---

<sub>这个仓库只用来渲染主页，不存放代码。</sub>

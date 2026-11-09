# 你好，我是 狐狸老逗比

Java / Android 出身，做过一点全栈。习惯把课程项目当成真项目写：能跑、能讲清楚、能被人接手。

目前主要在打磨两件事——一套完整的 Android 天气应用演进链，和一个 A 股行情监控服务（私有）。

## 项目索引

### Android 天气应用

一个功能完整的应用，加一条由浅入深的演进链。从编译跑通到收藏夹落地，每一版都能单独运行。

| 仓库 | 说明 |
|---|---|
| [android-weather-app](https://github.com/Xiaodoubi2333/android-weather-app) | 完整应用：省市县三级选择、实时天气与预报、AQI 与生活建议、后台每 8 小时刷新 |
| [android-weather-01-skeleton](https://github.com/Xiaodoubi2333/android-weather-01-skeleton) | 演进 01 · 骨架：LitPal 三张地区表 + 空壳主界面 |
| [android-weather-02-textbook](https://github.com/Xiaodoubi2333/android-weather-02-textbook) | 演进 02 · 教材复刻：课本级 Gradle 环境与地区选择界面 |
| [android-weather-03-source](https://github.com/Xiaodoubi2333/android-weather-03-source) | 演进 03 · 源码基线：教材原始结构，供逐行对照 |
| [android-weather-04-fragments](https://github.com/Xiaodoubi2333/android-weather-04-fragments) | 演进 04 · 双栈合并：四页签导航 + 完整天气模块 |
| [android-weather-05-navigation](https://github.com/Xiaodoubi2333/android-weather-05-navigation) | 演进 05 · 成品：SQLite 城市收藏夹（增删查改）+ 下拉刷新 + 手动换城市 |

### Android 基础练习

| 仓库 | 说明 | 技术 |
|---|---|---|
| [android-bottom-navigation](https://github.com/Xiaodoubi2333/android-bottom-navigation) | 底部导航四页签，每页独立 ViewModel，列表视图复用 | Navigation Component |
| [android-listview-adapter](https://github.com/Xiaodoubi2333/android-listview-adapter) | 自定义 `ArrayAdapter` + `ViewHolder`，实体列表渲染 | ListView |
| [android-jdbc-mysql-demo](https://github.com/Xiaodoubi2333/android-jdbc-mysql-demo) | 直连 MySQL 的连通性实验，用来回答「手机能不能直接连库」 | JDBC |

### 工具

| 仓库 | 说明 | 技术 |
|---|---|---|
| [bilibili-hide-viewcount](https://github.com/Xiaodoubi2333/bilibili-hide-viewcount) | 隐藏 B 站播放页的观看人数与弹幕数量 | Chrome Extension MV3 |

另有三个私有项目：`astock-console`（A 股行情监控服务，Python 服务端 + 前端监控台 + LLM 反代）、`sky-takeout-server`（苍穹外卖后端，Spring Boot 三模块）、`gomoku-ai-csharp`（C# 五子棋，遗传算法对手）。

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

提交信息统一为 Conventional Commits（`feat` / `fix` / `refactor` / `chore` / `docs`），每条对应一个可复述的改动，不再有「第 N 次提交」这类占位。

课程项目里的接口密钥、数据库口令一律标在「已知限制」里提醒，不写具体值。

---

<sub>这个仓库只用来渲染主页，不存放代码。</sub>

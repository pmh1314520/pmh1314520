<!--
================================================================================
  Profile README · pmh1314520（青云制作_彭明航）
  骨架文件 —— 8 个主要区块以成对注释标记界定，内部内容由后续任务逐块填充。
--------------------------------------------------------------------------------
  全局配色常量（后续所有区块统一取色依据；≤4 主色，不引入方案外额外主色）
  PRIMARY_VIOLET = #8B5CF6   主强调（卡片标题色 / 区块标题装饰 / 主徽章底色）
  ACCENT_CYAN    = #22D3EE   次强调（打字横幅文字 / 图标色 / 访客计数徽章）
  ACCENT_PINK    = #F472B6   点缀高亮（关键徽章 / 分隔装饰渐变收尾）
  BASE_INK       = 深色态 #C9D1D9 / 浅色态 #1F2328   中性正文文字（随主题切换）

  深色主题面：bg=#0D1117  border=#30363D  text=#C9D1D9
  浅色主题面：bg=#FFFFFF  border=#D0D7DE  text=#1F2328

  统一分隔元素：violet→cyan→pink 渐变分隔条（capsule-render type=rect），
  位于每个主要区块标题下方，作为可辨识的层次锚点；相邻区块间分隔类型一致。
  仅使用 GitHub 允许的内联 HTML 子集：div/table/tr/td/picture/source/img/a/sub/sup/h1-h4/hr/b/br。
================================================================================
-->

<!-- SECTION:TYPING_BANNER:START -->
<!--
  打字横幅：文档最顶部第一个可见区块（位于任何其他内容之前，无标题以确保居首）。
  顶部先放一条 capsule-render 渐变波浪装饰(waving)，再放 readme-typing-svg 打字动画，整体 <div align="center"> 居中。
  横幅字体改用 Google Fonts 的 "Ma Shan Zheng"（马善政毛笔书法体，艺术字），color=0891B2 加深青在深/浅两主题对比均达标，无需 <picture>。
  lines 以 ; 分隔，共 4 句（≥3）、每句 ≤50 字符，含昵称与简介，全中文以确保书法字体字形完整。
  【重要】中文必须做 URL 百分号编码，否则 GitHub 图片代理(camo)取不到图导致横幅空白。
-->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:22D3EE,100:F472B6&height=170&section=header" alt="顶部青紫粉渐变波浪装饰" />
  <br />
  <img
    src="https://readme-typing-svg.demolab.com/?font=Ma+Shan+Zheng&size=36&duration=3500&pause=800&center=true&vCenter=true&width=680&height=100&repeat=true&color=0891B2&lines=%E9%9D%92%E4%BA%91%E5%88%B6%E4%BD%9C_%E5%BD%AD%E6%98%8E%E8%88%AA;%E4%B8%80%E4%B8%AA%E7%97%B4%E8%BF%B7%E4%BA%8E%E8%AE%A1%E7%AE%97%E6%9C%BA%E6%8A%80%E6%9C%AF%E7%9A%84%E5%AD%A6%E7%94%9F;%E5%85%A8%E6%A0%88%E5%BC%80%E5%8F%91%20%C2%B7%20%E6%B8%B8%E6%88%8F%E5%BC%80%E5%8F%91%20%C2%B7%20%E8%87%AA%E5%8A%A8%E5%8C%96;%E4%BB%A3%E7%A0%81%E5%8D%B3%E7%83%AD%E7%88%B1%20%C2%B7%20%E5%88%9B%E9%80%A0%E5%8D%B3%E5%BF%AB%E4%B9%90"
    alt="青云制作_彭明航 - 一个痴迷于计算机技术的学生"
  />
  <br />
  <!-- 无限横向滚动跑马灯：手写 SMIL 动画 SVG，双拷贝无缝循环，边缘渐隐遮罩，本地资源稳定不破图 -->
  <img width="72%" src="assets/marquee.svg" alt="滚动横幅：学以致用才是王道 · Vibe Coding · Full-Stack · Game Dev · Automation · Open Source" />
</div>
<!-- SECTION:TYPING_BANNER:END -->

<!-- SECTION:ABOUT_ME:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/user-male-circle.png" alt="关于我图标" />&nbsp; 关于我 · About Me</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,50:22D3EE,100:F472B6&height=3" alt="紫罗兰到青到粉的渐变分隔条" width="100%" />
</div>

<h1 align="center">青云制作_彭明航 <sub>(he/him)</sub></h1>

<p align="center">一个痴迷于计算机技术的学生 · A student obsessed with computer technology</p>

<p align="center">
  <img height="20" src="https://img.icons8.com/fluency/48/quote-left.png" alt="格言" />
  <i>学习是永无止境的，学以致用才是王道！</i>
  <img height="20" src="https://img.icons8.com/fluency/48/quote-right.png" alt="格言" />
</p>

<p align="center"><img height="18" src="https://img.icons8.com/fluency/48/graduation-cap.png" alt="院校" /> 就读于 盐城工学院（Yancheng Institute of Technology）</p>

<p align="center"><img height="18" src="https://img.icons8.com/fluency/48/marker.png" alt="所在地" /> 江苏省盐城市（Yancheng City, Jiangsu Province）</p>

<!--
  自动年龄卡片：由每日刷新工作流(refresh-assets.yml)内联 Python 按生日 2006-10-26 计算年龄，
  生成主题自适应 SVG(age.svg) 推送到 output 分支，README 引用 raw URL，每天自动更新，无需人工维护。
  单张自适应 SVG(内置 prefers-color-scheme)，非 <picture>；alt 非空描述用途。
-->
<div align="center">
  <img src="https://raw.githubusercontent.com/pmh1314520/pmh1314520/output/age.svg" alt="我的年龄 · 由工作流按生日每日自动计算更新" />
</div>

- <img height="18" src="https://img.icons8.com/fluency/48/idea.png" alt="专注" /> 专注于计算机技术的学习与实践，热爱钻研底层原理与工程实现
- <img height="18" src="https://img.icons8.com/fluency/48/source-code.png" alt="开源" /> 持续维护多个开源项目，享受与社区一起打磨代码的过程
- <img height="18" src="https://img.icons8.com/fluency/48/gears.png" alt="自动化" /> 热衷于自动化工具的研发，让重复繁琐的工作交给程序完成
- <img height="18" src="https://img.icons8.com/fluency/48/artificial-intelligence.png" alt="AI" /> 资深 Vibe Coding 爱好者，享受与 AI 结对编程、把想法快速变成产品
- <img height="18" src="https://img.icons8.com/fluency/48/domain.png" alt="网站" /> 个人网站：[www.pmhs.top](https://www.pmhs.top)

<!-- SECTION:ABOUT_ME:END -->

<!-- SECTION:TECH_STACK:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/source-code.png" alt="技术栈图标" />&nbsp; 技术栈 · Tech Stack</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,50:22D3EE,100:F472B6&height=3" alt="紫罗兰到青到粉的渐变分隔条" width="100%" />
</div>

<!--
  技术栈徽章：<div align="center"> 内按 7 组排列 shields.io 徽章（style=for-the-badge）。
  每组前置 <h4 align="center"> 小标题；每个徽章含技术名称文字标签 + 官方 logo（有则带）+ 非空 alt。
  无官方图标的技术省略 logo 参数使用纯色文字徽章，仍保留名称与非空 alt。
  分组数 8（2~8）、徽章总数在 3~60 之间，必含 Python / TypeScript / Rust。
  徽章图片实时取自 img.shields.io（稳定），内容固定，属静态区块。
-->

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/code.png" alt="编程语言图标" />&nbsp; 编程语言 · Programming Languages</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C Sharp" />
  <img src="https://img.shields.io/badge/GDScript-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="GDScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/web.png" alt="前端图标" />&nbsp; 前端 · Frontend</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/multiple-devices.png" alt="跨端桌面图标" />&nbsp; 跨端 &amp; 桌面 · Cross-Platform &amp; Desktop</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white" alt="Tauri" />
  <img src="https://img.shields.io/badge/PyQt-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/server.png" alt="后端图标" />&nbsp; 后端 · Backend</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white" alt="Bun" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=gin&logoColor=white" alt="Gin" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="dotNET" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/database.png" alt="数据库图标" />&nbsp; 数据库 &amp; 中间件 · Databases &amp; Middleware</h4>
<p align="center">
  <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/cloud.png" alt="云原生图标" />&nbsp; 云原生 &amp; 运维 · Cloud Native &amp; DevOps</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/controller.png" alt="游戏多媒体图标" />&nbsp; 游戏 &amp; 多媒体 · Game &amp; Media</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
  <img src="https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot" />
  <img src="https://img.shields.io/badge/Unreal_Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white" alt="Unreal Engine" />
  <img src="https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white" alt="Blender" />
  <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white" alt="Photoshop" />
  <img src="https://img.shields.io/badge/Premiere_Pro-9999FF?style=for-the-badge&logo=adobepremierepro&logoColor=white" alt="Premiere Pro" />
  <img src="https://img.shields.io/badge/OBS_Studio-302E31?style=for-the-badge&logo=obsstudio&logoColor=white" alt="OBS Studio" />
  <img src="https://img.shields.io/badge/NetEase_ModSDK-8B5CF6?style=for-the-badge" alt="NetEase ModSDK" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/maintenance.png" alt="工具平台图标" />&nbsp; 工具 &amp; 平台 · Tools &amp; Platforms</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white" alt="PyCharm" />
  <img src="https://img.shields.io/badge/GoLand-000000?style=for-the-badge&logo=goland&logoColor=white" alt="GoLand" />
  <img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white" alt="Visual Studio" />
  <img src="https://img.shields.io/badge/1Panel-0195FF?style=for-the-badge&logo=1panel&logoColor=white" alt="1Panel" />
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows" />
</p>

<!-- SECTION:TECH_STACK:END -->

<!-- SECTION:STATS:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/combo-chart.png" alt="数据统计图标" />&nbsp; GitHub 数据 · GitHub Stats</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,50:22D3EE,100:F472B6&height=3" alt="紫罗兰到青到粉的渐变分隔条" width="100%" />
</div>

<!--
  三张统计卡片，均用 <picture> + <source media="(prefers-color-scheme: dark)"> + 浅色 <img> 回退实现深/浅主题切换。
  三卡配色参数取值完全一致且等于全局主题声明色值（Property 9）：
    深色 bg=0D1117 title=8B5CF6 text=C9D1D9 icon=22D3EE border=30363D
    浅色 bg=FFFFFF title=7C3AED text=1F2328 icon=0891B2 border=D0D7DE
  streak-stats 参数名不同（background/ring/fire/currStreakLabel/sideLabels/dates/stroke 等），但色值取相同值。
-->

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/combo-chart.png" alt="通用统计图标" />&nbsp; 通用统计 · Overall Stats</h4>
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-git-master-pmh1314520s-projects.vercel.app/api?username=pmh1314520&show_icons=true&count_private=true&include_all_commits=true&bg_color=0D1117&title_color=8B5CF6&text_color=C9D1D9&icon_color=22D3EE&border_color=30363D" />
    <img alt="pmh1314520 的 GitHub 通用统计卡片：展示 Star 总数、提交数、Follower 数与贡献数" src="https://github-readme-stats-git-master-pmh1314520s-projects.vercel.app/api?username=pmh1314520&show_icons=true&count_private=true&include_all_commits=true&bg_color=FFFFFF&title_color=7C3AED&text_color=1F2328&icon_color=0891B2&border_color=D0D7DE" />
  </picture>
</div>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/chat.png" alt="常用语言图标" />&nbsp; 常用语言 · Most Used Languages</h4>
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-git-master-pmh1314520s-projects.vercel.app/api/top-langs?username=pmh1314520&layout=compact&langs_count=8&bg_color=0D1117&title_color=8B5CF6&text_color=C9D1D9&icon_color=22D3EE&border_color=30363D" />
    <img alt="pmh1314520 的常用编程语言占比卡片：展示占比最高的前若干种语言及其百分比" src="https://github-readme-stats-git-master-pmh1314520s-projects.vercel.app/api/top-langs?username=pmh1314520&layout=compact&langs_count=8&bg_color=FFFFFF&title_color=7C3AED&text_color=1F2328&icon_color=0891B2&border_color=D0D7DE" />
  </picture>
</div>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/light-on.png" alt="连续贡献图标" />&nbsp; 连续贡献 · Contribution Streak</h4>
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=pmh1314520&background=0D1117&ring=8B5CF6&fire=22D3EE&currStreakLabel=8B5CF6&currStreakNum=C9D1D9&sideLabels=C9D1D9&sideNums=C9D1D9&dates=C9D1D9&stroke=30363D" />
    <img alt="pmh1314520 的连续贡献天数卡片：展示当前连续贡献天数与历史最长连续贡献天数" src="https://streak-stats.demolab.com/?user=pmh1314520&background=FFFFFF&ring=7C3AED&fire=0891B2&currStreakLabel=7C3AED&currStreakNum=1F2328&sideLabels=1F2328&sideNums=1F2328&dates=1F2328&stroke=D0D7DE" />
  </picture>
</div>

<!-- SECTION:STATS:END -->

<!-- SECTION:PROJECTS:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/rocket.png" alt="项目图标" />&nbsp; 代表项目 · Featured Projects</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,50:22D3EE,100:F472B6&height=3" alt="紫罗兰到青到粉的渐变分隔条" width="100%" />
</div>

<!--
  项目展示：<table> 两行两列（每行 2 列共 2 行）网格布局，各单元格 width=50% 宽度一致。
  恰好 4 个项目（WebRPA / MCTier / WinMsgHub / HypoMuxPlus），不多不少。
  每个单元格结构：仓库真实软件图标(取自各仓库 README 顶部) → 项目名(<a href> 指向仓库) + 主要语言徽章
  → shields.io 的 Star/Fork 徽章(稳定，替代已限流的 pin 卡) → ≤100 字符真实一句话简介(取自仓库 GitHub 描述)。
  图标 raw 地址注意各仓库默认分支不同：WebRPA=main / MCTier=master / WinMsgHub=main / HypoMuxPlus=main。
  每张图片 alt 非空；单张失败仅降级为自身 alt，不影响其余。
-->
<table>
  <tr>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/pmh1314520/WebRPA">
        <img src="https://raw.githubusercontent.com/pmh1314520/WebRPA/main/png/logo.png" width="72" alt="WebRPA 项目图标" />
      </a>
      <br />
      <a href="https://github.com/pmh1314520/WebRPA"><b>WebRPA</b></a>
      <br />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="主要语言 Python" />
      <br />
      <a href="https://github.com/pmh1314520/WebRPA">
        <img src="https://img.shields.io/github/stars/pmh1314520/WebRPA?style=for-the-badge&logo=github&label=Stars&color=8B5CF6&labelColor=0D1117" alt="WebRPA Stars 数" />
        <img src="https://img.shields.io/github/forks/pmh1314520/WebRPA?style=for-the-badge&logo=github&label=Forks&color=22D3EE&labelColor=0D1117" alt="WebRPA Forks 数" />
      </a>
      <br />
      <sub>可视化拖拽式 RPA 自动化工具，558 模块 + AI 助手，零代码搞定网页 / 桌面 / 手机自动化，完全离线。</sub>
      <br />
      <a href="https://rpa.pmhs.top"><img height="13" src="https://img.icons8.com/fluency/48/domain.png" alt="官网" /> 官网 · Live</a>
    </td>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/pmh1314520/MCTier">
        <img src="https://raw.githubusercontent.com/pmh1314520/MCTier/master/public/MCTierIcon.png" width="72" alt="MCTier 项目图标" />
      </a>
      <br />
      <a href="https://github.com/pmh1314520/MCTier"><b>MCTier</b></a>
      <br />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="主要语言 TypeScript" />
      <br />
      <a href="https://github.com/pmh1314520/MCTier">
        <img src="https://img.shields.io/github/stars/pmh1314520/MCTier?style=for-the-badge&logo=github&label=Stars&color=8B5CF6&labelColor=0D1117" alt="MCTier Stars 数" />
        <img src="https://img.shields.io/github/forks/pmh1314520/MCTier?style=for-the-badge&logo=github&label=Forks&color=22D3EE&labelColor=0D1117" alt="MCTier Forks 数" />
      </a>
      <br />
      <sub>虚拟局域网通用组网工具，基于 EasyTier + WebRTC，跨网络联机 / 语音 / 共享，支持 Windows 与 Android。</sub>
      <br />
      <a href="https://mctier.pmhs.top"><img height="13" src="https://img.icons8.com/fluency/48/domain.png" alt="官网" /> 官网 · Live</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/pmh1314520/WinMsgHub">
        <img src="https://raw.githubusercontent.com/pmh1314520/WinMsgHub/main/resources/icons/WinMsgHub_ICON.png" width="72" alt="WinMsgHub 项目图标" />
      </a>
      <br />
      <a href="https://github.com/pmh1314520/WinMsgHub"><b>WinMsgHub</b></a>
      <br />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="主要语言 Python" />
      <br />
      <a href="https://github.com/pmh1314520/WinMsgHub">
        <img src="https://img.shields.io/github/stars/pmh1314520/WinMsgHub?style=for-the-badge&logo=github&label=Stars&color=8B5CF6&labelColor=0D1117" alt="WinMsgHub Stars 数" />
        <img src="https://img.shields.io/github/forks/pmh1314520/WinMsgHub?style=for-the-badge&logo=github&label=Forks&color=22D3EE&labelColor=0D1117" alt="WinMsgHub Forks 数" />
      </a>
      <br />
      <sub>Python + PyQt6 的 Windows 消息聚合应用，8 类消息源统一接收，高度可定制的桌面弹窗智能通知。</sub>
      <br />
      <a href="https://wmh.pmhs.top"><img height="13" src="https://img.icons8.com/fluency/48/domain.png" alt="官网" /> 官网 · Live</a>
    </td>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/pmh1314520/HypoMuxPlus">
        <img src="https://raw.githubusercontent.com/pmh1314520/HypoMuxPlus/main/appicon.svg" width="72" alt="HypoMuxPlus 项目图标" />
      </a>
      <br />
      <a href="https://github.com/pmh1314520/HypoMuxPlus"><b>HypoMuxPlus</b></a>
      <br />
      <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="主要语言 Rust" />
      <br />
      <a href="https://github.com/pmh1314520/HypoMuxPlus">
        <img src="https://img.shields.io/github/stars/pmh1314520/HypoMuxPlus?style=for-the-badge&logo=github&label=Stars&color=8B5CF6&labelColor=0D1117" alt="HypoMuxPlus Stars 数" />
        <img src="https://img.shields.io/github/forks/pmh1314520/HypoMuxPlus?style=for-the-badge&logo=github&label=Forks&color=22D3EE&labelColor=0D1117" alt="HypoMuxPlus Forks 数" />
      </a>
      <br />
      <sub>Windows 多网卡带宽聚合下载加速工具，Tauri + Rust 重构，让 Steam / IDM / 浏览器跑满每张网卡。</sub>
      <br />
      <a href="https://hmp.pmhs.top"><img height="13" src="https://img.icons8.com/fluency/48/domain.png" alt="官网" /> 官网 · Live</a>
    </td>
  </tr>
</table>

<!-- SECTION:PROJECTS:END -->

<!-- SECTION:SOCIAL:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/link.png" alt="联系图标" />&nbsp; 联系我 · Connect With Me</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,50:22D3EE,100:F472B6&height=3" alt="紫罗兰到青到粉的渐变分隔条" width="100%" />
</div>

<!--
  社交链接：<div align="center"> 内每个平台为 [![alt](shields.io badgeURL)](targetURL) 形式的静态 Markdown 超链接徽章（Property 11 / 需求 6.4）。
  每个徽章 = shields.io badge（style=for-the-badge，含平台 Logo logo=、平台名称文字标签、非空 alt）。
  - 个人网站 → https://www.pmhs.top（含协议前缀绝对 URL，需求 6.1），主色紫罗兰 8B5CF6。
  - Bilibili  → https://space.bilibili.com/1102546347（需求 6.2），官方品牌粉 FB7299。
  邮箱徽章：无可公开的有效联系邮箱（全局配置未声明 EMAIL），属缺失链接目标，按需求 6.6 直接不写入。
  markdown 徽章置于 <div align="center"> 内，前后留空行以确保 GitHub 正常渲染 Markdown 语法。
-->
<div align="center">

[![个人网站 www.pmhs.top](https://img.shields.io/badge/个人网站-www.pmhs.top-8B5CF6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.pmhs.top)
[![Bilibili 主页 哔哩哔哩](https://img.shields.io/badge/Bilibili-哔哩哔哩-FB7299?style=for-the-badge&logo=bilibili&logoColor=white)](https://space.bilibili.com/1102546347)

</div>

<!-- SECTION:SOCIAL:END -->

<!-- SECTION:SPONSOR:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/coffee-to-go.png" alt="赞赏图标" />&nbsp; 赞赏支持 · Sponsor Me</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,50:22D3EE,100:F472B6&height=3" alt="紫罗兰到青到粉的渐变分隔条" width="100%" />
</div>

<!--
  赞赏支持：给访客一个自愿赞赏渠道。二维码为本地图片（assets/ 目录，随仓库推送），非外链，稳定不受第三方服务影响。
  微信 sponsor-wechat.png / 支付宝 sponsor-alipay.jpg，用 <table> 两列并排、居中展示，各带说明文字。
-->
<p align="center">如果我的项目或分享曾对你有帮助，欢迎请我喝杯咖啡，你的支持是我持续创作与开源的动力 <img height="16" src="https://img.icons8.com/fluency/48/like.png" alt="爱心" /></p>

<p align="center">
  <a href="https://ifdian.net/a/qypmh">
    <img src="https://img.shields.io/badge/爱发电-在爱发电支持我-946CE6?style=for-the-badge&logo=afdian&logoColor=white" alt="爱发电 - 在爱发电支持青云制作_彭明航" />
  </a>
</p>

<div align="center">
<table>
  <tr>
    <td align="center" width="260">
      <img src="assets/sponsor-wechat.png" width="220" alt="微信收款码 · WeChat Pay QR" />
      <br />
      <b>微信 · WeChat Pay</b>
    </td>
    <td align="center" width="260">
      <img src="assets/sponsor-alipay.jpg" width="220" alt="支付宝收款码 · Alipay QR" />
      <br />
      <b>支付宝 · Alipay</b>
    </td>
  </tr>
</table>
</div>

<!-- SECTION:SPONSOR:END -->

<!-- SECTION:VISITOR_SNAKE:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/conference-call.png" alt="访客图标" />&nbsp; 访客与贡献 · Visitors &amp; Contributions</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,50:22D3EE,100:F472B6&height=3" alt="紫罗兰到青到粉的渐变分隔条" width="100%" />
</div>

<!--
  访客计数徽章（komarev / ghpvc）：以数字形式展示主页累计访问次数（需求 7.1）。
  color=22D3EE 次强调青，style=for-the-badge 与全站徽章风格一致。
  alt 说明用途，图像无法加载时降级为该文本（需求 7.7）。
-->
<div align="center">
  <img
    src="https://komarev.com/ghpvc/?username=pmh1314520&label=Profile+Views&color=22D3EE&style=for-the-badge"
    alt="Profile Views - 主页累计访问次数"
  />
</div>

<!--
  蛇形贡献动画：引用 output 分支预生成 SVG（由刷新工作流 Platane/snk 每 24h 生成）。
  <picture> + <source media="(prefers-color-scheme: dark)"> 深色版 + 浅色 <img> 回退实现深/浅主题切换（需求 7.4）。
  资产尚不存在或加载失败时，浏览器降级展示 img 的 alt 文本以说明该区块用途（需求 7.5）。
-->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pmh1314520/pmh1314520/output/github-snake-dark.svg" />
    <img alt="pmh1314520 的 GitHub 贡献热图蛇形动画" src="https://raw.githubusercontent.com/pmh1314520/pmh1314520/output/github-snake.svg" />
  </picture>
</div>

<!-- SECTION:VISITOR_SNAKE:END -->

<!-- SECTION:FOOTER:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/like.png" alt="感谢图标" />&nbsp; 感谢访问 · Thanks for Visiting</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,50:22D3EE,100:F472B6&height=3" alt="紫罗兰到青到粉的渐变分隔条" width="100%" />
</div>

<!--
  页脚收尾：与其它区块一致的居中标题 + 渐变分隔条已在上方给出。
  此处补充一句居中的感谢/收尾文字，呼应"青云"主题与开源精神，保持整体视觉一致性（需求 8.2）。
-->
<p align="center">感谢你抵达这里 · 愿代码与热爱同行 <img height="18" src="https://img.icons8.com/fluency/48/rocket.png" alt="火箭" /></p>

<p align="center"><sub>Designed with <img height="14" src="https://img.icons8.com/fluency/48/like.png" alt="爱心" /> by 青云制作_彭明航 · Powered by GitHub Actions &amp; Open Source</sub></p>

<p align="center"><sub>图标由 <a href="https://icons8.com">Icons8</a> 提供 · Icons by Icons8</sub></p>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:F472B6,50:22D3EE,100:8B5CF6&height=150&section=footer" alt="底部粉青紫渐变波浪装饰" />
</div>

<!-- SECTION:FOOTER:END -->

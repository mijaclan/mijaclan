<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img src="assets/banner-light.svg" alt="mijaclan — 我不生产代码，我只是 AI 的甲方" width="100%">
</picture>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1100&color=1F6FEB&center=true&vCenter=true&width=660&lines=%E5%88%AB%E4%BA%BA%E5%8A%A0%E7%8F%AD%EF%BC%8C%E6%88%91%E5%8A%A0+agent;%E5%AE%83%E8%B7%91%E8%85%BF%EF%BC%8C%E6%88%91%E6%8B%8D%E6%9D%BF;%E5%85%88%E8%B7%91%E9%80%9A%EF%BC%8C%E5%86%8D%E4%BC%98%E9%9B%85;AI+%E5%B9%B2%E6%B4%BB%EF%BC%8C%E6%88%91%E8%83%8C%E9%94%85%EF%BC%88%E4%B8%8D%E6%98%AF%EF%BC%89" alt="typing" />
</p>

<p align="center">
  <code>🐤 早鸟型选手</code>&nbsp;<code>🧯 CI 拆弹</code>&nbsp;<code>🤖 Agent 派活</code>&nbsp;<code>🌏 Asia/Shanghai</code>
</p>

白天给产品写功能，晚上给 agent 写 prompt。两件事的共同点：**都得能被验收**。

我最值钱的技能不是手速，是知道**哪一步该丢给机器、哪一步必须自己签字**。

---

<table>
<tr>
<td width="34%" valign="top" align="center">
<h3>🧯</h3>
<b>我到底在修什么</b><br>
<sub>大部分不是自己写的 bug，是上游默默把接口改了、文档一个字没动。</sub>
</td>
<td width="33%" valign="top" align="center">
<h3>🤖</h3>
<b>我的隐藏副业</b><br>
<sub>给 agent 派活：读日志、翻仓库、开浏览器、跑验证。它从不抱怨加班。</sub>
</td>
<td width="33%" valign="top" align="center">
<h3>⚡</h3>
<b>我的迷信</b><br>
<sub>能跑就别动。要动先写测试。写完测试再想优雅。</sub>
</td>
</tr>
</table>

---

## 🎮 玩一下

> 三个小东西，三十秒能玩完。玩完顺手 star 一下也不算亏。

<details>
<summary><b>① 猜猜我一天几点写代码？</b>（点开对答案）</summary>

<br>

我把 47% 的 commit 留在了**早上七点前后**，剩下的大头在深夜十一点。

下午？下午通常在跟人说话、开会、或者假装在开会。

<sub>数据来自下面那块自动统计，不是我自己编的。</sub>

</details>

<details>
<summary><b>② 一道真题：这条流水线为什么天天红？</b>（点开看答案）</summary>

<br>

```text
Run anmol098/waka-readme-stats@master
  ...
  raise Exception("Something went wrong")
{"error": "API Keys are only for plugins, use your personal oauth token instead."}
```

- **A.** token 过期了
- **B.** 仓库权限没给够
- **C.** 服务方把 API Key 降级成"只写"，读取统计必须改用 OAuth

<details>
<summary>答案</summary>

**C。** 最坑的地方是：Key 本身没坏，写还照常写，只有读被拦——所以报错信息里那句 "only for plugins" 才是唯一线索。

我的处理不是"换个 Key 再试一次"，而是给流水线加了道**凭证预检**：跑之前先探一次，探不通就直接给一句人话，别再让人对着两分钟的 Python traceback 猜。

</details>

</details>

<details>
<summary><b>③ 轮到你了</b>（三个按钮，都是真能按的）</summary>

<br>

<table>
<tr>
<td align="center" width="33%"><a href="https://github.com/mijaclan/mijaclan/issues/new?title=%F0%9F%90%9B%20%E6%88%91%E6%8C%91%E5%88%B0%E4%B8%80%E6%A0%B9%E5%88%BA&body=%E5%9C%A8%20README%20%E7%9A%84%E5%93%AA%E4%B8%80%E5%9D%97%E7%9C%8B%E5%88%B0%E7%9A%84%EF%BC%9A%0A%0A%E6%88%91%E7%9C%8B%E5%88%B0%E7%9A%84%E9%97%AE%E9%A2%98%EF%BC%9A%0A%0A%E5%BB%BA%E8%AE%AE%E6%80%8E%E4%B9%88%E6%94%B9%EF%BC%9A%0A">🐛 <b>挑个刺</b></a><br><sub>这页哪儿写得不对、坏了、丑了</sub></td>
<td align="center" width="33%"><a href="https://github.com/mijaclan/mijaclan/issues/new?title=%F0%9F%92%A1%20%E6%88%91%E6%9C%89%E4%B8%AA%E6%83%B3%E6%B3%95&body=%E6%83%B3%E8%A6%81%E7%9A%84%E5%8A%9F%E8%83%BD%20%2F%20%E6%83%B3%E7%9C%8B%E7%9A%84%E6%A0%8F%E7%9B%AE%EF%BC%9A%0A%0A%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A7%89%E5%BE%97%E6%9C%89%E7%94%A8%EF%BC%9A%0A">💡 <b>提个需求</b></a><br><sub>想让我写点什么、加个栏目</sub></td>
<td align="center" width="33%"><a href="https://github.com/mijaclan/mijaclan/issues/new?title=%F0%9F%91%8B%20%E8%B7%AF%E8%BF%87%E6%89%93%E4%B8%AA%E6%8B%9B%E5%91%BC&body=%E9%9A%8F%E4%BE%BF%E8%AF%B4%E7%82%B9%E5%95%A5%E9%83%BD%E8%A1%8C%EF%BC%8C%E6%AF%94%E5%A6%82%E4%BD%A0%E6%9C%80%E8%BF%91%E5%9C%A8%E6%8A%98%E8%85%BE%E4%BB%80%E4%B9%88%EF%BC%9A%0A">👋 <b>打个招呼</b></a><br><sub>聊聊你最近在折腾啥</sub></td>
</tr>
</table>

</details>

---

## 🤖 我怎么用 agent（这才是重点）

我不把它当"高级补全"，当一个**能自己跑起来、会查证据、会写结论的执行者**。

```text
需求  →  侦察（日志 / 仓库 / 浏览器）  →  方案 + 风险  →  我签字  →  改 + 验证  →  留证据
```

分工是死的：**它跑腿，我拍板。** 涉及凭证、线上数据、删东西——一律回到我手上。

**三个真跑过的活儿**（都发生在这仓库或它周边，不是 PPT）：

- **CI 天天红** → 让它读 Actions 日志、判断是代码问题还是上游变了 → 得出"API Key 被降级成只写"这个结论，顺手加了预检：2 分钟的 traceback 变成 5 秒的中文报错。
- **接口返 202** → 大家以为是"没数据"，它翻文档确认是"统计还在算" → 改成轮询等待，README 再没写出过半空的周报。
- **浏览器里的破事** → 让它驱动真实浏览器改 secret、审页面渲染 → 省掉手动点击，还揪出三个挂掉的外部组件。

**我的三条规矩**：

1. 结论必须带证据——run id、日志行、截图，缺一样就不算完。
2. 只读的活随便跑，写入的活先问我。
3. 每次翻车留一条能复现的路径，同一个坑不踩第二次。

<p align="center">
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor" />
  <img src="https://img.shields.io/badge/GitHub%20Copilot-8957E5?style=flat-square&logo=githubcopilot&logoColor=white" alt="Copilot" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/MCP-1F6FEB?style=flat-square" alt="MCP" />
</p>

---

## 🧰 工具箱 · 2026

<p align="center">
  <img src="https://img.shields.io/badge/Go-1.27-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go 1.27" />
  <img src="https://img.shields.io/badge/Java-25%20LTS-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 25 LTS" />
  <img src="https://img.shields.io/badge/TypeScript-6.0-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript 6.0" />
  <img src="https://img.shields.io/badge/Python-3.15-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3.15" />
  <img src="https://img.shields.io/badge/Rust-1.100-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust 1.100" />
  <img src="https://img.shields.io/badge/Kotlin-2.4-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin 2.4" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-26%20LTS-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node 26 LTS" />
  <img src="https://img.shields.io/badge/React-19.3-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19.3" />
  <img src="https://img.shields.io/badge/Next.js-16.4-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16.4" />
  <img src="https://img.shields.io/badge/Vite-8.3-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite 8.3" />
  <img src="https://img.shields.io/badge/FastAPI-0.143-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-18-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL 18" />
  <img src="https://img.shields.io/badge/Redis-8.x-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis 8.x" />
  <img src="https://img.shields.io/badge/MongoDB-9.0-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB 9.0" />
  <img src="https://img.shields.io/badge/MySQL-9.7-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL 9.7" />
  <img src="https://img.shields.io/badge/Docker-29-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker 29" />
  <img src="https://img.shields.io/badge/Kubernetes-1.37-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes 1.37" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-CI-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## 📊 数据面板

> 数字放在最后是有原因的：它不会骗人，但它也不会解释自己。

<p align="center">
  <img src="https://streak-stats.demolab.com?user=mijaclan&theme=default&hide_border=true&locale=en" alt="streak" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mijaclan&theme=github" alt="GitHub 统计总览" />
</p>

<sub>↓ 下面这段由 GitHub Actions 每天自动抓 WakaTime 生成，人工零干预——包括它给我统计出我是个早鸟这件事。</sub>

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-706%20hrs%2026%20mins-blue?style=flat)

**🐱 My GitHub Data** 

> 📜 31 Public Repositories 
 > 
> 🔑 12 Private Repositories 
 > 
**I'm an Early 🐤** 

```text
🌞 Morning                1338 commits        ████████████░░░░░░░░░░░░░   47.30 % 
🌆 Daytime                280 commits         ██░░░░░░░░░░░░░░░░░░░░░░░   09.90 % 
🌃 Evening                168 commits         █░░░░░░░░░░░░░░░░░░░░░░░░   05.94 % 
🌙 Night                  1043 commits        █████████░░░░░░░░░░░░░░░░   36.87 % 
```

 Last Updated on 17/11/2026 08:17:37 UTC
<!--END_SECTION:waka-->

---

## 🎲 一点不正经的

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="dev quote" />
</p>

<details>
<summary>👀 点开看几句碎碎念</summary>

<br>

- 我的提交曲线是双峰：早上七点一波，深夜十一点一波——下午通常在跟别人讲话
- 给自己的脚本写脚本，是件很快乐的事
- 最常用的"框架"其实是 `git log` 和 `curl`
- 这个 README 里的统计段，本来就是 agent 在维护
- 三年前立志"每天提交"，然后被 streak 统计绑架至今

</details>

---

<p align="center">
  <a href="https://github.com/mijaclan"><img src="https://img.shields.io/badge/Follow-1F6FEB?style=flat-square&logo=github&logoColor=white" alt="Follow" /></a>
  <a href="https://github.com/mijaclan/mijaclan"><img src="https://img.shields.io/badge/%E7%82%B9%E4%B8%AA_Star-FFC53D?style=flat-square&logoColor=black" alt="点个 Star" /></a>
</p>

<p align="center">
  <sub>看到这儿了，说明你比 90% 的访客有耐心。</sub>
</p>

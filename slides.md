---
theme: seriph
background: /background.png
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## 个人作品集
drawings:
  persist: false
defaults:
  foo: true
transition: slide-left
title: Zain的作品集
mdc: true
---

# 作品集

By ZainCheung

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    空格或者点击进入下一页 <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
作品集
-->


---
layout: default
hideInToc: true
---

# 操作指南

## Keyboard Shortcuts

|     |     |
| --- |-----|
| <kbd>right</kbd> / <kbd>space</kbd>| 下一页 |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | 上一页 |
| <kbd>up</kbd> | 上一页 |
| <kbd>down</kbd> | 下一页 |

---
layout: default
hideInToc: true
---

# 目录

<Toc maxDepth="1"></Toc>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    空格或者点击进入下一页 <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
导航
-->

---
src: ./pages/introduce-self.md
hide: false
---

<!--
自我介绍
-->

---
src: ./pages/sleep.md
hide: false
---
<!--
睡眠功能
-->

---
src: ./pages/location.md
hide: false
---
<!--
定位功能
-->

---
src: ./pages/play.md
hide: false
---
<!--
玩手机功能
-->

---
src: ./pages/report.md
hide: false
---
<!--
每日报告
-->

---
src: ./pages/arrive.md
hide: false
---
<!--
到达提醒
-->

---
src: ./pages/track.md
hide: false
---
<!--
轨迹
-->

---
src: ./pages/message.md
hide: false
---
<!--
系统消息
-->

---
src: ./pages/notify.md
hide: false
---
<!--
消息通知
-->

---
src: ./pages/renew.md
hide: false
---
<!--
用户续费
-->

---
src: ./pages/user-data.md
hide: false
---
<!--
用户数据分析
-->

---
layout: center
hideInToc: true
---

# 感谢观看！

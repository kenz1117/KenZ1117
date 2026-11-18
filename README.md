### Hi, I'm Ken (@kenz1117) 👋

DeepSeek Harness（DSH）插件作者。所有插件一行安装，均已收录 [awesome-dsh-plugin](https://github.com/kenz1117/awesome-dsh-plugin) 精选列表与 [dsh-market](https://github.com/dsh-market/dsh-market) 应用市场。

---

## 🧩 DSH 插件集

### 📊 [dsh-ui-usage-billing](https://github.com/kenz1117/dsh-ui-usage-billing) · 用量费用仪表盘

侧边栏实时成本胶囊 + 全量仪表盘弹窗。用量从会话日志真实聚合，按多供应商价目计价；峰谷跟随模型、支持订阅额度与历史规则时间线，子智能体费用归并。

![npm version](https://img.shields.io/npm/v/@kenz1117/dsh-ui-usage-billing) ![npm downloads](https://img.shields.io/npm/dm/@kenz1117/dsh-ui-usage-billing) ![GitHub stars](https://img.shields.io/github/stars/kenz1117/dsh-ui-usage-billing?style=social)

```sh
dsh plugin --profile web add npm:@kenz1117/dsh-ui-usage-billing@latest
```

<p align="center">
  <a href="https://github.com/kenz1117/dsh-ui-usage-billing">
    <img src="https://raw.githubusercontent.com/kenz1117/dsh-ui-usage-billing/main/screenshots/demo.gif" width="640" alt="dsh-ui-usage-billing 仪表盘演示">
  </a>
</p>

---

### 🧠 [dsh-engram](https://github.com/kenz1117/dsh-engram) · 记忆宫殿

跨会话长期记忆：每条记忆钉在「房间#桩位」坐标上，固定路线定检索顺序。23 个窄参数工具，FTS5 + 本地向量混合检索、证据门、全链路审计、SM-2 间隔重复复习；纯本地 SQLite，零外部服务、零 API Key。

![npm version](https://img.shields.io/npm/v/@kenz1117/dsh-engram) ![npm downloads](https://img.shields.io/npm/dm/@kenz1117/dsh-engram) ![GitHub stars](https://img.shields.io/github/stars/kenz1117/dsh-engram?style=social)

```sh
dsh plugin --profile web add @kenz1117/dsh-engram
```

---

### 🌈 [dsh-ui-rainbowspeak](https://github.com/kenz1117/dsh-ui-rainbowspeak) · 虹语 + 桌宠「小虹」

聊天输入框的彩虹跑马灯边框 + 住在窗口里的吧唧球桌宠「小虹」。边框即会话状态：干活加速、等你琥珀脉冲、出错红色脉冲、完成庆祝闪光，可选「柔光外溢」；五颗糖果球是五个独立角色（红红傲娇 / 黄黄慵懒 / 粉粉憨萌 / 蓝蓝理性 / 绿绿暴躁），逐像素复刻，会看你的指针、戳一下果冻回弹，庆祝只以宿主回合边界为准。

![npm version](https://img.shields.io/npm/v/@kenz1117/dsh-ui-rainbowspeak) ![npm downloads](https://img.shields.io/npm/dm/@kenz1117/dsh-ui-rainbowspeak) ![GitHub stars](https://img.shields.io/github/stars/kenz1117/dsh-ui-rainbowspeak?style=social)

```sh
dsh plugin add @kenz1117/dsh-ui-rainbowspeak
```

<p align="center">
  <a href="https://github.com/kenz1117/dsh-ui-rainbowspeak">
    <img src="https://github.com/user-attachments/assets/16fbd528-3d17-47de-aa87-3e0f768cfdf8" width="560" alt="RainbowSpeak 桌宠「小虹」与彩虹边框">
  </a>
</p>

---

## 🔗 DSH 生态

- [awesome-dsh-plugin](https://github.com/kenz1117/awesome-dsh-plugin) — DSH 插件精选列表（我维护）
- [dsh-hyrealai-fde](https://github.com/kenz1117/dsh-hyrealai-fde) — Hyreal FDE 工作台插件
- [deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) — 宿主本体：Everything is a Plugin.

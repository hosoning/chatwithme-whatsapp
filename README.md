# chatwithme-whatsapp

WhatsApp-style front-end for the same ChatWithMe data room.

It intentionally keeps the original Firebase project and shared sync schema, so the WeChat-style PWA and this WhatsApp-style PWA can read/write the same conversations.

chatwithme-whatsapp/
├── index.html
├── style.css
├── manifest.json
├── sw.js
├── icon/
└── js/
    ├── tarot.js       // 78张塔罗牌数据 + 抽牌逻辑
    ├── wordcards.js   // 字卡 CRUD（localStorage）
    ├── ai.js          // AI 理解/决策逻辑（本地兜底 + 大模型接口预留）
    └── app.js         // 主程序：UI 渲染 + 交互 + 状态管理

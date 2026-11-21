# Hi, I'm Max

**English:** Software engineering leader (C#/.NET, device–cloud–app IoT). Below: a four-layer .NET 10 showcase series, from MQTT device connectivity to the hotel guest-room experience, plus my Claude Code skills.

## 關於我

我是 Max，長期使用 C#/.NET 的軟體工程主管，關注裝置—雲端—App 的 IoT 架構（MQTT、自助機、智慧門鎖、旅宿系統），以及工程管理與交付。
下面這組作品把一套旅宿 IoT 系統拆成四個層次，每一層各自獨立成一個可執行的 .NET 10 範例。

## 旅宿 IoT 四層系列

四個專案都是技術展示：純軟體模擬、使用虛構資料（虛構旅宿連鎖 Nestay），與任何真實企業無關。

```
客房體驗   room-control-pad      Pad 中控台 ─ MQTT ─ Gateway ─ 裝置
機隊維運   kiosk-fleet-monitor   狀態模型、離線偵測、RBAC 與稽核
發卡層     card-dispenser-kiosk  發卡流程、fallback、Mifare/DESFire
連線層     smartlock-mqtt        指令可靠性、MQTT 連線與上下線
```

| 層 | 專案 | 展示重點 | Demo |
|---|---|---|---|
| 連線層 | [smartlock-mqtt-dotnet](https://github.com/MaxCHL/smartlock-mqtt-dotnet) | 智慧門鎖 MQTT：冪等指令、TTL、狀態機、Last Will | [架構圖](https://maxchl.github.io/smartlock-mqtt-dotnet/architecture.html) |
| 發卡層 | [card-dispenser-kiosk-dotnet](https://github.com/MaxCHL/card-dispenser-kiosk-dotnet) | 自助報到機驅動發卡機：各種 fallback、Mifare / DESFire、離線 data-on-card | [流程圖](https://maxchl.github.io/card-dispenser-kiosk-dotnet/flow.html) |
| 機隊維運 | [kiosk-fleet-monitor-dotnet](https://github.com/MaxCHL/kiosk-fleet-monitor-dotnet) | 機隊狀態模型、心跳逾時離線偵測、RBAC 與稽核紀錄 | [監控 Dashboard](https://maxchl.github.io/kiosk-fleet-monitor-dotnet/) |
| 客房體驗 | [room-control-pad-dotnet](https://github.com/MaxCHL/room-control-pad-dotnet) | 客房 Pad 的 MQTT 軟體層；Zigbee / DALI / IR / KNX 收在 Gateway 之後 | [Pad 中控台](https://maxchl.github.io/room-control-pad-dotnet/) |

## craft-skills

[craft-skills](https://github.com/MaxCHL/craft-skills) 是一組 Claude Code skills：`pm-craft`（規格先行的 PM 文件流程）、`design-craft`（HTML 原生視覺設計）、`pptx-craft`（有風格的 PowerPoint）。

```bash
npx github:MaxCHL/craft-skills
```

## 技術重點

C# / .NET 10 · MQTT / MQTTnet · 狀態機與冪等設計 · xUnit · GitHub Pages

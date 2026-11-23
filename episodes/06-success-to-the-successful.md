# 第 6 集｜為什麼用的人越多，這個平台就越強？富者愈富

▶ [看影片](https://youtube.com/shorts/HeDMMTo64FU)　｜　[回到索引](../README.md)

## 核心觀念

兩方爭同一批有限的資源時，**一開始領先的一方會分到更多，下一輪就更領先**；落後的一方分到更少，更難追上。這個結構叫 Success to the Successful（富者愈富），本質上是兩個互相推開的增強環路。

## 重點整理

- **從哪裡來**：1990 年 Senge《第五項修練》把它列為九個基模之一；1998 年 Kim & Anderson 的工作手冊用 Success to the Successful 講解。（中文名「富者愈富」依 Senge 1994 天下雜誌的譯名。）
- **書裡的例子**（意譯、精簡）：主管帶兩位能力相當的實習生；其中一位 Terry 病假一週，主管多帶 Alex；Alex 進步較快，主管更常帶他；結果只有 Alex 獲得錄取。
- **畫成結構**：兩個增強環路，R1 與 R2。
  - R1：A 成功 → 分到更多資源 → A 更成功
  - R2：B 分到較少 → 更難成功 → 分到更少
  - Kim 的提醒（意譯）：勝負常取決於起始條件，不一定是誰比較好。
- **對照例：NVIDIA 的 CUDA**。黃仁勳說開發者來到一個運算平台，是因為裝機量（install base）大；所以 NVIDIA 先把 CUDA 放進每一台 GeForce，把裝機量養起來；裝機量大了，開發者支援 CUDA 的理由就更充分。

```mermaid
flowchart LR
    I["裝機量大"] -->|"+"| D["開發者跟進"]
    D -->|"+"| P["平台更好用"]
    P -->|"+"| I
```

（R：裝機量與開發者互相推高。**這張環路圖是本頻道的對照，不是黃仁勳或原書畫的。**）

- **帶走三問**：誰在爭同一批有限資源？領先的一方，優勢怎麼放大？落後的一方，是不夠好，還是沒機會？

## 引文（黃仁勳；Lex Fridman Podcast #494，官方人工逐字稿）

> "…They come to a computing platform because the install base is large."
> — 約 00:11:27

**意譯**：他們（開發者）來到一個運算平台，是因為裝機量大。

> "…we ought to put CUDA on GeForce and put it into every single PC whether customers use it or not…"
> — 約 00:13:29

**意譯**：我們應該把 CUDA 放上 GeForce，放進每一台 PC，不管客戶有沒有用到。

> "…if I support CUDA, tomorrow it'll be 10 times better. I just have to wait six months on average."
> — 約 01:16:17

**意譯**：（開發者的想法是）只要我支援 CUDA，明天就會好上 10 倍；我平均只要等半年。

## 推導與備註

- **推導**：把 CUDA 的裝機量與開發者畫成增強環路，是我們的對照，不是黃仁勳或原書的說法。
- 原書例子（MutualLife 故事）是我們意譯、精簡後的版本。
- 本頻道與 NVIDIA 無關聯。

## 來源

- Daniel Kim & Virginia Anderson, *Systems Archetype Basics*, 1998（Section 7）
- Peter Senge, *The Fifth Discipline*, 1990（⚠️ 僅背景）
- Lex Fridman Podcast #494, Jensen Huang，官方逐字稿，2026

（完整資訊見 [references.md](../references.md)）

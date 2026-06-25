# TCP/IP 網路協議：互聯網的基石

西元 1984 年，[TCP/IP 協議](https://zh.wikipedia.org/wiki/TCP/IP)已經在 ARPANET 上穩定運行，並正式成為美國國防部的網路標準。這套協議為日後的[互聯網](https://zh.wikipedia.org/wiki/互聯網)奠定了基礎。

## TCP/IP 的架構

TCP/IP 採用四層架構：

| 層次 | 功能 | 協議範例 |
|------|------|----------|
| 應用層 | 應用程式間通信 | HTTP, FTP, SMTP |
| 傳輸層 | 主機間端到端通信 | TCP, UDP |
| 網路層 | 路徑選擇和轉發 | IP, ICMP |
| 網路介面層 | 實際網路傳輸 | Ethernet, PPP |

## TCP 與 IP 的分工

### IP（網路層）
- 負責將資料包從源地址傳送到目標地址
- 提供不可靠的「最大努力」傳輸
- 不保證交付順序

### TCP（傳輸層）
- 在 IP 基礎上提供可靠的連接導向服務
- 確保資料按序到達、不重複、不丟失
- 流量控制和擁塞控制

## 標準化歷程

TCP/IP 的標準化經歷了以下階段：

### 1970 年代初期
Vint Cerf 和 Bob Khan 設計了 TCP/IP 協議。

### 1983 年 1 月 1 日
ARPANET 完成從 NCP 到 TCP/IP 的切換。

### 1984 年
TCP/IP 成為美國國防部所有網路的標準。

### 1989 年
TCP/IP 在 BSD Unix 中的實現促進了普及。

## 對後世的影響

TCP/IP 的發明和標準化對互聯網和社會產生了深遠影響：

### 全球互聯
TCP/IP 使全球不同網路之間的互聯成為可能。

### 開放標準
TCP/IP 的開放性促進了技術的快速採用。

### 創新加速
任何人都可以在 TCP/IP 基礎上開發新應用。

### 數位革命
TCP/IP 為電子商務、社交媒體、雲端運算奠定了基礎。

## 歷史意義

TCP/IP 的發明是互聯網歷史上最重要的事件之一。這套簡單優雅的協議，連接了全球數十億設備，改變了人類溝通和協作的方式。

延伸閱讀：
- [維基百科：TCP/IP](https://zh.wikipedia.org/wiki/TCP/IP)
- [維基百科：互聯網](https://zh.wikipedia.org/wiki/互聯網)
- [維基百科：Vint Cerf](https://zh.wikipedia.org/wiki/Vint_Cerf)
- [Google 搜尋：TCP/IP 1984 標準化](https://www.google.com/search?q=TCP+IP+1984+standardization
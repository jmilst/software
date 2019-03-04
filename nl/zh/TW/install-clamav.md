---
copyright:
  years: 1994, 2017
lastupdated: "2017-09-26"

subcollection: software
---
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# 安裝 ClamAV

使用此程序，以安裝 ClamAV。

1. 在 https://x.x.x.x:2087 上登入 WHM（將 x.x.x.x 取代為您的伺服器 IP）
2. 按一下畫面最右側的 cPanel 圖示。
3. 按一下**管理外掛程式**圖示，以檢視 cPanel 外掛程式清單。
4. 在**附加程式模組**頁面上，找到 **clamavconnector**。啟用**安裝及保留已更新項目**，然後按一下頁面結尾的**儲存**。
安裝大約需要 20 分鐘才能完成。

**附註**：依預設，會停用 lib 版本檢查。不過，伺服器應該已安裝 zlib 1.2.2 或更新版本。

授權是最常見的 ClamAV 安裝失敗原因。clamav 附加程式是免費的，不過，您需要登錄為專業授權。如需相關資訊，請參閱 `https://www.clamav.net/`。正確地登錄授權之後，請回到步驟 4，並解除安裝，然後重新安裝 clamavconnector。

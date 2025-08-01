TEST-2-UART to 電腦
===
UART與電腦互相通訊
---
# 內容
- 開發板連結至電腦之UART，使用此UART與電腦進行通訊。
- 與TEST-1使用輪詢方式不同，此練習使用中斷方式進行傳輸、接收，也更接近實用。
---
## 描述
- 練習STM32如何使用UART並與電腦連接，互相通訊。
- MCU傳送"Hello world"給電腦。
- 電腦收到"Hello world"，人工操作回傳4 byte data給MCU。
- 於MCU debug模式確認是否有接收到電腦回傳data。
---
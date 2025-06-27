# AGENTS.md -這個是關於適用 SEMI E88規範 控制erack

## 專案結構
/test_se/erack/GyroErackAdapter_e88.py - 複製與 e88_mirle_equipment.py 和 GuiErackSimulator.py溝通

/test_se/secsgem/* 負責接收HOST送過來的指令/事件 和發生指令/事件給HOST 同時會跟e88_mirle_equipment.py 通信

## 需要實現功能
- 各種remote功能(後續補充)

- 各種secsgem查詢變數，和上報(後續補充)

## 程式價格
- 能兼容python2.7和python3.8
- logger 或print都要用.format
- 註解可以使用英文

## 回答內容
- 使用台灣用於繁體中文

## 修改程式
- 需要提供Pull Request 

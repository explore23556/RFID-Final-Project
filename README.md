# RFID-Final-Project
<br>
<p align="center">
<img src="https://github.com/explore23556/RFID-Final-Project/blob/main/%E5%9C%96%E7%89%877.png"; width="40%";/>
</p>
  
## 一、專案摘要
### 新進學生初到校園，對校園的設施與環境皆很生疏，而以往的作法是學長姊在特定時間，帶著學弟妹們一一走訪校園，但由於Covid-19的關係，多人的團體行動是不被允許的。因此，本專案在學生常去的地點建置RFID讀卡器，讓學生們能夠透過學生證刷卡的方式，來自動地接收含有該地點重要資訊的郵件，以及學生到訪的紀錄來讓班導師查閱。
## 二、我在專案中負責的工作
### 我主要是負責RFID-MFRC522模組感應卡片資訊、ESP32的WiFi功能將資料傳輸至Firebase資料庫以及透過SMTP協定來將HTML格式的郵件寄至學生信箱。
## 三、專案架構
### 此專案主要是藉由ESP32微控制器來接收RFID卡片的資訊(UID)，然後再使用ESP32的WIFI功能將資料上傳至雲端資料庫firebase來儲存資料。此外，在PC端則是會透過python程式來擷取firebase的資料，然後再透過簡單郵件傳輸協定(SMTP)來將HTML格式的郵件寄給學生。
<br>
<p align="center">
<img src="https://github.com/explore23556/RFID-Final-Project/blob/main/%E5%9C%96%E7%89%878.png"; width="60%";/>
</p>

## 四、展示影片
### [影片連結](https://www.youtube.com/watch?v=HjIhahJ6sq8)


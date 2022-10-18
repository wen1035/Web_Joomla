# 在自己的電腦上建立 Joomla 網頁伺服器
### 用CSS、HTML和JavaScript撰寫小型專案
1. 純文字編輯器
  * NotePad++
2. 下載 XAMPP 並安裝和啟用
   * 先回到 XAMPP 網頁管理台，按下左邊的「安全」連結，會看到安全性設定頁面然後替 MySQL 的 root 帳號設定密碼  
3. 用 phpMyAdmin 存取資料庫
  * 設定完成後，我們在網址列輸入 localhost/phpmyadmin 就會進到 phpMyAdmin 的介面，輸入 root 的帳號與剛剛更改的密碼
4. 下載 Joomla 並安裝和啟用
  * 安裝和啟用後，輸入 http://localhost/joomla/administrator 可進入後台
  
# CMS 的核心架構
### Joomla CMS 由三個層次所組成，分別是框架層(framework)、應用層(application)與套件層(extension)
* **Framework 框架層**
  * 框架層包含核心 Framework 函式庫與許多第三方函式庫
  * 需要運用框架層編寫新的程式，可以由 JApplication 繼承出自己的應用層來使用
  
* **Application 應用層**
  *CMS 中的前台與後台各自就是一個框架層延伸出來的客戶端應用層，而安裝程式也是一個應用層，所以 CMS 下載回來時，總共有三個應用層
* **Extension 套件層**  
	 * 在應用層之上，就是各式各樣豐富的擴充套件(Extension)
	 * 套件分成幾個大類別: 元件、模組、外掛與模板，還有其他輔助的類別

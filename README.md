** 此為 Fire.app 製作的 prototype ， 需用 Fire.app Watch **    
或可在 http://miau715.github.io/eo4/index.html 直接查看 prototype 頁面。

## eo4 User Story
===
### 角色

1. 訪客：未登入的人
2. 使用者：已登入的人  
3. 接手工作者
4. 專案相關人員
5. 發包工作者
6. 專案管理者

權限：專案管理者 > 發包工作者 >= 專案相關人員 = 接手工作者 >= 使用者 > 訪客

### 訪客

1. 可瀏覽目前待認領和進行中的工作
2. 可瀏覽目前待認領和進行中的工作之詳細內容

### 使用者

1. 可在工作詳細內容頁面之討論區留言（可針對工作內容詢問細節以決定是否接下工作）
2. 可訂閱某一工作，在該工作頁面被更新時收到通知（包含討論板及接下工作後的進度更新）
3. 可取消訂閱已訂閱的工作
4. 可在「我參與的工作」頁面看見自己接手的工作、發包的工作、關注中的工作與已完成的工作
5. 可點擊「發包工作」，輸入要發包的工作內容送出後成為發包工作者
6. 可在工作詳細內容頁面點擊按鈕接手該工作，成為接手工作者。
7. 可在設定頁面設定自己的 email 與是否接收關注專案的訊息
8. 登入後即可看見自己關注中的工作有幾則已更新，點擊下拉選單即可看見工作名稱，再點擊名稱即可連結至該頁面

### 接手工作者

1. 接手工作後直接成為專案相關人員
2. 可以在工作詳細內容頁面發表進度更新

### 專案相關人員

1. 預設訂閱該專案的所有相關工作更新
2. 可取消訂閱全專案/單一工作的更新訊息

問題：不確定是否有哪個地方已經整理各參與人員的所屬專案，若無法直接取得此部份的資料，可能要由專案管理者進行設定。

### 發包工作者

1. 可在工作詳細內容頁面選擇編輯及變更專案狀態：
   1. 編輯專案內容
   2. 確認工作完成後將此工作的狀態設定為「已完成」
   3. 工作無法完成時可進行「重新發包」

### 專案管理者

問題：同樣不確定是否有方法取得專案參與人員的資料，若無法取得則需要從設定介面進行設定

1. 可新增其他專案管理者
2. 可取消自己的專案管理者身分（如果是最後一位管理者則不可取消）


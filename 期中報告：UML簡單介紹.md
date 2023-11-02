<h1>期中報告：UML簡單介紹(十八)——组件圖的基本概念與實利解析</h1><br>
<h2>1、組件圖</h2>
<p> 組件圖又被成為構件圖，主要用於靜態建模，是表示構件類型的組織以及各種構件之間依賴關係的圖。組件圖透過對組件間依賴關係的描述來估計系統構件的修改對系統可能帶來的影響。</p>
<h2>2、事務</h2>
<p>可替換的實體部分包括軟體程式碼、腳本或命令列文件，也可以表示運行時的對象，文檔，資料庫等。節點(node)是運行時的物理對象，代表一個電腦資源。事務的圖示如下：</p>

![image](https://github.com/Roseller37/UML-diagram/blob/main/%E4%BA%8B%E5%8B%99.png)

<h2>3、關係</h2>
<p>元件圖中的關係也比較簡單，主要是依賴和實作等，如下：</p> 

![image](https://github.com/Roseller37/UML-diagram/blob/main/Relationships.png)

<h2>4、實例</h2>
<p>圖中的構件名稱是Dictionary字典。該構件向外提供兩個接口，即兩個服務Spell-check拼寫檢查、Synonyms同義詞</p>

![image](https://github.com/Roseller37/UML-diagram/blob/main/Instance_1.png)

<p>圖中「Planner計畫者」構件向外提供一個「update更新」介面服務。同時，此構件要求外部介面提供一個「Reservations預定」服務。</p>

![image](https://github.com/Roseller37/UML-diagram/blob/main/Instance_2.png)

<h2>5.購票流程</h2>
<h2>5.1 情境描述</h2>
<p>情境一：

購買個人票可以透過公用資訊亭訂購也可直接向售票員購買，但購買團體票只能透過售票員。

情境二：

買票的人可以根據任意選擇預訂銷售或個人銷售或團體銷售中的一種方式，售票處為了方便銷售，需要信用卡付款服務的支持，同時也必然需要票數據庫處在有票可賣的狀況中。

圖示如下</p>

![image](https://github.com/Roseller37/UML-diagram/blob/main/%E8%B3%BC%E7%A5%A8%E6%B5%81%E7%A8%8B.png)

<h2>5.2 圖示關係</h2>

圖中依賴關係包括：顧客需要資訊亭介面提供服務

售票員需要職員介面提供服務

信用卡付款需要信用卡代理提供服務

職員介面需要預約銷售、個人銷售和團體銷售提供服務

管理介面需要資料庫狀態提供服務

售票處需要付款和購買提供服務


圖中實現關係包括：

信用卡付款提供付款服務

票資料庫提供購買和狀態查詢服務

售票處提供預訂購買、個人購買和團體購買服務

<hr>
<h1>參考資料</h1>
https://l.facebook.com/l.php?u=https%3A%2F%2Fblog.csdn.net%2Fljtyzhr%2Farticle%2Fdetails%2F46537513%3Futm_medium%3Ddistribute.pc_feed_404.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-5-46537513-blog-null.262%255Ev1%255Epc_404_mixedpudn%26depth_1-utm_source%3Ddistribute.pc_feed_404.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-5-46537513-blog-null.262%255Ev1%255Epc_404_mixedpud&h=AT0VRoP0F0zSNm6TPf0v3CuqKtb_fRUrASTpBnkFs6GizGl8VnlyI7DPbzBIYDHmYR1xuVT6Cc4FRR3iI1QWVxyxxmBQJ0n4BbZcJpro5p9vUPQ4R2xzyXM9t78NkE9Mwm8N4v9dMn5d9Kg&s=1

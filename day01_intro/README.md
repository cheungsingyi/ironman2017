## 第一天: 介紹文

![30天的主題大綱](https://github.com/eyesofkids/ironman2017/blob/master/day01_intro/asset/toc.png?raw=true)

大家好！我是Eddy。今天是鐵人賽的第一天，我個人是第一次參加，也沒在討論區中回答過什麼問題，可能按照前輩們所說的資格建議，是完全不符合。IT邦幫忙是一個很好的園地，但對於像我們這種網站程式開發領域的開發者來說，上面的JavaScript或相關技術的問答很少，就算是大神也無用武之地。尤其在現今像社群網站Facebook(FB)相當流行的年代，許多問答都集中到FB中的相關社團裡面，現在的技術性討論區網站已經不是很流行，更不用說像PTT裡面的相關技術討論版，每個月的問答主題少之又少，這是一個現實的趨勢。

當然，在社群網站上進行技術問答有很明顯的問題。首先，它無法被有效地的組織與保存下來，作為日後其他發生同樣問題開發者參考。其次，像以FB來說，它無法被有效地被搜尋，就算Google有再強大的搜尋引擎，仍然無法跨過FB所設限的世界之中。而另一個非常明顯的問題是，社群網站上的充斥各種訊息，雜亂而永無止盡，不論是與你有關的、無關的、朋友的、朋友的朋友的、各種像是新聞又不太像新聞的充斥其中，這當然可以滿足每個使用者打發時間、愛八卦或愛現的心理。但實際上對於一個技術開發者來說，除了分心之外沒有太多的幫助。我個人還是比較認同獨立的與專門的技術社群，所以還是支持一下IT邦幫忙的活動。

那為何我要來參加鐵人賽？主要當然是我認同鐵人賽的精神 -

> "用30天向世界宣告，這一年鋼鐵般的IT歷練"

在這一年之中，我仔細地再重頭開始學習ES6，這對於所有的已經熟悉JavaScript的開發者而言，都是一個全新的學習階段。而從這一年的學習過程中，我清楚的明白一件事，就是React與Redux本身的設計都不難理解，困難的是來自沒有紮實的ES6與JavaScript基礎，對於新式的語法當然會看不懂。

那麼我要如何說明我寫的教學文章，能夠真的讓讀者認為這些是對他(她)有幫助的？或者我寫出來的教學內容是讓讀者願意花時間來看的？

當然我已經學過也用過許多年的JavaScript程式，除此之外，我會要寫出一些已經作過的歷程，提供各位讀者作為參考，這些都是在2016年中才開始的:

第一在Gitbook上寫了兩本免費電子書，但有一些小章節還在增加與修改內容當中:

- [從ES6開始的JavaScript學習生活](https://www.gitbook.com/book/eyesofkids/javascript-start-from-es6/details)
- [從Promise開始的JavaScript異步生活](https://www.gitbook.com/book/eyesofkids/javascript-start-es6-promise/details)

第二當然是成立FB粉絲專頁與電子報，這是針對ReactJS的部份，目前只有經營半年左右，參與的人還不算多的:

- [ReactJS新聞 FB粉絲專頁](https://www.facebook.com/reactjs.tw/)
- [ReactJS電子報](https://reactjs-tw.top/)

最後，我會想參加這次的鐵人賽，除了重新檢視這一年以來學習的成果之外，也希望能吸引更多人來學習這些新的知識，然後一同參與交流。

## 文章內容說明

### 30天的主題大綱

這30天的大綱已經先列出來，本文的最上面有大圖片。主要分為四大部份:

- 工具篇(3篇): 介紹使用Node.js開發執行環境，使用的開發工具是微軟出品的Visual Studio Code，以及Babel、ESLint與Flow檢查工具。
- ES6(ES2015)篇(10篇): 介紹常用的幾個ES6標準中的新特性，大部份都會使用在React的開發上。
- React篇(10-12篇): 搭配簡單的幾個實作範例，學習React的使用方式。
- Redux篇(6篇): 從簡單的實作範例開始，到結合React使用。

由於時間上只有30天等於只有30篇文章，扣掉第一天的介紹文章，只剩29篇。所以最後有些文章主題可能會作刪減或修改。

在Github庫中已經列出來的每篇主題大綱:

- [30天的主題大綱](https://github.com/eyesofkids/ironman2017/blob/master/README.md)

### 寫作格式

在上面說的兩本電子書中，都有提及寫作風格的說明，鐵人賽的一系列文章也會遵照這個格式來寫作。主要的重點有幾個:

- 專有名詞: 對於專有名詞不進行中文翻譯，而是使用括號(())加註其後作為補充翻譯。例如`state(狀態)`。
- 符號: 對於符號儘可能在其後使用括號(())加註其後。例如`加號(+)`
- 不使用分號作為每行程式碼的結尾: 在使用JavaScript程式碼作為範例解說時，不使用分號(;)作為每行程式碼的結尾。
- 英文字詞解說: 針對重要的專業字詞，提供英文解說，並加入相關的字詞說明。

至於以下的部份由於時間的關係，無法一一作註解:

- 風格指引: 參考目前網路上知名的數個Javascript程式碼撰寫風格指引，提供在每個段落相關的建議。
- 讀音(用中文拼音): 使用"以中文讀音拼出英文字詞"的作法。

> 註: "不使用分號作為每行程式碼的結尾"是一種JavaScript程式撰寫的格式風格，詳細的內容可以參考這篇文章[JavaScript裡的語句用分號結尾是個選項嗎](http://eddychang.me/blog/javascript/97-js-semicolon.html)

## 其他的呈現方式

以下是為了本次鐵人賽所加入的幾個輔助的教學呈現方式:

### 圖片

圖片會使用於幾個地方:

#### 重點標註出每段文章

主要解說程式碼或文章內容的重點。下面是個展示:

![重點圖片](https://raw.githubusercontent.com/eyesofkids/ironman2017/master/day01_intro/asset/img_demo.png)

#### 展示簡單實作成果

這會使用gif圖片，展示實作成果的樣子。下面是個展示:

![gif圖片](https://github.com/eyesofkids/ironman2017/blob/master/day01_intro/asset/state.gif?raw=true)

### 影片

為方便解說操作的步驟，文章與圖片的敘述可能沒辦法很容易的解說步驟的進行，所以有些文章會特別錄製影片。所有的影片都會集中在這個Youtube頻道:

- [ReactJS 新聞](https://www.youtube.com/channel/UCKPwo1yvJsNx0dTqIoVyEgQ)

錄製的影片會以10分鐘以內為限，搭配解說的聲音，字幕如果有時間會加上。

## Github庫

我為本次鐵人賽新增了一個Github庫，內容包含所有的文章文字內容、圖片與程式碼範例，如果你看不到圖或文字、程式碼等等，可以到這裡去看。網址如下:

- ironman2017: [https://github.com/eyesofkids/ironman2017](https://github.com/eyesofkids/ironman2017)

## 問答與回饋

如果你對文章裡面的內容有問題，或是要給一些建議，可以利用以下的方式:

- [IT邦幫忙](http://ithelp.ithome.com.tw/)
- 到[Github庫](https://github.com/eyesofkids/ironman2017)發Issue
- 寫email給我([部落格](eddychang.me)上有email)

本文章也會在之後張貼到到我個人的[部落格](eddychang.me)與[segmentfault](https://segmentfault.com/u/eyesofkids)文章區中。

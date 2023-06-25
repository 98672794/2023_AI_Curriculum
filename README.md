# 2023_AI_Curriculum

ATW 生產力提升學院 

2023 AI 系列 - 2023 chatGPT應用課程


2023 chatGPT應用課程是一個介紹如何使用chatGPT這個人工智慧聊天機器人的課程。
chatGPT是由OpenAI開發的AI文本工具，它可以根據用戶的輸入和指示進行對話和生成內容。
這個課程的內容包括：

    1. ChatGPT 介紹、應用場景概述
        1.1 - 甚麼是 ChatGPT 
        1.2 - ChatGPT的應用場景

    2. ChatGPT 的基礎知識
        2.1 - 認識自然語言處理（NLP）
        2.2 - ChatGPT 模型結構與工作原理
        2.3 - ChatGPT 的限制與潛在挑戰

    3. 如何執行ChatGPT
        3.1 - 用Edge執行ChatGPT
        3.2 - 到官網執行ChatGPT

    4. ChatGPT註冊教學
        4.1 - 準備VPN
        4.2 - 註冊openai帳號
        4.3 - 購買境外電話號碼
     

- 如何在網頁版或桌面應用程序上使用chatGPT
- 如何設置和自定義chatGPT的參數和模式
- 如何利用chatGPT的插件和擴展功能²
- 如何評估和改進chatGPT的回答和生成品質
- 如何避免和處理chatGPT的錯誤和局限性


---

## 課程目錄：



### 1. ChatGPT 介紹、應用場景概述

    1.1 - 甚麼是 ChatGPT 

        ChatGPT是一個對話型的人工智能，不但能夠進行一問一答的交流，還能提出建議，及運用不同的語言來完成對話。
        2023年3月，ChatGPT從原有的ChatGPT-3.5正式升級至ChatGPT-4深度學習模型，不但具備更強大的理解及表達能力，還能支援影像輸入，廣泛應用於不同領域。

    1.2 - ChatGPT的應用場景

        1. 翻譯
            輸入英文或中文，ChatGPT 能翻譯成另一種語言。

        2. 修改文法錯誤
            輸入文字，ChatGPT 能判斷文法出錯之處，甚至能進一步要求程式解釋出錯原因及如何修正。

        3. 寫詩填詞
            輸入關鍵字，ChatGPT 能寫出符合主題、字數的詩詞或歌詞等文字創作。

        4. 整理文章重點
            輸入長篇的文字段落，ChatGPT 能分類並列出重點，適合會議記錄使用。

        5. 故事劇本創作
            輸入指令，要求特定格式，並且給予例子，ChatGPT 能完成短篇故事，甚至是角色對話的劇本。有人嘗試將 ChatGPT 結合圖像創作工具 MidJourney 完成圖文並茂的兒童繪本。

        6. 電郵回覆客戶
            輸入電郵收件內容，ChatGPT 能 撰寫回應信件，這有助處理日常大量客戶服務的對話。

        7. 編寫程式
            ChatGPT 不單懂得依據指令編寫程式，更能處理代碼壓縮、程序語言轉換（JavaScript 到 Python）、生成 SQL 語句等。



### 2. ChatGPT 的基礎知識

    2.1 - 認識自然語言處理（NLP）

        讓電腦擁有理解人類語言的能力，就是自然語言處理 (Natural Language Processing，縮寫 NLP)。

        以中文來說，第一步是斷詞、理解詞；第二步則是分析句子，包含語法及語義的自動解析。
        自然語言處理透過這兩個步驟，將複雜的語言轉化為電腦容易處理、計算的形式。早期是人工訂定規則。

        1980 年代末期，自然語言處理引進機器學習 (Machine Learning) 的演算法，不再用程式語言命令電腦所有規則，而是建立演算法模型，讓電腦學會從訓練的資料中，尋找資料所含的特定模式和趨勢。


    2.2 - ChatGPT 模型結構與工作原理

        當我們對 ChatGPT 有一些概念後，就可以繼續探究 ChatGPT 的關鍵技術了。
        ChatGPT 當中的「GPT」，其實代表「Generative Pre-trained Transformer」，中文譯作「生成型預先訓練變換模型」。

        GPT 是一種以網上數據作為訓練基礎的模型，背後數據庫擁有 1750億個參數，內容大部分來自網路，包括數十萬條維基百科條目、社交媒體貼文和新聞，能夠藉由學習人類生成的文字，做出自然的問答、文本摘要、翻譯、編寫代碼、對話等行為。

        從 2019年起，OpenAI 就致力改良並發展 GPT 的學習能力，而該技術也由最初的GPT-1，逐漸進化成 2020年的 GPT-3。而今日我們看到的 ChatGPT，正是由自然語言處理（NLP）模型「GPT-3」延伸出的「GPT-3.5」製作而成，因此能更準確地理解問題，為用家創造更流暢的對話體驗。

    2.3 - ChatGPT 的限制與潛在挑戰

        1、缺乏常識:
            不具備人類水平的常識——而且該模型也缺乏我們擁有的背景知識。有時可能會對某些問題或情況提供無意義或不准確的回答。

        2、缺乏情商:
            它並不具備真正的情商。它無法檢測到微妙的情緒暗示或對複雜的情緒情況做出適當的反應。

        3、理解上下文的局限性: 
            如果用戶在消息中使用諷刺或幽默，可能無法理解其中的含義，並提供不恰當或不相關的回應。

        4、無法生成長格式的結構化內容:
            雖然該模型能夠創建連貫且語法正確的句子，但它可能難以生成遵循特定結構、格式或敘述的冗長內容。因此，ChatGPT 目前最適合生成較短的內容，例如摘要、要點或簡要說明。

        5、同時處理多項任務的局限性:
            當模型只專注於一項任務或目標時表現最佳。如果您要求一次執行多個任務，它將難以確定優先級，這將導致效率和準確性下降。

        6、可能有偏見的回應: 
            因ChatGPT在大量文本數據上訓練，一些數據可能包含偏見或成見。這意味著人工智能有時可能會無意中產生偏見或歧視性的內容。

        7、有限的知識:
            雖然 ChatGPT 可以訪問大量信息，但它無法訪問人類擁有的所有知識。它可能無法回答有關非常具體或小眾的問題，並且可能不了解某些領域的最新發展或變化。

        8、準確性問題或語法問題: 
            ChatGPT 目前對打字錯誤、語法錯誤和拼寫錯誤的敏感性有限。該模型還可能產生技術上正確但在上下文或相關性方面可能不完全準確的響應。

        9、需要微調:
            如果您需要用於非常具體的用例，您需要微調模型以獲得您需要的內容。微調涉及在特定數據集上訓練模型以優化其針對特定任務或目標的性能，需要消耗大量時間和資源。

        10、計算成本和能力: 
            ChatGPT 是一種高度複雜的 AI 語言模型，需要大量計算資源才能有效運行，運行該模型可能非常昂貴，並且可能需要訪問專門的硬件和軟件系統。

        11、地區或機構限制: 
            由於當地的法規或互聯網基礎設施，ChatGPT 在某些國家無法使用。
            《自然》雜誌宣佈人工智能寫作應用程序不能被列為合著者；
            香港大學明確禁止任何“可以獲得學分的活動”中使用ChatGPT和其他人工智能工具，包括課堂作業、課後作業和評估任務。




### 3. 如何執行ChatGPT

    3.1 - 用Edge執行ChatGPT
    
        手機或電腦下載Edge，點圖示 b 開始使用

        缺點:
            回覆比較慢
            不能保存對話記錄
        優點:
            無需註冊及VPN
            可以分析網站內容


    3.2 - 到官網執行ChatGPT

        手機或電腦瀏覽器打開 https://chat.openai.com/ 

        缺點:
            需購買境外電話號碼註冊及使用VPN
            分析網站內容需額外安裝插件
        優點:
            回覆較快
            可以保存對話記錄




### 4. ChatGPT註冊教學


    4.1 - 準備VPN

        手機:
            到手機商店隨便下載一個免費的VPN程式
            連線選美國或日本

        個人電腦:
            下載日本筑波大学开发的免费VPN程式
            https://www.vpngate.net/cn/download.aspx
            連線選速度高的

    4.2 - 註冊openai帳號

        用瀏覽器打開 https://openai.com/ 
        點 Sign up
        填寫基本信息，姓名、電郵地址和密碼
        同意OpenAI的條款和條件，並點擊「註冊」
        到您的郵箱，打開openai的確認郵件，並點擊里面的鏈接確認帳戶
            

    4.3 - 購買境外電話號碼

        註冊openai帳號需要用電話號碼進行驗證。由於ChatGPT現時未有提供香港地區服務，可以使用sms-activate購買境外電話號碼。

        瀏覽器分頁打開 https://sms-activate.org
        點右上角Sign Up，輸入電郵和密碼。註冊完成後登錄。

        點右上角 Balance 下方的金額，選擇Top up balance充值
        選擇您的付款方式
        在彈出窗口中輸入你要充值的金額。目前建議充$1 = 72₽(盧布)即可。

        充值後，回首頁；左側欄搜索框，輸入 openai 找到 OpenAI 服務
        選擇Indonesia 加入購物車，網站會給你提供一個手機號，複製手機號。 

        回到 https://openai.com/ 
        並貼上手機號驗證
        點擊 Send code SMS

        回  sms-activate.org
        很快會收到 OpenAI 驗證碼

        回 openai.com
        填入驗證碼，即可完成驗證。

    現在您可以開始使用ChatGPT https://chat.openai.com/ 。





### 5. ChatGPT 提問技巧

    5.1 - 提示工程(Prompt Engineering)

        想讓 ChatGPT 做你想的事，你需學習寫好提示語 (prompt)，即如何提出好問題。提示語應該清晰、具體、相關、集中，並且給出一些規範和示例。

    5.2 - ChatGPT工作過程分解

        用戶輸入一個問題、信息需求或隨意陳述。
        ChatGPT分析輸入並用機器學習算法生成回應，用文字返回給用戶。
        然後用戶輸入額外內容，ChatGPT將再次分析和回應。此過程一直持續到對話結束。

        決定ChatGPT對話成功的關鍵因素在於啟動和引導對話時的「提示語質量」——清晰簡潔的提示語有助於保持對話在正軌上，相反的，虛無飄渺或是過於籠統的提示語會讓 ChatGPT 不知如何回答，從而導致對話脫節或缺乏焦點，讓你只能得到模糊的答案。

    5.3 - 無效的ChatGPT提示

        很多人在使用 ChatGPT 時，特別喜歡這樣問:

            “寫一篇演講稿。”

        結果，ChatGPT生成了一篇文句通順但內容全是亂編的文章；”這講稿不能用啊，還不如我自己打的呢!”。

        ChatGPT只是個語言模型，他擅長根據前後文，把文字接著寫下去。所以說，你要講什麼內容，受眾的屬性，以及你演講的風格都要在提試語中告知，這樣結果才能滿足你的需要。

    5.4 - 有效的ChatGPT提示

        提供清晰資料:
            立場、目的、條件、限制等，讓ChatGPT能夠針對問題給出合適回答。

        指定要扮演的角色:
            例如行銷專家、教師、作家等，讓ChatGPT能根據角色調整回答的風格和語氣。

        以目標導向的思考方式要求輸出:
            拆解問題並追問，讓ChatGPT能夠挖掘任何可能的要素，激盪出有創意的提案。

        例子:

            你充當Linux終端。我會鍵入命令，您需回复終端顯示的內容。你只需回復一個唯一代碼塊中的終端輸出，沒有別的。不要寫解釋。除非我指示你這樣做，否則不要鍵入命令。當我需要用英語告訴你一些事情時，我會通過將文本放在大括號內{像這樣}來做到這一點。我的第一個命令是 PWD

            你是英語翻譯專家、拼寫校正和改進者。我會用任何語言和你說話，你會檢測語言，翻譯它。並用我的文本更正和改進版本回答，用英語。我希望你用漂亮、優雅的高級英語單詞和句子，代替我簡化單詞和句子。保持含義相同，但使它們更具文學性。我希望你只回復更正，改進，沒有別的，不要寫解釋。我的第一句話是“istanbulu cok seviyom burada olmak cok guzel”

            我是手搖飲料店的老闆。店鋪在大學旁邊，附近有多家連鎖飲料店，主要客戶是大學的職員和學生，我店的優勢是價格比連鎖店便宜，劣勢是沒有預算行銷、及包裝商品。請以一個行銷專家的建議，提供三個行銷方案，文字簡潔，共 500 字內。

            你扮演面試官角色。我是候選人，你會問我職位的面試問題。你只需用面試官的身份回答。不要一次寫下所有的需求。你只要問我問題並等待我的回答。不要寫解釋。像面試官一樣一個接一個地問我問題，然後等待我的回答。我的第一句話是“嗨”position

            你是一個講故事的人。您將想出引人入勝，富有想像力和吸引觀眾的有趣故事。它可以是童話故事，教育故事或任何其他類型的故事，有可能吸引人們的注意力和想像力。根據目標受眾，您可以為您的講故事會議選擇特定的主題或主題，例如，如果是兒童，那麼您可以談論動物；如果是成年人，那麼基於歷史的故事可能會更好地吸引他們等。我的第一個要求是“我需要一個關於毅力的有趣故事。

        非官方提示生產生工具:
            http://www.promptgenius.site/


### 6. ChatGPT擴充功能

    1. WebChatGPT

        功能：
            因為ChatGPT只有收錄到2021年的資料，但安裝後可以在 ChatGPT 打開連結網路的功能，可以設定要爬取的文章數量、時間和地點，之後ChatGPT它就會先去網路上抓最新的資料進行整理。
        https://chrome.google.com/webstore/detail/webchatgpt-chatgpt-with-i/lpfemeioodjbpieminkklglpmhlngfcn/related?fbclid=IwAR3seO_J0rfWhQmLQOUKAidDuFb5ejMTQ57-EKVhbF8Hhx3_iq-vhNfq7HQ

    2. ChatGPT Prompt Genius

        功能：
            安裝好後會在 ChatGPT 的側邊欄位出現一個 Share&Export的功能，後續我們就可以將想要保存的內容匯出成 Png 或 PDF。
        https://chrome.google.com/webstore/detail/chatgpt-prompt-genius/jjdnakkfjnnbbckhifcfchagnpofjffo/related?fbclid=IwAR3aggm0rmJAk4Vgi0mx45foXjrJwLXydWcz2InZIjqsu7-qkUxqXdQYbTo

    3. ChatGPT Writer

        功能：
            將 Gmail 連結ChatGPT，後續我們可以在Gmail的後台中，點選藍色閃電符號，就可以輸入關鍵字讓ChatGPT幫我們撰寫Email內容或準備要回覆對方的Email內容並進行修改。
        https://chrome.google.com/webstore/detail/chatgpt-writer-write-mail/pdnenlnelpdomajfejgapbdpmjkfpjkp/related?fbclid=IwAR05nN5A6EKocYe058oEHd9fCXGgOVblQakBgk-mgtJ1r3P4Y0Pc1C3M1Go

    4. ChatGPT for Google

        功能：
            在Google搜尋後，會在搜尋結果的右側，多一個 ChatGPT 小視窗，然後將查詢結果進行摘要與整理。
        https://chrome.google.com/webstore/detail/chatgpt-for-google/jgjaeacdkonaoafenlfkkkmbaopkbilf?ref=producthunt&fbclid=IwAR04IekVARD2U5ey9Y2peIDf-CouwlCmZ_9KoDMa8oflxYBTRYoiL1Dzbdk

    5. YouTube Summary with ChatGPT

        功能：
            安裝後會在YouTube的右側會多出工具列，可以複製影片的字幕，也可打開ChatGPT直接讓它幫忙生成影片摘要，然後翻譯成中文。
        https://chrome.google.com/webstore/detail/youtube-article-summary-p/nmmicjeknamkfloonkhhcjmomieiodli/related
    
    6.Luna
        功能：
            安裝後就可以在瀏覽網頁時，針對不懂的專有名詞按下滑鼠右鍵，然後連結回ChatGPT讓它為你解答。
        https://chrome.google.com/webstore/detail/luna-chatgpt-for-your-bro/bignkmclhhmhagjojehblmmaifljphfe/related



### 9. 專案實作與證書頒發

   - 學員需實作一個基於 ChatGPT 的應用專案
   - 學員需專案演示與成果分享
   - 完成後 ATW 生產力提升學院將頒發 ChatGPT 應用課程證書


備註：課程目錄僅供參考，實際課程安排可能根據需求進行調整和修改。

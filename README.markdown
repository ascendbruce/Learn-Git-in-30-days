30 天精通 Git 版本控管
====================

作者: 黃保翕 ( Will 保哥 )

![Git](https://kkbox-registrano.s3.amazonaws.com/upload_images/13710/gitlogo_530.png)

文章簡介
------------

在軟體開發領域，對原始碼進行版本控管是非常重要的一件事，有別於Subversion或TFS這類集中式版本控管系統，Git是一套分散式版本控管系統，並帶來許多版本控管上的各種優勢與解決傳統集中式版本控管的缺失，例如支援本地操作、備份容易、功能強大且彈性的分支與合併等等。不過，由於Git版本控管無論在版控觀念與工具使用上，都與傳統集中式版控工具差異甚大，因此造成了不小的學習門檻，在未來的３０天內，希望能讓大家完整了解Git版本控管的精隨之處，並整理我的學習心得與我們公司從Subversion轉至Git的過程中所遭遇的問題與解決方法。

旅程從現在開始： (^_^)
--------------------------

* [第 01 天：認識 Git 版本控管](docs/01 認識 Git 版本控管.markdown)
* [第 02 天：在 Windows 平台必裝的三套 Git 工具](docs/02 在 Windows 平台必裝的三套 Git 工具.markdown)
* [第 03 天：建立儲存庫](docs/03 建立儲存庫.markdown)
* [第 04 天：常用的 Git 版本控管指令](docs/04 常用的 Git 版本控管指令.markdown)
* [第 05 天：了解儲存庫、工作目錄、物件與索引之間的關係](docs/05 了解儲存庫、工作目錄、物件與索引之間的關係.markdown)
* [第 06 天：解析 Git 資料結構 - 物件結構](docs/06 解析 Git 資料結構 - 物件結構.markdown)
* [第 07 天：解析 Git 資料結構 - 索引結構](docs/07 解析 Git 資料結構 - 索引結構.markdown)
* [第 08 天：關於分支的基本觀念與使用方式](docs/08 關於分支的基本觀念與使用方式.markdown)
* [第 09 天：比對檔案與版本差異](docs/09 比對檔案與版本差異.markdown)
* [第 10 天：認識 Git 物件的絕對名稱](docs/10 認識 Git 物件的絕對名稱.markdown)
* [第 11 天：認識 Git 物件的一般參照與符號參照](docs/11 認識 Git 物件的一般參照與符號參照.markdown)
* [第 12 天：認識 Git 物件的相對名稱](docs/12 認識 Git 物件的相對名稱.markdown)
* [第 13 天：暫存工作目錄與索引的變更狀態](docs/13 暫存工作目錄與索引的變更狀態.markdown)
* [第 14 天：Git for Windows 選項設定](docs/14 Git for Windows 選項設定.markdown)
* [第 15 天：標籤 - 標記版本控制過程中的重要事件](docs/15 標籤 - 標記版本控制過程中的重要事件.markdown)
* [第 16 天：善用版本日誌 git reflog 追蹤變更軌跡](docs/16 善用版本日誌 git reflog 追蹤變更軌跡.markdown)
* [第 17 天：關於合併的基本觀念與使用方式](docs/17 關於合併的基本觀念與使用方式.markdown)
* <a href="docs/18 修正 commit 過的版本歷史紀錄 Part 1 (reset & amend).markdown">第 18 天：修正 commit 過的版本歷史紀錄 Part 1 (reset & amend)</a>
* [第 19 天：設定 .gitignore 忽略清單](docs/19 設定 .gitignore 忽略清單.markdown)
* <a href="docs/20 修正 commit 過的版本歷史紀錄 Part 2 (revert).markdown">第 20 天：修正 commit 過的版本歷史紀錄 Part 2 (revert)</a>
* <a href="docs/21 修正 commit 過的版本歷史紀錄 Part 3 (cherry-pick).markdown">第 21 天：修正 commit 過的版本歷史紀錄 Part 3 (cherry-pick)</a>
* <a href="docs/22 修正 commit 過的版本歷史紀錄 Part 4 (rebase).markdown">第 22 天：修正 commit 過的版本歷史紀錄 Part 4 (rebase)</a>
* <a href="docs/23 修正 commit 過的版本歷史紀錄 Part 5 (rebase 2).markdown">第 23 天：修正 commit 過的版本歷史紀錄 Part 5 (rebase 2)</a>
* [第 24 天：使用 GitHub 遠端儲存庫 - 入門篇](docs/24 使用 GitHub 遠端儲存庫 - 入門篇.markdown)
* [第 25 天：使用 GitHub 遠端儲存庫 - 觀念篇](docs/25 使用 GitHub 遠端儲存庫 - 觀念篇.markdown)
* [第 26 天：多人在同一個遠端儲存庫中進行版控](docs/26 多人在同一個遠端儲存庫中進行版控.markdown)
* [第 27 天：透過分支在同一個遠端儲存庫中進行版控](docs/27 透過分支在同一個遠端儲存庫中進行版控.markdown)
* [第 28 天：了解 GitHub 上 forks 與 pull request 的版控流程](docs/28 了解 GitHub 上 forks 與 pull request 的版控流程.markdown)
* [第 29 天：如何將 Subversion 專案匯入到 Git 儲存庫](docs/29 如何將 Subversion 專案匯入到 Git 儲存庫.markdown)
* [第 30 天：分享工作中幾個好用的 Git 操作技巧](docs/30 分享工作中幾個好用的 Git 操作技巧.markdown)

獲獎紀錄
----------

* [2013第6屆iT邦幫忙鐵人賽得獎名單出爐!](http://ithelp.ithome.com.tw/question/10142953)
	* 【iT邦幫忙鐵人賽年度大獎】
	* 【開發技術組年度鐵人】

課程資訊
---------

* [Git 版本控管實戰：從入門到進階](https://kktix.com/events/git-taipei-01) [兩天課程]
	* 上課時間 (第一天): 2014/01/11 9:00 ~ 17:00
	* 上課時間 (第二天): 2014/01/18 9:00 ~ 17:00

與我聯絡
---------

* 粉絲頁: [Will 保哥的技術交流中心](https://www.facebook.com/will.fans)
* 部落格: [The Will Will Web](http://blog.miniasp.com/)



第 01 天：認識 Git 版本控管
==========================================

筆者使用 Subversion (SVN) 已經將近 10 年，從來都不覺得有任何必要轉換至其他版本控管平台，直到前幾年因應雲端化的改變，慢慢導入 TFS 版本控管 (TFS Service)，轉換的過程還算順利，只因為 SVN 與 TFS 的版本控管概念相近，都屬於集中式版本控管系統。這類集中式版本控管系統，使用上簡單、直覺且容易進行權限控管，說真的，在大部分的開發情境下，Subversion 或 TFS 已經相當足夠，那又是甚麼契機或是需求，迫使我們一定要轉換到 Git 版本控管呢？我相信，不同人採用 Git 一定有他的理由，有些人覺得好玩、有些人覺得新鮮、有些人覺得功能強大，無論如何，只要這個理由能夠支持你去主動認識一個陌生技術，都是好的，本篇文章除了帶大家認識 Git 版本控管機制外，也會說說我想轉換到 Git 的理由。

文章目的
-------

在軟體開發領域，對原始碼進行版本控管是非常重要的一件事，有別於 Subversion 或 TFVC (Team Foundation Version Control) 這類集中式版本控管系統，Git 是一套分散式版本控管系統(DVCS; Distributed Version Control System)，並帶來許多版本控管上的各種優勢與解決傳統集中式版本控管的缺失，例如支援本地操作、備份容易、功能強大且彈性的分支與合併等等。不過，由於 Git 版本控管無論在版控觀念與工具使用上，都與傳統集中式版控工具差異甚大，因此造成了不小的學習門檻。

雖然說本次文章的主題是「30 天精通 Git 版本控管」，不過，說實在的，還真有點言過其實了，因為 Git 博大精深，有非常多細節可以探究，如果真的要應用在工作上，學幾天可以真正上手呢？每天學一點，連續學習 30 天，似乎是個合理的數字 (或太多?)，如果有一個工具大家都要用，而且要立刻上手的工具，如果學 30 天都還不知道怎麼活用，那這學習門檻也太高了些。因此我想，這個系列的文章，主要還是專注於「如何在 30 天內學會 Git 版本控管，而且必須要能熟練的應用在實務開發工作上」，這才是本系列的真正目的，那些繁瑣的細節，我不會特別強調，但總是有些重要的概念與細節還是不能錯過，我會嘗試在每一個主題中提到一部份，一有機會就會深入探討，希望大家可以透過做中學，深刻體會 Git 版本控管的強大魅力。

轉換的契機
---------

這幾個月，公司因為有個大型專案，參與開發人數超過 12 人，最後大家決議採用 Git 作為本次專案的版本控管機制，與其說我們採用了 Git 版本控管，其實真正採用的原因是「我們選擇使用 GitHub 當成我們的版控平台」，原因就是 GitHub 平台實在整合得太好，完整的 Git 版控支援、議題追蹤與管理、線上 Wiki 文件管理、友善的原始碼審核(Code Review)介面。這些特性，都能有效協助我們在多人協同開發的過程中，減少團隊溝通的問題。

剛開始接觸 Git 說實在挺辛苦的，因為 Git 版本控管的觀念，實在與 Subversion 差太多，沒有辦法很直覺的去體會其差異，就算給了你 GUI 圖形化工具介面，你也不見得就會使用。你知道的，一個強大又好用的工具在你手上，「錯誤的使用方式」比「不會用」還可怕！說穿了，就是你必須先建立一套思維模式(Mindset)，了解 Git 的運作原理，然後再上手使用 Git 相關工具 (無論是指令列工具或圖形化介面工具)，才是正途！

學習的方法
---------

我在剛學習 Git 的時候，看了好幾本書 (其實是挑重點看)，也看了許多線上的文章與簡報，甚至還看了好幾部教學影片，看著看著，確實可以學會如何使用 Git 工具，我覺得並不會太過艱深。不過，Git 的指令與參數非常多，完全超出大腦能記憶的範圍，除非每天使用，否則哪有可能一天到晚打指令進行版控，如果每次要使用 Git 指令都要查書的話，那這也太沒效率了點，當下的我就直覺地認為，學習 Git 最終還是要回歸到好用的 GUI 工具，否則這東西在團隊中可能不容易推廣。

再者，因為 Git 是屬於「分散式版本控管」機制，當開發人數開始變多，版本庫又開始變成一人一份時，在第一次進行多人分支與合併的過程時，大家都飽受煎熬，而且持續一段不短的時間。雖然公司內部有先進行技術分享，不過由於大家都是第一次學，那些 Git 的抽象概念，還沒辦法深植人心，只能基於 Git 的使用方法進行分享，例如工具怎麼用、有哪些常用的指令、甚麼特殊的情況下應該下甚麼指令，諸如此類的。過程中就算說出了複雜的原理，由於大家對於 Git 的認知還很模糊，不同人對 Git 版控方式的理解也不盡相同，所吸收到的知識與概念，也不一定一致。所以，雖然上完課了，大家還是需要好幾天的時間不斷謀合，相互討論，互相解決問題，如果你只有一人使用 Git 的話，確實不容易感受 Git 帶來的好處，也恐怕不容易堅持下去。

所以，我認為，要學好 Git 版本控管，若先知道以下幾點，也許比較容易學會：

* 先擁有 Git 基礎觀念，透過下指令的方式學習是最快的方式，不要跳過這一段
* 找多一點人跟你一起學 Git 版本控管，最好能直接用在實務的開發工作上
* 團隊中最好要有幾個先遣部隊，可以多學一點 Git 觀念，好分享給其他人，或有人卡關時，能適時提供協助
* 了解 Git 屬於「分散式版本控管」，每個人都有一份完整的儲存庫(Repository)，所以必須經常合併檔案
* 使用 Git 的時候，分支與合併是常態，但只要有合併，就會有衝突，要學會如何解決衝突

認識 Git 版本控管
---------------

Git 的出現，來自於 Linux 之父 "Linus Torvalds" 開發 Linux kernel 的時候，因為早期的版本控制方法非常沒有效率，屬集中式控管，當 Linux kernel 這類複雜又龐大的專案在進行版本控管時，出現了許多問題。最早期 Linux kernel 採用  BitKeeper 進行版本控管，但後來 Linus Torvalds 基於 BitKeeper 與 Monotone 的使用經驗，設計出更棒的 Git 版控系統。原先 Git 只被設計成一個低階的版控工具，用來當做其他版控系統(SCM)的操作工具，後來才漸漸演變成一套完整的版本控制系統。 

有趣的是，Linus Torvalds 改採 Git 進行版本控管初期，由於 Git 太過複雜，許多版控觀念跟以往差異太大，也受到世界各地開放原始碼社群的反對，但經過幾年的努力與發展，操作 Git 的相關工具也越來越成熟，才漸漸平撫反對的壓力，從 2013 年的市場調查看來，全世界已有 30% 的開放原始碼專案改採 Git 進行版本控管，這是個非常驚人的市占率，意謂著 Git 絕對有其驚豔之處，不好好研究一番還不行呢！

講到 Git 的架構，完全是基於 Linus Torvalds 在維護 Linux kernel 這個大型專案時得到的經驗，以及他本身在檔案系統優化方面的豐富經驗進行設計，也因為這樣，Git 包含了以下幾個重要的設計：

* 強力支援非線性開發模式 (分散式開發模式)
	* Git 擁有快速的分支與合併機制，還包括圖形化的工具顯示版本變更的歷史路徑。
	* Git 非常強調分支與合併，所以版本控管的過程中，你會不斷的在執行分支與合併動作。
	* Git 的分支機制非常輕量，沒有負擔，每一次的分支只是某個 commit 的參考指標而已。
* 分散式開發模型
	* 參與 Git 開發的每個人，都將擁有完整的開發歷史紀錄。
	* 當開發人員第一次將 Git 版本庫複製(clone)下來後，完全等同於這份 Git 版本庫的「完整備份」。
	* 整個版本庫中所有變更過的檔案與歷史紀錄，通通都會儲存在本機儲存庫(local repository)。
* 相容於現有作業系統
	* Git 版本庫其實就只是一個資料夾而已，資料夾中有許多相關的設定檔與各種 blob 物件檔案而已。
	* Git 版本庫可以用任何方式發布，所以你用 HTTP, FTP, rsync, SSH 甚至於用 Git protocol 都可以當成存取 Git 版本庫的媒介，相容性極高。
* 有效率的處理大型專案
	* 由於完整的版本庫會複製(clone)一份在本機，該版本庫包含完整的檔案與版本變更紀錄，所以針對版本控管中的各種檔案操作速度，將會比直接從遠端存取來的快上百倍之多。
	* 這也代表著，Git 版本控管不會因為專案越來越大、檔案越來越多，而導致速度變慢。
* 歷史紀錄保護
	* Git 版控的過程，每次 commit 都會產生一組 hash id 編號，而且每個版本在變化的過程都會參考到這個 hash id，只要 hash id 無法比對的上，Git 就會無法運作，所以當專案越來越大，版本庫複製(clone)的越來越多份，你幾乎無法竄改檔案的內容或版本紀錄。
	* **請記得: 每個人都有一份完整的版本庫，你改了原始的那份，所有人的版本庫就無法再合併回原本的版本庫了，所以你幾乎不可能任意竄改版本紀錄。**
* 以工具集為主的設計 (Toolkit-based design)
	* Git 被設計成一個一個的工具軟體(指令列工具)，你可以很輕易的組合不同工具的使用，使用上非常彈性。
* 彈性的合併策略 (Pluggable merge strategies)
	* Git 有一個擁有良好設計的「不完整合併(incomplete merge)」 機制，以及多種可以完成合併的演算法，並在最後告知使用者為何無法自動完成合併，或通知你需要手動進行合併動作。
* 被動的垃圾回收機制
	* 在使用 Git 的時候，若想要中斷目前的操作或回復上一個操作，都是可以的，你完全可以不必擔心可能有其中一個指令下錯，或指令執行到一半當機等問題。
	* Git 的垃圾回收機制，其實就是那些殘留在檔案系統中的無用檔案，這個垃圾回收機制只會在這些無用的物件累積一段時間後自動執行，或你也可以自行下達指令清空它。例如: git gc --prune
* 定期的封裝物件
	* 我們在 Git 中提到的 "物件" 其實就是代表版本庫中的一個檔案。而在版本異動的過程中，專案中的程式碼或其他檔案會被更新，每次更新時，只要檔案內容不一樣，就會建立一個新的 "物件"，這些不同內容的檔案全部都會保留下來。
	* 你應該可以想像，當一個專案越來越大、版本越來越多時，這個物件會越來越多，雖然每個檔案都可以各自壓縮讓檔案變小，不過過多的檔案還是會檔案存取變得越來越沒效率。因此 Git 的設計有個機制可以將一群老舊的 "物件" 自動封裝進一個封裝檔(packfile)中，以改善檔案存取效率。
	* 那些新增的檔案還是會以單一檔案的方式存在著，也代表一個 Git 版本庫中的 "檔案" 就是一個 Git "物件"，但每隔一段時間就會需要重新封裝(repacking)。
	* 照理說 Git 會自動執行重新封裝等動作，但你依然可以自行下達指令執行。例如: git gc
	* 如果你要檢查 Git 維護的檔案系統是否完整，可以執行以下指令: git fsck 

關於 Git 的分散式版控系統，我再重申幾件事：

* Git 完全不需要伺服器端的支援就可以運作版本控制，因為每個人都有一份完整的儲存庫副本。
* 因為每個人都有一份完整的儲存庫副本，所以每次提交版本變更時，都僅提交到本地的儲存庫而已，因此提交速度非常快，也不用網路連線，可大幅節省開發時間。
* 由於每個人都有一份完整的儲存庫副本，代表著在使用 Git 版本控管時，沒有所謂的「權限控管」這件事，每個成員都能把儲存庫複製(clone)回來，也都可以在本地提交變更，沒有任何權限可以限制。使用 Git 時，唯一能設定的權限是，你有沒有權利存取上層儲存庫(upstream repository)或遠端儲存庫(remote repository)的權限。
* 如果需要跟別人交換變更後的版本，隨時可以透過「合併」的方式進行，Git 擁有非常強悍的合併追蹤（merge tracing）能力。
* 要合併多人的版本，你只要有存取共用儲存庫(shared repository)的權限或管道即可。
  **例如：在同一台伺服器上可以透過資料夾權限進行共用，或透過 SSH 遠端存取另一台伺服器的 Git 儲存庫，也可以透過 Web 伺服器等方式來共用 Git 儲存庫。**

今日小結
-------

今天這篇只是個大致介紹，若看不太懂 Git 的設計理念沒關係，你可以用一段時間之後再回來看這篇文章，或許會有更深一層的體會。

我覺得要寫「認識 Git 版本控管」比教大家怎麼用還難許多，以下我在列出一些 Git 相關連結，供大家進一步學習。


參考連結
-------

* [Git (software) - Wikipedia, the free encyclopedia](http://en.wikipedia.org/wiki/Git_(software) "Git (software) - Wikipedia, the free encyclopedia")
* [Pro Git Book](http://progit.org/)
* [Git Magic - 繁體中文版](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_tw/)
* [簡介 Git 及使用](http://ascc.sinica.edu.tw/iascc/articals.php?_section=2.4&_op=?articalID:4811)
* [版本控制 - 維基百科，自由的百科全書](http://zh.wikipedia.org/wiki/%E7%89%88%E6%9C%AC%E6%8E%A7%E5%88%B6)

第 02 天：在 Windows 平台必裝的三套 Git 工具
===========================================================

要開始使用 Git 版本控管，首先要安裝適當的 Git 工具，這個系列的文章主要還是以 Windows 平台為主，這篇文章將會介紹三套我們最常用的 Git 版控工具，並介紹這幾套工具之間的異同之處，還有在何時要用甚麼工具。


1. [Git for Windows](http://msysgit.github.io/)

這是一個可以在 **命令提示字元** (Command Prompt) 下執行的一套指令列工具，目前市面上所有 Git 的 GUI 工具，其實骨子裡都是執行這些較為底層的 Git 工具，所以是一套必備的 Git 管理工具，非裝不可！

以下是安裝過程：

* 先連到 http://msysgit.github.io/ 官網，準備下載安裝檔

![image](https://f.cloud.github.com/assets/88981/1144770/f8ea8f04-1dcc-11e3-8f36-a920c8a1bf23.png)

* 不管哪個版本，下載最新版就對了

![image](https://f.cloud.github.com/assets/88981/1144771/4a5d6b04-1dcd-11e3-91dc-b933ea52a8b6.png)

* 直接點擊下載的檔案進行安裝

![image](https://f.cloud.github.com/assets/88981/1144772/91e734f0-1dcd-11e3-8fb6-7a633c10d124.png)

* 安裝程式歡迎頁面

![image](https://f.cloud.github.com/assets/88981/1144773/c6339582-1dcd-11e3-9471-f768222a39d6.png)

* 同意 GPL 授權條款

![image](https://f.cloud.github.com/assets/88981/1144774/db78ad4c-1dcd-11e3-9aca-a5914b026e41.png)

* 選擇安裝路徑

![image](https://f.cloud.github.com/assets/88981/1144775/f3e3f81e-1dcd-11e3-846b-d842b3e02987.png)

* 選取元件，保留預設選項即可

![image](https://f.cloud.github.com/assets/88981/1144776/109b2d92-1dce-11e3-9e14-7e637d9e8e94.png)

* 設定程式集名稱，保留預設選項即可

![image](https://f.cloud.github.com/assets/88981/1144777/3651dd2e-1dce-11e3-883a-8a813c1d3b29.png)

* 這裡請選擇第二項：Run Git from the Windows Command Prompt 

![image](https://f.cloud.github.com/assets/88981/1144779/41c199e2-1dce-11e3-96db-c82fa0add2eb.png)

* 換行字元轉換，建議保留預設選項即可。

![image](https://f.cloud.github.com/assets/88981/1144780/4f9bb3d6-1dce-11e3-9d9c-1baf0c9548f8.png)

* 開始進行安裝

![image](https://f.cloud.github.com/assets/88981/1144781/5c571da4-1dce-11e3-8bef-fd06f1e0bc0d.png)

* 安裝完成

![image](https://f.cloud.github.com/assets/88981/1144782/66d00d90-1dce-11e3-8cd5-3ba0a238f603.png)

* 安裝完成後，直接開啟命令提示字元，就可以開始使用

![image](https://f.cloud.github.com/assets/88981/1144786/c4291d42-1dce-11e3-9d06-e3c3f1ac1591.png)

* 你可以輸入 `git --version` 指令查詢目前工具程式的版本

![image](https://f.cloud.github.com/assets/88981/1144787/dab6f5a2-1dce-11e3-9c97-63b5866af7d0.png)



2. [GitHub for Windows](http://windows.github.com/)

這套是由 [GitHub](https://github.com) 官方開發的工具，寫給那些對 Git 沒有很了解的人用的，用簡潔與親民的 GUI 介面，企圖隱藏 Git 那些難懂的觀念與指令參數。雖然 GitHub for Windows 工具比起 Git for Windows 親和許多，但對 Git 完全沒有概念的人來說，要上手 GitHub for Windows 工具可能也不是件容易的事。

	GitHub for Windows 內建了一個 Git Shell 工具，這工具會用到 [Git for Windows](http://msysgit.github.io/)，所以如果你沒有安裝 Git for Windows 的話，也將無法使用 [GitHub for Windows](http://windows.github.com/) 的 Git Shell 工具 。

這套工具，大概可以幫你完整的 Git 工作也很有限，最主要有以下能力：

* Clone Repositories
	* 將 GitHub 上面的儲存庫複製回來 (git clone)
* Browse History
	* 瀏覽本地儲存庫的版本歷史紀錄 
* Commit Changes
	* 提交變更到本地儲存庫 
* Branch Code 
	* 建立與管理 Git 分支，還可以在工作目錄中切換分支 
* Share on GitHub.com
	* 與 GitHub 同步變更
	* 這裡「同步」 (Sync) 的意思是將 git pull 與 git push 整合在一起

除此之外的大部分 Git for Windows 能做的事，在 GitHub for Windows 裡面都不能做！若真的要應用在較為大型的開發專案上，可能要考慮看看是否適用。

以下是 GitHub for Windows 安裝過程：

* 先連到 http://windows.github.com/ 準備下載安裝檔

![image](https://f.cloud.github.com/assets/88981/1145483/58e30d90-1e19-11e3-9e2e-809d9fe7067f.png)

* 下載完後直接執行安裝 

![image](https://f.cloud.github.com/assets/88981/1145488/8c71fdb0-1e19-11e3-8b7c-46234118e50d.png)

* 剛下載 GitHub for Windows 安裝檔的時候可能覺得安裝檔很小，但事實上真正在安裝的時候才會下載所需的檔案，所以必須保持網路連線

![image](https://f.cloud.github.com/assets/88981/1145493/a80b9784-1e19-11e3-876e-a1ed8cbe659c.png)

* 下載完成後，GitHub for Windows 工具會直接被開啟，並進行初始設定工作

	* 開啟 GitHub for Windows 的第一步就是先登入 GitHub 帳戶 (你也可以點擊 SKIP SETUP 跳過這一步)

![image](https://f.cloud.github.com/assets/88981/1145505/f9a35e1e-1e1a-11e3-9133-f13b2ded7721.png)

	* 然後他會要求你先設定好 user.name 與 user.email 這兩個參數，這兩個是使用任何 Git 工具最重要的步驟之一，沒有設定這兩個參數是完全無法 commit 任何版本的。 備註: 這兩個參數預設會設定到 Global config 之中，也就是 "C:\Users\<user>\.gitconfig" 這個檔案。

![image](https://f.cloud.github.com/assets/88981/1145513/4d50cdee-1e1b-11e3-8584-15d0368115e5.png)

* 設定完成

![image](https://f.cloud.github.com/assets/88981/1145515/8a7145fa-1e1b-11e3-82d2-45c57c37241d.png)

* 首次使用如果有成功登入 GitHub 帳戶，GitHub for Windows 會自動建立一組 SSH Key-Pair 在 `C:\Users\<username>\.ssh` 目錄下，這可以讓你在日後「同步」本地與遠端儲存庫時不用再輸入帳號密碼。

* GitHub for Windows 幫你產生的 SSH Key 預設路徑如下：

	* "C:\Users\<username>\.ssh\github_rsa"
	* "C:\Users\<username>\.ssh\github_rsa.pub"

* SSH Key 的簽章的部分也會在登入的同時上傳到 GitHub 網站，你可以從個人的設定畫面 ( [https://github.com/settings/ssh](https://github.com/settings/ssh) ) 中看到曾經上傳過的 SSH Key 簽章：

![image](https://f.cloud.github.com/assets/88981/1145576/a2a43962-1e1f-11e3-9dea-92f02f9c1815.png)

* GitHub for Windows 裝好之後，其實還額外幫你安裝了一個 Git Shell 工具，這預設是一個 PowerShell 介面的操作環境，好處有很多，之後我們的例子也會盡量使用 Git Shell 來進行操作：
	* 可以在指令列使用 ^ 符號 (在命令提示字元不能接使用 ^ 符號)
	* 可以在 Git 工作目錄下可以得到額外的提示資訊 (Prompt)
* 不過使用 Git Shell (PowerShell) 也有一個小缺點
	* 由於 PowerShell 裡面 `{}` 具有特殊意義，所以若你的 git 參數會用到 `{}` 符號的話，記得該參數的前後要加上 '單引號'

3. [SourceTree](http://www.sourcetreeapp.com/)

這套是由 [ATLASSIAN](https://www.atlassian.com) 這間公司開發的工具，是一套非常專業的 GUI 操作工具，不僅支援 Git 版本控管，同時也支援 [Mercurial](http://mercurial.selenic.com/) 版本控管機制，這兩套版本控管機制都屬於分散式版本控管的分類，概念上也十分相近，所以可以整合在這一套工具上使用。

	[SourceTree](http://www.sourcetreeapp.com/) 其實骨子裡也是透過 Git for Windows 工具進行版本操作，如果你沒有事先安裝 [Git for Windows](http://msysgit.github.io/) 的話，安裝的過程中他也會提示你要不要順便安裝起來。

[SourceTree](http://www.sourcetreeapp.com/) 的功能相較於 [GitHub for Windows](http://windows.github.com/) 是強大許多，幾乎所有的指令列功能都能夠過 SourceTree 的 GUI 介面完成(透過滑鼠操作)，不過還是老話一句，如果你對 Git 的核心觀念不太了解，再多的右鍵選單對你來說等同於白紙一張，一樣不知道怎樣操作。但你若認真的了解 Git 的運作機制與觀念，使用 SourceTree 絕對能夠事半功倍！

以下是 SourceTree 安裝過程：

* 先連到 http://www.sourcetreeapp.com/ 準備下載安裝檔

![image](https://f.cloud.github.com/assets/88981/1145540/a568ea42-1e1c-11e3-87d0-542deb15b303.png)

* 下載完後直接執行安裝，其餘的安裝步驟就直接一直按 `Next` 到最後，然後直接開啟 SourceTree 程式

![image](https://f.cloud.github.com/assets/88981/1145558/df457860-1e1d-11e3-9185-77b41b679caa.png)

![image](https://f.cloud.github.com/assets/88981/1145559/fc028b6e-1e1d-11e3-81dd-55797abdc31f.png)

![image](https://f.cloud.github.com/assets/88981/1145561/14dc332e-1e1e-11e3-96db-024ec861965e.png)

![image](https://f.cloud.github.com/assets/88981/1145562/21931d76-1e1e-11e3-8359-dcf9b2c3c8cb.png)

* 第一次啟動 SourceTree 時，會問你要不要順便安裝 [Mercurial](http://mercurial.selenic.com/)，可裝可不裝

![image](https://f.cloud.github.com/assets/88981/1145563/50148fe0-1e1e-11e3-9ae6-13899984e392.png)

* 第一次使用 SourceTree 時，跟 GitHub for Windows 一樣，都要設定預設的 user.name 與 user.email 這兩個參數，不過，如果你有按照本文步驟安裝的話，這一步應該不用特別輸入，因為之前輸入的參數都已經寫入到 Git for Windows 的 Global 設定檔中，這邊會自動被帶入，你直接按下 `Next` 即可。 

![image](https://f.cloud.github.com/assets/88981/1145567/a227c9e6-1e1e-11e3-8fb7-7e0afaa775e1.png)

* 這個步驟則是選擇適當的 SSH Client，這是為了跟遠端的 Git 儲存庫認證所需要的工具，選用預設值即可。

![image](https://f.cloud.github.com/assets/88981/1145572/147124c0-1e1f-11e3-92e4-54cc73b57e9e.png)

* 接著這個步驟則是問你是否已有 SSH Key 存在，由於我們在 GitHub for Windows 已經產生過一個 GitHub 專用的 SSH Key，所以你也可以在這一步按下 `Yes` 並選取 `C:\Users\<username>\.ssh\github_rsa` 這個檔案 (這是一個 SSH 私密金鑰)。

![image](https://f.cloud.github.com/assets/88981/1145573/3c2d4fca-1e1f-11e3-85ea-ed8ba97fb66b.png)

* 雖然 SourceTree 是免費軟體，但還是必須在安裝後 30 天內 "免費註冊" 得到序號後，才能繼續使用。

![image](https://f.cloud.github.com/assets/88981/1145605/50e68a5e-1e23-11e3-8c7a-28a81db4a655.png)

* 立即註冊一個授權

![image](https://f.cloud.github.com/assets/88981/1145606/6742cd6c-1e23-11e3-9e07-c8bb1be8a7da.png)

* 先輸入 Email 地址

![image](https://f.cloud.github.com/assets/88981/1145608/824ee14a-1e23-11e3-982c-b57ca22e61c3.png)

* 然後輸入一些個人基本資料與設定一個密碼，即可註冊完成

![image](https://f.cloud.github.com/assets/88981/1145611/a49452f8-1e23-11e3-96a3-f5be34d68662.png)

* 如果你在另外一台電腦也安裝 SourceTree 的話，直接輸入第一次註冊時設定的密碼即可自動下載授權檔進行註冊

![image](https://f.cloud.github.com/assets/88981/1145620/62bd3902-1e24-11e3-921f-4bf4926eb161.png)

* 註冊成功

![image](https://f.cloud.github.com/assets/88981/1145613/0edec6f2-1e24-11e3-9d9f-ae144eba39ba.png)


* 在使用 SourceTree 的時候，有個 Open in Terminal 功能，這會開啟一個類似 [Cygwin](http://www.cygwin.com/) 的命令提示字元視窗，讓你直接操作 git 命令。

![image](https://f.cloud.github.com/assets/88981/1145623/bf2f1ce6-1e24-11e3-8679-7e19afa1ddd0.png)


今日小結
-------

今天這篇鉅細靡遺的介紹三套在 Windows 底下常用且功能強大的 Git 版控工具，這三套只要能上手，絕對能夠大幅提升 Git 版本控管的使用效率，絕對值得大家好好研究研究。

不過，我再耳提面命一次，要學會使用 Git 的 GUI 介面工具，一定要先擁有完整的 Git 版控概念，否則真的很難靈活運用這些好用工具。 


參考連結
-------

*  [Git for Windows](http://msysgit.github.io/)
*  [GitHub for Windows](http://windows.github.com/)
*  [SourceTree](http://www.sourcetreeapp.com/)


第 03 天：建立儲存庫
===========================================================

要開始使用 Git 最重要的就是要先有一份 Git 儲存庫 (Git Repository) 才行，但是，這份儲存庫從哪裡來呢？本篇文章會介紹多種建立儲存庫的方式。

要建立儲存庫，事實上，你有很多選擇，例如：

* 在本機建立本地的儲存庫 (local repository)
* 在本機建立一個共用的儲存庫 (shared repository)
* 在 GitHub 或其他 Git 平台建立遠端的儲存庫 (remote repository)

無論如何，你總是需要一個儲存庫，我們分別說明如下：

在本機建立本地的儲存庫 (local repository)
---------------------------------------

我們先開啟 [GitHub for Windows](http://windows.github.com/) 的 Git Shell 工具，這工具其實是個 Windows PowerShell 介面，但外掛了一些 Git 相關的環境變數與命令提示設定(Command Prompt)： 

![image](https://f.cloud.github.com/assets/88981/1171591/417854a0-210a-11e3-930f-40c27196c8a0.png)

開啟後，預設會直接進入 `%USERPROFILE%\Documents\GitHub` 資料夾，這是 [GitHub for Windows](http://windows.github.com/) 的預設專案根目錄，也就是只要預設透過 [GitHub for Windows](http://windows.github.com/) 從 GitHub 複製 (clone) 下來的專案都會放在這個目錄。

所以，我們可以直接在這裡建立一個新目錄，好當成我們的「工作目錄」(working directory)，我們可以輸入指令 `mkdir git-demo` 把目錄建立起來。然後再用 `cd git-demo` 進入該目錄。

由於這是一個空目錄，並不包含任何 Git 儲存庫，這時我們要建立儲存庫，就可以用 `git init` 指令把儲存庫給建立起來，預設儲存庫會放在工作目錄下的 `.git` 目錄下。

完整的操作步驟如下圖示：

![image](https://f.cloud.github.com/assets/88981/1171658/e0f03c0e-210b-11e3-8d16-4d4d5c25d11f.png)

建立完成後，你在 Git Shell 的命令提示符號中，應該可以發現有些不太一樣，他在目前所在路徑後面加上了個高亮的 `[master]` 字樣。這段提示，會顯示你目前所在`工作目錄`的各種狀態，如果看得懂的話，是一個非常有用的資訊來源，可以讓你在用命令列工具操作 Git 時，少打很多 `git status` 指令來查詢目前工作目錄的狀態。這部分會再下一篇文章中特別說明。

在本機建立一個共用的儲存庫 (shared repository)
---------------------------------------

共用儲存庫 (shared repository) 是指建立一個 Git 儲存庫但不包含工作目錄，這種情況比較常發生在 Linux 作業系統下，因為在 Linux 作業系統下通常都是多人使用同一台 Linux 主機。雖然在 Windows 作業系統也可以這樣使用，不過我們的開發環境大多還是在 Windows Client 的環境，比較少有多人共用一台電腦的情況。

如果要建立共用儲存庫，可以使用 `git init --bare` 指令建立，如下圖示。你可以發現，當 `git init` 加上 `--bare` 參數後，他會在當前目錄建立所有 Git 儲存庫的相關檔案與資料夾，你必須特別注意，這個資料夾不能直接拿來做開發用途，只能用來儲存 Git 的相關資訊，大多數情況下，你都不應該手動編輯這個資料夾的任何檔案，最好透過 git 指令進行操作。

![image](https://f.cloud.github.com/assets/88981/1171776/92df5eac-210e-11e3-84da-892d2b72cd14.png)

由於這是一個「沒有工作目錄的純儲存庫」，所以共用儲存庫也有個別名叫做「裸儲存庫」 (bare repository)。

再次強調，Git 屬於「分散式版本控管」，每個人都有一份完整的儲存庫(Repository)。也就是說，當你想要建立一個「工作目錄」時，必須先取得這個「裸儲存庫」的內容回來，這時你必須使用 `git clone [REPO_URI]` 指令「複製」(clone)一份回來才行，而透過 `git clone` 的過程，不但會自動建立工作目錄，還會直接把這個「裸儲存庫」完整的複製回來。這個複製的過程，就如同「完整備份」一樣，是把所有 Git 儲存庫中的所有版本紀錄、所有版本的檔案、...等等，所有資料全部複製回來。完整的指令操作過程可以參考以下圖示：

![image](https://f.cloud.github.com/assets/88981/1172547/daf71efe-2123-11e3-9209-6ba8f9933090.png)

在實務上，會使用「共用儲存庫」或「裸儲存庫」的方式可能有幾種：

* 在一台多人使用的機器上進行協同開發，可開放大部分人對這個「裸儲存庫的資料夾」僅有唯讀權限，只讓一個人或少許人才有寫入權限。
* 有些人會把裸儲存庫放到 Dropbox 跟自己的多台電腦同步這個裸儲存庫

請注意: 雖然「工作目錄」下的 `.git` 目錄也是一個「儲存庫」，不過工作目錄下的儲存庫還包含一些工作目錄下的索引資訊，紀錄著工作目錄下的狀態資訊，這些狀態資訊不會出現在 「共用儲存庫」裡面，這裡只有版本資訊而已 (也就是 Git 的物件資訊)。


在 GitHub 或其他 Git 平台建立遠端的儲存庫 (remote repository)
---------------------------------------

其實「遠端儲存庫」跟「共用儲存庫」幾乎是一樣的，差別僅在於「共用儲存庫」大多使用直接的檔案存取，而「遠端儲存庫」通常使用 SSH, Git protocol, HTTP 等協定可「遠端」存取 Git 儲存庫，其他的使用方式基本上是一樣的。

以下示範透過 GitHub 建立儲存庫，並將儲存庫複製回本地的情況：

* 先登入 GitHub，然後建立一個新的儲存庫

![image](https://f.cloud.github.com/assets/88981/1172599/00121f8e-2126-11e3-8753-21257e0f021d.png)

* 設定 GitHub 專案的相關資訊並建立儲存庫

![image](https://f.cloud.github.com/assets/88981/1172620/9519750a-2126-11e3-9045-eca7389dd777.png)

* 建立完成後，他會提示你要如何取得該專案，或將你本地現有的專案匯入到 GitHub

![image](https://f.cloud.github.com/assets/88981/1172626/cb1a1b6e-2126-11e3-96a2-a3ff259b602b.png)

* 如上圖，我們可以在 Quick setup 的地方點擊 "Set up in Desktop"，你的電腦會自動開啟 GitHub for Windows 工具，並自動複製(clone)這個儲存庫回來，並且建立工作目錄。

* 你也可以將遠端 Git 儲存庫的網址複製(Copy)下來，然後執行 `git clone [REPO_URL]` 即可複製(clone)一份回來。

![image](https://f.cloud.github.com/assets/88981/1172650/84f75934-2127-11e3-9a18-92ef9f033f91.png)


今日小結
-------

以上就是三種建立 Git 儲存庫的方式。我重新整理一下本日學到的 Git 指令與參數：

* git init
* git init --bare
* git clone [REPOSITORY_URI] 

參考連結
-------

*  [GETTING AND CREATING PROJECTS - Git Reference](http://gitref.org/creating/)
*  [Git for Windows](http://msysgit.github.io/)
*  [GitHub for Windows](http://windows.github.com/)



第 04 天：常用的 Git 版本控管指令
===========================================================

本篇文章將帶大家學會幾個最重要也最基本的版控工作，其中將包含基本的檔案操作如新增、刪除、重新命名檔案，提交變更 (建立新版本)、查詢歷史紀錄等工作。

準備工作目錄
-----------

複習一下上一篇「第 03 天：建立儲存庫」的內容，我們直接來建立一個本地儲存庫，即可開始本篇文章的所有練習。

	mkdir git-demo
	cd git-demo
	git init


新增檔案
--------

我們在工作目錄下放一些檔案，至於放什麼檔案都可以，總之先複製一些現有的檔案與目錄進到目前的工作目錄下。

本篇文章，我將以 [YEOMAN](http://yeoman.io/) 工具，快速產生一個 webapp 範例網站，只要一個指令就可以建立一個完整網站：

	yo webapp

**註**: 關於 [YEOMAN](http://yeoman.io/) 在 Windows 平台的使用，可以參考筆者的文章 [如何在 Windows 平台安裝與使用 Yeoman 1.0 相關工具](http://blog.miniasp.com/post/2013/08/11/Yeoman-1-0-Installation-and-Usage-on-Windows.aspx)，該文詳述完整的安裝與使用過程。

新增了檔案之後，如果你還在 Git Shell 介面下，應該會立刻看到如下圖的提示：

![image](https://f.cloud.github.com/assets/88981/1174070/809bfc4e-2142-11e3-9ba7-498ac2ea3b09.png)

也就是以下這段位於路徑後面的提示：

	[master +10 ~0 -0 !]

在這段提示的地方，你可以看到幾個東西：

* master 代表目前工作目錄是 **master** 分支，也是 Git 的預設分支名稱。
* 「紅色」的數字都代表 Untracked (未追蹤) 的檔案，也就是這些變更都不會進入版本控管。
* +10 代表有 10 個「新增」的檔案
* ~0  代表有 0 個「修改」的檔案
* -0  代表有 0 個「刪除」的檔案

如果要要將這些新增的檔案加入到 Git 版本控管，你必須下達以下指令：

	git add .

如此一來，這個工作目錄下所有的檔案、目錄與子目錄下的所有檔案，全部都會被加入到這個 Git 工作目錄的【索引】或【快取】之中。請注意: 此時並沒有建立任何版本，只是告知 Git 這些檔案「即將」被加入 Git 版本庫而已。

如下圖示，是我這邊執行完 `git add .` 之後的結果，這裡所發生的 warning 訊息不是很嚴重，有興趣了解的人可以參考筆者的另一篇文章: [Git 在 Windows 平台處理斷行字元 (CRLF) 的注意事項](http://blog.miniasp.com/post/2013/09/15/Git-for-Windows-Line-Ending-Conversion-Notes.aspx)。

![image](https://f.cloud.github.com/assets/88981/1174159/a93a1de2-2143-11e3-8be8-02defc6e7feb.png)

不過有趣的地方在於，原本「紅色的數字」現在卻變成了「綠色的數字」，這裡所代表的意義是：

* 「綠色」的數字都代表 Staged (準備好) 的檔案，也就是這些變更才會進入版本控管。
* +23 代表有 23 個「新增」的檔案將被建立一個版本
* ~0  代表有 0 個「修改」的檔案將被建立一個版本
* -0  代表有 0 個「刪除」的檔案將被建立一個版本

但原本不是只有 +10 (紅色) 而已嗎? 怎麼執行完後變成了 +23 (綠色) 呢？

我們執行 `git reset` 重設一下工作目錄的索引狀態，然後再執行一次 `git status` 查詢當前工作目錄的詳細狀態，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1174252/f7e382fc-2144-11e3-9021-b016de2f8dc3.png)

你可以發現，這邊列出的只有「第一層目錄下的檔案與目錄」而已，因為 git 不會這個時候去查到底目錄下到底有多少檔案沒有被追蹤。

當我們執行 `git add .` 之後，再執行一次 `git status` 查詢狀態，你可以發現連子目錄下的檔案也都全部被加入了，所以這個數字才會變多，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1174283/5e6c30aa-2145-11e3-89aa-a6c7363e5293.png)

新增部分檔案
------------

剛剛提到的 `git add .` 指令會自動將所有檔案(含子目錄的檔案)加入到工作目錄索引中，有時候我們只想讓特定目錄或特定檔案加入版本，這時你也可以指定特定目錄，或利用萬用字元來加入檔案。

我們再執行一次 `git reset` 重設工作目錄的索引狀態，然後用 `git add app` 加入 app 這個資料夾與其下的所有檔案，還有用 `git add .*` 新增所有「點」開頭的檔案，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1174397/0d767794-2147-11e3-9d2e-d063cf878a13.png)

![image](https://f.cloud.github.com/assets/88981/1174412/2fdf7c0e-2147-11e3-82c9-cc541fe30aa8.png)

在執行的過程中，你應該可以發現，在執行 `git add` 的過程中，Git Shell 提示的文字也有了些變化，現在同時出現了「綠色的數字」與「紅色的數字」，所代表的意思跟上述是一樣的，是不是非常方便辨識！當你需要知道詳情才需要執行 `git status` 指令。

**註**: 詳細的指令與參數說明，可以輸入 `git help add` 查詢完整的文件。

提交變更 / 建立版本
------------------

這時我們預計要建立一個新版本了，在建立版本之前，我們還是把所有檔案給加入吧，請各位在執行一次 `git add .` 命令。

建立版本的指令如下：

	git commit
	git commit -m "版本紀錄的說明文字"

在 Git 版本控管中，所有的版本都必須擁有「版本紀錄的說明文字」 ( 簡稱 Log )，不像 Subversion 預設可以簽入「沒有版本紀錄說明」的版本。所以當你直接輸入 `git commit` 的話，預設會開啟 Notepad (記事本) 讓你輸入這個版本的訊息。開啟後的檔案會有很多 # 符號開頭的文字，這些都是註解，不會成為 Log 的一部分。

如下圖示，是我輸入的訊息文字：

![image](https://f.cloud.github.com/assets/88981/1174514/baa9f4da-2148-11e3-97cc-c07aef98cf67.png)

當你按下 Ctrl+S 儲存這個文字檔，這時還不會建立一個新版本，還必須關閉這個 Notepad 視窗，這時才會正式建立版本，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1174571/a18b4778-2149-11e3-801f-5a3255999c37.png)

建立版本完後，Git Shell 的提示就只剩下 `[master]` 字樣了，代表目前已經沒有任何要被建立版本的索引或快取。

**註**: 詳細的指令與參數說明，可以輸入 `git help commit` 查詢完整的文件。

查詢歷史紀錄
-----------

由於我們剛剛建立了一個版本，當我們想要查詢版本的歷史紀錄，可以輸入以下指令：

	git log

![image](https://f.cloud.github.com/assets/88981/1174606/3b215e0e-214a-11e3-9b90-1bfe4275ca6d.png)

有時候紀錄越來越多，你也可以透過以下指令限制輸出的版本數量，你只要透過一個減號 ( - ) 與一個數字，就可以限定輸出最近幾筆紀錄：

	git log -10

**註**: 詳細的指令與參數說明，可以輸入 `git help log` 查詢完整的文件。

刪除檔案
----------

在 Git 指令列工具中也有個 `rm` 指令，可以用來刪除檔案。例如我們想刪除 `Gruntfile.js` 這個檔案，可以輸入以下指令：

	git rm 'Gruntfile.js'

![image](https://f.cloud.github.com/assets/88981/1174637/fba7e7e2-214a-11e3-91a6-698ac73b111c.png)

這個 `git rm` 的指令執行的時候，會同時做兩件事：

1. 刪除工作目錄快取的 'Gruntfile.js' 這個檔案 (用來標示這個刪除檔案的動作要列入版本控管)
2. 刪除工作目錄下的 'Gruntfile.js' 這個實體檔案 (代表真的把這個實體檔案給刪除)

**註**: 詳細的指令與參數說明，可以輸入 `git help rm` 查詢完整的文件。

檔案更名
----------

在 Git 指令列工具中也有個 `mv` 指令，可以用來變更檔案或目錄的名稱。例如我們想把 `test` 目錄更名為 `unit-test` 名稱，可以輸入以下指令：

	git mv test unit-test

![image](https://f.cloud.github.com/assets/88981/1174712/4279df1c-214c-11e3-892e-e25906440611.png)

**註**: 詳細的指令與參數說明，可以輸入 `git help mv` 查詢完整的文件。

顯示工作目錄的索引狀態
---------------------

剛剛我們一直會看到 `git status` 來顯示工作目錄的狀態，你也可以使用 `git status -s` 來顯示較為精簡的版本。

![image](https://f.cloud.github.com/assets/88981/1174822/62e8204a-214e-11e3-9d38-c950fd33e662.png)

**註**: 詳細的指令與參數說明，可以輸入 `git help status` 查詢完整的文件。

重置目前的工作目錄
-----------------

我們曾經學過如何利用 `git reset` 重置目前工作目錄的索引狀態，但請注意，這個指令預設只會重置「索引狀態」，那些你用 `git rm` 刪除的目錄或檔案，還是用 `git mv` 更名的目錄或檔案，透過 `git reset` 都無法把「實體檔案」給救回來。

如果想把工作目錄也給還原到目前的最新版，則必須輸入以下指令：

	git reset --hard

**註**: 詳細的指令與參數說明，可以輸入 `git help reset` 查詢完整的文件。


還原其中一個被改壞的檔案
----------------------

如果檔案編輯到一半，發現被改壞了，你希望能救回改沒修改前的版本，這時你可以利用以下指令還原檔案：

	git checkout master Gruntfile.js

![image](https://f.cloud.github.com/assets/88981/1174862/496df756-214f-11e3-84ec-b015204c8b0d.png)

這段指令的意思是把 `master` 分支中最新版的 Grunefile.js 給還原，由於我先前已經把 Gruntfile.js 給刪除了，為了要救回這一個檔，可以用這個方式救回。這樣可以避免使用 `git reset --hard` 一次把所有檔案都給還原了！

請注意，還原的過程也會一併復原工作目錄的索引狀態喔！

**註**: 詳細的指令與參數說明，可以輸入 `git help checkout` 查詢完整的文件。

今日小結
-------

今日的文章，可以說是在 Git 版本控管中不斷會重複使用的指令與參數，必須非常熟練才行，接下來的文章，將會詳細探討 Git 版本控管的內部結構，千萬不要錯過！

我重新整理一下本日學到的 Git 指令與參數：

* git init
* git add .
* git add app/*
* git add *.txt
* git status
* git status -s
* git commit
* git commit -m "版本紀錄的說明文字"
* git log
* git log -10
* git rm '*.txt'
* git rm 'app/*.html'
* git mv 'oldname' 'newname'
* git reset
* git reset --hard
* git checkout master 'filename'


參考連結
-------

* [BASIC SNAPSHOTTING](http://gitref.org/basic/)


第 05 天：了解儲存庫、工作目錄、物件與索引之間的關係
===============================================================

在使用 Git 版本控管的過程中，有些很基本的觀念必須被建立，這樣才能更有效率也更有意義的學下去。有清楚且正確的觀念支持，不但有助於你學習 Git 指令操作，更重要的是，學習 Git 相關知識也會更加上手。

了解儲存庫
---------

我們要使用 Git 進行版本控管，很自然的，我們需要一個「版本庫」來儲存這些版本資訊，而英文的 Repository 就是這個意思，筆者習慣將這個英文翻譯成「儲存庫」，代表用來儲存所有版本的一個空間或一個資料夾與一堆檔案。

如果有 Git 使用經驗的人，應該很清楚，建立儲存庫有很多方法，如果你要在任意一個資料夾建立一個 Git 儲存庫，只要輸入以下指令就可以建立完成：

    git init

我們透過下圖建立 Git 儲存庫的過程來說明，透過這張圖我們可以很清楚的知道，當我們在 G:\git-demo 目錄下執行 git init 之後，Git 會自動幫我們建立一個所謂的 Git repository 在該目錄的 .git 目錄下，各位不用懷疑，這個 .git 資料夾，就是一個完整的 Git 儲存庫，未來所有版本的變更，都會自動儲存在這個資料夾裡面。

![image](https://f.cloud.github.com/assets/88981/1143039/c56e206a-1d12-11e3-818c-3da01f052d02.png)


了解工作目錄
-----------

在上述這個例子裡，目錄 G:\git-demo 此時就會自動成為我們的「工作目錄」 (working directory)。所謂「工作目錄」的意思，就是我們正在準備開發的專案檔案，未來都會在這個目錄下進行編輯，無論是新增檔案、修改檔案、刪除檔案、檔案更名、...以及所有其他 Git 相關的操作，都會在這個目錄下完成，所以才稱為「工作目錄」。

我們在操作 Git 相關指令參數的時候，也通常都是在「工作目錄」下執行的。

由於在使用 Git 版本控管時，會遭遇到很多分支的狀況，所以工作目錄很有可能會在不同的分支之間進行切換，有些 git 指令在執行的時候，會一併更新工作目錄下的檔案。例如當你使用 git checkout 切換到不同分支時，由於目前分支與想要切換過去的分支的目錄結構不太一樣，所以很有可能會將你目前工作目錄下的檔案進行更新，好讓目前的工作目錄下的這些目錄與檔案，都與另一個要切換過去的分支下的目錄與檔案一樣。

所以，適時的保持工作目錄的乾淨，是版本控管過程中的一個基本原則，更尤其是日後要進行合併的時候，這點尤其重要，相關知識我會在日後的文章中進一步說明。 

了解 Git 的資料結構
-----------------

在 Git 裡有兩個重要的資料結構，分別是「物件」與「索引」。

「物件」用來保存版本庫中所有檔案與版本紀錄，「索引」則是用來保存當下要進版本庫之前的目錄狀態。

關於物件
-------

所謂的「物件」是一個「特別的檔案」，該檔案的產生過程很有趣，是將一個檔案的內容中取出，透過內容產生一組 SHA1 雜湊值，然後依照這個 SHA1 雜湊值命名的一個檔案。

在使用 Git 進行版本控管的過程中，所有要進行控管的目錄與檔案，都會先區分「目錄資訊」與「檔案內容」，我們稱為 tree 物件與 blob 物件。

其中 blob 物件就是把原本的「檔案內容」當成 blob 檔案的內容 (注意: blob 物件其實就是一個實體檔案)，然後再將其內容進行 SHA1 雜湊運算後產生的一個 hash id，再把這個 hash id 當成 blob 檔案的檔名。由此可知，blob 物件是一個「只有內容」的檔案，其檔名又是由內容產生的，所以，任何一的單獨存在的 blob 檔案通常對版本控管沒有任何幫助。

另一個 tree 物件，則是用來儲存特定資料夾下包含哪些檔案，以及該檔案對應的 blob 物件的檔名為何。在 tree 物件中，除了可以包含 blob 物件的檔名與相關資訊，還可以包含其他的 tree 物件。所以 tree 物件其實就是「資料夾」的代名詞。

無論 blob 物件與 tree 物件，這些都算是物件，這些物件都會儲存在一個所謂的「物件儲存區」 (object storage) 之中，而這個「物件儲存區」預設就在「儲存庫」的 objects 目錄下，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1143067/2b2e2c52-1d17-11e3-953c-ba8ea3749749.png)

詳細的物件結構，我們會在接下來的文章談到。

關於索引
-------

所謂的「索引」是一個經常異動的暫存檔，這個檔案通常位於 .git 目錄下的一位名為 index 的檔案。簡單來說，「索引」的目的主要用來紀錄「有哪些檔案即將要被提交到下一個 commit 版本中」。換句話說，如果你想要提交一個版本到 Git 儲存庫，那麼你一定要先更新索引狀態，變更才會被提交出去。

這個索引檔，通常保存著 Git 儲存庫中特定版本的狀態，這個狀態可以由任意一個 commit 物件，以及 tree 物件所表示。

我們通常不會直接去編輯 .git\index 這個二進位檔，而是透過標準的 git 指令去操作這個索引檔，對於索引檔的操作指令大概有以下幾個：

* git add
* git mv
* git rm
* git status
* git commit
* git ls-files

Git 的「索引」是一個介於「物件儲存區」 (object storage) 與「工作目錄」 (working directory) 之間的媒介。

各位也許已經可以猜到，本篇文章想闡述的這幾個觀念之間的關係，可以用以下 5 個步驟解釋：

* 要使用 Git 版本控管，你必須先建立「工作目錄」與「版本庫」。(mkdir, git init)
* 你要先在「工作目錄」進行開發，你可能會建立目錄、建立檔案、修改檔案、刪除檔案、... 等操作。
* 然後當你想提交一個新版本到 Git 的「儲存庫」裡，一定要先更新「索引」狀態。(git add, git mv, ...)
* 然後 Git 會依據「索引」當下的狀態，決定要把那些檔案提交到 Git 的「儲存庫」裡。(git status)
* 最後提交變更時 (git commit)，才會把版本資訊寫入到「物件儲存區」當中 (此時將會寫入 commit 物件)。

詳細的索引結構與指令操作，我們會在接下來的文章談到。

    註: 由於 tree 的概念跟 directory 很像，所以在看國外原文時，working directory 也經常被寫成 working tree！

今日小結
-------

今天探討的 Git 架構，最重要的還是在「物件」與「索引」之間的關係，因為沒有「索引」資訊，Git 就無法建立版本。

而基於「物件」與「索引」的差異，你應該可以發現，「物件」是屬於一種「不可變的」 (immutable) 檔案類型，任何寫入到「物件儲存區」的物件，原則上都不會再發生異動，因為所有的物件都是從原本的檔案內容產生的。我們也可以說這是一個「物件資料庫」 (object database)，且這個資料庫通常只會增加內容，比較不會有「刪除內容」或「異動內容」的情況，只有在執行 git gc 清除垃圾資料時才會刪除資料。「索引」則是屬於一種「可變的」 (mutable) 索引檔，用來記錄目前工作目錄準備要 commit 的內容。

當你一步一步的接近 Git 核心，慢慢地將模糊不清的抽象概念，轉變成具象的觀念知識，你就不會再對 Git 感到不安，請繼續努力學習，成功就在前方。


參考連結
-------

* [Git Internals - Git Objects](http://git-scm.com/book/en/Git-Internals-Git-Objects)
* [Pro Git Book](http://progit.org/)
* [Git Magic - 繁體中文版](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_tw/)
* [Git (software) - Wikipedia, the free encyclopedia](http://en.wikipedia.org/wiki/Git_(software) "Git (software) - Wikipedia, the free encyclopedia")



第 06 天：解析 Git 資料結構 - 物件結構
=====================================================

在 Git 的資料結構中，「物件」是一種「不可變的」 (immutable) 檔案類型，所有儲存在「物件儲存區」的檔案通常只進不出，也不會被修改內容。原因在於，如果你竄改了檔案了內容，新的內容所運算出來的 SHA1 雜湊值將會與原有物件的檔名不一樣，這導致 Git 無法繼續執行，相對地也對 Git 儲存庫產生了一定程度的保護作用。本篇文章，將更加仔細地介紹 Git 的物件結構，最後也會透過一則影片，詳細解說整個物件被產生的過程與邏輯。

關於物件資料庫
------------

前一篇文章有提到，無論 blob 物件與 tree 物件，這些都算是物件，這些物件都會儲存在一個所謂的「物件儲存區」 (object storage) 之中，而這個「物件儲存區」預設就在「儲存庫」的 objects 目錄下，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1143067/2b2e2c52-1d17-11e3-953c-ba8ea3749749.png)

然而 Git 儲存庫中的每一個「物件」，都是以「檔案內容」進行 SHA1 雜湊運算出一個 hash 值，並用這個 hash 值當作物件的名稱 (檔名)。我們以 8a6b275638f3cf164395e65066a1132bb36b7896 為例，Git 會先拿前兩個字元(8a)當作目錄，然後把剩下的 hash 值當成檔名 (6b275638f3cf164395e65066a1132bb36b7896)，這些物件的實體目錄與檔案也都會放在 .git\objects 目錄下，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1114191/87b5e156-1a13-11e3-9355-9524a3f651b2.png)

物件的類型
---------

在這些「物件資料庫」裡面，又包含了 4 種物件類型，分別是：

1. **blob 物件**：就是工作目錄中某個檔案的 "內容"，且只有內容而已，當你執行 git add 指令的同時，這些新增檔案的內容就會立刻被寫入成為 blob 物件，檔名則是物件內容的雜湊運算結果，沒有任何其他其他資訊，像是檔案時間、原本的檔名或檔案的其他資訊，都會儲存在其他類型的物件裡 (也就是 tree 物件)。
2. **tree 物件**：這類物件會儲存特定目錄下的所有資訊，包含該目錄下的檔名、對應的 blob 物件名稱、檔案連結(symbolic link) 或其他 tree 物件等等。由於 tree 物件可以包含其他 tree 物件，所以瀏覽 tree 物件的方式其實就跟檔案系統中的「資料夾」沒兩樣。簡單來說，tree 物件這就是在特定版本下某個資料夾的快照(Snapshot)。
3. **commit 物件**：用來記錄有那些 tree 物件包含在版本中，一個 commit 物件代表著 Git 的一次提交，記錄著特定提交版本有哪些 tree 物件、以及版本提交的時間、紀錄訊息等等，通常還會記錄上一層的 commit 物件名稱 (只有第一次 commit 的版本沒有上層 commit 物件名稱。
4. **tag 物件**：是一個容器，通常用來關聯特定一個 commit 物件 (也可以關聯到特定 blob、tree 物件)，並額外儲存一些額外的參考資訊(metadata)，例如: tag 名稱。使用 tag 物件最常見的情況是替特定一個版本的 commit 物件標示一個易懂的名稱，可能是代表某個特定發行的版本，或是擁有某個特殊意義的版本。

Git 會將每一個版本中的檔案建立一個對應的 blob 物件，一樣的，該 blob 物件的檔名就是用上述的方式計算出來的，從這些 blob 檔案，你看不出跟版本有任何關係，你必須透過 tree 物件 (資料夾的快照) 與 commit 物件 (每一個版本的快照) 才能關聯出這些 blob 與版本的關係。

所有的物件都會以 zlib 演算法進行壓縮，不但可以有效的提升檔案存取效率，在日後進行封裝(pack)的時候也可以利用差異壓縮(delta compression)演算法來節省空間。他會自動找出相似的 blobs，並自動計算出 blob 之間的變化差異，再將這些差異儲存在一個名為 *packfile* 的檔案中，這樣就可以大幅節省磁碟空間的耗用)。通常 *packfile* 會置於 .git\objects\pack 目錄下，如下圖示：


![image](https://f.cloud.github.com/assets/88981/1143218/3626d60c-1d28-11e3-93b4-cd5ec3419b7d.png)

上述這四種物件之間的關係，可參考以下圖示：

![image](http://journal.code4lib.org/media/issue21/anderson/images/large/fig-09-git-revisions.png)

然而，光是觀看文字與圖示，或許還是難以看出這幾種物件類型之間的關係，沒關係，筆者特別錄製了一段教學影片，試圖用 git 指令的方式解釋 Git 的物件結構與產生物件的過程，也讓各位更清楚的了解到底 Git 如何產生與管理這些檔案。

YouTube 影片連結：[認識 Git 資料結構中的物件資料庫與物件之間的關係](http://www.youtube.com/watch?v=PZbSRy_ow0U)

物件結構的優點
------------

你應該可以漸漸了解 Git 的「物件」設計是如此的漂亮，我們在第一篇文章曾經提到幾個 Git 重要的設計，我們重新列出幾點與「物件」特性有關的設計來看看：

* 有效率的處理大型專案
	* 不僅僅是完整的版本庫會複製(clone)一份在本機，由於所有的 blob 物件都是透過「內容」來做定址的 (content addressable)，因此，若在不同版本之間找尋相同的內容，效率是非常高的。
* 歷史紀錄保護
	* Git 版控的過程，每次提交變更都會產生一個 commit 物件，而這個 commit 物件的名稱又是透過 commit 物件的內容產生。再者，commit 物件會關連到 tree 物件，tree 物件的名稱又是透過 tree 物件的內容所產生。tree 物件又會關聯到 blob 與 tree 物件，這些物件的名稱也是透過內容產生。就這樣一層一層的關聯下去，如果你今天真的想竄改某個版本的歷史紀錄，困難度也是挺高的！
	* 由於 Git 儲存庫經常會被 clone 或 fork，只要是被 clone 過的儲存庫，來源的儲存庫只要任何一個物件被修改，這些 clone 出去的儲存庫就很難再合併回來，所以你幾乎不可能任意竄改版本紀錄。
* 定期的封裝物件
	* 我們在 Git 中提到的 "物件" 其實就是代表版本庫中的一個檔案。而在版本異動的過程中，專案中的程式碼或其他檔案會被更新，每次更新時，只要檔案內容不一樣，就會建立一個新的 "物件"，這些不同內容的檔案全部都會保留下來。
	* 你應該可以想像，當一個專案越來越大、版本越來越多時，這個物件會越來越多，雖然每個檔案都可以各自壓縮讓檔案變小，不過過多的檔案還是會檔案存取變得越來越沒效率。因此 Git 的設計有個機制可以將一群老舊的 "物件" 自動封裝進一個封裝檔(packfile)中，以改善檔案存取效率。
	* 那些新增的檔案還是會以單一檔案的方式存在著，也代表一個 Git 版本庫中的 "檔案" 就是一個 Git "物件"，但每隔一段時間就會需要重新封裝(repacking)。
	* 照理說 Git 會自動執行重新封裝等動作，但你依然可以自行下達指令執行。例如: git gc
	* 如果你要檢查 Git 維護的檔案系統是否完整，可以執行以下指令: git fsck 


今日小結
-------

Git 裡的「物件」十分重要，其特性也十分重要，雖然我們在操作 Git 指令的過程中通常不太需要直接接觸這些檔案，不過了解這些物件的存在，也確實有助於讓你更加理解 Git 的運作模式，與 Git 獨到的設計概念。



參考連結
-------

* [Git Internals - Git Objects](http://git-scm.com/book/en/Git-Internals-Git-Objects)
* [Pro Git Book](http://progit.org/)
* [Git Magic - 繁體中文版](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_tw/)
* [Git (software) - Wikipedia, the free encyclopedia](http://en.wikipedia.org/wiki/Git_(software) "Git (software) - Wikipedia, the free encyclopedia")



第 07 天：解析 Git 資料結構 - 索引結構
=====================================================

我們知道在 Git 裡兩個重要的資料結構，分別是「物件」與「索引」，這篇文章主要用來解說「索引」的細節。使用 Git 版本控管的過程中，或許你可以很輕易的了解 git 指令的用法，不過那很容易流於死記，無法靈活運用，連 Linus Torvalds 都在郵件清單(Mailing List)中提到：「在使用者了解索引的意義之前，是無法完整了解 Git 的能力的」，因此，了解「索引」的用途十分重要。

關於索引
-------

簡單來說，「索引」的目的主要用來紀錄「有哪些檔案即將要被提交到下一個 commit 版本中」。

換句話說，「如果你想要提交一個版本到 Git 儲存庫，那麼你一定要先更新索引狀態，變更才會被提交出去。」

這裡的「索引」其實在國外很多文章裡曾經出現過很多別名，但其意思都是相同的，各位以後看到相關單字千萬不要被混淆了。

* Index (索引)
* Cache (快取)
* Directory cache (目錄快取)
* Current directory cache (當前目錄快取)
* Staging area (等待被 commit 的地方)
* Staged files (等待被 commit 的檔案)

幾個例子來說，指令 `git diff --cached` 就與 `git diff --staged` 是完全同義的。

操作索引的指令
-------------

由於「索引」對 Git 來說十分重要，在大多數的指令中都會有跟 Git 索引相關的參數可用，不過我們大致列出幾個直接與「索引」相關的指令來解說。

在解說指令之前，各位可以先看看以下示意圖，這說明了透過指令改變狀態的生命週期，事實上，這些改變的過程，都是在更新「索引檔」的過程：

![image](http://git-scm.com/figures/18333fig0201-tn.png)

首先，先介紹四種檔案狀態：

* untracked (未追蹤的，代表尚未被加入 Git 儲存庫的檔案狀態)
* unmodified (未修改的，代表檔案第一次被加入，或是檔案內容與 HEAD 內容一致的狀態)
* modified (已修改的，代表檔案已經被編輯過，或是檔案內容與 HEAD 內容不一致的狀態)
* staged (等待被 commit 的，代表下次執行 git commit 會將這些檔案全部送入版本庫)



### git status

取得 **工作目錄** (working tree) 下的狀態。

由於先前幾經講過儲存庫、工作目錄、物件與索引之間的關係，我們用一句話說明這關係：

	Git 儲存庫的運作，是將工作目錄裡的變化，透過更新索引的方式，將資料寫入成 Git 物件。

這裡的 `git status` 指令，目的是顯示出 **目前最新版** 與 **索引檔** 之間的差異，這當中的差異包含了一些微妙的關係，我們用一個例子來解釋這層關係。

以下是執行 git status 的結果：
	
	G:\git-demo>git status
	# On branch master
	# Changes to be committed:
	#   (use "git reset HEAD <file>..." to unstage)
	#
	#       new file:   c.txt
	#
	# Changes not staged for commit:
	#   (use "git add <file>..." to update what will be committed)
	#   (use "git checkout -- <file>..." to discard changes in working directory)
	#
	#       modified:   a.txt
	#
	# Untracked files:
	#   (use "git add <file>..." to include in what will be committed)
	#
	#       b.txt

這裡你會看到有三種不同的分組，分別是：

* Changes to be committed (準備提交的變更)
	* 這區有個 `new file: c.txt` 檔案，代表 c.txt 是一個新檔案，而且已經被標示可提交。
	* 這代表著幾件事：
		1. **目前最新版** 並沒有 c.txt 這個檔案
		2. **索引檔** 已經加入了這個 c.txt 檔案
		3. 所以該檔案會在執行 git commit 之後被存入下一個版本
* Changes not staged for commit (尚未準備提交的變更)
	* 這區有個 `modified: a.txt` 檔案，代表 a.txt 已經被變更，但尚未標示可提交。 (not staged)
	* 這代表著幾件事：
		1. **目前最新版** 也有 a.txt 這個檔案
		2. **索引檔** 尚未加入 a.txt 這個檔案
		3. 所以該檔案就算執行了 git commit 也不會在下一版中出現
* Untracked files (未追蹤的變更)
	* 這區有個 `b.txt` 檔案，代表 b.txt 尚未被追蹤。(untracked)
	* 這代表著幾件事：
		1. **目前最新版** 沒有 b.txt 這個檔案
		2. **索引檔** 也沒有 b.txt 這個檔案
		3. 所以該檔案就算執行了 git commit 也不會在下一版中出現

所以你可以看到，執行 git status 就是為了查出 **目前最新版** 與 **索引檔** 之間的差異，最終只有 **目前最新版** 與 **索引檔** 之間有差異的變更，才會真正儲存到下一個 commit 物件裡。

### git add 

`git add` 指令，是為了將目前「工作目錄」的變更寫入到「索引檔」裡。

使用 `git add -u` 則可以僅將「更新」或「刪除」的檔案變更寫入到「索引檔」中。

### git rm

我們以 `git rm` 為例，當你直接在檔案系統中刪除一個檔案，這只是從「工作目錄」中刪除而已，並沒有更新到索引檔，你可以利用 git status 看到這層改變，不過若要真正把「刪除」的狀態寫進索引檔的話，則要靠 `git rm filename` 更新索引檔。 

在執行 `git rm filename` 的時候，除了更新索引檔之外，連工作目錄下的檔案也會一併被刪除。若你只想刪除索引檔中的該檔，又要保留工作目錄下的實體檔案，那麼你可以在指令列加上 `--cached` 參數，就能做到，例如：

    git rm --cached a.txt 

### git mv

使用 `git mv oldname newname` 可以將檔案更名，執行此命令會同時更新索引與變更工作目錄下的實體檔案。 

### git commit

這個指令，則是把「索引檔」與「目前最新版」中的資料比對出差異，然後把差異部分提交變更成一個 commit 物件。

### git ls-files

在索引檔之中，預設就包含了 **目前最新版** 的所有檔案，外加你在工作目錄中新增檔案且透過 `git add` 更新索引檔後的那些檔案。透過 `git ls-files` 命令，可以列出所有目前已經儲存在「索引檔」中的那些檔案路徑。

從如下圖範例，你應該可以看出這幾個指令之間的關係：

![image](https://f.cloud.github.com/assets/88981/1143317/476ba898-1d32-11e3-9734-79667eb83db4.png)


今日小結
-------

Git 裡的「索引」是 Git 版控中最重要的觀念，有了這層觀念，也自然能得知，為什麼每次提交變更都要打一些指令把變更給加進去。當然，也有許多好用的 GUI 工具可以幫你少打許多指令，不過在我們正式開始使用 Git 的 GUI 工具之前，我們還是多靠指令把觀念給建立再說吧！ 


參考連結
-------

* [What is the deal with the Git Index? What is the Git Index? - GitGuys](http://www.gitguys.com/topics/whats-the-deal-with-the-git-index/)
* [Git - Recording Changes to the Repository](http://git-scm.com/book/en/Git-Basics-Recording-Changes-to-the-Repository)
* [Pro Git Book](http://progit.org/)
* [Git Magic - 繁體中文版](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_tw/)
* [Git (software) - Wikipedia, the free encyclopedia](http://en.wikipedia.org/wiki/Git_(software) "Git (software) - Wikipedia, the free encyclopedia")



第 08 天：關於分支的基本觀念與使用方式
===========================================================

在 Git 裡面 **分支** (Branch) 是個非常重要的機制，使用上也必須特別小心，因為專案總不能無限制的「分支」下去，最終總是要合併的，但合併是日後的議題，這篇文章將會先帶大家學會 Git 分支基本觀念與使用方式。

關於分支的基本觀念
----------------

在版本控管中使用「分支」機制，最主要的目的就是用來解決開發過程中版本衝突的問題。筆者認為，有許多曾經用過任何版本控管機制的人，都會認為「分支」是個「產生版本衝突」的元兇，因為當你開始分支之後，一定就會想到合併的議題，而當分支之後，若是有人跟你一樣修改到相同檔案的相同一行時，就會引發「版本衝突」，而只要發生衝突，就必須費心解決。

當衝突發生時，有時可以很輕易的決定要用自己的版本或是對方的版本，但有時卻沒那麼容易，複雜的時候還要依據衝突的片段，找到當初改過這幾行的人出來，協調出彼此的變更對系統的影響，最後決定要怎樣合併，諸如此類的問題非常繁瑣，也因此很多人會盡力避免「分支」的情況發生，以免發生「衝突」。

不過，若是開發團隊越來越大，系統功能越來越多，就算你不對版本做分支，大家的衝突情況一樣也會層出不窮，有時候還不是衝突的問題，而是 A 寫好一個功能，但被 B 的後續版本給蓋掉了，然後沒有任何衝突發生，這也不是大家所樂見的。然而，這也是一種「無形的衝突」狀況。

以前在集中管理的 Subversion 版控機制中，也有分支的概念，也可以運作的很好。當然，如果你的軟體架構不夠好，如果你對分支的概念、工具的使用也不是很清楚，我相信使用「分支」時也不會多順利，這是個必然的結果，這世界絕不會有「免學、無痛、自然學會分支」的這種版本控管工具出現，事在人為，人的觀念不對，用什麼工具都不會順的。

由於 Git 屬於「分散式版本控管機制」，在分散式版本管理的使用情境中，最不想做的事情就是「管理」，所以 Git 很少有所謂的管理機制或權限控管機制，它唯一想做的僅僅是讓大家可以順利的「分支」與「合併」而已。

我們以【第 03 天：建立儲存庫】這篇文章提到的「遠端的儲存庫 (remote repository)」為例，你可以這樣想像：從我們使用 `git clone` 指令開始，其實就是「分支」的開始，你從遠端儲存庫複製一份完整的儲存庫下來，然後開始在自己的本地端建立版本，等軟體修訂到一定程度後再「合併」回去，只是這時合併的指令叫做 `git push` 而已。

這種分支與合併的情形，在 Git 版本控管的過程中無所不在，遠端的儲存庫可以有分支，本地的儲存庫可以有分支，你可以從遠端任何一個分支合併(pull)到本地分支，也可以將本地的分支推向(push)遠端的分支，你當然也可以從本地任何一個分支合併(merge)到本地的另一個分支。可以想見，如果「分支」沒有一套良好的控管邏輯，最後可以組合出各種極其複雜的版本控管使用情境，這也不是大家所樂見的。因此，好好學會「分支」與「合併」真的非常重要。例如 git-flow 就是一套廣受歡迎的分支管理模式，這不是一套工具，而是一種管理分支的邏輯，這部分在我未來的文章中將會加以說明。

Linux kernel 發展的過程，在全世界有成千上萬的開發人員共同參與，為了管理這麼大量的開發團隊，Git 儼然而生，這是套分散式的版控機制，每個人都有完整的版本，版本散出去之後，大家必須管好自己的版本，然後遵照團隊的要求合併回來。然而，在合併回來之前，這套機制確保每個人都能夠順利的開發，不受任何其他開發人員的版本而影響，而 Git 確實做到了這點，同時又降低了版本控管的複雜度。

當然，我也必須講，如果參與軟體開發的團隊只有兩三人，而且這些人還都聚在一起，那確實不一定要使用 Git 版本控管，使用 Subversion 也是個很好的選擇，簡單又直覺，開發的過程中若遇到問題，前後左右協調一下就能解決，這比讓整個團隊都來了解 Git 來的方便很多。

如果你的團隊有點規模，或大家並沒有坐在一起工作，又要做版本控管的話，或許 Git 是個不錯的選擇，但工作團隊之間擁有一致的版控觀念或習慣，也是非常重要的一件事。


準備工作目錄
-----------

我們透過以下指令快速建立一個擁有兩個版本的 Git 儲存庫與工作目錄：

	mkdir git-branch-demo
	cd git-branch-demo
	git init
	
	echo. > a.txt
	git add .
	git commit -m "Initial commit"
	
	echo 1 > a.txt
	git add .
	git commit -m "a.txt: set 1 as content"

接著使用 `git log` 取得版本資訊如下：
	
	C:\demo\git-branch-demo>git log
	commit b917758c0f2f347a895ee5bbb5e5c8228f66335a
	Author: Will <doggy.huang@gmail.com>
	Date:   Fri Oct 4 20:58:16 2013 +0800
	
	    a.txt: set 1 as content
	
	commit aa3e4fe2ee065b046e00a74b1f12a0b0f8154003
	Author: Will <doggy.huang@gmail.com>
	Date:   Fri Oct 4 20:04:39 2013 +0800
	
	    Initial commit

接著我們透過 `git branch` 指令得知我們已經擁有一個名為 `master` 的分支，這是在 Git 儲存庫中的預設分支。如果你嘗試透過 `git branch -d master` 刪除這個分支，將會得到 `error: Cannot delete the branch 'master' which you are currently on.` 的錯誤訊息，這意思是「當你目前工作目錄分支設定為 master 時，不能刪除目前這個分支」，也就是說，你必須先切換到「其他分支」才能刪除這個分支。

![image](https://f.cloud.github.com/assets/88981/1269261/75173320-2cf5-11e3-905f-b899bd1e6196.png)

當然，我們現在只有一個分支，自然無法刪除自己。


建立分支
--------

建立分支最常見有兩種方法，分別是：

1. 建立分支，但目前工作目錄維持在自己的分支: `git branch [BranchName]`

	當我執行 `git branch newbranch1` 指令，這會建立一個新的 `newbranch1` 分支，我們接著用 `git branch` 查看目前有多少分支，你會看到兩個，但目前工作目錄還會停留在 `master` 分支上，如下圖示：

	![image](https://f.cloud.github.com/assets/88981/1269286/3877cf0a-2cf6-11e3-8928-70014298ca21.png)

	如果這時你在目前的工作目錄建立版本，這時會建立在 `master` 分支裡面，我們這時建立一個新檔案，並且透過 `git commit` 建立版本，指令如下：

		echo master > b.txt
		git add .
		git commit -m "Create b.txt with content 'master' in the master branch"

	請先記得：我們先在預設的 `master` 分支建立兩個版本，然後建立一個分支，然後在 `master` 分支又建立了一個版本。

2. 建立分支，並將目前工作目錄切換到新的分支: `git checkout -b [BranchName]`

	接下來，我們用第二種方法建立分支，當我執行 `git checkout -b newbranch2` 指令，不但會建立一個新分支，還會將目前工作目錄切換到另一個分支，最後用 `git branch` 查看目前有多少分支，你會看到已經有三個，而且目前工作目錄已經切換到剛剛建立的 `newbranch2` 分支上，如下圖示：

	![image](https://f.cloud.github.com/assets/88981/1269372/d8fa1e3c-2cf7-11e3-80c9-fdebf4fd5d43.png)

	如果這時你在目前的工作目錄建立版本，這時會建立在 `newbranch2` 分支裡面，我們這時建立一個新檔案，並且透過 `git commit` 建立版本，指令如下：

		echo newbranch2 > b.txt
 		git add .
		git commit -m "Modify b.txt with content 'newbranch2' in the newbranch2 branch"

	請記得：我們先在預設的 `master` 分支建立兩個版本，然後建立一個分支，然後在 `master` 分支又建立了一個版本，接著又把當下這份 `master` 分支的狀態建立一個新的 `newbranch2` 分支，並將工作目錄到切換到 `newbranch2` 分支，然後再建立一個版本。我們這時如果執行 `git log` 會顯示出 4 個版本紀錄，因為分支會自動繼承來源分支的完整歷史。

**註**: 詳細的指令與參數說明，可以輸入 `git help branch` 查詢完整的文件。

	git branch [branch_name]

切換分支
--------

如果你想將工作目錄切換到其他分支，你可以輸入以下指令 (不含 -b 參數)：

	git checkout [branch_name]

假設我們想把工作目錄切換到 `newbranch1` 分支，這時可以輸入 `git checkout newbranch1` 切換過去，然後你可以立刻使用 `git branch` 檢查目前工作目錄是否切換過去，然後再用 `git log` 檢查當下 `newbranch1` 分支的歷史紀錄。因為這是我們第一次建立的分支，照理說這個分支狀態應該只會有兩筆歷史紀錄而已，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1269498/03d8f4d2-2cfa-11e3-8c5c-52c505f850ac.png)

**註**: 詳細的指令與參數說明，可以輸入 `git help checkout` 查詢完整的文件。

	git checkout [branch_name]

刪除分支
---------

如果你想刪除現有的分支，就如同我們在**準備工作目錄**有提到過的指令，如下：

	git branch -d [branch_name]

先前也有提到，你不能刪除目前工作目錄所指定的分支，必須先切換到其他分支後，再刪除你目前這個分支。舉個例子來說，如果你想刪除當下這個 `newbranch1` 分支，那麼你必須先切換到其他分支，例如 `master` 分支，然後再下達 `git branch -d newbranch1` 指令，即可刪除分支，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1269540/e1c44e90-2cfa-11e3-88d9-3e03f86f112f.png)

查看工作目錄在哪個分支
--------------------

你可以透過 `git status` 命令，查看目前所在分支，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1269603/0456252c-2cfc-11e3-8cd5-f6146c0b97ee.png)

查看 Git 儲存庫的完整分支圖
-------------------------

最後，我用 SourceTree 工具來顯示目前 Git 儲存庫的分支圖。目前我們只有兩個分支，一個是 `master` 分支，另一個是 `newbranch2` 分支，因為 `newbranch1` 分支已經在練習的過程中被刪除了。為了要讓我們的分支有「樹狀」的感覺，接下來我要示範如何重新建立一個與先前 `newbranch1` 一樣狀態的分支，並且在這個分支下加入一個新版本。

不知道各位還記不記得，我們是在 `master` 分支建立兩個版本後才建立 `newbranch1` 分支的，現在我們就先找到到這個版本的 commit 物件 id，透過 `git log` 即可取得，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1269705/9d4b2772-2cfd-11e3-9397-0e3829717628.png)

所以我的 commit 物件 id 為: b917758c0f2f347a895ee5bbb5e5c8228f66335a

接著我先把工作目錄切換到這個版本，透過 `git checkout [commit_id]` 即可完成這個任務：

	git checkout b917758c0f2f347a895ee5bbb5e5c8228f66335a

這時你用 `git log` 應該只會看到兩個版本紀錄而已，因為我們已經把工作目錄的狀態切換成這個版本了。從下圖可以看到我們執行 `git checkout b917758c0f2f347a895ee5bbb5e5c8228f66335a` 時會出現一對訊息，這些訊息很重要，必須了解一下，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1269739/28a0f928-2cfe-11e3-86f9-6a13a649d523.png)

首先，由於你將工作目錄的版本切換到「舊的」版本，所以你會被提示這個工作目錄已經進入了所謂的 **detached HEAD** 狀態，這是一種「目前工作目錄不在最新版」的提示，你可以隨時切換到 Git 儲存庫的任意版本，但是由於這個版本已經有「下一版」，所以如果你在目前的「舊版」執行 `git commit` 的話，就會導致這個新版本無法被追蹤變更，所以建議不要這麼做。

若你要在 **detached HEAD** 狀態建立一個可被追蹤的版本，那麼正確的方法則是透過「建立分支」的方式來追蹤，現在我們就要在這個版本建立一個新的 `newbranch1` 分支，並將工作目錄切換過去，指令如下：

	git checkout -b newbranch1

![image](https://f.cloud.github.com/assets/88981/1269800/46a911b6-2cff-11e3-9cda-9a3f1a9c738c.png)

然後我們再建立一個新檔案 `b.txt`，內容為 `newbranch1`，並建立一個新版本，指令如下：

	echo newbranch1 > b.txt
	git add .
	git commit -m "Add b.txt in newbranch1"

好了，我們現在有了 `master` 以外的兩個分支，而且兩個分支都有自己的版本，你先在腦中思考一下這棵樹長怎樣！

接著我們開啟 SourceTree 工具，並將這個工作目錄加入到 SourceTree 的管理工具中：

![image](https://f.cloud.github.com/assets/88981/1269834/fdead6a2-2cff-11e3-84af-822eeb08fa6a.png)

![image](https://f.cloud.github.com/assets/88981/1269843/39d1461a-2d00-11e3-9281-50a3f30f754a.png)

加入後，我們切換到這個 Git 儲存庫的分支，總共有三個，我們分別切換過去看看：

![image](https://f.cloud.github.com/assets/88981/1269858/5f198fa4-2d00-11e3-8f1b-b1341464db6d.png)

![image](https://f.cloud.github.com/assets/88981/1269866/7547fcd4-2d00-11e3-98bb-a8da51b34223.png)

![image](https://f.cloud.github.com/assets/88981/1269871/83b4e732-2d00-11e3-9020-d43260bae2c9.png)

最早的版本在最下面，最新版在最上面，當我們切換到不同的分支，你可看到這三個個分支圖示都一樣，只有預設停留的「光棒」不一樣。首先，從圖片來看，你看到的是「整份 Git 儲存庫」中的所有版本、所有分支，以及該分支是從哪個版本開始建立分支的。而「光棒」則是該分支的「最新版」位於整個 Git 版本庫的哪個版本。


今日小結
-------

其實在 Git 裡面使用分支是很容易的事，難的地方在於讓大家都知道「分支」到底在做什麼，還有大家對「分支」的**想像**是否是一致的，只要大家對分支的想像是一致的，在團隊版控上就不會有太大的落差。

對我來說，分支我會把它想像成一種「快照」功能，把某個 commit 版本與其歷史版本建立出一個快照，然後複製一份出來，並給予一個分支名稱，你可以在這些分支上建立版本，等待日後進行合併。

而整份 Git 儲存庫，則會保留所有的分支與版本，最終呈現出一個樹狀架構的分支圖，我們最後透過 SourceTree 工具可以清楚的看到 Git 儲存庫中的分支狀況與版本變化。這張圖，我很早就看過，但第一次完全看不懂，只覺得是「一張圖」，沒有感覺，但自從越來越了解 Git 之後，這張分支圖可以讓我一目了然的理解整個 Git 儲存庫的變化情形，也更容易掌握 Git 的版本變化。

希望可以透過我的文字與指令搭配圖片示範，讓大家在自己腦中勾勒出一個分支架構，對 Git 分支結構有更深層的理解。

我重新整理一下本日學到的 Git 指令與參數：

* git branch
* git branch [branch_name]
* git checkout -b [branch_name]
* git checkout [branch_name]
* git branch -d [branch_name]
* git log 

參考連結
-------

* [BRANCHING AND MERGING](http://gitref.org/branching/)


第 09 天：比對檔案與版本差異
===========================================

使用任何版本控管軟體的過程中，經常會需要查看歷史紀錄與比對版本之間的差異。而在使用 Git 的時候要如何進行比對，將是本文重點。

準備工作目錄
-----------

我們透過以下指令快速建立一個擁有兩個檔案與兩個版本變更紀錄的 Git 儲存庫與工作目錄：

	mkdir git-demo
	cd git-demo
	git init
	
	echo 1 > a.txt
	echo 2 > b.txt
	git add .
	git commit -m "Initial commit"
	
	echo 3 > a.txt
	echo 4 > b.txt
	git add .
	git commit -m "Update a.txt and b.txt to 3 and 4"


關於 git diff 的基本觀念
------------------------

在 Git 中比對兩個版本之間的差異，通常會用 `git diff` 命令，我們先執行一個簡單的命令，比對兩個版本之間的差異：

1. 先執行 `git log` 取得版本資訊，並取得最近兩個 commit 物件的 id
2. 我們在執行 `git diff commit1 commit2` 指令，比對兩個版本間的差異，其中 commit1 請用較舊的版本，而 commit2 則用較新的版本。

如下圖示：

![image](https://f.cloud.github.com/assets/88981/1287745/7486ee5e-2ffd-11e3-9a5b-6b7545dfbbc3.png)

我們從 `git diff` 執行的輸出結果，將可得到一個執行的結果。由於我們這兩個版本庫中有兩個檔案，而且在這兩個版本之間也都有異動，所以他會列出兩段「差異比對」的結果。

各位可以從上圖看到每一段都是以 `diff --git` 開頭，代表 git 對哪兩個檔案進行比對。

第二行的 `index 37bcc8b..d855592 100644` 則是代表 git 在做這次比對時的｢標頭資訊｣(Header Line)，這裡可能會有好幾行，資訊不一定只有這些。這裡會標示許多關於此次差異比對的額外資訊。例如 index 這行，後面的兩個 hash id (`37bcc8b..d855592`) 就代表在 Git 物件儲存庫(object storage)中的兩個 blob 物件 id，用來比較這兩個 blob 物件。在後面的 `100644` 則是 git 屬性，有點類似 Linux 環境下的檔案屬性，例如宣告這是個檔案、目錄、可讀、可寫、可執行之類的。以下是幾個常見的 git 屬性範例：
	
	0100000000000000 (040000): Directory
	1000000110100100 (100644): Regular non-executable file
	1000000110110100 (100664): Regular non-executable group-writeable file
	1000000111101101 (100755): Regular executable file
	1010000000000000 (120000): Symbolic link
	1110000000000000 (160000): Gitlink

相關連結可參考以下討論串：

* [How to read the mode field of git-ls-tree's output](http://stackoverflow.com/questions/737673/how-to-read-the-mode-field-of-git-ls-trees-output)
* [index-format.txt](https://github.com/gitster/git/blob/master/Documentation/technical/index-format.txt)

接下來第三行的 `--- a/a.txt` 則代表兩個比對的版本中「比較舊的」那個版本。

接下來第四行的 `+++ b/a.txt` 則代表兩個比對的版本中「比較新的」那個版本。

接下來第五行的 `@@ -1 +1 @@` 則代表這個檔案在舊版的總行數與新版的總行數，-1 代表舊版只有 1 行，+1 代表新版也只有 1 行。

最後則是列出所有變更的內容，這裡有三種可能的表示法：

* 以減號 - 號開頭，代表從舊版到新版的過程中，此行被刪除了。
* 以加號 + 號開頭，代表從舊版到新版的過程中，此行是被新增上去的。
* 以空白字元開頭，則代表這一行在兩個版本中都有出現，沒有任何變更。

如此一來就完成了這兩個版本中第一個 blob 物件的差異比對，接著會顯示該版本中第二個 blob 物件的差異比對，以此類推。

在 Git 中使用 `git diff` 的時候，事實上是以 tree 物件為比較的單位，我們從【第 06 天：解析 Git 資料結構 - 物件結構】文章圖解與影片中有學到，其實每一個 commit 物件都會包括一個根目錄的 tree 物件。所以我們剛剛利用 `git diff` 比對兩個 commit 物件時，其實比對的是 commit 物件下的那個 tree 物件，而比對的過程又會遞迴的一直比下去。由此你應該可以感受到，Git 的 diff 比對機制十分強大，你可以很快速的比對出任意兩個版本之間的異動比較。

在使用 `git diff` 命令時，主要有三種 tree 物件的來源，分別是：

* 在所有的 commit graph 中存在的 tree object，也就是任意版本中任意一個 tree 物件的意思。
* 索引 (index)，代表你已經將檔案狀態送進「索引資料庫」的那些資訊，此時透過 `git add` 命令時，其實 tree 物件已經被建立。
* 你目前的工作目錄 (working directory)，雖然工作目錄的改變還沒有變成 tree 物件，但透過 `git diff` 是可以這樣用的。

四種基本的比較方式
-----------------

要透過 `git diff` 命令比對任意兩個版本，通常會有以下四種指令的用法：

1. git diff

	在什麼參數都不加的使用情況，比對的是「工作目錄」與「索引」之間的差異。這是個很常用的指令，因為當你執行 `git add .` 指令之前，先透過 `git diff` 查看你自己到底改了哪些東西。

	**註**：事實上，在使用 Git 版本控管的過程中，在執行 `git commit` 之前，的確有可能會執行 `git add` 指令好幾次，用以確認到底哪些檔案要加入到索引之中，最後才會 commit 進版本。

2. git diff commit

	如果你只在 `git diff` 之後加上一個 commit id，比對的是「工作目錄」與「指定 commit 物件裡的那個 tree 物件」。

	最常用的指令是 `git diff HEAD`，因為這代表你要拿「工作目錄」與「當前分支的最新版」進行比對。這種比對方法，不會去比對「索引」的狀態，所以各位必須區分清楚，你到底比對的是甚麼 tree 物件的來源。

3. git diff --cached commit

	在執行 `git commit` 之前，索引狀態應該已經都準備好了。所以如果你要比對「當前的索引狀態」與「指定 commit 物件裡的那個 tree 物件」，就可以用這個指令完成比對任務。

	最常用的指令一樣是 `git diff --cached HEAD`，這個語法代表的是「當前的索引狀態」與「當前分支的最新版」進行比對。這種比對方法，不會去比對「工作目錄」的檔案內容，而是直接去比對「索引」與「目前最新版」之間的差異，這有助於你在執行 `git commit` 之前找出那些變更的內容，也就是你將會有哪些變更被建立版本的意思。            

	**註1**: `git diff --cached` 與 `git diff --staged` 是完全一樣的結果，`--staged` 只是 `--cached` 的別名，讓你比較好記而已!

	**註2**: `git diff --cached` 與 `git diff --cached HEAD` 執行時也是完全一樣的結果，最後的 HEAD 可以省略。

4. git diff commit1 commit2

	最後一種則是透過兩個不同的版本 ( commit id ) 來比對其差異，這個命令可以跳過「索引」與「工作目錄」的任何變更，而是直接比對特定兩個版本。事實上 Git 是比對特定兩個版本 commit 物件內的那個 tree 物件。

	最常用的指令則是 `git diff HEAD^ HEAD` 命令，這代表你要比較【最新版的前一版】與【最新版】之間的差異。這裡的 HEAD 與 ^ 的意義，我們會在日後的文章中說明。


今日小結
-------

今天介紹的 `git diff` 是個很常用的指令，各位應該熟練地使用它。我們最後來複習一下其常用指令的差異：

    git diff                 => 工作目錄 vs 索引
    git diff HEAD            => 工作目錄 vs HEAD
	git diff --cached HEAD   => 索引     vs HEAD
    git diff --cached        => 索引     vs HEAD
	git diff HEAD^ HEAD	     => HEAD^   vs HEAD



我重新整理一下本日學到的 Git 指令與參數：

* git log
* git diff 
* git diff HEAD
* git diff --cached
* git diff --staged
* git diff HEAD^ HEAD

參考連結
-------

* [BASIC SNAPSHOTTING](http://gitref.org/basic/#diff)
* [git-diff(1) Manual Page](https://www.kernel.org/pub/software/scm/git/docs/git-diff.html)


第 10 天：認識 Git 物件的絕對名稱
=================================================

在 Git 版本控管的過程，每一個版本就代表一個 commit 物件。又因為版控過程中經常會建立分支，最終產出的 commit graph 可能會蠻複雜的，所以如何識別不同的版本，或是快速定位到特定版本已取得資訊，就變得很重要。本篇文章將帶大家認識 Git 裡常用的物件名稱概念與使用方法。

物件絕對名稱
------------

在 Git 中，每個物件都會有一個以 SHA 雜湊運算過的 id，而這個 id 就是所謂的「絕對名稱」。如果該物件是 commit 物件，那這就是 commit 物件的絕對名稱，所以我們只要找出 commit 物件的絕對名稱，就可以隨時取得該版本。如下圖箭頭標示處，就是我們透過 `git log` 取得的 commit 物件 id，我們隨時可以取得該 commit 物件的詳細資訊。

![image](https://f.cloud.github.com/assets/88981/1296206/6aaaef14-30c2-11e3-98bd-e4b096040ea8.png)

如果我們想看如上圖 commit 物件的內容，可以利用 `git cat-file -p commitid` 來取得，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1296247/76dbcd2a-30c3-11e3-8214-41992ef57325.png)

物件絕對名稱的簡短語法
---------------------

由於 Git 物件 id 是透過內容進行 SHA1 雜湊後的結果，所以很長，在 Git 標示「絕對名稱」時，可以用前面幾碼代替，最少不可低於 4 個字元。也就是說 4 ~ 40 個字元長度的「絕對名稱」都是可以用的。

例如我們從上圖也可以看出在這個 commit 物件的的內容包含了一個 tree 物件，該物件也有一個 tree 物件的絕對名稱 `07c1321be49815d53eb2413f0ad5286010ebb6cc`，所以我也可以再次透過 `git cat-file -p treeid` 來取得該 tree 物件的內容，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1296406/1bfed9ac-30c7-11e3-9ce4-937fb6ae45a2.png)

有時候我們想取得版本紀錄會使用 `git log` 命令，同時也會輸出每個檔案的變更比較結果，結果會十分冗長，這時可以用 `git log --pretty=oneline` 指令還取得較為精簡的歷史紀錄，同時你也可以取得 commit 物件完整的「絕對名稱」，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1296446/ddb3e27c-30c7-11e3-811b-fbb41c1aa5d3.png)

另外一個常用的技巧則是僅輸出部分的「絕對名稱」，透過 `git log --pretty=oneline --abbrev-commit` 指令執行即可，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1296456/0edb6a3c-30c8-11e3-9f5b-157fbde29ad7.png)


今日小結
-------

以上這就是絕對名稱的用法，由於 Git 物件的特性，你可以透過物件的絕對名稱存取到 Git 儲存庫中任意物件，還有很多 git 指令都會用到絕對名稱，熟悉了這些概念與表示法，你將更能掌握 Git 物件。

我重新整理一下本日學到的 Git 指令與參數：

* git log
* git cat-file -p [object_id]
* git log --pretty=oneline
* git log --pretty=oneline --abbrev-commit



第 11 天：認識 Git 物件的一般參照與符號參照
==========================================================

在認識了 Git 物件的「絕對名稱」後，接下來就要介紹 Git 版控過程中最常用到的「參照名稱」。

認識物件的參照名稱
------------------

參照名稱 (ref) 簡單來說就是 Git 物件的一個「指標」，或是相對於「絕對名稱」的另一個「好記名稱」，用一個預先定義或你自行定義的名稱來代表某一個 Git 物件。

在我們之前學到的｢分支名稱｣或我們曾經用過的 HEAD (代表最新版本)，或是我們之後會學到的「標籤名稱」，這些都是「參照名稱」，總之就是為了讓你好記而已。

我們以｢分支名稱｣為例，來說明一下「參照名稱」的實體結構為何。以下圖為例，我們透過 `git branch` 取得所有分支名稱，你可以看到我們目前有三個分支，然而這三個分支的名稱其實就是一個｢參照名稱｣，這代表這三個「參照名稱」分別對應到 Git 物件儲存庫中的三個 commit 物件。在下圖中你也可以看出這些分支的參照名稱其實就是一個檔案而已，所有「本地分支」的參照名稱皆位於 `.git\refs\heads` 目錄下：

![image](https://f.cloud.github.com/assets/88981/1297740/507280f0-30e8-11e3-80dd-1a7794265d27.png)

接著我再以下圖來證明這個檔案是如何跟「絕對名稱」做連結。我先透過 `git branch` 取得所有分支名稱，並發現目前「工作目錄」是指向 `newbranch1` 這個分支。此時我們透過 `git log --pretty=oneline` 即可取得該分支的所有版本紀錄。預設這些分支的「參照名稱」會指向分支的「最新版」，我們只要打開 `.git\refs\heads\newbranch1` 檔案的內容，就可以看出這是一個純文字檔而已，而且是指向版本歷史紀錄中的「最新版」。最後再以 `git cat-file -p 0bd0` 取得該 commit 物件的內容，以及用 `git show 0bd0` 取得該版本的變更紀錄，藉此證明這些檔案就是「參照名稱」的主要用途。

![image](https://f.cloud.github.com/assets/88981/1297769/f42c33d0-30e8-11e3-9b7f-cccc6a6dcde3.png)

我們再透過指令看看使用「絕對名稱」與「參照名稱」讀取特定 commit 物件的內容，證明這兩個指令執行的結果是相同的：

![image](https://f.cloud.github.com/assets/88981/1298039/b83adaca-30ed-11e3-893e-ef63a0b5b166.png)

在大多數的情況下，「參照名稱」通常都會指向一個 commit 物件，但並非必要，你也可以指向其他 Git 物件類型，像是 blob 物件、tree 物件、tag 物件等等。

關於 .git/refs/ 目錄
---------------------

從上述範例其實已經能看出，所有的「參照名稱」都是個檔案，而且一律放在 `git/refs/` 目錄下。而 Git 的參照名稱所放置的目錄位置，主要有三個：

* 本地分支：`.git/refs/heads/`
* 遠端分支：`.git/refs/remotes/`
* 標　　籤：`.git/refs/tags/`

再舉個簡單例子，如果你建立一個分支名稱為 `f2e`，這時你會知道本地分支的「參照名稱」會建立 `.git/refs/heads/f2e` 檔案，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1300419/c7bc822c-3111-11e3-84db-e2481a4c8d74.png)

事實上，這個 `f2e` 的「全名」應該叫做 `refs/heads/f2e` 才對，只是 Git 允許你輸入簡寫，方便你快速輸入參照名稱而已。如下圖示，這三種使用「參照名稱」的方式都是可行的：

![image](https://f.cloud.github.com/assets/88981/1300497/c25184bc-3112-11e3-810f-abd45a209cbd.png)

不過當你輸入參照名稱的「簡稱」時，預設 Git 會依照以下順序搜尋適當的參照名稱，只要找到對應的檔案，就會立刻回傳該檔案內容的「物件絕對名稱」：

* `.git/<參照簡稱>`
* `.git/refs/<參照簡稱>`
* `.git/refs/tags/<參照簡稱;標籤名稱>`
* `.git/refs/heads/<參照簡稱;本地分支名稱>`
* `.git/refs/remotes/<參照簡稱>`
* `.git/refs/remotes/<參照簡稱;遠端分支名稱>/HEAD`

例如，當你輸入 `git cat-file -p f2e` 指令的話，那麼 Git 就會用以下順序找到相對的「參照名稱檔」，取出該檔案的內容 (即 Git 物件的絕對名稱)：

* `.git/f2e` --> 找不到此檔案
* `.git/refs/f2e` --> 找不到此檔案
* `.git/refs/tags/f2e` --> 找不到此檔案
* `.git/refs/heads/f2e` --> **找到了參照名稱，以下就不繼續搜尋**
* `.git/refs/remotes/f2e`
* `.git/refs/remotes/f2e/HEAD`


認識物件的符號參照名稱 (symref)
-----------------------------

符號參照名稱 (symref) 其實也是參照名稱 (ref) 的一種，只是內容不同而已。我們從下圖應可看出其內容的差異，「符號參照」會指向另一個「參照名稱」，並且內容以 `ref:` 開頭：

![image](https://f.cloud.github.com/assets/88981/1300631/112713e8-3115-11e3-904b-298f2da3d34b.png)

在 Git 工具中，預設會維護一些特別的符號參照，方便我們快速取得常用的 commit 物件，且這些物件預設都會儲存在 `.git/` 目錄下。這些符號參考有以下四個：

* HEAD
	* 永遠會指向「工作目錄」中所設定的「分支」當中的「最新版」。
	* 所以當你在這個分支執行 `git commit` 後，這個 `HEAD` 符號參照也會更新成該分支最新版的那個 commit 物件。
* ORIG_HEAD
	* 簡單來說就是 HEAD 這個 commit 物件的「前一版」，經常用來復原上一次的版本變更。
* FETCH_HEAD
	* 使用遠端儲存庫時，可能會使用 `git fetch` 指令取回所有遠端儲存庫的物件。這個 FETCH_HEAD 符號參考則會記錄遠端儲存庫中每個分支的 HEAD (最新版) 的「絕對名稱」。
* MERGE_HEAD
	* 當你執行合併工作時 (關於合併的議題會在日後的文章中會提到)，「合併來源｣的 commit 物件絕對名稱會被記錄在 MERGE_HEAD 這個符號參照中。


一般參照與符號參照的使用方式
---------------------------

我們知道「參照名稱」有特殊的目的，通常用於「本地分支」、「遠端分支」與「標籤」等情境下，但事實上你可以建立任意數量的「自訂參照名稱」，只要透過 `git update-ref` 就可以自由建立「一般參照」。

我企圖建立一個名為 `InitialCommit` 的一般參照，並指向 Git 儲存庫中的第一個版本，請參見如下圖的指令執行順序，得知一般參照的建立方式：

![image](https://f.cloud.github.com/assets/88981/1303340/08900c84-3152-11e3-8681-c902ea5368f7.png)

建立完成後，預設檔案會放在 `.git` 資料夾下，且此時用「絕對名稱」與「參照名稱」都能存取特定 Git 物件的內容：

![image](https://f.cloud.github.com/assets/88981/1303357/86423b5c-3152-11e3-869b-cb8d468ad614.png)

**註**：請記得，參照名稱可以指向任意 Git 物件，並沒有限定非要 commit 物件不可。

若要建立較為正式的參照名稱，最好加上 `refs/` 開頭，例如：`git update-ref refs\InitialCommit [object_id]`。

若要刪除一般參照，則可以使用 `-d` 選項。如下圖示：

![image](https://f.cloud.github.com/assets/88981/1303372/0dc4e0ca-3153-11e3-80da-090c4c8ddfc3.png)

顯示所有參照的方式，則可以使用 `git show-ref` 指令，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1303388/34e8a528-3154-11e3-9002-54d7fcf484bb.png)

若要建立與刪除「符號參照」，可以參考如下圖 `git symbolic-ref` 的用法。請自行看圖說故事，理解之後，你真的會發現 Git 對於參照的用法非常靈活且強大。還有，執行 `git show-ref` 只會顯示在 `.git\refs` 目錄下的那些參照，而且不管是「一般參照」或「符號參照」都一樣：

![image](https://f.cloud.github.com/assets/88981/1303416/85c3d82c-3155-11e3-95b1-9aa7c1063a32.png)

本文稍早提到你可以建立參照到以下目錄：

* `.git/<參照簡稱>`
* `.git/refs/<參照簡稱>`
* `.git/refs/tags/<參照簡稱;標籤名稱>`
* `.git/refs/heads/<參照簡稱;本地分支名稱>`
* `.git/refs/remotes/<參照簡稱>`
* `.git/refs/remotes/<參照簡稱;遠端分支名稱>/HEAD`

自訂參照通常會自行建立在前兩個路徑下，以免分不清跟我們使用「本地分支」、「遠端分支」與「標籤」的使用方式。不過，你的確可以利用 `git update-ref` 建立任何自訂參照，若把自訂參照建立在 `refs/heads/Will` 的話，也等同於建立了一個名為 `Will` 的分支，而 Git 真的就是這麼單純，當你越來越了解 Git 的內部結構，也會更加喜歡上 Git 的各種特性。

今日小結
-------

我們知道「參照名稱 (ref)」 簡單來說就是 Git 物件的一個「指標」，用來指向特定 Git 物件，所以你可以把「參照名稱」想像成 Git 物件絕對名稱的別名 (Alias)，用來幫助記憶。在 Git 裡，有許多機制可以幫你控管專案，例如「分支」、「標籤」等等，這些機制骨子裡其實就是靠「參照」完成的。

Git 參照名稱又有區分「一般參照」與「符號參照」，兩者的用途一模一樣，只在於內容不太一樣。「符號參照」會指向另一個「一般參照」，而「一般參照」則是指向一個 Git 物件的「絕對名稱」。

我重新整理一下本日學到的 Git 指令與參數：

* git branch
* git log --pretty=oneline
* git log --oneline
* git cat-file -p [ref or object_id]
* git show [ref or object_id]
* git update-ref
* git symbolic-ref
* git show-ref



第 12 天：認識 Git 物件的相對名稱
=================================================

在認識了 Git 物件的「絕對名稱」與「參照名稱」後，最後我們來介紹 Git 版控過程中也很常用到的「相對名稱」。

我們在複習一次，在 Git 版本控管的過程，每一個版本就代表一個 commit 物件，每個 commit 物件會有一個「絕對名稱」，該名稱是將內容以 SHA1 雜湊運算後的一個 40 字元的字串，你可以用前 4 ~ 40 個字元來當成該 commit 物件的識別名稱。版控的過程中，也可以讓你透過「參照名稱」來代表某個 commit 物件，每個「參照名稱」最終會對應到一個物件的「絕對名稱」。而「參照名稱」又區分「一般參照」與「符號參照」，其中「一般參照」直接對應到｢絕對名稱｣，而「符號參照」則是對應到另一個「一般參照」。

這篇文章所要介紹的則是透過「相對名稱」的表示法，讓你找到特定 commit 物件後，用相對的位置來找到其他的「commit 物件」。

相對名稱的表示法
----------------

使用相對名稱其實非常簡單，這裡有兩個特殊符號你必須記得，一個是 `^` 另一個是 `~` 符號。

如果要找到 `HEAD` 的前一版本，我們會使用 `HEAD~` 或 `HEAD~1` 來表示「HEAD 這個 commit 物件的前一版」。**註**：這裡你應該已經很清楚 `HEAD` 是一個 Git 內建的「符號參照名稱」，代表目前分支的最新版。

如果你要找出另一個 `f2e` 分支的前兩個版本 (不含 `f2e` 的 `HEAD` 版本)，你則可以用 `f2e~2` 或用 `f2e~~` 來表示，這就是最基本的表示方法。

在沒有分支與合併的儲存庫中，關於 `^1` 與 `~1` 所表達的意思是完全相同的，都代表「前一版」。但事實上在有分支與合併的儲存庫中，他們有不同的意義，這部分容後在述。

這就是最基本的「相對名稱」表示法。


關於 commit 物件彼此間的連結
---------------------------

比較常見的 Git 儲存庫，預設只會有一個「根 commit 物件」，也就是我們最一開始建立的那個版本，又稱「初始送交」(Initial Commit)。你也至少要有第一個 commit 物件後才能開始分支，所以我們可以說：「在一個 Git 儲存庫中，所有的 commit 物件中，除了第一個 commit 物件外，任何其他的 commit 物件一定都會有一個以上的上層 commit 物件(parent commit)」。為什麼有可能有「一個以上」的上層 commit 物件呢？因為你很有可能會合併兩個以上的分支到另一個分支裡，所以合併完成後的那個 commit 物件就會有多個 parent commit 物件。

我們用個簡單的例子來證明這點，我們用 `git cat-file -p [object_id]` 來取得最前面兩筆 commit 物件的內容，藉此了解到每個 commit 物件確實一定會有 parent 屬性，並指向上層 commit 物件的絕對名稱，唯獨第一筆 commit 物件不會有 parent 屬性。如下圖示：

![image](https://f.cloud.github.com/assets/88981/1304846/2b76c408-318a-11e3-9ac5-d6d012041d07.png)

了解相對名稱表示法 `^` 與 `~` 的差異
------------------------------------

關於 `~` 的意義，代表「第一個上層 commit 物件」的意思。

關於 `^` 代表的意思則是「擁有多個上層 commit 物件時，要代表第幾個第一代的上層物件」。

如果你有一個「參照名稱」為 `C`，若要找到它的第一個上層 commit 物件，你可以有以下表達方式：

* C^
* C^1
* C~
* C~1

如果你要找到它的第二個上層 commit 物件 (在沒有合併的狀況下)，你可以有以下表達方式：

* C^^
* C^1^1
* C~2
* C~~
* C~1~1

但你不能用 `C^2` 來表達「第二個上層 commit 物件」！原因是在沒有合併的情況下，這個 `C` 只有一個上層物件而已，你如果用 `C^2` 代表｢上一層物件的第二個上層物件」。

上述講起來有點抽象又有點繞口，我特別畫了一張圖給各位看一下，透過圖解可能會比較明白些。如下圖示，我們想找到 `C` 這個 commit 物件的相對路徑下的其他 commit 物件(上層物件)，由於 `C` 這個 commit 物件有三個上層物件，這代表這個 commit 物件是透過合併而被建立的，那麼你要透過「相對名稱」找到每一個路徑，就必須搭配組合 `^` 與 `~` 的使用技巧，才能定位到每個你想開啟的版本。

![image](https://f.cloud.github.com/assets/88981/1305052/b7336614-318e-11e3-8b45-78285b0d01ce.png)


介紹 `git rev-parse` 指令
--------------------------

在 Git for Windows 工具裡有個 `git rev-parse` 指令，透過這個指令可以把任意「參考名稱」或「相對名稱」解析出「絕對名稱」，雖然這工具不是很常會用到，但做 Git 教學的時候還蠻實用的。用法如下範例：

* git rev-parse master
* git rev-parse HEAD
* git rev-parse ORIG_HEAD
* git rev-parse HEAD^
* git rev-parse HEAD~5


今日小結
-------

當瞭解了「相對名稱」後，在 Git 中表示 commit 物件的各種方式已經講解完畢，相信你應該更能掌握 Git 各版本之間的操作。

我重新整理一下本日學到的 Git 指令與參數：

* git log
* git cat-file -p [object_id]
* * git rev-parse



第 13 天：暫存工作目錄與索引的變更狀態
========================================================

有沒有遇過這種情境，某個系統開發寫到一半，結果被老闆或客戶「插單」，被要求緊急修正一個現有系統的 Bug 或添加一個功能，眼前的程式即將完成，老闆的「急件」又不能拖，一個未完成的軟體開發狀態外加緊急調整的需求，這簡直是軟體品質的一大考驗。如果你有這種困擾，那麼 Git 可以漂亮的幫你完成任務。

認識 git stash 指令
--------------------

我們知道使用 Git 版控的時候，有區分「工作目錄」與「索引」。工作目錄裡面會有你改到一半還沒改完的檔案(尚未加入索引)，也有新增檔案但還沒加入的檔案(尚未加入索引)。而放在索引的資料，則是你打算透過 `git commit` 建立版本 (建立 commit 物件) 的內容。

當你功能開發到一半，被緊急插單一定手忙腳亂，尤其是手邊正改寫到一半的那些程式碼不知該如何是好。在 Git 裡有個 `git stash` 指令，可以自動幫你把改寫到一半的那些檔案建立一個「特殊的版本」(也是一個 commit 物件)，我們稱這些版本為 stash 版本，或你可以直接稱他為「暫存版」。

建立暫存版本
------------

我們手邊改到一半的檔案，可能會有以下狀態：

* 新增檔案 (尚未列入追蹤的檔案) (untracked files)
* 新增檔案 (已經加入索引的檔案) (tracked/staged files)
* 修改檔案 (尚未加入索引的檔案) (tracked/unstaged files)
* 修改檔案 (已經加入索引的檔案) (tracked/staged files)
* 刪除檔案 (尚未加入索引的檔案) (tracked/unstaged files)
* 刪除檔案 (已經加入索引的檔案) (tracked/staged files)

若要將這些開發到一半的檔案建立一個「暫存版」，你有兩個選擇：

* `git stash` 會將所有已列入追蹤(tracked)的檔案建立暫存版
* `git stash -u`　會包括所有已追蹤或未追蹤的檔案，全部都建立成暫存版

**註**: `git stash` 也可以寫成 `git stash save`，兩個指令的結果是一樣的，只是 `save` 參數可以忽略不打而已。

我們來看看一個簡單的例子。我們先透過以下指令快速建立一個擁有兩個版本的 Git 儲存庫與工作目錄：

	mkdir git-stash-demo
	cd git-stash-demo
	git init
	
	echo. > a.txt
	git add .
	git commit -m "Initial commit"
	
	echo 1 > a.txt
	git add .
	git commit -m "a.txt: set 1 as content"

目前的「工作目錄」是乾淨的，沒有任何更新到一半的檔案：
	
	C:\git-stash-demo>git log
	commit 95eff6b19a9494667985ed5da37427bb08b8cdd7
	Author: Will <doggy.huang@gmail.com>
	Date:   Fri Oct 11 08:17:15 2013 +0800
	
	    a.txt: set 1 as content
	
	commit 346fadefdd6ed2c562201b5ca37d1e4d26b26d54
	Author: Will <doggy.huang@gmail.com>
	Date:   Fri Oct 11 08:17:14 2013 +0800
	
	    Initial commit
	
	C:\git-stash-demo>git status
	# On branch master
	nothing to commit, working directory clean

	C:\git-stash-demo>dir
	 磁碟區 C 中的磁碟是 System
	 磁碟區序號:  361C-6BD6
	
	 C:\git-stash-demo 的目錄
	
	2013/10/11  上午 08:17    <DIR>          .
	2013/10/11  上午 08:17    <DIR>          ..
	2013/10/11  上午 08:17                 4 a.txt
	               1 個檔案               4 位元組
	               2 個目錄   9,800,470,528 位元組可用

接著我新增一個 b.txt，再將 a.txt 的內容改成 2，如下：

	C:\git-stash-demo>type a.txt
	1
	
	C:\git-stash-demo>echo 2 > a.txt
	
	C:\git-stash-demo>type a.txt
	2
	
	C:\git-stash-demo>echo TEST > b.txt
	
	C:\git-stash-demo>dir
	 磁碟區 C 中的磁碟是 System
	 磁碟區序號:  361C-6BD6
	
	 C:\git-stash-demo 的目錄
	
	2013/10/11  上午 08:55    <DIR>          .
	2013/10/11  上午 08:55    <DIR>          ..
	2013/10/11  上午 08:54                 4 a.txt
	2013/10/11  上午 08:55                 7 b.txt
	               2 個檔案              11 位元組
	               2 個目錄   9,704,288,256 位元組可用
	
	C:\git-stash-demo>git status
	# On branch master
	# Changes not staged for commit:
	#   (use "git add <file>..." to update what will be committed)
	#   (use "git checkout -- <file>..." to discard changes in working directory)
	#
	#       modified:   a.txt
	#
	# Untracked files:
	#   (use "git add <file>..." to include in what will be committed)
	#
	#       b.txt
	no changes added to commit (use "git add" and/or "git commit -a")

現在我們用 `git status` 得出我們有兩個檔案有變更，一個是 a.txt 處於 "not staged" 狀態，而 b.txt 則是 "untracked" 狀態。

這時，我們利用 `git stash -u` 即可將目前這些變更全部儲存起來 (包含 untracked 檔案)，儲存完畢後，這些變更全部都會被重置，新增的檔案會被刪除、修改的檔案會被還原、刪除的檔案會被加回去，讓我們目前在工作目錄中所做的變更全部回復到 HEAD 狀態。這就是 Stash 幫我們做的事。如下所示：

	C:\git-stash-demo>git stash -u
	Saved working directory and index state WIP on master: 95eff6b a.txt: set 1 as c
	ontent
	HEAD is now at 95eff6b a.txt: set 1 as content
	
	C:\git-stash-demo>git status
	# On branch master
	nothing to commit, working directory clean

在建立完成｢暫存版｣之後，Git 會順便幫我們建立一個暫存版的「參考名稱」，而且是「一般參考」，在 `.git\refs\stash` 儲存的是一個 commit 物件的「絕對名稱」：

	C:\git-stash-demo>dir .git\refs\
	 磁碟區 C 中的磁碟是 System
	 磁碟區序號:  361C-6BD6
	
	 C:\git-stash-demo\.git\refs 的目錄
	
	2013/10/11  上午 08:57    <DIR>          .
	2013/10/11  上午 08:57    <DIR>          ..
	2013/10/11  上午 08:57    <DIR>          heads
	2013/10/11  上午 08:57                41 stash
	2013/10/11  上午 08:17    <DIR>          tags
	               1 個檔案              41 位元組
	               4 個目錄   9,701,650,432 位元組可用

我們用 `git cat-file -p stash` 即可查出該物件的內容，這時你就可以發現這其實就是一個有三個 parent (上層 commit 物件) 的 commit 物件：

	C:\git-stash-demo>git cat-file -p stash
	tree 86cf41ab650d8d0ce5fdd003bb7b722a917438a2
	parent 95eff6b19a9494667985ed5da37427bb08b8cdd7
	parent b79c4650e72ad4627d691a2d6cfb192626e24e94
	parent 9b4e4a100776783dc76d16c3872235e6314d15e3
	author Will <doggy.huang@gmail.com> 1381453062 +0800
	committer Will <doggy.huang@gmail.com> 1381453062 +0800
	
	WIP on master: 95eff6b a.txt: set 1 as content

有三個 parent commit 物件的意義就在於，這個特殊的暫存版是從另外三個版本合併進來的，然而這三個版本的內容，我們一樣可以透過相同的指令顯示其內容：

	C:\git-stash-demo>git cat-file -p 95ef
	tree eba2ef4205738a5015fc47d9cfe634d7d5eae466
	parent 346fadefdd6ed2c562201b5ca37d1e4d26b26d54
	author Will <doggy.huang@gmail.com> 1381450635 +0800
	committer Will <doggy.huang@gmail.com> 1381450635 +0800
	
	a.txt: set 1 as content
	
	C:\git-stash-demo>git cat-file -p b79c
	tree eba2ef4205738a5015fc47d9cfe634d7d5eae466
	parent 95eff6b19a9494667985ed5da37427bb08b8cdd7
	author Will <doggy.huang@gmail.com> 1381453061 +0800
	committer Will <doggy.huang@gmail.com> 1381453061 +0800
	
	index on master: 95eff6b a.txt: set 1 as content
	
	C:\git-stash-demo>git cat-file -p 9b4e
	tree b583bfe854b66756dd0f8ee96cab0c898193b5fd
	author Will <doggy.huang@gmail.com> 1381453062 +0800
	committer Will <doggy.huang@gmail.com> 1381453062 +0800
	
	untracked files on master: 95eff6b a.txt: set 1 as content

從上述執行結果你應該可以從「訊息紀錄」的地方清楚看出這三個版本分別代表那些內容：

1. 原本工作目錄的 HEAD 版本
2. 原本工作目錄所包含的索引內容
3. 原本工作目錄裡所有未追蹤的內容

也就是說，他把「原本工作目錄的 HEAD 版本」先建立兩個暫時的分支，這兩個分支分別就是「原本工作目錄所包含的索引內容」與「原本工作目錄裡所有未追蹤的內容」之用，並在個別分支建立了一個版本以產生 commit 物件並且給予預設的 log 內容。最後把這三個分支，合併到一個「參照名稱」為 `stash` 的版本　（這也是個 commit 物件)。還不僅如此，他還把整個「工作目錄」強迫重置為 HEAD 版本，把這些變更與新增的檔案都給還原，多的檔案也會被移除。

取回暫存版本
------------
由於「工作目錄」已經被重置，所以變更都儲存到 `stash` 這裡，哪天如果你想要把這個暫存檔案取回，就可以透過 `git stash pop` 重新「合併」回來。如下所示：

	C:\git-stash-demo>git status
	# On branch master
	nothing to commit, working directory clean
	
	C:\git-stash-demo>git stash pop
	# On branch master
	# Changes not staged for commit:
	#   (use "git add <file>..." to update what will be committed)
	#   (use "git checkout -- <file>..." to discard changes in working directory)
	#
	#       modified:   a.txt
	#
	# Untracked files:
	#   (use "git add <file>..." to include in what will be committed)
	#
	#       b.txt
	no changes added to commit (use "git add" and/or "git commit -a")
	Dropped refs/stash@{0} (0e5b72c96fcf693e0402c40cd58f980bb3ff7efd)

執行完畢後，所有當初的工作目錄狀態與索引狀態都會被還原。事實上 Git 骨子裡是透過「合併」的功能把這個名為 `stash` 的版本給合併回目前分支而已。最後，它還會自動將這個 `stash` 分支給刪除，所以稱它為【暫存版】非常貼切！

建立多重暫存版
--------------

Git 的 stash 暫存版可以不只一份，你也可以建立多份暫存檔，以供後續使用。不過，在正常的開發情境下，通常不會有太多暫存版才對，會有這種情況發生，主要有兩種可能：

1. 你的開發習慣太差，導致累積一堆可能用不到的暫存版。
2. 你老闆或客戶「插單」的問題十分嚴重，經常改到一版就被迫插單。(這就是身為 IT 人的 BI 啊~~~XD) (BI = Business Intelligence 或另一層意思... Well, you know....) 

我們延續上一個例子，目前工作目錄的狀態應該是有兩個檔案有變化，我們用 `git status -s` 取得工作目錄的狀態(其中 `-s` 代表顯示精簡版的狀態)：

	C:\git-stash-demo>git status -s
	 M a.txt
	?? b.txt

現在，我們先建立第一個 stash 暫存版：

	C:\git-stash-demo>git stash save -u
	Saved working directory and index state WIP on master: 95eff6b a.txt: set 1 as content
	HEAD is now at 95eff6b a.txt: set 1 as content

然後透過 `git stash list` 列出目前所有的 stash 清單，目前僅一份暫存版：

	C:\git-stash-demo>git stash list
	stash@{0}: WIP on master: 95eff6b a.txt: set 1 as content

而且你可以看到建立暫存版之後，工作目錄是乾淨的。此時我們在建立另一個 `new.txt` 檔案，並且再次建立暫存版：
	
	C:\git-stash-demo>git status -s
	
	C:\git-stash-demo>echo 1 > new.txt
	
	C:\git-stash-demo>git status -s
	?? new.txt
	
	C:\git-stash-demo>git stash save -u
	Saved working directory and index state WIP on master: 95eff6b a.txt: set 1 as c
	ontent
	HEAD is now at 95eff6b a.txt: set 1 as content

我們在再一次 `git stash list` 就可以看到目前有兩個版本：

	C:\git-stash-demo>git stash list
	stash@{0}: WIP on master: 95eff6b a.txt: set 1 as content
	stash@{1}: WIP on master: 95eff6b a.txt: set 1 as content

你應該會很納悶，都沒有自訂的註解，過了幾天不就忘記這兩個暫存檔各自的修改項目嗎？沒錯，所以你可以自訂「暫存版」的紀錄訊息。我們透過 `git stash save -u <message>` 指令，就可自訂暫存版的註解：

	C:\git-stash-demo>git stash -h
	usage: git core\git-stash list [<options>]
	   or: git core\git-stash show [<stash>]
	   or: git core\git-stash drop [-q|--quiet] [<stash>]
	   or: git core\git-stash ( pop | apply ) [--index] [-q|--quiet] [<stash>]
	   or: git core\git-stash branch <branchname> [<stash>]
	   or: git core\git-stash [save [--patch] [-k|--[no-]keep-index] [-q|--quiet]
	                       [-u|--include-untracked] [-a|--all] [<message>]]
	   or: git core\git-stash clear
	
	C:\git-stash-demo>git stash pop
	Already up-to-date!
	# On branch master
	# Untracked files:
	#   (use "git add <file>..." to include in what will be committed)
	#
	#       new.txt
	nothing added to commit but untracked files present (use "git add" to track)
	Dropped refs/stash@{0} (5800f37937aea5fb6a1aba0d5a1598a940e70c96)
	
	C:\git-stash-demo>git stash save -u "新增 new.txt 檔案"
	Saved working directory and index state On master: 新增 new.txt 檔案
	HEAD is now at 95eff6b a.txt: set 1 as content
	
	C:\git-stash-demo>git stash list
	stash@{0}: On master: 新增 new.txt 檔案
	stash@{1}: WIP on master: 95eff6b a.txt: set 1 as content

這時，如果你直接執行 `git stash pop` 的話，他會取回最近的一筆暫存版，也就是上述例子的 `stash@{0}` 這一項，並且把這一筆刪除。另一種取回暫存版的方法是透過 `git stash apply` 指令，唯一差別則是取回該版本 (其實是執行合併動作) 後，該暫存版還會留在 stash 清單上。

如果你想取回「特定一個暫存版」，你就必須在最後指名 stash id，例如 `stash@{1}` 這樣的格式。例如如下範例，我使用 `git stash apply "stash@{1}"` 取回前一個暫存版，但保留這版在 stash 清單裡：
	
	C:\git-stash-demo>git stash list
	stash@{0}: On master: 新增 new.txt 檔案
	stash@{1}: WIP on master: 95eff6b a.txt: set 1 as content
	
	C:\git-stash-demo>git stash apply "stash@{1}"
	# On branch master
	# Changes not staged for commit:
	#   (use "git add <file>..." to update what will be committed)
	#   (use "git checkout -- <file>..." to discard changes in working directory)
	#
	#       modified:   a.txt
	#
	# Untracked files:
	#   (use "git add <file>..." to include in what will be committed)
	#
	#       b.txt
	no changes added to commit (use "git add" and/or "git commit -a")
	
	C:\git-stash-demo>git stash list
	stash@{0}: On master: 新增 new.txt 檔案
	stash@{1}: WIP on master: 95eff6b a.txt: set 1 as content

如果確定合併正確，你想刪除 `stash@{1}` 的話，可以透過 `git stash drop "stash@{1}"` 將特定暫存版刪除。

	C:\git-stash-demo>git stash drop "stash@{1}"
	Dropped stash@{1} (118cb8a7c0b763c1343599027d79f7b20df57ebf)
	
	C:\git-stash-demo>git stash list
	stash@{0}: On master: 新增 new.txt 檔案

如果想清理掉所有的暫存版，直接下達 `git stash clear` 即可全部刪除。

	C:\git-stash-demo>git stash list
	stash@{0}: On master: 新增 new.txt 檔案
	
	C:\git-stash-demo>git stash clear
	
	C:\git-stash-demo>git stash list


今日小結
-------

Git 的 stash (暫存版) 機制非常非常的實用，尤其是在 IT 業界插單嚴重的工作環境下 (不只台灣這樣，世界各地的 IT 業界應該也差不多)，這功能完全為我們量身打造，非常的貼心。在 Subversion 裡就沒有像 Git 這麼簡單，一個指令就可以把工作目錄與索引的狀態全部存起來。

本篇文章也試圖透過指令了解 stash 的核心機制，其實就是簡單的「分支」與「合併」而已，由此可知，整套 Git 版本控管機制，大多是以「分支」與「合併」的架構在運作。

我重新整理一下本日學到的 Git 指令與參數：

* git stash
* git stash -u
* git stash save
* git stash save -u 
* git stash list
* git stash pop
* git stash apply
* git stash pop "stash@{id}"
* git stash apply "stash@{id}"
* git stash drop "stash@{id}"
* git stash clear

參考連結
-------

* [BASIC SNAPSHOTTING](http://gitref.org/basic/#diff)


第 14 天： Git for Windows 選項設定
====================================================

使用 Git for Windows 指令列工具絕對比透過 GUI 工具操作來的有效率，原因就在於你可以把許多重複的版控工作透過指令自動化，或將複雜的標準作業流程(SOP)轉化成簡單的指令操作。本篇文章將分享幾則使用 Git for Windows 指令列工具的小技巧。

關於 Git 指令列工具的選項設定
----------------------------

在 Git 指令列工具裡，有許多「選項」可以設定，如同我們使用 GUI 工具通常都會有 [工具] -> [偏好設定] 一樣，可以微調指令執行時的一些行為。最常見的，當然就是首次使用 Git for Windows 的時候，必須設定 `user.name` 與 `user.email` 選項，沒有這兩個選項設定，你連執行 `git commit` 的權力都沒有。

若要列出目前設定在 Git for Windows 工具下的所有選項，可以使用 `git config --list` 命令，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1323393/3e87a850-347d-11e3-8917-ae729cd8b09e.png)

**註**：由於網路上大部分的 Git 文章，都介紹 Linux 或 Mac 電腦的執行環境如何設定，我的文章將會專注於 Windows 平台的設定教學。不過，除了儲存路徑比較不一樣之外，其實指令的用法都是相通的。

若想查詢所有可用的「選項」有哪些，可在命令提示字元下執行 `git help config` 即可顯示完整的文件說明或可連到 [git-config(1) Manual Page](https://www.kernel.org/pub/software/scm/git/docs/git-config.html) 頁面查看。

儲存 Git 選項設定的三個地方
--------------------------

1. **系統層級** ( `--system` ) (System-level configuration) (**設定於整台電腦，適用於本機所有使用者的預設值**)

	如果要列出所有設定在「系統層級」的「選項」，可以執行 `git config --list --system` 命令，也就是額外加上 `--system` 即可篩選出關於系統層級的選項設定，如下圖示：

	![image](https://f.cloud.github.com/assets/88981/1323408/673e9e74-347e-11e3-87d3-79205a74b5fe.png)

	所有的「系統層級」的選項設定預設會儲存在 `C:\Program Files (x86)\Git\etc\gitconfig` 這個檔案裡。不過，如果你電腦使用的作業系統是 Windows Vista 以上版本 (含 Windows 7 與 Windows 8 作業系統) 又同時啟用「使用者帳戶控制」 (UAC; User Access Control) 的話，那麼這個路徑將會是 `%LOCALAPPDATA%\VirtualStore\Program Files (x86)\Git\etc\gitconfig` (這個路徑位於使用者的目錄下）。會有這層改變的原因就出在 UAC 限制了一般程式存取「系統資料夾」中的檔案權限，導致你無法在使用 `git config` 寫入選項設定到這個設定檔裡。在 Windows Vista 以上版本，實作了一套 **VirtualStore** 相容性技術，讓你的程式試圖寫入檔案的同時，也可以寫入成功，不過寫入的路徑卻是不同的，這點必須特別注意。

	這個 Windows 內建的 **VirtualStore** 相容性技術，其技術文件非常稀有，似乎代表著很少人知道這個東西，但這技術確實可能會讓使用者產生困擾。例如，我們用「**一般方式執行命令提示字元**」與用「**以系統管理員身分執行命令提示字元**」，所寫入的「系統層級選項」是不能互通的。換句話說，如果你用「**以系統管理員身分執行命令提示字元**」，如下圖示：

	![image](https://f.cloud.github.com/assets/88981/1323457/7e858244-3480-11e3-8858-1272448db3d1.png)

	然後執行 `git config --system --list` 先列出所有參數，我們可以發現目前的 `core.autocrlf` 參數為 `true`，接著我將系統層級的 `core.autocrlf` 修改為 false，最後執行 `git config --system core.autocrlf` 讀出 `core.autocrlf` 的內容，你可以看到我們已經把 `core.autocrlf` 選項修改為 `false` 了。如下圖示：

	![image](https://f.cloud.github.com/assets/88981/1323480/c7e11cae-3481-11e3-9b85-c09f544c5d9a.png)

	再來我們用一般權限執行「命令提示字元」：

	![image](https://f.cloud.github.com/assets/88981/1323481/f2fe2008-3481-11e3-9caa-3f277107e9b8.png)

	然後執行 `git config --system core.autocrlf` 讀出 `core.autocrlf` 的內容，這時你可以看到我的 `core.autocrlf` 選項值也是 `false`，目前並沒有發現任何問題。不過這時如果你再執行 `git config --system core.autocrlf true` 把 `core.autocrlf` 選項設定改回 `true` 的話，在目前的環境下也沒問題：

	![image](https://f.cloud.github.com/assets/88981/1323488/1b022396-3483-11e3-802e-d7b9756a72d7.png)

	但如果我們重新「**以系統管理員身分執行命令提示字元**」，再輸入一次 `git config --system core.autocrlf` 讀出 `core.autocrlf` 的內容，你會發現其選項值竟然為 `false`，這個所謂的「系統層級」設定並沒有真的套用到所謂的「系統層級」，所以你日後使用 Git 的過程中發現「怪怪的」狀況，或懷疑 Git for Windows 這工具好像有 Bugs，但事實上這跟工具一點關係都沒有，是作業系統的問題！

	![image](https://f.cloud.github.com/assets/88981/1323494/38854a7e-3483-11e3-84e2-f4ff82c454ea.png)

	如果你的 Windows 登入帳號為 `Will` 的話，這個 `%LOCALAPPDATA%\VirtualStore\Program Files (x86)\Git\etc\gitconfig` 路徑就會自動展開為 `C:\Users\Will\AppData\Local\VirtualStore\Program Files (x86)\Git\etc\gitconfig`，也代表著，當你在「一般權限」下執行「命令提示字元」，並且透過 `git config --system` 設定「系統層級」選項，那麼該設定將會變成只有「自己」能夠套用而已，不會套用到本機其他使用者身上。

	結論：**若要設定「系統層級」選項，請務必用【以系統管理員身分執行】的方式啟用命令提示字元，然後再執行 `git config` 命令，才能寫入正確的檔案位置。**

	補充資訊: [VirtualStore - Inside Windows Vista User Account Control](http://technet.microsoft.com/en-us/magazine/2007.06.uac.aspx)

2. **使用者層級** ( `--global` ) (User-level configuration) (**設定於目前登入的使用者**)

	如果要列出所有設定在「使用者層級」的「選項」，可以執行 `git config --list --global` 命令，也就是額外加上 `--global` 即可篩選出關於使用者層級的選項設定，如下圖示：

	![image](https://f.cloud.github.com/assets/88981/1323597/5d122a68-348a-11e3-9357-8849f4046458.png)

	關於「使用者層級」的選項設定預設會儲存在 `%USERPROFILE%\.gitconfig` 或 `C:\Users\<使用者帳號>\.gitconfig` 這個檔案裡。由於檔案儲存在自己的使用者資料夾下，沒有像「系統層級」設定時有權限問題。

	一般來說，我們通常會把 `user.name` 與 `user.email` 選項設定在「使用者層級」，例如以下設定範例(請換成你自己的姓名與電子郵件地址)：

		git config --global user.name "Will Huang"
		git config --global user.email "will@example.com"

	還有，由於「使用者層級」顧名思義就是「使用者自己專用的地方」，所以通常我們也會把「個人化」的環境設定都設定在這裡，這部分本文稍後就會分享幾個環境設定的技巧。

3. **儲存區層級** ( `--local` ) (Repository-level configuration) (**設定於工作目錄下的 `.git\config` 設定檔中**)

	如果要列出所有設定在「儲存區層級」的「選項」，可以執行 `git config --list --local` 命令，也就是額外加上 `--local` 即可篩選出關於儲存區層級的選項設定，如下圖示：

	![image](https://f.cloud.github.com/assets/88981/1323606/5cb267a8-348b-11e3-8860-17aaf4d06e9b.png)

	儲存區層級的選項設定檔預設儲存在你 Git 工作目錄的 `.git\config` 設定檔中，這檔案會在你建立本地儲存庫或透過 `git clone` 取得遠端儲存庫時自動建立，如果你要定義將「特定工作目錄」才要有的選項設定，則可以直接將選項設定儲存在這裡。

Git 選項設定的套用順序
----------------------

由於設定 Git 選項時可以套用三種不同的層級，不同的層級下可以設定相同名稱的選項，但要以哪一個層級的設定為準呢？事實上 Git 指令列工具在執行時會依據以下優先順序進行套用：

1. 先套用系統層級 (優先權最低)
2. 再套用使用者層級
3. 再套用儲存區層級 (優先權最高)

也就是說，你如果再系統層級曾經設定過 `core.autocrlf` 選項，然後在使用者層級又重新定義過一次，那麼最終會套用的 `core.autocrlf` 選項值將會是「使用者層級」的設定值。

不過，若你的執行環境若是使用 Windows Vista 以上並啟用 UAC 使用者存取控制，而且還只用「一般權限」執行這些 Git 命令的話，讀取與討用的順序會多一個判斷：

1. 套用系統層級: `C:\Program Files (x86)\Git\etc\gitconfig`
2. 套用系統層級: `%LOCALAPPDATA%\VirtualStore\Program Files (x86)\Git\etc\gitconfig`
3. 套用使用者層級: `%USERPROFILE%\.gitconfig`
4. 套用儲存區層級: `.git\config` 

若你想要知道目前的工作環境最終套用的選項設定有哪些，可以直接執行 `git config --list` 即可，以取得所有「已設定」的選項設定清單：

![image](https://f.cloud.github.com/assets/88981/1323393/3e87a850-347d-11e3-8917-ae729cd8b09e.png)

選項設定的操作方式
------------------

* 取得選項設定清單

		git config --list
		git config --list --system
		git config --list --global
		git config --list --local

* 取得特定選項值

		git config [config_section.config_name]

		git config user.name
		git config user.email

* 設定特定選項值

		git config [config_section.config_name] [config_value]

		git config user.name "Will Huang"
		git config user.email "will@example.com"

* 刪除特定選項設定 

		git config --unset --system [config_section.config_name]
		git config --unset --global [config_section.config_name]
		git config --unset --local  [config_section.config_name]

選項設定檔的內容結構
------------------

Git 選項設定的檔案內容其實格式都一樣，我們試著開啟一個**使用者層級**下的設定檔看看 ( `%USERPROFILE%\.gitconfig` )：

![image](https://f.cloud.github.com/assets/88981/1323767/ac864b60-3494-11e3-9e77-7a3a8a83af2b.png)

我們從上圖可以看到，中括號 ( `[` 與 `]` ) 所包含的是一個「區段名稱」，代表某一群設定檔的分類，而其他的內容則是一組 Key/Value 的對應設定。通常我們會用 `git config` 命令來操作這些選項設定，但你其實也可以直接用 Notepad 編輯這些檔案，可以達到完全一樣的效果。
如果想了解有哪些選項可用，可以在命令提示字元下執行 `git help config` 即可顯示說明文件。

常用選項設定
------------

* 設定指令別名 (Alias)

	有沒有覺得每次用 git 打指令很囉嗦，尤其是經常使用的 `git status`, `git commit`, `git add` 或 `git log` 等指令，有時候還要外加一些額外的指令參數，每次這樣輸入還真的挺煩的。其實你可以透過指令別名的設定，讓指令輸入的更短一些。

	首先，我們先設定一些我常用的 Git Alias 設定，指令如下：

		git config --global alias.co   checkout
		git config --global alias.ci   commit
		git config --global alias.st   status
		git config --global alias.sts  "status -s"
		git config --global alias.br   branch
		git config --global alias.re   remote
		git config --global alias.di   diff
		git config --global alias.type "cat-file -t"
		git config --global alias.dump "cat-file -p"
		git config --global alias.lo   "log --oneline"
		git config --global alias.ll "log --pretty=format:'%h %ad | %s%d [%Cgreen%an%Creset]' --graph --date=short"
		git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset %ad |%C(yellow)%d%Creset %s %Cgreen(%cr)%Creset [%Cgreen%an%Creset]' --abbrev-commit --date=short"

	設定完這些「指令別名」後，如果今後你要顯示工作目錄狀態，原本你要輸入完整的 `git status`，現在你可以只輸入 `git st` 即可完成。如果你要顯示簡易版的狀態資訊，以前你要輸入 `git status -s` 才能完成，現在你只要輸入 `git sts` 即可完成。要顯示單行的歷史紀錄，現在也只要輸入 `git lo`, `git ll` 或 `git lg` 就可以完成。是不是相對的簡單很多呢！ :-)

* 指定預設文字編輯器

	預設 Git for Windows 在執行 `git commit` 的時候，會開啟 Vim 編輯器。如果你想切換成記事本的話，可以透過以下指令完成設定：

		git config --global core.editor notepad.exe

	如果想指定 Notepad++ 當為主要編輯器的話，可以透過以下指令完成設定 (請自行修改執行檔路徑)：

		git config --global core.editor "\"C:\Program Files (x86)\Notepad++\notepad++.exe\""

	當然，你想換成 Sublime Text 也是沒問題的，只要把執行檔路徑寫對即可！

* 直接編輯設定檔

	有時候直接編輯設定檔會比下指令來的有方便些，所以如果你想要直接從指令列開啟編輯設定檔的話，可以參考以下指令：

		git config --edit --system
		git config --edit --global
		git config --edit --local

	如此一來可以省去開啟檔案總管，並找到路徑的後再開啟檔案的繁瑣步驟。

* 自動辨識 CRLF 字元

	在 Windows 底下，建議最好打開 core.autocrlf 選項，讓 Git 將檔案儲存進物件儲存區 ( object storage ) 時，可以自動過濾所有 CR 字元 ( `\r` )，以利 Git 專案能更容易跨平台，讓在 Linux 與 Windows 平台做開發的人都能順利使用 Git 版本控管。

		git config --global core.autocrlf true

	幣者曾經寫過一篇 [Git 在 Windows 平台處理斷行字元 (CRLF) 的注意事項](http://blog.miniasp.com/post/2013/09/15/Git-for-Windows-Line-Ending-Conversion-Notes.aspx) 的文章，建議各位可以看看。

* 自動訂正打錯的參數

	畢竟我們是用指令列工具再輸入，打錯字在所難免，例如你輸入 `git statsu` (打錯字了)，若啟用「自動訂正」選項，則 Git 工具會自動修正為 `git status` 並成功執行，讓你不用重打一次。以下是開啟自動訂正選項的指令：

		git config --global help.autocorrect 1

* 啟用訊息顏色

	預設 Git for Windows 的「系統層級」設定中已經啟用了訊息顏色功能，但如果你不小心關閉的話，可以用以下指令開啟：

		git config --system color.ui auto

* 自訂 commit 訊息範本

	每當我們輸入 `git commit` 的時候，都會跳出一個文字編輯視窗，讓我們輸入本次要 commit 的紀錄訊息，但每次都需要重頭輸入訊息。在團隊中，你可能會希望大家共用一個「文字範本」，好讓大家在 `git commit` 的時候都能夠填寫必要的欄位或資訊。

	如果要指令 commit 訊息範本，必須先建立一個文字範本檔案，假設我放在 G:\git-commit-template.txt

	接著透過以下指令，設定 commit 訊息範本的路徑：

		git config --local commit.template "G:\git-commit-template.txt"

	最後執行 `git commit` 所跳出的訊息編輯視窗就會有預設內容了：

	![image](https://f.cloud.github.com/assets/88981/1324062/f5e98b9e-34a5-11e3-85e1-50d271665352.png)

	各位不知道有沒有注意到，我故意用 `--local` 參數，將設定儲存在「儲存庫層級」下 ( `.git\config` )，主要原因就是「訊息範本」有時候是跟著「專案」走的，不同的專案可能會想套用不同的訊息範本。如果你跟我有相同的需求，就可以套用 `--local` 參數。否則，你也可以套用 `--global` 直接套用在使用者層級下。

今日小結
-------

今天介紹的 Git for Windows 選項設定不是很常用，通常也只需要設定一次就沒事了，但「工欲善其事、必先利其器」，先把環境、選項都給設定好，你將可大幅減少 Git 版本控管的花費時間。

我重新整理一下本日學到的 Git 指令與參數：

* git config --list
* git config --list --system
* git config --list --global
* git config --list --local

* git config --edit --system
* git config --edit --global
* git config --edit --local

* git config [config_section.config_name]
* git config [config_section.config_name] [config_value]
* git config --unset --system [config_section.config_name]
* git config --unset --global [config_section.config_name]
* git config --unset --local  [config_section.config_name]
 
* git config user.name
* git config user.email
* git config user.name "Will Huang"
* git config user.email "will@example.com"

* git config --global alias.co   checkout
* git config --global alias.ci   commit
* git config --global alias.st   status
* git config --global alias.sts  "status -s"
* git config --global alias.br   branch
* git config --global alias.re   remote
* git config --global alias.di   diff
* git config --global alias.type "cat-file -t"
* git config --global alias.dump "cat-file -p"
* git config --global alias.lo   "log --oneline"
* git config --global alias.ll "log --pretty=format:'%h %ad | %s%d [%Cgreen%an%Creset]' --graph --date=short"
* git config --global alias.lg "log --graph --pretty=format:'%Cred%h%Creset %ad |%C(yellow)%d%Creset %s %Cgreen(%cr)%Creset [%Cgreen%an%Creset]' --abbrev-commit --date=short"
* git config --global core.editor notepad.exe
* git config --global core.autocrlf true
* git config --global help.autocorrect 1
* git config --system color.ui auto
* git config --local commit.template "G:\git-commit-template.txt"


參考連結
-------

* [Git - Alias](http://c9s.blogspot.tw/2009/11/git-alias.html)
* [11. Aliases | Git How To](http://githowto.com/aliases)
* [7.1 Customizing Git - Git Configuration](http://git-scm.com/book/en/Customizing-Git-Git-Configuration)
* [git-config(1) Manual Page](https://www.kernel.org/pub/software/scm/git/docs/git-config.html)



第 15 天：標籤 - 標記版本控制過程中的重要事件
===========================================================

在使用 Git 版本控管的過程中，會產生大量的版本，隨著寒暑易節、物換星移，在這眾多的版本之中，一定會有一些值得我們紀錄的幾個重要版本，這就是｢標籤｣ (Tag) 能幫我們做的事。

關於標籤 (Tag) 的基本概念
------------------------

基本上，標籤的用途就是用來標記某一個「版本」或稱為「commit 物件」，以一個「好記的名稱」來幫助我們記憶【某個】版本。

Git 標籤 (Tag) 擁有兩種型態，這兩種類型分別是：

* 輕量標籤 (lightweight tag) 
* 標示標籤 (annotated tag)

我們在【第 11 天：認識 Git 物件的一般參照與符號參照】文章中有提到「一般參照」包含了「標籤名稱」這項，這裡的「標籤名稱」就是所謂的「輕量標籤」(lightweight tag) 。所以「輕量標籤」可以說是某個 commit 版本的「別名」而已，是一種「相對名稱」。

「標示標籤」(annotated tag)則是一種 Git 物件，就像我們在【第 06 天：解析 Git 資料結構 - 物件結構】提到的，Git 物件包含 4 種物件類型，分別是 Blob, Tree, Commit 與 Tag 物件，這裡講的「標示標籤」就是 Tag 物件。Tag 物件會儲存在 Git 的物件儲存區當中 ( 會存到 `.git\objects\` 目錄下 )，並且會關聯到另一個 commit 物件，建立「標示標籤」時還能像建立 commit 物件時一樣包含「版本訊息」。在內建的 Git 標籤機制中，甚至你還可以利用 [GnuPG](http://gnupg.org/) 金鑰對 Tag 物件加以簽章，以確保訊息的「不可否認性」。

雖然我們有這兩種標籤類型，看起來也都像某個 commit 物件的「別名」，但這兩種標籤在使用上只有些微的差異而已。在大部分的使用情境下，我們都會用「標示標籤」來建立「標籤物件」並且給予「版本訊息」，因為這種「標籤」才是 Git 儲存庫中「永久的物件」。( 儲存到物件儲存庫中的 Git 物件都是不變的，只有索引才是變動的 )

了解輕量標籤(lightweight tag)的使用方式
---------------------------------------

我用一個簡單的例子說明建立「輕量標籤」的過程，如下圖示：(請自行看圖說故事)

![image](https://f.cloud.github.com/assets/88981/1331276/98bb87ac-354e-11e3-8aea-fce46caf5c28.png)

**提示**：所有在 `.git\refs\` 下的檔案都是個「參考名稱」。

大致的使用說明如下：

* 列出所有標籤：`git tag`
* 建立輕量標籤：`git tag [tagname]`
* 刪除輕量標籤：`git tag [tagname] -d`

如果我們想看這個「輕量標籤」的內容，我們可以透過 `git cat-file -p [tagname]` 取得。如果我們想看這個「輕量標籤」的物件類型，可以透過 `git cat-file -t [tagname]` 取得。如下圖示：

![image](https://f.cloud.github.com/assets/88981/1331323/ad62bd80-3551-11e3-9f43-7e6d18a1a29c.png)

**請注意**: 輕量標籤不是個 Git 物件，所以我們從上圖可以看出，該 Tag 名稱取得的是 commit 物件的內容，而且該名稱所查出的物件類型是 commit 物件。

了解標示標籤(annotated tag)的使用方式
------------------------------------

我也用一個簡單的例子說明建立「標示標籤」的過程，如下圖示：(請自行看圖說故事)

![image](https://f.cloud.github.com/assets/88981/1331359/123e15aa-3553-11e3-8deb-619156fa5804.png)

這裡跟「輕量標籤」有些不一樣的地方：

1. 當我們執行 `git tag` 列出所有標籤時，所有標籤都會混在一起，看不出標籤的類型。
2. 建立「標示標籤」要加上 `-a` 參數。
3. 建立「標示標籤」要一定要加上「版本訊息」，跟執行 `git commit` 一樣都有 `-m` 參數可用。
4. 當我們執行 `git cat-file -p 1.0.0-beta` 時，你應該可以看出這個物件內容跟 commit 物件稍稍有點不同。
5. 當我們執行 `git cat-file -p 1.0.0-beta` 時，你從內容看到的 `type` 講的是上一行 `object` 的物件類型，這代表你也可以把任何 Git 物件建立成一個標籤物件。
6. 當我們執行 `git cat-file -t 1.0.0-beta` 時，得到的是 tag 物件類型。

標示標籤的指令用法，跟輕量標籤一模一樣，差別只有 `-a` 參數而已。

※ 預設 `git tag [tagname] -a` 會將當前的 `HEAD` 版本建立成「標籤物件」，如果要將其他特定物件建立為標籤的用法為 `git tag [tagname] [object_id]`。


今日小結
-------

最後，我把本篇文章建立的兩個例子重新比較一遍，從下圖你應該可以很清楚看出兩者之間的差異：

![image](https://f.cloud.github.com/assets/88981/1331395/e83515e0-3554-11e3-9490-a6d2ee122381.png)

我重新整理一下本日學到的 Git 指令與參數：

* git tag
* git tag [tagname]
* git tag [tagname] -a
* git tag [tagname] -d

※ 若想查詢 `git tag` 的完整用法，可在命令提示字元下執行 `git help tag` 即可顯示完整的文件說明。

參考連結
-------

* [BRANCHING AND MERGING](http://gitref.org/branching/#tag)
* [Semantic Versioning](http://semver.org/)


第 16 天：善用版本日誌 git reflog 追蹤變更軌跡
============================================================

其實學習 Git 版本控管的指令操作並不難，但要弄清楚 Git 到底對我的儲存庫做了什麼事，還真不太容易。當你一步步了解 Git 的核心與運作原理，自然能有效掌控 Git 儲存庫中的版本變化。本篇文章，就來說說 Git 如何記錄我們的每一版的變更軌跡。

了解版本紀錄的過程
-----------------

在清楚理解 Git 基礎原理與物件結構之前，你不可能了解版本紀錄的過程。而當你不了解版本紀錄的過程，自然會擔心「到底我的版本到哪去了」，也許有人跟你說「我們用了版本控管，所以所有版本都會留下，你大可放心改 Code」。知道是一回事，知不知道怎麼做又是一回事，然後是不是真的做得到又是另外一回事。我們在版控的過程中盡情 commit 建立版本，但如果有一天發現有某個版本改壞了，或是因為執行了一些合併或重置等動作導致版本消失了，那又該怎麼辦呢？

還好在 Git 裡面，有一套嚴謹的紀錄機制，而且這套機制非常開放，紀錄的檔案都是文字格式，還蠻容易了解，接下來我們就來說明版本紀錄的過程。

我們先進入任何一個 Git 工作目錄的 `.git/` 資料夾，你可以看到一個 `logs` 目錄，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1333182/df24ecac-358e-11e3-93d7-9740ce10458c.png)

這個 `logs` 資料夾下有個 `HEAD` 檔案，這檔案紀錄著「當前分支」的版本變更紀錄：

![image](https://f.cloud.github.com/assets/88981/1333369/60d3e8e4-3593-11e3-8430-be605a5d7295.png)

我們開啟該檔看看其內容 (其中物件 id 的部分我有刻意稍作刪減，以免每行的內容過長)：

	0000000 f5685e0 Will <xxxx@gmail.com> 1381718394 +0800	commit (initial): Initial commit
	f5685e0 38d924f Will <xxxx@gmail.com> 1381718395 +0800	commit: a.txt: set 1 as content
	38d924f efa1e0c Will <xxxx@gmail.com> 1381734238 +0800	commit: test
	efa1e0c af493e5 Will <xxxx@gmail.com> 1381837967 +0800	commit: Add c.txt

從這裡你將可看出目前在這個分之下曾經記錄過 4 個版本，此時我們用 `git reflog` 即可列印出所有「歷史紀錄」的版本變化，你會發現內容是一樣的，但順序正好顛倒。從文字檔中看到的內容，「第一版」在最上面，而透過 `git reflog` 則是先顯示「最新版」最後才是「第一版」：

![image](https://f.cloud.github.com/assets/88981/1333422/90659b88-3594-11e3-8457-b06c4895c567.png)

這時我們試圖建立一個新版本，看看記錄檔的變化，你會發現版本被建立成功：

![image](https://f.cloud.github.com/assets/88981/1333468/6dd7bf8c-3595-11e3-9614-af723cfd9056.png)

從上圖你可以發現到，這裡有個特殊的「參考名稱」為 `HEAD@{0}`，這裡每個版本都會有一個歷史紀錄都會有個編號，代表著這個版本的在記錄檔中的順位。如果是 `HEAD@{0}` 的話，永遠代表目前分支的「最新版」，換句話說就是你在這個「分支」中最近一次對 Git 操作的紀錄。你對 Git 所做的任何版本變更，全部都會被記錄下來。

復原意外地變更
--------------

初學者剛開始使用 Git 很有可能會不小心執行錯誤，例如透過 `git merge` 執行合併時發生了衝突，或是透過 `git pull` 取得遠端儲存庫最新版時發生了失誤。在這種情況下，你可以利用 `HEAD@{0}` 這個特殊的「參考名稱」來對此版本「定位」，並將目前的 Git 儲存庫版本回復到前一版或前面好幾版。

例如，我們如果想要「取消」最近一次的版本紀錄，我們可以透過 `git reset HEAD@{1} --hard` 來復原變更。如此一來，這個原本在 `HEAD@{0}` 的變更，就會被刪除。不過，在 Git 裡面，所有的變更都會被記錄，其中包含你做 `git reset "HEAD@{1}" --hard` 的這個動作，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1333551/ff3e98fa-3596-11e3-8a24-bd4d32f1a4aa.png)

這代表甚麼意義呢？這代表你在執行任意 Git 命令時，再也不用擔心害怕你的任何資料會遺失，就算你怎樣下錯指令都沒關係，所有已經在版本庫中的檔案，全部都會保存下來，完全不會有遺失的機會。所以，這時如果你想復原剛剛執行的 `git reset "HEAD@{1}" --hard` 動作，只要再執行一次 `git reset "HEAD@{1}" --hard` 即可，是不是非常棒呢！你看下圖，我把剛剛的 `9967b3f` 這版本給救回來了：

![image](https://f.cloud.github.com/assets/88981/1333591/e5be654e-3597-11e3-9080-7d3bf82f63f6.png)

紀錄版本變更的原則
-----------------

事實上在使用 Git 版控的過程中，有很多機會會產生「版本歷史紀錄」，我說的並不是單純的 `git log` 顯示版本紀錄，而是原始且完整的變更歷史紀錄。這些紀錄版本變更有個基本原則：【只要你透過指令修改了任何參照(ref)的內容，或是變更任何分支的 `HEAD` 參照內容，就會建立歷史紀錄】。也因為這個原則，所以指令名稱才會稱為 `reflog`，因為是改了 `ref` (參照內容) 才引發的 `log` (紀錄)。

例如我們拿 `git checkout` 命令還切換不同的分支，這個切換的過程由於會修改 `.git\HEAD` 參照的內容，所以也會產生一個歷史紀錄，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1333661/55ecdc3c-3599-11e3-9191-10b2cd9263a8.png)

還有哪些動作會導致產生新的 reflog 紀錄呢？以下幾個動作你可以參考，但其實可以不用死記，記住原則就好了：

* commit
* checkout
* pull
* push
* merge
* reset
* clone
* branch
* rebase
* stash

除此之外，每一個分支、每一個暫存版本(stash)，都會有自己的 reflog 歷史紀錄，這些資料也全都會儲存在 `.git\logs\refs\` 資料夾下。

只顯示特定分支的 reflog 紀錄
----------------------------

在查詢歷史紀錄時，你也可以針對特定分支(Branch)進行查詢，僅顯示特定分支的變更歷史紀錄，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1333693/1e095bfa-359a-11e3-814b-84f873d282fb.png)

顯示 reflog 的詳細版本記錄
--------------------------

我們已經學會用 `git reflog` 就可以取出版本歷史紀錄的摘要資訊。但如果我們想要顯示每一個 reflog 版本中，每一個版本的完整 commit 內容，那麼你可以用 `git log -g` 指令顯示出來：

![image](https://f.cloud.github.com/assets/88981/1333836/34814278-359d-11e3-9846-6c006291f1c2.png)

刪除特定幾個版本的歷史紀錄
------------------------

基本上，版本日誌(reflog)所記錄的只是變更的歷程，而且預設只會儲存在「工作目錄」下的 `.git/` 目錄裡，這裡所記錄的一樣只是 commit 物件的指標而已。無論你對這些紀錄做任何操作，不管是竄改、刪除，都不會影響到目前物件儲存庫的任何內容，也不會影響版本控管的任何資訊。

如果你想刪除之前紀錄的某些紀錄，可以利用 `git reflog delete ref@{specifier}` 來刪除特定歷史紀錄。如下圖示：

![image](https://f.cloud.github.com/assets/88981/1334053/02b57fac-35a2-11e3-8f7e-9d1bea1d74d7.png)

**註**：這些版本日誌預設並不會被同步到「遠端儲存庫」，以免多人開發時大家互相影響，所以版本日誌算是比較個人的東西。

設定歷史紀錄的過期時間
---------------------

當你的 Git 儲存庫越用越久，可想見這份歷史紀錄將會越累積越多，這樣難道不會爆掉嗎？還好，預設來說 Git 會幫你保存這些歷史紀錄 90 天，如果這些紀錄中已經有些 commit 物件不在分支線上，則預設會保留 30 天。

舉個例子來說，假如你先前建立了一個分支，然後 commit 了幾個版本，最後直接把該分支刪掉，這時這些曾經 commit 過的版本 (即 commit 物件) 還會儲存在物件儲存區 (object storage) 中，但已經無法使用 `git log` 取得該版本，我們會稱這些版本為「不再分支線上的版本」。

如果你想修改預設的過期期限，可以透過 `git config gc.reflogExpire` 與 `git config gc.reflogExpireUnreachable` 來修正這兩個過期預設值。如果你的硬碟很大，永遠不想刪除紀錄，可以考慮設定如下：

	git config --global gc.reflogExpire "never"
	git config --global gc.reflogExpireUnreachable "never"

如果只想保存 7 天，則可考慮設定如下：

	git config --global gc.reflogExpire "7 days"
	git config --global gc.reflogExpireUnreachable "7 days"

**註**：從上述範例所看到的 `7 days` 這段字，我找了好久都沒有看到完整的說明文件，最後終於找到 Git 處理日期格式的原始碼(C語言)，有興趣的也可以看看：[http://git.kernel.org/cgit/git/git.git/tree/date.c](http://git.kernel.org/cgit/git/git.git/tree/date.c)

除此之外，你也可以針對特定分支設定其預設的過期時間。例如我想讓 `master` 分支只保留 14 天期，而 `develop` 分支可以保留完整記錄，那麼你可以這樣設定：(注意: 以下範例我把設定儲存在本地儲存庫中，所以使用了 `--local` 參數)

	git config --local gc.master.reflogExpire "14 days"
	git config --local gc.master.reflogExpireUnreachable "14 days"

	git config --local gc.develop.reflogExpire "never"
	git config --local gc.develop.reflogExpireUnreachable "never"

上述指令寫入到 `.git\config` 的內容將會是：

	[gc "master"]
		reflogExpire = 14 days
		reflogExpireUnreachable = 14 days
	[gc "release"]
		reflogExpire = never
		reflogExpireUnreachable = never


清除歷史紀錄
-------------

若要立即清除所有歷史紀錄，可以使用 `git reflog expire --expire=now --all` 指令完成刪除工作，最後搭配 `git gc` 重新整理或清除那些找不到、無法追蹤的版本。如下圖示：

![image](https://f.cloud.github.com/assets/88981/1333880/19f26616-359e-11e3-835e-7dee15b9c146.png)


今日小結
-------

Git 的版本日誌(reflog)幫我們記憶在版控過程中的所有變更，幫助我們「回憶」到底這段時間到底對 Git 儲存庫做了什麼事。不過你也要很清楚的知道，這些只是個「日誌」而已，不管有沒有這些日誌，都不影響我們 Git 儲存庫中的任何版本資訊。

我重新整理一下本日學到的 Git 指令與參數：

* git reflog
* git reflog [ref] 
* git log -g 
* git reset "HEAD@{1}" --hard
* git reflog delete "ref@{specifier}"
* git reflog delete "HEAD@{0}"
* git reflog expire --expire=now --all
* git gc 
* git config --global gc.reflogExpire "never"
* git config --global gc.reflogExpireUnreachable "never"


參考連結
-------

* [git-reflog(1) Manual Page](http://git-scm.com/docs/git-reflog)
* [git-gc(1) Manual Page](http://git-scm.com/docs/git-gc)
* [http://git.kernel.org/cgit/git/git.git/tree/date.c](http://git.kernel.org/cgit/git/git.git/tree/date.c)


第 17 天：關於合併的基本觀念與使用方式
========================================================

我曾在【第 08 天：關於分支的基本觀念與使用方式】提過關於「分支」的基本觀念與用法，現在則要來講「合併」如何進行。由於 Git 是一種分散式版本控管系統(DVCS)，過程中會不斷的進行分支與合併，無論是有意的合併(`git merge`)或無意的合併(`git pull`)，總之使用 Git 版控「分支」與「合併」的動作確實經常發生。本篇文章將說明「合併」動作的基本觀念與使用方式。

關於「合併」的基本觀念
--------------------

當你在 Git 工作目錄下建立分支時，可以讓你的系統依據不同的需求分別進行開發，又不互相影響。例如你原本穩定的系統可以放在 `master` 分支中進行開發，而當要修正錯誤時則額外建立一個 `bugfix` 分支來改正軟體錯誤，等 Bugs 修正後，在透過「合併」的方式將 `bugfix` 分支上的變更重新套用到 `master` 上面，這就是一種主要的使用情境。

一般來說，大家都是以一個主要或預設分支進行開發(`master`)，然後再依據需求建立分支(`bugfix`)，最後則是將兩個分支合併成一個。事實上，執行「合併」動作時，是將另一個分支合併回目前分支，然後再手動將另一個分支給移除，這樣才符合「兩個分支合併成一個」的概念。

實務上，也經常有機會將三個、四個或更多的分支合併到其中一個分支。例如你除了主要分支(`master`)外，還額外建立了除錯用的分支(`bugfix`)與新增功能(`feature`)的分支，當開發到一定程度後，你可以決定要不要將這個兩個分支一起合併回主要分支(`master`)。

在 Git 使用合併時，有一個重要的觀念是【合併的動作必須發生在同一個儲存庫中】。請回想一下，在任何一個 Git 儲存庫中，都必須存在一個 Initial Commit 物件(初始版本)，而所有其他版本都會跟這個版本有關係，這個關係我們稱為「在分支線上的可追蹤物件」(the tracked object on the branch heads)，所以你不能將一個儲存庫的特定分支合併到另一個毫不相干的儲存庫的某個分支裡。

合併的時候，如果兩個分支當中有修改到相同的檔案，但只要修改的行數不一樣，Git 就會自動幫你套用/合併這兩個變更。但如果就這麼剛好，你在兩個分支裡面改到「同一個檔案」的「同一行」，那麼在合併的時候就會引發衝突事件。當合併衝突發生時，Git 並不會幫你決定任何事情，而是將「解決衝突」的工作交給「你」來負責，且這些發生衝突的檔案也都會被標示為 `unmerged` 狀態，合併衝突後你可以用 `git status` 指令看到這些狀態。 

體驗一場「成功的合併」
--------------------

簡單來說，「成功的合併」就是沒有發生「衝突」的合併。我們用一個簡單的例子說明合併的過程與指令的用法：
	
	mkdir git-merge-demo
	cd git-merge-demo
	git init
	
	echo. > a.txt
	git add .
	git commit -m "Initial commit (a.txt created)"
	
	echo 1 > a.txt
	git add .
	git commit -m "Update a.txt!"

執行結果如下圖示，我們建立了兩個版本，而且最新版的 `a.txt` 內容為 `1`：

![image](https://f.cloud.github.com/assets/88981/1342013/def008dc-3658-11e3-9215-24dee37d9a6e.png)

接著我們透過 `git checkout -b feature` 建立一個 `feature` 分支，並同時把工作目錄給切換到 `feature` 分支進行開發，然後建立一個內容為 `2` 的 `b.txt` 檔案：

![image](https://f.cloud.github.com/assets/88981/1342036/8c70fb60-3659-11e3-8768-d238ea867225.png)

**注意**：在切換「分支」之前，請隨時查看並保持「工作目錄」的狀態是「乾淨的」，不要有有任何檔案異動中的狀態。

現在我們回顧一下兩個分支的內容：

* 主要分支：`master`
	* 擁有 `a.txt` 其內容為 `1` 
* 功能分支：`feature` (目前所在分支)
	* 擁有 `a.txt` 其內容為 `1`	(此檔案室從 `master` 分支繼承過來的)
	* 擁有 `b.txt` 其內容為 `2`

我們現在要做 3 件事：

1. 將工作目錄切換回 `master` 主要分支
2. 將 `a.txt` 的內容新增一行 `NEW LINE` 在第二行 (第一行不動)
3. 將 `a.txt` 的異動加入索引，並 commit 版本 

如下圖示：

![image](https://f.cloud.github.com/assets/88981/1342178/ca97d2b6-365d-11e3-9c32-0e7d1daf2a8b.png)

現在我們再回顧一次當下兩個分支的內容：

* 主要分支：`master` (目前所在分支)
	* 擁有 `a.txt` 其內容有兩行，第一行為 `1`，第二行是 `NEW LINE`
	* 這裡沒有 `feature` 分支的變更，也就是沒有 `b.txt` 檔案。 
* 功能分支：`feature`
	* 擁有 `a.txt` 其內容為 `1`	(這是從 `master` 分支繼承過來的，在 `feature` 沒動過)
	* 擁有 `b.txt` 其內容為 `2`	(這是從 `feature` 才新建立的檔案)

我們用 SourceTree 可以查看較為漂亮的 commit graph (版本圖)：

![image](https://f.cloud.github.com/assets/88981/1342186/fe3e9d02-365d-11e3-969b-aa53d4da0727.png)

由於兩個分支都有在建立 `feature` 分支後都做過異動，不過你可能會發現到，這兩個分支當中，從「分支點」開始，所做的修改並沒有互相衝突，只要是這種狀況，合併並不會發生問題。接下來我們就來執行「合併」動作 (`git merge`)。

從下圖示中，有許多我想強調的細節：

1. 合併之前，先看清楚自己在哪個分支
2. 合併之前，請確保工作目錄是乾淨的
3. 合併時請用 `git merge [另一個分支]` 來將另一個分支的變更合併回來
4. 你可以從下圖看到我打錯字了，但 Git 還會自動幫我執行正確的指令，詳情請見【第 14 天： Git for Windows 選項設定】
5. 合併成功後，你可以利用 `git log` 查看版本紀錄，你可以發現**「合併」的過程會自動建立一個新版本**！

![image](https://f.cloud.github.com/assets/88981/1342227/2bbf4906-365f-11e3-9572-cf83d0e18d5a.png)

我們看看「合併後」的分支狀況，用 SourceTree 的 commit graph 來看：

![image](https://f.cloud.github.com/assets/88981/1342257/b377b4d2-365f-11e3-93dc-918da5d52e4b.png)

最後我們來看看合併後的檔案內容，確實如我們預期的把兩個分支中的變更都給合併了：

![image](https://f.cloud.github.com/assets/88981/1342374/1f0cf778-3662-11e3-8058-21d6a3e9b39e.png)

這就是一場成功的「合併」！ :-)

刪除不必要的分支
----------------

假設我們 `feature` 分支還會持續開發新功能，所以可以暫時將它留著，讓後續還能繼續切換到 `feature` 分支繼續開發。

如果你確定用不到的話，可以用 `git branch -d feature` 刪除該分支。

![image](https://f.cloud.github.com/assets/88981/1342332/26ff8604-3661-11e3-8a12-f6ed7c272ea1.png)

在 Git 裡，只要沒有執行過「合併」的分支，都不能用上述指令進行刪除，必須改用 `git branch -D feature` 才能刪除該分支。

救回誤刪的分支
--------------

不過，如果你不小心「誤刪」該分支(`feature`)的話，則必須用以下步驟救回分支，稍微麻煩一點：

1. 先利用 `git reflog` 找出該分支(`feature`)最後一個版本的 object id (也就是 SHA1 格式的物件絕對名稱)
2. 執行 `git branch feature <SHA1>` 即可

如下圖示，最終還是能把誤刪的 `feature` 分支給救回：

![image](https://f.cloud.github.com/assets/88981/1342355/ad79df54-3661-11e3-99d4-46685c7a031c.png)

體驗一場「衝突的合併」
--------------------

現在，我們從 `master` 分支的最新版(`HEAD`)建立一個 `hotfixes` 分支，執行指令：`git checkout -b hotfixes`

![image](https://f.cloud.github.com/assets/88981/1342402/c7c06418-3662-11e3-9e87-fbdfa931a362.png)

我們修改 `a.txt` 的第一行，把原本的 `1` 修改為 `bugfixed: 1`，並建立版本。然後切換回 `master` 分支：

![image](https://f.cloud.github.com/assets/88981/1342420/20b623b4-3663-11e3-8c22-d1076622cd56.png)

接著，我們在 `master` 分支修改 `a.txt` 的第一行，把原本的 `1` 修改為 `bugfixed by Will: 1`，並建立版本。

![image](https://f.cloud.github.com/assets/88981/1342439/842d0ffc-3663-11e3-9687-b023fa519712.png)

現在，我們兩個分支都同時修改了 `a.txt` 的檔案內容，而且都在同一行，這個時候發生衝突，勢必引發「衝突」。我們就馬上來體驗一下：

![image](https://f.cloud.github.com/assets/88981/1342452/f1f3b996-3663-11e3-8f60-2d643d7c16f2.png)

沒錯，真的衝突了，而且 Git 告訴我要自己修正(fix)這個衝突(conflicts)。我們用 `git status` 可以看出目前發生衝突的檔案有哪些，而且你也可以看到這個檔案位於 `Unmerged paths` 這個區段。

查看衝突的內容
--------------

當你發生衝突的時候，切莫慌張，先執行 `git diff` 自動比對出到底哪些檔案的哪幾行發生衝突了。

![image](https://f.cloud.github.com/assets/88981/1342473/4e5bf676-3664-11e3-80d1-79a33790d31d.png)

從上圖你必須注意的是 `diff` 針對衝突內容的表示法，看的懂，你才容易知道怎樣改：

* 從 `<<<<<<< HEAD` 到 `=======` 的內容，代表 `HEAD` 裡 `a.txt` 的內容。**註**：`HEAD` 代表當前 `master` 分支的最新版。
* 從 `=======` 到 `>>>>>>> hotfixes` 的內容，代表 `hotfixes` 分支裡 `a.txt` 的內容

解決衝突狀態的方法
-----------------

我先來說說「解決衝突狀態」的方法，其實很簡單，直接輸入 `git add .` 把目前工作目錄的狀態加入到「索引」之中，就可以取消這些 Unmerged 檔案的衝突狀態。

如果你很懶，遇到衝突什麼都不改，直接執行 `git add .` 再加上 `git commit` 的話，確實會「解決衝突」，但所 commit 的版本將會包含這些衝突的表示文字，如果你身處一個開發團隊，肯定會被罵翻到臭頭，請你千萬不要這麼做！

![image](https://f.cloud.github.com/assets/88981/1342540/a1dfd280-3665-11e3-9ce3-242ffa705d45.png)

做錯了？沒關係，只要執行 `git reset --hard ORIG_HEAD` 就可以回復到上一版，然後再重新合併一次引發相同的衝突。

![image](https://f.cloud.github.com/assets/88981/1342812/d266950c-3669-11e3-8004-3b5ff51e7081.png)

找出衝突的檔案
--------------

當合併發生衝突時的檔案數量很少時，或許直接打 `git diff` 可以看得出差異，但如果是兩個比較大的分支發生衝突的話，很有可能會有一大堆檔案有衝突的狀況。這時你可能會想一個一個檔案的來查看衝突的狀況，這時你可以用以下兩種 Git 指令找出衝突的檔案：

* 執行 `git status`
* 執行 `git ls-files -u`

![image](https://f.cloud.github.com/assets/88981/1342723/4b4d4af8-3668-11e3-9d6d-9debb683bd7a.png)

找到之後再用 `git diff [filepath]` 就可以僅比對其中一個檔案了：

![image](https://f.cloud.github.com/assets/88981/1342738/9b749266-3668-11e3-903d-aa264d80302c.png)

真正解決衝突
------------

真的要解決衝突，你必須手動把這些衝突的檔案改好。不過，如果這時使用 SourceTree 來修復衝突的檔案，那生命將會美好許多。

我們開啟 SourceTree 並進入 Working Copy 節點，在檔案清單中按下滑鼠右鍵，這時有個 **Resolve Conflicts** (解決衝突) 的選單，這裡你就能選擇你要用我的(`Mine`)或是用他的(`Theirs`)來解決這個檔案的衝突狀態。所謂「我的」就是你當前工作目錄的那個分支(`master`)，而「他的」就是被我們指定合併進來的那個分支(`hotfixes`)。

![image](https://f.cloud.github.com/assets/88981/1342901/0d32f4e0-366b-11e3-9343-2094141ac4d0.png)

如果我選 **Resolve Using 'Mine'** 的話，他還會出現一個確認合併的視窗，你按下 OK 之後，SourceTree 就會自動將檔案中發生衝突的那些段落，修改成「我的」版本：

![image](https://f.cloud.github.com/assets/88981/1342920/712a8828-366b-11e3-918d-ad78f64b04c8.png)

請注意：當你利用 SourceTree 幫你解決衝突後，該檔案也會直接加入到索引之中(`git add .`)，但不會幫你執行 `git commit` 動作，所以你還要自己多做這一步：

![image](https://f.cloud.github.com/assets/88981/1342967/deb24b74-366b-11e3-8f7c-c42712d82d6b.png)

輸入一些版本訊息後，就可以執行 Commit 動作( Commit 按鈕在視窗右下角 )： 

![image](https://f.cloud.github.com/assets/88981/1342974/f5fef174-366b-11e3-9b30-a678d7eb21aa.png)

我們來看解決衝突並合併後的 commit graph 如下：

![image](https://f.cloud.github.com/assets/88981/1342991/23bb83fc-366c-11e3-8518-27968fb0a566.png)


今日小結
-------

Git 合併算是比較困難的部分，但重點還是在觀念，觀念正確了，就算發生衝突也不用害怕。搭配好用的 GUI 工具，也能夠更加順利與快速的解決衝突問題。說真的，若發生衝突時沒有 GUI 工具，光是打指令真的會瘋掉。

我重新整理一下本日學到的 Git 指令與參數：

* git merge [other_branchname]
* git checkout -b [new_branchname]
* git reflog
* git branch -d [branchname]
* git branch -D [branchname]
* git branch feature <SHA1>
* git reset --hard ORIG_HEAD
* git status
* git ls-files -u
* git diff [filepath]

參考連結
-------

* [BRANCHING AND MERGING](http://gitref.org/branching/#merge)


第 18 天：修正 commit 過的版本歷史紀錄 Part 1
=============================================================

當你使用 Git 進行版本控管時，我們會利用 `git commit` 建立許多版本，由於 Git 屬分散式版本控管機制，對於版本控管方面沒有太多的權限設計，跟其他如 Subversion 或 TFVC 這類版控系統相比，Git 提供更多「修正版本記錄」的機制，讓你在「分享」版本給其他人的時候，能夠預先做個整理。

版本控管的基本原則
-------------------

我們在進行版本控管時，無論是 Git, Subversion 或 TFVC 都一樣，維持一個良好的版本紀錄有助於我們追蹤每個版本的更新歷程 (當有需要做這件事的時候)。以我個人的經驗，我們很好有機會，也不太想去追蹤我們某個專案中軟體開發的進程，我們許多專案累積的版本紀錄數量有多達數千筆，誰會有這種閒工夫去追查歷史呢？

然而實務上，當軟體的臭蟲(Bug)發生的時候，我們會需要去追蹤特定臭蟲的歷史紀錄，以查出該臭蟲真正發生的原因，這個時候就是版本控管帶來最大價值的時候。

也因此，要怎樣維持一個好的「版本紀錄」也是非常重要的，這邊有一些控管原則可以分享給大家：

* 做一個小功能修改就建立版本，這樣才容易追蹤變更
* 千萬不要累積一大堆修改後才建立一個「大版本」
* 有邏輯、有順序的修正功能，確保相關的版本修正可以按順序提交(commit)，這樣才便於追蹤

不過，人非聖賢、孰能無過，哪個人能確保團隊所有人都能時時刻刻照著上述原則進行版控？哪個人不是「想到哪改到哪」呢？這樣的要求變得有點緣木求魚、不切實際。所以，我們需要有一套「修改版本」的機制，讓版本提交到遠端伺服器上的時候，就已經是完美的版本狀態。


修正 commit 歷史紀錄的理由
---------------------------

到目前為止，我還沒提到關於「遠端儲存庫」的細節，所以大部分的 Git 操作都還專注在本地端，也就是在工作目錄下的版本管控，這個儲存庫就位於你的 `.git/` 目錄下。然而，之後我們即將提到「遠端儲存庫」的應用，到時就不只一個人擁有儲存庫，所需要注意的細節也就更多。

完全開放每個人都能夠任意的修正 commit 歷史紀錄，這個概念對於熟悉 Subversion 或 TFVC 的人來說或許聽起來非常很奇怪，因為以往大家都集中連接到版本控管的伺服器上，用的是集中式的儲存庫，如果有人可以任意串改歷史紀錄，那版控還叫做版控嗎？

其實在 Git 版本控管中，概念是一樣的，只要同一份儲存庫有多人共用的情況下，若有人任意串改版本，那麼 Git 版本控管一樣會無法正常運作。

所以，到底甚麼樣的使用情境會需要去修改版本紀錄呢？以下幾點各位可以參考看看。

假設我們現在有 [A] -> [B] -> [C] 三個版本：

* 可能 [C] 版本你發現 commit 錯了，必須刪除這一版本所有變更
* 你可能 commit 了之後才發現 [C] 這個版本其實只有測試程式碼，你也想刪除他
* 其中有些版本的紀錄訊息有錯字，你想修改訊息文字，但不影響檔案的變更歷程
* 你可以想把這些版本的的 commit 順序調整為 [A] -> [C] -> [B]，讓版本演進更有邏輯性
* 你發現 [B] 這個版本忘了加入一個重要的檔案就 commit 了，你想事後補救這次變更
* 在你打算｢分享」分支出去時，發現了程式碼有瑕疵，你可以修改完後再分享出去

修正 commit 歷史紀錄的注意事項
-----------------------------

Git 保留了「修改版本歷史紀錄」的機制，主要是希望你能在「自我控管版本」到了一定程度後，自己整理一下版本紀錄的各種資訊，好讓你將版本「發布」出去後，讓其他人能夠更清楚的理解你對這些版本到底做了哪些修改。

所以，修改版本歷史紀錄時，有些事情必須特別注意：

* 一個儲存庫可以有許多分支 (預設分支名稱為 `master`)
* 分享 Git 原始碼的最小單位是以「分支」為單位
* 你可以任意修改某個支線上的版本，只要你還沒「分享」給其他人
* **當你「分享」特定分支給其他人之後，這些「已分享」的版本歷史紀錄就別再改了！**

準備本日練習用的版本庫
----------------------

之前我們曾在【第 04 天：常用的 Git 版本控管指令】學過 `git reset` 的用法，主要用來 **重置目前的工作目錄**。不過，相同的指令，也可以用來修正版本歷史紀錄。

在開始說明前，我們一樣先用以下指令建立一個練習用的工作目錄與本地儲存庫：
	
	mkdir git-reset-demo
	cd git-reset-demo
	git init
	
	echo. > a.txt
	git add .
	git commit -m "Initial commit (a.txt created)"
	
	echo 1 > a.txt
	git add .
	git commit -m "Update a.txt!"
	
	echo 1 > b.txt
	git add .
	git commit -m "Add b.txt!"

![image](https://f.cloud.github.com/assets/88981/1360658/71071c7c-37fa-11e3-867c-c80f57f3062d.png)

以上建立了三個版本，執行 `git log` 的結果如下圖示：

![image](https://f.cloud.github.com/assets/88981/1360663/8a4c9324-37fa-11e3-9b1c-b407b333c243.png)


刪除最近一次的版本
-------------------

我們參考上圖，用文字表達這三個版本的順序如下：

	[83a841] > [0576e0] > [aef2a5] 

現在，我想把最後一個版本刪除，變成：

	[83a841] > [0576e0]

那麼，你可以執行 `git reset --hard "HEAD^"` 即可刪除 `HEAD` 這個版本：
**請注意**：在「命令提示字元下」 `^` 是特殊符號，所以必須用雙引號括起來！

![image](https://f.cloud.github.com/assets/88981/1360710/3754b57e-37fb-11e3-9082-241f9d8e98ab.png)

此時你可以看見，原本的最新版被刪除了，那是因為剛剛我們執行 `git reset --hard "HEAD^"` 這個動作，把 `HEAD` 指向的位址改到了前一個版本 ( `HEAD^` )，所以你打 `git log` 就看不到這個版本了。

事實上，原本你感覺被刪除的版本，其實一直儲存在 Git 的物件儲存區(object storage)裡，也就是這筆資料一直躺在 `.git\objects\` 目錄下。我們還是可以用 `git show 83a841` 取得該版本 ( 即 commit 物件 ) 的詳細資料：

![image](https://f.cloud.github.com/assets/88981/1360770/03ef0aa8-37fc-11e3-8648-5aa7c3f0afab.png)

刪除最近一次的版本，但保留最後一次的變更
------------------------------------

還記得嗎？無論你對 Git 儲存庫做了什麼事，都是可以還原的，只要執行 `git reset --hard ORIG_HEAD` 即可。

![image](https://f.cloud.github.com/assets/88981/1360806/98ebe0b8-37fc-11e3-9e3e-c1a0d108a907.png)

另一個刪除版本的技巧，則是「刪除最近一次的版本紀錄，但留下最後一次版本變更的異動內容」，這時你可以執行 `git reset --soft "HEAD^"` 達成這個任務：

![image](https://f.cloud.github.com/assets/88981/1360829/e4dfc9e4-37fc-11e3-8a04-d54cbeaa2600.png)

這代表著，你可以保留最後一次的變更，再加上一些變更後，重新執行 `git commit` 一次，並重新設定一個新的紀錄訊息。

重新提交一次最後一個版本 (即 `HEAD` 版本)
-----------------------------------------

如果你發現不小心執行了 `git commit` 動作，但還有些檔案忘了加進去 (`git add [filepath]`) 或只是紀錄訊息寫錯，想重新補上的話，直接執行 `git commit --amend` 即可。這個動作，會把目前紀錄在索引中的變更檔案，全部添加到當前最新版之中，並且要求你修改原本的紀錄訊息。

我們再執行一次 `git reset --hard ORIG_HEAD` 復原到原本的狀態。

底下我試著多新增一個 `c.txt` 檔案上去，然後直接執行 `git commit --amend` 命令，這時會跳出指定的文字編輯器進行編輯，且預設會把目前這次的訊息也給填上，你只要修改一下就可以了

![image](https://f.cloud.github.com/assets/88981/1360911/26724278-37fe-11e3-8c42-51eae03df019.png)

我把紀錄訊息修改成以下文字，並且存檔後退出，版本就會建立完成：
	
	Add b.txt!
	Add c.txt!

執行的結果如下，但最值得注意的是，最新版的 `HEAD` 已經是完全不同的 commit 物件了，所以用 `git log` 所看到的 commit 物件絕對名稱跟之前已經不一樣了。

![image](https://f.cloud.github.com/assets/88981/1360945/d966842a-37fe-11e3-83f6-c36a7a7553e4.png)

今日小結
-------

今天簡單的學到如何對【最新版】(`HEAD`)進行版本的變更，大多用在不小心 `git commit` 錯的情況，事實上還會有更多調整版本歷史紀錄的方式，這些會在之後的文章中出現。

我重新整理一下本日學到的 Git 指令與參數：

* git reset --hard "HEAD^"
* git reset --soft "HEAD^"
* git reset --hard ORIG_HEAD
* git commit --amend 

參考連結
-------

* [git-reset(1) Manual Page](https://www.kernel.org/pub/software/scm/git/docs/git-reset.html)


第 19 天：設定 .gitignore 忽略清單
========================================================

在開發專案時，工作目錄下可能經常會有新的檔案產生 (可能是透過 Visual Studio 工具產生的那些暫存檔案或快取檔案)，可能有許多檔案並不需要列入版本控管，所以必須要排除這些檔案，我們稱為「忽略清單」。

關於 .gitignore 檔案
--------------------------

在 Git 裡面，是透過 `.gitignore` 檔案來進行定義「忽略清單」，主要的目的是排除一些不需要加入版控的檔案，列在裡面的檔名或路徑 (可包含萬用字元)，都不會出現在 `git status` 的結果中，自然也不會在執行 `git add` 的時候被加入。不過，這僅限於 `Untracked file` 而已，那些已經列入版控的檔案 (`Staged file`)，不受 `.gitignore` 檔案控制。


透過 GitHub 建立預設的忽略清單
-----------------------------

如果你曾經在 GitHub 建立過專案，可能會用過這個功能，就在建立新的儲存庫(Repository)時，可以讓你選擇 GitHub 預先幫你定義好的忽略清單，這個忽略清單其實就只是一個檔案而已，其檔名為 `.gitignore`，並預設置於專案跟目錄下。

![image](https://f.cloud.github.com/assets/88981/1361075/b64e631a-3801-11e3-8d87-cf94af821bc9.png)

我們以上圖這個 CSharp 專案為例，建立完成後，在儲存庫中就會出現一個預設的 `.gitignore` 檔案：

![image](https://f.cloud.github.com/assets/88981/1361119/44df66e2-3802-11e3-82de-2b149bb0a717.png)

我們可以看看其內容：[https://github.com/doggy8088/sandbox-csharp/blob/master/.gitignore](https://github.com/doggy8088/sandbox-csharp/blob/master/.gitignore)
	
	# Build Folders (you can keep bin if you'd like, to store dlls and pdbs)
	[Bb]in/
	[Oo]bj/
	
	# mstest test results
	TestResults
	
	## Ignore Visual Studio temporary files, build results, and
	## files generated by popular Visual Studio add-ons.
	
	# User-specific files
	*.suo
	*.user
	*.sln.docstates
	
	# Build results
	[Dd]ebug/
	[Rr]elease/
	x64/
	*_i.c
	*_p.c
	*.ilk
	*.meta
	*.obj
	*.pch
	*.pdb
	*.pgc
	*.pgd
	*.rsp
	*.sbr
	*.tlb
	*.tli
	*.tlh
	*.tmp
	*.log
	*.vspscc
	*.vssscc
	.builds
	
	# Visual C++ cache files
	ipch/
	*.aps
	*.ncb
	*.opensdf
	*.sdf
	
	# Visual Studio profiler
	*.psess
	*.vsp
	*.vspx
	
	# Guidance Automation Toolkit
	*.gpState
	
	# ReSharper is a .NET coding add-in
	_ReSharper*
	
	# NCrunch
	*.ncrunch*
	.*crunch*.local.xml
	
	# Installshield output folder 
	[Ee]xpress
	
	# DocProject is a documentation generator add-in
	DocProject/buildhelp/
	DocProject/Help/*.HxT
	DocProject/Help/*.HxC
	DocProject/Help/*.hhc
	DocProject/Help/*.hhk
	DocProject/Help/*.hhp
	DocProject/Help/Html2
	DocProject/Help/html
	
	# Click-Once directory
	publish
	
	# Publish Web Output
	*.Publish.xml
	
	# NuGet Packages Directory
	packages
	
	# Windows Azure Build Output
	csx
	*.build.csdef
	
	# Windows Store app package directory
	AppPackages/
	
	# Others
	[Bb]in
	[Oo]bj
	sql
	TestResults
	[Tt]est[Rr]esult*
	*.Cache
	ClientBin
	[Ss]tyle[Cc]op.*
	~$*
	*.dbmdl
	Generated_Code #added for RIA/Silverlight projects
	
	# Backup & report files from converting an old project file to a newer
	# Visual Studio version. Backup files are not needed, because we have git ;-)
	_UpgradeReport_Files/
	Backup*/
	UpgradeLog*.XML

這些內容，真的就是在用 Visual Studio 寫 CSharp 專案時常見的「忽略清單」，非常具有實用價值，如果各位還有一些額外的檔案名稱或路徑要加入，也可以自行添加在這個檔案裡面。

參考其他程式語言的 `.gitignore` 內容範本
----------------------------------------

在 GitHub 上面，事實上還提供了很多其他開發環境所需的 `.gitignore` 範本，也都非常值得參考：

![image](https://f.cloud.github.com/assets/88981/1361211/ccff63fa-3803-11e3-9ece-2652ff9fa7f5.png)


今日小結
-------

今天的 `.gitignore` 檔案，我們幾乎每個專案都會用到，算是使用 Git 時一個必備的重要檔案。

參考連結
-------

* [gitignore(5) Manual Page](http://git-scm.com/docs/gitignore)
* [請勿將某些檔案類型的檔案簽入到 Subversion 版本庫 (二版)](http://blog.miniasp.com/post/2012/03/30/Do-not-commit-these-file-type-into-subversion-repository-2.aspx)





第 21 天：修正 commit 過的版本歷史紀錄 Part 3
=============================================================

在版本控管過程中，還有個常見的狀況，那就是當你在一個分支中開發了一段時間，但後來決定整個分支都不要了，不過當中卻有幾個版本還想留下，這時要刪除分支也不是，把這個分支合併回來也不是，那該怎麼辦呢？本篇文章將說明你該如何利用 `git cherry-pick` 指令「手動挑出」你想套用的變更。

準備本日練習用的版本庫
----------------------

在開始說明前，我們一樣先用以下指令建立一個練習用的工作目錄與本地儲存庫。文章看到這裡，想必各位看到指令應該都知道在做什麼事了吧。我們在一開始建立 2 個版本後，就建立了一個 `branch1` 分支，然後在分支裡建立了三個版本，其中一個版本為新增一個 `b.txt` 檔案，最後我們在切換回 `master` 分支，在新增一個變更：

	mkdir git-cherry-pick-demo
	cd git-cherry-pick-demo
	git init
	
	echo 1 > a.txt
	git add .
	git commit -m "Initial commit (a.txt created)"
	
	echo 2 > a.txt
	git add .
	git commit -m "Update a.txt to 2!"
	
	git checkout -b branch1
	
	echo 3 > a.txt
	git add .
	git commit -m "Update a.txt to 3!"
	
	echo b > b.txt
	git add .
	git commit -m "Add b.txt!"
	
	echo 4 > a.txt
	git add .
	git commit -m "Update a.txt to 4!"
	
	git checkout master

	echo 3 > a.txt
	git add .
	git commit -m "Update a.txt to 3!"


![image](https://f.cloud.github.com/assets/88981/1371480/0de9d178-3a3b-11e3-8085-c19922bd3701.png)

如果我們用 SourceTree 查看儲存庫的 commit graph (版本線圖) 的話，可以看到如下圖藍色的部分是我們 `master` 分支的變化，一共三個版本。紅色是 `branch1` 的分支，如果僅以這個分支來看也有三個版本。

![image](https://f.cloud.github.com/assets/88981/1371483/2d64014a-3a3b-11e3-8cae-f4703de8ef28.png)


使用 `git cherry-pick` 命令的注意事項
---------------------------------------

首先，你的「工作目錄」必須是乾淨，工作目錄下的「索引」不能有任何準備要 commit 的檔案 (staged files) 在裡面，否則將會無法執行。


使用 `git cherry-pick` 命令
-----------------------------

使用 `git cherry-pick` 跟使用 `git revert` 非常相似，也是讓你「挑選」任意一個或多個版本，然後套用在目前分支的最新版上，但主要差異則在於「`git revert` 執行的是相反的合併，而 `git cherry-pick` 則是重新套用完全相同的變更」，但一樣都是透過「合併」的方式進行，所以本篇文章我不會做太多類似的相關練習，而是專注在講解兩種指令上的差異。

**註**：`cherry-pick` 的英文是「撿櫻桃」的意思，代表你可以從其他籃子(分支)「挑」一些好的櫻桃到自己的籃子(分支)裡！

各位在使用 `git cherry-pick` 命令時，最好搭配 SourceTree 等 GUI 工具，查看你想要「挑選」出來的版本，然後套用在目前的分支上 (當然是套用在目前的 `HEAD` 版本之後)。

目前我們位於 `master` 分支上，若要查詢 `branch1` 的所有紀錄，我們執行 `git log branch1` 即可 (如下圖加上 `-4` 代表僅顯示前 4 筆紀錄)：

![image](https://f.cloud.github.com/assets/88981/1371642/b7519504-3a3e-11e3-8e23-12ce292ef2ca.png)

今天我想套用 `branch1` 的 `dc07017  Add b.txt!` 這個版本到目前的 `master` 版本上，可以執行 `git cherry-pick dc07017` 命令，若成功執行，則會在目前的 `master` 分支建立一個新版本。

![image](https://f.cloud.github.com/assets/88981/1371662/25e2fc60-3a3f-11e3-9854-5f5d2dc63aba.png)
 
不過，與 `git revert` 最大的不同之處，就在於執行完 `git cherry-pick` 命令後，其建立的版本訊息，將會與你指定挑選的那些版本一模一樣，其中包括 **Author** 與 **Date** 欄位，都會一模一樣，並不會用你在選項設定中指定的 `user.name` 與 `user.email` 參數。這點你必須特別注意！


使用 `git cherry-pick` 命令的其他參數
---------------------------------------

你可以選擇加上 `-x` 參數在指令列上，就會像 `git revert` 那樣，自動加上 `(cherry picked from commit dc070173c8d087b4e65084653e31b81910f3f2e5)` 的訊息，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1371730/1a7ff2ea-3a41-11e3-917c-160c53fd7d01.png)

不過，做這個動作之前也請先思考，你這次挑選的版本是不是只有「本地才有的分支」上挑選的，如果是的話，這樣的紀錄可能會造成其他人的混淆，因為他們查不到該版本的任何資訊。這在使用遠端儲存庫的情境比較會碰到。

如果希望在建立版本前先編輯訊息，那麼你可以輸入 `git cherry-pick dc07017 -e` 指令。

如果你不想建立版本，僅套用其變更，那麼你可以執行 `git cherry-pick dc07017 -n` 指令，這樣就不會自動建立版本，你可以在加上自己的修改後，執行 `git commit` 建立版本。透過 `-n` 參數，這次建立的版本就會留下自己的 Author & Date 資訊！


今日小結
-------

今天大家學到如何「撿櫻桃」的技巧，不過我沒辦法教你「怎樣挑出好的櫻桃」，這就要問你自己才知道了！ :-)

我重新整理一下本日學到的 Git 指令與參數：

* git reset --hard "HEAD~1"
* git cherry-pick [commit_id]
* git cherry-pick [commit_id] -e
* git cherry-pick [commit_id] -x
* git cherry-pick [commit_id] -n



第 22 天：修正 commit 過的版本歷史紀錄 Part 4 (Rebase)
======================================================================

我們之前已經講了三種不同的修正版本的方法，嚴格上來說 `git revert` 與 `git cherry-pick` 並不算「修正版本歷史紀錄」，而是套用先前曾經 commit 過的版本，看是「重新套用」或「反向套用」的差別而已。本篇文章將要來說明 Git 中的 Rebase 機制，這個所謂的 Rebase 機制就是真的用來修改 commit 紀錄的功能了，其功能重要而且強大。

準備本日練習用的版本庫
----------------------

我們一樣先用以下指令建立一個練習用的工作目錄與本地儲存庫 (一樣先切換到 `C:\` 然後複製貼上就會自動建立完成)：
		
	mkdir git-rebase-demo
	
	cd git-rebase-demo
	git init
	
	echo 1 > a.txt
	git add .
	git commit -m "Initial commit (a.txt created)"
	
	ping 127.0.0.1 -n 2 >nul
	
	echo 2 > a.txt
	git add .
	git commit -m "Update a.txt to 2"
	
	ping 127.0.0.1 -n 2 >nul
	
	:: 建立並切換到 branch1 分支
	git checkout -b branch1
	
	echo b > b.txt
	git add .
	git commit -m "Add b.txt"
	
	echo c > c.txt
	git add .
	git commit -m "Add c.txt"
	
	echo 333 > c.txt
	git add .
	git commit -m "Update c.txt to 333"
	
	echo d > d.txt
	git add .
	git commit -m "Add d.txt"
	
	ping 127.0.0.1 -n 2 >nul
	
	:: 切換到 master 分支
	git checkout master
	
	echo 3 > a.txt
	git add .
	git commit -m "Update a.txt to 3"

我們用 SourceTree 查看儲存庫的 commit graph (版本線圖) 如下：

![image](https://f.cloud.github.com/assets/88981/1379049/c6609d70-3ae2-11e3-89e5-b011f0ed15e5.png)


使用 `git rebase` 命令的注意事項
---------------------------------

首先，你的「工作目錄」必須是乾淨，工作目錄下的「索引」不能有任何準備要 commit 的檔案 (staged files) 在裡面，否則將會無法執行。

![image](https://f.cloud.github.com/assets/88981/1379084/f33a2310-3ae3-11e3-83c3-6dde9af36b4c.png)

再來，也是最重要的，如果你的分支是從遠端儲存庫下載回來的，請千萬不要透過 Rebase 修改版本歷史紀錄，否則你將會無法將修改過後的版本送到遠端儲存庫！

Rebase 是什麼？
-----------------

Rebase 是 "Re-" 與 "Base" 的複合字，這裡的 "Base" 代表「基礎版本」的意思，表示你想要重新修改特定分支的「基礎版本」，把另外一個分支的變更，當成我這個分支的基礎。

我們現在就來做一個簡單的 Rebase 示範，我們大概做幾件事：

1. 切換至 `branch1` 分支： `git checkout branch1`
2. 然後執行 Rebase 動作，把 `master` 當成我們的基礎版本： `git rebase master`

![image](https://f.cloud.github.com/assets/88981/1379140/6912217c-3ae5-11e3-85f2-2a6bdaf4e509.png)

請注意執行完 `git rebase master` 之後的顯示訊息，他說先將我們 `branch1` 分支的最新版本(head)倒帶(rewind)到跟 `master` 一樣的分支起點(rewinding head)，然後再重新套用(replay)指定的 `master` 分支中所有版本。英文的 **on top of it** 代表的是讓 `branch1` 分支原本的變更套用在 `master` 上面，所謂的「上面」代表的是先套用 `master` 的版本，然後才套用 `branch1` 的版本 (請見上圖的 `Applying:` 那幾行)。

我們看看套用完之後從 SourceTree 看到的版本線圖(commit graph)，你看看這是不是很神奇，版本線圖變成一直線了：

![image](https://f.cloud.github.com/assets/88981/1379156/0766ed80-3ae6-11e3-9700-f540727d77ef.png)

各位看官，看到上面的版本線圖，你會不會覺得「分支」的感覺不見了呢？事實上，分支並沒有改變，而是這幾個版本的「套用順序」被修改了。目前這張圖所代表的意思，就如同以下指令的執行順序：

1. 建立 Initial commit (a.tx created)，同時預設建立 `master` 分支
2. 建立 Update a.txt to 2
3. 建立 Update a.txt to 3
4. 建立並切換至 `branch1` 分支
5. 然後不斷 commit 到 Add d.txt 這個版本

所以，這其實還是「兩個分支」喔，並沒有被合併成一個！**千萬別認為**這張圖只有一條線，所以只有一個分支。

有分支，就有合併，現在的你，如果想要把 `branch1` 的變更，套用到 `master` 分支上，在使用過 Rebase 之後，你會有兩種合併的方式：

### 1. 透過一般合併指令，並觸發 Git 的快轉機制 (Fast-forward)

先切換到 `master` 分支，然後直接執行 `git merge branch1`，這時會引發 Git 的快轉機制(Fast-forward)。所謂的「快轉機制」，就是 Git 得知這個合併的過程，其實會依序套用 `branch1` 原本就有的變更，所以在合併的時候會直接修改 `master` 分支的 `HEAD` 參照絕對名稱，直接移動到 `branch1` 的 `HEAD` 那個版本。
	
![image](https://f.cloud.github.com/assets/88981/1379203/be448908-3ae7-11e3-91ab-c5da46871aaa.png)
	
最後我們得到的線圖還是一直線，但你可以看到 `master` 的分支已經移動到跟 `branch1` 一樣了。如下圖示：
	
![image](https://f.cloud.github.com/assets/88981/1379219/2b1501a2-3ae8-11e3-9155-1a53aad8e2ff.png)

### 2. 透過 `--no-ff` 參數，停用 Git 的快轉機制 

先切換到 `master` 分支，然後直接執行 `git merge branch1 --no-ff` 即可。

![image](https://f.cloud.github.com/assets/88981/1379253/1ee9a6b6-3ae9-11e3-93c3-68ca173b4631.png)

當你合併時指定停用 Git 的快轉機制，那就代表「不允許快轉」的意思。也代表著，他會強迫你打算合併的那個 `branch1` 先建立一個分支，然後最後再合併回 `master`，也代表著我們在次修變更了 `branch1` 的版本線圖。最終，你看到的版本線圖應該會長成以下這個樣子，不是比剛剛一直線的版本線圖還漂亮呢！ :-)

![image](https://f.cloud.github.com/assets/88981/1379268/9af439b0-3ae9-11e3-8268-9931547b87d0.png)

最後，如果你的 `branch1` 用不到的話，就可以把這個分支給刪除： `git branch -d branch1`

![image](https://f.cloud.github.com/assets/88981/1379276/e4473bbc-3ae9-11e3-9a33-61a80ba11430.png)

最終我們的版本線圖如下：

![image](https://f.cloud.github.com/assets/88981/1379282/037ff4ec-3aea-11e3-99ba-28e585f7a856.png)

我們來比對一下，如果用我們最剛開始的建立的初始版本進行合併的話，線圖會長得像以下這樣。各位有沒有發現，我們原本的 `branch1` 是從 **Update a.txt to 2** 這一版開始分支的，經過我們透過 Rebase 之後，分支的起點不太一樣了，而是改由 **Update a.txt to 3** 這個分支開始，是不是很有趣呢！

![image](https://f.cloud.github.com/assets/88981/1379289/5f4083b4-3aea-11e3-9045-ba3b3cddc7c1.png)


今日小結
-------

第一次接觸 Rebase 的人，或許會覺得很抽象，各位必須細心品味，才能真正感受到 Rebase 帶來的強大威力。之後的文章裡，我還會更加詳細的介紹 Rebase 的進階用法。

我重新整理一下本日學到的 Git 指令與參數：

* git rebase master
* git merge branch1
* git branch -d branch1


第 23 天：修正 commit 過的版本歷史紀錄 Part 5
============================================================

我們上一篇文章談到的 Rebase 是用來將現有的兩個分支進行「重新指定基礎版本」，執行 Rebase 之後，也會改掉原本分支的起點 (分支點移動了)，所以導致版本線圖發生變化。不過 Rebase 可以做到的能力不只這樣，他還能用來修改特定分支線上任何一個版本的版本資訊。

準備本日練習用的版本庫
-------------------------

我們一樣先用以下指令建立一個練習用的工作目錄與本地儲存庫 (一樣先切換到 `C:\` 然後複製貼上就會自動建立完成)：
		
	mkdir git-rebase-demo
	
	cd git-rebase-demo
	git init
	
	echo 1 > a.txt
	git add .
	git commit -m "Initial commit (a.txt created)"
	
	ping 127.0.0.1 -n 2 >nul
	
	echo 2 > a.txt
	git add .
	git commit -m "Update a.txt to 2"
	
	ping 127.0.0.1 -n 2 >nul
	
	:: 建立並切換到 branch1 分支
	git checkout -b branch1
	
	echo b > b.txt
	git add .
	git commit -m "Add b.txt"
	
	echo c > c.txt
	git add .
	git commit -m "Add c.txt"
	
	echo 333 > c.txt
	git add .
	git commit -m "Update c.txt to 333"
	
	echo d > d.txt
	git add .
	git commit -m "Add d.txt"
	
	ping 127.0.0.1 -n 2 >nul
	
	:: 切換到 master 分支
	git checkout master
	
	echo 3 > a.txt
	git add .
	git commit -m "Update a.txt to 3"

**註**：上述指令中的 `ping  127.0.0.1 -n 2 >nul` 主要是用到了 [如何在批次檔(Batch)中實現 sleep 命令讓任務暫停執行 n 秒](http://blog.miniasp.com/post/2009/06/24/Sleep-command-in-Batch.aspx) 文章中提到的技巧。

我們用 SourceTree 查看儲存庫的 commit graph (版本線圖) 如下：

![image](https://f.cloud.github.com/assets/88981/1379049/c6609d70-3ae2-11e3-89e5-b011f0ed15e5.png)


使用 `git rebase` 命令的注意事項
---------------------------------

這件事還是必須重申一次！首先，你的「工作目錄」必須是乾淨，工作目錄下的「索引」不能有任何準備要 commit 的檔案 (staged files) 在裡面，否則指令將會無法執行。

![image](https://f.cloud.github.com/assets/88981/1379084/f33a2310-3ae3-11e3-83c3-6dde9af36b4c.png)

再來，也是最重要的，如果你的分支是從遠端儲存庫下載回來的，請**千萬不要**透過 Rebase 修改版本歷史紀錄，否則你將會無法將修改過後的版本送到遠端儲存庫！

Rebase 能做的事
-----------------

上一篇文章講的，你可以將某個分支當成自己目前分支的「基礎版本」。除了這件事以外，你還可以用來修改某個分支中「特定一段」歷程的紀錄，你可以做的事情包括：

1. 調換 commit 的順序
2. 修改 commit 的訊息
3. 插入一個 commit
4. 編輯一個 commit
5. 拆解一個 commit
6. 壓縮一個 commit，且保留訊息紀錄
7. 壓縮一個 commit，但丟棄版本紀錄
8. 刪除一個 commit

這八件事，可以完整看出 Rebase 修正歷史版本紀錄的強大威力，接下來我們就逐一介紹如何好好利用 Rebase 幫我們修訂版本。

1. 調換 commit 的順序
-----------------------

首先，我們先切換到 `branch1` 分支 ( `git checkout branch1` )

![image](https://f.cloud.github.com/assets/88981/1382124/4bd35d66-3b2a-11e3-82fa-62322f9d68f7.png)

到 SourceTree 查看版本線圖，然後我們先決定這個分支中想要執行 Rebase 的起點 (不一定要是分支的起始點，任何一版都可以)，決定之後，直接在 SourceTree 複製該版本的**絕對名稱**(也就是以 SHA1 雜湊過的 Git 物件ID)。從下圖你可以看到，我們先在該版本按下滑鼠右鍵，然後再點選 **Copy SHA to Clipboard** 即可將 id 複製到剪貼簿中：

![image](https://f.cloud.github.com/assets/88981/1382144/9c617772-3b2a-11e3-9491-bd022904ab6b.png)

然後我們執行 `git rebase 92f937a190e1fca839eed4f51d7f7199b617e3d4 -i`
**注意**: 這裡的 `92f937a190e1fca839eed4f51d7f7199b617e3d4` 跟你自己建立的可能不一樣，請不要照抄。

接著會跳出編輯器，並且讓你編輯一系列「指令」，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1382203/6bdc8bd6-3b2b-11e3-928f-fc129ffc0e68.png)

你如果什麼都不改，就是執行這一系列 `pick` 等動作，這裡必須先讓各位瞭解的是這些指令的格式，與他的順利代表的意義。

我們先來看第一行，區分成三個欄位，分別以「空白字元」間隔，分別如下：

1. `pick` 代表的是「命令」，底下註解的部分有一系列「命令」的名稱與簡寫，你寫 `p` 與 `pick` 都是一樣的意思。
2. `d86532d` 代表的是要使用的 commit 物件編號(絕對名稱)。
3. 剩下的文字則是這個版本的紀錄訊息摘要。

如果你有看過【**第 22 天：修正 commit 過的版本歷史紀錄 Part 4**】這篇文章，你應該會知道執行 Rebase 的時候，會先將我們目前 `branch1` 分支的最新版本(head)倒帶(rewind)到你這次指定的分支起點(rewinding head)，在這個例子裡，我們指定的分支起點就是 `92f937a190e1fca839eed4f51d7f7199b617e3d4` 這個節點。

這時我們用 `git log` 查看一下目前的版本紀錄，我們指定的那個版本，並不在我們的 Rebase 指令清單中。該指令清單，由上至下分別是「最舊版」到「最新版」的順序，跟我們用 `git log` 執行的顯示順序剛好相反：

![image](https://f.cloud.github.com/assets/88981/1382307/fb276a6c-3b2c-11e3-87ef-bacff67e7656.png)
	
我們再重看一次這幾個版本如下：

	pick d86532d Add b.txt
	pick 22e1885 Add c.txt
	pick bf40b2c Update c.txt to 333
	pick 5027152 Add d.txt

這裡的 `pick` 代表的功能是 `use commit`，也就是我們要用這個版本來 commit 新版本。也就是上一篇文章講到的**重新套用**(replay)這個字，所以這幾個指令，就是讓你在分支「倒帶」之後，重新用這幾個版本套用一次版本變更，而且重新套用的過程會沿用當時版本的變更紀錄。

現在我們先來嘗試「**調換 commit 的順序**」這個命令。

若要完成「**調換 commit 的順序**」的任務，你只要很簡單的修改這份文字檔，把版本的前後順序對調即可，例如我們修改成：

	pick 22e1885 Add c.txt
	pick d86532d Add b.txt
	pick bf40b2c Update c.txt to 333
	pick 5027152 Add d.txt

然後存檔退出，我們看看指令最後的執行結果為何，你可以發現，我們這兩個版本真的順序對調了：

![image](https://f.cloud.github.com/assets/88981/1382455/d491943e-3b2e-11e3-9558-024cd74848a8.png)

這裡有一點你必須特別注意，那就是從 `92f937a190e1fca839eed4f51d7f7199b617e3d4` 這個版本開始，所有後續版本的 commit 絕對名稱全部都不一樣了，這代表我們在 Rebase 的過程會重新建立許多新的 commit 物件。那麼舊的物件到哪裡去了呢？真相是，這些以前的版本全部都還在，只是你找不到罷了，全都躺在 Git 物件儲存庫中，只要你知道這些版本(也就是 commit 物件)的絕對名稱，你就可以隨時取出！(請回憶一下 `git reflog` 命令)

我們從 SourceTree 裡面看一下版本線圖，感覺上跟上面那張圖好像差很多，但其實只有這兩個版本調換而已，線圖不太一樣的原因是時間序改變了，我想這應該是 SourceTree 的顯示邏輯跟時間序有關，才會讓這線圖變得跟之前差這麼多，初學者可別弄亂了。

![image](https://f.cloud.github.com/assets/88981/1382662/5b964dba-3b31-11e3-8ddd-0ca2b4bf36ff.png)


2. 修改 commit 的訊息
-----------------------

修改曾經 commit 過的訊息，只要稍加修改 Rebase 的命令即可，我們先看看目前的版本紀錄：

![image](https://f.cloud.github.com/assets/88981/1382707/e6e4b582-3b31-11e3-9c02-e366e51ac489.png)

如果我們打算把下圖標示紅線的版本訊息修改為 `Update: c.txt is changed to 333` 文字的話，我們先執行跟上個例子相同的指令：

	git rebase 92f937a190e1fca839eed4f51d7f7199b617e3d4 -i

然後會開啟文字編輯器，此時的內容應該如下：

	pick 3654a50 Add c.txt
	pick 0341056 Add b.txt
	pick 6883d87 Update c.txt to 333
	pick 36ed38f Add d.txt

我們想修改 `6883d87` 這個版本的訊息，只要把這一行前面的 `pick` 改成 `reword` 即可。修改完後的文字如下：

	pick 3654a50 Add c.txt
	pick 0341056 Add b.txt
	reword 6883d87 Update c.txt to 333
	pick 36ed38f Add d.txt

然後存檔退出，接著 Git 會開始重新 `pick` 這些版本進行套用，但套用到 `reword` 這個命令時，會重新再開啟一次文字編輯器，讓你可以在此時變更版本訊息文字，這時我們直接改成 `Update: c.txt is changed to 333` 文字後存檔退出，接著就會直接套用完後續的版本。

![image](https://f.cloud.github.com/assets/88981/1382771/c12d1e78-3b32-11e3-964e-c14ae43ab26c.png)

我們最後再用 `git log` 查看版本紀錄，發現該版本的訊息確實已經變更為我們修改的那段文字。而且該版本與後續的版本 commit 物件編號也會不一樣，不一樣代表這兩個是新的 commit 物件。

![image](https://f.cloud.github.com/assets/88981/1382783/f1c83b30-3b32-11e3-9154-178fd8b2d345.png)


3. 插入一個 commit
-----------------------

接著我們再執行一次 `git rebase 92f937a190e1fca839eed4f51d7f7199b617e3d4 -i` 指令，目前的 Rebase 指令如下：
	
	pick 3654a50 Add c.txt
	pick 0341056 Add b.txt
	pick a9eca79 Update: c.txt is changed to 333
	pick 7aacc1b Add d.txt

如果我們想在 `a9eca79` 版本之後「插入一個新版本」，只要在  `a9eca79` 這行前面的 `pick` 改成 `edit` 即可讓 Rebase 在重新套用的過程中「暫停」在這個版本，然後讓你可以對這個版本進行「編輯」動作：

	pick 3654a50 Add c.txt
	pick 0341056 Add b.txt
	edit a9eca79 Update: c.txt is changed to 333
	pick 7aacc1b Add d.txt

然後存檔退出，接著 Git 會開始執行套用，等執行到 `a9eca79` 這個版本時，套用的動作會被中斷，並提示你可以執行 `git commit --amend` 重新執行一次 commit 動作：

![image](https://f.cloud.github.com/assets/88981/1382845/c5376040-3b33-11e3-9305-fb2626f452c3.png)

因為我們的目的是希望在 `a9eca79` 這個版本之後「插入」一個新版本，所以我們可以直接在這個階段「建立新版本」！

例如我想新增一個版本是「新增一個 `z.txt` 檔案」，我可以這麼做：

![image](https://f.cloud.github.com/assets/88981/1382885/62a3baea-3b34-11e3-97b0-84abccbae534.png)

我們執行 `git rebase --continue` 讓 Rebase 指令繼續完成。最終完成的畫面如下圖示：

![image](https://f.cloud.github.com/assets/88981/1382898/8abab358-3b34-11e3-8dc5-191281bbd156.png)

最後我們用 `git log` 查看一下，確實我們剛剛建立的 `Add z.txt` 這個版本已經成功被建立！

![image](https://f.cloud.github.com/assets/88981/1382902/aa2557b6-3b34-11e3-9804-18b42b8e498e.png)


4. 編輯一個 commit
-----------------------

編輯一個 commit 的動作，就如【插入一個 commit】的示範一樣，你只要先把該版本修正為 `edit` 命令，就可以利用 `git commit --amend` 重新執行一次 commit 動作，就等同於編輯了某個版本的紀錄。


5. 拆解一個 commit
-----------------------

拆解一個 commit 紀錄，代表的是你想要把「某一個 commit 紀錄」變成兩筆紀錄，其實這個動作跟【插入一個 commit】幾乎是完全一樣的。差別僅在於你只要把編輯中的那個版本，將某些檔案從「索引」狀態中移除，然後執行 `git commit --amend` 就可以建立一個新版。然後再執行 `git add .` 重新把這些檔案加入，然後再執行 `git commit`，即可將原本一個版本的變更，變成兩個版本。


6. 壓縮一個 commit，且合併訊息紀錄
----------------------------------

所謂的「壓縮一個 commit 版本」，代表你這幾個版本中，有個版本訊息有點多餘，而且覺得可以把這個版本的變更合併到「上一個版本」(parent commit)中，那麼你可以修改 Rebase 指令，把 `pick` 修改為 `squash` 即可。

透過壓縮的方式，被套用 `squash` 命令的版本，其「版本紀錄訊息」會被自動加入到「上一個版本」的訊息中。


7. 壓縮一個 commit，但丟棄版本紀錄
----------------------------------

如果你只想合併兩個版本的變更，但不需要合併紀錄訊息的話，那麼你可以修改 Rebase 指令，把 `pick` 修改為 `fixup` 即可。


8. 刪除一個 commit
-----------------------

刪除一個 commit 版本是最簡單的，只要直接把要刪除的這幾行 `pick` 命令給移除即可。


今日小結
-------

看到這裡，你應該能感受到 Rebase 的強大威力。透過 `git rebase` 可以有效幫你「重整版本」，不但讓你的 Git 版本記錄更加易懂，也更有邏輯。這樣做的好處，在多人開發的 Git 專案中尤其明顯，為了你的團隊成員著想，各位不得不學啊！

我重新整理一下本日學到的 Git 指令與參數：

* git rebase -i [commit_id]
* git commit --amend



第 24 天：使用 GitHub 遠端儲存庫 - 入門篇
========================================================

GitHub 是目前全世界最多人採用的 Git 線上管理平台，他包含了完整的 Git 遠端儲存庫實作，還有完整的議題追蹤機制與報表，更有成千上萬的開源碼專案都在 GitHub 進行 Git 版本控管。即便在我們公司，也有許多專案採用 GitHub 當成我們主要的 Git 平台。本篇文章主要帶大家上手 GitHub 最基本的使用方式。


我們先來說明在 GitHub 建立專案的兩種不同的方式。

在 GitHub 建立一個「**沒有版本**」的空白 Git 儲存庫
----------------------------------------------------

先登入 GitHub，再進入 GitHub 首頁： [https://github.com](https://github.com)

點選右上角你的使用者名稱進入個人首頁：

![image](https://f.cloud.github.com/assets/88981/1398954/a97150e8-3cad-11e3-9530-d1d0b662d91a.png)

切換到 **Repositories** 頁籤：

![image](https://f.cloud.github.com/assets/88981/1398964/d4e079e8-3cad-11e3-9efe-323928eb132b.png)

再點選右邊綠色的 **New** 按鈕，以建立一個你自己的 GitHub 專案 (包含 Git 遠端儲存庫)：

![image](https://f.cloud.github.com/assets/88981/1398972/f1717698-3cad-11e3-93c1-3b8eab6b63c6.png)

如果你要建立一個「**沒有版本**」的空白 Git 儲存庫，最重要的就是最下方的 **Initialize this repository with a README** 不要勾選，還有 **Add .gitignore** 與 **Add a licenes** 都保留預設的 **None** 選項：

![image](https://f.cloud.github.com/assets/88981/1398983/36b2c6e4-3cae-11e3-931b-c7261294c51d.png)

最後按下 **Create repository** 即可建立完成，當你建立起一個「**沒有版本**」的空白 Git 儲存庫之後，畫面最下方也提到了幾個讓你上傳本地 Git 儲存庫的指令教學，照著打就可以把本地儲存庫的變更上傳到 GitHub 的遠端儲存庫中。

![image](https://f.cloud.github.com/assets/88981/1399023/0e98aed4-3caf-11e3-9e22-e5d0d091d3b0.png)


在 GitHub 建立一個「**有初始化版本**」的 Git 儲存庫
----------------------------------------------------

建立一個「**有初始化版本**」的空白 Git 儲存庫，其實就是在 GitHub 建立專案時，勾選了一些初始化的檔案，在建立的過程 GitHub 會依據你所挑選的選項，先幫你建立好一個初始化的 Git 版本：

![image](https://f.cloud.github.com/assets/88981/1399056/e86bee3c-3caf-11e3-9dc2-d9f6a46720ef.png)

建立完成後，在 GitHub 上顯示的內容會不太一樣，因為你已經有一個 commit 版本在上面了：

![image](https://f.cloud.github.com/assets/88981/1399066/41f39644-3cb0-11e3-9549-737dddb29566.png)


將本地儲存庫的變更上傳到遠端儲存庫的方法
--------------------------------------

我有在【第 03 天：建立儲存庫】這篇文章中提到如何取得從 GitHub 建立的遠端儲存庫 (remote repository)，不過若要將本地變更送上 GitHub 則有好幾種不同的方式，其中包括：

1. 在 GitHub 建立一個「**沒有版本**」的空白 Git 儲存庫，然後透過 `git clone` 取得遠端儲存庫，再建立版本後上傳
2. 在 GitHub 建立一個「**沒有版本**」的空白 Git 儲存庫，然後直接將現有的本地 Git 儲存庫上傳到指定的 GitHub 專案
2. 在 GitHub 建立一個「**有初始化版本**」的 Git 儲存庫，然後透過 `git clone` 取得遠端儲存庫，再建立版本後上傳
3. 在 GitHub 建立一個「**有初始化版本**」的 Git 儲存庫，然後直接將現有的本地 Git 儲存庫上傳到指定的 GitHub 專案

以上就是我們首次使用 GitHub 時，最常見的四種上傳方式。嚴格說起來，上述四種上傳方式，應該只有兩種而已，也就是：

1. 透過 `git clone` 取得遠端儲存庫，再建立版本後上傳
2. 直接將現有的本地 Git 儲存庫上傳到指定的 GitHub 專案

為什麼我想猜成四個來講呢？主要有兩個原因：

1. 【透過 `git clone` 取得遠端儲存庫，再建立版本後上傳】的這種方式，因為「**沒有版本**」的空白 Git 儲存庫，連預設的 `master` 分支都沒有，所以用預設的指令無法上傳到遠端儲存庫。所以在指令操作上會有兩種用法。
2. 【直接將現有的本地 Git 儲存庫上傳到指定的 GitHub 專案】的這種方式，因為通常一個 Git 儲存庫只會有一個「初始 commit 物件」，如果你在本地儲存庫已經建立了幾個版本，代表在你的本地儲存庫中已經有了自己的「初始 commit 物件」，這將會與 GitHub 建立的「**有初始化版本**」的 Git 儲存庫相互衝突，所以上傳的指令也會有些不同。

以下我們先來說明【**透過 `git clone` 取得遠端儲存庫，再建立版本後上傳**】這個方法。


透過 `git clone` 取得遠端儲存庫，再建立版本後上傳
------------------------------------------------

這個方法最簡單，因為你還沒有本地儲存庫的存在，甚至連工作目錄都還沒有，所以我們直接利用 `git clone` 即可把專案下載。然而，在使用 GitHub 的時候，最簡單的方法就是利用 GitHub for Windows 工具。你只要點擊 **Clone in Desktop** 按鈕，即可自動啟動 GitHub for Windows 工具幫你下載 Git 專案：

* 「**沒有版本**」的空白 Git 儲存庫

	![image](https://f.cloud.github.com/assets/88981/1399201/d8d64cee-3cb2-11e3-89f9-3e3b7a5da8fa.png)

* 「**有初始化版本**」的 Git 儲存庫

	![image](https://f.cloud.github.com/assets/88981/1399187/9a5acf94-3cb2-11e3-8efe-b7c0bb029a5d.png)

你也可以直接複製 GitHub 提供的 URL 網址，然後利用 `git clone` 指令下載，例如：

![image](https://f.cloud.github.com/assets/88981/1399226/8618a2bc-3cb3-11e3-9af4-95135f7e16c7.png)

如果你用 `git clone https://github.com/doggy8088/sandbox-empty.git` 複製一個 「**沒有版本**」的空白 Git 儲存庫，將會得到一個 **warning: You appear to have cloned an empty repository.** 警告訊息，不過這不影響你上傳本地的變更。

如果你用 `git clone https://github.com/doggy8088/sandbox-initialized.git` 複製一個 「**有初始化版本**」的 Git 儲存庫，將會直接從 GitHub 下載擁有完整變更歷史的「遠端儲存庫」，所以你會看到有下載物件數量、壓縮、解壓縮等資訊。

我們以 `sandbox-empty` 這個專案為例，由於這是一個 「**沒有版本**」的空白 Git 儲存庫，在 GitHub 上的遠端儲存庫是完全空的，連預設的 `master` 分支都沒有，所以在下達 `git push` 指令時必須加上 `-u` 參數，才能成功地把本地儲存庫上傳到 GitHub 上的遠端儲存庫，其指令是 `git push -u origin master`

![image](https://f.cloud.github.com/assets/88981/1399428/8debd114-3cb6-11e3-8c69-3b0ac69a2ffd.png)

![image](https://f.cloud.github.com/assets/88981/1399635/82b629f4-3cb9-11e3-984e-2de0a2b0e650.png)

我們再以 `sandbox-initialized` 這個專案為例，由於這是一個  「**有初始化版本**」的 Git 儲存庫，在 GitHub 上的遠端儲存庫已經有一個版本，同時也建立好預設的 `master` 分支，所以在下達 `git push` 指令時可以不用加上 `-u` 參數，就成功地把本地儲存庫上傳到 GitHub 上的遠端儲存庫，其指令是 `git push origin master`

![image](https://f.cloud.github.com/assets/88981/1399497/b3e41966-3cb7-11e3-8488-8d19273c8cfd.png)

當你第二次建立版本時，直接執行 `git push` 就會自動上傳成功：

![image](https://f.cloud.github.com/assets/88981/1399536/40e0db7e-3cb8-11e3-8975-9f3eda701318.png)

![2013-10-24 10-27-32](https://f.cloud.github.com/assets/88981/1399616/497ff9e4-3cb9-11e3-8871-0a95a7890779.jpg)

不過，當你執行簡單版本的 `git push` 會出現一段提示，告訴你要設定 `push.default` 這個選項，因為這種簡寫的 `git push` 方法，Git 的預設行為將會在 Git 2.0 之後發生改變，建議你透過設定  `push.default` 選項的方式明確指定 push 的方法。詳細說明請參見 `git help config` 的說明文件，搜尋 `push.default` 即可找到相關說明。我建議各位設定成 `simple`，以利跟日後的 Git 指令列工具的預設值相同，指令如下：

	git config --global push.default simple

設定好之後，下次執行 `git push` 就不會再出現提示訊息了：

![image](https://f.cloud.github.com/assets/88981/1399690/433ae430-3cba-11e3-937b-65e97a6bd7a2.png)

之後的操作，在我們這兩個練習用的工作目錄都完全一樣。

![image](https://f.cloud.github.com/assets/88981/1399713/83498324-3cba-11e3-8e77-ec734c1a7c1c.png)


直接將現有的本地 Git 儲存庫上傳到指定的 GitHub 專案
------------------------------------------------

接下來我們再來說明【**直接將現有的本地 Git 儲存庫上傳到指定的 GitHub 專案**】這個方法。但由於練習用的 GitHub 專案已經被上傳一些物件，所以請各位重新再建立兩個新專案，分別是一個「**沒有版本**」的空白 Git 儲存庫，與另一個「**有初始化版本**」的 Git 儲存庫。

一個「**有初始化版本**」的 Git 儲存庫，專案名稱：`sandbox-empty2`
一個「**沒有版本**」的空白 Git 儲存庫，專案名稱：`sandbox-initialized2`

接著我們建立兩個本地儲存庫與工作目錄，指令如下：

	mkdir sandbox-empty2
	cd sandbox-empty2
	
	git init
	
	echo a > a.txt
	git add .
	git commit -m "Initial commit"
	
	cd ..
	mkdir sandbox-initialized2
	cd sandbox-initialized2
	
	git init
	
	echo a > a.txt
	git add .
	git commit -m "Initial commit"


我們先以 `sandbox-empty2` 專案為例，由於我們本地儲存庫跟 GitHub 上的遠端儲存庫完全沒有關聯，所以必須告訴 Git 遠端儲存庫在哪。這時我們可以輸入 `git remote add origin https://github.com/doggy8088/sandbox-empty2.git` 建立一個名為 `origin` 的參照名稱，並指向 `https://github.com/doggy8088/sandbox-empty2.git` 位址，也就是我們在 GitHub 上的遠端儲存庫位址。接著就跟我們先前講解的步驟一模一樣，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1399913/b33173f6-3cbc-11e3-8c00-d4b8aa6f904a.png)
 
接著我們再以 `sandbox-initialized2` 專案為例，請記得複製到正確的 URL 位址：

![image](https://f.cloud.github.com/assets/88981/1399935/f44c6ff8-3cbc-11e3-8f26-138754d32a3c.png)

然後輸入跟以上相同的指令 (記得改 URL 喔)：`git remote add origin https://github.com/doggy8088/sandbox-initialized2.git`

![image](https://f.cloud.github.com/assets/88981/1399985/a46a7e8e-3cbd-11e3-8520-2e1373cda574.png)

你可以發現，這次的 `git push` 動作被 GitHub 拒絕了！因為你不能把兩個完全無關的 Git 版本直接上傳到 GitHub 上的遠端儲存庫。

解決的方法很簡單，只要把遠端儲存庫的 `master` 分支，成功合併回我本地的分支，即可建立兩個不同版本庫之間的關聯，這樣你就可以把本地的 `master` 分支推送到 GitHub 上遠端儲存庫的 `master` 分支了。

將遠端儲存庫的 `master` 分支取回，並合併到本地儲存庫的 `master` 分支，有兩種方法：

1. 使用 `git pull origin master` 指令
2. 使用 `git fetch` 指令後再執行 `git merge origin/master` 合併動作 (這個方法會在後續的文章詳述)

成功執行的過程如下圖示：

![image](https://f.cloud.github.com/assets/88981/1400029/58742560-3cbe-11e3-8c2f-ed383371a1f4.png)


今日小結
-------

本篇文章完整的介紹如何將本地儲存庫上傳到 GitHub 上的遠端儲存庫，雖然過程有點麻煩，但如果你透過 GitHub for Windows 操作的話，要上傳到 GitHub 只要簡單的按下 **sync** 按鈕，就可以自動上傳了，連帳號密碼都不用輸入，這樣是不是簡單很多。 (^_^)

![image](https://f.cloud.github.com/assets/88981/1400097/7354ea80-3cbf-11e3-9b31-668364330afa.png)


我重新整理一下本日學到的 Git 指令與參數：

* git push origin master
* git push -u origin master
* git pull origin master
* git config --global push.default simple
* git push
* git fetch
* git merge origin/master



第 25 天：使用 GitHub 遠端儲存庫 - 觀念篇
========================================================

上一篇大家學會了如何下載遠端儲存庫 (`git clone`, `git pull`) 與上傳遠端儲存庫 (`git push`)，本篇文章來教大家認識遠端儲存庫的其他細節。


與遠端儲存庫有關的指令
---------------------

* `git clone`

	將**遠端儲存庫**複製到本地，並建立**工作目錄**與**本地儲存庫** (就是 `.git` 資料夾)

* `git pull`

	將遠端儲存庫的最新版下載回來，下載的內容包含完整的物件儲存庫(object storage)。並且將遠端分支合併到本地分支。 (將 `origin/master` 遠端分之合併到 `master` 本地分支)

	所以一個 `git pull` 動作，完全相等於以下兩段指令：

		git fetch 
		git merge origin/master

* `git push`

	將本地儲存庫中目前分支的所有相關物件**推送**到遠端儲存庫中。

* `git fetch`

	將遠端儲存庫的最新版下載回來，下載的內容包含完整的物件儲存庫(object storage)。
	這個命令**不包含**「合併」分支的動作。

* `git ls-remote`

	顯示特定遠端儲存庫的參照名稱。包含**遠端分支**與**遠端標籤**。


關於追蹤分支的概念
------------------

我們先前學習過關於「分支」的概念，不過僅限於｢本地分支｣，今天我們多出了個「遠端分支」，事情就相對複雜一些。

基本上，當我們的版本控管流程加上了遠端儲存庫之後，原本的**分支**就可以被拆成四種不同的概念：

1. 遠端追蹤分支

	這個分支位於遠端，目的是用來追蹤分支的變化情形。通常遠端分支你是存取不到的。

2. 本地追蹤分支

	當你執行 `git clone` 複製一個遠端容器回來之後，所有遠端追蹤分支會被下載回來，並且相對應的建立起一個同名的 **本地追蹤分支**。

	我們以複製 jQuery 在 GitHub 上的專案為例，透過 `git clone https://github.com/jquery/jquery.git` 下載回來後，執行 `git branch -a` 指令，顯示出所有「本地分支」與「本地追蹤分支」。「本地追蹤分支」就是如下圖**紅字**的部分：

	![image](https://f.cloud.github.com/assets/88981/1405811/8c59cc46-3d3f-11e3-9919-c71b5ccb87ca.png)

3. 本地分支

	在透過 `git branch` 指令執行時所顯示的分支，就是所謂的「本地分支」，這些分支存在於本地端，而這些分支又常被稱為 **主題分支** (Topic Branch) 或 **開發分支** (Development Branch)，就是因為這些分支預設不會被推送到遠端儲存庫，主要用來做開發用途。

4. 遠端分支

	顧名思義，遠端分支就是在遠端儲存庫中的分支，如此而已。如果你用 GitHub 的話，你是無法存取遠端分支的。

	雖然說「概念上」可以分為這四類，但其實這些分支就只是**參照名稱**而已，而這裡的「追蹤分支」主要就是用來跟遠端的分支做對應，你不應該直接在這些分支上建立版本 (雖然你還是可以這麼做，但強烈不建議亂搞)，而是把這些「本地追蹤分支」視為是一種｢唯讀｣的分支。


註冊遠端儲存庫
---------------

我們在上一篇有提過可以透過 `git remote` 指令手動加入一個「遠端儲存庫」，例如：

	git remote add origin https://github.com/doggy8088/sandbox-empty2.git

這個 `origin` 名稱是在 Git 版本控管中慣用的預設遠端分支的參照名稱，主要目的是用來代表一個遠端儲存庫的 URL 位址。

不過，事實上你可以在你的工作目錄中，建立多個遠端儲存庫的參照位址。例如我們以 `sandbox-empty2` 這個專案為例，我們先複製回來，然後透過 `git remote -v` 可列出目前註冊在工作目錄裡的遠端儲存庫資訊。如果我們額外將 jQuery 的遠端儲存庫也一併下載回來，則可以用以下指令先行註冊一個名稱起來。

	git remote add jquery https://github.com/jquery/jquery.git

最後再用 `git fetch` 指令把完整的 jQuery 遠端儲存庫一併下載回來，完整的執行過程如下圖示：

![image](https://f.cloud.github.com/assets/88981/1408254/d9fa10d4-3d7e-11e3-9c36-677d2e54efcd.png)

你可以看到，我們事實上可以在一個 Git 工作目錄中，加入許多相關或不相關的遠端儲存庫，這些複製回來的**完整儲存庫**，都包含了這些儲存庫中的所有物件與變更歷史，這些 Git 物件隨時都可以靈活運用。不過，通常我們註冊多個遠端儲存庫的機會並不多，除非你想抓特其他團隊成員的版本庫回來查看內容。

這些註冊進工作目錄的遠端儲存庫設定資訊，都儲存在 `.git\config` 設定檔中，其內容如下範例：

	[remote "origin"]
		url = https://github.com/doggy8088/sandbox-empty2.git
		fetch = +refs/heads/*:refs/remotes/origin/*
	[remote "jquery"]
		url = https://github.com/jquery/jquery.git
		fetch = +refs/heads/*:refs/remotes/jquery/*

這個 `[remote "origin"]` 區段的設定，包含了遠端儲存庫的代表名稱 `origin`，還有兩個重要的參數，分別是 `url` 與 `fetch` 這兩個，所代表的意思是：「遠端儲存庫 URL 位址在 `https://github.com/doggy8088/sandbox-empty2.git`，然後 `fetch` 所指定的則是一個**參照名稱對應規格**(refspec)。」


何謂參照名稱對應規格 (refspec)
-------------------------------

我們先來看一下 refspec 的格式：

	+refs/heads/*:refs/remotes/origin/*

這個格式概略區分成 4 塊：

* `+`

	設定 `+` 加號，代表傳輸資料時，不會特別使用安全性確認機制。

* `refs/heads/*`

	「來源參照規格」，代表一個位於**遠端儲存庫**的**遠端分支**，而 `*` 星號代表 `refs/heads/` 這個路徑下｢所有的遠端參照」。

* `:`

	這用來區隔｢來源分支｣與「目的分支」

* `refs/remotes/origin/*`

	「目的參照規格」，代表一個位於**本地儲存庫**的**本地追蹤分支**，而 `*` 星號代表工作目錄的 `refs/remotes/origin/` 這個路徑下｢所有的本地參照」。

當我們定義好這份 refspec 對應規格後，主要會影響到的是 `git fetch` 與 `git push` 這兩個遠端儲存庫的操作。

`git fetch` 就是把遠端儲存庫的相關物件取回，但要取得那些遠端分支的物件呢？就是透過這份 refspec 的定義，他才知道的。以上述為例，當你執行 `git fetch` 或 `git fetch origin` 的時候，他會先透過 URL 連到遠端儲存庫，然後找出「來源參照規格」的那些遠端分支 (`refs/heads/*`)，取回之後放入「目的參照規格」的那些本地追蹤分支(`refs/remotes/origin/*`)。

我們要怎樣查詢遠端儲存庫到底有哪些分支呢？你可以執行 `git ls-remote` 或 `git ls-remote origin` 即可列出所有遠端分支：

![image](https://f.cloud.github.com/assets/88981/1408776/0cd78222-3d87-11e3-8f2f-ce6d664262fb.png)

如果你把 fetch 的 refspec 修改成以下這樣，那麼除了 `master` 以外的遠端分支，就不會被下載了！：

	fetch = +refs/heads/master:refs/remotes/origin/master

如果你想明確下在特定幾個分支就好，你可以重複定義好幾個不同的 `fetch` 參照規格 (refspec)，例如：

	[remote "origin"]
	       url = https://github.com/doggy8088/sandbox-empty2.git
	       fetch = +refs/heads/master:refs/remotes/origin/master
	       fetch = +refs/heads/TestBranch:refs/remotes/origin/TestBranch

另外，在我們透過 `git remote add [URL]` 建立遠端儲存庫設定時，並沒有 `push` 參照規格，其預設值如下：

	push = +refs/heads/*:refs/heads/*

所代表的意思則是，當執行 `git push` 時，Git 指令會參考這份 `push` 的參照規格，讓你將本地儲存庫在 `refs/heads/*` 底下的所有分支與標籤，全部都推送到相對應遠端儲存庫的 `refs/heads/*` 參照名稱下。

最後，無論你執行 `git push` 或 `git fetch`，在不特別加參數的情況下，Git 預設就是用 `origin` 當成遠端儲存庫，並使用 `origin` 的參照規格。


本地分支與遠端儲存庫之間的關係
---------------------------

我們已經知道，一個工作目錄下的本地儲存庫，可能會定義有多個遠端儲存庫。所以當你想將 **非 `master` 分支** 透過 `git push` 推送到遠端時，Git 可能不知道你到底想推送到哪裡，所以我們要另外定義本地分支與遠端儲存庫之間的關係。

我們以 `https://github.com/doggy8088/frontend-tools.git` 這個遠端儲存庫為例，我複製下來後，預設就會有一個 `master` 本地分支，我嘗試建立一個 `FixForCRLF` 本地分支，直接透過 `git push` 無法推送成功，你必須輸入完整的 `git push origin FixForCRLF` 指令才能將本地分支推送上去，原因就出在你並沒有設定「本地分支」與「遠端儲存庫」之間的預設對應。

![image](https://f.cloud.github.com/assets/88981/1405857/0425ab54-3d41-11e3-953b-faa3fbe6cd8c.png)

要將**本地分支**建立起跟**遠端儲存庫**的對應關係，只要在 `git push` 的時候加上 `--set-upstream` 參數，即可將本地分支註冊進 `.git\config` 設定檔，之後再用 `git push` 就可以順利的自動推送上去。

![image](https://f.cloud.github.com/assets/88981/1405874/cd6e0c9a-3d41-11e3-843c-f1cc78a11cdf.png)

執行 `git push --set-upstream origin FixForCRLF` 的同時，會在 `.git\config` 設定檔增加以下內容： 

	[branch "FixForCRLF"]
		remote = origin
		merge = refs/heads/FixForCRLF

你可以從這個設定檔的格式中發現，在這個 `[branch "FixForCRLF"]` 設定裡面，有兩個屬性分別是 `remote` 與 `merge`，所代表的意思是：「當你想要將本地的 `FixForCRLF` 分支推送到遠端儲存庫時，預設的遠端儲存庫為 `origin` 這個，然後推送的時候要將本次的變更合併到 `refs/heads/FixForCRLF` 這個遠端分支裡。」

當然，我們在一開始執行 `git clone https://github.com/doggy8088/frontend-tools.git` 的時候，Git 就會預設幫我們建立好 `master` 分支的對應關係，所以針對 `master` 分支進行操作時，不需要額外加上 `--set-upstream` 就能使用。其分支的定義內容如下：

	[branch "master"]
		remote = origin
		merge = refs/heads/master


今日小結
-------

本篇文章詳細的介紹，在面對遠端儲存庫時的一些重要觀念，尤其是參照規格 (refspec) 這一段,學會之後才有機會設定更加符合自己或團隊需要的設定。不過，還是建議大家不要修改預設值，以免把大家搞糊塗了。

我重新整理一下本日學到的 Git 指令與參數：

* git remote -v
* git branch -r
* git branch -a
* git branch
* git push
* git ls-remote 


第 26 天：多人在同一個遠端儲存庫中進行版控
========================================================

一個人用的版本控管，只能算是當作原始碼歷史備份工具，在大多數的情況下，版本控管機制都是設計給多人共同使用的，尤其是 Git 這套分散式版本控管系統，更是設計給成千上萬人都能順利使用的版本控管工具。不過，在多人使用的情境下，通常多多少少也會帶來一些副作用，多跟少的問題。在 Git 版控中，多人同時進行版控的策略有好幾種，今天將介紹大家共用一個遠端儲存庫的使用方式與問題解決方法。


建立多人使用的遠端儲存庫與工作目錄
---------------------------------

我們先假設所有人只會共用一個「遠端儲存庫」，由於大家會用 `git clone` 指令把遠端儲存庫給複製回來，所以每個人都會有一份擁有完整歷史的版本庫。

為了簡化講解，我先在本地先建立一個「共用儲存庫」，把它當成「遠端儲存庫」來用，其用法跟你在用 GitHub 的時候一模一樣，不但觀念一樣，指令操作也都完全相同。我們先用以下指令建立一個共用儲存物，並位於 `C:/myproject.git` 資料夾下：

	c:
	cd \
	mkdir myproject.git
	cd myproject.git
	git init --bare

再來我們假設有兩位開發人員準備開發一個新專案 `myproject`，分別是 `User1` 與 `User2` 這兩位。

首先，`User1` 先利用 `git clone C:/myproject.git User1WD` 建立一個工作目錄，並在工作目錄下建立一個初始版本，並推送到 `origin` 遠端儲存庫。其指令如下：

	c:
	cd \
	git clone C:/myproject.git User1WD
	cd User1WD
	echo a > a.txt
	git add .
	git commit -m "Add a.txt"
	git push origin master

現在我們的遠端儲存庫 `C:/myproject.git` 已經有了一個初始版本，並擁有一個 `a.txt` 檔案。

接著，`User2` 利用 `git clone C:/myproject.git User2WD` 建立另一個屬於 `User2` 自己的工作目錄，預設會自動建立號 `origin` 遠端儲存庫的設定。其指令如下：

	c:
	cd \
	git clone C:/myproject.git User2WD
	cd User2WD

現在我們已經準備好一個「多人」(兩人) 使用的版控環境，並共用一個遠端儲存庫。


遠端儲存庫的基本開發流程
-----------------------

現在 `User1` 與 `User2` 擁有完全相同的儲存庫，版本也都完全一樣，都只有一個。

現在 `User1` 先聲奪人，搶先建立了版本，而且也將變更推送到 `C:/myproject.git` 遠端儲存庫：

	C:\User1WD>echo b > b.txt
	
	C:\User1WD>git add .
	
	C:\User1WD>git commit -m "Add b.txt"
	[master 7bcbc05] Add b.txt
	 1 file changed, 1 insertion(+)
	 create mode 100644 b.txt
	
	C:\User1WD>git push origin master
	Counting objects: 4, done.
	Delta compression using up to 4 threads.
	Compressing objects: 100% (2/2), done.
	Writing objects: 100% (3/3), 267 bytes | 0 bytes/s, done.
	Total 3 (delta 0), reused 0 (delta 0)
	To C:/myproject.git
	   f4f7df9..7bcbc05  master -> master

這時 `User2` 的工作目錄有兩個分支，一個是本地的 `master` 分支，另一個是 `origin/master` 本地追蹤分支。但是 `User2` 現在的 `origin/master` 並沒有得到遠端儲存庫的最新版，而且 `User2` 並不知道 `User1` 已經將他手邊的版本推送到遠端儲存庫了，所以還是繼續自己的開發作業，也在他自己的工作目錄中建立了一個版本。但在準備將版本推送到遠端儲存庫時，發現了一個問題，因為他的推送作業被遠端儲存庫拒絕了！原因就出在存在於遠端儲存庫的初始版本之後，已經擁有了一個新版本，他不允許另外一個人建立一個多重的版本歷史，所以拒絕你將本地版本推送上去。

	C:\User2WD>echo c > c.txt
	
	C:\User2WD>git add .
	
	C:\User2WD>git commit -m "Add c.txt"
	[master dbebba3] Add c.txt
	 1 file changed, 1 insertion(+)
	 create mode 100644 c.txt
	
	C:\User2WD>git push origin master
	To C:/myproject.git
	 ! [rejected]        master -> master (fetch first)
	error: failed to push some refs to 'C:/myproject.git'
	hint: Updates were rejected because the remote contains work that you do
	hint: not have locally. This is usually caused by another repository pushing
	hint: to the same ref. You may want to first merge the remote changes (e.g.,
	hint: 'git pull') before pushing again.
	hint: See the 'Note about fast-forwards' in 'git push --help' for details.

![image](https://f.cloud.github.com/assets/88981/1415435/73ff2680-3f03-11e3-80a1-dc017ec8fb3f.png)

遇到這種問題請不要緊張，Git 很擅長處裡這種狀況。你 (`User2`) 現在要做的事，就是先把遠端儲存庫中的新物件取回，如下指令：

	C:\User2WD>git fetch
	remote: Counting objects: 4, done.
	remote: Compressing objects: 100% (2/2), done.
	remote: Total 3 (delta 0), reused 0 (delta 0)
	Unpacking objects: 100% (3/3), done.
	From C:/myproject
	   f4f7df9..7bcbc05  master     -> origin/master

![image](https://f.cloud.github.com/assets/88981/1415436/8dc47ec6-3f03-11e3-83e2-306c42b8c4cb.png)

這時我們可以看到 `User2WD` 中 `origin/master` 這個本地追蹤分支的的版本線圖，已經移動了一個版本，這代表你已經成功改變了 `origin/master` 的參照位址到最新的 `Add b.txt` 這個版本。

現在你要做的則是把 `origin/master` 版本的變更｢合併｣回自己的 `master` 本地分支：

	C:\User2WD>git merge origin/master
	Merge made by the 'recursive' strategy.
	 b.txt | 1 +
	 1 file changed, 1 insertion(+)
	 create mode 100644 b.txt

![image](https://f.cloud.github.com/assets/88981/1415438/9fecf66e-3f03-11e3-897a-ab27c7f73740.png)

這樣你就可以將遠端儲存庫中 `master` 遠端分支的所有版本套用到自己的 `master` 分支上，也代表你現在可以嘗試把本地修改過的變更版本推送到遠端儲存庫了。

	C:\User2WD>git push origin master
	Counting objects: 7, done.
	Delta compression using up to 4 threads.
	Compressing objects: 100% (4/4), done.
	Writing objects: 100% (5/5), 566 bytes | 0 bytes/s, done.
	Total 5 (delta 0), reused 0 (delta 0)
	To C:/myproject.git
	   7bcbc05..32ef41c  master -> master

![image](https://f.cloud.github.com/assets/88981/1415443/cb8b6dfa-3f03-11e3-9d3b-ce98442d3720.png)

如果這個時候 `User2` 又再度做出變更，而且 `User1` 也不知道原來 `User2` 也送出了一些變更到遠端儲存庫 (在分散式的版本控管系統中，這種狀況很常見，畢竟大家並沒有坐在同一間辦公室)，而又建立了一個版本，當然他也無法成功的把變更推送上去。

	C:\User1WD>echo d > d.txt
	
	C:\User1WD>git add .
	
	C:\User1WD>git commit -m "Add d.txt"
	[master 57ea603] Add d.txt
	 1 file changed, 1 insertion(+)
	 create mode 100644 d.txt

此時 `User1` 該做的事，其實跟剛剛 `User2` 做的事一模一樣，也是要先用 `git fetch` 取回遠端儲存庫中的最新版，然後再用 `git merge origin/master` 合併回自己的 `master` 本地分支，最後再用 `git push` 推送進遠端儲存庫。不過，這次我們改用 `git pull` 指令幫我們一次做到 `git fetch` 與 `git merge origin/master` 這個動作，這動作相對的會簡單很多。

	C:\User1WD>git pull
	Merge made by the 'recursive' strategy.
	 c.txt | 1 +
	 1 file changed, 1 insertion(+)
	 create mode 100644 c.txt

![image](https://f.cloud.github.com/assets/88981/1415445/fea0a624-3f03-11e3-975b-487488a32d9c.png)

最後，我們用 `git push origin master` 把版本給推送到遠端儲存庫：

	C:\User1WD>git push origin master
	Counting objects: 7, done.
	Delta compression using up to 4 threads.
	Compressing objects: 100% (4/4), done.
	Writing objects: 100% (5/5), 484 bytes | 0 bytes/s, done.
	Total 5 (delta 2), reused 0 (delta 0)
	To C:/myproject.git
	   32ef41c..1ae28db  master -> master

![image](https://f.cloud.github.com/assets/88981/1415448/35a19390-3f04-11e3-95f0-938675d7f2ea.png)

就這樣不斷周而復始，完成多人協同作業的步驟。


今日小結
---------

無法避免的，在執行 `git merge origin/master` 或 `git pull` 的過程中，還是很有可能會出現合併衝突的現象，遇到這種情形你還是必須手動處裡並協調解決衝突，但這已經是多人使用 Git 版本控管中最簡單的使用方式。

如果你今天發生了衝突狀況，而又不知道如何解決，因為版本尚未被成功合併，所以你可以執行以下指令「重置」到目前的 `HEAD` 版本：

	git reset --hard HEAD

如果你今天成功的合併了，但又想反悔這次的合併動作，那麼你還是可以執行以下指令「重置」到**合併前**的版本狀態，也就是重置到 `ORIG_HEAD` 這個版本：

	git reset --hard ORIG_HEAD

我重新整理一下本日學到的 Git 指令與參數：

* git init --bare
* git clone [repo_url] [dir]
* git add .
* git commit -m "message"
* git push origin master
* git fetch
* git merge origin/master
* git pull
* git reset --hard HEAD
* git reset --hard ORIG_HEAD



第 27 天：透過分支在同一個遠端儲存庫中進行版控
============================================================

如果在公司內部只有一個共用的 Git 遠端儲存庫，大家都有存取權限的情況下，可能會遇到一些協同作業上的問題，那就是不同人彼此之間的程式碼互相干擾的情況。例如你在團隊開發的過程中，被指派負責開發新功能，但同時間其他同事負責修正目前上線的程式錯誤，如果兩人共用同一個分支 (例如 `master` 分支)，那麼在版控的過程中就很容易發生衝突的情況，這時你應該要善加利用分支將不同用途的原始碼分別進行版本管理。

建立多人使用的遠端儲存庫與工作目錄
--------------------------------

我在 GitHub 上建立了一個 `sandbox-multi-branch` 專案，並直接在 GitHub 上建立一個 **Initial commit** 版本，用做本篇文章的遠端儲存庫。但這次我改用 `git@github.com:doggy8088/sandbox-multi-branch.git` 這個網址，透過 SSH 通訊協定來存取我的遠端儲存庫，好讓我可以不用每次執行遠端儲存庫的操作時都要輸入帳號密碼。

![image](https://f.cloud.github.com/assets/88981/1415618/57188c32-3f12-11e3-8f2a-9fa46045a320.png)

我們執行以下指令將專案複製回來：

	C:\>git clone git@github.com:doggy8088/sandbox-multi-branch.git
	Cloning into 'sandbox-multi-branch'...
	Receiving objecg objects: 3, done.Receiving objects:  33% (1/3)
	Receiving objects: 100%0), reused 0 (delta 0)ts:  66% (2/3)
	Receiving objects: 100% (3/3), done.
	
	C:\>cd sandbox-multi-branch
	
	C:\sandbox-multi-branch>git log
	commit 6eeee883275e3d5e0281767aca4f456d952fa682
	Author: Will 保哥 <xxx@gmail.com>
	Date:   Sun Oct 27 07:13:50 2013 -0700
	
	    Initial commit

	C:\sandbox-multi-branch>git branch -a
	* master
	  remotes/origin/HEAD -> origin/master
	  remotes/origin/master

此時我們的 `.git\config` 內容如下：

	[core]
		repositoryformatversion = 0
		filemode = false
		bare = false
		logallrefupdates = true
		symlinks = false
		ignorecase = true
		hideDotFiles = dotGitOnly
	[remote "origin"]
		url = git@github.com:doggy8088/sandbox-multi-branch.git
		fetch = +refs/heads/*:refs/remotes/origin/*
	[branch "master"]
		remote = origin
		merge = refs/heads/master


常見的分支名稱
--------------

我們知道在建立好一個新的 Git 儲存庫時，預設都會有一個 `master` 分支。在實務上，這個分支通常用來當作目前系統的「穩定版本」，也就是這個版本必須是乾淨且高品質的原始碼版本。所以，我們會要求所有人都不要用這個分支來建立任何版本，真正要建立版本時，一定會透過「合併」的方式來進行操作，以確保版本能夠更容易被追蹤。

進入開發階段時，我們通常會再從 `master` 分支建立起另一個 `develop` 分支，用來作為「開發分支」，也就是所有人都會在這個分支上進行開發，但這個時候或許會產生一些衝突的情形，因為大家都在同一個分支上進行版本控管。不過這種用法跟以往我們用 Subversion 的時候是比較類似的，所以使用上的觀念通常差不多。本文稍後就會介紹一些分支開發的練習，但我們現在就可以先建立一個 `develop` 分支起來。

	C:\sandbox-multi-branch>git branch
	* master
	
	C:\sandbox-multi-branch>git checkout -b develop
	Switched to a new branch 'develop'
	
	C:\sandbox-multi-branch>git branch
	* develop
	  master

開發過程中，有時候我們也會因為需求變更，而被指派開發一些新功能，但這些新功能可能變動性還很大，甚至只是想進行 PoC 驗證而開發的小功能。這些小功能只是測試用途，你不想因為開發這些測試功能而影響到大家的開發作業，所以這時我們會選擇再建立起一個「新功能分支」，專門用來存放這些新增功能的程式碼版本。這個測試用的「功能分支」，通常會建立在 `develop` 之上，所以我們會再從 `develop` 分支來建立另一個分支。但這個分支的名稱，實務上通常會取名為 `feature/[branch_name]`，例如：`feature/aspnet_identity`。

	C:\sandbox-multi-branch>git branch
	* develop
	  master
	
	C:\sandbox-multi-branch>git checkout -b feature/aspnet_identity
	Switched to a new branch 'feature/aspnet_identity'
	
	C:\sandbox-multi-branch>git branch
	  develop
	* feature/aspnet_identity
	  master

如果你發現在開發的過程中，「正式機」 (生產環境) 的系統出現了一個嚴重錯誤，但在「開發分支」裡又包含一些尚未完成的功能，這時你可能會從 `master` 分支緊急建立一個「修正分支」，通常的命名為 `hotfix/[branch_name]`，例如：`hotfix/bugs_in_membership`。

	C:\sandbox-multi-branch>git branch
	  develop
	* feature/aspnet_identity
	  master
	
	C:\sandbox-multi-branch>git checkout master
	Switched to branch 'master'
	
	C:\sandbox-multi-branch>git branch
	  develop
	  feature/aspnet_identity
	* master
	
	C:\sandbox-multi-branch>git checkout -b hotfix/bugs_in_membership
	Switched to a new branch 'hotfix/bugs_in_membership'
	
	C:\sandbox-multi-branch>git branch
	  develop
	  feature/aspnet_identity
	* hotfix/bugs_in_membership
	  master

如果你發現目前的 `master` 分支趨於穩定版本，那麼你可能會想替目前的 `master` 分支建立起一個「標籤物件」或稱「標示標籤」(annotated tag)，那麼你可以先切換到 `master` 分支後輸入 `git tag 1.0.0-beta1 -a -m "V1.0.0-beta1 created"` 即可建立一個名為 `1.0.0-beta` 的標示標籤，並透過 `-m` 賦予標籤一個說明訊息。

	C:\sandbox-multi-branch>git branch
	  develop
	  feature/aspnet_identity
	* hotfix/bugs_in_membership
	  master
	
	C:\sandbox-multi-branch>git checkout master
	Switched to branch 'master'
	
	C:\sandbox-multi-branch>git tag 1.0.0-beta1 -a -m "V1.0.0-beta1 created"
	
	C:\sandbox-multi-branch>git tag
	1.0.0-beta1

以上就是使用 Git 的過程中常見的命名規則與版控流程。


將本地分支送上遠端儲存庫
--------------------------

目前為止我們建立了好幾個分支與標籤，用 SourceTree 來看，目前還看不出分支的版本線圖，畢竟我們還沒有建立任何版本，但該有的分支已經被成功建立，如下圖示：

![image](https://f.cloud.github.com/assets/88981/1415681/dd19754a-3f16-11e3-9e85-b11d05e9773e.png)

不過，這些分支都僅儲存在本地儲存庫中，團隊中所有其他人都無法得到你建立的這些分支，如果要將這些分支的參照名稱推送到遠端儲存庫，可以使用 `git push --all` 這個指令。

	C:\sandbox-multi-branch>git push --all
	Total 0 (delta 0), reused 0 (delta 0)
	To git@github.com:doggy8088/sandbox-multi-branch.git
	 * [new branch]      develop -> develop
	 * [new branch]      feature/aspnet_identity -> feature/aspnet_identity
	 * [new branch]      hotfix/bugs_in_membership -> hotfix/bugs_in_membership

不過如果只下達 `--all` 參數是不夠的，可能還要加上 `--tags` 參數，才能將標示標籤也一併推送到遠端儲存庫。

	C:\sandbox-multi-branch>git push --tags
	Counting objects: 1, done.
	Writing objects: 100% (1/1), 159 bytes | 0 bytes/s, done.
	Total 1 (delta 0), reused 0 (delta 0)
	To git@github.com:doggy8088/sandbox-multi-branch.git
	 * [new tag]         1.0.0-beta1 -> 1.0.0-beta1

這個時候，所有物件與參照名稱都已經儲存在遠端儲存庫了。我們連到 GitHub 就能看到這些物件已經可以被瀏覽到：

![image](https://f.cloud.github.com/assets/88981/1415694/2a599f82-3f18-11e3-8bb3-b1e79e443e2a.png)

如果切換到 **Tags** 頁籤的話，也可以看到標籤物件也被送上來了：

![image](https://f.cloud.github.com/assets/88981/1415692/03dc24e2-3f18-11e3-842d-b1fa0a91dede.png)


請團隊成員下載遠端儲存庫所有物件
------------------------------

這個時候大家就能夠透過 `git fetch --all --tags` 將所有物件取回，包含所有物件參照與標籤參照。

我們建立起另一個工作目錄，模擬其他使用者取回資料的情況：

	C:\>git clone git@github.com:doggy8088/sandbox-multi-branch.git sandbox-multi-branch-user2
	Cloning into 'sandbox-multi-branch-user2'...
	remote: Counting objects: 4, done.
	remote: Compressing objects: 100% (2/2), done.
	remote: Total 4 (delta 0), reused 1 (delta 0)
	Receiving objects: 100% (4/4), done.
	
	C:\>cd sandbox-multi-branch-user2

	C:\sandbox-multi-branch-user2>git fetch --all --tags
	Fetching origin

取回物件後，用 SourceTree 查看儲存庫的狀態如下：

![image](https://f.cloud.github.com/assets/88981/1415707/1d037ab4-3f19-11e3-8d59-46a458d6a752.png)


開始各自進行不同的分支開發
-------------------------

現在開始，團隊所有成員都擁有了預先定義好的「Git 儲存庫範本」，大家就能各就各位，開發自己需要開發的功能。或許會有兩個人在 `develop` 分支上進行開發，或許會有一個人被指派 `hotfix/bugs_in_membership` 分支進行修復任務，諸如此類的，等分支完成開發後，再將變更推送到遠端儲存庫裡。

眼尖的你可能會發現，這個 `User2` 的本地分支只有 `master` 而已，跟我們原本建立的那個工作目錄有些不一樣。之前在【第 25 天：使用 GitHub 遠端儲存庫 - 觀念篇】文章中不是提到說「**把這些「本地追蹤分支」視為是一種｢唯讀｣的分支**」嗎？沒有本地分支要怎樣進行呢？

關於這一點，各位也不用擔心，Git 早就幫我們想好了。假設你現在被賦予的任務是去開發 `hotfix/bugs_in_membership` 分支，並負責把變更錯誤修正，你可以直接執行 `git checkout hotfix/bugs_in_membership` 將這個「本地追蹤分支」給取出 (checkout)。 

	C:\sandbox-multi-branch-user2>git branch -a
	* master
	  remotes/origin/HEAD -> origin/master
	  remotes/origin/develop
	  remotes/origin/feature/aspnet_identity
	  remotes/origin/hotfix/bugs_in_membership
	  remotes/origin/master
	
	C:\sandbox-multi-branch-user2>git checkout hotfix/bugs_in_membership
	Branch hotfix/bugs_in_membership set up to track remote branch hotfix/bugs_in_me
	mbership from origin.
	Switched to a new branch 'hotfix/bugs_in_membership'
	
	C:\sandbox-multi-branch-user2>git branch -a
	* hotfix/bugs_in_membership
	  master
	  remotes/origin/HEAD -> origin/master
	  remotes/origin/develop
	  remotes/origin/feature/aspnet_identity
	  remotes/origin/hotfix/bugs_in_membership
	  remotes/origin/master

在取出 `hotfix/bugs_in_membership` 這個「本地追蹤分支」後，Git 會動幫你建立起一個同名的「本地分支」，所以你根本不用擔心有沒有本地分支的情形。

![image](https://f.cloud.github.com/assets/88981/1415749/b111b87c-3f1b-11e3-9803-57e537718752.png)

這時我們模擬在 `hotfix/bugs_in_membership` 這個「本地分支」建立一個版本：

	C:\sandbox-multi-branch-user2>git status
	# On branch hotfix/bugs_in_membership
	nothing to commit, working directory clean
	
	C:\sandbox-multi-branch-user2>echo %date% %time% > a.txt
	
	C:\sandbox-multi-branch-user2>git add .
	
	C:\sandbox-multi-branch-user2>git commit -m "Add a.txt"
	[hotfix/bugs_in_membership 250e907] Add a.txt
	 1 file changed, 1 insertion(+)
	 create mode 100644 a.txt

目前的版本線圖如下：

![image](https://f.cloud.github.com/assets/88981/1415752/18ce7590-3f1c-11e3-955f-cd53fbbcc536.png)

接著如果你想將變更推送到遠端，只要下達 `git push origin hotfix/bugs_in_membership` 即可將變更推送回去：

	C:\sandbox-multi-branch-user2>git push origin hotfix/bugs_in_membership
	Counting objects: 4, done.
	Delta compression using up to 8 threads.
	Compressing objects: 100% (2/2), done.
	Writing objects: 100% (3/3), 294 bytes | 0 bytes/s, done.
	Total 3 (delta 0), reused 0 (delta 0)
	To git@github.com:doggy8088/sandbox-multi-branch.git
	   6eeee88..250e907  hotfix/bugs_in_membership -> hotfix/bugs_in_membership

不過目前為止，你所推送回去的，只有 `hotfix/bugs_in_membership` 這個分支的版本而已，你並沒有將變更「合併」回 `master` 分支。這樣操作所代表的意思是，你將變更放上遠端儲存庫，目的是為了將變更可以讓其他人看到，也可以取回繼續修改，就跟昨天【第 26 天：多人在同一個遠端儲存庫中進行版控】文章中講的版控流程一樣。

如果你想合併回去，可以先切換至 `master` 分支，再去合併 `hotfix/bugs_in_membership` 分支的變更，最後在推送到遠端儲存庫。如下指令範例：

	C:\sandbox-multi-branch-user2>git branch -a
	* hotfix/bugs_in_membership
	  master
	  remotes/origin/HEAD -> origin/master
	  remotes/origin/develop
	  remotes/origin/feature/aspnet_identity
	  remotes/origin/hotfix/bugs_in_membership
	  remotes/origin/master
	
	C:\sandbox-multi-branch-user2>git checkout master
	Switched to branch 'master'
	
	C:\sandbox-multi-branch-user2>git merge hotfix/bugs_in_membership
	Updating 6eeee88..250e907
	Fast-forward
	 a.txt | 1 +
	 1 file changed, 1 insertion(+)
	 create mode 100644 a.txt
	
	C:\sandbox-multi-branch-user2>git push
	Total 0 (delta 0), reused 0 (delta 0)
	To git@github.com:doggy8088/sandbox-multi-branch.git
	   6eeee88..250e907  master -> master

![image](https://f.cloud.github.com/assets/88981/1415759/0260a494-3f1d-11e3-8fe8-6ec23af07d4b.png)

如此一來，`master` 的分支內容就成功被更新，並且推送到遠端儲存庫了。

想當然爾，其他的分支也都是用類似的方式運作著。


今日小結
-------

今天更進一步介紹了 Git 更接近實務面的版控流程，讓大家透過不同的分支進行開發，彼此之間做一個有效區隔，然後還能在同一個遠端儲存庫中進行版控，同時享受了集中式版本控管的特性，以及分散式版本控管的彈性，非常優秀不是嗎！ ^_^

我重新整理一下本日學到的 Git 指令與參數：

* git push --all --tags
* git fetch --all --tags
* git branch -a
* git checkout hotfix/bugs_in_membership
* git push origin hotfix/bugs_in_membership



第 29 天：如何將 Subversion 專案匯入到 Git 儲存庫
==================================================================

當你越來越了解 Git 版本控管，一定會越來越想把手邊的 Subversion ( 簡稱 SVN ) 專案改用 Git 進行版本控管。但礙於兩者的版本架構差別甚大，轉換的過程稍微麻煩些，主要是要打些指令才行，還好 Git 已經內建了許多 SVN 的整合指令，讓我們可以容易地將 SVN 專案轉換過去。本篇文章將介紹如何用簡單的四步驟，將現有的 SVN 專案轉成 Git 儲存庫，並將轉換後的本地儲存庫送上遠端儲存庫。

準備使用者清單對應檔
--------------------

我們先來看一個用 TortoiseSVN 的 Show log 看到的版本歷史清單，在 **Author** 欄位看到的只有「使用者名稱」而已：

![image](https://f.cloud.github.com/assets/88981/1428691/8fe0a5d2-40a6-11e3-8799-0504b1f6f8c8.png)

不過，使用 Git 必須至少有「使用者名稱」與「電子郵件地址」才能建立版本，所以我們必須先把 SVN 專案中所有的 **Author** 取出，並設定好一個對應檔，才能完整的將 SVN 專案匯入到 Git 專案中。

我們假設 2 個變數：

* SVN 專案網址：`https://svnrepo:23443/svn/DoggyLibrarySolution`
* SVN 工作目錄：`D:\Projects\DoggyLibrarySolution`
* GIT 安裝路徑：`C:\Program Files (x86)\Git` 

**請注意**：執行 svn 命令必須事先安裝 Subversion 指令列工具，下載連結: [Subversion Edge Download](http://www.collab.net/downloads/subversion)

我們開啟「命令提示字元」並進入 SVN 工作目錄，然後執行以下指令，你會得到一個 `SVNUsers.txt` 檔案：

	SET PATH=%PATH%;C:\Program Files (x86)\Git\bin\
	svn log --quiet --xml | sed -n -e "s/<\/\?author>//g" -e "/[<>]/!p" | sort | sed "$!N; /^\(.*\)\n\1$/!P; D" > SVNUsers.txt

由於我們這個 SVN 專案只有 4 位開發人員，所以得到的 `SVNUsers.txt` 檔案內容如下：

![image](https://f.cloud.github.com/assets/88981/1428746/9c64cb84-40a7-11e3-8052-102b213e1f58.png)

接下來，我要修改這個檔案，在每一行後面加上 `=` 等號，再加上「使用者名稱」與「電子郵件地址」，格式如下：

	svnuser = GitUsername <GitEmail>

修改完後的內容如下：

![image](https://f.cloud.github.com/assets/88981/1428779/2ef5b45e-40a8-11e3-9709-13403c05f627.png)


將 SVN 專案取出並轉換成 Git 工作目錄
-------------------------------------

假設我想將 GIT 工作目錄設定在 `G:\DoggyLibrarySolution` 資料夾，那麼你可以先把修改後的 `SVNUsers.txt` 檔案複製到 `G:\` 目錄下，然後執行以下指令：

	git svn clone https://svnrepo:23443/svn/DoggyLibrarySolution --no-metadata -A SVNUsers.txt --stdlayout

如果你可以存取的 SVN 儲存庫權限只有 /trunk 而已的話，你不能使用 --stdlayout 屬性，例如：

	git svn clone https://svnrepo:23443/svn/DoggyLibrarySolution/trunk --no-metadata -A SVNUsers.txt

這個指令執行時，可能會需要你輸入 SVN 版本庫的登入帳號密碼。

![image](https://f.cloud.github.com/assets/88981/1428842/08079cbc-40a9-11e3-860b-7c7e6c1e0f7b.png)

轉換後的結果來看，你會發現轉換後的 Git 儲存庫，版本資訊非常完整，他會保留 SVN 當初留下的 commit 時間與作者資訊，這裡的作者資訊所顯示的使用者名稱與電子郵件地址則是我們剛剛定義檔所設定的那些對應資訊：

![image](https://f.cloud.github.com/assets/88981/1428868/6718898c-40a9-11e3-978c-77817d2d71a0.png)


轉換 SVN 的忽略清單 (即 `svn:ignore` 屬性)
-------------------------------------------

SVN 專案中有所謂的 `svn:ignore` 屬性，這等同於 Git 的 `.gitignore` 忽略清單。但是 SVN 的忽略清單散落在每個目錄屬性中，還好你可以透過 `git svn show-ignore` 指令轉換這些資訊為 Git 的格式。

接著我們直接透過以下指令取得 `.gitignore` 忽略清單檔的內容：

	git svn show-ignore

不過你可能會遇到以下錯誤：

	G:\DoggyLibrarySolution>git svn show-ignore
	config --get svn-remote.svn.fetch :refs/remotes/git-svn$: command returned error: 1

如果遇到這個錯誤，代表 `git svn show-ignore` 找不到你的 SVN 路徑，這通常發生在你的 SVN 版本庫使用了標準的 trunk, branches, tags 資料結構，這時你可以改輸入以下指令：

	git svn show-ignore -i trunk

![image](https://f.cloud.github.com/assets/88981/1428946/b3cfd2ca-40aa-11e3-9c6b-0819b16f08d0.png)

接著我們建立一個 `.gitignore` 忽略清單檔，並建立一個新版本，指令如下：

	git svn show-ignore -i trunk > .gitignore
	git add .gitignore
	git commit -m "Create .gitignore from SVN"

![image](https://f.cloud.github.com/assets/88981/1428959/009efcb6-40ab-11e3-9b86-fdd8fbeb5df2.png)


將專案推送到遠端儲存庫
------------------------

由於 GitHub 在預設的情況下，只能建立「開源碼」的 Git 專案，所以我們這次改用 [Bitbucket](https://bitbucket.org/) 網站來建立一個私有的 Git 專案 (Private Repository)。

![image](https://f.cloud.github.com/assets/88981/1428986/8b90368c-40ab-11e3-8eea-552acfef65a3.png)

建立完成後，按下 **Clone** 去複製 Git 儲存庫網址：

![image](https://f.cloud.github.com/assets/88981/1429016/fcf98b2a-40ab-11e3-93a4-b976c1959916.png)

接著就跟我們之前學到的一樣，把現有的專案給推送上去，如下指令：

	git remote add origin git@bitbucket.org:myaccount/doggylibrarysolution.git
	git push origin master

![image](https://f.cloud.github.com/assets/88981/1429044/637d5700-40ac-11e3-86c8-b03607400cad.png)


今日小結
-------

就這樣簡單四步驟，就可以把 SVN 專案完整的轉移到 Git 儲存庫，是不是非常簡單呢。

事實上，這個工作目錄還可以持續地跟原本的 SVN 版本庫溝通，可以 commit 變更，也可以 pull 變更回來 ( `git svn rebase` )，詳細的操作說明只要執行 `git help svn` 就可以取得完整說明。當然，我還是建議轉過去就轉過去了，否則在 Git 環境下操作 SVN 總覺得怪怪的，有點多此一舉的感覺，但確實有可能有這種需求。

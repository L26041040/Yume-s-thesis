# 信念構面單題直測範本與 NB／SN 判別效度寫法

**研究問題**：論文信念構面（行為信念 BB、規範信念 NB、控制信念 CB）目前的題項寫在具體子行為層級（住宿一題、餐飲一題、交通一題……），與「整體綠色旅遊行為意圖」不相容（違反 TACT 相容性原則）；且 NB 與 SN 題項高度重疊，判別效度堪憂。本報告查證 Ajzen 官方方法文件、觀光／綠色消費領域的單題直測前例，並給出改寫題項草稿。

**查證方式**：WebSearch + WebFetch，追到原始 PDF 全文逐句核實。抓不到全文、只有摘要層級的，會明確標註「未取得全文核實」，不編造題項或數據。

---

## 結論先講

1. **Ajzen 官方立場**：Ajzen 的方法論文件裡，「信念」從來不是以單一直測題項測量的——他的標準做法是「信念強度 × 結果評價／依從動機／控制力」的期望值相乘配對（見第 1 節）。論文採用「單題直測信念構面、不做期望值相乘」是一種**應用界的變體做法**，不是 Ajzen 本人示範的方法，但這個變體在觀光／綠色消費 SEM 文獻中確實存在且發表得出來——最乾淨的例證是 **Wu & Chen (2014)**（見第 2 節）。這點建議在論文方法論小節裡誠實交代：說明採用單題直測是「參考 Wu & Chen (2014) 等應用 TPB-SEM 文獻的做法，而非 Ajzen (2006) 原始期望值相乘的信念衡量法」，避免被口委抓到「你說依據 Ajzen，但題項設計跟 Ajzen 示範的不一樣」。
2. **TACT 相容性原則**確實白紙黑字寫在 Ajzen 的官方文件裡，且他的示範問卷裡「每一個構面的每一題」都逐字重複同一個 TACT 定義的行為片語（見第 1.3 節）。這證實了大哥的診斷：子行為層級的信念題項（住宿一題、餐飲一題）與整體層級的意圖題項不相容，必須統一到「綠色旅遊行為」整體層級。
3. **NB 與 SN 的判別寫法**，查到的最乾淨實證前例（Wu & Chen, 2014）靠的是「NB 具名特定 referent（家人／朋友）+ 依從强度；SN 不具名、改寫成對行為本身的整體道德／社會評價判斷（合宜的、應該的、有益眾人的）」這個結構性差異，且用 Gaski & Nevin (1985) 的相關係數 < 任一構面 Cronbach's α 準則過了判別效度（見第 3 節）——但這個準則比現在通行的 Fornell-Larcker／HTMT 寬鬆很多，論文正式寫作時建議至少補跑 Fornell-Larcker，不要只引 Gaski & Nevin 當唯一依據。
4. **找不到、且誠實說明找不到的部分**：Chen & Tung (2014)《Developing an extended theory of planned behavior model to predict consumers' intention to visit green hotels》（IJHM 36, 221-230）雖然是觀光/綠色旅宿 TPB 的高引用經典，但全文被 ScienceDirect 付費牆擋住，只查到摘要與被引用的結論層級資訊，**沒有取得逐字題項**，本報告不引用其題項字句，只引用可核實的方法論結論。同樣地，觀光領域中「NB 與 SN 同時列為獨立構念、且明確報告兩者判別效度」的乾淨範例，查找範圍內只找到 Wu & Chen (2014) 這一篇可逐字核實（該篇是綠色消費，非觀光專屬，但架構與大哥的論文完全同構：信念構面獨立直測 → 進 ATT/SN/PBC → SEM）。

---

## 1. Ajzen 官方 TPB 問卷建構指引

**來源**：Ajzen, I. *Constructing a Theory of Planned Behavior Questionnaire*（based on the appendix in Fishbein, M., & Ajzen, I. (2010). *Predicting and Changing Behavior: The Reasoned Action Approach*. Psychology Press）。
PDF：https://people.umass.edu/aizen/pdf/tpb.measurement.pdf （版權標註 2019，UMass Ajzen 官方頁面提供，全文已逐頁核實）

### 1.1 Belief-based（indirect）measures vs. Direct（reflective）measures 的區分

Ajzen 明確把 TPB 問卷分成兩套完全不同的測量系統：

- **Direct（reflective）measures**：直接測 Attitude、Subjective Norm、PBC、Intention 這四個構面本身。做法是「每個構面 5-6 題，七點雙極形容詞量表（bipolar adjective scale）」，逐字原文：

  > "Five to six items are formulated to assess each of the theory's major constructs: Attitude, subjective norm, perceived behavioral control, and intention. Seven-point bipolar adjective scales are typically employed."

- **Belief-based（indirect）measures**：測「信念」本身，但**從來不是單一題項**，而是每個 salient outcome／referent／control factor 都配一對題目：
  - 行為信念：Belief strength（該行為導致該結果的可能性，likely–unlikely）× Outcome evaluation（該結果本身好壞，good–bad）。
  - 規範信念又拆成兩支：
    - Injunctive（指令式）：Injunctive normative belief strength（「[referent] 認為我應該/不應該做」）× Motivation to comply（「我想不想照他的意思做」）。
    - Descriptive（描述式）：Descriptive normative belief strength（「像我這樣的人／該 referent 本身有沒有在做」）× Identification with the referent（「我想不想跟他一樣」）。
  - 控制信念：Control belief strength（該控制因子未來會不會出現，likely–unlikely）× Power of control factor（該因子促成/阻礙該行為的力道，disagree–agree）。

  逐字原文（範例，postoperative exercise 情境）：
  > "My exercising for at least 20 min, three times per week for the next three months will result in my having a faster recovery from my surgery." (likely : ... : unlikely) — 行為信念強度
  > "My having a faster recovery from my surgery is" (good : ... : bad) — 結果評價
  > "My doctor thinks that I should : ... : I should not exercise..." — 指令式規範信念強度
  > "When it comes to matters of health, I want to do what my doctor thinks I should do." (agree : ... : disagree) — 依從動機

**這對論文的意義**：Ajzen 本人從未示範過「信念構面直接用 5 題 Likert 單獨測、不配對評價/依從動機」這種做法。這不代表你的設計不能用（應用文獻裡很常見，見第 2 節），但**不能把它包裝成「完全依 Ajzen (2006) 方法論」**，正確的寫法是「信念構面採用單題直測（direct measure of belief），參考 [Wu & Chen, 2014 等] 的操作方式，而非 Ajzen 原始的期望值相乘法」。

### 1.2 Ajzen 對單題直測信念的立場

文件全文沒有一句話說「信念可以用單題直測」，也沒有一句話明確禁止——因為這個問題根本不在他討論的範圍內。他討論的「Reflective (Direct) Measures」永遠是指 ATT/SN/PBC/Intention 這四個高階構念，不是信念。他對信念的方法論立場只有一種：期望值相乘的間接測量法。這點請如實在論文限制段落交代，不要暗示 Ajzen 支持單題直測信念。

### 1.3 TACT 相容性原則原文要求

原文（Formative Research → Defining the Behavior）：

> "Before any work can begin, the behavior of interest must be clearly defined in terms of its **target, action, context, and time elements**."

範例定義：「Exercising for at least 20 min, three times per week for the next three months」（Target=自己, Action=exercising, Context=at least 20 min/three times per week, Time=next three months）。

**相容性的具體落實方式**（這是最關鍵的部分，Ajzen 自己在示範問卷裡怎麼做，而不只是說了什麼）：從行為信念、指令式/描述式規範信念、控制信念、Attitude、SN、PBC、Intention、一直到 Past Behavior，**每一題都逐字重複同一個 TACT 片語**「exercising for at least 20 min, three times per week for the next three months」，只有句子骨架（形容詞配對、referent、control factor）在變。原文明確指出這是刻意設計：

> "Note that the items are formulated to be exactly compatible with the behavioral criterion and to be self-directed."

**對照大哥現行草稿**：目前 BB/NB/CB/ATT/SN/PBC 每個構面內部的 5 題，分別指向住宿、餐飲、交通、遊程、購物 5 個不同子行為（例如 BB 第一題「選擇綠色旅宿可以幫助減少能源消耗」是住宿層級，第三題「選擇綠色交通可能會減少我的旅遊時間」是交通層級），但 GTBI（整體綠色旅遊行為意圖）和 GTB 卻是在「整體綠色旅遊行為」層級。這正是 Ajzen 這段話明確禁止的做法——每一題都應該重複同一個 TACT 片語（「從事綠色旅遊行為」），而不是把 5 題拆給 5 個子領域各一題。這不是「風格問題」，是相容性原則的直接違反，會系統性壓低 BB/NB/CB → ATT/SN/PBC → Intention 的路徑係數（因為左右兩端的行為定義對不上）。

---

## 2. 觀光／綠色消費 TPB 研究中「信念獨立直測 → 進 SEM」的實例

### 2.1 主範本：Wu, S.-I., & Chen, J.-Y. (2014)

**Wu, S.-I., & Chen, J.-Y. (2014).** A Model of Green Consumption Behavior Constructed by the Theory of Planned Behavior. *International Journal of Marketing Studies*, 6(5), 119-132. doi:10.5539/ijms.v6n5p119
全文 PDF（開放取用，CCSE 出版）：https://ccsenet.org/journal/index.php/ijms/article/download/40904/22602 （已逐頁核實）

**領域說明**：這篇是**綠色消費行為**（環保商品購買），不是觀光研究，但架構跟大哥的論文完全同構——這點請在論文文獻回顧裡誠實標註為「綠色消費領域之 TPB-SEM 範本」，不要誤植為觀光研究。台灣、7 點 Likert、信念構面獨立直測、進 SEM，三個條件都對上大哥先前初步調查的線索。

**架構**：Perceived benefit、Perceived risk（→ Attitude）；Normative belief、Moral obligation（→ Subjective Norm）；Control strength、Control belief（→ Behavioral Control）；Attitude、Subjective Norm、Behavioral Control（→ Behavioral Intention → Actual Behavior）。560 份有效問卷，AMOS SEM。

**規範信念（Norms belief, NB）逐字題項**（4 題，七點 Likert，α = 0.957，因素負荷 0.936–0.948）：

1. My families think I should practice green consumption.（我的家人認為我應該實行綠色消費）
2. My friends think I should practice green consumption.（我的朋友認為我應該實行綠色消費）
3. I value the opinion and feeling of my family on my green consumption.（我看重家人對我綠色消費的意見與感受）
4. I value the opinion and feeling of my friends on my green consumption.（我看重朋友對我綠色消費的意見與感受）

**主觀規範（Subjective norm, SN）逐字題項**（4 題，α = 0.904，因素負荷 0.852–0.910）：

1. I think purchasing environmental friendly products is appropriate.（我認為購買環保產品是合宜的）
2. I think purchasing environmental friendly products is righteous.（我認為購買環保產品是正當的）
3. I think purchasing environmental friendly products is necessary.（我認為購買環保產品是必要的）
4. I think purchasing environmental friendly products is to benefit other people as well as oneself.（我認為購買環保產品對他人及自己都有益）

**其他信念構面逐字題項**（供 CB 改寫參考）：

- Control force（CF，5 題，α=0.819）：I have sufficient money / time / resource / information and knowledge / capability to purchase environmental friendly products.
- Control belief（CB，3 題，α=0.841）：It's easy for me to practice green consumption；I can tell the differences between environmental products and ordinary products；I have much knowledge on green consumption.

**判別效度處理方式**（逐字）：
> "Gaski and Nevin (1985) stated that the correlation coefficient between any two constructs should be no more than the value of Cronbach's alpha of any single construct in order to ensure discriminant validity; this condition was also met."

全部 11 個構面（含 NB 與 SN）都通過這個準則。**方法論提醒**：Gaski & Nevin (1985) 這個「相關係數 < 任一構面 α」的準則，比現行常用的 Fornell-Larcker（√AVE > 構面間相關）或 HTMT 寬鬆很多，是比較舊、比較容易通過的判別效度檢定。建議大哥論文裡除了引用這個結構性設計邏輯，**正式檢定判別效度時用 Fornell-Larcker 或 HTMT**，不要只靠這一個準則就宣稱過關。

**注意一個小瑕疵（給大哥當借鏡，不要複製）**：這篇的 Perceived benefit／Perceived risk 題項（扮演「行為信念」的角色）其實寫在「環保產品」的屬性層級（如「environmental friendly products are more trustworthy／with better quality」），而不是「綠色消費行為」的行為層級，嚴格來說跟它自己的 Intention／Actual behavior 題項（「I would like to practice green consumption」）也有輕微的 TACT 落差。NB、SN、CF、CB、Attitude、BI 這幾個構面倒是內部一致地扣在「green consumption」這個行為片語上。這提醒大哥：**改寫 BB 題項時要小心，不要沿用「產品屬性」句型，要扣回「從事綠色旅遊行為」這個行為本身**。

### 2.2 找不到逐字題項、誠實標註的部分

**Chen, M.-F., & Tung, P.-J. (2014).** Developing an extended theory of planned behavior model to predict consumers' intention to visit green hotels. *International Journal of Hospitality Management*, 36, 221-230.

- 這是綠色旅宿 TPB 領域最常被引用的經典之一，查證確認：態度、主觀規範、PBC 對意圖均有顯著正向影響；另外納入「個人規範（personal norm）」與 SN 並列。
- **全文在 ScienceDirect 付費牆後（DOI 連結返回摘要層級），沒有取得可核實的逐字題項或信效度數據表**。本報告不引用其題項字句，只引用上述可從摘要/多方引用交叉確認的結論層級資訊。若大哥的學校圖書館有 ScienceDirect 訂閱權限，建議親自調閱全文附錄取得逐字題項，這篇作為「觀光/綠色旅宿」領域的信念直測範本，比 Wu & Chen (2014) 更貼題，值得優先取得全文。

### 2.3 觀光領域 TACT 相容直測示範（ATT/SN/PBC 層級，可作為措辭範本）

以下兩篇雖然沒有把信念做成獨立構面（只做 ATT/SN/PBC 的直接測量），但**示範了「全部題項在同一 TACT 片語下逐句重複」的正確寫法**，可以直接借用其句型結構：

**Cao, J., Qiu, H., & Morrison, A. M. (2023).** Self-Identity Matters: An Extended Theory of Planned Behavior to Decode Tourists' Waste Sorting Intentions. *International Journal of Environmental Research and Public Health*, 20(6), 5099. doi:10.3390/ijerph20065099
（全文核實於 https://pmc.ncbi.nlm.nih.gov/articles/PMC10049705/）

- 5 點 Likert。全部題項用同一個 TACT 開頭「During this trip, ...」，行為統一鎖在「waste sorting」這個行為本身，不拆成子場景：
  - Attitude：During this trip, I thought waste sorting was a wise / valuable / necessary / beneficial behavior.
  - Subjective Norm：During this trip, those important to me thought I should sort waste／expected me to sort waste／were delighted if I sorted waste.
  - PBC：During this trip, whether or not I sorted waste was up to me／I was capable of sorting waste／I was confident that if I wanted, I could sort waste.
- Cronbach's α：ATT 0.879、SN 0.887、PBC 0.824；AVE 0.647–0.726；Fornell-Larcker 判別效度成立（相關 0.523–0.639，均小於各自 √AVE）。
- **可借用的措辭機制**：SN 題項完全不具名 referent，只用「those important to me」統稱，且動詞用 thought I should／expected／were delighted——這是 Ajzen 官方指令式 SN 的標準句型（見 1.1 節），可直接借用來改寫大哥的 SN 題項。

**Pan, J., Teng, Y.-M., Wu, K.-S., & Wen, T.-C. (2022).** Anticipating Z-generation tourists' green hotel visit intention utilizing an extended theory of planned behavior. *Frontiers in Psychology*, 13, 1008705. doi:10.3389/fpsyg.2022.1008705
（全文核實於 https://pmc.ncbi.nlm.nih.gov/articles/PMC9764080/）

- 7 點 Likert。ATT α=0.943／AVE=0.815；SN α=0.924／AVE=0.868；PBC α=0.803／AVE=0.712；Fornell-Larcker 判別效度成立（SN 與 ATT 相關 0.590，小於兩者 √AVE）。
- 這篇同樣只做 ATT/SN/PBC 直接測量，沒有獨立的信念構面，且全文沒有討論 TACT 或相容性原則，列在此處是提供另一組七點量表的信效度數字級距供大哥的預試結果比對基準，**不作為 NB 措辭範本**。

---

## 3. NB（規範信念）vs. SN（主觀規範）判別寫法

### 3.1 文獻上兩者的一般寫法邏輯

| | 規範信念 NB | 主觀規範 SN |
|---|---|---|
| **理論定位**（Ajzen 官方文件） | 對「特定 referent」的信念元件，逐一列出 salient referents（如醫生、家人、朋友），每個 referent 各自配一題「該 referent 認為我該不該做」+ 一題「我依從這個 referent 的動機／認同這個 referent」 | 這些 referent 信念的加總聚合結果，用 1-2 題「整體」測，通常不具名特定 referent，只用「重要他人」「像我一樣的人」統稱 |
| **句型結構（Ajzen 官方範例）** | Injunctive：「[具名 referent] thinks that I should / should not [行為]」+「I want to do what [referent] thinks I should do」；Descriptive：「Most of my [referent] have [行為]」+「I want to be like my [referent]」 | 「Most people who are important to me approve of my [行為]」（agree–disagree）；「Most people like me [行為] in the past」（unlikely–likely） |
| **句型結構（Wu & Chen 2014 實證版，單題直測、無相乘）** | 具名兩個以上不同 referent 類別（家人、朋友），各一題「[referent] think I should [行為]」+ 各一題「I value [referent]'s opinion on my [行為]」——**共 4 題，兩兩成對但不相乘，各自獨立進 CFA** | 完全不具名 referent，改寫成對「行為本身」的整體道德／社會評價判斷：「appropriate／righteous／necessary／benefit others」——4 題 |
| **拉開判別效度的關鍵機制** | 題目主詞永遠是「某個具名的人／群體」，測的是「別人的期待」 | 題目主詞是「這個行為」，測的是「我對這個行為之社會可接受度／應然性的整體判斷」，不點名是誰施加壓力 |

### 3.2 為什麼現行草稿的 NB／SN 會撞在一起

大哥目前草稿（`docs/research` 同批文件外、論文本體第三章）NB 與 SN 題項節錄如下：

> NB：「我的家人會希望我選擇綠色餐廳」「我的朋友會支持我選擇友善環境的旅宿」
> SN：「我認為家人會支持我在旅遊時應該選擇綠色餐廳」「我的朋友圈都贊同我在旅遊時選擇綠色旅宿」

兩組題項都是「具名 referent + 態度動詞（希望/支持/贊同）+ 子行為」，句型結構幾乎同構，只是動詞從「希望」換成「支持」、從「支持」換成「贊同」——這些動詞在中文語境裡語意距離太近，受訪者很難在心理上區分「家人希望我做」跟「家人支持我做」有什麼不同，這就是判別效度會出問題的根源，也符合大哥自己的診斷。

### 3.3 建議的拉開策略（綜合 1.1、2.1、2.3 節文獻）

- **NB**：維持具名 referent（家人、朋友二選一或都留），但把「態度動詞」換成 Ajzen 官方的「認為我應該（think I should）」句型，並加入 Wu & Chen (2014) 驗證有效的第二層「我重視他們意見」句型（這一層近似 motivation to comply，但單題直測、不相乘）。
- **SN**：完全拿掉具名 referent，改寫成「大部分對我重要的人」這種聚合式統稱（Ajzen 官方 SN 標準句型），或進一步比照 Wu & Chen (2014) 改寫成對「行為本身」的整體社會評價判斷（合宜的／應該的／值得提倡的），不出現任何具名對象。兩條路線任選一條，但務必跟 NB 的「具名 referent」句型徹底分開。

---

## 4. 改寫題項草稿

以下題項全部統一鎖定同一個 TACT 定義：**Target=我自己（受訪遊客）、Action=從事、Object=綠色旅遊行為（涵蓋食、宿、遊、購、行等面向對環境友善的選擇）、Context=旅遊過程中、Time=下一次旅遊**——與現行草稿 BI 題項的「下次旅遊時」時間定義對齊，也與 ATT/SN/PBC/Intention 的整體層級對齊。五點 Likert（沿用現行草稿量表格式）。

### 4.1 行為信念（Behavioral Belief, BB）—— 5 題

| # | 題項 | 改編來源 |
|---|---|---|
| BB1 | 我認為在旅遊時從事綠色旅遊行為，可以減少我對環境造成的負面影響。 | 改寫自現行草稿 BB1「選擇綠色旅宿可以幫助減少能源消耗」，由住宿子層級提升為整體行為層級；句型結構參照 Ajzen (2006) 行為信念範例「My exercising... will result in...」 |
| BB2 | 我認為在旅遊時從事綠色旅遊行為，能讓我獲得更有意義、品質更好的旅遊體驗。 | 整合現行草稿 ATT4「購買環保產品是有價值的」與 BB4「參與綠色遊程讓我學到更多東西」，提升到整體行為層級 |
| BB3 | 我認為在旅遊時從事綠色旅遊行為，需要花費額外的金錢或時間。 | 改編自 Wu & Chen (2014) Perceived Risk 構面邏輯（負向結果信念），但改寫成行為層級而非產品屬性層級，避免重蹈該文 TACT 落差的瑕疵（見 2.1 節「小瑕疵」提醒） |
| BB4 | 我認為在旅遊時從事綠色旅遊行為，有助於支持在地社區與環境永續發展。 | 整合現行草稿 BB5「綠色購物讓我更認識當地文化」，提升為整體行為層級並貼齊 Ajzen「having a faster recovery」式的正向結果信念句型 |
| BB5 | 我認為在旅遊時從事綠色旅遊行為，能讓我對自己的旅遊選擇感到心安、無愧於環境。 | 新增，補足情感性結果評價面向（Fishbein & Ajzen 2010 對 outcome evaluation 的情感面向要求），句型參照 Ajzen 官方範例「My having a faster recovery... is good」的評價式結構 |

### 4.2 規範信念（Normative Belief, NB）—— 4 題

| # | 題項 | 改編來源 |
|---|---|---|
| NB1 | 我的家人認為我在旅遊時應該從事綠色旅遊行為。 | 逐句改編自 Wu & Chen (2014) NB1「My families think I should practice green consumption」，行為代換為「從事綠色旅遊行為」 |
| NB2 | 我的朋友認為我在旅遊時應該從事綠色旅遊行為。 | 逐句改編自 Wu & Chen (2014) NB2「My friends think I should practice green consumption」 |
| NB3 | 我看重家人對我從事綠色旅遊行為的看法與感受。 | 逐句改編自 Wu & Chen (2014) NB3「I value the opinion and feeling of my family on my green consumption」 |
| NB4 | 我看重朋友對我從事綠色旅遊行為的看法與感受。 | 逐句改編自 Wu & Chen (2014) NB4「I value the opinion and feeling of my friends on my green consumption」 |

（如需 5 題，可依 Ajzen (2006) 描述式規範信念補一題：「像我一樣的人，在旅遊時大多會從事綠色旅遊行為」——但這一題語意較接近描述性規範／社會期望，非本論文現有 NB 定義涵蓋的「重要他人期待」，是否加入建議先與指導教授確認構念定義範圍。）

### 4.3 控制信念（Control Belief, CB）—— 4 題

| # | 題項 | 改編來源 |
|---|---|---|
| CB1 | 我有足夠的時間，讓我在旅遊時從事綠色旅遊行為。 | 逐句改編自 Wu & Chen (2014) Control force「I have sufficient time to purchase environmental friendly products」 |
| CB2 | 我有足夠的金錢，讓我在旅遊時從事綠色旅遊行為。 | 逐句改編自 Wu & Chen (2014) Control force「I have sufficient money to purchase environmental friendly products」 |
| CB3 | 我有足夠的資訊與知識，知道如何在旅遊時從事綠色旅遊行為。 | 逐句改編自 Wu & Chen (2014) Control force「I have sufficient information and knowledge on environmental friendly products」，並整合現行草稿 PBC2「我知道如何找到綠色餐廳」的知識面向 |
| CB4 | 在旅遊目的地，要找到從事綠色旅遊行為的機會或管道，對我來說很容易。 | 整合現行草稿 CB3「在旅遊中找到綠色餐廳對我來說很容易」與 CB5「選擇綠色旅宿對我來說不會有太多障礙」，提升為整體行為層級；句型參照 Ajzen (2006) 控制信念範例的「facilitate」邏輯 |

（如需 5 題，可加入 Wu & Chen (2014) Control belief 構面的「I can tell the differences」邏輯，改寫為：「我能分辨哪些旅遊選擇算是『綠色旅遊行為』，哪些不是」——這一題補足「辨識能力」這個控制信念子面向，Wu & Chen (2014) 原文獨立列為 Control belief 構面，與 Control force 有區隔。）

---

## 5. NB vs. SN 對照表（供論文方法論小節直接使用）

| 面向 | 規範信念 NB | 主觀規範 SN |
|---|---|---|
| 測量對象 | 特定重要他人（家人、朋友）對「我」的期待 | 我對「這個行為」整體社會壓力／評價的感知 |
| 是否具名 referent | 是，逐一具名（家人、朋友） | 否（若採 Wu & Chen 2014 路線，完全不提及具名對象） |
| 句型骨架 | 「[具名對象] 認為我應該……」／「我看重 [具名對象] 的意見」 | 「我認為從事……是合宜的／應該的／有益眾人的」（不點名施壓者） |
| 理論位階 | Ajzen TPB 中主觀規範的「元件」（信念層級） | Ajzen TPB 中的「聚合構念」（態度性層級），由 NB 加總而來但本研究採直測法各自獨立測量 |
| 建議改寫依據 | Wu & Chen (2014) NB1-NB4 逐句改編 | Wu & Chen (2014) SN1-SN4 邏輯（不具名、評價式判斷）或 Ajzen (2006) 官方「most people who are important to me」聚合式句型二擇一 |
| 判別效度檢核建議 | 與 SN 分開跑 Fornell-Larcker／HTMT，不要只用 Gaski & Nevin (1985) 相關係數 < α 準則 | 同左 |

---

## 6. 待補查證清單（誠實列出，不編造）

- Chen & Tung (2014) IJHM 全文逐字題項與信效度表——需要 ScienceDirect 全文權限，本次未取得。
- 觀光領域（非綠色消費）中，NB 與 SN 同時列為獨立構念、且正式報告 Fornell-Larcker／HTMT 判別效度通過的乾淨範例——查找範圍內未找到可逐字核實的個案，Wu & Chen (2014) 是綠色消費而非觀光，這點請在論文中如實標註為「借用相鄰領域（綠色消費）的判別效度處理邏輯」，不要宣稱是觀光領域的直接前例。
- 若學校圖書館有 Elsevier／ScienceDirect 訂閱，建議優先調閱 Chen & Tung (2014) 全文附錄，取得題項後可直接補進本報告第 2.2 節與第 4 節的改寫來源。

---

## 參考文獻（已全文核實者標註 ✅，未取得全文者標註 ⚠️）

- ✅ Ajzen, I. *Constructing a Theory of Planned Behavior Questionnaire*. https://people.umass.edu/aizen/pdf/tpb.measurement.pdf
- ✅ Wu, S.-I., & Chen, J.-Y. (2014). A Model of Green Consumption Behavior Constructed by the Theory of Planned Behavior. *International Journal of Marketing Studies*, 6(5), 119-132. https://doi.org/10.5539/ijms.v6n5p119
- ✅ Cao, J., Qiu, H., & Morrison, A. M. (2023). Self-Identity Matters: An Extended Theory of Planned Behavior to Decode Tourists' Waste Sorting Intentions. *IJERPH*, 20(6), 5099. https://doi.org/10.3390/ijerph20065099
- ✅ Pan, J., Teng, Y.-M., Wu, K.-S., & Wen, T.-C. (2022). Anticipating Z-generation tourists' green hotel visit intention utilizing an extended theory of planned behavior. *Frontiers in Psychology*, 13, 1008705. https://doi.org/10.3389/fpsyg.2022.1008705
- ⚠️ Chen, M.-F., & Tung, P.-J. (2014). Developing an extended theory of planned behavior model to predict consumers' intention to visit green hotels. *International Journal of Hospitality Management*, 36, 221-230.（僅摘要層級，全文題項未核實，付費牆擋下）

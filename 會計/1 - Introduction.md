# 何謂會計？

>Accounting is the information system that identifies, records, and communicates the economic event of an organization to interested users.

白話文：會計資訊是用來紀錄企業買賣商品／服務的故事。

### 三項會計活動

```mermaid
flowchart LR
    id1("認定")
    id2("紀錄")
    id3("溝通")
    id1 --> id2
    id2 --> id3
```

### 有效的資訊

有效的資訊必須擁有兩個特性：

- Relevance（實用性）：財務資訊須具備影響決策的能力
- Faithful Representation（忠實表達）：財務資訊須與事實一致

### 會計的使用者

- 內部使用者
    - 公司的管理階層
    - 使用「管理會計」(managerial accounting)
- 外部使用者
    - 投資人、債權人、稅捐稽徵處、主管機關、客人、工會
    - 使用「財務會計」(financial accounting)

# 會計準則

>有效的財務報告仰賴正確且道德的行為。

### 兩大組織與兩大準則

|組織|準則|主要使用者|特色|
|:-:|:-:|:-:|:-:|
|IASB|IFRS|國際通用|Principle-based（只做原則性的「建議」）|
|FASB|GAAP|美國|Rule-based（詳細「規範」每一個細則）|

>[!Info]
>台灣本來有自己的 GAAP (ROC GAAP)，但自 2013 開始採用 IFRS。

### 資產價值的兩種衡量原則

###### Historical Cost Principle

- 資產的價值等於其「買入成本」
- 適用於 fixed assets（固定資產），如：不動產、廠房及設備 (Property, Plant and Equipment/PP&E)

###### Fair Value Principle

- Fair value 中文為「公允價值」
- 資產的價值等於其「被處分的價格」，「處分」包括交易、所有權移轉
- 適用於經常被交易的資產，如：證券

>[!Note]
>IFRS 允許對 PP&E 進行 revaluation（資產重估價），但 GAAP 不允許。

### IFRS 的對財務報表的基本假設

###### Monetary Unit Assumption

會計紀錄只包含可以用貨幣表達的資料。

- 優點：可以量化，就有比較的標準
- 缺點：有些東西難以量化，比如服務的品質、老闆及員工的健康狀況、道德水平

###### Economic Entity Assumption

個人與企業的活動要分開，即使個人是老闆也不例外。

###### Accrual Basis

會計資訊應在經濟活動／事件發生當下即認列，不是等實際收到錢才紀錄。

###### Going-Concern Assumption

假設企業會永久經營下去，所以：

- 資產可以持續使用至目的完成 → 須要「折舊」
- 負債可於到期時清償
- 不用「清算」公司價值

但當企業打算解散時，就應放棄此假設。

### 三種企業型態

###### Proprietorship（獨資）

業主對於債務有「無限清償責任」。

>[!Note]
>在法律上，企業與業主是同一個體，但在會計中，還是要遵守 [#Economic Entity Assumption](</./會計/1 - Introduction.md#Economic Entity Assumption>)。

###### Partnership（合夥）

所有合夥人對於債務皆有無限清償責任。

###### Corporation（公司）

- 所有權被分割為若干份可移轉的股份
- 擁有股份的人稱為股東
- 股東對於債務僅有「有限清償責任」，清償上限為出資額

# 會計恆等式

$$
\large{\underset{資產}{\textnormal{Assets}} = \underset{負債}{\textnormal{Liabilities}} + \underset{股東權益}{\textnormal{Stock-Holders' Equity}}}
$$

### Assets（資產）

具備下列必要條件者，可以被視為公司的資產：

- 公司可以控制（但不一定有所有權）
- 現在或預期未來可以產稱經濟效益

>[!Note]
>Employees (員工) 不是公司資產，因為公司控制不了員工！

資產的分類方式有很多，包括：

###### 以流動性區分

- Current assets：一年內可兌現
- Fixed assets (Non-current assets)：一年內無法兌現

>[!Note]
>Non-current assets 有可能隨著時間的推移而變成 current assets，比如有些 notes receivable (應收票據) 會從超過一年到期變成一年內到期。

###### 以形體區分

- Tangible assets
- Intangible assets

### Liabilities（負債）

公司因過去的經濟活動產生的義務，該義務使得未來預期會有經濟資源流出。

Liabilities 同時也被視為「債權人對公司資產的請求權」。

###### 以流動性區分

- Current liabilities：須在一年內清償
- Non-current liabilities：無須在一年內清償

### Share-Holders' Equity（股東權益）

>[!Note]
>其實會計恆等式應該寫成 $E = A - L$ ，因為 share-holders' equity 的定義就是「資產減去負債」。

Share-holders' equity 簡稱 equity，又稱為 residual equity (剩餘權益)，因為法律上債權人對於公司資產具有優先請求權，剩下的才是股東／公司所有權人對公司資產的請求權。

常見的 equity 包括：

###### Common Stock (Share Capital - Ordinary)

$$
\underset{普通股股本}{\textnormal{Common Stock}} = \underset{面額}{\textnormal{par value}} \times \underset{在外流通股數}{\textnormal{shares outstanding}}
$$

###### Additional Paid-In Capital (APIC)

$$
\underset{資本公積}{\textnormal{APIC}} = (\textnormal{market value} - \textnormal{par value}) \times \textnormal{shares outstanding}
$$

###### Retained Earnings

$$
\underset{保留盈餘}{\textnormal{Retained Earnings}} = \underset{淨利}{\textnormal{net income}} - \underset{股利}{\textnormal{dividends}}
$$

###### Other Comprehensive Income (其他綜合損益, OCI)

---

Assets, liabilities, share-holders' equity 同時也是「資產負債表」的三大要素。

# 衡量公司的經營績效

一般常用 [EPS](</財務管理與投資/2 - 各種財務指標.md#EPS>) 衡量公司的經營績效：

$$
\textnormal{EPS} = {\textnormal{net income} - \overset{特別股股利}{\textnormal{preferred dividends}} \over \textnormal{Avg. shares outstanding}}
$$

其中 $\textnormal{Net Income} = \textnormal{Revenues} - \textnormal{Expenses}$

### Revenues

Revenues 包括以下兩種：

- 公司提供之產品或服務賣出後產生的收入
    - 如果公司還未提供產品／服務就先收錢，這種收入稱為 unearned revenues（預收收入），==unearned revenues 屬於 liabilities==。
- 公司其他經濟活動（如：金融商品的增值、處分 PP&E）產生的利益

### Expenses

Expenses 包括以下兩種：

- 公司為了提供產品或服務所產生的支出
    - 包括 wage expense (薪資費用)、interest expense (利息費用)、deprecation (折舊)、taxes (稅) … 等
- 公司其他經濟活動產生的損失

---

>[!Info] 延伸會計恆等式
>$$
>\eqalign{
>A
>&= L + (\textnormal{Common Stock} + \textnormal{Retained Earnings})\\
>&= L + (\textnormal{Common Stock} + \textnormal{Net Income} - \textnormal{Dividends})\\
>&= L + (\textnormal{Common Stock} + \textnormal{Revenues} - \textnormal{Expenses} - \textnormal{Dividends})
>}
>$$

# 經濟活動對會計恆等式的影響

- 現金增資
    - 等式左側：Cash 增加 → Assets 增加
    - 等式右側：Common stock 增加 → Equity 增加
- 購買設備（付現）
    - 等式左側：Cash 減少、PP&E 增加 → Assets 不變
    - 等式右側：不變
- 賒購設備 (purchase on account)
    - 等式左側：PP&E 增加 → Assets 增加
    - 等式右側：Account Payable 增加 → Liabilities 增加

# 參考資料

- <https://ifinbook.tabf.org.tw/File/EBook/381723/S0307/files/basic-html>

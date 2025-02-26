# Financial Accounting

> Karry Ren
>
> 期末考试只涉及到后面 8 到 12 共五章的内容，所以在此重新打开了一个 Note 进行后五章复习的梳理。
>
> 我深知自己在期中后对很多知识的理解都没有到位，加之没有及时的复习，在复习前对知识的掌握程度是完全不足够考试的。所以最后冲刺阶段，我留了两整天的时间来完成此次复习，核心有以下三个阶段：
>
> - 完成基本知识的扫盲，参考 PPT，师姐笔记和心蕾笔记，对于所有的知识都要有基本且深刻的理解；
> - 完成基本题目的重做，重做老师上课讲过的题目并和基础知识点匹配；
> - 完成基础知识 + 拔高题目的专项训练，需要一字一句，把每一个细节都掌握。
>
> 基于期中考试，我们不难发现，40 道选择能够考察太多的细节了，所以必须要每一个细小的部分都注意到！



## CH 8. REPORTING AND ANALYZING RECEIVABLES

> 这一章核心点是资产中的**应收账款**，之前我们已经有了一定的了解，但是还需进行深入的探索。重点有以下 9 点：
>
> 1. Identify the **different types** of receivables (8.1).
> 2. Explain how accounts receivable are **recognized** in the accounts (8.2).
> 3. Describe the methods used to account for **bad debts** (8.3).
> 4. Compute the **interest** on notes receivable (8.4).
> 5. Describe the entries to record the **disposition** of notes receivable (8.4).
> 6. Explain the **statement presentation** of receivables (8.4).
> 7. Describe the principles of sound (健全的) accounts **receivable management** (8.5).
> 8. Identify **ratios** to analyze a company’s receivables (8.5).
> 9. Describe methods to **accelerate the receipt** of cash from receivables (8.5).

### Words

- due: 应得的
- amounts owned: 欠的数量
- invoice: 账单
- claims: 债权, 期中考试提到了这个概念, stock holders' equity 就是 stock holders' 的 claims
- loans: 贷款
- advances for employees: 预先付给雇员的款项
- grant credit: 授予信用 (授信额度)
- payee: 收款人, 借出去钱的人
- income taxes refundable: 可退回所得税
- promissory note: 本票
- default: 违约
- allowances for doubtful accounts: 坏账准备金 (十分重要的一个概念)
- immaterial: 非物质的
- net realizable value: 可变现净值

### 8.1 Types of Receivables

**Receivables** 的概念: refer to amounts due from individuals and companies that are expected to be collected in cash

- **Accounts receivable**: amounts owned by customers that result from the sale of goods and services

  > 有如下几个重要特点。1）related to trade: 和交易相关，主要来自于卖东西或服务；2）do not require payment of interest；3）short due date: are expected to be collected within 30 to 60 days（期限一般都比较短，除非特殊情况，否则一直都是在 current assets 中）；4）subsidiary ledger kept with separate accounts for each customer（每个顾客独立使用一个帐户）.

- **Notes receivable**: claims for which formal instruments of credit are issued as evidence of debt

  > 有如下几个重要特点。1）trade or non-trade: 可能和交易相关，也可能无关；2）normally require payment of interest. 3）extend for time periods of 60-90 days or longer（期限一般比较长，可能是 current 一年以下，也可能是 long-term 一年以上，具体要看情况）

- **Other receivables**: Non-trade receivables (和交易无关，通过金融过程产生), including interest receivable, loans to company officers (eg: I OWN YOU, IOU. 这个地方所讲的就是 P2P 直接借贷), advances to employees, and income taxes refundable.

### 8.2 How to recognize accounts receivable?

> 一般在形式上有两种情况会产生 accounts receivable：
>
> - 卖服务或者卖东西的时候用 accounts 而不用 cash, 这一部分来自于销售商品那一章
> - 自己发行信用卡, 让别人买东西 (本质也是赊销)

#### a. Sales on account

- Step 1. Sales on account (赊销产品) 

  > Jordache Co., on July 1, 2012, sold merchandise on account to Polo Company for $1,000 terms 2/10, n/30.
  >
  > ```
  > Dr. A/R    1,000
  > 	Cr. Sales Revenue   1,000
  > ```

- Step 2. Return goods (退换商品) 

  > On July 5, Polo returns merchandise worth $100 to Jordache Co.
  >
  > ```
  > Dr. Sales R&A    100
  > 	Cr. A/R    100
  > ```

- Step 3. Receive cash for A/R (收到现金) 

  > On July 11, Jordache receives payment from Polo Company for the balance due.
  >
  > ```
  > Dr. Cash                882
  > 		Sales Discounts     18 (900 * 2%)
  > 	Cr. A/R                            900
  > ```

#### b. Retailer's own credit card

Walmart can issue credit cards you can buy them. 顾客在购买东西的时候, 可直接使用信用卡, 而不需要使用现金, 增加了坏账风险。

```
Dr. A/R
	Cr. Sales Revenue
```

需要注意的是, 可能因为长时间不还钱, 开始收利息, 收利息的时候本金可能还没还, 要进行好区分。

### 8.3 Account for bad debts

> 有 receivable 就一定有坏账, 不同的坏账, 也有不同的记录方法, 主流是两种记录方法。
>
> - Sales on account raise the possibility of accounts not being collected. 
> - The seller records losses that result from extending credit as **Bad Debts Expenses**.

#### a. Direct write-off 直接核销法

For **immaterial** amounts, use the direct write-off method. 直接核销是最简单的方式, 但是并不好, 所以基本上不会使用

> ```
> Dr. Bad debts expense
> 	Cr. A/R
> ```

#### b. Allowance method 津贴方法 (可能有一个大题 E8-3, P8-2A)

For material amounts, use the allowance method. 方法较为复杂, 但能够很清晰地记录不同的阶段, 一般都会使用。这种方法的核心是针对 A/R 引入了一个 contra 账户: allowance of doubtful accounts (allowance of D/A) (Dr. 为减, Cr. 为增), 通过会计期末的调整**评估可能有多少坏账**向这个账户中加钱, 作为 Expenses。最后在 B/S 中需要在 A/R 中减去这个账户。其核心包括如下四步：

- Step 1. Credit sales.

  > ```
  > Dr. A/R
  > 	Cr. Sales rev.
  > ```

- Step 2. End of Accounting Period (do adjusting) 在会计期末进行**评估调整**, 设立 Allowance for D/A 条目, 注意这个时候并没有坏账产生! 只不过是进行的评估, 下个会计期末完全可能调整回来。本条目的会计含义就是一个坏账池子, 什么时候产生坏账就放水。

  > Hampson Furniture has credit sales of \$1,200,000 in 2012, of which \$200,000 remains uncollected on December 31. The credit manager estimates that \$12,000 of these sales will prove uncollectible2.
  >
  > ```
  > Dr. Bad debts expense    200
  > 	Cr. Allowance for D/A     200
  > ```

- Step 3. Recording Write-Off of an Uncollectible Account 真正的坏账产生的时候就开始放水, 减少 Allowance 的同时, 减少 A/R

  > The vice-president of finance of Hampson Furniture on March 1, 2013, authorizes a write-off of the $500 balance owed by R. A. Ware. The entry to record the write-off is
  >
  > ```
  > Dr. Allowance for D/A    500
  > 	Cr. A/R-Hamson Furniture    500
  > ```

- Step 4. Recovery of an Uncollectible Account 之前被记做坏账的部分现在恢复了, 并且收到的现金。这其中有两步, 一是坏账恢复流出去的水又可以回来了, 二是收到现金 Cash 增加 A/R 减少

  > On July 1, R. A. Ware paid the $500 amount that Hampson Furniture had written off on March 1. Hampson makes these entries:
  >
  > ```
  > Dr. A/R    500
  > 	Cr. Allowance for D/A    500
  > Dr. Cash    500
  > 	Cr. A/R    500
  > ```

基于上述分析, 可以发现其中的一个关键问题是如何在会计期末评估 Allowance。在此使用的是: Percentage of receivables basis to estimate the Allowance, 即使用坏账百分比法进行估计。(E8-5)

- Under the **percentage of receivables** basis, management establishes a percentage relationship between the amount of receivables and expected losses from uncollectible accounts.
- **Aging the accounts receivable** - customer balances are classified by the time they have been unpaid. 通过账龄来分析可能的比例, 具体例子看下图, 可以看到账龄越长, 收回的概率越小, 坏账的部分越大

<img src="./NOTE.assets/Fig 8-1.png" alt="Fig 8-1 " style="zoom:50%;" />

对于 Allowance 来说, 这就是一次账户调整, 遵循之前调整的思路, 需要在分类账中做 Adj.

> Assume the unadjusted trial balance shows Allowance for Doubtful Accounts with a credit balance of \$528. Prepare the adjusting entry assuming \$2,228 is the estimate of uncollectible receivables from the aging schedule.
>
> ```
> Dr. Bad debts expense    1,700
> 	Cr. Allowance for doubtful accounts    1,700
> ```
>
> <img src="./NOTE.assets/Fig 8-2.png" alt="Fig 8-2" style="zoom:50%;" />

当然, 我们在期末需要衡量 A/R 的具体数额, 这个时候就需要进行 Valuing, 只需要使用 A/R - Allowance 就能得到 **Net realizable value**.

### 8.4 Notes Receivable

#### promissory note

Companies may grant credit in exchange for a promissory note. A **promissory note** is a written promise to pay a specified amount of money on demand or at a definite time 简单来说 promissory note 就是 N/R 的象征.  Promissory notes may be used 

- when individuals and companies lend or borrow money (借钱, non-trade)
- when the amount of transaction and credit period exceed normal limits
- in settlement of accounts receivable (客户短期资金不足, 将 A/R 延长为 N/R)

#### a. Record N/R

基于上述分析, 可以发现产生 N/R 分成三个部分 (E8-8)

```
Dr. N/R
	Cr. Cash (non-trade, 借钱)
		  or xxx Rev (产生 Revenue, 别人想要长期赊账)
		  or A/R (将 A/R 转换为 N/R)
```

> Brent Company wrote a $1,000, two-month, 8% promissory note dated May 1, to settle an open account.
>
> ```
> Dr. Notes receivable    1,000
> 	Cr. Accounts receivable    1,000
> ```

N/R 需要注意每一期都要调整利息 Interest, 需要进行如下记账, 计算 Interest 的公式也很简单, 不同的单位下有不同的计算方式
$$
\text{Face Value of Note} \times \text{Annual Interest Rate} \times \text{Time in Terms of One Year}
$$

```
Dr. Interest Receivable
	Cr. Interest Rev
```

<img src="./NOTE.assets/Fig 8-3.png" alt="Fig 8-3" style="zoom:50%;" />

> 一次性记账的情况. Wolder Co. lends Higley Inc. $10,000 on June 1, accepting a five-month, 9% interest note. If Wolder presents the note to Higley Inc. on November 1, the maturity date, Wolder’s entry to record the collection is:
>
> ```
> Dr. Cash    10,375
> 	Cr. Notes receivable    10,000
>          Interest revenue    375 ($10,000 x 9% x 5/12)
> ```
>
> 中间有调整的情况, 对 Accrual of Interest 进行调整. Suppose instead that Wolder Co. prepares financial statements as of September 30. The adjusting entry by Wolder is for four months ending Sept. 30. Prepare the entry Wolder’s would make to record the honoring of the Higley note on November 1.
>
> ```
> Sep 30. Dr. Interest receivable    300
> 					Cr. Interest revenue    300 ($10,000 x 9% x 4/12)
> Nov 1.  Dr. Cash    10,375
> 					Cr. Notes receivable    10,000
> 				      Interest revenue    75 ($10,000 x 9% x 1/12)
> 				      Interest receivable 300
> ```

最后收回得到现金的时候应该按照如下的方式记账

```
Dr. Cash
	Cr. N/R (本金 Face Value of Note)
		  Interest Receivable (之前 Adj 出来的 Interest)
		  Interest Revenue (本期的 Interest Rev)
```

#### b. Valuing Notes Receivable

和 A/R 一样的处理方法, 仍然是通过 Allowance 这一 Contra Account 进行中间性处理。通过会计期末调整计提 Allowance, 在最后需要衡量的时候把 N/R 减去 Allowance 得到 net realizble value

- Report short-term notes receivable at their **cash (net) realizable value**. 
- Estimation of cash realizable value and bad debts expense are done similarly to accounts receivable.
- Allowance for Doubtful Accounts is used.

#### c. Disposing of Notes Receivable

N/R 到期的时候, 需要对其做最后的处理:

- Notes may be held to their maturity date. (正常到期)
- Maker may default and the payee must make an adjustment to the account. (违约, 借款方需要做调整)
- Holder speeds up conversion to cash by selling the note receivable. (通过出售票据, 加快变现速度, 转移风险)

**Dishornerd Note** 如果遇到违约的票据, 该如何处理 ?

> horned note: A note is **honored** when its maker pays it in full at its maturity date.
>
> dishonored note: A **dishonored note** is not paid in full at maturity. Dishonored note receivable is no longer negotiable.

- If no hope of collection, write-off

  ```
  Dr. Allowance for D/A
  	Cr. N/R
  ```

- Negotiation of new terms, 通过协商将 N/R 做转化, 比如转为 A/R 就可以化解。在转化的时候要顾及到 Interest, 同时需要重新制定新的还款期限。

  ```
  Dr. A/R
  	Cr. N/R
  		  Interest Receivable
  		  Interest Revenue
  ```

到此, 我们就将 A/R 和 N/R 的基本含义搞清楚了, 其最终是如何呈现在 Statement 中的呢?

<img src="./NOTE.assets/Fig 8-4.png" alt="Fig 8-4" style="zoom:50%;" />

### 8.5 Receivable Management — Five steps to manage receivable

<img src="./NOTE.assets/Fig 8-5.png" alt="Fig 8-5" style="zoom:50%;" />

**Determine to whom to extend credit.**

> Analyze other entities, evaluating the ability to pay back. 分析识别借款方的风险, 进行正确借款

- If the **credit policy is too tight**, you will lose sales. 
- If the **credit policy is too loose**, you may sell to a customer who will pay either very late or not at all. 
- It is important to **check references** for potential new customers as well as periodically to check the financial health of continuing customers.

**Establish a payment period.**

> 例如 credit n/30, 给予早还款方一定的优惠

- Companies should determine a required payment period and communicate that policy to their customers. 和客户商量
- The payment period should be consistent with that of competitors. 和市场一致

**Monitor collections.**

> Take a look at the aging of receivables, how many days past due.

- Companies should prepare an accounts receivable aging schedule at least monthly. 
- The treasurer (财务主管) should prepare a cash budget.
- Significant concentrations of credit risk must be discussed in the notes to its financial statements.

**Evaluate the liquidity of receivables, using ratios analysis.** (概念习题参考 P8-7A, 计算参考 P8-9A)
$$
\text{Receivable trunover ratio (RTO)} = \frac{\text{Net credit sales}}{\text{Avg. Net A/R}}
$$

> Assess the liquidity of the receivables. + Measure the number of times, on average, a company collects receivables during the period. 关于这个比率有两个点需要注意：
>
> - Net credit sales 是指通过赊账卖出去的产品，现金卖出去的不算在其中, Net credit sales = Net sales- cash sales
> - Net A/R = A/R - Allowance for D/A (如果 write-off bad debt, Net A/R 是不会变的！)

越高的 RTO 意味着 A/R 收回的越快，说明 A/R 管理得越好, 流动性越好
$$
\text{Avg. Collection period} = \frac{\text{365}}{\text{RTO}}
$$

> Used to assess the effectiveness of credit and collection policies.  
>
> The Collection period should not exceed the credit term period.

这个比率的含义就是多少天能收回 A/R 越小说明流动性越好, 收回得越快。如果收回的时间比借款的时间还长, 就可能出现问题。

**Accelerate cash receipts from receivables when necessary.**

> 如果发现自己的收回效率比较低, 流动性很差, 就需要加快应收的回收速度, 主要有以下两种方法。

- National credit cash sales, 通过第三方信用卡机构来辅助收款

  > 我们允许顾客赊账买东西, 但必须使用指定的信用卡, 这意味着我们可以直接从信用卡发行方那拿到 Cash, 把收款风险转嫁到他们身上。在这个过程中我们需要支付一些**服务费用**。这和我们自己发行的信用卡有天壤之别, 我们之所以要发信用卡, 核心就是因为想通过 A/R 来及时满足顾客, 但此处的目的是为了减少 A/R 加快现金收回速度。
  >
  > **Three parties** are involved when credit cards are used.
  >
  > - credit card issuer
  > - retailer
  > - customer
  >
  > 比如: Morgan Marie purchases $1,000 of compact discs for her restaurant from Sondgeroth Music Co., and she charges this amount on her Visa First Bank Card. The service fee that First Bank charges Sondgeroth Music is 3%.
  >
  > ```
  > Dr. Cash 970
  >     Service charge expense 30
  > 	Cr. Sales revenue 1000
  > ```

- Sales of receivable, 直接将 receivable 卖掉

  > 直接卖掉的底层逻辑是三条原因：
  >
  > - Size. 规模太大
  > - Companies may sell receivables because they may be the only reasonable source of cash. 
  > - Billing and collection are often time-consuming and costly.
  >
  > 常见的操作是将 Receivable 卖给中介机构 Factor (A **factor** is a finance company or bank that buys receivables from businesses for a fee and then collects the payments directly from the customers.)
  >
  > 比如: Hendredon Furniture **factors** $600,000 of receivables to Federal Factors, Inc. Federal Factors assesses a service charge of 2% of the amount of receivables sold.
  >
  > ```
  > Dr. Cash 	588,000
  > 	  Service charge expense 	12,000
  > 	Cr. Accounts receivable			600,000
  > ```



## CH 9. REPORTING AND ANALYZING LONG-LIVED ASSETS

> 这一章的核心是分析长期资产, 对如何计算价值以及如何计算折旧都进行了详尽的展示。
>
> 1. Describe how the **cost principle** applies to **plant assets.** (9.1)
> 2. Explain the concept of **depreciation**. (9.2)
> 3. Compute periodic **depreciation** using the straight-line method and contrast its expense pattern with those of other methods. (9.2)
> 4. Describe the procedure for **revising** periodic depreciation. (9.3)
> 5. Explain how to account for the **disposal** of plant assets. (9.4)
> 6. Describe methods for **evaluating** the use of plant assets. (9.5)
> 7. Identify the basic issues related to reporting **intangible assets**. (9.6)
> 8. Indicate how long-lived assets are **reported** in the financial statements. (9.7)

### Words

- tangible asset: 有形资产 (有大小和形状)
- closing cost: 手续费/结算费用
- excavation: 挖掘
- contractor: 承包商
- expenditures: 支出

### 9.1 Plant Assets (PPE)

#### a. The definition of PPE

A plant asset (also called property, plant, and equipment, or PPE, or **fixed assets**) is a **tangible** asset with **a useful life of more than one year** that is used **in the operations of a business** (not intended for sale to customers). 重点关注三个特征:

- physical substance (a definite size and shape) 一定是有型的, 能看得见摸得着的
- expected to **provide service** to the company for a number of years, except for land. 大于 1 年, 总会报废, 不能无限使用 (Land!)
- **used in the operations** of a business 一定是在生产中使用的, 而不是卖给别人的

#### b. General cost of principle for PPE

Cost consists of all expenditures necessary to acquire an asset and make it ready for its intended use. 同时牢记 GAAP 假设会计假设中的 Cost Principle (requires that companies record plant assets at cost). 总共可以分成两种 expenditures:

- **Capital expenditure**: are costs spent to **acquire or upgrade** productive assets(such as buildings, machinery and equipment, vehicles) to **increase the capacity or efficiency** of a company for **more than one accounting** period. 这些 Cost 是为了打造 PPE 而花的, 能够增强 PPE 的价值, 同时还可以用不止 1 年。这一部分 Cost 会被直接记在 Assets 中

  ```
  Dr. PPE
  	Cr. Cash
  ```

- **Revenue expenditures**: cover a business' ongoing operational costs. They are **recurring** and **short-term**. 这一部分会被直接记在 Expense 中, 关键在于这一部分并非一次性的, 而且并没有加强 PPE

  ```
  Dr. Expenses
  	Cr. Cash
  ```

#### c. Major classes of PPE (E9-2, E9-3)

**Land**

- **All necessary costs** incurred in making the land **ready for its intended use** increase **(debit)** the Land account.

- Including 1> **purchase price**; 2> **closing costs such as title and attorney's fees** (所有权和律师费); 3> **real estate brokers' commissions** (房地产经理人佣金); 4> **expenditures for grading and clearing land**; 5> **net removal cost** (cost **increase** from old buildings needs to be removed, cost decrease from selling the salvage (这个地方很重要, 考量的是净成本, 需要用**清扫成本 - 清扫收益**). 

- **Unlimited life** → No depreciation; 土地是唯一的一个特例, 无限使用, 在中国 land 只有使用权没有所有权, 所以账本中没有 land.

- **Demos**: 

  > Assume that Hayes Manufacturing Company acquires real estate at a cash cost of \$100,000. The property contains an old warehouse that is razed at a net cost of \$6,000 (\$7,500 in costs less \$1,500 proceeds from salvaged materials). Additional expenditures are the attorney’s fee, \$1,000, and the real estate broker’s commission, \$8,000. 
  >
  > ```
  > 100,000 + 1,000 + 8,000 + 7,500 - 1,500 = 115,000
  > ```

**Land improvement** (Not Land)

- all expenditures necessary to make the improvements **ready for their intended use**.
- Including structural additions made to land, such as **driveways** (车道), **parking lots,** **fences**, **landscaping** (园林绿化), and **underground sprinklers** (地下喷头).
- **Limited useful lives** → Expense (depreciate) the cost of land improvements over their useful lives. 这是 Land improvement 和 Land 之间最大的区别, 也是识别最有效的方式, 就是看这些 Expenses 所带来的东西有没有使用期限, 需不需要折旧。

**Buildings**

- All costs related directly to **the purchase or construction**, 楼房可以自己掏钱买或者自己建
- Including 2 kinds:
  - **For purchasing - Purchase costs: 购买 + 修理费用**。1> Purchase price, closing costs (attorney’s fees, title insurance, etc.), and real estate broker’s commission. 2> Remodeling and replacing or repairing the roof, floors, electrical wiring, and plumbing.
  - **For construction - Construction costs: 建筑师 + 建筑许可 + 挖掘 + 利息费用**。Contract price plus payments for architects’ fees, building permits, excavation costs, and interest costs.
- Purchase vs. Construction (including **interest costs** incurred during the construction period).

**Equipment**

- Include all costs incurred in **acquiring the equipment** and **preparing it for use**. 和 Land 一样需要考虑买的钱和修缮费用

- Including Cash purchase price, Sales taxes, Freight charges, **Insurance during transit** paid by the purchaser, and Expenditures required in assembling, installing, and testing the unit. 

- Two criteria apply in determining the cost of equipment (需要一定的判断)

  - The frequency of the cost: one-time or recurring. 产生频率, 是一次性的还是每年都会产生的, 前者就是 Equipment 后者不是
  - The benefit period: the life of the asset or short term. 使用年限, 如果是 life 的就是, 反之 short term 的不是

- Demos: Lenard Company purchases a delivery truck at a cash price of \$22,000. Related expenditures are sales taxes \$1,320, painting and lettering \$500, motor vehicle license \$80, and a three-year accident insurance policy $1,600. **Compute the cost** of the delivery truck. (&BE9-2). 其他加油钱可能是 Maintenance and Repairs Expense

  ```
  按照上述的两原则, motor vehicle license 和 three-year accident insurance policy 都不能被算, 因为他们都只是临时的, 使用时间有限的, 可以重复购买的, 因此 cost = 22,000 + 1,320 + 500 = 23,820
  
  Cr. Equipment 				23,820
  		License expense 	80
  		Prepaid insurance 1,600
  	Dr. Cash							25,500
  ```

#### d. To buy or to lease?

A lease is a **contractual agreement** in which the owner of an asset (**lessor**) allows another party (**lessee**) to use the asset for a period of time at an agreed price. 

-  经营性租赁 **An operating lease** is an arrangement allowing the lessee to account for the transaction as a rental (Rent expense, with neither an asset nor a liability recorded, 只算租赁成本, 租客没有任何资产账户的变化)
- 资本性租赁 **Under a capital lease**, the lessee shows both the asset and the liability on the balance sheet (showed as Property under PPE, report separately) (相当于把房子直接借给租客, 租客的 Asset 和 Liability 都增加)

Some **advantages** of leasing

- Reduced risk of obsolescence. 
- Little or no down payment. 
- Shared tax advantages. 
- Assets and liabilities not reported.

### 9.2 Record depreciation over useful life

#### a. Concept of depreciation

Process of **allocating to expense** the cost of a plant asset over its useful (service) life in a rational and systematic manner to match Expense with Revenue (Matching Principles). It has four important attributes:

- Process of **cost allocation**, **not asset valuation**.
- Applies to land improvements, buildings, and equipment, **not land**.
- Depreciable, because the **revenue-producing ability of asset will decline** over the asset’s useful life.
- Salvage Value: estimate of the assets' value at the end of its useful life.

#### b. Record depreciation

Journal entries:

```
Dr. Depreciation Expense
	Cr. A.D.
```

Comput the book value:

- $\text{Book Value} = \text{Cost at the beginning} - \text{A.D.} = \text{Beg. BV} - \text{Dep Exp}$, 一种方法是用初始价格减去累计折旧, 一种方法是用当期初始价格减去当期折旧
- The BV of the asset can never go bellow the salvage value (Estimate of the asset's value at the end of useful life). 当到达 Salvage Value 的时候就要停止折旧了
- Consider the impact of impairment (permanent decline in MV)

#### c. Depreciation Methods

> Management selects the method it believes best measures an asset’s contribution to revenue over its useful life. 在 US 公司使用的方法中, 88% Straight-Line; 2% Double decling balance; 3% Units of activity; 7% others.  但不论使用哪一种方法都要谨记**<u>*BV 始终大于等于 Salvage Value*</u>**。算对 Depreciation 的核心在于确定好时间线。
>
> 附加知识: IRS (Internal Revenue Service, 美国国内税务局) **does not require** taxpayer to use the same depreciation method on the tax return that is used in preparing financial statements. IRS requires the **straight-line** method or a special accelerated-depreciation method called the **Modified Accelerated Cost Recovery System** (MACRS). MACRS is **NOT acceptable** under GAAP. 

**Way 1. Straight Line (S-L)**
$$
=\text{Depericiation cost} \times \text{S-L rate} = \text{(Cost} - \text{Salvage value)} \times \frac{1}{\text{useful lifes}}
$$

- S-L 方法是最简单直接的方法, 按照时间来进行划分
- Expense is **same amount** for each year.

**Way 2. Double decling balance (DDB)**
$$
= \text{Beg. BV} \times (2\times \text{S-L rate}) = \text{Beg. BV}  \times \frac{2}{\text{useful lifes}}
$$

- DDB 比较复杂, 需要从最刚开始开始逐年往后推, (注意: 一个会计年内的各个月份均分, 但也仅限一个会计年内, 每个会计年初都要重新计算 E9-19 !!)
- 刚开始 BV 大的时候 Expense 也大, BV 后续小的时候 Expense 也就小了, 这是一种 Accelerated method.

**Way 3. Unites-of-Activity (UOA) **
$$
=\text{Depericiation cost} \times \text{Current units of activity} =  \text{(Cost} - \text{Salvage value)} \times \frac{\text{Current units}}{\text{Total units}}
$$
**A demo**

<img src="./NOTE.assets/Fig 9-1.png" alt="Fig 9-1 " style="zoom:50%;" />

- **Straight-Line Method**

  <img src="./NOTE.assets/Fig 9-2.png" alt="Fig 9-2 " style="zoom:30%;" />

- **Double decling balance** 注意到最后一行本来算出来是 674, 但因为已经到了最后一个时间段, 所以加到了 685, 反之亦然做减法

  <img src="./NOTE.assets/Fig 9-3.png" alt="Fig 9-3" style="zoom:30%;" />

- **Units-of-Activity**

  <img src="./NOTE.assets/Fig 9-4.png" alt="Fig 9-4 " style="zoom:30%;" />

### 9.3 Revise Depreciation

#### a. Principles

- Accounted for in the period of change and future periods. 只需要对变化的当期和未来期限做会计处理
- Not handled retrospectively. 不用追溯处理, 也就是说不需要对过往的数据做 Journal Entry 调整
- Not considered error. 不视作错误

#### b. Method

$$
= (\text{Revised BV} - \text{Revised salvage value}) \times\frac{1}{\text{Revised useful life}}
$$

什么时候 BV, Salvage value, 或 useful life 会变呢？

- Changes in estimate: 估计的数值变了, Salvage value 和 Useful life 都可能产生改变

- Capital expense during useful life: 因为一些费用产生导致 BV 变了

  ```
  Dr. PPE Exp
  	Cr. PPE
  ```

- Impairment: 产生了损伤或其他的增益, 导致 BV 变了

  > Expenditure During Useful Life 有两种:
  >
  > - **Ordinary Repairs** **-** expenditures to **maintain** the operating efficiency and productive life of the unit.
  >
  >   ```
  >   Debit - Repair (or Maintenance) Expense. 不会造成 BV 的改变
  >   ```
  >
  > - **Additions and Improvements** - costs incurred to increase the operating efficiency, productive capacity, or useful life of a plant asset.
  >
  >   ```
  >   Debit - the plant asset affected. 会造成 BV 的改变
  >   ```

**Demo**

Arcadia HS, purchased equipment for \$510,000 which was estimated to have a useful life of 10 years with a salvage value of \$10,000 at the end of that time. Depreciation has been recorded for 7 years on a straight-line basis. In 2012 (year 8), it is determined that the total estimated life should be 15 years with a salvage value of \$5,000 at the end of that time.

- Step 1. 算 BV = 510,000 - (510,000 - 10,000) * 7/10 = 160,000 
- Step 2. Revised salvage value = 5,000
- Step 3. Revised useful life = 15 - 7 = 8
- Step 4. Dep = (160,000 - 5,000) *1/8=19,375
- 注意: 不需要任何的 journal entry to correct the prior years’ depreciation!

### 9.4 Disposal of PPE

Companies dispose of plant assets in three ways —Retirement, Sale, or Exchange.

#### a. Principle 

Compare the **book value** of the asset with the **proceeds** received from the sale. 

- If proceeds **exceed** the book value, a **gain** on disposal occurs. 
- If proceeds **are less than** the book value, a **loss** on disposal occurs.

#### b. Disposal Steps

- **Step 1.** Update the Dep. 在进行处理前必须要更新到最新的 AD, 一般来说题目都会耍心眼, 给一个 A.D. 但其并不是卖东西那一天的 A.D. 需要做一定的调整 (在这上面栽过很多跟头, 需要注意)

- **Step 2.** Eliminate Assets. 可以确定的有三个点: 收到现金 + PPE 减少 + AD 减少, 唯一不确定的是赚钱 or 赔钱 (根据 Principle 计算)

  ```
  Dr. Cash
  	  A.D.
  	  Loss on disposal (if loss)
  	Cr. PPE
  			Gain on disposal (if gain)
  ```

  其实在实际做题的时候没必要这么复杂, 就直接线算一下 BV = Cost - A.D. 然后和 Cash 做比较, 心里有数之后得到 Journal Entry 即可

**Demo**

On July 1, 2012, Wright Company sells office furniture for \$16,000 cash. The office furniture originally cost \$60,000. As of January 1, 2012, it had accumulated depreciation of \$41,000. Depreciation for the first six months of 2012 is \$8,000. Prepare the journal entry to record depreciation expense up to the date of sale.

- Step 1. Update A.D. on July 1, 2012

  ```
  Dr. Depreciation Exp    8000
  	Cr. A.D.								8000
  ```

- Step 2. Eliminate 

  ```
  Dr. Cash    16,000
  	  A.D.    49,000
  	Cr. Equipment.                 60,000
  	    Gain on disposal            5,000
  ```

  Assume that instead of selling the office furniture for \$16,000, Wright sells it for \$9,000.

  ```
  Dr. Cash               9,000
  	  A.D.              49,000
  	  Loss on disposal   2,000
  	Cr. Equpiment.             60,000
  ```

#### c. Retirement of Plant Assets

- **No cash** is received. 十分简单, 没有现金需要考虑, AD 就是 PPE
- **Decrease** **(debit) Accumulated Depreciation** for the full amount of depreciation taken over the life of the asset.
- **Decrease** **(credit) the asset account** for the original cost of the asset.

### 9.5 Analyzing Plant Assets

**Return on Asset Ratio** indicates the amount of net income generated by each dollar of assets.
$$
\text{Return on assets ratio (ROA)} = \frac{\text{Net income}}{\text{Avg. Total Assets}} = \frac{\text{Net income}}{\text{Net Sales}} \times \frac{\text{Net Sales}}{\text{Avg. Total Assets}}
$$
拆分成了 Profit Margin Ratio 和 Asset Turnover Ratio 更容易理解。

- **Profit Margin Ratio** tells how effective a company is in turning its sales into income — that is, how much income each dollar of sales provides.
- **Asset Turnover Ratio** indicates how efficiently a company uses its assets to generate sales.

### 9.6 Intangible Asset

#### a. Concept

**Intangible assets** are rights, privileges, and competitive advantages that result from ownership of **long-lived assets** that do not **possess physical substance**.

- **Limited life** or an **indefinite life**. 可以有无限的使用寿命
- No physical assets. 没有实体

#### b. Cost

和 PPE 一样, Intangible Asset 也是有两种 Expenditure:

- **Capital expenditures**: acquisition costs and related legal costs (eg.defense cost) → capitalize on the B/S as an asset. 这部分成本会增加 Intangible Asset 的价值, 因为这鞋成本直接导致了无形资产的产生

  ```
  Dr. Patent
  	Cr.Cash
  ```

- **Revenue expenditures**: research and development costs (R&D) are expenditures that may lead to patents, copyrights, new processes, and new products → expense it immediately, when it occurred. 这些成本就是 Exp, 尤其要明确研发成本就是成本

  ```
  Dr.R&D Expense 研发费用 
  	Cr.Cash
  ```

#### c. Amortization 摊销

- **Limited life**: should be amortized over its legal life or useful life, whichever is **shorter**.

  > Eg. Patent: 10 years useful life, 20 years of legal life, 按照10年来计算

  在摊销的时候直接不再有和 A.D. 一样的累积折旧会计项, 直接减在对应的 Assets 上。另外摊销也只考虑 S-L 方法

  ```
  Dr. Amortization Expense → Amortize to expense.
  	Cr. Patent → Credit intangible asset account.
  ```

- **Indefinite life**: should not be amortized.

#### d. Major Classes

**(1) Patent** 专利

- **Concept**: Patent is an exclusive right (专有权) that enables the recipient (接收者) to manufacture, sell, or otherwise control an invention for a period of 20 years from the date of the grant.

- **Capital expenditure**: 1> **Capitalize costs of purchasing** a patent; 2> Legal fees incurred successfully **defending** a patent are capitalized to Patent account. 购买费用和辩护费用都是 Patent 的价值。amortize over its 20-year life or its useful life, whichever is shorter 按照 20 年或者使用寿命摊销, 哪个短用哪个

- **Revenue expenditure**: **Expense any R&D** costs in developing a patent. 所有的研发费用都是 Expense, 经常有题目会问到 Patent 的价值, 其价值一般都是 Legal 费用, R&D 切记不可加入其中。

- **Demo**: 

  > National Labs purchases a patent at a cost of $60,000 on June 30. National estimates the useful life of the patent to be eight years. Prepare the journal entry to record the amortization for the six-month period ended December 31.
  >
  > ```
  > Dr. Amortization 3,750
  > 	Cr. Patent        3,750
  > ```

**(2) Copyright** 版权

- **Concept**: Copyrights are granted by the federal government and give the owner theexclusive right to reproduce and sell an artistic or published work.
- **Captial expenditure**: Granted for the life of the creator plus 70 years. 其他的全部和 Patent 一致

**(3) Trademarks or trade names** 商标或商标名称

- **Concept**: A **word or symbol** that distinguishes or identifies a particular enterprise or product. The registration provides 20 years' protection (Amortization) and may be renewed indefinitely (No Amortization).
- Capitalize acquisition costs.
- Renewed indefinitely: No Amortization.

**(4) Goodwill** 商誉

- **Concept**: Represents the value of all favorable attributes that relate to a company, including desirable location, skilled employees, etc.
- Be recorded **only when** purchase an entire business; **No amortization**.
- Internally created goodwill should not be capitalized; Goodwill is recorded as **the excess of purchase price** over the FMV of the identifiable net assets acquired.

**(5) Franchises and Licenses** 专营权或许可

- **Concept**: A contractual agreement (合同安排) under which the franchiser (特许经营人) grants the franchisee (被特许人) the right to conduct certain business activities, usually within a designated geographic area. 麦当劳加盟店的例子
- **Captial expenditue**: Acquisition and related costs of the franchise or license.  Limited life: be **amortized** to expense over the life of the franchise. Indefinite or perpetual: be carried at cost and **not amortized**.
- **Revenue expenditure**: Annual payments made under a franchise agreement 例如每年都需要交许可证的费用。

### 9.7 Long lived assets

在 B/S 中针对 PPE 需要列出来 Cost 和 A.D. 针对 Intangible Assets 直接列出来净值即可。

<img src="./NOTE.assets/Fig 9-5.png" alt="Fig 9-5" style="zoom:50%;" />



## CH 10. REPORTING AND ANALYZING LIABILITIES

> 这一章开始分析债务, 核心是对 Bond 的认识。
>
> 1. Explain a current liability and identify the major types of current liabilities. (10.1)
> 2. Describe the accounting for notes payable. (10.1)
> 3. Explain the accounting for other current liabilities. (10.1)
> 4. Identify the types of bonds. (10.3)
> 5. Prepare the entries for the issuance of bonds and interest expense. (10.3)
> 6. Describe the entries when bonds are redeemed. (10.4)
> 7. Identify the requirements for the financial statement presentation and analysis of liabilities. (10.5)

### Word

- cash register readings 收银机读书
- on credit 贷款

### 10.1 Current Liabilities

A current liability is a **debt** that a company reasonably **expects to pay** from **existing current asset** (现有资产 Current Asset 还债) or through the **creation of other current liabilities** (借新债)  within **one year or the operating cycle**, whichever is longer. 总的来说就是两个特征, 一是需要还债, 二是需要在一年或一个经营周期内还。

Current liabilities include **notes payable**, **accounts payable**, **unearned revenues**, and accrued liabilities such as **taxes**, **salaries and wages**, and **interest payable**.

#### a. Notes Payable

N/P are obligations in the form of **written promissory note** (本票, 由 Borrower (maker) 写给 Payee) and usually require interest payment. Those **due within one year** of the balance sheet date are usually classified as current liabilities. 和 Account Payable 最大的不同在于其需要支付 Interest. 这一部分的记账分为 3 步：

- **Step 1**. The maker borrow money

  ```
  Dr. Cash
  	Cr. N/P
  ```

- **Step 2**. Adjust the interest at the end of one year

  ```
  Dr. Interest Expense
  	Cr. Interest Payable
  ```

- **Step 3**. The maker return money

  ```
  Dr. N/P
  	  Interst Payable (之前 Adj 的)
  	  Interst Expense (本期产生的)
  	Cr. Cash
  ```

**Demo**

> First National Bank agrees to lend \$100,000 on September 1, 2012, if Cole Williams Co. signs a \$100,000, 12%, four-month note maturing on January 1. When a company issues an interest-bearing note, the amount of assets it receives generally equals the note’s face value.
>
> ```
> Sep 1. Dr. Cash    100,000
> 					Cr. N/P    100,000
> ```
>
> If Cole Williams Co. prepares financial statements annually, it makes an adjusting entry at December 31 to recognize interest.
>
> ```
> Dec 31. Dr. Interest Expense   100,000*12%*4/12 = 4,000
> 					Cr. Interest Payable    4,000
> ```
>
> At maturity (January 1), Cole Williams Co. must pay the face value of the note plus interest. It records payment as follows.
>
> ```
> Jan 1. Dr. Notes payable    100,000
>        		 Interest payable	4,000
>        	Cr. Cash    104,000
> ```

#### b. Sales taxes payable (E10-4)

> 这是美国才有的概念, 中国用到的是增值税, 增值税较比销售税更加复杂

Sales taxes are expressed as a stated percentage of the sales price. 就是说在支付的时候直接算在了 Cash 里面。

- Retailer collects tax from the customer.

  ```
  Dr. Cash
  	Cr. Sales revenue
  	    Sales tax payable = Sales revenue * tax ratio
  ```

- Retailer remits (汇款) the collections to the state’s department of revenue.

  ```
  Dr. Sales tax payable
  	Cr. Cash
  ```

**Demo**

> The March 25 cash register readings for Cooley Grocery show sales of \$10,000 and sales taxes of \$600 (sales tax rate of 6%), the journal entry is:
>
> ```
> Dr. Cash    10,600
> 	Cr. Sales revenue    10,000
> 	    Sales tax payable   600
> ```

#### c. Unearned revenues

**Revenues that are received before** the company delivers goods or provides services. 这一部分在期中考试前就涉及到了

- Company received cash in advance

  ```
  Dr. Cash
  	Cr. Uneared revenues
  ```

- Company delivers goods or provides services

  ```
  Dr. Revenues
  	Cr. Unearned revenues 
  ```

**Demo**

> Superior University sells 10,000 season football tickets at $50 each for its five-game home schedule. The entry for the sales of season tickets is:
>
> ```
> Dr. Cash    500,000
> 	Cr. Unearned ticket revenue    500,000
> ```
>
> As each game is completed, Superior records the earning of revenue. 
>
> ```
> Dr. Unearned ticket revenue    500,000
> 	Cr. Ticket revenue              500,000
> ```

#### d. Current portion of long-term debt (CPLTD)

> 这个很容易理解, 5 年的 N/P 可能是逐年还, 这样的话一年内需要还的就是 Current Liabilities 而不是 Long-term 了

- Portion of long-term debt that comes due in the current year.
- No adjusting entry required.

**Demo**

> Wendy Construction issued a five-year, interest-bearing \$25,000 note on January 1, 2011. This note specifies that each January 1, starting January 1, 2012, Wendy should pay $5,000 of the note. When the company prepares financial statements on December 31, 2011,
>
> - What amount should be reported as a current liability? $5,000
> - What amount should be reported as a long-term liability? $20,000

#### e. Payroll and payroll taxes payable (E10-5)

Determining the **payroll** involves computing three amounts: (1) **gross earnings** (税前总工资), (2) **payroll deductions** (交税造成的减少), and (3) **net pay** (税后工资数额)。这一部分的本质是对雇员 (employee) 征收的工资税

```
Dr. Sales & Wages Exp (税前总工资)
	Cr. Sales & Wages payable (税后工资数额)
	    Taxes (公司帮助雇员交的税)
	    	- FICA (50%) 公司交一半, 雇员自己交一半, 这一部分的一半是雇员的一半
	    	- Fedral tax payable
	    	- State tax payable
```

**Payroll tax expense** results from three taxes that governmental agencies levy **on employers**. 这一部分是**公司自己需要交**的税, 是对雇主 (employer) 征收的工资税, 总共包含三个部分

```
Dr. Payroll tax Exp (公司自己的税)
	Cr. FICA (50%) 公司自己交的一半
			Federal unemployment tax payable
			State unemployment tax payable
```

### 10.2 Identify the types of bonds

**Bonds** are a form of **interest-bearing notes payable** issued by corporations, universities, and governmental agencies. Sold in small denominations (面值) (usually \$1,000 or multiples of \$1,000).

> Bond 和一般 N/P 的区别：**债权人的数量**。
>
> 其他的 N/P: you just lend from **one** borrower; bond can be issued to public, many creditors/investors.

#### a. Type of bonds

- Secured bonds 抵押债券: have specific assets of the issuer pledged as collateral (抵押品) for the bonds.
- Unsecured bonds 无抵押债券: are issued against the general credit of the borrower (also called debenture)
- Convertible bonds 可转换债券: maybe converted into stock at the investors' option
- Callable bonds 可赎回债券: issuer may pay off at a prearranged price whenever issuer chooses.

#### c. Bond certificate

- The **face value** (面值) is the amount of principal due at the maturity date. (到期日还的钱)
- The **maturity date** (到期日) is the date that the final payment is due to the investor from the issuing company.
- The constractual interest rate (stated rate, 票面利率) is the rate used to determine cash interest, generally annually or semiannually. 票面利率决定每一期利息的金额大小，是固定的

### 10.3 Entries for issurance of bonds and interst expense using effective-interst method

> Recognizes time value of money on **interest expense**. 简单来说：
>
> - 市场利率较高的时候就会折价发行, 发行时产生 Discount (Contra Account), 后续的 Interest Exp > Interest Payable, Discount 被摊销, CV 不断增加, 摊销多少增加多少
> - 市场利率较低的时候就会溢价发行, 发行时产生 Premium, 后续的 Interest Exp < Interest Payable, Premium 被摊销, CV 不断减少, 摊销多少减少多少

#### a. Determining the market value of bonds

Market value is a function of the three factors that determine **present value** (贴现法):

- the dollar amounts to be received 可能获得的现金
- the length of time until the amounts are received 时间长度 
- the market rate of interest 市场利率

Bond **market price** (as % of face value) = PV of all the future cash payments discounted by market rate, 通过将未来期全部贴现
$$
\text{Market Price} = \frac{\text{Int}}{(1 + r_m)} + \frac{\text{Int}}{(1 + r_m)^2} + \cdots + \frac{\text{Int} + \text{Face Value}}{(1 + r_m)^n} \\
= \text{Int}\times (\frac{1}{1+r_m})\times\frac{1-\frac{1}{(1+r_m)^n}}{1 - \frac{1}{(1+r_m)}} + \frac{ \text{Face Value}}{(1 + r_m)^n} \\
= \text{Int}\times \frac{1-\frac{1}{(1+r_m)^n}}{r_m}  + \frac{ \text{Face Value}}{(1 + r_m)^n} \\
= \text{Face Value} \times (\frac{r_s}{r_m} - \frac{\frac{r_s}{r_m} - 1}{(1+r_m)^n})
$$
从数学上可以看出来:

- 如果 $r_s = r_m$ 那么 $\text{Market Price} = \text{Face Price}$, 也即市场利率等于票面利率的时候应该溢价发行 (利息正好)

- 如果 $r_s > r_m$ 那么 $\text{Market Price} > \text{Face Price}$, 也即市场利率小于票面利率的时候应该溢价发行 (利息多了多收钱)

  issued at a premium

  ```
  Dr. Cash     Market Price
  	Cr. Bond paybale     Face value
  	    Premium on B/P   Market Price - Face value
  ```

- 如果 $r_s < r_m$ 那么 $\text{Market Price} < \text{Face Price}$, 也即市场利率大于票面利息的时候应该折价发行 (利息少了少收钱)

  issued at a discount

  ```
  Dr. Cash              Market Price
  	  Discount on B/P   Market Price - Face value
  	Cr. Bond payable      Face value
  ```

为什么市场利率会和票面利率有所不同呢 ? 刚开始制定的时候尽量相同, 但是市场利率会波动可能导致不同, 但是票面价格会逐渐收敛至市场价格。可以通过下面的实际情况看到每一期的增长值 or 减少值为 Interst Payble - Interst Expense

#### b. Periodic: Accounting for Interest Payment 定期付利息

$$
\text{Periodic payment} = \text{Face value} \times \text{State rate} \\
\text{Interst expense} = \text{Carrying value} \times \text{Market rate}
$$

- Carrying value 是实际价格, 就是这一时刻的市场价值

- Interst expense 是为了记账引入的, 表示如果按照市场利率去借钱的话应该给多少利息

- 这二者很难相等, 根据上面的推导, 这二者存在一定的差, 差的就是 Amortization of Premium 或者 Discount
  $$
  \text{Interst expense} =\text{Face value} \times(r_s - \frac{r_s - r_m}{(1+r_m)^n})
  $$
  如果 $r_s > r_m$ , 尽管 $\text{Carrying value} > \text{Face value}$, 但是 $\text{Interst expense} < \text{Periodic payment}$, 反之则反。也就是说：**折价发行付的利息比市场利息要多、溢价发行付的利息比市场利息要少**

来一个例子看一下: 假设 $r_m = 8\%, r_s = 7\%$  折价发行, 发行时的 journal entry 是

```
Dr. Cash            360,727
    Discount on B/P 39,273
	Cr. B/P 						400,000
```

那么第一期付息的时候就有

```
Dr. Interest Exp. 360,727*0.08=28,858
	Cr. Interst Payable 400,000*0.07=28,000
			Discount on B/P                 858
```

和我们推理得一致, 折价发行的 Interst Exp 反而更高。总的来说，这只是一种记账方法, 将之前的 Discount 不断吃掉, 吃到最后的均衡。反之如果溢价发行的话, 就会将之前的 Premium 吃掉最后到相等。

- 溢价发行

  ```
  Dr. Interst Exp.
      Premium on B/P (Premium 减少)
  	Cr. Interest Payable
  ```

- 折价发行

  ```
  Dr. Interest Exp.
  	  Cr. Discount on B/P (Discount 减少)
  	  		Interst Payable 
  ```

#### c. Total cost of borrowing

发行债券借钱的整个过程中产生了多少成本 (仅加和 Cash 不考虑折算) 呢？首先不论是折价还是溢价发行, 都要付固有的 Interst, 但是折价发行还要多付 Discount, 溢价发行的时候要少付 Premium。所以折价发行的成本更高, 溢价发行成本更低。

### 10.4 Accounting for Bond Retirements (到期前/到期赎回)

#### a. Redeeming Bonds at Maturity

到期的时候赎回, 因为 Interest 都已经派完了, 所以只需要管 Face Value 即可

```
Dr. Cash
	Cr. B/P
```

#### b. Redeeming Bonds before Maturity

When a company retires bonds before maturity, it is necessary to: 

- **Step 1**. eliminate the carrying value of the bonds at the redemption date; 
- **Step 2**. record the cash paid;
- **Step 3**. recognize the gain or loss on redemption. 如果付出的 Cash (Market Price) 比 CV 少, 那就是 Gain; 反之则是 Loss

```
Dr. B/P (收益)
    Preminum on B/P (or Cr. Discount on B/P)
	Cr. Cash (成本)
	    Gain on Bonds Redemption (or Cr. Loss on Bonds Redemption)
```

其中的难点在于确定 carrying value, 需要逐期向后推才能算出来, The carrying value of the bonds is the face value of the bonds less unamortized bond discount or plus unamortized bond premium at the redemption date. (一定是要多找几个题目多多练习！)

**Demo**:

> Assume at the end of the fourth period, Candlestick Inc., having sold its bonds at a premium, retires the bonds at 103 after paying the annual interest. Assume that the carrying value of the bonds at the redemption date is \$100,400 (principal \$100,000 and premium $400). 
>
> Candlestick records the redemption at the end of the fourth interest period (January 1, 2016) as: 
>
> ```
> Dr. B/P                      100,000
> 		Preminum                 400
> 		Loss on Bonds Redemption 2,600
> 	Cr. Cash                      103,000
> ```

#### c. Convert into stock

无非是将上述的 Cash 变为了 Common Stock

### 10.5 Report & analyze liabilities

#### a. B/S presentation

其中最为关键的是在 B/P 下面有一行 Less: Discount on bonds payable, 如果是还有 Premium 的话就要 Add 上去

<img src="./NOTE.assets/Fig 10-1.png" alt="10-1" style="zoom:50%;" />

#### b. Ratio Analysis of liabilities

**Liquidity ratios** measure the short-term ability of a company to pay its maturing obligations and to meet unexpected needs for cash:
$$
\text{Current Ratio} = \frac{\text{Current Assets}}{\text{Current Liabilities}}
$$
**Solvency ratios** measure the ability of a company to survive over a long period of time:

- $$
  \text{Debt to Total Assets Ratio} = \frac{\text{Total Liabilities}}{\text{Total Assets}}
  $$

- $$
  \text{Times Interst Earn Ratio} = \frac{\text{Net Income} + \text{Interst Exp.} + \text{Tax Exp.}}{\text{Interst Exp.}}
  $$

  利息保障倍数: 分母是息税前利润 (EBIT), 整个比率所表达的含义是每单位利息费用能对应多少 EBIT

#### c. Off-Balance-Sheet Financing

除了上述的表内融资, 我们还可以进行一定的表外融资

Contingencies: Events with uncertain outcomes that may represent potential liabilities

- 败诉可能带来损失
- 进行租赁也可能带来损失



## CH 11. REPORTING AND ANALYZING STOCKHOLDER’S EQUITY

> 所有者权益的细致说明
>
> 1. Identify and discuss the major **characteristics** of a corporation (11.1).
> 2. Record the **issuance** of common stock. (11.2)
> 3. Explain the accounting for the **purchase** of **treasury stock** (库存股票, 可以买卖的). (11.2)
> 4. Differentiate **preferred stock from common stock** (11.1).
> 5. Prepare the entries for **cash dividends** and understand the effect of stock dividends and stock splits. (11.3)
> 6. Identify the items that affect **retained earnings**. (11.3)
> 7. Prepare a comprehensive stockholders’ equity section. (11.4)
> 8. Evaluate a corporation’s dividend and earnings performance from a stockholder’s perspective. (11.4)
> 9. Prepare entries for **stock dividends**. (11.3)

### 11.1 Concepts

A corporation is a legal entity thatt is separate and distinct from its owners.

#### a. Common Classifications

- **By purpose**: For profict or nonprofit corporation
- **By Ownership**: Publicly held or privately held corporation

#### b. Characteristics of a Corporation

**Advantages**

- Separate Legal Existence (和经营者独立, 有自己的责任主体)
- Limited Liability of Stockholders (有限责任)
- Transferable Ownership Rights (好转化, 可以直接卖股票)
- Ability to Acquire Capital (好融资)
- Continuous Life (好延续)
- Corporate Management — Professional Managers (管理者专业)

**Disadvantages**

- Corporate Management — Separation of ownership and management (目标可能不一致, 起冲突)
- Government regulations (政府法则繁琐)
- Additional taxes (双重交税)

<img src="./NOTE.assets/Fig 11-1.png" alt="Fig 11-1 " style="zoom:50%;" />

#### c. Stockholder rights (C.S. *vs* P.S.)

When a corporation has only one class of stock, it is identified as **common stock**.

- **Voting right**: **Vote** in election of board of directors and on actions that require stockholder approval.
- **Receipt of dividends**: **Share** the corporate **earnings** through receipt of dividends.
- **Residual claim**: Share in assets upon liquidation in proportion to their holdings. (清算的时候按比例索取, 但顺序落后于债权人和 P.S.)
- **Preemptive right**: Keep the same percentage ownership when new shares of stock are issued.

**Preferred stock:**

- dividened preference (could be cumulative) 先收到分红, 并且可以累积 (都需要得到今年的和之前年份没有派发的) 分红多少一般直接给出一个 share 分多少。

  > M-Bot Corporation has 10,000 shares of 8%, \$100 par value, cumulative preferred **stock outstanding** at December 31, 2010. No dividends were declared in 2008 or 2009. If M-Bot wants to pay \$375,000 of dividends in 2010, common stockholders will receive: 375,000 - 3*80,000 = 135,000 (逐年累积) 且必须要把累积的填完, 才能发 C.S. 的

- liquidation preference (清算时优先级更高)

- nonvoting rights (没有投票权)

#### d. Stock issue considerations:

**Authorized stock**

The amount of stock a corporation is authorized to sell. Number of authorized shares is often reported in the stockholders’ equity section. 只是被授权的股票数量, 最终究竟发多少取决于 Company 自身。这一步一般不需要写 Entry

**Par value stock**

Capital stock that has been assigned a value per share in the corporate charter. Years ago, par value determined the **legal capital per share that a company must retain** in the business for the protection of corporate creditors. 京东的面值就设的十分低, 就是害怕股票跌落而被退市。

**No-par value stock**

Capital stock that has not been assigned a value per share. No-par value stock is quite common today. 现在很多股票没有面值

**Stated value** 

In many states, the board of directors assigns a stated value to no-par shares. 做了一个固定价值代表面值

<img src="./NOTE.assets/Fig 11-2.png" alt="Fig 11-2 " style="zoom:50%;" />

- **Paid-in capital** is the total amount of cash and other assets paid in to the corporation by stockholders in exchange for capital stock. 说白了就是发行股票的时候别人买股票投入的钱
- **Retained earnings** is net income that a corporation retains for future use.

### 11.2 Issuance and repurchase of stock

#### a. Issuace

```
Dr. Cash                 => Market Price (获得的资金就是别人购买要花的市场价格)
	Cr. C.S or P.S         => Par Value or State Value (Par 和 State 价格都是不变的)
	    Paid-in capital in excess of par or stated value (PICIE) (中间的差价需要多加资金补上)
```

**Illustration**: Assume that Hydro-Slide, Inc. issues 1,000 shares of $1 par value common stock at par.

```
Dr. Cash    1,000
	Cr. C.S.	  1,000
```

**Illustration**: Now assume Hydro-Slide, Inc. issues an additional 1,000 shares of the \$1 par value common stock for cash at \$5 per share. Prepare Hydro-Slide’s journal entry.

```
虽然票面价值是 1, 但是市场价格是 5, 所以能筹到的资金一定是 5, 但是股票还是那么多的价值, 就需要补足差价
Dr. Cash    5,000
	Cr. C.S.	  1,000
			PICIE —— C.S.		4,000
```

<img src="./NOTE.assets/Fig 11-3.png" alt="Fig 11-3 " style="zoom:50%;" />

**Illustration:** Stine Corporation issues 10,000 shares of \$10 par value preferred stock for \$12 cash per share.

```
Dr. Cash    120,000
	Cr. P.S.	  				100,000
			PICIE —— P.S.		 20,000
```

#### b. Repurchse

**Treasury stock**: corporation’s own stock that it has reacquired from shareholders, but not retired. 重新获取但是没有退股的股票

**Why purchase treasury stock?**

- To reissue shares to officers and employees under **bonus and stock compensation plans**. (作为奖励重新发放)
- To **increase trading** of the company’s stock in the securities market. (增加交易, 向市场表示价格被低估)
- To have additional shares available for use in **acquiring other companies**. (有更多股份可以收购其他公司)
- To **increase earnings per share**. (增加每股收益)
- Another infrequent reason is to eliminate hostile shareholders. (消除敌对股东)

**Purchase of Treasury Stock**

- Generally accounted for by the **cost method**.
- **Debit Treasury Stock** for the price paid.
- Treasury stock is a **contra stockholders’ equity** account, not an asset.
- Purchasing of treasury stock **reduces stockholders’ equity**.

**Illustration:** On February 1, 2012, Mead acquires 4,000 shares of its stock at $8 per share.

```
Dr. Treasury Stock    32,000
	Cr. Cash              32,000
```

<img src="./NOTE.assets/Fig 11-4.png" alt="Fig 11-4" style="zoom:60%;" />

#### c. Reissue

可能会重新发行 Treasury 的股票, 那么就会得到

```
Dr. Cash    => Market Price
	Cr. T.S.  => Par Value
	    Additional PICIE —— T.S.
```

#### d. Shares Outstanding

$$
= \text{Number of issued} - \text{Number of T.S.}
$$

### 11.3 Dividend distribution

#### a. Cash dividends — Cash 转到 Equity 上去

**计算 Cash dividends 数量的两种方式**

- $= \text{shares outstanding} \times \text{DPS(dividends per share)}$
- $= \text{shares outstanding} \times \text{par value} \times \text{par value dividends ratio}$

**发放要求**

- **Retained earnings** **-** Payment of cash dividends from retained earnings is legal in all states.
- **Adequate cash**.
- **Declaration** by the Board of Directors.

**发放过程 three dates**

<img src="./NOTE.assets/Fig 11-5_.png" alt="Fig 11-5" style="zoom:50%;" /> 

- **Declaration date**: 声明需要发多少 (现在只是粗略地算了一下数量是多少, 不知道谁能拿到)

  > 这个地方需要展开上述的两种记录方法, 注意 50¢ per share 表示每股 50 美分

  ```
  Dr. Cash Dividends
  	Dr. Dividends Payable
  ```

- **Record date**: 记录到底是哪些人, 具体是谁分多少钱 No Change, No Entry

- **Payment date**: 将应付的资金付出

  ```
  Dr. Dividends Payable
  	Cr. Cash
  ```

#### b. Stock dividends — Retained earnings 注入 Stock 中

**计算方式**
$$
\text{shares outstanding} \times \text{stock value} \times \text{value dividend ratio}
$$
其中 stock value 到底是按照 par value 算, 还是按照 market value 算呢 ? 具体需要参考 dividend ratio

- 如果 dividend ratio <= 20% | market value, 少
- 如果 dividend ratio > 20% | par value

**发放原因**

- Satisfy stockholders’ dividend expectations without spending cash. (不花现金满足要求)
- Increase the marketability of the corporation’s stock. (提高股票的交易流动性)
- Emphasize that a portion of stockholders’ equity has been permanently reinvested in the business. 

**发放产生的影响**

- Changes the **composition** of stockholders’ equity. 
- Total stockholders’ equity **remains the same**. (R/E 减少, Stock 增加, 一定不影响总数, 十分重要 !!!)
- **No effect** on the par or stated value per share.
- Increases the **number of shares outstanding**.

**发放过程** (以例题为样板)

Medland Corp. declares a 10% stock dividend on its \$10 par common stock when 50,000 shares were outstanding. The market price was \$15 per share (E11-7, 刚开始的时候一定是没有 PICIE 的)

- **Step 1.** 根据公式算总共 Dividend 多少钱 50,000 * 15 * 0.1 = 75,000, 也就是说 Paid-in 要加 75,000, Retained Earnings 减这些
- **Step 2.** 基于 Step 1. 中结果计算需要分发多少股份 75,000 / 15 = 5,000 
- **Step 3.** 将 5,000 的资金分开, 一部分是 Stock: 5,000*10 = 50,000, 一部分是 PICIE: 25,000

<img src="./NOTE.assets/Fig 11-6.png" alt="Fig 11-6" style="zoom:40%;" />

因此 Entry 也是很明显的公式

- **Declaration date**: 声明需要发多少, 并完成拆分

  ```
  Dr. Stock Dividends    Div 的总金额
  	Cr. Common Stock Div. distributable    CS 中分到的金额
  		  PICIE                              因为市场价带来的差额
  ```

- **Payment date**: 将应新增的 CS 新增出来

  ```
  Dr. Common Stock Div. distributable
  	Cr. CS
  ```

#### c. Stock Split

**影响**

- Reduces the market value of shares.
- No entry recorded for a stock split. 没有任何资金的流入流出改变, 所以不用 Care
- Decrease par value and increase number of shares.

<img src="./NOTE.assets/Fig 11-7.png" alt="Fig 11-7" style="zoom:50%;" />

<img src="./NOTE.assets/Fig 11-8.png" alt="Fig 11-8 " style="zoom:50%;" />

#### e. Retained Earnings

**Concepts**

- **Retained earnings** is net income that a company retains for use in the business.

- **Net income** increases Retained Earnings and a **net loss** decreases Retained Earnings.

- Retained earnings is part of the **stockholders’ claim** on the total assets of the corporation.

- A debit balance in Retained Earnings is identified as a **deficit**. 

  **如果最终 Retained Earnings 是负数就要记录成 Accumulated defict**

- `RE_End = RE_Beg - Cash Dividends - Stock Dividends`

**Retained Earnings Restrictions 留存收益限制**

可能因为种种原因让 RE 存在限制, 不能全部发完 (所以全部可以发放的说法明显是错误的), 必须要留下来一部分

 Restrictions can result from:

- Legal restrictions.
- Contractual restrictions. (有一些成本需要留存资金)
- Voluntary restrictions.

### 11.4 Balance Sheet Presentation

#### a. How to present ?

<img src="./NOTE.assets/Fig 11-9.png" alt="Fig 11-9 " style="zoom:50%;" />

其中分成两个部分, 共四个 Subtotals, 一部分是 Capital Stock (CS, PS), 一部分是 Additional paid-in capital (PICIE - CS, PICIE - PS)

#### b. Ratio analysis (P11-2 a 必须再来一遍)

**Payout Ratio** for **Dividend Record**

The **payout ratio** measures the percentage of earnings a company distributes in the form of cash dividends.
$$
\text{Payout Ratio} = \frac{\text{Cash Div. Declared on C.S.}}{\text{NI}}
$$
**Return  on Common Shareholders' equity ratio** (ROE)
$$
\text{Return on Common Shareholders' equity ratio} = \frac{\text{NI - P.S. Div}}{\text{Avg. C.S. Equity}}
$$
其中: $\text{C.S. Equity}$ 可以用两种方法计算

- Total SE - P.S. - PICIE—P.S.
- C.S. + PICIE—C.S. + R/E - T.S.



## CH 12. STATEMENT OF CASH FLOWS

> 现金流量表的细节, 从 Net Income 以及各项 Expenses, Receivable 和 Payable 中还原出 Cash 的真正走势
>
> - Indicate the usefulness of the statement of cash flows. （12.1）
> - Distinguish among operating, investing, and financing activities. （12.1）
> - Explain the impact of the product life cycle on a company’s cash flows. (12.3)
> - Prepare a statement of cash flows using the **indirect method**. (12.4)
> - Use the statement of cash flows to evaluate a company. (12.5)
> - Prepare a statement of cash flows using the **direct method**. (12.4)

### 12.1 Concepts

#### a. Concepts and Usefullness of Sttaement of Cash Flows

The satement of cash flows reports the **cash receipts, and cash payments** from the **operating, investing, and financing activities** **during a period**, in a format that reconciles the **beginning and ending cash balances**.

- Predicts future cash flows
- Determines ability to pay dividends and interst
- Shows the relationship of net income to cash flows
- Reports how managers got cash and how they used cash to run business

#### b. 3 Principle types of business activity

- **Operating activities** 经营活动: 影响 Income Statement Items & Current assets

  > Include the cash effects of transactions that **create revenues and expenses** and thus enter into the determination of net income.

- **Investing activities** 投资: Changes in **Investments** and **Long-Term** Asset Items, 注意投资是不影响负债和所有者权益的

  > - acquiring and disposing of investments & PPE 
  > - lending money and collecting the loans (A/R, N/R)

- **Financing activities** 融资: Changes in Liabilities and Stockholders’ Equity 和投资最大的区别在于其影响了负债和所有者权益, 是对股权和债权的深度操作

  > - obtaining cash from issuing debt and repaying the amounts borrowed
  > - obtaining cash from stockholders, repurchasing shares, and paying dividends

### 12.2 CFO + CFI + CFF

#### a. CFO - Operating activities:

> involve **cash flows** from ongoing regular business activities in a given period. 在计算 CFO 的时候可以用 Direct 的方法, 也可以用 Indirect 的方法, 而 CFI 和 CFF 都只有 Direct 方法。

**Cash inflows**

- From sale of goods or services
- From interst and dividends received (发债券 or 买股票得到的定期收益)

**Cash outflows**

- To suppliers for inventory (买存货), Invetory 增加多少 Cash 减少多少
- Toemployees for services. (付工资)
- To government for taxes.
- To lenders for interest. (付利息)
- To others for expenses. (各种各样的费用)

#### b. CFI - Investing activities:

> involve cash flows resulting from changes in investments, loans and long-lived assets
>
> 【注】investments long-term &short-term 都有可能，eg.purchase another company's stock for a short

**Cash inflows**

- From sale of property, plant, and equipment
- From sale of investments in debt or equity securities of other entities (卖其他公司的债/股)
- From collection of principal on loans to other entities (到期收回本金)
- 注意: 投资的利息和分红的收入都是在 CFO 那边, 不在 CFI 这边

**Cash outflows**

- To purchase property, plant, and equipment
- To purchase investments in debt or equity securities of other entities
- To make loans to other entities

#### c. CFF - Financial activities:

> involve cash flows resulting from changes in debt (long-term &short-term) and stockholders equity

**Cash inflows**

- From sale of common stock 发股票
- From issuance of debt (bonds and notes) 发债券和票据

**Cash outflows**

- To stockholders as dividends 进行分红  (dividend distributed)
- To redeem debt or reacquire capital stock (treasury stock) 赎回债/股

#### d. Significant noncash activities. Examples are:

> 尽管产生了很多了很多 Asset 或者 Liability 或者 Equity 的变化, 但是都没有涉及到 Cash, 单独记在一行

- Issuance of common stock to purchase assets. 发股票买资产, 不计现金, 直接记资产
- Conversion of bonds into common stock. 债转股
- Issuance of debt to purchase assets. 发债买资产, 不计现金, 直接记资产
- Exchanges of plant assets. PPE 互换

### 12.3 The impact of the product life cycle on a company's cash flows

<img src="./NOTE.assets/Fig 12-1.png" alt="Fig 12-1" style="zoom:60%;" />

刚开始: 在募资, Financing 比较多, Operating 还没起来, Investing 也还没起来,

成长期: Operating 增加, Financing 平稳, Investing 增加

成熟期: Operating 和 Investing 平稳, Financing 降低

衰退期: Operating 和 Investing, Financing 都降低

### 12.4 Prepare a statement of cash flows

#### a. Format of the statement of cash flow

<img src="./NOTE.assets/Fig 12-2.png" alt="Fig 12-2" style="zoom:50%;" />

其实是比较流畅的, 这个表一定要牢记在心里！然后要铭记一个原则, CFO 可以用 Direct 也可以用 Indirect 但是 CFF 和 CFI 都只能用 Direct 的计算方法。据统计 Indirect 方法站到了绝大多数。

#### b. Prepare a statement of cash flows using the indirect method

在进行 CFO 的梳理之前, 要拿到三个信息: 两年间变化的 B/S, 今年的 Income Statement, 以及补充材料

**Step 1. CFO**

Determine net cash provided/used by operating activities by converting net income from accrual basis to cash basis. 从权责发生制到收复实现制的转变。**基于 Net Income 进行调整**, 原则很简单, 就是把那些没有反应在 Net Income 中的 Cash 都调整了。

> 目前的 Net Income 来自于 Rev - Exp 
>
> - 当 Rev 产生的时候可能是 Cash 增加, 也可能是 A/R, N/R, A/P, N/P 等非 Cash 增加或减少
> - 当 Exp 产生的时候可能是 Cash 减少, 也可能是上述等非 Cash 减少或增加, 也可能是非 Cash Exp 出现
> - 另外这一部分还可能有 Loss 和 Gain, 这些的确导致了 Net Income 变化但没有导致 Cash 变化, 所以也要调整
> - 另外 Inv 和 Prepaied 也是一样的道理
>
> 所以先来最简单的, 可以从 I/S 里面看到的 Nocash Exp 以及 Gain 和 Loss, 然后再来从 B/S 里面看到的 Current Assets 和 Liabilities 的变化。

- **ADD**: No cash expenses (depreciation or depletion expense)
- **Deduct gains and add losses** from Investing and Financing activities (为 CFI 和 CFF 擦屁股): 
  - **ADD**: Any **loss** on sale is **added** to net income in the operating section.
  - **LESS**: Any **gain** on sale is **deducted** from net income in the operating section.
- Changes to Noncash Current Asset Accounts,
  - **ADD**: When A/R, N/R Less. Inventory 的净减少, 说明买 Inventory 的钱不如 COGS 那么多, 所以要加上; Prepaid Expenses 减少说明买 Pred Exp 的钱没有 Exp 那么多, 所以要加上
  - **LESS**: When A/R, N/R Add. 如果 Inventory 有净增加, 说买 Inventory 的钱比 COGS 还多, 所以要进一步继续减去; Prepaid Expenses 增加说明买 Pre Exp 的钱比 Exp 还多, 所以要继续减去
- Changes to Noncash Current Liability Accounts
  - **ADD**: When current liabilities decrease
  - **LESS**: When current liabilities increase

请注意, 这一部分的核心逻辑就在于看 Net Income 是否多减了或者是否多加了, Current Asset 增加就说明少减了, Current Liability 增加多减了。为了不漏掉任何一项, 最好的处理方法是先看 I/S 再看 B/S。

<img src="./NOTE.assets/Fig 12-3.png" alt="Fig 12-3 " style="zoom:50%;" />

**Step 2. CFI & CFF**

Individual CI and CO are reported. 只需要一个个找到然后放下即可。

#### c. Prepare a statement of cash flows using the direct method

> 和 inderect 最大的不同就在于这儿并没有一个 Net Income 的依靠, 而是从 0 开始搭建, 这一部分的核心是找到相关的账户, 然后画 T account 即可。这一部分一定会考察选择题, 不需要记忆任何东西, 只需要理清楚逻辑。但是如果想要加快速度, 需要对逻辑十分熟悉才可以。

**Part 1. Cash Inflows (CI)**

- CI from customer = Revenue + A/R(Begin - End)
- CI from interest = Interest Revenue + Interst/Receivable(Begin - End)

**Part 2. Cash Outflows (CO)**

- CO to supplier. 因为买 Inv 可能使用 A/P 也可能是用 Cash, 所以需要先识别买了多少, 然后再识别多少用 Cash 卖的。此处的 A/P
  - **Step 1**. Pur = COGS + Inv (End - Begin)
  - **Step 2**. CO = Pur + A/P (Begin - End) 
- CO for SGA (销售、一般、管理费用).
  - **Way 1**. CO = SGA Exp + Prepaid Assets (End - Begin)
  - **Way 2**. CO = SGA Exp + Accruared Liabilities (Begin - End)
- CO for Int = Interest Exp + I/P (Begin - End)
- CO for Tax = Tax Exp + T/P (Begin - End)

**如何做到不重不漏?** 根据 I/S 一个个往下看

- Sales Rev + A/R
- COGS
- Operating Exp (SGA)
- Int and other Exp (Int Exp, Divident Exp)
- Taxes Exp

### 12.5 Using Cash Flows to Evaluate a Company

#### a. Free cash flow

**Free cash flow** describes the cash remaining from operations after adjustment for capital expenditures and dividends.
$$
\text{Free cash flow} = \text{CFO} - \text{Capital Expenditures} - \text{Cash Dividends}
$$
<img src="./NOTE.assets/Fig 12-4.png" alt="Fig 12-4" style="zoom:50%;" />

#### b. Current Cash Debt Coverage Ratio (Liquidty) (E12-9)

$$
\frac{\text{CFO}}{\text{Avg. Current Liabilities}}
$$

#### c. Cash Debt Coverage Ratio (Solvency) (E12-9)

$$
\frac{\text{CFO}}{\text{Avg. Total Liabilities}}
$$

> 所有的 Avg 都是用年初和年末计算


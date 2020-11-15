Capital Investment and Financial Risk

# 一、Present Value和Discounting
- ==由于钱会随时间增加而earn return，所以present value（未来收到的钱在现在的价值）小于future value。==
- present value取决于return rate和number of period。

## 1. single period的present value
- 计算present value的过程称为==discounting（贴现）==，用==discount rate（贴现率==）计算present value。
- ==$PV = FV_n / (1+r)^n$==
	- PV = present value, FV = future value
	- ==$r$ = rate of return, $n$ = number of period==

## 2. multiple period的present value
- 如果r不变，则present value经过n次积累，其价值和future value一样。
- ==$PV = FV_n / (1+r)^n = FV * PV_f$==
	- ==可使用present value公式、financial calculator或计算机表格，或present value table计算（表格中的值代表$PV_f = 1/(1+r)^n$））==


# 二、annuity的present value
- ==年金（annuity）：在一定期间内，每期末都支付同金额的payment==
- ==计算年金现值时，可计算每次支付金额的现值，再将其相加得到sum of present value==。年金现值可以通过将每个周期的payment乘以present value of annuity表格中的annuity factor来确定。
- ==$PAVF = [1-(1/(1+r)^n)]/r$==
- $PVA = A*PVAF$
	- 其中A = 每次支付的payment
	- $PVAF$是present value of annuity factor

# 三、Unequal payment的present value
- 现实中，并非每次支付的金额都是相等（equal）的。==annuity中，若每次的payment都是unequal，则基本方法为算出每次payment的present value，之后进行加总（此时需要使用present value table），即 $\sum( 每次的payment * 当期的PV_f)$==

# 四、net present value（净现值）
- net present value技术为根据required rate of return来discount cash outflow/ inflow。
- ==investment的net present value是其cash inflow的现值与cash outflow的现值之差==。用于折现的return rate ( r )是投资者要求的。
	- ==在进行投资选择时，遵循NPV rule（只有NPV大于0时才进行投资）==。
	- ==企业通常将其要求的rate of return设置为与其cost of capital 相等，以便让其能cover资金成本。==
- $NPV = -C_0 + (C_t/(1+r)^t) + ...+(C_n/(1+r)^n) = \sum_1^n(C_n/(1+r)^n) - C_0$ 
	- $C_0$ = 项目开始时的cash flow
	- $C_t$ = period 为 t 时的payment
	- $r$ = discount rate (贴现率)
	- $n$ = number of period (期间)
	- 要注意：$C_0$的符号为负（即cash outflow为负，即第一次的投资为支出），$C_t$符号为正（cash inflow为正）。若investment要有多次cash outflow，则该等式不适用。
	- 其中$\sum_1^n(C_n/(1+r)^n)$可使用present value table一个一个计算出来，再做相加即可。
- ==在做投资决策时，NPV analysis和NPV rule不应成为惟一的方法（sole determinant），有时NPV analysis无法考虑到所有的因素（有时即使NPV>0，也不意味着一定可以接受该方案）。==
- ==NPV analysis的缺陷：==
	- ==cash flow的amount和timing和预计的不一样==
	- ==NPV analysis未考虑风险（uncertainty）对未来现金流、loss、discount rate或time horizon的影响==
	- ==NPV analysis主要关注最大化economic value，忽略了企业的non-financial goal和其他stakeholder interest==

# 五、评估capital investment proposal
- capital investment proposal为企业提供了spend capital的机会，并预期未来的net cash flow会增加。
- 在确定net present value（NPV）时，通常采用long-term capital budgeting, cash inflow and outflow以及cash flow analysis来确定investment proposal是否会产生现值大于投资额的净现金流。

## 1. Capital Budgeting and Expenditure
- ==capital budgeting（根据proposal中cash outlay和可能产生的cash inflow的现值来评估资本投资的过程==）用于cash expenditure（费用）或receipt（收取）跨越多个accounting period的情况。
	- ==企业有两项expenditure==
		> ==operating expenditure: 在一年或一个会计年度内内会消耗的费用==
		>
		> ==capital expenditure: 跨越多个会计期间才会消耗完的财产==
- capital budgeting 主要关注capital expenditure（即需要长期收取cash或需要cash支出）。通常涉及需要立即支出现金的资产或活动，但可能会产生未来的cash receipt。企业必须对比future cash inflow的present value和investment proposal initial cost，才能做出是否要投入capital asset的决定。
	
	>例如企业建造plant（immediate cash disbursement），盖好的plant会在其life span中以致产生cash receipt（inflow）

## 2. NPV方法
- NPV method是应用于cash flow analysis的方法，该方法可计算proposal的net cash flow（cash inflow - cash outflow）是否为正，若net cash flow为正，则投资可产生比specific rate高的return rate，若net cash flow为负，则proposal产生的return rate低于specific rate。
- ==为使用net present value评估capital investment proposal，需要获取如下信息：==
	- ==initial investment amount：即第一次的投入金额，required investment等于当期的cash outflow（此时不需要贴现）==
	- ==acceptable annual rate of return==
		> 最小的acceptable annual rate of return也就是企业这笔资金的资金成本（cost of capital），这项数值由企业给到风管人员（而非由风管人员决定）。
		>
		>==rate of return不只有资金成本决定，风险厌恶的financial officer可能会要求一个更高的rate of return以平衡investment proposal的higher risk（这被称为risk-return trade-off，即潜在收益随着风险增加而增加），这需要investor在lowest possible risk 和highest possible return中找到合适的平衡点。==
		>
		> minimum rate of return确定好后，所有cash inflow的现值大于outflow现值的投资即可被接受（根据NPV method）。
	- ==在estimated useful life期间，与proposal有关的annual net cash flow（税后）的数量和时间==
		> ==net cash flow (NCF)  = 预期产生的cash inflow - cash outflow。==
		>
		>==differential annual after-tax net cash flow是企业一年执行投资计划后aggregate annual net cash flow的变化。==
	- ==investment的salvage value（残值，investment在end of useful life时的residual value）==

- NPV method的步骤：
	- 第一步：计算未来cash flow的present value，累加
	- 第二步：对比现有投资额和第一步得出的累加值。
		- $NPV = PVpresent value - PVinitial$
		- NPV>0, 值得投资，NPV<0,不值得投资

## 3. Cash Flow Analysis
- 实践中，capital budget需要从revenue和expense中计算net cash flow。当审核revenue和expense数据时，企业需使用cash flow analysis研究net cash inflow（而非研究gross cash inflow）。
	
> 当购买设备时，不应仅考虑由此带来的持续收入和initial outlay of cost。它还会包括未来维修费的增加，以及因费用从应税收入中扣除而导致的所得税减少，进而抵消这些增加。它还涉及所得税的减少（由设备的初始资本支出的折旧导致）。
	
- ==对于for profit企业，income tax属于cash outflow，所以必须从cash revenue中进行扣除，之后在计算net cash flow==
	- ==tax属于另一种支出（cash layout），其根据taxable income的百分比计算。==
	- ==taxable income基于cash和non-cash revenue和expense计算，对于不适用income tax的企业，可简化为计算cash flow。==
- ==在capital budgeting 决策中，主要影响income tax的non-cash项目是long-term asset的depreciation expense（一种会计折旧方法，purchase expense分散到item的整个life expectancy==）在expense确认期间不属于cash outflow，而仅认为是将outlay分散在多年内分散cost，并和revenue period相匹配。
- ==最简单的depreciation method（折旧方法）是直线折旧法（straight-line depreciation method，在asset预期使用寿命的每一年，将资产成本等额折旧）。==
	
	- 使用直线折旧法（straight-line depreciation method）的资产的残值（salvage value）为零。尽管直线折旧时，并未发生实际的cash outflow，但仍应在计算taxable income时，将depreciation计入其他费用（other expense）。marginal income tax假定为应纳税所得额的40%。
- 计算步骤
	1. ==先用每年创收的revenue减去每年的维护费（包括保险费）等，得出Before-tax Net Cash Flow（Before-tax NCF）==
		- $NCF_(beforetax)  = Cash Revenue - Cash Expense$
	2. 用before-tax NCF减去折旧得出taxable income
		- $taxable income = NCF_(beforetax) - depreciation$
	3. 用税率乘以taxable income得出income tax
		- $income tax = taxable income * tax rate$
	4. 用before-tax NCF减去income tax，得出after-tax NCF
		- $NCF_(after-tax) = NCF_(beforetax) - income tax$
- NPV = [(年回报-年费用) - (年回报 - 年费用 - 初始资金 / 使用年限) * 税率] *  PV_f - 初始资金	
	
	- 其中after-tax cash flow = [(年回报-年费用) - (年回报 - 年费用 - 初始资金 / 使用年限) * 税率]
- 对于没有income tax的企业，after-tax NCF等于before-tax NCF。不管是否考虑income tax，计算NCF并确定NPV为风管评估investment 提供了基础。
- 在所有企业中，NCF（net cash flow）都受到uncertainty（risk）的影响，在选择discount rate（cost of capital）时应考虑此类风险。==未来net cash flow的不确定性越大，要求的minimum rate of return越高（企业希望从更多风险中获得更高的回报）。==
- 理想情况下，风管人员应尝试对企业面临的NCF风险进行量化，并将cost纳入到NPV计算中，但是这其中很多成本是无法精确衡量的。当uncertainty cost无法衡量时，企业应为uncertainty分配一个price tag（cost），从而可以像对待其他成本一样，应对这种税后成本。这样成本称为cost of uncertainty（或risk premium）。
- ==cost of uncertainty的风险增加会导致discount rate增加，减小after-tax net cash flow，进而可能导致NPV从正变负，导致proposal被拒（即使NCF大于初始投资，也有可能导致此种情况）。==
- 在uncertainty改变的情况下，==sensitivity analysis（用于确定一个或多个变量对financial analysis的结果有多大影响==）可用于决定是否要改变接收或拒绝proposal。==当被分析的变量外的所有变量都保持不变时，分析是最准确的。之后可测量NPV，看它对该变量的变化有多敏感。==

# 六、评估treating hazard risk的cash flow
- 在评估capital investment proposal时，需知晓expected accidental hazard loss，风管人员可分析各种loss control技术的effect。
	- ==accident loss要在计算tax前，从cash revenue 中减去（相当于是费用的一部分）。==
	- ==accident lossk可能会对cash flow analysis产生重大影响。==
	- ==loss control活动会对NPV产生正面或负面的影响（增加或减少NPV）。==

- 通过选取合适的风控技术，风管人员可减少accident loss对proposal的影响。

# 七、使用call option限制financial risk
- 因为price change导致的net income loss可能会非常大。风管人员应熟悉使用risk financing 技术来抵消price change带来的business risk。
- ==可使用call option平抑价格波动带来的风险。==


## 1. 基本概念
- 企业可使用hedging对冲price change带来的business risk。企业在购买原材料以及卖出物品时的价格变动是price risk的主要来源，这种风险会严重影响企业的operation和value。
- 原材料价格上涨，企业产品出售价会减小企业cash flow和net income，反之则反。有些企业知道原材料和产品出售价会变化，但他们无法准确预测价格变化的方向和size。
- 不想承受或不能承受此类fluctuation的企业，通常使用hedging来稳定其cash flow。
- ==使用forward contract（合同约定在指定的未来日期，一方有义务在约定价格购买，另一方有义务在约定价格出售特定financial instrument或physical commodity），future 或 call option时，企业必须牺牲一部分或全部潜在的net revenue gain（价格有可能朝着利于企业的方向变化），但这种牺牲可让企业在价格变化时接近其projected operating result。==
- ==call option可让holder在合同到期之前以合同确定的价格（strike price）购买物品，从而抵消原材料价格上涨而导致的损失。call的价格相当于保险的保费，所以有时option contract也被称为insurance。==
	- ==若执行时市场价（spot price）高于合同确定的价格（strike price），holder可按照strike price购买商品，之后在市场上以spot price卖出，以赚取利润。这种可利润会给赋予合同commercial value，所以这种合同也被称为in the money. 由于此类合同有value，他可以在organized market上进行交易，从而买卖物品成为买卖contract。==
	- ==若spot price低于strike price（这种情况称为out of the money），这种合同仍会具有一些value（因为spot price也许会在expiration date前超过strike price），但其价值低于in the money的合同。==
	- ==spot price升高时，call value增加；spot price减少时，call value减少。==
		> 购买了call的企业，在spot price升高时，企业可卖出call，用盈利抵消成本上升导致的损失；在spot price下降时，企业可保留call，此时net income的上升（由lower原材料spot price导致）可能会抵消购买call的成本
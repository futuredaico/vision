FutureDAO 白皮书:
刘永新 v1.0

目录
FutureDAO 白皮书:	1
1.	背景：	2
1.1.	网络社群与文化多样性趋势：	2
1.2.	初创公司融资成本阻碍创意与文化繁荣	2
1.3.	传统互联网股权众筹的问题	2
1.4.	ICO的成功与失败	3
1.5.	IEO的问题	3
2.	寻找更好的ICO-DAICO	4
2.1.	债券曲线	4
2.2.	双曲线融资模型：	6
2.3.	CO持续性组织	6
2.4.	CO双曲线融资模型	6
3.	FutureDAO	9
3.1.	设计哲学	9
3.2.	单曲线VS双曲线	10
3.3.	链上治理	10
3.4.	链下治理	12
4.	合规	12
5.	应用场景	13
6.	价值与意义	13
7.	总结	14








1.	背景：
1.1.	网络社群与文化多样性趋势：
移动互联网已经构建了庞大的在线社交网络，2019年一季度Facebook月度活跃用户达到23亿，而微信则是11亿，全世界大多数人口已经通过少数社交网络链接起来，人和人之间的交流变得便捷又紧密。在广泛连接的社交平台基础上，不同人群会以某种文化为核心，形成小众社群，其中又以ACG（Animation、Comic、Game）文化社群为主要形式。这些社群有较强的文化归属感，同时具有强大的消费意愿和能力。以游戏为例，根据Newzoo分析，2018年全球游戏收入达到1379亿美元，活跃玩家超过23亿，付费玩家超过11亿。而随着人工智能技术逐渐成熟，将会有越来越多的体力劳动和工作岗位被人工智能和机器人替代掉，人类将花费更多时间在文化产品上，文化创意消费兴起，文化创意产品的创造也会繁荣。
1.2.	初创公司融资成本阻碍创意与文化繁荣
文化创意产品有小众化和流行化的特点，对于传统投资机构和个人来说，产品流行的不确定性大，风险高，同时由于法律和监管的原因，初创公司的融资成本很高，所以融资成本高昂阻碍了文化创意产品的繁荣。
1.3.	传统互联网股权众筹的问题
	2009年kickstarter的出现，为创意产品提供了新的互联网众筹的融资模式，但是kickstarter的众筹是公益性的捐赠，没有分红权，因此能够筹集到的资金有限，2018年Kickstarter上众筹金额最多的项目是520万美元，第20名是130万美元。而在Kickstarter基础发展起来的股权众筹则面临着政府的严格监管，同时股权缺乏退出渠道，没有流动性，投资参与人数少，因此很难成为创意产品的融资方式。
1.4.	ICO的成功与失败
	比特币、以太坊等区块链平台出现后，ICO成为一种新的融资方式，以区块链智能合约技术为基础，资产发行的成本很低，在各种区块链代币交易平台支持下，代币发行后即可上市交易获得流动性，早期投资人退出时间大大缩短，2017年，ICO融资达到高潮，我们应该看到，ICO成功的关键因素是其超高的流动性。但由于ICO没有任何监管，因此伴随着很多ICO骗局，给投资人造成损失，并最终ICO被主流国家禁止，在少数国家允许在监管机构注册许可后发行ICO，受监管后的ICO任然没有降低融资成本。
1.5.	IEO的问题
ICO被禁止后，2019年，IEO成为一种新的代币融资发行机制，通过IEO，代币可以融资后直接上市交易，为了吸引投资人，项目方通常会在交易后拉高价格，需要付出比融资金额更多的资金成本，所以IEO实际并不是一种融资方式，只是一种吸引流量的方式，同时需要为此付出高额成本，而为了收回成本，项目方不得不进行二级市场价格操纵，从而期望获利，而早期投资人也并不关心项目的实际价值和意义，他们期望项目方能够操纵二级市场价格，从而让他们卖出获利，所以当项目方采用IEO的方式融资的时候，交易所、项目方和投资人实际形成了恶的共同体。	
区块链发展到今天，仍然没有解决融资成本问题。

2.	寻找更好的ICO-DAICO
	为了避免ICO融资形成的缺点，寻找更好的ICO机制，许多人进行了探索，2017年Vitalik对DAO和ICO结合的形式——DAICO进行了探讨，2017年，Simon de la Rouviere第一次提出了以债券曲线作为一种代币发行机制的概念，而bancor项目则提出了以bancor协议作为代币发行机制，以bnt代币为储备金。2018年，Wilson Lau讨论了以双曲线债券曲线模型为项目方融资模式。
2.1.	债券曲线
债券曲线是一种特定类型的智能合约，通过买卖功能发行自己的代币。为了购买代币，买方将资金（如ETH/DAI）发送到买函数，该函数计算代币的平均价格并向你发送正确的代币数量。卖出函数则反向运行，合约计算当前代币的平均价格，并向你发送正确的资金数量。（摘录自Token Bonding Curves Explained）
债权曲线具有以下特点：
λ	无限供应。可以铸造的令牌数量没有限制。
λ	确定性价格计算。令牌的买卖价格随着令牌的数量而增加或减少。
λ	保证和即时流动性。债券曲线合约是交易的交易对手，并且总是保留足够的ETH来回购买代币。因此，令牌可以随时立即购买或出售，粘合曲线充当自动化做市商。
λ	持续的价格。令牌n的价格低于令牌n + 1并且高于令牌n-1，计算给定量的ETH（或给定量令牌发回的ETH的数量）铸造的令牌数量需要一些积分微积分。
算法模型：
债券曲线可以有多种计算模型，例如直线型、指数型、倒数型，我们以最简单的直线型债券曲线为例，x轴表示代币发行的数量Q，y轴表示价格，价格可以用y=x来表示。在Q(0)点买入Q(1)-Q(0)数量的代币，所要花费的资金总额是A区域面积。




2.2.	双曲线融资模型：
债券曲线的基本模型只是一种代币发行机制，但并没有考虑项目团队如何获得和使用资金，早期一些想法是在买和卖之间建立差价，差价作为项目团队的资金，自由支配。2018年，WilsonLau对利用债券曲线作为融资机制进行
了探讨。
2.3.	CO持续性组织
2018年，thibauld建立持续性组织（Continuous Organization,CO），一个持续性组织是一个发行称为FAIR的完全数字化的证券，而其部分或全部现金流会流入一个分散式自治信托（Decentralized Autonomous Trust， DAT)，一个DAT是一个利用债券曲线自动挖矿、销毁和分发FAIR证券的合约。
CO主要通过双曲线债券曲线机制实现为组织持续筹款，投资人不拥有组织，组织自行决定所筹资金用途。
2.4.	CO双曲线融资模型
CO使用2种不同函数的债券曲线，一种用于买入曲线，另一种用于卖出曲线：B（对于buy）和S（对于sell）存在。

 投资 - buy（）
对于投资者，他们通过调用DAT的buy()功能来做到这一点。每当“外部”投资者（而不是组织本身）向DAT发送资金时，发送的一小部分资金将由DAT保留在“回购”储备中，其余资金将转移到组织的钱包。调用buy()时，I百分比比例的资金会保存到回购准备金中。I是一个常数。

投资发生时的资金流

投资发生时对DAT债券曲线合约的影响
当投资者购买代币时，他们希望投资于底层组织。投资者不希望他们的钱被DAT保留，他们希望他们的钱能够被组织好好利用。因此，s的值必须比b低一个数量级。
示例：假设投资者向DAT发送10 ETH ，如果I = 10％，则DAT将9 ETH转移到组织的钱包，并将在其“回购”储备中保留1 ETH。
当投资者以成本c购买FAIR时，他会收到x FAIR，x等于：

其中，c是用来购买FAIR的金额，b是卖出斜率，而a是交易前已经在流通的FAIR数量。
投资者-sell():
投资者可以随时决定出售他们的FAIR以获得ETH。他们通过调用DAT的sell()功能来做到这一点。当DAT收到FAIR时，它会销毁收到的FAIR并根据功能S（对于sell）将ETH发送回卖出的投资者。S有一个斜率s,会随着DAT收到付款而增加。发回给投资者ETH是取自DAT “回购”储备，并不会影响到公司的现金储备。

发生FAIR卖出时的资金流：

当投资者出售其代币时对DAT的债券曲线合约的影响
微积分:
当投资者出售x FAIR时，假设之前没有FAIR被烧毁，他会收到一笔金额c，c等于：

s是卖出曲线的斜率，a是FAIR交易前的流通数量。
完整的算法及证明请参考这里。
3.	FutureDAO
3.1.	设计哲学
FutureDAO的核心目的是希望降低初创公司或组织的融资成本，因此保护投资人的利益和权益是FutureDAO设计的核心思路。我们希望通过债券曲线解决小型企业股权的流动性缺乏的问题，同时认为所有投资人共同拥有组织，拥有组织资金使用的决策权，通过投票决定资金使用提案是否通过。
3.2.	单曲线VS双曲线
在单曲线融资机制下，所有的资金都是储备金，同时组织有权利决定所有资金如何使用，单曲线融资机制的优点是，当出现51%攻击时，其他人可以立即退出保护自己，但是100%储备金有利于投机，在极端情况下，模型会简化为FOMO模式，同时在大户退出时可能会形成恐慌挤兑，从而让组织流动性枯竭，没有足够资金支撑项目发展。同时，100%储备金制度下，当社区发生重大矛盾时，按持股比例清退基金也不可能，因为当清退即将发生时，从债券曲线合约抢先退出是最有利的，从而大家都会争先恐后退出，引发挤兑。
在双曲线融资机制下，部分资金作为储备金，以支持投资人随时退出，另一部分作为项目治理资金池，用于项目发展，通过储备金池退出时，不影响项目资金，不会出现恐慌挤兑，保证了项目安全。但是，由于治理池的资金只能通过投票使用，部分储备金制度会面临51%攻击问题。
FutureDAO使用CO的双曲线债券曲线模型作为融资机制，同时通过简单多数投票对组织资金进行治理，在部分储备金制度下51%攻击无法完全消除，但是我们可以尽可能提高51%攻击难度。
3.3.	链上治理
3.3.1.	投票
FutureDAO通过简单多数投票实现治理，投资人的持股数即为投票权重。为避免51%攻击问题，当反对票达到总票数30%时，提案即被否决，由于大部分人实际上并不会参与到治理中，因此通常是很难达到30%的投票量的，此时简单多数投票是有效的，但是当出现攻击时，攻击会在社区传播，每个投资人都应该通过投票保护自己。30%反对票否决提案不能完全避免51%攻击，但是将51%攻击的难度提高到71%。
3.3.2.	清退
当社区发生不可调和的矛盾时，例如核心成员退出，持续的30%反对票否决提案，或者项目周期已经完成时，投资人可以按持股比例从所有资金中退出资金，我们可以有一个清退提案，当达到30%比例（或其他）票数想清退时，他们就可以从所有资金池按比例拿走资金同时销毁股份，剩下的人继续管理组织。清退是良性的，而不像51%攻击应该竭力避免，因为至少投资人的资金得到了保证，而清退的资金可以重新投入到其他组织中去，是一次资源再分配的过程。
3.3.3.	预挖
当一个项目在融资时，他可能不止仅是一个想法，而是已经有了一个团队，并做了一些工作，在这种情况下，创始团队可以通过预挖为自己保留一部份股份。但是预挖会使卖出曲线的斜率变小，增加了后期投资人盈利的难度。预挖的股权需要锁仓一定时间，以避免创始团队欺诈，并提供激励。
3.3.4.	种子轮融资
当一个项目开始融资时，不应该从一开始就应用债券曲线，而是应该设置启动资金门槛，当在规定时间段没有达到融资门槛时，募集到的资金应原路返还给投资人，我们称之为种子轮融资。种子轮融资可以为设置初始发行价和发行数量，达到门槛后开始应用债券曲线，由于种子轮投资者在价格上有优势，因此种子轮投资者的股权同样应该锁仓一定时间。
3.4.	链下治理
FutureDAO的核心目的在于降低初创组织的融资成本，组织本身究竟是去中心化组织还是公司组织并不重要。实际上，出于效率考量，我们鼓励执行团队是一个公司组织。链上治理的核心在于资金如何使用以及避免51%攻击，不需要深入到组织治理的所有细节。理论上，组织所有成员都可以发起提案，但这是不应该的。组织应该有链下治理规则，例如应该有执行团队和大股东组成的理事会，理事会负责决定组织发展战略，制定预算，发起提案。同时全体股东可以投票选举监事成员，组成监事会，监事会负责监督理事会和执行团队，可以负责号召股东投反对票反对提案以及发起清退投票。理事会可以以时间单位例如季度或年度制定预算，也可以以里程碑为单位制定预算，提案通过后，预算内资金可以由执行团队自由裁决。为进一步增加资金使用透明度，理事会和监事会可以形成私有DAO，预算资金流入私有DAO，由少数人投票决定资金使用。
4.	合规
我们不认为FutureDAO的设计应该完全符合目前的金融监管法律，我们理解监管的核心目的是控制风险，例如控制初创企业的众筹金额，如果我们完全符合SEC关于初创公司的众筹监管法律，那么债券曲线无法有效运转。但是，智能合约本身就是监管手段，如果我们认为什么规则可以控制风险，我们可以直接写在合约里，DAO可以有多种控制风险的手段，例如所有人都可以参与资金使用的决策，例如储备金退出和清退退出，我们也可以在合约里限制每年最大可以使用的金额而不是控制融资金额。所以在DAO机制内，整体风险都是可控的，当前的监管规则是基于过去的技术条件制定的，当我们有新的技术和机制来控制风险时，不应该被过去的监管法律所束缚，从而发挥不出新技术的潜力。
5.	应用场景
理论上FutureDAO可以作为任何组织的股权融资管理平台，但是我们认为最合适的是有清晰盈利模型和盈利预期的轻资产的文化创意创业公司，例如游戏、动漫等领域。我们可以通过DAO的组织形式来组织产品的生产，而产品本身不一定必须是应用了区块链技术，以游戏为例，游戏本身可以不需要是区块链游戏，可以是面向传统游戏玩家的作品，从而增加盈利预期。未来，当支付本身也发生在区块链上后，我们可以形成链上的融资、支付、分红的完整去信任化流程，投资人的权益得到最大化保障，从而降低投资成本，促进投资市场的繁荣。
6.	价值与意义
我们认为DAICO平台的价值与意义是重大的，他通过流动性储备金制度和链上治理机制，降低了初创企业的融资成本，特别适合文创公司融资，同时当一个初创公司通过DAICO平台进行融资开始，它就已经是一个上市公司，完全公开，共同治理，股票可以随时交易。智能合约和代币经济学的应用，降低了分布式组织的管理成本，交易摩擦，平衡了股东和执行团队之间的权利和义务，将会促进社会的创新和繁荣。
7.	总结
扎卡伯格夫人普莉希拉·陈在一次采访中说：“运气不应该是成功的重要因素”，而运气之所以成为因素，是因为过去小企业的融资成本太高，很多有才华的人很难获得资金展示自己的才华，而合理的DAICO模型应该能够降低分布式组织的管理成本，融资成本，能够让才华和资金更容易的匹配，让才华更轻松的体现出自己的价值。让有才华的人更容易成功，让社会的文化更加的繁荣丰富，这就是FutureDAO的愿景。





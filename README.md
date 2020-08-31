# vnpy-Enterprise

VNPY官网： http://www.vnpy.cn
VNPY扎根于国内合规期货市场和A股市场，为金融机构和量化爱好者提供全系列的量化产品线， 包含了历史行情数据、实时行情数据、仿真回测、商业化软件（资管系统、跟单软件）。


VNPY仿真回测系统解决了第三方回测框架各自一套费标准方法的问题，通过对原生API进行仿真来实现回测，这样做的好处是可以提供和原生API一致的方法，不再依赖于平台，所以VNPY仿真回测系统支持市场上绝大多数的CTP框架。

VNPY仿真回测目前主要提供了基于CTP接口（支持商品期货、股指期货、商品期权、股指期权）的仿真。

http://www.vnpy.cn

无论是你自己开发的CTP系统还是CTP框架，甚至是快期V2交易客户端，都可以通过替换dll方式接入VNPY仿真柜台柜台。

VNPY仿真回测系统开创了第4类回测，并且受国家专利法保护。

VNPY仿真回测这项底层仿真回测技术是和编程语言无关的，并且没有第3方平台提供的方法，可以在不修改原有代码的前提下实现回测。

VNPY仿真回测支持各种自编CTP程序，例如C++、Python、JAVA、C#等，同时还支持各种编程语言框架和自编程序。几乎是无所不兼容，这样的产品避免了CTP策略开发者过于依赖平台的窘境。

大多数基于K线的回测都会丢失不少细节的，会产生较大的回测误差，会误导策略开发者。

此外，由于VNPY仿真回测是基于TICK的回测，比大多数第三方软件回测精度高2个数量级以上，实现更精细化的回测。

可以真正帮助策略开发者掉入量化交易回测陷阱。

VNY的优势远远大于第三方期货量化软件回测，可以真正避免了和真实盘口不一致的情况，几乎100%还原了真实的价格变化，是真正面向职业开发者的好产品。

很多量化交易软件回测曲线是这样的

![Image text](http://www.vnpy.cn/comm/assets/uploads/files/1598886338836-000f9971-86c0-4ab0-9619-85ab688606b2-%E5%9B%BE%E7%89%87.png)


而VNPY仿真回测柜台资金曲线是这样的

 ![Image text](http://www.vnpy.cn/comm/assets/uploads/files/1598886349349-bc94ac89-81bd-40af-9998-ce4149b80f07-%E5%9B%BE%E7%89%87.png)

在采用VNPY仿真回测资金曲线和实盘资金曲线分时图取样资金曲线的比较，几乎达到了99.99%的一致。

VNPY仿真回测系统提供了基础免费版本，对所有人免费。
VNPY仿真回测系统在量化行业有多棒，答案就是VNPY最棒棒。

 

VNPY仿真回测柜台在VNPY开源框架基础以外，真正实现了和平台无关的基于TICK级的精细化回测


项目捐赠

需强调：VNPY是免费开源项目，不接受任何捐赠！任何打着VNPY旗号索取捐赠的均为利益误导和诈骗。




VNPY是一套基于Python的开源量化交易系统开发框架， 在开源社区6年持续不断的贡献下一步步成长为全功能量化交易平台，目前国内外金融机构用户已经超过500家，包括：私募基金、证券自营和资管、期货资管和子公司、高校研究机构、自营交易公司、交易所等。

 

在使用VNPY进行二次开发（策略、模块等）的过程中有任何疑问，请查看VNPY项目文档，如果无法解决请前往官方社区论坛的【提问求助】板块寻求帮助，也欢迎在【经验分享】板块分享你的使用心得！

针对VNPY的金融机构用户，创建了一个专门的【VNPY机构用户群】（QQ群号：236828089），主要分享机构应用方面相关的问题，如：银行间市场接入、资管O32系统、分布式部署等内容。请注意本群只对金融机构用户开放，加群时请注明：姓名-机构-部门。
功能特点

    全功能量化交易平台（vnpy.trader），整合了多种交易接口，并针对具体策略算法和功能开发提供了简洁易用的API，用于快速构建交易员所需的量化交易应用。

    覆盖国内外所有交易品种的交易接口（vnpy.gateway）：

        国内市场

            CTP（ctp）：国内期货、期权

            CTP Mini（mini）：国内期货、期权

            CTP证券（sopt）：ETF期权

            飞马（femas）：国内期货

            恒生UFT（uft）：国内期货、ETF期权

            宽睿（oes）：国内证券（A股）

            中泰XTP（xtp）：国内证券（A股）、ETF期权

            恒生期权（hsoption）：ETF期权

            华鑫奇点（tora）：国内证券（A股）

            飞鼠（sgit）：黄金TD、国内期货

            金仕达黄金（ksgold）：黄金TD

            鑫管家（xgj）：期货资管

            融航（rohon）：期货资管

            中汇亿达（comstar）：银行间市场

        海外市场

            富途证券（futu）：港股、美股

            老虎证券（tiger）：全球证券、期货、期权、外汇等

            Interactive Brokers（ib）：全球证券、期货、期权、外汇等

            易盛9.0外盘（tap）：全球期货

            直达期货（da）：全球期货

            MetaTrader 5（mt5）：外汇、CFD、期货、股票

            Alpaca（alpaca）：美股（零佣金）

            佳兆业投资（kasia）：港股

        数字货币

            BitMEX（bitmex）：数字货币期货、期权、永续合约

            Bybit（bybit）：数字货币永续合约

            币安（binance）：数字货币现货

            币安永续（binances)：数字货币永续合约

            OKEX（okex）：数字货币现货

            OKEX永续（okexs）：数字货币永续合约

            OKEX期货（okexf）：数字货币期货

            OKEX期权（okexo）：数字货币期权

            火币（huobi）：数字货币现货

            火币期货（huobif）：数字货币期货

            火币永续（huobis）：数字货币永续

            Gate.io永续（gateios）：数字货币永续合约

            Deribit（deribit），数字货币期权、永续合约

            Bitfinex（bitfinex）：数字货币现货

            Coinbase（coinbase）：数字货币现货

            Bitstamp（bitstamp）：数字货币现货

            1Token（onetoken）：数字货币券商（现货、期货）

        特殊应用
            RPC服务（rpc）：跨进程通讯接口，用于分布式架构

    开箱即用的各类量化策略交易应用（vnpy.app）：

        cta_strategy：CTA策略引擎模块，在保持易用性的同时，允许用户针对CTA类策略运行过程中委托的报撤行为进行细粒度控制（降低交易滑点、实现高频策略）

        cta_backtester：CTA策略回测模块，无需使用Jupyter Notebook，直接使用图形界面直接进行策略回测分析、参数优化等相关工作

        spread_trading：价差交易模块，支持自定义价差，实时计算价差行情和持仓，支持半自动价差算法交易以及全自动价差策略交易两种模式

        option_master：期权交易模块，针对国内期权市场设计，支持多种期权定价模型、隐含波动率曲面计算、希腊值风险跟踪等功能

        portfolio_strategy：组合策略模块，面向同时交易多合约的量化策略（Alpha、期权套利等），提供历史数据回测和实盘自动交易功能

        algo_trading：算法交易模块，提供多种常用的智能交易算法：TWAP、Sniper、Iceberg、BestLimit等等，支持常用算法配置保存

        script_trader：脚本策略模块，针对多标的组合类交易策略设计，同时也可以直接在命令行中实现REPL指令形式的交易，不支持回测功能

        chart_wizard：K线图表模块，基于RQData数据服务（期货）或者交易接口（数字货币）获取历史数据，并结合Tick推送显示实时行情变化

        portfolio_manager：投资组合模块，面向各类基本面交易策略，以独立的策略子账户为基础，提供交易仓位的自动跟踪以及盈亏实时统计功能

        rpc_service：RPC服务模块，允许将某一VN Trader进程启动为服务端，作为统一的行情和交易路由通道，允许多客户端同时连接，实现多进程分布式系统

        data_manager：历史数据管理模块，通过树形目录查看数据库中已有的数据概况，选择任意时间段数据查看字段细节，支持CSV文件的数据导入和导出

        data_recorder：行情记录模块，基于图形界面进行配置，根据需求实时录制Tick或者K线行情到数据库中，用于策略回测或者实盘初始化

        excel_rtd：Excel RTD（Real Time Data）实时数据服务，基于pyxll模块实现在Excel中获取各类数据（行情、合约、持仓等）的实时推送更新

        risk_manager：风险管理模块，提供包括交易流控、下单数量、活动委托、撤单总数等规则的统计和限制，有效实现前端风控功能

    Python交易API接口封装（vnpy.api），提供上述交易接口的底层对接实现。

    简洁易用的事件驱动引擎（vnpy.event），作为事件驱动型交易程序的核心。

    跨进程通讯标准组件（vnpy.rpc），用于实现分布式部署的复杂交易系统。

    Python高性能K线图表（vnpy.chart），支持大数据量图表显示以及实时数据更新功能。

    社区论坛和知乎专栏，内容包括vn.py项目的开发教程和Python在量化交易领域的应用研究等内容。

    管理严格（定期清除长期潜水的成员），入群费将捐赠给vn.py社区基金。
    
    高频金融市场中交易策略的使用会产生不同的影响。目前还没有专门设计用来评估市场流动性的工具。然而，它通常是通过观察证券买卖价差的大小来评估的。根据经验法则，最佳投资方案和最佳兜售方案之间的小差距是流动性充裕的标志，而大差距则表明流动性不足。基于这一原理，研究人员一致认为，高频交易者所采用的套利和做市策略对市场流动性的贡献极为有利。一些研究人员解释说，他们已经在市场上高频交易的存在与供求之间建立了一种负相关关系。因此，托管大大优化了交易时间，增强了交易者的决策能力。

托管是指数据中心内属于证券交易所的专用空间。它用于获得执行订单的速度（以纳秒为单位），尽可能接近股票交易所的交易引擎。
基于VNPY数据采集工具采集的TICK数据

分7个目录2017.11~2018.11期货全品种TICK数据解压后100Gb（DataCollect格式）百度网盘下载
网盘下载的数据 CSV数据文件字段顺序：
localtime (本机写入TICK的时间),
InstrumentID (合约名),
TradingDay (交易日),
ActionDay (业务日期),
UpdateTime （时间）,
UpdateMillisec（时间毫秒）,
LastPrice （最新价）,
Volume（成交量） ,
HighestPrice （最高价）,
LowestPrice（最低价） ,
OpenPrice（开盘价） ,
ClosePrice（收盘价）,
AveragePrice（均价）,
AskPrice1（申卖价一）,
AskVolume1（申卖量一）,
BidPrice1（申买价一）,
BidVolume1（申买量一）,
UpperLimitPrice（涨停板价）
LowerLimitPrice（跌停板价）
OpenInterest（持仓量）,
Turnover（成交金额）,
PreClosePrice (昨收盘),
PreOpenInterest (昨持仓),
PreSettlementPrice (上次结算价)

 
 

贡献代码

VNPY使用Github托管其源代码，如果希望贡献代码请使用github的PR（Pull Request）的流程:

    创建 Issue - 对于较大的改动（如新功能，大型重构等）最好先开issue讨论一下，较小的improvement（如文档改进，bugfix等）直接发PR即可

    Fork vn.py - 点击右上角Fork按钮

    Clone你自己的fork: git clone  
        如果你的fork已经过时，需要手动sync：同步方法

    从dev创建你自己的feature branch: git checkout -b $my_feature_branch dev

    在$my_feature_branch上修改并将修改push到你的fork上

    创建从你的fork的$my_feature_branch分支到主项目的dev分支的[Pull Request] - 在此点击compare across forks，选择需要的fork和branch创建PR

    等待review, 需要继续改进，或者被Merge!

在提交代码的时候，请遵守以下规则，以提高代码质量：

    使用autopep8格式化你的代码。运行autopep8 --in-place --recursive . 即可。
    使用flake8检查你的代码，确保没有error和warning。在项目根目录下运行flake8即可。



 

长期维护捐赠清单，请在留言中注明是项目捐赠以及捐赠人的名字。
 

版权说明  

MIT

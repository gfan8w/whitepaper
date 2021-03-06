### **I.Abstract**

> big data era arrived, internet of everything is not far away. The ability of human in produce, acquire, and process data has been dramatically improved. Proper usage of data could greatly advance our knowledge of the world, the reaction to demands, plans for the business and society activity, as well as cooperation.

With the rapid development of internet and information technology, the speed of data production increase exponentially in recent years. For the society, data is a continuously expanding treasure. However, as the amount of data skyrocketed, data monopoly and information silo issues becoming increasingly urgent. Get data flowing and utilize it legally could yield unimaginable value to social productivity and economy.

Data is the most important means of production in the future, not only in a giant scale but continuously change with the evolution of human activity. Data is the key for us to understand business and society, which is indispensable for most industries. The blockchain is one of the inevitable and fundamental technology in the future, building an “internet of value” that could be maintained and participated by everyone. As a trusted internet, blockchain is capable of minimizing the cost of data transfer and exchange.

**The combination of data, the most valuable resource, and blockchain, an essential technology in the future, could discharge huge business and society value, which establishes the mission and vision our team.**

We have been building several products based on blockchain and data. As the cornerstone, GXChain combined big data and blockchain. The aim of GXChain is to build a trustworthy and all around applicable data exchange network, enabling data from every aspects to flow, circulate, and exchange efficiently, saving them from silo and monopoly, and facilitating them to provide more for our life.

### **II.The “CBD” Ecosystem**

Leverage blockchain technology and current pain points of the society, we designed a new business model – the CBD ecosystem, “C” refer to customer, “B” refer to “business”, and “D” refer to “developer”.

### Blockcity – a mobile app designed for the customer (To C)

Blockcity is the mobile app based on GXChain, it is designed for assisting data management and sharing. Blockcity helps users to take control of their data, it has a lot of incentive to encourage users to authorize their identity and information. Blockcity does not cache data, and protect the privacy of the users. 

### Decentralized data marketplace (To B)

The data marketplace provides an alternative to traditional data transactions, including data trading through middlemen or underground data transaction. The decentralized data marketplace has many advanced features: including data uncached, privacy protection, copyright protection, fraud prevention, and bilateral anonymity support. Currently, the data marketplace providing services for various industries, including fintech startups, loans, peer-to-peer lending, banks, governments, insurance companies, healthcare, and logistics. The marketplace commercialized on September 24th, 2017. To date, revenue of the marketplace passed 7 million USD. 

### GXChain – a public blockchain for developers (To D)

GXChain is a permissionless blockchain, which greatly supports all kinds of app development. Comparing to other public chains, GXChain not only supports smart contract, blockchain as a service (BaaS) but also provides many unique services, including ID verification, multi-dimensional data, KYC, and swift login. GXChain currently offers 100,000 TPS, which can accommodate most business applications. GXChain also supports new assets issuance.

### Connect customers, businesses, and developers with data

Blockcity is designed for general public, which is the passport for the blockchain world. After real name verification, a unique G-ID will be generated for using services at Blockcity. Users can consolidate their data through third-party platform authorization and data exchange service (DES), enabling users to purchase their data from decentralized data marketplace. The more abundant of data category that users have, the more they could earn from the incentive. In addition, data that generated from application usage also belongs to users. If business or company want to check users’ data, like credit information, they need to acquire the authorization before checking their data. To sum up, Blockcity facilitates customers to profit from the usage of their data or information. 

The decentralized data marketplace originally designed for B2B, now we expand the scope from B2B to B2B, B2C, C2B, and C2C via data exchange service. As a result, individual used to be a data generator, now they can act as a data seller.

Developer is the most important part in the “CBD” ecosystem. Applications developed on GXChain will become a critical part of data generation and consumption. Both developers and users could profit from the usage of the application. Upon agreement of profit distribution, developers can help users monetize their data and information while earning from their usage.

### **III.GXChain**

GXChain is a public blockchain for data exchange, developed by GXB team. GXChain is the foundation of GXB data exchange, supporting the exchange of data in a million times per second. In addition, GXChain also supports app development. Apps developed on GXChain will be greatly supported by bigdata among various fields, which set GXChain apart from other public blockchains. Apps developed on GXChain would be real life oriented.

GXS data exchange, the first to business application based on GXChain, commercialized on September 24th, 2017, proving the commercial feasibility of GXChain. To date, data transaction on GXB data exchange platform passed 700 million times.

Moreover, the second application based on GXChain, GXB Decentralized App \(Dapp\), which aims for personal credit management and face to face credit verification. The alpha version will release at the end of 2017.

#### **Consensus algorithm**

GXChain is using delegate proof of stake\(DPoS\) for bookkeeping on blockchain and proof of credit share\(PoCS\) for data exchange consensus.  
DPoS is originated from Graphene, it is an alternative consensus mechanism that requires coin holders to vote for “delegates”, who are then responsible for validating transactions and maintaining the blockchain. In DPoS, stakeholders elect what are known as witnesses. Witnesses are responsible and rewarded for generating blocks which are then added to the blockchain. DPoS is an alternative to the more commonly known, Proof-of-Stake model which requires miners to put up a stake in a cryptocurrency in-order for them to be able to validate transactions.

PoCS, is a consensus algorithm developed by GXB team, aiming to solve the imbalance of exchange of data between big companies and small companies. Each PoCS score of alliance members will be calculated when they finished exchanging of data. In other words, PoCS score is based on transaction frequency, and the score will contribute to the transaction fee. Members with lower PoCS score will pay more transaction fee for the data, while members with the higher score will spend less on transaction fee.

Here is the psedo code for PoCS mechanism:

```
if ((total_sell + total_buy) >= pocs_threshold) {

    pocs = calculate_pocs(total_sell, total_buy);

    fee = scale_fee(pocs, data_transaction_base_fee);

} else {

    fee = data_transaction_base_fee;
}
```

pocs is the PoCS score, alliance members will have their unique PoCS score.

total\_sell is the frequency of data sold by the member.

total\_buy is the frequency of data bought by the member.

pocs\_threshold is the threshold to determine whether to reduce the transaction fee for members.

data\_transaction\_base\_fee is the basic transaction fee charged for exchange of data.

calculate\_pocs is the function to calculate PoCS score.

scale\_fee is the function to calculate transaction fee.

#### **Reasons to choose DPoS consensus algorithm**

Currently, most projects employed PoW and PoS as their consensus algorithm, and some projects used modified BFT. Bitcoin, the most successful cryptocurrency based on PoW, demonstrating the stability and fairness of PoW algorithm. However, bitcoin is often criticized for its energy-intensive mining activity. Billions of Dollars are investing to perform calculation SHA256 for maintaining the network, and besides that, no other utilization was involved in this activity. In addition, current transaction speed of bitcoin is 5 TPS, limited by its controversial block size, and 25 TPS for another famous project, Ethereum, hindered by maximum GAS of single block. These numbers are far from VISA and Mastercard, that able to deal with thousands of transactions per second.

Peercoin and NXT brought two relatively matured blockchain based on PoS algorithm, featured energy friendly compared with PoW projects. Achieving PoS consensus by introducing the coin age theory. Instead of buying expensive mining equipment, PoS algorithm enables more people to attend bookkeeping. The computing power is correlated with the holding tokens and holding time. One hold more tokens for more time, the more possibility of generating blocks he will be.  Once he generates a new block, the number of whose coin age will be initialized to zero. Then a new loop starts.

Under PoS Consensus, people tend to lock coins for a long time to get more return, limiting coin supply and circulation, which is adverse to the price stability. Moreover, it is also possible that the majority token is held by a small portion of people, making the whole blockchain network more centralized. Compared to the PoW consensus algorithm, the cost of being dishonest is much lower, as a result, it demands more mechanism for preventing fork/double spending attacks, as well as realizing consensus.  Normally blockchain network with PoS algorithm could generate 12 transactions per second, however, due to consensus issues and network delay, it takes 60 seconds to finish broadcasting reliable blocks. In the long term, speed for generating new blocks is far lower than network communication and broadcasting, as a result, blockchains based on PoS have to limit the speed of block generation to keep the stability of main net.

DPoS could inherently overcome drawbacks of PoW and PoS in processing efficiency. DPoS algorithm requires verification of current block has been signed by a trusted node before generating next block. DPoS employs a committee mechanism by choosing trustable nodes\(witnesses\)to represent other token holders for bookkeeping. Witnesses are required to remain online for a long time, solving the block generation delay problems occurred on blockchains based on PoS. DPoS is capable of 10000-100000 TPS, depending on the network quality, which is suitable for industrial applications. GXB data exchange platform requires high transaction frequency and network stability, making DPoS is an exclusive choice.

#### **Features of GXChain**

**High-performance and expandable**

GXChain can process 10000-100000 transactions per second, with 3 seconds blocktime. Considering the growing demand of on-chain business, GXChain can expand horizontally, enabling even higher transaction speed without a hard fork.

**Real-time parameter adjustment**

Instead of a fork to realize change parameters, GXChain can change blocktime, blocksize, transaction fee etc. via voting.

**Supported by big data**

GXB data exchange support data transaction or exchange in multiple industry. Companies and individuals could acquire those data via purchase.

**Blockchain as a service**  
GXChain also supports services API, including storage and verification.

**Support for application development**

Apps developed on GXChain would get support by numerous data from multiple field on the data exchange

**User-Issued Assets**

GXChain allows individuals and companies to create and issue their own tokens.

**Open source**

We made GXChain code open to the public at [https://github.com/gxchain](https://github.com/gxchain)

#### **Technical structure**

![](/assets/gxsaa.png)

#### **GXChain development kit**

![](/assets/gxsproduct.png)

GXChain support developers to use modularized services for application development, including DES, BaaS, Cli-API, Statistical Analysis API, and Blockchain Explorer API.

#### Data Exchange Service (DES)
A service for data exchange, based on GXChain. DES support smart contract, which supports tri-party bookkeeping agreement, and a peer to peer data exchange protocol based on IPFS. The protocol provides reliable, safely, high-throughput data exchange service, and will automatically record the history of data exchange. One can use DES for permanent proof of existence, and data copyright registration.

#### Blockchain as a Service (BaaS)
Encapsulation a lot blockchain system API to provide simple and handy services. Currently, BaaS supports data storage, proof of existence and verification. Developers can store application data on GXChain, realizing openness of data accounting.

#### Cli-API
Enables usage of command-line wallet, which could visit ledger and process transaction directly.

#### Statistical analysis API
Support statistical analysis of GXChain ledger, facilitate developing data visualization functions.

#### Blockchain explorer API
Enable checking various information, including block, transaction, account information, and support developers to using web and API manners https://block.gxb.io/#/.


#### **IV. GXS**
GXS is the **utility token** on GXChain, issued by GXS Foundation Ltd. All data services on GXChain will be settled by GXS.

• Total supply: 100,000,000

• ICO amount: 24,510,000

• Private equity distributed amount: 10,000,000

• Blockcity mining pool: 5,000,000  

• Community developer support: 9,490,000

• GXS foundation: 51,000,000

The token hold by GXS foundation is frozen at the time of initial coin offering and will unfreeze 6,000,000 for the first year. Start from the second year, the unfrozen amount will be 5,000,000. The fund is for hiring, consulting, business development, and marketing activities. GXS foundation account is open to the public for supervision, one can check through GXChain block explorer.


GXS has the following values:

• GXS would be consumed for app development, certification, and services on GXChain.

• GXS could be used as the ballot for voting witnesses.

• GXS is payment for using applications at the GXChain ecosystem.

**GXS business model**

GXS is the essential media to connect businesses, customers, and developers. It has the following applications：

**To Customers**

• GXS can be mined at Blockcity, it is a way for user incentive.

• GXS can be acquired by finishing quests and tasks.

• GXS can be rewarded for contributions at GXChain community.

• GXS can be acquired/consumed by peer to peer data transactions.

• GXS can be consumed by using services at Blockcity.

• GXS can be consumed by using blockchain as a service (BaaS) on GXChain.

• GXS can be used for payment third party applications.

**To Developers**

• GXS can be rewarded for contributions at GXChain community, including bug bounty program.

• Developers can deploy their applications on GXChain, and customers using GXS as a payment method for using/buying applications.

• GXS can be consumed by using blockchain as a service (BaaS) on GXChain.

• GXS is required for developer registration. 

### **V.GXChain team**

#### **Minqiang Huang** 
Founder and Chief Executive officer

Minqiang has over 10 years experience in data exchange, financial technology, and blockchain, he dived into cryptocurrency in 2012, and initiated several projects since then. He used to be CTO at Hakim Unique Internet Co Ltd \(SHE:300300\), and Director at financial services of HAKIM UNIQUE. He received his bachelor in computer science at Shandong University of Science and Technology, He received his master in management at Hong Kong Finance and Economics College. Besides blockchain, Minqiang is interested in ultramarathon, trail running, and mountain biking.

#### **Guojun Tu** 
Co-founder and Vice President

Guojun was a senior executive at 3 public traded IT company, he is a serial entrepreneur, who had more than 21 years’ experience in the field of information security, payment, and IT. Guojun received his bachelor degree in computer science at Hunan University.

#### **Cheng Wang** 
Chief Technology Officer

Cheng is a data expert, proficients in data collection, cleaning, machine learning and mining. He used to work as a full stack engineer at 51.com. Before 51 he worked at treefinance.com, and Vobile Info Tech Co., Ltd. as a core developer.

#### **Ruosong Xu** 
Chief Marketing Officer

Ruosong used to work at Huawei Technologies, China Mobile, and Tongdun. He is an expert in credit risk control.

#### **Xiaopeng Xu** 
Operations Director

Xu has 6 years experience of sales and marketing. He used to be marketing project manager at ZheJiang Media Group, Simei Media \(SHE: 002712\), and NetEase, Inc. \(NASDAQ: NTES\)

#### **Liyu Wu** 
Product manager

Liyu used to work as a senior product manager at NetEase,Inc.\(NASDAQ: NTES\), before NetEase he worked at Hithink Flush Information Network Co Ltd\(SHE: 300033\) and weidai.com.cn as product designer. He experienced in product management for both customer and business application.

#### **Xin Cai** 
Operations Manager

Xin used to be oversea technology manager at a fortune 500 company, she is proficient in Japanese, English, and Korean. Currently, she is responsible for business development at . Xin received her master degree in wireless communication at Osaka University.

#### **Haoxiang Lan** Full-stack Engineer, Data Exchange Product Director

Haoxiang is an expert in Node.js, iOS, frontend/backend development. He is experienced in blockchain development, especially for the application layer. He used to work at 51.com and treefinance.com as frontend engineer. Together with Cheng Wang, he developed a unique data crawling method for backend/frontend interaction, which has been widely imitated by competitors.

#### **Junjie Zhang** Full-stack engineer, UI design, Front-end/back-end web development

Junjie proficient in node.js, python. He used to lead front-end development of several renowned fintech companies in China.

#### **Liting Zhu** 
Blockchain developer

BS in Mathematics, MS in Computer Science, Proficient in P2P web development, C/C++, Python, Shell, he used to be core developer at Vobile Info Tech Co., Ltd.

#### **Jiahua Tu** 
Blockchain developer

Jiahua used to be cybersecurity project manager and core developer at Hangzhou Hikvision Digital Technology Co., Ltd., yielding multiple upgrades of the security platform.

#### **Lei Xu** 
Blockchain developer

Lei is a full stack engineer, who proficient in PHP, Node.js, Python. He experienced in cross end developing and data visualization product developing. Lei used to work as a core developer at ZhejiangDailyMedia and tops001.com.

#### **Jun Yao** 
Blockchain developer

As a JAVA engineer, Jun is used to working at treefinance.com as a core developer, he is proficient in data collection, data mining, and data analysis.

#### **Dongming Shen**
Blockchain developer

Dongming used to work at ddyc.com as a core developer, he is an expert in App development for Android OS.

#### **Diwu Ye** 
Blockchain developer

Diwu is a backend engineer, he has abundant experience for data modeling, he developed data collection service with component-based approach.


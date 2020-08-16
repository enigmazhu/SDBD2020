# Workshop Program Overview


<img src="programoverview.png">


# Keynote Talks

## Keynote I: Federated Learning Systems: A New Holy Grail for System Research in Data Privacy and Protection?

### Prof. Bingsheng He

Associate Professor,
National University of Singapore 

<img src="bingsheng.png" width="150">

### Abstract

Federated learning has been a hot research area in enabling the collaborative training of machine learning models among different organizations under the privacy restrictions. As researchers try to support more machine learning models with different privacy-preserving approaches, there is a requirement in developing systems and infrastructures to ease the development of various federated learning algorithms. Just like deep learning systems such as Caffe, PyTorch, and Tensorflow that boost the development of deep learning algorithms, federated learning systems are equivalently important, and face challenges from various issues such as unpractical system assumptions, scalability and efficiency. Inspired by federated systems in other fields such as databases and cloud computing, we study the system design requirements for federated learning systems. We find that two important features for federated systems in other fields, i.e., heterogeneity and autonomy, are rarely considered in the existing federated learning systems. In this talk, we will take a systematic comparison among the existing federated learning systems and present our research progress and future system research opportunities and directions.

More details about our research can be found at [http://www.comp.nus.edu.sg/~hebs/](http://www.comp.nus.edu.sg/~hebs/) and related survey [https://arxiv.org/abs/1907.09693](https://arxiv.org/abs/1907.09693). 


### Speaker Bio

Dr. Bingsheng He is currently an Associate Professor and Vice-Dean (Research) at School of Computing, National University of Singapore. Before that, he was a faculty member in Nanyang Technological University, Singapore (2010-2016), and held a research position in the System Research group of Microsoft Research Asia (2008-2010), where his major research was building high performance cloud computing systems for Microsoft. He got the Bachelor degree in Shanghai Jiao Tong University (1999-2003), and the Ph.D. degree in Hong Kong University of Science & Technology (2003-2008). His current research interests include cloud computing, database systems and high performance computing. His papers are published in prestigious international journals (such as ACM TODS and IEEE TKDE/TPDS/TC) and proceedings (such as ACM SIGMOD, VLDB/PVLDB, ACM/IEEE SuperComputing, ACM HPDC, and ACM SoCC). He has been awarded with the IBM Ph.D. fellowship (2007-2008) and with NVIDIA Academic Partnership (2010-2011). Since 2010, he has (co-)chaired a number of international conferences and workshops, including IEEE CloudCom 2014/2015, BigData Congress 2018 and ICDCS 2020. He has served in editor board of international journals, including IEEE Transactions on Cloud Computing (IEEE TCC), IEEE Transactions on Parallel and Distributed Systems (IEEE TPDS), IEEE Transactions on Knowledge and Data Engineering (TKDE), Springer Journal of Distributed and Parallel Databases (DAPD) and ACM Computing Surveys (CSUR). He has got editorial excellence awards for his service in IEEE TCC and IEEE TPDS in 2019. 


## Keynote II: Federated Learning Systems: A New Holy Grail for System Research in Data Privacy and Protection?

### Dr. Jiaping Wang (王嘉平)

CEO, Moqun Computing (墨群计算)

Former Lead Researcher, Microsoft Research 

<img src="jiaping.png" width="150">

### Abstract

Blockchain systems introduced a new computing paradigm that no computing system achieved before, to establish a computing process avoids coupling with particular hardware deployment and thus prevents being controlled by the hardware owner or the creator of the system. This ensures equal roles for all participants in a distributed system. Cryptocurrency (e.g. Bitcoin) fully leverages the democratizing nature of the blockchain system to achieve the world-wide trust without endorsement from any authority. Such capability can be employed for broader applications in human society for finance, governance, collaboration and social interactions. 
Scalability is the top technical challenge that blockchain systems are encountered, which must be solved before adopting in sectors with much higher complexity and larger scale beyond cryptocurrency. We proposed parallel architecture to linearly scale out the blockchains sytem to match with the production needs. It is particular challenge to parallelize the blockchain system without weakening the democratizing nature and security. The talk will introduce the architecture that we have done and published on NSDI 2019, and follow up works regarding the programmability and production on top of it.

More details about our research can be found at [https://www.usenix.org/conference/nsdi19/presentation/wang-jiaping](https://www.usenix.org/conference/nsdi19/presentation/wang-jiaping)


### Speaker Bio

Dr. Jiaping Wang is currently the CEO and founder of Moqun computing Ltd focus on cutting edge technologies for distributed systems like blockchains and overlay networks.  Before that, he held a research position in the ATG of Microsoft Research and IG of Microsoft Research Asia, where his research interests cover high performance computing, distributed GPU farms for machine learning and computer graphics. His works are published in prestigious journals (ACM ToG, IEEE TVCG) and top conferences (ACM SIGGRAPH, USENIX/NSDI). He is inventor of tens of granted US patents based on his academia works. Dr. Jiaping Wang received Ph.D. degree in Institute of Computing Technology of the Chinese Academy of Sciences, advised by Dr. Harry Shum, former Executive Vice President of Microsoft. 


# Invited Talks

## Invited Talk I:  Decentralized Data Crowdsourcing: Fair, Private, and even Super Cheap

### Prof. Qiang Tang

Assistant professor, New Jersey Institute of Technology

<img src="qiangtang.png" width="150">

### Abstract

Many popular Apps and platforms deploy certain crowdsourcing mechanisms to facilitate the sharing economy. Over the years, concerns like fairness, data privacy have become more significant. In this talk, I will briefly survey our recent work on decentralized crowdsourcing facilitated by blockchain, and interesting findings we learnt along the way.


### Speaker Bio

Qiang Tang is currently an assistant professor at New Jersey Institute of Technology, and also a director of JD-NJIT-ISCAS joint blockchain lab. Before joining NJIT, he was a postdoc at Cornell IC3. His research interests lie broaderly on applied cryptography and blockchain technology, and most of his work published at flagship venues of cryptography, computer security, and distributed computing venues. He won a few awards including MIT TR 35, China 2019 and a Google Faculty Award.


## Invited Talk II:  Efficient MPC-enabled Privacy-Preserving Federated Learning

### Dr. Zengxiang Li

Former Scientist, Institute of High Performance Computing, A*STAR, SINGAPORE

<img src="zengxiang.png" width="150">

### Abstract

Countries across the globe have been pushing strict regulations on the protection of personal or private data collected. The traditional centralized machine learning method, where data is shared and consolidated, may not be feasible for many data-driven industry applications in light of such regulations. Federated Learning (FL) enables multiple participants to train a machine learning model collectively without directly exchanging data. However, recent studies have shown that there is still a possibility to exploit the shared models to extract personal or confidential data. In this talk, we will introduce Multi- Party Computation (MPC) as-a-service framework and how to leverage it for privacy-preserving model aggregation for FL in an efficient and scalable manner.  The MPC-enabled FL framework has been integrated in an IoT platform for smart manufacturing. According to the experiments using real-world datasets, federated learning could achieve comparable accuracy as traditional centralized machine learning method, and MPC-as-a service framework could reduce the communication cost and FL training time significantly.  



### Speaker Bio

Dr. Li Zengxiang is a former A*STAR Scientist at Institute of High Performance Computing (IHPC), Singapore. Dr. Li specializes in urban computing and transportation optimizations based on city-scale spatiotemporal data/graph analytics, machine learning and deep learning. Recently, his research group is focusing on secure data sharing and trusted collaborations for multiple industry domains, based on the convergence of cloud, data analytics, IoT, Blockchain, multi-party computation and federated learning technologies.


## Invited Talk III:  A Reliable Storage Partitioning for Permissioned Blockchain

### Prof. Cheqinq Jin

Professor, East China Normal University

<img src="cheqing.png" width="150">

### Abstract

The full-replication data storage mechanism, as commonly utilized in existing blockchains, is the barrier to the system’s scalability, since it retains a copy of entire blockchain at each node so that the overall storage consumption per block is O(n) with n participants. Yet another drawback is that this mechanism may limit the throughput in permissioned blockchain. Moreover, due to the existence of Byzantine nodes, existing partitioning methods, though widely adopted in distributed systems for decades, cannot suit for blockchain systems directly, so that it is critical to devise new storage mechanism for blockchain systems. We propose a novel storage engine, called BFT-Store, to enhance storage scalability by integrating erasure coding with Byzantine Fault Tolerance (BFT) consensus protocol. The first property of BFT-store is that the storage consumption per block can be reduced to O(1) for the first time, which enlarges overall storage capability when more nodes attend the blockchain. Second, we design an efficient online re-encoding protocol for storage scale-out and a hybrid replication scheme to enhance reading performance. Analysis in theory and extensive experimental results illustrate the scalability, availability and efficiency of BFT-Store via the implementation in an open-source permissioned blockchain Tendermint.

### Speaker Bio

Prof. Cheqing Jin is a professor and vice dean of the School of Data Science and Engineering, East China Normal University. He is a senior member of China Computer Federation Technical Committee on Databases. His research interests include blockchain, data stream management, location-based services, uncertain data management and so on.  He was the PI of several National Natural Science Foundations, and has co-authored 1 Monograph and more than 100 papers.


# Workshop Co-Chairs

- Feida Zhu (Singapore Management University)
- Jian Pei (Simon Fraser University)
- Zijiang James Yang,  (Western Michigan University )
- Xiaokui Xiao (National University of Singapore)


### Prof. Feida Zhu

Associate Professor, Singapore Management University

Founder, Symphony Protocol

<img src="feida.png" width="150">

### Bio

Prof. Feida Zhu is currently a tenured associate professor at Singapore Management University. His research interests include large-scale data mining and machine learning, block chain, text mining, graph/network mining and social network analysis, with emphasis on their application to business, financial and consumer innovation. 

Feida Zhu was the founding director of both the Pinnacle Lab for Analytics with China Ping An Insurance Group and DBS-SMU Life Analytics Lab, focusing on social data mining and analysis for finance industry. Prof. ZHU has been the Founder and Chief Scientist of Symphony Protocol, which is a next-generation blockchain-based protocol to empower a data-driven economy by democratized and personalized Intelligence with privacy by design. 

Prof. ZHU has published extensively at peer-reviewed top international venues, including ICDE, VLDB,  SIGMOD, KDD, WWW, JMLR, TODS, TKDE, etc. His work on large-scale frequent pattern mining has won the Best Student Paper Awards at 2007 IEEE International Conference on Data Engineering (ICDE’07) and 2007 Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD’07).  He also received the Best Paper Award at the 21th International Conference on Database Systems for Advanced Applications (DASFAA'16) and the Best Demo Paper Award at The 17th International Conference on Web-Age Information Management (WAIM'16).  He won the Early Career Award of PAKDD’19 and is the General Co-Chair of ICDM’18 and KDD’21. Prof. ZHU obtained his Ph.D. in Computer Science from the University of Illinois at Urbana-Champaign (UIUC) in 2009, supervised by Prof. Jiawei Han.



### Prof. Jian Pei

Professor, Simon Fraser University


<img src="jianpei.png" width="150">

### Bio

Jian Pei is currently a Professor in the School of Computing Science and an associate member of the Department of Statistics and Actuarial Science at Simon Fraser University, Canada. His general areas include data science, big data, data mining, and database systems. His expertise is on developing effective and efficient data analysis techniques for novel data intensive applications. He is recognized as a Fellow of the Royal Society of Canada (RSC), Academy of Science, a Fellow of ACM and a Fellow of IEEE.
 
Jian Pei is a productive and influential author in data mining, database systems, and information retrieval. Since 2000, he has published one textbook, two monographs and over 200 research papers in refereed journals and conferences, which have been cited over 94,000 times in literature, and over 36,000 times in the last 5 years. His H-index is 87. His research has generated remarkable impact substantially beyond academia. His algorithms have been adopted by industry in production and popular open source software suites. He is responsible for several commercial systems of unprecedentedly large scale. 

Jian Pei received many prestigious awards, including the 2017 ACM SIGKDD Innovation Award, the 2015 ACM SIGKDD Service Award, the 2014 IEEE ICDM Research Contributions Award, the British Columbia Innovation Council 2005 Young Innovator Award, an NSERC 2008 Discovery Accelerator Supplements Award (100 awards cross the whole country), an IBM Faculty Award (2006), a KDD Best Application Paper Award (2008), an IEEE ICDE Influential Paper Award (2018), a PAKDD Best Paper Award (2014), a PAKDD Most Influential Paper Award (2009), and an IEEE Outstanding Paper Award (2007). 

### Prof. Zijiang James Yang

Professor, Western Michigan University 


<img src="zijiang.png" width="150">

### Bio

Zijiang James Yang is a professor of Computer Science at Western Michigan University. His research is in the broad areas of software engineering and formal methods. The primary focus is to develop formal method based tools to support the debugging, analysis and verification of complex systems. He has published over seventy referred conference and journal papers. He is also an inventor of ten United States patents.

Dr. Yang received his Ph.D. under the supervision of Prof. Rajeev Alur from the University of Pennsylvania, M.S. under the supervision of Prof. Moshe Vardi from Rice University, and B.S. from the University of Science and Technology of China, all in computer science. He was a recipient of the 2018 ACM SIGSOFT Distinguished Paper Award, 2015 CEAS outstanding researcher award, 2010 PADTAD best paper award, 2008 ACM TODAES best paper award and the 2008 CEAS outstanding new researcher award. He was a visiting professor at EECS, University of Michigan from 2009 to 2013. He is the general chair of the 12th  IEEE Conference on Software Testing, Validation and Verification (ICST).

### Prof. Xiaockui Xiao

Associate Professor, National University of Singapore


<img src="xiaokui.png" width="150">

### Bio

Xiaokui Xiao is an associate professor at the School of Computing (SoC), National University of Singapore (NUS). Prior to joining NUS, he was an associate professor at the School of Computer Science and Engineering, Nanyang Technological University. He obtained a PhD in Computer Science from the Chinese University of Hong Kong in 2008, and did a postdoctoral stint at the Department of Computer Science, Cornell University.

Xiaokui’s research focuses on data management and analytics, especially on algorithms for large data, data privacy, and data mining. He has published extensively in the leading data management conference and journals, and is serving as associate editors for the International Journal on Very Large Data Bases (VLDBJ) and the IEEE Transactions on Knowledge and Data Engineering (TKDE). Two of his papers were invited to the TKDE special issues on “The Best Papers of ICDE 2010” and “The Best Papers of ICDE 2015”, respectively.


# Industrial & Media Partners

<img src="suanlizhiku.png">

# Workshop Overview

With the advent of Bitcoin, a cryptographically-enabled peer-to-peer digital payment system, blockchain together with a whole package of distributed ledger technologies, which serve as the underlying foundation of all the crypto-currencies, have been gaining attention from both academia and industry in the last decade. Furthermore, the recent years have witnessed tremendous momentum in the development of blockchain and distributed ledger technologies， largely due to the impressive rise in the market capital of these digital tokens.  More and more industries, from banking and insurance, to supply chain and e-commerce, are quickly realizing the great potential in blockchain technology in efficiency boost, process automation and secure data sharing across otherwise isolated data silos.  

Blockchains are distributed ledgers that enable parties who do not fully trust one another to maintain a set of global states. The parties agree on the existence, values, and histories of the states. Most attention and research so far have been devoted to the underlying technologies from the database, distributed architecture, cryptography and consensus aspects, primarily because the priority as yet has been attached to the feasibility, stability and scalability of the platforms.  Yet, as it has been gaining increasing awareness that the greatest potential of blockchain and distributed technologies lies in unleashing a whole new economy empowered by the capabilities to convert a rich class of emerging class of virtual assets into attributable value, including a long list of promising new concepts such as influence, social capital, swarm intelligence, personal data and credit.  How to bring the greatest value out of the various types of new “on-chain” data in the blockchain setting becomes an urgent task.  Consequently, it is both important and challenging to explore a wealth of interesting new research topics in this new setting that fall broadly under the scope of KDD yet with the unique requirement to achieve the optimal balance among data utility, security and privacy.  
 
The workshop aims to provide a venue at SIGKDD for developers, practitioners, and researchers from different background to discuss how the unique properties of blockchain and distributed ledger that benefit current and future applications, particular from the perspective of integrating data mining, analysis and intelligence into the underlying framework.   To best integrate with KDD community and scope, we have proposed the special theme of “Smart Data” to highlight the mission and focus of this workshop.  Due to COVID-19 situation, this year's workshop will be held online on August 24, 20120 in conjunction with the ACM SIGKDD 2020.

# Call For Papers

The Second International Workshop on Smart Data for Blockchain and Distributed Ledger (SDBD’20) aims to bring together practitioners and researchers with a specific focus on the emerging trends and industry needs associated with the AI, data mining, data governance, data privacy and other topics under the “Smart Data” framework. Both theoretical and experimental submissions are encouraged. Topics of interest include but are not limited to:



- Data mining in distributed ledger setting
- Privacy-preserving AI and data mining in blockchain and distributed setting
- Secure data sharing through blockchain
- Applications and use cases of blockchain
- Algorithm design, complexity analysis, implementation for blockchain
- Benchmarking and performance study
- Blockchain consensus protocols
- Blockchain protocol analysis and security
- Data provenance
- Distributed ledgers
- Data analytics on blockchain
- Data governance
- Data stores for blockchain
- Execution engine
- Systems: Hyperledger. Corda, Ethereum, EOS, etc
- Secure smart contracts
- Throughput and scalability

# Submission Guidelines

We invite submissions for original research papers both theory and application-oriented as well as submissions from the research track and applied data science track of the main conference. We encourage the participants to submit papers on novel datasets and release them to advance the field. Papers must be submitted in PDF according to the [ACM Proceedings Template](https://www.acm.org/publications/proceedings-template) in a single-blind format (including author names and affiliations). We welcome both long papers (maximum length of 9 pages) and short papers (maximum length of 5 pages). The accepted papers will be published on the workshop’s website, and will not be considered archival for resubmission purposes. Please submit your papers at the [EasyChair submission link](https://easychair.org/account/signin_timeout?l=0Gqswiuc95cQEulHDdOfPc#).
 


## Key Dates

All deadlines are 11:59 PM Pacific Standard Time

- Workshop paper submissions:  June 25, 2020

- Workshop paper notifications: June 30, 2020

- Workshop date: August 24, 2020





Please email fdzhu@smu.edu.sg  for any questions.



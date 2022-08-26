---
title: "Security Analysis of Smart Contracts"
excerpt: "A smart contract is a self-executing contract with the terms of the agreement between buyer and seller being directly written into lines of code. The code is stored on a blockchain across a distributed, decentralized blockchain network. The code controls the execution, and transactions are trackable and irreversible. Because the smart contract is irreversible, we must audit the written program to ensure it is secure. <br/><img src='/images/Smart-Contract-Security-2.jpg'>"
collection: portfolio
---
# Table of Contents
- [Blogs](#blogs)
- [Papers](#papers)
- [Books](#books)
- [Trainings](#Trainings)
- [Tools](#tools)
  * [Visualization](#Visualization)
  * [Verification](#Verification)
  * [Linters](#Linters)
  * [BugHunting](#BugHunting)
  * [Reverse Engineering](#Reverse_Engineering)

- [Awesome-Smart-Contract-Security !awesome](#awesome-smart-contract-security-)
- [Table of Contents](#table-of-contents)
- [Blogs](#blogs)
- [Papers](#papers)
- [Books](#books)
    - [Security Journal list](#security-journal-list)
- [Trainings](#trainings)
- [Tools](#tools)
    - [Visualization](#visualization)
    - [Verification](#verification)
    - [Linters](#linters)
    - [BugHunting](#bughunting)
    - [Reverse Engineering](#reverse-engineering)
- [Labs](#labs)
- [Capture the Flag and Wargames](#capture-the-flag-and-wargames)
- [Talks](#talks)
- [Misc](#misc)
- [Podcasts](#podcasts)
- [Cheat Sheets](#cheat-sheets)
- [Checklists](#checklists)
- [Bug Bounty & Writeups](#bug-bounty--writeups)
- [Bug Bounty Platforms & Project](#bug-bounty-platforms--project)
# Blogs

* [Reversing Ethereum Smart Contracts](https://arvanaghi.com/blog/reversing-ethereum-smart-contracts/)
* [Emin Gün Sirer, professor in Cornell Tech’s IC3 lab focused on blockchain security.](http://hackingdistributed.com/) 
* [ Phil Daian, grad student behind KEVM, Hydra, and other Ethereum academic projects](https://pdaian.com/blog/) 
* [Cybersecurity R&D firm with a blockchain security practice](https://blog.trailofbits.com/) 
* [ Martin Swende, programmer and appsec consultant](http://swende.se/) 
* [Company blog about security issues and practices within blockchain ecosystem](https://blog.smartdec.net/) 
* [Solidity Security: Comprehensive list of known attack vectors](https://blog.sigmaprime.io/solidity-security.html)
* [Use cryptography in mobile apps the right way](https://blog.oversecured.com/Use-cryptography-in-mobile-apps-the-right-way/)
* [Subzero is an HSM-backed method for cold storage of Bitcoin developed by Square](https://medium.com/square-corner-blog/open-sourcing-subzero-ee9e3e071827) 
* [Contract upgrade anti-patterns](https://blog.trailofbits.com/2018/09/05/contract-upgrade-anti-patterns/)
* [How the winner got Fomo3D prize — A Detailed Explanation](https://medium.com/coinmonks/how-the-winner-got-fomo3d-prize-a-detailed-explanation-b30a69b7813f)
* [How to debug Solidity Smart Contracts with Tenderly and Truffle](https://medium.com/tenderly/how-to-debug-solidity-smart-contracts-with-tenderly-and-truffle-da995cfe098f)
* [Lashing out at a Spank Channel](https://medium.com/coinmonks/lashing-out-at-a-spank-channel-2b42b23f0dc6)
* [Malicious GasToken Minting](https://medium.com/level-k/public-disclosure-malicious-gastoken-minting-236b2f8ace38)
* [Missing return value bug in ERC20 tokens](https://medium.com/coinmonks/missing-return-value-bug-at-least-130-tokens-affected-d67bf08521ca)
* [Not A Fair Game – Fairness Analysis of Dice2win](http://blogs.360.cn/post/Fairness_Analysis_of_Dice2win_EN.html)
* [Initial Formal Verification of Ethereum Casper Protocol](https://runtimeverification.com/blog/runtime-verification-completes-formal-verification-of-ethereum-casper-protocol/)
* [Security considerations for Shamir's secret sharing](https://ethresear.ch/t/security-considerations-for-shamirs-secret-sharing/4294)
* [SmartDec smart contract audit beginner's guide](https://blog.smartdec.net/smartdec-smart-contract-audit-beginners-guide-d04cc7f1c571)
* [The Anatomy of a Block Stuffing Attack](https://osolmaz.com/2018/10/18/anatomy-block-stuffing/)
* [The phenomenon of smart contract honeypots](https://medium.com/@gerhard.wagner/the-phenomena-of-smart-contract-honeypots-755c1f943f7b)
* [Use our suite of Ethereum security tools](https://blog.trailofbits.com/2018/03/23/use-our-suite-of-ethereum-security-tools/)
* [Vertcoin (VTC) was successfully 51% attacked](https://medium.com/coinmonks/vertcoin-vtc-is-currently-being-51-attacked-53ab633c08a4)


# Papers
* [Security Strengths and Weaknesses of Blockchain Smart Contract System: A Survey](https://www.researchgate.net/profile/Malaw-Ndiaye/publication/360624196_Security_Strengths_and_Weaknesses_of_Blockchain_Smart_Contract_System_A_Survey/links/62824c3590841d5155d7dbb7/Security-Strengths-and-Weaknesses-of-Blockchain-Smart-Contract-System-A-Survey.pdf)
* [Ethereum smart contract security research: survey and future research opportunities](https://link.springer.com/article/10.1007/s11704-020-9284-9)
* [Smart contract security: A software lifecycle perspective](https://ieeexplore.ieee.org/iel7/6287639/8600701/08864988.pdf)
* [Ethainter: a smart contract security analyzer for composite vulnerabilities](https://dl.acm.org/doi/abs/10.1145/3385412.3385990)
* [NeuCheck: A more practical Ethereum smart contract security analysis tool](https://onlinelibrary.wiley.com/doi/abs/10.1002/spe.2745)
* [Smart contract: Attacks and protections](https://ieeexplore.ieee.org/abstract/document/8976179/)
* [Smart contract vulnerability analysis and security audite](https://ieeexplore.ieee.org/abstract/document/9143290/)
* [Security analysis methods on ethereum smart contract vulnerabilities: a survey](https://arxiv.org/pdf/1908.08605)
* [Smart contract privacy protection using AI in cyber-physical systems: tools, techniques and challenges](https://ieeexplore.ieee.org/iel7/6287639/8948470/08976143.pdf)
* [LedgerHedger: Gas Reservation for Smart-Contract Security](https://eprint.iacr.org/2022/056.pdf)
* [Combining graph neural networks with expert knowledge for smart contract vulnerability detection](https://arxiv.org/pdf/2107.11598)
* [Security checklists for Ethereum smart contract development: patterns and best practices](https://arxiv.org/pdf/2008.04761.pdf)
* [Exploring Security Practices of Smart Contract Developers](https://arxiv.org/pdf/2204.11193)


# Books

 * [Fundamentals of Smart Contract Security](https://www.amazon.com/Fundamentals-Smart-Contract-Security-Richard/dp/194944936X)
 * [Hands-On Smart Contract Development with Solidity and Ethereum ](https://www.oreilly.com/library/view/hands-on-smart-contract/9781492045250/ch12.html)
 * [Mastering Ethereum](https://www.bookstack.cn/read/ethereumbook-en/a09dd11523647de0.md)

### Security Journal list

* IEEE Transactions on Information Forensics and Security [[web]](http://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)
* Computer & Security[[web]](http://www.elsevier.com/wps/find/journaldescription.cws_home/405877/description#description)
* IET Information Security[[web]](http://www.ietdl.org/IET-IFS)
* ACM Transactions on Information and System Security[[web]](http://tissec.acm.org/)
* International Journal of Information Security[[web]](http://www.springerlink.com/content/107927/)
* Security and Communication Networks[[web]](http://www.wiley.com/bw/journal.asp?ref=1939-0114)
* IEEE Security & Privacy[[web]](	http://www.computer.org/portal/web/security/home)
* IEEE Transactions on Dependable and Secure Computing [[web]](http://www.computer.org/tdsc/)
* Security and Communication Networks[[web]](http://onlinelibrary.wiley.com/journal/10.1002/(ISSN)1939-0122)
* Computer Fraud & Security[[web]](http://www.elsevierscitech.com/nl/cfs/home.asp )

# Trainings

* [SEC554: Blockchain and Smart Contract Security](https://www.sans.org/cyber-security-courses/blockchain-smart-contract-security/)
* [SecDim](https://secdim.com)
* [Ethereum Smart Contract Security](https://academy.moralis.io/courses/ethereum-smart-contract-security)
* [Solidity, Blockchain, and Smart Contract Course ](https://www.youtube.com/watch?v=M576WGiDBdQ)
* [Smart Contract Security 101](https://pro.eattheblocks.com/p/smart-contract-security-101)
* [Certified Blockchain Security Professional (CBSP)](https://blockchaintrainingalliance.com/products/cbsp)
* [Learn blockchain security](https://www.infosecinstitute.com/skills/learning-paths/blockchain-security/)

# Tools
### Visualization

* [ethereum-graph-debugger](https://github.com/fergarrui/ethereum-graph-debugger) - A graphical EVM debugger. Displays the entire program control flow graph.
* [Slither](https://github.com/trailofbits/slither) - Slither can map method visibility and modifiers, state variables that are read and written, calls, and can print the inheritance graph of a smart contract
* [Solgraph](https://github.com/raineorshine/solgraph) - Generates DOT graphs with function control flow of a solidity contract
* [Surya](https://github.com/ConsenSys/surya) - Generates various visual outputs of function call graphs
* [sol-function-profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler

### Verification 

* [KEVM](https://github.com/kframework/evm-semantics) - K Semantics of the Ethereum Virtual Machine (EVM)
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for EVM

### Linters

* [Remix](https://remix.ethereum.org/) - Browser-based Solidity IDE with linting features
* [SmarrtCheck](https://tool.smartdec.net/) - A linter for Solidity and Vyper that checks code for security issues and bad practices.
* [Solhint](https://github.com/protofire/solhint) - Linter for both security and style-guide validations. It strictly adheres to the [Solidity Style Guide](https://solidity.readthedocs.io/en/latest/style-guide.html).
* [Solium](https://github.com/duaraghav8/Solium) - Linter for both security and style-guide validations. Does not strictly adhere to the Solidity Style Guide.
### BugHunting

* [Echidna](https://github.com/trailofbits/echidna) - Fuzzer for Ethereum smart contracts. Uses property testing to generate malicious inputs that break smart contracts.
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for Ethereum smart contracts that includes detectors for common security flaws
* [Mythril OSS](https://github.com/ConsenSys/mythril/) - Open-source security analysis tool for Ethereum smart contracts built around detector modules
* [Securify v2.0](https://github.com/eth-sri/securify2) - Static analysis tool from ChainSecurity
* [Slither](https://github.com/trailofbits/slither) - Static analysis framework, written in Python, with detectors for many common Solidity issues
* [Octopus](https://github.com/pventuzelo/octopus) - : Blockchain Smart Contracts (BTC/ETH/NEO/EOS)
### Reverse Engineering

* [abi-decompiler](https://github.com/beched/abi-decompiler) - EVM reverse engineering helper utility
* [ethereum-dasm](https://github.com/tintinweb/ethereum-dasm) - EVM disassembler with static and dynamic analysis abilities, including function signature lookup
* [Ethersplay](https://github.com/trailofbits/ethersplay) - Visual disassembler for EVM bytecode built on Binary Ninja
* [evmlab](https://github.com/ethereum/evmlab) - Utilities for interacting with the Ethereum virtual machine
* [IDA-EVM](https://github.com/trailofbits/ida-evm) - IDA plugin to view EVM instructions
* [Panoramix](http://eveem.org/about)
* [pyevmasm](https://github.com/trailofbits/pyevmasm) - EVM assembler and disassembler with a CLI and a Python API
* [Rattle](https://github.com/trailofbits/rattle) - EVM binary static analysis framework. Produces SSA representations of EVM code.
# Labs

* [Smart Contract Labs](https://smartcontractlabs.ee/)  
* [ChainLink Lab](https://chainlinklabs.com/)
* [A lab that focuses on smart contract security](https://github.com/JonZeolla/lab-SmartContractSecurity)

# Capture the Flag and Wargames

* [Capture the Ether](https://capturetheether.com/)  
* [The Ethernaut](https://ethernaut.openzeppelin.com/)  
* [Etherhack](https://etherhack.positive.com/)  
* [Security Innovation Blockchain CTF](https://blockchain-ctf.securityinnovation.com/)  
* [Ciphershastra CTF](https://ciphershastra.com/)  
* [Defi Hack](https://www.defihack.xyz/)  
* [Gacha Lab (BSC Testnet)](https://gachalab.inspex.co/)
# Talks
  

| Title | Conference | Year |
| --- | --- | --- |
|[6th Workshop on Trusted Smart Contracts](https://fc22.ifca.ai/wtsc/) | WTSC 2022 | 2022| 
|[Smart Contract Security: a Practitioners’ Perspective](https://conf.researchr.org/details/icse-2021/icse-2021-papers/12/Smart-Contract-Security-a-Practitioners-Perspective) | ICSE 2021 |2021|
| [Predicting Random Numbers in Ethereum Smart Contracts](https://schd.ws/hosted_files/appseccalifornia2018/00/AppSecCali%202018%20-%20Predicting%20Random%20Numbers%20in%20Ethereum%20Smart%20Contracts.pdf) | OWASP AppSec | 2018 |
| [Blockchain Autopsies - Analyzing Smart Contract Deaths](https://github.com/trailofbits/publications/tree/master/presentations/Blockchain%20Autopsies%20-%20Analyzing%20Smart%20Contract%20Deaths) | Blackhat USA | 2018 |
| [Rattle - an EVM binary analysis framework](https://www.trailofbits.com/presentations/rattle/) | reCON | 2018 |
| [Blackhat Ethereum](https://github.com/trailofbits/publications/blob/master/presentations/Blackhat%20Ethereum) | CanSecWest | 2018 |
| [Smashing Ethereum Smart Contracts for Fun and Profit](https://github.com/b-mueller/smashing-smart-contracts) | HITB Amsterdam | 2018 |
| [Automatic Bug Finding for the Blockchain](https://github.com/trailofbits/publications/blob/master/presentations/Automatic%20bugfinding%20for%20the%20blockchain) | EkoParty | 2017 |
# Misc

* [Hacking Smart Contracts: Beginners Guide](https://learn.block6.tech/hacking-smart-contracts-beginners-guide-9c84e9de7194)
* [Security Pitfalls & Best Practices 101](https://secureum.substack.com/p/security-pitfalls-and-best-practices-101?s=r)
* [A guide to smart contract security best practices](https://github.com/ConsenSys/smart-contract-best-practices)    
* [Decentralized Application Security Project (or DASP) Top 10](https://www.dasp.co/)
* [Solidity Security Considerations](https://docs.soliditylang.org/en/latest/security-considerations.html)
* [A Collection of Vulnerabilities in ERC20 Smart Contracts](https://github.com/sec-bit/awesome-buggy-erc20-tokens)
* [Examples of Solidity security issues](https://github.com/crytic/not-so-smart-contracts)
* [A guide to smart contract security best practices](https://github.com/ConsenSys/smart-contract-best-practices)
* [A guide to EOS smart contract security best practices](https://github.com/slowmist/eos-smart-contract-security-best-practices)
# Podcasts

* [CoinSec Podcast](https://coinsecpodcast.com/)
* [The Smartest Contract](http://www.thesmartestcontract.com/)
* [Zero Knowledge](http://www.zeroknowledge.fm/)

# Cheat Sheets 
* [Solidity Cheat Sheet](https://intellipaat.com/blog/tutorial/blockchain-tutorial/solidity-cheat-sheet/)
* [Solidity Cheatsheet and Best practices](https://github.com/manojpramesh/solidity-cheatsheet)
* [Ethereum Cheat Sheet](https://intellipaat.com/blog/tutorial/blockchain-tutorial/ethereum-cheat-sheet/)
* [The Ultimate Blockchain Cheat Sheet](https://101blockchains.com/blockchain-cheat-sheet/)
# Checklists
* [Solidity Auditing Checklistt](https://github.com/cryptofinlabs/audit-checklist)
* [SMART CONTRACT SECURITY CHECKLIST](https://ethereum.org/en/developers/tutorials/secure-development-workflow/)
* [Smart Contract Security Audit: Intro & Top 5 Best Practices](https://www.getastra.com/blog/security-audit/smart-contract-security/)
* [Smart Contract Security Verification Standard](https://securing.github.io/SCSVS/)
* [Security checklists for Ethereum smart contract development](https://arxiv.org/pdf/2008.04761)

# Bug Bounty & Writeups

* [Hands on the Ethernaut CTF](https://blog.trailofbits.com/2017/11/06/hands-on-the-ethernaut-ctf/) - Writeups for various Ethernaut CTF challenge contracts.
* [Ethernaut - Naught Coin (ERC20) Exploitation](https://medium.com/coinmonks/ethernaut-naught-coin-erc20-exploitation-218c86bb953b) - Writeup for a vulnerable ERC20 from the Ethernaut CTF.
* [EtherHack CTF Writeup](https://blog.positive.com/phdays-8-etherhack-contest-writeup-794523f01248) - Writeup for EtherHack CTF challenges.
* [PolySwarm Smart Contract Hacking Challenge Writeup](https://raz0r.name/writeups/polyswarm-smart-contract-hacking-challenge-writeup/) - Demonstrates advanced use of Manticore

* [Write up of Metaplex Vuln 2022](https://github.com/Bonfida/metaplex-vulnerability-012022)
* [Smart Contract security audit reports](https://github.com/TechRate/Smart-Contract-Audits)
# Bug Bounty Platforms & Project
* [Immunefi](https://immunefi.com/explore/)
* [hackenproof](https://hackenproof.com/)
* [ETHEREUM Bounty Program](https://bounty.ethereum.org/#bounty-scope)
* [Etherscan Bugbounty Program](https://etherscan.io/bugbounty)
* [Parity Bug Bounty Program](https://www.parity.io/bug-bounty/)
* [Gitcoint project](https://gitcoin.co/explorer?network=mainnet&idx_status=open&applicants=ALL&order_by=-web3_created)
* [Code Arena Bugbounty project](https://code4rena.com/)
* [Smartlink Dapps](https://www.smartlink.so/bug-bounty/)
\[1\]Rachit Agarwal, Tanmay Thapliyal, and Sandeep Kumar Shukla. 2022. Vulnerability and Transaction Behavior Based Detection of Malicious Smart Contracts. In _Cyberspace Safety and Security_ (Lecture Notes in Computer Science), Springer International Publishing, Cham, 79–96. DOI:https://doi.org/10.1007/978-3-030-94029-4\_6

\[2\]Elvira Albert, Jesús Correas, Pablo Gordillo, Guillermo Román-Díez, and Albert Rubio. 2019. SAFEVM: a safety verifier for Ethereum smart contracts. In _Proceedings of the 28th ACM SIGSOFT International Symposium on Software Testing and Analysis_. Association for Computing Machinery, New York, NY, USA, 386–389. Retrieved February 26, 2022 from https://doi.org/10.1145/3293882.3338999

\[3\]Monika di Angelo and Gernot Salzer. 2019. A Survey of Tools for Analyzing Ethereum Smart Contracts. In _2019 IEEE International Conference on Decentralized Applications and Infrastructures (DAPPCON)_, 69–78. DOI:https://doi.org/10.1109/DAPPCON.2019.00018

\[4\]Nami Ashizawa, Naoto Yanai, Jason Paul Cruz, and Shingo Okamura. 2021. Eth2Vec: Learning Contract-Wide Code Representations for Vulnerability Detection on Ethereum Smart Contracts. (January 2021). Retrieved February 28, 2022 from https://arxiv.org/abs/2101.02377v2

\[5\]Rabia Musheer Aziz, Mohammed Farhan Baluch, Sarthak Patel, and Abdul Hamid Ganie. 2022. LGBM: a machine learning approach for Ethereum fraud detection. _Int. j. inf. tecnol._ (January 2022). DOI:https://doi.org/10.1007/s41870-022-00864-6

\[6\]Chaïmaa Benabbou and Önder Gürcan. 2021. A Survey of Verification, Validation and Testing Solutions for Smart Contracts. In _2021 Third International Conference on Blockchain Computing and Applications (BCCA)_, 57–64. DOI:https://doi.org/10.1109/BCCA53669.2021.9657040

\[7\]Venkata Siva Vijayendra Bhamidipati, Michael Chan, Derek Chamorro, Arpit Jain, and Ashok Murthy. 2019. Adaptive Security for Smart Contracts using High Granularity Metrics. In _Proceedings of the 3rd International Conference on Vision, Image and Signal Processing_. Association for Computing Machinery, New York, NY, USA, 1–6. Retrieved February 26, 2022 from https://doi.org/10.1145/3387168.3387214

\[8\]Lexi Brent, Anton Jurisevic, Michael Kong, Eric Liu, Francois Gauthier, Vincent Gramoli, Ralph Holz, and Bernhard Scholz. 2018. Vandal: A Scalable Security Analysis Framework for Smart Contracts. _arXiv:1809.03981 \[cs\]_ (September 2018). Retrieved February 28, 2022 from http://arxiv.org/abs/1809.03981

\[9\]Weimin Chen, Xinran Li, Yuting Sui, Ningyu He, Haoyu Wang, Lei Wu, and Xiapu Luo. 2021. SADPonzi: Detecting and Characterizing Ponzi Schemes in Ethereum Smart Contracts. _Proc. ACM Meas. Anal. Comput. Syst._ 5, 2 (June 2021), 26:1-26:30. DOI:https://doi.org/10.1145/3460093

\[10\]Yuchiro Chinen, Naoto Yanai, Jason Paul Cruz, and Shingo Okamura. 2020. RA: Hunting for Re-Entrancy Attacks in Ethereum Smart Contracts via Static Analysis. In _2020 IEEE International Conference on Blockchain (Blockchain)_, 327–336. DOI:https://doi.org/10.1109/Blockchain50366.2020.00048

\[11\]Mojtaba Eshghie, Cyrille Artho, and Dilian Gurov. 2021. Dynamic Vulnerability Detection on Smart Contracts Using Machine Learning. In _Evaluation and Assessment in Software Engineering_ (EASE 2021), Association for Computing Machinery, New York, NY, USA, 305–312. DOI:https://doi.org/10.1145/3463274.3463348

\[12\]Josselin Feist, Gustavo Grieco, and Alex Groce. 2019. Slither: A Static Analysis Framework For Smart Contracts. _2019 IEEE/ACM 2nd International Workshop on Emerging Trends in Software Engineering for Blockchain (WETSEB)_ (May 2019), 8–15. DOI:https://doi.org/10.1109/WETSEB.2019.00008

\[13\]João F. Ferreira, Pedro Cruz, Thomas Durieux, and Rui Abreu. 2020. SmartBugs: A Framework to Analyze Solidity Smart Contracts. In _2020 35th IEEE/ACM International Conference on Automated Software Engineering (ASE)_, 1349–1352.

\[14\]Christof Ferreira Torres, Mathis Baden, Robert Norvill, Beltran Borja Fiz Pontiveros, Hugo Jonker, and Sjouke Mauw. 2020. &#xc6;GIS: Shielding Vulnerable Smart Contracts Against Attacks. In _Proceedings of the 15th ACM Asia Conference on Computer and Communications Security_ (ASIA CCS ’20), Association for Computing Machinery, New York, NY, USA, 584–597. DOI:https://doi.org/10.1145/3320269.3384756

\[15\]Bo Gao, Ling Shi, Jiaying Li, Jialiang Chang, Jun Sun, and Zijiang Yang. 2021. sVerify: Verifying Smart Contracts Through Lazy Annotation and Learning. In _Leveraging Applications of Formal Methods, Verification and Validation_ (Lecture Notes in Computer Science), Springer International Publishing, Cham, 453–469. DOI:https://doi.org/10.1007/978-3-030-89159-6\_28

\[16\]Zhipeng Gao. 2020. When deep learning meets smart contracts. In _Proceedings of the 35th IEEE/ACM International Conference on Automated Software Engineering_. Association for Computing Machinery, New York, NY, USA, 1400–1402. Retrieved February 26, 2022 from https://doi.org/10.1145/3324884.3418918

\[17\]Zhipeng Gao, Vinoj Jayasundara, LingXiao Jiang, Xin Xia, David Lo, and John Grundy. 2019. SmartEmbed: A Tool for Clone and Bug Detection in Smart Contracts through Structural Code Embedding. In _2019 IEEE International Conference on Software Maintenance and Evolution (ICSME)_, 394–397. DOI:https://doi.org/10.1109/ICSME.2019.00067

\[18\]Juan Guarnizo, Bithin Alangot, and Pawel Szalachowski. 2020. SmartWitness: A Proactive Software Transparency System using Smart Contracts. In _Proceedings of the 2nd ACM International Symposium on Blockchain and Secure Critical Infrastructure_ (BSCI ’20), Association for Computing Machinery, New York, NY, USA, 117–129. DOI:https://doi.org/10.1145/3384943.3409428

\[19\]Jingxuan He, Mislav Balunović, Nodar Ambroladze, Petar Tsankov, and Martin Vechev. 2019. Learning to Fuzz from Symbolic Execution with Application to Smart Contracts. In _Proceedings of the 2019 ACM SIGSAC Conference on Computer and Communications Security_ (CCS ’19), Association for Computing Machinery, New York, NY, USA, 531–548. DOI:https://doi.org/10.1145/3319535.3363230

\[20\]Ningyu He, Ruiyi Zhang, Lei Wu, Haoyu Wang, Xiapu Luo, Yao Guo, Ting Yu, and Xuxian Jiang. 2020. Security Analysis of EOSIO Smart Contracts. _arXiv:2003.06568 \[cs\]_ (July 2020). Retrieved February 28, 2022 from http://arxiv.org/abs/2003.06568

\[21\]Tharaka Mawanane Hewa, Yining Hu, Madhusanka Liyanage, Salil S. Kanhare, and Mika Ylianttila. 2021. Survey on Blockchain-Based Smart Contracts: Technical Aspects and Future Research. _IEEE Access_ 9, (2021), 87643–87662. DOI:https://doi.org/10.1109/ACCESS.2021.3068178

\[22\]Huiwen Hu and Yuedong Xu. 2021. SCSGuard: Deep Scam Detection for Ethereum Smart Contracts. _arXiv:2105.10426 \[cs\]_ (May 2021). Retrieved February 28, 2022 from http://arxiv.org/abs/2105.10426

\[23\]Jianjun Huang, Songming Han, Wei You, Wenchang Shi, Bin Liang, Jingzheng Wu, and Yanjun Wu. 2021. Hunting Vulnerable Smart Contracts via Graph Embedding Based Bytecode Matching. _IEEE Transactions on Information Forensics and Security_ 16, (2021), 2144–2156. DOI:https://doi.org/10.1109/TIFS.2021.3050051

\[24\]Wanqing Jie, Arthur Sandor Voundi Koe, Pengfei Huang, and Shiwen Zhang. 2021. Full-Stack Hierarchical Fusion of Static Features for Smart Contracts Vulnerability Detection. In _2021 IEEE International Conference on Blockchain (Blockchain)_, 95–102. DOI:https://doi.org/10.1109/Blockchain53845.2021.00091

\[25\]Zulfiqar Ali Khan and Akbar Siami Namin. 2020. A Survey on Vulnerabilities of Ethereum Smart Contracts. _arXiv:2012.14481 \[cs\]_ (December 2020). Retrieved February 28, 2022 from http://arxiv.org/abs/2012.14481

\[26\]Yuntae Kim, Dohyun Pak, and Jonghyup Lee. 2019. ScanAT: Identification of Bytecode-Only Smart Contracts With Multiple Attribute Tags. _IEEE Access_ 7, (2019), 98669–98683. DOI:https://doi.org/10.1109/ACCESS.2019.2927003

\[27\]Ao Li, Jemin Andrew Choi, and Fan Long. 2020. Securing smart contract with runtime validation. In _Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and Implementation_ (PLDI 2020), Association for Computing Machinery, New York, NY, USA, 438–453. DOI:https://doi.org/10.1145/3385412.3385982

\[28\]Ziyuan Li, Wangshu Guo, Quan Xu, Yingjie Xu, Huimei Wang, and Ming Xian. 2020. Research on Blockchain Smart Contracts Vulnerability and A Code Audit Tool based on Matching Rules. In _Proceedings of the 2020 International Conference on Cyberspace Innovation of Advanced Technologies_ (CIAT 2020), Association for Computing Machinery, New York, NY, USA, 484–489. DOI:https://doi.org/10.1145/3444370.3444617

\[29\]Jian-Wei Liao, Tsung-Ta Tsai, Chia-Kang He, and Chin-Wei Tien. 2019. SoliAudit: Smart Contract Vulnerability Assessment Based on Machine Learning and Fuzz Testing. In _2019 Sixth International Conference on Internet of Things: Systems, Management and Security (IOTSMS)_, 458–465. DOI:https://doi.org/10.1109/IOTSMS48152.2019.8939256

\[30\]Han Liu, Chao Liu, Wenqi Zhao, Yu Jiang, and Jiaguang Sun. 2018. S-gram: towards semantic-aware security auditing for Ethereum smart contracts. In _Proceedings of the 33rd ACM/IEEE International Conference on Automated Software Engineering_. Association for Computing Machinery, New York, NY, USA, 814–819. Retrieved February 26, 2022 from https://doi.org/10.1145/3238147.3240728

\[31\]Ye Liu, Yi Li, Shang-Wei Lin, and Rong Zhao. 2020. Towards automated verification of smart contract fairness. In _Proceedings of the 28th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering_ (ESEC/FSE 2020), Association for Computing Machinery, New York, NY, USA, 666–677. DOI:https://doi.org/10.1145/3368089.3409740

\[32\]Zhenguang Liu, Peng Qian, Xiang Wang, Lei Zhu, Qinming He, and Shouling Ji. 2021. Smart Contract Vulnerability Detection: From Pure Neural Network to Interpretable Graph Feature and Expert Pattern Fusion. _arXiv:2106.09282 \[cs\]_ (June 2021). Retrieved February 28, 2022 from http://arxiv.org/abs/2106.09282

\[33\]Zhenguang Liu, Peng Qian, Xiaoyang Wang, Yuan Zhuang, Lin Qiu, and Xun Wang. 2021. Combining Graph Neural Networks with Expert Knowledge for Smart Contract Vulnerability Detection. _IEEE Trans. Knowl. Data Eng._ (2021), 1–1. DOI:https://doi.org/10.1109/TKDE.2021.3095196

\[34\]Antonio López Vivar, Ana Lucila Sandoval Orozco, and Luis Javier García Villalba. 2021. A security framework for Ethereum smart contracts. _Computer Communications_ 172, (April 2021), 119–129. DOI:https://doi.org/10.1016/j.comcom.2021.03.008

\[35\]Oliver Lutz, Huili Chen, Hossein Fereidooni, Christoph Sendner, Alexandra Dmitrienko, Ahmad Reza Sadeghi, and Farinaz Koushanfar. 2021. ESCORT: Ethereum Smart COntRacTs Vulnerability Detection using Deep Neural Network and Transfer Learning. _arXiv:2103.12607 \[cs\]_ (March 2021). Retrieved February 28, 2022 from http://arxiv.org/abs/2103.12607

\[36\]Bruno Mazorra, Victor Adan, and Vanesa Daza. 2022. Do not rug on me: Zero-dimensional Scam Detection. _arXiv:2201.07220 \[cs, q-fin\]_ (January 2022). Retrieved February 28, 2022 from http://arxiv.org/abs/2201.07220

\[37\]Alexander Mense and Markus Flatscher. 2018. Security Vulnerabilities in Ethereum Smart Contracts. In _Proceedings of the 20th International Conference on Information Integration and Web-based Applications & Services_ (iiWAS2018), Association for Computing Machinery, New York, NY, USA, 375–380. DOI:https://doi.org/10.1145/3282373.3282419

\[38\]Feng Mi, Zhuoyi Wang, Chen Zhao, Jinghui Guo, Fawaz Ahmed, and Latifur Khan. 2021. VSCL: Automating Vulnerability Detection in Smart Contracts with Deep Learning. In _2021 IEEE International Conference on Blockchain and Cryptocurrency (ICBC)_, 1–9. DOI:https://doi.org/10.1109/ICBC51069.2021.9461050

\[39\]Pouyan Momeni, Yu Wang, and Reza Samavi. 2019. Machine Learning Model for Smart Contracts Security Analysis. In _2019 17th International Conference on Privacy, Security and Trust (PST)_, 1–6. DOI:https://doi.org/10.1109/PST47121.2019.8949045

\[40\]K. Lakshmi Narayana and K. Sathiyamurthy. 2021. Automation and smart materials in detecting smart contracts vulnerabilities in Blockchain using deep learning. _Materials Today: Proceedings_ (April 2021). DOI:https://doi.org/10.1016/j.matpr.2021.04.125

\[41\]Peng Qian, Zhenguang Liu, Qinming He, Roger Zimmermann, and Xun Wang. 2020. Towards Automated Reentrancy Detection for Smart Contracts Based on Sequential Models. _IEEE Access_ 8, (2020), 19685–19695. DOI:https://doi.org/10.1109/ACCESS.2020.2969429

\[42\]Meng Ren, Fuchen Ma, Zijing Yin, Ying Fu, Huizhong Li, Wanli Chang, and Yu Jiang. 2021. Making smart contract development more secure and easier. In _Proceedings of the 29th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering_ (ESEC/FSE 2021), Association for Computing Machinery, New York, NY, USA, 1360–1370. DOI:https://doi.org/10.1145/3468264.3473929

\[43\]Noama Fatima Samreen and Manar H. Alalfi. 2020. A survey of security vulnerabilities in ethereum smart contracts. In _Proceedings of the 30th Annual International Conference on Computer Science and Software Engineering_ (CASCON ’20), IBM Corp., USA, 73–82.

\[44\]Noama Fatima Samreen and Manar H. Alalfi. 2021. A Survey of Security Vulnerabilities in Ethereum Smart Contracts. _arXiv:2105.06974 \[cs\]_ (May 2021). Retrieved February 28, 2022 from http://arxiv.org/abs/2105.06974

\[45\]R Sujeetha and C. A. S Deiva Preetha. 2021. A Literature Survey on Smart Contract Testing and Analysis for Smart Contract Based Blockchain Application Development. In _2021 2nd International Conference on Smart Electronics and Communication (ICOSEC)_, 378–385. DOI:https://doi.org/10.1109/ICOSEC51865.2021.9591750

\[46\]Wesley Joon-Wie Tann, Xing Jie Han, Sourav Sen Gupta, and Yew-Soon Ong. 2019. Towards Safer Smart Contracts: A Sequence Learning Approach to Detecting Security Threats. _arXiv:1811.06632 \[cs\]_ (June 2019). Retrieved February 28, 2022 from http://arxiv.org/abs/1811.06632

\[47\]Zhiyuan Wan, Xin Xia, David Lo, Jiachi Chen, Xiapu Luo, and Xiaohu Yang. 2021. Smart Contract Security: a Practitioners’ Perspective. In _Proceedings of the 43rd International Conference on Software Engineering_. IEEE Press, 1410–1422. Retrieved February 26, 2022 from https://doi.org/10.1109/ICSE43902.2021.00127

\[48\]Ben Wang, Hanting Chu, Pengcheng Zhang, and Hai Dong. 2021. Smart Contract Vulnerability Detection Using Code Representation Fusion. In _2021 28th Asia-Pacific Software Engineering Conference (APSEC)_, 564–565. DOI:https://doi.org/10.1109/APSEC53868.2021.00069

\[49\]Wei Wang, Jingjing Song, Guangquan Xu, Yidong Li, Hao Wang, and Chunhua Su. 2021. ContractWard: Automated Vulnerability Detection Models for Ethereum Smart Contracts. _IEEE Transactions on Network Science and Engineering_ 8, 2 (April 2021), 1133–1144. DOI:https://doi.org/10.1109/TNSE.2020.2968505

\[50\]Yajing Wang, Jingsha He, Nafei Zhu, Yuzi Yi, Qingqing Zhang, Hongyu Song, and Ruixin Xue. 2021. Security enhancement technologies for smart contracts in the blockchain: A survey. _Trans Emerging Tel Tech_ 32, 12 (December 2021). DOI:https://doi.org/10.1002/ett.4341

\[51\]Karl Wüst, Sinisa Matetic, Silvan Egli, Kari Kostiainen, and Srdjan Capkun. 2020. ACE: Asynchronous and Concurrent Execution of Complex Smart Contracts. In _Proceedings of the 2020 ACM SIGSAC Conference on Computer and Communications Security_. Association for Computing Machinery, New York, NY, USA, 587–600. Retrieved February 26, 2022 from https://doi.org/10.1145/3372297.3417243

\[52\]Valentin Wüstholz and Maria Christakis. 2020. Harvey: a greybox fuzzer for smart contracts. In _Proceedings of the 28th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering_. Association for Computing Machinery, New York, NY, USA, 1398–1409. Retrieved February 26, 2022 from https://doi.org/10.1145/3368089.3417064

\[53\]Pengcheng Xia, Haoyu Wang, Bingyu Gao, Weihang Su, Zhou Yu, Xiapu Luo, Chao Zhang, Xusheng Xiao, and Guoai Xu. 2021. Trade or Trick? Detecting and Characterizing Scam Tokens on Uniswap Decentralized Exchange. _Proc. ACM Meas. Anal. Comput. Syst._ 5, 3 (December 2021), 39:1-39:26. DOI:https://doi.org/10.1145/3491051

\[54\]Cipai Xing, Zhuorong Chen, Lexin Chen, Xiaojie Guo, Zibin Zheng, and Jin Li. 2020. A new scheme of vulnerability analysis in smart contract with machine learning. _Wireless Netw_ (July 2020). DOI:https://doi.org/10.1007/s11276-020-02379-z

\[55\]Yinxing Xue, Jiaming Ye, Wei Zhang, Jun Sun, Lei Ma, Haijun Wang, and Jianjun Zhao. 2021. Machine Learning Guided Cross-Contract Fuzzing. _arXiv:2111.12423 \[cs\]_ (November 2021). Retrieved February 28, 2022 from http://arxiv.org/abs/2111.12423

\[56\]Shanqing Yu, Jie Jin, Yunyi Xie, Jie Shen, and Qi Xuan. 2021. Ponzi Scheme Detection in Ethereum Transaction Network. In _Blockchain and Trustworthy Systems_ (Communications in Computer and Information Science), Springer, Singapore, 175–186. DOI:https://doi.org/10.1007/978-981-16-7993-3\_14

\[57\]Xiao Liang Yu, Omar Al-Bataineh, David Lo, and Abhik Roychoudhury. 2020. Smart Contract Repair. _ACM Trans. Softw. Eng. Methodol._ 29, 4 (September 2020), 27:1-27:32. DOI:https://doi.org/10.1145/3402450

\[58\]Xingxin Yu, Haoyue Zhao, Botao Hou, Zonghao Ying, and Bin Wu. 2021. DeeSCVHunter: A Deep Learning-Based Framework for Smart Contract Vulnerability Detection. In _2021 International Joint Conference on Neural Networks (IJCNN)_, 1–8. DOI:https://doi.org/10.1109/IJCNN52387.2021.9534324

\[59\]Pengcheng Zhang, Feng Xiao, and Xiapu Luo. 2020. A Framework and DataSet for Bugs in Ethereum Smart Contracts. In _2020 IEEE International Conference on Software Maintenance and Evolution (ICSME)_, 139–150. DOI:https://doi.org/10.1109/ICSME46990.2020.00023

\[60\]Qingzhao Zhang, Yizhuo Wang, Juanru Li, and Siqi Ma. 2020. EthPloit: From Fuzzing to Efficient Exploit Generation against Smart Contracts. In _2020 IEEE 27th International Conference on Software Analysis, Evolution and Reengineering (SANER)_, 116–126. DOI:https://doi.org/10.1109/SANER48275.2020.9054822

\[61\]Yanmei Zhang, Siqian Kang, Wei Dai, Shiping Chen, and Jianming Zhu. 2021. Code Will Speak: Early detection of Ponzi Smart Contracts on Ethereum. In _2021 IEEE International Conference on Services Computing (SCC)_, 301–308. DOI:https://doi.org/10.1109/SCC53864.2021.00043

\[62\]Teng Zhou, Kui Liu, Li Li, Zhe Liu, Jacques Klein, and Tegawendé F. Bissyandé. 2021. SmartGift: Learning to Generate Practical Inputs for Testing Smart Contracts. In _2021 IEEE International Conference on Software Maintenance and Evolution (ICSME)_, 23–34. DOI:https://doi.org/10.1109/ICSME52107.2021.00009

\[63\]Yuan Zhuang, Zhenguang Liu, Peng Qian, Qi Liu, Xiang Wang, and Qinming He. 2021. Smart contract vulnerability detection using graph neural networks. In _Proceedings of the Twenty-Ninth International Joint Conference on Artificial Intelligence_ (IJCAI’20), Yokohama, Yokohama, Japan, 3283–3290.

\[64\]Albert, Elvira, et al. “Taming Callbacks for Smart Contract Modularity.” Proceedings of the ACM on Programming Languages, vol. 4, no. OOPSLA, Nov. 2020, p. 209:1-209:30. November 2020, https://doi.org/10.1145/3428277.

\[65\]Xue, Yinxing, Mingliang Ma, et al. “Cross-Contract Static Analysis for Detecting Practical Reentrancy Vulnerabilities in Smart Contracts.” Proceedings of the 35th IEEE/ACM International Conference on Automated Software Engineering, Association for Computing Machinery, 2020, pp. 1029–40. ACM Digital Library, https://doi.org/10.1145/3324884.3416553.

\[66\]Xue, Yinxing, Jiaming Ye, et al. “XFuzz: Machine Learning Guided Cross-Contract Fuzzing.” IEEE Transactions on Dependable and Secure Computing, 2022, pp. 1–14. IEEE Xplore, https://doi.org/10.1109/TDSC.2022.3182373.

\[67\]Ye, Jiaming, et al. “Clairvoyance: Cross-Contract Static Analysis for Detecting Practical Reentrancy Vulnerabilities in Smart Contracts.” Proceedings of the ACM/IEEE 42nd International Conference on Software Engineering: Companion Proceedings, Association for Computing Machinery, 2020, pp. 274–75. ACM Digital Library, https://doi.org/10.1145/3377812.3390908.

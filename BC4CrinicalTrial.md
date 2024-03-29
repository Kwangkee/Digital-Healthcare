Back to https://github.com/Kwangkee/Digital-Healthcare
***

## TBD

- Collaborating to evaluate blockchain in clinical trials, https://www.ibm.com/blockchain/resources/healthcare/#section-7  

***
*** 
## Blockchain in Healthcare Today
- Blockchain in Healthcare Today, https://blockchainhealthcaretoday.com/index.php/journal/index
- Commercially Successful Blockchain Healthcare Projects: A Scoping Review, https://blockchainhealthcaretoday.com/index.php/journal/article/view/166

***
## Researcher: Khaled Salah
- Khaled Salah, https://scholar.google.co.kr/citations?hl=ko&user=s2X97uIAAAAJ&view_op=list_works&sortby=pubdate
- Blockchain for Patient Safety: Use Cases, Opportunities and Open Challenges, https://www.mdpi.com/2306-5729/7/12/182
- A Blockchain-Based Regulatory Framework for mHealth, https://scholar.google.co.kr/citations?view_op=view_citation&hl=ko&user=s2X97uIAAAAJ&sortby=pubdate&citation_for_view=s2X97uIAAAAJ:DBa1UEJaJKAC
- NFTs in Healthcare: Vision, Opportunities, and Challenges, https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0,5&q=NFTs+in+Healthcare:+Vision,+Opportunities,+and+Challenges&btnG
- The role of blockchain technology in telehealth and telemedicine, https://www.sciencedirect.com/science/article/pii/S1386505621000253?via%3Dihub

***
## Researcher: Yan Zhuang
- Yan Zhuang, https://scholar.google.com/citations?hl=en&user=ISEhE10AAAAJ&view_op=list_works&sortby=pubdate
- [[Re-engineering a Clinical Trial Management System Using Blockchain Technology](https://github.com/Kwangkee/Digital-Healthcare/blob/main/BC4CrinicalTrial.md#re-engineering-a-clinical-trial-management-system-using-blockchain-technology)], https://www.jmir.org/2022/6/e36774/
- [[Development of A blockchain framework for virtual clinical trials](https://github.com/Kwangkee/Digital-Healthcare/blob/main/BC4CrinicalTrial.md#development-of-a-blockchain-framework-for-virtual-clinical-trials)], https://scholar.google.com/citations?view_op=view_citation&hl=en&user=ISEhE10AAAAJ&sortby=pubdate&citation_for_view=ISEhE10AAAAJ:Tyk-4Ss8FVUC
- A Patient-Centric Health Information Exchange Framework Using Blockchain Technology, https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9090282
>- patient-centric HIE designs that shift data ownership from providers to patients  
>- Utilizing the smart contract feature, which is a programmable self-executing protocol running on a blockchain, we developed a blockchain model to protect data security and patients’ privacy, ensure data provenance, and provide patients full control of their health records. By personalizing data segmentation and an “allowed list” for clinicians to access their data, this design achieves patient-centric HIE.  

***
## Researcher: Ilhaam Aziz Omar
- Ilhaam Aziz Omar, https://scholar.google.com/citations?hl=ko&user=pUuYa_kAAAAJ&view_op=list_works&sortby=pubdate
- Applications of blockchain technology in clinical trials: review and open challenges, https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=pUuYa_kAAAAJ&sortby=pubdate&citation_for_view=pUuYa_kAAAAJ:9yKSN-GCB0IC  
- Ensuring protocol compliance and data transparency in clinical trials using Blockchain smart contracts, https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=pUuYa_kAAAAJ&sortby=pubdate&citation_for_view=pUuYa_kAAAAJ:2osOgNQ5qMEC  

***
## Development of A blockchain framework for virtual clinical trials
- Development of A blockchain framework for virtual clinical trials, https://scholar.google.com/citations?view_op=view_citation&hl=en&user=ISEhE10AAAAJ&sortby=pubdate&citation_for_view=ISEhE10AAAAJ:Tyk-4Ss8FVUC

#### System Design

![image](https://user-images.githubusercontent.com/109835677/208568531-22f3aade-51c3-44b2-aa3a-96d34c2bf431.png)  
(1) **Patient Recruitment module**: a smart contract that automatically matches potential subjects, asks matched patients for consent to join the VCT, and generates a specific trial contract for each VCT that is only accessible to the participants.  
(2) **Patient Engagement module**: a smart contract to allow patients to input data and interact with clinical trial sponsors or principal investigators, and  
(3) **Persistent Monitoring module**: a smart contract to persistently monitor anomalies through the analytics tool, either installed on the sponsor’s node or embedded inside the monitor contract.  

![image](https://user-images.githubusercontent.com/109835677/208570101-0875ec39-f925-4157-bdaf-1147a53b15a9.png)  
The monitor contract can also trigger an analytics tool installed on the sponsor’s node and keeps a log of data use in the blockchain. The tool can be a basic comparison model as shown in Figure 3(a), a simple statistical model to summarize the effectiveness of the new treatment, **or even a sophisticated machine-learning model with AI components to detect comorbidities and predict outcomes** depending on the needs of the sponsor.  

***
## Re-engineering a Clinical Trial Management System Using Blockchain Technology
- Re-engineering a Clinical Trial Management System Using Blockchain Technology: System Design, Development, and Case Studies, https://www.jmir.org/2022/6/e36774/
- Re-engineering Clinical Trial Management System Using Blockchain Technology, https://blockchainhealthcaretoday.com/index.php/journal/article/view/215

![image](https://user-images.githubusercontent.com/109835677/208403426-90de7204-6271-4fe5-ae51-70fc876021d4.png)

- Quorum
>-	https://steemit.com/kr/@andybclee/jp-morgan-quorum
>-	https://portalcripto.com.br/ko/%EC%BF%BC%EB%9F%BC-jp-%EB%AA%A8%EA%B1%B4-%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-%EA%B8%88%EC%9C%B5-%ED%94%8C%EB%9E%AB%ED%8F%BC%EC%9D%B4%EB%9E%80%3F/
>-	https://github.com/ConsenSys/quorum

- Future Work
>Our future work will continue to investigate the needs of the clinical trial process and add more comprehensive functions to the proposed blockchain-based CTMS architecture, such as **adding machine learning tools to monitor patient conditions persistently and predict side effects and overall outcomes**. 
>- The current safety monitoring process described in the Study Conduct section relies on the EDC process. However, the Data and Safety Monitoring Board convenes only when the clinical trial has been conducted for a while and the data have met a certain point. **Adding artificial intelligence components to the Study Conduct module can achieve more efficient monitoring.** 
>- We will also investigate more potential in CTMS design using blockchain technology, such as integrating secure multiparty computation with blockchain for computational applications such as subject matching and using the cryptocurrency concept to build a novel CTMS that will help ensure timely validation and payment.  

[References]  
- CTMS: What You Should Know, https://www.appliedclinicaltrialsonline.com/view/ctms-what-you-should-know


***
## Using Blockchain Technology to Manage Clinical Trials Data: A Proof-of-Concept Study  
https://medinform.jmir.org/2018/4/e11949/  

Results:  
>We described **BlockTrial, a system that uses a Web-based interface to allow users to run trials-related Smart Contracts on an Ethereum network**. Functions allow patients to grant researchers access to their data and allow researchers to submit queries for data that are stored off chain. As a type of distributed ledger, the system generates a durable and transparent log of these and other transactions. BlockTrial could be used to increase the trustworthiness of data collected during clinical research with benefits to researchers, regulators, and drug companies alike. In addition, the system could empower patients to become more active and fully informed partners in research.

Conclusions:  
>Blockchain technology presents an opportunity to address some of the common threats to the integrity of data collected in clinical trials and ensure that the analysis of these data comply with prespecified plans. Further technical work is needed to add additional functions. Policies must be developed to determine the optimal models for participation in the system by its various stakeholders.

***
Back to https://github.com/Kwangkee/Digital-Healthcare

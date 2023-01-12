---
pageClass: projects-page
---

## Research Projects


### Blockchain

<ProjectCard image = "/projects/blockchain.jpg">

**Blockchain, Cryptocurrency and Decentralized Finance (DeFi) (in progress)**

*Joint work with [Yang Wang](https://yangwang.ischool.illinois.edu/), [Tanusree Sharma](https://tanusreesharma.github.io/), and [Yun Huang](https://ischool.illinois.edu/people/yun-huang) at UIUC*
  
We are recently working on multiple aspects of blockchain, cryptocurrency and DeFi, including security, usability and trust.

</ProjectCard>


### Misinformation and Misbehavior Mitigation

<ProjectCard image = "/projects/fake.jpg">

**Fact-tampering Attacks against Fake News Detection** 
  
*Joint work with [Justin Hsu](https://justinh.su/) at Wisconsin, [Huankang Guan](https://guanhuankang.github.io/) at Wuhan University, and [Meghana Moorthy Bhat](https://meghu2791.github.io/) at Ohio State* 

News plays a signiﬁcant role in shaping people's beliefs and opinions. 
Fake news has always been a problem and quite a few detection methods have been proposed to combat fake news. 
However, they focus mainly on linguistic aspects of an article without any fact checking. 
We argue that fact-tampering fake news can escape such detection and under-written real news can be wrongly flagged. 
Through experiments on Fakebox, a state-of-the-art fake news detector, we show that fact tampering attacks 
(fact distortion, subject-object exchange and cause confounding) can be effective. 
To address such weaknesses, we argue that fact checking should be adopted in conjunction with linguistic analysis, 
so as to truly separate fake news from real news. 
A crowdsourced knowledge graph is proposed as a straw man solution to collecting timely facts about news events.
  
- **[Paper 1](https://arxiv.org/ftp/arxiv/papers/1901/1901.09657.pdf)**: "Fake News Detection via NLP is Vulnerable to Adversarial Attacks" (ICAART) 
- **Paper 2**: "Fake News Detection via NLP Becomes Harder" (WiML Workshop)

</ProjectCard>


<ProjectCard image = "/projects/fact-fake.png">

**Fake Node Attacks against Rumor Detection based on Bi-directional GCN**

*Undergraduate thesis, advised by [Chenliang Li](http://www.lichenliang.net/) at Wuhan University*
  
Some recent work tried to detect rumor in social media with graph convolutional networks (GCN). 
GCN can better capture propagation features of rumor compared to models solely based on linguistic characteristics, achieving SOTA performance. 
However, GCN is vulnerable to adversarial attacks. 
As a result, rumor sources are able to escape GCN-based detection with the manipulation of adversaries. 
One example escape strategy is to create some robot accounts which seem to be "uninfected" as the rumor source's followers. 
We propose an attack which successfully subvert bi-directional GCN based rumor detector by 4%. 

</ProjectCard>


<ProjectCard image = "/projects/cheating.jpg">

**Mitigating Cheating Behavior in Online Games**

*Joint work with Song Liang and Boya Yin at Tencent*
  
Some users deliberately act badly and throw a game in order to be matched with weaker opponents later, making their teammates frustrated.
We use machine learning algorithms (LSTM, XGBoost) and expert rules to mitigate such misbehavior, creating a better environment for players. 

</ProjectCard>


### Machine Learning Security

<ProjectCard image = "/projects/aml.png">

**Certified Defense against Adversarial Examples** 

*Joint work with [Furong Huang](http://furong-huang.com/) and [Jiahao Su](https://www.linkedin.com/in/jiahao-su-247550a5/) at Maryland, and [Huimin Zeng](https://www.linkedin.com/in/huimin-zeng-264aa1186/?originalSubdomain=de) at TU Munich* 

Machine learning models have been shown to be vulnerable to adversarial examples. 
Tiny perturbation in the input can result in totally different predictions. 
For example, by adding noise to a "panda" picture, the adversary can force the model to recognize it as a "truck". 
In this project, we try to achieve provable robustness against adversarial examples (a.k.a. certified defense). \
Current methods suffer from either high computational complexity or loose relaxation. 
To solve the issues, we propose a technique called **latent space encoding** which is a much lighter mechanism. 
More specifically, we map clean data and adversaries into a latent space, and provably reduce the divergence between the latent distributions. 
Experiments on MNIST show that our method achieves certiﬁed robustness without a large drop in accuracy.

</ProjectCard>


### Social Computing

<ProjectCard image = "/projects/old.jpg">

**Information Seeking and Consumption Practices of Older Adults During COVID-19 (in progress)**

*Joint work with [Yang Wang](https://yangwang.ischool.illinois.edu/) at UIUC*
  
We conduct semi-structured interviews with older adults in China to understand their information seeking and consumption practices during the COVID-19 pandemic.
The study could inform future information systems design for this group of people.

</ProjectCard>


<ProjectCard image = "/projects/mzj.jpeg">

**Foodshow Watching for Life Management**
  
*Joint work with [Xianghua Ding](http://xianghuading.com/index.html) and Xinru Tang at Fudan University, and [Yunan Chen](https://www.ics.uci.edu/~yunanc/) at UC Irvine* 

We conduct semi-structured interviews to understand foodshow watching practices of Chinese users. It turns out that eating-related UGV play important roles in daily life management. 
They are well integrated into viewers' daily lives, shaping eating and sleeping behaviors, relieving stress, and providing comfort. 

- **Paper**: "Watching for Life: Eating Shows and Daily Life Management" (in submission)

</ProjectCard>


<ProjectCard image = "/projects/douyin.jpg">

**Video Streaming for Active Ageing**
  
*Joint work with Xinru Tang and [Xianghua Ding](http://xianghuading.com/index.html) at Fudan University*

We conduct semi-structured interviews to understand older adults' usage of online video streaming platforms such as Douyin. 
We ﬁnd that online streaming enables a form of active ageing by providing great motivations and opportunities for older adults to present themselves to a broad audience, interact with others, and engage in various types of learning.

- **Paper**: "Active Entertainment and Beyond: A Study of the Use of Short Video Streaming Platforms among Older Adults" (in submission)

</ProjectCard>

<style lang="stylus">

.projects-page
  background-color #fafbfc

</style>
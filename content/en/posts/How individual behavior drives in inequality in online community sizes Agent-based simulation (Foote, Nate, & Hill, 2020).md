---
title: "Paper Notes: How individual behavior drives community size inequality"
date: 2021-07-24T16:37:57+08:00
draft: false
---

Foote, Teblunthuis, Hill, & Shaw, 2018

- Abstract 
	- Why are online community sizes so extremely unequal?
		- Cumulative advantage - however, it cannot provide explanation for specific social dynamics, _agency of users in communities, and lack a clear link to individual-level behavior_. 
	- Agent-based Simulation
	- Test whether **individual-level processes of social exposure** and **decisions based on individual expected benefits** reproduce the size data from Reddit
	- Both processes together (but neither alone) contribute to distributions of community sizes.

- Intro
	- >Massive inequality in membership is a feature of virtually every platform hosting online communities.
	- Two questions: why are some online communities larger than others? why do people (make the decision to) join online communities?
		- The answer to the second question was given related to how people make decisions but limited to _a single community context_.
			- 3 sequential processes that influence individuals' decisions to join or leave communities - learn about communities through **social ties and social influence** (which is called social exposure), decide whether to participate at the first time or not, discontinue their participation. This approach is referred to as individual decision benefits.
		- Linkage: how well do individual joining processes explain macro outcomes like membership size?
			- ==online communities provide a way to find the micro-macro link in the social psychology and group dynamics==
		- Simulation - a computational method which can bridge the micro-macro link 
			- >ABS involves building empirically-informed formal approximations of theories of individual behavior, using computers to step through simulated interactions between individual agents behaving according to the formalized theories, and comparing the macro-level outcomes of these simulations against empirically-observed data.
- Background (LitRev)
	- >Social computing research on community participation and community growth is divided into two largely distinct bodies of micro- and macro-level scholarship.
	- How to link the group-level (Crowton & Howison, 2005; )and individual-level
- Agent-based simulation
	- *Pattern-Oriented Modeling of Agent-Based Complex Systems: Lessons from Ecology (2005 Sci)*
	- >All of the models are intended to simulate populations of people and communities over time. Each simulation proceeds through a series of steps. In each time step, each agent sees a subset of communities (the exposure set).
	- Four set of simulations: agents joining and leaving communities randomly; test the influence of social exposure and IEB decisions separately; include both social exp and IEB.
- Outcomes
	- Null models: 
		1. the probability of leaving communities for each agent: the proportion of people who leave reddits each month.
		2. the probability of social exposure for each agent
		3. the probability of joining the community after social exp
	- Social exposure models:
		1. randomly sampling *k* community members from each of the focal agent's *n* communities. 
		2. during each time step, each of these *k* neighboring community members samples up to *m*(1-4) of their other communities to share with the focal agent. An exposure set for each agent of maximum size `n*k*m`.
	- IEB decision models
		1. users get more benefits in successful rather than failed communities. 
--------
### 文书思路
1. 怀着政治与社会理论、技术哲学所启发的对数字公共生活、数字治理的兴趣，关注如何让在线社区中的参与协作（peer production）变得更好

==There are usually two kinds of understanding when it comes to "online communities", one of which refers to those driven by specific topics or interest for chatting, like forums or interest groups; the other connects more with commons-based peer production, such as Wikipedia. I am more interested in the latter, motivated by the key concern - how do people live their public life in the digital environment- since peer production was claimed "radically decentralized, collaborative and nonproprietary" (Benkeler).==

Delighted by the potential to better the public life of online communities featured by peer production, in a social scientific perspective, I would propose a research on how various kinds of characteristics of online communities emerge from the individual-level behaviors. 

For the macro-micro link, the typical social scientific research focused on the structure which formed by the micro interaction, however, the processes through which individual behavior led to the macro structure have not been unmasked. Recent computational methods provide a way to make up this gap, especially agent-based simulation. The theory-data link is more relevant about the value of technology. How would technological change promote the public life? The classical political philosophers or theoristis have proposed images of a good public life, which cannot be approached without a 


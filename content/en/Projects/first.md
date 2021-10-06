---
title: "Mediated Local Governance in China"
date: 2021-09-10T14:49:39+08:00
draft: false
---

 - Funded Undergraduate research project, 09/20 - 05/21
 - Advisor: Associate Professor Yan Yan (Ph.D. in communication at University of Alabama)

## Background

Internet technology use has changed the government behavior and the public life. In China, a large number of government-related official accounts on Weibo (which is a Chinese online platform like Twitter) has been run to better conduct governance.

This project was focused on a typical set of official accounts run by departments of the local government in a particular district. In this case, local citizens or residents have digital access to posing questions relevant about the public life, and are promised to get a prompt response and feedback from the government on the Weibo platform. The following figure shows how the feedback pattern runs.

<div align = center>
        <img src = "https://raw.githubusercontent.com/YbFan115/ybfan115.github.io/master/resources/_gen/images/MediatedGovern.png">
    </div>

We were using mixed research methods to conduct three studies to understand the coordination, collaboration, and effects of the mediated government behavior.

## Study 1: Collaboration and coordination

- Method: We conducted interviews with 7 official staff of different departments in the local government, who are running the Weibo accounts as all or part of their daily work.
- Findings:
    1. The staff from different departments of the local government formed a community to collaborate to solve the problems posed by the residents. They would communicate online and meet offline regularly. 
    2. There was one particular account who play a role as the coordinator, which means it aggregated the tweets posed by residents online, then reposted them to mention the corresponding department, and gave feedback to the residents after the problems got solved. The whole process would be shown publicly on the Weibo platform that everyone could see, and all the relevant tweets were given a tag by the coordinator to form aggregation.
    3. The coordinator which was claimed as the account of the department of publicity, however, was run by one editor who actually served as an  editor in the local journalism media. The higher level of media literacy with the double identites made the edtior balance between the mediated society and the traditional administration departments.


## Study 2: Governance, propoganda, or both?

- Method: We pulled the digital data of all the local governance related tweets under the tag from 2015 to 2021 by Python. 

- Findings:
    1. The data consist of 1711 tweets, among which 1199 tweets are reposted by the coordinator account, which means only around one third in the amount of tweets are truly from those residents who used Weibo to pose local problems. The coordination account reposted the tweets in a short response time (mean = 9.57 h),  to conduct the collaboration with the departments, and to show off the government was playing its role in local governance.
    <div align = center>
        <img src = "https://raw.githubusercontent.com/YbFan115/ybfan115.github.io/master/resources/_gen/images/ResponseTime.png">
    </div>

    2. According to the interaction in tweets, we visualized the coordinator-centric network, in which every node represented an account for particular department in the local government, with the node degree (mean = 14, SD = 19) was defined as the times these accounts were mentioned by the coordinator:
    <div align = center>
        <img src = "https://raw.githubusercontent.com/YbFan115/ybfan115.github.io/master/resources/_gen/images/Govern_network_raw.png">
        <img src = "https://raw.githubusercontent.com/YbFan115/ybfan115.github.io/master/resources/_gen/images/Govern_network_column.png">
    </div>

    3. Then we removed the accounts whose node degree was lower than the mean value, and added the collaboration among other accounts. There appear three clusters, which are verified to be related intensely to the **public transport** (3, 8; 2, 4) and **urban planning** (1, 9).

    <div align = center>
        <img src = "https://raw.githubusercontent.com/YbFan115/ybfan115.github.io/master/resources/_gen/images/Govern_network_simple.png ">
    </div>

## Study 3: Digital divide and participation difference

- Conference Paper Presentation: **Fan, Y.** (2021). The Effects of Digital Divide on the Citizen Engagement in Local Governance: Based on a Survey on the Audience of Official Weibo Run by Local Government in Ma'anshan. Paper presented on the [*2021 ICA-affiliated New Media International Conference in SJTU.*](https://en.sjtu.edu.cn/events/2046-call-for-papers-2021-ica-affiliated-new-media-international-conference-in-sjtu) *Shanghai, China.*
- Method: Survey on a representative sample (n=288) of local residents who are the audience of official Weibo. 
- Major findings: 
    1. The degree of psychological acceptance of digital media can significantly improve citizens' appeal expression behavior and willingness to participate in local governance.
    2. The frequency of using government microblogs can significantly increase the audience's willingness to participate in governance through government microblogs.




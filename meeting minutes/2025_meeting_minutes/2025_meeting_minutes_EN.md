# 2025-06-24 Weekly Meeting Minutes of OSS Compass Community
## Time
June 24 2025, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui，Situ Lingyun，Qi Guoqiang，Zhang Shengxiang，Zhang Yixiang，Hu Liwei，Zhu Jiashun，Dai Ruiqi，Li Shengbao ，Lai Xingyou, Li Songnan,，Li Chunmin
## Topic - Compass community work progress discussion
### I. Open Source Summer Project Progress Report (Dai Ruiqi)
Dai Ruiqi introduced the optimization plan for API calling relationships, shifting from file-based to API-based units to avoid duplicate node issues. Qi Guoqiang proposed discussing and finalizing specific roadmaps, delivery standards, and milestone dates in the coming days. Regarding API graph construction, Qi plans to further improve attributes, enrich graph content, build API graphs for different programming languages, and support multiple application scenarios.
 
### II. Open Source Summer Project Progress Report (Zhu Jiashun，Zhang Shengxiang, Qi Guoqian)
Low-Code Platform Research and Implementation：Zhu Jiashun surveyed domestic and international low-code platforms and selected the Long Flow platform. He presented a minimum viable workflow diagram for open source project influence assessment, covering dimensions such as contributors and project update frequency. The discussion also focused on the platform's visual orchestration and modular management, emphasizing the importance of module isolation and standardized protocols.

Discussion on AI Capabilities and Data Openness ：Regarding AI capability utilization, Zhang Shengxiang proposed opening data query capabilities via the MCP protocol to support calls from external AI tools. The discussion highlighted separating data governance from AI capability provision to maintain openness and flexibility. Qi Guoqiang suggested leveraging large model resources (e.g., ModelForce) to enhance model capabilities and avoid limitations of small models.
### IV. Progress and Next Steps for Project API Internationalization (Hu Liwei)
Hu Liwei announced the completion of API internationalization for the Compass web server project, with the PR merged. Wang Yehui instructed Li Songnan to communicate with Hu to determine the next task arrangements.
### V. WeChat Official Account Operation Optimization (Zhang Shengxiang, Li Chunmin)
Discussing WeChat official account operations, Li Chunmin noted limited postings as a service account. Zhang Shengxiang proposed dual-channel operations via Video account and the official account, optimizing the structure of the top four articles and incorporating Xiaohongshu-style content to enhance dissemination. Wang Yehui agreed to trial Zhang's suggestions to improve operational efficiency.
### VI. Outstanding Issues
●Align and confirm specific roadmaps, delivery standards, and milestone dates after the meeting. (Responsible: Dai Ruiqi; Deadline: July 1, 2025)

●Design a scenario to demonstrate the application of the COT model . (Responsible: Zhu Jiashun; Deadline: July 1, 2025)

# 2025-06-17 Weekly Meeting Minutes of OSS Compass Community
## Time
June 17 2025, 19:00-20:00 PM Beijing time
## Attendees
Qi Guoqiang，Zhang Shengxiang，Zhang Yixiang，Hu Liwei，Zhu Jiashun，Dai Ruiqi，Li Shengbao ，Lai Xingyou, Li Songnan,，Li Chunmin
## Topic - Compass community work progress discussion
### I. Open Source Summer Project Progress Report (Dai Ruiqi)  
Regarding one-click generation of multi-language ASTs, Dai Ruiqi stated that the tool currently supports C++, Java, JavaScript, and Python. After continuous attempts, language processing issues were resolved by installing required libraries. For optimizing the AST generation tool, Qi Guoqiang suggested improving its accuracy before introducing large models. Dai also mentioned that input/output information of APIs has been captured, but dependency relationships remain unaddressed. Qi recommended supplementing API dependencies to form a complete API graph, suggesting the use of Deep wiki to automatically generate API call diagrams for analysis.  

### II. Open Source Summer Project Progress Report (Zhu Jiashun)  
Concerning the Agent process, Zhu Jiashun reported resolving MCP calling issues and optimizing the report browsing function. The file upload feature is still under modification, expected to be completed next week. He also introduced methods for obtaining data via the Compass API, to which Qi Guoqiang added details on data layering and explained the conceptual design of models, including the hierarchical relationship among raw data, metrics, and models. Finally, Zhu proposed the need to design evaluation method indicators. For task orchestration, Qi recommended tools like Airflow; for COT guidance, he suggested researching relevant papers and preparing specific task flows.  

### III. Remaining Issues  
1. Resolve the file upload function by next week to ensure smooth follow-up work.
(Responsible: Zhu Jiashun; Deadline: June 24, 2025)

# 2025-06-10 Weekly Meeting Minutes of OSS Compass Community
## Time
June 10 2025, 19:00-20:00 PM Beijing time
## Attendees
Qi Guoqiang，Zhang Shengxiang，Zhang Yixiang，Hu Liwei，Dai Ruiqi，Li Shengbao ，Lai Xingyou, Li Songnan,，Li Chunmin
## Topic - Compass community work progress discussion
### I. Introduction to the Press Conference Content
On June 3rd, OSS-Compass held a press conference at Peking University. Qi Guoqiang introduced the relevant information of the conference: the release of the Open Source Research Data Hub Service, Open Source Software Selection and Evaluation Service, Open Source Ecosystem Situation Insight Service, and Developer Portrait Service, as well as the establishment of two working groups, ISO WG and AI WG.
### II. Discussion on Video Channel Operation and Account Certification
Due to the live broadcast rules restrictions of the video channel, Qi Guoqiang, Zhang Shengxiang, and Li Chunmin discussed how to increase the number of followers through operational means, such as event promotion or prize incentives. They also considered certifying the account to solve the live broadcast permission issue.
### III. Progress of the "Summer of Open Source" Internship Program
The open source internship program has two topics, which have been respectively undertaken by Zhu Jiashun and Dai Ruiqi. The topics involve AI process orchestration and code artifact analysis. Dai Ruiqi shared the progress of analyzing API call relationships through AST, and discussed tool selection and subsequent functional expansion with Qi Guoqiang and Zhang Shengxiang.
### IV. Future Work Plan
Qi Guoqiang stated that four students will intern in the community, focusing on AI capability construction. In addition, he proposed a plan to build a service dashboard system for managing internal and external traffic statistics, project task flows, and resource status. Zhang Shengxiang suggested using mature monitoring tools like Prometheus to implement data collection and monitoring dashboards, reducing development workload.
### V. Remaining Issues
●Start the internship next week and participate in document inspection to improve document quality and evaluate its correspondence with APIs; (Responsible persons: Zhu Jiashun, Dai Ruiqi; Completion time: Before June 17, 2025)

●Review and resolve issues encountered in the video channel certification process; (Responsible person: Li Chunmin; Completion time: Before June 17, 2025)

# 2025-05-20Weekly Meeting Minutes of OSS Compass Community
## Time
May 20 2025, 19:00-20:30 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang, Zhang Yixiang, Hu Liwei, Chen Hongyun, Zhu Jiashun, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
## Meeting Minutes
### I. Progress of the "Summer of Open Source" Project (Wang Yehui)
Wang Yehui reported that several student proposals for the "Summer of Open Source" project have been received and are currently under review. After discussion, Wang Yehui and Qi Guoqiang agreed that since the project lasts three months, it would be appropriate to finalize the selected candidates first and then assist other students in finding alternative internship opportunities, such as recommending internships at the Institute of Software. 
### II. Preparation Progress for the June Conference (Wang Yehui)
With significant development of new services ongoing, Wang Yehui noted that some services have been launched and require validation of their functionality, performance, and user experience. He requested Zhang Yixiang and Hu Liwei to support the validation work for the new services. Li Songnan will provide a detailed briefing on the functions to be validated after the meeting.
### III. Introduction and Discussion on the Open Source Community Evaluation System (Chen Hongyun, Wang Yehui)
Chen Hongyun introduced the open source community evaluation framework, which covers four dimensions: vitality, organization, collaboration, and services. She confirmed that the evaluation system will serve as the research direction for her graduation thesis. Wang Yehui provided several suggestions:The terminology used in the evaluation framework should be as accessible as possible to reduce interpretation costs and facilitate practical application;Evaluation objects should be categorized into three types: communities, individuals, and software artifacts, as different stakeholders focus on different aspects;Emphasized the importance of multi-dimensional evaluation to comprehensively cover various aspects of the evaluation objects and improve accuracy.
### IV. Discussion on the LLM Engineering Platform Construction Plan (Zhu Jiashun, Qi Guoqiang)
Zhu Jiashun introduced three construction plans for the LLM engineering platform, detailing their architectures and advantages. He and Qi Guoqiang discussed topics such as model inference, evolution directions, and supporting tools. Finally, Wang Yehui requested Zhu Jiashun to organize the meeting discussions into documentation for future reference.
### V. Remaining Issues
None

# 2025-05-13Weekly Meeting Minutes of OSS Compass Community
## Time
May 13 2025, 19:00-20:30 PM Beijing time
## Attendees
Wang Yehui, Li Xiaoming, Zhang Shengxiang, Qi Guoqiang, Zhang Yixiang, Hu Liwei, Jin Xi, Dai Ruiqi, Li Xuhui, Wang Lei, Zhu Jiashun, Gu Hailong, Liao Kaifeng, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin, Hawk 
## Meeting Minutes
### I. Introduction of Community Projects (Qi Guoqiang)
At the meeting, Qi Guoqiang introduced in detail the OSS Compass community and the two internship projects applied for by the community to the attending students and community members. He pointed out that the OSS Compass is an open-source community. The participants cover multiple entities such as individuals, enterprises, and organizations. Its core function is to evaluate the open-source ecosystem. Through building professional evaluation models, it conducts analysis on open-source projects and communities from multi-dimensional indicators such as the number of project members, the number of contributors, the code update frequency, and the code quality.

To support the functions of the community, in terms of platform architecture design, capabilities such as data collection, data pipeline and engine, and data analysis layer have been built. It covers mainstream code hosting platforms and various types of data. Through data processing and analysis tools, a series of evaluation models have been formed. The two project topics released by the community aim to build a general large model engineering platform and, based on this, provide API graph and API analysis and evaluation services for the platform. Among them, the API graph helps users manage API dependencies in a refined way. The API analysis and evaluation service relies on AI to reduce interaction costs. In the forms of functional assistants and indicator models, it meets the needs of users for understanding basic functions and querying complex project information. At the same time, deep application scenarios for university researchers, government agencies, and VC investment analysts, such as competitive product analysis and portrait retrieval, have been envisioned.

In terms of the construction of the large model engineering platform, it includes modules such as interaction, intention, execution, and knowledge engineering. The focus is on intention engineering and execution engineering. Through building a series of agents, the decomposition and execution of complex tasks are achieved. In addition, Qi Guoqiang also introduced the data server configuration of the community, covering computing, data, service, and AI nodes, providing resource guarantee for the projects. Finally, he invited students interested in the projects to reorganize their thinking and submit preliminary plans. Although only two students will be selected to participate in the two projects this time, more community and internship opportunities will be provided in the future.
### II. Discussion on the Open-source Community (Wang Yehui, Zhang Shengxiang)
Wang Yehui said that the open-source community meeting is a platform that brings strangers together based on common interests, allowing everyone to share what they have gained and jointly achieve goals. The open-source community is not just about pure voluntary contributions. It actively meets the needs of participants, whether it is personal value, brand value, or social network value. The development of the open-source community in China benefits from its ability to bring everyone together to share things and jointly achieve goals.
Zhang Shengxiang expressed his agreement. He said that he hopes that more students from different backgrounds will join the community and be able to integrate into the community and make contributions.
### III. Random Self-introduction Interaction（All）
To liven up the meeting atmosphere, Wang Yehui proposed to carry out a common random rotation self-introduction warm-up activity in the community. After each person's self-introduction, the next person is randomly designated to start the self-introduction. The attending personnel actively interacted, introducing their relevant information and hobbies at the meeting. 
### IV. Remaining Issues
None

# 2025-04-29Weekly Meeting Minutes of OSS Compass Community
## Time
Apirl 29 2025, 19:00-20:00 PM Beijing time
## Attendees
Yehui Wang,YiXiang Zhang，Guoqiang Qi, Xingyou Lai, Songnan Li, LiWei Hu，Chunmin Li
## Meeting Minutes
### I. Progress of the Development Project & Discussion of Issues (Zhang Yixiang, Hu Liwei, Li Songnan)
#### 1.Current Progress:
Firstly, the development interfaces by the two interns have been completed, but one interface field still needs to be modified. Next, they need to conduct a code review. In addition, they also need to perform performance testing to ensure that the project can run properly in the production environment. Finally, it is recommended that they use gray-scale testing and interface calls for performance testing.

### 2.Issue Communication:
●Hu Liwei raised the issue that regarding the sorting problem in index data query, it is necessary to confirm the cause of the inconsistent fields. Li Songnan and Wang Yehui explained that the field names of the creation time in different data sources may be different and need to be unified. Li Songnan needs to follow up on this issue in the future.

●Zhang Yixiang mentioned that there was no relevant data in the test database, so he needed to construct requests by himself. He also said that he solved the problem of test data by changing the requested repository.

### II. Arrangement of Follow-up Work (Wang Yehui)
●Annual Meeting Invitation: Invite the two interns to participate in the annual meeting to be held at Peking University on June 4th.

●AI Working Group: It was mentioned that the community is currently establishing an AI working group, and the two interns were asked if they were interested in participating.

●Intern Arrangement: The functions of API, CHAOSS's Metrics, and Metrics Models were mentioned, and the two interns may be responsible for these in the future.

●New Member Joining: Currently, two students are going to join the community, and it is necessary to follow up on the relevant situation.

### III. Remaining Issues:
●Complete the performance testing and ensure the stability of performance; (Person in charge: Zhang Yixiang, Hu Liwei; Completion time: Before May 6, 2025)

●Follow up on the actual situation of the field names of the creation time in different data sources; (Person in charge: Li Songnan; Completion time: Before April 30, 2025)

●Complete the code review and communicate with Xingyou to prepare for the delivery of the production environment; (Person in charge: Li Songnan; Completion time: Before May 6, 2025)

●Follow up on the situation of new members and invite them to participate in the regular meeting after the holiday; (Person in charge: Li Chunmin; Completion time: Before April 30, 2025)

# 2025-04-22Weekly Meeting Minutes of OSS Compass Community
## Time
Apirl 22 2025, 19:00-20:00 PM Beijing time
## Attendees
Yehui Wang, Lingyun Situ，YiXiang Zhang，Hailing Zhao，Guoqiang Qi, Shengbao Li，Xingyou Lai, Songnan Li, LiWei Hu，Chunmin Li
## Meeting Minutes
### I. Discussion on Compass Cooperation Matters (Wang Yehui, Situ Lingyun)
The main current work content of OSS-Compass was discussed at the meeting. Wang Yehui introduced the background of the upcoming press conference and the relevant released functions. In addition, Teacher Situ from Nanjing University introduced the software tools he is currently developing at the school and the current commercial cooperation situation. The two parties had an in-depth discussion on the possible cooperation methods between the tool and Compass, and agreed to meet offline next Tuesday for further discussion.
### II. Discussion on the Progress of Financial Standard Development Work (Li Songnan, Zhang Yixiang, Hu Liwei)
●Firstly, Li Songnan introduced the technical background of the Rest API development work. Wang Yehui proposed that the mirror machine mirror station download service should be focused on being launched this year.

●Zhang Yixiang described the current work progress. The environment has been set up, and he proposed that it may be necessary to divide the tasks of the developed interfaces in the future. Regarding the problems encountered during the work process, he pointed out that during the process of setting up the database in the environment, the account passwords of different users are different. After discussing with Li Songnan, the situation has been fixed, but there is still a login part that needs to configure the front-end framework, which has not been configured yet. Wang Yehui suggested splitting the tasks, and then normally proceeding with the development work.

●Hu Liwei described the current work progress. He has already discussed with Li Songnan and cooperated with Yixiang. The relevant problems have been solved, and the subsequent development work can be started.
### III. Discussion on Optimizing the Development Library and Interface Design (Zhang Shengxiang)
Issues such as the attributes of users or code libraries, development work, interface design, and UI application were discussed. Zhang Shengxiang suggested doing solid work on the engineering level to achieve a better experience in the future. Wang Yehui proposed that Peking University and the Zhongke Soft Research Institute will establish a mirror station, which can share the computing power problem. In addition, the understanding of data based on the interface and how to maintain a consistent calling method and data under the cluster were also discussed.
### IV. Remaining Issues
●Complete the development tasks and formulate subsequent verification and acceptance plans; (Completion time: Before April 30, 2025; Person in charge: Li Songnan, Zhang Yixiang, Hu Liwei)
# 2025-04-15Weekly Meeting Minutes of OSS Compass Community
## Time
Apirl 15 2025, 19:00-20:00 PM Beijing time
## Attendees
Yehui Wang, ShengXiang Zhang，YiXiang Zhang，Guoqiang Qi, Shengbao Li，Xingyou Lai, Songnan Li, LiWei Hu，Chunmin Li
## Meeting Minutes
### I. Task Allocation (Yehui Wang)
It was mainly reported that since the beginning of this year, the financial standards have been achieved. The second demo was completed last week, and the overall architecture design, including the infrastructure layer and the PaaS layer, has been finalized. Subsequently, Zhang Yixiang and Hu Liwei will mainly follow up on the development of the data set interfaces for L1 to L3.
### II. Introduction to the Data Platform Architecture Design (Songnan Li)
The architecture of the data platform was mainly introduced. Starting from the data platform, it is divided into three layers: L1, L2, and L3. L1 is mainly responsible for collecting raw data and performing flattening processing. L2 is the indicator layer, where projects are processed through indicators. L3 is the model layer, which consists of indicator data.
### III. Discussion on Related Issues (Yehui Wang, Songnan Li, YiXiang Zhang，LiWei Hu)
Regarding the above - mentioned content, the meeting discussed the processing of metadata and the implementation of query interfaces. Li Songnan stated that there is no need to consider which layer it belongs to during the development process. Wang Yehui gave a relatively detailed explanation of the role of APIs. In addition, Wang Yehui introduced the five SaaS services (including the open - source situation insight service, community ecosystem evaluation service, developer profile, open - source selection evaluation service, data & model research service), and mentioned the definition and verification of the L1 to L3 data sets in the past week, as well as the method of obtaining REST APIs for future cooperation with the two students. Finally, the meeting mainly discussed the overall plan for 2025, the development in the direction of REST APIs, the implementation of the CHAOSS model, and the establishment of the AI Working Group. Additionally, Compass will hold its annual meeting at Peking University on June 4th, and the two students are hoped to participate.
### IV. Remaining Issues
Complete the development work in the direction of REST APIs to obtain the L1 to L3 data sets within half a month .(Completion time: Before the end of April；Person in charge:YiXiang Zhang，LiWei Hu)

# 2025-02-25Weekly Meeting Minutes of OSS Compass Community
## Time
February 25 2025, 20:00-21:00 PM Beijing time
## Attendees
Yehui Wang, YiXiang Zhang，Hailing Zhao，Guoqiang Qi, Shengbao Li，Xingyou Lai, Songnan Li, Chunmin Li
## Topic - Compass community work progress discussion
### I. Discussion on the cooperation between Open Source Summer and Compass (Yixiang Zhang)
The discussion covered aspects including the layout part, coding effects, chunking standards, etc., as well as the work of readability evaluation. It was proposed to try to conduct rapid information retrieval through knowledge distillation. Regarding the evaluation of the timeliness of texts, currently, the update frequency is judged by the version submission time, and the correlation between timeliness and content was discussed. The update frequency and timeliness of API documents were discussed, and the importance of version information was emphasized.  Yehui Wang proposed that although the timeliness of API documents is closely related to version updates, function additions, etc., it is not the most important. In fact, what everyone generally pays attention to is the usage guide and capabilities of API documents.

### II. Discussing the Situation of the Yearbook Report (Zhao Hailing)
#### 1.Analysis of the Influence of the Open Source Community and Developers
The following questions were raised: a. Regarding open source communities with international influence, including the Linux community, Kubernetes community, etc., and which open source communities in China have international influence. b. Regarding open source developers, including active open source developers and newly added open source developers, and how many open source developers in China are at the ten-thousand level; for this question, Yehui Wang proposed the statistical method in the report, requiring that only developers who have made code contributions be counted. c. Regarding the number of open source developers in China, what is the unified external caliber of the data; Wang Yehui discussed the data sources and definition methods, which may include developers who have submitted issues, cumulative developers who have ever made contributions to Chinese projects, etc. Finally, regarding how to measure the influence of an open source project, Yehui Wang proposed that currently there is no unified measurement standard in the industry, but it can be estimated through indicators such as the number of developers and users, and it also needs to be verified through cross-data and conduct horizontal comparisons. In addition, some proxy indicators, such as the number of issue submissions, download volumes on different websites, etc., can be used to screen out open source communities with potential influence to provide references for decision-making.
 
#### 2.Discussion on Follow-up Cooperation
The establishment situation of the special committee and the follow-up cooperation plan were discussed. Regarding the report, the final draft is expected to be released this week.
 
### III. Remaining Issues：
●Complete the final draft of the report; (Responsible Person: Hailing Zhao; Completion Time: Before March 2nd)

●Discuss with everyone later to determine an appropriate report promotion method; (Responsible Person: Hailing Zhao; Completion Time: March 5th)

# 2025-02-11Weekly Meeting Minutes of OSS Compass Community
## Time
February 11 2025, 20:00-20:30 PM Beijing time
## Attendees
Yehui Wang, ShengXiang Zhang，YiXiang Zhang，Xiaojie Hu,Guoqiang Qi, Shengbao Li，Xingyou Lai, Songnan Li, LiWei Hu，Chunmin Li
## Topic - Compass community work progress discussion
### I. Discuss the Progress of Financial Standard Model Development (Yehui Wang)
The discussion focused on the progress of the customized development of the financial standard model at the Institute of Software, Chinese Academy of Sciences. Yehui Wang mentioned that a multi-faceted model customization platform for different clients would be developed next.
 
### II. Discuss the Annual Report Status (Xiaojie Hu)
Annual Report Data Status: The discussion covered the annual report issues related to OpenAtom, including the number and activity of global open-source projects. For the data of 2022 and 2023, Yehui Wang indicated that key data could be provided, but the volume of data is substantial and requires filtering based on specific needs.

Issue Discussion and Analysis: The discussion analyzed technical vertical growth trends, data analysis, acquisition methods, compliance, and other issues. Yehui Wang expressed hope to collaborate through the annual report work and conduct continuous data efforts via the Data Committee. Finally, Xiaojie Hu stated that the final draft is planned to be completed this week or next.

Annual Report Promotion: Regarding the promotion of the OpenAtom annual report, Yehui Wang proposed that OSS-Compass could collaborate with OpenAtom for joint promotion. Xiaojie Hu mentioned that the related promotion plans would be synchronized later, with the earliest release of information expected in March-April.
 
### III. Remaining Issues:
1.lProvide the total number of global active open-source projects in 2022 and 2023 for reference (Responsible: Yehui Wang, Shengbao Li ; Deadline: Before February 18, 2025).

2.lShare the required data in the group after the meeting for follow-up work (Responsible: Yehui Wang, Shengbao Li ; Deadline: Before February 12, 2025).


# 2025-12-09 Weekly Meeting Minutes of OSS Compass Community
## Time
December 9 2025, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang, Zhang Shengxiang, Zhu Jiashun, Dai Ruiqi, Wang Lei，Huangjinxin， Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
### I. Progress Report on Libyear Project & Open Source Summer Internship (Zhu Jiashun, Dai Ruiqi, Ran Fengyuan)
1.Reported the progress of central repository processing: Rust, Python, and Ruby central repositories have been processed with a success rate of approximately 60%. Discussed issues including probe usage, old repository handling methods, version information acquisition, and package information management. Emphasized the need to obtain information from multiple data sources and ensure the acquisition of the real upstream addresses of source codes.

2.Reported that the current query success rate is about 80%. Suggested enhancing and modifying the tool, modularizing data processing and calculation for easier maintenance and expansion. Supplements and improvements will be made based on the discussion after the meeting.

3.Discussed how to merge data of the same packages across multiple operating systems and perform batch updates. Zhu Jiashun suggested merging codes first, stressing that codes should be as modular as possible to facilitate subsequent quality development and maintenance. Pointed out the need to uniformly collect upstream data with additional data processing, and emphasized fundamentally improving data accuracy while requiring clear task division next.

4.Stated that project progress and task division have been clarified, with primary responsibilities for research and implementation of the agent. Hoped that Ran Fengyuan would share specific progress at the next meeting and cooperate with Zhu Jiashun to implement scenarios into products.
### II. Progress of Technology Classification Project (Wang Lei)
Proposed that approximately 13,000 pieces of data can be processed daily, including data from invalid repositories. Qi Guoqiang stated that additional resources will be added to improve processing capacity and suggested spot-checking data during the process to avoid deviations. Regarding invalid data, Li Shengbao believed there is no need to handle empty projects, only focusing on the reasoning part.
### III. Discussion on OSS-Compass Data Accuracy (Huang Jinxin)
Introduced the ongoing Shanghai Open Source Industry Mapping Project, which requires open source project data accurate to the city level. Regarding data accuracy, Wang Yehui explained the current data collection methods and accuracy, introduced plans for improving accuracy in the future, and finally stated that any subsequent questions can be discussed at any time.
### IV. Pending Issues
●Share project progress and cooperation with Jiashun at the next meeting. (Responsible person: Ran Fengyuan; Deadline: December 16, 2025)

●Complete database table merging and plan subsequent task division. (Responsible person: Li Songnan; Deadline: December 12, 2025)

●Complete code merging and unify upstream data collection logic. (Responsible persons: Zhu Jiashun, Dai Ruiqi; Deadline: December 12, 2025)

# 2025-12-02 Weekly Meeting Minutes of OSS Compass Community
## Time
19:00-20:00 PM (Beijing Time), December 2, 2025
## Participants
Wang Yehui, Qi Guoqiang, Zhang Shengxiang, Zhu Jiashun, Dai Ruiqi, Ran Fengyuan, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
### I. New Member Joining (Ran Fengyuan)
First, we welcomed the new member—Ran Fengyuan—to the OSS-Compass community. The new member introduced themselves in terms of learning experience, competitions, research work, and future research directions, and will gradually participate in community work. Community members extended a warm welcome to the new member.
### II. Progress on the Agent Project (Zhu Jiashun)
The deployment documentation has been updated, and the data returned by the Compass API has been simplified, retaining three categories of data: core contributors, regular contributors, and peripheral contributors, to reduce token usage. Discussions were held on data processing and optimization, API design and calls, stability of project name links, management of technical frameworks and tools, and optimization directions for the Agent model. It was suggested to further optimize community tools and process task orchestration.
### III. Discussion on Progress of Linux Distribution Upstream Version Detection (Zhu Jiashun, Dai Ruiqi)
The progress of Linux distribution upstream version detection was reported, with the current success rate at 58%. Optimizations have been made to the language and description fields. Discussions focused on ways to improve the detection success rate; it was planned to further analyze the causes of detection failures in the meeting this Friday, and it was noted that there is still room for improvement in the accuracy of information obtained from the software center repository.
### IV. Discussion on Follow-up Tasks (Wang Yehui, Qi Guoqiang, Li Songnan)
Li Songnan introduced the progress of the system architecture: the data collection layer has been completed, the task scheduling layer has been built, and the next step will be data joint debugging and API design. Regarding interface design requirements, Wang Yehui requested listing the current API interfaces and evaluating their sufficiency. For the subsequent division of labor for MCP, it was hoped that Zhu Jiashun and Qi Guoqiang would jointly advance the relevant work, synchronize related documents to Ran Fengyuan, who may join in if interested. Finally, discussions were held on the utilization of existing resources, and key time nodes were confirmed to ensure the project progresses as planned.
### V. Outstanding Issues
1.Improve the stability of project name transmission; review and evaluate the logic used by maintainers in open source projects to obtain and update upstream version information, so as to improve accuracy.(Responsible persons: Zhu Jiashun, Dai Ruiqi; Completion date: December 9, 2025)

2.Provide API interface definitions.(Responsible person: Li Songnan; Completion date: December 5, 2025)

# 2025-11-25 Weekly Meeting Minutes of OSS Compass Community
## Time
November 25 2025, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang, Zhang Shengxiang, Zhu Jiashun, Dai Ruiqi, Wang Lei, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
### I. Progress of Open Source Summer Internship Program (Zhu Jiashun)
Reported the latest progress of the COT module, indicating that task templates have been adopted and part of the registration work has been completed. Mentioned that some API calls are unstable; Qi Guoqiang suggested testing stability through minor input adjustments. Additionally, discussions covered model usage, task process and template optimization, deployment documentation and environment configuration, data aggregation and report generation. It was proposed to use rules for data interception and extraction; since the health metrics are not sufficiently scientific, prioritizing community resources for data acquisition was recommended.
### II. Progress of Operating System Libyear Task (Li Songnan, Zhu Jiashun, Dai Ruiqi)
Reported the progress of Linux distribution-related work: code updates have been implemented, and the software package information acquisition rate has reached approximately 80%. Li Songnan raised the issue of irregular repository addresses, for which no effective solution has been formulated yet. Qi Guoqiang proposed supplementing data through package management centers to avoid missing source code repository data, and obtaining all version-related page information through multiple iterations to ensure data consistency. Zhu Jiashun stated that he will first complete data collection for all sub-versions, followed by aggregation and supplementation to improve data integrity.
During the progress report, the problem of difficult language information statistics due to missing language field data was raised. Qi Guoqiang suggested using tools to scan code repositories for language information. Li Songnan noted that the scheduling system has been set up, with the next step being joint debugging. Plans include data pulling first, followed by phased resolution of existing issues. The timeline for completing tasks next week was confirmed, and synchronization of respective work progress was scheduled.
### III. Progress of Technology Classification Project (Wang Lei, Li Shengbao)
Discussed the secondary and tertiary classification of tags, highlighting issues such as difficulty in ensuring the completeness of tertiary tags and slow model processing speed. Proposed the need for a universal computing resource configuration to meet general requirements; emphasized conducting concurrency testing to determine system throughput and average task latency, thereby calculating required server resources. Finally, the launch time for full-scale data scanning and classification was discussed, with the goal of initiating analysis early next week.
Addressed issues including data structure, data acquisition methods, API concurrency and performance testing, along with corresponding solutions. Noted that full data acquisition via API is currently not feasible; suggested resolving account overlap through email deduplication or discussing with Huawei Cloud personnel to explore data export mechanisms. Additionally, Wang Yehui requested resolving data API integration issues and identifying duplicate projects across code hosting platforms to avoid data redundancy. Technical details were further discussed, emphasizing the importance of obtaining repository lists via API and the need to confirm specific implementation methods.
### IV. Pending Issues
●Collate key data points mentioned in the meeting and record them in issues for subsequent follow-up ；(Owner: Zhu Jiashun; Deadline: December 2, 2025)

●Complete software package information acquisition and Libyear calculation ；(Owners: Zhu Jiashun, Dai Ruiqi; Deadline: December 2, 2025)

●Continue improving the secondary classification of project technical domains ；(Owner: Li Shengbao; Deadline: December 2, 2025)

●Verify the accuracy of the Qwen3-32B large model for domain classification ；(Owners: Wang Lei, Li Shengbao; Deadline: December 2, 2025)

●Deploy the Qwen3-32B large model on GPU servers and test domain classification speed 。(Owners: Qi Guoqiang, Wang Lei; Deadline: December 2, 2025).
# 2025-11-18 Weekly Meeting Minutes of OSS Compass Community
## Time
November 18 2025, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui,  Zhang Shengxiang, Dai Ruiqi，Wanglei， Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
### I. Progress of the Operating System Libyear Task Project ( Li Songnan, Dai Ruiqi)
The current progress was reported. Li Songnan stated that the data collection architecture has been established, and the implementation of project functions is underway. Dai Ruiqi shared his progress in data capture, including the capture of version numbers and update dates. Additionally, some issues encountered in capturing version numbers and update dates, as well as database connections, were discussed. Currently, the project progress meets expectations. A task scheduling system will be built and joint debugging will be conducted subsequently.
### II. Progress of the Technology Classification Project (Wang Lei)
Discussions covered the classification and label system, data processing and performance optimization, classification accuracy and performance issues, as well as resource allocation. It is suggested to coordinate with Shengbao to resolve network issues. It is also recommended to optimize labels and conduct manual inspections to ensure their accuracy and rationality. Regarding whether labels need to be expanded, Wang Yehui pointed out that the current focus is on overall insights, aiming to quickly solve the classification problem of tens of millions of projects. Specific project information is not within the scope of this insight requirement.
### III. Discussion on Data Acquisition (Wang Yehui, Zhang Shengxiang)
The situation of data acquisition from Gitee was discussed. It was noted that full-network data was obtained through Gitee last year. It is proposed that this year's data should maintain consistency, and a unified platform acquisition plan is required. Further discussions are expected next week.
### IV. Pending Issues
1.Supplement and improve based on the three-tier domain classification provided by Wang Lei. (Person in Charge: Li Shengbao; Completion Date: Before November 25, 2015)

2.An accuracy issue was encountered when using the Gitee AI large model for domain classification. Seek support from Li Shengbao to resolve it, provide sampled examples of domain classification, and evaluate the rationality of the domain classification based on expert experience. (Person in Charge: Wang Lei; Completion Date: Before November 25, 2015)


# 2025-11-11 Weekly Meeting Minutes of OSS Compass Community
## Time
November 11 2025, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang, Zhang Shengxiang, Zhu Jiashun,Dai Ruiqi， Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
## Topic – Discussion on Compass Community Work Progress 
### I. Open Source Summer Internship Progress (Zhu Jiashun)
It elaborates on the current key progress, mainly focusing on the agent integration of MCP toolbox capabilities and the opening up of ADK toolbox capabilities. However, the progress of the central warehouse is relatively slow. The report has been compiled, covering aspects such as community capabilities, confirmation of code repositories, and ecological health assessment. In addition, issues including data processing, review and evaluation standards, tool scenarios and usage, and project health assessment were discussed.
### II. Discussion on the Progress and Planning of the Operating System Libyear Task Project (Wang Yehui, Li Songnan, Zhu Jiashun, Dai Ruiqi)
#### 1. Discussion on Task Progress
A preliminary architectural design diagram was presented, and the main functions to be implemented, such as data collection tasks and version detection, were explained. Regarding data collection and APIs, Li Songnan stated that external APIs will be provided, and data collection and task scheduling are core functional modules. Additionally, he mentioned that the architecture of the open-source project needs further improvement. Finally, discussions were conducted on task division, version dependency management, and data storage design.
#### 2. Discussion on Subsequent Plans
Discussions centered on interface design and the construction of the data collection layer, emphasizing the need to quickly build the project framework of the data collection layer to facilitate the development of subsequent work. It was pointed out that the operating system requires comprehensive monitoring and evaluation. In addition, attention should be paid to the project's open-source statement and technical reference to Repology. It is recommended to set the repository as a private warehouse in the early stage of the project and configure corresponding permissions to enable tool scanning and management.
### III. Pending Issues
None.

# 2025-11-4 Weekly Meeting Minutes of OSS Compass Community
## Time
November 4 2025, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang, Zhang Shengxiang, Zhu Jiashun, Wanglei，Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
## Topic – Discussion on Compass Community Work Progress 
### I. Progress of the "Open Source Summer" Internship（Zhujiashun）
The preliminary version of the COT module was shared. Discussions were held on issues related to dynamic tool registration, Agent management, and data acquisition and calling. It was proposed that the ADK provides functions for content positioning and memory, which are helpful for generating detailed reports. The use of a multi-agent architecture was suggested to process data by dimensions, thereby improving efficiency and presentation effectiveness. Regarding the optimization of the multi-round iteration mechanism, it was recommended that tools should be guided to complete the core structure of the report to ensure consistency and repeatability.
### II. Progress and Planning Discussion of the "Libyear" Operating System Task Project（Lisongnan、Zhu Jiashun）
#### 1. Task Progress Report
Zhu Jiashun introduced the current progress of the four tasks, focusing primarily on researching the data architecture and data processing flow of Repology, as well as the approaches to obtaining software package version information. Discussions were conducted on matters related to the citation of open-source projects, parsers and data standardization, data acquisition strategies, and platform data parsing.
#### 2. Discussion on Subsequent Plans
The overall design of the system architecture and the interaction methods between various modules were discussed, with emphasis on the importance of interface design. Moving forward, Xingyou will assist in the front-end interface design, while Jiashun and Ruiqi will be responsible for the development of core modules—all modules, however, must interact within a unified architecture. Finally, it was suggested that data from different sources should be compared and integrated to improve data accuracy and reliability. It was also reminded that the overall data scheduling mechanism needs to be considered to ensure the coordinated work of all modules.
### III. Progress of the Technical Classification Internship（Wanglei）
The progress related to technical classification was reported. Issues encountered in label classification generation and large-scale data processing, as well as their solutions, were discussed. Finally, it was proposed that data acquisition and processing require a certain amount of time, and the final results only need to be completed by the end of December. In addition, it was hoped that Qi Guoqiang would support Wang Lei in the label-related work, including national standards and classification based on existing topics.
### IV. Pending Issues
1.Conduct research on the relevant situation of open-source code citation; (Person Responsible: Li Songnan; Completion Date: November 11, 2025)

2.Complete architecture design, interface design and scheduling design; (Person Responsible: Li Songnan; Completion Date: November 11, 2025)

3.Enrich and improve label categories. (Person in Charge: Wang Lei; Deadline: November 11, 2025)

# 2025-10-21 Weekly Meeting Minutes of OSS Compass Community
## Time
October 21 2025, 19:00-20:00 PM Beijing time
## Attendees
Wangyehui，Qi Guoqiang，Zhang Shengxiang，Zhu Jiashun，Dai Ruiqi，Li Shengbao,Li Songnan,Li Chunmin
## Topic – Discussion on Compass Community Work Progress 
### I. Progress of Summer of Open Source Internship Project (Dai Ruiqi)
Last week's work was reported, and discussions were held on issues such as the reproduction problems of Fedora and OpenHarmony, and the 500 status code encountered on GT. It was suggested to re-attempt and organize the request logs. In addition, regarding the classification of open source projects, it was proposed to first use existing tools to organize data in accordance with standard methods, and for non-standard parts, internal promotion of standardized management could be carried out.
### II. Progress of Summer of Open Source Internship Project (Zhu Jiashun)
Discussions covered the framework research, MCP Server functions, X-Agent orchestration methods, as well as the selection and comparison of Agent frameworks. In addition, it was mentioned that a detailed study had been conducted on the version release and snapshot management mechanisms of different operating systems, and relevant contents were discussed. The progress of the COT part will be further accelerated in the follow-up.
### III. Progress of Internship Project (Wang Lei)
Issues related to project classification and feature extraction were discussed. It was suggested to refine multi-classification, which could improve accuracy in similar project clustering. Meanwhile, efforts should be made to find training data for experiments on large models.
### IV. Follow-up Task Plan (Li Songnan)
The overall plan and key milestones of the operating system "Libyear" task project were shared. A bullet screen demonstration and acceptance check will be conducted at the end of the year. It was proposed that progress alignment should be carried out regularly to ensure timelines and deliverables. Several students stated that there was no conflict and would follow up on time in the future.
### V. Discussion on Community Operation Plan (Zhang Shengxiang)
The plan for joint community operation was discussed, including three aspects: 
1. The GOTC Conference will be held in the near future, and invited Compass participate in the topic sharing of the sub-forum; 
2. It is planned to organize live activities such as online topic roundtables and debates in the follow-up; 
3. It was emphasized that the release of the economic index needs to be advanced, and the timeline should be aligned with Wang Yehui. Li Chunmin supplemented the relevant operation plan and stated that alignment and confirmation would be made within this week.
### VI. Pending Issues:
1. Confirm the activity plan within this week.
(Completion Time: October 28, 2025; Person in Charge: Li Chunmin)
# 2025-10-14 Weekly Meeting Minutes of OSS Compass Community
## Time
October 14 2025, 19:00-20:00 PM Beijing time
## Attendees
Wangyehui，Qi Guoqiang，Zhang Shengxiang，Zhu Jiashun，Dai Ruiqi，Li Songnan，Li Chunmin
## Topic – Discussion on Compass Community Work Progress  
### I. Discussion on the Joint Operation of Compass and Gitee Community Activities (Zhang Shengxiang, Wang Yehui, Qi Guoqiang, Li Chunmin)
Starting from the preliminary community interaction planning activity plan formulated by Compass, the discussion was held from several aspects such as activity background, activity objectives, activity strategy, and activity effect. First, Gitee expressed support for the joint interaction between the two communities, but further discussion and optimization were needed regarding the specific strategy of the activity.The two sides clarified the following aspects: Regarding the activity objectives, they are the improvement of community functions, the exposure of community projects, and the further exploration of the commercial value of projects etc; Regarding the implementation of activities, it is proposed to plan a series of long-term activities to gradually enhance the influence of Compass; focusing on high-value projects, which can be achieved through topic creation and value display to attract more people's understanding and thinking about Compass; In addition, it can also be combined with Gitee's existing activities. Regarding the specific details of the activity, the two sides need to discuss and improve further before determining.
### II. Progress and Subsequent Arrangements of Open Source Summer Internship Project (Zhu Jia Shun, Dai Ruiqi, Wang Yehui)
a.Zhu Jia Shun reported the recent progress of the internship project, the deployment and synchronization of related libraries have been completed, and regarding the COT project and Python project framework selection, it is recommended to use the existing framework.

b.Dai Ruiqi reported the progress of operating system analysis, and discussed the configuration files, repositories and version information of operating systems.

c.Discussing data processing and research task allocation, Wang Yehui suggested that Dai Ruiqi and Zhu Jia Shun should divide the research on different operating systems, each focusing on one or two; In addition, confirm whether the interns have other resource needs and ensure that they can be met.
### III. Suggestions on the Follow-up Promotion of Compass (Zhang Shengxiang)
It is proposed that at present, Compass has many valuable cooperation projects, but the external output content is limited, which can be combined with college teachers and students to output more valuable research results, and can also be combined with recently launched models for promotion.
### IV. Outstanding Issues
●Plan the subsequent joint interaction operation plan of Compass and Gitee. (Person in charge: Li Chunmin; Completion time: October 31, 2025)



# 2025-09-09 Weekly Meeting Minutes of OSS Compass Community
## Time
19:00-20:00 PM (Beijing Time), September 9, 2025
## Attendees
Qi Guoqiang, Zhang Shengxiang, Zhang Yixiang, Hu Liwei, Zhu Jiashun, Dai Ruiqi, Qiao Xinyu, Li Shengbao, Li Songnan, Li Chunmin
## Topic - Discussion on the Work Progress of the Compass Community
### I. Progress of the Internship Project (Wang Lei)
Discussed how to analyze the time zone distribution within the community. It was suggested to use a scatter plot to display the time zone distribution of developers, and the importance of nodes in the network could be evaluated through centrality indicators to determine the representative time zones in the community. In addition, the issue of filtering contributors with a small number of submissions was discussed, and it was agreed that contributors with a small number of submissions should be retained.
### II. Progress of the Open Source Internship Project (Dai Ruiqi)
Introduced the process of building the graph database and presented its function description and flow chart; discussed whether files and functions should be used as nodes and how to define the relationships between them; regarding similarity-based queries, proposed the idea of using the graph database for function queries and screening by library name to improve performance; suggested establishing a unified knowledge base for data from multiple projects to facilitate the testing of similarity and accuracy.
### III. Progress of the Open Source Internship Project (Zhu Jiashun)
Discussed the problems encountered recently, including errors in report generation and low efficiency in analyzing qualitative data; proposed to standardize and refine the report template, and reminded all members to submit code in accordance with open source practices. Members were also encouraged to write design documents and user documents to improve the project development and design processes. In the follow-up, the COT work will continue to be optimized based on the discussion results.
### IV. Discussion on Other Issues (Hu Liwei)
Planned to analyze the third-party libraries in open source operating system distributions, and discussed the data collection plan. It may reuse existing models or external scripts. The key challenge lies in locating the repositories and upstream metadata of each distribution, which may require special handling.
### V. Outstanding Issues
None

## Time
August 12 2025, 19:00-20:00 PM Beijing time
## Attendees
Qi Guoqiang，WangLiang、Zhang Shengxiang，Zhang Yixiang，Dai Ruiqi，Qiao Xinyu，Li Shengbao ，Lai Xingyou, Li Songnan,，Li Chunmin
## Topic — Discussion on the Work Progress of the Compass Community
### I. Progress of Open Source Internship Project (Dai Ruiqi)
The optimization of API maps and API function descriptions was discussed, with the improved methods and effects shared. The application of code vectorization, suggestions for function search, dynamic libraries and their dependency relationships were also discussed. It is planned to incorporate relevant methods in subsequent research to solve the problems. It is suggested to select more large-scale and mature projects for testing.
### II. Progress of Internship Project (Qiao Xin Yu)
The research on the classification of technical fields was discussed. An attempt was made to train on the Style dataset, and the training process, optimization, as well as the differences between data parallelism and model parallelism, and the problems and challenges in domain division were introduced. Regarding the current research on the classification and characteristics of operating systems, it is suggested to classify from the perspective of core architecture and key technologies, emphasize paying attention to the application and evolution of new technologies in operating systems, investigate the existing classification of operating systems through extracurricular reading, and understand the division standards of different technical directions. For the research on the characteristics of AI and operating system fields, it is suggested to focus on traditional feature engineering technologies, first learn from existing ideas, then carry out innovation in combination with specific scenarios, so as to promote the improvement and optimization of feature extraction methods.
### III. Discussion on Other Issues (Wang Liang, Zhang Shengxiang, Zhang Yixiang)
●The issues of API analysis, technical field identification, and the standardization of the Compass project were discussed. It was mentioned that a standard could be formulated through the Compass project, which can serve as a reference for everyone, helping to reduce confusion and improve operability.

●The export of AI datasets was discussed. It is suggested that more fine-grained data can be obtained through web page atomization processing. The acquisition and processing of classification information were discussed, and it is necessary to further check whether there are problems in the pagination logic.
### IV. Outstanding Issues
None

# 2025-08-05 Weekly Meeting Minutes of OSS Compass Community
## Time
August 5 2025, 19:00-20:00 PM Beijing time
## Topic — Discussion on the Work Progress of the Compass Community
### I. Progress of Open Source Internship Project (Dai Ruiqi)
Shared progress related to model optimization, especially the code similarity detection function and improvements to the code function description template. It was suggested to first conduct tests on function query and similarity clustering to ensure the effectiveness of the selected models. In addition, the application of AST (Abstract Syntax Tree) and code vectorization was discussed.
### II. Progress of Open Source Internship Project (Zhu Jiashun)
Discussed issues regarding network deployment and service calls, suggesting that local port forwarding could be used. Furthermore, the problem of open source ID and framework was addressed, with relevant optimization recommendations put forward. Regarding project architecture design and process optimization, Zhu Jiashun stated that he would refer to the processes of other projects to design the overall workflow.
### III. Progress of Internship Project (Wang Lei)
Discussed data crawling and analysis. Currently, the crawled data has undergone standardization processing. The impact of geographical location information filling on data accuracy was discussed. To address this issue, it was proposed to further verify the accuracy of developers' regional information through collaboration relationships, festival characteristics, and language habits. Additionally, there are plans to verify developers' regional characteristics through collaborative network analysis and design a collaboration index to evaluate the concentration and dispersion of regional distribution.
### IV. Progress of Internship Project (Qiao Xinyu)
Tested the performance of T5 and BERT models in technical classification and function summarization. It was found that the T5 model performed generally, while the BERT model showed better results. The impact of preprocessing and input formats on model performance was discussed, and it was suggested to add more constraints and examples to improve the quality of model output. Plans are underway to try other models and datasets to further optimize the effectiveness of technical classification and function summarization.
### V. Outstanding Issues
None

# 2025-07-29 Weekly Meeting Minutes of OSS Compass Community
## Time
July 29 2025, 19:00-20:00 PM Beijing time
## Attendees
Qi Guoqiang，Zhang Shengxiang，Zhang Yixiang，Hu Liwei，Zhu Jiashun，Dai Ruiqi，Qiao Xinyu，Wanglei，Hamm，Li Shengbao ，Lai Xingyou, Li Songnan,，Li Chunmin
## Topic – Discussion on Compass Community Work Progress  
### I. Progress of Open Source Summer Project (Dai Ruiqi)  
Dai Ruiqi shared the current status of functional descriptions, mentioning that the functional description documents have been completed. Qi Guoqiang suggested that semantic descriptions should be centralized and recommended using a functional description template for better matching. Zhang Yixiang proposed adding code comments and examples to help large models understand better. Dai Ruiqi noted that tests have been conducted using models of different scales, and attempts have been made to describe application scenarios. Zhang Yixiang suggested using slightly smaller models to save costs, emphasizing the need for more project documentation support.  
### II. Progress of Open Source Summer Project (Zhu Jiashun)  
Zhu Jiashun discussed issues encountered during the project with Qi Guoqiang, Zhang Shengxiang, and Zhang Yixiang, including Docker installation methods, data recovery, server connection, specific project requests, and interface standards. Regarding the research on the COT project, Zhu Jiashun mentioned that existing COT-related papers mainly focus on task decomposition, and some commercial models adopt fixed-rhythm task decomposition methods. Qi Guoqiang emphasized the need to clarify the specific plans for the COT project.  
### III. Sharing on Text Feature Classification (Qiao Xinyu)  
Qiao Xinyu introduced the development history of text classification algorithms from traditional machine learning to deep learning, elaborating on methods in feature engineering such as text preprocessing and feature extraction. She also presented several mainstream deep learning-based text classification methods and mentioned some authoritative evaluation metrics introduced in related papers. Qi Guoqiang suggested that Qiao Xinyu test some open-source models to evaluate their application effects in practical tasks. Zhang Yixiang stated that he would provide GPU resources for Qiao Xinyu to facilitate model testing.  
### IV. Discussion on Subsequent Internship Work Arrangements (Qi Guoqiang, Li Shengbao, Wang Lei)  
Qi Guoqiang explained that the current task focuses on evaluation and measurement for the open-source community, with emphasis on building regional portraits of developers. This includes identifying the number of developers and their regional distribution. He also mentioned subsequent work arrangements for intern Wang Lei, and Li Shengbao further introduced and presented details on this part. Li Shengbao demonstrated methods to identify developers' regional attributes using location information from their profile accounts and commit data, but noted issues with data missing. He discussed the accuracy of location information self-reported by developers with Qi Guoqiang and Zhang Shengxiang. Zhang Shengxiang suggested that developers' locations could be inferred by analyzing the matching between submission times and time zones. Finally, Qi Guoqiang advised Wang Lei to design a complete workflow to integrate various data for developer regional identification, starting with the 10,000 most active developers to gradually validate the workflow.  
### V. Outstanding Issues  
1. Research and implement the image upload function; (Person in charge: Zhu Jiashun; Deadline: August 5, 2025)
   
2. After the meeting, search for relevant data to conduct data analysis and identification of developer activity, and attempt to gradually validate the workflow. (Person in charge: Wang Lei; Deadline: August 5, 2025)
# 2025-07-15 Weekly Meeting Minutes of OSS Compass Community
## Time
July 15 2025, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui，Qi Guoqiang，Zhang Shengxiang，Zhang Yixiang，Hu Liwei，Zhu Jiashun，Dai Ruiqi，Qiao Xinyu，Wanglei，Hamm，Li Shengbao ，Lai Xingyou, Li Songnan,，Li Chunmin
## Topic - Compass community work progress discussion
### I.Progress of the Summer of Code Internship Project (Dai Ruiqi) 
Dai Ruiqi shared content related to CODE QL semantic analysis, pointing out that it is more inclined to structural semantics. In addition, issues related to API functions were discussed.

●API vector generation method: Dai Ruiqi proposed a multi-layer feature vector generation method, which converts API information into vectors for matching. 

●Functional modeling and semantic matching: Qi Guoqiang believes that it is necessary to define functional templates and use large models to fill them to generate standardized functional vectors. He suggested using the template filling method to improve the accuracy of semantic similarity calculation and let the model generate annotations. 

●Namespace and version management: Dai Ruiqi mentioned that the current simple naming rules lead to duplicate name conflicts, and plans to add namespaces and version numbers for distinction. Qi Guoqiang suggested that the naming should include library name, component name and version number. In addition, the issue of naming conflicts between different versions was discussed, and Qi Guoqiang proposed that including library names and version numbers can effectively avoid conflicts. 
 
### II.Progress of the Summer of Code Internship Project (Zhu Jiashun) 
●Discussion on project progress issues: Zhu Jiashun put forward the problems encountered in the internship project, including difficulties in tool debugging, API calls and image generation. He said that he is solving the problem of how to use tools effectively. 

●Open source community contribution and discussion: Qi Guoqiang mentioned that the written content should be contributed to the open source community and hoped that Zhu Jiashun could submit the module to the community. He also proposed to set several high-frequency usage scenarios for testing to ensure that the system can run well in practical applications. Regarding the use of components, Zhu Jiashun said that the addition of components is going smoothly at present, various tools can be integrated smoothly, and the system has high flexibility. 
 
### III.Internship cooperation (Qi Guoqiang, Qiao Xinyu) 
Qi Guoqiang mentioned that interns Wang Lei and Qiao Xinyu have joined, and hoped that they would do related tasks in the project. The task allocation between the two will be coordinated later. Qiao Xinyu mentioned that she has read a review paper on text classification algorithms and learned some machine learning and in-depth knowledge. Qi Guoqiang suggested that Qiao Xinyu share this review paper in the next meeting to establish everyone's perception of the technical field classification. 
 
### IV.Outstanding issues 
●Improve the solution to duplicate problems next week, including registration content and solving API duplicate name issues; (Person in charge: Dai Ruiqi; Completion time: July 22, 2025)

●Enrich the API and deploy it to the server within this week to better meet user needs; (Person in charge: Zhu Jiashun; Completion time: July 18, 2025)

●Share the latest progress and effects of the paper on technical field classification. (Person in charge: Qiao Xinyu; Completion time: July 22, 2025)

# 2025-07-08 Weekly Meeting Minutes of OSS Compass Community
## Time
July 8 2025, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui，Qi Guoqiang，Zhang Yixiang，Hu Liwei，Zhu Jiashun，Dai Ruiqi，Qiao Xinyu，Li Shengbao ，Lai Xingyou, Li Songnan,，Li Chunmin
## Topic - Compass community work progress discussion
### I.Planning for Subsequent Topics (Qi Guoqiang) 
Qi Guoqiang proposed that future community regular meetings should plan topics in advance to accommodate the participation of more cooperative organizations and universities. Tencent Docs or similar tools can be used to allow participants to add topics by themselves, with time limits set to improve meeting efficiency. 
### II.Progress of the Summer of Open Source Projects (Dai Ruiqi, Zhu Jiashun) 
●Dai Ruiqi shared his understanding of CodeQL implementation and API management and query languages. Qi Guoqiang introduced the background of CodeQL and its application in security detection. Regarding whether CodeQL truly retains the semantic information of the original API, Qi Guoqiang also mentioned that CodeQL has a high learning cost and is suitable for complex pattern matching.

●Zhu Jiashun raised some problems encountered in open-source data query, and Qi Guoqiang arranged for the backend to investigate. In addition, Zhu Jiashun tried different API calling methods, and Qi Guoqiang suggested using Moli Ark for testing. They discussed matters related to AI Agent and task flow, project display and evaluation, and environment access, and Qi Guoqiang put forward corresponding suggestions. Finally, they discussed the capabilities of the COT tool and whether the model can design workflows by itself. Zhu Jiashun pointed out that only administrators have the permission to arrange workflows, and Qi Guoqiang suggested defining workflows for several scenarios first, confirming that workflows can be exposed as MCP Server. 
### III.Discussion on the Identification of Technical Field Classification for Open-Source Software (Zhang Yixiang) 
●Functional modeling and semantic extraction: Qi Guoqiang proposed that it is necessary to extract API Block from ST and dependency relationships for functional modeling and analysis, and believed that if QQL realizes semantic information mapping through annotation documents, it is worth learning from. Dai Ruiqi mentioned that when some APIs have no annotation documents, large models can be used to supplement functional descriptions. Zhang Yixiang expressed the hope to see specific examples. 

●Vulnerability detection and code analysis: Zhang Yixiang explained how to track according to vulnerability trigger points in the vulnerability detection process and also discussed the advantages and disadvantages of static analysis and dynamic testing in vulnerability detection. 

●API documentation and information extraction: Zhang Yixiang focused on how to use API documentation annotations for information extraction and classification recognition, and how to expand the feature library by enriching the data structure and content of documents. Dai Ruiqi mentioned that when document annotations are incomplete, large models can be used for supplementation.
### IV.Outstanding Issues 
●Optimize the topic collection process for subsequent community regular meetings; (Person in charge: Li Chunmin; Completion time: July 11, 2025) 

●Conduct in-depth research on the specific usage of API semantics in CodeQL. (Person in charge: Dai Ruiqi; Completion time: July 15, 2025)

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


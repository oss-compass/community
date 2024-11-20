# 2024-11-12 Weekly Meeting Minutes of OSS Compass Community
## Time
November 19, 2024, 20:00-20:30 PM Beijing time
## Attendees
Yehui Wang, Xiaohua Xin, FenJu Fu，Rongman Xu, Shengxiang Zhang, Hailing Zhao, Xiaojie Hu, Guoqiang Qi, Xingyou Lai, Songnan Li, Chunmin Li
## Topic - Compass Community Work Progress Discussion
### I. Insights & Thoughts on OSS-Compass (RongMan Xu)
● Currently have completed the learning mechanism of Rest API, including the use of HTTP methods, the meaning of Status code, how to design interfaces that conform to the style of REST architecture; as well as tested the paging and data passing mechanism through a simple code implementation;
● Familiarized with the OpenAPI specification, understood the main contents of OpenAPI, and wrote an example API document in Swagger Editor to initially familiarize with API document writing and interface testing process;
● Discussed the design of the full-volume data acquisition mechanism and the caching mechanism, and proposed some problems that need to be solved, and Shengxiang Zhang suggested that Shengbao Li could be contacted to provide relevant support.
### II.Demonstration of Compass Lab Demo (Xingyou Lai)
● Demonstrated the updated Compass Lab demo on the current OSS-Compass website, demonstrating the operation of the updated process, and the process has now been published in the official website blog as well as the public number article;
● Discussed the weight adjustment of the annual activity metrics, Yehui Wang suggested that it can be adjusted by the relevant people themselves, and also suggested that different thresholds should be used in different areas such as operating systems and databases;
● Regarding the permissions of models and reports, users can choose to open or not, but need to set permissions such as whitelist.
### III. Remaining issues
None

# 2024-11-12 Weekly Meeting Minutes of OSS Compass Community
## Time
November 12, 2024, 20:00-22:00 PM Beijing time
## Attendees
Yehui Wang, Yanguang Wang, Xiaohua Xin, Yixiang Zhang, Rongman Xu, Shengxiang Zhang, Hailing Zhao, Xiaojie Hu, Guoqiang Qi, Xingyou Lai, Shengbao Li, Songnan Li, Chunmin Li
## I.Topic -Discussion on Compass's cooperation with Open Source Summer and Open Atom Foundation(Yixiang Zhang)
Work plan and data vulnerability analysis：The next work plan was discussed, including detection based on cross-function vulnerability, data set alignment, clustering problem, etc.. First, Yixiang Zhang proposed to perform cross-function vulnerability-based detection, then arrange the dataset and consider cooperation with component analysis. Next, clustering operations are performed, including the relative relationship between images and texts, completeness and timeliness. In addition, issues such as how to deal with document layout and feature extraction were discussed with Yehui Wang.

Text Content Clustering and Quality Assessment：Discusses how to cluster text, including categorization of quality, high school and low school. In order to achieve these goals, factors such as relevance, ordinality, and quality levels need to be considered. In addition, Qi mentioned the document coding guidelines from Google and Microsoft and suggested to refer to the dimensions therein.
## II Insights & Reflections on OSS-Compass (RongMan Xu)
● Discussion on how to provide full amount of data to users and fast delivery of processed data to users. Yehui Wang suggested that there are problems with the current Compass API: ① there is no public schema; ② there is no productized and public way of delivering full-volume data. In addition, issues such as the frequency of data updates and permission settings were also discussed.
● Regarding REST API, Yehui Wang suggested that REST API can add many security configurations, such as rate limit, token checking and so on. In addition, Qi suggested that the REST API can be used to realize the perception of the model, understand the data model definition, and try to do some checksums and symmetric encryption. Finally, Shengxiang Zhang suggests to understand more OPEN API specification from the perspective of engineering practice.
## III. Discussion on the cooperation between Open Atom and Compass
### 1.Sharing Data Building Model with Open Atom (Yehui Wang)
Shared the data building model with Open Atom, grabbed the full amount of data from 2022 to 2024, and shared the framework diagram to build the data model through five dimensions, such as active projects, new projects, active contributors, new contributors, and contribution volume. In order to observe the developer behavior in different countries or regions, he proposed the concept of contributor portrait and analyzed the differences between different countries.

### 2.Discussions were conducted:
#### Yearbook report design discussion (Xiaojie Hu)
Discussed how to evaluate major open source projects, including aspects such as activity, contributors, and ecological construction. The goal of the Open Atom Almanac report is to look for the logic and patterns behind the data, rather than simply ranking them. The report will focus on three areas: database, operating system and AI big model, and analyze the distribution of global countries and Chinese cities. In addition, the possibility of replacing new open source projects with the fastest growing open source projects was discussed with Yehui Wang. 

#### Assessment and Trends of AI Big Model Open Source Projects (Xiaojie Hu)
The evaluation logic and dimensions of open source projects in the field of operating systems and databases, as well as the definition and application of AI big models were discussed. It was pointed out that current AI big models with small requirements for arithmetic power are more suitable for personal and small group use, while open source big models may not be suitable. In addition, Yehui Wang mentioned the role of open source projects in collaboration and how to discover and promote these laws.

#### Discussion on Selection and Incentive Mechanism of Open Source Projects (Xiaojie Hu)
Issues about the selection and data availability of open source projects were discussed. Firstly, it was mentioned to combine the report with a developer conference to publish the most active open source projects in 2024. Regarding the assessment of the value of developers in different technological fields and how to construct dimensions for evaluating projects, Hu emphasized that the selection of open source projects is meant to recognize open source projects in Chinese technological fields. In addition, on how to incentivize organizations and individuals in the field of operating systems and how to define the direction of incentives. Wang Yehui suggested to incentivize around the OS field in terms of enhancing the frequency of software updates and increasing investment in technical software.

#### Contribution Analysis in OS and AI (Xiaojie Hu)
Business contributions, AI model applications, and database industry applications were discussed. Yehui Wang mentioned the importance of operating systems and databases in industry applications, and also emphasized the importance of data breadth insights for developers. He suggested focusing on 2024 data, analyzing data for AI domains, operating systems, and databases, and providing some empirically based recommendations. It is also recommended to talk to experts in related industries to understand the dimensions of their concerns, such as application aspects or industry attributes, in order to consider the problem more concretely.

#### Construction and Application of Project and Developer Profiles (Xin Xiaohua)
Xin Xiaohua raised two questions: One is how to judge whether a project is in China or not, through technical means and data statistics; the other is how to measure the global top30 industry projects, through multiple indicators and models for evaluation. Wang Yehui thinks that there are many labels for each project in the compass database, and it is necessary to establish project and developer profiles and integrate them.

#### Project and Developer Portrait Analysis (Wang Yanguang)
Discussed how to rank active contributors and how to consider the impact of projects. First, Yegui Wang suggested that ranking needs to be done in multiple dimensions, including technology domains, project activity, and so on. Second, there is a need to focus on the differences between developers in different countries and regions in the same field. It is also necessary to pay attention to the ranking of different operating system kernels in the same field. Finally, for details such as document quality, PR quality, etc., it can be used as a series of actions for in-depth insight.

#### Data Analysis and Project Characterization Exploration (Hailing Zhao)
Issues regarding the analysis of developers from different countries were discussed, as well as the combination of projects from the Software Institute of the Chinese Academy of Sciences and Happy Hospital. Zhao Hailing proposed whether to analyze the horizontal indicators of each project by vertical fields in the process of analysis, and analyze the developer's activity based on these indicators. Yehui Wang thought it could be designed based on the above and emphasized the data insight perspective, hoping to include big and comprehensive content in the initial framework rather than covering everything at the beginning.
## IV. Remaining Issues
●Understand Rest API and try to use it to write through documents to interface with Compass model;
(Responsible person: Rong-Man Xu; Completion date: November 19, 2024)

●Finish the initial first draft of the data model based on the built-out data model in mid-December 
(Responsible person: Yehui Wang; Completion time: mid-December)

●Report back to leadership on progress of work on how to measure and incentivize upstream community contributions (Responsible person: Xiaojie Hu;
Completion date: November 19, 2024)

●Communicate with leadership on the logic and strategy of the annual report and incentives aspects, and align with Compass on subsequent directions; 
(Responsible person: Xiaojie Hu; Completion: November 19, 2024)

●Focus on 2024 data and provide data support for AI domains, operating systems, and databases 
(Responsible person: Xiaojie Hu; Completion: November 19, 2024)
# 2024-11-05 Weekly Meeting Minutes of OSS Compass Community
## Time
November 5, 2024, 19:00-20:00 PM Beijing time
## Attendees
Yehui Wang, Yixiang Zhang, Rongman Xu, Shengxiang Zhang, Hailing Zhao, Xiaojie Hu, Guoqiang Qi, Xingyou Lai, Chunmin Li
## Topic -Discussion on Compass's cooperation with Open Source Summer and Open Atom Foundation
### I. Discussion on cooperation matters between Open Source Summer and Compass (Yixiang Zhang)
● Discussion of data crawling results： discussed the recent results of data crawling, and planned to modify the API code in order to crawl the top 10,000 projects; discussed with Yehui Wang about the data migration and storage of the lower ranked projects, and how to filter the high quality data; also explored the model of the community service and support scores and how to evaluate the data by the activity level and community service support.

● Discussion on model evaluation and correlation with project documents: discussed how to evaluate existing project documents through models to get scores for all projects. Qi suggested that the scores of the model can be observed through clustering and other methods to observe the characteristics of different groups, and mentioned the impact of community support on the quality of the whole community. Finally, the issue of treating models as black boxes was discussed, as well as the importance of documentation in open source.

● Model Testing and Optimization Exploration Discussion: discussed the application of a model in scoring, Yixiang Zhang found that the model may generate unreasonable results when dealing with a large number of tokens, and discussed with Yefai Wang, Shengxiang Zhang, and Guoqiang Qi whether the model is optimized for specific types of projects and how to deal with unrecognizable links, etc., and finally proposed that the follow-up needs Yixiang Zhang to do a good job in accumulating the test results and output conclusions.
### II. Insights & Thoughts on OSS-Compass (Rongman Xu)
● It was found that OSS-Compass currently focuses on the community perspective, but lacks the observation of the developer's perspective;

● Discussed the issue of data-oriented objects, and Yefai Wang suggested that data should ultimately serve people, and user orientation needs to be clarified;

● Discussed how to provide full-volume data and how to deliver processed data quickly;

● Discussed how to analyze Raw Data, and how to quickly access different types of data.
### III. Discussion on the cooperation between Open Atom Foundation and OSS-Compass (Hailing Zhao, Xiaojie Hu)
● Discussion on the progress of cooperation: a consensus has been reached on the plan to establish a LF Research-like organization at the Open Atom Foundation, which will be set up by referring to the LF Research organizational structure to set up a data driven research committee or lab similar to the one at Open Atom; in response to the need for continuous evaluation, insights, and governance of projects at UltraAtomics, Yefei Wang proposed that the cooperation can be done in a looser but more Wang Yefai suggested a looser but more in-depth approach to business-specific collaboration;

● Discussion of external resources cooperation strategy: Regarding the work plan of OSS-Compass to establish a community and the development of open source reports, the Open Atomics Foundation proposes to provide relevant support; in addition, the Foundation plans to contact the Open Source Chip Research Institute (OSCRI) and other external forces to participate in the work, and to coordinate the resources to actively cooperate with the work. Wang Yefui proposed to provide full data collection and analysis for 2022-2024 to facilitate the insight work.

● Discussion on report preparation and open source project exploration: Regarding the outline of the report, it is suggested to follow the practice of well-known annual reports in the industry and analyze some important points in depth while spreading the insight data as a whole in order to increase the value of the report. In addition, regarding the technology direction, it is recommended to start with three major technology directions, namely operating system, database and artificial intelligence, and list 10 open source projects in each field, including the mainstream open source projects and those with the most growth potential in China.

● Project Selection and Evaluation Considerations: First, the suggestion of listing candidate projects based on technology areas, such as operating systems, databases, and AI, is presented. Then, it discusses how to conduct competitive analysis from a global perspective and Huawei's perspective, emphasizing the importance of the domestic situation; it raises questions about the list of open source projects, such as whether it is necessary to classify projects into different types. Finally, it was suggested that the domestic situation and needs should be considered when selecting projects.
### IV. Remaining issues
● Make a list of requirements for inviting external experts to participate in the work next week;
(Responsible person: Hailing Zhao; Completion date: November 12, 2024)

● Make a list of candidate projects in three technical directions (e.g. OS, database, AI);
(Responsible person: Xiaojie Hu; Completion date: November 12, 2024)

● Finish evaluating the big technology directions next week to give a rough direction;
(Responsible person: Yehui Wang; Completion date: November 12, 2024)

● Discuss specific dimension indicators next week to decide on subsequent sessions to validate the data;
(Responsible parties: Shengxiang Zhang and Yehui Wang; Completion date: November 12, 2024)

# 2024-10-29 Weekly Meeting Minutes of OSS Compass Community
## Time
October 29, 2024, 19:00-20:00 PM Beijing time
## Attendees
Yehui Wang, Yixiang Zhang, Hailing Zhao, Xiaojie Hu, Fenju Fu, Guoqiang Qi, Xingyou Lai, Shengbao Li, Songnan Li, Chunmin Li
## Topic -Discussion on Compass's cooperation with Open Source Summer and Open Atom Foundation
### Open Source Summer Collaboration Project Research Tracking：Document Quality Assessment-README(Yixiang Zhang)
● README document: He analyzed the specific target personnel to extract some of the relevant features, can be used directly in the way of pattern matching, or directly through the surface model extraction to solve the README document should contain what should be included in the relevant perfect knowledge, the content of the classification and so on，he raised the need for Compass to provide the relevant dataset Subsequently.

● Document Coding style: Subsequently, he will continue to refine the research sample before laying out on that level.

● Document layout rationality: We can use the existing model to try to improve the content of the text of the Chinese document to understand the way as well as writing logic analysis to improve the readability of the document, but need to provide the relevant data sets; on the permutation-related issues, we can analyze the relevant content more deeply, and for the kind of interaction between the picture and the text and so on the design of the situation.

● Document timeliness: We can add two points to the original “whether to update only the function”, one is that version updates need to be prompted; the second is that the open source community documents are not only released on Github, but also synchronized with the internal community documents.

### Discussion on the cooperation between Open Atom and Compass (Hailing Zhao & Xiaojie Hu)
● Open Source Project Evaluation and Developer Positioning: The two sides had an in-depth exchange of views on the selection of projects, data collection and processing, and the fairness and transparency of the awards. There is a need to jointly communicate a mutually agreeable outcome and to find key developers within the project. At the same time, both sides discussed how to evaluate open source projects and developers, and how to ensure the fairness and transparency of the award. Finally, a consensus was reached that this year's technology areas will be determined based on the Foundation's development direction and its own planning.

● List model design: Open Atom proposes that the modeling of the indicators behind the list should be simple to understand and not overly complex. It is suggested that the calculation rules and evaluation rules should be made public for transparency. At the same time, they will consider the dimensions of different technical areas and communicate them according to specific needs.

● Team collaboration and communication of work support needs:The Open Atom Foundation has offered to provide support for OSS-Compass, including evaluation indicator dimensions, expert resources, etc. Subsequently, Compass will need to communicate clearly with other teachers to understand exactly what data or dimensions they need, and coordinate the support resources.

### The remaining issues of the meeting:
● Provide Zhang Yixiang with the dataset needed for the README document to evaluate the rationality of the document layout 
（Relevant person：Guoqiang Qi，Deadline：2024.11.05）

●Provide project ranking interface to Yixiang Zhang
（Relevant person：Xingyou Lai，Deadline：2024.11.05）

● Open Atom Foundation needs to provide a pre-framework, and identify relevant technical areas within this week 
（Relevant person：Xiaojie Hu，Deadline：2024.11.05）

● Follow up to identify the need for commissioning Open Atom to conduct expert meetings 
（Relevant person：Hailing Zhao，Deadline：2024.11.05）
# 2024-08-20 Weekly Meeting Minutes of OSS Compass Community
## Time
August 20, 2024, from 14:15 to 14:37 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
The design of evaluation model dimension and metrics of OSS Compass projects in OSPP have been completed. And they are now under development phase.
### Operations
1. The first episode of the Open Source Project Analysis Insights interview program will take place on August 23.
2. The drafting of the ISO international standard for open source evaluation in collaboration between Compass and CHAOSS is in progress.
3. The Compass survey design for the 2024 OpenAtom Open Source Ecosystem Conference is underway.
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-08-06 Weekly Meeting Minutes of OSS Compass Community
## Time
August 6, 2024, from 14:15 to 15:00 (Beijing Time)
## Attendees
[Shengxiang Zhang](https://github.com/normal-coder), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi), Fenju Fu - OpenAtom
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
The backend development of OSS Compass projects in OSPP is underway.
### Operations
1. The planning of the Open Source Project Analysis Insights interview program is in progress.
2. The collaboration between Compass and CHAOSS on the ISO international standard for open source evaluation is ongoing.
3. The 2024 OpenAtom Open Source Ecosystem Conference has been postponed to the end of September. Compass has applied for an exhibition booth and will research open source communities' interest on evaluation models and metrics.
4. Discussion:
   - Which dimensions of metrics are the community more concerned about? Based on experience, community activity > community services and support, but this needs to be verified.
   - A contributor evaluation system similar to professional titles based on the results of Compass's contributor model evaluation can be developed.
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-07-16 Weekly Meeting Minutes of OSS Compass Community
## Time
July 16, 2024, from 14:15 to 14:25 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Xingyou Lai](https://github.com/coder-sett), [Ran Zhou](https://github.com/JuliaZhou2022), [Rongman Xu](https://github.com/Gevenal)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
OSS Compass projects in OSPP: The Open Source Community Persona project is under development. The Developer Persona project needs to confirm the relevant plans as soon as possible. The two college students will attend the weekly development discussion meetings on Monday evenings.
   - **AP: Yehui Wang and Shengxiang Zhang remind students to attend the meetings on time and follow up on relevant plans and development work.**
### Operations
OpenAtom Open Source Ecosystem Conference 2024 is confirmed to be held from August 27-29. Topic submissions are due by July 16. Compass will not submit a topic but will prepare exhibition materials based on the previously submitted booth requirements.
   - **AP: Ran Zhou follows up on the booth preparation matters.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-07-02 Weekly Meeting Minutes of OSS Compass Community
## Time
July 2, 2024, from 14:15 to 14:33 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Huatian Qin](https://github.com/EdmondFrank), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi), Rongman Xu
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
The recently backlogged PRs for open source project evaluation reports submitted to Gitee has been processed.
### Operations
1. OSS Compass projects in OSPP: The preliminary communication of requirements for the Open Source Community Persona project has been completed. The Developer Persona project needs to complete the initial discussion as soon as possible.
    - **AP: Shengxiang Zhang should promptly meet with the student and other community developers to discuss the development requirements for the Developer Persona project.**
2. Collaboration between the Open Source Face-to-Face Blog Platform and Compass Community: The guest for the first episode has been confirmed as Yehui Wang, and the interview recording is planned to take place this Thursday evening.
3. The OpenAtom Open Source Ecosystem Conference 2024 has been postponed to August, awaiting topic submission for the next call.
    - **AP: Ran Zhou should promptly synchronize relevant information with community members.**
4. Follow-up communication on the data usage application of a graduate student from the University of Chinese Academy of Sciences:
    - **AP: Ran Zhou should communicate with the relevant student to confirm subsequent cooperation.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-06-18 Weekly Meeting Minutes of OSS Compass Community
## Time
June 18, 2024, from 14:15 to 14:26(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Xingyou Lai](https://github.com/coder-sett), [Guoqiang Qi](https://github.com/guoqiangqi), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
No update at this time.
### Operations
1. **OSS Compass projects in OSPP**: The community review of student applications has been completed, and it is now awaiting the review by the OSPP Committee. Results will be announced next week. After the announcement, news release needs to be published on WeChat Official Account Platform and the official website.
    - **AP: Ran Zhou prepares the student selection news release.**
2. **Collaboration between Open Source Face-to-Face Blog Platform and Compass Community**: The outline for the first episode is being prepared, and the recording is scheduled for early July.
3. **Participation in OpenAtom Open Source Ecosystem Conference 2024**: The community has confirmed participation in the form of a booth and a sub-forum topic. Booth design requirements are to be submitted this week, and sub-forum topics next week.
    - **AP: Ran Zhou fills out the booth design requirements form, and Yehui Wang prepares the sub-forum topics.**
4. Participation in other external conferences needs further confirmation.
    - **AP: Ran Zhou promptly updates relevant conference information and discusses with Yehui Wang to confirm participation.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-06-11 Weekly Meeting Minutes of OSS Compass Community
## Time
June 11, 2024, from 14:15 to 14:25(Beijing Time)
## Attendees
[Shengxiang Zhang](https://github.com/normal-coder), [Wenxuan Long](https://github.com/hncslwx), [Xingyou Lai](https://github.com/coder-sett), [Guoqiang Qi](https://github.com/guoqiangqi), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
No update at this time.
### Operations
1. OSS Compass projects in OSPP: Student applications have been reviewed by mentors, pending community review; specific project development plans and schedules need further discussion and refinement.
    - **AP: Ran Zhou completes the community review as soon as possible after receiving the notification email from OSPP. Shengxiang Zhang and Yehui Wang discuss the relevant plans and schedules.**
2. Collaboration between Open Source Face-to-Face Blog Platform and Compass Community: It has been confirmed to try out one episode first, and the guest for the first interview has been confirmed, but the content needs to be planned.
    - **AP: Ran Zhou communicates with the relevant person to confirm the content and timing of the first episode.**
3. The community plans to participate in the OpenAtom Open Source Ecosystem Conference 2024.
    - **AP: Ran Zhou confirms the form of participation with Yehui Wang.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-06-04 Weekly Meeting Minutes of OSS Compass Community
## Time
June 4, 2024, from 14:15 to 14:28(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Huatian Qin](https://github.com/EdmondFrank), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), Xi Chen
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
No update at this time.
### Operations
1. Students registration of OSS Compass projects in OSPP will soon be closed. The students registration for OSS Compass Open Source Community Persona project has been confirmed, while OSS Compass Developer Persona project needs to confirm students registration before the deadline.
    - **AP: Shengxiang Zhang confirms with the students as soon as possible.**
2. Cooperation between Open Source Face-to-Face Blogging Platform and Compass Community: need to continue to communicate the details and clarify the cooperation program and the benefits that can be brought to the community.
    - **AP: Ran Zhou continues to communicate with the person in charge of the platform.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-05-28 Weekly Meeting Minutes of OSS Compass Community
## Time
May 28, 2024, from 14:15 to 14:25(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Guoqiang Qi](https://github.com/guoqiangqi), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
The recent user request for expediting the processing of Compass analysis report subscription for a Gitee project has been finished.
### Operations
1. Students registration status of OSS Compass projects in OSPP: 
    - Two students have communicated with their mentors and confirmed their registration, with one pending. Mentors need to confirm with the students, and follow up on the registration status for application submitting before the deadline of June 4.
      - **AP: Ran Zhou reminds the mentors to handle this matter as soon as possible.**
2. Recently, a blogging platform reached out to the Compass community for collaboration. After communication, it was confirmed that a series of interview programs could be produced and promoted based on Compass platform features and services together.
   - **AP: Ran Zhou follows up on this matter.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-05-21 Weekly Meeting Minutes of OSS Compass Community
## Time
May 21, 2024, from 14:15 to 14:29(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Wenxuan Long](https://github.com/hncslwx), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Guoqiang Qi](https://github.com/guoqiangqi), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Community Collaboration Matters
### Frontend and Backend
1. Recently, the official blog content has been updated.
2. Robot exclusion function has been OK, and it will be effective after the data is updated.
3. The issue that official mailbox can not receive mails needs to be dealt with.
   - **AP: Shengxiang Zhang and Huatian Qin deal with it as soon as possible.**
4. Recently, a user reported that his Gitee project request for subscription to Compass analytics report has been pending for a long time and needs to be processed as soon as possible.
   - **AP: Shengxiang Zhang handles it as soon as possible.**
### Community Collaboration
1. The recently submitted application for using Compass data for academic research needs review comments.
   - **AP: Shengxiang Zhang will send an email to inform the applicant of the relevant comments and the follow-up cooperation program.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-05-14 Weekly Meeting Minutes of OSS Compass Community
## Time
May 14, 2024, from 14:15 to 14:25(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Guoqiang Qi](https://github.com/guoqiangqi), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
1. Ongoing updates to the secondary classification of open source projects, with 10+ new categories added.
2. Recently, over 40,000 new open source projects have been added to OSS Compass database.
3. Project Deep Dive Insight Solution now supports specific repositories filtering within the community, with new features for excluding bots and searching organizations.
### Operations
1. The official email is not receiving registration verification codes or recent external collaboration application emails and this issue needs to be addressed.
    - **AP: Shengxiang Zhang handles this as soon as possible.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-05-07 Weekly Meeting Minutes of OSS Compass Community
## Time
May 7, 2024, from 14:15 to 14:32(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Guoqiang Qi](https://github.com/guoqiangqi), [Ran Zhou](https://github.com/JuliaZhou2022), Xiaomeng Wang - National Industrial Information Security Development Research Center
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
No updates at the moment.
### Operations
1. Recently, some students have inquired about registering for the OSS Compass projects in OSPP event. It is recommended that students contact mentors directly, and mentors can get involved early in the students selection process.
   - **AP: Ran Zhou informs the students who inquired to contact the mentors.**
2. Notify the foreign university researchers who previously applied to use Compass open source evaluation data that the Compass data usage process is now ready.
   - **AP: Ran Zhou should notify the relevant personnel ASAP.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-04-23 Weekly Meeting Minutes of OSS Compass Community
## Time
April 23, 2024, from 14:15 to 14:30(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Huatian Qin](https://github.com/EdmondFrank), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Guoqiang Qi](https://github.com/guoqiangqi), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
- Interfaces related to robot and organization selection in the Project Deep Dive Insight Solution have been added.
### Operations
- Projects application for the OSPP event:
   - **AP: Ran Zhou completes the project application within this week.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-04-16 Weekly Meeting Minutes of OSS Compass Community
## Time
April 16, 2024, from 14:15 to 14:25(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Feng Zhong](https://github.com/poorfish), [Huatian Qin](https://github.com/EdmondFrank), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
1. The backend workflow has been updated to support one-click releases from the frontend. Future frontend updates will not require deployment actions by the backend.
2. The project's sub-category pages now have search, sorting, and pagination functionalities added.
3. Project names on GitHub are case insensitive, whereas on Gitee they are case sensitive. Currently, Compass maintains case sensitivity to ensure compatibility. Related [issue](https://github.com/oss-compass/compass-web-service/issues/69).
### Operations
1. Compass will soon implement a collaboration project with OpenHarmony.
2. Projects applications for OSPP need to be submitted promptly.
    - **AP: Shengxiang Zhang needs to complete the content within this week, and Ran Zhou will make organizing and supplementing as necessary.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-04-09 Weekly Meeting Minutes of OSS Compass Community
## Time
April 09, 2024, from 14:15 to 14:31(Beijing Time)
## Attendees
[Shengxiang Zhang](https://github.com/normal-coder), [Huatian Qin](https://github.com/EdmondFrank), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
1. Revision of the text description of the three-dimensional evaluation system graph: "South Fit" to "Upstream Ecology", and "Northbound Adoption" to "Downstream Ecology"; completed.
2. Issues in project info repository are being handled and will be completed this month.
   - **AP: Shengxiang Zhang handles them as soon as possible.**
3. The [issue](https://github.com/oss-compass/compass-web-service/issues/70) for bugs of project report pages' data anomalies has been raised , and more issues should be raised for other similar bugs as soon as possible.
   - **AP: Shengxiang Zhang completes the creation as soon as possible.**
4. The English version of the Compass data usage process has been put on line, and the relevant terms of agreement can be temporarily removed from the website, to be sent to the applicant when there is relevant cooperation.
   - **AP: Ran Zhou communicates with Xingyou Lai to delete the agreement terms in the application process.**
### Operation
1. Community registration for OSPP activity has been reviewed and now needs to be declared for the projects.
   - **AP: Shengxiang Zhang fills out the projects as soon as possible, Ran Zhou makes information addition.**
2. Keep the collection of user survey feedback and no processing for the time being.
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-04-02 Weekly Meeting Minutes of OSS Compass Community
## Time
April 02, 2024, from 14:15 to 14:34(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Wenxuan Long](https://github.com/hncslwx), [Huatian Qin](https://github.com/EdmondFrank), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
1. The issue regarding the loss of project report page data recently mentioned by openKylin community has been investigated and resolved. It was due to insufficient memory leading to node crashes, affecting over 2000 repositories. The issue has now been fixed.
   - **AP: Ran Zhou informs openKylin community that the issue has been resolved.**
2. The bugs related to project report page data anomalies reported by users last weekend need to be tracked in issues.
   - **AP: Shengxiang Zhang creates the relevant issues.**
### Operations
1. Last week, OSS Compass community participated in the 2nd OSPO Summit & Dev.Together 2024 held in Shenzhen, conducting user surveys through questionnaires and one-on-one interviews. The feedback collected mainly includes:
   - Compared to open source community maintainers, operators, and others directly involved in managing open source projects, OSPOs, foundations, consulting agencies, and other entities indirectly managing or observing open source projects tend to make more use of the existing open source evaluation SaaS services provided by OSS Compass;
   - Respondents generally expressed a desire for future OSS Compass open source evaluation reports to provide summaries and analyses after presenting the data;
   - Regarding the community portrait and contributors' individual portrait widget features to be developed by the community in 2024, respondents generally showed high expectations and willingness to use them.
2. The number of responses currently collected from the survey questionnaire is not enough, and more users need to be found to fill it out.
   - **AP: By mid-April, Shengxiang Zhang seeks more users to fill out the questionnaire through Gitee.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-03-26 Weekly Meeting Minutes of OSS Compass Community
## Time
March 26, 2024, from 14:00 to 15:00(Beijing Time)
## Location
- Offline: The office of OSChina
- Online: Tecent Meeting 513-5733-3878
## Attendees
- In Person: Hongshu - OSChina, [Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Feng Zhong](https://github.com/poorfish), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi)
- Online: [Wenxuan Long](https://github.com/hncslwx), [Huatian Qin](https://github.com/EdmondFrank)
## Topic - Progress Discussion on Compass Community 2024 Business Collaboration Progress, Technical Planning, and Operations Matters
### Business Collaboration Progress
OSS Compass, in cooperation with CHAOSS, has worked on writing open source evaluation standards. The framework and plan have now been confirmed, pending academic support. Subsequently, it will be recommended by the Linux Foundation for the standard to become an ISO international standard, and certification services will be provided.
### 2024 Technical Planning
1. After discussion and decision, the main features to be developed in 2024 are:
   - Community Profile: A one-page report that can display and mine the value of open source communities.
   - Individual Profile: A one-page report showing the value of open source contributions.
2. **AP: Yehui Wang leads the community developers to further discuss the specific information that needs to be displayed for the above two features as soon as possible.**
### Operations
1. The main goal of the community participating in the 2nd OSPO Summit & Dev.Together 2024 from March 28-30 is user research and collecting user feedback.
   - **AP: Ran Zhou organizes related user research work, with support from Shengbao Li and Xingyou Lai.**
2. The community will participate in the Open Source Promotion Plan of China, recruiting college students to develop the community profile and individual profile features.
    - **AP: Ran Zhou submits the application materials as soon as possible within this week.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-03-19 Weekly Meeting Minutes of OSS Compass Community
## Time
March 19, 2024, from 14:15 to 14:33(Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Feng Zhong](https://github.com/poorfish), [Huatian Qin](https://github.com/EdmondFrank), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi), Fenju Fu - OpenAtom
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
1. A new search bar will be added above the Project Deep Dive Insight Solution details page. The related [Issue](https://github.com/oss-compass/compass-web/issues/330) has been created, and the frontend modification needs to be completed as soon as possible.
   - **AP: Xingyou Lai completes it as soon as possible.**
2. Some bugs has recently been fixed in the backend.
3. The expansion of OpenSearch is completed, with no issues found for the time being.
4. Memory usage optimization has been launched. The effect will be reviewed after a full data refresh next week.
### Operations
1. Participation in the 2nd OSPO Summit on March 28-29: The promotional copy for the event has been published on WeChat official account platform; Yuehui Wang will attend the office hour on the morning of the 29th and the roundtable discussion in the afternoon; The details of presenting the OSS Compass usage survey at the conference need to be clarified as soon as possible.
   - **AP: Ran Zhou confirms the details of the survey presentation with the organizers as soon as possible.**
2. Participation in the Dev.Together 2024 on March 30: Joining the community treasure chest market, the organizers provide a booth and a small display rack, requiring the preparation of roll-up banners, display board design documents, computers, etc.; Posters, display boards, and roll-up banners are being designed, with the related [Issue](https://github.com/oss-compass/community/issues/72) already created. The display board will feature a QR code for the OSS Compass usage survey, and the roll-up banner will present community introduction content, needing to be reusable.
   - **AP: Feng Zhong provides design documents by this Friday if possible; Ran Zhou promptly releases the copy and posters for promotion, arranges for the production of roll-up banners and submission of display board design files to the organizers for production within this week, and confirms the deadline for soliciting topics for the Unconference meeting at the same time.**
3. The options of the OSS Compass usage survey questions need further review and confirmation.
   - **AP: Yuehui Wang reviews and confirms them as soon as possible.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-03-12 Weekly Meeting Minutes of OSS Compass Community
## Time
March 12, 2024, from 14:15 to 14:59 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Feng Zhong](https://github.com/poorfish), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
1. An Issue template for bug fixes has been created and will be added to the Issue creation process in all repositories.
   - **AP: Xingyou Lai makes the addition.**
2. Collection of topic data at the repo stage has been completed. [Issue](https://github.com/oss-compass/compass-metrics-model/issues/104) has been submitted, awaiting the merging of related PRs.
   - **AP: Yehui Wang reviews and merges related PRs.**
3. The issue of large memory consumption in model calculations has been resolved. [Issue](https://github.com/oss-compass/compass-metrics-model/issues/110) has been closed.
4. Contributor domain personas have been updated with metrics such as signed-off-by, reviewed-by, code_committer, etc. The related [Issue](https://github.com/oss-compass/compass-metrics-model/issues/106) has been closed.
5. Issue/PR details information table for Project Deep Dive Insight Solution streamlining: URL column removed, titles hyperlinked, creation time and closing time merged into one column, and adding alerts of exceeding the average for processing time.
   - **AP: Xingyou Lai confirms with Feng Zhong and makes specific modifications for frontend adjustments; Shengbao Li and Huatian Qin provide backend data support, such as recalculating averages, providing data interface, etc.**
### Operations
1. The second draft of the user survey questionnaire is completed, pending modifications based on meeting discussions and testing.
   - **AP: Ran Zhou makes modifications promptly and asks team members to conduct test fills.**
2. Design work for the 2nd OSPO Summit and Dev.Together 2024 posters, roll-ups, etc., needs to be completed promptly. Try to finish the first wave of the meeting participation promotion this week.
   - **AP: Ran Zhou promptly confirms meeting details with the organizers, and completes related design and promotional work.**
3. Compass data usage process: Place it on the Compass Collaboration page, replacing the "Contact Us" button at the top with a "Data Usage Request" button, and displaying the relevant process and agreement content in a pop-up form.
   - **AP: Xingyou Lai makes relevant frontend modifications. Ran Zhou promptly provides an English version of the process and agreement, and promotes this update on Twitter and WeChat official account platform after frontend modifications are completed.**
4. Set up reminders for community meetings.
   - **AP: Ran Zhou and Xingyou Lai make relevant settings.**
5. The offline workshop for community development members is scheduled for March 26th at OSChina. Meeting notifications need to be sent before the meeting.
   - **AP: Ran Zhou sends meeting notifications to attendees before March 26th.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-03-05 Weekly Meeting Minutes of OSS Compass Community
## Time
March 05, 2024, from 14:15 to 14:47 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Feng Zhong](https://github.com/poorfish), [Huatian Qin](https://github.com/EdmondFrank), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi), Fenju Fu - OpenAtom
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
1. Add filtering to the contributors list in the Project Deep Dive Insight Solution:
   - Currently, only general filters such as all repositories and including bots are moved to the top.
   - Other filters related to columns remain unchanged, still adding organizational filters in the table header.
   - Domain persona and role persona filters are selected by default, currently not checked, and need to be fixed.
     - **AP: Xingyou Lai makes the fixing.**
2. The official homepage now includes recent update alerts at the top.
3. The default view range for Project Deep Dive Insight Solution data has been changed to 6 months.
4. The technology secondary classification has recently added Rust projects. Currently, only 30 projects are displayed by default in each category, and now pagination is needed to display all.
   - **AP: Xingyou Lai confirms with Huatian Qin and makes the modification.**
5. Project repository topic data needs to be gathered into the Compass dataset.
   - **AP: Shengbao Li collects this data.**
6. Recent backend work mainly involves supporting table filtering parameters, ensuring dependencies are updated regularly, etc. OpenSearch expansion is scheduled for next week.
   - **AP: Huatian Qin proceeds with the OpenSearch expansion as soon as possible.**
7. The issue of excessively high memory usage in recent model runs will be resolved this week; the issue has been created.
   - **AP: Shengbao Li resolves it as soon as possible.**
8. Repository Dashboard maintenance: update status in a timely manner, handle all remaining tasks by the end of March, and update the corresponding status.
   - **AP: Shengxiang Zhang urges relevant personnel to maintain the Dashboard.**
### Operations
1. The legal affairs of Compass data usage terms have been confirmed as OK.
   - **AP: Ran Zhou quickly asks the frontend to update the related processes and terms on the official website, and at the same time, contact the foreigner who wanted to use Compass data before to discuss the specific usage plan.**
2. March 28-30, Compass team will attend the 2nd OSPO Summit and Dev.Together 2024 held in Shenzhen to conduct user research and will set up a booth at the Dev.Together summit to present OSS Compass, finding users, and understanding their demands.
   - **AP: Ran Zhou finalizes the draft survey questionnaire within this week for discussion and feedback from the team, completes the final version of the questionnaire as soon as possible, and designs the booth plan promptly.**
3. Organize an offline meeting for community development members at the end of March to discuss the community's technical planning.
   - **AP: Ran Zhou confirms everyone's availability as soon as possible and organizes the meeting.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-02-27 Weekly Meeting Minutes of OSS Compass Community
## Time
February 27, 2024, from 14:15 to 14:37 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Wenxuan Long](https://github.com/hncslwx), [Feng Zhong](https://github.com/poorfish), [Xingyou Lai](https://github.com/coder-sett), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), Xiaoming Li - Kaiyuanshe
## Topic - Progress Discussion on Compass Frontend, Backend and Operational Matters
### Frontend and Backend
1. Development of OpenHarmony dashboard is about to commence.
2. Update on the status of lingering issues in the project repository board.
   - **AP: Shengxiang Zhang informs Huatian Qin for updates.**
3. Optimization needed for excessive server memory usage during backend model data processing.
   - **AP: Shengbao Li and Huatian Qin make optimization promptly.**
4. Estimate the time required to rerun all data after resolving memory issues.
   - **AP: Shengbao Li and Huatian Qin make the estimation.**
5. The Contributor Persona List in Project Deep Dive Insight Solution now includes a contributor search button. It's suggested to place the search box at the top, enabling search for contributors, projects, etc.
   - **AP: Feng Zhong redesigns the search box placement. Xingyou Lai adjusts the frontend. Shengbao Li and Huatian Qin make backend modification support.**
6. Introduce search boxes in the Project Deep Dive Insight Solution's Issue and PR lists, remove the URL column, add hyperlinks in the title column, optimize table display, and enhance reading experience.
   - **AP: Feng Zhong designs search box placement and proposes a new display format for Issue and PR lists. Xingyou Lai adjusts the frontend. Shengbao Li and Huatian Qin make backend modification support.**
7. Profile pictures have been added for each contributor in the Contributor Persona List of Project Deep Dive Insight Solution, clicking on which will redirect to their Gitee or Github homepage.
8. Textual explanations for various types of repositories on the project submission page added .
9. Content update on the official website's dynamic page: updating previously pending articles from the WeChat official account platform in both Chinese and English, to be completed this week.
   - **AP: Xingyou Lai complete as soon as possible.**
### Operations
1. Organize offline discussions among community developers in March to plan business strategies and identify killer applications.
2. By the end of March, Yehui Wang will lead relevant community members to participate in The 2nd OSPO Summit and Dev.Together 2024 held in Shenzhen. Surveys will be distributed during the events for user research.
   - **AP: Ran Zhou designs survey questionnaire promptly and submits a draft within two weeks.**
3. User interviews.
   - **AP: Shengxiang Zhang assists in inviting open source community managers and developers for interviews through Gitee resources to understand user demands.**
4. Expedite the review of Compass data usage agreements.
   - **AP: Shengxiang Zhang promptly requests legal review and submits the final draft.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-02-20 Weekly Meeting Minutes of OSS Compass Community
## Time
February 20, 2024, from 14:15 to 14:54 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Xingyou Lai](https://github.com/coder-sett), [Huatian Qin](https://github.com/EdmondFrank), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Compass Community 2024 Business Planning and Operational Matters Discussion
### 2024 Business Plan
1. SaaS Services:
    - Add custom community persona components and personal prersona components to meet the personalized needs of open source community managers and developers.
    - Add software package version information to address open source selection needs.
    - Add developer info search in the search box.
    - Provide a one-page diagnostic report for each project.
    - New features to be added to Project Deep Dive Insight Solution: labeling robots of contributors list, support of repository filtering for community projects, support of searching specific contributors in the contributors list, support for viewing code line numbers in domain persona, and distinguishing between internal and external developers.
    - Develop frontend tracking functionality to capture user behavior, analyze which modules users are more interested in, and provide data for analysis.
    - Bug fixes for existing functionalities.
2. Evaluation System:
    - Add contributor journey, security, and compliance models.
3. Compass Evaluation of Community Value/Developer Value.
### Operations
1. User Surveys:
    - User positioning shifts from focusing solely on OSPOs of big corporations to also targeting a broader range of small-scale open source community managers and developers.
    - Conduct surveys targeting open source community developers and managers to understand their real needs from Compass.
    - Collect user feedback to prioritize feature updates.
    - Mainly survey three types of users: open source community managers/developers gathered by OSChina, security/compliance vendors, and Apache China open source community managers/developers.
       - **Assigned Personnel (AP): Shengxiang Zhang supports user surveys through Gitee's resources channel, initially categorizing relevant open source communities and later participating in the survey process. Ran Zhou should plan the overall survey as soon as possible, designing the format and content of the survey. Yehui Wang guides the survey execution, participates in the survey process, and analyzes the survey results.**
2. Collaborate with external vendors for community operations.
   - Collaborate with external vendors in security, compliance, and other areas to jointly build models and promote related community operational work.
3. Initial draft of Compass Data Usage Agreement completed.
    - **AP: Ran Zhou should confirm the specific content with Shengxiang Zhang as soon as possible, and Shengxiang Zhang communicates with the legal department for reviewing.**
4. Community organization structure adjustment：
   - Community members become community contributors.
    - Add a user committee.
      - **AP: Ran Zhou records the matter, and Yehui Wang organizes the discussion at the next Board meeting.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-2-6 Weekly Meeting Minutes of OSS Compass Community
## Time
February 6, 2024, from 14:15 to 14:40 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Wenxuan Long](https://github.com/hncslwx), [Xingyou Lai](https://github.com/coder-sett), [Huatian Qin](https://github.com/EdmondFrank), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022)
## Topic - Progress Discussion on Compass Frontend and Backend and Operational Matters
### Frontend and Backend
1. The organization information modification feature has been deployed and is effective after testing.
2. The display format of Domain Persona has been updated, with text prompts displayed as pop-ups, scheduled for release this week.
3. The three-dimensional evaluation system diagram on the project report page now remains consistent with the homepage when in full-screen mode.
4. Compass badges are awaiting updates.
   - **AP: Xingyou Lai communicates with Feng Zhong for redesigning the badges.**
5. Compass proxy updates are currently under stable testing, and further observation will continue.
6. Some backend bugs have been fixed.
7. Currently, intervals and limits on access times have been set for Compass data access permissions. It is suggested the limit can be adjusted to 1000 times per hour.
   - **AP: Huatian Qin makes adjustments and handles the deployment as soon as possible.**
### Operations
1. Compass Data Usage Agreement to be drafted by the end of this week.
   - **AP: Shengxiang Zhang completes it as soon as possible.**
2. Tweets regarding the organization information modification feature and domain persona updates to be published later this week.
   - **AP: Ran Zhou completes and publishes the content as soon as possible.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-1-23 Weekly Meeting Minutes of OSS Compass Community
## Time
January 23, 2024, from 14:15 to 14:53 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Feng Zhong](https://github.com/poorfish), [Xingyou Lai](https://github.com/coder-sett), [Huatian Qin](https://github.com/EdmondFrank), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi), Tiandong Liu - Kaiyuanshe
## Topic - Progress Discussion on Compass Frontend and Backend and Operational Matters
### Frontend and Backend
1. Project Deep Dive Insight Solution:
    - The frontend work for downloading contributor persona details table functionality is completed and in the grayscale phase. The table content is currently in English, and translation to Chinese will not be provided until users demand it. This feature should be live by the end of the month.
    - Domain persona tag colors have been modified for better differentiation, displaying different categories of the tags in rows. To avoid information overload,  it is suggested to hide the details and only show 5 major categories of the tags. And categories with more contributions are marked for each contribulor.
        - **AP: Feng Zhong redesigns the display style, and Xingyou Lai modifies the frontend.**
    - Colors for contributor distribution and frequency distribution pie charts have been adjusted. The four types of the role persona above the frequency distribution chart are currently arranged by contributor quantity, and they need to be rearranged alphabetically.
        - **AP: Xingyou Lai makes adjustment promptly.**
    - Data interface for supporting the organization information modification is in progress. Modification through the Project Deep Dive Insight Solution page needs to include prompts and icons in a popup format for filling in the dates.
        - **AP: Shengbao Li and Huatian Qin quickly integrate model data, Huatian Qin provides remaining interfaces promptly, and Xingyou Lai adjusts the frontend promptly. Ensure this feature goes live by the end of the month.**
    - Bug of displaying incomplete project evaluation data within the last year is still being addressed.
        - **AP: Huatian Qin and Shengbao Li identify the cause and fix it ASAP.**
    - The organization information currently provided is in English. Naming rules of organization information need to be established for user-input.
        - **AP: Huatian Qin and Shengbao Li discuss and confirm the rules.**
2. Compass Data API Retrieval Mechanism: Access logs need reviewing for the design of limit mechanism for access by token.
    - **AP: Huatian Qin handles related matters promptly.**
### Operations
1. Community report of 2023 should be released this week.
    - **AP: Ran Zhou optimizes the content and proceeds the publishing promptly. Board members' approval are needed before publication.**
2. Compass data usage process was confirmed OK, awaiting supplementary terms, to be completed before the Spring Festival.
    - **AP: Shengxiang Zhang supplements the terms promptly, and Ran Zhou communicates with the relevant user.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-1-16 Weekly Meeting Minutes of OSS Compass Community
## Time
January 16, 2024, from 14:15 to 14:42 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Wenxuan Long](https://github.com/hncslwx), [Xingyou Lai](https://github.com/coder-sett), [Huatian Qin](https://github.com/EdmondFrank), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi), Daniel Izquierdo - Bitergia
## Topic - Progress Discussion on Compass Frontend and Backend and Operational Matters
### Frontend and Backend
1. The color of domain tags in the contributor persona details page needs to be optimized.
   - **Action Point (AP): Xingyou Lai should coordinate with Feng Zhong and Shengxiang Zhang for verification and make the necessary modifications as soon as possible.**
2. The URL for downloading the table in the contributor persona details page becomes quite long when additional table parameters are appended. This may cause issues when using it in WeChat. It is suggested to maintain the current solution and assess its effectiveness during usage. Any problems can be addressed later.
   - **AP: Xingyou Lai should create an issue first and follow up accordingly.**
3. The interface for downloading the table in the contributor persona details page needs to be restructured to support the download. The backend interface has been completed and awaits frontend verification.
   - **AP: Xingyou Lai should coordinate with Huatian Qin for verification as soon as possible.**
4. The backend development testing for the Project Deep Dive Insight Solution, which allows administrators and developers to modify organization information, has been completed and is ready for deployment.
   - **AP: Huatian Qin should deploy it as soon as possible.**
5. The processing of the CNCF contributor organization information list is still ongoing.
   - **AP: Shengbao Li and Huatian Qin should complete this task within this month.**
6. The interface for personal modification of organization information has been completed. The process and format for administrators or third parties to submit pull requests to modify organization information need further refinement.
   - **AP: Shengbao Li should confirm the process and format.**
7. Progress on formulating the mechanism for accessing Compass data APIs: Communication is needed with the operations team and service providers to obtain the real IP addresses.
   - **AP: Huatian Qin should expedite progress on this matter.**
### Operations
1. Publish the 2023 annual report this week.
   - **AP: Ran Zhou should finalize the content as soon as possible, and Yehui Wang will review and provide modifications if necessary.**
2. The data usage process for Compass：
   - **AP: Shengxiang Zhang should review the draft and provide feedbacks as soon as possible.**
3. Plan a live talk show after the Spring Festival about open source evaluation, featuring Daniel Izquierdo and Wang Yehui as key speakers.
   - **AP: Yehui Wang should confirm the schedule and specific topic with Daniel. Ran Zhou will handle the planning.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-1-9 Weekly Meeting Minutes of OSS Compass Community
## Time
January 9, 2024, from 14:15 to 15:01 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Wenxuan Long](https://github.com/hncslwx), [Feng Zhong](https://github.com/poorfish), [Xingyou Lai](https://github.com/coder-sett), [Huatian Qin](https://github.com/EdmondFrank), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), Liang Wang, Liwen Zhang
## Topic - Progress Discussion on Compass Frontend and Backend and Operational Matters
### Frontend and Backend
1. In the Project Deep Dive Insight Solution page, optimization was made for the filtering of contributor persona and distribution details, requiring further text adjustments.
   - **AP: Xingyou Lai continues optimizing the text.**
2. OSS Compass now supports clicking URLs to redirect to repositories or official websites for open source projects submitted as communities.
3. The "Is Maintained" metrics model chart has been changed to a line graph.
4. The Project Deep Dive Insight Solution needs to support contributor organization information modifying, and the frontend and backend work can be started:
   - Open source project administrators are allowed to modify contributor organization information in the Project Deep Dive Insight Solution page, and contributors are allowed to modify organization information in their personal account setting pages.
   - The above modifications should be done through submitting pull requests (PRs).
   - In case of conflicting information, the information submitted by the contributors take precedence.
   - Changes to organization information take effect immediately and the model data is updated periodically.
   - The dates in the organization information need to be precise (day, month, year).
   - If a contributor has multiple roles or belongs to multiple organizations, they can only select one role at a time, either as an individual contributor or belonging to a specific organization.
   - Create a separate file in the repository for each project to record contributor organization information.
   - Organization information should allow both modifications and additions, with options for manual input and direct selection, along with a predefined list of organization names for selecting during modification.
   - Currently, contributor information is not publicly available.
   - **AP: Shengbao Li and Huatian Qin update the backend, Xingyou Lai modifies the frontend, and Feng Zhong designs the display form of user operations entry.**
5. Progress on displaying the text "Statistics in progress" for models without data in the three-dimensional evaluation system on Gitee needs to be pushed forward.
   - **AP: Shengxiang Zhang expedites the related updates.**
6. The parsed information of nearly 50,000 contributors maintained by CNCF is being applied to Compass and updated monthly.
   - If there are conflicts between the parsed data and existing Compass data, user-submitted modifications take precedence.
   - **AP: Shengbao Li clearly indicates the priority of data extraction in the relevant documentation.**
7. Data API acquisition mechanism for Compass:
   - Currently, basic data can be obtained directly by parsing the webpage through the API with a set limit on the number of requests.
   - Core data APIs require token-based authentication.
   - **AP: Huatian Qin and Shengbao Li configure the backend settings.**
### Operations
1. Bilibili account has been created, and WeChat Official Account verification is completed.
2. The process of using Compass data has been finalized. It is necessary to promptly review the process details and check with the foreign university researcher who has recently requested to use Compass data.
   - **AP: Shengxiang Zhang reviews the process, and provides comments. Ran Zhou communicates with the relevant requestor as soon as modifications are complete.**
3. After the completion of the update for organization information modificationin in the Project Deep Dive Insight Solution page, an article will be written for promotion.
   - **AP: Ran Zhou handles the writing and publishing when ready.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

# 2024-1-2 Weekly Meeting Minutes of OSS Compass Community
## Time
January 2, 2024, from 14:15 to 14:44 (Beijing Time)
## Attendees
[Yehui Wang](https://github.com/eyehwan), [Shengxiang Zhang](https://github.com/normal-coder), [Xingyou Lai](https://github.com/coder-sett), [Huatian Qin](https://github.com/EdmondFrank), [Shengbao Li](https://github.com/lishengbao), [Ran Zhou](https://github.com/JuliaZhou2022), [Guoqiang Qi](https://github.com/guoqiangqi), Xiaoming Li - Kaiyuanshe
## Topic - Progress Discussion on Compass Frontend and Backend and Operational Matters
### Frontend and Backend
1. Two new cases from Nanjing University have been added, and already deployed in Compass Collaboration.
2. Fixed spelling errors and bugs on the report page.
3. News page needs updates for recent videos and articles.
   - **AP: Ran Zhou provides contents, Xingyou Lai updates them on the official website.**
4. Recent model optimizations have been deployed to production; results will be compiled after running all data. Based on the current situation, an estimated additional month is needed.
    - **AP: Huatian Qin runs data and compiles results as soon as possible.**
5. Some repository data collection tokens are blocked; the cause needs investigation.
    - **AP: Shengxiang Zhang addresses such issue promptly.**
6. Forked repositories without development activity can be deleted.
    - **AP: Shengxiang Zhang and Huatian Qin confirm and handle this matter.**
### Operations
1. Compass data usage process:
   - Processes for commercial companies and academic research need differentiation.
       - **AP: Ran Zhou quickly drafts relevant processes for team discussion and revision.**
   - The authorized entity is OSCHINA, and the authorization is for the use of the APIs of the data processed by OSS Compass from public channels such as Gitee and Github. Personal information like account IDs and emails will not be provided. A document for authorized use needs to be signed, specifying that this data cannot be used for other purposes.
      - **AP: Ran Zhou drafts the authorization document; Yehui Wang and Shengxiang Zhang conduct initial review.**
   - Processes and authorization documents need legal review; OSCHINA is responsible for final usage.
      - **AP: Yehui Wang seeks a lawyer to review the relevant documents.**
2. WeChat public account authentication, and Bilibili account creation.
   - **AP: Shengxiang Zhang handles these matters promptly.**
3. OSS Compass will be promoted on the Gitee platform in the near future.
   - **AP: Yehui Wang and Ran Zhou provide relevant support.**
## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

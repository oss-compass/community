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


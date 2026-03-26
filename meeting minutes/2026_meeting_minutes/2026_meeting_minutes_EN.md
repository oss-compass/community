# 2026-03-24 Weekly Meeting Minutes of OSS Compass Community
## Time
March 24 2026, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang， Zhu Jiashun, Dai Ruiqi, Wang Lei, Ran Fengyuan, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
## Meeting Minutes
### I. Discussion on Progress of Agent Evaluation Report Generation
Regarding the generation of evaluation reports for the Developer Experience Agent, Dai Ruiqi and Zhu Jiashun updated each other on the optimization and verification status of the current process. Concerning the report content and formatting specifications, Dai Ruiqi simplified the scoring criteria and controlled the output content. The generation logic was adjusted to only output analysis, improvement suggestions, key issue diagnosis, and radar charts after all submissions are completed, avoiding redundant information in intermediate steps.
### II. Progress of Other Modules
For the PR information flow reconstruction, Wang Lei adjusted the PR filtering logic to prioritize PRs with high comment volumes. He redesigned the information flow filtering rules for the comment section, removing irrelevant information through regular expression matching and other methods to save Tokens and improve model processing efficiency.
### III. Introduction of the New Evaluation Report Template
Qi Guoqiang introduced the design concept and structural optimization of the new version of the evaluation report template. Minor adjustments were made to the structural hierarchy, with a new chapter on "Developer Journey" to be added. By visualizing the developer's action flow during evaluation, the assessment results, deficiencies, and advantages are intuitively displayed. Improvement suggestions are moved forward from the end of the report to facilitate quick problem location. The original standardized learning content is retained to ensure the professionalism and continuity of the report.
### IV.  Outstanding Issues
●Regenerate a complete evaluation report based on the new report template.(Completion Date: March 27, 2026; Person in Charge: Dai Ruiqi)

# 2026-03-17 Weekly Meeting Minutes of OSS Compass Community
## Time
March 17 2026, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang， Zhu Jiashun, Dai Ruiqi, Wang Lei, Ran Fengyuan, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin 
## Meeting Minutes
### I. Discussion on Agent Evaluation Report Template and Issue Submission Process (Dai Ruiqi)
Discussions were held on report generation issues, and the principles for generating the Agent automatic evaluation report template were clarified. Regarding the frequent errors in reading web page content via browser automation, it is recommended to prioritize data retrieval through API to improve stability. For detailed functions that cannot be realized via API， they can be ignored temporarily.
For locating the issue contribution guide, it is clarified that the requirement is deemed satisfied as long as instructions for submitting issues can be found in the project README file; a separate CONTRIBUTING file is not mandatory. The check for the "Code of Conduct" will not be implemented at the current stage and may be added in subsequent iterations.
### II. Discuss Progress on Automatic Analysis of PR Contribution Process (Wang Lei)
Wang Lei is conducting automatic analysis of the PR processing workflow, attempting to extract events, stages, timestamps and other information from PRs for statistical analysis. It is recommended to adjust the PR sampling strategy to obtain more valuable information.
In the follow-up work, Wang Lei will focus on the analysis of the PR process, and the final evaluation report generation template will be shared with Dai Ruiqi’s deliverables. A relatively complete report generation process is planned to be demonstrated in the subsequent presentation.
### III. Discussion on Environment Deployment and NPU Adaptation (Ran Fengyuan)
Ran Fengyuan stated that the containerized deployment and testing of basic functions have been successfully completed in both GPU and CPU environments. However, issues were encountered when running Docker containers on NPU servers; the error may be related to inconsistent file permission mapping inside and outside the container.Qi Guoqiang suggested checking and adjusting the **other** permissions of the files, granting at least read and execute permissions.
### IV. Outstanding Issues
●Complete the generation and debugging of the Issue report template, and deliver a complete report including the Agent execution path.（Person in charge: Dai Ruiqi; Deadline: March 24, 2026）

●Generate a relatively complete report based on the latest PR data and prepare the Demo.（Person in charge: Wang Lei; Deadline: March 20, 2026）

# 2026-03-10 Weekly Meeting Minutes of OSS Compass Community
## Time
March 10 2026, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang， Zhu Jiashun, Dai Ruiqi, Wang Lei, Ran Fengyuan, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
## Meeting Minutes
### I. Discussion on Server Connection and Report Generation (Zhu Jiashun, Dai Ruiqi)
Issues related to server connection and code submission workflow were discussed. The Remote SSH feature in VS Code cannot be used directly as TCP forwarding permissions are disabled; development is currently conducted via the command line or Web IDE. Qi Guoqiang will apply for the relevant permissions. For report generation and data transmission, Wang Yehui proposed using Pydantic for strong type constraints, standardizing field descriptions to ensure stable output formats.
### II. Discussion on PR Submission Workflow (Wang Lei)
The PR submission process and Agent role definition were reviewed. Wang Yehui emphasized that the Agent should serve as an auxiliary tool in the PR workflow. For code changes or complex decisions, manual confirmation is mandatory, with humans determining whether to submit and the specific modifications. Technical challenges of code revision and log retrieval were discussed; Wang Lei suggested AI-assisted code modification, while Wang Yehui recommended limiting AI use to confirmatory changes, with complex revisions requiring manual intervention.
### III. Discussion on Sandbox Environment Testing and Authentication (Ran Fengyuan)
Sandbox environment and authentication issues were addressed. Ran Fengyuan tested the AIO Sandbox, but Qi Guoqiang noted its lack of customizability and recommended referencing the OpenClaw implementation for environment orchestration and task scheduling via Docker, along with email verification for CLA signing. For CRA signing, Wang Yehui suggested using real email addresses for simulation to avoid verification issues caused by disposable emails.
### IV. Outstanding Issues
●Implement human intervention logic in the Agent.Owner: Dai Ruiqi, Zhu Jiashun; Deadline: March 13, 2026

●Prepare demo for Friday’s meeting.Owner: Wang Lei; Deadline: March 13, 2026

# 2026-01-27 Weekly Meeting Minutes of OSS Compass Community
## Time
January 27 2026, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang， Zhu Jiashun, Dai Ruiqi, Wang Lei, Ran Fengyuan, Wangchangjin，Jiayunxiang，Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
### I. Discussion on the Progress of the Project for Optimizing Open Source Community Experience Capabilities (Zhu Jiashun, Dai Ruiqi, Ran Fengyuan)
Qi Guoqiang introduced the project background, highlighted the importance of open source community experience, emphasized the limitations of traditional questionnaires, and mentioned the use of large models to process unstructured content and automated methods to improve the effectiveness of community experience analysis.

Zhu Jiashun reported on the current progress, noting that issues with the sandbox execution environment were affecting code operation and that a resolution was planned for the coming days. Qi Guoqiang proposed prioritizing the resolution of the environment issues and suggested that Fengyuan’s team check the feasibility of providing solutions. Regarding task arrangements, Qi Guoqiang stated that upon resolving the execution-related issues, the pre-planned tasks would be basically completed; for the division of new subsequent tasks, he hoped that Ruiqi and Fengyuan would join the project.

Wang Yehui provided a further introduction to the new project and suggested holding a weekly meeting starting this week to track project progress and resolve problems. He required the prompt verification of the prototype design and the generation of relevant merit diagrams to demonstrate the interaction logic of each node. Subsequently, Zhu Jiashun would be responsible for sorting out the relevant source code and leading other team members to join the project.

The participants also discussed the status of technical research and environment construction, as well as the progress of the community virtual assistant project. Qi Guoqiang pointed out that the customizability of the environment and the information transmission process were key considerations and suggested an in-depth study of these two aspects. Wang Yehui held that the research on the sandbox environment and task execution should be carried out simultaneously and recommended completing the testing of a full case within this week.
### II. Discussion on the Progress of the Libyear Project (Li Songnan, Dai Ruiqi)
Dai Ruiqi reported on the current progress,n the current progress: the task of running all historical versions was underway, expected to be fully completed within this week, with the current accuracy rate standing at approximately 70%. For this task, Wang Yehui suggested conducting a public demonstration next week after receiving feedback from Professor Liang to ensure project quality.
### III. Pending Issues
Design workflows for typical scenarios to support the team in running prototypes and solving practical problems.(Owner: Zhu Jiashun; Deadline: January 30, 2026)

# 2026-01-20 Weekly Meeting Minutes of OSS Compass Community
## Time
January 20 2026, 19:00-20:00 PM Beijing time
## Attendees
Qi Guoqiang, Zhang Shengxiang, Zhu Jiashun, Dai Ruiqi, Wang Lei, Ran Fengyuan, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
### I. Progress Report on Libyear Project & Open Source Summer Internship (Zhu Jiashun, Dai Ruiqi, Ran Fengyuan)
The team discussed the environment construction of Agent and Chain of Thought (COT), as well as the chatDEV project. Ran Fengyuan pointed out that the chatDEV project is associated with programming and corresponding program design. Qi Guoqiang mentioned the application of containers and Kubernetes (K8s) in environment construction, and suggested referring to relevant projects.

Zhu Jiashun and Dai Ruiqi respectively reported the progress of the projects under their charge and put forward the problems encountered. The team deliberated on anti-crawling strategies and corresponding solutions for web crawlers. Qi Guoqiang advised optimizing the crawler strategy, paying close attention to account suspension logic, and avoiding anti-crawling peak periods as much as possible.
### II.  Progress of Technical Classification Project (Wang Lei)
Wang Lei presented the findings of paper research on developer evaluation, and the group discussed the community matching algorithm, code quality assessment and modeling. Qi Guoqiang proposed the need to introduce code importance modeling into programming capability and technical influence evaluation.
### III. Discussion on Community Operations (Zhang Shengxiang)
The discussion focused on the development trends of AI and Agent, as well as the traffic-driven nature of the Agent network. Zhang Shengxiang introduced the mechanism of remote Agent invocation, and noted that recent research has been divided into two directions: model enhancement capability and Agent orchestration. At present, most research remains at the framework and theoretical level, and specific applications are not yet mature. Qi Guoqiang expressed the hope for continuous communication and knowledge sharing in subsequent work.

# 2026-01-06 Weekly Meeting Minutes of OSS Compass Community
## Time
January 6 2026, 19:00-20:00 PM Beijing time
## Attendees
Wang Yehui, Qi Guoqiang， Zhu Jiashun, Dai Ruiqi, Wang Lei, Ran Fengyuan, Li Shengbao, Lai Xingyou, Li Songnan, Li Chunmin
### I. Progress Report on the Libyear Project & Open Source Summer Internship (Zhu Jiashun, Dai Ruiqi, Ran Fengyuan)
Discussions were held on issues related to software package upstream addresses, source code address resolution, and community ecosystem health assessment. Relevant personnel suggested leveraging expert experience for judgment to enhance credibility; introducing an automatic blacklist mechanism to skip entities with repeated failures, thereby improving crawler stability; and refining reasoning scripts while integrating large model APIs to boost judgment accuracy. It was agreed that an initial demo version would be released by late January or early February, with all participants expected to advance work in accordance with the schedule.

Updates were provided on the current multi-round dialogue and context management mechanism, Agent system design, report generation and template design, among other aspects. Qi Guoqiang proposed that statistics should be collected on the frequency of use and success rate of the Agent to facilitate performance optimization.

Deliberations covered API restructuring and data calculation, definition of community health dimensions, application of models and Agents, and design of data analysis pipelines. Wang Yehui introduced the main services and product roadmap of OSS Compass, emphasizing the need for consistency in model definitions and calculation methods to align with the OSS Compass evaluation system. He suggested using Agents to expand the scope and scenarios of model application, thereby continuously optimizing and verifying model effectiveness.
### II. Progress on the Technology Classification Project (Li Shengbao)
A progress update on technology classification was delivered. To date, over 5 million projects have been analyzed, with further analysis underway. Qi Guoqiang pointed out that intermediate results should be reviewed on a regular basis and planned to explore deeper insights through multi-round interactions. Regarding the paid nature of the Google Search API, he stated that a decision on its adoption would be made after cost evaluation.
### III. Discussion on Community Gifts (Li Chunmin)
Discussions centered on the selection of relevant gifts and the scale of distribution. Follow-up work will be continued, with feedback provided in a timely manner.
### IV. Outstanding Issues
Collect statistics on the frequency of use and success rate of the Agent.(Responsible Person: Zhu Jiashun；Completion Date: January 13, 2026)
### IV. Outstanding Issues
None.

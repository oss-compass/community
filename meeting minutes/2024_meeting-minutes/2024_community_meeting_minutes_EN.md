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

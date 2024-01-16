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

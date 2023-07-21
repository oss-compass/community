# 2023-07-20 Open Source Compass Lab Meeting Minutes

## Time
July 20, 2023, 14:15 to 15:30 (Beijing Time)

## Attendees
Yehui Wang, Shengxiang Zhang, Chaoqun Huang, Xingyou Lai, Huatian Qin, Shengbao Li, Feng Zhong, Wenxuan Long, Guoqiang Qi, Wenhao Yang, Ruiqiao Qiu, Ran Zhou

## Topic - Compass Lab Frontend and Backend Design and Operation Planning

### 1. Adding Issue Template to Github Repository
Requesting Compass Lab access permission by submitting an application through the Community project using Issue, **AP: Feng Zhong designs the Issue template**.

### 2. Lab Frontend Design
- (1) The pages under Lab have been mostly designed already.
- (2) Model Page
  - Display style: The model page is presented in the form of cards.
  - Difference between creating a new version and global editing: Creating a new version involves basic configurations (ecosystem dimension, model name, industry attributes, public visibility, selected dataset), while global editing under the three dots in the top right corner is used to edit specific parameters of the model, such as metrics and algorithms.
  - Selected datasets are shown in card format, while editing datasets appears as a popup.
  - Indicate the metrics from CHAOSS.
  - Change "Submit" on the new model page to "Save" or "Confirm," **AP: Feng and Shengxiang to confirm**.
  - Weight and threshold settings: Displayed in table format with draggable sliders to adjust. The default values for thresholds should be set with text prompts, specifying that some are absolute values while others are proportional values, with a range from 0 to 100 or 0 to 100%.
  - Algorithm selection: The default algorithm's formula should be displayed, and it's suggested to be included in a link for reference.
  - Remove the border of the model page and use colored blocks instead.
- (3) Adding Collaborative Users for Models
Invite users proactively or accept user applications passively. Account setup should be based on email, and users should be prompted to create a Compass Lab account, guiding them to the community for communication.
- (4) Dashboard Page
  - When first opened, the discussion area should be displayed by default, and users can close it if they prefer.
  - Charts - Y-axis scaling function, **AP: Chaoqun revises the wording, Xingyou works on the backend, and Zhou Ran writes and pushs the tweet next week. Feng should remove the explanatory text below the indicators**.
- (5) Frontend and Backend Design in Sync
**AP: Hua Tian and Xingyou collaborate on the tasks after discussing the details**.

### 3. Backend
**AP: Hua Tian modifies the backend code based on frontend improvement suggestions; Shengbao starts splitting metrics from existing metrics model and forms new metrics sets next week.**

### 4. Operation
  - (1) WeChat official account Platform and Twiteer Tweet Cover Design
    - Zhou Ran has submitted the requirements and created tasks, **AP: Zhong Feng completes the design work this week**.
  - (2) How to Display Community Updates on the Official Website
    - **AP: Zhou Ran organizes the content of community updates to be displayed on the official website, and discusses with Feng on how to present it before the next meeting.**
    
# 2023-07-18 Weekly Meeting Minutes of OSS Compass

## Time
2023.07.18, 14:15pm~15:30pm, Local Time, Beijing

## Participant
Yehui Wang, Shengxiang Zhang, Chaoqun Huang, Xingyou Lai, Huatian Qin, Shengbao Li, Feng Zhong, Wenxuan Long, Guoqiang Qi, Wenhao Yang, Ruiqiao Qiu, Ran Zhou

## Topics
Compass Lab Frontend and Backend Design Discussion and Planning

### Backend
- (1) High-Level Design: Separate storage of user-customized model analysis report data from existing report content.
- (2) Numbers of datasets and metrics selected by users should be controlled, and selection by project is recommended with some categorization set.
- (3) Users are not allowed to submit data that has not been processed by our model; they must create a new project.
- (4) Versioning Design: Default timestamp or user selection; versions are mapped to models.
- (5) The comment section defaults to the current version, with an option to switch to all versions.
- (6) The official website will be hosted in China and should undergo sensitive word scanning in comments - **Action Point: Yehui Wang and Shengxiang Zhang will continue to discuss how to resolve this.**
- (7) User-defined metrics require disassembling all the metrics from the metric model, creating a new metric set, and adding the disassembled metrics one by one. Mapping is needed for the disassembled metrics and indexes. - **Action Point: Shengbao Li and Huatian Qin will further discuss and refine this process, clarifying the required time and how to interact with OpenSearch. All discussions about this matter should be taken place in the WeChat PKU communication group.**
- (8) Only after the duration of the metric disassembly process is determined, can we know if the business logic can be arranged synchronously with metric disassembly or not.
- (9) Backend development work should be started from today.

### Frontend
- (1) The blog section has been incorporated into the community section on the homepage of OSS Compass website.
- (2) How to display community updates - **Action Point: Ran Zhou will plan community operation content, and we will discuss how to present it in the next meeting.**
- (3) Community users want to embed a specific chart into their web page. **Conclusion: After running each report, generate a static URL for the report's chart to embed it as an image. Provide the charts generated within six months.**

### Conflicts in Compass Subcategory Names
When there is a conflict between submitted and existing categories, modify the existing category name through a pull request, continuously absorbing and merging the subcategory names to reduce technical debt.

## Kanban tracking
https://github.com/orgs/oss-compass/projects/1

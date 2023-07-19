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

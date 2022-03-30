# QER
## The Quality of Experience Report (QER) Power BI template for CQD has two primary functions

1.  Empower organizations to proactively identify issues that are impacting the Teams meeting and calling expierence. 
2.  Enable organizations to respond quickly to escalating issues and help answer the question, "What happened during the meeting?" 

The template was created as the output from hundereds of customer workshops across multiple years of effort.  The template is a community driven project and is constantly evolving due to feedback and improvements in Microsoft telemetry.  New ideas and insights are incorporated and an updated template is released once a quarter.

### Contents
1. **QERPBI.zip** - The QER Power BI teamplate. Includes relase notes and installation instructions (.docx), Microsoft Call Quality Connector (.pqx), and the template (.pbit)
3. **CQD-BuildingData.xlsx** - A template to help organizations create a [CQD Building Data file](https://docs.microsoft.com/microsoftteams/cqd-upload-tenant-building-data).
4. **CQD-EndpointData.xlsx** - A template to help organizations create a [CQD Endpoint Data file](https://docs.microsoft.com/microsoftteams/cqd-upload-tenant-building-data#endpoint-data-file).
5. **CQD-Teamplate-Rolling-Reports.zip** - A collection of templates for the CQD web UI. (legacy)
6. **QER-CQDv3-Templates.zip** - A collection of QER templates for the CQD web UI. (legacy, commercial tenants only)

### Requirements
1. Power BI Desktop - Download through [Windows Store](https://aka.ms/pbidesktopstore) or [Microsoft Downloads](https://aka.ms/pbiSingleInstaller).
2. Microsoft Power BI Connector for CQD - Included with template download (.pqx)

### Reference Material
* [Using Power BI to analyze CQD data](https://docs.microsoft.com/microsoftteams/cqd-power-bi-query-templates)
* [Microsoft Power BI Connector for CQD](https://docs.microsoft.com/microsoftteams/cqd-power-bi-connector)

### This template provides the following reports

* Search – enables searching by Meeting URL, Conference ID, Subnet, or UPN.
* Meeting Health Details – detailed metrics for a single meeting.
* User Health Details – detailed metrics for a single user.
* Media Health – high level overview of Key Health Indicators (KHI) for overall tenant meeting and calling health.
* Media Setup – analyze media setup failures.
* Media Reliablity – analyze media reliability issues.
* Audio/Video/Sharing Health – review mid-level KHIs for audio, video, or sharing health.
* Audio/Video/Sharing Health Details – review detailed metrics on audio, video, or sharing health.
* VPN – review the impact of VPN on meeting health. (Estimated or Mapped VPN)
* Top 10 Reports – identify areas of impact in your tenant health.
* Dailies – review daily report of KHIs.
* Usage – general meeting and calling usage.
* User Feedback – review user survey feedback, also known as Rate My Call.
* Transport – identify networks that are blocking UDP.
* Devices – review the impact of devices.
* Clients - review client focused metrics.
* Building Data – review the building data file in CQD.
* PSTN Health and User Details – two reports that provide a high level summary as well as individual user health for PSTN based calls.
* Network Metrics – two reports that display raw network metric details for jitter, packet loss, and latency. 

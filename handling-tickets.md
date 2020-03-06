---
layout: wso2-theme-toc
title: Handling Tickets
permalink: /handling-tickets/
---

##  Getting a Ticket

Check if you have already assigned tickets from the JIRA filter [My open issues](https://support.wso2.com/jira/issues/?filter=-1).

If there are no tickets assigned for you, Check on the jira dashboards for Open, Reopen and Waiting On WSO2 (WOW) tickets using the following dashboards.

- [Incident dashboard](https://support.wso2.com/jira/secure/Dashboard.jspa?selectPageId=12896)
- [Overall ticket Dashboard](https://support.wso2.com/jira/secure/Dashboard.jspa?selectPageId=13461)

If you still could not find a ticket please escalate to the support lead.

**Note** :

Please **Do not** pre-book issues. Take it up only if you can work on it NOW.

Give priority to incidents and escalated tickets.

**Do not** In-Progress multiple tickets, if you cannot parallelly work on them.

***

##  Working on the Ticket

**Preliminary work**

When you are ready to work on the ticket please make sure it is assigned to you. Then the ticket status must be changed to In-Progress.

Add the necessary tags to the ticket if it&#39;s not already added.

Tag to identify the product related to this ticket

- **APIM** (apim)
- **IAM** (iam)
- **EI** (ei)
- **OB** (ob)
- **Analytics** or **DAS** (analytics)

Every **incident** should be **acknowledged immediately** and every **query** should be **acknowledged** before **24 hours**

**Understanding the ticket**

- Read the ticket thoroughly and understand the real issue of the ticket. Try to figure out whether there are any XY problems.
- Fully concentrate on the ticket that you are currently working on.
- If you need more context to understand the ticket, use the following resources.
    - Get customer details using [CIP](https://identity-gateway.cloud.wso2.com/t/wso2internal928/wso2cip/)
    - Get details from the previous tickets of the project
    - Search keywords in [WSO2 Group Mail](https://groups.google.com/a/wso2.com/forum/?hl=en#!overview)
    - Search keywords in [support jira portal](https://support.wso2.com/jira/issues/?filter=-1&amp;jql=project%20%20%3D%20%22ProjectName%22%20AND%20text%20~%20%22KeyWord%22%20order%20by%20updated%20DESC)
    - Search keywords in the Knowledge Base (still in-progress)
    - Get the architecture details from [SA drive.](https://drive.google.com/drive/folders/0B5o8DTpT8DFCfjlCYnliTFZtS3VJNjdZLUNINWVOd21tSXk0aG5zM0RXbGVaSlUyRmxMV0k)
    - Get Patch details from [PMT](https://supporttools.wso2.com/pmtapp/pages/advance-search.jag)
    - Google it (Make sure you are using the WSO2 account when searching)

- If the ticket description is still not clear enough to understand the ticket, Escalate to it to your support lead or senior person in your team.

**Analyze the Ticket**

- Properly analyze the details you have gathered.
- Think twice when you try to reproduce an issue and decide whether it&#39;s necessary.
- As the owner of the ticket you must have a clear idea on the problem and possible options to overcome it. Only the best possible option needs to be proposed to the customer in most cases.
- If you are working on a critical incident where the customer system is down, make sure to restore the system even with a workaround first to prevent business loss to the customer.

**Answering the Ticket**

- Keep the customer informed regularly and keep in mind about the [SLA](https://sites.google.com/wso2.com/tempwso2site/home/sla?authuser=0).
- Always help the customer to overcome their issues permanently and try to prevent it from happening again. Always keep in mind about the [Support Sustainability](https://sites.google.com/wso2.com/tempwso2site/home/support-sustainability?authuser=0) aspects. If you are unable to come to conclusions please escalate to the lead well before any SLA violations.
- Keep the customer informed always and meet the [internal status update SLA](https://docs.google.com/spreadsheets/d/1l77_7yEG-5BvnuhDnNPcUNJ_NrV_FWTSVJ2MgbRbiTI/).
- Provide useful updates to the customer by adhering to the [Response template](https://sites.google.com/wso2.com/tempwso2site/home/support-process/response-template?authuser=0).
- Also pay attention to the below.

**DO**

- Short sentences
- No Essays, use bullet points, clear instructions and short paragraphs
- Be Precise
- Clear instructions on getting what you need from the customer (logs, config files, steps to reproduce)
- List all assumptions

**DON&#39;T**

- Putting comments that do not add value

e.g. Don&#39;t just say I cannot reproduce – give the steps you tried to reproduce

- Being unprofessional
- Saying things like I hope this works

- When you comment in JIRA use &#39;Text&#39; option rather than &#39;Visual&#39; option. This may help to reduce unnecessary line breaks.
- See [JIRA options](https://jira.atlassian.com/secure/WikiRendererHelpAction.jspa?section=advanced) on creating appealing comments and use them only to improve readability.

**IMPORTANT:**

When you are new to support, put comments as &#39;Developer only&#39; and get it verified by support lead before making it visible to the customer until you are familiar with the support protocol.

Once you have answered the ticket make sure to change the ticket status to Waiting On Client (WOC).

**Customer Calls**

- Pick up the phone if it feels easier to do so, especially if you are unable to reproduce. Also for urgent and critical incidents.
- Schedule for 15 mins to 30 mins.
- Put the call invitation to the ticket by mentioning the scheduled time with timezone.
- Make sure you join the meeting at least 5 minutes before the scheduled start time to ensure you are logged in when the customer joins. Please do not wait till the last minute to join the meeting, it gives a very bad impression to the customer.
- Do NOT pull more than 2 into the call.
- After the call put the call notes along with the attendees to the ticket. Please see the [Call Notes Template](https://sites.google.com/wso2.com/tempwso2site/home/support-process/call-notes-template?authuser=0).
- Report ALL time spent on the call.

**Time Reporting**

- Please refer [Time reporting guidelines](https://sites.google.com/wso2.com/tempwso2site/home/support-process/reporting-time?authuser=0).
- End of the day, make sure to report all the time logs to [PMT](https://supporttools.wso2.com/pmtapp).
- Once it is provided with a workaround to an incident, the incident must be tagged with WOCW (Waiting On Client Workaround).
- Own the ticket for its lifetime to improve the response quality and to avoid the context switching.

***

## Closing the Ticket

It is important to follow the[Post Resolution Activities (PRA)](https://sites.google.com/wso2.com/tempwso2site/home/support-process/post-resolution-activity?authuser=0) to resolve the support ticket. Following are the main two links to follow on the resolution process

1. [Resolution flowchart](https://drive.google.com/file/d/19E2ZKvJ5hzKSWETzmEUk7pvbGSAGBATQ/)
2. [PRA View in PMT](https://supporttools.wso2.com/pmtapp/pages/pra_view/main_view.jag)

***

## Getting your feedback

- Please view your weekly performance based ratings through[PMT](https://supporttools.wso2.com/pmtapp/pages/evaluation/evaluation_developer_view.jag) and identify any plus points and improvement points. If you are in doubt, please talk to the respective lead and clarify.
- It is really important to spend some time going through these feedbacks and identify any improvement points as needed. Please discuss with your support team leads if you are unclear about the feedback.
- Your performance will be evaluated through the guidelines[listed here](https://docs.google.com/spreadsheets/d/18cAJomjBTM8iRS3Iq0lchF6hDl9QVVB4E9L-FNDgfPo/edit#gid=1403325901).
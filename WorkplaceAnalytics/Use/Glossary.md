---
# Metadata Sample
# required metadata

title: Workplace Analytics Glossary
description: This glossary defines concepts and other terms important for working with Workplace Analytics.
author: madehmer
ms.author: v-midehm
ms.date: 06/15/2018
ms.topic: get-started-article
localization_priority: normal 
ms.prod: wpa
---

# Glossary for Workplace Analytics

This glossary defines concepts and other terms (excluding [query metric definitions](../use/Metric-definitions.md)) used when working with Workplace Analytics.

|Term|Definition|
|----|----------|
|Adjusted meeting hours|An adjustment is applied so that overlapping time is not double-counted when a person has overlapping meeting hours. For example, a person with non-declined meeting requests from 2:00 to 3:00 PM and 2:30 to 3:30 PM would yield 1.5 adjusted meeting hours.|
|Attended|A person *attended* a meeting if they either accepted or did not respond to a meeting request (also referred to as a *non-declined meeting request*).|
|Attendee|A person who was invited and *attended* the meeting.|
|Attributes|A defined characteristic about the person, such as team, department, or function. *Required attributes* are the subset of attributes that are required in order to calculate metrics.|
|Calendar fragmentation|When a person does not have blocks of time sufficient to focus on completing complex tasks. This is typical of those with only small blocks of time (15, 30, or 60 minutes) between meetings. Anything that is not *focus time* (uninterrupted time blocks of two hours or more with no meetings) is considered calendar fragmentation.|
|Collaborators|Anyone that *measured employees* or *time investors* interact with by email or in meetings. Collaborators are identified as internal (within the company) or external (outside of the company). |
|Collaborator group|A group of collaborators that are identified as internal (within the company) or external (outside of the company) that interacts by email or in meetings with a specified *time investor*.|
|Connection|Two or more *meaningful interactions*.|
|Custom attribute|*Organizational data* attributes that describe the people being analyzed. If supplied by the company, these attributes can be used in grouping of data, and to filter reports and customize metrics. However, they are not reserved for metrics calculations.|
|Focus time|Uninterrupted time blocks of two hours or more with no meetings.|
|Fragmented hours | A person's time after you subtract their meeting hours and their focus hours. |
|Insularity|When collaboration happens only with people from within a person’s team, function, department, and so on.|
|Invitee|A person who is invited to a meeting with a meeting request.|
|Layer|The number of *levels* of reporting in a company, starting from CEO and going down. For example, the CEO equals level 0.|
|Level|A *required attribute* that is a company-specific way of organizing employees by job experience or seniority.   |
|Meaningful interactions|An email or meeting that includes between two and five people.|
|Measured employee|A person about whom Workplace Analytics gathers Office 365 data, and about whom analysts can calculate metrics.|
|Multitasking|The concept of not staying focused on the task at hand. Defined in Workplace Analytics as a person sending two emails or more per meeting hour, and in meetings shorter than an hour, two emails or more per meeting.|
|Non-declined meeting request|In Workplace Analytics, this is synonymous with *attended*.|
|Optional attribute|Optional *organizational data* attributes that describe the people being analyzed. If supplied by the company, you can use these attributes to explore metrics, filter queries, and customize metrics. These can be reserved for future metric calculations. Optional attributes include FunctionType, HireDate, HourlyRate, Layer, and TimeZone.|
|Organization|A *required attribute* that describes the organizational unit in which the employee resides. The exact value will be determined by the company’s structure, as well as how that structure is captured in within the company’s human resources information system. For example, the organization might also be known as department, function, or defined by a specific manager name in the management hierarchy. |
|Organizational data|Attributes about people in the organization or people who collaborate with the organization that Workplace Analytics can analyze. Most organizational data is obtained from a company’s human resources information system. For example, job family, job role, organization, line of business, cost center, location, region, layer, level, number of direct reports, manager, and so on. |
|Organizer|The person who organizes a meeting. This person is also counted as an *attendee*.|
|People meeting hours|The sum of adjusted meeting hours for each person in the meeting. For example, if a meeting lasts at least one hour with three attendees (and no attendees have overlapping meetings), the people meeting hours for that meeting is three.|
|Person|The *measured employee* for whom the metric is calculated.|
|Recipient|A person included in an email (includes the sender and people included in the cc and bcc lines).|
|Redundant|A meeting is considered redundant if at least three attendees are from different *levels* within the same organization. For example, a meeting whose attendees included a General Manager, a Director, and an Independent Contributor from the same organization would be a redundant meeting.|
|Required attribute|Mandatory organizational data attributes that describe the people being analyzed. Required attributes are used in Workplace Analytics to explore, calculate, and customize metrics and filter query results. Required attributes include PersonId, EffectiveDate, ManagerId, LevelDesignation (also referred to as level), and Organization.|
|Sender|The person who sends an email.|
|Span|The number of direct reports per manager.|
|Time investor|A *measured employee* that interacts with other collaborators in meetings and with email. Time investors allocate their time with the other participants or *collaborators* in the interaction in proportion to how many people are in the collaborator group for that interaction. People who do not have a license for Workplace Analytics can appear as collaborators, but never as time investors.|
|Time zones|Workplace Analytics uses these [time zones](../use/timezones-for-workplace-analytics.md). Personal metrics (Person query results) are calculated by using the person’s time zone. Meeting metrics (Meeting query results) are calculated by using the organizer’s time zone.|
|Working hours|Hours that represent the typical workweek for the company. The Workplace Analytics default setting is Monday through Friday from 8:00 AM to 5:00 PM for calculations of working hours. This default is only used for users who have not already set up their working days and hours in Outlook. Your admin can change the default working days and hours in the [System defaults](../setup/Configure-wpa-settings.md) section.

### Related topic

[Metric descriptions for Workplace Analytics](../use/Metric-definitions.md)

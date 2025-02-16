---
layout: section
title: Maintenance
summary: Log of ARCHER2 Service Maintenance
banner: web_banners_03.jpg
---

- [Q3 2021](#maintenance-sessions-quarter3-2021-1st-july---30th-september-2021)
- [Q2 2021](#maintenance-sessions-quarter2-2021-1st-april---30th-june-2021)
- [Q1 2021](#maintenance-sessions-quarter1-2021-1st-january---31st-march-2021)

## Maintenance Sessions: Quarter3 2021 (1st July - 30th September 2021)

| Status | Type | Start | End | System | User Impact | Reason |
| ---    | ---  | ---   | --- | ---    | ---         | ---    |
| Completed | Partial: Compute Nodes | 30/09/21 0830 | 30/09/21 1130 | ARCHER2 4Cabinet: Compute Nodes | Users will be able to connect to User Access Nodes and will be able to submit jobs to the compute nodes. The queued jobs will start once the compute nodes are returned to service. | A switch within the 4 Cabinet Service requires a reboot |
| Completed | Unplanned Full | 14/09/21 1100 | 15/09/21 1600 | ARCHER2 4Cabinet: User Access and Compute Nodes | Users will not be able to connect. | Power Issues within the Edinburgh area |
| Completed | Full (took place within unplanned outage) | 15/09/21 0900 | 15/09/21 1600 | ARCHER2 4Cabinet: User Access and Compute Nodes | Users will not be able to connect. Jobs can be queued and will start once the service returns | Apply a fix for Singularity Issue. |
| Completed | At-risk | 7/9/21 | 9/9/21 | ARCHER2 4Cabinet: User Access and Compute Nodes | Momentary interruptions to connections to UANs |  Allow our HPC Systems team to move the ARCHER2 4 cabinet system to a new Network at the Advanced Computing Facility (ACF) |
| Completed | Full | 25/8/21 1400 | 26/8/21 1115 | ARCHER2 4Cabinet: User Access and Compute Nodes | No access to the UANs and the queues will start to drain on the compute nodes from Monday 23rd August at 1400  |  Allow HPE Systems team to apply an essential security patch to the ARCHER2 4 cabinet system |
| Completed | At-risk | 25/8/21 | 25/8/21 | ARCHER2 4Cabinet: User Access and Compute Nodes | Momentary loss of external network traffic to the User Access Nodes (UAN) on ARCHER2 |  Allow our HPC Systems team to move the ARCHER2 4 cabinet system to a new Network at the Advanced Computing Facility (ACF) |
| Completed | At-risk | 18/8/21 1000 | 18/8/21 1500 | ARCHER2 4Cabinet: User Access and Compute Nodes | Connection to the User Access Nodes (UAN) on ARCHER2 may be lost.  File transfers may be affected. Jobs running on the compute nodes will not be impacted |  Allow our HPC Systems team to move the ARCHER2 4 cabinet system to a new Network at the Advanced Computing Facility (ACF) |
| Completed | Unplanned | 28/7/21 12:00 | 28/7/21 15:00 | ARCHER2 4Cabinet: Compute and file system |  Running jobs failed, no jobs able to start, filesystem unavailable | Power issue at ACF |
| Completed | Unplanned | 20/7/21 | 22/7/21 | ARCHER2 4Cabinet: User Access and Compute Nodes |Prevented new jobs from starting on the system to reduce the impact on users. Some running jobs may also have crashed as a result of this issue but any currently running should be unaffected  | Issue with the interconnect on the ARCHER2 service that causes some new jobs to fail on MPI initialisation |



## Maintenance Sessions: Quarter2 2021 (1st April - 30th June 2021)

| Status | Type | Start | End | System | User Impact | Reason |
| ---    | ---  | ---   | --- | ---    | ---         | ---    |
| Completed | Full | 29/6/21 06:00 | 29/6/21 23:00 | ARCHER2 4Cabinet: Full system | System unavailable to users | Essential power work at the ACF |
| Completed | Full | 28/4/21 09:00 | 28/6/21 11:00 | ARCHER2 4Cabinet: Full system | Users were able to access data and the User Access Nodes (UANs) throughout the maintenance session. Installing this PE required a reboot of the compute nodes. |A new version of the HPE Cray Programming Environment was installed to address memory leaks that were affecting a significant number of users and to help users prepare for the main ARCHER2 system. |


## Maintenance Sessions: Quarter1 2021 (1st January - 31st March 2021)

| Status | Type | Start | End | System | User Impact | Reason |
| ---    | ---  | ---   | --- | ---    | ---         | ---    |
| Completed | Full | 18/3/21 09:00 | 18/3/21 12:30 | ARCHER2 4Cabinet | System unavailable to users |High Speed Network (HSN) rebooted to allow the return of failed links which were causing job failures |
| Completed | Full | 18/2/21 08:30 | 18/2/21 14:00 | ARCHER2 4Cabinet | System unavailable to users | Updated the system to software v1.3.3, this included patched for the critical ‘sudo’ vulnerability |
| Completed | Unplanned | 7/2/21 21:15 | 9/2/21 09:30 | ARCHER2 4Cabinet | System unavailable to users | Power outage affecting SE Scotland |
| Completed | Full | 4/2/21 08:00 | 4/2/21 14:00 | ARCHER2 4Cabinet | System unavailable to users | High Speed Network (HSN) rebooted to allow the return of failed links which were causing job failures |





# Service Level Agreement for DRYCC Cloud Services

Last updated on November 9, 2021

This Service Level Agreement for Drycc Cloud Services (SLA) applies only to Drycc Cloud Services production clusters, excluding the Developer Tier. For the Drycc Cloud users registered prior to the last updated date, this SLA will be effective on January 10, 2022.

## 1. Definitions

1.1 **“Month”** refers to the calendar month.

1.2 **“Monthly Uptime Percentage”** is calculated per Drycc Cloud cluster on a monthly basis and is calculated as: (Total Minutes in Month – Unavailable Minutes in Month) ÷ Total Minutes in Month × 100%.

1.3 **“Unavailable Minutes in Month”** is the total number of minutes that a single Drycc Cloud cluster is unavailable in a monthly billing cycle. If all attempts to establish connections to the cluster fail within one (1) minute, the minute is considered unavailable. A Drycc Cloud cluster deployed in part of the month is assumed to be 100% available during the undeployed part of the month.

1.4 **“Monthly Service Fee”** means the total fee you paid for a particular Drycc Cloud cluster in the month.

1.5 **“Service Credit”** is the percentage of the monthly service fee to be credited to you if Doopai approves your claim.

## 2. Service Commitment

2.1 Doopai will use commercially reasonable efforts to make Drycc Cloud clusters available with a monthly uptime percentage of at least 99% during any monthly billing cycle.

## 3. Service Credit

3.1 If Doopai does not achieve and maintain the Monthly Uptime Percentages, then you may be eligible for a service credit as described below.

|Monthly Uptime Percentage                        |Service Credit |
|-------------------------------------------------|---------------|
|Less than 99% but equal to or greater than 95%	  | 10%           |
|Less than 95% but equal to or greater than 90%	  | 25%           |
|Less than 90%	                                  | 100%          |

## 4. Credit Request
4.1 To receive a service credit, you must submit a claim by submitting a Credit Request through the Drycc Cloud Support Center. To be eligible, the Credit Request must be received by Doopai by the end of the second billing cycle after the incident occurred. The necessary information for the Credit Request must include:

4.1.1 A detailed description of the event that caused the service unavailable;

4.1.2 Downtime and duration;

4.1.3 Descriptions of your attempts to resolve the downtime at the time of occurrence.

4.2 If Doopai confirms that the Monthly Uptime Percentage is less than the service commitment, Doopai will issue the Service Credit to you within one (1) billing cycle following the month in which the request occurred. If the submission is overdue, or you fail to provide the necessary information, you will lose your eligibility for the Service Credits. Service Credits must not be transferred or used in any other account.

## 5. Limitations
5.1 **“Minutes Unavailable in Month”** does not include, and you will not be eligible for a Service Credit for, any performance or availability issue that results from:

5.1.1 Force majeure, such as natural disasters, wars, terrorist acts, riots, government actions, etc.;

5.1.2 Network or equipment failure between your site and the Drycc Cloud;

5.1.3 Scheduled maintenance, including but not limited to the system upgrade, maintenance, etc., that Doopai provides advance notice;

5.1.4 Caused by the Cloud Providers, including but not limited to their network, hardware, software failure and system maintenance;

5.1.5 An attack on your application;

5.1.6 You have not followed the basic operational guidelines set forth in the Drycc Cloud Documentation, including without limitation (i) overloading a database instance so that such database instance is inoperable and (ii) creating an excessively large number of tables leading to significant increase of the recovery time;

5.1.7 Loss or leakage of data or passwords caused by you;

5.1.8 You have not followed appropriate safety practices; or

5.1.9 Any cluster belonging to the Developer Tier which has a resource limitation(s) on CPU, memory or storage.

# 6. Modification to the SLA

6.1 Doopai will provide at least sixty (60) calendar days’ advance notice for any adverse changes to this SLA. If you disagree with Doopai’s changes to the SLA, you have the right to stop using the Drycc Cloud Services, and if you continue to use the Drycc Cloud Services, you are deemed to have accepted the modified SLA.
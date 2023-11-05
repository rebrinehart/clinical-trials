# A dashboard for withdrawn, terminated, and suspended clinical trials
## Introduction

Clinical trials are central to human health advancement. Highly structured and regulated, they seek to evaluate the efficacy and safety of new approaches to care - such as drugs, vaccines, surgical procedures, medical devices, or behavioral treatments in human volunteers.

While many clinical trials are successful, some are cancelled early. The reasons trials are cancelled or suspended can be complex and nuanced. This may occur because the trial is unlikely to achieve its primary objectives, protocol violations have occurred and participant safety is at risk, the trial has insufficient enrollment, or a mix of many factors. In the field of clinical research, where all outcomes have far-reaching implications for patients, cancelled trials can significantly impact future funding, erode patient trust, and initiate discussions around ethics. 

When clinical trials are registered on [ClinicalTrials.gov](http://clinicaltrials.gov/), they must submit the recruitment status, which indicates the current stage of the trial. For cancelled or suspended trials, there are three types of recruitment statuses which I focused in on:

1. **Withdrawn trials** — voluntarily halted by the investigator or sponsor before the enrollment of any participants. Potential reasons could be a change in the study protocol or a difficulty in recruiting participants [1].
2. **Terminated trials** — halted prematurely and will not continue. All enrolled participants are no longer being examined or receiving intervention.
3. **Suspended trials** — stopped prematurely but could continue, upon an Institutional Review Board’s approval of a request for trial re-initiation [2].

Because [ClinicalTrials.gov](http://clinicaltrials.gov/) refers to these three status types as “study halted prematurely”, I chose to refer to this subset as “halted trials” [3].

## **Purpose**

In this analysis, I take a closer look at withdrawn, terminated, or suspended clinical trials - here referred to as halted trials. I seek to uncover patterns or insights from the dataset that shed light on the historical trends of halted trials.

## Stakeholders

Potential stakeholders for this analysis might be:

- Any clinical research organization seeking to understand the past patterns of halted trials, prioritize particular research areas or conditions, or anticipate potential resource allocation risks.
- Interested companies or researchers seeking to evaluate sponsor performance and reliability
    - It is important to note that halted trials are not always a negative indicator of business or trial performance. There are many reasons why a trial may be halted.
- Researchers or sponsors seeking to anticipate and address potential challenges in future trials.

## Data

The dataset is from the Aero Data Lab [4], and contains data from 10 clinical trial companies. There are 13,748 trials included. The dataset was published in July 2019, and covers trials with start dates from 1984 to 2020. The dataset contains information on the trials’ titles, summaries, start dates, phases, enrollment size, statuses, sponsors, and primary medical condition.

If you would like to learn more about this dataset, you can view the [webpage](https://www.aerodatalab.org/birds-eye-view-of-research-landscape), companion [article](https://www.statnews.com/2019/07/18/clinical-trials-birds-eye-view-drug-development/), or [full dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/S8C77Q) on the Harvard Dataverse. I highly recommend reading the companion article by Dr. Spencer Hey; he does a fantastic job explaining the dataset and his own birds-eye visualization. He also poses some really thought-provoking questions about the ethics, power dynamics, and inefficiencies of clinical research as a whole.

## Dashboard

![full-dashboard](https://github.com/rebrinehart/clinical-trials/assets/135187192/c93ece4f-4cda-46b3-af85-c87351327f35)

## Insights & Read More
To read about the data insights, dashboard creation, and my entire process, check out [my Medium post](https://medium.com/@reb.rinehart/clinical-trials-dashboard-256b88bf48cb).

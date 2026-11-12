# Sql-playground
SQL methodology showcase -  collection of standalone techniques


This repository is a SQL playground: a collection of standalone examples of techniques I’ve used in production work. Each example stands on its own and isn’t part of an end-to-end business project. I’m building separate repositories that apply these techniques to real-world use cases. Folders organize techniques by industry use case, such as healthcare, insurance and logistics.

Techniques and where to find them:

<ins>Business Area</ins>	&emsp;&emsp; &emsp;&emsp; &emsp;&emsp;  <ins>Folder location</ins>                                                                                                

1) General Advanced Techniques	   &emsp;&emsp;&nbsp;&nbsp;  /general                                                          
<br>
General Advanced Techniques: Window functions (ROW_NUMBER, RANK, DENSE_RANK, LAG/LEAD), running totals, moving averages, top-N per group, QUALIFY, CTEs, recursive CTEs, correlated subqueries, CROSS APPLY / OUTER APPLY, self-joins, anti-joins and semi-joins (EXISTS / NOT EXISTS), range joins, INTERSECT / EXCEPT, conditional aggregation, PIVOT/UNPIVOT, GROUPING SETS/ROLLUP, gaps and islands, date spine generation, cohort analysis, sessionization, slowly changing dimensions (Type 2), MERGE/upserts, incremental loads, deduplication, data validation checks, source-to-target reconciliation, JSON parsing and flattening, query optimization, stored procedures, dynamic SQL, funnel analysis, percentile calculations

<br><br>

<ins>Business Area</ins>	&emsp;&emsp; &emsp;&emsp; &emsp;&emsp;  <ins>Folder location</ins>                                                                                                


2) Healthcare	   &emsp;&emsp; &emsp;&emsp; &emsp;&emsp;  /healthcare                                                          
<br>
Healthcare Techniques: Patient deduplication (master patient index), readmission rates (30-day), length of stay, encounter sequencing, care gap analysis, chronic condition flagging, risk stratification, claims aggregation, denial rate analysis, provider utilization, payer mix, ICD/CPT code grouping, medication adherence (proportion of days covered), episode of care grouping, patient cohort building, no-show rates, bed occupancy, ED wait times, HEDIS quality measures, member eligibility spans (gaps and islands), slowly changing dimensions (Type 2), data quality validation	

<br><br>


<ins>Business Area</ins>	 &emsp;&emsp; &emsp;&emsp; &emsp;&emsp;  <ins>Folder location</ins> 

3) Insurance	   &emsp;&emsp; &emsp;&emsp; &emsp;&emsp;&nbsp;&nbsp;  /insurance                           	                                  
<br>
Insurance Techniques (Property & Casualty, Auto, etc.): Loss ratio, combined ratio, claim frequency, claim severity, loss development triangles, IBNR estimation, earned vs. written premium, policy retention rate, policy renewal analysis, quote-to-bind conversion, premium by risk segment, exposure calculation, claims cycle time, open claim aging, subrogation recovery, fraud flagging, catastrophe loss aggregation, agent performance, territory rating analysis, multi-policy bundling, policy term spans (gaps and islands), slowly changing dimensions (Type 2), data quality validation

<br><br>


<ins>Business Area</ins>	 &emsp;&emsp; &emsp;&emsp; &emsp;&emsp;  <ins>Folder location</ins> 

4) Logistics	   &emsp;&emsp; &emsp;&emsp; &emsp;&emsp;&nbsp;&nbsp;&nbsp;&nbsp;  /logistics                                                                    
<br>
Logistics Techniques: On-time delivery rate, transit time analysis, shipment tracking event sequencing, dwell time, carrier performance scorecards, cost per shipment, cost per mile, lane analysis, load optimization (truckload utilization), freight spend by mode, inventory turnover, days of supply, stockout analysis, warehouse throughput, order fill rate, pick and pack cycle time, route sequencing, deadhead miles, fleet utilization, demand forecasting baselines, accessorial charge analysis, freight invoice auditing, shipment status gaps (gaps and islands), slowly changing dimensions (Type 2), data quality validation

<br><br>


<ins>Business Area</ins>	 &emsp;&emsp; &emsp;&emsp; &emsp;&emsp;  <ins>Folder location</ins> 

5) Workforce Analytics     &emsp;&emsp;&nbsp;  /workforceanalytics                       
<br>
Workforce Analytics Techniques: Point-in-time headcount, running headcount, workforce mix, turnover rate, cohort retention, regrettable vs. non-regrettable attrition, tenure buckets, time to promotion, internal mobility, org hierarchy, span of control, time to fill, recruiting funnel conversion, pay bands, compa-ratio, pay equity analysis, slowly changing dimensions (Type 2), deduplication


<br>
Notes: 
Type 1: overwrite the old value, with no history kept
Type 2: add a new row for each change, keeping full history
Type 3: add a “previous value” column, keeping only one prior value

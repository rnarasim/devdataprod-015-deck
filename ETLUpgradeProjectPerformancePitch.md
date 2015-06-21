---
title: "ETL Upgrade Project Performance Monitoring App"
author: "Ravi Narasimhan"
date: "June 21, 2015"
mode: selfcontained
output: slidy_presentation

---

## Background


We are currently working on a project to migrate our ETL (Extract, Transform and Load) Platform.  ETL Jobs are categorized into many projects based on functional areas. Each functional team is interested in reviewing the jobs they own and support. To date we have migrated 10 projects and total of 2919 jobs. Monitoring performance of these projects is crucial for success of the teams. With several thousands of of these jobs executing on a daily basis - it could be quiet challenging to get keep tabs on the Batch Performance. This app comes to your rescue!!! All you need to know is your functional area/project name. The app helps monitor the batch performance gained by the migration project and helps developers pin point batch delays to a set of jobs to fine tune.

* If you are interested in a test drive - access the app here: https://rnarasim.shinyapps.io/ETLUpgradeProjectPerformance




## ETL Project Status

 * These are the Projects and Number of Jobs that have been successfully migrated.
<!-- html table generated in R 3.1.1 by xtable 1.7-4 package -->
<!-- Sun Jun 21 16:59:48 2015 -->
<table border=1>
<tr> <th>  </th> <th> Project </th> <th> JobCount </th>  </tr>
  <tr> <td align="right"> 1 </td> <td> BI - Customer </td> <td align="right"> 161 </td> </tr>
  <tr> <td align="right"> 2 </td> <td> BI - EDW </td> <td align="right"> 941 </td> </tr>
  <tr> <td align="right"> 3 </td> <td> EDW To Stores </td> <td align="right">  98 </td> </tr>
  <tr> <td align="right"> 4 </td> <td> Store Host Apps </td> <td align="right"> 142 </td> </tr>
  <tr> <td align="right"> 5 </td> <td> experian </td> <td align="right"> 1510 </td> </tr>
  <tr> <td align="right"> 6 </td> <td> fresco </td> <td align="right">   7 </td> </tr>
  <tr> <td align="right"> 7 </td> <td> logistics </td> <td align="right">  10 </td> </tr>
  <tr> <td align="right"> 8 </td> <td> mpa </td> <td align="right">  41 </td> </tr>
  <tr> <td align="right"> 9 </td> <td> sigcap </td> <td align="right">   3 </td> </tr>
  <tr> <td align="right"> 10 </td> <td> xbr </td> <td align="right">   8 </td> </tr>
   </table>


## What is in it for Functional Area Managers?


- Review Performance of ETL  projects your team support with one click of a button
- Monitor and take action if you see batch delays
- If you are interested in a test drive - access the app here: https://rnarasim.shinyapps.io/ETLUpgradeProjectPerformance


## What is in the App For Developers?

- Review Project and Job Level Performance 
- Tune Jobs that are critical to the success of your batch operations
- If you are interested in a test drive - access the app here: https://rnarasim.shinyapps.io/ETLUpgradeProjectPerformance


## To Do for next release
  * New Project be automatically setup for stats collection
  * Push updated datasets daily to the app.



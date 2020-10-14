---
authors:
    - Jiaqi Xiao
date: 2020-09-26
---

# Enterprise Resource Planning (ERP)

**Before entering MSIS, you are expected to know the usage of ERP in the modern business world. It would be optimal if you had some experiences of using an ERP software during your undergraduate study or professional work.**

## During the MSIS program

During your time in the MSIS program you would have the access to and be practicing on a handful servers of SAP (a very common-used ERP software in modern enterprises). Throughout the course, you would play the role of a business manager and oversee the day-to-day activities of a company using the SAP system.

## SAP 

SAP is one of the leading software in the ERP industry. In your first semester of MSIS, you will be using SAP to practice those ERP concepts you learn in the ERP module. Right now you may not have access to use it, but feel free to browse over the [SAP's website](https://www.sap.com/index.html). 

## Major Concepts

### What Is ERP? Why Do We Use It? 

ERP, as known as the Enterprise Resource Planning, refers to a type of software that organizations internally implement to monitor, manage and review day-to-day business activities. 

The article, [<u>*Enterprise Resources Planning* (ERP) </u>](https://www.investopedia.com/terms/e/erp.asp ) from Investopedia, explicitly elaborate on more detailed definition of ERP.

Oracle is one of the industry leaders in ERP software.  [<u>This Oracle article</u>](https://www.oracle.com/applications/erp/what-is-erp.html) substantially introduce ERP to you about how Oracle defines the fundamental of ERP. and the business value it strives to bring via its cloud ERP system 

### The Historical Purpose of ERPs

The introduction of desktop computing in the 80s, which is also remarked as "The PC revolution", has granted a lot of efficiency for modern businesses, but also created gaps, or silos, in between different functional departments. Back in time, companies were having trouble sharing their data. As a response, ERP rose to a powerful integration solution that it solved this problem by allowing the users to better plan and integrate the resources across all departments within the enterprise. If you are interested in the origin of ERP:

> The term ERP was first used in the 1990s by the Gartner Group, but enterprise resource planning systems actually have their roots deep in the manufacturing industry, and can trace their history back to the 1960s.

To learn more about ERP's historical meaning, read [the article "*A Brief History of ERP*"](https://www.geniuserp.com/blog/a-brief-history-of-erps#:~:text=The%20term%20ERP%20was%20first,track%2C%20and%20control%20their%20inventory.) from *[Genius ERP.](https://www.geniuserp.com/)* *Genius ERP* has been there for 25 years and it is a consulting firm that provides ERP implementation solutions for small and mid-sized manufacturers.





------



### Data Type

There are essentially four types of data that a company use and store. They are: 

- **Configuration/Organizational Data**
- **Master Data**
- **Transaction Data**
- **Situational Data**

The first three types of data are the most common data one would use and identify. The fourth type, situational data, are data specific to tasks, and they are sometimes mixed with master data and transaction data.

Configuration/Organizational data is very easy to understand. They basically describe the structure of an organization. 

Read this article if you would like to see some examples: [*Prepare Organizational Data*](https://docs.microsoft.com/en-us/workplace-analytics/setup/prepare-organizational-data#:~:text=Examples%20of%20organizational%20data%20include,of%20direct%20reports%2C%20and%20manager.)

Some might find it difficult to tell between master data and transaction data. Here is some great resources to help you understand their differences!

- Watch this great video first. It is created by Jared Hillam, a EIM Practice Director at *INTRICITY. INTRICITY* is a specialized team of over 100 data management and business process professionals providing data integration, BI, and Digital Transformation solutions in a variety of industries.

  <iframe width="560" height="315" src="https://www.youtube.com/embed/Iv9P5D6yj30" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
- The author of the above video post compared these two data types in a more detailed article ["*Master Data vs Transaction Data*"](https://www.linkedin.com/pulse/master-data-vs-transaction-jared-hillam/) on his LinkedIn explaining more ways to decipher and mange Master Date vs Transaction Data.

After you have learned about the data types, [try thiese quiz questions.](https://fadyums.files.wordpress.com/2013/08/revision-chapter-2.pdf) This file is also a very useful file where you could find more practical examples of these different types of data. It has some review questions (short answers, multiple choices, T/F) to test your understanding. Do it and test how well you know about **DATA**!



------

### Logging and Undo in SAP

Most of transaction records, once logged[^1] into the system, are impossible to be deleted in SAP. However, when necessary you should undo[^2] transactions to reverse the wrong input.

Please do click around the hyperlinks within [the SAP's official manual](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/cf/74bb3ee5bf7173e10000000a114084/content.htm?no_cache=true) on these concepts to make sure you understand this point. It is essential to know how logging and undo works in SAP in order to use SAP smoothly.

[^1]: Store the log entries so that they are constantly available for normal database operation.
[^2]:Set database to the consistent state that it had before the transaction was started



### Exercises

###### 1. Define ERP, what does it stand for and how might it be useful in different sized-companies? 

###### 

###### 2. How does ERP help with the "silos" in between business functions/departments?



###### 3. Identify what data type is for each of the following data (don't worry about identifying Situational data if you feel perplexed. Being able to identify whether they are organizational, master, or transaction data is sufficient.)

- Warehouse 
- Job role
- Dividends
- Donations
- Organization Branch
- Customer  
- Purchases
- Employee
- Payroll
- Cost Center
- Credits
- Interest
- Debits
- Line of Business 
- Subscriptions




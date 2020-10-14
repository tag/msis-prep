---
authors:
    - Jiaqi Xiao
date: 2020-09-26
---

## During the MSIS program

Upon entering the MSIS Program you will be tasked with learning SAP, an <abbr title="Enterprise Resource Planning">ERP</abbr> software which is used by companies all around the world to
assist in their day-to-day business activities. In the ERP Module, you will be exposed to the Planning, Procurement, and Production processes followed by participating in hands-on simulations against your classmates. In preparation for this it is best if you come into the program with a bit of knowledge related to What ERP is, along with how these systems work.

## What is SAP?

SAP is a globally recognized brand in the enterprise resource planning software market. In your first semester of MSIS, you will begin using SAP to streamline the previously mentioned business processes. The exercises conducted in-class will allow you to gain an understanding of the software which may aid you throughout your concentration and/or career. Although you may not currently have access to SAP, feel free to browse over the [SAP's website](https://www.sap.com/index.html).

## Major Concepts

### Learning Outcome

- [ ] Being able to define ERP and recognize its importance in current business world.

- [ ] Being able to explain the reason of implementing ERP.

- [ ] Being able to identify and define the three major different data types of organizational data, master data and transaction data.

- [ ] Being able to compare different data and correctly recognize their types.

- [ ] Being able to understand the concepts of Log, Undo and Redo in SAP. Being able to explain the importance of these actions in the context of real world business.



### What Is ERP? Why Do We Use It?

<abbr title="Enterprise Resource Planning">ERP</abbr> is a type of software that organizations internally implement to monitor, manage and review day-to-day business activities.

The article, [*Enterprise Resources Planning* (ERP) ](https://www.investopedia.com/terms/e/erp.asp ) from Investopedia, gives a much more detailed definition of ERP.

Oracle, an industry leader in ERP Software, has a thorough article explaining the fundamental parts of an ERP system. You may find that article [<u> here </u>](https://www.oracle.com/applications/erp/what-is-erp.html)

### The Historical Purpose of ERPs

The introduction of desktop computing in the 1980s, also known as "The PC revolution", granted a lot of efficiency for modern businesses. However, this efficiency came at a cost, it created gaps and silos between business departments. Companies at that time were having trouble sharing data amongst themselves and others. As a response, ERP systems rose to be a powerful integration solution that solved this problem by allowing the users to better plan and integrate resources across all departments within an enterprise. If you are interested in the origin of ERP:

> The term ERP was first used in the 1990s by the Gartner Group, but enterprise resource planning systems actually have their roots deep in the manufacturing industry, and can trace their history back to the 1960s.

To learn more about ERP's historical meaning, read the article ["*A Brief History of ERP*"](https://www.geniuserp.com/blog/a-brief-history-of-erps#:~:text=The%20term%20ERP%20was%20first,track%2C%20and%20control%20their%20inventory.) from *[Genius ERP.](https://www.geniuserp.com/)* Genius ERP specializes in consulting small and mid-sized manufacturers on ERP implementation and has done so for 25+ years.

------



### Data Type

There are essentially four types of data that a company use and store. They are:

- **Configuration/Organizational Data**
- **Master Data**
- **Transaction Data**
- **Situational Data**

The first three types of data are the most common data one would use and identify. The fourth type, situational data, is data specific to tasks, and oftentimes mixed with master and transaction data.

**Configuration/Organizational** data is  easy to understand as it describes the structure of an organization.

Interest in reading a few examples? Reference the following article: [*Prepare Organizational Data*](https://docs.microsoft.com/en-us/workplace-analytics/setup/prepare-organizational-data#:~:text=Examples%20of%20organizational%20data%20include,of%20direct%20reports%2C%20and%20manager.)

Some might find it difficult to tell between **master data** and **transaction data**. Below are some great resources to better illustrate their differences.

- We recommend watching the following video first. Created by Jared Hillam, a EIM Practice Director at *INTRICITY*. INTRICITY is a specialized team of over 100 data management and business process professionals providing Data Integration, BI, and Digital Transformation solutions in a variety of industries.

  <iframe width="560" height="315" src="https://www.youtube.com/embed/Iv9P5D6yj30" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
- The author of the above video compared both data types in a more detailed article, ["*Master Data vs Transaction Data*"](https://www.linkedin.com/pulse/master-data-vs-transaction-jared-hillam/), on his LinkedIn profile explaining ways to decipher and manage Master Date vs Transaction Data.



------

### Logging and Undo in SAP

Most transaction records, once <abbr title="Store the log entries so that they are constantly available for normal database operation.">logged</abbr> into the system, are irreversible in SAP. However, when necessary you should <abbr title="Set database to the consistent state that it had before the transaction was started">undo</abbr> transactions to reverse the wrong input.

##### There's no "delete record" for most of SAP transactions.

Understand that any records belonging to a company in the real world can contain critical information. You will always need records to trace back past business activities which have occurred inside a company. You don't want to lose any of the records, despite reasons such as a typo.

##### Situation where you might want to "delete" or redo a transaction.

For example, you are in charge of a local warehouse for an ice cream company and  input any goods shipment into SAP. You recently sent out 80 boxes of blueberry flavored ice cream. However, when you are inputting this transaction into SAP, you mistakenly put it down as 80 boxes of banana flavored ice-cream. Soon you realize the mistake you have made in your log, but goods are shipped and you cannot delete the blueberry document you created before. What can you do now?

##### Undo and Redo the transaction to fix log error

To solve the problem, you simply need to undo whatever you have done by creating the log for that blueberry ice cream shipment. There are transaction codes for "undo" transactions in SAP just like other transactions. So, you would use the **undo** transaction to reverse that shipment of blueberry ice cream. The inventory of blueberry ice cream would be restored.

The next step you need to do, obviously, is to log the correct shipment for banana ice cream. You will use the same transaction code you used as you did for your last log, but this time you would **redo** the transaction of goods shipment with the correct goods.

Please do click around the hyperlinks within [the SAP's official manual](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/cf/74bb3ee5bf7173e10000000a114084/content.htm?no_cache=true) on these concepts to make sure you understand this point. It is **important** to know how logging and undo works in SAP in order to use SAP smoothly. This official guide shows you lots of concepts in the process of using SAP. Please pay close attention to the following pages:

- [Log Concept](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/e3/e693df6e23b94fb953b780cf8e28e5/content.htm?no_cache=true)
- [Redo Log Entry](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/54/58c33e3a443907e10000000a114084/content.htm?no_cache=true)
- [Undo Log Entry](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/8e/58c33e3a443907e10000000a114084/content.htm?no_cache=true)







### Exercises

###### 1. Define ERP, what does it stand for and how might it be useful in different sized-companies?



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
- Vendors
- Debits
- Line of Business
- Company Codes
- Subscriptions

###### 4. Why is "undo" transactions necessary? Explain it by giving an real-world example. What can it do in order to manage and control the business process? (Hint: consider the following scenario, if you are the CFO and some accountant under you have created transaction for wrong amount, maybe you would really want to know what the wrong amount was and how was it fixed as you are going over the financial statement of that day.)

######

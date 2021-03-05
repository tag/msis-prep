---
authors:
    - Jiaqi Xiao
date: 2020-09-26
---

## During the MSIS program

During your time in the MSIS program you will be required to learn and utilize SAP, an industry leading <abbr title="Enterprise Resource Planning">ERP</abbr> software. The SAP platform is used by organizations worldwide to assist in their day-to-day business activities, however, your uses will be relatively limited to simulated exercises involving Planning, Procurement, and Product processes. It is crucial that you understand how these processes interact with one another to successfully tackle the required coursework, which is done at both the team and individual level.

Feel free to [learn more about SAP here](https://www.sap.com/index.html)!

## Major Concepts

**You should have an understanding of what an ERP system is, how they are used to benefit organizations, as well as the varying data types** found within these systems.

1. _**Define what an ERP system is**_
2. Explain the _**reason an organization might implement**_ an ERP system
3. Be able to identify and _**compare the different data types**_
4. Understand the concepts and importance of _**Log, Undo, and Redo within the SAP platform**_

### What Is ERP? Why Do We Use It?

Enterprise Resource Planning is a software that organizations internally implement to monitor, manage, and review day-to-day business activities.

The following article, [Enterprise Resources Planning (ERP) ](https://www.investopedia.com/terms/e/erp.asp ), from Investopedia, provides a much more detailed definition of ERP.

Oracle, an industry leader in ERP software, has a in-depth article explaining the fundamental parts of an ERP system: [What is ERP](https://www.oracle.com/applications/erp/what-is-erp.html)  

### The Historical Purpose of ERPs

The introduction of desktop computing in the 80s, as known as "The PC revolution", granted a lot of efficiency for modern businesses. However, this efficiency came at a cost, it created gaps and silos between business departments. Companies at that time were having trouble sharing their data amongst themselves and others. As a response, ERP systems rose to be a powerful integration solution that solved this problem by allowing the users to better plan and integrate resources across departments within an enterprise. If you are interested in the origin of ERP:

> The term ERP was first used in the 1990s by the Gartner Group, but enterprise resource planning systems actually have their roots deep in the manufacturing industry, and can trace their history back to the 1960s.

To learn more about ERP's historical meaning, read the article ["*A Brief History of ERP*"](https://www.geniuserp.com/blog/a-brief-history-of-erps#:~:text=The%20term%20ERP%20was%20first,track%2C%20and%20control%20their%20inventory.) from *[Genius ERP.](https://www.geniuserp.com/)* Genius ERP specializes in consulting small and mid-sized manufacturers on ERP implementation and has done so for 25+ years.

### Data Type

There are essentially four data types that an organization may use and store. They are:

- Configuration/Organizational Data
- Master Data
- Transaction Data
- Situational Data

The first three types of data are the most common data one would use and identify. The fourth, Situational Data, is  specific to tasks, and oftentimes mixed with both Master and Transaction Data.

**Configuration/Organizational data** is very easy to understand as it describes the structure of an organization.

Interest in reading a few examples? Reference the following article: [*Prepare Organizational Data*](https://docs.microsoft.com/en-us/workplace-analytics/setup/prepare-organizational-data#:~:text=Examples%20of%20organizational%20data%20include,of%20direct%20reports%2C%20and%20manager.)

On occasion, it can be difficult to differentiate between **Master Data** and **Transaction Data**; below you will find resources which aim to better illustrate their differences.

We recommend watching the following video first - created by Jared Hillam, EIM Practice Director at INTRICITY. INTRICITY is a specialized team which provides Data Integration, BI (Business Intelligence), and Digital Transformation solutions across a variety of industries.

  <iframe width="560" height="315" src="https://www.youtube.com/embed/Iv9P5D6yj30" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Jared Hillam has also authored a piece which compares both data types on his LinkedIn; this article explains additional ways to decipher and manage [Master Data vs Transaction Data](https://www.linkedin.com/pulse/master-data-vs-transaction-jared-hillam/).

### Logging and Undo in SAP

Most transaction records, once <abbr title="Store the log entries so that they are constantly available for normal database operation">logged</abbr> into a system, are impossible to delete. When necessary you should <abbr title="Set database to the consistent state that it had before the transaction was started">undo</abbr> transactions in order to reverse the wrong input.

##### There's no "delete record" for most of SAP transactions.

Understand that records oftentimes do contain critical information, and that in _most_ cases business activities must have records which are traceable back to specific dates and events.

##### Situation that you might want to "delete" or redo a transaction.

For example, you are in charge of a local warehouse which carries frozen goods. You recently sent out eighty boxes of Blueberry flavored ice cream. As you update your SAP system you notice that you mistakenly put down shipping out eighty boxes of Banana flavored ice cream. Upon noticing this mistake in your logs, you realize that the truck has already left the shipping dock and you are unable to delete the documents you created before. What can you do now?

##### Undo and Redo the transaction to fix log error

In order to solve this problem, you would need to undo whatever you have done by creating the log for the Blueberry ice cream shipment. There are transaction codes for _**undo**_ transactions in SAP just like other transactions. So, you would use the undo transaction code to reverse that shipment of Blueberry ice cream. The inventory of Blueberry ice cream would then be restored.

Next, you need to correctly log the correct shipment of ice cream. You will utilize the same transaction codes used for your last log, but this time you will _**redo**_ the transactions of goods shipped with the correct flavored ice cream.

You may find it extremely useful to reference SAP's [official manual](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/cf/74bb3ee5bf7173e10000000a114084/content.htm?no_cache=true). This manual covers the previously outlined concepts in-depth to ensure you understand the concepts up until this point. It is _critical_ to know how logging and undo functions work within SAP.

- [Log Concept](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/e3/e693df6e23b94fb953b780cf8e28e5/content.htm?no_cache=true)
- [Redo Log Entry](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/54/58c33e3a443907e10000000a114084/content.htm?no_cache=true)
- [Undo Log Entry](https://help.sap.com/doc/saphelp_pserv472/4.72/en-US/8e/58c33e3a443907e10000000a114084/content.htm?no_cache=true)

### Exercises

1. Define ERP, what does the acronym stand for and how might it be useful in different-sized organizations?
2. How might ERP platforms assist with "silos" between business functions and departments?
3. Identify the data types associated with each of the following actors and activities:
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
4. Why is it necessary to "undo" transactions? Additionally, identify a real-world scenario where you might need to undo a transaction.

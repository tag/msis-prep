---
authors:
    - Jiaqi Xiao
    - Tom Gregory
date: 2020-09-26
updated: 2021-03-30
---
## During the MSIS program

During your time in the MSIS program you will be required to learn and utilize SAP, an industry leading ERP software. The SAP platform is used by organizations worldwide to assist in their day-to-day business activities. However, your in-class use will be relatively limited to simulated exercises involving planning, procurement, and product processes. It is crucial that you understand how these processes interact with each other. You may not have access to SAP, but you can visit the [SAP website](https://www.sap.com/index.html) to learn more about the company.

*[ERP]: Enterprise Resource Planning

## Major Concepts

You should have an understanding of what an ERP system is, how they are used to benefit organizations, as well as the varying data types found within these systems.

1. Define what an ERP system is.
2. Explain the reason an organization might implement an ERP system.
3. Be able to identify and compare the different data types used by ERPs.
4. Understand the concepts and importance of _**log**_, _**undo**_, and _**redo**_ within the SAP platform,

### What Is ERP?

**Enterprise Resource Planning** is software that organizations internally implement to monitor, manage, and review day-to-day business activities. The article ["Enterprise Resources Planning (ERP)"](https://www.investopedia.com/terms/e/erp.asp ) (_Investopedia_), provides a much more detailed definition of ERP.

Oracle, an industry leader in ERP software, has a in-depth article explaining the fundamental parts of an ERP system: [What is ERP](https://www.oracle.com/applications/erp/what-is-erp.html)  

### The Historical Purpose of ERPs

The introduction of desktop computing in the 80s, as known as "The PC revolution", granted a lot of efficiency for modern businesses. However, this efficiency came at a cost, it created gaps and silos between business departments. Companies at that time were having trouble sharing their data amongst themselves and others. As a response, ERP systems rose to be a powerful integration solution that solved this problem by allowing the users to better plan and integrate resources across departments within an enterprise. To learn more, read ["A Brief History of ERP"](https://www.geniuserp.com/blog/a-brief-history-of-erps).[^generp]

Many companies sell ERP software. SAP, Oracle (Oracle ERP Cloud), and Microsoft (Microsoft Dynamics) are some of the biggest. Traditionally, ERP systems were installed locally in companies' data centers, but ERP vendors have been moving to managed and hybrid cloud offerings. In 2016, Oracle purchased NetSuite, a popular web-based ERP targeting small and mid-size companies.

### Data Type

There are essentially four types of data used in an ERP system:

- Configuration/Organizational Data
- Master Data
- Transaction Data
- Situational Data

The first three types of data are the most common data one would use and identify. The fourth, Situational Data, is  specific to tasks, and oftentimes mixed with both Master and Transaction Data.

**configuration data** (sometimes calls organizational data) describes the structure of an organization.  **Master data** represented people, places, and items tracked by the company. **Transaction data** describes events or transactions on master data. When a customer purchases a product, the product information (weight, location) is master data, and the purchase price and payment method are transaction data.


The following video from Jared Hillam helps explain the difference:[^erpvid]

  <iframe width="560" height="315" src="https://www.youtube.com/embed/Iv9P5D6yj30" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Hillam has also authored a piece which compares both data types; this article explains additional ways to decipher and manage [Master Data vs Transaction Data](https://www.linkedin.com/pulse/master-data-vs-transaction-jared-hillam/).

### Logging and Undo in SAP

ERP systems are designed so that most transaction records, once entered into a system, are impossible to delete. Sometimes mistakes are made, and it's necessary to reverse a transaction. However, there is no "delete record" option in most ERP systems. This is an intentional financial control to help prevent fraud. Business records contain critical information, and financial laws (and good accounting practice) require business activity records be  traceable back to specific dates and events. Undoing mistakes can be cumbersome, as every action is recorded by the system for later auditing.

### Exercises

1. Define ERP. How might ERP software be useful in different-sized organizations?
2. How might ERP platforms assist with "silos" between business functions/departments?
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

4. Why might it necessary to "undo" transactions? How does "undo" work differently in ERP systems?

5. Why is it important for financial and business records to be tracked in was that cannot be easily changed?

[^erpvid]: Video by Jared Hillam, EIM Practice Director at INTRICITY
[^generp]: Anne Mulvenna, _Genius ERP_

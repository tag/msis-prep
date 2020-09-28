---
authors:
    - Jiaqi Xiao
date: 2020-09-26
---

# Enterprise Resource Planning (ERP)

<br>

**Before entering MSIS, you are expected to know the usage of ERP in the modern business world. It would be optimal if you had some experiences of using an ERP software during your undergraduate study or professional work.**

<br>

## During the MSIS program

During your time in the MSIS program you would have the access to and be practicing on a handful servers of SAP (a very common-used ERP software in modern enterprises). Throughout the course, you would play the role of a business manager and oversee the day-to-day activities of a company using the SAP system.

<br>

## SAP 

SAP is one of the leading software in the ERP industry. You will be using SAP to practice those ERP concepts you learn in the ERP module. Right now you may not have access to use it, but feel free to browse over the [SAP's website](https://www.sap.com/index.html). 

<br>

## Major Concepts

<br>

### What Is ERP? Why Do We Use It? 

ERP, as known as the Enterprise Resource Planning, refers to a type of software that organizations internally implement to monitor, manage and review day-to-day business activities.

Click [<u>here</u>](https://www.investopedia.com/terms/e/erp.asp ) to review a Investopedia article on more detailed definition of ERP.

Oracle(ORCL) is one of the industry leaders in ERP software.  Click [<u>here</u>](https://www.oracle.com/applications/erp/what-is-erp.html) to read more about how Oracle defines the fundamental of ERP. and the business value it strives to bring via its cloud ERP system. 

<br>

### The Historical Purpose of ERPs

The PC revolution has granted a lot of efficiency for modern businesses, but also created gaps, or silos, in between different functional departments. Back in time, companies were having trouble sharing their data. As a response, ERP rose to a powerful integration solution that it solved this problem by allowing the users to better plan and integrate the resources across all departments within the enterprise. If you are interested in the origin of ERP:

> The term ERP was first used in the 1990s by the Gartner Group, but enterprise resource planning systems actually have their roots deep in the manufacturing industry, and can trace their history back to the 1960s.

To learn more about ERP's historical meaning, read [this article on Genius ERP](https://www.geniuserp.com/blog/a-brief-history-of-erps#:~:text=The%20term%20ERP%20was%20first,track%2C%20and%20control%20their%20inventory.)

<br>

<br>

------

<br>

### Data Type

There are essentially four types of data that a company use and store. They are: 

- **Configuration/Organizational Data**
- **Master Data**
- **Transaction Data**
- **Situational Data**

The first three types of data are the most common data one would use and identify. The fourth type, situational data, are data specific to tasks, and they are sometimes mixed with master data and transaction data.

<br>Configuration/Organizational data is very easy to understand. They basically describe the structure of an organization. 

Read this article if you would like to see some examples: [*Prepare Organizational Data*](https://docs.microsoft.com/en-us/workplace-analytics/setup/prepare-organizational-data#:~:text=Examples%20of%20organizational%20data%20include,of%20direct%20reports%2C%20and%20manager.)

<br>Some might find it difficult to tell between master data and transaction data. Here is some great resources to help you understand their differences!

- Watch this great video first.
[![Master and Transaction](pic\data type.png)](https://www.youtube.com/watch?v=Iv9P5D6yj30 "Master and Transaction")
- The author of the above video post this [article](https://www.linkedin.com/pulse/master-data-vs-transaction-jared-hillam/) on his LinkedIn explaining more ways to decipher and mange Master Date vs Transaction Data.

After you have learned about the data types, [this](https://fadyums.files.wordpress.com/2013/08/revision-chapter-2.pdf) is a very useful file where you could find more practical examples of these different types of data. It has some review questions (short answers, multiple choices, T/F) to test your understanding. Do it and test how well you know about **DATA**!

<br>

------

<br>

### The Business Activities Cycles

> Tom Gregory: "The business cycles begin with capturing data/information about a transaction. They end with information output, such as a financial statement or payment (similar to a system). Similar transactions are grouped together to form a business cycle. "

There are 5 major Business Cycles:

1. Procurement cycle (Expense, Purchasing, Procure to Pay)
2. Revenue cycle (Sales, Order to Cash)
3. Production cycle (Manufacturing or Operations)
4. Human Resources / Payroll cycle
5. Accounting Cycle

During the CORE, you would participate in different business activities of these cycles using SAP. Here, I would focus on introducing the **Procurement Cycle** and the **Revenue Cycle**. There are a lot of good resources online that you could find about other three cycles. You are very welcome to dig into them as knowing them would help you better understand business processes in organizations.

<br>

- #### Procurement Cycle (Procure-to-Pay)

Read about the Procurement Cycle: 

[*Procurement Cycle (The Telegraph)*](https://jobs.telegraph.co.uk/article/procurement-cycle/ )

[*Procurement Management Process - The 2020 Guide (Kissflow)*](https://kissflow.com/procurement-process/)

![Procurement Flow](https://kissflow.com/wp-content/uploads/2020/09/procurement-process-flow.png)

<br>From [the Telegraph article](https://jobs.telegraph.co.uk/article/procurement-cycle/ ) above, you could find that there are many important documents that are involved in the procurement cycle. You would find it helpful in the future if you could gain a basic understanding of them right now. They are:

1. Purchase Order: prepared by the **buyer** when ordering goods or services

2. Goods Receipt: prepared by the **buyer** when taking physical possession of goods

3. Invoice / Bill: prepared by the **seller** and sent to the **buyer**

4. Check (Payment): Prepared by the **buyer** and given to the **seller**, usually accompanied by a remittance advice to seller knows where to apply the payment

   <br>

- #### Sales Cycle (Order-to-Cash)

Read [this article](https://trackmaven.com/marketing-dictionary/sales-cycle/#:~:text=The%20sales%20cycle%20is%20the,on%20how%20they%20define%20it.) to learn about Sales Cycle:

> The sales cycle is the process that companies undergo when selling a product to a customer. It encompasses all activities associated with closing sale. Many companies have different steps and activities in their sales cycle, depending on how they define it.

Below are two more detailed websites explaining the stages and documents that are involved. Pay attention again to each step as they would generate documents that are essential for firms:

*[Step by Step: What you Should Know About the Order-to-Cash Process (Salesforce)](https://www.salesforce.com/products/cpq/resources/what-to-know-about-order-to-cash-process/)* 

[*A Walk Through The Order To Cash (O2C) Cycle*](https://www.purchasecontrol.com/blog/order-to-cash-process/)

![Sales cycle](https://c1.sfdcstatic.com/content/dam/web/en_us/www/images/hub/service/8-steps-in-the-order-to-cash-process-002.png)<br>The documents that are generated from the sales cycle are:

1. Sales Order: typically a reflection of (and response to) the Purchase Order
2. Packing Slip: accompanies the goods and usually omits $ dollar amount as an internal control measure *(pause a second to think here: why does packing slip omit the dollar amount? Do some research!)*
3. Invoice (Bill): Prepared by the **Selling company**
4. Payment Receipt: produced by the **Seller** and/or may be reported on a monthly statement of account.

<br>

*Note: You are encouraged to look online for examples of the above documents if you don't know what they might look like.*

------






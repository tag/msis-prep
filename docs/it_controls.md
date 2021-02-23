---
authors:
    - Jiaqi Xiao
    - Tom Gregory
date: 2020-10-05
updated: 2020-02-02
---

## During the MSIS program
Security and risk management are important to all organizations. Therefore, all students are expected to take foundational modules in IT controls and IT risk management. Depending on your program major, you might take additional specialization courses.

Although the MSIS program will cover the basics, many entering students completed at least one course coving IT controls. You will be well served to have a brief foundation before beginning the masters program.

## Major concepts

1. Describe the components of the IT Risk Triad: _**confidentiality**_, _**integrity*_, and _**availability**_.
2. Understand what IT controls are, what do they do, why they are necessary.
3. Explain the difference between _**general controls**_ and _**application controls**_.
4. Define the three types of IT controls. Give examples of each.
5. Describe the purpose of the COBIT and COSO control frameworks, and how they differ.

## Resources

IT risk is also called "enterprise risk" or "cyber risk". Unfortunately, there are few good, _free_ resources for learning about IT risk and IT controls. (If you find one, let us know!) While there are some common fundamentals and underlying regulations, each company and consultancy tends to define and organize risks slightly differently.

* Read the opening section of [Chapter 6: "Information Systems Security"][iss4bb-ch6] titled "The Information Security Triad: Confidentiality, Integrity, Availability (CIA)"
* Skim the _Wikipedia_ articles ["IT Risk Management"](https://en.wikipedia.org/wiki/IT_risk_management), ["COSO"][wiki-coso], and ["Sarbanes-Oxley"][wiki-sox]
* Investopedia has a useful article on ["Internal Controls"](https://www.investopedia.com/terms/i/internalcontrols.asp)

*[CIA]: Confidentiality, Integrity, Availability

[iss4bb-ch6]:https://opentextbook.site/informationsystems2019/chapter/chapter-6-information-systems-security-information-systems-introduction/
[wiki-coso]:https://en.wikipedia.org/wiki/Committee_of_Sponsoring_Organizations_of_the_Treadway_Commission
[wiki-sox]:https://en.wikipedia.org/wiki/Sarbanes%E2%80%93Oxley_Act

## IT Controls

In the business world, _**IT controls**_ are specific activities performed by people/systems which are designed to ensure that business objectives are safely met. Some examples of control include a password policy, a requirement to use two-factor authentication, or a database schema enforcing specific types on data.

IT controls play a critical role in assuring that IT is used correctly, data is correct and protected, and the organization is in compliance with all applicable laws and regulations. Controls prevent, detect, and correct transaction errors and fraud.

### The Two Categories of IT Controls

*[ITGC]: IT General Controls
*[ITAC]: IT Application Controls

There are two categories of IT controls: _**general controls (ITGC)**_ and _**application controls (ITAC)**_.

- **ITGC:** General control are implemented as procedures or policies. Because they are often enforced by people, compliance may vary. There are several subcategories/domains/systems of general controls, including:

    * [**Enterprise risk management**](https://www.investopedia.com/terms/e/enterprise-risk-management.asp), which includes processes for documenting and organizing risks.
    * **IT Change Management**: Sometimes called "change control", IT change management is different from organizational change management. A change control system includes documentation of all implemented IT systems, and formal processes for making changes to those systems. (In contrast, "organization change management" is about encouraging organizations to adopt organizational changes. It's incredibly important, but isn't a "control".)
    * [**Disaster recovery**](https://www.vmware.com/topics/glossary/content/disaster-recovery), which includes creating and testing response plans for likely risks.

- **ITAC:** Application control are enforced by technology rather than by policy. Enterprises work with huge volumes of data, so automatically enforced controls are necessary to keep data error-free.

    Application controls are often designed to control desirable characteristics of data, including:
        - **Accuracy**: Whether the data values stored for an object are the correct values
        - **Validity**: The reasonableness of data
        - **Integrity**: Detecting whether data has been altered
        - **Completeness**: Whether the data represents an entire population or just a sample

    Application controls help manage other features of data, including bias, timeliness, shareability, and security. In addition to enforcing data controls, there are many other purposes of application controls, including access control and encryption. For example, a two-factor authentication requirements build into web or software systems is an application control.

### Types of IT Controls

- _**Preventive Controls**_: Deter problems before they occur
- _**Detective Controls**_: Discover problems after they occur
- _**Corrective Controls**_: Mitigate problems after they occur

Here are some examples to better understand these control types:

- **Preventive**: Lock on a door, to prevent intruders
- **Detective**: Fire alarm, when fire goes off
- **Corrective**: House insurance

If you want to read more, look at what this public university [has to say about managing its internal controls](https://www.odu.edu/about/compliance/internal-auditing/internal-controls)

## Control frameworks, regulations, and organizations

*[COSO]: Committee of Sponsoring Organizations
*[COBIT]: Control OBjectives for Information and related Technology
*[SOX]: Sarbanes-Oxley
*[ISACA]: Information Systems Audit and Control Foundation

### COSO internal control framework

The Committee of Sponsoring Organizations (COSO) issued the [**Internal Control Framework**](https://www.coso.org/Pages/default.aspx) in 1992. The COSO Internal Control Framework is widely accepted as the authority on internal controls, and provides guidance for evaluating internal control systems.

### SOX (Sarbanes-Oxley Act of 2002)
In the late 1990s and early 2000s, a series of multi-million-dollar accounting frauds made headlines (e.g., ENRON, WorldCom). The impact on financial markets was substantial, and Congress responded by  passing of the **Sarbanes-Oxley Act of 2002 (SOX)**. SOX imposed many requirements for controls, and had a strong impact on how public companies operated.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xW9pSAwaeO0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The intent of SOX is to protect investors in public companies by:

  - Preventing financial statement fraud
  - Making financial reports more transparent
  - Demanding stronger internal controls by requiring companies use a control framework
  - Punishing executives who commit fraud

### COBIT Internal Control Framework

- **COBIT** stands for "Control Objectives for Information and related Technology" standard developed by the Information Systems Audit and Control Foundation (**ISACA**)
- The [COBIT framework][COBIT] is of generally applicable information systems security and control practices for IT control.
- Most recent update: COBIT-2019. (Timeline graphic from [ISACA][COBIT].)

![COBIT2019](/images/COBIT2019.png)

[COBIT]:https://www.isaca.org/resources/cobit

Resources to read more about COBIT[^1]:

- ["What is the COBIT Framework: Benefits and Components"](https://www.simplilearn.com/what-is-cobit-significance-and-framework-rar309-article), _Simplilearn_
- ["COBIT 2019 – the Key Changes to COBIT 5"](https://www.joetheitguy.com/cobit-2019-key-changes-cobit-5/), _Joe the IT Guy_
_NOTE: There are many more IT control frameworks and organizations. These will be discussed during your time in the MSIS program._

### COBIT vs. COSO

Read ["What Are The Differences Between COBIT & COSO"](https://reciprocitylabs.com/what-are-the-differences-between-cobit-coso/) to understand the differences between COSO and COBIT.

#### Exercises

1. What is the purpose of IT controls? Why do you think it is necessary for companies to have formal controls?

2. What is the difference between general controls and applicaiton controls?

3. List several characteristics of data. Are these characteristics best enforced by general controls or application controls?

4. In your own words, describe the three types of IT controls. Give examples of each.

5. In your own words, explain how the following terms relate to IT controls:

    1. COSO
    2. COBIT
    3. SOX

[^1]:  These article links are NOT an endorsement of these (or any) consulting companies.

# Team Project - XXX
The original assignment is [here](https://docs.google.com/document/d/13vUmeWuM2COGP6vKGhU66AC_evl0T1YajcbFQybSm5Q/edit).

### Legenda
- _italic_ - task description

### 0. Preface
We have rethought the New Century Wellness Group in order to make it fit better into our Big Data Systems program.

We've made the following suggestions:
- New Century Wellness Group is still a small company but they want to scale and widen the range of their clients
- The want to increase the level of their non-medical services
- The want to suggest their customers a new service - support in workplace programs implementation

### 1. Business profile - general
_Use the background information to create a business profile for New Century Wellness Group, and indicate areas where more information will be needed. The profile should include an organization chart of the office staff. You can create the chart using Microsoft Word or a similar program, or you can draw it by hand. In Word 2010, click the Insert tab on the Ribbon, then Smart Art, then Organization Chart_.

**Name**: New Century Wellness Group

**Address**: Brea, California

**Status**: live company

**Contact**: Dr. Jones, Dr. Garcia, Lisa Sung

**Partners/managers**: Dr. Jones, Dr. Garcia

**Year established**: 5 years ago

**Capital managed**: n/a, additional information is needed

**Industry preferences**: preventive medicine and traditional medical care

**Current permanent staff**: at least 17 (mentioned in the document), 21 according to the book

**Number of customers**: 3500 patients,  275 employers

**Mission**:
- to promote and support programs that encourage the wellness of our clients' employees through education and initiatives that:
  - Encourage habits of wellness
  - Increase awareness of factors and resources contributing to well-being
  - Inspire and empower individuals to take responsibility for their own health
  - Support a sense of community
-  to support the adoption of attitudes that contribute to positive well-being and providing information, activities and services designed to support healthy lifestyle choices.

**Competitors**: The clinic has competition from other health care providers, but no other clinic offers the same range of services.

#### Organisation structure

<img src='http://g.gravizo.com/g?
@startuml;
usecase dir as "Board:;
--;
Dr.Jones, Dr.Garcia";
usecase found as "CEO:;
--;
Dr.Jones";
usecase office as "Office manager:;
--;
Anita Davenport";
usecase medrec as "Medical records\n maintenance:;
--;
Susan Gifford";
usecase hr as "HR and employee\n benefits:;
--;
Fred Brown";
usecase tax as "Payroll, tax reporting,\n profit; distribution:;
--;
Corinne Summers";
usecase acc as "Accounts recievables:;
--;
Tom Capaletti";
usecase ins as "Insurance billing:;
--;
Tammy Alipio";
usecase app as "Customers support and\n appointments:;
--;
Lisa Sung";
usecase suppl as "Office and medical\n supplies:;
--;
Carla Herrera";
dir -down-> found;
found -down-> office;
office -down-> medrec;
office -down-> hr;
hr -down-> tax;
office -down-> acc;
office -down-> ins;
office -down-> app;
office -down-> suppl;
found -down-> (4 doctors);
found -down-> (3 physical\n therapists);
found -down-> (4 nurses);
@enduml
'>

### 2. Business processes
_Identify six business processes that New Century performs, and explain who has primary responsibility for each process. Construct the Organizational chart structured by department and basic business-processes._

#### Business processes

 Name | Who's responsible | Data required  |  Data generated
--- | --- | --- | ---
Medical supplies ordering	| Carla Herrera |	Inventory lists, supplies usage records, suppliers info	| Updated inventory lists, supplies orders and bills
Patient intake |	Lisa Sung	| Doctor availability and patients personal and financial data |	Patients and insurance records; doctors' schedule
Insurance billing	| Tammy Alipio |	Patients personal and financial data, insurance contracts |	Bills sent to insurance companies and patients
Accounts recievable	 | Tom Capaletti |	Payments and invoices |	Accounting data
Payroll	| Corrine Sommers (Fred Brown) | Employee list, pay rates, employee's accounts info, employee's schedules, employee's benefits lists | Payments to the employee, records about these payments
Hiring a new stuff member	| Fred Brown |	New stuff member's personal info |	New payroll, set of benefits

#### Organizational Chart correction

I don't think any correction is needed. The chart above corresponds to the business processes.

### 3. Business Model Canvas
_Form a business profile  of the  New Century. With use template of  Business model canvas try to construct it for case._  

#### Partners
- IT company (support and outsourcing)
- Other clinics/hospitals
- Fire department
- Police department
- Local MD specialists
- Ambulance service
- Medical universities
- Regulators&Government

#### Activities
- Patient services
- Patient intake
- Logistics
- HR
- Marketing
- b2b's customers employee services
- b2b's customers services

#### Resources
- Clinic staff
- Medical equipment
- Patient management systems
- tech (IT) staff

#### Offerings
- Patient facilities
- Prevention services
- Diagnosis
- Wellness Communities building
- Support programs promotion

#### Benefits
- Learning about their conditions
- Emotional support in wellness
- Family stability
- Happiness and productivity levels growth in companies

#### Customer Relationships
- Personal assistance
- Dedicated Personal Assistance
- Automated Services
- Communities
- Co-creation

#### Channels
- Websites
- Social media
- Companies' Channels
- Mobile applications
- TV Commercials

#### Cost structure
- Salaries and trainings
- Marketing/advertising
- IT outsourcing
- Claims fixes
- Medical equipment
- Clinic maintenance

#### Revenue streams
- Usage fee
- Subscription Fees
- Non-profit tax benefits
- Charging insurance for services
- Fundation events

### 4. Customers’ Model
_Describe  customers’ model of New Century. Find additional material about customer modeling. On what firm' goals a customers loyalty influences ? Explain why this  plays important role in the studied case ? Also describe what data is required and what information is generated by each process._

Based on the high number of patients served by New Century, it would be already beneficial to introduce customer segmentation. This approach, which has been used for many years in areas such as retail, would allow the company to better engage patients and the offered services could be more aligned with the needs of the patients such as personalized services and products. Through an successfull customer segmentation the following objectives could be achieved:

* Improved profitability
* Identified valuable customers
* Better served high priority customers

Moreover, a customer segmenation strategy can positively influence customer loyality, enhance customer satisfaction, and improve compatitive advantage of the company. However, it is essential to set up a suitable implementation strategy for the customer segmenation. Such a strategy could consists of the following development cycles:

* Indetify business context
* Customer segmentation
* Planning and exection
* Institutionalization

**Identify business context**

Firstly, the customer needs has to be identified. The output of this phase is a list of customer needs.

**Customer segmentation**

Based on the identified customer needs, meaningful and measurable unique, homogenous customer groups can be created. The customer segmentation is performed according to different criteria based on needs, behaviours and other traits of the patients.

As an example, the organization of the could be done by the following characteristics:

* Psychographics
* Attitudes
* Demographics (age, gender, income,...)
* Values
* Lifestyle

Another approach could be done according to the lifestyle status:

* New customer
* Frequent customer
* VIP customer
* Nonactive customer

Finally, another possibility would be based on value segments for frequent customers:

* less than 100 dollars in last 3 months
* more than 100 dollars in last 3 months
* more than 500 dollars in last 3 months

The output of this phase is a list of customer segments with defined, measurable characteristics.

**Planning and execution**

In this the customer segmentation supporting system is planned and set up and the patients are initially added into a particular customer segment.

**Institutionalization**

In this phase a long term perfomrance measurement of each segment is done. After the analysation of the results, the customer segments are adjusted. The customer segmentation should be updated on regular bases. Through this approach over time a market competition change.

The introduction of the customer segmentation would be aligned with the company's strategic goals. Firstly, it would increase customer loyality. Secondly, it would attract new customers. Finally, this would result in a higher profitability.

### 5. IT System Recommendations
_Based on what you know at this point, is it likely that you will recommend a transaction processing system, a business support system, or a user productivity system? What about an ERP system? Explain your reasons._

As it was mentioned in case study, the main goal of the new IT system implementation is to support the current clinic’s operations and future growth. The actual processes in the clinic are based on the paper documents and some legacy systems.

The main recommendation is to focus on the marketing strategies that will allow to make a client vortex for the companies that want to make a "boxed" service of workplace wellness and prevention medicine.
As they seem to be not very experienced with IT and marketing we'd recommend:
- hire 1-2 experienced marketing professionals who will develop the marketing strategies and make them outsource most of the low-level work in this sphere.  
- the same thing can be done with IT. We can suggest to outsource the IT support for the clinic's IT systems (see below) and IT support for marketing activities. 1 or 2 IT specialists (or managers) should be hired to coordinate all the outsourced work and make the IT starategy.

As we can see in the business processes table above, some processes require the same income data and some of them depend on the data produced by other processes. So reducing the paper flow can cause a significant speed-up in data flows and the rise of efficiency of the processes.

We don’t think that implementing only one of suggested systems is enough for any business.
So, we suggest a combination of
- a user productivity system can help with staying on the schedule for all the employee and can help managing the communications with the customers;
- a transaction processing system will help the monetary side of the company in managing the accounts receivable and insurance issues;
- a business support system as each part of the company needs access to some part of information in order to do their job. Doctors need information to help patients. Patient billing requires customer personal information as well as insurance information. The appointment manager needs information on the doctors' schedules.

If the amount of resources for IT transformation is limited we can suggest a step-by-step (or agile) implementation in the following order:
- transaction processing system
- user productivity system
- a business support system

The ERP system is not needed as there is no need for everyone to get access to all of the company data.

### 6. Goals
_What is the goals of change New Century Wellness Group through information system development? Construct tree of goals._

![Goal tree img][goal-tree]

### 7. Performance and Strategy
_With use BSC template  try to determine  KPI (for goals, for business activities), try to construct strategy map._

#### Critical Success Factors
Based on the mission of the company we can determine the CSF<sup>1</sup>:
- Clients' executives sponsorship and visible support
- Embedded in organization’s strategic direction and frameworks
- Measurement - baseline and ongoing
- Program alignment with demographic profile, needs and interests of customers population
- Effective marketing services to companies and individuals
- Recruitment of experienced managerial talent
- Clients accessibility
- Dedication and hard work of the founders
- Raising productivity
- Lowering overall costs
- Medical supplies quality
- Medical supply deliverance accuracy

#### KPI
Thus the sample KPIs can be suggested:
Title | Rationale | Target  |  Data Source(s)
--- | --- | --- | ---
Amount of b2b clients | More companies trust the NCWG => better promotion of wellness | _ | Clients DB
AVG % of b2b's employee involved in the program | The wellness community in the company size | _ | Customer surveys
AVG % of returning  b2с customers | Wellness community quality | _ | Clients DB, customer surveys
Accordance between demographic profile of the design client and a real client | The better we predict the client's profile the more relevant service can be suggested | Marketing service | Client records, surveys

#### The Performance Prism <sup>2</sup>

![pp](https://github.com/BigDataHSE2016/m01-02-sa/blob/master/m02-gr-prj/team-xxx/perf-pr.png?raw=true)

##### Stakeholder satisfaction
Who are our stakeholders? | What do they want?
--- | ---
Investors | a return on their investment in the form of capital gains, reward for loyalty in the form of dividends or interest
Investors | accurate results and reports from the organisation
Investors | faith in the management team
Customers | ‘fast, right, cheap and easy’ + confidence + information accessibility
Employees | interesting work, wish to be cared for by their employer, to learn transferable skills and to receive decent level of remuneration
Suppliers | a relationship that allows them to be profitable, and enables their business to grow
Suppliers | receive feedback on their performance
Suppliers | want to be trusted
Regulators | act legal, fair, safe and true

##### Stakeholder contribution
Stakeholder | What do we want and need from them?
--- | ---
Investors | capital for growth
Employees | skill growth, confidence in data, people-based culture
Regulators |  lack of bureaucracy, confidence in data

##### Strategies
(what strategies do we need to put in place to satisfy the wants and needs of or our stakeholders while satisfying our own requirements too)
- create a marketing department
- develop a marketing plan
- develop a promotional campaign framework for implementing into b2b clients' companies (using newsletters, signs, bulletin boards, computers, and other media available within the workplace)
- develop a promotional campaign for attracting and maintaining b2c customers
- proactive availability of information
- promote superiority of core service


##### Processes
(what processes do we need to put in place to enable us to execute our strategies)
- processes of gathering statistics about clients, suppliers and employee
- customer service strategy
- proactive traces
- customer access tools

##### Capabilities
(what capabilities do we need to put in place to allow us to operate our processes?)
- teamwork
- technology
- additional fundation/investments
- marketing and IT professionals to join the teamwork
- product offering

### 8. The Environment
_Think about environment of New Century Wellness Group. List the external environment element._

#### SWOT-analysys

![SWOT img][swot-img]

#### External environment elements

External environment elements lst:
- individual customers and b2b customers (employers who provide provide insurance coverage for employee wellness and health maintenance)
- insurance companies and suppliers that provide medical and office equipment
- competitors
- government policies and their local implementations
- financial organizations – the banks, which gives money to business improvement
- natural forces
- social and cultural changes that influence on the lifestyle, public opinion and fashion  trends
technology

### 9. Context Diagram
_Prepare a context diagram for New Century's information system._

<img src='http://g.gravizo.com/g?
@startuml;
node p as "Patient";
node ic as "Insurance Company";
node oe as "Offce Employee";
node pr as "Provider";
node gov as "Gevernment";
component oms as "0\n---\nNew Century\nInformation System ";
p -right-> oms : patients payments;
p -right-> oms : patients inputs;
oms -left-> p : patients reports\nand outputs;
ic -down-> oms : insurance payments;
oms -up-> ic : claims;
oms -> oe : reports and outputs;
pr -down-> oms : providers inputs;
oms -up-> pr : reports and outputs;
gov -up-> oms : orders and recommendations;
oms -down-> gov : reports;
@enduml
'>

### 10. 0 DFD Diagram
_Prepare a diagram 0 DFD for New Century. Be sure to show numbered processes for handling appointment processing, payment and insurance processing, report processing, and records maintenance. Also, prepare lower-level DFDs for each numbered process._

![0dfd img][0dfd-img]

### 11. Data Stores and Data Flows
_Prepare a list of data stores and data flows needed for the system. Under each data store, list the data elements required._

Data stores:
- Patient medical history. Data elements required:
  - Patient ID
  - Patient Name
  - Patient age  
  - Patient health records
  - Patient surgeries
  - Patient medicine taken at current time

Data flows:
- Gives information
- Opens new file Update   
- Submit information
- Update medical history
- Make payments
- Accept/reject claims
- Payment clain  
- Process payment
- Recept  

### 12. Data Dictionary
_Prepare a data dictionary entry and process description for one of the system's functional primitives._

Clinical Data System | Data process description
--- | ---
System | Medical history
Name | Generate information process
Purpose | Submit new information about the clients, update the patients medical history's data store and generate the payments
Input data flows | Submit information about the clients   
Output flows | Update the medical history and the amount of payments
----

**Footnotes:**

1. See Critical success factors (ACCA) in [1](http://www.accaglobal.com/ng/en/student/exam-support-resources/professional-exams-study-resources/p3/technical-articles/critical-success-factors.html)
2. The Performance Prism (ACCA) in [2](http://www.accaglobal.com/caribbean/en/student/exam-support-resources/professional-exams-study-resources/p5/technical-articles/performance-prism.html)

[goal-tree]:
https://github.com/BigDataHSE2016/m01-02-sa/raw/master/m02-gr-prj/team-xxx/goal_tree.png

[swot-img]: https://github.com/BigDataHSE2016/m01-02-sa/raw/master/m02-gr-prj/team-xxx/swot.png

[diag1]: https://github.com/BigDataHSE2016/m01-02-sa/raw/master/m02-gr-prj/team-xxx/diag1.png

[0dfd-img]:
https://github.com/BigDataHSE2016/m01-02-sa/blob/master/m02-gr-prj/team-xxx/0dfd.png?raw=true

[pp-img]:
https://github.com/BigDataHSE2016/m01-02-sa/blob/master/m02-gr-prj/team-xxx/perf-pr.png?raw=true

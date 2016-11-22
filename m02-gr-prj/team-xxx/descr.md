# Team Project - XXX
The original assignment is [here](https://docs.google.com/document/d/13vUmeWuM2COGP6vKGhU66AC_evl0T1YajcbFQybSm5Q/edit).

## The team project’ tasks description:
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

**Mission**: New Century Health clinic was founded by two doctors Timothy Jones and Dolores Garcia who decided to combine their individual practices with a focus on preventive medicine by helping patients maintain health and fitness and by providing traditional medical care.

**Competitors**: The clinic has competition from other health care providers, but no other clinic offers the same range of services.

#### Organisation structure
<img src='http://g.gravizo.com/g?
@startuml;
usecase found as "Founders:;
--;
Dr.Jones, Dr.Garcia";
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
1 | 2 | 3 | 4
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

#### KEY PARTNERS
##### Who are our Key Partners?
##### Who are our key suppliers?
##### Which Key Resources are we acquiring from partners?
##### Which Key Activities do partners perform?

MOTIVATIONS FOR PARTNERSHIPS:
- Optimization and economy
- Reduction of risk and uncertainty
- Acquisition of particular resources and activities

#### KEY ACTIVITIES

##### What Key Activities do our Value Propositions require?
##### Our Distribution Channels?
##### Customer Relationships?
##### Revenue streams?

CATEGORIES
- Production
- Problem Solving
- Platform/Network

#### KEY RESOURCES
##### What Key Resources do our Value Propositions require?
##### Our Distribution Channels?
##### Customer Relationships?
##### Revenue Streams?

TYPES OF RESOURCES:
- Physical
- Intellectual (brand patents, copyrights, data)
- Human
- Financial

#### VALUE PROPOSITIONS
##### What value do we deliver to the customer?
##### Which one of our customer’s problems are we helping to solve?
##### What bundles of products and services are we offering to each Customer Segment?
##### Which customer needs are we satisfying?

CHARACTERISTICS
- Newness
- Performance
- Customization
- "Getting the Job Done"
- Design
- Brand/Status
- Price
- Cost Reduction
- Risk Reduction
- Accessibility
- Convenience/Usability

#### CUSTOMER RELATIONSHIPS
##### What type of relationship does each of our Customer Segments expect us to establish and maintain with them?
##### Which ones have we established?
##### How are they integrated with the rest of our business model?
##### How costly are they?

EXAMPLES:
- Personal assistance
- Dedicated Personal Assistance
- Self-Service
- Automated Services
- Communities
- Co-creation

#### CHANNELS
##### Through which Channels do our Customer Segments want to be reached?
##### How are we reaching them now?
##### How are our Channels integrated?
##### Which ones work best?
##### Which ones are most cost-efficient?
##### How are we integrating them with customer routines?

Channel phases:
1. Awareness: How do we raise awareness about our company’s products and services?
2. Evaluation: How do we help customers evaluate our organization’s Value Proposition?
3. Purchase: How do we allow customers to purchase specific products and services?
4. Delivery: How do we deliver a Value Proposition to customers?
5. After sales: How do we provide post-purchase customer support?

#### COST STRUCTURE

##### What are the most important costs inherent in our business model?
##### Which Key Resources are most expensive?
##### Which Key Activities are most expensive?

IS YOUR BUSINESS MORE
- Cost Driven (leanest cost structure, low price value proposition, maximum automation, extensive outsourcing)
- Value Driven ( focused on value creation, premium value proposition)

SAMPLE CHARACTERISTICS
Fixed Costs (salaries, rents, utilities)
Variable costs
Economies of scale
Economies of scope

#### REVENUE STREAMS

##### For what value are our customers really willing to pay?
##### For what do they currently pay?
##### How are they currently paying?
##### How would they prefer to pay?
##### How much does each Revenue Stream contribute to overall revenues?

TYPES
Usage fee
Subscription Fees
Lending/Renting/Leasing
Brokerage fees

FIXED PRICING
List Price
Product feature dependent
Customer segment dependent
Volume dependent

DYNAMIC PRICING
Negotiation( bargaining)
Yield Management
Real-time-Market1


### 4.
_Describe  customers’ model of New Century. Find additional material about customer modeling. On what firm' goals a customers loyalty influences ? Explain why this  plays important role in the studied case ? Also describe what data is required and what information is generated by each process._

### 5.
_Based on what you know at this point, is it likely that you will recommend a transaction processing system, a business support system, or a user productivity system? What about an ERP system? Explain your reasons._

### 6. Goals
_What is the goals of change New Century Wellness Group through information system development? Construct tree of goals._

![Goal tree img][goal-tree]

### 7.
_With use BSC template  try to determine  KPI ( for goals, for business activities)  , try to construct strategy map._

### 8.
_Think about environment of New Century Wellness Group. List the external environment element._

#### SWOT-analysys

![SWOT img][swot-img]

### 9.
_Prepare a context diagram for New Century's information system._

### 10.
_Prepare a diagram 0 DFD for New Century. Be sure to show numbered processes for handling appointment processing, payment and insurance processing, report processing, and records maintenance. Also, prepare lower-level DFDs for each numbered process._

### 11.
_Prepare a list of data stores and data flows needed for the system. Under each data store, list the data elements required._

### 12.
_Prepare a data dictionary entry and process description for one of the system's functional primitives._

----

[goal-tree]: https://www.dropbox.com/s/esftt80zscogv6k/goal_tree.png?dl=0

[swot-img]: https://www.dropbox.com/s/3amof92ebz12hzn/swot.png?dl=0

# JOB Ticket   
<<<<<<< HEAD
=======
<img decoding="async" src="../../picture/Icon/carrier.jpg" width="20%"> 
>>>>>>> a7914bb43b2d9ac3c83bba33e05b59c47d19deac

<img decoding="async" src="picture/../../../picture/Icon/carrier.jpg" width="20%"> 

**Requesting Organization: WC chiller platform**
**Operational Owner: Xijia Zhu**
**Project Title: 19MV4 System Design KPI Selection Support**
**Program Name: 550-1100Ton Centrifugal Platform**


**Project Objectives & Benefits** <font color="blue">_(High level summary of what the overall objective is and benefits of executing this work.  To be updated as appropriate)_ </font>

* Execute 1000 Tonnage MV4 KPI selection to support 19MV4 KPI tracking in system design (Also a cross-check with system engineering team).
* Develop KPI selection tool / method which focus intelligently selection of best KPI case, to increase engineering work efficiency.
* Get prepared for improving MV4 KPI selection by data science process / workflow.
* Guide a web-online help system to better present whole workflow. 

**Ownership** <font color="blue">_(To include project owner and key team members)_</font>

Project Lead: Dong Liu
Project Team:
Yang, Gan; Yang, Georgina; Li, Cheng

**Internal Customers** <font color="blue">_(Indicate the customer(s) that are reliant on the completion of this work)_</font>
* Xijia Zhu: Product MBD Engineer, SRDC Centrifugal
* Jenny Si: Associate Engineering Manager, SRDC Centrifugal
* Qianyu Yang: Product System Engineer, SRDC Centrifugal
* Alireza Behfar: Engineering Project Leader, CML Chillers - Applied
  
**Other Stakeholders:** 
* Mingyu Wang: ELP Rotation Engineer, SRDC

**Internal Suppliers** <font color="blue">_(Indicate internal supplier(s) and/or items (labs, funding, etc.) that are required to complete the objective)_</font>
* Gang Pan: Engineering Project Leader, SRDC Centrifugal
* Jia Li: Senior Product System engineer, SRDC Centrifugal
* Cong Ding: Product System engineer, SRDC Centrifugal
* Xijia Zhu: Product MBD engineer, SRDC Centrifugal

**Winning Solution/Requirements / KPIs** <font color="blue">_(To be updated as appropriate, add table rows as required)_</font>

Product feature: The key deliverables are to include the following features. 
* Bring out best solution case for 1000Ton KPI selection, which includes R515B and R134a in AHRI conditions for both CLT and Asia region.
* An optimization tool / method based on excel to reach best solution case among thousands of selection cases based on simple heat transfer area comparison in heat exchanger
  * Accurate optimization: Give exact ikw/Ton, WSPD, cost(optional) target, only returns 1 selection.
  * Range optimization: A tolerance on ikw/Ton or WSPD target, returns top 3 selection in different measurement dimension.

The success of this project will be measured: 
1. On time and on quality delivery before 4/14, based on clear inputs ready on 4/4 and on time QA.
2. Execution time for accurate optimization should be less than 30 sec., and range optimization less than 1 min. 
3. Document for recording workflow:
    * Executable website-based workflow help file guidance;

**Schedule** <font color="blue">_(Milestones & Deliverables w/ Planned Dates) (To be updated as appropriate, add table rows as required)_</font>

| **Activity** | **Owner** | **Date** |
| :----| :---- | :---- |
| Kick off MV4 KPI selection support meeting | Dong Liu | Mar. 31, 2023 (complete) |
| Prepare Job ticket  | Xijia Zhu | Apr. 4, 2023 |
| Bring out 1000Ton KPI selection solution  | Dong Liu | Apr. 14, 2023 |
| Bring out a tool / method to support two kinds of optimization  | Dong Liu | Apr. 14, 2023 |
| Build initial website-based help file for workflow, based on Xijia’s contents.  | Georgina Yang, Mingyu Wang, Xijia Zhu | Apr. 30, 2023 |

**Project Costs:** Not Applicable

**Related Items** <font color="blue">_(Identify related items such as Technical Approach, Project Plan, Staffing Plan, Risk Plan, etc.  Can include information directly below or add Hyperlinks to documents in Windchill.)_</font>

**Approval / Revision History** <font color="blue">_(To be updated as appropriate per the approval protocol below)_</font>




Appendix1: KPIs Input Conditions

|  | Asia | NA |
| :-----| :---- | :---- |
| **BOLT Model** | MV4_DV_Subclr | MV4_DV_Subclr |
| **Capacity, Ton** | 1000 | 1000 |
| **Refrigerant** | R134a | R515B |
| **Eco** | Yes | Yes |
| **Condition** | AHRI | AHRI |
| **Calculation Type** | Full load / IPLV | Full load / IPLV |
| **Z_Uey correction** | No | No |
| **Diameter_CheckValve** | 10 | 10 |
| **Dia_Dischrage Pipe** | 10 | 10 |
| **Dia_Econ Vapor Pipe** | 5 | 5 |
| **Dia_ICP** | 12 | 12 |
| **Dia_Isolation Valve** | 10 | 10 |
| **Dia_Suction Pipe** | 12 | 12 |
| **Cooler Tubing** | ESP_100_025_R134a | B4HSL_075_025_R134a |
| **Condenser Tubing** | SPKIII_075_025_R134a_HX1to6 | C_SL_075_025_R134a |
| **Cooler Passes** | 2 | 2 |
| **Condenser Passes** | 2 | 2 |
| **Cooler bundle family** | See attached appendix4: HX Bundle Family | See attached appendix4: HX Bundle Family |
| **Condenser bundle family** | See attached appendix4: HX Bundle Family | See attached appendix4: HX Bundle Family |
| **Compressor eta** | See latest table in attached appendix5 | See latest table in attached appendix5 |
| **Mechanical loss** | See latest table in attached appendix5 | See latest table in attached appendix5 |
| **Motor efficiency** | See latest table in attached appendix5 | See latest table in attached appendix5 |
| **VFD efficiency** | See latest table in attached appendix5 | See latest table in attached appendix5 |

Appendix2: Standard Work for Simulation

<<<<<<< HEAD


<a href="https://carcgl.sharepoint.com/:w:/r/sites/MINGYU/Shared%20Documents/General/How%20to%20add%20new%20refrigerant%20in%20BOLT.docx?d=w8dbba90e252e41cebaa1af14f69af176&csf=1&web=1&e=un9Qz5" alt="How to add new refrigerant in BOLT">How to add new refrigerant in BOLT</a>



<a href="https://carcgl.sharepoint.com/:w:/r/sites/MINGYU/Shared%20Documents/General/How%20to%20simulate%20MV4%20Bolt%20models_20220719.docx?d=w94c2a824ed6e4477a11e99533ebe784f&csf=1&web=1&e=zMtEuF" alt="How to simulate MV4 Bolt models">How to simulate MV4 Bolt models</a>


=======
<img decoding="async" src="../../picture/Icon/word.jpg" width="6%">

<a href="https://carcgl.sharepoint.com/:w:/r/sites/MINGYU/Shared%20Documents/General/How%20to%20add%20new%20refrigerant%20in%20BOLT.docx?d=w8dbba90e252e41cebaa1af14f69af176&csf=1&web=1&e=un9Qz5" alt="How to add new refrigerant in BOLT">How to add new refrigerant in BOLT</a>

<img decoding="async" src="../../picture/Icon/word.jpg" width="6%">

<a href="https://carcgl.sharepoint.com/:w:/r/sites/MINGYU/Shared%20Documents/General/How%20to%20simulate%20MV4%20Bolt%20models_20220719.docx?d=w94c2a824ed6e4477a11e99533ebe784f&csf=1&web=1&e=zMtEuF" alt="How to simulate MV4 Bolt models">How to simulate MV4 Bolt models</a>

<img decoding="async" src="../../picture/Icon/word.jpg" width="6%">
>>>>>>> a7914bb43b2d9ac3c83bba33e05b59c47d19deac

<a href="https://carcgl.sharepoint.com/:w:/r/sites/MINGYU/Shared%20Documents/General/How%20to%20run%20KPI%20in%20MR_20220719.docx?d=w114bc27ae1ec412e83fbf240e1ffef68&csf=1&web=1&e=gov1wq" alt="How to run KPI in MR">How to run KPI in MR</a>


For any link of BOLT, better to download through svn, instead of the link in standard work, since the serve location is moved to other place according to Corporation policy.
http://vmchqm0pa008.carcgl.com/svn/CentrifugalChiller/MV4ConceptPackage/?r=22

Appendix3: Template for Speeding up Simulation and Analyze Process

<<<<<<< HEAD



<a href="https://carcgl.sharepoint.com/:x:/r/sites/MINGYU/Shared%20Documents/General/FlashTank.xlsm?d=w9b248897bea146f5929cf98a826ac16f&csf=1&web=1&e=8UtiyA" alt="Flash Tank_Subcooler_IPLV">Flash Tank_Subcooler_IPLV</a>


=======
<img decoding="async" src="../../picture/Icon/excel.png" width="5%">

<a href="https://carcgl.sharepoint.com/:x:/r/sites/MINGYU/Shared%20Documents/General/FlashTank.xlsm?d=w9b248897bea146f5929cf98a826ac16f&csf=1&web=1&e=8UtiyA" alt="Flash Tank_Subcooler_IPLV">Flash Tank_Subcooler_IPLV</a>

<img decoding="async" src="../../picture/Icon/excel.png" width="5%">
>>>>>>> a7914bb43b2d9ac3c83bba33e05b59c47d19deac

<a href="https://carcgl.sharepoint.com/:x:/r/sites/MINGYU/Shared%20Documents/General/MV4%20KPI%20Case.xlsx?d=w19d4cc361584442085eff33325d08467&csf=1&web=1&e=tLKCgN" alt="MV4 KPI cases_V1_221104">MV4 KPI cases_V1_221104</a>

Appendix4: HX Bundle Family

<<<<<<< HEAD

=======
<img decoding="async" src="../../picture/Icon/excel.png" width="5%">
>>>>>>> a7914bb43b2d9ac3c83bba33e05b59c47d19deac


<a href="https://carcgl.sharepoint.com/:x:/r/sites/MINGYU/Shared%20Documents/General/MV4%20HX%20Family.xlsx?d=wa783add64aab47c7a2601e27d9a484b8&csf=1&web=1&e=sEqgUd" alt="MV4 HX Family">MV4 HX Family</a>

Appendis5: Power train compressor & mechanical loss & motor & VFD efficiency and loss

<<<<<<< HEAD

=======
<img decoding="async" src="../../picture/Icon/excel.png" width="5%">
>>>>>>> a7914bb43b2d9ac3c83bba33e05b59c47d19deac

<a href="https://carcgl.sharepoint.com/:x:/r/sites/MINGYU/Shared%20Documents/General/Compressor%20%26%20Motor%20Efficiency.xlsx?d=w22335d7cc57c4cfe8e5205fa5c681e02&csf=1&web=1&e=F4vsgN" alt="Compressor & Motor Efficiency">Compressor & Motor Efficiency</a>

Appendix6: KPI targets from PRD

<<<<<<< HEAD

=======
<img decoding="async" src="../../picture/Icon/excel.png" width="5%">
>>>>>>> a7914bb43b2d9ac3c83bba33e05b59c47d19deac

<a href="https://carcgl.sharepoint.com/:x:/r/sites/MINGYU/Shared%20Documents/General/KPIs%27.xlsx?d=w4a7a8cf4e3384a7db696458252f285ec&csf=1&web=1&e=vIuoCI" alt="KPIx'">KPIx'</a>


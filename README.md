java c
IOM205
1st SEMESTER 2024/25 Group Coursework
BSc Information Management  Information Systems
Advanced Database Management
Coursework Title:
Group coursework: Designing a Database
Scenario
ContextUniBooks is a small start-up company specialising in second-hand textbooks. The company buys surplus academic books in bulk from publishers but also buys individual books from students. The books are advertised and sold via the company’s website. You have been approached to develop a database system for the company. The system needs to be able to store details of the books held in stock, to process incoming books and to record all sales. The system will also need to be able to perform. other functions, such as producing invoices and different management reports.
Specification
UniBooks supplies textbooks to university students at discounted prices. The company obtains stocks of books directly from publishers and students:
•    Usually, UniBooks is able to purchase large stocks of books from publishers for as little as 30% of the cover price.
•    After completing a course, a student may wish to sell his/her unwanted textbooks. UniBooks buys textbooks directly from students for 20% of the cover price.
•    All books  are sold to the public for  80% of the cover price. There is also a standard charge of ¥10 for postage and packaging, regardless of the size of the order placed.
The current system suffers from several limitations:
•    Occasionally, a customer will order a book that is not held in stock (e.g. print on demand titles). A staff member will need to search for details of the book’s publisher, and then contact the publisher to  see if UniBooks can obtain  a  copy  of the book. The  current system does not provide a search facility that can be used to locate a publisher’sdetails.
•    When stocks of a given book run out, it is left to a staff member to reorder a fresh supply from publishers. This raises two problems: customer orders are delayed until new stocks of the book arrive, and there is inconsistency regarding the number of books ordered from publishers. As an example, sometimes too few or too many books are ordered, resulting in further delays to customers or increased inventory costs. Ideally, it should be possible to set reorder levels and reorder quantities for books to improve inventory control.
•    Management   information    takes   a    great    deal   of   time    to   produce    since   it    is collected/processed  manually.  As  a  result,  managers  are  only  able  to  see  important information, such as sales figures, on a monthly basis. Ideally, management information should be available on demand.
•    Most publishers offer discounts based on order size (in addition to the discount over cover price). In general, discounts are given as shown below in Table 1. At present, UniBooks often fails to claim the discounts it is entitled to.
Table 1: Discount from Publishers
Copies Ordered
Discount
(% Of Total Order Value)
20 - 49
5
50 - 99
7.5
100 - 199
10
More than 200
12.5
•    UniBooks offer discounts to  customers based on order size (in addition to the discount over  cover  price) .  Currently,  these  discounts  are  processed  manually,  and  the  sales information is not recorded accurately. In general, discounts are given as shown below in Table 2.
Table 2: Discount to buyers
Order Size
Discount
(% Of Total Order Value)
10 -19
5
20 - 29
7.5
30 - 39
10
More than 40
12.5
Task Details/Description:The  primary  task  for  your  group  is  to  go  through  the  scenario  context  and   specification  to understand and analyse the company’s data and information requirements. This should help you to design an appropriate database structure, which can meet the requirements of the organisation. In developing,  realising  and  implementing  the  design,  your  group  must  create  sample  records (dummy data) for the identified entities.This is a group task and each member of the group must complete an equal share of the work. Each group will be asked to review its own performance and may be given an opportunity to redistribute  some  of the  marks  awarded  for  the  work  (in  case  of  conflicts  within  the  group members). A list of tasks (not exhaustive) that you will need to perform. as a group in completing this coursework are given below.
Tasks:
•    TG1: Decide upon the entities to create tables and corresponding attributes you will need, to address a range of requirements stemming from the scenario and specification. Example entities and this is not an exhaustive list: customer, book, student, employee, order etc.
•    TG2: Create an Entity-Relationship Model (ERM) using Microsoft Access to address the requirements. This model must be normalised to reduce data redundancy and improve data integrity.
•    TG3:  Include  sample  records  (at least  four)  in  Microsoft Access for  each table  after developing  the  ERM  and  include  validation  of  the   attribute  types,  constraints  and primary/for代 写IOM205 Advanced Database Management 2024/25
代做程序编程语言eign keys.
•    TG4: Reflect upon your ERM, discuss  two issues/limitations associated with the design and anticipated operation of your database , and its impact on the business, i.e. how it might affect the business.
All these above the tasks will help you to make progress and completing this group coursework. Upon  completion of  the group  coursework, the  deliverables produced will provide  a suitable starting point for  the  individual  coursework.  Additionally, feedback provided  on  the  group coursework will aid in refining the work you will undertake in the individual courseworkPlease ensure you have created one or more back-ups of your work in suitable places using appropriate mediums available to you, to avoid losing the work you may have already done.
Your work will be assessed on robustness, correctness, design meeting the business requirements, and the overall quality of your design.
Deliverables:
You        MUST         submit         the         following         to         complete        this         coursework.
•    Deliverable 1: The report (as a word or PDF document) should not exceed 500 words (+/- 10%). Estimated word limits for each section are provided below to help you write the report.
•    Deliverable 2: Entity Relationship  Model as a PDF document from Microsoft Access (Further instructions on how to save Entity Relationship Model as a PDF from Microsoft Access will be uploaded in blackboard in due time)
•    Deliverable 3: Your Microsoft Access Database File
Contents of the report [deliverable 1]
•    GD1: The front cover page of the report must include your group number and student number for each member in the group. [No word count applies]
•    GD2: Briefly explain the normalisation and resolving m:m relationship process with the aid of a suitable example (for each part - may use the same example) drawn from your own ER model. You should not explain normalisation and its objectives, rather explain how you have employed normalisation and resolved m:m relationship in your ER model (using suitable at least one suitable example).    [estimated word limit – not more than 300 words]
•    GD3:  A  brief  discussion  of  two  issues  associated  with  the  design  and  anticipated operation of your database, and how these issues may impact the business/organisation. You may discuss any issues/problems for which a solution is not yet clear, or where there are competing alternative designs.  [Estimated word limit – not more than 200 words].
Please note, you MUST at a (or the) minimum discuss two issues suitably in your report (as stated above) to score a passing mark for this component.
Note
1.   Please  refer  to  the  grading  criteria  at  the  end  of this  document,  to  know  how  each component or a combination of components will be graded.
2.   You  will  submit  three  separate  files  electronically.  Further  instructions  about  the submission will be provided in Week 4 lecture.
Feedback Methods:
Formative feedback will be available before the final submission, to help you develop  and refine your work. This will include the following methods:


•    Weekly labs - these will include tasks and activities (related to the coursework) to help you apply knowledge from the lectures, develop your own solution and obtain feedback in the session to help you to improve your work. You are therefore encouraged to engage during the lectures and workshops to make progress, receive feedback, clarify doubts, and refine your work.
•    Assignment  clinic  -  In  week  5,  there  will  be  sessions  dedicated  to  reviewing  the assessment requirements, clarify areas of doubt and obtain further feedback on your work, before the final submission.
•    Office hours - You are advised to use office hours early in the term, so you have time to acton the feedback.
•    Discussion  Forum  in  LM - you can ask questions, discuss among peers and receive responses via the discussion forum.   Turnaround time for a response from the module tutor is 2-3 working days or it will be given in the following lecture.
Summative feedback will be provided after the final submission. This accompanies your final grade and uses the assessment criteria shown at the end of this document.
Submission:
The coursework is going to be submitted electronically. Further instructions about how to do this will be given later.
You will submit 3files including:
•    Group report (either asapdfor word document)
•    Entity relationship model (as a pdf saved from Microsoft Access)
•    Microsoft Access database file.
Assessment Weighting for the Module:
The weight of the group coursework is 30%
Assessment Criteria
Marking guidelines for this coursework are provided at the end of this document.
Learning Sessions Relevant to this Coursework
•    Week 1: Introduction to Databases
•    Week 2: Entity Relationship Modelling
•    Week 3: Normalisation
•    Week 4: Recap
•    Week 5: Formative Feedback Session





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

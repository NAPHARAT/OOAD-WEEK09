#OOAD-WEEK09

ส่งการบ้าน class diagram นางสาวนภารัตน์ ฐิติกรโกวิท 57030180

ข้อ 1 Bank

โค้ด 

```
@startuml
customer <|-- Bank
customer : + deposit ()
customer : + withdraw ()
customer : - customer_name 
customer : - Account_number 
customer : - address 
customer : - phone
Bank : - Customer_detail
Bank : + providing_loan ()
Bank : + uppate_detail ()
Bank : + collect_money ()

@enduml
```
![]
()

ข้อ 2 course manager student

โค้ด
```
@startuml
course_manager -- course_section
course_section : + isFull()
course_section : + add_student ()
course_section : + create ()
course_section : + remove_student ()

@enduml
```
![]
()

ข้อ 3 employee

โค้ด
```
@startuml
Department <|-- Emp_detail
Emp_detail : - emp_name
Emp_detail : - emp_ID
Emp_detail : - contact
Department : - dept_ID


@enduml
```
![]
()

ข้อ 4 พาสปอต

โค้ด

```

@startuml
Fight <|-- booking

Fight : + add_fight ()
Fight : - fight_No
Fight : - destination
booking : + date
booking : + time
booking : + date
booking : + passenger

@enduml

```

![]
()

ข้อ 5 Passengers

โค้ด 
```

@startuml
Passengers <|-- Railway_admin

Railway_admin : + display ()
Railway_admin : + list of train ()
Railway_admin : - Train_no 
Railway_admin : + list of train ()
Passengers : - Name 
Passengers : + payment 
@enduml

```
![]
()

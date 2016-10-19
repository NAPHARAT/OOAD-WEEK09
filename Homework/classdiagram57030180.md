#OOAD

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

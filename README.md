# OOAD-WEEK08

## ส่งการบ้าน ooad week 08 เรื่อง use case 5 ภาพ
ภาพที่ 1 ฉันเล่นฟุตบอลกับเพื่อน

```@startuml
:myfriend: as Admin
(playing football) as (Use)
kay -> (Start)
kay --> (Use)

Admin ---> (Use)

note right of Admin : funny.

note right of (Use)
  YeaH
end note

note "GoGo." as N2
(Start) .. N2
N2 .. (Use)
@enduml
```

![](http://www.plantuml.com/plantuml/img/NKyn3i8m3DppYbEdTY13nmweJ31rGGoCGKrAH1gZ91toUs9I2Od9lZlxV1vZKY5jgnF3cc62rNuUe29EysgzQDzEPUiN6ABqKCvrhBMtg3iXNYhZS4HxPOkkGiPL_HeKuiTuIXh1Biy4ClK01hDvd-M_M3U0krQNKaH91PxOvvepOI7PS9Yf5ti2ICbewhcf3cDPBCzz0000)


ภาพที่ 2 สิ่งที่แม่ฉันทำ
```
@startuml
:mom: --> (cooking)
:mom: --> (clean)
:mom: --> (plant a tree)

@enduml
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuRBApS-rKj3LjLFGICxFpyxCIzT44Sj9JSn34Id8ISmhKKXKA2bAJTNaud98pKi1cWC0)



ภาพที่ 3    อาชีพพ่อแม่
```
@startuml
'default
top to bottom direction
mother --> (maid)
father --> (farmer)

@enduml
```
![](http://www.plantuml.com/plantuml/img/HSmn3e0W30NGlQVefWnUmN2LAYMIK6hgv_wwkRxXvGSIcDPfALfbTX3yPZWV3hXnQQ4dcWyonwN1sxRpQj9AeYg_L0dJI4HPH_c-5m00)



ภาพที่ 4 พนักงานโรงแรม

```@startuml
left to right direction
skinparam packageStyle rect
actor customer
actor hotelstaff
rectangle hotel {
  customer -- (checkout)
  (checkout) .> (payment) : include
  (checkin) .> (checkout) : extends
  (checkout) -- hotelstaff
}
@enduml
```

![](http://www.plantuml.com/plantuml/img/LOz13i8m30JlUOMFvL0Um07r3xp0SjqsQk9KYIDH8VwE2wY5uth7wtLN5BFM65pWGK4JP3zE2htFJEgJk39xMJ1ZX0Lfnf5lkWQ6pNP8cZ9GBPeYvw-SadAms65m6uGo6luUmiF1JaFRGaCJqvogdimu19olq2ouHXOJ5_12eVQyCru-oB5m0RuhIr_-S-p4JvkdwmonNry0)


ภาพที่ 5 เล่น facebook

```
@startuml
title Simple <b>Usecase</b>\nwith one actor

"Use facebook" as (Use)
kay -> (Use)

@enduml
 ```

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuIh9BCb9LGZEp2q0KZP9Tg75gSc9nQas-absCNdbcIKP2lbvgGg9oINvHLnSIa1PXRJ4vDIa_Fni9ON4OWKDe8WcLtPYfOAk7PJ3vP2Qbm8q6W00)


















## Use Case Diagram (ภาษาไทย)
* บรรยายเรื่อง UML โดย อ.ปานใจ  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/0eq2FGEQul8/0.jpg)](http://www.youtube.com/watch?v=0eq2FGEQul8 "บรรยายเรื่อง UML โดย อ.ปานใจ  " target="_blank") 

* เรียนการออกแบบโปรแกรมด้วย UML กับโปรเอิ๊ก ตอนที่ 1 การเขียน Requirement Card และ Use case   

[![IMAGE ALT TEXT](http://img.youtube.com/vi/u9sNT6x0Mlo/0.jpg)](http://www.youtube.com/watch?v=u9sNT6x0Mlo "เรียนการออกแบบโปรแกรมด้วย UML กับโปรเอิ๊ก ตอนที่ 1 การเขียน Requirement Card และ Use case " target="_blank") 

* How to draw a UML Use Case Diagram

[![IMAGE ALT TEXT](http://img.youtube.com/vi/UzprPX82Nac/0.jpg)](http://www.youtube.com/watch?v=UzprPX82Nac "How to draw a UML Use Case Diagram" target="_blank") 

## Use Case Diagram Tutorial (VTC)

* 3.01_Use Case Basics  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/tLJXJLfLCCM/0.jpg)](http://www.youtube.com/watch?v=tLJXJLfLCCM " 3.01_Use Case Basics " target="_blank") 

* 3.02_Modeling Use Case Elements  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/_JCsqdNf8bA/0.jpg)](http://www.youtube.com/watch?v=_JCsqdNf8bA " 3.02_Modeling Use Case Elements " target="_blank") 
 
* 3.03_A Use Case Diagram for an ATM  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/SmcBTsPsbIY/0.jpg)](http://www.youtube.com/watch?v=SmcBTsPsbIY " 3.03_A Use Case Diagram for an ATM" target="_blank") 

 

* 3.04_The ''include'' Dependency  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/q7O2EAZ_s7M/0.jpg)](http://www.youtube.com/watch?v=q7O2EAZ_s7M " 3.04_The ''include'' Dependency " target="_blank") 

 

* 3.05_The ''extend'' Dependency  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/bL_Bl_Xl7wQ/0.jpg)](http://www.youtube.com/watch?v=bL_Bl_Xl7wQ " 3.05_The ''extend'' Dependency" target="_blank") 

 
* 3.06_Generalization  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/x5LkaZlLT28/0.jpg)](http://www.youtube.com/watch?v=x5LkaZlLT28 " 3.06_Generalization" target="_blank") 

 
* 3.07_Putting It All Together  

[![IMAGE ALT TEXT](http://img.youtube.com/vi/gYmOzpU7DDI/0.jpg)](http://www.youtube.com/watch?v=gYmOzpU7DDI " 3.07_Putting It All Together" target="_blank") 
 

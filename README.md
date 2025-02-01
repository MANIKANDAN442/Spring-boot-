# Spring-boot-
All project in spring boot
# Spring-boot-
All project in spring boot
Spring boot initializer
step1: ADD dependence
1.develer tool
2.spring boot web
3.Spring data JPA
4.Thymleaf
5.mysql driver

import file------>existing Maven----browser----file click

step2: create package
1.Controller
2.JPA
3.Model

step3:
1.Controller------>>class
2.JPA---------->>>interface
3.Model------->>> class

step4: working principle
Controller---->index.html(submit button)----->>postMapping("/abc")----->modelata(getter/setter)---->>return------>>controller(ob.savefile(s)----->Respository---->
database(send)

step5:
Model-----@Entity(anotation)------>just Create table ------
Controller-------@Contoller(html file view)---------> direction
                  @RestController(Rest APi)
JPA--------->@Respository-------->datainsert

//Constructor injection
//getter and setter injection----->(right click-->source---->generate getter/setter )

java/main/resource
static--->css.file,js file---->create 
template---->html.file----->create

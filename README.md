# english_technical_books_store
English technical books resources
## currently involved technology book stack

1. C Language
   * C Primer Plus, 6th Edition
   * C++ Primer Plus 6th Edition
   * C++ Primer
   * C++.In.Action
   * Expert C Programming - Deep C Secrets
   * Fundamentals of C++ Programming
   * Fundamentals-of-Computer-Programming-with-C#-v2013
   * Modern X86 Assembly Language Programming-Daniel_Kusswurm
   * Practical C++ Programming
   * Programming from the Ground Up
   * The C Programming Language
   * understanding-and-using-c-pointers

2. Code Quality
   * Clean Code-A Handbook of Agile Software Craftsmanship
   * Code Complete 2th Edition
   * open-close principle
   * Working Effectively with Legacy Code
  
3. Computer System&Network and Virtualization
   * Computer Networks_ A Systems Approach, 3rd Edition-Petersen
   * Computer System_EN
   * Computer-Organization-And-Design(Hardware_Software interface)-5th-Ed-2014
   * How computer work-The Evolution of Technology
   * Network_Performance_Engineering__A_Handbook
   * Operating_System_by_Willam_Stalling
   * Signals And Systems
   * TCP IP Illustrated Volume 1
   * TCP IP Illustrated Volume 2
   * TCP IP Network Administration 3rd Edition
   * Virtualization Essentials
    
4. Golang
   * A very short tutorial：effective-go
   * An Introduction to Programming in Go
   * Concurrency in Go：Tools and Techniques for Developers
   * Go-in-Action
   * Introducing Go-build reliable,scalable programs
   * The Go Programming Language
  
5. Head First Series
   * Head First Design Patterns
   * Head First C
   * Head First Data Analysis
   * Head First EJB
   * Head First Statistics
  
6. Java
   * Advanced_Design_and_Implementation_of_Virtual_Machines
   * Building_Microservices
   * Cloud Native Java
   * Domain Driven Design
   * Effective Java (2017, Addison-Wesley)
   * Elasticsearch- The Definitive Guide
   * Elasticsearch.Server.3rd.Edition.Packet
   * Elasticsearch_Server.2nd_Edition
   * Expert One-on-One J2EE Development Without EJB 中文版
   * Java IO (O'Reilly Java)
   * Java Version History
   * Java_concurrency_in_practice
   * Mastering_Elasticsearch_2nd
   * O'Reilly Tomcat The Definitive Guide (2nd Edition)
  
7. Python
   * Python Crash Course
   * Python for Data Analysis 2nd-Edition
  
8.  Security
    * EN-Hacking Web Applications
    * Hacking- The Art of Exploitation (2nd ed. 2008) - Erickson
    * Hyper-V Security
    * JavaScript Security
    * Penetration Testing - A hands-on introduction to Hacking
    * The Manager's Guide to Web Application Security
    * The.Web.Application.Hackers.Handbook.Oct.2007
  
9. Specification
    * jls14
    * jls8
    * JSR 338-JavaPersistence API
    * jstat - Java Virtual Machine Statistics Monitoring Tool
    * jvms14
    * jvms8
    * portlet-1_0-fr-spec
    * servlet-3_0-final-spec
  
10. Spring Series
    * Apress.Expert.Spring.MVC.and.Web.Flow.Feb.2006
    * Hands on Spring Security for Reactive Applications
    * Spring Batch in Action
    * Spring Boot in Action
    * Spring Data-Modern Data Access for Enterprise Java
    * Spring Integration in Action
    * Spring-Data-Programming-Cookbook
    * spring-webflow-reference
    * Spring.in.Action.3rd
    * Spring.Microservices.in.Action2017
  
11. UML and Pattern
    * Applying UML and Patterns_2th_Ed
    * Applying_UML_and_Patterns_3rd_Ed.Craig_Larman_(2004)
    * Design Pattern-Examples
    * Design Patterns Explained-Addison Wesley(2001)
    * Design Patterns-Elements of Reusable Object-Oriented Software
    * Distributed Systems-Concepts and Practice - by George Coulouris
    * Patterns of Enterprise Application Architecture - Martin Fowler
    * UML-diagrams
  
12. Unix Core and Programming
    * Advanced Programming in UNIX Environment(Volume3,3rd Edition)
    * Essential System Administration
    * How Linux Works What Every Superuser Should Know
    * Learning Unix For OS X Mountain Lion
    * Linux Kernel Development, 3rd Edition
    * Professional Linux Kernel Architecture-WolfgangMauerer
    * Solaris 10 - The Complete Reference
    * The Linux Command Line
    * The Unix Programming Environment-kernighan-pike
    * Understanding.Linux.Kernel
    * UNIX and Linux System Administration Handbook
    * UNIX Network Programming(Volume1,3rd)
    * UNIX Network Programming(Volume2,2rd Edition)
  
13. Version Control
    * A successful Git branching model
    * Apache Maven Cookbook
    * Gradle in Action
    * Maven - The Complete Reference
    * Maven-The Definitive Guide
    * Pro Git

---
> C++ Primer/Head First Design Patterns/Hea First C were managed by Git Large Storage,
> to pull such file, need install `git lfs`
* set up Git LFS per user account:
```bash
git lfs install
```
* track file/or file types you'd like Git LFS to manage:
```bash
git lfs track "*.pdf"
```
* make sure `.gitattributes` is tracked:
```bash
git add .gitattributes
```
* add large file and commit them as usual, now Git LFS will manage the large file
```bash
git add "C++ Primer.pdf"
git commit -m "Add large pdf file"
git push origin main
```
* to pull/download large file managed by Git LFS
```bash
git lfs pull origin master
```

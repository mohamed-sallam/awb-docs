<style type="text/css">
body {
    counter-reset: h2
}

h2 {
    counter-reset: h3
}

h3 {
    counter-reset: h4
}

h4 {
    counter-reset: h5
}

h2:before {
    counter-increment: h2;
    content: counter(h2) ". "
}

h3:before {
    counter-increment: h3;
    content: counter(h2) "." counter(h3) ". "
}

h4:before {
    counter-increment: h4;
    content: counter(h2) "." counter(h3) "." counter(h4) ". "
}

h5:before {
    counter-increment: h5;
    content: counter(h2) "." counter(h3) "." counter(h4) "." counter(h5) ". "
}
</style>

# <center>Software Requirements Specification for Digital Detoxing Application</center>
###### <center>Abdalrhman M. Hemida, Mohamed M. Sallam, Mohamed Sherif, Mohamed Yehia, Yousef Ahmed</center>


## Preface
### Document Purpose
The main purpose of this document is to provide details, specifications ,and requirements for our Digital Detoxing App (Awb).
The document will provide an overview of the system in the first section; then each part will be explained in detail.
### Target Users
- As long as our application is open source, our target users include:
    - Supervisor
        - To check whether our system meets our needs or not.
        - Confirm what was agreed upon.
    - Developers
        - Whether they are on a team project or contributors.
    - Testers
        - Use SRS to develop validation tests for the system.
### Revision History
Version | Author | Description | Data
-------------|--------------|-------------|-------------
|0.1.0 | whole team | initial | 14-10-2022

## Introduction
### Purpose
Awb works with your self-control with the pre-commitment strategy; If the soul is like a baby, as Imam Al-Busairi -may God have mercy on him- said:
>“The soul is like a baby, if you neglect him, he will grow in love with
breastfeeding, and if you wean him, he will be weaned”.
>
Awb aims to limit your digital usage to help you achieve the following:
- Minimize the use of social media applications.
- Track and control your phone usage.
- Lock the phone for some time (from 1s to 12h) or more.
- Helping others to quit smartphone addiction.

### Scope 
Awb is open-source software for detoxing, it helps to quit digital applications addiction whether they are social media apps or games usually. Awb provides users to lock their applications for some time by restricting them and also provides us with scheduling to schedule our lockers. Awb supports collaborative work.

### Overview  
This document is organized as follows: first, an overview description of (AWb) application and the big picture of our applicatino is presented in (sections 2.1 and 2.2). Section 3 illustrates the definitions, abbreviations, and acronyms. Section 4 states the type of users who can use Awb. 
<!-- - Section 1
    - Descripe what SRS is for, who use our system and version of our project.
- Section 2
    - Our system's aims, a brief of our achievements by Awb, and list our goals then explain our structre.
- Section 3
    - Talking about acronyms and abbreviatinos. -->
## Glossary  
### Acronyms, definitions, and abbreviations
**UI**: User interface.
**UX**: User experience.
**API**: Application user interface.
## System Users
### System stakeholders
### Users objectives 
## User Requirements definitions
### System Function
### Constraints 
## System Architecture
<!--new chapter-->
## Functional requirements
### Phone Locking  
The user can lock his phone (partially or entirely) for a customized amount of time (from 1s to 12h), or more time by displaying a warning message.
### Whitelisting 
Awb is a permanent minimal launcher that allows only useful apps during the detoxing period while locking other time-wasting apps.
### Detox Schedule
The Detoxing periods can be Scheduled (daily and weekly) and it can be repeated.
### Flexibility
Awb is a tool (flexible to some extent) to help users be wise and careful with their time, so a special warning is displayed for important (built-in) applications (except settings app) and user can add/remove from this group.

### App Grouping
User can create A group of apps with a name to be treated as one app (in usage time) i.e., social media apps, studying apps ... etc.

### Synchronization
User can Lock all synchronized devices with only one click.
### Allow users to change wallpaper
The program is an App launcher like others but with Digital Detoxing features.
### Group therapy 
Allow a group of users to be the observers of one another, the individual Access is monitored by the group for each one in this group, so each User has a partner to help him throughout his detoxing journey.
## Interface Requirements
### User interfaces
- UI: Figma.
- UX: simple and minimal.
### Software Interfaces
Database access will be wrapped through Object Relation Mapping Framework (JDBC Framework).
### Communications Interfaces 
#### Database Communication
- Application-Database communication will be through TCP/IP Communication on port 1433.
- client will access the server through HTTPS protocol. 
<!--new chapter-->
## Non-functional requirements 
### General 
#### Reliability
Impossible to break the lock even if you restart the phone unlike the other apps so we made it an apps launcher. 
#### High Performance 
- low Response Time.
- Lightweight, fast and minimal.
#### Security 
<!---OL---> 
1. Awb does not collect any data, even metadata, about you in any way with or without your consent.
1. The Exchange of Data between server and user is minimal.
1. Database cannot capture anything used to control devices.
1. Public and private keys are used in QR code form to provide user Authentication. 
1. HTTPS protocol is used in the exchange of data between client and server which provides a layer of protection through Encryption and Authentication.    
#### free and opensource
A free and open-source launcher with no Ads presented so any contributor can review, edit or redistribute the source code and report bugs and security threats if any.
### Technologies
- Build Tool for Java: Gradle
- Unit Test for Java: JUnit & Mockito 
- Spring Boot for Server-Side Logic
- Client-Server Communication: REST APIs
- Database: PostgreSQL vs MySQL <!--yousef:evaluation-->
- Build Tool for Qt C++: CMake
- Unit Test for Qt C++: QtTest, GoogleTest or CppUnit <!--evaluation-->
<!--new chapter-->
## System Models and Diagrams 
## System Evolution
-  The application shall works on new versions of OSs (Unix, Android and Windows).
-  The application shall run on new versions of hardware devices.
## Time Plan
### Work Breakdown Structure  
### Gantt chart  

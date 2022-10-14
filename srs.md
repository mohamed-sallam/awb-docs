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
The main purpose of this document to provide details, specifications and requirements of our Digital Detoxing App (Awb).
The document will provide an overview of the system in the first section; then each part will be explained in detail.
### Target Users
- Anyone who abuses the phone or the computer and wants to limit that with the pre-commitment strategy.
- Anyone wants to quit social media apps.
- Anyone who needs to track and control applications usage.
- No gender or age restrictions, as long as you have the intention to limit your digital usage, so Awb is for you.
### Revision History
Version | Author | Description | Data
-------------|--------------|-------------|-------------
|0.1.0 | whole team | initial | 14-10-2022

## Introduction
### Purpose
Awb works with your self-control with the pre-commitment strategy; If the soul is
like a baby, as Imam Al-Busairi -may God have mercy on him- said:
>“The soul is like a baby, if you neglect him, he will grow in love with
breastfeeding, and if you wean him, he will be weaned”.
>
Awb aims to limit your digital usage to help you achieve the following:
- Minimize the use of social media applications.
- Track and control your phone usage.
- Lock the phone for some time (from 1s to 12h) or more.
- Helping others to quit smartphone addiction.

### Scope 
Awb is open-source software for detoxing, it helps to quit digital applications addiction whether they are social media apps or games.
Awb provides users to lock their applications for some time by restricting them and also provides us with scheduling to schedule our lockers.
Awb supports collaborative work.

### Overview  
- Section 1
    - Descripe what SRS is for, who use our system and version of our project.
- Section 2
    - Our system's aims, a brief of our achievements by Awb, and list our goals then explain our structre.
- Section 3
    - Talking about acronyms and abbreviatinos.
## Glossary  
### Acronyms, definitions, and abbreviations

## System Users
### System stakeholders
### Users objectives 
## User Requirements definitions
### System Function
### Constraints 
## System Architecture
## Functional requirements
### // TODO: Add Functional requirements
## Interface requirements  
### User interfaces
### Software Interfaces
### Communications Interfaces 
## Non-functional requirements 
### Availability
### Security
### Safety
## System Models and Diagrams 
## System Evolution
## Time Plan
### Work Breakdown Structure  
### Gantt chart  

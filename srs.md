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
### Target Users 
### Revision History
## Introduction
### Purpose
### Scope  
### Overview  
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

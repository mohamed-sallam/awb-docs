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

figcaption:before {
    counter-increment: figcaption;
    font-style: italic;
    font-weight: bold;
    content: "Figure " counter(figcaption)
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
#### FOSS Contributors
- Responsible for reporting bugs and security threats.
- Responsible for cleaning and maintaining the code for the FOSS community.
- Responsible for adding, removing, and modifying the source code.
- Responsible for redistributing the code base.
#### App Users
- Responsible for using the app features to quit digital addiction.
- Responsible for reporting bugs and requesting new features.
#### Software Engineering Team
- Responsible for creating the first version of the app.
- Responsible for the development of the app.
- Responsible for writing the first version of the SRS document.
- Responsible for almost what Contributors do.

### Users objectives
#### FOSS Contributors
- Gain experience in studying, reading, modifying, or cleaning the source code.
- Are allowed to distribute the code base to fit their needs.
- Have a good portfolio for getting jobs.
#### App Users
- Have quality time with their family and friends.
- Have a life.
- Quit all forms of digital addiction.
- Have much time to do their goals in life.
#### Software Engineering Team
- Gain experience in architecting, designing, coding, documenting, and testing a real-life project in an Agile environment.
- Gain experience in using mainstream industrial technologies (mentioned in section @#$%&).
- Have a good portfolio for getting jobs.
- Gain teamwork, self-learning, and presentation skills.

## User Requirements Definition
### System functions
1. Phone locking
2. Whitelisting
3. Detox schedule
4. Flexibility
5. App grouping
6. Devices synchronization
7. Allow user to change wallpaper
8. Group therapy

### Constraints
#### Cultural constraints
- All code must follow team standards.
- Version control workflow must follow team convention.
- The team must create -at least- automated tests for the Android app.

#### Hardware limitations
- The app should work on older Android versions properly.
- The app should be able to run on Android TVs.
- The app should work on older PCs.
- No Apple ecosystem support.
## System Architecture
<center>
    <figure class="image">
        <img src="imgs/SystemArchitecture.png">
        <figcaption>
                System Architecture
        </figcaption>
    </figure>
</center>

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

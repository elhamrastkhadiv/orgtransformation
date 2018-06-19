# README

## Introduction
 README file is normally the first entry point of a code base. It should tell people why/how they should the module.
 Standardizing how you write your README makes creating, maintaining and on boarding to the codebase easier.
 
 This RFC introduces the concept of the `Standard README.md`

## Solution
All of OpenTable Repository should have a README.md file and follow basic requirement for a READMe.md file. 
we can add a linter validation to fail build ?? 

##Suggested Sections
basic READMe.md file need to have following sections:

* Requirements
* Basic instructions to run the app
* Testing 
* Deploy process
* Run book
* Toggles(optional)
* Contribute
* License(Optional)


## Sections description
####  Title
####  Table of Content
####  Requirements
#### Basic instructions to run the app
#### Testing 
####  Deploy process
####  Run book
    * [follow the wiki run book standards(dashboard,environments)](https://wiki.otcorp.opentable.com/display/CP/Service+Runbook+Example) 
    * Trouble shooting
#### Toggles(optional)
    * Features flags
    * A/B tests
#### Internationalization i18n(Optional)
#### Contribute
    * CONTRIBUTING.md
    * SLA
    * Coding standards    
         - style guides
    
####  License(Optional)



## Sample Repo with a good README file
* [Booking-flow](https://github.com/opentable/booking-flow)
* [wtf-service](https://github.com/opentable/wtf-service)



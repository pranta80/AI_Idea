# AI_Idea
Building AI course project

# Work estimate calculator

Final project for the Building AI course

## Summary

The purpose of the solution is to use database which contains work estimates and actual working hours/days data to calculate a recommended work estimate for new project with given parameters. 


## Background

I work as an Integration Developer and one biggest problem has been when creating new integrations/automations, that the personnel who order work from us and write down definitions of what the integration/automation should do, do not always know how all the tools that are needed work (for example API's etc). This causes that work estimates are inaccurate and for that reason for example:
* savings calculations are off
* development work schedules are not accurate

Of course the frequency of the problem decreases all the time when developers get familiar with new programs etc. but I still feel it would help if there where some kind of logic behind this kind of stuff rather than only the experience of the developers. And I also think that if you can automate some process or task, it is always worth it!

Note that we do have standardized processes for development work so there are detailed tasks to be done in every project. Starting from the automation idea all the way to production imployment phase. 


## How is it used?

First of all solutions requires a database where developers would store data from previous projects. In database there would be given work estimate and actual working time and also needed parameters for calculations. Parameters list would probably increase all the time but at least following would be needed: 
* input method/trigger (file, schedule, API call, SQL query etc). If file, file format (csv, json, excel etc)
* output format (file, API call, SQL query etc). If file, file format (csv, json, excel etc)
* system linked/needed (for example data needed from two systems and inputted to third)
* is there already automation made to linked systems (yes/no)
* developers time needed in meetings in hours

Secondly some kind of form would be needed where person who needs and automation or has an idea for automation would answer list of questions based on the parameters needed for calculations. Based on the input data to the form and the database data automation would calculate pre-work estimation and the person could take that work estimation and proceed with the automation idea to next phase. 


## Data sources and AI methods

At the moment we have created around 400+ different kind of integrations from simple filetransfer to complicated data collecting and calculations (for example data updates from master data to other systems). We would have to collect this data and insert it to database and create parameters list based existing knowledge. 

I would use linear and logistic regresion for this and maybe even some neural network. 


## Challenges

Biggest challenge comes when we have get familiar with new system or API etc. Person who would use the form/solution does not often know if there is sufficient documentation etc from the system or API and what else is needed so that we can use that resource. This always increases the work estimate and might also need some third party involvement. Other challenge is the skill level of the developer. Someone who is familiar with all needed systems and is an experienced developer will be much more efficient with his/hers work. 

## What next?

I think that this project could grow and could be expanded to other projects than just integration/automation projects. But for now this is just quite quickly descriped idea and mainly for this course but I could bring this up at work since we are exploring with AI.


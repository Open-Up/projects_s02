# Second semester projects

## Second semester project objectives

 - Being able to report to a manager about my work following a method
 - Being independent in my work, working only with guide lines
 - Experience with OpenSource software projects
 - Present my work in english

## Planning

The project planning is the following : 

 - On 4th march 2016 : Final project list
 - On 7th march 2016 : End of project choice (In case of disagreement, I will choose my self the groups which will gain the projects, so make sure to discuss this between you before)
 - On 11th march 2016 : Backlog task validation (see below) by Benoit Tellier
 - On 14th march 2016 : First weekly report (see below)
 - On 20th may 2016 : Project results return
 - On 27th may 2016 : Project presentation

## Project notation

### Evaluated competences

 - Independency   3/20
 - Results        5/20
 - Presentation   9/20
 - Management     3/20

### Evaluation grades

#### Independency

0/3 : Needs strong help technically. Do not understand the subject.
1/3 : Frequently asks for help
2/3 : Is independence
3/3 : Even takes initiatives

#### Results

1 point on punctuality
1 point on working demonstration

0/3 : No results
1/3 : Partial results
3/3 : Complete results

1 bonus point : Demonstrate non asked interesting capabilities

#### Presentation

This evaluation point is individual

1 point on speech time (should be ~15 minutes)
1 point on oral fluency ( gests ? Speech fluidity ? Reads his notes ? )
2 points on english : we should easily understand what is said
2 points : Student should be able to present technically his project
2 points : Student develops his works
1 points on slides (look and integration with speech)

#### Management

1 point on weekly reports
1 point on Trello backlog
1 point on Trello tasks 

## Orders

We need to settle simple rules to work together. In this section we will speek of workflow.

Having a decent workflow help give precise overview to your management, and better see your project advancement. It helps working continuously on a project, with keeping track of every important change.

Our workflow is composed of three important units :

 - Backlog : Big tasks you need to tackle
 - Tasks : small tasks that can be done by a simple guy. Several tasks compose a backlog entry.
 - Weekly report : to OpenUp manager as well as your tutor.

We provided a full example of :

  - the backlog board
  - the task  board
  - A weekly report

For a fictive team and a fictive project.

Here is the project description :

```
Linagora maintain a blog for technical blog posts from R&D teams. But we today are not satisfied by 
our current Joomla blog. We need to install a new wordpress connected to Linagora LDAP for posts.

We want to have two sections :

 - a simple blog section, on which you will be importing Joomla data
 - a *project* section.
```

### Workflow

You will maintain two [Trello]() boards : 

 - One for your backlog
 - One for your tickets

You will do weekly summaries to Benoit Tellier about your weekly work. Ree the following sections for more details.

#### Backlog

This is your first task. You need to split your project on several objectives. Each of these objectives will be a **back-log** entry.

Each entry has :

 - a descriptive title
 - some short explanation
 - a due date
 - acceptation criteria
 - a state :
    - Must : You must do it for your project.
    - Should : You consider this backlog entry important but it is not compulsary
    - Could : You can do it, but this not your priority
    - Wont : You canceled this backlog entry because you lacked time and prefer to give priority to other entries
    - In progress : You are working on these backlog entries
    - Done : You validated their acceptation criteria
 - As comments, links to tasks (more on that later). Task needs to be added during **In progress** state, need be prepared slightly before switching backlog entry to **In Progress**, and can be modified 
during progress.

Note : State needs to be modified depending on your work / decisions.

See this [example](https://trello.com/b/tqaVikEz/sample-backlog) of backlog board.

#### Task Board

This board is about your current tasks. A task is a low level thing one person is working on. It can last from 10 minutes to 1 or 2 days of work (no more) for a single person.

A task is described with : 

 - A self explainatory title
 - The link to the backlog entry it belongs
 - A small description
 - Time estimation
 - Time spent
 - Has a owner (the guy working on it)
 - (if applicable : review link in comments)
 - Acceptance criteria
 - A state :
   - TODO : Something you should do
   - In progress : someone of the team is working on
   - Review : task is finished but you need peers validation
   - DONE : Task is accepted by the team and considered resolved

You can find here a [sample task board](https://trello.com/b/8cj2k02m/sample-task-board) for our sample project.

#### Weekly reports

You will provide to btellier[at]linagora.com as well as to your tutor a weekly report of your work. It will contain :

 - The title will contain [openup] Weekly report (for filtering), team name, and contain the date formatted as day-month-year (eg : 01-03-2016)

Example of valid subject :

```
[openup] Weekly report Team : "Crazy rabbits" Date : 01-03-2016
```

 - The team name
 - The list of member
 - The link to your github project (reminder for me)
 - List of changes made to your backlog
 - List of changes made to your task
 - Your plans for the next week
 - Difficulties you faced

Example of mail :

```
Subject : [openup] Weekly report Team : "Crazy rabbits" Date : 01-03-2016
Boddy :

    Team : Crazy rabbits
    Members : Benoit Tellier, Louis Vidal
    Github project : https://github.com/Open-Up/projects_s02
    
    # Backlog changes
    
    Moving *Configure a LDAP server* to DONE
    Moving *Install wordpress* to in progress
    Moving *Develop a plugin connecting to Github to display project advancement* to WONT

    # Task changes

    Moving *import existing users* to DONE with time h30/2h
    Moving *install MySQL* to DONE with time 2h/3h
    Moving *Install Apache server and Php modules* to Review with time 3h/2h
    Moving *Install PHPMyAdmin* to In progress with time 1h/1h
    Working on *Install wordpress* chane in time from 1h to 2h
    Adding task *Install a FTP server* to backlog *Install WordPress*

    # Difficulties
    
    We faced issue with database rights but managed to solve that thanks to our tutor.
    
    We are quite happy with our week as we managed to finish our first backlog entry and did hafl 
    of our second !

    # Plans for next week

    We plan to finish backlog entry *Install wordpress*. We also hope to achieve backlog entry 
    *Link WordPress to the LDAP*.
    
    Regards,
    
    The 'Crazy Rabbit' team
```

## List of projects



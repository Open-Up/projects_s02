# Second semester projects

## Online presentation

Here is an [online presentation for Open-Up students](https://rawgit.com/Open-Up/projects_s02/master/presentation/index.html).

## Student modification

Students are expected to modify this document :

 - in order to register themselves in a team
 - in order to register their team in a project

To do so, please **fork** this project. **Watch** this project too, it is going to be important for solving conflicts

When it is done, make your modifications. Then commit it and open a pull request.

 - I will instantly validate teams.
 - I will give 1 day for other people to contest your project choice. You then have to discuss in comments. I will then merge when an agreement is met.

I advice to make two separated PRs for teams and projects.

Other advice : Do not all register as team 1. ;-)

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

 - 0/3 : Needs strong help technically. Do not understand the subject.
 - 1/3 : Frequently asks for help
 - 2/3 : Is independence
 - 3/3 : Even takes initiatives

#### Results

 - 1 point on punctuality
 - 1 point on working demonstration

 - 0/3 : No results
 - 1/3 : Partial results
 - 3/3 : Complete results

1 bonus point : Demonstrate non asked interesting capabilities

#### Presentation

This evaluation point is individual

 - 1 point on speech time (should be ~15 minutes)
 - 1 point on oral fluency ( gests ? Speech fluidity ? Reads his notes ? )
 - 2 points on english : we should easily understand what is said
 - 2 points : Student should be able to present technically his project
 - 2 points : Student develops his works
 - 1 points on slides (look and integration with speech)

#### Management

 - 1 point on weekly reports
 - 1 point on Trello backlog
 - 1 point on Trello tasks 

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

You will maintain two [Trello](https://trello.com/) boards : 

 - One for your backlog
 - One for your tickets

You will do weekly summaries to Benoit Tellier (btellier[at]linagora.com) about your weekly work. Ree the following sections for more details.

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

### 1 Migration from Zimbra to OBM : provide scripts

Several times a year, Linagora System Administration teams should handle migration of their clients from Zimbra to OBM. As it remains a not so common task, it has not been automated yet. Alexandra Chapellon, at the head of the franch integration team proposes you to automate this task. You should install Zimbra software stack (https://www.zimbra.com/documentation/zimbra-collaboration-open-source/) and populate it with contacts, mails, and events. Then install the OBM software stack (http://obm.org/content/install-obm-3-debian-wheezy). You should the write script to automate migration, and provide documentation to explain how to do it to the French team. You should provide automated and unattended extraction tools that produce ics files for calendar data, vcf for contacts, and make sure imapsync is still the  way to go when migrating emails. You will be supervised by Alexandre Chapellon.

Keywords : Migration, OBM, Zimbra, scripting

Team : 

### 2 Document single james set up + mailet configuration

JAMES (Java Apache Mail Enterprise Server) is Linagora new e-mail server for OpenPaas. As todays main contributor, we would like to develop community around JAMES. One big obstacle we face is the lack of "getting started" session providing simple setup for a production ready JAMES, for someone that do not know anything about mail servers. In this project, you should configure a JAMES server so that it can be defended against Spam, Viruses, is not an open relay, verify clients authenticity, and is trusted by other mail server. You should explain in depth your choices, diagnose missing features for the JAMES team, and write some documentation. You will be supervised by Benoit Tellier from JAMES team.

Keywords : SMTP, Spam, Viruses, SMTP relay, JAMES

Team : JAV (JAMES-Anti-Virus)

### 3 Set up LDAP authentication on James + provide quota reading from LDAP

JAMES (Java Apache Mail Enterprise Server) is Linagora new e-mail server for OpenPaas. JAMES team at Linagora only used JAMES with locally stored user. We would llike you to deploy a James server using Linagora LDAP for authentication. You will provide your configuration, and write some Java tests for this feature. Finaly, you might contribute a plugin allowing to read user quotas from a LDAP, and tests for this feature. You will be supervised by Benoit Tellier from JAMES team.

Keywords : JAMES, LDAP, IMAP quotas

Team : 

### 4 Document production replicated settings for OpenPaas

OpenPaas is a brand new Linagora product. It is an enterprise social network, with mail, contact and calendar capabilities. It uses a lot of middle-ware, for instance a MongoDB database, Redis for messages, ElasticSearch as a search engine, JAMES for mails, Cassandra for JAMES persistence. Today, the OpenPaas team lacks documentation on production ready settings for these middlewares. You are expected to experiment with these middle-ware, and provide a configuration for each one of them that is production ready, efficient, and supporting distributed environments. You are also expected to do some administrative tasks like adding and removing nodes, perform repairs, and other classical maintenance tasks. You will be supervised by a developer from OpenPass team, as well as Benoit Tellier on James part.

Keywords : OpenPaas, MongoDB, Redis, ElasticSearch, JAMES, Cassandra

Team : redpill (2)

### 5 Vtiger CRM

You will be responsible to experiment Vtiger CRM at Linagora. You will deploy it, test it, introduce it to Linagora revevant teams and finaly migrate data from our previous CRM engine. Your instalation should use Linagora LDAP for authentication. You will be supervised by Guilhem Valentin.

Keywords : VtigerCRM, Nginx, OpenLDAP

Team : 

### 6 OBM Linshare and Jabber for Open-Up team

On a server given to your disposal, you will install a collaborative plateform for the Open Up students. It will be composed of a LDAP for authentication, of OBM collaborative plateform. It will rely on Jabber for instant messaging, and people will be able to share files using LinShare software. You will gain the openup.linagora.com domain name delegated and you will have to configure it for your needs.

Keywords : Mail, DNS, OBM, LinShare, Jabber, mail

Team : 

### 7 Packages for LinShare

Linshare is a collaborative software from Linagora. It allows you to share file with other people. You can manage access rights, as well as share expirency. LinShare team would like to make it more easy for the community to use its software. To do so, you will prepare packages for debian and RPM.

Keywords : LinShare, packages

Team : BkGirls

### 8  Mail server

You are the network and the system administrator of a small company. You have to provide a mail service to employees. Their informations (names, passwords) are on a LDAP server. 
You have to set the SMTP server with Postfix, the webmail service with Roundcube and the IMAP mailboxes server Cyrus. You are also expected to configure SpamAssasin anti-spam server and ClamAV anti-virus. Your infrastucture should remain available in the case of single server failure. So you should configure load balancing, as well as distributed storage.

Keywords : Network addressing, name resolution, OpenLDAP, Postfix, Cyrus IMAP, RoudCube, High availability, file system replication, load balancing, shared IPs.

Team : 

### 9 Unintended instalation

Design a fully automated installation system. A classroom with 10 identical desktops must be install with the fewer operator action as possible. The installation system allows the operator to choose an image located on a server and this image is automatically installed on the desktop. Use less media as possible : network, desktop and server only. After installation and reboot, desktop are operational.

The documentation describes how to install and how to create an system image.

Keywords : network boot, automation, unattended, partitionning, network file share, DHCP, NFS, Samba

Team : Team n°8 : Unintended installation

### 10 Server supervision

You are the system administrator managing few servers. Design an alert system to inform you when security events occur on a supervised server. Examples of alerts : too many failed connection attempts, user management files modifications, passwords changing, too easy passwords,  package installation, filesystems usage, CPU charge, opened ports, etc. Choose three priorities and for each, a way to alert the central administration server.

Keywords : Remote logging, filesystems supervision, shell scripts writing, syslog, Nagios

Team : 

## Teams

2 or 3 people by team ...

**1 Team name : JAV (JAMES-Anti-Virus)**

 - Members : Tran Trung Hieu & Nguyen Van Minh
 - Trello backlog : 
 - Trello tasks : 

**2 Team name : redpill**

 - Members : Le Cong Tuan (github.com/tuanict), Pham Trung Dung (github.com/RockyMeadow), Hoang Minh Tuan (github.com/tmh1999)
 - Project : 4 Document production replicated settings for OpenPaas
 - Trello backlog : 
 - Trello tasks : 

**3 Team name : BkGirls**

 - Members :  Phạm Như Quỳnh, Ngô Thị Thủy, Hà Thị Hoàn
 - Trello backlog : 
 - Trello tasks : 

**4 Team name :**

 - Members : 
 - Trello backlog : 
 - Trello tasks : 

**5 Team name :**

 - Members : Phạm Xuân Tường, Bùi Xuân Thanh, Trần Tiến Hiển
 - Trello backlog : 
 - Trello tasks : 

**6 Team name : Good guys**

 - Members : Cuong Nguyen Ngoc, Duy Le Xuan
 - Trello backlog : 
 - Trello tasks : 

**7 Team name : Les trois mousquetaires**

 - Members : Đặng Văn Đại, Nguyễn Tuấn Kiên, Hoàng Quốc Hồng Nhật
 - Trello backlog : 
 - Trello tasks : 

**8 Team name :**

 - Members : Trần Xuân Giáp (https://github.com/txgvnn), Hoàng Thành Công (https://github.com/hoangcongst)
 - Trello backlog : 
 - Trello tasks : 

**9 Team name :**

 - Members : Khuat Duy Toan,Ha Minh Quyet,Pham Van Viet
 - Trello backlog : 
 - Trello tasks : 

**10 Team name :**

 - Members :
 - Trello backlog : 
 - Trello tasks : 

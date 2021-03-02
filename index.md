## Welcome to REED

An opinionated project folder structure for modern teams trying to build cool things. Works for Research, UX, Design, Dev and Project Management for freelancers or employees.

## Why

Product teams are chaging, more tools are online, methodologies and testing have been udpated, and yet we still use the same structure.

This folder structure has been adapted based on working with multiple clients, indside several companies, and a myriad of different teams.

The foundations are there for a quick start but you should adapt it to a way that works for you!

## Structure

```
CLIENT_OR_COMPANY/
├─ Company/
│  ├─ _Admin/
│  ├─ Brand/
│  ├─ Expenses/
│  ├─ Invoices/
│  ├─ Legal/
│  ├─ Pitches/
│  ├─ Proposals/
│
├─ TEAM/
│  ├─ Project_1/
│  ├─ Project_2/
│
├─ PROJECT_NAME/
│  ├─ _Project/
│  ├─ 01_Research/
│  ├─ 02_Explore/
│  ├─ 03_Experience/
│  ├─ 04_Delivery/
│

```

## Company

This folder has everything you need for the company,
- Brand Assets
- Identity
- Logos
- Fonts
- Icons
- Templates
- Imagery
- Videos
- Design Systems
- Code Samples

There is also a folder called **_Admin**, this is for those who are working **IN** the company. So you have a place where you can keep all the documents that get lost
- Contracts
- Payslips
- Policies - (Compliance, HR, IT, Legal, Security, etc)
- Process - Specific to the company (Career progress, promotions, reviews, training)
- Starter Pack - The inevitable documents like floor plans, vouchers, checklists, etc)
- Tax - This will depend on where you live, but there are always things you need to keep

Note: If you are sharing this with anyone, make sure to only share your **_Admin** folder with people that should have access to it. 🙄


## Root naming structure

### Naming convention

This is personal preference, if your projects are short or time bound

```
Short projects
- PROJECT_ID - Project Name
- PRO21001 - Short Project
- PRO21002 - Website Project

Long running projects
- Project Name
- CompanyWebsite-com
```

### Teams

If you work with multiple teams then it might make sense to group them based on the team

```
TEAM_CLIENT/
├─ Company/
├─ Web Team/
│  ├─ Project_1/
│  ├─ Project_2/
│

PROJECT_CLIENT/
├─ Company/
├─ 2019 - Website Redesign/
├─ 2020 - Website Redesign/
│

PROJECT_ID_CLIENT/
├─ Company/
├─ PROJ19 - Website Redesign/
├─ PROJ20 - Website Redesign/
├─ PROJ21 - Website ReReDesign
│
```

The key is to pick something that makes sense to you and to stay consistent.

## Project Structure

### _Project

Everything related to the **project**, this should be available to all people in the team, and managing and running the team effectively.

- _Notes - That have not been organized yet
- Brief - What the project is about
- Meetings - All team meetings, notes
- Resources - Project specific
- Strategy - Discovery, Planning, Process, Resourcing, Timelines
- Team - Sponsors, Stakeholders, Members, Users

Why are **Pitches** and **Proposals** not inside the project?
- The majority of people in the team dont need access to these.
- They also live on a company level since a single proposal or pitch could create multiple projects.
- You also probably should not be working on a project if you dont have the contracts in place for them 😉

Why is **Resources** inside the project folder, theres already one in the Company Brand folder?

- Many projects use specific resources that dont make sense for company as a whole
- Fonts, Logos, Images, Videos, Icons, Code, might only be release when the project is done
- A good rule of thumb, if the client says "Dont share this with anyone" its a project resource

Why not keep all things in the project **Resources** folder?

- Any resources that can be shared across multiple projects should live in the company
- This also prevents "Do not share" resources with people before they are ready
- We also prevent team members from storing the same files (often large) in multiple places

### 01_Research

This is a working folder for everything you need to find out, think of it as:
- Things you know
- Things you want to find out
- Things you believe
- Data and research gathered

This folder also includes all previous research, things you have received from the client, what you have learned about and from the stakholders, users, competitors, etc.

```
01_Research/
├─ 01_Input/
├─ 02_Stakeholders/
├─ 03_Users/
├─ 04_System/
├─ 05_Competitors/
├─ 06_Personas/
├─ 07_Journeys/
├─ 08_Process/
├─ 09_Data/
├─ 10_Stories/
│
```

#### Input

Anything from the client, or information gathered external to your team.

#### Stakeholders

Anything related to the stakeholders of the project, who are they, what their goals are, their hopes and fears. Interviews or workshops you have had with them, and finally any reports that you are preparing for them.


#### Users

Same as the stakeholder folder, this is anything that is related to the users, who they are, goals, hopes, fears, interview, workshops. This also includes any documents you are preparing to share about the users to others.

#### Systems

Depending on the client or project, you will be working within certain systems. This folder is about anything related to the context you are working within. Is there a particular framework, technology, hardware you need to work with, all of that information goes here.

#### Competitors

All information related to your competitors, depending on the amount of competitors or how you are approaching the analysis. You can do create subdirectories based on **Review Type** or **Competitor**.

#### Personas

Take all the information you have gathered and compile your personas

#### Journeys

Take all the information you have gathered and create your journeys. These should be all journeys, now, proposed, future.

#### Process / Flows

This folder is about any specific process that you need to follow. Does your experience or systems have any specific requirements? Maybe X needs to happen before Y, but not when you select Z. Those requirements and process needs to be documented, this is the place for that.

#### Data

Whenever possible you should be creating with data, this is where the data samples go. If you have samples of blog content, Twitter data, product exports, reviews, whatever. If its real data, it should go here.

#### Stories

The user stories you are working from, "As X i want to do Y so that i can Z". If your working in a more feature drive environment just change the name of the folder.

### 02_Explore / Experiment

This is a working folder for everything you want to try, or think could work:
- Inspiration
- Rough work
- Tests
- Experiments

This folder also includes all previous research, things you have received from the client, what you have learned about and from the stakholders, users, competitors, etc.

This folder includes everything you think could work, things that are currently being tested, things that are being validated.

```
02_Explore/
├─ 01_Inspiration/
├─ 02_Moodboards/
├─ 03_Scamps/
├─ 04_Sitemap/
├─ 05_Structure/
├─ 06_Wireframes/
├─ 07_Prototypes/
├─ ?Method/
├─ Experiments/
├─ Tests/
├─ Sprints/
│
```

#### Inspiration

Any screenshots, pictures, colors, photos, that may be relevant to help start the creative process

#### Moodboards

Need to create a visual identity, particular look and feel, this is your working folder to iron that out before you share it with the client

#### Scamps / Concepts

Depending on where you live you might have a different name for this, but its the really rough and dirty sketches you make in your notebooks, working sessions that start to form what you are making. Just have a bunch of photos of those sketches, no problem, put them here.

#### Sitemaps / App Maps

Depending on what your making this will be different, but how is the technical structure of what you are making put together.

#### Structure

This is the hiarchy of information of what you are creating. Content strucutre, IA, data structure concepts, these all go here.

#### Wireframes

Need low fidelity but with real content and structure? All your wireframes go in here. If you have a design system and you go straight into design no problem.

#### Prototypes

Depending on your team, tools, and type of product you are creating your prototypes go in here. These could be links to Figma, Miro, InVision, Marvel. It could also be your Framer prototoype files, or if you create a coded sample put that here.


#### Method

This is a sample of a few different types of experimentation methods, but feel free to use whatever works for you

#### Sprints

If your team uses sprints, drop the folder here. Each sprint you'll have:
- Input (What you are going to do)
- Working (The working folder for anything your doing)
- Ready (Whats ready to demo)
- Document / presentation about what happened during the sprint. If your using a ticket system such as Jira, Trello, etc, just export a sprint report.

#### Tests

If you use a testing methodology use that folder instead.
- Input (What you are testing)
- Working (Working files for what you are testing, eg version A vs version B)
- Results (What the results of each of the versions was)
- Document / presentation about what the results of the test where

To make it easier you can also include the results of the test in the file names, this makes it easy to see at a glance which tests one, and which ones failed.

#### Experiments

If you use an experiments method use this folder instead
- Experiment_ID (Scope of test) What you are testing or flows
- EX001 (Dashboard) Homepage, Register, Login
- Document / Presentation about waht the results of the experiment where

### 03_Experience

This is the working folder for what you are building:
- Think of this as your master / live folder
- This should only include designs or versions which have been validated
- Dont put tests or experiements in this folder
- Someone should be able to go in here, and be able to trust they could build / develop it

The folder structure here is entirely based on what you are creating, thus the name the experience. Depending on the size and scope of what you are creating this could look very different. There are a few different examples

#### Flow based experience

```
03_Experience/
├─ [DEVICE]/
│  ├─ [DEVICE][SECTION] Flows/
│
├─ [Android]/
│  ├─ [Android][Homepage] Homepage, Register, Login/
│  ├─ [Android][Dashboard] Stats, Users, Disable/
│
├─ [iOS]/
│  ├─ [iOS][Homepage] Homepage, Register, Login/
│  ├─ [iOS][Dashboard] Stats, Users, Disable/
│
```

#### Multi device experience

```
03_Experience/
├─ DEVICE/
├─ Android/
├─ iOS/
│
├─ Web/
│  ├─ Desktop/
│  ├─ Mobile/
│
```

#### Small experience

```
03_Experience/
├─ PAGE/
├─ SECTION/
├─ Dashboard/
├─ Products/
│
```

#### Large experience

```
03_Experience/
├─ TOOL_1/
│  ├─ SECTION/
│  ├─ PAGE/
│  ├─ Dashboard/
│
├─ TOOL_2/
│  ├─ SECTION/
│  ├─ PAGE/
│  ├─ Dashboard/
│
```

Why is there no **Dev or Code** folder inside the experience folder?

- Most shared folder strucuters are not well suited for changing code
- You should not develop in a shared folder, npm install will cause 30,000 files to sync to all team members 😩
- There is also no good way to version code when compared to Github, Gitlab, Bitbucket, SVN, etc
- The long directory structure will cause compile errors on certain systems
- Anything you compile here can break for someone else

Where do you put **Code**?

- Code is stored in repos, Github, Gitlab, Bitbucket, etc.
- Development is done on local machines with short path names ~/Dev/ProjectName/
- Use a trusted, easy branching, version system like Git, Perforce, SVN, depending on your project needs.
- Production ready, compiled and zipped builds are stored in the delivery folder 

### 04_Delivery

**This is your output folder, never work on files in this folder**
Everything in here should be the latest version of all the other work you have done.

If your not using a shared system such as Zeplin or Avocode, this would be your designers export folder.

```
04_Delivery/
├─ Code/
│  ├─ Bundled-Game/
│  ├─ Versioned-Compiled-Website/
│
├─ Design/
├─ Images/
├─ Presentations/
├─ Screenshots/
├─ Videos/
│
```

Essentially anything you are going to share external to anyone outside of the team, when you click 'Browse for file' in Slack, Email, whatever, that file should be coming from here. Never edit from this folder. If you need to make changes to a file, create a new version in the files original location, and expor the new version to here.

This not only ensure everyone can trust this folder, but means that you are versioning everything else correctly. If the client or anyone asks for a file, you should be able to quickly go here and send it, or present all those times someone asks to see what you have.

## FAQ

### Q: Why dont you include project name conventions?
**A:** Every team, company and project is different. If you use a ticket system, use the project ID, otherwise you can use the project name, or a combination of Client + Year + ID. There are too many variables to have it be consistent for everyone.

### Q: Why do you have the Date in the name?
**A:** Versions are not enough, people and clients are not consistent in when the increase the version number, and the version 1 you recieved yesterday could be very different from the version 1 you receive today.

### Q: Why is the date YYYY-MM-DD
**A:** It makes it universal and consistent so that the latest file will always be either on top, or at the bottom depending on how the user has chosen to sort.

### Q: Why is the date sometimes at the front and sometimes at the end?
**A:** There are two main types of files, those that are based on the date they occured / are created, and those that can live for a long period

- Documents which have date significance, contracts, meetings, presentations, photos, receipts, Interviews, etc. Thes are prefixed with the Date, this does so that you get a sense for the chronology and can known when items where delivered.
  - 2021-01-01-Meeting with Jane
  - 2021-01-02-Meeting with John
- Items which will last for long periods of time such as design files, experiements, etc. These are suffixed with the Date, this groups the same files together. This is thanks to the version taking precendence over the date, so older versions can be updated while still keeping the latest at the top/bottom.
  - DesignFile-v1.0-2021-01-01
  - DesignFile-v1.1-2021-01-26
  - DesignFile-v2.0-2021-01-02

### Q: Why do you sometimes use dash (-) and sometimes underscore (_)
**A:** Anything that can be separated by a space or logically put in a subfolder is separated by a dash. This makes it easier to search for all files from CLIENT-FILE_TYPE-VERSION

- You can search by client
- You can search by file type
- You can search by version
- You can search by date

Items that should not be separated use an underscoe Project_File, User_Story

### Q: Why dont you just use spaces?
**A:** Certain files and folders can have spaces in them, as long as the rule that anything that can **EVER** be put online, should not contain spaces. Essentially anything inside the **Delivery** folder cannot have spaces. This prevents URL encoding from adding '+' or '%20' to the names you add. I have just using this convention throughout as depending on the system you are using spaces can become a pain. This is especially true if you are a developer and you need to escape each space when going through folders.

### Q: Why dont you do X instead of Y?
**A:** This is the system that I have built up based on the scenarios I have encountered. If you have a use case please make a suggestion

### Q: This doesn't work for X scenario?
**A:** Please add a comment and I'll see if I can make it work

### Q: This is stupid!
**A:** Not a question, but a valid oppinion.

### Q: Can I just use this for myself?
**A:** Please do, if you have any comments on how to make it better please open a ticket

### Q: Can I contribute?
**A:** Jepp, just open a pull request with your edits and we can start a discussion

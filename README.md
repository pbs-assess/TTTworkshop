# TTTworkshop
TESA workshop on tools for transparent, traceable and transferable assessments

## Logistics

**When:** Tuesday 27th to Friday 30th November 2018 (note that these dates changed from the original announcement a while back).

**Where:** [Coast Bastion Hotel](https://www.coasthotels.com/hotels/bc/nanaimo/coast-bastion-hotel/), Nanaimo, BC.  

**Accommodation:** 
The hotel has set aside 20 hotel rooms for 26th-30th November, at $117 each (Comfort Rooms).
Phone group code CBI-GFC18589 or just use the link [http://coa.st/yuk5](http://coa.st/yuk5).

Please book once you know your travel plans as they like to see some uptake of the rooms. In any case, any unbooked rooms will be released on **27th October**.

**Flights**

Fly into Nanaimo airport (YCD). Air Canada Rouge now has direct flights from Toronto but not every day, so may be worth looking into.

Taxi is about $50 or there is a cheaper [shuttle bus](https://nanaimoairporter.com/). Good idea to book either one ahead (there aren't always too many taxis at the airport). Taxi info [here](http://www.nanaimoairport.com/air-guide/transportation). 

## Workshop outline (rough, subject to evolution)

### Purpose
A workshop to foster a common understanding of modern methods and tools
in DFO that enables an exchange of knowledge, data and 
 methods for stock
assessment. This should lead to a greater transparency and reproducibility in the assessment process in DFO.

### Chairs
Andrew Edwards (PBS) & Daniel Duplisea (IML)

### Overview of tools to be introduced

We will introduce and demonstrate a number of tools that, when used together, give a very efficient workflow for working on large complex collaborative documents (and other projects).

A quick overview of some of the tools is:

Git and GitHub - a version control system for keeping track of changes to files and for collaborating with other users. 

knitr - combines R code and write-up of results, such that reports can be automatically generated, and easily updated when, say, an assessment model is updated.

Rmarkdown - a simplified way to use knitr with very simple formatting commands 

csasdown - an R package to format a Res Doc in the CSAS style 

### Updated schedule (still subject to change as we get closer)

**Note:** The original idea for the workshop mentioned TMB (Template Model Builder) a fair bit as many people had taken the TESA TMB course in January 2018. However, we will focus more on building assessment documents based on the output of models, rather than running the models themselves. So whether the assessment model is run using TMB or something else is not so important for this workshop.

If anyone does have TMB code that they using operationally (we do have some but have not used it for real assessments yet) they can hopefully integrate it into the workshop. But knowledge of TMB is not necessary for everyone, and we may end up not mentioning it all unless someone has a working example.

#### Tuesday

| Time |  |
|  ---- |  - |
| 9:00 | Introductions |
| 9:15 | Motivation for workshop (Duplisea and Edwards) |
| 9:45 | Some motivation for using Git (Edwards) |
| 10:15 | An interactive introduction to Git (Edwards and Grandin) | 
| 10:30 | Break |
| 10:45 | Introduction to Git (including exercises) |
| 12:00 | Lunch |
| 13:15 | Introduction to Git (including exercises) |
| 14:45 | Break |
| 15:00 | Introduction to Git (including exercises) |
| 16:20 | Overview of the day and plan for tomorrow |


#### Wednesday

Quick recap of Tuesday.

Simple knitr example and exercises using Rmarkdown, to show automatic (re)generation of figures and tables into a report (Edwards).

Minimal Working Example of building a Res Doc using [csasdown](https://github.com/pbs-assess/csasdown); just use Sean's built-in example (Anderson?).

Simplified version of Pacific Cod assessment, with some exercises for participants (Grandin). If the model changes and is re-run then the whole document
is automatically updated, including figures, tables and values in the text. This is especially valuable for assessments conducted annually.

Technical Report example, including ongoing building of Proceedings for this meeting (Grinnell).

Maybe: further general tricks, tips and lessons learnt through our ongoing experiences with annual Pacific Hake, Pacific Herring and Pacific Cod assessments, and with the Groundfish synopsis report. We are gradually working out the best workflow for such projects.
 
#### Thursday

Quick recap of Wednesday.

Thursday morning - Rpackages introduction (Anderson?). Originally we were not going to include this, but having everything in packages does make life easier. And it helps to understand how packages are structured (when you want to delve into them). A short intro will help participants be able to read Hadley Wickham's [free Rpackages book](http://r-pkgs.had.co.nz/).


**Translation (the fourth T?)** This is becoming more of an issue with people being asked to shorten their assessment documents to save on translation costs. And it is creating delays in getting Res Docs published (which is particularly problematic for annual assessments). 

Thursday, 1:15pm. Ann Mariscak from our local CSAS office will talk about the translation rules and what is working for getting Res Docs (in particular) translated.

We could look at Rowan Haigh's `linguaFranca()` R function, line 1007 [here](https://github.com/pbs-software/pbs-tools/blob/master/PBStools/R/M01_Utility.r). And maybe share code from participants from other regions.

#### Friday

To be determined by participants' desires. We should practice collaborating by making further examples. The best way to get the idea of these tools is by using them, and it helps to do this *not* during the busy process of actually doing an assessment. And in having a roomful of people to help you.

Short talk on experiences using GitLab enterprise (Ricard).

Form some working groups to, for example, generalise some code? 

Wrap up (Duplisea and Edwards).

----


**Other further ideas, keeping here for now**

 Participants to improve the existing code for documentation, producing figures and tables. They
 would extend code in a way that is generalisable, understandable and
 usable by others (e.g. R functions that are documented with options),
 while satisfying their local needs. Simpler surplus-production and
 delay-difference model examples could also be built. Participants can use
 their own existing code and make it generalisable to be used by others.

 As an example, there are likely many versions of R code that people use
 to display results of stock status with respect to the DFO
 Precautionary-Approach diagram. We could agree on one standardised
 (but still customisable) version across DFO.

**Original motivation** The workshop is very timely as it builds on the recent TESA "Introduction to TMB
workshop" that DFO participants attended and gave very favourable reviews.
If DFO stock assessment scientists are going to convert their existing models
into TMB then it makes sense to at least start from some common methdology. This
will also make it easier to incorporate ecosystem effects into such models,
since TMB code is relatively short, and common starting point will allow
assessors in different regions to build upon each others' experiences. **Current thinking** TMB will **not** be a major part of the workshop, but if people do move towards TMB in the future then this workshop will help that, and if they don't plan on using TMB then the workshop is still completely appropriate for building assessment documents.

Note that
the aim is **not** to have all assessors using the exact same models (or to build something like Stock Synthesis), but to start
from a similar understanding, to share understanding in building stock
assessment documents, and to generate efficiencies by easily sharing computer code.



## Workshop dinner

We will have a group dinner for those interested -Thursday 6:30pm at the [Firehouse Grill](http://www.firehousegrillnanaimo.com/).

## Prerequisites

Very proficient in R: know how to write functions, construct and tailor figures.

Knowledge of LaTeX desirable but not essential, since Rmarkdown and pandoc will also be introduced.

Some TMB knowledge may be desirable - if you have a TMB model that you use then please share it (we do not have any operational models yet in Pacific Region).

## Computer programs to be installed

To be determined. We will send out an email the week of 12th November. You will very likely need admin privileges.

## Products

Proceedings (Can. Tech. Rep.), which can hopefully be collaboratively written during the workshop as an example of efficiently producing a document.

GitHub repositories to share code.

### Participants

(From Susan's 23rd July spreadsheet, Andy updated Pacific participants, then continually updating as necessary).

If you cannot attend then please email me and your local TESA rep.

| Region | Name | 
| ------ | -----|
| C&A   | Ross Tallman |
| C&A   | Kevin Hedges |
| C&A   | Xinhua Zhu |
| C&A   | Kim Howland |
| QUE   | Daniel Duplisea |
| QUE   | Mathieu Desgagnés |
| QUE   | Hugues Benoit |
| GULF  | Daniel Ricard |
| GULF  | David Fishman |
| GULF  | Tobie Surette |
| NL    | Mark Simpson |
| NL    | Bob Rogers |
| NL    | Laura Wheeland |
| NL    | Krista Baker |
| NL    | Luiz Mello |
| PAC	| Kendra Holt |
| PAC	| Carrie Holt |
| PAC	| Jaclyn Cleary |
| PAC   | Catarina Wor |
| PAC   | Shannon Obradovich |
| PAC   | Jackie King |
| PAC   | Erika Anderson |
| PAC   | Cameron Freshwater |
| PAC   | Brendan Connors |
| PAC   | Chris Rooper |
| PAC   | Michael Folkes |
| PAC   | Lingbo Li |
| PAC   | Philina English |
| NCR   | Rob Kronlund |

### Instructors

| Region | Name | 
| ------ | -----|
| PAC	| Andrew Edwards |
| PAC	| Chris Grandin |
| PAC	| Sean Anderson |
| PAC	| Matt Grinnell |
| PAC   | Elise Keppel |

For email list: Add Philina. Leave Brooke and Marianne on even though they can't make it.
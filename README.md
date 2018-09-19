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
in DFO that enables an exchange of knowledge, data and methods for stock
assessment. This should lead to a greater transparency and reproducibility in the assessment process in DFO.

### Chairs
Andrew Edwards (PBS) & Daniel Duplisea (IML)

### Updated schedule (still subject to change as we get closer)

**Note:** The original idea for the workshop mentioned TMB (Template Model Builder) a fair bit as many people had taken the TESA TMB course in January 2018. However, we will focus more on building assessment documents based on the output of models, rather than running the models themselves. So whether the assessment model is run using TMB or something else is not so important for this workshop.

If anyone does have TMB code that they using operationally (we do have some but have not used it for real assessments yet) they can hopefully integrate it into the workshop. But knowledge of TMB is not necessary for everyone.

#### Day 1

Motivation for workshop (Duplisea and Edwards).

Introduction to git and GitHub for easily sharing code and collaborating (Edwards and Grandin).

#### Day 2

Importing results from an assessment model into a knitr/LaTeX/Rmarkdown format to automatically
generate figures and tables. The structure for setting up such a system
will be explained, based on our experiences with annual Pacific Hake,
Pacific Herring and Pacific Cod assessments. Code is easily shared between authors via GitHub so that they can continually build the updated document.

If the model changes and is re-run then the whole document
is automatically updated, including figures, tables and values in the
text. This is especially valuable for assessments conducted annually.
Led by Edwards, Grandin, Anderson, Grinnell, ... 
 
#### Days 3-4 (rough ideas)

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

### To incorporate into schedule

Building of R packages - this is fairly easy now.

Dan R. to discuss experiences using GitLab enterprise.

## Workshop dinner

We will have a group dinner for those interested -Thursday 6:30pm at the [Firehouse Grill](http://www.firehousegrillnanaimo.com/).

## Prerequisites
Very proficient in R: know how to write functions, construct and tailor figures.

Knowledge of LaTeX desirable but not essential, since Rmarkdown and pandoc may also be introduced.

Some TMB knowledge may be desirable - if you have a TMB model that you use then please share it (we do not have any operational models yet in Pacific Region).

## Computer programs to be installed

To be determined. May need admin privileges.

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
| C&A   | Marianne Marcoux |
| C&A   | Kim Howland |
| QUE   | Daniel Duplisea |
| QUE   | Mathieu Desgagnés |
| QUE   | Hugues Benoit |
| QUE   | Marie-Julie Roux |
| GULF  | Daniel Ricard |
| GULF  | David Fishman |
| GULF  | Tobie Surette |
| NL    | Mark Simpson |
| NL    | Bob Rogers |
| NL    | Laura Wheeland |
| NL    | Karen Dwyer |
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
| NCR   | Rob Kronlund |

### External participant
| Institute | Name | 
| ------ | -----|
| Northwest Fisheries Science Center, NOAA, USA | Ian Taylor|

### Instructors

| Region | Name | 
| ------ | -----|
| PAC	| Andrew Edwards |
| PAC	| Chris Grandin |
| PAC	| Sean Anderson |
| PAC	| Matt Grinnell |
| PAC   | Elise Keppel |

For email list: remove Heather Bowlby and Hai Nguyen, add Rob Kronlund, Brendan Connors, Michael Folkes and Chris Rooper (and leave Brooke on even though she can't make it).
# Project Capture Document for ECEN 160 HTML Quiz Tool Conversion
#### *Author: Cameron Thompson*
#### *Stakeholder(s): Corey Moore*
#### *Date: 4/26/2019*


## Background

Quality Assurance will run an audit of ECEN160 links, quizes in D2L where there are external files for the questions as a "tool" that reference brightspace and need to be removed so they will work in canvas.

Examples: (Will be depreciated when Brightspace goes 'offline')
- https://byui.brightspace.com/content/enforced/32043-Online.Reference.ECEN160/TT_3input_2output_L3_theorem.html
- https://byui.brightspace.com/content/enforced/32043-Online.Reference.ECEN160/TT_3input_1output_generic.html
- https://byui.brightspace.com/content/enforced/32043-Online.Reference.ECEN160/Boolean_expressions.html

<!--

Explain the context of the problem.
Explain key terms/words, words that may be unfamiliar to a new hire.


Do Example:

   Corey and his team have been manually going through the html for all images in canvas and filling in the alt attribute. This has been very time consuming.
   - Alt image text, also called "image alt text", or just "alt text", is the text that appears on html pages if the image fails to load.

Don't Example:

   Aaron TODO

-->

-----

## Definition of Done
Redo  the HTML pages that are quiz tools to not reference Brightspace/D2L.
All the pages will recreated to remove any references to Brightspace/D2L, they will keep the same functionality and will adopt some of the Canvas styling (Ex. Font, button style, Cleaner look, ect.). These pages will be stored in on contribution to Equella. The contribution will have the HTML files as well as the JS and CSS files.

<!--

What is/are the project outcome(s)?
("Can you give me one sentence describing what you want done?")
We are trying to clean up the yard by Mow, Edge, and Rake.

Do Example:

   We are creating a tool to find all images that are in need of alt text in canvas which will automate this process by showing an image and prompting for alt text.

Don't Example:

   Aaron TODO

-->


-----

# Requirements

### General Requirements
Keep the same naming convention for the HTML pages that is currently present in Brightspace/D2L. 

### Input Requirements

#### Definition of Inputs
A CSV list of quizzes, questions, and webpages that need to be converted to remove the reference from Brightspace/D2L.

[Link to the CSV data](https://docs.google.com/spreadsheets/d/1SR0fBQhIXrVsQvat1LPgAZkKTQHz0Ve_4rUF7tcJ-tQ/edit#gid=0)
<!-- List here a type definition for each input. For example, if it is a CSV define the column names. If it is a JSON, give an example of the JSON structure. If it is user input, what will the user be asked for? -->

#### Source of Inputs
Ashley will coordinate the audit of ECEN 160 with the Quality Assurance team 
<!-- Paragraph of how to get inputs. From who? From where: Slack, email, server...? This also includes user selected options at runtime. How will we know what options to select? For example, in conversion tool, you'd follow the values on the Trello Board. It would also include the steps to get access to the information you need, such as getting added to a Trello Board, or access to a server. -->

---

### Output Requirements

#### Definition of Outputs

<!-- List here a type definition for each output? For example, if the changes are directly to the LMS, list all changes that occur. If it is a CSV define the column names. If it is a JSON, give an example of the JSON structure. -->

#### Destination of Outputs

<!-- Paragraph where/who to send outputs. To who? To where: Email, server, directly to LMS...? It would also include the steps to get access to the locations you need, such as getting added to a Trello Board, or access to a server, or the LMS. -->

---

### User Interface

#### Type: None

<!-- CLI with Flags, CLI With Prompt, Web Page, Server, Library, etc -->

<!-- What are the flags, what are Major Questions, Images of UX/UI Design. -->

-----

## Expectations

### Timeline

<!-- Include Milestone List here with Deadlines and try to make each milestone a minimum viable product
- Milestone 1: Finish Design (3/19)
- Milestone 2: Build Core logic to search for words in syllabi (3/22)
- Milestone 3: Connect inputs to core logic and set up outputs (3/25)
- Milestone 4: Deliver the project (3/26)
This will probably be overkill for small projects -->

one month deadline

### Best Mode of Contact
Contact Corey or Ashley via Email.

### Next Meeting


### Action Items
<!-- Recap Meeting -->
#### TechOps
#### Stakeholder
Spread sheet to keep track

Ashley will share the spreadsheet monday

-----

#### *Approved By:*
#### *Approval Date:*

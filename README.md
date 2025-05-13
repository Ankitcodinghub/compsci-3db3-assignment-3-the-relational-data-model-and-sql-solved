# compsci-3db3-assignment-3-the-relational-data-model-and-sql-solved
**TO GET THIS SOLUTION VISIT:** [COMPSCI_3DB3 Assignment 3-The Relational Data Model and SQL Solved](https://www.ankitcodinghub.com/product/compsci_3db3-assignment-3-the-relational-data-model-and-sql-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92604&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMPSCI_3DB3 Assignment 3-The Relational Data Model and SQL Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Description

Our local cinema chain recently introduced a subscription service that gives regular visitors the option to watch a film at their cinema whenever they want for a fixed price per month. To promote this new service, an online community consultant proposed to expand the cinema website with elements that encourage engagement. To do so, the consultant proposed to build a social online environment into the cinema ordering website such that subscribers can review and discuss films and make friendships with other subscribers. The consultant already put in some legwork by providing an ER-model for this social online environment and a relational schema to store basic film information.

The consultant provided a two-part design. The first part describes the social media features and the second part describes a high-level sketch of the information maintained per film (which the consultant figured would be of use for other parts of the website as well).

Part one: The social media features

The social media features center around its users (the subscribers). Users have usernames, which are not necessary unique. To distinguish users with the same username, the consultant proposed to assign each such user a different number. Users will log in using their unique email address and a password. According to the consultant, the password should not be stored in plain text, but as a pair of a 512-bit (64-byte) hash and a 64-byte salt value. Together, the hash and salt are sufficient to determine whether a login attempt provided the right password, this without providing easy access to the stored password (even if the system gets compromised).

The social media features break down in three types:

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;Users can befriend other users. If a user 𝑋 indicates that 𝑌 is a friend, then this indicates that 𝑋 follows the activities of 𝑌 , but this does not imply that 𝑌 is also a friend of 𝑋 .</li>
<li>􏰀 &nbsp;Users can review films. Each review assigns a score to the film and reviews can be revised with more information. Each review can optionally have a video component (e.g., as in a vlog) and optionally have a text component (e.g., as in a blog).</li>
<li>􏰀 &nbsp;Users can place reactions on reviews and on other reactions (a reaction is either on a single review or on a single reaction, but not on both).
The ER-Diagram for the social media feature can be found in Figure 1. Part two: The film information

The consultant sketched the following layout of the database maintaining film information, but indicated that some details still need to be figured out:
</li>
</ul>
<ul>
<li>􏰀 &nbsp;A table person(id, name, birthdateoptional).

This table provides basic information on people that work on films.</li>
<li>􏰀 &nbsp;A table film(title, year, creator, duration, budget).

This table represent films. The consultant figured out that films can have the same title and be released in the same year (e.g., in 2005 there was a film Chaos directed by Tony Giglio and another film Chaos directed by David DeFalco—The consultant didn’t see either of them, however). To distinguish between films with the same title and made in the same year, the consultant proposed to use the main director (creator, which refers to the id column in the person table) of the film.</li>
<li>􏰀 &nbsp;A view film_info to easily retrieve a film (columns title, year, duration, and budget) together with the name of its creator (column creator_name).</li>
<li>􏰀 &nbsp;The consultant wants a table role that stores, per film, all people that worked on the film and on the role these people had (e.g., actor, writer, director, producer, costume, casting, editor, or makeup). The consultant had difficulties coming up with a proper design for this table, but noted that people can have several roles in the same film.</li>
<li>􏰀 &nbsp;A constraint that all film creators (mentioned in the film table) have the role of director for that film (as recorded in the role table).
Assignment

The goal of the assignment is to translate the above description into proper SQL statements that create tables and set up all required constraints. To do so, you proceed in two steps. First, you write a report in which you step-by-step translate the ER diagram of part one (Figure 1) into a relational schema and complete the details of the relational schema of part two. Next, you provide the translation of your relational schema into a sequence of SQL statements that will set up the database. Your submission:

<ol>
<li>must be two files: a PDF file with the report and a plain-text file (txt) with the SQL statements to set up the database;</li>
<li>must include (in the report) a clear description of the steps taken to translate the ER diagram of part one to SQL tables, each choice made during this translation, and each constraint present;</li>
<li>must use the constructs presented on the slides or in the book (we do not allow any system-specific constructs that are not standard SQL);</li>
</ol>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Friend_Of

</div>
<div class="column">
number

</div>
</div>
<div class="layoutArea">
<div class="column">
username

</div>
</div>
<div class="layoutArea">
<div class="column">
email

hash

salt

</div>
</div>
<div class="layoutArea">
<div class="column">
Subscriber

</div>
</div>
<div class="layoutArea">
<div class="column">
title content

</div>
<div class="column">
id By

On_Reaction ISA

</div>
<div class="column">
Author

On_Review

</div>
<div class="column">
ForFilm

</div>
<div class="column">
The table film

(from part 2)

revision

score timestamp

description

</div>
</div>
<div class="layoutArea">
<div class="column">
Reaction

</div>
</div>
<div class="layoutArea">
<div class="column">
Review

</div>
</div>
<div class="layoutArea">
<div class="column">
ThreadR

</div>
</div>
<div class="layoutArea">
<div class="column">
ReviewR

</div>
</div>
<div class="layoutArea">
<div class="column">
ISA

</div>
</div>
<div class="layoutArea">
<div class="column">
VideoReview

</div>
</div>
<div class="layoutArea">
<div class="column">
TextReview

</div>
</div>
<div class="layoutArea">
<div class="column">
video

Figure 1: ER-Diagram for the social media features.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
from

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
to

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
4. must work when using DB2 (on db2srv2): test this yourself!

Submissions that do not follow the above requirements will get a grade of zero.

As multi-table checks via CHECKs and ASSERTATIONs are not supported by DB2 or any other major DBMS, you do not need to use these constructs in your solution. Make note in your report of all constraints present in the description that you cannot express via the constraint types we have seen for SQL or which can only be expressed via multi-table CHECKs and ASSERTATIONs.

Grading

The final grade will be split between part one (75% of the grade) and part two (25%). While evaluating your work, we will look at:

completeness Does your solution contain all tables and constraints described in the requirements?

correctness Does your solution use the correct SQL syntax and do you take the right decisions in your translations? Are all included constraints correct? Do all excluded constraints have a proper motiva- tion?

presentation Is the report readable? Does the report properly motivate the choices made while translating toward SQL?

The maximum grade for part one is equally determined by the quality of your translation of each of the entities and relationships, whereas the grade for part two is equally determined by the quality of the translation of the five items. Every SQL error will result in a reduction of the overall grade (with the lowest possible grade being zero).

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>

# nosql-challenge
Week 12, NoSQL, non-relational databases

code source: mary mackin, from listening to and participating in class lectures & office hours https://github.com/maryemackin/nosql-challenge.git

NoSQL for Mere Mortals, Author Dan Sullivan, Publisher Addison Wesley 2015

MongoDB Documentation https://www.mongodb.com/docs/

ProGit 2nd Edition Authors Chacon & Sraub Publisher Apress 2014


* Homework note: In the notebook file NoSQL_analysis_starter.ipynb, Part 3: Exploratory Analysis, Section 2: "Which establishments in London have a RatinvgValue greater than or equal to 4?"

The first part instructs: "# Find the establishments with London as the Local Authority and has a RatingValue greater than or equal to 4."

The result of the query created per the instructions is 0 documents.  There are no documents with "London" in the field "LocalAuthorityName".  There are however, 512 documents with "London" in the field "AddressLine4".

I completed the assignment usiung "AddressLine4" instead of "LocalAuthorityName" as we would have no results if we use the latter.

Mary Mackin
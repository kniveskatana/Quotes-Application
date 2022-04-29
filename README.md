# Quotes-Application
Angular quotes is a web apllication where users can create quotes and have those quotes voted on whether they are appalling or are inspirational.

##### By Joan Deng

## Table of content

- [Description](#description)
- [User Requirements](#requiements)
- [BDD(behaviour driven development)](#BDD)
- [Licence](#licence)

## Description

Angular quotes is a web apllication where users can create quotes and have those quotes voted on whether they are appalling or are inspirational.

### User Requirements
The applications allows users to do the following

-Create a new quote.
-Upvote or downvote a quote.
-Delete a quote
-See the number of upvotes and number of downvotes for each quote. 

* Quote component-parent component
* Quote-form-component-for submitting the Quotes
* Quote-details-component- showing properties of the quote instance: author, publisher, time ago and votes

[Go Back to the top](#Quotes-Application)
 
## BDD(behaviour driven development)
* User submitting a quotes
Example Input quote,quote author and quote publisher
Example Output a section containing inputted quotes with votes init to 0
We use ngModels to do two way data binding from a template to a component a create an instance of a quote using the ngSubmit
* Delete a quote
  * Exampe Input delete quote 3
  * Example Output if confirmation() quotes.splice(3,1)
* Upvote a quote
  * Exampe Input upvote quote 3
  * Example Output quotes[3].upvotes +=1
* Downvote a quote
  * Exampe Input downvote quote 3
  * Example Output quotes[3].downvotes +=1
* Time ago
  * Exampe Input post a quote
  * Example Output a few seconds/ X minutes/ X hours/ X days quote.date| timeago


#### Set up process
* to clone this repo

``
Make sure you have all the Requirements or running angular apps installed such as node,npm, tsc and watchman
``

``
Clone the project into your machine from https://github.com/kniveskatana/Quotes-Application.git
``

``
cd Quotes-Application folder
``

``
code . to open the folder in your Vs Code
``


## live link
* [KatanaRistorante](https://kniveskatana.github.io/KatanaRistorante/)


[Go Back to the top](#Quotes-Application)

 
## Bugs
<p>if you encounter any bugs in the code, click <a href="https://github.com/kniveskatana/Quotes-Application/issues">here</a> your assistance will be valued

## Support and Contact Details
<p> If you encounter any problems running this Website, please reach out to me via email @joan.deng@student.moringaschool.com .</p>

## Copyright and Licence

MIT License

Copyright (c) 2022 kniveskatana

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Go Back to the top](#Quotes-Application)

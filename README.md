# Evaluator-app

## Description
**Evaluator-app** is the application that provides a customizable web-based evaluation form with data summarization and status reporting.  Event organizers can create a custom form for their event containing a list of entrants (contestants, projects, presentors, performers, etc) and a set of criteria that they are to be rated on. Criteria may also include guidance (help) on ratings.  There may optionally be space for entering comments.
The event organizers control who can view and submit an evaluation, and the time interval during which submission is allowed.  The organizers can elect to allow self-registration for open events.
The application authenticates each person who submits a form and ensures only one evaluation per person, although a person may revise and resubmit a prior submission, and evaluations may be submitted incrementally.  The application provides a status display for organizers that shows who has submitted an evaluation and whether its complete or not, but does not allow the organizer to view content of the evaluation. 
After the submittal period has ended, the application displays a summary of evaluations or scores, and provides access to comments.  It may limit who can view comments.
At some events the entrants/contestants are also allowed to submit evaluations. Students at KU can submit a senior project evaluation or vote at Exceed Camp even if they have a project entered in the competition.  The organizer can specify whether this is allowed and whether or not someone may evaluate his own project.

## Author
Name-Surname | StudentID | GitHub  
-------------|--|--------
Chatchapong Chumpada |6010546877| [**ChatchapongC**](https://github.com/ChatchapongC) 

## Prerequisites
- **Python** (v.3.6 or newer) : [Download](https://www.python.org/downloads/)

- **Virtual Environment**
    ```shell script
    > pip install virtualenv
    ```
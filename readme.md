# Activity 1
![image](https://user-images.githubusercontent.com/19890962/135788675-416e83cb-d49e-4120-9feb-634cc997daa8.png)

# Activity 3
![image](https://user-images.githubusercontent.com/19890962/135788693-86b03613-1801-4f44-b08e-c81c98366522.png)

# Activity 4
![image](https://user-images.githubusercontent.com/19890962/135788719-9b88a6df-f3ac-4d01-9cdb-18348900cd27.png)

Chang Yeon (Nick) Woo  
  
This repo is a clone of https://github.com/nelaturuk/education_pathways  
  
# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`

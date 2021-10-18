# CARTE Education Pathways

Janelle Cuevas

This is a clone of the repo: https://github.com/nelaturuk/education_pathways

Activity 1:

![image](https://user-images.githubusercontent.com/43123955/137651834-f2270397-9bca-4f89-beff-b40f4086f648.png)

Activity 2-5:
home page
![image](https://user-images.githubusercontent.com/43123955/137666989-65d1d903-ea2a-445f-8e3d-edc5185ee1d3.png)

form
![image](https://user-images.githubusercontent.com/43123955/137667020-2567971e-14a2-4b50-9d49-07ec563715a1.png)

table
![image](https://user-images.githubusercontent.com/43123955/137668726-5f3b6d17-f5ef-4102-8348-5935a32f4507.png)






Activity 6:
The search form is more clear in the new UI because of the form formatting. The headers in the search results are also more clear because of the header colour.


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

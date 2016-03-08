# Anaconda
Used for autocomplete and tooltips

## Setup
- Package control install anaconda
- Disable Jedi and code intel if you're still using that
- In sublime
	- Preferences -> Browse Packages
	- Create a folder called python and go into it
	- `wget --no-check-certificate https://raw.githubusercontent.com/DamnWidget/anaconda/master/Completion%20Rules.tmPreferences`


Settings for chris:
```
"anaconda_linting_behaviour": "save-only",
"anaconda_linting": false,
"anaconda_gutter_marks": false,
"pep8": false
```
### Attention
This script has been made for educational purposes **ONLY**. It is illegal to automate interaction with the Facebook website, and the author shall not be held liable for any such actions.

# Facebook Tagging Automation

A little Python program using selenium. Enables tagging multiple persons on a comment in Facebook.

## Features
+ Tag multiple people
+ Ability to exclude those who have already seen the post
+ Fuzzy matching of names

## Limitations
+ Only matches names, so the script cannot differentiate between people with same names

## How it works
1. Edit the contents of `config.toml`  according to your needs.
2. Add the names to tag in `data/names.txt` and  the ones to exclude in `data/exclude.txt`.
3. You may need to force disable website notifications in Firefox.
4. Run `pipenv install` to setup the virtualenv.
5. Ensure that the geckodriver is in system `PATH`, it is required by selenium.
5. To start the script, run `pipenv run python auto-tag.py`.

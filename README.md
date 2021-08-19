# Collaborating with GitHub

This repo was used for the webinar "Collaborating with Github" by [Microsoft Learn Student Ambassadors (MLSA)](https://studentambassadors.com/), organized by [Obumuneme Nwabude](https://obumnwabude.com/).

Find attendees who made created issues and made pull requests to this repo at https://mlsagithub.web.app

## Attendee Instructions

Having attended the "Collaborating with GitHub" event, create an issue, then send your pull request (that closes the issue you created) to get your name on the event site at https://mlsagithub.web.app. Carry out the following instructions to create an issue and to make your pull request. If you do not have a GitHub account, first create one [here](https://github.com/join).

Re-open this page on a new tab, so that you can refer to the instructions here and carry them out on that new tab. 

1. Click on the `Issues` tab.

2. Click on the `New Issue` button.

3. In both the Title and "Leave a comment" fields, enter "Add <YOUR-NAME> to the attendee website" without quotes and with your real name.

4. Click on `Submit new issue`. Take note of your issue number (it will be close to the title) of the issue you just created.

5. [Fork](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo) this [repository](https://github.com/obumnwabude/mlsa-github) by clicking on **Fork** at the top right corner of this page (Be sure you are viewing this README from github.com and as a desktop site).

6. In your fork, Go to the [`attendees.json`](public/attendees.json) file, found in the [`public`](public) folder.

7. In the upper right corner of the file view, click ![edit icon](edit-icon.svg) to open the file editor to [edit](https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/editing-files-in-your-repository) the `attendees.json` file.

8. Copy the sample attendee from the first opening brace - **{** - (on line 2) to the first closing brace - **}** - (on line 10), without the comma. What you copy should look like the following:

```
  {
    "name": "Your Name",
    "website": "https://example.com",
    "linkedin": "https://linkedin.com/xx/xxx",
    "facebook": "https://facebook.com/xxx",
    "twitter": "Your Twitter Username",
    "github": "Your Github Username",
    "instagram": "Your Instagram Username"
  }
```

10. Scroll to the end of the `attendees.json` file, add a comma - **,** - immediately after the last closing brace - **}** -, and press the enter key.

11. On the new line, paste the sample you just copied.

12. Edit the values with yours. Please verify that they are correct. `name` is compulsory.

#### Note:

If you don't have any social media, please delete the sample value for that social media and leave the content of the quotation marks empty.

13. Type the following as the title of your commit message at the bottom of the page. Use your name instead.

```
    YOUR-NAME attended the MLSA Github Event
```

14. Type the following in the description box. Use your issue number. Include the hash symbol.

```
  Closes #ISSUE-NUMBER
```

15. Click on the green `Commit changes` button.

16. Visit the following link on a new tab. Use your GitHub username instead (don't delete the three full stops).

```
    https://github.com/obumnwabude/mlsa-github/compare/main...YOUR-GITHUB-USERNAME:main
```

17. Type the following as the title of your pull request at the top of your page. Use your name instead.

```
    YOUR-NAME attended the MLSA Github Event
```

18. Click on the green `Create pull request` button.

### Hooray!!!

You have just made a pull request. When your pull request will be merged, your name will reflect on the event site at https://mlsagithub.web.app

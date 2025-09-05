# Getting started with Git Lab
## Instructions
In this lab, we'll be going through some basic tasks you'll need to do as you manage the GitHub repository for your CollectionBuilder site. The questions below are designed to help you learn and remember what you need to do to perform these tasks, as well as where you can go to look for help. 
## Creating your repository and editing files
**What did you click on to create a new repository in the web interface of Github (i.e., on Github.com)?**

Create New > New Repository

**What is the difference between a private and a public repository?**
>  From GitHub Docs: "Public repositories are accessible to everyone on the internet. 
> Private repositories are only accessible to you, people you explicitly share access with, and, for organization repositories, certain organization members."
>


**Once your repository has been made and has at least one file, what button do you need to click on the web interface in order to create a new file in your repository?**

Add File > Create new file

**Describe the steps you took to clone your repository on Github Desktop**

Clicked on my repository file from within Github desktop, then clicked clone

**What is the title of GitHub documentation?**

GitHub Docs

**What is the URL for GitHub documentation on creating your first repository?** 

https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories

**Where is your local repository versus the remote repository?** 

The local repository is saved on my hard drive, while the remote is saved on the cloud.

**What happens when you fetch?** 
> From the glossary: "When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch."


**What happens when you pull changes/commits?**
> From the glossary: Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. 

**When working on GitHub Desktop, what order should you generally perform push, pull, and fetch?** 

You would probably fetch the file first to work on it. Then, once you change it you would push those changes to the cloud. Then, if someone else changed the remote file, you would pull those changes to your local file

**What happens when you push commits from your local repository?**

It updates the remote file, but all previous versions are still saved.

**What is the URL for the Github glossary?**

https://docs.github.com/en/get-started/learning-about-github/github-glossary

**Where can you find a list of your commits?**
On the repository homepage, there's a clock with the number of commits. You can click that to see them all

**What is the URL for documentation on reverting a commit?**

https://docs.github.com/en/desktop/managing-commits/reverting-a-commit-in-github-desktop?versionId=free-pro-team%40latest&productId=repositories&restPage=creating-and-managing-repositories%2Cquickstart-for-repositories

**How do you revert a commit?** 

On GitHub Desktop: History > Revert Changes in Commit

## Git-flavored markdown
**What is the name of the page or URL in GitHub documentation where there's information on how to format your Markdown for GitHub?** 

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

**What precedes a second-level heading in Github markdown?** ##

**How do you indicate text that has been struckthrough?** 

~~ ~~ or ~ ~ Example: 	~~This was mistaken text~~

**How do you create a hyperlink in your markdown?** 

You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut Command+K to create a link. Example: [Link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)

**How do you link to a section in the same or another markdown file?** 

It's similar to a weblink, but you add # before the section title. 

Remember the following rules for creating an anchor:If you need to determine the anchor for a heading in a file you are editing, you can use the following basic rules:

    - Letters are converted to lower-case.
    - Spaces are replaced by hyphens (-). Any other whitespace or punctuation characters are removed.
    - Leading and trailing whitespace are removed.
    - Markup formatting is removed, leaving only the contents (for example, _italics_ becomes italics).
    - If the automatically generated anchor for a heading is identical to an earlier anchor in the same document, a unique identifier is generated by appending a hyphen and an auto-incrementing integer.
 Example: [Return to Top](#getting-started-with-git-lab)

**What are the three possible symbols for indicating an unordered list?** 

You can make an unordered list by preceding one or more lines of text with -, *, or +.

**Format the following text into a footnote:**
Main text: Alex Wingate went to William and Mary[^1]. 

[^1]: [William and Mary](https://www.wm.edu/) is a university in Williamsburg, VA founded in 1693.  



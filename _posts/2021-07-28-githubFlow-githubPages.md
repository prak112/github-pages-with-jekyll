---
title: "Lessons learnt from GitHub Learning Lab"
date: 2021-07-28
---

# _**[GitHub Lessons](https://lab.github.com/)**_ 📑
    
### [GitHub Flow](https://github.com/prak112/github-slideshow.git)

Development of an idea or a project through GitHub involves the following -
    1. Create a repository
    2. Update README.md
    3. Build the project along the master/main branch
    
If a collaborator/yourself has a feature suggestion/bug correction for the project, then the following applies -
    1. Open a new branch entitled with feature/bug
    2. Commit changes to the branch
    3. Create/Open a Pull Request
    4. Review Pull Request and suggest/apply correction if needed
    5. Post-Review, Merge feature/bug branch to master branch
    
### [GitHub Pages](https://github.com/prak112/github-pages-with-jekyll) 📃
  
The developed project can be deployed as a website, considering we have the required information in the following files -
  1. _**INDEX.md or README.md**_
        information regarding the project being published
  2. _**_CONFIG.yml**_
        settings such as theme, author, title, brief description, social network handles.
  3. _**_POSTS/YYYY-MM-DD-title.md**_
        the _POSTS folder consists of the blog posts with timestamp & title, either as a .md or .html file


### [Merge Branch to Origin](https://github.com/prak112/merge-conflicts) 🤞

Task - main Branch (master) MERGED into Feature/Bug Branch 
1. for testing the new enhancement on the entire codebase (master Branch) 
2. for the application to run without conflicts/errors
3. merge conflicts might arise based on code compatibility, and if conflicts arise they should be sorted as suggested in [managing-merge-conflicts tutorial](https://lab.github.com/githubtraining/managing-merge-conflicts).
4. Post resolving merge conflicts, merge Feature/Bug Branch into main Branch(master)


### Securing Workflows 🎛️ ㊙️

- Sometimes vulnerabilities aren't in the code you write, but in the code your project depends on. 
- Staying up-to-date with the most recent versions is the best line of defense.
- Git uses a file called .gitignore to decide which files and directories to ignore when committing. 
- Keep files containing sensitive data, like configuration(.CONFIG) or environment (.ENV) files, out of the repositories.
- Check [here](https://github.com/github/gitignore) for more info about .gitignore files

</br>      

### *Constructive Feedback is highly welcome* 🔰 🤓

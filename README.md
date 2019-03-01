# hp-git-demo
silly repo for demonstrating some git stuff.  


## json code block for demoing merge conflicts.

```json
{
  "best_things":
  {
  "text_editor": "vim",
  "juicy_lucy": "5-8 club",
  "football_team": "green bay packers"
  }
}
```
## Commonly Used Commands
* `git clone` - Pull down a git repository into your current working directory.  To pull this repo: `git clone https://github.com/Freeze/hp-git-demo.git`
* `git add` - Start "tracking" a file with git.  `git add new_file.txt`
* `git commit` - After changes are made, use this to say the change is ready to go back to your Git host. `git commit -am "I have added a new file"`
* `git push` - This will push your changes back to the remote you clone your repository from, assuming you have the rights to write to that repo. `git push`

## Workflow
Let's leave this as simple as possible.  
1. `git clone` your repository
2. edit any files you need to edit.
3. `git add` any new files you may have created.
4. `git commit -am "message"` commit your changes, the best commit format is (Implied)<If commited, this change will....> (Actual Message)<do this>.

## Useful Tools
* [Git Bash](https://git-scm.com/download/win) is the best way to handle Git repositories on Windows aside from using an IDE.
* [Atom](https://atom.io/) is the IDE that Holden prefers to use when a GUI is required.  
* [Visual Studio Code](https://code.visualstudio.com/) is probably the most popular IDE, especially at HP.  Holden just likes Atom better.

## Useful Links
* [Roger Dudler's Guide](http://rogerdudler.github.io/git-guide/)  This is a great guide to Git.  It has swearing.  I will not recommend you read it at work because swear words are bad.  

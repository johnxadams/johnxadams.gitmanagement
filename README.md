###### john adams gitmanagement with ==markdown==

---

A simple git rule says: <br>
After git cloning a project out of cloud, the first thing to do renaming the remote which is **origin**. How do I rename and what's the new name going to be?

- [x] git remote rename origin upstream
- [ ] ~~git add remote origin upperstream~~
- [ ] ~~git super rename main origin~~

#### Here are a couple of git commands

| syntax                                                             | meaning                                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| git init                                                           | initializes directory-connection with gitHub                                   |
| git add _(+fileName)_                                              | add a specific workprogress to git                                             |
| git add .                                                          | adds all progress in directory to git                                          |
| git commit -m                                                      | add a message of what you've done so far                                       |
| git branch                                                         | In which branch am I ?                                                         |
| git branch -M main _(special case, only once)_                     | rename Master _(-M)_ into **main**                                             |
| git branch _super_                                                 | make a new branch, name it _super_                                             |
| git checkout _super_                                               | move to branch named _super_                                                   |
| git checkout -b _super_                                            | make a new branch, name it _super_, then move to _super_                       |
| git brand -d _super_                                               | remove branch named _super_                                                    |
| git remote -v                                                      | show me all the remote-project-connections                                     |
| ` git remote add origin git@github.com:johnxadams/projectName.git` | builds a bridge named **origin** from local _(user-pc)_ to cloud _(gitHub)_    |
| git remote remove origin                                           | remove origin                                                                  |
| git push -u origin main (special case, only once)                  | making sure the bridge is between main(local) and main(cloud), -u means update |
| git status                                                         | what's the current status of modification?                                     |
| git log                                                            | Show me the project-history                                                    |

---

_<p> Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. </p>_

#### Workflow

1. Starting with the: echo "_line number one!_" >> `README.md`
1. git init
1. followed by: git add `README.md` && git commit -m "what I've done so far"
1. let rename the branch: git branch -M main
1. now lets build the path: git remote add origin `git@github.com:johnxadams/johnxadams.gitmanagement.git`
1. now lets safe the path with: git push -u origin main

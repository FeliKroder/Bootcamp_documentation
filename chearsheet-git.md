git

- version controll system

repository

- container für das projekt
- jedes projekt bekommt ein repository

commit

- bestätigen und mitteilen der Änderungen

<br>

## Markdown Examples

| Element                                                                | Git Syntax                                                                                                      |
| ---------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| `git init`                                                             | Mach mir aus diesem Ordner in dem ich mich befinde ein Git Repo. Ordner hat dann einen versteckten .git Ordner. |
| `echo ".DS_Store" > .gitignore`                                        | Write something into a file, here into the gitignore file.                                                      |
| `git add .`                                                            | Add all files to the stage.                                                                                     |
| `git log --online`                                                     | Allgemeine Infos anzeigen, dann `q` drücken um aus diesem Modus raus zu kommen.                                 |
| `git status`                                                           | show what you added to the stage.                                                                               |
| `git commit -m "write your commit message here"`                       | After you added files to the stage, you can commit them and add a commit msg.                                   |
| `git push origin main` or `git push -u origin main`                    | if you push for the first time Push your commited files to the Github repository.                               |
| `git restore --staged <filename>`                                      | Von der Stage runternehmen und zu modiefied wieder "zurücksetzen".                                              |
| `**_italicized bold text_**`                                           | Macht alles bis zum letzten commit rückgängig, davor muss man die Datei aber von der Stage nehmen.              |
| `git remote -v`                                                        | Wo bin ich auf Github?                                                                                          |
| `git remote rm origin`                                                 | Remote Verknüpfung entfernen, z.B. wenn ich ausversehen https verwendet habe aber ssh will.                     |
| `git remote add origin git@github.com:FeliKroder/Nameofrepository.git` | push an existing repository from the command line                                                               |
| `git branch -M main`                                                   | Rename branch into main                                                                                         |
| `git push -u origin main`                                              | send commited branches to the main branch                                                                       |

<br>

<!-- add further git syntax:
git switch -c Nameofnewbranch

    git push -u origin feature/newname

    :bq  -->

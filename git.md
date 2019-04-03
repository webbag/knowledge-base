# Git

`git config --global user.name "name"`

`git config --global user.email "adres@email.pl"`

`git config --global color.status auto`

`git config --global color.branch auto`


### Move files with git and keep file history

Be sure you don't have files uncommitted, if not commit them before next step.

`git status`

* In project-directory create symfony subfolder

`mkdir symfony`

* Move files with git mv except symfony subfolder to avoid errors

`for file in $(ls | grep -v 'symfony'); do git mv $file symfony; done;`

* Move specific files like .htaccess etc...

`git mv .htaccess symfony/`

* Commit changes

`git commit -m 'Moved files to symfony/'`

* That's all !

`git log -M summary`

`git push bitbucket --tags`
`git fetch`
`git tag`
`git branch`
`git checkout v1.3.54`


`git reset --hard`


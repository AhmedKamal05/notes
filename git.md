# create a new repo 
* `cd` => where you will creat your file
* `mkdir` => create new folder
* `git clone` paste your ssh url (دا عشان يتم تعريف السيرفر والملف بتاعك)
___
## push your work
* `git status` to see files 
* `git add` **(file name)** => to add file in git
* `git add *` => to add all files
* `git reset head` **(file name)** => undo adding file 
* `git commit -m ` **"your comment here"**
* `*git branch` to see branches in your server
* `git push` **(RemoteName)** **(BranchName)** 
* `git remote add` **(name server)**
* `git remote -v` to see server added or not(بيجيب ال RemoteName)
___

### Configurations
* `git config -l` بيجيب ال list الخاصه بال configuration 
* `git config --global user.email` لو عاوز اجيب value specific زي ال email
* `git config --global user.email` **اكتب الميل**
* `git config --global --unset` **الي عايز احزفه**
* `git config --global --edit`  عشان نعمل edit بال editor 
* **touch <اسم الملف>.extension** => عشان اعمل فايل جديد في البروجيكت 
* `touch new_file.text` 

___
#### create project and upload to github
* `cd Documents`
* `mkdir` => <**name**>
* `cd` => <**name**>
* **create file for ex : `touch index.html`**
* `git status`
* `git add` index.html
* `git commit -m` "any text"
___
#### upload to git
* `git remote add origin` <**repo link**> بحط لنك الريبو الي عملته على github 
* `git push -u origin main`
**وظيفة الu انها تسحب التعديل الي حصل على الفايل وبعدها ارفع التعديل بتاعي**
___

## Tasks

### 0. Create and setup your Git and GitHub account

#### Step 0 - Create an account on GitHub

You will need a GitHub account for all your projects at ALX. You can create an account for free  [here](https://alx-intranet.hbtn.io/rltoken/hQPhGkQBxYfTYTYDKtrZvw "here")

#### Step 1 - Create a Personal Access Token on Github

To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

You can follow  [this tutorial](https://alx-intranet.hbtn.io/rltoken/1sEAC5BvAQ1G5VabbAl2iA "this tutorial")  to create a token.

Once it’s created, you should have a token that looks like this:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/a449483cd76a72cef1b42df831e686c64faa1cf6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220320%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220320T185145Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f37bc2853c349b41f47e88954ef2ce6929a4b8992c3d1036a7eab86865c22bf0)

#### Step 2 - Update your profile on the Intranet

Update your Intranet profile by adding your Github username  [here](https://alx-intranet.hbtn.io/rltoken/vHKiFlBLIC7VCcAWGWF8FA "here")

If it’s not done  **the Checker won’t be able to correct your work**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/6270480a0a982cd1846b877eda2ee405d2e8f575.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220320%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220320T185145Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8b6d3f2d1d4dcbe1053593da0b63e53b075253a673d7a96fe1e1962d69edb2e4)

#### Step 3 - Create your first repository

Using the graphic interface on the  [github website](https://alx-intranet.hbtn.io/rltoken/hQPhGkQBxYfTYTYDKtrZvw "github website"), create your first repository.

-   Name:  `alx-pre_course`
-   Description:  `I'm now a ALX Student, this is my first repository as a full-stack engineer`
-   Public repo
-   No  `README`,  `.gitignore`, or license

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/2340a2d0f7c74b5dd6f8fc2aa58f94d13ea2c775.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220320%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220320T185145Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5aafb6bc43e01fac468b4a64d6fee4916e0304b0ff43e3b492731ae9276cd473)

#### Step 4 - Open the sandbox

On the intranet, just under the task, click on the button  ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/9db8eece71455dfddf4b7d8585c037c535f1d18d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220320%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220320T185145Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=734fa9b0ac336f3e87234591b61691c9459a550f1e65b5fe2b81290b010574fc)  and  `run`  to start the machine.

Once the container is started, click on  ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/be9d1fbfb3d97e6924a4d2af7df9290ad7ae77df.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220320%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220320T185145Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a31db53f29f8f9502c446f1c78c4c3e619fc5f0766fa77b363fcd32aa69046ad)  to open a shell where you can start work from.

#### Step 5 - Clone your repository

On the webterm of the sandbox, do the following:

-   Clone your repository

```
root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git                  
Cloning into 'alx-pre_course'...
warning: You appear to have cloned an empty repository.       

```

**Replace {YOUR_PERSONAL_TOKEN} with your token from step 1**

**Replace {YOUR_USERNAME} with your username from step 0 and 1**

#### Step 6 - Create the README.md and push the modifications

-   Navigate to this new directory.  [Tips](https://alx-intranet.hbtn.io/rltoken/_hv6gkuqwPeF_nefdPygcw "Tips")

```
root@896cf839cf9a:/# cd alx-pre_course/
root@896cf839cf9a:/alx-pre_course#

```

-   Create the file  `README.md`  with the content  `My first readme`.  [Tips](https://alx-intranet.hbtn.io/rltoken/0U_R5Z7fbzEFJ1hXKx4fdQ "Tips")

```
root@896cf839cf9a:/alx-pre_course# echo 'My first readme' > README.md                                                                 
root@896cf839cf9a:/alx-pre_course# cat README.md                                                                                      
My first readme                                                                                                                       

```

-   Update your git identity

```
root@896cf839cf9a:/alx-pre_course# git config --global user.email "you@example.com"
root@896cf839cf9a:/alx-pre_course# git config --global user.name "Your Name"

```

-   Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin

```
root@896cf839cf9a:/alx-pre_course# git add .
root@896cf839cf9a:/alx-pre_course# git commit -m 'My first commit'
[master (root-commit) 98eef93] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
root@896cf839cf9a:/alx-pre_course# git push                                                                                           
Enumerating objects: 3, done.                                                                                                         
Counting objects: 100% (3/3), done.                                                                                                   
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.                                                                          
Total 3 (delta 0), reused 0 (delta 0)                                                                                                 
To https://github.com/{YOUR_USERNAME}/alx-pre_course.git                                                                                       
 * [new branch]      master -> master              

```

Good job!

You pushed your first file in your  **first repository**  of the  **first task**  of your  **first ALX School project**.

You can now check your repository on GitHub to see if everything is good.

**Repo:**

-   GitHub repository:  `alx-pre_course`
-   File:  `README.md`

### 1. Repo-session

Create a new directory called  `0x01-git`  in your  `alx-pre_course`  repo.

Make sure you include a non empty  `README.md`  in your directory:

-   at the root of your repository  `alx-pre_course`
-   AND in the directory  `0x01-git`

And important part:  **Make sure your commit and push your code to Github - otherwise the Checker will always fail.**

**Repo:**

-   GitHub repository:  `alx-pre_course`

### 2. Coding fury road

For the moment we have an empty project directory containing only a  `README.md`. It’s time to code!

-   Inside  `0x01-git`:
    
    -   Create these directories at the root of your project:  `bash`,  `c`,  `js`
    -   Create these empty files:
    -   `c/c_is_fun.c`
    -   `js/main.js`
    -   `js/index.js`
    -   Create a file  `bash/alx`  with these two lines inside:  `#!/bin/bash`  and  `echo "ALX"`
    -   Create a file  `bash/school`  with these two lines inside:  `#!/bin/bash`  and  `echo "School"`
    -   Add all these new files to git
    -   Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

**Repo:**

-   GitHub repository:  `alx-pre_course`
-   Directory:  `0x01-git`
-   File:  `bash/alx, bash/school, c/c_is_fun.c, js/main.js, js/index.js`


### 3. Collaboration is the base of a company


A branch is like a copy of your project. It’s used mainly for:

-   adding a feature in development
-   collaborating on the same project with other developers
-   not breaking your entire repository
-   not upsetting your co-workers

The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

For this project, create a branch  `update_script`  and in this branch:

-   Create an empty file named  `bash/98`
-   Update  `bash/alx`  by replacing  `echo "ALX"`  with  `echo "ALX School"`
-   Update  `bash/school`  by replacing  `echo "School"`  with  `echo "The school is open!"`
-   Add and commit these changes (message: “My personal work”)
-   Push this new branch  [Tips](https://alx-intranet.hbtn.io/rltoken/npNmc0VkyeeqpZESyP0FWA "Tips")

Perfect! You did an amazing update in your project and it’s isolated correctly from the  **main**  branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

-   Change branch to  `main`
-   Update the file  `bash/alx`  by replacing  `echo "ALX"`  with  `echo "ALX School is so cool!"`
-   Delete the directory  `js`
-   Commit your changes (message: “Hot fix”) and push to the origin

Ouf, hot fix is done!

**Repo:**

-   GitHub repository:  `alx-pre_course`
-   Directory:  `0x01-git`
-   File:  `bash/alx, bash/school, bash/98`

### 4. Collaboration: be up to date

Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.

For this task –  **and only for this task**  – please update your file  `README.md`  in the main branch from GitHub.com. It’s the  **only time**  you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:

-   Get all changes of the main branch locally (i.e. your  `README.md`  file will be updated)
-   Create a new file  `up_to_date`  at the root of your directory and in it, write the git command line used
-   Add  `up_to_date`  to git, commit (message: “How to be up to date in git”), and push to the origin

**Repo:**

-   GitHub repository:  `alx-pre_course`
-   Directory:  `0x01-git`
-   File:  `README.md, up_to_date`

### 5. HAAA what did you do???

Collaboration is cool, but not really when you update the same file at the same time…

To illustrate that, please merge the branch  `update_script`  to  `main`: “Cool, all my changes will be now part of the main branch, ready to be deployed!”

**HHHHHHHAAAAAAAA**

```
CONFLICT (content): Merge conflict in bash/alx

```

As you can see, you have conflicts between two branches on the same file.

Your goal now is to resolve conflicts by using the version of the branch  `update_script`, and push the result to the origin.

At the end, you should have all your work from the branch  `update_script`  (new file and two updated files) and all latest  `main`  commits (new files, delete folder, etc.),  _without_  conflicts.

**Repo:**

-   GitHub repository:  `alx-pre_course`
-   Directory:  `0x01-git`

### 6. Never push too much

Create a  `.gitignore`  file and define a rule to never push  `~`  files (generated by Emacs).  [Tips](https://alx-intranet.hbtn.io/rltoken/nPfu8B_aZtkiOQjSil6eiw "Tips")

**Repo:**

-   GitHub repository:  `alx-pre_course`
-   Directory:  `0x01-git`
-   File:  `.gitignore`

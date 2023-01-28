# Remote Access Tutorial 

## Step 1: Navigate to CSE15L Account 
- [Look up your course specfic account](https://sdacs.ucsd.edu/~icc/index.php)
- [Reset your password](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit)

## Step 2: Visual Studio Code
- [Download VSCODE](https://code.visualstudio.com/download)
    - Click on install button that correpsonds to your OS (mac, windows, linux) once you have navigated to the download page linked above
    - VSCODE will install and you should be able to open it when it completes
- The home screen should look like this: <br>
![vscodehomescreen](../images/vscodedownload.png)

## Step 3: Remote Connection via SSH 
- [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Open up git bash in your vscode terminal(``CTRL + ` ``)
- Recall your course specfic account name (ACCOUNT_NAME we will call it) from step 1 (looks like this: cs15lwi23zz)
- Type in `ssh ACCOUNT_NAME@ieng6.ucsd.edu`
- Enter yes if asked for continued conection confirmation
- Input the new password you created in step 1 once prompted 
- You should see this once the Secure Shell connection is complete:
![ucsdsshconnection](../images/sshconnectionsuccess.png)

## Step 4: Try Some Commands!
- Now that you're connected, lets try some `git` bash commands 
- Here is an example of commands `-pwd` and `-ls` being used: 
![examplebashcommands](../images/gitbashcommands.png)
    - As you can see, `pwd`, or "print working directory", allows you to see the file path you are in. 
        - Can be concluded that cs15lwi23aix was the final directory of the root path
    - The `ls` command "listed" the files and directories existing in the working directory. 
        - Can be concluded per15 is the only file/directory in cs15lwi23aix
- Go ahead and try some commands yourself once you are connected to the remote server!

<p style="text-align: center; font-style: italic;">You are now good to go!</p>

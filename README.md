# PLPBasicGitAssignment
PLPBasicGitAssignment CLI
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment> 
>> git init
>>
At line:1 char:1
+ cd PLPBasicGitAssignment
+ ~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\pc\One...icGitAssignment:String) [Set-Location], ItemNotFoundException
 
Reinitialized existing Git repository in C:/Users/pc/OneDrive/Desktop/PLPBasicGitAssignment/.git/
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment> git add hello.txt
>>
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment> git commit -m "Add hello.txt with a greeting"
On branch master
nothing to commit, working tree clean
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment> git remote add origin https://github.com/Jacheri254/PLPBasicGitAssignment
error: remote origin already exists.
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Jacheri254/PLPBasicGitAssignment'
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment> git add hello.txt
>> git commit -m "Add hello.txt with a greeting"
>> 
On branch master
nothing to commit, working tree clean
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment> git add hello.txt
>> git commit -m "Add hello.txt with a greeting"
>> git remote -v
>> 
nothing to commit, working tree clean
origin  https://github.com/Jacheri254/PLPBasicGitAssignment (fetch)
origin  https://github.com/Jacheri254/PLPBasicGitAssignment (push)
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment> git push origin master
>>
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 238 bytes | 119.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Jacheri254/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/Jacheri254/PLPBasicGitAssignment
 * [new branch]      master -> master
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment>
PS C:\Users\pc\OneDrive\Desktop\PLPBasicGitAssignment>

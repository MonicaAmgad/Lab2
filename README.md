 "locally"
 git branch -d <branch_name>
 "remotely"
 git push origin --delete <branch_name>
----------------------------------------------------------------------------
Annotated Tags:
Includes tagger’s name, email, date, and message.
Stored as a Git object.
Command	git tag -a <tagname> -m "message"
Lightweight Tags:
No metadata, just a reference to a commit.
Stored as a reference.
git tag <tagname>
-----------------------------------------------------------------------------
Rebase is used to have :
-Clean History:
linear commit history by integrating changes without merge commits.
-Feature Branch Updates:
Rebase a feature branch onto the latest main branch to incorporate the latest changes.
-----------------------------------------------------------------------------
To list all tags:
 git tag 
 ---------------------------------------------------------------------------- 
 To delete remote tag:
 git push origin --delete v1.0
 To delete local tags:
 git tag -d v1.0
  ----------------------------------------------------------------------------
![Image icon](https://raw.githubusercontent.com/username/repository/main/path/to/ph.png)

  ----------------------------------------------------------------------------



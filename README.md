# Lab2

### remove branches
##### remove branches locally
``` git branch -d branch_name```

##### remove brances remote
```git push origin :branch_name```

--------------------------------
### **Tags**
1.*lighweight tags*
 - for quick, local references (e.g., marking a commit for testing).
 - No tagger info (name, email, date).
 - No message (description).

2.*Annotated Tags*
 - for releases  where metadata matter(e.g., v1.0.0)
 - Tagger name & email and Date of tagging
 - A Description message
--------------------------------------
## when to use **Rebase**
 when merge branches , multi commits on old brances be unnecessary and can be collectd to one commit on top of the main branch
> *result* liner clean history without extra merge commits 
>> *Avoid* rebase in public / shared (remote) branches that cause confilcts 
```git checkout feature-branch
git rebase main```
------------------------------------------
### list tags
1.to list all tags 
``` git tag
```
2.list tags with annotations
```git tag -n
```





 

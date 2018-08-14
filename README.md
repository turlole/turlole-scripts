# turlole-scripts
* * *

scripts and other common commands

## First commit

```
mkdir foo-repo
cd foo-repo/
echo "# Title" > README.md
```

```
git init                                                                                                 
```

```
Initialized empty Git repository in C:/__github/github_com/turlole/foo-repo/.git/                    
```

```
git add README.md
```

```
git commit -m "first commit"                                                                             
[master (root-commit) 0f041f4] first commit                                                                 
 1 file changed, 4 insertions(+)                                                                            
 create mode 100644 README.md                                                                               
```

```
git remote add origin https://github.com/turlole/foo-repo.git                                     
```

```
git push origin master                                                                                   
```

```
Counting objects: 3, done.                                                                                  
Delta compression using up to 4 threads.                                                                    
Compressing objects: 100% (2/2), done.                                                                      
Writing objects: 100% (3/3), 267 bytes | 89.00 KiB/s, done.                                                 
Total 3 (delta 0), reused 0 (delta 0)                                                                       
To https://github.com/turlole/foo-repo.git                                                           
 * [new branch]      master -> master                                                                       
```

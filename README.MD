1) To check how works history cleanup, you can run:
```
git filter-repo --invert-paths --path dir3/test1.txt --force
```

`dir3, dir4, dir5` folders have been created and removed in history, each containing five files. 
You can play with any of them.

2) To rewrite 'senstive' data, you can run:
```
git filter-repo --replace-text passwords.txt
```

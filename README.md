# git-test
...

# globalno opste


```
echo pera >> README.md
git status
git add README.md
git status
git commit -m "pera"
git push origin
```

# rad na "feature" branch-u

```
git branch nova_funkcionalnost
git status
echo zika >> README.md
git status
git add README.md
git status
git commit -m "zika"
git log
```

ILI


```
git checkout -b nova_f_2
git status
echo "laza" >> README.md
git status
git add README.md
git status
git commit -m "laza"
git log
```

# merge feature branch-a u main

```
git switch main
git status # da vidis koji ti je trenutni branch
git merge nova_funkcionalnost
```

# 

>> Commands Used:
1. PART 1:
Cloning the repo to my local:
> git clone https://github.com/iAmNsengi/git/settings
> cd git
> touch test{1..4}.md
> git add test1.md && git commit -m "chore: Create initial file"
> git add test2.md && git commit -m "chore: Create another file"
> git add test3.md test4.md && git commit -m "chore: Create third and fourth files"
> git status
> git log

2. Staging the test4.md
> git add test4.md
> git commit --ammend -m "chore: Create third and fourth files"
> git log

1  node -v
    2  git --version
    3  ls
    4  cd git
    5  rm -fr ".git/rebase-merge"
    6  touch test4.md
    7  touch unwanted.txt
    8  git rebase -i HEAD~2
    9  git rebase -i HEAD~2
   10  git rebase -i --root
   11  git add unwanted.txt
   12  git commit -m 'Unwanted commit'
   13  git rebase -i HEAD~2
   14  git log
   15  git rebase -i HEAD~2
   16  git rebase -i HEAD~1
   17  git rebase -i --root
   18  git rebase -i --HEAD~3
   19  git rebase -i --root
   20  git log
   21  git rebase -i --root
   22  git branch ft/branch
   23  git branch
   24  git checkout ft/branch
   25  touch test5.md
   26  git add .
   27  git add test5.md
   28  git commit -m 'Implemented Test5'
   29  git log
   30  git checkout main
   31  git cherry-pick 6966590183325a43923838f027151dd606030fc6
   32  git log --graph
   33  git log --graph --oneline --all
   34  git reflog
   35  git branch
   36  git branch ft/new-feature
   37  git checkout ft/new-feature
   38  touch feature.txt
   39  git add feature.txt
   40  git commit -m "Implemented core functionality for new feature"
   41  git checkout man
   42  git checkout main
   43  touch readme.txt
   44  git add readme.txt
   45  git commit "Updated project readme"
   46  git push origin main
   47  git push remote origin
   48  git push
   49  git branch
   50  git checkout ft/new-feature
   51  git push origin ft/new-feature
   52  git checkout main
   53  git push origin main
   54  git pull origin main
   55  git checkout ft/new-feature
   56  git pull origin main
   57  git checkout main
   58  git pull
   59  touch readme.md
   60  git rebase -i HEAD~2
   61  git rebase -i --root
   62  git commit -m "chore: created readme.md file "
   63  git rebase -i --root
   64  git add .
   65  git commit -m "chore: created readme.md file "
   66  git rebase -i --root
   67  git push origin main
   68  git pull ft/new-feature
   69  git pull origin
   70  git fetch
   71  git rebase ft/new-feature
   72  git add .
   73  git commit -m 'fix: error in pushing, main is behind'
   74  git push origin main
   75  git push origin ft/new-feature
   76  git push
   77  git rebase ft/feature
   78  git branch
   79  git rebase ft/branch
   80  git push
   81  git push ft/branch
   82  git push origin ft/branch
   83  git push
   84  git push --help
   85  git pull
   86  git pull origin
   87  git push
   88  git pull
   89  git status
   90  git add .
   91  git commit -m 'deleted readme.md'
   92  git push
   93  git status
   94  git fetch main
   95  git fetch origin
   96  git status
   97  git pull
   98  git push
   99  git status
  100  git push --force
  101  git branch -d ft/new-feature
  102  git branch -D ft/new-feature
  103  git history
  104  history


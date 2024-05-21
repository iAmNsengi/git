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

3. Editing commit history
> git rebase -i HEAD~2
> reword 2204c12 Create Third and Fouth Files
> pick 5ed612b chore: Create initial file

4. 


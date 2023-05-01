# curso_ebac
Comandos Usados:
PS C:\curso_ebac> git init
Initialized empty Git repository in C:/curso_ebac/.git/
PS C:\curso_ebac> echo "nome" >nome.txt
PS C:\curso_ebac> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        nome.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\curso_ebac> git add .
PS C:\curso_ebac> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   nome.txt

PS C:\curso_ebac> git commit -m "initial commit"
[master (root-commit) 5cdd148] initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 nome.txt
PS C:\curso_ebac> git branch -M exercicio_git
PS C:\curso_ebac> git status
On branch exercicio_git
nothing to commit, working tree clean
PS C:\curso_ebac> git remote add origin https://github.com/DiasdeCarrera/curso_ebac.git
PS C:\curso_ebac> git push -u origin exercicio_git

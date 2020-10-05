➜  ~ git clone /path/to/repository
fatal: repository '/path/to/repository' does not exist
➜  ~ git clone /path/to/repository
fatal: repository '/path/to/repository' does not exist
➜  ~ git clone https://github.com/lrojash/terminal-git-practice.git
Cloning into 'terminal-git-practice'...
remote: Enumerating objects: 35, done.
remote: Counting objects: 100% (35/35), done.
remote: Compressing objects: 100% (17/17), done.
remote: Total 35 (delta 9), reused 35 (delta 9), pack-reused 0
Unpacking objects: 100% (35/35), 4.98 KiB | 300.00 KiB/s, done.
➜  ~ cd terminal-git-practice
➜  terminal-git-practice git:(main) ls
README.md info.yml
➜  terminal-git-practice git:(main) git checkout -b develop
Switched to a new branch 'develop'
➜  terminal-git-practice git:(develop) git checkout -b solutions
Switched to a new branch 'solutions'
➜  terminal-git-practice git:(solutions) touch solutions.md
➜  terminal-git-practice git:(solutions) ✗ git add solutions.md
➜  terminal-git-practice git:(solutions) ✗ git commit -m"add solution file to save my commands"
[solutions 2473a5f] add solution file to save my commands
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 solutions.md
➜  terminal-git-practice git:(solutions) code solutions.md
➜  terminal-git-practice git:(solutions) ~/.bash_history
zsh: permission denied: /Users/luis/.bash_history
➜  terminal-git-practice git:(solutions) 
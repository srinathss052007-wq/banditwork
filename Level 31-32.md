Level 31-32

The password is stored in a file that Git is configured to ignore. By force-adding the ignored file, its contents can be accessed. This exposes the next password. commands used: git clone ssh://bandit31-git@localhost/home/bandit31-git/repo cd repo cat README.md git add -f key.txt cat key.txt


![level 31-level 32](https://github.com/user-attachments/assets/23b66ee2-7c32-48ae-b558-04f5101efda0)

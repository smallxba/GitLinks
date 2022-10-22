# GitLinks
连接GitHub与Gitee



# 从下午4点忙到凌晨4点的环境配置

ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$
git config --global --unset user.name "ShengYan"


ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$ ^[[200~
bash: $'\E[200~': command not found

ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$ git config --global --unset user.email "2469216314@qq.com"

ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$ ssh-keygen -t rsa -C "2469216314@qq.com" -f "id_rsa_github"
Generating public/private rsa key pair.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in id_rsa_github
Your public key has been saved in id_rsa_github.pub
The key fingerprint is:
SHA256:fKMiZeKsHzsX1slmfocN1YQ81oQw54m3MtQ2oF/tc8I 2469216314@qq.com
The key's randomart image is:
+---[RSA 3072]----+
|          +o.=.  |
|         . B*oo  |
|        . o.O+.  |
|       . o +.=.  |
|    . ooS.*.. E .|
|   o +o *o.+   + |
|    =..=.  +     |
|   ..+... o o    |
|  ..oo   . .     |
+----[SHA256]-----+

ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$ ssh-keygen -t rsa -C "2469216314@qq.com" -f "id_rsa_gitee"
Generating public/private rsa key pair.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in id_rsa_gitee
Your public key has been saved in id_rsa_gitee.pub
The key fingerprint is:
SHA256:vrO+oIePxj3HEpXFBHAubueGoPkzIPupvb9GAsk5Vik 2469216314@qq.com
The key's randomart image is:
+---[RSA 3072]----+
|    . ..o+.      |
| E o   o  o      |
|..+   . .o       |
|o=   . .o        |
|... . o.S        |
|. oo.o.=         |
| oo= ooo+        |
|.. oBo=o+.       |
|.o==**.==+       |
+----[SHA256]-----+

ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$ ssh -T git@github.com
The authenticity of host 'github.com (20.205.243.166)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).

ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$ ssh -T git@github.com
git@github.com: Permission denied (publickey).

ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$ ssh -T git@github.com
Hi smallxba! You've successfully authenticated, but GitHub does not provide shell access.

ShengYan@LAPTOP-L1MNI7CF MINGW64 ~/.ssh
$

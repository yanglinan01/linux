# ssh免密码登陆
ssh免密码和ssh-copy-id命令
Linux系统配置免密码的方式：

1：ssh-keygen -t rsa

生成密钥

2：ssh-copy-id -i ~/.ssh/id_rsa.pub 127.0.0.1

把本机的公钥追到jifeng02的 .ssh/authorized_keys 里

### 1、设置Git的user name和email

git config --global user.name "tom"

git config --global user.email "tom@gmail.com"

### 2、生成密钥(linux和windows一样)

ssh-keygen -t rsa -C "tom@gmail.com"

### 3、在~/.ssh文件目录下查看公钥

cat id_rsa.pub

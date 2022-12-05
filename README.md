# Lab-7
ssh -D8888 -p 3922 root@yoko.ukrtux.com

ssh-keygen -t rsa - ми додаємо new key

ssh-add /home/mykhailo/.ssh/id_rsa

ssh-copy-id -i /home/mykhailo/.ssh/id_rsa.pub -p3922 root@yoko.ukrtux.com 

ssh -p3922 root@yoko.ukrtux.com

Основні команди для перевірки:

ssh - D8844 -p3922 root@yoko.ukrtux.com

python3 -m http.server 8855

ssh -R 13922:localhost:8855 -p3922 root@yoko.ukrtux.com

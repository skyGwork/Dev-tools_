> C:\Users\skyde>ssh-keygen -t rsa -C "main@gmail.com"

    Generating public/private rsa key pair.
    Enter file in which to save the key (C:\Users\skyde/.ssh/id_rsa):
    Created directory 'C:\Users\skyde/.ssh'.
    Enter passphrase (empty for no passphrase):
    Enter same passphrase again:
    
    Your identification has been saved in C:\Users\skyde/.ssh/id_rsa.

- C:\Users\skyde\.ssh>ssh-add .\id_rsa
  Identity added: .\id_rsa (main@gmail.com)

> C:\Users\skyde>ssh-keygen -t rsa -C "sub1@gmail.com"

    Generating public/private rsa key pair.
    Enter file in which to save the key (C:\Users\skyde/.ssh/id_rsa): C:\Users\skyde/.ssh/id_rsa_sub1
    Enter passphrase (empty for no passphrase):
    Enter same passphrase again:

    Your identification has been saved in C:\Users\skyde/.ssh/id_rsa_sub1.

- C:\Users\skyde\.ssh>ssh-add .\id_rsa_sub1
  Identity added: .\id_rsa_skytech (sub1@gmail.com)

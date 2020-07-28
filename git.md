# Git
-----

## Configuration
### Git config for multiple users

- Git config file
```
[user]
          name = Foxy-z
          username = foxy
          email = thefoxy41@gmail.com
          signingkey = 98E9E826929ECF1C
```
```
[user]
          name = Loïc Frémaux
          username = loicfmx
          email = loic.fremaux1@gmail.com
          signingkey = 0C3F9C8353CF19B8
```

- SSH config
```
Host github.com-foxy-z
        HostName github.com
        User git
        IdentityFile ~/.ssh/id_rsa_thefoxy41
Host github.com-loicfmx
        HostName github.com
        User git
        IdentityFile ~/.ssh/id_rsa_loicfmx
IdentityFile /home/loic/.ssh/id_rsa_thefoxy41
```

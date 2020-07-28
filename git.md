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
[remote "origin"]
        url = git@github.com-foxy-z:loic-fremaux/knowledge.git
        fetch = +refs/heads/*:refs/remotes/origin/*
```
```
[user]
        name = Loïc Frémaux
        username = loicfmx
        email = loic.fremaux1@gmail.com
        signingkey = 0C3F9C8353CF19B8
[remote "origin"]
        url = git@github.com-loicfmx:loic-fremaux/knowledge.git
        fetch = +refs/heads/*:refs/remotes/origin/*
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

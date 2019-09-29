The website is generated from Jekyll templates, the source code can be found in the develop branch:
https://github.com/katieskleandev/katieskleandev.github.io/tree/develop

The generated website is hosted from github pages:
https://github.com/katieskleandev/katieskleandev.github.io/tree/master

## How to commit to github:
- Make sure the ssh key is added to github and the key is located for example in: '~/.ssh/katiesklean.pub' (and '~/.ssh/katiesklean' for the private key).
- Make sure the ssh key is added to ssh-agent: ssh-add ~/.ssh/katiesklean.
- Have a record in the ssh config for this key:

> Host katieskleandev
>         HostName github.com
>         User git
>         IdentityFile ~/.ssh/katiesklean
>         IdentitiesOnly yes

- Make sure the .git/config has the remote as:
> [remote "origin"]
>         url = git@katieskleandev:katieskleandev/katieskleandev.github.io.git


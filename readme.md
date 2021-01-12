# heroku-install-private-ssh-key buildpack

Copies contents of a private ssh key from SSH_KEY environment variable to ~/.ssh/id_rsa

Example usage:

```bash
heroku buildpacks:add https://github.com/JaakkoRoponen/heroku-install-private-ssh-key

git push heroku master
```

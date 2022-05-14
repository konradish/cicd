# CICD environment
- [ ] Connect to Portainer on port 9000 and set up username/password
- [ ] Log in to Gitlab, set admin password
- [ ] Add user account to GitLab, make admin
- [ ] In Gitlab, open settings CICD section and follow instructions to register Gitlab Runner
```sh
docker-compose exec gitlab-runner gitlab-runner register
# Choose shell
```


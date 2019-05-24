# 不用打开浏览器，直接在cmd用github api创建repo

```bash
curl -u 'cuilei5205189' https://api.github.com/user/repos -d '{"name":"github-cmd-newrepo"}'
git remote add origin https://github.com/cuilei5205189/github-cmd-newrepo.git
git push -u origin master
```
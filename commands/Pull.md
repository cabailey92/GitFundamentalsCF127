# git pull

Similar to a [git push](./PUSH.md), a `git pull` will interact with a remote repository. Only this time it will **push** the changes it does not have from the remote down to the local repository.

This mean any commit made that are on the remote repository wil pulled downa nd added to the local repository.

This can be done by adding the remote name branch name:
```
git pull origin main
```

If there is any upstream connection established, you can use `git pull` without specifying a remote or branch.

## Resources

- [Git Pull Documentation](https://git-scm.com/docs/git-pull)

---

[Back at home](../README.md)
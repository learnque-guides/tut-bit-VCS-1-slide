# Configuration

* *git init* initializes local repository in current directory. The operation is performed only once - when we want to create new project.

```bash
git init
```

* *git config*
Environment configuration, including username and email address setting, that enables the authorization on the remote repository. The operation can be performed repeatedly, depending on the need.

```bash
git config --global user.name "<full name>"
git config --global user.email "<email address>"
```
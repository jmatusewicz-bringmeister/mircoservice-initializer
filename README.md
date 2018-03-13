# mircoservice-initializer

Usage:

Create new git repository:

```bash
mkdir my-new-service && cd my-new-service && git init
echo "Init" > README.md && git add README.md && git commit -m "Init"

git remote add origin git@bitbucket.org:bringmeister/my-new-service.git
git push -u origin master

```

Initialize project structure
```$bash
bash <(curl -s https://raw.githubusercontent.com/jmatusewicz-bringmeister/mircoservice-initializer/master/init-repo) git@bitbucket.org:bringmeister/con-starter.git my-new-service
```

Review created branch and merge into master
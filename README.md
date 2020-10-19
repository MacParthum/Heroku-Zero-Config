https://git.heroku.com/heroku-zero-config.gi

https://blog.heroku.com/deploying-react-with-zero-configuration

https://devcenter.heroku.com/articles/renaming-apps#updating-git-remotes

* `npm install -g create-react-app`
* `create-react-app my-app`
* `cd my-app`
* `git init`
* `heroku create -b https://github.com/mars/create-react-app-buildpack.git`
* `git add .`
* `git commit -m "react-create-app on Heroku"`
* `git push heroku master`
* `heroku open`

Create empty github repo and follow instructions to **push existing repository from the command line.**

* `git remote add origin git@github.com:MacParthum/Heroku-Zero-Config.git`
* `git branch -M main`
* `git push -u origin main`
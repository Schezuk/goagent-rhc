Runtime Configuration
======================
This will easily create an Openshift diy-0.1 app with Python 2.7.6

````shell
rhc create-app -a goagent -t diy-0.1
cd goagent
git remote add upstream -m master https://github.com/wssbwssbwssb/goagent-rhc.git
git pull -s recursive -X theirs upstream master
git push
read
````

And watch the scripts do their thing.

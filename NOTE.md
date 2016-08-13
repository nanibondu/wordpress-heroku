#Heroku is awesome and they're nice enough to give you the ability to host your websites there for free. 

Things you will need before getting started: 
1) GIT installed on your PC (https://git-scm.com)
2) An account with Heroku
3) Heroku toolbelt (https://toolbelt.heroku.com)

**Instructions:**

1) Open console. 

2) Run: git clone git://github.com/mhoofman/wordpress-heroku.git 

3) Run: cd wordpress-heroku

4) Run: heroku create YOUR_APP_NAME [optional]

5) Run: heroku addons:create heroku-postgresql

6) Run: heroku pg:promote HEROKU_POSTGRESQL_INSTANCE (where HEROKU_POSTGRESQL_INSTANCE) is the result of the create code you ran before.

7) Run: git add .

8) Run: git push heroku master

9) Wait. 

10) Navigate to website. 

11) Go through instructions. 

12) Done.

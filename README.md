
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Welcome to your Rails project on Cloud9 IDE!

To get started, just do the following:

1. Run the project with the "Run Project" button in the menu bar on top of the IDE.
2. Preview your new app by clicking on the URL that appears in the Run panel below (https://ksl-spree-kslagdive.c9users.io/).

Happy coding!
The Cloud9 IDE team


## Support & Documentation

Visit http://docs.c9.io for support, or to learn more about using Cloud9 IDE. 
To watch some training videos, visit http://www.youtube.com/user/c9ide


https://github.com/spree/spree
http://guides.spreecommerce.org/developer/heroku.html


bundle clean --force

heroku run rake db:migrate
seed database-->

load sample-->

heroku pg:psql
heroku pg:psql --app ksl-spree DATABASE

\? - psql help

Heroku Postgress Reset -

1. heroku pg:reset DATABASE
2. heroku run rake db:migrate
3. heroku run rake db:seed
4. 


clean c9 workspace - 
du-c9 | sort -h
rm -rf /home/ubuntu/.local/share/heroku & Gems

rake -T - lists rake tasks